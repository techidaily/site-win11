---
title: How to Reset and Redo Store Registrations in Win 11
date: 2024-06-25T11:33:21.150Z
updated: 2024-06-26T11:33:21.150Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reset and Redo Store Registrations in Win 11
excerpt: This Article Describes How to Reset and Redo Store Registrations in Win 11
keywords: Windows 11 Registration Recovery,Win11 Update Store Settings,Resetting Microsoft Store,Redoing App Registrations,Win11 Store Fixes,Reinstalling Apps in Win11,Restore Win11 App Marketplace
thumbnail: https://thmb.techidaily.com/9f88f4d439bd19afe08962ae532d3a6f41b689b2a4dc10b0fa384c3313d41768.jpg
---

## How to Reset and Redo Store Registrations in Win 11

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
<li><a href="https://win11.techidaily.com/key-to-the-past-windows-11s-historical-files-retrieval/"><u>Key to the Past: Windows 11’S Historical Files Retrieval</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-common-onedrive-issues-on-pc/"><u>Conquering Common OneDrive Issues on PC</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-code-0x800700e9-on-xbox-game-pass-and-windows-11/"><u>Tackling Error Code 0X800700E9 on Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-your-life-top-11-fixes-for-windows-11-issues/"><u>Simplify Your Life: Top 11 Fixes for Windows 11 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-read-only-shackles-of-windows-11/"><u>Breaking Free From the Read-Only Shackles of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/paving-the-way-for-progress-updating-windows-drivers/"><u>Paving the Way for Progress: Updating Windows Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-err0r-code-e1-in-w10w11/"><u>Fixing Err0r: Code E1 in W10/W11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/mobile-guide-embedding-songs-on-your-facebook-page-for-2024/"><u>Mobile Guide  Embedding Songs on Your Facebook Page for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your OnePlus Ace 2 | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-decode-the-mystery-top-7-tiktok-emojis-explored/"><u>[Updated] In 2024, Decode the Mystery  Top 7 TikTok Emojis Explored</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/ultimate-guide-from-honor-magic5-ultimate-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Honor Magic5 Ultimate FRP Bypass</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-free-sustainable-scenes-for-filmmakers/"><u>[Updated] In 2024, Free Sustainable Scenes for Filmmakers</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-premier-mac-4k-monitor-selections-top-10-edition/"><u>In 2024, Premier Mac 4K Monitor Selections  Top 10 Edition</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-how-to-tailor-youtube-thumbnails-for-maximum-impact/"><u>In 2024, How to Tailor YouTube Thumbnails for Maximum Impact</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-2024-approved-top-7-ways-to-promote-twitch-stream/"><u>Updated 2024 Approved Top 7 Ways to Promote Twitch Stream</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-androids-leading-image-editing-does-pickup-reign-supreme/"><u>2024 Approved  Android's Leading Image Editing  Does PickUp Reign Supreme?</u></a></li>
</ul></div>
