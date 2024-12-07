---
title: Reverting Custom Sort and Group Order of Files
date: 2024-12-03T23:22:51.071Z
updated: 2024-12-06T17:34:35.933Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reverting Custom Sort and Group Order of Files
excerpt: This Article Describes Reverting Custom Sort and Group Order of Files
keywords: File Reordering Tips,Custom File Arrangement,Revise File Sort Method,Alter Grouped Files,Change File Priority,Modify File Hierarchy,Adjust File Sequence
thumbnail: https://thmb.techidaily.com/6395a405feac0920efaceeee04a9b0803cb7c1fce78f830a62381ffd05e1b2e3.jpg
---

## Reverting Custom Sort and Group Order of Files

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Run a Batch File to Reset Folder View Settings to Default

 Resetting the Folder View Settings with this method requires creating and running a batch file. This will reset the settings for all folders across your computer. Here's how to do it:

1. Right-click on your desktop and select**New > Text Document** .
2. Name it**ResetFolderViewSettings** and press Enter to save it.
3. Open the newly created text file in Notepad or any other text editor of your choice.
4. Now copy and paste the following code into the file:  
`@echo off  

:: Resets folder view settings, window size and position of all folders  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\BagMRU" /F  
Reg Delete "HKCU\SOFTWARE\Classes\Local Settings\Software\Microsoft\Windows\Shell\Bags" /F  

:: To reset "Apply to Folders" views to default for all folder types  
REG Delete "HKCU\Software\Microsoft\Windows\CurrentVersion\Explorer\Streams\Defaults" /F  

:: To reset size of details, navigation, preview panes to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\GlobalSettings\Sizer" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Modules\NavPane" /F  

:: To reset size of Save as amd Open dialogs to default for all folders  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDOpen" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CIDSave" /F  
Reg Delete "HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\ComDlg32" /F  

:: To kill and restart explorer process  
taskkill /f /im explorer.exe  
start explorer.exe`
5. After adding the code, click**File** in the top menu, then select**Save As** .
6. Now select**All Files** in the Save as type menu, and add**.bat** to the end of the file’s name.  
![Run a Batch File to Reset Folder View Settings to Default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-a-batch-file-to-reset-folder-view-settings-to-default.jpg)
7. From the left pane, select**Desktop** as the location.
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Reset Folder View Settings to Default Using Registry Editor

 The last method to reset Folder View settings involves using the Windows Registry Editor. You should only use this method if you are an experienced user and know how it works, since messing with its keys could cause serious problems. To avoid data loss, you must[create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before continuing.

 To reset folder view settings using the registry editor, do the following:

1. Press**Win + R** on your keyboard to[open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the text box and press Enter. This will[open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/) .
3. Navigate to the following location:  
HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell
4. In the left sidebar, right-click on the**BagMRU** folder and select**Delete.**  
![Reset Folder View Settings to Default Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-using-registry-editor.jpg)
5. Click**Yes** when asked to confirm your action.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Reset Folder View Settings to Default

 Folder View on Windows allows users to customize their view of files and folders. This includes settings such as the file size information, restoring the previous folder when logging in, and automatically entering words when searching.

 However, if you have changed the View settings, this guide will help you reset Folder Options to its default.

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
<li><a href="https://fox-glue.techidaily.com/new-professionals-palette-prowess-color-command-secrets-for-2024/"><u>[New] Professionals' Palette Prowess - Color Command Secrets for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-elevate-your-youtube-presentations-with-imovie-editing-skills-for-2024/"><u>[Updated] Elevate Your YouTube Presentations with iMovie Editing Skills for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-android-sound-recording-without-root-simple-guide/"><u>2024 Approved Android Sound Recording Without Root [Simple Guide]</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevating-your-videos-visual-impact-youtubthumbnail-design-on-macos/"><u>Elevating Your Video's Visual Impact YoutubThumbnail Design on macOS</u></a></li>
<li><a href="https://win-howtos.techidaily.com/enhancing-your-gaming-experience-enabling-directx-11-on-incompatible-video-cards/"><u>Enhancing Your Gaming Experience: Enabling DirectX 11 on Incompatible Video Cards</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/high-speed-windows-photoviewer-for-2024/"><u>High-Speed Windows Photoviewer for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-infinix-note-30-vip-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Infinix Note 30 VIP Devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-custom-snapping-windows-powertoys-guide/"><u>Mastering Custom Snapping: Windows' PowerToys Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-control-of-file-deletion-prompts/"><u>Mastering the Control of File Deletion Prompts</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-missing-devices-from-razers-synapse-in-windows/"><u>Quick Fix for Missing Devices From Razer's Synapse in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/regain-lost-speaker-level-settings-post-system-changes/"><u>Regain Lost Speaker Level Settings Post-System Changes</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-google-pixel-8-pro-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Google Pixel 8 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/through-the-looking-glass-reevaluating-rights-with-edges-restrictions/"><u>Through the Looking Glass: Reevaluating Rights with Edge's Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/vigorously-vault-into-victory-new-folders-in-win11/"><u>Vigorously Vault Into Victory: New Folders in Win11</u></a></li>
</ul></div>

