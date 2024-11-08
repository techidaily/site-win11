---
title: "Executing Windows SFC: A Step-Wise Procedure"
date: 2024-11-02T18:52:21.200Z
updated: 2024-11-07T21:09:48.477Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Executing Windows SFC: A Step-Wise Procedure"
excerpt: "This Article Describes Executing Windows SFC: A Step-Wise Procedure"
keywords: Fix Windows Files (SFC),SFC Command Guide,System File Check (SFC),SFC Scan Processing,Execute SFC Stepwise,Troubleshoot SFC Failure,Windows System Repair
thumbnail: https://thmb.techidaily.com/18e0761348cb4d28e3480c4ed08a893497db31dc39159b03c85adcc25dd9aaa4.jpg
---

## Executing Windows SFC: A Step-Wise Procedure

 Your Windows computer depends on operating system files to get the information it needs to run smoothly. But sometimes, these files can become corrupted or go missing from your PC, affecting your system negatively in various ways. For example, when something’s wrong with a critical system file, your computer might become slow or crash frequently.

 An easy way to fix problematic system files is to use the System File Checker (SFC). This tool will scan your computer, check the integrity of each system file, and repair those that are damaged or missing.

 Here’s what you need to know about running the SFC tool on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047406/19272" target="_top" id="2047406">
  <img src="//a.impactradius-go.com/display-ad/19272-2047406" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you don’t want to bother with searching through the**CBS.log** file for the entries with the**\[SR\]** tag, you can extract them to a file called**sfcdetails.txt** . To do that, open Command Prompt as an administrator, and run the below command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >sfcdetails.txt`

 You can find**sfcdetails.txt** by heading to**This PC > Local Disk (C:) > Windows > System32** .

![the sfc details text file in File Explorer on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-details-file.jpg)

 You’ll see that the log file contains entries from the System File Checker only.

![the sfc details text file on Windows opened in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-detail-txt.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115946/19272" target="_top" id="2115946">
  <img src="//a.impactradius-go.com/display-ad/19272-2115946" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://extra-skills.techidaily.com/new-instantize-image-movement-with-photoshop/"><u>[New] Instantize Image Movement with Photoshop</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-expanding-possibilities-with-virtual-reality/"><u>[Updated] Expanding Possibilities with Virtual Reality</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-media-management-on-instagram/"><u>[Updated] Mastering Media Management on Instagram</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-nocostcam-the-infinite-gaming-screen-record-tool-for-2024/"><u>[Updated] NoCostCam The Infinite Gaming Screen Record Tool for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-handbook-ios-photo-alignment-and-cloud-synchronization/"><u>2024 Approved The Ultimate Handbook IOS Photo Alignment & Cloud Synchronization</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-incorporate-emulators-into-playnite/"><u>Effortlessly Incorporate Emulators Into Playnite</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-11-isp-settings/"><u>Exploring Windows 11 ISP Settings</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-locked-or-disabled-on-iphone-12-mini-7-mehtods-you-cant-miss-by-drfone-ios/"><u>In 2024, Apple ID Locked or Disabled On iPhone 12 mini? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-vivo-y100t-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Vivo Y100t Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-my-spouse-from-spying-on-my-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop My Spouse from Spying on My Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-ultimate-guide-to-bypassing-icloud-activation-lock-on-apple-iphone-6-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Bypassing iCloud Activation Lock on Apple iPhone 6</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-disk-space-optimization-on-win-1011/"><u>Mastering Disk Space Optimization on Win 10/11</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-art-of-checking-powershell-versions-in-windows-11-with-help-from-revouninstaller/"><u>Mastering the Art of Checking PowerShell Versions in Windows 11 with Help From RevoUninstaller</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-efficiency-incorporating-custom-tasks-into-windows-explorer/"><u>Maximizing Efficiency: Incorporating Custom Tasks Into Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/monitor-mania-tailoring-your-taskscape-with-themed-windows/"><u>Monitor Mania: Tailoring Your Taskscape with Themed Windows</u></a></li>
<li><a href="https://win11.techidaily.com/pathway-exploration-navigating-to-windowsstore-directory/"><u>Pathway Exploration: Navigating to WindowsStore Directory</u></a></li>
<li><a href="https://win11.techidaily.com/removing-onedrive-from-windows-file-explorer-a-guide/"><u>Removing OneDrive From Windows File Explorer: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/the-pinnacle-collection-best-free-aid-for-windows-11-users/"><u>The Pinnacle Collection: Best Free Aid for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-windows-error-0x800f0831/"><u>Understanding and Remedying Windows Error 0X800F0831</u></a></li>
</ul></div>

