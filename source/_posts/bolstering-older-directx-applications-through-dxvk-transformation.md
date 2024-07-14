---
title: Bolstering Older DirectX Applications Through DXVK Transformation
date: 2024-07-13T10:23:27.668Z
updated: 2024-07-14T10:23:27.668Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bolstering Older DirectX Applications Through DXVK Transformation
excerpt: This Article Describes Bolstering Older DirectX Applications Through DXVK Transformation
keywords: DirectX Upgrade,DXVK Enhancement,Xbox Compatibility,OpenGL Support,Video Game Retro,Codec Improvement,Performance Boost
thumbnail: https://thmb.techidaily.com/90ad0e184ba79f95e662dd6bac421c2714531f47a3dc9eccb9055a4b28f7166a.jpg
---

## Bolstering Older DirectX Applications Through DXVK Transformation

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
<li><a href="https://win11.techidaily.com/a-deep-dive-into-microsoft-family-safety-tools/"><u>A Deep Dive Into Microsoft Family Safety Tools</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-clearing-defender-history-on-windows-pcs/"><u>A Comprehensive Guide to Clearing Defender History on Windows PCs</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-easy-path-to-crafting-your-audio-book-a-detailed-tutorial-for-2024/"><u>New The Easy-Path to Crafting Your Audio Book A Detailed Tutorial for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-activating-god-control-on-pcs/"><u>A Step-by-Step Guide to Activating God Control on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/5-precise-steps-to-rectify-your-screen-res-in-windows/"><u>5 Precise Steps to Rectify Your Screen Res in Windows</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-moons-magic-dos-and-donts-of-immersive-night-photography/"><u>2024 Approved  Moon's Magic  Do's & Don'ts of Immersive Night Photography</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-the-black-desktop-background-display-issue-on-windows/"><u>8 Ways to Fix the Black Desktop Background Display Issue on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719355296197-dimming-windows-11-brightness-simple-fixes-unveiled/"><u>Dimming Windows 11 Brightness - Simple Fixes Unveiled</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-secure-your-content-free-windows-screenshot-tools/"><u>2024 Approved  Secure Your Content  Free Windows Screenshot Tools</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-use-windows-11-more-efficiently/"><u>7 Ways to Use Windows 11 More Efficiently</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/free-screenshot-and-recording-made-simple-for-android-users/"><u>Free Screenshot & Recording Made Simple for Android Users</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-era-for-windows-users-understanding-copilot-key-impact/"><u>A New Era for Windows Users: Understanding Copilot Key Impact</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-for-navigating-windows-11s-troubleshooter/"><u>A Compreenas for Navigating Windows 11'S Troubleshooter</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-swift-screen-tape-with-sound-included/"><u>2024 Approved  Swift Screen Tape with Sound Included</u></a></li>
<li><a href="https://win11.techidaily.com/5-best-windows-counterparts-to-procreate-app/"><u>5 Best Windows Counterparts to Procreate App</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-overcome-excessive-gpu-demand-in-winwm/"><u>7 Ways to Overcome Excessive GPU Demand in WinWM</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-poco-f5-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Poco F5 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719366255245-functional-failures-cure-win10-key-issues-now/"><u>Functional Failures? Cure Win10 Key Issues Now!</u></a></li>
<li><a href="https://fox-access.techidaily.com/accelerated-image-viewer-in-windows-environment/"><u>Accelerated Image Viewer in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/4-minimalist-devices-compact-windows-edition/"><u>4 Minimalist Devices: Compact Windows Edition</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-comparative-analysis-of-screen-capture-software-obs-and-fraps/"><u>In 2024, Comparative Analysis of Screen Capture Software  OBS and Fraps</u></a></li>
<li><a href="https://fox-direct.techidaily.com/the-professionals-secret-utilizing-windows-movie-maker-expertly-in-windows-8-systems/"><u>The Professional's Secret  Utilizing Windows Movie Maker Expertly in Windows 8 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-boost-your-studying-on-windows/"><u>8 Ways to Boost Your Studying on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-temporarily-disable-windows-security-in-windows-11/"><u>4 Ways to Temporarily Disable Windows Security in Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-strength-of-visual-client-commitment-to-brands/"><u>[Updated] The Strength of Visual Client Commitment to Brands</u></a></li>
<li><a href="https://games-able.techidaily.com/why-idevices-entice-me-with-top-tier-game-selection-via-apple-arcade/"><u>Why iDevices Entice Me with Top-Tier Game Selection via Apple Arcade</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-create-youtube-channel-in-mobile-personal-and-business/"><u>[Updated] In 2024, How to Create YouTube Channel in Mobile [Personal & Business]</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/a-quick-primer-on-what-is-discord/"><u>A Quick Primer On What Is Discord</u></a></li>
<li><a href="https://win11.techidaily.com/1719333062146-resolve-windows-scheduler-glitches-now/"><u>Resolve Windows Scheduler Glitches Now</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-accelerate-office-productivity-with-speech-recognition-word/"><u>[New] Accelerate Office Productivity with Speech Recognition (Word)</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-t2x-5g-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Vivo T2x 5G Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-bypass-apple-iphone-15-passcode-easily-video-inside-by-drfone-ios/"><u>How to Bypass Apple iPhone 15 Passcode Easily Video Inside</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-walkthrough-to-activate-notepad-dark-mode-on-windows-11/"><u>A Detailed Walkthrough to Activate Notepad Dark Mode on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/8-tactics-to-unlock-windows-with-persistent-pin-problems/"><u>8 Tactics to Unlock Windows with Persistent PIN Problems</u></a></li>
<li><a href="https://win11.techidaily.com/1719373181052-gpt4alls-local-window-companion-a-cost-free-chatbot-clone/"><u>GPT4All's Local Window Companion - A Cost-Free ChatBot Clone.</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-leaders-in-virtual-marvel-universe-creation/"><u>2024 Approved  Leaders in Virtual Marvel Universe Creation</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-itel-a05s-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Itel A05s? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/1719374180426-navigate-through-faulty-shift-in-windows/"><u>Navigate Through Faulty Shift in Windows.</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-resolving-upgrade-error-in-windows-os/"><u>A Step-By-Step Guide to Resolving Upgrade Error in Windows OS</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-holistic-locomotion-examination-2023/"><u>[Updated] Holistic Locomotion Examination 2023</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-walkthrough-for-installing-apps-via-wpm-on-windows-11/"><u>A Step-by-Step Walkthrough for Installing Apps via WPM on Windows 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/how-to-add-audio-to-mkv/"><u>How to Add Audio to MKV</u></a></li>
<li><a href="https://win11.techidaily.com/7-reasons-why-most-users-havent-upgraded-to-windows-11/"><u>7 Reasons Why Most Users Haven’t Upgraded to Windows 11</u></a></li>
</ul></div>
