---
title: Instructions for Setting Windows Backups Against Original Standards
date: 2024-08-15T23:59:42.768Z
updated: 2024-08-16T23:59:42.768Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Instructions for Setting Windows Backups Against Original Standards
excerpt: This Article Describes Instructions for Setting Windows Backups Against Original Standards
keywords: Windows Backup Guide,Standard Backup Setup,Restore Original Files,Windows Data Safety,File Recovery Tips,Regular Backup Schedule,Secure Windows Updates
thumbnail: https://thmb.techidaily.com/f7aa9f91ee25ba92e513ec309ccac0797742d37b71585737d9811b8df3523624.jpg
---

## Instructions for Setting Windows Backups Against Original Standards

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/ree-youtube-money-calculators-calculate-youtube-money-for-2024/"><u>[New] Free YouTube Money Calculators-Calculate YouTube Money for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-smartphone-photography-boosted-the-premier-editing-apps/"><u>[New] Smartphone Photography Boosted  The Premier Editing Apps</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-fun-filled-photography-how-to-use-lens-on-snapchat-for-playfulness/"><u>2024 Approved  Fun-Filled Photography  How To Use Lens on Snapchat for Playfulness</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-high-speed-media-manipulation-a-practical-approach/"><u>2024 Approved  High-Speed Media Manipulation  A Practical Approach</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-temporarily-disable-windows-security-in-windows-11/"><u>4 Ways to Temporarily Disable Windows Security in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/6-fixes-to-try-if-the-right-click-context-menu-gets-stuck-in-windows/"><u>6 Fixes to Try if the Right Click Context Menu Gets Stuck in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/9-quick-ways-to-fix-wwe-2k23-crashing-on-windows-11/"><u>9 Quick Ways to Fix WWE 2K23 Crashing on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-outlook-preview-setup-on-windows-11/"><u>A Comprehensive Guide to Outlook Preview Setup on Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/a-quiet-revolution-mastering-audio-settings-in-gaming/"><u>A Quiet Revolution: Mastering Audio Settings in Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-ram-demand-of-user-service-on-platforms/"><u>Addressing High RAM Demand of User Service on Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/automation-bane-keep-your-windows-backdrop-steady/"><u>Automation Bane: Keep Your Windows Backdrop Steady</u></a></li>
<li><a href="https://win11.techidaily.com/autonomous-windows-update-an-offline-methodology/"><u>Autonomous Windows Update: An Offline Methodology</u></a></li>
<li><a href="https://win11.techidaily.com/beautifying-your-pc-adding-a-weather-image-to-the-system-tray/"><u>Beautifying Your PC: Adding a Weather Image to the System Tray</u></a></li>
<li><a href="https://fox-helps.techidaily.com/benchmark-analysis-djis-drone-phantom-3-for-2024/"><u>Benchmark Analysis  DJI's Drone Phantom 3 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/best-approaches-for-removing-wifi-from-windows-11/"><u>Best Approaches for Removing Wifi From Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-techniques-for-moving-files-in-windows-11/"><u>Boost Productivity: Techniques for Moving Files in Windows 11</u></a></li>
<li><a href="https://win-able.techidaily.com/boost-your-gaming-experience-with-these-techniques-to-improve-frame-rates-in-watch-dogs-legion/"><u>Boost Your Gaming Experience with These Techniques to Improve Frame Rates in Watch Dogs: Legion</u></a></li>
<li><a href="https://win11.techidaily.com/cant-open-exe-files-on-windows-try-these-fixes/"><u>Can’t Open EXE Files on Windows? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-the-mystery-of-infinite-c-drive-usage/"><u>Combatting the Mystery of Infinite C: Drive Usage</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/constructing-unique-instagram-story-panels/"><u>Constructing Unique Instagram Story Panels</u></a></li>
<li><a href="https://win11.techidaily.com/contrasting-features-of-installation-methods-exe-vs-msi-files/"><u>Contrasting Features of Installation Methods: Exe vs Msi Files</u></a></li>
<li><a href="https://win11.techidaily.com/cut-to-perfection-top-video-editors-for-your-win11-pc/"><u>Cut-to-Perfection: Top Video Editors For Your Win11 PC</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1721985528301-elevate-private-messaging-navigate-the-cutting-edge-world-of-secure-ai-powered-communication-with-duckduckgo-and-more/"><u>Elevate Private Messaging: Navigate the Cutting-Edge World of Secure, AI-Powered Communication with DuckDuckGo and More</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-taskbar-design-proposals-for-windows-11s-user-interaction-improvements/"><u>Elevating Taskbar Design: Proposals for Windows 11'S User Interaction Improvements</u></a></li>
<li><a href="https://win11.techidaily.com/essential-techniques-to-revitalize-frozen-spotify-win11/"><u>Essential Techniques to Revitalize Frozen Spotify Win11</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-tecno-camon-30-pro-5g-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Tecno Camon 30 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oneplus-12-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock OnePlus 12 Phone with Broken Screen</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-change-vivo-y55s-5g-2023-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Vivo Y55s 5G (2023) Lock Screen Password?</u></a></li>
<li><a href="https://win11.techidaily.com/installation-steps-for-dolby-atmos-in-windows-11/"><u>Installation Steps for Dolby Atmos in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/instructions-for-completely-getting-rid-of-wsl-on-win-11/"><u>Instructions for Completely Getting Rid of WSL on Win 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/passfab-iphone-6s-plus-backup-unlocker-top-4-alternatives-drfone-by-drfone-ios/"><u>PassFab iPhone 6s Plus Backup Unlocker Top 4 Alternatives | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-compression-and-decompression-tactics-in-windows-cli/"><u>Quick Compression & Decompression Tactics in Windows CLI</u></a></li>
<li><a href="https://driver-download.techidaily.com/quick-download-compatible-lexadrive-usb-software/"><u>Quick Download: Compatible LexaDrive USB Software</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-pcs-login-trail-a-win-flip-guide/"><u>Securing Your PC's Login Trail: A Win-Flip Guide</u></a></li>
<li><a href="https://win11.techidaily.com/solving-steamuidll-not-loaded-problems-in-windows-steam/"><u>Solving “Steamui.dll Not Loaded” Problems in Windows Steam</u></a></li>
<li><a href="https://win11.techidaily.com/solving-uninstall-issues-in-windows-11/"><u>Solving Uninstall Issues in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-manage-secure-boot-and-tpm-settings-on-virtualbox-70/"><u>Step-by-Step Guide to Manage Secure Boot & TPM Settings on VirtualBox 7.0</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-mask-after-dim-display-option-on-pcs/"><u>Steps to Mask After Dim Display Option on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-windowsapps-protection-measures/"><u>Strategies to Overcome WindowsApps Protection Measures</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-0x30017-update-issue-in-windows-os/"><u>Troubleshooting 0X30017 Update Issue in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-your-window-11-potential-7-tips/"><u>Unleash Your Window 11 Potential: 7 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-complexities-of-windows-system-restore-for-easy-rollbacks/"><u>Unraveling the Complexities of Windows System Restore for Easy Rollbacks</u></a></li>
<li><a href="https://win11.techidaily.com/winpc-restoring-lost-connections-with-easy-6-strategies-for-troubleshooting-adapters/"><u>WinPC: Restoring Lost Connections with Easy 6 Strategies for Troubleshooting Adapters</u></a></li>
</ul></div>
