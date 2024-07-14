---
title: "DXVK Uncovered: Enhancing Win-Based Gameplay Dynamics"
date: 2024-07-13T09:44:06.200Z
updated: 2024-07-14T09:44:06.200Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes DXVK Uncovered: Enhancing Win-Based Gameplay Dynamics"
excerpt: "This Article Describes DXVK Uncovered: Enhancing Win-Based Gameplay Dynamics"
keywords: DXVK Optimization,Kernel Mode Gaming,Win Dynamics Boost,Advanced Game Playing,Xbox Enhancement,Game Performance Improvement,Windows Gaming Tech
thumbnail: https://thmb.techidaily.com/f1107e3da6770974363fecbf7658ee04571722ec05c10e1ad65882453b11db44.jpg
---

## DXVK Uncovered: Enhancing Win-Based Gameplay Dynamics

 Direct3D has been a part of Windows gaming for decades, unifying the segmented PC hardware landscape under one 3D-enabled umbrella. However, an app created primarily for Linux, DXVK, is sometimes a much better option to use, even if you're on Windows.

 Would you like better compatibility and, more importantly, performance for your apps and games? Then you need to try out DXVK.

## The Problem With DirectX on Windows

 Microsoft created DirectX as a "unified solution" that helped programmers use any PC's hardware capabilities. Instead of writing different code for each hardware part, software developers could "target" DirectX's DirectDraw (2D graphics), Direct3D (hardware-accelerated 3D), and DirectSound (audio) libraries. Then, let Microsoft's solution "translate" their code to "the native language" of each hardware part.

 DirectX became an irreplaceable core technology in Windows and has been evolving since. However, there's a small catch with Direct3D: it's not 100% backward compatible.

 Microsoft, and the creators of GPUs that support the Direct3D API (as in "Nvidia, AMD, and Intel"), have occasionally dropped support for features introduced in past versions of Direct3D but which never gained traction. Thus, some older games might fail to run correctly on a modern GPU with the newest versions of Direct3D.

## What Is Vulkan?

 Supposedly a more "open" answer to Microsoft's closed-source Direct3D, OpenGL was a mutated version of the 3D graphics libraries used in Silicon Graphics' graphics workstations.

 OpenGL, though, always lagged, feature-wise, compared to Microsoft's Direct3D. Eventually, it seemed more rational to reboot the effort. That's why Vulkan, also known as "OpenGL Next", was created, offering better performance and increased control over hardware.

 Like OpenGL, and unlike Microsoft's Windows-bound Direct3D, Vulkan is "open" and cross-platform. You can use Vulkan on Windows, Linux, and even smartphones. Although not natively supported on Macs, it's usable there through MoltenVK.

 That was the short version. To learn more about Vulkan, check our article on [what Vulkan run time libraries are in Windows](https://www.makeuseof.com/tag/vulkan-run-time-libraries-windows/).

## What Is DXVK?

 DXVK is a wrapper, "translating" Direct3D to Vulkan. In the human world, a translator can be a mediator between an English and a Japanese speaker, enabling them to understand one another. Similarly, "wrappers", or "translation layers", can "take" code written for a specific piece of hardware, platform, or API, and translate it to run on another.

 DXVK was originally developed for Linux with support from Valve, which also uses it on SteamOS and the Steam Deck. You can learn more about that in our article where we saw [what is Steam Proton and how it runs Windows games on Steam Deck](https://www.makeuseof.com/what-is-steam-proton-how-does-it-run-windows-games-on-steam-deck/).

## Why Should You Use DXVK on Windows?

 If a game already runs fine on your hardware, there's no reason to use DXVK. But some games written for older versions of DirectX don't run "correctly" (if at all) on newer versions of DirectX and modern hardware.

 By "translating" old-and-buggy Direct3D code into the more modern Vulkan API, there's a minimal toll on performance (if any). At the same time, problematic games with broken graphics or missing features may become fully playable again.

 Since Vulkan is on par with Direct3D 12, and both are much better (and faster) than older versions of Direct3D (as we saw when [we compared DirectX 11 VS DirectX 12](https://www.makeuseof.com/directx-11-vs-directx-12-differences/)), "translating" old Direct3D games to Vulkan can sometimes improve the game's performance.

 Intel's work on their Arc GPUs is proof of that. Intel could try to add support for every single older title in Arc GPU drivers. Instead, Intel decided to work on further improving DXVK. Initial results from Intel's "experiment" lead up to a 2x boost in performance for older titles, with dozens rendered playable "through" DXVK.

## How to Use DXVK on Windows

 Using DXVK on Windows is easy, since there is nothing to tweak or configure. You only have to download it, extract it into a game's correct folder, and it's ready to go.

 However, you have to use the correct DXVK version that matches the Direct3D version used by your game.

 It's probably easier if we go through the whole process together to see how you can download the latest version of DXVK, identify your game's "tech", and install the correct DLLs in the proper folder.

### How to Download DXVK

 DXVK is open-source software and free to use. You can find its latest version on GitHub.

1. Visit DXVK's [official GitHub page](https://GitHub.com/doitsujin/dxvk) and click on the **Latest** version link on the right of the page, under **Releases**.
2. Scroll down on the releases page and find the **Assets** section of the latest version. Click on the latest DXVK tar.gz archive to download it. At the time of writing, it was version 2.2.  
![DXVK Latest Release Asset](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-latest-release-asset-1.jpg)
3. Store the downloaded archive somewhere, for you will need to extract its contents to the folder of every game you want to run with DXVK instead of Direct3D.

### How to Choose the Correct DXVK Version

 If you need to know which version of Direct3D your game is using, the PC Gaming Wiki website can help.

1. Visit [PC Gaming Wiki](https://pcgamingwiki.com/) with your browser, and use the search field on the top right to seek the game to which you want to add DXVK.
2. When you find your game, visit its page and scroll down to reach the **Other Information** section. Turn your attention to the API tables. There, on the **Technical Specs** and **Supported** columns, you will see the version of Direct3D your game is using. Underneath, the **Executable**, **32-bit**, and **64-bit** columns will "tell" you which architecture you should choose.  
![PCGamingWiki Game API Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/pcgamingwiki-game-api-information-1.jpg)

### How to Add DXVK to Your Games

 Now that you know which Direct3D version and CPU architecture your game uses, you can add the correct version of DXVK to its folder.

1. Open the DXVK archive with your favorite archive manager (for this article, we're using WinRAR), and enter the single DXVK folder you'll see there.  
![DXVK Folder Within Archive 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-folder-within-archive-1.jpg)
2. Inside, you'll find two subfolders, one for each computer architecture. Enter the correct one for your game. Even if your OS is 64-bit, like most versions of Windows today, if your game is 32-bit, you should go for the 32-bit folder.  
![DXVK 32 bit and 64 bit folders within archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-32-bit-and-64-bit-folders-within-archive-1.jpg)
3. Select the **DXGI.DLL** plus the correct DLL for the version of **Direct3D** your game is using. As you will see, there are three more DLLs, one for each of the previous versions of Direct3D: 9, 10, and 11.  
![DXVK DLLs Within Archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-dlls-within-archive-1.jpg)
4. Find the local folder where your game is installed and locate the subfolder with its executable ("the file from which the game runs"). Extract the DLLs from the previous step to this folder.  
![Extracting DXVK DLLs To Game Directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/extracting-dxvk-dlls-to-game-directory-1.jpg)

### How to Test and Benchmark Your Enhanced Game

 If you run your game now, it should use Vulkan instead of Direct3D and hopefully perform better.

 Even if you don't see any dramatic changes in frame rates, sometimes the improvements can be "felt" in other ways. For example, we tried DXVK with the classic Batman: Arkham City on a PC equipped with a Ryzen 5900x, 64GBs of RAM, and an Nvidia RTX 3070 GPU. Our hardware was already over this old game's top specs, achieving very high frame rates. Even if they got higher with Vulkan, the difference wouldn't be easily perceivable.

![Arkham-City-Instant-Transitions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/arkham-city-instant-transitions.jpg)

 However, the game's action felt smoother. Transitions between screens, loading levels, and pressing Alt + Tab were almost instant with DXVK.

## When You Should Not Use DXVK

 DXVK has many benefits and can bring the performance of older games into the modern era. Despite this, it's not a silver bullet for improved performance, and sometimes it's just not worth using it.

### 1\. DXVK Doesn't Improve the Game's Performance

 If you've added the DXVK DLLs to your game but saw no difference afterward, you can remove them again if you like. You can delete the DLLs you've added to a game's folder to do that.

### 2\. DXVK Causes Worse Performance or Introduces New Glitches

 Sometimes adding DXVK to a game might have the opposite effect. Unfortunately, there's no way for an end user to fix such issues.

 Did a game's performance tank or visual glitches appear after adding DXVK? Exit the game and delete the DXVK's DLLs from its directory.

### 3\. You Want to Play Your Game Online

 DXVK is a compatibility layer and only affects the graphic output of a game. Still, some companies are against any modification of their games to ensure a fair environment for everyone.

 DXVK might not be "cheating", but it's still a "game modification", and could get flagged as such.

### 4\. The Game Already Has Built-In Vulkan Support

 If a game already uses the Vulkan API, like Doom Eternal, there's no reason to set its output to Direct3D to then translate it to Vulkan.

### 5\. The Game Uses Direct3D 12

 Since Direct3D 12 is almost fully on par with Vulkan, there's nothing to gain by translating one ultra-modern graphics API to another one.

## Enhance Your Old Games With "Translated" 3D on Windows

 What started as a way to play more Windows-bound games on Linux, ended up becoming a useful compatibility solution and performance booster. So, keep a recent archive of DXVK's DLLs handy. Add them to any game where you'd like to eliminate glitches, improve its performance, get smoother in-game action, and improve its responsiveness.

 Even if it doesn't end up helping, trying it out will only take seconds, and more often than not, you might be surprised by the results.

 Would you like better compatibility and, more importantly, performance for your apps and games? Then you need to try out DXVK.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/avoiding-error-pitfalls-with-anydesk-on-windows-platforms/"><u>Avoiding Error Pitfalls with AnyDesk on Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-pathway-errors-with-windows-devices/"><u>Addressing Pathway Errors with Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-cpu-consumption-by-dropbox-on-windows-pcs/"><u>Decreasing Excessive CPU Consumption by Dropbox on Windows PCs</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-16-unique-metaverse-scenarios-demonstrating-vrs-impact/"><u>[New] 16 Unique Metaverse Scenarios Demonstrating VR's Impact</u></a></li>
<li><a href="https://fix-guide.techidaily.com/strategies-for-apps-that-wont-download-from-play-store-on-infinix-note-30-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Strategies for Apps That Wont Download From Play Store On Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-unrivaled-selection-of-top-10-mobile-video-calling-apps/"><u>[New] Unrivaled Selection of Top 10 Mobile Video Calling Apps</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-discover-the-top-10-free-game-download-sites-for-pc-and-android/"><u>New Discover the Top 10 Free Game Download Sites for PC and Android</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-overcoming-youtube-buffering-a-step-by-step-guide/"><u>2024 Approved  Overcoming YouTube Buffering   A Step-by-Step Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-windows-10-syncing-guide-effortless-mov-file-management/"><u>[New] 2024 Approved  Windows 10 Syncing Guide  Effortless .mov File Management</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-spin-swivel-and-shuffle-videos-effortlessly-using-vlc-player-for-2024/"><u>[Updated] Spin, Swivel, and Shuffle Videos Effortlessly Using VLC Player for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-xiaomi-redmi-k70e-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Xiaomi Redmi K70E | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-discoverability-of-lost-network-elements-in-winos/"><u>Enhancing Discoverability of Lost Network Elements in WinOS</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-discover-best-screenshots-software-watermark-less/"><u>[Updated] 2024 Approved  Discover Best Screenshots Software (Watermark-Less)</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-earn-big-on-tiktok-unveiling-the-top-8-profitable-approaches/"><u>[Updated] 2024 Approved  Earn Big on TikTok  Unveiling the Top 8 Profitable Approaches</u></a></li>
<li><a href="https://win11.techidaily.com/setting-updeactivating-wi-fi-data-tracking-on-windows-11/"><u>Setting Up/Deactivating Wi-Fi Data Tracking on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/guidance-to-reconnect-controlled-audio-from-windows-bluetooth-devices/"><u>Guidance to Reconnect Controlled Audio From Windows' Bluetooth Devices</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-erroneous-non-existing-device-alert-on-win-11/"><u>Overcoming Erroneous Non-Existing Device Alert on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/smashing-through-disconnection-issues-during-wins-discord-setup/"><u>Smashing Through Disconnection Issues During Win's Discord Setup</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/digital-enhancement-social-story-recorder/"><u>Digital Enhancement  Social Story Recorder</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-solutions-workarounds-when-renaming-folders-is-impossible-on-win-11/"><u>Innovative Solutions: Workarounds When Renaming Folders Is Impossible on Win 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-discover-stop-motion-a-newcomers-guide-to-tools-and-techniques/"><u>Updated Discover Stop Motion A Newcomers Guide to Tools and Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/escape-heavy-requirements-tiny11-delight/"><u>Escape Heavy Requirements: Tiny11 Delight</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-vivo-y27-4g-device-sim-by-drfone-android/"><u>Easily Unlock Your Vivo Y27 4G Device SIM</u></a></li>
<li><a href="https://win11.techidaily.com/ease-system-load-cutting-back-on-malware-scanning-power/"><u>Ease System Load: Cutting Back on Malware Scanning Power</u></a></li>
<li><a href="https://win11.techidaily.com/handling-dxgierrordeviceremoved-in-win-10-and-11/"><u>Handling DXGI_ERROR_DEVICE_REMOVED in Win 10 & 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-leveraging-user-feedback-with-instagram-story-questions/"><u>[New] 2024 Approved  Leveraging User Feedback with Instagram Story Questions</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-camera-conflict-error-0xa00f4243/"><u>Remedying Windows' Camera Conflict Error 0xA00F4243</u></a></li>
<li><a href="https://win11.techidaily.com/handling-glitches-in-microsofts-nearby-sharing-service/"><u>Handling Glitches in Microsoft's Nearby Sharing Service</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-restoring-secure-file-connections-on-win/"><u>Strategies for Restoring Secure File Connections on Win</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-keyword-mastery-the-10-best-online-resources-to-increase-views/"><u>[Updated] Keyword Mastery  The 10 Best Online Resources to Increase Views</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-professionals-complete-handbook-to-fcp-mastery/"><u>[New] Professional's Complete Handbook to FCP Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-pasting-snippets-via-crafted-keybinds-in-windows-11-and-11/"><u>Effortless Pasting Snippets via Crafted Keybinds in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-map-a-network-drive-in-windows-11/"><u>How to Map a Network Drive in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/harness-the-power-of-shortcut-creation-on-windows-11/"><u>Harness the Power of Shortcut Creation on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-conflicting-apps-camera-use-windows-error-0xa00f4243/"><u>Addressing Conflicting Apps' Camera Use: Windows Error 0xA00F4243</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-xiaomi-redmi-note-12-5g-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Xiaomi Redmi Note 12 5G to New Android? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-not-found-the-ultimate-list/"><u>Overcoming Windows Not Found: The Ultimate List</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-captivating-audiences-on-a-shoestring-budget-youtube-shorts-success-tips/"><u>2024 Approved  Captivating Audiences on a Shoestring Budget – YouTube Shorts Success Tips</u></a></li>
<li><a href="https://win11.techidaily.com/activate-direct-search-within-windows-11s-task-manager-interface/"><u>Activate Direct Search Within Windows 11'S Task Manager Interface</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-5-solutions-for-xiaomi-redmi-13c-unlock-without-password-by-drfone-android/"><u>In 2024, 5 Solutions For Xiaomi Redmi 13C Unlock Without Password</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-d3d11-hardware-error-in-w11w10-environments/"><u>Fixing D3D11 Hardware Error in W11/W10 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/busted-byteguardian-wait-weigh-your-worthiness/"><u>Busted ByteGuardian? Wait, Weigh Your Worthiness</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-survival-housing-in-minecraft-6-10-guide-for-2024/"><u>[Updated] Survival Housing in Minecraft  #6-10 Guide for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-prime-fareless-streaming-and-recording-software/"><u>[Updated] 2024 Approved  Prime Fareless Streaming & Recording Software</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-jamboree-discovering-5-entertaining-techniques/"><u>Command Prompt Jamboree: Discovering 5 Entertaining Techniques</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-unlock-your-potential-tiktok-money-making-techniques-explained/"><u>2024 Approved  Unlock Your Potential  TikTok Money-Making Techniques Explained</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-supercharge-your-video-editing-top-adobe-premiere-plugins-free/"><u>Updated 2024 Approved Supercharge Your Video Editing Top Adobe Premiere Plugins (Free)</u></a></li>
<li><a href="https://win11.techidaily.com/from-obscured-space-to-optimization-windows-guide-for-reclaiming-disk/"><u>From Obscured Space to Optimization: Windows Guide for Reclaiming Disk</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-the-best-of-the-best-top-10-4k-video-conversion-tools/"><u>Updated In 2024, The Best of the Best Top 10 4K Video Conversion Tools</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensively-unveiling-windows-11s-narrator-commands/"><u>Comprehensively Unveiling Windows 11'S Narrator Commands</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-professional-grade-hd-video-editing-software-top-5-recommendations/"><u>In 2024, Professional-Grade HD Video Editing Software Top 5 Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-activate-superior-control-over-windows-11-task-management/"><u>How to Activate Superior Control Over Windows 11 Task Management</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-revamp-for-windows-11-status-area-include-a-chosen-weather-symbol/"><u>Aesthetic Revamp for Windows 11 Status Area: Include a Chosen Weather Symbol</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-your-emulated-games-into-playnite-on-windows/"><u>How to Add Your Emulated Games Into Playnite on Windows</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-how-to-send-and-add-snapchat-gifs-100-in-easy-way/"><u>Updated In 2024, How to Send and Add Snapchat GIFs 100 in Easy Way</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-sign-out-problem-due-to-malware-intrusion/"><u>Remedying Windows Sign-Out Problem Due to Malware Intrusion</u></a></li>
</ul></div>
