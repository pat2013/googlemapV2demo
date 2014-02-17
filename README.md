googlemapV2demo
===============
How to test Google Map V2 on emulator?

Officially, Google Map V2 can not run on emulator,but there is always a way go round it.
 For this purpose simply followed these steps:
Go to http://www.genymotion.com/ Download Genymotion Emulator.
Create an emulator with Galaxy Nexus-4.2.2 with google apps-Api 17 
Download the two zip files from the link ARM Translation Installer v1.1 http://goo.gl/JBQmPa and Google Apps for Android 4.2 http://goo.im/gapps/gapps-jb-20130812-signed.zip
Then copy these files to desktop(For ubuntu).
Open genymotion emulator and go to home screen then from the desktop drag and drop the first file Genymotion-ARM-Translation_v1.1.zip .A dialog will appear and show as file transfer in progress ,then another dialog will appear and ask that do you want to flash it on the emulator then click OK after this it will ask to reboot the device then restart adb .
After this drag and drop the second file gapps-jb-20130812-signed.zip and repeat the same steps as above. restart adb and this will install google apps on your emulator.
Remember you can drag and drop files into the emulator only from the desktop in case of ubuntu (You can drag and drop from everywhere on windows). After emulator restart, you should be able to run Google Map V2 on your emulator.
