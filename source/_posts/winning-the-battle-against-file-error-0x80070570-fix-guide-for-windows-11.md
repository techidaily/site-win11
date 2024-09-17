---
title: "Winning the Battle Against File Error 0X80070570: Fix Guide for Windows 11"
date: 2024-09-11T05:40:24.651Z
updated: 2024-09-17T02:50:37.554Z
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

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135409/19272" target="_top" id="2135409">
  <img src="//a.impactradius-go.com/display-ad/19272-2135409" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135409/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139119/17108" target="_top" id="2139119">
  <img src="//a.impactradius-go.com/display-ad/17108-2139119" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139119/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115924/19272" target="_top" id="2115924">
  <img src="//a.impactradius-go.com/display-ad/19272-2115924" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115924/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Input your user account password.
5. Select **Continue** to initiate the repair.

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/updated-harnessing-the-power-of-software-for-seamless-vimeo-video-downloads-for-2024/"><u>[Updated] Harnessing the Power of Software for Seamless Vimeo Video Downloads for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/44cm44kk44oz44k44o844on44od44oi44gl44kj5yuv55s744ks44kt44oj44ox44ob44oj44gz44kl44gf44kb44gu44k544og44od44ox44oq44kk44k544og44od44ox44ks44kk44oj44cn/"><u>「インターネットから動画をキャプチャするためのステップバイステップガイド」</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-seamless-stories-from-the-past-accessing-older-fb-content-on-pcmobile/"><u>2024 Approved Seamless Stories From The Past Accessing Older FB Content on PC/Mobile</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-honor-100-pro-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-simple-guide-converting-stunning-hdr-videos-into-compatible-sdr-format/"><u>A Simple Guide: Converting Stunning HDR Videos Into Compatible SDR Format</u></a></li>
<li><a href="https://win11.techidaily.com/can-i-trust-online-video-conversion-services-understanding-their-security-risks-and-benefits/"><u>Can I Trust Online Video Conversion Services? Understanding Their Security Risks and Benefits</u></a></li>
<li><a href="https://win11.techidaily.com/clipchampgif/"><u>Clipchampによる簡単なGIF制作手順とヒント:動画から始めましょう!</u></a></li>
<li><a href="https://fox-that.techidaily.com/guide-performing-apples-remote-diagnostics-on-iphone-hardware/"><u>Guide: Performing Apple's Remote Diagnostics on iPhone Hardware</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Realme Narzo 60 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/key-techniques-for-smooth-inshot-pivots-for-2024/"><u>Key Techniques for Smooth Inshot Pivots for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/44oh44oh44kj44ki44ov44kh44kk44or566h55cg44gr54m55yyw44gx44gf44gv44gplus44gw44gplus44gq44k944ov44oi44km44kn44ki44o744oe44o844or44go44ki44ox44oq44kx44o844k34490/"><u>メディアファイル管理に特化したさまざまなソフトウェア・ツールとアプリケーションを紹介する</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    