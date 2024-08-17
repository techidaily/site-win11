---
title: Guide for Old Ribbon Revival in New Windows
date: 2024-08-15T23:59:34.826Z
updated: 2024-08-16T23:59:34.826Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guide for Old Ribbon Revival in New Windows
excerpt: This Article Describes Guide for Old Ribbon Revival in New Windows
keywords: Ribbon Guide Win,Window Ribbon Revive,New Win Ribbon Help,Ribbon Redesign Tips,Navigate Old Ribbons,Windows Ribbon Fix,Update Win Ribbon Guide
thumbnail: https://thmb.techidaily.com/d765545ba359efe066eea79e8d50579ac2c2c25cde956ba79513b5dc7e88e8de.jpg
---

## Guide for Old Ribbon Revival in New Windows

 Microsoft redesigned File Explorer’s user interface for Windows 11\. Windows 11’s File Explorer has a command bar on which you can select options. That bar replaces the tabbed ribbon interface from Windows 10’s File Explorer.

 Do you prefer the tabbed File Explorer in Windows 10? If so, you don’t have to stick with File Explorer’s command bar in Windows 11\. This is how you can restore Explorer’s classic ribbon interface on a Windows 11 PC.

## 1\. Press the Up Button in the Control Panel

 File Explorer is accessible from the Control Panel. Furthermore, Explorer will still have the old, ribbon interface from Windows 10 when you open it from there. You can access the classic File Explorer in Windows 11 by clicking the up button in the Control Panel as follows:

1. Press the **Windows + S** key combination to access Windows 11’s search box.
2. Input **Control Panel** and select to open the matching search result.
3. If the Control Panel opens in an icon view, click the **View by** drop-down menu and select **Category**.  
![The View by menu in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/view-by-menu.jpg)
4. Then click the **Up to “Desktop”** button (up arrow) button on the Control Panel’s navigation bar. Alternatively, press the **Alt + Up arrow key** keyboard shortcut.  
![The Up to Desktop button in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/up-button.jpg)

 Now you’ll see the classic File Explorer from Windows 10 that incorporates a tab bar. You’ll always need to open the Control Panel first to access classic File Explorer through it. So, consider [setting up a Control Panel shortcut](https://www.makeuseof.com/windows-11-set-up-control-panel-shortcuts/) in Windows 11 to give you more direct access.

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Manually Edit the Registry

 Users utilizing Windows 11 21H2 or earlier versions can restore the classic File Explorer ribbon by manually tweaking the registry. However, the same registry tweak will not work in Windows 11 22H2 or later builds. This is how you can restore the classic File Explorer ribbon interface by manually editing the registry:

1. Open Windows 11’s Registry Editor app. Our guide to [opening Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) includes various methods for launching that app.
2. Go to the **ShellExtensions** key by inputting this location in the Registry Editor’s address bar:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Shell Extensions\`
3. If you can’t see a **Blocked** subkey, right-click ShellExtensions and select New and Key. You can skip through to step five if you can already see a Blocked key.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/new-key-option.jpg)
4. Input **Blocked** to create that key.
5. Right-click the **Blocked** key and select **New** \> **String Value**.
6. Input **{e2bf9676-5f8f-435c-97eb-11607a5bedf7**} in the new string’s text box. You can copy and paste that string name in by selecting its text, pressing **Ctrl** \+ **C**, and then pressing **Ctrl** \+ **V**.  
![The string value for restoring File Explorer's ribbon UI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-string-value.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Then you'll need to [restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) or Windows 11 for the registry tweak to take effect.

 Now press the **File Explorer** taskbar button to see the change. Or open that file manager app with any other method you prefer to [open File Explorer on Windows](https://www.makeuseof.com/windows-open-file-explorer/). The File Explorer that opens will have the tabbed ribbon interface from Windows 10\.

![The tabbed ribbon interface in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-tabbed-ribbon-file-explorer.jpg)

 If you ever want to go back to the original command bar, delete the string you added. To do so, right-click **{e2bf9676-5f8f-435c-97eb-11607a5bedf7}** within the **Blocked** key and select **Delete**. Click **Yes** when asked to confirm deletion.

![The Delete option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/delete-option.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
## 3\. Execute a Registry Command via Command Prompt

 Alternatively, you can restore File Explorer’s classic ribbon interface by executing a command that adds the **{e2bf9676-5f8f-435c-97eb-11607a5bedf7}** string value. Note that this is another method that won’t work in Windows 11 22H2\.

 However, you can restore Explorer’s classic ribbon UI in Windows 11 21H1 and earlier build versions via the Command Prompt as follows:

1. Press **Win + S**, input the **CMD** search phrase, and select Command Prompt’s **Run as administrator** option.
2. Execute this command to restore Explorer’s classic ribbon UI:  
`reg add "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}\InprocServer32" /f /ve`  
![The command for restoring File Explorer's ribbon UI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restore-classic-file-explorer-ribbon-command.jpg)
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
3. You can bring back the command bar by executing this command:  
`reg delete "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}" /f`

 This method is somewhat more straightforward than manually editing the registry. The first command adds the **{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}** string value. Entering the second command deletes that string, which restores Explorer’s default command bar.

 If the command for restoring classic File Explorer doesn’t work when you execute it, there might be spaces at the end of it. Make sure there aren’t any extra spaces included at the end of the command before executing.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Restore Explorer’s Classic Ribbon UI With ExplorerPatcher

 You can still restore Explorer’s ribbon interface in Windows 11 22H2 and all other build versions with ExplorerPatcher. ExplorerPatcher is freeware software that enables you to customize Windows 11’s Start menu, taskbar, File Explorer, and system tray. It includes many options for [making Windows 11 look more like Windows 10](https://www.makeuseof.com/windows-11-look-like-windows-10-explorerpatcher/).

 This is how you can restore tabs in Windows 11’s File Explorer with ExplorerPatcher.

1. Open this [ExplorerPatcher Softpedia page](https://www.softpedia.com/get/Tweak/System-Tweak/Explorer-Patcher-for-Windows-11.shtml) and download the file.
2. Double-click the **ep\_setup** file to install Explorer Patcher.
3. Activate the Power User menu by right-clicking the **Start** taskbar button to select **Search**.
4. Enter **ExplorerPatcher** in the Windows 11 search box and click **Properties (ExplorerPatcher)**.
5. Click the **File Explorer** tab in ExplorerPatcher.
6. Next, click the **Control interface** option to select **Windows 10 Ribbon**.  
![The Windows 10 Ribbon option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-10-ribbon.jpg)
7. Click **Restart File Explorer** on the Properties window.

 ExplorerPatcher might also automatically apply changes to the Start menu and taskbar when installed. You can restore the original Windows 11 taskbar by selecting the **Windows 11 (default)** option on the **Taskbar** tab. To restore the original menu, select **Windows 11 (default)** for ExplorerPatcher’s **Start menu style** setting.

 ExplorerPatcher has other settings with which you can further restore the Windows 10 File Explorer design. For example, File Explorer in Windows 10 has square corners. You can restore those square corners by clicking **Other** \> **Disable rounded corners for applications windows** in ExplorerPatcher.

![The Disable rounded corners option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/disable-rounded-corners-option.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->

 Windows 11’s File Explorer also has a redesigned context menu. You can disable that new right-click menu by clicking the **Disable the Windows 11 context menu** option on the **File Explorer** tab. Then right-clicking a file in Explorer will show only the classic context menu, as in Windows 10\.

## Restore a Tabbed User Interface in Windows 11's File Explorer

 Although Windows 11’s command bar has its advantages, there are some good reasons to restore File Explorer’s tabbed ribbon UI of old with the methods above.

 For example, restoring the tabbed ribbon UI will enable you to select a **Slideshow** option for images on the **Picture Tool** tab, which isn’t accessible from the command bar. You can also select additional options for sharing files on the **Share** tab.

 Do you prefer the tabbed File Explorer in Windows 10? If so, you don’t have to stick with File Explorer’s command bar in Windows 11\. This is how you can restore Explorer’s classic ribbon interface on a Windows 11 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-cloud.techidaily.com/new-excellent-streamers-guide-to-360-degree-live-footage-for-2024/"><u>[New] Excellent Streamers' Guide to 360-Degree Live Footage for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-interactive-television-take-pot-perspectives/"><u>[New] INTERACTIVE TELEVISION TAKE  Pot Perspectives</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-music-making-magic-selecting-background-beats-for-vids-for-2024/"><u>[New] Music Making Magic  Selecting Background Beats for Vids for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-prime-strategies-in-zoom-video-to-zoom-outcomes/"><u>[New] The Prime Strategies in Zoom Video to Zoom Outcomes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-enhancing-youtube-videos-with-professional-techniques-using-wmm-for-2024/"><u>[Updated] Enhancing YouTube Videos with Professional Techniques Using WMM for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-explore-novel-editing-techniques-the-synergy-of-storyremix-and-windows-11/"><u>2024 Approved  Explore Novel Editing Techniques  The Synergy of StoryRemix & Windows 11</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-mastering-the-art-of-android-clip-inversions/"><u>2024 Approved  Mastering the Art of Android Clip Inversions</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-prime-jocular-photo-artist/"><u>2024 Approved  Prime Jocular Photo Artist</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-synesthetic-screens-the-future-of-cinema/"><u>2024 Approved  Synesthetic Screens  The Future of Cinema</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-microsoft-family-safety/"><u>A Beginner's Guide to Microsoft Family Safety</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-resource-utilization-in-wsl-android/"><u>Best Practices for Resource Utilization in WSL-Android</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-steam-content-unavailable-glitches/"><u>Bypassing Steam Content Unavailable Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-nvidia-geforce-notaxc0f1103f-error/"><u>Correcting Windows Nvidia GeForce NotaXC0F1103F Error</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-secure-network-shadows-in-windows/"><u>Crafting Secure Network Shadows in Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-where-to-find-your-favorite-music-visuals-on-the-internet/"><u>Discover Where to Find Your Favorite Music Visuals on the Internet</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-working-state-for-ccleaner-in-windows-1011-systems/"><u>Enabling Working State for CCleaner in Windows 10/11 Systems</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-logitech-speakers-up-and-running-on-windows-1178-driver-downloads-available-now/"><u>Get Your Logitech Speakers Up & Running on Windows 11/7/8: Driver Downloads Available Now!</u></a></li>
<li><a href="https://driver-download.techidaily.com/hassle-free-download-for-canon-ts6200-drivers-with-easy-update-feature/"><u>Hassle-Free Download for Canon TS6200 Drivers with Easy Update Feature</u></a></li>
<li><a href="https://win11.techidaily.com/how-regular-windows-backup-prolongs-peace-of-mind/"><u>How Regular Windows Backup Prolongs Peace of Mind</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-an-enhanced-run-tool-to-windows-10-and-11/"><u>How to Add an Enhanced Run Tool to Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-league-of-legends-disconnecting-on-windows/"><u>How to Fix League of Legends Disconnecting on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-dolby-atmos-in-windows-11-pro/"><u>How to Install Dolby Atmos in Windows 11 Pro</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-cross-platform-guide-extracting-facebook-video-content/"><u>In 2024, Cross-Platform Guide  Extracting Facebook Video Content</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-can-we-bypass-tecno-pop-7-pro-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Tecno Pop 7 Pro FRP?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-zte-nubia-z60-ultra-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on ZTE Nubia Z60 Ultra?</u></a></li>
<li><a href="https://techidaily.com/is-your-honor-100-pro-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Honor 100 Pro working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/launch-into-productivity-must-have-ms-store-picks/"><u>Launch Into Productivity: Must-Have MS Store Picks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-turn-off-corner-shaping/"><u>Mastering Windows 11: Turn Off Corner Shaping</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-windows-11-search-backup-procedure/"><u>Navigate to Windows 11 Search Backup Procedure</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/navigating-stardew-the-complete-guide-to-ginger/"><u>Navigating Stardew  The Complete Guide to Ginger</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-landscape-of-winapp-and-browser-mastery/"><u>Navigating the Landscape of WinApp and Browser Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-hello-fingerprint-malfunctions-easily/"><u>Navigating Windows Hello Fingerprint Malfunctions Easily</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-full-screen-display-defeating-windows-overscan/"><u>Optimize Full-Screen Display: Defeating Windows Overscan</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-windows-11-taskbar-performance/"><u>Optimizing Windows 11 Taskbar Performance</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unauthorized-user-error-in-windows-1111/"><u>Overcoming Unauthorized User Error in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-mobile-app-match-android-plus-windows-pc-edition/"><u>Perfect Mobile App Match: Android + Windows PC Edition</u></a></li>
<li><a href="https://win11.techidaily.com/post-install-windows-heres-how-to-get-online/"><u>Post-Install Windows? Here's How to Get Online</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-over-malfunctioning-windows-snippers/"><u>Regaining Control Over Malfunctioning Windows Snippers</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-legacy-windows-photo-viewer-features-in-win11/"><u>Restoring Legacy Windows Photo Viewer Features in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/sidestepping-error-0x80070522-on-windows-by-accessing-client-rights/"><u>Sidestepping Error 0X80070522 on Windows by Accessing Client Rights</u></a></li>
<li><a href="https://win11.techidaily.com/skirting-persistent-login-prompt-issues-in-windows/"><u>Skirting Persistent Login Prompt Issues in Windows</u></a></li>
<li><a href="https://program-issues.techidaily.com/solve-your-steam-streaming-glitches-quick-fix-tips-for-remote-play/"><u>Solve Your Steam Streaming Glitches - Quick Fix Tips for Remote Play</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-recover-lost-access-to-ubisofts-launcher/"><u>Steps to Recover Lost Access to Ubisoft's Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-windows-exception-breakpoint-errors/"><u>Strategies to Address Windows Exception Breakpoint Errors</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-fix-inaudible-microphone-during-screen-recordings/"><u>Techniques to Fix Inaudible Microphone During Screen Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-rediscovering-missing-panes-top-tips-and-hacks-for-windows-users/"><u>The Ultimate Guide to Rediscovering Missing Panes: Top Tips and Hacks for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/timeless-windows-syncing-the-digital-second-hand/"><u>Timeless Windows: Syncing the Digital Second Hand</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-optimizing-windows-lockscreen-with-spotlight/"><u>Tips for Optimizing Windows Lockscreen with Spotlight</u></a></li>
<li><a href="https://win11.techidaily.com/trimming-early-edges-methods-to-stop-tab-preload-on-windows-11/"><u>Trimming Early Edges: Methods to Stop Tab Preload on Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ultra-30-action-camera-by-garmin-detailed-reviews-and-features/"><u>Ultra 30 Action Camera by Garmin – Detailed Reviews & Features</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-11s-6-unusual-visual-cues/"><u>Understanding Windows 11'S 6 Unusual Visual Cues</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-full-power-of-task-manager-with-admin-rights-in-win11/"><u>Unleash Full Power of Task Manager with Admin Rights in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-windows-activation-error-0x8007251d-and-how-do-you-fix-it/"><u>What Is the Windows Activation Error 0X8007251D and How Do You Fix It?</u></a></li>
<li><a href="https://win11.techidaily.com/why-ditch-bot-helmed-windows-key-creation/"><u>Why Ditch Bot-Helmed Windows Key Creation?</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-customize-your-functional-keys-configuration/"><u>Win 10/11: Customize Your Functional Keys Configuration</u></a></li>
</ul></div>
