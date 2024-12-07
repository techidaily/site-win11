---
title: Resolving Windows 11'S Corrupted Files Error 0X80070570
date: 2024-12-04T22:15:31.329Z
updated: 2024-12-06T16:21:47.631Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Windows 11'S Corrupted Files Error 0X80070570
excerpt: This Article Describes Resolving Windows 11'S Corrupted Files Error 0X80070570
keywords: Windows 11 Corruption Fix,0X80070570 File Error,Win11 Error Repair,XT700 Error Resolution,0X700 Files Fixing Guide,0X8070570 Windows Troubleshooting,Corrupted Files in Win11
thumbnail: https://thmb.techidaily.com/63eaa39ba6f901f19dd5d6107e02d0bfc04195c0f440f8e4bb186694932a1b6e.jpg
---

## Resolving Windows 11'S Corrupted Files Error 0X80070570

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-elevating-visuals-with-hdr-excellence-in-photoshop/"><u>[New] 2024 Approved Elevating Visuals with HDR Excellence in Photoshop</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-efficient-thumbnail-generation-with-your-phone-for-video-content/"><u>[Updated] In 2024, Efficient Thumbnail Generation with Your Phone for Video Content</u></a></li>
<li><a href="https://driver-download.techidaily.com/asus-ac68-usb-wireless-router-driver-secure-download-links/"><u>ASUS AC68 USB Wireless Router Driver - Secure Download Links!</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-max-and-min-cpu-in-power-settings-labyrinth/"><u>Exploring Max & Min CPU in Power Settings Labyrinth</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-service-not-started-for-virtual-disks-on-pc/"><u>Fixing Service Not Started for Virtual Disks on PC</u></a></li>
<li><a href="https://tech-revival.techidaily.com/get-ahead-of-the-pack-with-these-7-free-ai-driven-trip-planning-tools-no-booking-hassle/"><u>Get Ahead of the Pack with These 7 Free AI-Driven Trip Planning Tools - No Booking Hassle</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-13-mini-to-other-iphone-14-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 13 mini to other iPhone 14 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/key-uses-for-visual-cplusplus-redistribution/"><u>Key Uses for Visual C++ Redistribution</u></a></li>
<li><a href="https://fox-access.techidaily.com/masterclass-in-merging-movies-with-modern-education/"><u>Masterclass in Merging Movies with Modern Education</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-input-methods-and-keyboard-setups-for-win-11-users/"><u>Optimize Input Methods and Keyboard Setups for Win 11 Users</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/overcoming-missing-winhttpdll-errors-essential-troubleshooting-techniques/"><u>Overcoming Missing Winhttp.dll Errors: Essential Troubleshooting Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-addressing-no-such-file-or-directory-errors/"><u>Strategies for Addressing 'No Such File or Directory' Errors</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-update-windows-11-admin-identity-and-role/"><u>Strategies to Update Windows 11 Admin Identity and Role</u></a></li>
<li><a href="https://extra-tips.techidaily.com/tailoring-medical-messages-in-social-media-ads/"><u>Tailoring Medical Messages in Social Media Ads</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-6-appsservices-to-trace-any-xiaomi-redmi-note-12t-pro-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>Top 6 Apps/Services to Trace Any Xiaomi Redmi Note 12T Pro Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-aw-snap-error-in-google-chrome-on-winos/"><u>Troubleshooting “Aw, Snap!” Error in Google Chrome on WinOS</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    