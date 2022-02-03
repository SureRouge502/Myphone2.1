---------------------------------------------------------------------------------------------------------------------------------------------------------------------

myphone .sh
---------------

About: This program is created by SureRouge502 automating the process of using your Phone over wired or wireless connection in
       A linux machine. This program Uses ADB (Android Debug Bridge) and Fastboot in order to work..
       Works on All types of linux (Mostly tested on Debian And Kali coz i have those two only right now)
       This is the MyPhone2.1.

       Lets Move on to the installation process now...

NOTE: I have kept the name for the file as myphone1.sh in order to reduce the amount of work i needed to put in to improvemnets.
      Do not get confused , if this is in the myphone2.1 folder then this IS myphone 2.1 file, only that the file name is still myphone1.sh.
NOTE: DO NOT TRY TO RENAME THE FILE. This will intercept with the way this app has been built. Each file depends on the other. So please do not try to rename it!
      If ever , by accident you end up renaming it , then simply rename the file back to 'myphone1.sh'. This will fix the issue!

What's New?
-----------
          1. Myphone 2.1 provides a simple user interface that helps even the novices to understand how to use the program effortlessly!
          2. Myphone 2.1 now also comes with the bug fixes to the previous verision of the app. Ex: glitching ,
             errors in the code , and etc!
          3. This version of the app now brings a BRAND new feature to the production of Myphone app by SureRouge502. That is the use of Sndcpy technology! More on it down the page in the 'New Features' section of the page
          4. A Control Panel which helps you Control prime features of your device from anywhere around the house. More on this in the 'Features' section.
             as long as its registered to your machine through the app 
             NOTE: This works for both Wired and Wireless modes. Also , Know that theres no difference in options for Both modes. Both modes provide the same features!
             Further info in the 'Features' section of the README.md file


Features:
---------
          Toolbox:
                  This latest feature provides you a better hold of your device itself

                  1. Check wired connections.
                     This tool helps you to check/ detect wired devices (Android with USB debugging enabled) connected
                     to the machine. It helps in making sure weather you have USB debug mode ON/OFF.

                  2. Wired
                     This tool will help you initiate the adb toolkit.i.e Control Panel,  embedded into the app in "Wired" mode

                  3. Wireless
                     This will help you initiate the adb toolkit i.e. Control Panel ,embedded into the app in Wireless mode
 
                  4. Control Panel
                     Now , This is the biggest update there is to this app. The Control panel is a part of the app which helps you control ,manage your device in a more Advance Environment!
                     It brings New features like:
                     4.1 Reboot
                         This brings in multiple options and advanced reboot options as well
                         -Reboot -- A totally normal reboot of the deivce connect to the machine at the moment
                         -Recovery Reboot -- reboots your deivce into recovery mode
                         -Reboot Bootloader -- reboots the bootloader of your device
                         -Root Reboot - reboots your device into root user mode. (I'm not sure but i think this is for rooted devices only)
                    4.2 Shell
                        This opens a terminal window with Android Shell control initiated. You can intput Android shell input directly to your device right from here!
                        NOTE: Works on both Root and Non-Root devices
                    4.3 Install package
                        This feature allows you to install apps right into your device from your Linux Machine.
                        Usually , the Destination file would look something like this:
                        '/home/user/file/installationfile.apk'
                    4.4 Files Exchange
                        This feature helps you to transfer files between your PC and your device. 
                        NOTE: This can also work using the drag and drop feature.To use it simply open the screen of your device and drag and drop the file into the screen. This file will be stored into the 'Downloads' folder of your device
                        This also helps you to pull files from your device to your PC. Simply paste the destination file of your file from your device. It should look something like this
                        '/sdcard/video.mp4'
                        The following file will be placed in the Output Folder of the app.
                    4.5 Powerbutton toggle
                        This option toggles the act of powerbutton.Basically useful for when someone has your phone and you need to lock it immediately without even them touching it XD !
                        Can also be helpful for when your screen casting but the phone falls asleep.
                    4.6 Homescreen
                        This option initiates the act of homebutton on your device
                    4.7 swipe up
                        This option initiates the act of swiping upwards on a screen
                        NOTE: This may not work for all devices!
                    4.8 Volume Control
                        I think its pretty predictable what this option does , but still. SO this basically gives you the ability to control volume of your device
                        Volume levels range from "0-15"
                    4.9 About Device
                        Another very useful feature with this new update for Myphone app , this feature helps in getting your device information to you. Some types of information, like processes running in your phone ,may be too big to display hence they'll be dumped in Their own specific files in the same folder as Myphone2
                        NOTE: All previous data will be deleted when you initiate this 'About Device' option the next time and new information will be loaded!
                    4.10 Restart Casting
                         This option is for the times when you accidentaly close the ScreenMirror from your linux machine XD, trust me it happens at times XD!
                         This can also be used for when youre only using your toolbox , but need ScreenCAsting from your device


New Features:
-------------
This update of Myphone2.1 brings a Brand new feature , something you might've found really lacking in the app. Well not more like lacking , more like a required feature! 
Yes , I am talking about the abilty to share/ stream Audio right from your phone! This can be done in both wireless and wired modes. 

Wired:
    - Simply connect your phone using a USB , with USB debugging enabled!
    - Make sure your linux machine has detected your device . You could do this using the 'Check wired connections' option from the toolkit from the Main menu!
    - Run the myphone2.0 app using the code './myphone1.sh' (Make sure you've installed the app first!)
    - Once in the menu, select the 'Stream Audio' option from the main menu
    - A background terminal will open up , with the intent to connect to your device in order to stream Audio.
NOTE: The audio will be streaming to this pc as long as the background terminal is running, do not close it unless you want to stop audio streaming.

Wireless:
         

Installation:
--------------

Its quiet easy if i say so myself. infact just one piece of code to install all tools required to run this program

---> First, Give executable abilities to the program and the installer itself using the code :

chmod +x install.sh 

--->Now that you've given the executable permissions, You can now start the installation process by typing the command:

./install.sh

--->After that, you should get a message saying Installation complete and now you're ready to run the program itself
    In-order to run the program whenever u need it to...run the command:

./myphone1.sh

Enjoy the program...




Credits:
--------

*Creator: SureRouge502
*Email (In case you want to contact): iyengara41@gmail.com
*More of SureRouge502's work at:
 https://github.com/SureRouge502
