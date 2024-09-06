---
title: Reverting Custom Sort and Group Order of Files
date: 2024-09-05T08:39:01.593Z
updated: 2024-09-06T08:39:01.593Z
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

<!-- affiliate ads begin -->
<span id="1975503">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975503.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975503">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975503.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975503%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975503/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Reverting Custom Sort and Group Order of Files

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.
<!-- affiliate ads begin -->
<span id="1770776">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770776.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770776">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770776.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770776%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770776/20702" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2118314/7443" target="_top" id="2118314">
  <img src="//a.impactradius-go.com/display-ad/7443-2118314" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118314/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-entry-editor-for-diverse-tech-landscape-of-2023/"><u>[New] The Ultimate Entry Editor for Diverse Tech Landscape of 2023</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-timeline-enhancement-incor-written-by-assistant/"><u>[New] Timeline Enhancement  Incor Written by Assistant</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-which-online-platform-stands-out-discord-and-skype-compared/"><u>[New] Which Online Platform Stands Out? Discord & Skype Compared</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-masterclass-guide-screen-recording-hulu-videos-effortlessly/"><u>[Updated] 2024 Approved  Masterclass Guide  Screen Recording Hulu Videos Effortlessly</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-cold-climate-chronicles-highlights-from-the-icy-stage/"><u>[Updated] Cold Climate Chronicles  Highlights From the Icy Stage</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-mastering-the-art-of-uploading-youtube-videos-on-fb-for-2024/"><u>[Updated] Mastering the Art of Uploading YouTube Videos on FB for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-maximizing-impact-in-snapchat-spotlight/"><u>[Updated] Maximizing Impact in Snapchat Spotlight</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-prime-focus-best-photo-viewing-win11-app/"><u>[Updated] Prime Focus  Best Photo Viewing Win11 App</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-audio-enabled-mac-video-recorder/"><u>2024 Approved  Audio-Enabled Mac Video Recorder</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-masterclass-conquering-one-device-livestream-challenges/"><u>2024 Approved  Masterclass  Conquering One-Device Livestream Challenges</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-list-of-engaging-history-content-on-youtube/"><u>2024 Approved  The Ultimate List of Engaging History Content on YouTube</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-ultimate-guide-top-6-cutting-edge-21-hdmi-portable-displays/"><u>2024 Approved  Ultimate Guide  Top 6 Cutting-Edge 2.1 HDMI Portable Displays</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unlocking-crossfade-magic-using-audacity-effectively/"><u>2024 Approved  Unlocking Crossfade Magic  Using Audacity Effectively</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Asus ROG Phone 7 Ultimate | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/compatibility-crusade-four-key-windows-troubleshooters/"><u>Compatibility Crusade: Four Key Windows Troubleshooters</u></a></li>
<li><a href="https://tech-revival.techidaily.com/converse-face-to-face-w-chatgpt/"><u>Converse Face-to-Face W/ ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-the-non-start-issue-for-windows-speech-recognition/"><u>Correcting the Non-Start Issue for Windows Speech Recognition</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-windows-11s-0x0000011b-operational-error/"><u>Decoding and Fixing Windows 11'S 0X0000011B Operational Error</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unresponsive-battlenet-application-on-windows-pc/"><u>Fixing Unresponsive Battle.net Application on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-11-anydesk-errors/"><u>Fixing Windows 11 AnyDesk Errors</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-samsung-galaxy-a05s-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Samsung Galaxy A05s FRP Locks</u></a></li>
<li><a href="https://win11.techidaily.com/get-the-most-out-of-windows-11-essential-settings-for-upgraded-speed/"><u>Get the Most Out of Windows 11: Essential Settings for Upgraded Speed</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-conceal-dim-display-feature-in-win-os-control-panel/"><u>Guide to Conceal Dim Display Feature in Win OS Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-parent-controls-on-microsoft-windows-11/"><u>Guide to Parent Controls on Microsoft Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-zte-nubia-z60-ultra-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your ZTE Nubia Z60 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-random-console-window-flashes/"><u>How to Prevent Random Console Window Flashes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tell-the-age-of-a-windows-laptop-or-desktop/"><u>How to Tell the Age of a Windows Laptop or Desktop</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-disabled-iphone-8-how-to-unlock-a-disabled-iphone-8-by-drfone-ios/"><u>In 2024, Disabled iPhone 8 How to Unlock a Disabled iPhone 8?</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-mobile-mastery-in-thumbnail-creation-for-engaging-youtube-videos/"><u>In 2024, Mobile Mastery in Thumbnail Creation for Engaging YouTube Videos</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-5ghz-connection-not-appearing-in-windows-11-try-these-7-fixes/"><u>Is Your 5GHz Connection Not Appearing in Windows 11? Try These 7 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/is-yourphoneexe-a-threat-tips-for-windows-108-users/"><u>Is YourPhone.exe a Threat? Tips for Windows 10/8 Users</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-latest-features-for-taskbar-in-win11/"><u>Leveraging Latest Features for Taskbar in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-admin-access-revamping-windows-uac-protocols/"><u>Mastering Admin Access: Revamping Windows UAC Protocols</u></a></li>
<li><a href="https://printer-issues.techidaily.com/mended-printer-not-responding/"><u>Mended Printer Not Responding</u></a></li>
<li><a href="https://driver-error.techidaily.com/missing-driver-detection-issue/"><u>Missing Driver Detection Issue</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-error-0x80070522-in-windows-privileges-restoration-guide/"><u>Navigating Error 0X80070522 in Windows: Privileges Restoration Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-file-access-barriers-on-windows-11/"><u>Overcoming File Access Barriers on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steam-network-errors-in-win11/"><u>Overcoming Steam Network Errors in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/photo-perfect-camouranage-integrating-files-into-images/"><u>Photo-Perfect Camouranage: Integrating Files Into Images</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/precision-color-correction-with-mastery-over-ps-3d-luts-for-2024/"><u>Precision Color Correction with Mastery over PS 3D LUTs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/premium-choices-top-windows-platforms-for-dsswitch-experience/"><u>Premium Choices: Top Windows Platforms for DS/Switch Experience</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-infinix-hot-30i-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Infinix Hot 30i to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quickly-fix-crashing-file-explorers-on-up-to-date-windows-11/"><u>Quickly Fix Crashing File Explorers on Up-to-Date Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/rediscover-lost-control-panel-configurations-in-win11/"><u>Rediscover Lost Control Panel Configurations in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-non-existent-camera-issue-in-windows-device-hub/"><u>Resolve Non-Existent Camera Issue in Windows Device Hub</u></a></li>
<li><a href="https://win11.techidaily.com/resurrect-missing-links-to-shared-windows-sites/"><u>Resurrect Missing Links to Shared Windows Sites</u></a></li>
<li><a href="https://win-solutions.techidaily.com/rocket-league-update-troubles-master-the-techniques-to-prevent-app-crashes/"><u>Rocket League Update Troubles? Master the Techniques to Prevent App Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-extend-windows-11-shutdown-process/"><u>Strategies to Extend Windows 11 Shutdown Process</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-reveal-hidden-taskbar-icons/"><u>Strategies to Reveal Hidden Taskbar Icons</u></a></li>
<li><a href="https://win11.techidaily.com/superior-tools-replacing-windows-snipping-feature-in-various-oses/"><u>Superior Tools Replacing Windows' Snipping Feature in Various OSes</u></a></li>
<li><a href="https://win11.techidaily.com/tailor-your-clock-and-dates-windows-1011-guide/"><u>Tailor Your Clock and Dates: Windows 10/11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-mind-maps-organizing-notes-using-obsidian-canvas/"><u>The Art of Mind Maps: Organizing Notes Using Obsidian Canvas</u></a></li>
<li><a href="https://win11.techidaily.com/the-quest-for-efficient-browsing-ram-friendly-windows-applications-ranked/"><u>The Quest for Efficient Browsing: RAM-Friendly Windows Applications Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-smooth-gameplay-better-frame-rates-in-roblox-win/"><u>Tips for Smooth Gameplay: Better Frame Rates in Roblox Win</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-no-cost-performance-boosters-to-enhance-windows-vehicles/"><u>Top 5 No-Cost Performance Boosters to Enhance Windows Vehicles</u></a></li>
<li><a href="https://win11.techidaily.com/track-down-and-fix-gone-data-devices-on-pc/"><u>Track Down and Fix Gone Data Devices on PC</u></a></li>
<li><a href="https://program-issues.techidaily.com/1722985667652-troubleshooting-solutions-for-non-responsive-discord-overlays-instant-fixes/"><u>Troubleshooting Solutions for Non-Responsive Discord Overlays - Instant Fixes!</u></a></li>
<li><a href="https://activate-lock.techidaily.com/ultimate-guide-from-apple-iphone-14-pro-icloud-activation-lock-bypass-by-drfone-ios/"><u>Ultimate Guide from Apple iPhone 14 Pro iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-your-win11-status-key-indicators-and-checks-for-uptime/"><u>Understanding Your Win11 Status: Key Indicators and Checks for Uptime</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-power-of-fixed-recovering-non-functional-win-apps/"><u>Unleash the Power of Fixed: Recovering Non-Functional Win-Apps</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secrets-of-windows-function-fn-control-techniques/"><u>Unlocking Secrets of Windows' Function (Fn) Control Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-webcam-visibility-alerts-in-win11/"><u>Unlocking Webcam Visibility Alerts in Win11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unveiling-what-net-neutrality-really-means-and-its-impact/"><u>Unveiling What Net Neutrality Really Means and Its Impact</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-win11s-five-privacy-snooping-techniques/"><u>Unveiling Win11's Five Privacy Snooping Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/windows-canary-explained-start-your-journey/"><u>Windows Canary Explained: Start Your Journey</u></a></li>
</ul></div>
