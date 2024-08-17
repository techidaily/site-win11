---
title: Flattening Windows 11 Corner Style
date: 2024-08-15T23:28:59.364Z
updated: 2024-08-16T23:28:59.364Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Flattening Windows 11 Corner Style
excerpt: This Article Describes Flattening Windows 11 Corner Style
keywords: Win11 Modernize,Flat UI Window,Cornerless PC Aesthetic,Unified Windows Design,Sleek Windows Edge,Streamlined WS11 Interface,Simplified Windows Style
thumbnail: https://thmb.techidaily.com/4f7878f35a5617dd30422b38a025795d7b590bfdd2ba7a274f89a9a6584223ab.jpg
---

## Flattening Windows 11 Corner Style

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
## 2\. How to Disable Rounded Corners in Windows 11 Using the Registry Editor

 Don't want to use a third-party tool? No problem. You can also disable rounded corners in Windows 11 by making changes to the Windows Registry. However, it's crucial to exercise caution, as modifying registry files without proper knowledge can be risky.

 Before you proceed, consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just in case. After that, use these steps to disable rounded corners via the Registry Editor:

1. Press **Win + S** to open the search menu.
2. Type in **registry editor** and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Navigate to **Computer > HKEY\_CURRENT\_USER > Software > Microsoft > Windows > DWM**.
5. Right-click on the **DWM** key and select **New > DWORD (32-bit) Value**. Rename it to **UseWindowFrameStagingBuffer**.
6. Double-click the newly created DWORD and enter **0** in the **Value data** field. Then, click **OK**.
7. [Restart your PC](https://www.makeuseof.com/windows-restart-methods/) to apply the changes.  
![Disable Rounded Corners in Windows 11 via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rounded-corners-in-windows-11-via-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-audiences-choice-for-best-action-capture-tools/"><u>[New] 2024 Approved  Audience's Choice for Best Action Capture Tools</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-capturing-the-essence-of-hits-shortform-music-video-tips/"><u>[New] 2024 Approved  Capturing the Essence of Hits  Shortform Music Video Tips</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-the-minecraft-enthusiasts-blueprint-6-essential-recordings-strategies/"><u>[New] In 2024, The Minecraft Enthusiast's Blueprint  6 Essential Recordings Strategies</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-iphones-panoramic-videos-explained-for-fb-sharing-for-2024/"><u>[New] IPhone's Panoramic Videos Explained for FB Sharing for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/outube-kiddie-corner-10-year-old-ryan-hits-millionaire-mark-for-2024/"><u>[New] YouTube Kiddie Corner  10-Year-Old Ryan Hits Millionaire Mark for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-discover-the-best-mac-gif-recorders-now/"><u>[Updated] 2024 Approved  Discover the Best Mac GIF Recorders Now</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-micro-movies-on-facebook-galore/"><u>[Updated] Micro-Movies on Facebook Galore</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-secrets-for-hd-streaming-on-the-worlds-largest-social-network/"><u>[Updated] Secrets for HD Streaming on the World's Largest Social Network</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-quintessential-stop-motion-gems-for-cinephiles/"><u>2024 Approved  Quintessential Stop-Motion Gems for Cinephiles</u></a></li>
<li><a href="https://win11.techidaily.com/7-proven-methods-for-restoring-optional-features-on-pc/"><u>7 Proven Methods for Restoring Optional Features on PC</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-tecno-pova-6-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Tecno Pova 6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/a-beginners-guide-to-video-editing-on-mac-create-stunning-movies/"><u>A Beginners Guide to Video Editing on Mac Create Stunning Movies</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-recovery-mode-on-microsoft-devices/"><u>Accessing Recovery Mode on Microsoft Devices</u></a></li>
<li><a href="https://win11.techidaily.com/address-excel-display-issue-in-windows-notepad/"><u>Address: Excel Display Issue in Windows Notepad</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dxgi-failures-on-windows-1011/"><u>Addressing DXGI Failures on Windows 10/11</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-sony-xperia-5-v-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Sony Xperia 5 V? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boot-time-essentials-configuring-windows-startups/"><u>Boot Time Essentials: Configuring Windows Startups</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-code-of-windowsstore-folder-protection/"><u>Breaking the Code of WindowsStore Folder Protection</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-bandwidth-gap-between-laptops-phones/"><u>Bridging the Bandwidth Gap Between Laptops, Phones</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-lock-essential-tpm-hacks-for-windows-11/"><u>Bypassing the Lock: Essential TPM Hacks for Windows 11</u></a></li>
<li><a href="https://article-helps.techidaily.com/capturing-photos-from-moving-frames-on-windows-11/"><u>Capturing Photos From Moving Frames on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/connect-your-games-across-screens-win-11-and-android-via-google-linkup/"><u>Connect Your Games Across Screens: Win 11 & Android via Google Linkup</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/effortless-repetition-replay-your-youtube-videos-via-tv-connection/"><u>Effortless Repetition  Replay Your YouTube Videos via TV Connection</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-file-examination-in-win1011-with-new-tool-integration/"><u>Elevate File Examination in Win10/11 with New Tool Integration</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-typing-managing-filter-keys-on-pcs/"><u>Elevate Your Typing: Managing Filter Keys on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-hyper-v-in-windows-11-steps-to-follow/"><u>Enabling Hyper-V in Windows 11: Steps to Follow</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-regaining-original-windows-configs/"><u>Expert Advice: Regaining Original Windows Configs</u></a></li>
<li><a href="https://win11.techidaily.com/first-steps-in-windows-11-here-are-top-8-blunders-to-evade/"><u>First Steps in Windows 11? Here Are Top 8 Blunders to Evade</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-absent-bluetooth-listings-on-pc-device-manager/"><u>Fixing Absent Bluetooth Listings on PC Device Manager</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-helldivers-ii-how-to-resolve-the-initial-black-screen-issue-upon-launch/"><u>Fixing Helldivers II - How to Resolve the Initial Black Screen Issue Upon Launch</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-samsung-galaxy-s24plus-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-motorola-g54-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-update-error-0x80246007-in-windows-11-and-11/"><u>How to Fix the Windows Update Error 0X80246007 in Windows 11 & 11</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-samsung-galaxy-a23-5g-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Samsung Galaxy A23 5G Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-gmail-password-on-oppo-a59-5g-devices-by-drfone-android/"><u>How to Reset Gmail Password on Oppo A59 5G Devices</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-unlock-icloud-account-without-password-from-apple-iphone-xr-by-drfone-ios/"><u>In 2024, 3 Effective Ways to Unlock iCloud Account Without Password From Apple iPhone XR</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-oneplus-nord-ce-3-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For OnePlus Nord CE 3 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-download-playback-streaming-youtube-videos-on-ios-securely-and-smoothly/"><u>In 2024, Download Playback  Streaming Youtube Videos on iOS Securely and Smoothly</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-infinix-smart-7-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Infinix Smart 7 for Streaming | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-screen-brilliance-adjustments-in-windows-11/"><u>Mastering Screen Brilliance Adjustments in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-correcting-error-740-on-winos/"><u>Mastering the Art of Correcting Error 740 on WINOS</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721473165289-overcome-iphone-ringsilent-switch-issues-expert-tips-for-effective-solutions/"><u>Overcome iPhone Ring/Silent Switch Issues: Expert Tips for Effective Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sluggishness-fixing-edge-speed-woes-in-windows-10plus11/"><u>Overcoming Sluggishness: Fixing Edge Speed Woes in Windows 10+11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unrecognizable-hardware-in-windows-1011/"><u>Overcoming Unrecognizable Hardware in Windows 10/11</u></a></li>
<li><a href="https://win-answers.techidaily.com/pc-gamers-guide-fixing-the-crash-problem-in-rainbow-six-extraction-game/"><u>PC Gamers Guide: Fixing the Crash Problem in Rainbow Six Extraction Game</u></a></li>
<li><a href="https://win11.techidaily.com/pioneering-techniques-for-effective-qr-scanning-on-pcs/"><u>Pioneering Techniques for Effective QR Scanning on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-microsoft-office-365-fault-code-30015-26/"><u>Rectify Microsoft Office 365 Fault: Code 30015-26</u></a></li>
<li><a href="https://tech-revival.techidaily.com/reviving-your-sound-blaster-mic-a-step-by-step-guide/"><u>Reviving Your Sound Blaster Mic: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/running-task-manager-administrative-command-for-windows-11/"><u>Running Task Manager: Administrative Command for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/severing-cloud-storage-bond-onedrive-from-your-microsoft-account-in-windows/"><u>Severing Cloud Storage Bond: OneDrive From Your Microsoft Account in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/sleight-of-keyboard-how-to-make-keys-unseen/"><u>Sleight of Keyboard: How to Make Keys Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/speak-clearly-write-exactly-using-whisper-in-windows/"><u>Speak Clearly, Write Exactly: Using Whisper in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-steam-network-failure-on-modern-pc-win11/"><u>Tackling Steam Network Failure on Modern PC, Win11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-artificial-intelligence-the-distinction-between-strong-and-weak-ai/"><u>Understanding Artificial Intelligence: The Distinction Between Strong and Weak AI</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-faster-typing-using-windows-powertools/"><u>Unleash Faster Typing Using Windows' PowerTools</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-your-samsung-galaxy-m14-5gs-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>Unlock Your Samsung Galaxy M14 5Gs Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-post-update-linux-subsystem-challenges-on-windows-11/"><u>Unraveling Post-Update Linux Subsystem Challenges on Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-clearer-photos-a-guide-to-picsarts-bg-eraser-for-2024/"><u>Unveiling Clearer Photos  A Guide to Picsart's Bg Eraser for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-user-sid-identification-methods/"><u>Unveiling Windows 11'S User SID Identification Methods</u></a></li>
<li><a href="https://techidaily.com/vivo-x100-pro-support-turn-off-screen-lock-by-drfone-android-unlock-android-unlock/"><u>Vivo X100 Pro support - Turn Off Screen Lock.</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-vivo-y78-5g-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win11-mastering-custom-key-combos-for-fixed-text-insertions/"><u>Win11: Mastering Custom Key Combos for Fixed Text Insertions</u></a></li>
<li><a href="https://win11.techidaily.com/windows-activation-the-hidden-traps-in-inexpensive-keys/"><u>Windows Activation: The Hidden Traps in Inexpensive Keys</u></a></li>
<li><a href="https://win11.techidaily.com/windows-unseen-the-emergence-of-ai-futures/"><u>Windows Unseen: The Emergence of AI Futures</u></a></li>
<li><a href="https://vp-tips.techidaily.com/xsplit-collection-comprehensive-gaming-review-for-2024/"><u>XSplit Collection  Comprehensive Gaming Review for 2024</u></a></li>
</ul></div>
