# beatbox
Using these scripts you can create jobs in rundeck, to utilize a raspberry pi as a digital signage system.

The concept is that you can manage multiple raspberry pi's, so the media is stored at a central location, which can be accessed by all the pi's. In this case the central location is an ftp server, which the pi's access using lftp, and mirror whatever media is on the ftp server. (video, audio, images). The scripts can also handle showing a website, and download or stream a youtube video.

There's also a script that prepares the pi, instals all dependencies, and configures it to boot to a blank screen. It also displays a logo, when the screen is not used for showing other media.
