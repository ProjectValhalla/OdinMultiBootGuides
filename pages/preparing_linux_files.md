# Preparing the Odin and Files

## Preparing the software

1. For Windows Host Install the [Google USB Driver](https://developer.android.com/studio/run/win-usb). Extract the archive and right-click on the `android_winusb.inf` and select install.

2. Extract the contents of `custom_boot_1.0.2.10_beta.zip` into a folder.

3. Extract the contents of `odin_debian_sid_gnome_ufs_xxxxxxxx.zip` into a separate folder.

## Odin Device Preparation

1. Power off your Odin and start it back up by pressing and holding the **Volume Down + Power** button until you see the green START text. You are now booted to fastboot.

2. Plug your device into your pc, and run the `flash.bat` for Windows Host or `flash.sh` for Linux Host in the `custom_boot_1.0.2.10_beta` folder. This will repartition your device. It will take several minutes to complete.

 If this step doesn't work, you may need to manually assign the device the correct driver from device manager by finding the device, right-clicking on it and selecting update driver. Then select browse my computer for drivers followed by let me pick from a list of available drivers. It should be under Google, then select the bootloader interface driver and hit next.

3. The Odin will reboot to fresh start Android when the configuration has completed. Power it off and unplug it at this time.

## Step 2

[Installing Linux](https://github.com/ProjectValhalla/OdinMultiBootGuides/blob/main/pages/installing_linux.md)
