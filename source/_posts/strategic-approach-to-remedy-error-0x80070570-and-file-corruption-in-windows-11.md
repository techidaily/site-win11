---
title: Strategic Approach to Remedy Error 0X80070570 & File Corruption in Windows 11
date: 2024-12-04T09:36:21.290Z
updated: 2024-12-06T22:10:01.309Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategic Approach to Remedy Error 0X80070570 & File Corruption in Windows 11
excerpt: This Article Describes Strategic Approach to Remedy Error 0X80070570 & File Corruption in Windows 11
keywords: Fixing 0X80070570 Error,Windows 11 Corruption Remedy,0X80070570 File Issue,Strategic Windows 11 Repair,XP70 Error Windows Fixing Guide,11 Files Restoration Tactics,Overcoming Windows Corruption Error
thumbnail: https://thmb.techidaily.com/fb64d3334f8fecc4f94c1ae3403a6dd894e812df5486b2d51ee08c850ba80fdd.jpg
---

## Strategic Approach to Remedy Error 0X80070570 & File Corruption in Windows 11

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Input your user account password.
5. Select **Continue** to initiate the repair.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-capture.techidaily.com/new-7-tips-for-capturing-live-online-classes-gratis-for-2024/"><u>[New] 7 Tips for Capturing Live Online Classes Gratis for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-digital-dominion-for-techno-gamers-for-2024/"><u>[New] Digital Dominion for Techno Gamers for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-coolest-minecraft-mansion-projects-revealed-for-2024/"><u>[Updated] Coolest Minecraft Mansion Projects Revealed for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-capture-facebook-videos-like-a-pro-select-the-best-firefox-addons-and-downloaders/"><u>2024 Approved Capture Facebook Videos Like a Pro Select the Best Firefox Addons & Downloaders</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unlock-creative-potential-utilizing-luts-to-enhance-video-quality/"><u>2024 Approved Unlock Creative Potential Utilizing LUTs to Enhance Video Quality</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/athenas-articulation-the-evolution-of-hellenic-speech/"><u>Athena’s Articulation: The Evolution of Hellenic Speech</u></a></li>
<li><a href="https://win11.techidaily.com/disable-tracking-of-program-execution-start-in-windows/"><u>Disable Tracking of Program Execution Start in Windows</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-tackling-photo-app-errors-in-windows-11/"><u>In 2024, Tackling Photo App Errors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-for-windows-blue-screen-0x8007007e/"><u>Mastering the Fix for Windows Blue Screen 0X8007007E</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-windows-1110-crashing-video-drivers/"><u>Repairing Windows 11/10 Crashing Video Drivers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-lava-blaze-pro-5g-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-5-deceptive-gpt-tactics/"><u>Top 5 Deceptive GPT Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-lsa-failure-causes-fixes-for-windows/"><u>Understanding LSA Failure Causes, Fixes for Windows</u></a></li>
</ul></div>

