---
title: Regaining Original Directory Display Preferences
date: 2024-07-13T10:53:47.815Z
updated: 2024-07-14T10:53:47.815Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regaining Original Directory Display Preferences
excerpt: This Article Describes Regaining Original Directory Display Preferences
keywords: Restore Dir Disp Settings,Fix Directory Show Options,Set Default Dir Views,Revert URL Display Mode,Correct Listing Layout,Adjust Display Preferences,Reset Display Preference
thumbnail: https://thmb.techidaily.com/f578a6dc00b86f004f0eebf050b3c39c1e5f0c46ca38580b5c0bd47ee47b9b9c.jpg
---

## Regaining Original Directory Display Preferences

 Folder View Settings in Windows help you control how the contents of a particular folder are displayed and organized. If you’ve changed these settings, but now want to reset them to the default view, it’s easy. Read this guide to learn how to reset Folder View settings on your Windows 11 PC.

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

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on [how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.
4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

### 3\. Reset Folder View Settings to Default Using Registry Editor

 The last method to reset Folder View settings involves using the Windows Registry Editor. You should only use this method if you are an experienced user and know how it works, since messing with its keys could cause serious problems. To avoid data loss, you must [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before continuing.

 To reset folder view settings using the registry editor, do the following:

1. Press**Win + R** on your keyboard to [open the Run command](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**regedit** in the text box and press Enter. This will [open the Registry Editor window](https://www.makeuseof.com/windows-11-open-registry-editor/) .
3. Navigate to the following location:  
HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\Shell
4. In the left sidebar, right-click on the**BagMRU** folder and select**Delete.**  
![Reset Folder View Settings to Default Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-using-registry-editor.jpg)
5. Click**Yes** when asked to confirm your action.
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
<li><a href="https://win11.techidaily.com/overcoming-missing-action-buttons-on-windows-11-pc/"><u>Overcoming Missing Action Buttons on Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/disable-dim-display-feature-via-control-panel-quick-guide/"><u>Disable Dim Display Feature via Control Panel Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-a-microsoft-account-and-a-local-account-are-different-on-windows/"><u>6 Ways a Microsoft Account and a Local Account Are Different on Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-essential-techniques-for-youtube-image-crafting/"><u>[New] The Essential Techniques for YouTube Image Crafting</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-unleash-the-80s-easy-vhs-effects-for-final-cut-pro-users/"><u>Updated Unleash the 80S Easy VHS Effects for Final Cut Pro Users</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-beginners-blueprint-for-initiating-instagram-discussions/"><u>[New] Beginner's Blueprint for Initiating Instagram Discussions</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11-start-up-with-these-simple-ideas/"><u>Streamline Windows 11 Start-Up with These Simple Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-running-intel-unison-correctly-in-windows-11/"><u>Mastering the Art of Running Intel Unison Correctly in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-ink-to-paper-translation-selecting-best-windows-tabs/"><u>Ideal Ink-to-Paper Translation: Selecting Best Windows Tabs</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-efficiency-quick-access-to-system-restore-in-windows-11/"><u>Unlocking Efficiency: Quick Access to System Restore in Windows 11</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/nstant-insight-into-colour-difference-filming-methods-for-2024/"><u>[New] Instant Insight Into Colour Difference Filming Methods for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-uninstall-microsoft-edge-from-windows-11/"><u>How to Uninstall Microsoft Edge From Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-tune-up-discover-windows-best-speed-solutions/"><u>Turbo Tune-Up: Discover Windows' Best Speed Solutions</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-show-your-love-how-to-create-a-beautiful-valentines-day-video-montage/"><u>Updated Show Your Love How to Create a Beautiful Valentines Day Video Montage</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-from-monochrome-to-multicolor-grading-journey/"><u>2024 Approved  From Monochrome to Multicolor  Grading Journey</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-windows-mail-glitches-the-0x80072746-fix-guide/"><u>Combatting Windows Mail Glitches: The 0X80072746 Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-windows-assistance-entry/"><u>Mastering the Art of Windows Assistance Entry</u></a></li>
<li><a href="https://win11.techidaily.com/resurrect-your-xbox-on-a-slow-pc-steps-to-take/"><u>Resurrect Your Xbox on a Slow PC: Steps to Take</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-apple-iphone-se-2020-without-anyone-knowing-drfone-by-drfone-virtual-ios/"><u>How To Leave a Life360 Group On Apple iPhone SE (2020) Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-your-printer-on-windows-11-step-by-step/"><u>Fixing Your Printer on Windows 11: Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-dark-screen-quandary-in-window-8/"><u>Overcoming the Dark Screen Quandary in Window 8</u></a></li>
<li><a href="https://win11.techidaily.com/darkmodetoggleforwin-basedtexteditor/"><u>DarkModeToggleForWin-basedTextEditor</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/gif-galore-converting-tweet-videos-at-zero-cost/"><u>GIF Galore  Converting Tweet Videos at Zero Cost</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-complete-guide-to-xiaomi-redmi-note-12-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Xiaomi Redmi Note 12 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/beneath-the-surface-steps-to-engage-with-windows-covert-personality-explorer/"><u>Beneath the Surface: Steps to Engage with Windows’ Covert Personality Explorer</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-step-by-step-strategy-for-unearthing-secret-youtube-videos/"><u>[Updated] In 2024, Step-by-Step Strategy for Unearthing Secret YouTube Videos</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-face-fluidity-adding-dynamic-blur-to-photos-via-picsart/"><u>[New] Face Fluidity  Adding Dynamic Blur to Photos via Picsart</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/is-photoshops-shake-control-a-game-changer-in-2024/"><u>Is Photoshop's Shake Control a Game Changer, In 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/mastering-instagram-engagement-the-5-key-strategies-for-influencers-today-for-2024/"><u>Mastering Instagram Engagement  The 5 Key Strategies for Influencers Today for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-poco-f5-5g-phone-forgot-password-by-drfone-android-unlock-android-unlock/"><u>How to Unlock Poco F5 5G Phone Forgot Password</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-video-editing-power-filmora-for-youtube-trailers/"><u>In 2024, Video Editing Power  Filmora for YouTube Trailers</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-security-new-passwords/"><u>Navigating Windows 11 Security: New Passwords</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-video-editing-face-off-final-cut-pro-vs-lumafusion-choosing-the-right-fit-for-2024/"><u>Updated Video Editing Face-Off Final Cut Pro vs LumaFusion - Choosing the Right Fit for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-modify-win11s-network-preferences/"><u>Guide to Modify Win11's Network Preferences</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-motorola-edge-40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-accessing-the-fax-editor-in-win11/"><u>Essential Tips: Accessing the Fax Editor in Win11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-maximizing-youtube-profits-strategies-for-revenue-growth/"><u>In 2024, Maximizing YouTube Profits  Strategies for Revenue Growth</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/high-quality-game-recordings-methods-and-tools-for-2024/"><u>High-Quality Game Recordings  Methods and Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/moment-update-windows-11-unpacks-future-looking-features/"><u>Moment Update: Windows 11 Unpacks Future-Looking Features</u></a></li>
<li><a href="https://win11.techidaily.com/minimizing-edges-process-count-in-windows/"><u>Minimizing Edge's Process Count in Windows</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/pokemon-go-cooldown-chart-on-apple-iphone-8-drfone-by-drfone-virtual-ios/"><u>Pokémon Go Cooldown Chart On Apple iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-tray-interface-with-numeric-and-caps-indicators/"><u>Personalize Tray Interface with Numeric and Caps Indicators</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-coding-in-windows-a-guide-to-using-microsoft-copilot/"><u>Mastering Coding in Windows: A Guide to Using Microsoft Copilot</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-oppo-find-x7-ultra-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Oppo Find X7 Ultra Phones</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-force-delete-or-uninstall-a-printer-in-windows-11-and-11/"><u>How to Force Delete or Uninstall a Printer in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-extend-windows-10-shutdown-for-ongoing-processes/"><u>Strategies to Extend Windows 10 Shutdown for Ongoing Processes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/leveraging-iphone-features-for-gif-storage-and-entertainment/"><u>Leveraging iPhone Features for GIF Storage & Entertainment</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-enhancing-your-stream-5-key-techniques-for-gamers/"><u>2024 Approved  Enhancing Your Stream  5 Key Techniques for Gamers</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-boost-image-impact-top-iphone-and-android-sticker-augmenting-tools/"><u>In 2024, Boost Image Impact  Top iPhone and Android Sticker Augmenting Tools</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-enable-facebook-viewing-for-appletv-users/"><u>In 2024, Enable Facebook Viewing for AppleTV Users</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-realme-narzo-n55-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Realme Narzo N55 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-windows-11-tackling-lag-and-delay/"><u>Fast-Track Windows 11: Tackling Lag and Delay</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-about-to-expire-message-on-microsoft-os/"><u>Bypassing the About To Expire Message on Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/cooler-computing-strategies-for-gamers-systems/"><u>Cooler Computing Strategies for Gamers' Systems</u></a></li>
<li><a href="https://win11.techidaily.com/a-fresh-start-for-your-computers-firewall-settings/"><u>A Fresh Start for Your Computer's Firewall Settings</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-10-royalty-free-image-websites-you-need-to-know/"><u>2024 Approved 10 Royalty-Free Image Websites You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/1719334729837-fix-unusable-compatibility-center-on-vista7-pcs-fast/"><u>Fix Unusable Compatibility Center on Vista/7 PCs Fast</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-use-of-windows-module-installer-worker/"><u>Decreasing Excessive Use of Windows Module Installer Worker</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-uncover-gpo-settings/"><u>Mastering Windows: Uncover GPO Settings</u></a></li>
<li><a href="https://data-recovery.techidaily.com/iphone-data-salvage-ensure-safety-and-restore-files/"><u>IPhone Data Salvage: Ensure Safety and Restore Files</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-mail-readability-removing-html-from-email-text/"><u>Enhancing Windows 11 Mail Readability: Removing HTML From Email Text</u></a></li>
<li><a href="https://win11.techidaily.com/7-obstacles-hindering-windows-11-upgrade-traction/"><u>7 Obstacles Hindering Windows 11 Upgrade Traction</u></a></li>
<li><a href="https://win11.techidaily.com/managing-safe-browsing-in-microsofts-win11/"><u>Managing Safe Browsing in Microsoft’s Win11</u></a></li>
<li><a href="https://win11.techidaily.com/swift-resolution-to-windows-update-error-code-0xc1900101/"><u>Swift Resolution to Windows Update Error Code 0xC1900101</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-exploring-the-best-voice-mimicry-applications-of-the-year/"><u>In 2024, Exploring the Best Voice Mimicry Applications of the Year</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-xbox-app-issues-on-your-windows-system/"><u>Overcome Xbox App Issues on Your Windows System</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-raw-footage-to-cinematic-success-in-your-youtube-channel-for-2024/"><u>[Updated] From Raw Footage to Cinematic Success in Your YouTube Channel for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-prime-selection-of-innovative-vr-cycling-games/"><u>[New] 2024 Approved  Prime Selection of Innovative VR Cycling Games</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-recipes-that-resonate-best-practices-for-eating-themed-titles/"><u>[Updated] Recipes That Resonate  Best Practices for Eating-Themed Titles</u></a></li>
</ul></div>
