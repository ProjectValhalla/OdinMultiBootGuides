#Preparing the Odin and Files

## Preparing the software

1. Install the [Google USB Driver](https://developer.android.com/studio/run/win-usb).

2. Extract the contents of custom_boot_1.0.2.10.zip into a folder.

3. Extract the contents of windows_usb_installer.zip into a separate folder and put the install.wim you selected in the images folder.

## Odin Device Preparation

1. Power off your Odin and start it back up by pressing and holding the Volume Up + Power button until you see the green START text. You are now booted to fastboot.

2. Plug your device into your pc, and run the flash.bat in the custom_boot_1.0.2.10 folder. This will repartition your device. It will take several minutes to complete.

## USB Stick Preparation

1. While that is flashing is the perfect time to setup your windows installation drive. Copy the contents of the windows_usb_installer folder onto the root of your USB drive. Make sure the install.wim file is in the images folder.
