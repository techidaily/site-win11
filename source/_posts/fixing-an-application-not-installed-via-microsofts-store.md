---
title: Fixing an Application Not Installed via Microsoft's Store
date: 2024-07-13T10:16:16.748Z
updated: 2024-07-14T10:16:16.748Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing an Application Not Installed via Microsoft's Store
excerpt: This Article Describes Fixing an Application Not Installed via Microsoft's Store
keywords: App Install Error Fix,MS Store Download Issue,Uninstall Failed Windows,Troubleshoot App Setup,Resolve Missing Installed App,Microsoft Store Fix,Reinstall Application Steps
thumbnail: https://thmb.techidaily.com/bf80edb76b200416e748e081aeadfa243850d855fed3e04f595dd2c29ba995d4.jpg
---

## Fixing an Application Not Installed via Microsoft's Store

 The Microsoft Store lets you install verified apps securely from its app store. However, when you try to install an app, you may encounter an error that says "this app couldn’t be installed." This can happen with a specific app or all the apps you want to install.

 The problem can be as simple as a corrupted Microsoft Store cache or issues with system files. Here are a few troubleshooting steps to quickly resolve this error and get Microsoft Store working again.

## 1\. Run the Microsoft Store Troubleshooter

![windows store apps troubleshooter 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-store-apps-troubleshooter-1.jpg)

 You can quickly fix common Microsoft Store problems using the Windows Store Apps troubleshooter. It is a built-in troubleshooting utility that can scan and fix issues preventing the Microsoft Store from installing apps.

To run the Windows Store Apps troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Troubleshooter.**
3. Next, click on**Other troubleshooters.**
4. Scroll down and click on the**Run** button for Windows Store Apps. The troubleshooter will perform a scan and recommend fixed. Apply any recommended fixes and check for improvements.

## 2\. Clear and Reset the Windows Store Cache Using WSReset

![wsreset clear microsoft store cache](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/wsreset-clear-microsoft-store-cache.jpg)

 WSReset or Windows Store Reset is a built-in utility to reset or clear Windows Store Cache. Resetting the store cache can help you fix temporary glitches preventing you from installing apps from Microsoft Store.

To reset the Windows Store cache:

1. Press the**Win** key and type**wsreset** .
2. Click on**wsreset** –**run command** from the search result. This will open a black Window that will reset the Windows Store cache. The window will close automatically and launch Microsoft Store.
3. Close Microsoft Store and then relaunch the app to see if the error is resolved.

## 3\. Restart the Microsoft Store Install Service

 Microsoft Store Install service provides support for the Microsoft Store and starts on demand. If the service is disabled, you may not be able to install apps from the store resulting in the "this app couldn’t be installed" message.

 To fix the error, check if the service is running. If not, you can enable it manually using the Services snap-in.

To restart Microsoft Store Install Service:

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** .
3. In the**Services** snap-in, locate the**Microsoft Store Install Service** entry.  
![microsoft store install service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/microsoft-store-install-service-properties.jpg)
4. Right-click on the service entry and select**Properties** .
5. In the**Properties** dialog, check if the**Startup type** is set to**Disabled** .  
![microsoft store install service manual startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/microsoft-store-install-service-manual-startup-type.jpg)
6. If yes, click the**Startup type** drop-down and select**Manual** .  
![microsoft store install service restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/microsoft-store-install-service-restart.jpg)
7. Click**Apply** and**OK** to save the changes.
8. Next, right-click on**Microsoft Store Install Services** and select**Restart** .

 Close the Services snap-in and launch Microsoft Store. Then, try to install the app and check if the error is resolved.

## 4\. Perform a Microsoft Store Repair

![repair microsoft store windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-store-windows-11.jpg)

 You can use the built-in repair tool to fix common issues that may prevent the Microsoft Store from triggering such errors. Follow these steps to repair the Microsoft Store app.

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab in the left pane.
3. Click on**Installed apps** .
4. Next, search for**Microsoft Store.**
5. Click the**three-dots menu** and select**Advanced options.**
6. Scroll down to the**Reset** section.
7. Click on**Repair** and wait for the process to complete.
8. Once done, relaunch Microsoft Store and try to install the app to see if the error is resolved.

## 5\. Manually Reset Microsoft Store Apps

![reset microsoft store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/reset-microsoft-store.jpg)

 You can manually reset the Microsoft Store app from the Settings app. The Reset option will delete all the app data, and you may need to log in to use Microsoft Store again.

To reset Microsoft Store:

1. Press**Win + I t** o open**Settings** .
2. Open the**Apps** tab in the left pane.
3. Click on**Installed apps** to view all the apps installed on your PC.
4. Search for the**Microsoft Store** app.
5. Click the**three-dots menu** and select**Advanced Options.**
6. Scroll down to the**Reset** section.
7. Click on**Reset** and again on the**Reset** button to confirm the action.
8. Once the**reset** is complete, you’ll see a**checkmark** beside the**Reset** button.

 Launch Microsoft Store and sign in with your Microsoft Account if required. Then, try to install the app and check for any improvements.

## 6\. Re-register the Microsoft Store App

![powershell re_register microsoft store app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/powershell-re_register-microsoft-store-app.jpg)

 Another way to fix the "this app couldn’t be installed" error is to re-register the Microsoft Store using PowerShell. Here’s how to do it.

1. Make sure**Microsoft Store** is closed.
2. Next, press the**Win key** and type**powershell** .
3. Right-click on**PowerShell** and select**Run as administrator.**
4. In the PowerShell window, type the following command to re-register the app for the current user:  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
5. Wait for the command to process and close PowerShell. Relaunch Microsoft Store and check if you can install the app without the error.

## 7\. Reinstall the Microsoft Store

 You can reinstall Microsoft Store to fix issues with the app due to corrupt app files or bugs. Since clearing the cache didn’t help, you can perform a reinstall to resolve the error.

 Note that Microsoft Store is a system app. As a result, you cannot uninstall it from the Settings panel. Instead, you’ll need to use the**Get-AppxPackage** cmdlet in PowerShell to remove and reinstall the app.

 Make sure to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before uninstalling Microsoft Store. When something goes awry, you can use the restore point to undo the changes and restore your PC to its current state.

To reinstall Microsoft Store:

1. Press the**Win** key and type**powershell** .
2. Right-click on Windows PowerShell and select**Run as administrator.**  
![remove microsoft store powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/remove-microsoft-store-powershell.jpg)
3. Next, in the PowerShell Windows, type the following command and press Enter:  
`get-appxpackage *store |remove-appxpackage`
4. Once the app is removed, use the following command to reinstall Microsoft Store:  
`Get-AppxPackage -AllUsers Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}  

`
5. Wait for the app to install successfully. Then, type**exit** and press**Enter** to close PowerShell.  
![reinstall microsoft store powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/reinstall-microsoft-store-powershell.jpg)
6. Press**Win** key and type**Microsoft Store** to launch the app.

## Fixing the "This App Couldn’t Be Installed" Error on Windows

 This error is often due to issues with the corrupt app cache and temporary glitches. Use the Windows Store Apps troubleshooter or run the WSreset tool to fix common problems with Microsoft Store. If the issue persists, you can perform a reset or re-register the app to resolve the error.

 That said, if the issue persists with a specific app, you can download the Microsoft Store apps using a third-party service and install them manually on your PC.


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
<li><a href="https://win11.techidaily.com/tips-for-recovering-lost-run-data/"><u>Tips for Recovering Lost Run Data</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/tips-for-adding-mp4-files-from-windows-movie-maker-onto-vimeo-for-2024/"><u>Tips for Adding MP4 Files From Windows Movie Maker Onto Vimeo for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-precision-crafting-win11-self-extractables/"><u>The Path to Precision: Crafting Win11 Self-Extractables</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-turn-off-overlay-effects-in-nvidia-graphics/"><u>How to Turn Off Overlay Effects in NVIDIA Graphics</u></a></li>
<li><a href="https://win11.techidaily.com/fast-setupuninstall-bings-ai-on-win-11-taskbar/"><u>Fast Setup/Uninstall: Bing's AI on Win 11 Taskbar</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/caption-your-video-in-fcpx-a-quick-and-easy-guide-for-2024/"><u>Caption Your Video in FCPX A Quick and Easy Guide for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-itel-p55t-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Itel P55T without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/winmc-lan-connectivity-woes-solutions-explored/"><u>WinMC LAN Connectivity Woes: Solutions Explored</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-beyond-reality-boundaries-the-vr-journey-continues/"><u>2024 Approved  Beyond Reality Boundaries  The VR Journey Continues</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-enhancing-mobile-instagram-videos-velocity-tips/"><u>2024 Approved  Enhancing Mobile Instagram Videos' Velocity (Tips)</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-steam-read-only-barrier-errors-in-windows-11/"><u>Eliminating Steam Read-Only Barrier Errors in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Tecno Camon 20 Premier 5G? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Motorola Edge 2023 | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/streaming-giants-clash-a-detailed-twitchyoutube-analysis/"><u>Streaming Giants Clash  A Detailed Twitch/YouTube Analysis</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-vivo-x100-pro-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Vivo X100 Pro Fingerprint Lock</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-flash-dead-realme-11x-5g-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Realme 11X 5G Safely | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/smoothly-switching-programs-for-your-first-win-11-experience/"><u>Smoothly Switching Programs for Your First Win 11 Experience</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-download-youtube-videos-directly/"><u>2024 Approved  Download YouTube Videos Directly</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-oppo-a18-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Oppo A18 Phones? | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-restore-shadows-in-iphone-hdr-footage-using-premiere-pro-techniques/"><u>2024 Approved  Restore Shadows in iPhone HDR Footage Using Premiere Pro Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-printer-network-errors-in-windows/"><u>Steps to Resolve Printer Network Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-steam-network-access-on-pc-windows/"><u>Unlocking Steam Network Access on PC Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-writable-registry-for-hidden-themes/"><u>Mastering Windows 11' Writable Registry for Hidden Themes</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-iphone-meme-magic/"><u>[New] IPhone Meme Magic</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-new-world-of-windows-11-avoidance-guide-top-8/"><u>Navigating the New World of Windows 11: Avoidance Guide (Top 8)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/recipe-realms-stepwise-food-videography-for-2024/"><u>Recipe Realms  Stepwise Food Videography for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/pathways-to-the-authorization-interface-in-windows-11/"><u>Pathways to the Authorization Interface in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-error-windows-security-cut-by-admin-policies/"><u>Deciphering Error: Windows Security Cut by Admin Policies</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-20-banger-tracks-from-tiktok-influencers-you-need/"><u>[Updated] 2024 Approved  20 Banger Tracks From TikTok Influencers You Need</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-overcoming-windows-1011s-isdonedll-errors/"><u>Deciphering and Overcoming Windows 10/11'S ISDone.dll Errors</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-your-computers-msvcr110dll-void/"><u>Remedying Your Computer’s Msvcr110.dll Void</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-in-tpm-deactivation-for-modern-windows-users/"><u>Triumph in TPM Deactivation for Modern Windows Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-zoom-android-tips-for-starting-and-syncing-meetings-for-2024/"><u>Mastering Zoom  Android Tips for Starting & Syncing Meetings for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/top-windows-compatible-nds-emulators/"><u>Top Windows Compatible NDS Emulators</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/state-of-the-art-gametime-documentation-tools-for-2024/"><u>State-of-the-Art Gametime Documentation Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-dedicated-ram-win-11-edition-guide/"><u>Augmenting Dedicated RAM: Win 11 Edition Guide</u></a></li>
<li><a href="https://win11.techidaily.com/the-13-step-blueprint-to-reactivating-your-windows/"><u>The 13-Step Blueprint to Reactivating Your Windows</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tools-for-managing-users-in-command-prompt/"><u>Essential Tools for Managing Users in Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-window-preview-failures-in-win-810/"><u>Addressing Window Preview Failures in Win 8/10</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-unidentified-devices-issue-in-win-11/"><u>How to Clear Unidentified Devices Issue in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-windows-experience-filter-key-settings/"><u>Customize Your Windows Experience: Filter Key Settings</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-common-errors-in-windows-update-xc004f050/"><u>Bypassing Common Errors in Windows Update Xc004f050</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-boosting-skype-engagement-best-zoom-utilization-techniques/"><u>2024 Approved  Boosting Skype Engagement  Best Zoom Utilization Techniques</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-how-to-record-with-your-macbooks-camera-for-2024/"><u>[Updated] How to Record with Your MacBook's Camera for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastery-of-safaris-picture-in-picture-for-ios-and-macos-for-2024/"><u>Mastery of Safari's Picture-in-Picture for iOS & macOS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/zero-entry-login-remote-desktop-innovations-on-win-11/"><u>Zero-Entry Login: Remote Desktop Innovations on Win 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-top-choices-for-screen-recorders-that-dont-tie-you-down/"><u>[New] 2024 Approved  Top Choices for Screen Recorders That Don't Tie You Down</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-resolving-iomap64-bsod-on-windows-108-devices/"><u>Quick Tips: Resolving IOMap64 BSOD on Windows 10/8 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-removing-windows-defender-error-0x80004004/"><u>Understanding & Removing Windows Defender Error 0X80004004</u></a></li>
<li><a href="https://win11.techidaily.com/quickening-boot-process-windows-11-timeout-reduction-guide/"><u>Quickening Boot Process: Windows 11 Timeout Reduction Guide</u></a></li>
<li><a href="https://win11.techidaily.com/five-methods-for-protecting-your-pc-avoiding-bitlocker/"><u>Five Methods for Protecting Your PC: Avoiding BitLocker</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-guide-to-android-slow-motion-video-magic/"><u>2024 Approved  The Ultimate Guide to Android Slow Motion Video Magic</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-tailored-sound-rate-on-youtube-desktopmobile/"><u>[Updated] Tailored Sound Rate on YouTube (Desktop/Mobile)</u></a></li>
<li><a href="https://win11.techidaily.com/managing-your-digital-life-restarting-apps-in-windows-11/"><u>Managing Your Digital Life: Restarting Apps in Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-discover-the-best-6-apps-to-supercharge-your-instagram-reels/"><u>[New] Discover the Best 6 Apps to Supercharge Your Instagram Reels</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-no-support-errors-5-effective-steps/"><u>Navigating Windows No-Support Errors: 5 Effective Steps</u></a></li>
<li><a href="https://win11.techidaily.com/1719368082467-switch-off-windows-11-defender-firewall-now/"><u>Switch Off Windows 11 Defender Firewall Now</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-access-barriers-top-solutions/"><u>Navigating Through Windows Access Barriers: Top Solutions</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-10-best-romance-anime-movies-you-need-to-watch-for-2024/"><u>New 10 Best Romance Anime Movies You Need to Watch for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-enable-startup-diagnostics/"><u>A Step-by-Step Guide to Enable Startup Diagnostics</u></a></li>
</ul></div>
