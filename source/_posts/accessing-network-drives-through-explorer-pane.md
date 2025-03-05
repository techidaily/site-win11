---
title: Accessing Network Drives Through Explorer Pane
date: 2025-03-04T03:54:55.034Z
updated: 2025-03-05T04:39:09.369Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Accessing Network Drives Through Explorer Pane
excerpt: This Article Describes Accessing Network Drives Through Explorer Pane
keywords: Drive Access via Explorer,Explore Network Drives,Remote NDrive Explorer,Windows Explorer NDrives,NDrive Connect Explorer,Explorer NDrive Viewing,Navigate NDrives Explorer
thumbnail: https://thmb.techidaily.com/56f4900e7c7d867bb901f7b64e907d973f9debc0b4d9e6ff3cf0e83ec62a7ce4.jpg
---

## Accessing Network Drives Through Explorer Pane

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
<li><a href="https://fox-glue.techidaily.com/new-adding-media-to-enhance-content-for-2024/"><u>[New] Adding Media to Enhance Content for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-refined-retouches-using-the-eraser-in-photoshop-proficiently/"><u>[New] In 2024, Refined Retouches Using the Eraser in Photoshop Proficiently</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-youtube-moguls-and-millionaires/"><u>[Updated] In 2024, YouTube Moguls and Millionaires</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-swiftly-expand-your-youtube-following-for-minimal-cost/"><u>[Updated] Swiftly Expand Your YouTube Following for Minimal Cost</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-11s-inability-to-open-files-for-writing/"><u>Correcting Windows 11'S Inability to Open Files for Writing</u></a></li>
<li><a href="https://win11.techidaily.com/credential-manager-your-problem-solving-companion/"><u>Credential Manager: Your Problem-Solving Companion</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/definitive-top-5-superlight-cinematography-devices-for-2024/"><u>Definitive Top 5 Superlight Cinematography Devices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/easing-windows-update-restrictions-a-guide-to-uninstalling-apps/"><u>Easing Windows Update Restrictions: A Guide to Uninstalling Apps</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-restoring-touch-key-positions-in-win-11/"><u>Guidelines for Restoring Touch Key Positions in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/increase-visible-pins-in-the-win-11-start-menu/"><u>Increase Visible Pins in the Win 11 Start Menu</u></a></li>
<li><a href="https://win11.techidaily.com/insights-into-pagefilesys-functionality-on-windows-systems/"><u>Insights Into Pagefile.sys Functionality on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/revive-sleeping-pcs-with-keys-and-mice-on-windows-1011/"><u>Revive Sleeping PCs with Keys and Mice on Windows 10/11</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-perfect-blend-of-exercise-tracking-and-music-streaming-discover-the-garmin-vivoactive-3/"><u>The Perfect Blend of Exercise Tracking & Music Streaming: Discover the Garmin Vivoactive 3!</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-oppo-reno-10-proplus-5g-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Oppo Reno 10 Pro+ 5G for Parents | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/top-5-applicazioni-piu-efficienti-per-la-registrazione-dello-schermo-del-computer/"><u>Top 5 Applicazioni Più Efficienti per La Registrazione Dello Schermo Del Computer</u></a></li>
<li><a href="https://discover-best.techidaily.com/top-convertisseur-hevc-encodeur-video-le-plus-efficace-pour-windows-11-et-mac/"><u>Top Convertisseur HEVC - Encodeur Vidéo Le Plus Efficace Pour Windows 11 Et Mac</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-global-precision-advanced-mouse-navigation-via-powertoys/"><u>Unlocking Global Precision - Advanced Mouse Navigation via PowerToys</u></a></li>
</ul></div>

