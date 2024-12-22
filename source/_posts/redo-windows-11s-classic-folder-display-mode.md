---
title: Redo Windows 11'S Classic Folder Display Mode
date: 2024-12-18T16:27:45.387Z
updated: 2024-12-22T16:53:26.983Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Redo Windows 11'S Classic Folder Display Mode
excerpt: This Article Describes Redo Windows 11'S Classic Folder Display Mode
keywords: Win11ClassicMode,Windows11ClsFldr,ClassiWin11Display,RedoWin11ClfMode,ClassicWindows11View,ClsFldrWin11Redo,11WindowsClassicMode
thumbnail: https://thmb.techidaily.com/6368130d53d4726baee2d761c0d301b46230227e22c8ccd434c4356090bf9d54.jpg
---

## Redo Windows 11'S Classic Folder Display Mode

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-recording.techidaily.com/updated-effortless-methods-to-archive-slideshows-for-2024/"><u>[Updated] Effortless Methods to Archive Slideshows for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-swift-solution-for-effortless-srt-to-text-txt-transform/"><u>[Updated] The Swift Solution for Effortless SRT to Text (TXT) Transform</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-maximizing-fb-instream-ad-impact-configuration-techniques-and-metrics/"><u>2024 Approved Maximizing FB Instream Ad Impact Configuration Techniques and Metrics</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-premier-free-tools-for-easy-jpggif-transformation/"><u>2024 Approved Premier Free Tools for Easy JPG/GIF Transformation</u></a></li>
<li><a href="https://win11.techidaily.com/cross-examining-microsoft-vs-standard-windows-user-accounts/"><u>Cross-Examining Microsoft vs Standard Windows User Accounts</u></a></li>
<li><a href="https://facebook.techidaily.com/discover-how-six-factors-make-facebook-indispayer-for-modern-life/"><u>Discover How Six Factors Make Facebook Indispayer for Modern Life</u></a></li>
<li><a href="https://win11.techidaily.com/displaying-networked-storage-options-on-screen/"><u>Displaying Networked Storage Options on Screen</u></a></li>
<li><a href="https://win11.techidaily.com/easy-deactivation-four-proven-methods-to-cut-off-users-in-win11/"><u>Easy Deactivation: Four Proven Methods to Cut Off Users in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-experience-powertoys-on-win11/"><u>Enhancing User Experience: PowerToys on Win11</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-3-solutions-to-find-your-apple-iphone-12-pro-max-current-location-of-a-mobile-number-drfone-by-drfone-virtual-ios/"><u>In 2024, 3 Solutions to Find Your Apple iPhone 12 Pro Max Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-flashlight-from-apple-iphone-13-pro-lock-screen-drfone-by-drfone-ios/"><u>In 2024, How To Remove Flashlight From Apple iPhone 13 Pro Lock Screen | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ntfs-enablingdisabling-file-compression/"><u>Mastering NTFS: Enabling/Disabling File Compression</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/peak-hours-for-releasing-podcasts-for-2024/"><u>Peak Hours for Releasing Podcasts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-outlook-folder-unreadable-error-steps-for-personal-computers/"><u>Resolve 'Outlook Folder Unreadable' Error: Steps for Personal Computers</u></a></li>
<li><a href="https://win11.techidaily.com/swift-surfing-steps-for-windows-based-network-speed-verification/"><u>Swift Surfing: Steps for Windows-Based Network Speed Verification</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-malwarebytess-failed-execution-calls-on-windows-1011/"><u>Tackling Malwarebytes's Failed Execution Calls on Windows 10/11</u></a></li>
<li><a href="https://win-blog.techidaily.com/update-eliminates-fall-guys-lag-and-freeze-problems-during-gameplay-on-personal-computers/"><u>Update Eliminates Fall Guys Lag and Freeze Problems During Gameplay on Personal Computers</u></a></li>
</ul></div>

