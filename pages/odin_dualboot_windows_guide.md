# Windows Dual Boot Installation

## ⚠️ Warning ⚠️
This is **NOT** an official Windows port made by AYN. AYN will **NOT** provide support for this operating system and installing this may in fact VOID your warranty.

This is a community effort project, and thus we cannot guarantee no issues when attempting to install this port on your Odin.

Furthermore, this installation may brick your device. Do so at your own risk! We take no responsibility for hardbricked devices!

This will reset your device! Make sure to backup all files and configurations that you want to save!

It will also divide your available storage in half between the two operating systems. If you have a 128GB storage it will be 64GB/64GB and if you have a 256GB storage it will be 128GB/128GB.

## What you’ll need :

### Hardware :

- A Windows or Linux based computer (vm will work)
 
- An **Odin-Base** (4GB RAM with 64GB Storage) or an **Odin-Pro** (8GB RAM with 128GB or 256GB Storage)

- An 8GB or larger USB flash drive formatted to FAT32

- A USB-A to USB-C adapter to plug the flash drive into the C port of the Odin (if your drive doesn't have a USB-C connector)

### Prerequisite Software:

- [Google USB Driver](https://developer.android.com/studio/run/win-usb)

- [odin_custom_boot_1.0.3.7z](https://download.project-valhalla.com/custom_boot/odin_custom_boot_1.0.3.7z)

- [odin_windows_installer.7z](http://download.project-valhalla.com/custom_boot/odin_windows_installer.7z)

- Sensor Config Driver if you have **Model: Odin_M2** [qcSensorsConfig850-M2.zip](http://download.project-valhalla.com/custom_boot/qcSensorsConfig850-M2.zip)

- An install.wim from either folder in this [link](http://download.project-valhalla.com/windows_release/). 
  - Build 22621.1 is recommended as it has the least graphical issues at this time.

## Installation Steps:

1. [Preparing Windows Odin and Files](https://github.com/ProjectValhalla/OdinMultiBootGuides/blob/main/pages/preparing_windows_files.md)

2. [Installing Windows](https://github.com/ProjectValhalla/OdinMultiBootGuides/blob/main/pages/installing_windows.md)
