---
title: Reinstate Your Favorite Microsoft Store for Windows Devices
date: 2024-06-25T11:35:33.167Z
updated: 2024-06-26T11:35:33.167Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstate Your Favorite Microsoft Store for Windows Devices
excerpt: This Article Describes Reinstate Your Favorite Microsoft Store for Windows Devices
keywords: WinStore Restore,MSFT Store Access,Reinstate MSOFT,Windows Device Hub,Devices Store Fix,Microsoft Window Support,Retrieve MStores
thumbnail: https://thmb.techidaily.com/3be6004f814f322eb7c81e59f5f3e6dc5377a1a28f18fb94887b3ff8d1dce543.jpg
---

## Reinstate Your Favorite Microsoft Store for Windows Devices

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://win11.techidaily.com/stop-windows-update-freeze-implementing-effective-fixes/"><u>Stop Windows Update Freeze: Implementing Effective Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-chrome-file-uploading-woes-a-guide-for-windows-devices/"><u>Navigate Chrome File Uploading Woes: A Guide for Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-to-transition-from-stuck-in-windows-1011-s-mode/"><u>Tactics to Transition From Stuck in Windows 10/11 S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-corruption-errors-fixing-file-issues-code-0x80070570-on-windows-11/"><u>Disabling Corruption Errors - Fixing File Issues Code 0X80070570 on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-quality-over-novelties/"><u>Enhancing Windows 11: Quality over Novelties</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-previewable-files-issue-in-outlook-for-personal-computers/"><u>Fixing Non-Previewable Files Issue in Outlook for Personal Computers</u></a></li>
<li><a href="https://win11.techidaily.com/review-of-surface-laptop-go-3s-new-cpu-unchanged-shortcomings/"><u>Review of Surface Laptop Go 3'S New CPU - Unchanged Shortcomings</u></a></li>
<li><a href="https://win11.techidaily.com/resurrect-your-chrome-on-win11-with-ease/"><u>Resurrect Your Chrome on Win11 with Ease!</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-full-enter-key-capabilities-in-win-os/"><u>Regaining Full Enter Key Capabilities in Win OS</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-honor-x50iplus-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Honor X50i+ Phones with/without a PC</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-6-appsservices-to-trace-any-apple-iphone-15-pro-max-location-by-mobile-number-drfone-by-drfone-virtual-ios/"><u>Top 6 Apps/Services to Trace Any Apple iPhone 15 Pro Max Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-from-frame-by-frame-filmmaking-to-financial-flourishing/"><u>In 2024, From Frame-by-Frame Filmmaking to Financial Flourishing</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-efface-markings-iosandroid-apps-for-clear-videos/"><u>[New] 2024 Approved  Efface Markings  IOS/Android Apps for Clear Videos</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-infinix-zero-30-5g-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Infinix Zero 30 5G Phone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/10-best-free-music-recording-software/"><u>10 Best Free Music Recording Software</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-ultimate-guide-to-powerdirector-2024-mastery/"><u>The Ultimate Guide to PowerDirector 2024 Mastery</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oneplus-ace-2v-bootloader-easily-by-drfone-android/"><u>How to Unlock OnePlus Ace 2V Bootloader Easily</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-about-google-pixel-8-pro-frp-bypass-by-drfone-android/"><u>In 2024, About Google Pixel 8 Pro FRP Bypass</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-masterful-bots-to-take-discord-engagement-to-new-heights/"><u>[Updated] Masterful Bots to Take Discord Engagement To New Heights</u></a></li>
</ul></div>
