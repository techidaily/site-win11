---
title: "Demystifying Windows Error X70: Your Path to Data Recovery"
date: 2024-10-12T21:45:19.608Z
updated: 2024-10-15T22:36:51.092Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Demystifying Windows Error X70: Your Path to Data Recovery"
excerpt: "This Article Describes Demystifying Windows Error X70: Your Path to Data Recovery"
keywords: Fixing X70 in Windows,Error X70 Solution,Windows X70 Recovery,Restoring Lost Files,Avoiding Data Loss X70,X70 Windows Troubleshoot,Secure Data After X70
thumbnail: https://thmb.techidaily.com/97b5d85adaa70d7cf066a732f43c0486f51d36a4ba60d02434a07b91f944e872.jpg
---

## Demystifying Windows Error X70: Your Path to Data Recovery

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135355/19272" target="_top" id="2135355">
  <img src="//a.impactradius-go.com/display-ad/19272-2135355" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135355/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135372/19272" target="_top" id="2135372">
  <img src="//a.impactradius-go.com/display-ad/19272-2135372" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135372/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151854/7443" target="_top" id="2151854">
  <img src="//a.impactradius-go.com/display-ad/7443-2151854" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151854/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.
4. Input your user account password.
5. Select **Continue** to initiate the repair.

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972665/19272" target="_top" id="1972665">
  <img src="//a.impactradius-go.com/display-ad/19272-1972665" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972665/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-non-vimeo-powerhouses-for-video-content-creation-for-2024/"><u>[New] Non-Vimeo Powerhouses for Video Content Creation for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-explore-new-territory-your-guide-to-live-streaming-tiktoks/"><u>[Updated] 2024 Approved Explore New Territory Your Guide to Live-Streaming TikToks</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-the-best-10-pc-cameras-and-recording-software-on-win-10/"><u>[Updated] 2024 Approved The Best 10 PC Cameras & Recording Software on Win 10</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-a-beginners-guide-to-jujutsu-kaisen-on-tiktok/"><u>[Updated] In 2024, A Beginner’s Guide to Jujutsu Kaisen on TikTok</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-unleashing-potential-the-instagram-success-story-guide-for-2024/"><u>[Updated] Unleashing Potential - The Instagram Success Story Guide for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-speedy-precision-the-leading-video-control-software/"><u>2024 Approved Speedy Precision The Leading Video Control Software</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-ultimate-soundscape-creators-for-immersive-video-streaming/"><u>2024 Approved Ultimate Soundscape Creators for Immersive Video Streaming</u></a></li>
<li><a href="https://win-great.techidaily.com/correcting-file-corruption-on-your-windows-10-pc-detection-and-repair-tactics/"><u>Correcting File Corruption on Your Windows 10 PC: Detection and Repair Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-updater-fails-code-x80246007-for-w1011/"><u>Eliminating Updater Fails: Code X80246007 for W10/11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-avi-files-of-realme-gt-neo-5-se-with-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and AVI files of Realme GT Neo 5 SE with Video Repair Utility on Mac?</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-pokemon-unite-a-beginners-guide-to-excellence/"><u>Mastering Pokémon Unite: A Beginner's Guide to Excellence</u></a></li>
<li><a href="https://win11.techidaily.com/method-to-release-restricted-app-on-pc/"><u>Method to Release Restricted App on PC</u></a></li>
<li><a href="https://win11.techidaily.com/oled-asus-s15-review-pure-stealth-in-design-durability-ensured/"><u>OLED Asus S15 Review: Pure Stealth in Design, Durability Ensured</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-cortana-activation-in-windows-11/"><u>Preventing Cortana Activation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-steam-login-issues/"><u>Resolving Windows Steam Login Issues</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-editability-in-win-folders-with-ease/"><u>Resurrecting Editability in Win Folders with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-tutorial-mastery-of-component-services-on-w11/"><u>Step-By-Step Tutorial: Mastery of Component Services on W11</u></a></li>
<li><a href="https://win11.techidaily.com/title-optimizing-desktop-icon-placement-in-windows-xp-to-z/"><u>Title: Optimizing Desktop Icon Placement in Windows XP to Z</u></a></li>
<li><a href="https://win11.techidaily.com/tomorrows-os-reimagining-windows-post-11/"><u>Tomorrow’s OS: Reimagining Windows Post-11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    