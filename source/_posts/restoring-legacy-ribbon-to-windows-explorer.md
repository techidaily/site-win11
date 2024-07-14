---
title: Restoring Legacy Ribbon to Windows Explorer
date: 2024-07-13T09:45:29.037Z
updated: 2024-07-14T09:45:29.037Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Legacy Ribbon to Windows Explorer
excerpt: This Article Describes Restoring Legacy Ribbon to Windows Explorer
keywords: Restore Ribbon Windows,Ribbon Explorer Update,Legacy Ribbon Fix,WinExplorer Ribbon,Renew Explorer Features,Rebuild Window Ribbon,Reinstate Explorer Bar
thumbnail: https://thmb.techidaily.com/b034e397cf58f21c63fc5dd80cb149d6528213f9e99cf7ed2375f403fbf9fc3e.jpg
---

## Restoring Legacy Ribbon to Windows Explorer

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
7. Then you'll need to [restart File Explorer](https://www.makeuseof.com/ways-to-restart-file-explorer-windows-10/) or Windows 11 for the registry tweak to take effect.

 Now press the **File Explorer** taskbar button to see the change. Or open that file manager app with any other method you prefer to [open File Explorer on Windows](https://www.makeuseof.com/windows-open-file-explorer/). The File Explorer that opens will have the tabbed ribbon interface from Windows 10\.

![The tabbed ribbon interface in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-tabbed-ribbon-file-explorer.jpg)

 If you ever want to go back to the original command bar, delete the string you added. To do so, right-click **{e2bf9676-5f8f-435c-97eb-11607a5bedf7}** within the **Blocked** key and select **Delete**. Click **Yes** when asked to confirm deletion.

![The Delete option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/delete-option.jpg)

## 3\. Execute a Registry Command via Command Prompt

 Alternatively, you can restore File Explorer’s classic ribbon interface by executing a command that adds the **{e2bf9676-5f8f-435c-97eb-11607a5bedf7}** string value. Note that this is another method that won’t work in Windows 11 22H2\.

 However, you can restore Explorer’s classic ribbon UI in Windows 11 21H1 and earlier build versions via the Command Prompt as follows:

1. Press **Win + S**, input the **CMD** search phrase, and select Command Prompt’s **Run as administrator** option.
2. Execute this command to restore Explorer’s classic ribbon UI:  
`reg add "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}\InprocServer32" /f /ve`  
![The command for restoring File Explorer's ribbon UI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/restore-classic-file-explorer-ribbon-command.jpg)
3. You can bring back the command bar by executing this command:  
`reg delete "HKCU\Software\Classes\CLSID\{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}" /f`

 This method is somewhat more straightforward than manually editing the registry. The first command adds the **{d93ed569-3b3e-4bff-8355-3c44f6a52bb5}** string value. Entering the second command deletes that string, which restores Explorer’s default command bar.

 If the command for restoring classic File Explorer doesn’t work when you execute it, there might be spaces at the end of it. Make sure there aren’t any extra spaces included at the end of the command before executing.

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
<li><a href="https://win11.techidaily.com/flip-your-lens-6-simple-steps-for-picture-spin-on-windows-11/"><u>Flip Your Lens: 6 Simple Steps for Picture Spin on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-to-try-connections-glitch-on-windows-pcs/"><u>Quick Fix to 'Try Connections' Glitch on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/best-lighter-browsing-options-tested-for-memory-conservation/"><u>Best Lighter Browsing Options Tested For Memory Conservation</u></a></li>
<li><a href="https://win11.techidaily.com/enliven-windows-11-desktop-a-step-by-step-guide-to-animated-walls/"><u>Enliven Windows 11 Desktop: A Step-by-Step Guide to Animated Walls</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-capture-the-thrill-mastering-4-techniques-of-xbox-screen-recording/"><u>[Updated] 2024 Approved  Capture the Thrill  Mastering 4 Techniques of Xbox Screen-Recording</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/ace-your-online-presence-youtubes-studio-command-center/"><u>Ace Your Online Presence  YouTube's Studio Command Center</u></a></li>
<li><a href="https://fox-http.techidaily.com/innovative-methods-to-subtly-soften-audible-output-via-lumafusion-for-2024/"><u>Innovative Methods to Subtly Soften Audible Output via Lumafusion for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-vivo-s17-pro-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Vivo S17 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-steps-to-initiate-system-restore-on-windows-11/"><u>Decoding the Steps to Initiate System Restore on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-system-sounds-in-windows-11-by-activating-mixer-feature/"><u>Perfect System Sounds in Windows 11 by Activating Mixer Feature</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-strategies-for-pinpointing-hardware-identification-in-windows/"><u>Advanced Strategies for Pinpointing Hardware Identification in Windows</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/mobile-mastery-in-saving-team-video-gatherings/"><u>Mobile Mastery in Saving Team Video Gatherings</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-unfading-flight-ambitions-top-10-longevity-drone-lists/"><u>[Updated] 2024 Approved  Unfading Flight Ambitions  Top 10 Longevity Drone Lists</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-the-complete-handbook-to-adding-auditory-elements-to-ae-projects-revised/"><u>Updated In 2024, The Complete Handbook to Adding Auditory Elements to AE Projects, Revised</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-ai-assistance-in-development-an-introduction-to-microsoft-copilot/"><u>Leveraging AI Assistance in Development: An Introduction to Microsoft Copilot</u></a></li>
<li><a href="https://win11.techidaily.com/top-benefits-of-windows-11-overtaking-macos/"><u>Top Benefits of Windows 11 Overtaking macOS</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-perfect-pacing-with-macos-a-specialists-guide-to-srt-editing/"><u>2024 Approved  Perfect Pacing with macOS  A Specialist's Guide to SRT Editing</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-instant-access-to-hd-facebook-feeds-for-2024/"><u>[Updated] Instant Access to HD Facebook Feeds for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-initial-steps-to-instagram-video-discussion-success/"><u>[Updated] 2024 Approved  Initial Steps to Instagram Video Discussion Success</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-gpu-memory-potential-in-windows-11-os/"><u>Maximizing GPU Memory Potential in Windows 11 OS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-fast-forwarding-instagram-videos-efficiently/"><u>2024 Approved  Fast-Forwarding Instagram Videos Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-disk-management-virtual-disk-hiccups/"><u>Rectifying Disk Management Virtual Disk Hiccups</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-users-with-precision-four-easy-techniques-on-win11/"><u>Disabling Users with Precision: Four Easy Techniques on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-window-11-dual-screen-usage/"><u>Perfecting Window 11 Dual Screen Usage</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-notes-obsidian-canvas-approach/"><u>Streamline Your Notes: Obsidian Canvas Approach</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-to-resolve-battlenet-login-on-pcs/"><u>Troubleshooting Steps to Resolve Battle.net Login on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inactive-voice-over-on-microsofts-document-reader/"><u>Fixing Inactive Voice-Over on Microsoft's Document Reader</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-nokia-g22-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Nokia G22 | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-sonically-superior-best-replacements-for-audacity-on-cross-platform-operating-systems/"><u>In 2024, Sonically Superior Best Replacements for Audacity on Cross-Platform Operating Systems</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/how-to-live-stream-to-facebook-from-dji-drone-for-2024/"><u>How to Live Stream to Facebook From DJI Drone for 2024</u></a></li>
<li><a href="https://printer-issues.techidaily.com/successful-installation-of-multi-function-printer/"><u>Successful Installation of Multi-Function Printer</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-common-isdonedll-isarcextract-failures/"><u>Overcoming Common ISDone.dll (ISArcExtract) Failures</u></a></li>
<li><a href="https://win11.techidaily.com/forecasting-with-finesse-windows-11s-prime-weather-tools/"><u>Forecasting with Finesse: Windows 11'S Prime Weather Tools</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-windows-a-start-free-of-ads/"><u>Streamlined Windows: A Start Free of Ads</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-characters-on-windows-11-screen/"><u>Navigating the Characters on Windows 11 Screen</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-voice-creation-made-easy-online-9-free-generators-to-convert-text/"><u>New In 2024, Voice Creation Made Easy Online 9 Free Generators to Convert Text!</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Samsung Galaxy F54 5G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/lock-your-realme-narzo-n55-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Realme Narzo N55 Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-guiding-iphone-and-android-owners-to-fix-video-sending-problems-in-fb-chat/"><u>[Updated] In 2024, Guiding iPhone & Android Owners to Fix Video Sending Problems in FB Chat</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/device-unlock-motorola-moto-g73-5g-by-drfone-android-unlock-android-unlock/"><u>Device unlock  Motorola Moto G73 5G</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-8-ways-to-transfer-photos-from-realme-narzo-60x-5g-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 8 Ways to Transfer Photos from Realme Narzo 60x 5G to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-win-lol-initial-load-issue/"><u>Resolving Win: LOL Initial Load Issue</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-dissective-review-of-sharex-criticism-and-substitutes/"><u>In 2024, Dissective Review of ShareX  Criticism & Substitutes</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-the-heart-of-windows-print-controls/"><u>Accessing the Heart of Windows Print Controls</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-the-ultimate-guide-to-auditory-clarity-prime-apps-for-removing-unwanted-sounds/"><u>New 2024 Approved The Ultimate Guide to Auditory Clarity Prime Apps for Removing Unwanted Sounds</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-friendship-in-folded-space-top-vr-games/"><u>2024 Approved  Friendship in Folded Space  Top VR Games</u></a></li>
<li><a href="https://win11.techidaily.com/winx-troubleshooting-correcting-nvidias-retrieval-errors/"><u>WinX Troubleshooting: Correcting NVIDIA's Retrieval Errors</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-win11-dns-client-service-adjustment/"><u>Essential Tips for Win11 DNS Client Service Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-default-heat-reduction-rules-in-winos/"><u>Reclaiming Default Heat Reduction Rules in WinOS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/optimizing-video-posts-with-flawless-srt-file-integration-tactics/"><u>Optimizing Video Posts with Flawless SRT File Integration Tactics</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-oppo-reno-9a-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-vivo-v27-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Vivo V27 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11.techidaily.com/method-to-reset-windows-11-search-bar-aesthetics/"><u>Method to Reset Windows 11 Search Bar Aesthetics</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-remove-passcode-from-apple-iphone-se-2022-complete-guide-by-drfone-ios/"><u>In 2024, How To Remove Passcode From Apple iPhone SE (2022)? Complete Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ranked-highest-audio-transformation-tools-including-magic-for-2024/"><u>Ranked Highest Audio Transformation Tools, Including Magic for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/handling-virtualbox-usb-disconnect-issues-effectively-on-windows/"><u>Handling VirtualBox USB Disconnect Issues Effectively on Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-step-by-step-guide-to-crafting-iphone-image-art/"><u>2024 Approved  Step-by-Step Guide to Crafting iPhone Image Art</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-systemsettings-crashes-in-windows-11/"><u>Overcoming SystemSettings Crashes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-gaps-in-window-systems-reliability-vs-performance/"><u>Bridging Gaps in Window Systems: Reliability Vs. Performance</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-0x800713f-issue-for-smooth-function-of-win11s-mail-app/"><u>Decoding 0X800713F Issue for Smooth Function of Win11's Mail App</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-edges-load-times-and-resource-use/"><u>Decreasing Edge's Load Times and Resource Use</u></a></li>
<li><a href="https://win11.techidaily.com/quick-steps-for-mending-windows-hello-fingerprint-issues/"><u>Quick Steps for Mending Windows Hello Fingerprint Issues</u></a></li>
</ul></div>
