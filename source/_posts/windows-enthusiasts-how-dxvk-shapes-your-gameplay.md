---
title: Windows Enthusiasts - How DXVK Shapes Your Gameplay
date: 2024-07-13T10:25:22.896Z
updated: 2024-07-14T10:25:22.896Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows Enthusiasts - How DXVK Shapes Your Gameplay
excerpt: This Article Describes Windows Enthusiasts - How DXVK Shapes Your Gameplay
keywords: Gaming Performance Windows,DXVK Vulkan Driver Benefits,Gameplay Window Enhancement,DXVK Optimization Tech,Immersive Gaming Experience,Advanced GPU Utilization,High-Fidelity Graphics Windows
thumbnail: https://thmb.techidaily.com/1d8d4d66e7cc9a5877fb43968732d769c13ca22c34daec24e1d24e09cc0c1b30.jpg
---

## Windows Enthusiasts - How DXVK Shapes Your Gameplay

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
<li><a href="https://win11.techidaily.com/mastering-the-art-of-rescuing-flaky-windows-programs/"><u>Mastering the Art of Rescuing Flaky Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-windows-essence-crafting-and-evaluating-system-data/"><u>Peering Into Windows Essence: Crafting & Evaluating System Data</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/instant-understanding-of-keying-concepts/"><u>Instant Understanding of Keying Concepts</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-error-0x800700e1-in-windows-11-os/"><u>Essential Fixes for Error 0X800700E1 in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-video-memory-crashes-in-hogwarts-legacy-windows-edition/"><u>Remedying Video Memory Crashes in 'Hogwarts: Legacy' Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-mouse-without-borders-and-peek-features-in-powertoys/"><u>How to Use the Mouse Without Borders and Peek Features in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-shifting-printer-preferences-in-windows/"><u>Overcoming Shifting Printer Preferences in Windows</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/election-excursions-best-gamified-democracy-sites/"><u>Election Excursions  Best Gamified Democracy Sites</u></a></li>
<li><a href="https://win11.techidaily.com/from-simple-logon-to-strong-authentication-changing-your-windows-11-login-habit/"><u>From Simple Logon to Strong Authentication: Changing Your Windows 11 Login Habit</u></a></li>
<li><a href="https://win11.techidaily.com/file-locations-decoded-win11s-best-practices-for-retrieving-file-and-folder-paths-6-methods/"><u>File Locations Decoded: Win11's Best Practices for Retrieving File & Folder Paths (6 Methods)</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/assembling-an-original-identification-alphanumeric/"><u>Assembling an Original Identification Alphanumeric</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-tackle-misdirected-token-call-on-windows/"><u>Methods to Tackle Misdirected Token Call” On Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reorient-your-windows-a-guide-to-90-degree-display-adjustment/"><u>Reorient Your Windows: A Guide to 90-Degree Display Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/rebooting-strategies-your-file-explorer-fixes/"><u>Rebooting Strategies: Your File Explorer Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/foster-innovation-for-privacy-protection-explore-cutting-edge-technologies-like-onboard-anonymization-systems-or-secure-data-transmission-techniques-to-mini44/"><u>Foster Innovation for Privacy Protection: Explore Cutting-Edge Technologies Like Onboard Anonymization Systems or Secure Data Transmission Techniques to Minimize the Risk of Violating Customer's Privacy During Cookie Deliveries.</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-retain-calculator-top-status-on-win-os/"><u>Methods to Retain Calculator Top Status on Win OS</u></a></li>
<li><a href="https://facebook.techidaily.com/what-are-the-significant-shifts-in-metas-privacy-rules/"><u>What Are the Significant Shifts in Meta's Privacy Rules?</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-11s-hidden-data-files/"><u>Navigating Through Windows 11'S Hidden Data Files</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win11-22h2-for-older-systems/"><u>Navigating Win11 22H2 for Older Systems</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-media-player-disruptions/"><u>Overcoming Windows Media Player Disruptions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-solve-active-directory-issues-impacting-print-in-windows-11/"><u>How to Solve Active Directory Issues Impacting Print in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-does-microsofts-copilot-key-transform-windows-11/"><u>How Does Microsoft's Copilot Key Transform Windows 11?</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-charting-the-peak-1-shorter-videos-downloader-hub-for-2024/"><u>[New] Charting the Peak  #1 Shorter Videos Downloader Hub for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-installation-in-vmware-17-player/"><u>Mastering Windows 11 Installation in VMWare 17 Player</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-and-reset-face-id-on-iphone-14-drfone-by-drfone-ios/"><u>In 2024, How to Remove and Reset Face ID on iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-frontier-of-gesture-based-technology-advancements/"><u>[New] The Frontier of Gesture-Based Technology Advancements</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-delaying-windows-10-shutdown-processes/"><u>Mastering the Art of Delaying Windows 10 Shutdown Processes</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-precision-in-recordings-discover-the-best-10-free-slack-apps/"><u>[New] In 2024, Precision in Recordings  Discover the Best 10 Free Slack Apps</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-scripts-in-windows-quick-fixes-for-loading-powershell-failures/"><u>Enabling Scripts in Windows: Quick Fixes for Loading PowerShell Failures</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-soundless-cinema-mastering-the-art-of-audio-removal-in-movies-for-windowsmac-enthusiasts-for-2024/"><u>Updated Soundless Cinema Mastering the Art of Audio Removal in Movies for Windows/Mac Enthusiasts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/modify-homescreen-without-altering-windows-11-start-menu/"><u>Modify Homescreen without Altering Windows 11 Start Menu</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-clear-obstacles-no-access-allowed-windows-errors/"><u>Methods to Clear Obstacles: No Access Allowed Windows Errors</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/elevate-content-appeal-with-these-essential-5-tiktok-caption-techniques-for-2024/"><u>Elevate Content Appeal with These Essential 5 TikTok Caption Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/is-steam-unable-to-connect-to-the-internet-on-windows-heres-how-to-fix-it/"><u>Is Steam Unable to Connect to the Internet on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/slowing-down-the-action-vlc-video-playback-tricks-for-2024/"><u>Slowing Down the Action VLC Video Playback Tricks for 2024</u></a></li>
</ul></div>
