---
title: Enhancing Windows Explorer to Show Disk Space
date: 2024-09-05T08:40:49.953Z
updated: 2024-09-06T08:40:49.953Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enhancing Windows Explorer to Show Disk Space
excerpt: This Article Describes Enhancing Windows Explorer to Show Disk Space
keywords: Windows Explore Optimize,Display Disk Space Usage,Check Disk Space Quickly,Visualize Free Disk Space,Enhance File Explorer Views,Monitor System Storage,Streamline Disk Space Viewer
thumbnail: https://thmb.techidaily.com/dfad489a283b58802ec92c884b7191bbab4a284ecb771027987a79177a9a76e0.jpg
---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Enhancing Windows Explorer to Show Disk Space

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115925/19272" target="_top" id="2115925">
  <img src="//a.impactradius-go.com/display-ad/19272-2115925" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115925/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123901/26106" target="_top" id="2123901">
  <img src="//a.impactradius-go.com/display-ad/26106-2123901" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123901/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)

 Then copy and paste the below text into Notepad:

`Windows Registry Editor Version 5.00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"  
"System.IsPinnedToNamespaceTree"=dword:00000001  
"SortOrderIndex"=dword:00000050  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\DefaultIcon]  
@=hex(2):69,00,6d,00,61,00,67,00,65,00,72,00,65,00,73,00,2e,00,64,00,6c,00,6c,\  
  00,2c,00,2d,00,33,00,32,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\InProcServer32]  
@=hex(2):43,00,3a,00,5c,00,57,00,49,00,4e,00,44,00,4f,00,57,00,53,00,5c,00,73,\  
  00,79,00,73,00,74,00,65,00,6d,00,33,00,32,00,5c,00,73,00,68,00,65,00,6c,00,\  
  6c,00,33,00,32,00,2e,00,64,00,6c,00,6c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance]  
"CLSID"="{0E5AAE11-A475-4c5b-AB00-C66DE400274E}"  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\Instance\InitPropertyBag]  
"Attributes"=dword:00000011  
"TargetFolderPath"=hex(2):44,00,3a,00,5c,00,00,00  
  
[HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}\ShellFolder]  
"FolderValueFlags"=dword:00000028  
"Attributes"=dword:f080004d  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=dword:00000001  
  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]  
@="D: Drive"`

 Press **Ctrl + S**, name the file **add-d-drive-file-explorer.reg**, and then click **Save**. Don’t forget to add the REG file extension to let Windows know it’s working with a Registry file.

![saving a registry file in Notepad on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/save-reg-file-add-drive-nav-pane.jpg)

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)

<!-- affiliate ads begin -->
<span id="1444782">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1444782.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1444782">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1444782.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1444782%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1444782/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

<!-- affiliate ads begin -->
<span id="1977023">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977023.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977023">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977023.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977023%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977023/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-a-rolling-reel-of-jokes-tiktoks-best-comedic-videos/"><u>[New] 2024 Approved  A Rolling Reel of Jokes  TikTok's Best Comedic Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-decoding-facebook-capturing-and-keeping-status-videos/"><u>[New] In 2024, Decoding Facebook  Capturing and Keeping Status Videos</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-elevate-your-content-strategies-for-youtube-success/"><u>[New] In 2024, Elevate Your Content  Strategies for YouTube Success</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-gear-up-for-greatness-choosing-webcams-for-youtube-excellence/"><u>[New] In 2024, Gear Up for Greatness  Choosing Webcams for YouTube Excellence</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-optimal-viewing-times-on-instagram-videos-for-2024/"><u>[New] Optimal Viewing Times on Instagram Videos for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-the-ultimate-guide-to-capturing-professional-quality-in-zoom-podcasts/"><u>[Updated] 2024 Approved  The Ultimate Guide to Capturing Professional Quality in Zoom Podcasts</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-navigating-powerpoints-voice-recognition-lands-market/"><u>[Updated] Navigating PowerPoint's Voice Recognition Lands Market</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-vivo-y02t-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Vivo Y02T | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/clearing-up-opaque-video-views-on-youtube-for-2024/"><u>Clearing Up Opaque Video Views on YouTube for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-one-channel-sound-issue-for-windows-bluetooth-device/"><u>Correcting One-Channel Sound Issue for Windows' Bluetooth Device</u></a></li>
<li><a href="https://extra-hints.techidaily.com/discover-innovative-free-playback-options-across-systems/"><u>Discover Innovative, Free Playback Options Across Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-intel-processor-drivers-fast-and-simple-get-them-now/"><u>Download Intel Processor Drivers Fast and Simple - Get Them Now</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-smooth-play-fixing-saving-problems-in-pubg-windows-edition/"><u>Ensuring Smooth Play: Fixing Saving Problems in PUBG (Windows Edition)</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-evolution-of-security-shifting-from-pin-to-password-on-windows-11/"><u>Exploring the Evolution of Security: Shifting From PIN to Password on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fix-malfunctioning-windows-keyboard-buttons/"><u>Fix Malfunctioning Windows Keyboard Buttons</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-poco-c55-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Poco C55 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-the-task-managers-real-time-update-speed-on-windows-11/"><u>How to Change the Task Manager's Real-Time Update Speed on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-error-0x80041015-in-microsoft-office/"><u>How to Reset Error 0X80041015 in Microsoft Office</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-your-touch-keys-initial-setup-in-win-11/"><u>How to Reset Your Touch Keys' Initial Setup in Win 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-honor-play-7t-photos-an-easy-method-explained-by-fonelab-android-recover-photos/"><u>How to Restore Deleted Honor Play 7T Photos  An Easy Method Explained.</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-googles-nearby-share-to-share-files-between-android-and-windows/"><u>How to Use Google's Nearby Share to Share Files Between Android and Windows</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-leveraging-eco-friendly-visual-effects-revolutionizing-online-video-content/"><u>In 2024, Leveraging Eco-Friendly Visual Effects  Revolutionizing Online Video Content</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721480806637-iphoneipad-siri-not-responding-discover-7-key-solutions-to-get-it-working-again/"><u>IPhone/iPad Siri Not Responding? Discover 7 Key Solutions to Get It Working Again</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-control-battery-saver-settings-on-windows-pcs/"><u>Learn to Control Battery Saver Settings on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/leverage-time-management-with-windows-11-calendar/"><u>Leverage Time Management with Windows 11 Calendar</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-command-line-for-wordpad-activation/"><u>Mastering Command Line for WordPad Activation</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-screen-size-in-windows-with-this-fix-guide/"><u>Mastering Screen Size in Windows, With This Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-steam-display-fixes-on-microsoft-os/"><u>Mastering Steam Display Fixes on Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/minimize-intruding-windows-tips-and-tricks-alerts/"><u>Minimize Intruding Windows Tips and Tricks Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-downloads-woes-in-win-1011-ecosystems/"><u>Navigating Downloads Woes in Win 10/11 Ecosystems</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-username-changes-in-windows-11/"><u>Navigating UserName Changes in Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/quick-screen-grabs-for-win-11-users-for-2024/"><u>Quick Screen Grabs for Win 11 Users for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/removing-ms-edge-steps-for-w11-os/"><u>Removing MS Edge: Steps for W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-application-displacement-on-pc/"><u>Resolving 'Application Displacement on PC'</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-wows-critical-crash-win11-edition/"><u>Resolving WoW's Critical Crash: Win11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-revive-batch-files-in-windows-environment/"><u>Steps to Revive Batch Files in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/switch-to-gesture-based-navigation-in-ms-edge-on-windows-11/"><u>Switch to Gesture-Based Navigation in MS Edge on Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-battle-of-video-players-vlc-vs-mx-for-2024/"><u>The Battle of Video Players  VLC Vs. MX for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/top-5-efficient-mac-snippers-for-quick-captures-for-2024/"><u>Top 5 Efficient Mac Snippers for Quick Captures for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/uncover-10-keys-to-picking-your-perfect-broadcast-platform-for-2024/"><u>Uncover 10 Keys to Picking Your Perfect Broadcast Platform for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/unlocking-the-power-of-google-meet-recordings-two-key-tactics/"><u>Unlocking the Power of Google Meet Recordings  Two Key Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-search-feature-in-win11-taskbar/"><u>Unlocking the Search Feature in Win11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/windows-masterclass-silent-images-for-hidden-archives/"><u>Windows Masterclass: Silent Images for Hidden Archives</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>