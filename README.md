# SM-J320FN

Rooting Samsung SM-J320FN

Needed software (PC)
--------------------
* Download **Samsung Odin** from http://odindownload.com. I have had no success with the OSX version of this software.
* Using version 3.12
* Download a Samsung USB Driver for PC.

Downloading firmware
--------------------
* Download J320FNXXU0APH1_J320FNNEE0APH1_J320FNXXU0APH1_HOME.tar.md5
* Start **Odin** and click the **AP** button. Select the downloaded firmware (.md5) file.
* Power off your phone and restart in download mode.
* Connect your phone. The log should display something like "Added!!". Then click the **Start** button.
* The phone will reboot when finished.
* Follow the android installation instructions

Set developer mode
------------------
* Start your phone.
* Go to Settings -> About device -> Software Info
* Tap multiple times on **Build Number**
* Go to Settings -> Developer options
* Select **OEM unlock**
* Select **USB debugging**
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
* https://xxdaroot.blogspot.se
	* Some xposed files corrupt when downloading. Keep trying.


Log
-----
* J320FNXXU0APH1_J320FNNEE0APH1_J320FNXXU0APH1_HOME.tar.md5
*
*
