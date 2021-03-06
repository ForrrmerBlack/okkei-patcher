# Okkei Patcher
**Okkei Patcher** is a simple tool for localizing the Android version of CHAOS;CHILD.
It downloads the latest revision of CHAOS;CHILD Android English patch and automatically applies it to the installed Japanese version.
It creates a backup of your original installation of CHAOS;CHILD as well. You can check a checkbox whether you want to backup/restore your save data (note that if you change state of the checkbox throughout the process it won't affect it in any way, change the state before starting).
It is not planned to update the English patch. If you improved my English patch in some way, please contact me so I can upload it if it's compatible with Okkei Patcher.
Link to the patch: [Reddit post](https://old.reddit.com/r/steinsgate/comments/bxk37h/chaoschild_android_english_port/)

It is not recommended to run Okkei Patcher on weak, low-budget or very old devices.
Okkei Patcher supports devices running Android from version 4.4 KitKat (5.0 Lollipop before version 1.11) and above with armeabi-v7a.
Ensure that you have enough free space on your device for a backup (min. 2 GB).
It is recommended to not uninstall Okkei Patcher until you decide to uninstall CHAOS;CHILD completely, for your convenient user experience.
NOTE: Okkei Patcher doesn't support Android 11 yet.

### **Steps for patching**
1. Ensure that you have a stable internet connection. Also it is recommended to use Wi-Fi instead of mobile data due to large size of downloadable files.
2. Launch Okkei Patcher and click "PATCH". Please don't interrupt the process.
3. Somewhere in the middle of the process you will be asked to confirm uninstallation of CHAOS;CHILD. You need to confirm this.
4. Immediately after uninstallation you will be asked to install patched version of CHAOS;CHILD. You need to confirm this.
5. After installing CHAOS;CHILD the process of downloading patched OBB cache will start. Please don't interrupt it and don't disconnect from network. If you have save data from older installations of CHAOS;CHILD in Okkei Patcher backup folder, Okkei Patcher will restore it.

### **Steps for restoring your Japanese installation**
1. Launch Okkei Patcher and click "UNPATCH".
3. You will be asked to confirm uninstallation of CHAOS;CHILD. You need to confirm this.
4. Immediately after uninstallation you will be asked to install original version of CHAOS;CHILD. You need to confirm this.
5. After installing CHAOS;CHILD the process of restoring original OBB cache will start. Please don't interrupt it. If you have save data backup in Okkei Patcher backup folder, Okkei Patcher will restore it.

### **Possible problems**
* ~~If you confirmed the installation of CHAOS;CHILD and still got an error message that it was not installed, it is possible that this message is wrong and the process will continue as normal. If you have experience in programming for Android platform and are interested in fixing this, contact me.~~ Solved since v1.11.

## **Third party components**
See [THIRDPARTY](THIRDPARTY.md)
