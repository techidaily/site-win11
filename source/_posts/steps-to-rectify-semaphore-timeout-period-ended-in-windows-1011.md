---
title: Steps to Rectify 'Semaphore Timeout Period Ended' In Windows 10/11
date: 2024-06-25T11:25:29.241Z
updated: 2024-06-26T11:25:29.241Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Rectify 'Semaphore Timeout Period Ended' In Windows 10/11
excerpt: This Article Describes Steps to Rectify 'Semaphore Timeout Period Ended' In Windows 10/11
keywords: Win10 Semaphore Fix,Win11 Semaphore Stop,Timeout Error Resolution,Semaphore Ended Solution,Windows Update Issue,System Semaphore Fix,Semaphore Timer Problem
thumbnail: https://thmb.techidaily.com/34062c0c76761441d1daaab882479cf039a7dd266a5c393fca1f08310200c903.jpg
---

## Steps to Rectify 'Semaphore Timeout Period Ended' In Windows 10/11

 Error 0x80070079 is an issue that can arise when users try to copy (or transfer) files between external USB or network storage drives and Windows PCs. The error 0x80070079 message says, “The semaphore timeout period has expired.” As a result, users can’t copy or move files between their PCs and storage devices.

 Some users might wonder what a semaphore is, which is an integer variable. The 0x80070079 error message highlights there’s been an operation timeout. This is how you can fix error 0x80070079 in Windows 11/10\.

## 1\. Try Transferring or Copying Files in Smaller Groups

 It might be the case that the 0x80070079 error occurs on your PC because of an issue with one particularly large file in a group. So, try transferring (or copying) a smaller group of files to see if that makes a difference. If that works, move or copy more files of the files you need within another smaller batch.

## 2\. Change the Connection Cable

 Error 0x80070079 can arise if there’s an issue with the cable you’re using for connecting an external USB storage drive to the computer. Try utilizing a different USB cable if you have one available. If you can see your current cable is visibly damaged, consider purchasing a replacement.

## 3\. Run the Hardware and Devices Troubleshooter

 The Hardware and Devices troubleshooter is a tool for fixing hardware-related issues in Windows. A few users have confirmed in forums that troubleshooter resolved error 0x80070079 on their PCs. This is how you can open and utilize the Hardware and Devices troubleshooter in Windows 11/10:

1. Find Command Prompt by pressing the **Win + S** keys and typing CMD in the search box.
2. Click on Command Prompt to run that app.
3. Execute this Hardware and Devices troubleshooter command and hit **Enter**:  
`msdt.exe -id DeviceDiagnostic`  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/hardware-and-devices-command.jpg)
4. Select **Next** to start the troubleshooting and apply the fixes suggested.  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/hardware-and-devices-troubleshooter.jpg)

 Users who need to fix error 0x80070079 for network drives should consider utilizing the Network Adapter and Internet Connections troubleshooters. You can access both of those troubleshooters in Settings. Check out our [guide about running troubleshooters](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) in Windows for further details about how to open them in Windows 11/10\.

## 4\. Perform Generic Windows-Based Fixes for Troubleshooting USB Drives

 If you're still struggling with this error, here are some more general Windows-based fixes you can try:

### Run a System File Check Scan

 Corrupted or missing system files on your PC’s drive can cause operations to time out. To resolve such an issue, run a System File Checker command. You can repair the system files on an internal hard drive by executing a standard SFC command as outlined in our guide to [running the SFC tool on Windows](https://www.makeuseof.com/system-file-checker-sfc-windows/).

![The SFC scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-scannow-command.jpg)

### Run the CHKDSK Scan Command

 CHKDSK is Windows’ Check Disk utility that scans and repairs bad drive sectors. That tool could be useful for fixing error 0x80070079 if it’s caused by disk errors on a drive you’re trying to transfer files to. So, try scanning the target drive by running the CHKDSK via the Command Prompt. Our guide on [running Check Disk scans on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=The%20CHKDSK%20utility%20scans%20your,and%20sizes%2C%20and%20bad%20sectors.) includes full instructions for applying this potential fix.

![The chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/chkdsk-command.jpg)

### Turn Off Any Active Firewalls

 Disabling firewalls might work when 0x80070079 occurs for wireless transfers from or to network drives. A firewall can block communication with a network drive. So, try temporarily [disabling Windows Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) before transferring any data from or to a network drive. Or turn off any third-party firewall installed.

![Turn off firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/customize-firewall-options.jpg)

### Disable Your Antivirus Shields

 If you’ve installed a third-party antivirus (security) utility, that might be causing the issue by preventing or restricting data transfer between drives. Temporarily disable your antivirus software’s shield before selecting to move or copy files from one drive to another. To do that, click on the antivirus tool’s system tray icon with the right mouse button and select the disable shield option.

### Perform a Clean Boot

 Some users confirm performing a clean boot fixes error 0x80070079\. Applying a clean boot will disable all third-party startup apps and services from starting. This resolution might eliminate third-party background program conflicts interfering with the data transfer and causing error 0x80070079\.

 You can apply this resolution by following the instructions in our [guide to performing a clean boot](https://www.makeuseof.com/clean-boot-windows-11/). Restart your PC when you’ve disabled all third-party startup items with Task Manager and System Configuration. Then copy or move the files you need to between drives after clean booting.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-services-tab.jpg)

### Update the Driver for Your PC’s Network Adapter Driver

 Updating a PC’s network adapter driver can be a viable fix when error 0x80070079 occurs for wireless data transfers. An outdated or faulty network driver could be causing network connection issues between devices.

![The Driver Booster software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/update-now-button.jpg)

 You can update your PC’s network adapter by utilizing driver updater software. Such software will tell you if your network adapter’s driver is outdated and enable you to update it if necessary. Check out [how to update Windows, apps, and drivers](https://www.makeuseof.com/tag/update-windows-software-guide/) to give your PC a quick refresh, including your network adapter.

### Change Your External Drive to NTFS Format

 Some Windows PC users have fixed error 0x80070079 by reformatting their external USB drives to the NTFS format. The reason this resolution has worked for some users is probably that FAT32 can’t store single files larger than four gigabytes. Reformatting a FAT32 drive to NTFS will eliminate such a restriction.

![The Format window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/format-seagate-drive.jpg)

 You can apply this possible resolution as covered within our guide to [reformatting USB drives in Windows 11](https://www.makeuseof.com/windows-11-format-usb-drive-ntfs/).

 Reformatting a drive will wipe all the data on it. So, make sure you back up the drive’s data before reformatting if you want to keep any files on it.

### Reset Your Network

 This potential resolution is more applicable for users who encounter error 0x80070079 with network storage drives. Resetting your network will restore it to its settings to default and reinstall your PC’s network adapter. To apply this resolution, check out our [how to reset your network settings on Windows](https://www.makeuseof.com/reset-network-settings-windows-11/) guide.

![The Reset now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-reset-now-button.jpg)

 Note that you’ll need to reconnect your PC to the internet after applying this resolution. So, make sure you have your internet connection name and password details before resetting the network. You can usually find such details stuck on the bottom of most routers.

## Transfer Data Between Drives Again on Windows

 Finding a solution for error 0x80070079 isn’t always easy since it’s an issue with variable factors. However, one of the resolutions covered here will probably solve the “semaphore timeout period has expired” error on your PC. If not, however, you might be able to work around this issue by transferring data in different ways with cloud storage, file-sharing apps, or other methods.

 Some users might wonder what a semaphore is, which is an integer variable. The 0x80070079 error message highlights there’s been an operation timeout. This is how you can fix error 0x80070079 in Windows 11/10\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/eradicating-restrictive-settings-from-steam-libraries-win-11/"><u>Eradicating Restrictive Settings From Steam Libraries Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719196389328-resolving-stuck-windows-update-problems-now/"><u>Resolving Stuck Windows Update Problems Now</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-stop-laptops-internal-keystrokes/"><u>Step-by-Step: Stop Laptop's Internal Keystrokes</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-stalker-unveiled-preventive-measures-against-wacatacbml/"><u>The Silent Stalker Unveiled: Preventive Measures Against Wacatac.B!ml</u></a></li>
<li><a href="https://win11.techidaily.com/employing-rufus-to-navigate-windows-11s-security-barriers/"><u>Employing Rufus to Navigate Windows 11'S Security Barriers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-text-actions-in-the-snipping-tool-on-windows-11/"><u>How to Use Text Actions in the Snipping Tool on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-rdp-access-quickly-in-the-latest-windows/"><u>Unlock RDP Access Quickly in the Latest Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-settings-managing-device-permissions/"><u>Navigating Windows Settings: Managing Device Permissions</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-inability-to-link-with-nvidia-experience-on-pcs/"><u>Overcoming the Inability to Link with NVIDIA Experience on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-in-use-errors-unique-device-names-on-windows-pcs/"><u>Clearing Up In Use Errors: Unique Device Names on Windows PCs</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-top-5-guitar-centric-audio-capture-programs-for-musicians/"><u>New In 2024, Top 5 Guitar-Centric Audio Capture Programs for Musicians</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-comprehensive-walkthrough-setting-up-sound-recording-on-garageband/"><u>New Comprehensive Walkthrough Setting Up Sound Recording on GarageBand</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-find-your-fit-understanding-basic-to-pro-plans-at-vimeo-for-2024/"><u>[New] Find Your Fit  Understanding Basic to Pro Plans at Vimeo for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-video-invitation-design-made-easy-top-apps-for-iphone-and-android/"><u>Updated In 2024, Video Invitation Design Made Easy Top Apps for iPhone and Android</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-sony-xperia-5-v-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Sony Xperia 5 V Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-understanding-intellectual-property-rights-on-video-screen-captures/"><u>2024 Approved  Understanding Intellectual Property Rights on Video Screen Captures</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/precise-portrayal-of-pixels-master-netflix-recordings-with-these-6-mac-tactics-for-2024/"><u>Precise Portrayal of Pixels  Master Netflix Recordings with These 6 Mac Tactics for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-vivo-y100a-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Vivo Y100A to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/best-vivo-v27-pro-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Vivo V27 Pro Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/audio-formats-guide-how-to-choose-best-audio-formats-solved-for-2024/"><u>Audio Formats Guide How to Choose Best Audio Formats Solved for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>