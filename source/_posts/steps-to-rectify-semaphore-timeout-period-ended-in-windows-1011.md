---
title: Steps to Rectify 'Semaphore Timeout Period Ended' In Windows 10/11
date: 2024-07-13T09:55:42.009Z
updated: 2024-07-14T09:55:42.009Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/darkmodetoggleforwin-basedtexteditor/"><u>DarkModeToggleForWin-basedTextEditor</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missing-action-buttons-on-windows-11-pc/"><u>Overcoming Missing Action Buttons on Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/1719334729837-fix-unusable-compatibility-center-on-vista7-pcs-fast/"><u>Fix Unusable Compatibility Center on Vista/7 PCs Fast</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-your-printer-on-windows-11-step-by-step/"><u>Fixing Your Printer on Windows 11: Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-security-new-passwords/"><u>Navigating Windows 11 Security: New Passwords</u></a></li>
<li><a href="https://apple-account.techidaily.com/unlock-apple-id-without-phone-number-on-apple-iphone-xs-max-by-drfone-ios/"><u>Unlock Apple ID without Phone Number On Apple iPhone XS Max</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-modify-win11s-network-preferences/"><u>Guide to Modify Win11's Network Preferences</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-essential-tips-for-flv-file-fusion-on-youtube/"><u>2024 Approved  Essential Tips for FLV File Fusion on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/achieving-optimal-security-in-win-11-with-ms-defender-application-guard-for-edge/"><u>Achieving Optimal Security in Win 11 with MS Defender Application Guard for Edge</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-coding-in-windows-a-guide-to-using-microsoft-copilot/"><u>Mastering Coding in Windows: A Guide to Using Microsoft Copilot</u></a></li>
<li><a href="https://win11.techidaily.com/cooler-computing-strategies-for-gamers-systems/"><u>Cooler Computing Strategies for Gamers' Systems</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-gifs-to-stickers-comprehensive-tutorial-series-for-multiple-chat-apps/"><u>[Updated] From Gifs to Stickers  Comprehensive Tutorial Series for Multiple Chat Apps</u></a></li>
<li><a href="https://win11.techidaily.com/moment-update-windows-11-unpacks-future-looking-features/"><u>Moment Update: Windows 11 Unpacks Future-Looking Features</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-exploring-the-peaks-of-magix-samplitude-a-comprehensive-review/"><u>In 2024, Exploring the Peaks of MAGIX Samplitude A Comprehensive Review</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-instagram-tv-deactivation-made-easy-for-2024/"><u>[Updated] Instagram TV Deactivation Made Easy for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-accessing-the-fax-editor-in-win11/"><u>Essential Tips: Accessing the Fax Editor in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-windows-mail-glitches-the-0x80072746-fix-guide/"><u>Combatting Windows Mail Glitches: The 0X80072746 Fix Guide</u></a></li>
<li><a href="https://some-tips.techidaily.com/top-streamers-choice-does-virusmix-or-wirecast-rule-the-game-in-2024/"><u>Top Streamers Choice  Does VirusMix or WireCast Rule the Game, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-running-intel-unison-correctly-in-windows-11/"><u>Mastering the Art of Running Intel Unison Correctly in Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/top-ranked-youtube-extractors-pc-mobile-and-more-tips-for-2024/"><u>Top-Ranked YouTube Extractors - PC, Mobile, and More Tips for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-dark-screen-quandary-in-window-8/"><u>Overcoming the Dark Screen Quandary in Window 8</u></a></li>
<li><a href="https://win11.techidaily.com/minimizing-edges-process-count-in-windows/"><u>Minimizing Edge's Process Count in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-uncover-gpo-settings/"><u>Mastering Windows: Uncover GPO Settings</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-flawless-playlist-integration-techniques-in-web-development-for-2024/"><u>[New] Flawless Playlist Integration Techniques in Web Development for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-crafting-universal-streams-for-youtube-and-beyond-networks/"><u>[Updated] 2024 Approved  Crafting Universal Streams for YouTube & Beyond Networks</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-uninstall-microsoft-edge-from-windows-11/"><u>How to Uninstall Microsoft Edge From Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-windows-assistance-entry/"><u>Mastering the Art of Windows Assistance Entry</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-tray-interface-with-numeric-and-caps-indicators/"><u>Personalize Tray Interface with Numeric and Caps Indicators</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-optimal-pick-the-top-ten-phone-and-pc-video-calls-for-2024/"><u>[New] Optimal Pick  The Top Ten Phone & PC Video Calls for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-original-directory-display-preferences/"><u>Regaining Original Directory Display Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-use-of-windows-module-installer-worker/"><u>Decreasing Excessive Use of Windows Module Installer Worker</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-millions-watch-but-how-much-do-they-earn/"><u>[New] In 2024, Millions Watch, But How Much Do They Earn?</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-xbox-app-issues-on-your-windows-system/"><u>Overcome Xbox App Issues on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-windows-11-tackling-lag-and-delay/"><u>Fast-Track Windows 11: Tackling Lag and Delay</u></a></li>
<li><a href="https://win11.techidaily.com/swift-resolution-to-windows-update-error-code-0xc1900101/"><u>Swift Resolution to Windows Update Error Code 0xC1900101</u></a></li>
<li><a href="https://win11.techidaily.com/7-obstacles-hindering-windows-11-upgrade-traction/"><u>7 Obstacles Hindering Windows 11 Upgrade Traction</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-the-editors-beat-pairing-visual-sequences-with-musical-tempo-using-adobe-premiere-pro/"><u>In 2024, The Editors Beat Pairing Visual Sequences with Musical Tempo Using Adobe Premiere Pro</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-go-joystick-on-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Xiaomi Civi 3? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-ink-to-paper-translation-selecting-best-windows-tabs/"><u>Ideal Ink-to-Paper Translation: Selecting Best Windows Tabs</u></a></li>
<li><a href="https://network-issues.techidaily.com/rtx-nightmare-buster-your-gaming-rescue-plan/"><u>RTX Nightmare Buster - Your Gaming Rescue Plan</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-about-to-expire-message-on-microsoft-os/"><u>Bypassing the About To Expire Message on Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11-start-up-with-these-simple-ideas/"><u>Streamline Windows 11 Start-Up with These Simple Ideas</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-proven-winners-selecting-the-best-hdr-cameras/"><u>In 2024, Proven Winners  Selecting the Best HDR Cameras</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-mail-readability-removing-html-from-email-text/"><u>Enhancing Windows 11 Mail Readability: Removing HTML From Email Text</u></a></li>
<li><a href="https://win11.techidaily.com/managing-safe-browsing-in-microsofts-win11/"><u>Managing Safe Browsing in Microsoft’s Win11</u></a></li>
</ul></div>
