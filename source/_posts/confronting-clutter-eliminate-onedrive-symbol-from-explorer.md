---
title: "Confronting Clutter: Eliminate OneDrive Symbol From Explorer"
date: 2024-06-25T10:30:28.138Z
updated: 2024-06-26T10:30:28.138Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Confronting Clutter: Eliminate OneDrive Symbol From Explorer"
excerpt: "This Article Describes Confronting Clutter: Eliminate OneDrive Symbol From Explorer"
keywords: DropOneDriveIcon,DeleteDriveSymbol,RemoveDriveInExplorer,EliminateOneDriveEye,ClearOneDriveFromIE,EradicateDriveIExplore,DitchDriveSymbolIcon
thumbnail: https://thmb.techidaily.com/8b86753cae048297a750321083f2087f1622c0cfcb3cab69136de042dba1a8be.jpg
---

## Confronting Clutter: Eliminate OneDrive Symbol From Explorer

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
<li><a href="https://win11.techidaily.com/from-boring-to-stunning-switching-themes-in-windows-11-made-simple/"><u>From Boring to Stunning: Switching Themes in Windows 11 Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unresponsive-audio-devices-in-windows/"><u>Troubleshooting Unresponsive Audio Devices in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-win-troubleshooting-toolkit/"><u>The Ultimate Win Troubleshooting Toolkit</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-resolve-microphone-problems-on-pc-and-xbox/"><u>Guidelines to Resolve Microphone Problems on PC & Xbox</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-workflow-essential-windows-shorthand/"><u>Streamline Your Workflow: Essential Windows Shorthand</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-pcs-global-ip-address-with-terminal-commands/"><u>Unveiling PC's Global IP Address with Terminal Commands</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-data-discovery-on-pc-via-everythingapp/"><u>Effortless Data Discovery on PC via EverythingApp</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-windows-colour-mismanagement-issues/"><u>Eliminate Windows Colour Mismanagement Issues</u></a></li>
<li><a href="https://win11.techidaily.com/covert-compression-techniques-for-windows-1011-users/"><u>Covert Compression Techniques for Windows 10/11 Users</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-capture-the-competition-essential-tools-for-gamers-on-pcmac/"><u>[Updated] 2024 Approved  Capture the Competition  Essential Tools for Gamers on Pc/Mac</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-tuneup-snapchat-a-guide-to-musical-video-clips/"><u>In 2024, TuneUp Snapchat  A Guide to Musical Video Clips</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-innovative-strategies-for-captivate-demonstrations/"><u>[New] Innovative Strategies for Captivate Demonstrations</u></a></li>
<li><a href="https://unlock-android.techidaily.com/full-guide-to-unlock-your-vivo-y100i-power-5g-by-drfone-android/"><u>Full Guide to Unlock Your Vivo Y100i Power 5G</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/demystifying-color-grading-with-powerful-luts-for-2024/"><u>Demystifying Color Grading with Powerful LUTs for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-mastering-audio-manipulation-adjusting-speed-and-tone-over-the-internet/"><u>New 2024 Approved Mastering Audio Manipulation Adjusting Speed & Tone Over the Internet</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-top-5-solutions-to-obs-studio-video-editing/"><u>2024 Approved  Top 5 Solutions to OBS Studio Video Editing</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-comic-crafting-mastering-7-cheeky-content-strategies-for-2024/"><u>[New] Comic Crafting  Mastering 7 Cheeky Content Strategies for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-unlock-the-power-of-live-videos-on-facebook/"><u>[New] 2024 Approved  Unlock the Power of Live Videos on Facebook</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/non-game-console-apps-excelling-at-game-recordings-for-2024/"><u>Non-Game Console Apps Excelling at Game Recordings for 2024</u></a></li>
</ul></div>
