# Preparing the Odin and Files

## Preparing the software

1. For Windows Host Install the [Google USB Driver](https://developer.android.com/studio/run/win-usb). Extract the archive and right-click on the `android_winusb.inf` and select install.

2. Extract the contents of `odin_custom_boot_1.0.3.7z` into a folder.

3. Extract the contents of `odin_debian_sid_gnome_ufs_xxxxxxxx.zip` into a separate folder.

## Odin Device Preparation

Power off your Odin and start it back up by pressing and holding the **Volume Down + Power** button until you see the green START text. You are now booted to fastboot.

Plug your device into your pc
 - If you have **Model: Odin**  Run the `flash_odin_m0.bat` for Windows Host or `flash_odin_m0.sh` for Linux Host in the `odin_custom_boot_1.0.3` folder. This will repartition your device. It will take several minutes to complete.
 - If you have **Model: Odin_M2**  Run the `flash_odin_m2.bat` for Windows Host or `flash_odin_m2.sh` for Linux Host in the `odin_custom_boot_1.0.3` folder.

 This will repartition your device, it will take several minutes to complete.

 If this step doesn't work, you may need to manually assign the device the correct driver from device manager by finding the device, right-clicking on it and selecting update driver. Then select browse my computer for drivers followed by let me pick from a list of available drivers. It should be under Google, then select the bootloader interface driver and hit next.

The Odin will reboot to fresh start Android when the configuration has completed. Power it off and unplug it at this time.

## Step 2

[Installing Linux](https://github.com/ProjectValhalla/OdinMultiBootGuides/blob/main/pages/installing_linux.md)
