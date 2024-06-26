---
title: "Confronting Clutter: Eliminate OneDrive Symbol From Explorer"
date: 2024-06-25T11:37:55.425Z
updated: 2024-06-26T11:37:55.425Z
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
<li><a href="https://win11.techidaily.com/mastering-directdraw-fixes-in-windows-10-and-11/"><u>Mastering DirectDraw Fixes in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-addressing-windows-onedrive-errors-and-restoring-folder-integration/"><u>Quick Guide: Addressing Windows OneDrive Errors and Restoring Folder Integration</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inaccessible-remove-functionality-on-windows-11-os/"><u>Fixing Inaccessible Remove Functionality on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-android-and-windows-11-with-webcam-capabilities/"><u>Uniting Android and Windows 11 with Webcam Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-window-pc-always-unlocked/"><u>Keep Your Window PC Always Unlocked</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-it-all-the-top-7-ways-to-use-windows-11-effectively/"><u>Optimize It All: The Top 7 Ways to Use Windows 11 Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-windows-tools-for-superior-macos-experience/"><u>Utilizing Windows Tools for Superior macOS Experience</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-win32keygen-threat-symptoms-damage-and-removal-guide/"><u>Unraveling Win32/Keygen Threat: Symptoms, Damage, & Removal Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-7-free-video-editing-programs-that-work-flawlessly/"><u>[New] 2024 Approved  7 Free Video Editing Programs That Work Flawlessly</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-strategies-to-create-stellar-podcast-names-plus-a-curated-list-of-50plus-examples/"><u>[New] Top Strategies to Create Stellar Podcast Names + A Curated List of 50+ Examples</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-obs-and-zoom-synchronization-techniques/"><u>[New] OBS & Zoom Synchronization Techniques</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-chuckle-combat-top-20-tiktok-jokes-and-riddles-for-laughter-lovers/"><u>[Updated] Chuckle Combat  Top 20 TikTok Jokes & Riddles for Laughter Lovers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unlocking-obs-potential-strategies-involving-lut-filters-for-2024/"><u>Unlocking OBS Potential  Strategies Involving LUT Filters for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-turning-youtube-shorts-into-a-stream-of-income/"><u>[Updated] In 2024, Turning YouTube Shorts Into a Stream of Income</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-invigorate-clips-with-top-winter-backdrop-choices/"><u>2024 Approved  Invigorate Clips with Top Winter Backdrop Choices</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-boosting-creativity-the-most-outstanding-free-slide-show-templates/"><u>[Updated] Boosting Creativity  The Most Outstanding Free Slide Show Templates</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/from-captured-moments-to-digital-fame-broadcasting-with-gopro-and-social-platforms/"><u>From Captured Moments to Digital Fame  Broadcasting with GoPro & Social Platforms</u></a></li>
</ul></div>
