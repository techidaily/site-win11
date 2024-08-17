---
title: Augmenting Time-Honored DirectX Experiences Through DXVK
date: 2024-08-15T23:16:22.034Z
updated: 2024-08-16T23:16:22.034Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Augmenting Time-Honored DirectX Experiences Through DXVK
excerpt: This Article Describes Augmenting Time-Honored DirectX Experiences Through DXVK
keywords: DirectX Enhancement,X Window Improvement,DXVK Benefits,Virtualization for Gaming,Cross-Platform Rendering,Performance Boosting,Emulation Innovation
thumbnail: https://thmb.techidaily.com/fb64d3334f8fecc4f94c1ae3403a6dd894e812df5486b2d51ee08c850ba80fdd.jpg
---

## Augmenting Time-Honored DirectX Experiences Through DXVK

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

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
3. Store the downloaded archive somewhere, for you will need to extract its contents to the folder of every game you want to run with DXVK instead of Direct3D.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### How to Choose the Correct DXVK Version

 If you need to know which version of Direct3D your game is using, the PC Gaming Wiki website can help.

1. Visit [PC Gaming Wiki](https://pcgamingwiki.com/) with your browser, and use the search field on the top right to seek the game to which you want to add DXVK.
2. When you find your game, visit its page and scroll down to reach the **Other Information** section. Turn your attention to the API tables. There, on the **Technical Specs** and **Supported** columns, you will see the version of Direct3D your game is using. Underneath, the **Executable**, **32-bit**, and **64-bit** columns will "tell" you which architecture you should choose.  
![PCGamingWiki Game API Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/pcgamingwiki-game-api-information-1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How to Add DXVK to Your Games

 Now that you know which Direct3D version and CPU architecture your game uses, you can add the correct version of DXVK to its folder.

1. Open the DXVK archive with your favorite archive manager (for this article, we're using WinRAR), and enter the single DXVK folder you'll see there.  
![DXVK Folder Within Archive 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-folder-within-archive-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
2. Inside, you'll find two subfolders, one for each computer architecture. Enter the correct one for your game. Even if your OS is 64-bit, like most versions of Windows today, if your game is 32-bit, you should go for the 32-bit folder.  
![DXVK 32 bit and 64 bit folders within archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-32-bit-and-64-bit-folders-within-archive-1.jpg)
3. Select the **DXGI.DLL** plus the correct DLL for the version of **Direct3D** your game is using. As you will see, there are three more DLLs, one for each of the previous versions of Direct3D: 9, 10, and 11.  
![DXVK DLLs Within Archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-dlls-within-archive-1.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Find the local folder where your game is installed and locate the subfolder with its executable ("the file from which the game runs"). Extract the DLLs from the previous step to this folder.  
![Extracting DXVK DLLs To Game Directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/extracting-dxvk-dlls-to-game-directory-1.jpg)

### How to Test and Benchmark Your Enhanced Game

 If you run your game now, it should use Vulkan instead of Direct3D and hopefully perform better.

 Even if you don't see any dramatic changes in frame rates, sometimes the improvements can be "felt" in other ways. For example, we tried DXVK with the classic Batman: Arkham City on a PC equipped with a Ryzen 5900x, 64GBs of RAM, and an Nvidia RTX 3070 GPU. Our hardware was already over this old game's top specs, achieving very high frame rates. Even if they got higher with Vulkan, the difference wouldn't be easily perceivable.

![Arkham-City-Instant-Transitions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/arkham-city-instant-transitions.jpg)

 However, the game's action felt smoother. Transitions between screens, loading levels, and pressing Alt + Tab were almost instant with DXVK.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## When You Should Not Use DXVK

 DXVK has many benefits and can bring the performance of older games into the modern era. Despite this, it's not a silver bullet for improved performance, and sometimes it's just not worth using it.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. DXVK Doesn't Improve the Game's Performance

 If you've added the DXVK DLLs to your game but saw no difference afterward, you can remove them again if you like. You can delete the DLLs you've added to a game's folder to do that.

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
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
<li><a href="https://fox-access.techidaily.com/new-best-power-packs-for-black-gopro-hero5-cameras-authenticity-confirmed/"><u>[New] Best Power Packs for Black GoPro Hero5 Cameras – Authenticity Confirmed</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-elevating-video-reach-the-role-of-smart-backlinking-techniques/"><u>[New] In 2024, Elevating Video Reach  The Role of Smart Backlinking Techniques</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-creative-composers-cache-essential-no-cost-afx-tools/"><u>[Updated] In 2024, Creative Composer's Cache  Essential, No-Cost AFX Tools</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-mastering-viral-videos-creating-engaging-memes-for-fbinsta-for-2024/"><u>[Updated] Mastering Viral Videos  Creating Engaging Memes for FB/Insta for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-quick-snapshots-on-xbox-one-a-users-manual-for-2024/"><u>[Updated] Quick Snapshots on Xbox One  A User's Manual for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-simple-steps-to-change-iphones-call-alert-sounds/"><u>[Updated] Simple Steps to Change iPhones' Call Alert Sounds</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-honor-x9a-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Honor X9a | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-social-strategies-for-disseminating-health-information/"><u>2024 Approved  Social Strategies for Disseminating Health Information</u></a></li>
<li><a href="https://win11.techidaily.com/altering-security-protocols-for-generalist-windows-user/"><u>Altering Security Protocols for Generalist Windows User</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-windows-screenshot-game-4-key-solutions/"><u>Boost Your Windows Screenshot Game: 4 Key Solutions.</u></a></li>
<li><a href="https://extra-resources.techidaily.com/boosting-visuals-implementing-filters-on-devices/"><u>Boosting Visuals  Implementing Filters on Devices</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-windows-11-and-10s-s-mode/"><u>Breaking Free From Windows 11 and 10'S S Mode</u></a></li>
<li><a href="https://fox-access.techidaily.com/champion-steadicams-for-uav-filmmaking-excellence-for-2024/"><u>Champion Steadicams for UAV Filmmaking Excellence for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/digital-detox-for-pcs-a-collection-of-13-revival-methods/"><u>Digital Detox for PCs: A Collection of 13 Revival Methods</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-better-performance-on-roblox-windows-edition/"><u>Elevate Your Gaming: Better Performance on Roblox Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-linux-capabilities-through-windows-software/"><u>Elevating Linux Capabilities Through Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-package-registration-problems-on-windows-devices/"><u>Eliminating Package Registration Problems on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/hiding-archives-within-pictures-techniques-for-windows-users/"><u>Hiding Archives Within Pictures: Techniques for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-unresponsive-mail-alerts-on-windows-11/"><u>How to Overcome Unresponsive Mail Alerts on Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-fundamentals-of-digital-tale-construction/"><u>In 2024, Fundamentals of Digital Tale Construction</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-itel-s23plus-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Itel S23+? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-things-you-should-know-when-unlocking-total-wireless-of-apple-iphone-6s-plus-by-drfone-ios/"><u>In 2024, Things You Should Know When Unlocking Total Wireless Of Apple iPhone 6s Plus</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-top-11-brain-games-engaging-trivia-channels/"><u>In 2024, Top 11 Brain Games  Engaging Trivia Channels</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/introducing-the-user-friendly-overhaul-of-stellars-data-rescue-application/"><u>Introducing the User-Friendly Overhaul of Stellar’s Data Rescue Application</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-seamless-program-deployment/"><u>Navigating Windows 11'S Seamless Program Deployment</u></a></li>
<li><a href="https://win11.techidaily.com/no-window-no-problem-master-the-art-of-reviving-hidden-apps-on-win-1011-with-6-tactics/"><u>No Window, No Problem! Master the Art of Reviving Hidden Apps on Win 10/11 with 6 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-camera-app-error-0xa00f425d-in-windows-11/"><u>Overcoming Camera App Error 0xA00F425D in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-get-assistance-problems/"><u>Overcoming Windows 11 'Get Assistance' Problems</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-error-nvidia-geforce-x0001/"><u>Overcoming Windows 11 Error: Nvidia GeForce X0001</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unbidden-command-window-activations/"><u>Preventing Unbidden Command Window Activations</u></a></li>
<li><a href="https://win11.techidaily.com/quantify-windows-computer-power-usage-for-optimization/"><u>Quantify Windows Computer Power Usage for Optimization</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-silent-speaker-issue-in-win11-environments/"><u>Resolving Silent Speaker Issue in Win11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-how-ai-pcs-outperform-standard-computers/"><u>Revealing How AI PCs Outperform Standard Computers</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-winget-a-guide-for-windows-11-users/"><u>Reviving Winget: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-remove-programs-without-permission-in-windows/"><u>Steps to Remove Programs Without Permission in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-microsofts-activation-error-code-0x8007251d/"><u>Tackling Microsoft's Activation Error Code 0X8007251d</u></a></li>
<li><a href="https://win11.techidaily.com/the-end-of-an-era-microsofts-abandonment-of-windows-7-and-81/"><u>The End of an Era: Microsoft's Abandonment of Windows 7 and 8.1</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-chaos-into-clarity-with-obsidian-visual-techniques/"><u>Transforming Chaos Into Clarity with Obsidian Visual Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-steam-disconnect-in-windows-os/"><u>Troubleshoot Steam Disconnect in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unblock-your-pcs-usb-troubleshooting-guide-for-windows-users/"><u>Unblock Your PC's USB: Troubleshooting Guide for Windows Users</u></a></li>
<li><a href="https://fox-that.techidaily.com/understanding-imessages-converted-into-texts-is-this-a-sign-youre-blocked/"><u>Understanding iMessages Converted Into Texts: Is This a Sign You're Blocked?</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/watch-dogs-legion-critique-the-unveiling-of-a-fresh-environment-in-the-franchise/"><u>Watch Dogs: Legion Critique - The Unveiling of a Fresh Environment in the Franchise</u></a></li>
</ul></div>
