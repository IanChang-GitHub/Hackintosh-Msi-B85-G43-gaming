# Hackintosh-Msi-B85-G43-gaming
![GitHub release](https://img.shields.io/github/v/release/ianchang-github/Hackintosh-Msi-B85-G43-gaming)

![image](https://github.com/IanChang-GitHub/Hackintosh-Msi-B85-G43-gaming/blob/master/Picture/Big%20Sur%2011.2.2.png)

## Computer Device

| Devie     | Information        |
| -------- | ------------------------------|
| CPU | Intel Xeon E3-1230 V3 3.30GHz    |
| Motherboard | Msi B85-G43 Gaming         |
| Ram   |  Kingston DDR3 1600Hz 4G* 4    |
| Disk  | Seagate BarraCuda 250G    |
| Display Card   | Msi Radeon RX580 ARMOR 8G     |

## Disable CFG Lock
Before intalling MacOS, you need to disable Cfg lock.
If you don't do this step and use my package.
It would be frozen when installing.

![image](https://github.com/IanChang-GitHub/Hackintosh-Msi-B85-G43-gaming/blob/master/Picture/B85-G43%20CFG.JPG)

- Select the Modified GRUB Shell on Opencore boot menu.

- Key "setup_var 0x67 0x0" and press enter.

## Issue unsolve
1. Computer sleeping capability may be turned off, it would wake up unsuccessfully.

## Update Log

2021/06/24 Update MacOS to Big Sur 11.2.2 and Opencore to 0.7.1.
