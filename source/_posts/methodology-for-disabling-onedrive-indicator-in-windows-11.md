---
title: Methodology for Disabling OneDrive Indicator in Windows 11
date: 2024-06-25T09:44:50.024Z
updated: 2024-06-26T09:44:50.024Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methodology for Disabling OneDrive Indicator in Windows 11
excerpt: This Article Describes Methodology for Disabling OneDrive Indicator in Windows 11
keywords: Disable OneDrive Sign,Win11 Stop OneDrive LED,Turn Off OneDrive Icon,End OneDrive Light Display,Deactivate OneDrive Indicator,Suppress OneDrive Status Lamp,Halt Windows 11 OneDrive Glow
thumbnail: https://thmb.techidaily.com/4718cfe78df90fc96fd0823cd6a47f148478c5d534b3bf1b20e29d9f9fc07b91.jpg
---

## Methodology for Disabling OneDrive Indicator in Windows 11

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

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

## How to Show the OneDrive Icon Again in File Explorer

![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

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
<li><a href="https://win11.techidaily.com/immediate-repairs-how-to-tackle-post-windows-update-glitches/"><u>Immediate Repairs: How to Tackle Post-Windows Update Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-resolving-roblox-glitches-on-pc/"><u>Guidelines for Resolving Roblox Glitches on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-effectively-restart-your-windows-graphics-driver/"><u>How to Effectively Restart Your Windows Graphics Driver</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-windows-experience-with-top-5-affordable-car-update-tools/"><u>Elevate Your Windows Experience with Top 5 Affordable Car Update Tools</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-deactivating-nvidias-visual-effects/"><u>Windows Guide: Deactivating NVIDIA's Visual Effects</u></a></li>
<li><a href="https://win11.techidaily.com/from-chaos-to-clarity-manage-all-open-windows-win1110/"><u>From Chaos to Clarity: Manage All Open Windows (Win11/10)</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-tackle-zeroxc000003e-application-errors-in-win1011/"><u>Strategies to Tackle ZeroXc000003e Application Errors in Win10/11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-create-a-youtube-auto-subscribe-link/"><u>[Updated] 2024 Approved  How to Create a YouTube Auto-Subscribe Link</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-top-6-online-audio-extractors/"><u>New 2024 Approved Top 6 Online Audio Extractors</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-8-plus-to-androidios-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone 8 Plus To Android/iOS? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-mastering-instagram-reels-incorporating-music-and-voiceovers/"><u>[New] In 2024, Mastering Instagram Reels  Incorporating Music & Voiceovers</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-the-best-free-video-surveillance-software-a-comprehensive-guide-for-2024/"><u>Updated The Best Free Video Surveillance Software A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-straightforward-video-editing-tools-for-all-for-2024/"><u>New Straightforward Video Editing Tools for All for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-efficient-selections-top-picks-for-6-fb-lite-vids/"><u>[New] Efficient Selections  Top Picks for 6 FB Lite Vids</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-countdown-in-forward-the-counterintuitive-playlist-method/"><u>[Updated] Countdown in Forward  The Counterintuitive Playlist Method</u></a></li>
</ul></div>
