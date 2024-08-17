---
title: Adding Removable Storage via Explore Navigation Menu
date: 2024-08-15T23:17:26.019Z
updated: 2024-08-16T23:17:26.019Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adding Removable Storage via Explore Navigation Menu
excerpt: This Article Describes Adding Removable Storage via Explore Navigation Menu
keywords: Storage Expansion,Explore Menu Access,Mobile Device Add-On,Data Portability,External SD Utilization,SIM Card Mounting,USB Drive Integration
thumbnail: https://thmb.techidaily.com/633f0a6d177df3d7fb477a15a0804c21edff9926ab23c2607a0458a0d217d945.jpeg
---

## Adding Removable Storage via Explore Navigation Menu

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Do I Add the D: Drive to the Navigation Pane in File Explorer?

 Start by pressing **Win + S** to bring up Windows Search. Then, type **notepad** in the Search box, and when Notepad shows up in the search results, click on it to launch it.

![The Notepad search result](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/notepad-search-result.png)
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Next, double-click the Registry file you just created and click **Yes** on the UAC prompt. You’ll then be asked if you want to continue with the merge, so click **Yes**. Afterward, press **Win + E** to open File Explorer.

![the D drive showing in the bottom section of the Navigation pane on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/d-drive-nav-pane.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The D: drive should now be visible in the bottom part of the Navigation pane.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
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
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Create an Easier Way to Access the D: Drive on Your Windows Computer

 With this guide, you will remove an extra step when accessing the D: drive on your Windows computer. Once you have created the registry files, adding and removing the D: drive from the Navigation pane will be easy. While the registry files are safe, don’t forget to create a backup of your Registry or a system restore point for good measure.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-the-secret-to-capturing-seamless-google-classesmeets/"><u>[New] 2024 Approved  The Secret to Capturing Seamless Google Classes/Meets</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-alternatives-to-xboxs-game-bar-for-gamers-for-2024/"><u>[New] Alternatives to Xbox’s Game Bar for Gamers for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-elevating-your-instagram-conversations-an-in-depth-guide-for-2024/"><u>[New] Elevating Your Instagram Conversations  An In-Depth Guide for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-examining-video-comments-on-youtube-for-2024/"><u>[New] Examining Video Comments on YouTube for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-tailoring-your-youtube-video-introduction-perfectly/"><u>[New] In 2024, Tailoring Your YouTube Video Introduction Perfectly</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-quick-tips-for-setting-up-zoom-on-your-android-phonetablet/"><u>[New] Quick Tips for Setting Up Zoom on Your Android Phone/Tablet</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-best-facebook-practices-videographers-dilemrante-for-2024/"><u>[Updated] Best Facebook Practices  Videographer's Dilemrante for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-insta-tiktik-mastery-uniting-two-social-giants/"><u>[Updated] Insta-TikTik Mastery  Uniting Two Social Giants</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-novice-to-vlogger-top-tips-to-enhance-your-tiktok-videos/"><u>2024 Approved  From Novice to Vlogger  Top Tips to Enhance Your TikTok Videos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-hook-your-viewers-quickly-with-these-6-video-types/"><u>2024 Approved  Hook Your Viewers Quickly with These 6 Video Types</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-maximize-your-google-meet-experience-without-paying-a-penny/"><u>2024 Approved  Maximize Your Google Meet Experience, Without Paying a Penny</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-navigating-premieres-export-woes-to-fix-srt-files/"><u>2024 Approved  Navigating Premiere's Export Woes to Fix SRT Files</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-sound-mastery-pro-tips-for-effective-audiovisual-blending-audacity/"><u>2024 Approved  Sound Mastery  Pro Tips for Effective Audiovisual Blending (Audacity)</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-step-by-step-guide-to-crafting-unique-iphone-tones/"><u>2024 Approved  Step-by-Step Guide to Crafting Unique iPhone Tones</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unlocking-canvas-potential-10-secrets-for-professionals/"><u>2024 Approved  Unlocking Canvas Potential - 10 Secrets for Professionals</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-microsoft-edge-speeding-tips-for-windows-1011/"><u>Boosting Microsoft Edge: Speeding Tips for Windows 10/11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/boot-windows-resolving-black-screen-issues/"><u>Boot Windows: Resolving Black Screen Issues</u></a></li>
<li><a href="https://win11.techidaily.com/classic-computing-redeemed-by-atlasos/"><u>Classic Computing Redeemed by AtlasOS</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-windows-control-with-administrator-rights/"><u>Conquering Windows Control with Administrator Rights</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-efficient-windows-11-shortcuts-for-uwp-apps/"><u>Crafting Efficient Windows 11 Shortcuts for UWP Apps</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-diskusage-in-windows-strategies-for-effective-drive-space-analysis/"><u>Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-procedure-for-total-disabling-of-windows-subsystem/"><u>Detailed Procedure for Total Disabling of Windows Subsystem</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/detailed-review-of-doctorsim-unlock-service-for-apple-iphone-11-pro-drfone-by-drfone-ios/"><u>Detailed Review of doctorSIM Unlock Service For Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-windows-alt-key-errors-48-characters/"><u>Diagnosing Windows Alt Key Errors (48 Characters)</u></a></li>
<li><a href="https://facebook.techidaily.com/discover-the-perks-of-taking-a-digital-pause/"><u>Discover the Perks of Taking a Digital Pause</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-shutdown-the-guide-to-auto-mode-with-windows-1011/"><u>Efficient Shutdown: The Guide to Auto Mode with Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/ending-failed-operations-fix-code-0x0000011b/"><u>Ending Failed Operations: Fix Code 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-file-system-usability-in-windows-max-156/"><u>Enhancing File System Usability in Windows (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/explore-1-6-gpu-power-tools-to-assess-on-your-pc/"><u>Explore #1-#6 GPU Power Tools to Assess on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-absence-of-rockalldll-in-windows-os/"><u>Fixes for Absence of Rockalldll in Windows OS</u></a></li>
<li><a href="https://program-issues.techidaily.com/fixing-elden-ring-multiplayer-issues-a-step-by-step-guide/"><u>Fixing 'Elden Ring' Multiplayer Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-unrecognized-flash-drive-errors-understanding-and-solving-device-descriptor-request-failed-issues/"><u>Fixing Unrecognized Flash Drive Errors: Understanding and Solving 'Device Descriptor Request Failed' Issues</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/free-premium-visual-aids-for-business-professionals-for-2024/"><u>FREE Premium Visual Aids for Business Professionals for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-controlling-installer-service-in-windows/"><u>Guide to Controlling Installer Service in Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-sony-xperia-5-v-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Sony Xperia 5 V? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-pick-win-friendly-video-coders-wisely/"><u>How to Pick Win-Friendly Video Coders Wisely</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-write-prohibited-files-in-windows-11/"><u>How to Tackle Write-Prohibited Files in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/improve-energy-monitoring-full-charge-alerts-for-a-more-efficient-win11/"><u>Improve Energy Monitoring: Full Charge Alerts for a More Efficient Win11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-boosted-visuals-a-beginners-guide-to-gopro-video-editing/"><u>In 2024, Boosted Visuals  A Beginner's Guide to GoPro Video Editing</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-connect-play-and-share-the-essentials-of-xbox-zoom/"><u>In 2024, Connect, Play and Share  The Essentials of Xbox Zoom</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-connectivity-windows-11-and-mobile-devices-unite/"><u>Innovative Connectivity: Windows 11 & Mobile Devices Unite</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-windows-features-for-macos-advantages/"><u>Integrating Windows Features for MacOS Advantages</u></a></li>
<li><a href="https://tech-haven.techidaily.com/intellects-edge-beyond-alan-turings-legacy/"><u>Intellect's Edge: Beyond Alan Turing's Legacy</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-level-powershell-setup-with-admin-privileges-in-windows-11/"><u>Mastery Level: PowerShell Setup with Admin Privileges in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-hyper-v-setup-for-modern-windows-11/"><u>Navigating Hyper-V Setup for Modern Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-transition-dance-mastering-enterexit-rituals-of-terminals-focused-state/"><u>Navigating the Transition Dance: Mastering Enter/Exit Rituals of Terminal's Focused State</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-fundamental-features-to-consider-when-selecting-an-audio-editor-for-mac-users-for-2024/"><u>New Fundamental Features to Consider When Selecting an Audio Editor for Mac Users for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-your-keyboard-precise-text-pasting-hotkeys/"><u>Personalize Your Keyboard: Precise Text Pasting Hotkeys</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-samsung-galaxy-s23-ultra-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Samsung Galaxy S23 Ultra? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-start-guide-for-efficient-note-placement-in-win11win10/"><u>Quick-Start Guide for Efficient Note Placement in Win11/Win10</u></a></li>
<li><a href="https://printer-issues.techidaily.com/reconciled-printer-not-responding/"><u>Reconciled: Printer Not Responding</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-connection-issues-solutions-for-lost-ark-players/"><u>Resolving Connection Issues: Solutions for Lost Ark Players</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-stalled-downloads-in-qbittorrent-for-windows/"><u>Reviving Stalled Downloads in qBittorrent for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/skyrim-to-nostalgia-windows-11-reskins-into-98-style/"><u>Skyrim to Nostalgia: Windows 11 Reskins Into 98 Style</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-disable-protected-app-ban-on-windows/"><u>Steps to Disable Protected App Ban on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-windows-login-new-pin-creation/"><u>Streamline Your Windows Login: New PIN Creation</u></a></li>
<li><a href="https://win11.techidaily.com/the-artisans-approach-to-perfect-slide-printouts-from-powerpoint-in-windows/"><u>The Artisan's Approach to Perfect Slide Printouts From PowerPoint in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-guide-to-widget-personalization-on-windows-11-pcs/"><u>The Beginner's Guide to Widget Personalization on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-most-impressive-windows-10-sketch-software-lineup/"><u>The Most Impressive Windows 10 Sketch Software Lineup</u></a></li>
<li><a href="https://games-able.techidaily.com/the-twitch-guide-platform-overview-and-streamer-resources/"><u>The Twitch Guide: Platform Overview and Streamer Resources</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/unlock-the-secrets-of-automatic-youtube-videos-on-fb/"><u>Unlock the Secrets of Automatic YouTube Videos on FB</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-spiritual-command-center-of-windows-11-os/"><u>Unlocking The Spiritual Command Center of Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-disruptions-preventing-unexpected-crashes-in-dwarf-fortress/"><u>Unraveling Disruptions: Preventing Unexpected Crashes in Dwarf Fortress</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-when-windows-cant-locate-powershell-console/"><u>What to Do When Windows Can't Locate PowerShell Console</u></a></li>
<li><a href="https://win11.techidaily.com/windows-installation-manual-for-chatgpt/"><u>Windows Installation Manual for ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/windows-users-save-your-keys-from-failure/"><u>Windows Users: Save Your Keys From Failure</u></a></li>
</ul></div>
