---
title: Reinstate Your Favorite Microsoft Store for Windows Devices
date: 2024-08-16T00:03:02.944Z
updated: 2024-08-17T00:03:02.944Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstate Your Favorite Microsoft Store for Windows Devices
excerpt: This Article Describes Reinstate Your Favorite Microsoft Store for Windows Devices
keywords: WinStore Restore,MSFT Store Access,Reinstate MSOFT,Windows Device Hub,Devices Store Fix,Microsoft Window Support,Retrieve MStores
thumbnail: https://thmb.techidaily.com/3be6004f814f322eb7c81e59f5f3e6dc5377a1a28f18fb94887b3ff8d1dce543.jpg
---

## Reinstate Your Favorite Microsoft Store for Windows Devices

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://article-posts.techidaily.com/new-2024-approved-expert-picks-our-1-10-list-of-camera-lenses-for-the-best-shots/"><u>[New] 2024 Approved  Expert Picks  Our #1-10 List of Camera Lenses for the Best Shots</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-on-demand-video-preservation/"><u>[New] In 2024, On-Demand Video Preservation</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-secret-to-stellar-instagram-video-engagement-flawless-sizing-techniques/"><u>[New] The Secret to Stellar Instagram Video Engagement  Flawless Sizing Techniques</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-craft-impressive-content-with-proficient-video-cropping-and-exportation-for-2024/"><u>[Updated] Craft Impressive Content with Proficient Video Cropping & Exportation for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-perfecting-your-storytelling-chapter-division-in-youtube-videos/"><u>[Updated] Perfecting Your Storytelling  Chapter Division in YouTube Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-deck-to-deck-excellence-a-close-look-at-durecorder/"><u>2024 Approved  Deck-to-Deck Excellence  A Close Look at DuRecorder</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-optimizing-your-vlc-livestream-over-the-net/"><u>2024 Approved  Optimizing Your VLC Livestream over the Net</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-streamlined-social-integration-linktree-and-tiktok-profiles-united/"><u>2024 Approved  Streamlined Social Integration  Linktree and TikTok Profiles United</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-who-takes-the-lead-in-live-action-footage-hero-4-or-x1000v/"><u>2024 Approved  Who Takes The Lead In Live-Action Footage, Hero 4 or X1000V?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/apk-essentials-start-playing-funimate-now/"><u>APK Essentials  Start Playing Funimate Now</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/app-based-romanian-learning-by-locals/"><u>App-Based Romanian Learning by Locals</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boost-your-development-with-zero-cost-here-are-5-amazing-phi-variant-replacements-at-hand/"><u>Boost Your Development with Zero Cost: Here Are 5 Amazing Phi Variant Replacements at Hand</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-configuration-with-microsofts-pc-manager-on-w11/"><u>Conquer Configuration with Microsoft's PC Manager on W11</u></a></li>
<li><a href="https://win11.techidaily.com/consistent-connections-avoiding-disruptions-in-windows/"><u>Consistent Connections: Avoiding Disruptions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-unique-snap-configurations-in-win-os/"><u>Crafting Unique Snap Configurations in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-win-11-boot-drive-essential-tips-for-3-techniques/"><u>Creating a Win 11 Boot Drive – Essential Tips for 3 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-usefulness-of-pagefilesys-backup-storage/"><u>Decoding Windows’ Usefulness of Pagefile.sys Backup Storage</u></a></li>
<li><a href="https://win11.techidaily.com/end-hibernation-hurdles-with-easy-fixes-for-win/"><u>End Hibernation Hurdles with Easy Fixes for Win</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-shared-connectivity-options-google-versus-windows/"><u>Exploring Shared Connectivity Options: Google Versus Windows</u></a></li>
<li><a href="https://win11.techidaily.com/high-res-quests-ultimate-guide-to-playing-adventures-in-hd-using-scummvm/"><u>High-Res Quests: Ultimate Guide to Playing Adventures in HD Using ScummVM</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-a-found-apple-iphone-14-pro-by-drfone-ios/"><u>In 2024, How To Unlock A Found Apple iPhone 14 Pro?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/market-dominance-keyphrases-for-successful-advertising/"><u>Market Dominance  Keyphrases for Successful Advertising</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixed-overcoming-application-crash-error/"><u>Mastering the Art of Fixed: Overcoming 'Application Crash' Error</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-teams-screen-share-issues-quick-fixes/"><u>Microsoft Teams Screen Share Issues: Quick Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-package-open-failures-in-win11win10-systems/"><u>Navigating Package Open Failures in Win11/Win10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unwanted-keystrokes-during-typing/"><u>Preventing Unwanted Keystrokes During Typing</u></a></li>
<li><a href="https://win11.techidaily.com/regain-control-fixing-wi-fi-mouse-malfunctions-in-windows/"><u>Regain Control: Fixing Wi-Fi Mouse Malfunctions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-external-monitor-not-responding-in-windows-os/"><u>Resolving External Monitor Not Responding in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/stop-spacing-out-sounds-fixes-to-unmute-keyboard-volume/"><u>Stop Spacing Out Sounds: Fixes to Unmute Keyboard Volume</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-network-link-disruptions-in-winmc-minecraft/"><u>Tackling Network Link Disruptions in WinMC Minecraft</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-overcoming-a-non-functional-search-in-windows-11s-environment/"><u>Tips for Overcoming a Non-Functional Search in Windows 11’S Environment</u></a></li>
<li><a href="https://win11.techidaily.com/transition-to-open-source-enable-linux-subsystem-for-windows/"><u>Transition to Open Source: Enable Linux Subsystem for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/typingpros-guide-to-swift-typing-using-typingaid/"><u>TypingPros Guide to Swift Typing Using TypingAid</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-new-browsing-potential-with-gesture-controls-in-microsoft-written-by-ai/"><u>Unlocking New Browsing Potential with Gesture Controls in Microsoft' Written by AI</u></a></li>
<li><a href="https://win11.techidaily.com/unravel-windows-mysteries-get-the-support-you-need/"><u>Unravel Windows Mysteries: Get the Support You Need!</u></a></li>
<li><a href="https://screen-recording.techidaily.com/windows-snap-shotting-simplified-for-2024/"><u>Windows Snap Shotting Simplified for 2024</u></a></li>
</ul></div>
