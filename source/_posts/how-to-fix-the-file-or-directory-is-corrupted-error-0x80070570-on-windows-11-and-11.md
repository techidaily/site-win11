---
title: How to Fix the “File or Directory Is Corrupted” Error 0X80070570 on Windows 11 & 11
date: 2024-09-11T09:44:56.317Z
updated: 2024-09-12T09:44:56.317Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the “File or Directory Is Corrupted” Error 0X80070570 on Windows 11 & 11
excerpt: This Article Describes How to Fix the “File or Directory Is Corrupted” Error 0X80070570 on Windows 11 & 11
keywords: WinErrorCode0X80070570Repair,Windows11FileCorruptionFix,FixedDirErrorWindows11,Error0X80070570Resolution,DirectoryErrorSolveWin11,CorruptedFileTroubleshootWin,FixErrorCode0X80070570Win11
thumbnail: https://thmb.techidaily.com/b1dd8faa0beaf2c68ee22b112a11d419910d65751f8e67cea228594ebc93d2a9.jpg
---

## How to Fix the “File or Directory Is Corrupted” Error 0X80070570 on Windows 11 & 11

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
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137201/26400" target="_top" id="2137201">
  <img src="//a.impactradius-go.com/display-ad/26400-2137201" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137201/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<span id="1993645">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993645.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993645">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993645.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993645%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993645/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135364/19272" target="_top" id="2135364">
  <img src="//a.impactradius-go.com/display-ad/19272-2135364" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135364/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118310/7443" target="_top" id="2118310">
  <img src="//a.impactradius-go.com/display-ad/7443-2118310" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118310/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Input your user account password.
5. Select **Continue** to initiate the repair.

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/new-premium-smartphones-shining-in-high-definition-video-for-2024/"><u>[New] Premium Smartphones Shining in High Definition Video for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-can-you-receive-a-monthly-check-from-youtube/"><u>[Updated] In 2024, Can You Receive a Monthly Check From YouTube?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-skype-call-recording-tips-ensuring-clarity-across-platforms/"><u>2024 Approved Skype Call Recording Tips - Ensuring Clarity Across Platforms</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/android-hacks-counterclockwise-video-stream/"><u>Android Hacks Counterclockwise Video Stream</u></a></li>
<li><a href="https://extra-information.techidaily.com/comprehensive-study-editmagics-power-edition/"><u>Comprehensive Study EditMagic's Power Edition</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-reset-count-for-unsuccessful-logins-on-windows-11-systems/"><u>Configuring Reset Count for Unsuccessful Logins on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-geforce-error-x0001-on-windows-devices/"><u>Correcting GeForce Error X0001 on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-screen-snooze-secrets/"><u>Deciphering Window's Screen Snooze Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/decrypting-the-secure-key-conundrum-a-guide-to-five-fixes-for-windows-users/"><u>Decrypting the Secure Key Conundrum: A Guide to Five Fixes for Windows Users</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-how-to-bypass-honor-90-gt-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Honor 90 GT FRP Android 10/11/12/13</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-harmonize-files-on-dual-windows-pcs-using-aoemi/"><u>Effortlessly Harmonize Files on Dual Windows PCs Using AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-windows-app-functionality-enhance-internet-connectivity/"><u>Elevate Windows App Functionality: Enhance Internet Connectivity</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/elevate-your-gaming-with-fbx-capture-pro-for-2024/"><u>Elevate Your Gaming with FBX Capture Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-webp-conversion-by-chrome-on-your-computer/"><u>Eliminate WebP Conversion by Chrome on Your Computer</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-isarcextract-error-a-w11-guide/"><u>Eliminating the ISArcExtract Error: A W11 Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-anthropics-innovative-ai-prompt-store-with-claude-3-technology/"><u>Exploring Anthropic’s Innovative AI Prompt Store with Claude 3 Technology</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-blocked-notification-errors-for-your-pc/"><u>Fixing Blocked Notification Errors for Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-erratic-media-playback-on-pcs/"><u>Fixing Erratic Media Playback on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-wsl-disruptions-after-win-11-rollout/"><u>Fixing WSL Disruptions After Win 11 Rollout</u></a></li>
<li><a href="https://win11.techidaily.com/from-failures-to-functionality-mastery-of-windows-script-repair/"><u>From Failures to Functionality: Mastery of Windows Script Repair</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-the-program-compatibility-troubleshooter-to-the-context-menu-on-windows/"><u>How to Add the Program Compatibility Troubleshooter to the Context Menu on Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/how-to-find-the-optimal-balance-equipment-for-drone-photography/"><u>How To Find the Optimal Balance Equipment for Drone Photography</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-xiaomi-civi-3-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Xiaomi Civi 3 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-force-camera-activation-notification-in-windows-11/"><u>How to Force Camera Activation Notification in Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-nubia-red-magic-9-proplus-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Nubia Red Magic 9 Pro+ Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-nokia-c22-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Nokia C22? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-motorola-razr-40s-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>In 2024, Unlock Your Motorola Razr 40s Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://win11.techidaily.com/insights-gained-from-windows-bsod-memory-logs/"><u>Insights Gained From Windows BSOD Memory Logs</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/maintaining-your-preferred-os-a-guide-to-halting-windows-11-updates-and-remaining-on-windows-10/"><u>Maintaining Your Preferred OS: A Guide to Halting Windows 11 Updates & Remaining on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-network-nooks-how-to-fix-file-transfer-issues-on-win11/"><u>Navigating Network Nooks: How to Fix File Transfer Issues on WIN11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-0x800704cf-problem-in-windows-microsoft-store/"><u>Overcoming 0X800704CF Problem in Windows' Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/ranking-windows-finest-encrypted-software-choices-149-chars/"><u>Ranking Windows' Finest Encrypted Software Choices (149 Chars)</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolved-ultimate-guide-to-eliminate-fortnite-latency-problems/"><u>Resolved: Ultimate Guide to Eliminate Fortnite Latency Problems</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-folder-access-denied-issue-in-microsoft-outlook-for-pcs/"><u>Resolving Folder Access Denied Issue in Microsoft Outlook for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/strengthening-the-synergy-between-wsl-and-windows-11-ecosystems/"><u>Strengthening the Synergy Between WSL and Windows 11 Ecosystems</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-windows-ssds-synchronize-with-ssfresh-tactics/"><u>Supercharge Windows SSDs: Synchronize with SSFresh Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-correcting-transfer-problems-with-windows-usb-drives/"><u>Techniques for Correcting Transfer Problems with Windows USB Drives</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-sustainable-wlanextexe-operation/"><u>Techniques for Sustainable WLANEXT.EXE Operation</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-windows-11s-volume-control-setup/"><u>The Essentials of Windows 11’S Volume Control Setup</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-rejuvenating-non-starting-adobe/"><u>The Ultimate Guide to Rejuvenating Non-Starting Adobe</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-taskbar-absence-with-maximized-edges/"><u>Troubleshooting Taskbar Absence with Maximized Edges</u></a></li>
<li><a href="https://win11.techidaily.com/turn-your-laptop-or-desktop-into-a-wireless-internet-source/"><u>Turn Your Laptop or Desktop Into a Wireless Internet Source</u></a></li>
<li><a href="https://win11.techidaily.com/uncover-9-steps-to-mastering-volume-controls-in-windows-11/"><u>Uncover 9 Steps to Mastering Volume Controls in Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/unlocking-power-of-index-effortless-strategies-for-data-retrieval-in-excel-spreadsheets/"><u>Unlocking Power of INDEX: Effortless Strategies for Data Retrieval in Excel Spreadsheets</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secure-tests-with-win-11s-sandbox/"><u>Unlocking Secure Tests with Win 11'S Sandbox</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-true-potential-of-windows-11-the-best-changes-to-make/"><u>Unlocking the True Potential of Windows 11: The Best Changes to Make</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-old-pcs-steps-to-windows-11-22h2/"><u>Upgrading Old PCs: Steps to Windows 11 22H2</u></a></li>
<li><a href="https://win11.techidaily.com/windows-shuttering-your-essential-knowledge-pool/"><u>Windows Shuttering: Your Essential Knowledge Pool</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    