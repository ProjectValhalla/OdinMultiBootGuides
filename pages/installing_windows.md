🔙 Previous Step: [Partitioning the device](https://github.com/ProjectValhalla/OdinMultiBootGuides/blob/main/pages/preparing_windows_files.md)

# Installing Windows

1. With your powered off Odin unplugged from your pc, plug the USB drive into the port on the Odin and start the device with the same **Volume Up + Power** button press. Hold it until you see the Project Valhalla logo.

2. Windows will now begin installing. This process will take quite some time. You will see a console on the screen showing the installation progress.

3. Give it time and it will eventually show you a BSOD (Blue Screen of Death). This is part of the install process. Turn it off by holding the power button. The device will reboot to Android.

4. Unplug the USB drive, power the device off again and press **Volume Up + Power** until you see the Project Valhalla logo. It will now boot to Windows and configure. This will take a long time as well.

5. Windows will need to reboot multiple times throughout the installation and setup process. As the device will default to booting into Android, you will need to daul boot back to windows to resume the setup each time.  


## Setting up Windows Navigation

1. By default the screen will by in the vertical position. To fix this, tap and hold on the desktop for a moment and then release. Select Display Settings and set the Display Orientation to Landscape. Enable Rotation Lock. You may also want to turn the brightness down while you are here. 

2. To Enable On Screen keyboard (OSK), tap the windows icon at the bottom centre of the screen, Then tap Settings. From settings, Tap the menu bar at the top left of this menu and select Time & Language. Now Tap Typing, then Touch Keyboard, then enable "Show the touch keypad when there's no keyboard attached".

3. Windows may automatically lock the device when it sleeps with the PIN you were asked to set during setup. To Disable the pin, go into Settings, then the Menu Bar at the top left, then select Accounts. From here scroll down to Sign-in Options, select PIN and then select Remove. You will need to retype in your windows password to do this. 



## Choosing Operating Systems

Android will be the primary OS the device boots to if you press ther Power button. To boot to Windows, power off the device and press **Volume Up + Power** until you see the Project Valhalla Logo and the device will boot to Windows.




Enjoy!


## Returning to Android Only

Boot the device into fastboot by powering off the device and press **Volume Down + Power** until you see the Green START screen. Plug your device into your pc and run the `restore.bat` for Windows Host or `restore.sh` for Linux Host file in the `custom_boot_1.0.2.10_beta` folder.
