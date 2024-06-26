---
title: Essential Tips to Run the SFC Tool Successfully
date: 2024-06-25T10:18:50.008Z
updated: 2024-06-26T10:18:50.008Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Tips to Run the SFC Tool Successfully
excerpt: This Article Describes Essential Tips to Run the SFC Tool Successfully
keywords: SFC Tool Success,Essential SFC Tips,SFC Optimization Guide,Efficient SFC Use,Running SFC Smoothly,Mastering SFC Execution,SFC Performance Enhancement
thumbnail: https://thmb.techidaily.com/5d3b16b34799fd4027e4ade17484dcb7de0969abd15218a509c4db117b716df9.jpg
---

## Essential Tips to Run the SFC Tool Successfully

 Your Windows computer depends on operating system files to get the information it needs to run smoothly. But sometimes, these files can become corrupted or go missing from your PC, affecting your system negatively in various ways. For example, when something’s wrong with a critical system file, your computer might become slow or crash frequently.

 An easy way to fix problematic system files is to use the System File Checker (SFC). This tool will scan your computer, check the integrity of each system file, and repair those that are damaged or missing.

 Here’s what you need to know about running the SFC tool on Windows.

## How to Run a System File Checker Scan on Windows

 To use the SFC, you need to run a single command in Command Prompt. Here’s how:

1. Press**Win + S** to open Windows Search and type**command prompt** in the search box.
2. This will bring up**Command Prompt** in the search result. Click on the**Run as administrator** option.  
![Run Command Prompt Using Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-Command-Prompt-Using-Windows-Search.jpg)
3. Click**Yes** in the UAC prompt to allow Command Prompt to make changes to your computer.
4. In Command Prompt, enter the below command, and then hit the**Enter** key:  
`SFC /scannow`

 If you’re unfamiliar with operating system files, please read our guide on[what system files are on Windows](https://www.makeuseof.com/windows-system-files-guide/) . And to learn everything you need to know about Command Prompt, you can check out our[beginner's guide to Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) .

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

 If you’re doing an offline scan, you can enable logging by simply specifying the file path with the following command structure:

`/offlogfile=[offline log file path]`

 Just replace**offline log file path** in the square brackets with the actual path you want to store the offline log file in the offline directory. Then, insert this entire command after the**/windir** command when running an offline SFC scan.

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
<li><a href="https://win11.techidaily.com/win11-fixing-persistent-read-only-folders/"><u>Win11: Fixing Persistent Read-Only Folders</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-windows-n-editions-for-business-purposes/"><u>Investigating Windows N Editions: For Business Purposes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-erroneous-non-existing-device-alert-on-win-11/"><u>Overcoming Erroneous Non-Existing Device Alert on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/recover-missing-wireless-signal-a-windows-10-solution-guide/"><u>Recover Missing Wireless Signal: A Windows 10 Solution Guide</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-ties-with-windows-11-store/"><u>Cutting Ties with Windows 11 Store</u></a></li>
<li><a href="https://win11.techidaily.com/skilled-tactics-bypassing-windows-11s-security-measures/"><u>Skilled Tactics: Bypassing Windows 11'S Security Measures</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-steam-sync-issue/"><u>Solving Windows Steam Sync Issue</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-techniques-to-effectively-modify-software-sizes-in-win11/"><u>Keyboard Techniques to Effectively Modify Software Sizes in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-dxgierror-post-device-disconnect/"><u>Avoidance of DXGI_Error Post Device Disconnect</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-vivid-vistas-the-ultimate-selection-of-popular-discotheme-sets/"><u>[Updated] 2024 Approved  Vivid Vistas  The Ultimate Selection of Popular DiscoTheme Sets</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-motorola-moto-g73-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Motorola Moto G73 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-locked-or-disabled-from-iphone-15-7-mehtods-you-cant-miss-by-drfone-ios/"><u>In 2024, Apple ID Locked or Disabled From iPhone 15? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/list-of-pokemon-go-joysticks-on-tecno-phantom-v-fold-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Tecno Phantom V Fold | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-oppo-a79-5g-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Oppo A79 5G Is Unlocked</u></a></li>
<li><a href="https://extra-resources.techidaily.com/capture-the-light-filmographys-five-essential-camera-techniques-of-24/"><u>Capture the Light  Filmography's Five Essential Camera Techniques of '24</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-in-2024-how-to-remove-motion-blur-in-photoshop/"><u>New In 2024, How to Remove Motion Blur In Photoshop</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-step-by-step-guide-for-proficient-use-of-movie-maker-in-win11/"><u>2024 Approved  Step-by-Step Guide for Proficient Use of Movie Maker in Win11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/creating-captivating-360-footage-for-social-media-sharing/"><u>Creating Captivating 360 Footage for Social Media Sharing</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-complete-guide-to-live-streaming-on-instagram-via-obs-for-2024/"><u>The Complete Guide to Live Streaming on Instagram via OBS for 2024</u></a></li>
</ul></div>
