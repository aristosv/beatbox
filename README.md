#beatbox
Using these scripts you can create jobs in [rundeck](https://github.com/rundeck/rundeck), to utilize a raspberry pi as a digital signage system. The scripts can handle playing:

- local video or audio
- stream or download from youtube
- show a website or a slideshow. 

There is also a script that prepares the pi, installs all dependencies, and configures a few parameters more suitable for a signage system.

- admin_prepare -> prepare the pi
- signage_audio -> play local audio files
- signage_browser -> show a website
- signage_images -> play slideshow
- signage_stop -> stop signage services
- signage_stream -> stream youtube video
- signage_video -> play local video files
- signage_youtube -> download and play youtube video

Keep in mind I'm working on this for the learning experience. There's no warranty whatsoever that these are robust enough to be used in a production environment.
