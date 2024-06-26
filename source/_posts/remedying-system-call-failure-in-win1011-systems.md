---
title: Remedying System Call Failure in Win10/11 Systems
date: 2024-06-25T10:16:39.966Z
updated: 2024-06-26T10:16:39.966Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedying System Call Failure in Win10/11 Systems
excerpt: This Article Describes Remedying System Call Failure in Win10/11 Systems
keywords: Fix Windows Call Issues,Solve OS System Errors,Remedy Windows Signal Failures,Resolve Kernel Calls Errors,Rectify Win10/11 Signals,Correct System Call Faults,Address Win10/11 Call Problems
thumbnail: https://thmb.techidaily.com/b55c24263d5a9a2d0075e95ed2cba33cc134d0a45b0aad772e33e1d818e77a97.jpg
---

## Remedying System Call Failure in Win10/11 Systems

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
<li><a href="https://win11.techidaily.com/steering-clear-of-fullscreen-failures-with-sonic-adventure-w11-edition/"><u>Steering Clear of Fullscreen Failures with Sonic Adventure, W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/the-top-9-reasons-to-favor-pc-computing-over-macos/"><u>The Top 9 Reasons to Favor PC Computing Over MacOS</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-rectify-erroneous-device-listings-in-windows/"><u>Guidelines to Rectify Erroneous Device Listings in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-11-making-ai-images-with-paint-tool-sai/"><u>Transform Windows 11: Making AI Images with Paint Tool SAI</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-hello-authentication-compatibility-issue/"><u>Remedying Windows Hello Authentication Compatibility Issue</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-access-to-windows-odbc-settings/"><u>Mastering Access to Windows' ODBC Settings</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-stalled-resource-monitors-procedure-in-windows-11/"><u>Streamlining Stalled Resource Monitors: Procedure in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-out-windows-11-drag-and-drop-issues/"><u>Smooth Out Windows 11 Drag-and-Drop Issues</u></a></li>
<li><a href="https://win11.techidaily.com/from-problem-to-perfection-tactics-to-install-missing-features-in-windows-11-and-11-pro/"><u>From Problem to Perfection: Tactics to Install Missing Features in Windows 11 & 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-fix-to-unknown-not-initialized-in-windows/"><u>Step-by-Step Fix to 'Unknown Not Initialized' In Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-mastering-clear-sound-from-partially-silenced-fb-content/"><u>[Updated] Mastering Clear Sound From Partially Silenced Fb Content</u></a></li>
<li><a href="https://change-location.techidaily.com/ipogo-will-be-the-new-ispoofer-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Vivo Y100i Power 5G? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/resolve-your-apple-iphone-8-keeps-asking-for-outlook-password-drfone-by-drfone-ios/"><u>Resolve Your Apple iPhone 8 Keeps Asking for Outlook Password | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/crafting-the-perfect-facebook-video-post-pcandroid-techniques/"><u>Crafting the Perfect Facebook Video Post, PC/Android Techniques</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-curate-content-the-10-best-youtube-video-length-tools/"><u>[New] 2024 Approved  Curate Content  The 10 Best YouTube Video Length Tools</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-how-to-enhancing-your-experience-with-facebooks-lived-in-content/"><u>[Updated] In 2024, How-To  Enhancing Your Experience with Facebook's Lived-In Content</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-perfect-loop-technique-for-all-your-youtube-favorites/"><u>2024 Approved  The Perfect Loop Technique for All Your YouTube Favorites</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-insights-into-instagrams-maxed-out-videos/"><u>[New] 2024 Approved  Insights Into Instagram's Maxed-Out Videos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-a-comprehensive-tutorial-changing-gender-in-social-media-images/"><u>[Updated] 2024 Approved  A Comprehensive Tutorial  Changing Gender in Social Media Images</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/lightning-fast-the-art-of-windows-file-scanning-for-2024/"><u>Lightning-Fast  The Art of Windows File Scanning for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>