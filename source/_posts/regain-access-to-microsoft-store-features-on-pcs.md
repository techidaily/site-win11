---
title: Regain Access to Microsoft Store Features on PCs
date: 2024-06-25T09:43:23.378Z
updated: 2024-06-26T09:43:23.378Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regain Access to Microsoft Store Features on PCs
excerpt: This Article Describes Regain Access to Microsoft Store Features on PCs
keywords: Microsoft Store Reentry,Gain MSFT Store Access,Restore Microsoft Pc Features,Regain MSO Store Functionality,Recover MS Windows Store Features,Resume Windows Store Use,Reactivate Microsoft Store on PC
thumbnail: https://thmb.techidaily.com/0a18a6b406ce9f21eda937adac64825b459ee3a87d13a642256000f5335eb2cc.jpg
---

## Regain Access to Microsoft Store Features on PCs

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
<li><a href="https://win11.techidaily.com/step-by-step-guide-for-deleting-ms-edge-win11/"><u>Step-by-Step Guide for Deleting MS Edge Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-spiritual-command-center-of-windows-11-os/"><u>Unlocking The Spiritual Command Center of Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/halting-unintentional-launches-of-microsofts-storeapp/"><u>Halting Unintentional Launches of Microsoft's StoreApp</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-studio-2-the-artists-dream-device-unveiled/"><u>Surface Laptop Studio 2: The Artist's Dream Device Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/festive-fireworks-christmas-window-gifts-via-mstore/"><u>Festive Fireworks: Christmas Window Gifts via MSTORE</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-auto-opens-on-microsofts-marketplace-app/"><u>Ceasing Auto-Opens on Microsoft's Marketplace App</u></a></li>
<li><a href="https://win11.techidaily.com/5-creative-ways-to-transform-windows-for-a-mac-appearance/"><u>5 Creative Ways to Transform Windows for a Mac Appearance</u></a></li>
<li><a href="https://win11.techidaily.com/trimming-down-excessive-ntoskrnlexe-utilization/"><u>Trimming Down Excessive Ntoskrnl.exe Utilization</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-systems-replacing-aged-windows-drivers-efficiently/"><u>Streamlining Systems: Replacing Aged Windows Drivers Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-valorant-gameplay-fps-fixes-and-tips/"><u>Elevate Valorant Gameplay: FPS Fixes and Tips</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/unleash-fcpx-top-10-free-plugin-essentials-for-2024/"><u>Unleash FCPX Top 10 Free Plugin Essentials for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-infinix-note-30-vip-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Infinix Note 30 VIP Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ultimate-guide-leading-4k-uhd-blu-ray-devices/"><u>Ultimate Guide  Leading 4K UHD Blu-Ray Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-oppo-a78-5g-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/top-10-economical-video-conferencing-applications-for-2024/"><u>Top 10 Economical Video Conferencing Applications for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/how-to-blur-faces-in-photos-and-videos-a-step-by-step-tutorial/"><u>How to Blur Faces in Photos and Videos A Step-by-Step Tutorial</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-cutting-edge-8-streaming-selectors/"><u>[New] 2024 Approved  Cutting-Edge 8 Streaming Selectors</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-the-essentials-of-real-time-tweets-on-twitter-for-2024/"><u>[Updated] The Essentials of Real-Time Tweets on Twitter for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/leading-win11-screen-recording-apps-ranked-top-15/"><u>Leading Win11 Screen Recording Apps Ranked (Top 15)</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-dive-deep-into-stardews-heart-with-our-guide-to-ginger-isle/"><u>2024 Approved  Dive Deep Into Stardew's Heart with Our Guide to Ginger Isle</u></a></li>
</ul></div>
