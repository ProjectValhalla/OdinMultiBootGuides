🔙 Previous Step: [Partitioning the device](https://github.com/ProjectValhalla/OdinMultiBootGuides/blob/main/pages/preparing_linux_files.md)

# Installing Linux

1. Power off your Odin and start it back up by pressing and holding the **Volume Down + Power** button until you see the green START text. You are now booted to fastboot.

2. Plug your device into your pc, and run the `flash.bat` for Windows Host or `flash.sh` for Linux Host in the `odin_debian_sid_gnome_ufs_xxxxxxxx` folder. This will Linux OS. It will take several minutes to complete and Odin will rebooted.

## Choosing Operating Systems

Android will be the primary OS the device boots to if you press ther Power button. To boot to Windows, power off the device and press **Volume Up + Power** until you see the Project Valhalla Logo and the device will boot to Windows.

Enjoy!

## Returning to Android Only

Boot the device into fastboot by powering off the device and press **Volume Down + Power** until you see the Green START screen. Plug your device into your pc and run the `restore.bat` file in the `custom_boot_1.0.2.10_beta` folder.
