# RaspNas
RaspNas OS Collect and Made by Wang, can be burned and run on Raspberry Pi 2B+, 3B+, 4B and OrangePi

### Make Synology-like but more portable NAS with Raspberry Pi, Orange Pi or etc.
The Raspberry Pi is a low-power consumption device that is naturally suitable as the main control board of a NAS. If it has a GPU, then services based on vision processing algorithms will be easier to set up. Today's tutorial I will show you how to build a Raspberry Pi NAS using my designation of RaspNasPCB, which is easier and more succinct than quad sata hat. A baffle of GOT added only for decoration. ^-^
![Basic](https://github.com/Torah/RaspNas-from-Wang/blob/main/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20221129185520.jpg "basic setup")

## Materials
Here is the list of required components and tools. The list is simple, and all you need is
- Raspberry pie, orange pie, or others
- the RaspNas PCB from me
- 2.5" HDD or SSD
- DC power supply
- a TF card within which the RaspNas image OS system that I organized has burned

## Protocols
- First of all, you need to get the RaspNas PCB that I designed, which currently has 4 x SATA hard disk ports and 4 USB ports. I already plan to draw schematics for RaspNas PCBs with more SATA interfaces.
- Second, you need to download the RaspNas OS image  I compiled and burn it into your TF card. Currently supports Raspberry Pi 3B+ and 4B, and some friends have tested Raspberry Pi 2B+ to work. Then plug in the Raspberry Pi and connect with the RaspNas PCB, network cable,  a small silent fan if you wish, and the DC power supply. You can see that the Raspberry Pi NAS is already available.
- Third, open the IP:5000 to access the desktop of the Raspberry Pi NAS, double-click the second icon to open Openmediavault, format your SSD on it and add volumes, you can store files on your disk now.
Double-click the third icon to open portainer, you can customize various services with docker. For a personal office environment like my usual use, see the videos below.

## Enjoy yourself
![Basic](https://github.com/Torah/RaspNas-from-Wang/blob/main/basic.gif "basic setup")
![3DView](https://github.com/Torah/RaspNas-from-Wang/blob/main/3D%20Viewer.gif "thingiverse")
![Games](https://github.com/Torah/RaspNas-from-Wang/blob/main/Game.gif "basic setup")
[![A Video]({https://github.com/Torah/RaspNas-from-Wang/blob/main/Game.gif})]({https://github.com/Torah/RaspNas-from-Wang/blob/main/Game.mp4} "Games")

## Other boards may support
We list as much boards as possible which may Compatible with this RaspNas OS Image. It means you can reuse the boards you already have but in idle. Join us with Wechat
![WeChat](https://github.com/Torah/RaspNas-from-Wang/blob/main/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20221129185331.jpg "WeChat")
