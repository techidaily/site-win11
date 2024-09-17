---
title: Restoring Basic Settings for Your Windows Explore
date: 2024-09-10T01:17:08.717Z
updated: 2024-09-16T16:04:33.550Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Basic Settings for Your Windows Explore
excerpt: This Article Describes Restoring Basic Settings for Your Windows Explore
keywords: WinXp Sets Restore,Explorer Config Fix,Update OS Search Ease,Default Browser Tuneup,SafeExplorer Settings,Windows Default Tuning,Explore Basic Retune
thumbnail: https://thmb.techidaily.com/1505d6f4180ef3234fcf66cf60e394c6b774b52749b9718fd3308deebd93e5f0.jpg
---

## Restoring Basic Settings for Your Windows Explore

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121334/18498" target="_top" id="2121334">
  <img src="//a.impactradius-go.com/display-ad/18498-2121334" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121334/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-masterful-screenshots-made-simple-top-10-free-mac-apps/"><u>[New] 2024 Approved Masterful Screenshots Made Simple – Top 10 FREE Mac Apps</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-insider-guide-to-flourishing-on-youtube-games-included/"><u>[New] The Insider Guide to Flourishing on YouTube, Games Included</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-video-vouchers-for-trust-in-brands/"><u>[Updated] 2024 Approved Video Vouchers for Trust in Brands</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-leveraging-video-production-microsofts-movie-maker-for-windows-11/"><u>2024 Approved Leveraging Video Production Microsoft's Movie Maker for Windows 11</u></a></li>
<li><a href="https://article-posts.techidaily.com/face-id-vs-snapchats-face-unlock-the-apple-vs-samsung-debate-for-2024/"><u>Face ID Vs. Snapchat's Face Unlock The Apple Vs. Samsung Debate for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/playing-japanese-region-bddvd-on-american-systems-without-a-specialized-disc-player/"><u>Playing Japanese Region BD/DVD on American Systems Without a Specialized Disc Player</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-lost-data-from-itel-a60s-by-fonelab-android-recover-data/"><u>Recover lost data from Itel A60s</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-conversion-top-3-techniques-for-turning-your-google-slides-into-videos/"><u>Seamless Conversion: Top 3 Techniques for Turning Your Google Slides Into Videos</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-audio-conversion-discover-the-three-best-avi-to-mp3-transformation-techniques/"><u>Simplify Audio Conversion: Discover the Three Best AVI to MP3 Transformation Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-ac3-audio-format-conversion-the-ultimate-tool-for-fast-and-effortless-mp3-creation/"><u>Speedy AC3 Audio Format Conversion: The Ultimate Tool for Fast and Effortless MP3 Creation</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-on-downloading-snappea-software-for-your-windows-computer/"><u>Step-by-Step Guide on Downloading Snappea Software for Your Windows Computer</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-converting-your-dvd-collection-into-common-video-formats-like-mp4-mkv-and-more/"><u>Step-by-Step Guide: Converting Your DVD Collection Into Common Video Formats Like MP4, MKV & More</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-converting-your-entire-itunes-library-into-high-quality-mp3-format/"><u>Step-by-Step Guide: Converting Your Entire iTunes Library Into High-Quality MP3 Format</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-10-best-romantic-songs-for-proposal/"><u>Top 10 Best Romantic Songs for Proposal</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-5-from-honor-magic5-ultimate-to-iphone-contacts-transfer-apps-and-software-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 5 from Honor Magic5 Ultimate to iPhone Contacts Transfer Apps and Software | Dr.fone</u></a></li>
</ul></div>

