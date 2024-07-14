---
title: Adding External Disk to Explorer's Sidebar
date: 2024-07-13T11:21:15.625Z
updated: 2024-07-14T11:21:15.625Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adding External Disk to Explorer's Sidebar
excerpt: This Article Describes Adding External Disk to Explorer's Sidebar
keywords: External Disk Addition,Sidebar Extension,Disk Explorer Integration,Expanding Sidebar Storage,Portable Drive Display,Hardware Interface,File System Connectivity
thumbnail: https://thmb.techidaily.com/2d544a9f24903c4dca30f002769bbf9a409fd7c6d44eed802125a7dc9d0fc154.jpg
---

## Adding External Disk to Explorer's Sidebar

 To access the D: drive, you normally have to open File Explorer, click on **This PC** in the Navigation pane, and expand the **Devices and drives** section. With a simple hack, you can add it to the Navigation pane so you can easily access it straight from there. It will require you to tweak the Windows Registry, but don’t worry; we'll show you an extremely easy way of going about it.

## Before You Proceed…

 We are going to [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/) to add the D: drive to the Navigation Pane. This file will make changes to the Windows registry, and you need to be careful [not to mess up the Windows Registry](https://www.makeuseof.com/tag/not-accidentally-mess-windows-registry/). A slip-up could make Windows unusable.

 Furthermore, we highly recommend that you learn how to [back up and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/). That way, you have a way of returning it to the state it was in before you made any changes that broke it.

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

 The D: drive should now be visible in the bottom part of the Navigation pane.

## How Do I Remove the D: Drive From the Navigation Pane in File Explorer?

 To remove the D: drive from the navigation pane, open Notepad and then copy and paste the below text:

`Windows Registry Editor Version 5.00  
  
[-HKEY_CURRENT_USER\Software\Classes\CLSID\{0525388b-89d9-4112-bf4d-2aaccb716a7f}][HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\HideDesktopIcons\NewStartPanel]  
"{0525388b-89d9-4112-bf4d-2aaccb716a7f}"=-  
  
[-HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace\{0525388b-89d9-4112-bf4d-2aaccb716a7f}]`

 Save the file as **remove-d-drive-file-explorer.reg**. Afterward, double-click the registry file and click **Yes** on the UAC prompt. When asked if you want to continue with the merge, click **Yes** again.

 Now the D: drive should be gone from the navigation pane in File Explorer.

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
<li><a href="https://win11.techidaily.com/explore-versatility-the-best-10-uses-for-windows-powertoys-tools/"><u>Explore Versatility: The Best 10 Uses for Windows PowerToys Tools</u></a></li>
<li><a href="https://win11.techidaily.com/gently-lowering-highs-a-guide-to-windowed-serenity/"><u>Gently Lowering Highs: A Guide to Windowed Serenity</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-synching-youtube-songs-to-video-frameworks/"><u>2024 Approved  Synching YouTube Songs to Video Frameworks</u></a></li>
<li><a href="https://win11.techidaily.com/the-essence-of-version-numbering-in-windows/"><u>The Essence of Version Numbering in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-embedding-google-play-into-windows-11/"><u>Guide to Embedding Google Play Into Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/advance-your-task-management-with-windows-flow-launcher/"><u>Advance Your Task Management with Windows' Flow Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-monitor-1-and-2-in-windows/"><u>How to Change Monitor 1 and 2 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/extracting-tabbed-files-windows-11-quick-guide/"><u>Extracting Tabbed Files: Windows 11 Quick Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-simplicity-in-recording-an-overwatch-perspective/"><u>[New] Simplicity in Recording  An Overwatch Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-beast-high-cpu-usage-in-setups/"><u>Taming the Beast: High CPU Usage in Setups</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-lock-on-iphone-12-pro-by-drfone-ios/"><u>How to Bypass iCloud Lock on iPhone 12 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/solving-unseen-second-monitor-problems/"><u>Solving Unseen Second Monitor Problems</u></a></li>
<li><a href="https://win11.techidaily.com/fix-cluttered-desktop-with-removal-of-win11s-focus-icons/"><u>Fix Cluttered Desktop with Removal of Win11's Focus Icons</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/ways-to-stop-parent-tracking-your-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>Ways to stop parent tracking your Apple iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-seek-out-all-shared-media-on-messenger-platform/"><u>2024 Approved  Seek Out All Shared Media on Messenger Platform</u></a></li>
<li><a href="https://extra-resources.techidaily.com/flawless-photo-management-on-iphone-size-adjustment-basics/"><u>Flawless Photo Management on iPhone  Size Adjustment Basics</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-audio-mastery-on-a-budget-top-ten-cost-free-editors/"><u>New Audio Mastery on a Budget Top Ten Cost-Free Editors</u></a></li>
<li><a href="https://win11.techidaily.com/unplugged-access-navigating-localized-onedrive-files/"><u>Unplugged Access: Navigating Localized OneDrive Files</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/frame-by-frame-focus-high-quality-video-devices/"><u>Frame by Frame Focus  High-Quality Video Devices</u></a></li>
<li><a href="https://win11.techidaily.com/revive-typical-windows-explore-view-configuration/"><u>Revive Typical Windows Explore View Configuration</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-redmi-note-12-pro-4g-phone-without-password-by-drfone-android/"><u>How To Unlock Xiaomi Redmi Note 12 Pro 4G Phone Without Password?</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-expect-from-microsofts-win11-feb-release/"><u>What to Expect From Microsoft's Win11 Feb Release</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-bsod-data-for-system-debugging/"><u>Leveraging BSOD Data for System Debugging</u></a></li>
<li><a href="https://win11.techidaily.com/winx-troubleshooting-correcting-nvidias-retrieval-errors/"><u>WinX Troubleshooting: Correcting NVIDIA's Retrieval Errors</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-android-and-windows-11-with-webcam-capabilities/"><u>Uniting Android and Windows 11 with Webcam Capabilities</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-beyond-virtualdub-exploring-the-best-video-editing-software-alternatives/"><u>New 2024 Approved Beyond Virtualdub Exploring the Best Video Editing Software Alternatives</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/iphone-transfer-transfer-contact-from-apple-iphone-15-plus-to-iphone-without-icloud-drfone-by-drfone-transfer-from-ios/"><u>iPhone Transfer Transfer Contact from Apple iPhone 15 Plus to iPhone without iCloud | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-experience-linking-win-prefixes-and-ms-logins/"><u>Enhancing User Experience: Linking Win Prefixes & MS Logins</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-the-heart-of-windows-print-controls/"><u>Accessing the Heart of Windows Print Controls</u></a></li>
<li><a href="https://win11.techidaily.com/make-your-grans-old-computer-senior-friendly-and-simple/"><u>Make Your Gran’s Old Computer Senior-Friendly & Simple</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/elevate-tiktok-visuals-switch-backgrounds-with-confidence-and-precision-for-2024/"><u>Elevate TikTok Visuals  Switch Backgrounds with Confidence and Precision for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-perfecting-soft-audio-edges-a-guide-to-smooth-transitioning-in-imovie/"><u>Updated 2024 Approved Perfecting Soft Audio Edges A Guide to Smooth Transitioning in iMovie</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-digital-gateway-easy-desktop-connectivity-with-win-11/"><u>Unlocking the Digital Gateway: Easy Desktop Connectivity with Win 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/seamless-music-import-into-premiere-pro-workflows/"><u>Seamless Music Import Into Premiere Pro Workflows</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-error-code-0x80073cf3-at-microsoft-store-windows-1111/"><u>Unraveling Error Code 0X80073CF3 at Microsoft Store, Windows 11/11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-rapid-rendering-of-epic-battle-royale-tiles/"><u>[New] Rapid Rendering of Epic Battle Royale Tiles</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-the-leading-17-lights-and-stands-reviewed/"><u>[New] In 2024, The Leading 17 Lights & Stands Reviewed</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-quicktweet-clip-swiftly-gather-social-media-vids/"><u>[New] QuickTweet Clip  Swiftly Gather Social Media Vids</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-malwarebytes-cant-properly-called-proc/"><u>Troubleshooting Error: Malwarebytes Can't Properly Called Proc</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-from-idea-to-screen-smartphone-video-creation-tips/"><u>[New] From Idea to Screen  Smartphone Video Creation Tips</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-nuances-of-using-github-desktop-in-windows-oses/"><u>Navigating the Nuances of Using GitHub Desktop in Windows OSes</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-broad-spectrum-of-uavs/"><u>[New] Broad Spectrum of UAVs</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-on-tecno-pova-5-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Tecno Pova 5 Devices</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-mastering-the-art-of-video-framing-for-2024/"><u>New Mastering the Art of Video Framing for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-pinnacle-performance-radeons-new-era-for-2024/"><u>[New] Pinnacle Performance  Radeon's New Era for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boost-safety-measures-include-trusted-sites-on-windows-11/"><u>Boost Safety Measures: Include Trusted Sites on Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-full-guide-to-iphone-8-icloud-bypass-by-drfone-ios/"><u>In 2024, Full guide to iPhone 8 iCloud Bypass</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-frontier-of-gesture-based-technology-advancements/"><u>[New] The Frontier of Gesture-Based Technology Advancements</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-copy-pasting-malfunctions-in-windows-11/"><u>Rectifying Copy-Pasting Malfunctions in Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/step-by-step-approach-to-crafting-youtube-intros/"><u>Step-by-Step Approach to Crafting YouTube Intros</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-blueprint-to-victory-in-original-diablo/"><u>Beginner’s Blueprint to Victory in Original Diablo</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-prime-time-for-podcast-debuts/"><u>[New] 2024 Approved  Prime Time for Podcast Debuts</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-motorola-moto-g73-5g-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Motorola Moto G73 5G without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-photo-viewer-a-step-by-step-guide-for-11-users/"><u>Reviving Windows Photo Viewer: A Step-by-Step Guide for 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-error-x70-file-and-directory-recovery-on-windows-1011/"><u>Bypassing Error X70: File and Directory Recovery on Windows 10/11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/mind-blown-by-numbers-yearly-youtube-insights-in-2017/"><u>Mind Blown by Numbers  Yearly YouTube Insights in 2017</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obstacles-your-guide-to-color-perfection-on-windows/"><u>Overcoming Obstacles: Your Guide to Color Perfection on Windows</u></a></li>
</ul></div>
