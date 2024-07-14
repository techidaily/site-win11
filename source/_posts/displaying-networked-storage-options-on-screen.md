---
title: Displaying Networked Storage Options on Screen
date: 2024-07-13T10:19:14.047Z
updated: 2024-07-14T10:19:14.047Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Displaying Networked Storage Options on Screen
excerpt: This Article Describes Displaying Networked Storage Options on Screen
keywords: Storage Showcase,NetStor Display,Storage Access,InterNetwork Storage,DataShare Views,Networked Storage,ProStorage Network
thumbnail: https://thmb.techidaily.com/9929e26ad232462fb3012e528ec110b36cc8e34a7ab835cf659d05f21b4127d5.jpg
---

## Displaying Networked Storage Options on Screen

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

 Then copy and paste the below text into Notepad:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"  
"System.IsPinnedToNamespaceTree"=dword:00000001  
"SortOrderIndex"=dword:00000050  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\DefaultIcon]  
@=hex(2):69,00,6d,00,61,00,67,00,65,00,72,00,65,00,73,00,2e,00,64,00,6c,00,6c,\  
  00,2c,00,2d,00,33,00,32,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\InProcServer32]  
@=hex(2):43,00,3a,00,5c,00,57,00,49,00,4e,00,44,00,4f,00,57,00,53,00,5c,00,73,\  
  00,79,00,73,00,74,00,65,00,6d,00,33,00,32,00,5c,00,73,00,68,00,65,00,6c,00,\  
  6c,00,33,00,32,00,2e,00,64,00,6c,00,6c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance]  
"CLSID"="{0E5AAE11-A475-4c5b-AB00-C66DE400274E}"  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance\InitPropertyBag]  
"Attributes"=dword:00000011  
"TargetFolderPath"=hex(2):44,00,3a,00,5c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\ShellFolder]  
"FolderValueFlags"=dword:00000028  
"Attributes"=dword:f080004d  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=dword:00000001  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"`

 Press **Ctrl + S**, name the file **add-d-drive-file-explorer.reg**, and then click **Save**. Don’t forget to add the REG file extension to let Windows know it’s working with a Registry file.

![saving a registry file in Notepad on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/save-reg-file-add-drive-nav-pane.jpg)

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

 The D: drive should now be visible in the bottom part of the Navigation pane.

## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/unveiling-and-solving-roblox-errors-tied-to-account-restrictions/"><u>Unveiling and Solving Roblox Errors Tied to Account Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-performance-and-functionality-with-alomwares-tools/"><u>Optimize Performance & Functionality with AlomWare's Tools</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-try-connecting-error-on-windows-11-devices/"><u>Conquering Try Connecting Error on Windows 11 Devices</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-lock-apps-on-infinix-note-30-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Infinix Note 30 to Protect Your Individual Information</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-streamlining-audio-capture-in-windows-11/"><u>In 2024, Streamlining Audio Capture in Windows 11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-in-this-article-ill-share-to-you-some-of-the-skin-care-vlog-ideas-for-you-to-start-doing-a-skin-care-review-on-your-youtube-channel-bu/"><u>Updated 2024 Approved In This Article Ill Share to You some of the Skin Care Vlog Ideas for You to Start Doing a Skin Care Review on Your YouTube Channel. But Before that Ill Share with You How Important Is Skin Care?</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-free-end-credits-excellence-top-6-tutorials/"><u>[New] 2024 Approved  Free End Credits Excellence  Top 6 Tutorials</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-overcoming-black-screens-in-youtube-content/"><u>[New] 2024 Approved  Overcoming Black Screens in YouTube Content</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-internal-audio-faults-in-audacity-wos-edition/"><u>Dissecting Internal Audio Faults in Audacity, WOS Edition</u></a></li>
<li><a href="https://win11.techidaily.com/traversing-through-system-failsafe-files-after-blue-screen/"><u>Traversing Through System Failsafe Files After Blue Screen</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-stealthy-speakers-sanctuary-discovering-quiet-voice-apps-androidios/"><u>In 2024, Stealthy Speakers' Sanctuary  Discovering Quiet Voice Apps (Android/iOS)</u></a></li>
<li><a href="https://win11.techidaily.com/ace-at-tech-how-to-revitalize-your-pcs-apps/"><u>Ace at Tech: How to Revitalize Your PC's Apps</u></a></li>
<li><a href="https://win11.techidaily.com/gpu-strain-tested-the-most-effective-win-utilities-ranked/"><u>GPU Strain Tested: The Most Effective Win Utilities Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-era-of-taskbars-proposing-key-improvements-to-microsofts-design/"><u>A New Era of Taskbars: Proposing Key Improvements to Microsoft's Design</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-samsung-galaxy-s24plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/regain-missing-windows-storage-access/"><u>Regain Missing Windows Storage Access</u></a></li>
<li><a href="https://win11.techidaily.com/tactical-steps-to-evade-windows-account-prompts/"><u>Tactical Steps to Evade Windows Account Prompts</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-ultimate-free-switch-console-simulations-for-2024/"><u>[New] Ultimate Free Switch Console Simulations for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/ultimate-list-of-accurate-3ds-pc-simulations/"><u>Ultimate List of Accurate 3Ds PC Simulations</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-ditch-sony-vegas-find-a-better-video-editing-solution-for-your-windows-pc-for-2024/"><u>Updated Ditch Sony Vegas Find a Better Video Editing Solution for Your Windows PC for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-plugged-inspection-error-for-audio-hardware-on-winos/"><u>Fixing Plugged Inspection Error for Audio Hardware on WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-esd-and-its-transformation-into-iso-format-for-pcs/"><u>Understanding ESD and Its Transformation Into ISO Format for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/booting-into-safety-6-ways-to-enter-windows-11s-safe-mode/"><u>Booting Into Safety: 6 Ways to Enter Windows 11'S Safe Mode</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-sizzling-tweetstorms-americas-favorites/"><u>[Updated] In 2024, Sizzling Tweetstorms  America's Favorites</u></a></li>
<li><a href="https://win11.techidaily.com/removing-intrusive-edge-toolbar-items/"><u>Removing Intrusive Edge Toolbar Items</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-essential-elements-missing-windows-error/"><u>Overcoming 'Essential Elements Missing' Windows Error</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-essential-ps2-emulators-for-ios-devices/"><u>2024 Approved  Essential PS2 Emulators for IOS Devices</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-top-choices-in-custom-discord-fonts-mobile-devices/"><u>[New] In 2024, Top Choices in Custom Discord Fonts - Mobile Devices</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-elevate-your-marketing-game-free-50-youtube-adornments-here/"><u>2024 Approved  Elevate Your Marketing Game - Free 50 YouTube Adornments Here</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-breakthrough-turned-breach-windows-hellos-future/"><u>Biometric Breakthrough Turned Breach: Windows Hello's Future?</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-essential-mp3-recording-apps-a-list-of-the-top-5-best-on-todays-market/"><u>New Essential MP3 Recording Apps A List of the Top 5 Best on Todays Market</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-xiaomi-redmi-note-12r-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Xiaomi Redmi Note 12R without App | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-assessing-the-riches-of-mr-beast/"><u>2024 Approved  Assessing the Riches of Mr. Beast</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-the-ultimate-path-to-a-thriving-instagram-community/"><u>[Updated] In 2024, The Ultimate Path to a Thriving Instagram Community</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-to-unlock-your-windows-pin/"><u>Efficient Methods to Unlock Your Windows PIN</u></a></li>
<li><a href="https://win11.techidaily.com/minimalist-pc-large-space-slight-lag/"><u>Minimalist PC - Large Space, Slight Lag</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-tracking-and-managing-network-data-using-netstat-in-win11/"><u>Master the Art of Tracking and Managing Network Data Using Netstat in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-xpatch-fixes-for-error-0x80073712/"><u>Mastering Windows XPatch Fixes for Error 0X80073712</u></a></li>
</ul></div>
