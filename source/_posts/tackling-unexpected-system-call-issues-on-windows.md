---
title: Tackling Unexpected System Call Issues on Windows
date: 2024-09-09T16:05:52.123Z
updated: 2024-09-17T05:02:49.762Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Unexpected System Call Issues on Windows
excerpt: This Article Describes Tackling Unexpected System Call Issues on Windows
keywords: Win System Calls Errors,Fixing SysCalls in Windows,Solving Windows Syscall Fails,Overcoming Windows Call Issues,Windows Call Debugging,Addressing Windows Syscalls,Resolving Windows Unexpected Calls
thumbnail: https://thmb.techidaily.com/596dd6315d1559e3cb5b3aa52b6f2b9825ab34a39bbf16416336b018124bf2bc.jpg
---

## Tackling Unexpected System Call Issues on Windows

 The “system call failed” error message is a common error that usually pops up when you try to open File Explorer. However, this error message can also affect the Start menu. When this error occurs, you cannot access File Explorer or other Windows features affected by this error.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123465/16836" target="_top" id="2123465">
  <img src="//a.impactradius-go.com/display-ad/16836-2123465" border="0" alt="https://techidaily.com" width="80" height="31"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123465/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135474/26400" target="_top" id="2135474">
  <img src="//a.impactradius-go.com/display-ad/26400-2135474" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135474/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the “System Call Failed” Error Fixed

 Those “System call failed” error solutions are confirmed to work by many users who have needed to resolve that File Explorer issue.

 So, it’s very likely one will solve that issue, so you can fully utilize File Explorer again. If none of those resolutions are enough, consider contacting the Microsoft Windows support service for further guidance.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-poll-power-players-leading-electoral-game-reviews/"><u>[New] In 2024, Poll Power Players Leading Electoral Game Reviews</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-expert-voice-memo-solutions-for-ipads-3-picks-for-2024/"><u>[Updated] Expert Voice Memo Solutions for iPads, #3 Picks for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-screen-recorder-showdown-features-and-prices-compared/"><u>[Updated] In 2024, Screen Recorder Showdown Features and Prices Compared</u></a></li>
<li><a href="https://apple-account.techidaily.com/a-step-by-step-guide-to-finding-your-apple-id-from-your-iphone-12-mini-by-drfone-ios/"><u>A Step-by-Step Guide to Finding Your Apple ID From Your iPhone 12 mini</u></a></li>
<li><a href="https://win11.techidaily.com/canva-tutorial-mastering-video-sound-adjustments-eliminating-or-incorporating-audio-seamlessly/"><u>Canva Tutorial: Mastering Video Sound Adjustments - Eliminating or Incorporating Audio Seamlessly</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-download-and-set-up-focusrite-scarlett-2i4-drivers-on-your-windows-computer/"><u>How to Download and Set Up Focusrite Scarlett 2I4 Drivers on Your Windows Computer</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-an-airtag-from-your-apple-id-account-on-iphone-12-mini-by-drfone-ios/"><u>In 2024, How to Remove an AirTag from Your Apple ID Account On iPhone 12 mini?</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-youtube-video-extraction-dumpertnls-top-4-strategies-unveiled/"><u>Mastering the Art of YouTube Video Extraction: Dumpert.nl's Top 4 Strategies Unveiled!</u></a></li>
<li><a href="https://win11.techidaily.com/top-rated-audio-amplifier-a-user-friendly-guide-to-boosting-sound-clarity/"><u>Top-Rated Audio Amplifier: A User-Friendly Guide to Boosting Sound Clarity</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshoot-wi-fi-and-cellular-problems-on-iphone-via-network-recovery-mode/"><u>Troubleshoot Wi-Fi and Cellular Problems on iPhone via Network Recovery Mode</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-fixing-the-causes-behind-the-0xc00d3e8c-error-in-windows-11/"><u>Troubleshooting Guide: Fixing the Causes Behind the 0XC00D3E8C Error in Windows 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-tips-for-when-msvbvm50dll-is-mia-on-your-pc/"><u>Troubleshooting Tips for When msvbvm50.dll Is MIA on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-converting-ogv-audio-files-to-mp3-format-on-your-windows-pc/"><u>Ultimate Guide: Converting OGV Audio Files to MP3 Format on Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-the-top-12-leading-youtube-to-mp4-converter-tools/"><u>Ultimate Guide: The Top 12 Leading YouTube to MP4 Converter Tools</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/ultimate-screen-guide-choosing-the-best-displays-for-ps5-and-xbox-series-systems/"><u>Ultimate Screen Guide: Choosing the Best Displays for PS5 and Xbox Series Systems</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-techniques-for-changing-a-videos-fps-from-60-to-24/"><u>Ultimate Techniques for Changing a Video's FPS From 60 to 24</u></a></li>
</ul></div>

