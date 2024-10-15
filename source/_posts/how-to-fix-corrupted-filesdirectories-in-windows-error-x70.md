---
title: How to Fix 'Corrupted' Files/Directories in Windows (Error X70)
date: 2024-10-11T18:31:47.099Z
updated: 2024-10-15T22:56:47.204Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix 'Corrupted' Files/Directories in Windows (Error X70)
excerpt: This Article Describes How to Fix 'Corrupted' Files/Directories in Windows (Error X70)
keywords: Windows Corrupted Files Solution,X70 Error File Repair,Fixing Windows Directory Errors,Windows X70 File Troubleshoot,Error X70 File Recovery,Reversing Windows Data Errors,Eradicating Error X70 in Windows
thumbnail: https://thmb.techidaily.com/0a4429b41076dffc8b778c6281e805f6a7937a0d2383fe5591ff482b234f870f.jpg
---

## How to Fix 'Corrupted' Files/Directories in Windows (Error X70)

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144277/7443" target="_top" id="2144277">
  <img src="//a.impactradius-go.com/display-ad/7443-2144277" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144277/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134492/18498" target="_top" id="2134492">
  <img src="//a.impactradius-go.com/display-ad/18498-2134492" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134492/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139111/17108" target="_top" id="2139111">
  <img src="//a.impactradius-go.com/display-ad/17108-2139111" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139111/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-lab.techidaily.com/kyrocketing-view-figures-by-sustaining-youtubes-creative-commons-license-for-2024/"><u>[New] Skyrocketing View Figures by Sustaining YouTube's Creative Commons License for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-essential-tips-for-smooth-youtube-content-trimming-for-2024/"><u>[Updated] Essential Tips for Smooth YouTube Content Trimming for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-iconic-image-reimagining-tools-visualmorph-v2/"><u>[Updated] Iconic Image Reimagining Tools VisualMorph V2</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-breaking-down-snapchats-new-highlight-functionality/"><u>2024 Approved Breaking Down Snapchat's New Highlight Functionality</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/collaborative-creativity-unleashed-the-definitive-guide-to-mastering-tiktok-duets/"><u>Collaborative Creativity Unleashed: The Definitive Guide to Mastering TikTok Duets</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-unaltered-screenscape-in-windows-11/"><u>Guide to Unaltered Screenscape in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-discord-installation-has-failed-error-on-windows-11-and-11/"><u>How to Fix the Discord “Installation Has Failed” Error on Windows 11 & 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-books-unlocking-potential-with-7-top-study-methods-on-a-windowed-computer/"><u>Master the Books: Unlocking Potential with 7 Top Study Methods on a Windowed Computer</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-excessive-heat-on-windows-11-devices/"><u>Mitigating Excessive Heat on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-error-0x80041015-in-ms-word-and-excel/"><u>Quick Fixes for Error 0X80041015 in MS Word & Excel</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-fabricated-device-specification-error-in-win-11/"><u>Rectifying Fabricated Device Specification Error in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-1011-uninstalls-that-fail/"><u>Resolving Windows 10/11 Uninstalls That Fail</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functionality-to-your-corrupted-windows-11-trash/"><u>Restoring Functionality to Your Corrupted WIndows 11 Trash</u></a></li>
<li><a href="https://fox-direct.techidaily.com/the-best-of-the-best-yts-premier-unboxing-sites-for-2024/"><u>The Best of the Best YT's Premier Unboxing Sites for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-reviews-the-definitive-source-for-hardware-evaluations/"><u>Tom's Reviews: The Definitive Source for Hardware Evaluations</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-10-best-free-email-services-for-your-online-communication-needs/"><u>Top 10 Best Free Email Services for Your Online Communication Needs</u></a></li>
</ul></div>

