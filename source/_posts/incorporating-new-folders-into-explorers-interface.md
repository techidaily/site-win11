---
title: Incorporating New Folders Into Explorer's Interface
date: 2024-07-13T10:33:16.393Z
updated: 2024-07-14T10:33:16.393Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Incorporating New Folders Into Explorer's Interface
excerpt: This Article Describes Incorporating New Folders Into Explorer's Interface
keywords: Explore Explorer Modify,Adding Folder Windows,Changing Explore Layout,Explorer Interface Update,Folder Navigation Tool,Integrating New Directories,Altering Explorer Views
thumbnail: https://thmb.techidaily.com/f0922cdea4398af9eb93c3915c9d932ac3a495368c2166a8e69e3bccbb692700.jpg
---

## Incorporating New Folders Into Explorer's Interface

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
<li><a href="https://win11.techidaily.com/configuring-command-prompt-for-ultimate-control/"><u>Configuring Command Prompt for Ultimate Control</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-windows-11-tackling-lag-and-delay/"><u>Fast-Track Windows 11: Tackling Lag and Delay</u></a></li>
<li><a href="https://win11.techidaily.com/darkmodetoggleforwin-basedtexteditor/"><u>DarkModeToggleForWin-basedTextEditor</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-creative-anime-characters-and-scenes-for-viral-tiktoks/"><u>[Updated] 2024 Approved  Creative Anime Characters & Scenes for Viral TikToks</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-dark-screen-quandary-in-window-8/"><u>Overcoming the Dark Screen Quandary in Window 8</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-step-by-step-tutorial-for-efficient-video-capturing-via-zd/"><u>2024 Approved  Step-by-Step Tutorial for Efficient Video Capturing via ZD</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/moment-update-windows-11-unpacks-future-looking-features/"><u>Moment Update: Windows 11 Unpacks Future-Looking Features</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-oneplus-nord-3-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-step-by-step-guide-to-adding-subtitles-in-wmp/"><u>In 2024, Step-by-Step Guide to Adding Subtitles in WMP</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-monetization-magic-geek-channels/"><u>In 2024, Monetization Magic  Geek Channels</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-s17e-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo S17e Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-quick-guide-to-tecno-camon-20-pro-5g-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Tecno Camon 20 Pro 5G FRP Bypass Instantly</u></a></li>
<li><a href="https://win11.techidaily.com/cooler-computing-strategies-for-gamers-systems/"><u>Cooler Computing Strategies for Gamers' Systems</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/dynamic-images-from-static-pixels-from-photos-to-video/"><u>Dynamic Images From Static Pixels  From Photos to Video</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missing-action-buttons-on-windows-11-pc/"><u>Overcoming Missing Action Buttons on Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-uncover-gpo-settings/"><u>Mastering Windows: Uncover GPO Settings</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-manual-how-to-turn-off-igtv/"><u>2024 Approved  Manual  How to Turn Off IGTV</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-ink-to-paper-translation-selecting-best-windows-tabs/"><u>Ideal Ink-to-Paper Translation: Selecting Best Windows Tabs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-uninstall-microsoft-edge-from-windows-11/"><u>How to Uninstall Microsoft Edge From Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/reconnect-steam-friends-list-step-by-step-guide-windows-11/"><u>Reconnect Steam Friends List: Step-by-Step Guide, Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-fall-guys-connection-errors-on-windows/"><u>How to Fix Fall Guys Connection Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-digital-age-essential-keys-fan-deal-at-lowest-price-on-windows-11-612lifetime/"><u>Master the Digital Age - Essential Keys Fan Deal at Lowest Price on Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/top-5-sources-for-legal-comedy-soundtracks-online/"><u>Top 5 Sources for Legal Comedy Soundtracks Online</u></a></li>
<li><a href="https://win11.techidaily.com/altering-output-displays-in-window-based-os/"><u>Altering Output Displays in Window-Based OS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-lace-footage-with-music-using-premiere-pro/"><u>In 2024, Lace Footage with Music Using Premiere Pro</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-windows-mail-glitches-the-0x80072746-fix-guide/"><u>Combatting Windows Mail Glitches: The 0X80072746 Fix Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-a-complete-rundown-reels-vs-stories-on-instagram-for-2024/"><u>[Updated] A Complete Rundown  Reels vs Stories on Instagram for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-instant-access-extract-and-save-fb-videos-as-mp4s/"><u>[Updated] 2024 Approved  Instant Access  Extract and Save FB Videos as MP4s</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-connect-your-device-bluetooth-error-in-windows-11/"><u>Troubleshooting Connect Your Device Bluetooth Error in Windows 11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/the-best-audio-converter-software-for-every-need-for-2024/"><u>The Best Audio Converter Software for Every Need for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/managing-safe-browsing-in-microsofts-win11/"><u>Managing Safe Browsing in Microsoft’s Win11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-lava-yuva-3-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-encyclopedia-of-hand-centered-interaction-systems/"><u>2024 Approved  The Encyclopedia of Hand-Centered Interaction Systems</u></a></li>
<li><a href="https://win11.techidaily.com/minimizing-edges-process-count-in-windows/"><u>Minimizing Edge's Process Count in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11-start-up-with-these-simple-ideas/"><u>Streamline Windows 11 Start-Up with These Simple Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-running-intel-unison-correctly-in-windows-11/"><u>Mastering the Art of Running Intel Unison Correctly in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/experience-refined-creativity-with-microsofts-latest-paint-features/"><u>Experience Refined Creativity with Microsoft's Latest Paint Features</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-master-plan-youtube-content-into-mp4/"><u>[New] Master Plan  YouTube Content Into MP4</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/forgot-your-rog-phone-7-lock-screen-pattern-pin-or-password-heres-what-to-do-by-drfone-android-unlock-android-unlock/"><u>Forgot your ROG Phone 7 lock screen pattern, PIN or password? Here’s what to do</u></a></li>
<li><a href="https://win11.techidaily.com/7-obstacles-hindering-windows-11-upgrade-traction/"><u>7 Obstacles Hindering Windows 11 Upgrade Traction</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-security-new-passwords/"><u>Navigating Windows 11 Security: New Passwords</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-your-printer-on-windows-11-step-by-step/"><u>Fixing Your Printer on Windows 11: Step by Step</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-how-to-design-a-great-gaming-youtube-banner-with-templates/"><u>In 2024, How to Design a Great Gaming YouTube Banner with Templates</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/fcpx-hacks-smooth-skin-without-breaking-the-bank-or-using-plugins-for-2024/"><u>FCPX Hacks Smooth Skin without Breaking the Bank (or Using Plugins) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-coding-in-windows-a-guide-to-using-microsoft-copilot/"><u>Mastering Coding in Windows: A Guide to Using Microsoft Copilot</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-comprehensive-handbook-for-recording-calls-for-2024/"><u>The Comprehensive Handbook for Recording Calls for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-forgot-iphone-passcode-again-unlock-apple-iphone-13-without-passcode-now-drfone-by-drfone-ios/"><u>In 2024, Forgot iPhone Passcode Again? Unlock Apple iPhone 13 Without Passcode Now | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-accessing-the-fax-editor-in-win11/"><u>Essential Tips: Accessing the Fax Editor in Win11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-maximizing-engagement-avoiding-common-youtube-thumbnail-errors/"><u>2024 Approved  Maximizing Engagement  Avoiding Common YouTube Thumbnail Errors</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-tecno-spark-20-proplus-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Tecno Spark 20 Pro+</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-prime-10-selection-accessible-no-cost-acoustic-adjustment-services/"><u>Updated 2024 Approved Prime 10 Selection Accessible, No-Cost Acoustic Adjustment Services</u></a></li>
<li><a href="https://win11.techidaily.com/swift-resolution-to-windows-update-error-code-0xc1900101/"><u>Swift Resolution to Windows Update Error Code 0xC1900101</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-6-system-issues-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 6 System Issues? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-bsod-code-0x0000003b-and-troubleshooting-guide/"><u>Navigating Windows BSOD -Code 0X0000003B & Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-xbox-app-issues-on-your-windows-system/"><u>Overcome Xbox App Issues on Your Windows System</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-10-facts-about-instagram-reels-the-truth-you-may-ignore/"><u>[Updated] 10 Facts About Instagram Reels-The Truth You May Ignore</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-the-blueprint-to-surge-in-youtubers-popularity/"><u>[New] The Blueprint to Surge in Youtubers' Popularity</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-steam-cloud-errors-on-windows/"><u>Addressing Steam Cloud Errors on Windows</u></a></li>
</ul></div>
