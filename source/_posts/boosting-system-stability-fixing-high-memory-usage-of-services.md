---
title: "Boosting System Stability: Fixing High Memory Usage of Services"
date: 2024-08-08T13:12:32.438Z
updated: 2024-08-09T13:12:32.438Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boosting System Stability: Fixing High Memory Usage of Services"
excerpt: "This Article Describes Boosting System Stability: Fixing High Memory Usage of Services"
keywords: Service Stability Boost,MemUsage Reduction,HighMemService Fix,SystemStability Enhance,ServiceMemoryOptimize,StabilityHighMemoryFix,ServiceUseBalancing
thumbnail: https://thmb.techidaily.com/e1c802d034de253a949204241dbf65a06fa99afd9e0063ab337a82a91478e440.jpg
---

## Boosting System Stability: Fixing High Memory Usage of Services

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/024-approved-adding-tag-to-youtube-video-better-read-this-first/"><u>[New] 2024 Approved  Adding Tag to YouTube Video? Better Read This First</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-the-essential-steps-to-auto-starting-facebook-vids/"><u>[New] In 2024, The Essential Steps to Auto-Starting Facebook Vids</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-rhyme-and-share-spotlight-on-popular-tiktok-rap-hits-for-2024/"><u>[New] Rhyme & Share  Spotlight on Popular TikTok Rap Hits for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-the-emoticon-experts-guide-to-capturing-and-preserving-twitters-gif-images-for-2024/"><u>[New] The Emoticon Expert’s Guide to Capturing and Preserving Twitter's GIF Images for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-the-ultimate-list-of-flashy-discord-tags/"><u>[New] The Ultimate List of Flashy Discord Tags</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-top-5-online-facebook-video-downloader/"><u>[New] Top 5 Online Facebook Video Downloader</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-device-manager-error-unfolds/"><u>[SOLVED]: Device Manager Error Unfolds</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-cutting-edge-techniques-to-upgrade-channel-descriptions-for-2024/"><u>[Updated] Cutting-Edge Techniques to Upgrade Channel Descriptions for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-how-to-manual-for-creating-an-inclusive-and-productive-skype-chat-room-accessible-by-both-windows-and-mac-users/"><u>[Updated] How-To Manual for Creating an Inclusive and Productive Skype Chat Room Accessible by Both Windows & Mac Users</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-maximize-engagement-a-comprehensive-thumbnail-guidebook/"><u>[Updated] Maximize Engagement  A Comprehensive Thumbnail Guidebook</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-vlogging-through-verbiage-a-2023-guide-to-twitter-threads-for-2024/"><u>[Updated] Vlogging Through Verbiage - A 2023 Guide to Twitter Threads for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/5-routes-to-enter-startup-repair-on-a-pc/"><u>5 Routes to Enter Startup Repair on a PC</u></a></li>
<li><a href="https://extra-hints.techidaily.com/action-seekers-dream-the-ultimate-review-of-sj-cam-s6/"><u>Action Seeker's Dream  The Ultimate Review of SJ-CAM S6</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-zipping-with-command-prompt-step-by-step/"><u>Advanced Zipping with Command Prompt, Step by Step</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723004019476-baldurs-gate-3-crashing-on-pc-solved/"><u>Baldur’s Gate 3 Crashing on PC [Solved]</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-wi-fi-disconnect-in-win-11/"><u>Best Practices for Wi-Fi Disconnect in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-efficiency-setting-up-shortcuts-for-fixed-text-paste-and-copy/"><u>Boost Your Efficiency: Setting Up Shortcuts for Fixed Text Paste & Copy</u></a></li>
<li><a href="https://win11.techidaily.com/curing-dll-missing-error-rockalldll-in-windows-10/"><u>Curing DLL Missing Error: Rockalldll in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/effective-use-of-windows-explorer-over-traditional-ls/"><u>Effective Use of Windows Explorer Over Traditional LS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/enhance-post-strategy-with-these-top-8-ios-and-android-planners/"><u>Enhance Post Strategy with These Top 8 iOS & Android Planners</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-on-capturing-windows-calls-effectively/"><u>Essential Tips on Capturing Windows Calls Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-app-store-glitch-0x80131500/"><u>Fixing Microsoft App Store Glitch #0X80131500</u></a></li>
<li><a href="https://win11.techidaily.com/free-up-local-drives-in-win11-ensuring-file-safety-every-step-of-the-way-max-156-chars/"><u>Free Up Local Drives in Win11: Ensuring File Safety Every Step of the Way (Max 156 Chars)</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-vivo-s17e-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Vivo S17e?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-data-from-lost-or-stolen-iphone-12-pro-in-easy-steps-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How To Recover Data From Lost or Stolen iPhone 12 Pro In Easy Steps | Stellar</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-resolve-iphone-text-message-issues-with-these-10-effective-tips/"><u>How to Resolve iPhone Text Message Issues with These 10 Effective Tips</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>How to Stop Google Chrome from Tracking Your Location On Apple iPhone 13 mini? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-itel-s23-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Itel S23? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-golivefacebook-a-practical-guide-for-android-and-ios-enthusiasts/"><u>In 2024, GoLiveFacebook  A Practical Guide for Android & iOS Enthusiasts</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-passcode-from-apple-iphone-7-complete-guide-drfone-by-drfone-ios/"><u>In 2024, How To Remove Passcode From Apple iPhone 7? Complete Guide | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-complete-guide-to-itel-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Itel FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-unveiling-the-secrets-to-a-flawless-fb-live-session/"><u>In 2024, Unveiling the Secrets to a Flawless FB Live Session</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/key-strategies-for-high-definition-iptv-logging-for-2024/"><u>Key Strategies for High-Definition IPTV Logging for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-screen-use-with-a-90-degree-window-rotation-tutorial/"><u>Maximize Screen Use with a 90-Degree Window Rotation Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-surface-studio-2-almost-perfect-creators-choice/"><u>Microsoft Surface Studio 2 - Almost Perfect Creator's Choice</u></a></li>
<li><a href="https://win-answers.techidaily.com/multiversus-no-more-master-the-art-of-fixing-crashes-with-our-top-8/"><u>MultiVersus No More! Master the Art of Fixing Crashes with Our Top 지정된 8 해결책</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-public-ip-using-windows-command-window/"><u>Navigate to Public IP Using Windows Command Window</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-system-maintenance-tips-for-setting-active-windows-11-times/"><u>Navigating System Maintenance: Tips for Setting Active Windows 11 Times</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-tech-habits-dont-disable-win-11-alerts/"><u>Optimal Tech Habits: Don't Disable Win 11 Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-live-gaming-streams-on-windows-via-intels-toolkit/"><u>Optimize Live Gaming Streams on Windows via Intel's Toolkit</u></a></li>
<li><a href="https://win-solutions.techidaily.com/optimizing-graphics-performance-in-cyberpunk-2077-on-new-windows-11-issue-resolved/"><u>Optimizing Graphics Performance in Cyberpunk 2077 on New Windows 11 - Issue Resolved!</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-your-core-how-to-launch-windows-undisclosed-identity-analyzer/"><u>Peering Into Your Core: How to Launch Windows' Undisclosed Identity Analyzer</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-frozen-recycle-icon-status-in-win11/"><u>Resolving Frozen Recycle Icon Status in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/revive-the-shield-5-key-fixes-for-windows-family-protection/"><u>Revive the Shield: 5 Key Fixes for Windows Family Protection</u></a></li>
<li><a href="https://win11.techidaily.com/silent-shopkeepers-integrating-covert-window-11-menus/"><u>Silent Shopkeepers: Integrating Covert Window 11 Menus</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-microsofts-error-code-0x8007251d-for-users/"><u>Simplifying Microsoft's Error Code 0X8007251D for Users</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-workflow-5-best-windows-11-productivity-tools/"><u>Skyrocket Workflow: 5 Best Windows 11 Productivity Tools</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-wallpapers-for-each-windows-11-workspace-element/"><u>Step-by-Step Wallpapers for Each Windows 11 Workspace Element</u></a></li>
<li><a href="https://win11.techidaily.com/temporary-profile-tricks-for-uninterrupted-access/"><u>Temporary Profile Tricks for Uninterrupted Access</u></a></li>
<li><a href="https://win11.techidaily.com/the-next-generation-of-windows-microsofts-ai-copilot-revolutionizes-the-taskbar/"><u>The Next Generation of Windows: Microsoft’s AI Copilot Revolutionizes the Taskbar</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-vivo-v30-lite-5g-for-parents-drfone-by-drfone-virtual-android/"><u>Top 10 Telegram Spy Tools On Vivo V30 Lite 5G for Parents | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-starter-gopro-gear-essentials-for-2024/"><u>Top Starter GoPro Gear Essentials for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-disabled-microsoft-outlook-push-notifications/"><u>Troubleshooting Disabled Microsoft Outlook Push Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-virtual-disk-service-failure-in-windows/"><u>Troubleshooting: Resolving Virtual Disk Service Failure in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-smooth-spotify-link-functionality-in-windows-11/"><u>Unlocking Smooth Spotify Link Functionality in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-auditory-interference-mystery/"><u>Unraveling Windows' Auditory Interference Mystery</u></a></li>
<li><a href="https://win11.techidaily.com/win11-simplifying-file-server-connections/"><u>Win11: Simplifying File Server Connections</u></a></li>
</ul></div>
