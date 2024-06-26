---
title: Displaying Networked Storage Options on Screen
date: 2024-06-25T10:12:09.347Z
updated: 2024-06-26T10:12:09.347Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-widget-integration-into-windows-11/"><u>Mastering the Art of Widget Integration Into Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-code-a00f425d-on-windows-11-camera-app/"><u>Resolving Error Code A00F425D on Windows 11 Camera App</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tactics-avoiding-counterfeit-creations-on-microsofts-platform/"><u>Tech Tactics: Avoiding Counterfeit Creations on Microsoft's Platform</u></a></li>
<li><a href="https://win11.techidaily.com/making-your-desktop-more-dynamic-activate-windows-11-widget-bar/"><u>Making Your Desktop More Dynamic: Activate Window's 11 Widget Bar</u></a></li>
<li><a href="https://win11.techidaily.com/from-vanished-panes-to-visible-windows-essential-steps-for-recovering-hidden-screens-6-ways/"><u>From Vanished Panes to Visible Windows: Essential Steps for Recovering Hidden Screens (6 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-non-persistent-nvidia-panel-changes/"><u>Correcting Non-Persistent Nvidia Panel Changes</u></a></li>
<li><a href="https://win11.techidaily.com/the-starting-line-in-diablo-basic-play-wisdom/"><u>The Starting Line in Diablo: Basic Play Wisdom</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-htc-u23-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for HTC U23 | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-audience-favourite-debate-which-is-better-black-gopro-or-sony-fdr-x1000v/"><u>2024 Approved  Audience Favourite Debate  Which Is Better, Black GoPro or Sony FDR-X1000V?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-most-effective-ways-to-bypass-iphone-xr-activation-lock-by-drfone-ios/"><u>In 2024, The Most Effective Ways to Bypass iPhone XR Activation Lock</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-do-i-stop-someone-from-tracking-my-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do I Stop Someone From Tracking My Oppo Reno 11F 5G? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-tailoring-lengthy-content-for-youtube-excellence/"><u>In 2024, Tailoring Lengthy Content for YouTube Excellence</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-boost-communication-how-to-use-google-hangouts-on-mobile-for-2024/"><u>[Updated] Boost Communication  How to Use Google Hangouts on Mobile for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/oppo-reno-11-pro-5g-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Oppo Reno 11 Pro 5G Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/elevate-podcast-quality-with-advanced-garageband-editing-methods-for-2024/"><u>Elevate Podcast Quality with Advanced GarageBand Editing Methods for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-itel-a05s-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Itel A05s</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>