---
title: Incorporating New Folders Into Explorer's Interface
date: 2024-06-25T10:24:48.629Z
updated: 2024-06-26T10:24:48.629Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Incorporating New Folders Into Explorer's Interface
excerpt: This Article Describes Incorporating New Folders Into Explorer's Interface
keywords: Explore Explorer Modify,Adding Folder Windows,Changing Explore Layout,Explorer Interface Update,Folder Navigation Tool,Integrating New Directories,Altering Explorer Views
thumbnail: https://thmb.techidaily.com/f0922cdea4398af9eb93c3915c9d932ac3a495368c2166a8e69e3bccbb692700.jpg
---

## Incorporating New Folders Into Explorer's Interface

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/remedying-media-player-server-crashes/"><u>Remedying Media Player Server Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-power-management-tools-for-windows-devices/"><u>Unlocking Power Management Tools for Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-system-call-failed-error-on-windows-10-and-11/"><u>How to Fix the “System Call Failed” Error on Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-persistent-boot-related-windows-audio-failures/"><u>Eliminate Persistent Boot-Related Windows Audio Failures</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-control-over-your-screen-amidst-the-dark/"><u>Reclaim Control Over Your Screen Amidst the Dark</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-your-windows-environment-adding-to-the-desktop-menu/"><u>Personalizing Your Windows Environment: Adding to the Desktop Menu</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-maneuvers-to-navigate-stalled-windows-install-steps/"><u>Masterful Maneuvers to Navigate Stalled Windows Install Steps</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-sound-revolution-embrace-dolby-atmos/"><u>Win 10/11 Sound Revolution: Embrace Dolby Atmos</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-better-performance-on-roblox-windows-edition/"><u>Elevate Your Gaming: Better Performance on Roblox Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-steam-sync-errors-in-windows/"><u>Remedying Steam Sync Errors in Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-ultimate-top-10-tools-for-professional-tiktok-editors-pc/"><u>[New] Ultimate Top 10 Tools for Professional TikTok Editors (PC)</u></a></li>
<li><a href="https://extra-information.techidaily.com/unlock-your-creativity-with-top-title-methods/"><u>Unlock Your Creativity with Top Title Methods</u></a></li>
<li><a href="https://fox-blue.techidaily.com/10plus-iconic-ae-text-techniques-for-professionals/"><u>10+ Iconic AE Text Techniques for Professionals</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-top-25-social-stars-essential-instagram-icons-for-2024/"><u>[Updated] Top 25 Social Stars  Essential Instagram Icons for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unparalleled-live-tv-experience-with-local-channels/"><u>2024 Approved  Unparalleled Live TV Experience with Local Channels</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-streamlining-twitter-media-on-instagram-platforms/"><u>In 2024, Streamlining Twitter Media on Instagram Platforms</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-vivo-s18e-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Vivo S18e | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/download-and-audit-voice-recordings/"><u>Download & Audit Voice Recordings</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-tecno-phantom-v-fold-device-sim-by-drfone-android/"><u>Easily Unlock Your Tecno Phantom V Fold Device SIM</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-the-ultimate-list-10-premier-microphone-apps-for-windows-users/"><u>New 2024 Approved The Ultimate List 10 Premier Microphone Apps for Windows Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>