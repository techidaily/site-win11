---
title: Regain Access to Microsoft Store Features on PCs
date: 2024-06-25T11:22:43.925Z
updated: 2024-06-26T11:22:43.925Z
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
<li><a href="https://win11.techidaily.com/mastering-windows-uncover-gpo-settings/"><u>Mastering Windows: Uncover GPO Settings</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-resolving-windows-11s-fatal-error/"><u>Deciphering and Resolving Windows 11'S Fatal Error</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-show-more-pins-on-win-11-startscreen/"><u>Techniques to Show More Pins on Win 11 Startscreen</u></a></li>
<li><a href="https://win11.techidaily.com/critical-guide-restoring-lost-logins-in-windows-11/"><u>Critical Guide: Restoring Lost Logins in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-chrome-file-uploading-woes-a-guide-for-windows-devices/"><u>Navigate Chrome File Uploading Woes: A Guide for Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-windows-event-viewer-fixes/"><u>Strategies for Windows Event Viewer Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/10-quick-tips-recognizing-your-xbox-controller-in-windows/"><u>10 Quick Tips: Recognizing Your Xbox Controller in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-removing-epic-games-hub-from-windows-11-a-quick-guide/"><u>Trouble Removing Epic Games Hub From Windows 11: A Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-restart-efficient-three-ways/"><u>Mastering Windows Restart: Efficient Three Ways</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-social-media-showdown-unveiling-similarities-and-differences-between-apps-max-156-chars/"><u>[New] Social Media Showdown  Unveiling Similarities & Differences Between Apps (Max 156 Chars)</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/youtubes-economic-model-month-to-month-income-in-2024/"><u>YouTube's Economic Model  Month-to-Month Income, In 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-what-if-i-accidentally-refreshed-tiktok-in-2024/"><u>[New] What If I Accidentally Refreshed TikTok, In 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-unlock-the-power-of-mp3-conversion-on-windows-a-must-read-article/"><u>Updated In 2024, Unlock the Power of Mp3 Conversion on Windows A Must-Read Article</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-spotifys-1-hitlist-rankings/"><u>[Updated] Spotify's #1 Hitlist Rankings</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-apple-musics-role-in-professional-video-production/"><u>In 2024, Apple Music's Role in Professional Video Production</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-enhancing-twitter-posts-via-facebook-connection/"><u>[Updated] In 2024, Enhancing Twitter Posts via Facebook Connection</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-the-best-free-divx-video-cutting-software/"><u>In 2024, The Best Free Divx Video Cutting Software</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-free-android-video-editing-apps-no-watermark-no-catch/"><u>New Free Android Video Editing Apps No Watermark, No Catch</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/refined-music-mixes-to-amplify-web-videos-for-2024/"><u>Refined Music Mixes to Amplify Web Videos for 2024</u></a></li>
</ul></div>
