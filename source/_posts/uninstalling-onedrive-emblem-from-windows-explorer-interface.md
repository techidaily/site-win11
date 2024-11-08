---
title: Uninstalling OneDrive Emblem From Windows Explorer Interface
date: 2024-11-06T20:21:52.134Z
updated: 2024-11-07T17:09:31.675Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Uninstalling OneDrive Emblem From Windows Explorer Interface
excerpt: This Article Describes Uninstalling OneDrive Emblem From Windows Explorer Interface
keywords: Uninstall OneDrive Icon,Remove OneDrive File Icon,Delete OneDrive Explorer Emblem,Eliminate OneDrive Windows Icons,Clear OneDrive From Explorer,Dismiss OneDrive Symbols,Free OneDrive Space on PC
thumbnail: https://thmb.techidaily.com/7bdbd3764d17d309bfae3520695cdadc9f0f0ab5ea703a9227f88bc7f132643b.jpg
---

## Uninstalling OneDrive Emblem From Windows Explorer Interface

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134499/19576" target="_top" id="2134499">
  <img src="//a.impactradius-go.com/display-ad/19576-2134499" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134499/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134503/19576" target="_top" id="2134503">
  <img src="//a.impactradius-go.com/display-ad/19576-2134503" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134503/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151883/7443" target="_top" id="2151883">
  <img src="//a.impactradius-go.com/display-ad/7443-2151883" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151883/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.

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
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-elevate-video-consumption-constructing-an-ideal-watch-later-list-on-youtube/"><u>[Updated] 2024 Approved Elevate Video Consumption Constructing an Ideal 'Watch Later' List on YouTube</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-effortless-screen-changes-made-simple/"><u>[Updated] Effortless Screen Changes Made Simple</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-navigating-virtual-language-basics/"><u>2024 Approved Navigating Virtual Language Basics</u></a></li>
<li><a href="https://screen-recording.techidaily.com/cutting-edge-5-online-video-capture-applications-for-2024/"><u>Cutting-Edge 5 Online Video Capture Applications for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-elevation-for-power-users-on-pc/"><u>Enabling Elevation for Power Users on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-file-or-directory-is-corrupted-error-0x80070570-on-windows-11-and-11/"><u>How to Fix the “File or Directory Is Corrupted” Error 0X80070570 on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-microsoft-teams-error-80080300-in-windows-11/"><u>How to Fix the Microsoft Teams Error 80080300 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-portal-elevated-terminal-at-your-fingertips/"><u>Quick Portal: Elevated Terminal at Your Fingertips</u></a></li>
<li><a href="https://os-tips.techidaily.com/simple-guide-on-reinitializing-your-iphone-device/"><u>Simple Guide on Reinitializing Your iPhone Device</u></a></li>
<li><a href="https://win-reviews.techidaily.com/wie-sie-mit-einem-asus-notebook-den-wiederherstellungsmodus-in-windows-11-nutzen-konnen-eine-praktische-anleitung/"><u>Wie Sie Mit Einem Asus-Notebook Den Wiederherstellungsmodus in Windows 11 Nutzen Können: Eine Praktische Anleitung</u></a></li>
<li><a href="https://win11.techidaily.com/windows-shortcuts-gaining-infinite-capabilities/"><u>Windows Shortcuts: Gaining Infinite Capabilities</u></a></li>
</ul></div>

