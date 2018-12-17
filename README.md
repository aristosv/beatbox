# beatbox
Using these scripts you can create jobs in [rundeck](https://github.com/rundeck/rundeck), to utilize a raspberry pi as a digital signage system. They have been tested on Raspbian Stretch Lite released on 2018-11-13.

It's as simple as adding a step and copying the script.
![alt text](https://github.com/aristosv/beatbox/blob/master/example1.png)

Or adding a step and linking it to the script.
![alt text](https://github.com/aristosv/beatbox/blob/master/example2.png)

The scripts can:
- play local video or audio
- stream or download from youtube
- show a website or a slideshow. 

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

Keep in mind I'm working on this for the learning experience. There's no warranty whatsoever that these are robust enough to be used in a production environment.
