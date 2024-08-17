---
title: Steps for Eradicating System Call Failed Problem in Windows 11
date: 2024-08-16T00:19:29.429Z
updated: 2024-08-17T00:19:29.429Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Run the SFC and DISM Tools in Command Prompt

![Windows System File Checker tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
6. Select **Quarantine** and **Yes** if Malwarebytes detects malware.

## 5\. Disable Startup Items and Services With a Clean Boot

 Another possibility is that a third-party program or service is conflicting or interfering with the File Explorer processing, causing the “System call failed” error to occur on your PC.

 You can address a software conflict by disabling all third-party startup items and services, which is otherwise the clean booting troubleshooting method. You can apply that troubleshooting method by following the instructions in this guide on [performing a clean boot in Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/).

 Restart your PC when you’ve disabled all third-party startup items and services. Then try opening File Explorer again to check if this “System call failed” error continues.

 If the error is fixed after clean booting, it will probably reoccur if you re-enable all startup apps and services again. You can try to identify what’s causing the error by gradually re-enabling items, and then disabling the startup app or service that triggers the issue again.

![Services tab on Windows Configuration menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab5.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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
<li><a href="https://vimeo-videos.techidaily.com/new-efficient-downloads-transform-vimeo-videos-into-mp4/"><u>[New] Efficient Downloads  Transform Vimeo Videos Into MP4</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-flip-order-3-easy-steps-to-rewind-youtube-listeners/"><u>[New] Flip Order  3 Easy Steps to Rewind Youtube Listeners</u></a></li>
<li><a href="https://youtube-data.techidaily.com/08533117-updated-download-premium-video-covers-free-fast-and-easy/"><u>[Updated] Download Premium Video Covers - Free, Fast & Easy!</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-seamless-integration-tailor-made-youtube-shorts-images-made-easy/"><u>[Updated] Seamless Integration  Tailor-Made YouTube Shorts Images Made Easy</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-the-sleep-inducing-series-analyzing-video-bedtime-stories/"><u>2024 Approved  The Sleep-Inducing Series  Analyzing Video Bedtime Stories</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-exploration-of-win11s-voice-control-shortcuts/"><u>A Detailed Exploration of Win11's Voice Control Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/breeze-through-blurred-taskbars-in-windows-11/"><u>Breeze Through Blurred Taskbars in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-comfortable-computing-environment-configuring-active-periods-and-managing-updates-in-windows-11/"><u>Crafting a Comfortable Computing Environment: Configuring Active Periods & Managing Updates in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-repairing-windows-enter-key-issues/"><u>Diagnosing and Repairing Windows Enter Key Issues</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-steam-connectivity-issues-with-quick-solutions/"><u>Enhancing Steam Connectivity Issues with Quick Solutions</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inaccessible-window-resolutions-8-simple-steps/"><u>Fixing Inaccessible Window Resolutions: 8 Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-automatic-detect-of-proxy-issues/"><u>Fixing Windows' Automatic Detect of Proxy Issues</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-silence-the-expiring-windows-license-message/"><u>How To Silence the Expiring Window's License Message</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-uninstall-programs-without-admin-privileges-on-windows/"><u>How to Uninstall Programs Without Admin Privileges on WINDOWS</u></a></li>
<li><a href="https://extra-information.techidaily.com/illustrate-instantly-image-to-illustration-on-any-device/"><u>Illustrate Instantly  Image to Illustration on Any Device</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-how-to-fix-obs-camera-not-working/"><u>In 2024, How to Fix OBS Camera Not Working</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-a-previously-synced-google-account-from-your-xiaomi-14-pro-by-drfone-android/"><u>In 2024, How to Remove a Previously Synced Google Account from Your Xiaomi 14 Pro</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-apple-id-and-apple-password-on-iphone-6s-plus-by-drfone-ios/"><u>In 2024, How to Reset Apple ID and Apple Password On iPhone 6s Plus</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-vivo-y78plus-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Vivo Y78+? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-top-notch-solutions-for-disabled-apple-id-on-iphone-12-making-it-possible-by-drfone-ios/"><u>In 2024, Top-Notch Solutions for Disabled Apple ID On iPhone 12 Making It Possible</u></a></li>
<li><a href="https://win11.techidaily.com/journey-to-greatness-your-ultimate-new-pc-apps/"><u>Journey to Greatness: Your Ultimate New PC Apps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-process-to-remove-wsl-from-windows/"><u>Mastering the Process to Remove WSL From Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-error-correction-for-rpc-failures/"><u>Mastering Windows Error Correction for RPC Failures</u></a></li>
<li><a href="https://review-topics.techidaily.com/mp4-video-repair-tool-repair-corrupt-damaged-unplayable-video-files-of-infinix-note-30-vip-racing-edition-by-stellar-video-repair-mobile-video-repair/"><u>MP4 Video Repair Tool - Repair corrupt, damaged, unplayable video files of Infinix Note 30 VIP Racing Edition</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-troubled-waters-eliminating-error-code-80080300-in-win11-tech/"><u>Navigate Through Troubled Waters: Eliminating Error Code 80080300 in Win11 Tech</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-steps-for-integrating-soundtracks-into-mkv-format-mkv-v202-release/"><u>New 2024 Approved Steps for Integrating Soundtracks Into MKV Format (MKV v2.0.2 Release)</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-windows-streams-stopping-abrupt-download-drops/"><u>Optimize Windows Streams: Stopping Abrupt Download Drops</u></a></li>
<li><a href="https://win11.techidaily.com/orchestrated-workflows-joining-ifttt-and-to-do/"><u>Orchestrated Workflows: Joining IFTTT and To-Do</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-xbox-audio-hurdles-with-windows-11-system-upgrades/"><u>Overcoming Xbox Audio Hurdles with Windows 11 System Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-user-interaction-ai-integration-into-windows-11/"><u>Redefining User Interaction: AI Integration Into Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-integration-web-pages-as-windows-tools/"><u>Seamless Integration: Web Pages as Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/securing-access-how-to-use-windows-11s-security-interface/"><u>Securing Access: How to Use Windows 11'S Security Interface</u></a></li>
<li><a href="https://win11.techidaily.com/securing-save-configurations-in-your-windows-pubg-game/"><u>Securing Save Configurations in Your Windows PUBG Game</u></a></li>
<li><a href="https://win11.techidaily.com/securing-windows-11-with-additional-firewall-options-via-context-menu/"><u>Securing Windows 11 with Additional Firewall Options via Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/skirting-enforced-driver-checks-for-easier-updates/"><u>Skirting Enforced Driver Checks for Easier Updates</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-intel-wi-fi-6a-driver-failure-in-windows-os/"><u>Solutions for Intel Wi-Fi 6A Driver Failure in Windows OS</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-into-the-future-of-entertainment-tcls-q-and-s-class-expands-now-featuring-19-cutting-edge-models/"><u>Step Into the Future of Entertainment – TCL's Q and S Class Expands, Now Featuring 19 Cutting-Edge Models</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-directx-setup-failures/"><u>Steps to Resolve DirectX Setup Failures</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-restore-screen-share-in-teams/"><u>Steps to Restore Screen Share in Teams</u></a></li>
<li><a href="https://win11.techidaily.com/stepwise-guide-to-amplifying-virtual-memory-on-microsofts-latest-os/"><u>Stepwise Guide to Amplifying Virtual Memory on Microsoft's Latest OS</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-swiftly-finding-and-fixing-windows-update-problems/"><u>Strategies for Swiftly Finding and Fixing Windows Update Problems</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-sync-windows-plus-android-via-flow-app/"><u>Streamlining Sync: Windows + Android via Flow App</u></a></li>
<li><a href="https://win11.techidaily.com/system-tray-simplified-the-art-of-minimizing-apps-on-windows/"><u>System Tray Simplified: The Art of Minimizing Apps on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/systematic-solutions-locating-and-correcting-windows-errors-via-the-power-of-command-prompt/"><u>Systematic Solutions: Locating & Correcting Windows Errors via the Power of Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-web-safety-including-reliable-domains-in-windows-11/"><u>Tailored Web Safety: Including Reliable Domains in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/taking-out-trash-onedrive-from-your-pcs-file-explorer/"><u>Taking Out Trash: OneDrive From Your PC's File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/the-forgotten-windows-11-theme-archive/"><u>The Forgotten Windows 11 Theme Archive</u></a></li>
<li><a href="https://win11.techidaily.com/the-window-whisperers-guide-to-unveiling-off-screen-apps-in-win-1011-6-proven-steps/"><u>The Window Whisperer's Guide to Unveiling Off-Screen Apps in Win 10/11 (6 Proven Steps)</u></a></li>
<li><a href="https://win11.techidaily.com/tidy-up-your-machine-best-windows-software-to-ditch/"><u>Tidy Up Your Machine: Best Windows Software to Ditch</u></a></li>
<li><a href="https://win11.techidaily.com/turn-on-school-inspired-themes-for-win-11/"><u>Turn On School-Inspired Themes for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-solving-error-code-31-in-windows-systems/"><u>Understanding and Solving Error Code 31 in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/windows-mastery-directing-app-and-browser-traffic/"><u>Windows Mastery: Directing App and Browser Traffic</u></a></li>
<li><a href="https://win11.techidaily.com/windows-program-commands-keybinding-setup/"><u>Windows Program Commands: Keybinding Setup</u></a></li>
</ul></div>
