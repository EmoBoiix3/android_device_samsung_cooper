android_device_samsung_cooper
==========================
Device configuration for cooper (Samsung Galaxy Ace, GT-S5830), specifically for Project Equilibrium.

Getting Started
---------------
To get started with Project Equilibrium, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the CyanogenMod trees, use a command like this:

    repo init -u git://github.com/Project-Equilibrium/android.git -b cm-10.2

Then to sync up:

    repo sync

Build your device:

    ./build.sh cooper

Disclaimer
--------
This repo was forked from the AndroidARMv6 Project:

"All of these device are not supported by CyanogenMod since they use the old Qualcomm Snapdragon MSM7x27 chip, and hence cut off by the CyanogenMod team. This team (androidarmv6) is in no way, shape or form affiliated by the CyanogenMod team and this project is not endorsed or supported by the CyanogenMod team."
