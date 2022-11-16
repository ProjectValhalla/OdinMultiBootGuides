🔙 Previous Step: [Partitioning the device](https://github.com/ProjectValhalla/OdinMultiBootGuides/blob/main/pages/preparing_windows_files.md)

# Installing Windows

## Choosing Operating Systems
Latest ABL version is capable to directly boot to Android or another OS such as Windows or Linux.

Go to Fastboot mode by pressing and holding the **Volume Down + Power** button until you see the green START text.

Look at the **DEFAULT BOOT** value if it's `DEFAULT BOOT =  Android` then you need to switch to `DEFAULT BOOT =  Custom` by selecting `Switch Default Boot` option.

To navigate the boot option use **Volume Up** or **Volume Down** buttons, and use **Power** button for selecting the option.
![Default Boot](/images/fastboot_default_boot.png)
The device will be restarted and entering Fastboot menu again after you select **Switch Default Boot** option, press power button to start the booting process or select **Power off** option tu turn of the device.

1. With your powered off Odin unplugged from your PC, plug the USB drive into the port on the Odin and start the device. Hold it until you see the Project Valhalla logo.

2. Windows will now begin installing. This process will take quite some time. You will see a console on the screen showing the installation progress.

3. Give it time and it will eventually show you a BSOD (Blue Screen of Death). This is part of the install process. Turn it off by holding the power button. 

4. Unplug the USB drive, it will now boot to Windows and configure. This will take a long time as well.

Enjoy!

## Returning to Android Only

Boot the device into Fastboot by powering off the device and press **Volume Down + Power** until you see the Green START screen. 

Plug your device into your PC
 - If you have **Model: Odin**  Run the `restore_odin_m0.bat` for Windows Host or `restore_odin_m0.sh` for Linux Host in the `odin_custom_boot_1.0.3` folder.
 - If you have **Model: Odin_M2**  Run the `restore_odin_m2.bat` for Windows Host or `restore_odin_m2.sh` for Linux Host in the `odin_custom_boot_1.0.3` folder.

 This will repartition your device. It will take several minutes to complete.