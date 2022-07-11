# Preparing the Odin and Files

## Preparing the software

1. Install the [Google USB Driver](https://developer.android.com/studio/run/win-usb). Extract the archive and right-click on the `android_winusb.inf` and select install.

2. Extract the contents of `custom_boot_1.0.2.10.zip` into a folder.

3. Extract the contents of `windows_usb_installer.zip` into a separate folder and put the `install.wim` you selected in the `images` folder.

## Odin Device Preparation

1. Power off your Odin and start it back up by pressing and holding the **Volume Down + Power** button until you see the green START text. You are now booted to fastboot.

2. Plug your device into your pc, and run the `flash.bat` in the `custom_boot_1.0.2.10` folder. This will repartition your device. It will take several minutes to complete.

 If this step doesn't work, you may need to manually assign the device the correct driver from device manager by finding the device, right-clicking on it and selecting update driver. Then select browse my computer for drivers followed by let me pick from a list of available drivers. The Driver should appear under the Google section, select this and hit next. If the Android section or Google section is not present in the Drivers listed, click the "ALL Drivers" option at the top of the list. This will change the menu setup. Google should now be a visible section with three drivers listed, select "Android Bootloader Interface", hit next

3. The Odin will reboot to fresh start Android when the configuration has completed. Power it off and unplug it at this time.

## USB Stick Preparation

1. While that is flashing is the perfect time to setup your USB drive. Copy the contents of the `windows_usb_installer` folder onto the root of your FAT32 formatted USB drive. Make sure the `install.wim` file is in the `images` folder.

## Step 2

[Installing Windows](https://github.com/ProjectValhalla/OdinMultiBootGuides/blob/main/pages/installing_windows.md)
