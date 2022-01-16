# rpi-bird-box-cam

🐦📷 
My variant of a bird box camera

Abstract
--------


References
----------

Hardware
--------
* RaspberryPi Zero W
* NoIR Camera
* IR Led
* ...

Setup rpi
---------
* Write SD card using Rasberry Pi Imager. 
    REMARK: Use Buster version, since camera software is changed in Bullseye and motion support is currently unknown.  
    `Ctrl + Shift + x` to setup:
    * Set hostname: `birdboxcam` (or whatever you prefer)
    * Enable SSH, and set a strong password for pi user. 
    * Configure WiFi
* Mount SD card and fire up the rpi
* `sudo apt update | sudo apt upgrade`
* Enable camera interface
    * `sudo raspi-config`
    * Give gpu more memory? 256mb?

* Install motion + motionEye: https://github.com/ccrisan/motioneye/wiki/Install-On-Raspbian