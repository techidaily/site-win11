---
title: "Efficient Approach: Nullifying OneDrive Presence on Explore"
date: 2024-08-08T13:20:46.494Z
updated: 2024-08-09T13:20:46.494Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Efficient Approach: Nullifying OneDrive Presence on Explore"
excerpt: "This Article Describes Efficient Approach: Nullifying OneDrive Presence on Explore"
keywords: Efficient OneDrive Removal,Eliminate Drives From Windows Explorer,Stop OneDrive in File Explorer,Eradicate OneDrive Search,Disable OneDrive Quick Access,End OneDrive Explore Links,Nullify OneDrive on Windows
thumbnail: https://thmb.techidaily.com/70f241d066e5ba09e0220593e00f2a957d64d581fb486617b19976fb6093a216.jpg
---

## Efficient Approach: Nullifying OneDrive Presence on Explore

 The OneDrive cloud storage client comes pre-installed on your Windows 11 computer. By default, you'll notice a OneDrive shortcut in the left pane of File Explorer, allowing quick access to your OneDrive files and folders.

 However, if you find the shortcut cluttering or ruining your File Explorer experience, you can remove it using a registry hack. Here's how to remove the OneDrive icon from File Explorer without uninstalling OneDrive.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## How to Remove OneDrive Shortcut From File Explorer via the Registry Editor

 You can remove the OneDrive icon from File Explorer using a registry hack. This way, you can get rid of the icon in File Explorer without uninstalling the OneDrive client. If you would rather remove the app entirely, follow our guide on[removing OneDrive on Windows 11](https://www.makeuseof.com/windows-11-disable-remove-onedrive/) .

 Note that modifying the Windows registry involves risk. We recommend you[create a system restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) before you proceed with the steps below. A restore point will help you restore your computer in case something goes wrong.

 Once done, follow these steps to remove the OneDrive shortcut from File Explorer:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor. Click**Yes** if prompted by**User Account Control (UAC).**
3. Next, in the Registry Editor, navigate to the following location. Copy and paste the registry path in the editor for quicker navigation:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
4. In the right pane, right-click on**System.IsPinnedToNameSpaceTree** DWORD value and select**Modify** .  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
![remove onedrive icon windows 11 registry editor modify system is pinned to name space free](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-modify-system-is-pinnedtonamespace-free.jpg)
5. In the**Value data** field, type**0** and click**OK** .  
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![remove onedrive icon windows 11 registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor.jpg)
6. Next, navigate to the following location in Registry Editor:  
`HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Desktop\NameSpace`
7. In the left pane, right-click on**{018D5C66-4533-4307-9B53-224DE2ED1FE6}** and select**Delete** to remove the entry.  
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![remove onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/remove-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)
8. Once done, close the Registry Editor.
9. When you open File Explorer, the OneDrive icon will not be visible anymore.

## How to Show the OneDrive Icon Again in File Explorer

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
![show onedrive icon windows 11 registry editor delete key under name space](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/show-onedrive-icon-windows-11-registry-editor-delete-key-under-name-space.jpg)

 To show the OneDrive icon in File Explorer, you’ll need to modify a registry entry again. Here’s how to do it.

1. Press**Win + R** to open**Registry Editor.**
2. Next, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID\{018D5C66-4533-4307-9B53-224DE2ED1FE6}`
3. In the right pane, double-click on**System.IsPinnedToNameSpaceTree** DWORD value.
4. Next, type**1** in the**Value data f** ield and click**OK** to save the changes.
5. Relaunch File Explorer to see the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Remove OneDrive Icon Without Uninstalling OneDrive

 This registry hack is a handy way to make the OneDrive icon disappear without deleting the app entirely from your PC. Alternatively, if you don’t use the service, you can completely remove OneDrive on Windows 11 or disable the service using Group Policy Editor.


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
<li><a href="https://youtube-video-recordings.techidaily.com/new-best-practices-boosting-your-game-videos-with-tags/"><u>[New] Best Practices  Boosting Your Game Videos with Tags</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-duplex-monitoring-transcription-for-2024/"><u>[New] Duplex Monitoring Transcription for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-stop-stalled-profile-visits-on-facebook/"><u>[New] In 2024, Stop Stalled Profile Visits on Facebook</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-professionally-impressive-quick-made-valorant-game-thumbnails/"><u>[New] Professionally Impressive, Quick-Made Valorant Game Thumbnails</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-capture-and-convey-top-10-image-writing-aid-apps-iosandroid-for-2024/"><u>[Updated] Capture and Convey  Top 10 Image Writing Aid Apps (iOS/Android) for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-from-zero-to-million-in-minutes-rapidly-rise-as-an-instagram-influencer-with-these-top-tips-for-2024/"><u>[Updated] From Zero to Million in Minutes  Rapidly Rise as an Instagram Influencer with These Top Tips for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-infinite-storage-pathways-select-services-showcase/"><u>[Updated] Infinite Storage Pathways  Select Services Showcase</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-mouse-properties-on-windows-11/"><u>10 Ways to Open Mouse Properties on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/11-fresh-features-in-windows-11-post-update-milestone/"><u>11 Fresh Features in Windows 11, Post-Update Milestone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-capture-the-moment-smartphone-snapchat-recording-101/"><u>2024 Approved  Capture the Moment  Smartphone Snapchat Recording 101</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-essential-guide-the-finest-free-windows-screen-capture-tools-1-5/"><u>2024 Approved  Essential Guide  The Finest Free Windows Screen Capture Tools #1-5</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-leading-tag-tracker-software-on-major-platforms-like-fb-tweet-and-insta/"><u>2024 Approved  Leading Tag Tracker Software on Major Platforms Like FB, Tweet & Insta</u></a></li>
<li><a href="https://win11.techidaily.com/6-simple-time-management-and-productivity-apps-for-windows/"><u>6 Simple Time Management and Productivity Apps for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-methods-to-mend-your-obs-studio-connection-on-windows-pcs/"><u>7 Methods to Mend Your OBS Studio Connection on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensible-guide-to-accessing-windows-fix/"><u>A Comprehensible Guide to Accessing Windows Fix</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-quickly-opens-sticky-notes-in-windows-11/"><u>A Guide to Quickly Opens Sticky Notes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-for-optimizing-task-management-in-administrative-mode-on-windows-11/"><u>A Step-by-Step Guide for Optimizing Task Management in Administrative Mode on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-flawless-youtube-viewing-on-chrome-windows/"><u>Achieving Flawless YouTube Viewing on Chrome, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/activate-windows-11-task-managers-search-functionality/"><u>Activate Windows 11 Task Manager's Search Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-connection-dropouts-with-steam-remote/"><u>Addressing Connection Dropouts with Steam Remote</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnection-hurdles-in-nvidia-for-windows-users/"><u>Addressing Disconnection Hurdles in Nvidia for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-limited-usb-interface-on-pcs/"><u>Addressing Limited USB Interface on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-inkpad-functionality-woes/"><u>Addressing Windows Inkpad Functionality Woes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/advanced-strategies-for-enhancing-footage-with-gopro-studio/"><u>Advanced Strategies for Enhancing Footage with GoPro Studio</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-ntfs-compression-in-win11-systems/"><u>Advanced Tips for NTFS Compression in Win11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/app-and-browser-domination-on-windows-os/"><u>App & Browser Domination on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/audio-enhancement-for-windows-step-by-step-driver-instructions/"><u>Audio Enhancement for Windows: Step-by-Step Driver Instructions</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-app-guard-features-with-graphical-upgrades-on-edge/"><u>Augmenting App Guard Features with Graphical Upgrades on Edge</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-hot-zone-tips-to-prevent-pc-overheating-during-games/"><u>Avoiding the Hot Zone: Tips to Prevent PC Overheating During Games</u></a></li>
<li><a href="https://win11.techidaily.com/baffling-taskers-display-with-edge-and-others/"><u>Baffling Tasker's Display with Edge & Others</u></a></li>
<li><a href="https://extra-tips.techidaily.com/behind-the-scenes-crafting-a-movie-blueprint-for-2024/"><u>Behind the Scenes  Crafting a Movie Blueprint for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/best-6-to-do-list-programs-tailored-for-windows-11-enthusiasts/"><u>Best 6 To-Do List Programs Tailored for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-classic-gameplay-seamlessly-adding-achievements-using-retroarch/"><u>Boosting Classic Gameplay - Seamlessly Adding Achievements Using Retroarch</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-visual-quality-enable-win11s-color-adjustment/"><u>Boosting Visual Quality: Enable Win11's Color Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/1719355296197-dimming-windows-11-brightness-simple-fixes-unveiled/"><u>Dimming Windows 11 Brightness - Simple Fixes Unveiled</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/elevate-your-fan-count-top-tactics-for-fb-page-ranks-for-2024/"><u>Elevate Your Fan Count  Top Tactics for FB Page Ranks for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/gpt-4-versus-gpt-35-key-features-compared-in-detail-for-ai-enthusiasts/"><u>GPT-4 Versus GPT-3.5: Key Features Compared in Detail for AI Enthusiasts</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-your-apple-id-password-on-your-iphone-xr-by-drfone-ios/"><u>How To Change Your Apple ID Password On your iPhone XR</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Samsung Galaxy S24? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-tecno-spark-go-2024-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Recover Deleted Photos from Android Gallery App on Tecno Spark Go (2024)</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-affordable-video-editing-solutions-for-creators/"><u>In 2024, Affordable Video Editing Solutions for Creators</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-essential-strategies-for-documenting-ps3-matches/"><u>In 2024, Essential Strategies for Documenting PS3 Matches</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-precision-leaders-best-7-shooting-adventures/"><u>In 2024, Precision Leaders  Best 7 Shooting Adventures</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-blueprint-for-attracting-brands-as-youtube-affiliates/"><u>In 2024, The Blueprint for Attracting Brands as Youtube Affiliates</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tips-and-tricks-to-tell-if-your-apple-iphone-7-is-unlocked-by-drfone-ios/"><u>In 2024, Tips And Tricks To Tell if Your Apple iPhone 7 Is Unlocked</u></a></li>
<li><a href="https://unlock-android.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-vivo-g2-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Vivo G2</u></a></li>
<li><a href="https://win11.techidaily.com/1719254078043-navigating-through-windows-issues-made-simple/"><u>Navigating Through Windows Issues Made Simple</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-oppo-a59-5g-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Oppo A59 5G Screen | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/samsung-galaxy-s23-fe-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Samsung Galaxy S23 FE Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719334307866-skip-wsl-save-time/"><u>Skip WSL, Save Time</u></a></li>
<li><a href="https://win11.techidaily.com/1719330356134-unlocking-direct-storage-sharing-using-dropbox-googledrive-on-c/"><u>Unlocking Direct Storage Sharing: Using Dropbox, GoogleDrive on C</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-nokia-c210-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Nokia C210? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719277126929-windows-times-ticking-off-align-it-back/"><u>Windows Time's Ticking Off? Align It Back</u></a></li>
<li><a href="https://extra-tips.techidaily.com/youtube-to-mpeg-transformation-hacks-you-need/"><u>YouTube-to-MPEG Transformation Hacks You Need</u></a></li>
</ul></div>
