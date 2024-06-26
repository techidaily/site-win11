---
title: Steps for Eradicating System Call Failed Problem in Windows 11
date: 2024-06-25T11:30:47.746Z
updated: 2024-06-26T11:30:47.746Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Eradicating System Call Failed Problem in Windows 11
excerpt: This Article Describes Steps for Eradicating System Call Failed Problem in Windows 11
keywords: WINDOWS_SysCallErrorSolution,FixingSystemCallsInWin11,EradicateWindowsCallFailures,Windows11SyscallFailureTroubleshooting,ResolveSyscallIssuesWin11,EliminateSystemCallErrorWin11,CorrectingFailedCallsWindows11
thumbnail: https://thmb.techidaily.com/f8ecdc6c33144a8756139b14ccc37972ba5fac5122e75e4781350dfcc5ba234f.jpg
---

## Steps for Eradicating System Call Failed Problem in Windows 11

 The “system call failed” error message is a common error that usually pops up when you try to open File Explorer. However, this error message can also affect the Start menu. When this error occurs, you cannot access File Explorer or other Windows features affected by this error.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

## 1\. Restart Windows File Explorer

![The Processes tab in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-restart-option2.jpg)

 Restarting the explorer.exe process can fix the “System call failed” error. It's a really easy and quick fix, so it's a good starting point for troubleshooting the “system call failed” error.

 You can restart the explorer.exe process with Task Manager, as covered in this guide on [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).

## 2\. Run the SFC and DISM Tools in Command Prompt

![Windows System File Checker tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow.jpg)

 Corrupted system files could be causing File Explorer to crash. As such, it's worth running the System File Checker (SFC). This tool is a Windows Command-Prompt utility that checks for and repairs system files.

 On top of that, the Deployment Image Serving and Management (DISM) tool can fix errors within the Windows system image. It's worth running the DISM tool before the SFC scan to check for any errors that may affect the SFC scan's efficiency.

 You can learn how to run both the SFC and DISM commands in our guide to [repairing system files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

## 3\. Check For Disk Errors With CHKDSK

 A failing hard drive is another potential cause of the “system call failed” error. You can check for and repair disk errors with the Check Disk (CHKDSK) tool on Windows.

 Our [how to run CHKDSK](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) guide explains how you can utilize the Check Disk tool.

## 4\. Initiate a Malwarebytes Scan

 Malware can cause many kinds of crashes to occur on Windows. The “system call failed” error could be occurring because of malware on your PC.

 You can scan for malware with many antivirus apps, including Windows Security. However, Malwarebytes is one of the [best free antivirus software for Windows](https://www.makeuseof.com/tag/ten-best-antivirus-programs/). So, try running a Malwarebytes scan like this:

1. Go to the [Malwarebytes download page](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2028435/https://www.malwarebytes.com/mwb-download) and download the tool from there.
2. Open the **MBSetup** file from your Downloads folder and click **Install**.
3. Next, click **Skip** if you don’t want to install the additional software offered.
4. Select **Open Malwarebytes** to run the software.
5. Click **Scan** to initiate a malware scan.  
![The Scan option in Malwarebytes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-scan-option.jpg)
6. Select **Quarantine** and **Yes** if Malwarebytes detects malware.

## 5\. Disable Startup Items and Services With a Clean Boot

 Another possibility is that a third-party program or service is conflicting or interfering with the File Explorer processing, causing the “System call failed” error to occur on your PC.

 You can address a software conflict by disabling all third-party startup items and services, which is otherwise the clean booting troubleshooting method. You can apply that troubleshooting method by following the instructions in this guide on [performing a clean boot in Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/).

 Restart your PC when you’ve disabled all third-party startup items and services. Then try opening File Explorer again to check if this “System call failed” error continues.

 If the error is fixed after clean booting, it will probably reoccur if you re-enable all startup apps and services again. You can try to identify what’s causing the error by gradually re-enabling items, and then disabling the startup app or service that triggers the issue again.

![Services tab on Windows Configuration menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab5.jpg)

## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)

## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

## Get the “System Call Failed” Error Fixed

 Those “System call failed” error solutions are confirmed to work by many users who have needed to resolve that File Explorer issue.

 So, it’s very likely one will solve that issue, so you can fully utilize File Explorer again. If none of those resolutions are enough, consider contacting the Microsoft Windows support service for further guidance.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/optimize-your-legacy-computer-for-windows-11-via-to-go-and-rufus/"><u>Optimize Your Legacy Computer for Windows 11 via To Go & Rufus</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-solving-the-failure-errors-in-discord-installation/"><u>Decoding and Solving the Failure Errors in Discord Installation</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-requires-elevation-puzzle-win-11s-error-740-solution/"><u>Unraveling the Requires Elevation Puzzle: Win 11'S Error #740 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-tracking-disk-space-usage-in-windows-pcs/"><u>The Ultimate Guide to Tracking Disk Space Usage in Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-full-screen-display-defeating-windows-overscan/"><u>Optimize Full-Screen Display: Defeating Windows Overscan</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-an-offline-windows-update-plan/"><u>Crafting an Offline Windows Update Plan</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-network-link-disruptions-in-winmc-minecraft/"><u>Tackling Network Link Disruptions in WinMC Minecraft</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionary-driver-solutions-at-no-cost-to-optimize-windows-cars/"><u>Revolutionary Driver Solutions at No Cost to Optimize Windows Cars</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-shortage-of-usb-interface-points-in-windows/"><u>Fixing Shortage of USB Interface Points in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719271419179-navigate-through-windows-woes-with-simple-fixes/"><u>Navigate Through Windows Woes with Simple Fixes!</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-s-top-rated-free-video-editors-for-32-bit-windows-users/"><u>2024 Approved S Top-Rated Free Video Editors for 32-Bit Windows Users</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-dive-into-digital-friendship-start-your-facebook-journey/"><u>[New] Dive Into Digital Friendship  Start Your Facebook Journey</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-everlasting-deactivation-tactics-against-youtubes-sneaky-snack/"><u>[Updated] 2024 Approved  Everlasting Deactivation Tactics Against YouTube's Sneaky Snack</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-stream-without-interruptions-fix-mobile-video-problems/"><u>[New] In 2024, Stream Without Interruptions - Fix Mobile Video Problems</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-5-key-strategies-for-professional-looking-screenshots-for-2024/"><u>[Updated] 5 Key Strategies for Professional-Looking Screenshots for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-spark-ar-visual-upgrades-the-role-of-downloadable-luts-in-development/"><u>[Updated] In 2024, Spark AR Visual Upgrades  The Role of Downloadable LUTs in Development</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-beauty-bliss-essential-tutorials-for-ultimate-style/"><u>In 2024, Beauty Bliss  Essential Tutorials for Ultimate Style</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-nokia-c02-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Nokia C02 Phones with/without a PC</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-a-compreshift-guide-to-creating-profitable-and-engaging-youtube-collaborations/"><u>[Updated] A Compreshift Guide to Creating Profitable & Engaging YouTube Collaborations</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-identifying-replica-soundscapes-for-rusty-fins-whistle-for-2024/"><u>Updated Identifying Replica Soundscapes for Rusty Fins Whistle for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>