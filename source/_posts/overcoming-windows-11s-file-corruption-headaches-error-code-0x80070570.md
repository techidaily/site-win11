---
title: Overcoming Windows 11'S File Corruption Headaches (Error Code 0X80070570)
date: 2024-11-14T23:12:49.709Z
updated: 2024-11-17T19:49:31.789Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Windows 11'S File Corruption Headaches (Error Code 0X80070570)
excerpt: This Article Describes Overcoming Windows 11'S File Corruption Headaches (Error Code 0X80070570)
keywords: Win11FileCorruptHeadache,ErrorCode0x80070570Solve,WindowsFileErrorX070570,CorruptionErrorWin11,FixWindowsError070570,Win11DataIntegrityError,ResolveX8070570Win
thumbnail: https://thmb.techidaily.com/46162ff1d50cb6f1b35f044048a0b2464ebecd738e59505ca40bf7c4a2c48673.png
---

## Overcoming Windows 11'S File Corruption Headaches (Error Code 0X80070570)

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
<a href="https://aligracehair.sjv.io/c/5597632/1959773/19272" target="_top" id="1959773">
  <img src="//a.impactradius-go.com/display-ad/19272-1959773" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959773/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123729/7443" target="_top" id="2123729">
  <img src="//a.impactradius-go.com/display-ad/7443-2123729" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123729/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880972/19272" target="_top" id="1880972">
  <img src="//a.impactradius-go.com/display-ad/19272-1880972" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880972/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-clips.techidaily.com/new-navigating-twitters-reaction-videos-explained/"><u>[New] Navigating Twitter's Reaction Videos Explained</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-enhance-snapchat-stories-with-these-top-6-mobile-editors-for-2024/"><u>[Updated] Enhance Snapchat Stories with These Top 6 Mobile Editors for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-innovative-igtv-editor-apps-for-creative-vertical-content/"><u>[Updated] In 2024, Innovative IGTV Editor Apps for Creative Vertical Content</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-professionals-complete-handbook-to-fcp-mastery/"><u>[Updated] Professional's Complete Handbook to FCP Mastery</u></a></li>
<li><a href="https://extra-resources.techidaily.com/clearing-photos-expert-background-takedown-in-photopea-for-2024/"><u>Clearing Photos Expert Background Takedown in Photopea for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-pc-skills-with-these-5-cmd-tricks/"><u>Elevate Your PC Skills with These 5 Cmd Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-steam-faster-pace-preventing-sudden-drops-in-speed/"><u>Enhancing Steam Faster Pace: Preventing Sudden Drops in Speed</u></a></li>
<li><a href="https://win11.techidaily.com/forceful-deletion-of-windows-11-printers-explained/"><u>Forceful Deletion of Windows 11 Printers Explained</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-initiate-wordpad-functionality-in-windows/"><u>Guide to Initiate WordPad Functionality in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-erase-the-imprint-of-epic-games-hub-on-w11/"><u>How to Erase the Imprint of Epic Games Hub on W11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-infinix-smart-7-hd-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Infinix Smart 7 HD FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11.techidaily.com/masterclass-in-efficiency-10-essential-windows-apps/"><u>Masterclass in Efficiency: 10 Essential Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-freeze-tips-for-resource-monitors-on-windows-11/"><u>Overcoming the Freeze: Tips for Resource Monitors on Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/student-tech-perks-securing-affordable-microsoft-products-through-educational-savings/"><u>Student Tech Perks: Securing Affordable Microsoft Products Through Educational Savings</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-to-prevent-not-working-on-your-pc/"><u>Swift Solutions to Prevent 'Not Working' On Your PC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-premier-manual-for-subtitle-precision-via-web-resources-for-2024/"><u>The Premier Manual for Subtitle Precision via Web Resources for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-overturning-personalised-windows-11-search/"><u>Tutorial: Overturning Personalised Windows 11 Search</u></a></li>
</ul></div>

