---
title: Windows Folder View Reset to Default State
date: 2024-09-12T00:13:43.154Z
updated: 2024-09-16T18:35:31.276Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows Folder View Reset to Default State
excerpt: This Article Describes Windows Folder View Reset to Default State
keywords: Windows Default View,Reset Explorer Display,Folder Layout Standard,View Settings Restore,System Folder View Fix,Reset Windows Explore,Default Explorer State
thumbnail: https://thmb.techidaily.com/d529ee3f9777395e3e6b4e63c228e25fbb4330a46358a8f92c3ef7608136a4ab.jpg
---

## Windows Folder View Reset to Default State

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
<span id="1983545">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983545.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983545">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983545.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983545%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983545/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115948/19272" target="_top" id="2115948">
  <img src="//a.impactradius-go.com/display-ad/19272-2115948" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115948/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-essential-tips-to-avoid-obs-framing-errors/"><u>[New] In 2024, Essential Tips to Avoid OBS Framing Errors</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-twitters-best-binge-friends-amazon-primes-most-liked-shows-23/"><u>[New] In 2024, Twitter's Best Binge-Friends Amazon Prime's Most Liked Shows, '23</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-find-zen-with-these-10-game-choices/"><u>[Updated] In 2024, Find Zen with These 10 Game Choices</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/10-top-must-have-gear-items-for-youtubers/"><u>10 Top Must-Have Gear Items for YouTubers</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-fix-iphone-8-passcode-not-working-by-drfone-ios/"><u>How to Fix iPhone 8 Passcode not Working?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-put-iphone-6-or-ipad-on-recovery-mode-step-by-step-tutorial-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Put iPhone 6 or iPad on Recovery mode? (Step by Step Tutorial) | Stellar</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-vivo-y27-5g-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From Vivo Y27 5G To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-streaming-mkv-video-formats-on-your-ios-device/"><u>Step-by-Step Guide: Streaming MKV Video Formats on Your iOS Device</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-displays-lacking-hdcp-support-for-better-streaming-quality/"><u>Troubleshooting Displays Lacking HDCP Support for Better Streaming Quality</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-solving-the-issue-of-unsuccessful-webm-file-imports-into-adobe-premiere-pro/"><u>Troubleshooting Guide: Solving the Issue of Unsuccessful WebM File Imports Into Adobe Premiere Pro</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-how-to-set-up-an-operating-system-installation-directly-from-an-iso-file-no-discs-needed/"><u>Ultimate Tutorial: How to Set Up an Operating System Installation Directly From an ISO File, No Discs Needed</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-appeal-of-60-fps-anime-a-visual-quality-comparison/"><u>Understanding the Appeal of 60 Fps Anime - A Visual Quality Comparison</u></a></li>
<li><a href="https://win11.techidaily.com/usb-video-playback-easy-instructions-for-toshiba-tv-users/"><u>USB Video Playback: Easy Instructions for Toshiba TV Users</u></a></li>
</ul></div>

