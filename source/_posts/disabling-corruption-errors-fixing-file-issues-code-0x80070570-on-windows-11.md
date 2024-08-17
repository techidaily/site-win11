---
title: Disabling Corruption Errors - Fixing File Issues Code 0X80070570 on Windows 11
date: 2024-08-15T23:36:02.757Z
updated: 2024-08-16T23:36:02.757Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Corruption Errors - Fixing File Issues Code 0X80070570 on Windows 11
excerpt: This Article Describes Disabling Corruption Errors - Fixing File Issues Code 0X80070570 on Windows 11
keywords: Win11CorruptionErrorFix,XP70FileIssueCode,Error0X80070570Resolve,FileMalfunctionWindows11,Code0X80070570Solution,WindowsFileCorruptionFixes,0X80070570ErrorRepair
thumbnail: https://thmb.techidaily.com/878905428de37ec37afcf7b8018e7d924bf2c1ca322a8100dfaafbd0ac4bcb97.jpg
---

## Disabling Corruption Errors - Fixing File Issues Code 0X80070570 on Windows 11

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
3. Next, select your Windows user account.
4. Input your user account password.
5. Select **Continue** to initiate the repair.

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-best-text-plugins-for-after-effects/"><u>[New] Best Text Plugins For After Effects</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlocking-the-palette-of-possibilities-with-downloadable-spark-ar-luts/"><u>[New] Unlocking the Palette of Possibilities with Downloadable Spark AR LUTs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-gleaming-graphics-the-art-of-crafting-insta-highlights-3-ways/"><u>[Updated] In 2024, Gleaming Graphics  The Art of Crafting Insta Highlights (3 Ways)</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-infuse-melodies-into-powerpoint-visuals/"><u>[Updated] Infuse Melodies Into PowerPoint Visuals</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-quicktime-magic-precise-timelapse-shots-with-samsung/"><u>[Updated] Quicktime Magic  Precise Timelapse Shots with Samsung</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-the-journey-through-timeran-images-3-methods-on-facebook-for-2024/"><u>[Updated] The Journey Through Time'ran Images  3 Methods on Facebook for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-ultimate-buyers-blueprint-for-youtubers/"><u>2024 Approved  The Ultimate Buyer's Blueprint for Youtubers</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Samsung Galaxy F14 5G | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/accelerate-your-metaverse-journey-with-7-must-have-devices-for-2024/"><u>Accelerate Your Metaverse Journey with 7 Must-Have Devices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-ai-and-windows-with-vivetool-steps/"><u>Bridging AI and Windows with ViveTool Steps</u></a></li>
<li><a href="https://win11.techidaily.com/brighten-dull-extend-volume-buttons-in-diskmgmt/"><u>Brighten Dull Extend Volume Buttons in DiskMgmt</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-ignored-win11-themes-worth-checking/"><u>Bypass Ignored: Win11 Themes Worth Checking</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-local-lsa-deactivated-warning/"><u>Bypassing 'Local LSA Deactivated' Warning</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-common-steam-connectivity-issues/"><u>Bypassing Common Steam Connectivity Issues</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-error-0x8007251d-in-windows-system-activation/"><u>Bypassing Error 0X8007251D in Windows System Activation</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-initial-load-issues-in-lotr-lol-game/"><u>Bypassing Initial Load Issues in LOTR (LOL) Game</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-server-stumbled-problem-in-ms-store-a-guide-for-windows-11-and-11-users/"><u>Bypassing Server Stumbled Problem in MS Store: A Guide for Windows 11 and 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/cant-set-the-time-zone-automatically-in-windows-try-these-fixes/"><u>Can’t Set the Time Zone Automatically in Windows? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/capture-your-gameplay-utilizing-windows-and-intel-graphics-tools/"><u>Capture Your Gameplay: Utilizing Windows & Intel Graphics Tools</u></a></li>
<li><a href="https://win11.techidaily.com/cease-use-of-voice-recognition-ai-on-windows/"><u>Cease Use of Voice Recognition AI on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/classic-computers-for-a-modern-world-running-windows-11-through-to-go-and-rufus/"><u>Classic Computers for a Modern World: Running Windows 11 Through To Go and Rufus</u></a></li>
<li><a href="https://win11.techidaily.com/cleanse-your-pc-banishing-temporary-windows-files/"><u>Cleanse Your PC: Banishing Temporary Windows Files</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-access-denied-errors-fixing-outlook-issues-in-windows-os/"><u>Clearing 'Access Denied' Errors: Fixing Outlook Issues in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-access-issues-fixing-files-not-displayed-on-windows-pc/"><u>Clearing Up Access Issues: Fixing Files Not Displayed on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-confusion-how-to-fix-0x8007045d-blue-screen-in-win11/"><u>Clearing Up Confusion: How to Fix 0X8007045d Blue Screen in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-corruption-fix-your-win1011-recycle-error/"><u>Clearing up CORRUPTION! Fix Your WIN10/11 Recycle Error</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-win10-fix-invalid-network-path/"><u>Clearing Up Win10: Fix Invalid Network Path</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-windows-1011-xbox-game-pass-connection-glitch/"><u>Clearing Windows 10/11: Xbox Game Pass Connection Glitch</u></a></li>
<li><a href="https://win11.techidaily.com/clone-without-cutting-corners-windows-edition/"><u>Clone Without Cutting Corners: Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/clutter-free-computing-minimize-to-system-tray-with-a-keyboard-shortcut/"><u>Clutter-Free Computing: Minimize to System Tray with a Keyboard Shortcut</u></a></li>
<li><a href="https://win11.techidaily.com/cmd-magic-show-unraveling-5-mesmerizing-maneuvers/"><u>CMD Magic Show: Unraveling 5 Mesmerizing Maneuvers</u></a></li>
<li><a href="https://win11.techidaily.com/combat-reduced-desktop-icon-dimensions-on-windows-11/"><u>Combat Reduced Desktop Icon Dimensions on Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-easily-and-quickly-draw-on-photos-app-in-windows-11-for-2024/"><u>How to Easily and Quickly Draw on Photos App in Windows 11 for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-samsung-galaxy-m54-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-innovating-with-color-a-complete-look-at-ps-3d-luts/"><u>In 2024, Innovating with Color  A Complete Look at PS 3D LUTs</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-streamlined-playback-controlling-youtube-video-delivery-speeds/"><u>In 2024, Streamlined Playback  Controlling YouTube Video Delivery Speeds</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-realme-11-pro-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Realme 11 Pro Phone Hassle-Free</u></a></li>
<li><a href="https://win-howtos.techidaily.com/missing-media-hardware-driver-restored-computer-functionality-enhanced/"><u>Missing Media Hardware Driver Restored, Computer Functionality Enhanced</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/overcoming-unexpected-display-challenges-in-windows-11-expert-fixes/"><u>Overcoming Unexpected Display Challenges in Windows 11: Expert Fixes</u></a></li>
<li><a href="https://fix-guide.techidaily.com/quick-fixes-for-why-is-my-honor-magic-vs-2-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Honor Magic Vs 2 Black and White | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/score-a-steam-machines-dream-999-gaming-pc-with-high-end-graphics-and-speedy-processor-by-cyberpower/"><u>Score a Steam Machines Dream: $999 Gaming PC with High-End Graphics and Speedy Processor by CyberPower.</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-review-ultimate-computer-hardware-analysis/"><u>Tom's Tech Review: Ultimate Computer Hardware Analysis</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-some-outdated-hardware-drivers-on-windows-11-and-10-and-7-by-drivereasy-guide/"><u>Use Device Manager to identify some outdated hardware drivers on Windows 11 & 10 & 7</u></a></li>
</ul></div>
