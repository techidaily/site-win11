---
title: Realigning Windows & WSL After the Advent of Windows 11
date: 2024-09-11T09:39:32.464Z
updated: 2024-09-12T09:39:32.464Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Realigning Windows & WSL After the Advent of Windows 11
excerpt: This Article Describes Realigning Windows & WSL After the Advent of Windows 11
keywords: WinWSL21Alignment,WSLUpdatesWindows11,Windows11WLSAdjustment,WSLConfigWin11New,WSLSetupWindows11Revamp,11WLSIntegrationCheck,Win11WSLSystemUpdate
thumbnail: https://thmb.techidaily.com/423415d175d6eec024525c4afdad758a2e4f561184514d4182ee660b64af6137.jpg
---

## Realigning Windows & WSL After the Advent of Windows 11

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135400/19272" target="_top" id="2135400">
  <img src="//a.impactradius-go.com/display-ad/19272-2135400" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135400/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134500/19576" target="_top" id="2134500">
  <img src="//a.impactradius-go.com/display-ad/19576-2134500" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134500/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130531/26400" target="_top" id="2130531">
  <img src="//a.impactradius-go.com/display-ad/26400-2130531" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130531/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.
4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137411/7443" target="_top" id="2137411">
  <img src="//a.impactradius-go.com/display-ad/7443-2137411" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136618/26400" target="_top" id="2136618">
  <img src="//a.impactradius-go.com/display-ad/26400-2136618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136618/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

<!-- affiliate ads begin -->
<span id="1983588">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983588.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983588">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983588.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983588%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983588/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fixing WSL After Upgrading to Windows 11

 Upgrading to Windows 11 usually goes smoothly, but apps and features can occasionally break. If you find that WSL is no longer working after upgrading to the newest Windows OS, don't worry, there is usually an easy fix. You might only need to re-enable the feature in the Windows system settings, but if not, running through the other fixes here will usually solve the problem.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-live-stream-audio-effective-recording-methods-for-the-digital-age/"><u>[New] 2024 Approved Live Stream Audio Effective Recording Methods for the Digital Age</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-a-comprehensive-guide-to-crafting-memes-on-9gag/"><u>[New] A Comprehensive Guide to Crafting Memes on 9GAG</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-unleash-potential-optimizing-short-films-in-marketing/"><u>[New] Unleash Potential Optimizing Short Films in Marketing</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-accelerating-operations-discover-the-leading-scheduling-tools/"><u>[Updated] 2024 Approved Accelerating Operations Discover the Leading Scheduling Tools</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-behind-the-scenes-what-does-an-unlisted-video-mean-in-2024/"><u>[Updated] Behind the Scenes What Does an 'Unlisted' Video Mean, In 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-the-essential-tutorial-on-using-instagram-filters/"><u>[Updated] In 2024, The Essential Tutorial on Using Instagram Filters</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-top-10-epic-adventures-ultimate-gameplay-showdowns/"><u>[Updated] In 2024, Top 10 Epic Adventures Ultimate Gameplay Showdowns</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-comprehensive-manual-for-effective-morphvox-voice-changes/"><u>2024 Approved The Comprehensive Manual for Effective MorphVOX Voice Changes</u></a></li>
<li><a href="https://article-files.techidaily.com/acid-pro-overview-plus-best-software-match-ups-for-2024/"><u>ACID Pro Overview + Best Software Match-Ups for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/boost-your-minecraft-gameplay-eradicate-stuttering-with-this-comprehensive-guide/"><u>Boost Your Minecraft Gameplay: Eradicate Stuttering With This Comprehensive Guide</u></a></li>
<li><a href="https://os-tips.techidaily.com/charge-multiple-gadgets-simultaneously-with-belkins-latest-200w-usb-c-portable-power-station/"><u>Charge Multiple Gadgets Simultaneously with Belkin's Latest 200W USB-C Portable Power Station</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-resolve-windowss-perplexing-pink-screens/"><u>Comprehensive Guide to Resolve Windows's Perplexing Pink Screens</u></a></li>
<li><a href="https://tech-haven.techidaily.com/conversational-clarity-deciding-on-snapchat-ai-vs-gpt/"><u>Conversational Clarity: Deciding on Snapchat AI vs GPT</u></a></li>
<li><a href="https://win11.techidaily.com/de-jam-your-devices-top-9-solutions-for-unstuck-windows-setup/"><u>De-Jam Your Devices: Top 9 Solutions for Unstuck Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-steam-authentication-errors-a-rust-powered-windows-approach/"><u>Dealing with Steam Authentication Errors: A Rust-Powered Windows Approach</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-win-error-messages-your-step-by-step-solution/"><u>Decoding Win Error Messages - Your Step-by-Step Solution</u></a></li>
<li><a href="https://win11.techidaily.com/efficiency-seekers-guide-to-lightweight-browsers-for-windowsmacoschromeos/"><u>Efficiency Seekers' Guide to Lightweight Browsers for Windows/macOS/ChromeOS</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-system-installation-guide-for-pc-manager-w11/"><u>Elevate Your System - Installation Guide for PC Manager W11</u></a></li>
<li><a href="https://win11.techidaily.com/encrypted-space-covertly-placing-zip-archives-in-pixels/"><u>Encrypted Space: Covertly Placing Zip Archives in Pixels</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-11-notepad-with-digital-sage/"><u>Enhance Windows 11 Notepad with Digital Sage</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-clearing-printer-connection-errors/"><u>Expert Guide to Clearing Printer Connection Errors</u></a></li>
<li><a href="https://win11.techidaily.com/find-my-missing-f-16-copilot-in-windows-11-steps/"><u>Find My Missing F-16 Copilot In Windows 11 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-a-non-functional-xbox-controller-for-pc/"><u>Fixing a Non-Functional Xbox Controller for PC</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-11-installer-issues-effectively/"><u>Fixing Windows 11 Installer Issues Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/handling-runtime-failure-tips-for-correcting-malwarebytes-execution-errors-on-win10win11/"><u>Handling Runtime Failure: Tips for Correcting Malwarebytes' Execution Errors on Win10/Win11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-to-edit-text-in-image-photo-text-editor-online-and-app/"><u>How to Edit Text in Image? [Photo Text Editor Online and App]</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-the-enhanced-taskbar-in-windows-11/"><u>How to Enable the Enhanced Taskbar in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-intellij-unison-back-up-and-running-on-win11/"><u>How to Get IntelliJ Unison Back Up & Running on Win11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-iphone-8-plus-ios-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair iPhone 8 Plus iOS System? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-random-opens-in-microsoft-shop-app/"><u>How to Stop Random Opens in Microsoft Shop App</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-best-balanced-mounts-capture-clear-shots-every-time/"><u>In 2024, Best Balanced Mounts Capture Clear Shots Every Time</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-passfab-iphone-14-plus-backup-unlocker-top-4-alternatives-by-drfone-ios/"><u>In 2024, PassFab iPhone 14 Plus Backup Unlocker Top 4 Alternatives</u></a></li>
<li><a href="https://win11.techidaily.com/intel-unison-not-working-try-this-fix-guide-on-windows-11/"><u>Intel Unison Not Working? Try This Fix Guide on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-notes-at-the-forefront-on-win-oses/"><u>Keep Your Notes at the Forefront on Win OSes</u></a></li>
<li><a href="https://win11.techidaily.com/leap-from-batch-processing-to-executables-in-windows/"><u>Leap From Batch Processing to Executables in Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/macx-dvd-video-converter-pro-pack-get-your-free-promo-code-and-save-big-on-professional-software/"><u>MacX DVD Video Converter Pro Pack: Get Your Free Promo Code & Save Big on Professional Software!</u></a></li>
<li><a href="https://win11.techidaily.com/making-desktops-come-alive-with-sketches/"><u>Making Desktops Come Alive with Sketches</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-remedy-for-error-code-0x80071a90/"><u>Mastering the Remedy for Error Code: 0X80071A90</u></a></li>
<li><a href="https://win11.techidaily.com/migrating-user-defined-powertoys-settings/"><u>Migrating User-Defined PowerToys Settings</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-utorrent-installation-failures-in-windows-108/"><u>Mitigating uTorrent Installation Failures in Windows 10/8</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-search-troubleshooting-steps/"><u>Navigating Through Windows Search Troubleshooting Steps</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-blue-screen-interrupt-exception-fix/"><u>Overcoming Blue Screen: Interrupt Exception Fix</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-disk-needs-initializing-error-on-windows/"><u>Overcoming Disk Needs Initializing Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-each-window-11-screen-with-distinct-wallpapers/"><u>Personalize Each Window 11 Screen with Distinct Wallpapers</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolve-audio-stuttering-and-distortion-in-windows-117-with-easy-fixes/"><u>Resolve Audio Stuttering & Distortion in Windows 11/7 with Easy Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-win11-vagrant-start-issues-with-7-effective-approaches/"><u>Resolve Win11 Vagrant Start Issues with 7 Effective Approaches</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-the-webp-effect-modify-google-chromes-save-settings-win-wise/"><u>Reverse the WebP Effect: Modify Google Chrome's Save Settings, Win-Wise</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-transition-getting-started-with-outlook-preview-on-windows-11/"><u>Seamless Transition: Getting Started with Outlook Preview on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-pcs-automatic-shutdown-at-idle-w11-style/"><u>Secure Your PCs: Automatic Shutdown at Idle, W11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-handling-unable-to-terminate-error-on-pc/"><u>Solutions for Handling 'Unable to Terminate' Error on PC</u></a></li>
<li><a href="https://youtube-web.techidaily.com/y-methods-for-shuffling-youtube-lists-on-devices/"><u>Speedy Methods for Shuffling YouTube Lists on Devices</u></a></li>
<li><a href="https://win11.techidaily.com/starting-again-methodical-steps-for-a-windows-11-new-life/"><u>Starting Again: Methodical Steps for a Windows 11 New Life</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-service-not-responding-error-in-windows/"><u>Steps to Overcome Service Not Responding Error in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/stepwise-guide-for-converting-cr2-images-to-windows-jpeg-files/"><u>Stepwise Guide for Converting CR2 Images to Windows JPEG Files</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-correct-opengl-error-3-in-nvidia-gpus-win1011/"><u>Strategies to Correct OpenGL Error 3 in Nvidia GPUs (Win10/11)</u></a></li>
<li><a href="https://win11.techidaily.com/swift-system-solutions-the-essential-10-tools/"><u>Swift System Solutions: The Essential 10 Tools</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-messages-from-honor-90-by-fonelab-android-recover-messages/"><u>The way to get back lost messages from Honor 90</u></a></li>
<li><a href="https://youtube-data.techidaily.com/form-yt-video-quality-utilizing-the-power-of-wm-maker/"><u>Transform YT Video Quality Utilizing the Power of WM Maker</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshoot-and-stop-manor-lords-game-from-freezing-on-pc/"><u>Troubleshoot and Stop Manor Lords Game From Freezing on PC</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-win11s-capabilities-new-folder-fundamentals/"><u>Unlock Win11's Capabilities: New Folder Fundamentals</u></a></li>
<li><a href="https://driver-install.techidaily.com/update-processor-suitability/"><u>Update Processor Suitability</u></a></li>
<li><a href="https://win11.techidaily.com/win-back-missing-windows-top-tips-for-offscreen-recovery-in-windows-11/"><u>Win Back Missing Windows: Top Tips for Offscreen Recovery in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-teammers-your-screens-puzzle/"><u>Windows Teammers, Your Screen's Puzzle</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-iastordatasvc-32-bit-cpu-drain-on-windows-10-solution-inside/"><u>Winning the Battle Against IAStorDataSvc (32 Bit) CPU Drain on Windows 10 [Solution Inside]</u></a></li>
</ul></div>

