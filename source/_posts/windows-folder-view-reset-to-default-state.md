---
title: Windows Folder View Reset to Default State
date: 2024-10-15T18:16:46.792Z
updated: 2024-10-21T02:58:21.125Z
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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148641/16836" target="_top" id="2148641">
  <img src="//a.impactradius-go.com/display-ad/16836-2148641" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148641/16836" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880944/19272" target="_top" id="1880944">
  <img src="//a.impactradius-go.com/display-ad/19272-1880944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880944/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135363/19272" target="_top" id="2135363">
  <img src="//a.impactradius-go.com/display-ad/19272-2135363" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135363/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037474/7443" target="_top" id="2037474">
  <img src="//a.impactradius-go.com/display-ad/7443-2037474" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037474/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-create-endless-video-on-iphone/"><u>[New] 2024 Approved How-To Create Endless Video on iPhone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-expert-android-guide-to-top-gba-emulators-for-2024/"><u>[New] Expert Android Guide to Top GBA Emulators for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-navigating-the-path-to-facebooks-exclusive-verified-marker/"><u>[New] In 2024, Navigating the Path to Facebook's Exclusive Verified Marker</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-vlog-glow-achieving-professional-video-setup/"><u>[Updated] In 2024, Vlog Glow Achieving Professional Video Setup</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-innovative-mac-tool-for-screen-and-audio-capture-for-2024/"><u>[Updated] Innovative Mac Tool for Screen & Audio Capture for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-top-vectors-alternatives-to-the-classic-acid-pro/"><u>[Updated] Top Vectors Alternatives to the Classic ACID Pro</u></a></li>
<li><a href="https://games-able.techidaily.com/adapting-sonys-console-to-pc-gaming-with-ease/"><u>Adapting Sony's Console to PC Gaming with Ease</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-setup-guide-iphone-drivers-for-windows-11/"><u>Download & Setup Guide: IPhone Drivers for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-updating-windows-icon-cache/"><u>Guidelines for Updating Windows Icon Cache</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-step-by-step-guide-to-rearranging-youtube-playlists/"><u>In 2024, Step-by-Step Guide to Rearranging YouTube Playlists</u></a></li>
<li><a href="https://win11.techidaily.com/opening-act-emailcalendar-troubles-in-w11-os/"><u>Opening Act: Email/Calendar Troubles in W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/quick-start-engaging-snipping-tool-on-windows-11/"><u>Quick Start: Engaging Snipping Tool on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-your-workflows-with-an-exclusive-run-command-feature-for-windows-11/"><u>Revolutionize Your Workflows with an Exclusive Run Command Feature for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-stopping-exception-breakpoint-failure-in-windows/"><u>Solutions for Stopping Exception Breakpoint Failure in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-access-remedying-epic-launcher-on-windows/"><u>Unblocking Access: Remedying Epic Launcher on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-user-management-for-windows-home-editions/"><u>Unlock Full User Management for Windows Home Editions</u></a></li>
<li><a href="https://win11.techidaily.com/windowed-wisdom-mastering-folderfile-properties/"><u>Windowed Wisdom: Mastering Folder/File Properties</u></a></li>
</ul></div>

