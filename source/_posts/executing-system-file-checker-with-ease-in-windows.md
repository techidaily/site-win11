---
title: Executing System File Checker with Ease in Windows
date: 2025-01-28T01:10:45.742Z
updated: 2025-02-03T18:24:03.634Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Executing System File Checker with Ease in Windows
excerpt: This Article Describes Executing System File Checker with Ease in Windows
keywords: SFC Execution Guide,Windows SFC Troubleshoot,Easy SFC Run,Windows File Integrity,System Repair Tool Use,Quick Fix SFC Errors,Windows File Audit
thumbnail: https://thmb.techidaily.com/6ae69a61ee431cd865eb63071b7e7dab33df662eeb4d068d44c620780bca6c82.jpeg
---

## Executing System File Checker with Ease in Windows

 Your Windows computer depends on operating system files to get the information it needs to run smoothly. But sometimes, these files can become corrupted or go missing from your PC, affecting your system negatively in various ways. For example, when something’s wrong with a critical system file, your computer might become slow or crash frequently.

 An easy way to fix problematic system files is to use the System File Checker (SFC). This tool will scan your computer, check the integrity of each system file, and repair those that are damaged or missing.

 Here’s what you need to know about running the SFC tool on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Run a System File Checker Scan on Windows

 To use the SFC, you need to run a single command in Command Prompt. Here’s how:

1. Press**Win + S** to open Windows Search and type**command prompt** in the search box.
2. This will bring up**Command Prompt** in the search result. Click on the**Run as administrator** option.  
![Run Command Prompt Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-Command-Prompt-Using-Windows-Search.jpg)
3. Click**Yes** in the UAC prompt to allow Command Prompt to make changes to your computer.

4. In Command Prompt, enter the below command, and then hit the**Enter** key:  
`SFC /scannow`

 If you’re unfamiliar with operating system files, please read our guide on[what system files are on Windows](https://www.makeuseof.com/windows-system-files-guide/) . And to learn everything you need to know about Command Prompt, you can check out our[beginner's guide to Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Happens After I Run the System File Checker?

 After the System File Checker completes its scan, it will display a message in the Command Prompt window with the results.

 If your system files are okay, you’ll see a message that says "Windows Resource Protection did not find any integrity violations." If SFC found and fixed all problematic files, the message will read "Windows Resource Protection found corrupt files and successfully repaired them."

![the results of an sfc scan in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-scan-results.jpg)

 On the other hand, if it found corrupted files but couldn’t repair any or all of them, the message will read "Windows Resource Protection found corrupt files but was unable to fix some of them." And if SFC encounters a problem, the message will say "Windows Resource Protection could not perform the requested operation."

## Other SFC Commands You Can Run on Windows

 The**SFC /scannow** isn’t the only System File Checker Command you can run. Here are a couple more and what they do:

| SFC Command | Description                                                                                                                                                                                                                                                                       |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| /verifyonly | Run this command if you want SFC to check for problematic operating system files without fixing them.                                                                                                                                                                             |
| /scanfile   | Run this command if you want SFC to check a specific file for problems and fix it if it does have them. For example, Here’s the full command for checking and fixing the**user32.dll** file:**SFC /scanfile=c:\\windows\\system32\\user32.dll**                                   |
| /verifyfile | Run this command if you only want to check a particular system file for problems. Even if SFC finds an issue with the file, it will not repair it. For example, Here’s the full command for checking the**user32.dll** file:**SFC /verifyfile=c:\\windows\\system32\\user32.dll** |
| /offbootdir | Run this command to tell the SFC which directory contains a bootable version of Windows. You need to do this every time you use the tool outside of Windows. For example, to select the**E:** drive on your PC, enter**/offbootdir=e:\\**                                         |
| /offwindir  | Run this command to tell the SFC which folder in the directory — the one you specified with the**SFC /offbootdir** command — contains Windows. For example, enter**/offwindir=e:\\windows** to tell the System File Checker that Windows is on the**E:** drive.                   |

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Run an Offline SFC Scan on Windows

 There are a few scenarios that warrant the use of the SFC without logging into Windows. One such scenario is if the operating system files are so corrupted that Windows cannot start.

 In that case, you can run SFC by[creating a bootable Windows disc or drive](https://www.makeuseof.com/tag/make-bootable-usb-cd-dvd-install-windows-using-iso-file/) and using it to fix damaged system files. This is called an offline scan.

 The important thing to remember about an offline scan is that you need to tell the SFC where to find Windows on the bootable drive. Here’s what a**/scannow** command would look like if you ran it offline:

`SFC /scannow /offbootdir=d:\ /offwindir=d:\windows`

 That above command will tell SFC to look for Windows in the**Windows** folder on the**D:** drive. But keep in mind that the Windows version on the bootable media needs to be the same as the one installed on your PC for the scan and repair to be successful.

## How to Find the SFC Log File On Windows

 After the SFC does its thing, it will log the results of the scan and any repairs it made into a text file called**CBS.log** . To open it, press**Win + R** to open Windows Run, enter the below text, and click**OK** :

`%windir%\logs\cbs\cbs.log`

 The CBS.log file contains other logs besides those from the System File Checker. When looking through the entries, look for those that have an**\[SR\]** tag on them. Each entry will contain the date and time of the scan, along with the details of what happened.

![cbs log file on Windows that has been opened in Notepad with the SR tag part showing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/cbs-log-sfc-windows.jpg)

 If you don’t want to bother with searching through the**CBS.log** file for the entries with the**\[SR\]** tag, you can extract them to a file called**sfcdetails.txt** . To do that, open Command Prompt as an administrator, and run the below command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >sfcdetails.txt`

 You can find**sfcdetails.txt** by heading to**This PC > Local Disk (C:) > Windows > System32** .

![the sfc details text file in File Explorer on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-details-file.jpg)

 You’ll see that the log file contains entries from the System File Checker only.

![the sfc details text file on Windows opened in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-detail-txt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you’re doing an offline scan, you can enable logging by simply specifying the file path with the following command structure:

`/offlogfile=[offline log file path]`

 Just replace**offline log file path** in the square brackets with the actual path you want to store the offline log file in the offline directory. Then, insert this entire command after the**/windir** command when running an offline SFC scan.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Running the System File Checker, Demystified

 We have only just begun to scratch the surface of what you can do with the System File Checker on Windows 10 and 11\. However, now that you know**how to run SFC** (both in and out of Windows), you can use the tool effectively to troubleshoot problems with operating system files.

 Using the SFC effectively is a necessary skill for every Windows user, and it’s just one of the many tools you can use to fix problems on your Windows computer.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/024-approved-youtube-revenue-per-million-viewer-count/"><u>[New] 2024 Approved Youtube Revenue Per Million Viewer Count</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-cost-free-chromebook-video-capturing-leaders-for-2024/"><u>[New] Cost-Free Chromebook Video Capturing Leaders for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-elevate-your-video-edits-ken-burns-in-camtasia/"><u>[Updated] 2024 Approved Elevate Your Video Edits Ken Burns in Camtasia</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-unveiling-magixs-image-organizer-insights/"><u>[Updated] In 2024, Unveiling MAGIX's Image Organizer Insights</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-unlocking-fullscreen-footage-screen-recording-made-simple-for-mac-users/"><u>[Updated] Unlocking Fullscreen Footage Screen Recording Made Simple for Mac Users</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-the-ultimate-guide-to-crafting-dynamic-canon-time-lapses/"><u>2024 Approved The Ultimate Guide to Crafting Dynamic Canon Time-Lapses</u></a></li>
<li><a href="https://driver-download.techidaily.com/audio-technica-driver-update-procedure-improve-sound-quality-with-the-latest-software-upgrade/"><u>Audio-Technica Driver Update Procedure: Improve Sound Quality With The Latest Software Upgrade</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-0x800f0845-error-in-windows-updates/"><u>Correcting 0X800f0845 Error in Windows Updates</u></a></li>
<li><a href="https://discover-deluxe.techidaily.com/customizable-lock-screen-options-for-windows-8/"><u>Customizable Lock Screen Options for Windows 8</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-quick-launch-to-begin-with-onedrive-and-file-explorer/"><u>Customizing Quick Launch to Begin with OneDrive and File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-visibility-of-pinned-apps-on-windows-11/"><u>Enhance Visibility of Pinned Apps on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-microsoft-store-error-code-0x800704cf-in-windows/"><u>Mastery over Microsoft Store Error: Code 0X800704CF in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-and-fix-common-microsoft-store-login-issues/"><u>Navigate and Fix Common Microsoft Store Login Issues</u></a></li>
<li><a href="https://win-help.techidaily.com/trasferisci-rapidamente-le-tue-immagini-dal-mac-al-dischiotto-hard-drive-con-queste-due-metodi-semplici/"><u>Trasferisci Rapidamente Le Tue Immagini Dal Mac Al Dischiotto Hard Drive Con Queste Due Metodi Semplici</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-failed-connections-to-nvidia-geforce-ex/"><u>Troubleshooting Failed Connections to NVIDIA GeForce Ex</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-lan-access-issues-on-windows-mc/"><u>Troubleshooting LAN Access Issues on Windows MC</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-fbm-potential-10-fixes-for-computer-users/"><u>Unleashing FBM Potential: 10 Fixes for Computer Users</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-connections-fixes-for-failed-nvidia-experience-in-windows-11/"><u>Unlocking Connections: Fixes for Failed Nvidia Experience in Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/xbox-game-pass-guide-why-its-a-must-have/"><u>Xbox Game Pass Guide: Why It's a Must-Have</u></a></li>
</ul></div>

