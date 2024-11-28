---
title: How to Overcome 'Failed System Call' In Windows OS
date: 2024-11-24T16:46:26.266Z
updated: 2024-11-27T18:10:21.068Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Overcome 'Failed System Call' In Windows OS
excerpt: This Article Describes How to Overcome 'Failed System Call' In Windows OS
keywords: Fixing Failed Calls in WinOS,Resolve Windows SysCall Errors,Overcoming SysCalls Failures,Troubleshoot WinSysError,Stop SysCall Fails on PC,Mend Windows Call Issues,Avoid Failed OS Calls
thumbnail: https://thmb.techidaily.com/b7025f879b7f69fff163ff4565fc3f42cd715d8a0e343c5b6d69fd8b7007ad8a.jpg
---

## How to Overcome 'Failed System Call' In Windows OS

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Disable Startup Items and Services With a Clean Boot

 Another possibility is that a third-party program or service is conflicting or interfering with the File Explorer processing, causing the “System call failed” error to occur on your PC.

 You can address a software conflict by disabling all third-party startup items and services, which is otherwise the clean booting troubleshooting method. You can apply that troubleshooting method by following the instructions in this guide on [performing a clean boot in Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/).

 Restart your PC when you’ve disabled all third-party startup items and services. Then try opening File Explorer again to check if this “System call failed” error continues.

 If the error is fixed after clean booting, it will probably reoccur if you re-enable all startup apps and services again. You can try to identify what’s causing the error by gradually re-enabling items, and then disabling the startup app or service that triggers the issue again.

![Services tab on Windows Configuration menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab5.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://visual-screen-recording.techidaily.com/updated-correcting-missed-audio-segments-in-obs-recordings/"><u>[Updated] Correcting Missed Audio Segments in OBS Recordings</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-insta-stories-enhancing-background-blur-technique/"><u>[Updated] Insta Stories Enhancing Background Blur Technique</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-guide-managing-vms-secure-boot-and-tpm-on-virtualbox/"><u>Detailed Guide: Managing VM's Secure Boot & TPM on VirtualBox</u></a></li>
<li><a href="https://buynow-info.techidaily.com/expert-review-of-nokia-31-your-gateway-to-modern-communication/"><u>Expert Review of Nokia 3.1 - Your Gateway to Modern Communication</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-recurrent-gameplay-disruptions-tips-for-running-smoothly-with-dirt-5-on-pc/"><u>Fixing Recurrent Gameplay Disruptions - Tips for Running Smoothly with Dirt 5 on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-taskbar-visible-when-maximizing-chromeedge/"><u>How to Make Taskbar Visible When Maximizing Chrome/Edge</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mastering-photo-editing-unveiling-background-eraser-in-adobe-photoshop/"><u>Mastering Photo Editing Unveiling Background Eraser in Adobe Photoshop</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-maze-of-pubg-setting-adjustments-on-win-1011/"><u>Navigating the Maze of PUBG Setting Adjustments on Win 10/11</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-screen-flip-issue-with-windows-11/"><u>Overcoming Screen Flip Issue with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-uninitialized-disk-problem-in-windows-os/"><u>Resolving 'Uninitialized' Disk Problem in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-erroneous-onedrive-blob-tags-in-windows-environment/"><u>Resolving Erroneous OneDrive Blob Tags in Windows Environment</u></a></li>
<li><a href="https://blog-min.techidaily.com/revolutionizing-performance-the-all-electric-volkswagen-golf-gti-concept-debuts/"><u>Revolutionizing Performance: The All-Electric Volkswagen Golf GTI Concept Debuts</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/shades-and-tones-mastering-the-visual-spectrum/"><u>Shades and Tones Mastering the Visual Spectrum</u></a></li>
<li><a href="https://tech-haven.techidaily.com/social-media-safety-and-tech-advancements-navigating-through-recent-twitter-scams-metas-leap-with-verified-user-authentication-and-the-advanced-world-of-cha68/"><u>Social Media Safety & Tech Advancements: Navigating Through Recent Twitter Scams, Meta’s Leap with Verified User Authentication, and The Advanced World of ChatGPT-4 Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-way-managing-windows-gpgpu-task-management/"><u>Tailoring Your Way: Managing Windows' GPGPU Task Management</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-avoid-overloading-edge-processes/"><u>Techniques to Avoid Overloading Edge Processes</u></a></li>
<li><a href="https://techidaily.com/the-way-to-convert-mts-for-samsung-galaxy-s23-by-aiseesoft-video-converter-play-mts-on-android/"><u>The way to convert MTS for Samsung Galaxy S23</u></a></li>
<li><a href="https://win11.techidaily.com/top-3-fixes-conquering-the-black-screen-problems-in-win11/"><u>Top 3 Fixes: Conquering the Black Screen Problems in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/traversing-digital-terrain-finding-mac-addresses-on-windows-11/"><u>Traversing Digital Terrain: Finding Mac Addresses on WIndows 11</u></a></li>
</ul></div>

