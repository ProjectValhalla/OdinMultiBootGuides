🔙 Previous Step: [Partitioning the device](https://github.com/ProjectValhalla/OdinMultiBootGuides/blob/main/pages/preparing_windows_files.md)

# Installing Windows

1. With your powered off Odin unplugged from your pc, plug the USB drive into the port on the Odin and start the device with the same **Volume Up + Power** button press. Hold it until you see the Project Valhalla logo.

2. Windows will now begin installing. This process will take quite some time. You will see a console on the screen showing the installation progress.

3. Give it time and it will eventually show you a BSOD (Blue Screen of Death). This is part of the install process. Turn it off by holding the power button. The device will reboot to Android.

4. Unplug the USB drive, power the device off again and press **Volume Up + Power** until you see the Project Valhalla logo. It will now boot to Windows and configure. This will take a long time as well.

## Choosing Operating Systems

Android will be the primary OS the device boots to if you press ther Power button. To boot to Windows, power off the device and press **Volume Up + Power** until you see the Project Valhalla Logo and the device will boot to Windows.


Enjoy!

## If **Volume Up + Power** doesnt work for booting Valhalla

If **Volume Up + Power** doesn't work, you probably need to reflash your Odin with the newer Version out there.
To do that just follow the steps in the [Flashing ProjectValhalla Firmware](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/FlashingProjectValhallaFirmware.md) but with the Odin Firmware.
[Odin Firmware](https://drive.google.com/drive/folders/1PrheTNtgZXvNBXgGlDkM4ilhVerKDPtT?usp=sharing)
After you reflashed your Odin, it should be ready for the Dualboot.
Don't skip any step!
The reflashing step will erase everything!

## Returning to Android Only

Boot the device into fastboot by powering off the device and press **Volume Down + Power** until you see the Green START screen. Plug your device into your pc and run the `restore.bat` for Windows Host or `restore.sh` for Linux Host file in the `custom_boot_1.0.2.10_beta` folder.
