---
title: Reclaiming Your Preferred File Layout Settings
date: 2024-08-08T13:23:05.576Z
updated: 2024-08-09T13:23:05.576Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reclaiming Your Preferred File Layout Settings
excerpt: This Article Describes Reclaiming Your Preferred File Layout Settings
keywords: File Layout Preference,Reclaim File Settings,Resetting File Setup,Personalize File View,Adjust File Display,Format File Preferences,Change File Layout
thumbnail: https://thmb.techidaily.com/db3dbeacfdd5ea435b3f8eb406f01646288938a037fe9e28d65cbe9fbebcdbb0.png
---

## Reclaiming Your Preferred File Layout Settings

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

## How to Reset Folder View Settings to Default on Windows

 There are three ways to reset your Folder View Settings to the default view. The first method is to run a batch file, the second using File Explorer, whereas the third and final method involves tweaking the registry editor. This post explains each method in detail. Let's dive into it.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Run a Batch File to Reset Folder View Settings to Default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-a-batch-file-to-reset-folder-view-settings-to-default.jpg)
7. From the left pane, select**Desktop** as the location.
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
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
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
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
<li><a href="https://instagram-videos.techidaily.com/new-hidden-glances-instagram-story-viewing-without-revealing-personal-details-pc-android-iphone/"><u>[New] Hidden Glances  Instagram Story Viewing without Revealing Personal Details [PC, Android, iPhone]</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-a-comprehensive-guide-to-producing-videos-for-social-media/"><u>[New] In 2024, A Comprehensive Guide to Producing Videos For Social Media</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-from-text-to-voice-a-complete-tiktok-technique-overview/"><u>[New] In 2024, From Text to Voice  A Complete TikTok Technique Overview</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-craft-eye-catching-youtubes-end-titles/"><u>[Updated] 2024 Approved  How to Craft Eye-Catching YouTubes End Titles</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-capture-music-from-facebook-streams/"><u>[Updated] Capture Music From Facebook Streams</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-dive-into-the-world-of-interactive-video-features-on-youtube/"><u>[Updated] Dive Into the World of Interactive Video Features on YouTube</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-trailblazers-of-the-cinematic-visual-and-auditory-fusion/"><u>[Updated] Trailblazers of the Cinematic, Visual & Auditory Fusion</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-convert-spoken-words-into-written-content-using-ms-words-in-built-tools/"><u>2024 Approved  Convert Spoken Words Into Written Content Using MS Word's In-Built Tools</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-navigating-the-world-of-giant-file-movement-between-iphone-and-macos/"><u>2024 Approved  Navigating the World of Giant File Movement Between iPhone and macOS</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-srt-optimization-the-ultimate-performance-boosters-for-computers/"><u>2024 Approved  SRT Optimization  The Ultimate Performance Boosters for Computers</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-top-free-android-calling-tools-ranked-by-cost/"><u>2024 Approved  Top Free Android Calling Tools Ranked by Cost</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-unlock-icloud-account-without-password-from-iphone-11-by-drfone-ios/"><u>3 Effective Ways to Unlock iCloud Account Without Password From iPhone 11</u></a></li>
<li><a href="https://win11.techidaily.com/5-routes-to-enter-startup-repair-on-a-pc/"><u>5 Routes to Enter Startup Repair on a PC</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-zipping-with-command-prompt-step-by-step/"><u>Advanced Zipping with Command Prompt, Step by Step</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-motorola-moto-g23-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Motorola Moto G23? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-efficiency-setting-up-shortcuts-for-fixed-text-paste-and-copy/"><u>Boost Your Efficiency: Setting Up Shortcuts for Fixed Text Paste & Copy</u></a></li>
<li><a href="https://data-wizards.techidaily.com/boosting-mac-speed-introducing-stellars-solution/"><u>Boosting Mac Speed: Introducing Stellar’s Solution</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-browser-speed-discrepancy-across-devices/"><u>Bridging Browser Speed Discrepancy Across Devices</u></a></li>
<li><a href="https://win11.techidaily.com/effective-use-of-windows-explorer-over-traditional-ls/"><u>Effective Use of Windows Explorer Over Traditional LS</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-strategies-for-dispelling-blue-screen-of-operation-requires-elevation-in-winos/"><u>Efficient Strategies for Dispelling Blue Screen of Operation Requires Elevation in WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/essential-methods-unlocking-computer-management-on-windows-11/"><u>Essential Methods: Unlocking Computer Management on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-on-capturing-windows-calls-effectively/"><u>Essential Tips on Capturing Windows Calls Effectively</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-xiaomi-redmi-a2-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Xiaomi Redmi A2 Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-secure-hassle-free-passport-images-top-10-choices/"><u>In 2024, Secure, Hassle-Free Passport Images - Top 10 Choices</u></a></li>
<li><a href="https://driver-download.techidaily.com/latest-acer-touchpad-software-update-for-optimal-performance-on-windows-11/"><u>Latest Acer Touchpad Software Update for Optimal Performance on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-surface-studio-2-almost-perfect-creators-choice/"><u>Microsoft Surface Studio 2 - Almost Perfect Creator's Choice</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-public-ip-using-windows-command-window/"><u>Navigate to Public IP Using Windows Command Window</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-system-maintenance-tips-for-setting-active-windows-11-times/"><u>Navigating System Maintenance: Tips for Setting Active Windows 11 Times</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-tech-habits-dont-disable-win-11-alerts/"><u>Optimal Tech Habits: Don't Disable Win 11 Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/revive-the-shield-5-key-fixes-for-windows-family-protection/"><u>Revive the Shield: 5 Key Fixes for Windows Family Protection</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-quiet-slack-signals-on-windows-11-pcs/"><u>Reviving Quiet Slack Signals on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/secrets-to-seamlessly-engagedisengage-windows-terminal-focus/"><u>Secrets to Seamlessly Engage/Disengage Windows Terminal Focus</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-microsofts-error-code-0x8007251d-for-users/"><u>Simplifying Microsoft's Error Code 0X8007251D for Users</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/starting-point-learning-to-thrive-in-instagrams-virtual-spaces-for-2024/"><u>Starting Point  Learning to Thrive in Instagram's Virtual Spaces for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-wallpapers-for-each-windows-11-workspace-element/"><u>Step-by-Step Wallpapers for Each Windows 11 Workspace Element</u></a></li>
<li><a href="https://fox-that.techidaily.com/top-strategies-to-solve-continuous-airpod-connectivity-issues-with-iphone/"><u>Top Strategies to Solve Continuous AirPod Connectivity Issues with iPhone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-disabled-microsoft-outlook-push-notifications/"><u>Troubleshooting Disabled Microsoft Outlook Push Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-virtual-disk-service-failure-in-windows/"><u>Troubleshooting: Resolving Virtual Disk Service Failure in Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unlock-your-creative-potential-with-inshot-for-pcs-and-laptops/"><u>Unlock Your Creative Potential with Inshot for PCs & Laptops</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-smooth-spotify-link-functionality-in-windows-11/"><u>Unlocking Smooth Spotify Link Functionality in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secrets-of-rapid-system-restart-windows-11-edition/"><u>Unlocking the Secrets of Rapid System Restart: Windows 11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-auditory-interference-mystery/"><u>Unraveling Windows' Auditory Interference Mystery</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-identifying-core-functionalities-in-digital-sound-editors-for-mac/"><u>Updated 2024 Approved Identifying Core Functionalities in Digital Sound Editors for Mac</u></a></li>
<li><a href="https://win11.techidaily.com/win11-simplifying-file-server-connections/"><u>Win11: Simplifying File Server Connections</u></a></li>
</ul></div>
