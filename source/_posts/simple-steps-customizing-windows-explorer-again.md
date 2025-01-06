---
title: "Simple Steps: Customizing Windows Explorer Again"
date: 2025-01-01T20:32:42.278Z
updated: 2025-01-06T16:29:35.901Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Simple Steps: Customizing Windows Explorer Again"
excerpt: "This Article Describes Simple Steps: Customizing Windows Explorer Again"
keywords: Customize WinExplorer,Personalize File Explorer,Windows Explorer Tips,Explore Windows Settings,Optimize File Explorer,Adjust WinExplorer Views,Enhance File Explorer UI
thumbnail: https://thmb.techidaily.com/720039bdcfeba97eefefa9824f21f9715183b78c763bbf782b71c474fcdd45b6.jpg
---

## Simple Steps: Customizing Windows Explorer Again

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-access.techidaily.com/updated-download-without-risks-the-pathway-to-secure-free-vlc-on-macos/"><u>[Updated] Download without Risks The Pathway to Secure, Free VLC on macOS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instagram-media-techniques-for-mp3-extraction/"><u>[Updated] Instagram Media Techniques for Mp3 Extraction</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-preferred-choices-affordable-channels-for-newbie-monetizers/"><u>2024 Approved Preferred Choices Affordable Channels for Newbie Monetizers</u></a></li>
<li><a href="https://extra-hints.techidaily.com/comprehensive-overview-merging-srt-with-mp4-files-and-videos-for-2024/"><u>Comprehensive Overview Merging SRT with MP4 Files and Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/customize-smartfilter-settings-for-secure-web-browsing/"><u>Customize SmartFilter Settings for Secure Web Browsing</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-pin-problems-and-fixes/"><u>Decoding Window's PIN Problems & Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/direct-paths-to-iis-explorer-in-windows-web-services/"><u>Direct Paths to IIS Explorer in Windows Web Services</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/eliminate-your-yahoo-email-for-good-detailed-steps-to-account-deletion/"><u>Eliminate Your Yahoo Email For Good: Detailed Steps to Account Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-and-modifying-proxy-settings-in-windows-11-os/"><u>Exploring and Modifying Proxy Settings in Windows 11 OS</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-oneplus-nord-3-5g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from OnePlus Nord 3 5G to New Android? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-my-spouse-from-spying-on-my-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop My Spouse from Spying on My Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-the-quake-setting-on-windows-terminal/"><u>Initiating the Quake Setting on Windows Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-username-alterations-in-modern-windows/"><u>Mastery of UserName Alterations in Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-tailor-the-dynamic-background-picture-of-windows/"><u>Swiftly Tailor the Dynamic Background Picture of Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/top-value-picks-identifying-the-most-affordable-video-game-sites/"><u>Top Value Picks: Identifying the Most Affordable Video Game Sites</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlocking-better-performance-discover-the-7-crucial-windows-configurations-that-must-stay-on-for-optimal-use/"><u>Unlocking Better Performance: Discover the 7 Crucial Windows Configurations That Must Stay On for Optimal Use</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-ai-potential-for-enhanced-windows-applications/"><u>Unveiling AI Potential for Enhanced Windows Applications</u></a></li>
</ul></div>

