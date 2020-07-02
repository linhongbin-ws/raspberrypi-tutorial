# How to Setup a new raspberry pi

## Software Required:

1. Balena Etcher
2. Putty

 

## Setup Raspberry pi 

1. Download Raspbian from [link](https://www.raspberrypi.org/downloads/raspberry-pi-os/). Normally choose 
`Raspberry Pi OS (32-bit) with desktop and recommended software`.

2. Use `Balena Etcher` to write image of Raspbian system which is downloaded from official website, following these step: a) choose download image file. b) choose your writing destination (your SD card). c) Write it.

3.      
Creat a new blank file named as 'ssh' without extension in the drive location of SD card.

## Setup with Wifi connection

1. Insert SD card on the Raspberry Pi board. Plug in the power cable. Connect ethernet cable between raspberry pi and your host PC. 

2. Open putty on host computer, type IP address `raspberrypi.local` to connect.

3. It will open a terminal. Type Login: `pi`  and Password: `raspberry`.

4. Once you access the remote terminal, type `sudo raspi-config`, then in the open GUI, choose `NETWORK OPTION` -> Wireless LAN -> enter SSID and password.

5. type `sudo ifconfig` to get your wifi IP address. Something like `192.168.0.197`.

6. Now you can use `putty` on your host computer to access the raspberry pi



