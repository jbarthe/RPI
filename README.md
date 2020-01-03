# RPI
wiki for RaspberryPi


## Raspbian install

Download Raspbian latest release on : https://www.raspberrypi.org/downloads/raspbian/

Format SD card, and flash it with Etcher (https://www.balena.io/etcher/) 

Active SSH: add a file named ssh (without extension) in the boot partition.

To use z-wave on rpi3, disable bluetooth by adding this line in /boot/config.txt :
`dtoverlay=pi3-disable-bt`

To improve the available current over USB, in /boot/config.txt: `max_usb_current=1`



