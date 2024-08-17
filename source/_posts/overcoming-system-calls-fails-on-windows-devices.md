---
title: Overcoming System Calls Fails on Windows Devices
date: 2024-08-15T23:32:24.420Z
updated: 2024-08-16T23:32:24.420Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming System Calls Fails on Windows Devices
excerpt: This Article Describes Overcoming System Calls Fails on Windows Devices
keywords: Windows Call Fail Resolution,Fixing Syscalls Errors WINDOWS,WinDev Syscall Fail Management,Overcoming Windows SysCall Failure,Syscall Issues in Windows Devices,Preventing System Calls Crashes WINDOWS,Remedy for Windows Call Fails
thumbnail: https://thmb.techidaily.com/c8166e8b96eec7a32e2c5447a156a34a01b3ade6d8a5a024a318a811ffe0e892.jpg
---

## Overcoming System Calls Fails on Windows Devices

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

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Disable Startup Items and Services With a Clean Boot

 Another possibility is that a third-party program or service is conflicting or interfering with the File Explorer processing, causing the “System call failed” error to occur on your PC.

 You can address a software conflict by disabling all third-party startup items and services, which is otherwise the clean booting troubleshooting method. You can apply that troubleshooting method by following the instructions in this guide on [performing a clean boot in Windows](https://www.makeuseof.com/how-perform-clean-boot-windows-10/).

 Restart your PC when you’ve disabled all third-party startup items and services. Then try opening File Explorer again to check if this “System call failed” error continues.

 If the error is fixed after clean booting, it will probably reoccur if you re-enable all startup apps and services again. You can try to identify what’s causing the error by gradually re-enabling items, and then disabling the startup app or service that triggers the issue again.

![Services tab on Windows Configuration menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-services-tab5.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->

## 6\. Restore Windows 11/10 to an Earlier Time

 System Restore is a tool that rolls Windows 11/10 back to a backup image, otherwise called a restore point. Restoring Windows to a date that predated the “System call failed” error on your PC might fix system file issues. Doing so will also remove third-party software installed on your PC after the restoration date that could be causing the issue.

 However, this potential resolution will only be effective if you can select a restoration point that predates the issue. If you don’t have System Restore enabled, you may as well skip to the next possible solution. If you do keep restoration points, try rolling back Windows 11/10 to an earlier time as covered within our [guide to utilizing System Restore](https://www.makeuseof.com/use-system-restore-windows/).

![Restore Points in System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/restore-points-in-system-restore.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->

## 7\. Apply a Factory Reset

 A factory reset will restore your Windows PC to a default (out-of-the-box) system configuration. Applying a factory reset is a drastic potential resolution but one that will likely resolve the “System call failed” error. It will mean you lose user-installed software that will then have to be reinstalled.

 The standard method for applying a factory reset is to utilize the Reset this PC tool. That includes a few options you can select for the reset and one of those is to keep user files. This [how-to reset Windows guide](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) has instructions for applying a factory reset.

![The Keep my files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/reset-this-pc-tool4.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-repairing-an-inoperative-obs-video-feed/"><u>[New] Repairing an Inoperative OBS Video Feed</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-cutting-edge-liquid-simulations-for-gamers/"><u>[Updated] In 2024, Cutting Edge Liquid Simulations for Gamers</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-uncover-top-affordable-video-enhancement-platforms-a-comprehensive-guide-for-2024/"><u>[Updated] Uncover Top Affordable Video Enhancement Platforms - A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-achieving-flawless-audio-to-text-translation-using-google/"><u>2024 Approved  Achieving Flawless Audio to Text Translation Using Google</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-ultimate-t5-eye-cutting-edge-action-video-capture/"><u>2024 Approved  Ultimate T5 Eye  Cutting-Edge Action Video Capture</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Honor Magic 5 Pro | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-xiaomi-13-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Xiaomi 13 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/contrasting-local-and-remote-protocols-for-upgrading-windows-operating-system/"><u>Contrasting Local and Remote Protocols for Upgrading Windows Operating System</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-effective-power-indicators-in-windows/"><u>Crafting Effective Power Indicators in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/defrost-stuck-menus-top-fixes-to-try-today/"><u>Defrost Stuck Menus: Top Fixes to Try Today</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-11s-spotify-connectivity-fails/"><u>Eliminating Windows 11'S Spotify Connectivity Fails</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/final-cut-pro-like-a-pro-5-expert-tips-to-elevate-your-edits-for-2024/"><u>Final Cut Pro Like a Pro 5 Expert Tips to Elevate Your Edits for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixed-silent-outlook-alerts-in-windows-environment/"><u>Fixed Silent Outlook Alerts in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-skirt-sie-and-load-unsigned-drivers-in-windows-oses/"><u>How to Skirt SIE & Load Unsigned Drivers in Windows OSes</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-6s-plus-without-passcode-4-easy-methods-drfone-by-drfone-ios/"><u>How To Unlock iPhone 6s Plus Without Passcode? 4 Easy Methods | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-t2-pro-5g-phone-without-password-by-drfone-android/"><u>How To Unlock Vivo T2 Pro 5G Phone Without Password?</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-10-best-youtube-keyword-tools-to-get-more-views-filmora/"><u>In 2024, 10 Best YouTube Keyword Tools to Get More Views - Filmora</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-realme-narzo-n55-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Realme Narzo N55 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-oppo-a56s-5gfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Oppo A56s 5GFRP Lock</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Vivo Y55s 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Samsung Galaxy M34 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-playback-how-to-start-windows-media-player/"><u>Initiating Playback - How to Start Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-android-pc-connection-step-by-step-guide/"><u>Mastering Android-PC Connection: Step by Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-activation-failures-in-office-suite/"><u>Navigating Activation Failures in Office Suite</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-how-to-translate-instagram-videos-for-global-engagement-for-2024/"><u>New How to Translate Instagram Videos for Global Engagement for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-top-10-best-free-mp4-video-editors-2023/"><u>New In 2024, Top 10 Best Free MP4 Video Editors 2023</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-windows-inactive-session-limit/"><u>Personalizing Windows Inactive Session Limit</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/profile-persona-painting-crafting-an-animated-imagery/"><u>Profile Persona Painting  Crafting an Animated Imagery</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-original-look-for-discoloured-extend-volume/"><u>Reclaim Original Look for Discoloured Extend Volume</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-your-preferred-file-layout-settings/"><u>Reclaiming Your Preferred File Layout Settings</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolution-fixing-nvidia-install-issue/"><u>Resolution: Fixing NVIDIA Install Issue</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-faulty-troubleshooting-tools-in-windows-1011/"><u>Resolving Faulty Troubleshooting Tools in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-ui-proposing-innovations-in-windows-11-widget-design/"><u>Revolutionizing UI: Proposing Innovations in Windows 11 Widget Design</u></a></li>
<li><a href="https://win11.techidaily.com/security-alert-hacked-fingerprint-recognition-on-windows/"><u>Security Alert: Hacked Fingerprint Recognition on Windows?</u></a></li>
<li><a href="https://win11.techidaily.com/squashing-faulty-empty-directory-alert-with-0x80070091-on-windows-11/"><u>Squashing Faulty Empty Directory Alert with #0X80070091 on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/swift-systems-top-strategies-for-fixed-windows-11-wwe-games/"><u>Swift Systems: Top Strategies for Fixed Windows 11 WWE Games</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-transition-text-editor-from-light-to-dark-windows-11-style/"><u>Swiftly Transition Text Editor From Light to Dark, Windows 11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-11-no-response-to-click-events/"><u>Tackling Windows 11: No Response to Click Events</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-10-best-tools-to-bypass-icloud-activation-lock-from-iphone-6s-you-should-try-out-by-drfone-ios/"><u>The 10 Best Tools to Bypass iCloud Activation Lock From iPhone 6s You Should Try Out</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/the-twitch-enthusiasts-recording-guidebook-for-2024/"><u>The Twitch Enthusiast's Recording Guidebook for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/top-windows-fixes-to-unblock-firefox-page-load-blockage/"><u>Top Windows Fixes to Unblock Firefox Page Load Blockage</u></a></li>
<li><a href="https://win11.techidaily.com/traversing-technological-timelines-using-a-windows-7-key-in-windows-11-setup/"><u>Traversing Technological Timelines: Using a Windows 7 Key in Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-essential-tools-your-guide-to-zero-cost-win11-power/"><u>Unveiling Essential Tools: Your Guide to Zero-Cost Win11 Power</u></a></li>
<li><a href="https://win11.techidaily.com/windows-12x-steam-deck-step-by-step-guide/"><u>Windows 12X Steam Deck: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/windows-photos-magic-mastering-ctrl-combinations/"><u>Windows Photos Magic: Mastering Ctrl Combinations</u></a></li>
</ul></div>
