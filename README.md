# SM-J320FN

Rooting Samsung SM-J320FN

Needed software (PC)
--------------------
* Download **Samsung Odin** from http://odindownload.com. I have had no success with the OSX version of this software.
* Download a Samsung USB Driver for PC.

Downloading firmware
--------------------
* Get U.K. version of the firmware from http://www.sammobile.com/firmwares/download/87976/J320FNXXU0APH1_J320FNBTU0APH1_BTU
* Start **Odin** and click the **AP** button. Select the downloaded firmware (.md5) file.
* Power off your phone and restart in download mode.
* Connect your phone. The log should display something like "Added!!". Then click the **Start** button.
* The phone will reboot when finished.
* Follow the android installation instructions

Set developer mode
------------------
* Go to Settings -> About device -> Software Info
* Tap multiple times on **Build Number**

Allow unknown sources
---------------------
* Go to Settings -> Lock screen and security
* Select **Unknown sources**

Flashing TWRP
-------------
* Start your phone in download mode
* Start **Odin**
* Click the **AP** button and select the file TWRP_3.0.2-0_SM-J320F.tar.tar
* Click **Start**

Installing SuperSU from TWRP
----------------------------
* Transfer the file UPDATE-SuperSU-v2.76-20160630161323.zip to internal storage on the phone
* Start the phone in recovery mode
*
* In TWRP select **Install** and choose the transferred file




Links
-------
* Rooting J3 http://forum.xda-developers.com/general/help/samsung-galaxy-j3-sm-j320fn-how-to-root-t3369511/page2#post68596176
* Chainfire https://autoroot.chainfire.eu
* SamMobile firmware http://www.sammobile.com/firmwares/
* xda-developers http://forum.xda-developers.com


Log
-----
* Installed UK version of firmware
* Prompted for software update - selected YES
* Flashed TWRP
