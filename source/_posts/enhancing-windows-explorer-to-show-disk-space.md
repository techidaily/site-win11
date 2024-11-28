---
title: Enhancing Windows Explorer to Show Disk Space
date: 2024-11-26T00:07:28.596Z
updated: 2024-11-27T17:01:56.213Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enhancing Windows Explorer to Show Disk Space
excerpt: This Article Describes Enhancing Windows Explorer to Show Disk Space
keywords: Windows Explore Optimize,Display Disk Space Usage,Check Disk Space Quickly,Visualize Free Disk Space,Enhance File Explorer Views,Monitor System Storage,Streamline Disk Space Viewer
thumbnail: https://thmb.techidaily.com/dfad489a283b58802ec92c884b7191bbab4a284ecb771027987a79177a9a76e0.jpg
---

## Enhancing Windows Explorer to Show Disk Space

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://some-techniques.techidaily.com/new-innovative-drone-flight-q500-typhoon-review/"><u>[New] Innovative Drone Flight - Q500 Typhoon Review</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-finding-inner-voice-how-to-confidently-share-stories-online/"><u>[Updated] In 2024, Finding Inner Voice How to Confidently Share Stories Online</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-maximizing-efficiency-in-remote-group-meetings/"><u>[Updated] In 2024, Maximizing Efficiency in Remote Group Meetings</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-webcam-perfection-in-live-streaming-and-recording/"><u>[Updated] WebCam Perfection in Live-Streaming and Recording</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-strategies-to-elevate-your-video-in-the-trending-topics/"><u>2024 Approved Strategies to Elevate Your Video in the Trending Topics</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-application-launch-disruptions-from-qt-shortfall/"><u>Correcting Application Launch Disruptions From Qt Shortfall</u></a></li>
<li><a href="https://win11.techidaily.com/digitizing-the-decade-old-games-with-dosbox-x/"><u>Digitizing the Decade: Old Games with DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-reactivate-printer-service/"><u>Efficiently Reactivate Printer Service</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-disappeared-battery-life-meter-for-windows-11-computers/"><u>Fixing Disappeared Battery Life Meter for Windows 11 Computers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-xbox-game-pass-0x800700e9-error-in-windows-10-and-11/"><u>How to Fix the Xbox Game Pass 0X800700e9 Error in Windows 10 & 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-get-the-ea-origin-platform-running-smoothly-on-windows-11-machines/"><u>How to Get the EA 'Origin' Platform Running Smoothly on Windows 11 Machines</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-and-resolve-video-crash-on-win1110-pcs/"><u>How to Prevent and Resolve Video Crash on Win11/10 PCs</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-motorola-g24-power-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Motorola G24 Power Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-vivo-t2-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Vivo T2 5GMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-transform-videos-with-tiktok-effects/"><u>In 2024, Transform Videos with TikTok Effects</u></a></li>
<li><a href="https://some-approaches.techidaily.com/intelegerea-politici-privinde-expediertele-si-remasurile-guvernul-si-privirea-publica/"><u>Înțelegerea Politici Privinde Expediertele Și Remașurile: Guvernul Și Privirea Publică</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-solve-windows-11-upgrade-issue-0x800f0922/"><u>Quick Guide to Solve Windows 11 Upgrade Issue 0X800f0922</u></a></li>
<li><a href="https://win11.techidaily.com/secure-savings-on-w11-pro-exclusive-deals-inside/"><u>Secure Savings on W11 Pro - Exclusive Deals Inside</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-when-windows-cant-use-powershell/"><u>What to Do When Windows Can’t Use PowerShell</u></a></li>
</ul></div>

