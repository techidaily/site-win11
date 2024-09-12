---
title: Windows Folder View Reset to Default State
date: 2024-09-11T09:46:57.501Z
updated: 2024-09-12T09:46:57.501Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115913/19272" target="_top" id="2115913">
  <img src="//a.impactradius-go.com/display-ad/19272-2115913" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115913/19272" style="position:absolute;visibility:hidden;" border="0" />
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
8. Then click**Save** and close the text editor window.
9. Finally, double-click the batch file you created, and it will reset your Folder View Settings to the default view.

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123901/26106" target="_top" id="2123901">
  <img src="//a.impactradius-go.com/display-ad/26106-2123901" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123901/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Reset Folder View Settings to Default via File Explorer

 If you only need to reset the View Settings of all folders of the same type, this method is for you. Here's what you have to do:

1. Click on Start and search for**File Explorer Options** . To learn more about it, see our guide on[how to open the Folder Options on Windows](https://www.makeuseof.com/windows-10-open-folder-options/) .
2. Now, select the**View** tab in the top bar and tap on**Reset Folders** .  
![Reset Folder View Settings to Default Via File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-folder-view-settings-to-default-via-file-explorer.jpg)
3. Click**Yes** when prompted to confirm your action.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098705/14409" target="_top" id="2098705">
  <img src="//a.impactradius-go.com/display-ad/14409-2098705" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098705/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Finally, hit**OK** and the window will close.

 This will reset your Folder View Settings to Windows' default settings.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120861/26400?prodsku=Saturn" target="_top" id="2120861">
  <img src="//a.impactradius-go.com/display-ad/26400-2120861" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120861/26400?prodsku=Saturn" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Similarly, delete the**Bags** folder and close the Registry window.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135473/26400" target="_top" id="2135473">
  <img src="//a.impactradius-go.com/display-ad/26400-2135473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135473/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-http.techidaily.com/new-in-2024-disabling-automated-podcast-suggestions-for-privacy/"><u>[New] In 2024, Disabling Automated Podcast Suggestions for Privacy</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-rising-above-internet-naysayers-and-detractors/"><u>[New] In 2024, Rising Above Internet Naysayers and Detractors</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unique-14-motion-graphics-showcasing-text/"><u>[New] Unique 14 Motion Graphics Showcasing Text</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-iconic-acting-peek-vimeo/"><u>[Updated] 2024 Approved Iconic Acting Peek - Vimeo</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-beating-the-curve-adapting-to-new-facebook-content-rules-for-2024/"><u>[Updated] Beating the Curve Adapting to New Facebook Content Rules for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-framemaster-hd-recording-suite/"><u>[Updated] FrameMaster HD Recording Suite</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1-winx-dvd-editor-pro-advanced-and-easy-to-use-dvd-software-for-windows-1011/"><u>1. WinX DVD Editor Pro: Advanced & Easy-to-Use DVD Software for Windows 10/11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-perfect-audio-connection-must-have-tips-for-podcasters/"><u>2024 Approved Perfect Audio Connection Must-Have Tips for Podcasters</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-showcasing-brilliance-iconic-anime-intros/"><u>2024 Approved Showcasing Brilliance Iconic Anime Intros</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722902421066-all-about-nothing-phone-3-projected-pricing-expected-release-date-specifications-the-buzz-continues/"><u>All About Nothing Phone 3: Projected Pricing, Expected Release Date, Specifications - The Buzz Continues!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-vivo-v29e-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Vivo V29e</u></a></li>
<li><a href="https://win-solutions.techidaily.com/check-for-software-conflicts/"><u>Check for Software Conflicts</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-file-properties-on-windows-platforms/"><u>Customizing File Properties on Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-the-lunar-client-not-functional-message-in-os/"><u>Dealing with the Lunar Client Not Functional Message in OS</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-unwanted-edge-desktop-buttons/"><u>Disabling Unwanted Edge Desktop Buttons</u></a></li>
<li><a href="https://facebook.techidaily.com/elevate-your-gameplay-with-the-ultimate-asus-vg245h-gaming-monitor/"><u>Elevate Your Gameplay with The Ultimate Asus VG245H Gaming Monitor</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-this-file-has-no-app-windows-issue/"><u>Eliminating 'This File Has No App' Windows Issue</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-edge-safety-integrate-microsofts-defender-aguard/"><u>Enhance Edge Safety: Integrate Microsoft's Defender Aguard</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-audio-integrating-dolby-atmos-in-windows/"><u>Enhance Your Audio: Integrating Dolby Atmos in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-consistent-reading-pane-openness-setup-for-email-attachments-in-ms-word/"><u>Ensuring Consistent Reading Pane Openness: Setup for Email Attachments In MS Word</u></a></li>
<li><a href="https://win11.techidaily.com/five-strategies-to-rejuvenate-file-explorer/"><u>Five Strategies to Rejuvenate File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/guide-finding-the-storage-for-your-desktop-pics/"><u>Guide: Finding the Storage for Your Desktop Pics</u></a></li>
<li><a href="https://win11.techidaily.com/handling-download-issues-with-windows-1011-files/"><u>Handling Download Issues with Windows 10/11 Files</u></a></li>
<li><a href="https://win11.techidaily.com/how-and-when-to-use-the-ping-command-in-windows/"><u>How (and When) to Use the Ping Command in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-15-pro-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 15 Pro without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-hidden-results-from-your-windows-1011-search-tool/"><u>Identifying Hidden Results From Your Windows 10/11 Search Tool</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>In 2024, How does the stardust trade cost In pokemon go On Apple iPhone 11? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-nubia-z50-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Nubia Z50 Ultra? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/journey-into-the-new-era-evolution-of-file-explorer-on-windows-11/"><u>Journey Into the New Era: Evolution of File Explorer on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/legacy-techs-leap-into-the-win11-era-a-roadmap/"><u>Legacy Tech's Leap Into the Win11 Era: A Roadmap</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-solutions-for-create-failed-issue-windows-error-30005/"><u>Mastering Solutions for Create Failed Issue - Windows Error 30005</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-error-code-0x80070570-fixes-for-broken-files-on-windows-11/"><u>Navigating Through Error Code 0X80070570: Fixes for Broken Files on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-intricate-boot-configuration-landscape/"><u>Navigating Through Windows' Intricate Boot Configuration Landscape</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-oppo-a58-4g-phone-unlock-it-now-by-drfone-android/"><u>Network Locked SIM Card Inserted On Your Oppo A58 4G Phone? Unlock It Now</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-extract-audio-from-video-top-mp4-to-mp3-apps/"><u>New 2024 Approved Extract Audio From Video Top MP4 to MP3 Apps</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-screen-quality-resetting-graphics-in-windows-11/"><u>Optimize Screen Quality: Resetting Graphics in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/prolific-path-to-excellence-our-top-7-windows-11-widget-choices/"><u>Prolific Path to Excellence: Our Top 7 Windows 11 Widget Choices</u></a></li>
<li><a href="https://win11.techidaily.com/realignment-of-data-win11-hdd-optimization-techniques/"><u>Realignment of Data: Win11 HDD Optimization Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-your-win11-experience-three-tricks-up-your-sleeve/"><u>Reboot Your Win11 Experience: Three Tricks Up Your Sleeve</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-the-start-page-for-windows-task-manager/"><u>Redefining the Start Page for Windows Task Manager</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-functionality-to-windows-photos-with-registering-packages/"><u>Reinstating Functionality to Windows Photos with Registering Packages</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-sony-xperia-10-v-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Sony Xperia 10 V Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-gaps-between-windows-explorer-folders/"><u>Resolving Gaps Between Windows Explorer Folders</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-vitality-to-slow-moving-windows-batches/"><u>Restoring Vitality to Slow-Moving Windows Batches</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/revealing-the-sonic-superiority-of-sony-wh-1000xm4-headphones/"><u>Revealing the Sonic Superiority of Sony WH-1000XM4 Headphones</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-and-solving-winerror-0x80071a90-in-windows/"><u>Simplifying & Solving WinError: 0X80071a90 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/sixfold-solution-to-off-screen-woes-a-roadmap-for-rejuvenating-your-windows-desktop/"><u>Sixfold Solution to Off-Screen Woes: A Roadmap for Rejuvenating Your Windows Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/solving-stranded-status-on-xbox-for-pc-a-practical-approach/"><u>Solving ‘Stranded’ Status on Xbox for PC: A Practical Approach</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-resolve-error-403-in-robloxwindows/"><u>Strategies to Resolve Error 403 in Roblox/Windows</u></a></li>
<li><a href="https://sound-issues.techidaily.com/successfully-installing-the-idt-hd-audio-codec-for-windows-10-step-by-step-solution/"><u>Successfully Installing the IDT HD Audio Codec for Windows 10 - Step-by-Step Solution</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-to-the-not-supported-interface-error/"><u>Swift Solutions to the Not-Supported Interface Error</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-for-dodging-enter-credentials-message-in-windows/"><u>Tactics for Dodging 'Enter Credentials' Message in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-5-best-apps-to-help-you-write-better-on-a-windows-pc/"><u>The 5 Best Apps to Help You Write Better on a Windows PC</u></a></li>
<li><a href="https://fox-helps.techidaily.com/the-pinnacle-of-personal-data-holdings-for-2024/"><u>The Pinnacle of Personal Data Holdings for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-managing-deletion-alerts-in-windows-os/"><u>Tips for Managing Deletion Alerts in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11s-full-potential-with-microsofts-copilot-key/"><u>Unlocking Windows 11'S Full Potential with Microsoft's Copilot Key</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-code-4-spotify-connection-problem-in-w10w11/"><u>Unraveling the Code 4 Spotify Connection Problem in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-taskbar-chat-discontinuation-what-does-this-mean-for-us/"><u>Windows 11 Taskbar Chat Discontinuation: What Does This Mean for Us?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-time-tangle-solved-unify-system-dates/"><u>Windows Time Tangle Solved: Unify System Dates</u></a></li>
<li><a href="https://win11.techidaily.com/winning-task-managers-for-windows-10-and-11-users/"><u>Winning Task Managers for Windows 10 & 11 Users</u></a></li>
</ul></div>

