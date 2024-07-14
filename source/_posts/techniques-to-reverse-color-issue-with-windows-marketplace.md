---
title: Techniques to Reverse Color Issue with Windows Marketplace
date: 2024-07-13T10:32:35.634Z
updated: 2024-07-14T10:32:35.634Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Reverse Color Issue with Windows Marketplace
excerpt: This Article Describes Techniques to Reverse Color Issue with Windows Marketplace
keywords: Windows Marketplace Color Fix,Reverse Color Windows Apps,Marketplace Colors Reversed,Resolve Color Issues Windows,Microsoft Windows Color Trick,Uncolorize Window's Store,Correcting Color Windows
thumbnail: https://thmb.techidaily.com/b820d864536876d7d0a61d1c45147aa7dcf60bfd63d25396a1af928aebb65bae.jpg
---

## Techniques to Reverse Color Issue with Windows Marketplace

 If you’re looking for a new app to install on your Windows computer, chances are you’re using Microsoft Store.

 Microsoft Store has the advantage that every listed app is certified by Microsoft, so there’s no chance of hidden malware or virus. Also, you can download movies and TV shows.

 But if the store is displaying a white or black screen, you will not be able to get any new apps or movies. However, you can easily get back Microsoft Store functionality by going through the steps below.

## 1\. Restart the Microsoft Store

 Microsoft Store showing a black or white screen might be due to a temporary glitch. In this case, restarting the app should be enough to fix it.

 Once you close Microsoft Store, press**Ctrl + Shift + Esc** to bring up Task Manager. Then, open the**Processes** tab. Right-click**Microsoft Store** and select**End task** to close any process that might be running in the background.

![Clost Microsoft Store tasks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/end-microsoft-store-1.jpg)

Open Microsoft Store again and check if it’s now working.

 If you're encountering a lot of glitches that go away after a restart, you might be leaving your PC on for too long. Check out these [reasons why you should turn off your PC every night](https://www.makeuseof.com/reasons-why-should-shut-down-computer/) for some inspiration.

## 2\. Check Your Internet Connection

 There might be nothing wrong with Microsoft Store, but you’re simply having an internet connectivity problem. If you’re [dealing with an unstable WiFi connection](https://www.makeuseof.com/tag/fix-slow-unstable-wi-fi-connection/) or downloading a large file, Microsoft Store might display a black or white screen.

 If possible, access the store from a different device. If everything works as usual, the problem is limited to your computer.

## 3\. Run the Microsoft Store Troubleshooter

 Every time you run into an issue on your Windows computer, try running the corresponding troubleshooter. These tools are designed to fix any generic issues that you may encounter.

 So, for any trouble regarding the Microsoft Store, you should run the Windows Store Apps troubleshooter. Here’s how to do it:

1. Right-click the**Start** button and go to**Settings** .
2. Click**System > Troubleshoot** .
3. Select**Other trouble-shooters** .
4. Click the**Run** button next to**Windows Store Apps** .

![Run Windows app troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/store-troubleshooter-1.jpg)

 Windows will search for any issues and fix them automatically. Once the process is complete, try to launch Microsoft Store again.

## 4\. Delete the Microsoft Store Cache

 Like most apps, Microsoft Store uses cache to improve performance. But if the app’s cache somehow gets corrupted, you’ll run into all sorts of issues, including Microsoft Store displaying a black or white background every time you open the app. In this case, deleting the cache should fix the problem.

 Press**Win + R** to bring up a Run dialog. Then, type**wsreset.exe** , and press**Shift + Enter** to run the command with administrative rights.

 This should open a blank Command Prompt window for several seconds. Once it deletes the cache, Windows will close Command Prompt and launch the Microsoft Store app.

## 5\. Run the SFC Tool

 There’s a chance that Microsoft Store isn’t working as usual due to corrupt or damaged system files. To fix the issue, you should run the Windows System File Checker tool.

 First, launch Command Prompt with administrative rights. Then, type**sfc/ scannow** and press**Enter** .

 Make sure you don’t close the Command Prompt window until the scan is complete. Windows will search and automatically replace any corrupt or damaged system files.

![Run SFC scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/sfc-scan-1-3.jpg)

## 6\. Check Your System's Set Time and Region

 Microsoft Store servers must be synced with your system, so everything works properly. If your computer’s time and region, Microsoft Store will show a black, white, or even blue screen.

Go through the below steps to change the Windows region:

1. Press**Win + I** to bring up Windows Settings.
2. From the left-hand menu, click**Time & language** .
3. Select**Language & region** .
4. Set**Country or region** to your current region.
5. Restart your computer and check if Microsoft Store is working.

![Change Windows region](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-region-1.jpg)

 Also, you can [manually change Windows date and time settings](https://www.makeuseof.com/windows-11-change-date-time/) .

## 7\. Re-register the Microsoft Store

 If you couldn’t get Microsoft Store to work using the above solutions, you should re-register the app through PowerShell. The process is quite easy and fast.

 First, launch PowerShell with administrative rights. If you don't know how to do this, refer to [how to open PowerShell with administrative rights](https://www.makeuseof.com/windows-11-powershell-administrator/) .

 Then, copy the **Get-AppXPackage \*WindowsStore\* -AllUsers | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($\_.InstallLocation)\\AppXManifest.xml"}** command, and press**Enter** to run it.

## 8\. Reset Your Windows PC

 If Microsoft Store showing a black or white screen isn’t the only problem you noticed, there might be some deep corruption within your system files. In this case, you could try to [factory reset your Windows PC](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) . This will revert it back to its factory settings, so make sure you back up all essential data.

## Get the Microsoft Store Working Again

 It can be frustrating when you need to install a new app, but Microsoft Store isn’t working. Instead of looking for the same app on not-so-trustworthy websites, you can use the above solutions to fix Microsoft Store.

 But if you can’t find a specific app, there are several websites where you can download apps without compromising your system security.


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
<li><a href="https://win11.techidaily.com/overcoming-windows-error-codes-0xc0000001-guide/"><u>Overcoming Windows Error Codes - 0xC0000001 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-cortana-integration-vivetool-approach/"><u>Optimizing Cortana Integration: ViveTool Approach</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-the-sonic-landscape-a-study-on-sound-forgeutility/"><u>Updated In 2024, The Sonic Landscape A Study on Sound Forgeutility</u></a></li>
<li><a href="https://facebook.techidaily.com/emergency-protocols-for-defeating-fb-account-intrusion/"><u>Emergency Protocols for Defeating FB Account Intrusion</u></a></li>
<li><a href="https://win11.techidaily.com/override-hardware-acceleration-in-widnos-graphics-ordering/"><u>Override Hardware Acceleration in WIDNO's Graphics Ordering</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-closed-caption-fixes-the-win11-way/"><u>Mastering Closed Caption Fixes: The Win11 Way</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-detection-issues-with-razer-on-windows-11/"><u>Overcoming Device Detection Issues with Razer on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-analysis-of-windows-11-settings/"><u>In-Depth Analysis of Windows 11 Settings</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-crafting-your-perfect-minecraft-shelter/"><u>[Updated] Crafting Your Perfect Minecraft Shelter</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-best-itel-frp-bypass-guide-by-drfone-android/"><u>In 2024, Best Itel FRP Bypass Guide</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-crafting-a-jujutsu-kaisen-tiktok-challenge-for-2024/"><u>[New] Crafting a Jujutsu Kaisen TikTok Challenge for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-alter-windows-dashboard-imagery-effortlessly/"><u>How to Alter Windows Dashboard Imagery Effortlessly</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-2024-approved-register-online/"><u>Updated 2024 Approved Register | Online</u></a></li>
<li><a href="https://win11.techidaily.com/from-ios-to-desktop-seamless-sync-with-windows-os/"><u>From iOS to Desktop: Seamless Sync with Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/lowering-intensive-resource-usage-managing-dropboxs-cpu-in-windows/"><u>Lowering Intensive Resource Usage: Managing Dropbox's CPU in Windows</u></a></li>
<li><a href="https://ai-voice.techidaily.com/2024-approved-the-most-direct-guide-to-learning-how-to-clone-your-voice/"><u>2024 Approved The Most Direct Guide to Learning How to Clone Your Voice</u></a></li>
<li><a href="https://win11.techidaily.com/purging-power-users-the-guide-to-default-settings/"><u>Purging Power Users: The Guide to Default Settings</u></a></li>
<li><a href="https://win11.techidaily.com/max-out-your-games-on-windows-the-amd-optimization-guide/"><u>Max Out Your Games on Windows: The AMD Optimization Guide</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-lost-thx-audio-functionality-in-windows/"><u>Restoring Lost THX Audio Functionality in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/instructions-for-setting-windows-backups-against-original-standards/"><u>Instructions for Setting Windows Backups Against Original Standards</u></a></li>
<li><a href="https://extra-information.techidaily.com/desktoponline-passport-picture-creation-10-per-person/"><u>Desktop/Online Passport Picture Creation - 10 Per Person</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/end-screen-magic-free-templates-to-boost-video-appeal-for-2024/"><u>End-Screen Magic  Free Templates to Boost Video Appeal for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-connection-problem-with-mb-services-in-win11/"><u>Overcoming the Connection Problem with MB Services in Win11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-heads-up-on-high-tech-the-best-motorcycle-cam-gear-guide-in-23/"><u>[New] Heads Up on High-Tech - The Best Motorcycle Cam Gear Guide in '23</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-maneuvers-to-navigate-stalled-windows-install-steps/"><u>Masterful Maneuvers to Navigate Stalled Windows Install Steps</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-resolving-roblox-glitches-on-pc/"><u>Guidelines for Resolving Roblox Glitches on PC</u></a></li>
<li><a href="https://win11.techidaily.com/guide-for-old-ribbon-revival-in-new-windows/"><u>Guide for Old Ribbon Revival in New Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/guide-to-new-intel-hd-graphics-on-pcs/"><u>Guide to New Intel HD Graphics on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-to-fix-rpc-fails-on-your-pc/"><u>Master Plan to Fix RPC Fails on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/improving-the-effectiveness-of-win-based-discord-queries/"><u>Improving the Effectiveness of Win-Based Discord Queries</u></a></li>
</ul></div>
