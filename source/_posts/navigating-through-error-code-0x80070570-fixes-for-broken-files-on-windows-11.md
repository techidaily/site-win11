---
title: "Navigating Through Error Code 0X80070570: Fixes for Broken Files on Windows 11"
date: 2024-12-04T02:09:54.967Z
updated: 2024-12-06T16:45:23.423Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating Through Error Code 0X80070570: Fixes for Broken Files on Windows 11"
excerpt: "This Article Describes Navigating Through Error Code 0X80070570: Fixes for Broken Files on Windows 11"
keywords: WinErrorCodeFix0x70570,FileCorruptionWindows11,Error0X70570Solution,BrokenFilesRepairTips,Windows11FileError,0X80070570Troubleshoot,Fix0X70570Errors
thumbnail: https://thmb.techidaily.com/70a221261e83ff3179ef93192d51afbff1f7257579ffa960f9e7a085032e4b04.png
---

## Navigating Through Error Code 0X80070570: Fixes for Broken Files on Windows 11

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/rBnnLFJbvr4?si=LlHYrYlOBp7NLMec" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-the-ultimate-guide-to-cropped-video-content-on-instagram/"><u>[New] In 2024, The Ultimate Guide to Cropped Video Content on Instagram</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-mastering-the-name-game-for-top-podcast-titles/"><u>[Updated] 2024 Approved Mastering the Name Game for Top Podcast Titles</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-transform-photos-with-ease-using-basic-adobe-tools/"><u>[Updated] Transform Photos with Ease Using Basic Adobe Tools</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-youtubes-income-leap-at-500-subs-count/"><u>2024 Approved YouTube's Income Leap at 500 Subs Count</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-samsung-galaxy-s23-tactical-edition-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Samsung Galaxy S23 Tactical Edition</u></a></li>
<li><a href="https://win11.techidaily.com/diving-deep-into-drive-space-analysis-using-windows-diskusage-command/"><u>Diving Deep Into Drive Space Analysis Using Windows DiskUsage Command</u></a></li>
<li><a href="https://win11.techidaily.com/embrace-the-new-normal-resize-your-desktops-taskbar-images/"><u>Embrace the New Normal: Resize Your Desktop's Taskbar Images</u></a></li>
<li><a href="https://driver-install.techidaily.com/get-tp-links-wireless-adapter-software-for-windows-gratis/"><u>Get TP-Link's Wireless Adapter Software for Windows Gratis</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-another-computer-is-using-the-printer-error-on-windows-11-and-11/"><u>How to Fix the “Another Computer Is Using the Printer” Error on Windows 11 & 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-google-pixel-8-pro-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Google Pixel 8 Pro Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/keybinding-innovations-for-text-paste-sniping/"><u>Keybinding Innovations for Text Paste Sniping</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-charge-alerts-for-windows-devices/"><u>Mastering Charge Alerts for Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-deleting-windows-arp-cache-126-chars-exceeds-limit-adjusted-to-fit-better-windows-arp-clear-guide/"><u>Mastering the Art of Deleting Windows ARP Cache (126 Chars, Exceeds Limit, Adjusted to Fit Better: Windows ARP Clear Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-complexity-of-security-faults/"><u>Navigating Through the Complexity of Security Faults</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-maze-of-multimonitors-in-windows-11/"><u>Navigating Through The Maze Of Multimonitors In Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-ultimate-iphone-guide-for-shooting-hdr-photos/"><u>The Ultimate iPhone Guide for Shooting HDR Photos</u></a></li>
<li><a href="https://driver-install.techidaily.com/windows-10-sound-troubleshooting-start-with-driver-reinstall/"><u>Windows 10 Sound Troubleshooting: Start with Driver Reinstall</u></a></li>
</ul></div>

