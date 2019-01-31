# Hackintosh running MacOS Mojave 10.14.3
ASRock z390 Phantom Gaming ITX/AC Hackintosh

 ![image](https://raw.githubusercontent.com/befuture/EFI-ASRock-Z390-Phantom-Gaming/master/images-folder/itx-systeminfo.png)

## Introduction

### Hardware

* [Intel Core i5-8500](https://item.jd.com/6405178.html)
* [ASRock Z390 Phantom Gaming-ITX/AC](https://item.jd.com/100000544940.html)
* [Kingston Fury DDR4 2400 16GB](https://item.jd.com/2551276.html)
* [HP EX900 500G M.2 NVMe](https://item.jd.com/6245707.html)
* [Broadcom BCM94352Z](http://www.taobao.com/)

![image](https://raw.githubusercontent.com/befuture/EFI-ASRock-Z390-Phantom-Gaming/master/images-folder/itx-build.png)
![image](https://raw.githubusercontent.com/befuture/EFI-ASRock-Z390-Phantom-Gaming/master/images-folder/full-build.png)

### Work

* IGPU with hardware acceleration(4k resolution)
* Audio
* Ethernet
* Wi-Fi / Bluetooth / Airdrop
* Sleep and Wakeup

### Doesn't work

* Thunderbolt
* Type-C

## Installation

### Motherboard

Flash [BIOS 1.50](https://www.asrock.com/mb/Intel/Z390%20Phantom%20Gaming-ITXac/index.asp#BIOS)

BIOS Settings:

* Advanced > Chipset Configuration -> VT-d -> Disabled
* Advanced > USB Configuration > XHCI Hand-off -> Enabled

### USB mapping

This EFI has a [custom DSDT by bydavy](https://github.com/bydavy/EFI-ASRock-Z390-Phantom-Gaming-data) to map USB ports used.

### Bluetooth & Wi-Fi
![image](https://raw.githubusercontent.com/befuture/EFI-ASRock-Z390-Phantom-Gaming/master/images-folder/itx-bluetooth.png)
![image](https://raw.githubusercontent.com/befuture/EFI-ASRock-Z390-Phantom-Gaming/master/images-folder/itx-wifi.png)