---
title: Tackling Unexpected System Call Issues on Windows
date: 2024-09-11T09:40:35.771Z
updated: 2024-09-12T09:40:35.771Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115914/19272" target="_top" id="2115914">
  <img src="//a.impactradius-go.com/display-ad/19272-2115914" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115914/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restarting the explorer.exe process can fix the “System call failed” error. It's a really easy and quick fix, so it's a good starting point for troubleshooting the “system call failed” error.

 You can restart the explorer.exe process with Task Manager, as covered in this guide on [how to restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/).

## 2\. Run the SFC and DISM Tools in Command Prompt

![Windows System File Checker tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow.jpg)

<!-- affiliate ads begin -->
<span id="1492813">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1492813.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1492813">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1492813.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1492813%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1492813/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Disable Startup Items and Services With a Clean Boot

 Another possibility is that a third-party program or service is conflicting or interfering with the File Explorer processing, causing the “System call failed” error to occur on your PC.

 You can address a software conflict by disabling all third-party startup items and services, which is otherwise the clean booting troubleshooting method. You can apply that troubleshooting method by following the instructions in this guide on [performing a clean boot in Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/).

 Restart your PC when you’ve disabled all third-party startup items and services. Then try opening File Explorer again to check if this “System call failed” error continues.

 If the error is fixed after clean booting, it will probably reoccur if you re-enable all startup apps and services again. You can try to identify what’s causing the error by gradually re-enabling items, and then disabling the startup app or service that triggers the issue again.

![Services tab on Windows Configuration menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab5.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115921/19272" target="_top" id="2115921">
  <img src="//a.impactradius-go.com/display-ad/19272-2115921" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115921/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<span id="1983582">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983582.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983582">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983582.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983582%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983582/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121331/18498" target="_top" id="2121331">
  <img src="//a.impactradius-go.com/display-ad/18498-2121331" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121331/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get the “System Call Failed” Error Fixed

 Those “System call failed” error solutions are confirmed to work by many users who have needed to resolve that File Explorer issue.

 So, it’s very likely one will solve that issue, so you can fully utilize File Explorer again. If none of those resolutions are enough, consider contacting the Microsoft Windows support service for further guidance.

 The “system call failed” error stems from File Explorer’s explorer.exe process. This is how you can fix the “System call failed” Windows 11/10 error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-jaunt-vr-uncovered-a-comprehensive-look/"><u>[New] In 2024, Jaunt VR Uncovered A Comprehensive Look</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-essential-asmr-apps-android-and-ios-edition/"><u>[Updated] 2024 Approved Essential ASMR Apps Android & iOS Edition</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-screen-saver-games-the-top-9-independent-titles-for-android-no-wi-fi/"><u>[Updated] In 2024, Screen-Saver Games The Top 9 Independent Titles for Android (No Wi-Fi)</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-convenient-and-quality-passport-images-top-free-tools-listed-here/"><u>2024 Approved Convenient & Quality Passport Images - Top Free Tools Listed Here</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-for-using-windows-canary-service/"><u>Comprehensive Guide for Using Windows' Canary Service</u></a></li>
<li><a href="https://win-able.techidaily.com/convenient-tips-for-navigating-the-drive-easy-portable-application/"><u>Convenient Tips for Navigating the Drive Easy Portable Application</u></a></li>
<li><a href="https://facebook.techidaily.com/demystifying-how-photodna-identifies-counterfeits/"><u>Demystifying How PhotoDNA Identifies Counterfeits</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/dodging-ai-crafted-windows-11-keys-a-good-practice/"><u>Dodging AI-Crafted Windows 11 Keys: A Good Practice</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1723862684696-dont-miss-out-high-performance-m3-macbook-air-laptop-16gb-ram-and-13-display-for-only-1149/"><u>Don't Miss Out: High-Performance M3 MacBook Air Laptop - 16GB RAM & 13 Display for Only $1,149</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-network-drive-configuration-for-enhanced-workflow/"><u>Efficient Network Drive Configuration for Enhanced Workflow</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-disabled-obstacles-for-executing-powershell-scripts/"><u>Eliminating 'Disabled' Obstacles for Executing PowerShell Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-precision-and-speed-of-windows-11-laptop-screens/"><u>Enhance Precision and Speed of Windows 11 Laptop Screens</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-frayed-script-extensions-in-skyrim-games/"><u>Fixing Frayed Script Extensions in Skyrim Games</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/heaviest-aerial-transporters-top-10-drones-reviewed-for-2024/"><u>Heaviest Aerial Transporters Top 10 Drones Reviewed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-err0r-x7e1-on-win10-pcs/"><u>How to Reset Err0r: X7E1 on Win10 PCs</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-iphone-7-plus-screen-lock-without-passcode-by-drfone-ios-unlock-ios-unlock/"><u>How to unlock iPhone 7 Plus screen lock without Passcode?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ideal-microphones-for-precision-in-4k-video-and-sound-recording/"><u>Ideal Microphones for Precision in 4K Video & Sound Recording</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-honor-play-7t-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Honor Play 7T Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-track-imei-number-of-oneplus-11r-through-google-earth-by-drfone-android/"><u>In 2024, How To Track IMEI Number Of OnePlus 11R Through Google Earth?</u></a></li>
<li><a href="https://win11.techidaily.com/key-complementary-aid-for-elevating-your-windows-11-use/"><u>Key Complementary Aid for Elevating Your Windows 11 Use</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-tcpip-with-python-servers-on-windows-networks/"><u>Leveraging TCP/IP with Python Servers on Windows Networks</u></a></li>
<li><a href="https://win11.techidaily.com/modify-display-scaling-in-windows-11/"><u>Modify Display Scaling in Windows 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/motherboard-selection-mastery-understanding-7-critical-factors/"><u>Motherboard Selection Mastery: Understanding 7 Critical Factors</u></a></li>
<li><a href="https://win11.techidaily.com/onedrives-invalid-reparse-point-a-guide-to-mend-it-on-windows/"><u>OneDrive’s Invalid Reparse Point: A Guide to Mend It on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-errors-with-googles-nearby-sharing-on-pc/"><u>Overcoming Errors with Google's Nearby Sharing on PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-login-block-after-failure/"><u>Overcoming Windows Login Block After Failure</u></a></li>
<li><a href="https://extra-tips.techidaily.com/pinnacle-of-brainy-content-general-knowledge-top-11/"><u>Pinnacle of Brainy Content General Knowledge Top 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-unsupported-boot-state-in-windows/"><u>Quick-Fix for Unsupported Boot State in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/regain-command-function-keys-restoration-in-win10/"><u>Regain Command: Function Keys' Restoration in Win10</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-the-impact-of-glitches-winvolume-fix-guide/"><u>Reverse the Impact of Glitches: WinVolume Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/seamlessly-merge-your-android-with-a-windows-system/"><u>Seamlessly Merge Your Android with a Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-15-ways-to-reach-windows-settings/"><u>Simplify: 15 Ways to Reach Windows Settings</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-tutorial-for-setting-up-a-custom-email-signature-in-godaddy-webmail-services/"><u>Step-by-Step Tutorial for Setting Up a Custom Email Signature in GoDaddy Webmail Services</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-resolving-not-handled-error-on-windows-1011/"><u>Tips for Resolving Not Handled Error on Windows 10/11</u></a></li>
<li><a href="https://techtrends.techidaily.com/turn-off-auto-repeat-the-comprehensive-guide-to-stopping-apple-musics-nonstop-songs/"><u>Turn Off Auto-Repeat: The Comprehensive Guide to Stopping Apple Music's Nonstop Songs</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-the-0x8007045d-blue-screen/"><u>Understanding and Remedying the 0X8007045D Blue Screen</u></a></li>
<li><a href="https://win11.techidaily.com/vivetool-steps-for-windows-copilot-enablement/"><u>ViveTool Steps for Windows Copilot Enablement</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-zte-nubia-flip-5g-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On ZTE Nubia Flip 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-webcam-troubleshooting-avoid-code-0xa00f4289/"><u>Win10/11 Webcam Troubleshooting - Avoid Code 0xA00F4289</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-google-play-setup-protocols/"><u>Windows 11 Google Play Setup Protocols</u></a></li>
<li><a href="https://win11.techidaily.com/windows-reset-triggers-top-10-tips/"><u>Windows Reset Triggers: Top 10 Tips</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    