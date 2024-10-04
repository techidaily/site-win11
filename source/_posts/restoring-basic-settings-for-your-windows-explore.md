---
title: Restoring Basic Settings for Your Windows Explore
date: 2024-09-30T18:43:00.437Z
updated: 2024-10-04T05:25:10.430Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135409/19272" target="_top" id="2135409">
  <img src="//a.impactradius-go.com/display-ad/19272-2135409" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135409/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://dhgate.sjv.io/c/5597632/1186802/12108" target="_top" id="1186802">
  <img src="//a.impactradius-go.com/display-ad/12108-1186802" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186802/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868590/19272" target="_top" id="1868590">
  <img src="//a.impactradius-go.com/display-ad/19272-1868590" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868590/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972693/19272" target="_top" id="1972693">
  <img src="//a.impactradius-go.com/display-ad/19272-1972693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972693/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/new-tread-lightly-in-the-digital-jungle-vr-fitness-machines-examined/"><u>[New] Tread Lightly in the Digital Jungle VR Fitness Machines Examined</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-aquatic-videography-evolved-top-camcorders-of-the-year-for-2024/"><u>[Updated] Aquatic Videography Evolved - Top Camcorders of the Year for 2024</u></a></li>
<li><a href="https://win-unique.techidaily.com/debunking-common-misconceptions-how-windows-enthusiasts-often-misunderstand-macos/"><u>Debunking Common Misconceptions: How Windows Enthusiasts Often Misunderstand macOS</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-exploring-and-expunging-windows-history/"><u>Essential Steps for Exploring and Expunging Windows History</u></a></li>
<li><a href="https://driver-download.techidaily.com/free-rtx-2070-super-graphics-card-drivers-and-latest-updates-for-windows-10-and-11/"><u>Free RTX 2070 Super Graphics Card Drivers & Latest Updates for Windows 10 and 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-quest-for-freedom-guide-to-affordable-mmo-games/"><u>In 2024, Quest for Freedom Guide to Affordable MMO Games</u></a></li>
<li><a href="https://win11.techidaily.com/intuitive-shorthand-for-power-buttons-on-modern-windows-11/"><u>Intuitive Shorthand for Power Buttons on Modern Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/maximize-productivity-with-ai-mastering-the-art-of-using-chatgpt-as-an-on-demand-business-companion/"><u>Maximize Productivity with AI: Mastering the Art of Using ChatGPT as an On-Demand Business Companion</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-ssd-capabilities-integrate-windows-and-fresh-optimization/"><u>Maximize SSD Capabilities: Integrate Windows & Fresh Optimization</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-faulty-input-devices-on-a-windows-system/"><u>Resolving Faulty Input Devices on a Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/shut-off-windows-11-notifications-swiftly/"><u>Shut Off Windows 11 Notifications Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/uncover-windows-11-wallpaper-location-secret/"><u>Uncover Windows 11 Wallpaper Location Secret</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unveiling-the-secrets-behind-electric-two-wheeler-functionality/"><u>Unveiling the Secrets Behind Electric Two-Wheeler Functionality</u></a></li>
</ul></div>

