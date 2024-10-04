---
title: "Winning the Battle Against File Error 0X80070570: Fix Guide for Windows 11"
date: 2024-09-29T01:29:43.852Z
updated: 2024-10-03T22:49:15.609Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Winning the Battle Against File Error 0X80070570: Fix Guide for Windows 11"
excerpt: "This Article Describes Winning the Battle Against File Error 0X80070570: Fix Guide for Windows 11"
keywords: Win2FileErrorFix,Windows11ErrorSolve,XP70CorrectGuide,FileErrorXP0x70Win,Error0X70WindowsCure,0X80070570FIX,Win11FileErrorResolve
thumbnail: https://thmb.techidaily.com/bc72bcdc29440f3559a7ac3b3d313c8c685d10379af7ea84f2fb960950ffa85c.jpg
---

## Winning the Battle Against File Error 0X80070570: Fix Guide for Windows 11

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
<a href="https://versadesk.pxf.io/c/5597632/1828647/21290" target="_top" id="1828647">
  <img src="//a.impactradius-go.com/display-ad/21290-1828647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1828647/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094421/7443" target="_top" id="2094421">
  <img src="//a.impactradius-go.com/display-ad/7443-2094421" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094421/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148644/16836" target="_top" id="2148644">
  <img src="//a.impactradius-go.com/display-ad/16836-2148644" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148644/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.

4. Input your user account password.
5. Select **Continue** to initiate the repair.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006941/19272" target="_top" id="2006941">
  <img src="//a.impactradius-go.com/display-ad/19272-2006941" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006941/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-strategies-for-effective-ppt-sharing-in-google-meet-sessions/"><u>[New] 2024 Approved Strategies for Effective PPT Sharing in Google Meet Sessions</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-instagram-engagement-game-changers-the-top-25-hashtags-you-need/"><u>[Updated] 2024 Approved Instagram Engagement Game-Changers The Top 25 Hashtags You Need</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-expert-analysis-top-5-high-end-recording-apps/"><u>[Updated] In 2024, Expert Analysis Top 5 High-End Recording Apps</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-the-pinnacle-of-photography-top-ten-camera-lens-selections-2024/"><u>[Updated] The Pinnacle of Photography Top Ten Camera Lens Selections 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/behance-portfolio-image-constraints-for-2024/"><u>Behance Portfolio Image Constraints for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/deciph-written-by-your-name/"><u>Deciph Written by [Your Name]</u></a></li>
<li><a href="https://howto.techidaily.com/fix-zte-axon-40-lite-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix ZTE Axon 40 Lite Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-hp-officejet-pro-abd-device-drivers-for-your-windows-pc/"><u>Get the Latest HP OfficeJet Pro Abd Device Drivers for Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/hush-the-language-indicator-on-win11s-status-ui/"><u>Hush the Language Indicator on Win11’s Status UI</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-disabled-apple-iphone-6ipad-without-computer-by-drfone-ios/"><u>In 2024, How to Unlock Disabled Apple iPhone 6/iPad Without Computer</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-java-install-process-on-your-windows-pc/"><u>Mastering Java Install Process on Your Windows PC</u></a></li>
<li><a href="https://youtube-web.techidaily.com/g-the-upside-down-inventive-techniques-to-rewind-yt-media/"><u>Seeing the Upside Down Inventive Techniques to Rewind YT Media</u></a></li>
<li><a href="https://win11.techidaily.com/unfreeze-windows-hibernate-with-simple-steps/"><u>Unfreeze Windows Hibernate with Simple Steps</u></a></li>
</ul></div>

