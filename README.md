# beatbox
Using these scripts you can create jobs in [rundeck](https://github.com/rundeck/rundeck), to utilize a raspberry pi as a digital signage system. They have been tested on Raspbian Stretch Lite released on 2018-11-13.

It's as simple as adding a step and copying the script.
![alt text](https://github.com/aristosv/beatbox/blob/master/example1.png)

Or adding a step and linking it to the script.
![alt text](https://github.com/aristosv/beatbox/blob/master/example2.png)

For example this is how I set up a raspberry pi as a digital signage system. Step 7 basically configures the variables in the scripts that were created on the pi during the previous steps. Step 8 copies an image to be used as a logo on the framebuffer.
![alt text](https://github.com/aristosv/beatbox/blob/master/example3.png)

When this pi powers up for the first time, it will expand / to utilize the whole microSD, connect to an ssh server to create a reverse tunnel, and show a logo on it's screen. It will then be a matter of running any of the signage_* scripts to enable any signage feature you need.

If you need help shrinking your SD card, check [this out](https://github.com/aristosv/sdshrink)

The scripts can:
- play local video or audio
- stream or download from youtube
- show a website or a slideshow

There is also a script that prepares the pi. It installs all dependencies, and configures a few parameters more suitable for a signage system.

- admin_filesystem -> expand filesystem on first boot
- admin_monitor -> resource monitor
- admin_prepare -> prepare the pi
- admin_report -> generate & email report on boot
- admin_tunnel -> create reverse ssh tunnel
- signage_audio -> play local audio files
- signage_browser -> show a website
- signage_images -> play slideshow
- signage_logo -> show framebuffer logo
- signage_stop -> stop signage services
- signage_stream -> stream youtube video
- signage_video -> play local video files
- signage_youtube -> download & play youtube video

Keep in mind I'm working on this for the learning experience. There are no warranties whatsoever.
