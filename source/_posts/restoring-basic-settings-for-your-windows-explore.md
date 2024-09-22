---
title: Restoring Basic Settings for Your Windows Explore
date: 2024-09-15T20:03:45.491Z
updated: 2024-09-21T16:49:20.136Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2006960/19272" target="_top" id="2006960">
  <img src="//a.impactradius-go.com/display-ad/19272-2006960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006960/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106658/12108" target="_top" id="2106658">
  <img src="//a.impactradius-go.com/display-ad/12108-2106658" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106658/12108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-reimagining-received-gifts-the-joy-of-openness/"><u>[New] In 2024, Reimagining Received Gifts The Joy of Openness</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-top-essentials-for-enhanced-uav-functionality-for-2024/"><u>[New] Top Essentials for Enhanced UAV Functionality for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-introducing-efficient-speech-to-text-utilization-in-powerpoint/"><u>2024 Approved Introducing Efficient Speech-to-Text Utilization in PowerPoint</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-securely-downloading-youtube-audios-3-easy-and-reliable-methods/"><u>2024 Approved Securely Downloading YouTube Audios 3 Easy & Reliable Methods</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/amplify-reach-todays-most-effective-instagram-tag-strategies/"><u>Amplify Reach Today's Most Effective Instagram Tag Strategies</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-realme-narzo-n53-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Realme Narzo N53 Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-leading-free-video-trimming-software-our-top-6-recommendations/"><u>Discover the Leading Free Video Trimming Software: Our Top 6 Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-conversion-from-qt-to-mp4-your-ultimate-guide-to-changing-quicktime-files/"><u>Effortless Conversion From QT to MP4: Your Ultimate Guide to Changing QuickTime Files</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-xiaomi-redmi-note-12-pro-4g-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Xiaomi Redmi Note 12 Pro 4G Phone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, The Best iSpoofer Alternative to Try On Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/itunes-iphoneandandroid/"><u>ITunesにダビング！カメラ撮影動画から音楽へ - iPhone&Android利用者向けガイド</u></a></li>
<li><a href="https://win11.techidaily.com/1726030325875-pc/"><u>PCゲーム記録：シンプルな手法とコツをご紹介</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-13-pro-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 13 Pro Data From iCloud | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/simple-tricks-capturing-and-downloading-your-favorite-instagram-live-sessions/"><u>Simple Tricks: Capturing and Downloading Your Favorite Instagram Live Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-transforming-mkv-videos-into-high-quality-av1-format/"><u>Step-by-Step Guide: Transforming MKV Videos Into High-Quality AV1 Format</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-remedies-to-resolve-the-0xc00d36c4-error-during-videoaudio-playback/"><u>Top 4 Remedies to Resolve the '0xC00D36C4' Error During Video/Audio Playback</u></a></li>
</ul></div>

