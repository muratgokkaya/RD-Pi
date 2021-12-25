# RD-Pi
Thin Client for Microsoft Remote Desktop using Raspberry Pi
![alt text](https://github.com/muratgokkaya/RD-Pi/blob/main/splash.png?raw=true)


## Features

![Screenshots](https://github.com/muratgokkaya/RD-Pi/blob/main/screenshot.jpg)

```
▲ Plug and play, affordable,        ▲ Boots directly into a RDP       ▲ WiFi & other system config        ▲ FREE to use as long as
     no config required                        session                        is just simple                        you want
```


## Prerequisites:
* Raspberry PI (Raspberry Pi 4 2GB veya Raspberry Pi 3b+)
* Raspberry PI Adaptor
* MicroSD Card (4 GB Minimum)
* HDMI Cable
* Network Cable
* Monitor
* Keyboard
* Mouse

## Download RD-Pi v1.0
https://drive.google.com/file/d/1vP9zPTANlXPPtjUTvp6vvLuMY10CH_Gk/view?usp=sharing

## Installation
Simply burn it to SD Card or USB Memory using Raspberry Pi Imager

## Details
There are 2 files in boot partition should be configured ;
* rd-pi_config.ini for RDP Server IP
* dhcpcd.conf if you wan to use your Raspberry Pi with static IP

If you want to remote login via SSH there is a user for it ;

`username : admin`
`password : 123456`


## RDP Wrapper Library v1.6.2.1 for Multi Session Windows

ℹ️ It is an external link to another github page, use it on your own risk.

https://github.com/DrDrrae/rdpwrap/releases/tag/v1.6.2.1


