---
title: Restoring Natural Windows File Sorting Settings
date: 2024-06-25T11:27:41.548Z
updated: 2024-06-26T11:27:41.548Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Natural Windows File Sorting Settings
excerpt: This Article Describes Restoring Natural Windows File Sorting Settings
keywords: Windows Restore Settings,File Organize Naturally,Windows Default Order,Recover Files By Type,Reorder Windows Files,Fix Windows Sorter Issue,Natural Window Sorting Fix
thumbnail: https://thmb.techidaily.com/6a8b7b3cdb25a03e07ba1819bb3940ce3cb079bf3680cebd2f9e48a956c136d3.jpg
---

## Restoring Natural Windows File Sorting Settings

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

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
6. Similarly, delete the**Bags** folder and close the Registry window.

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
<li><a href="https://win11.techidaily.com/mastering-steam-error-troubleshooting-e84-edition/"><u>Mastering Steam Error Troubleshooting: E84 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-data-views-tabbing-in-windows-explorer/"><u>Streamlining Data Views: Tabbing in Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-io-errors-in-photo-import-from-apple-devices/"><u>Essential Fixes for I/O Errors in Photo Import From Apple Devices</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-faster-downloads-in-microsofts-app-stores/"><u>Mastering Faster Downloads in Microsoft's App Stores</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-obs-studio-audio-silence-fixes-for-w11-pcs/"><u>Reverse OBS Studio Audio Silence: Fixes for W11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-frozen-recycle-icon-status-in-win11/"><u>Resolving Frozen Recycle Icon Status in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/dispel-limitations-escalating-internet-speed-past-100mbps-in-windows/"><u>Dispel Limitations: Escalating Internet Speed Past 100Mbps in Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-best-online-bunches-of-premium-quality-vector-icons/"><u>[Updated] Best Online Bunches of Premium-Quality Vector Icons</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-enhance-engagement-with-these-15-snap-insights/"><u>[New] Enhance Engagement with These 15 Snap Insights</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-mastering-opencv-object-tracking-a-comprehensive-guide-for-beginners-and-experts/"><u>Updated In 2024, Mastering OpenCV Object Tracking A Comprehensive Guide for Beginners and Experts</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-unleash-your-potential-with-instagram-tv-upload/"><u>In 2024, Unleash Your Potential with Instagram TV Upload</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-insta-rotation-rituals-mastering-angles-that-engage-captivate-and-amaze/"><u>[Updated] In 2024, Insta Rotation Rituals  Mastering Angles that Engage, Captivate, and Amaze</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-go-live-on-youtube-from-a-phone-no-need-for-huge-fans-yet/"><u>In 2024, Go Live on YouTube From a Phone, No Need for Huge Fans Yet</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-watch-hulu-outside-us-on-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-the-ultimate-visual-diary-unparalleled-tips-for-documenting-your-sims-stories-in-sims-4/"><u>[New] 2024 Approved  The Ultimate Visual Diary  Unparalleled Tips for Documenting Your Sims' Stories in Sims 4</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-a-step-by-step-approach-to-popularizing-instagram-posts/"><u>2024 Approved  A Step-by-Step Approach to Popularizing Instagram Posts</u></a></li>
</ul></div>
