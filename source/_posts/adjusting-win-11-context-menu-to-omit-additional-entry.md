---
title: Adjusting Win 11 Context Menu to Omit Additional Entry
date: 2024-07-13T11:25:22.945Z
updated: 2024-07-14T11:25:22.945Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Win 11 Context Menu to Omit Additional Entry
excerpt: This Article Describes Adjusting Win 11 Context Menu to Omit Additional Entry
keywords: Win 11 Context Menu Edit,Omitting Menu Entry in Win 11,Removing Win 11 Add-Ons,Editing Windows Menu Options,Customizing Win 11 UI,Adjusting Context Menu Items,Streamlining Win 11 Interface
thumbnail: https://thmb.techidaily.com/a68fefb1cd3e565ec5f454a0d5028d3000ec7ede8d478967f77735423a6ab539.jpg
---

## Adjusting Win 11 Context Menu to Omit Additional Entry

 Windows 11 comes with a fresh new look and has mainly got a positive response for its new interface. However, there are a couple of features that are not being welcomed by the users. For instance, the addition of the "show more options" entry to the right-click context menu.

 Although it was introduced to simplify things, many users still prefer the old context menu from Windows 10\. Fortunately, you can remove Show more options from the context menu on Windows 11 by following the below methods.

## 1\. How to Remove "Show More Options" From the Context Menu With Folder Options

 The [Windows Folder Options](https://www.makeuseof.com/windows-folder-options-guide/) in File Explorer is the go-to place to view and manage File Explorer settings. You can use it to [enable compact view in File Explorer on Windows 11](https://www.makeuseof.com/how-to-enable-compact-view-windows-11-file-explorer/) , manage file thumbnails, remove the "show more options" entry, and much more.

 Here's how to use the folder option to remove the "show more options" entry from the context menu:

1. Press the**Win + E** hotkey to open the**File Explorer.**
2. Click the three horizontal dots at the top bar and choose**Options.**
3. In the**Folder Options,** switch to the**View** tab.
4. Check the**Launch folder** **windows in a separate process** box.  
![Launch folder windows in a separate process box in the Folder option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/launch-folder-windows-in-a-separate-process-box.jpg)
5. Click**Apply** \>**OK** to save the changes.

Next, restart your computer for the changes to take effect.

## 2\. Remove Show More Options From the Context Menu Using the Command Prompt

 If you're a power user, you can use Command Prompt to remove the "show more options" entry from the context menu. Here's how:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. Click**Yes** to the UAC that crops up.
4. In the elevated Command Prompt window, type the following command and press**Enter** :  
`reg add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve`

![Command to Remove Context menu in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-to-remove-context-menu.jpg)

 After executing the command, you'll see the "The operation completed successfully" message to confirm that it went through.

 Now, you will have to restart Windows Explorer to see the changes. To do that, open the**Task Manager** (see how to [launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) ), right-click on**Windows Explorer,** and choose**Restart.**

 Check if you can see the changes. If not, then you will have to restart your computer for the changes to take effect.

 In the future, if you want to add the "show more options" entry to the context menu, then open Command Prompt with admin rights and run the following command:

`reg delete "HKEY_CURRENT_USER\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}" /f​`

## 3\. Remove Show More Options From the Context Menu Using the Registry Editor

 Another quick way to remove the "show more options" entry is through the Registry Editor. Here's what you need to do:

 Before making any changes to the registry, ensure you've [created a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) or [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will ensure your system settings and files are secure, and you can quickly access them if something goes wrong.

1. Open the Start Menu, type**Registry Editor** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_CURRENT_USER\Software\Classes\CLSID`
3. Right-click on the empty space on the right pane, click**New,** and then select**DWORD** **(32-bit) Value** from the context menu.
4. Name the value as**"UndockingDisabled"** and press**Enter** .  
![UndockingDisabled entry in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/undockingdisabled-entry.jpg)
5. Double-click on the UndockingDisabled key, type**1** in the**Value data,** and click**OK** to save the changes.  
![Editing UndockingDisabled in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/editing-undockingdisabled.jpg)

## 4\. Remove the "Show More Options" Entry From the Context Menu Using Winaero Tweaker

 There are plenty of third-party tools using which you can customize the look of your Windows 11 computer. For this guide, we will use Winaero Tweaker.

 Here's how to download Winaero Tweaker and use it to remove the "show more options" entry from the context menu:

1. Download the [Winaero Tweaker zip file](https://winaero.com/downloads/winaerotweaker.zip) on your computer.
2. Unzip the file, open the executable, and then follow the on-screen instructions to install it on your computer.
3. Launch Winaero Tweaker and choose the**Classic Full Context Menus** option from the left sidebar.  
![Classic Full Context Menus option of Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/classic-full-context-menus-option.jpg)
4. Check the**Enable classic full context menus** box.  
![Enable classic full context menus option in Winaero](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-classic-full-context-menus.jpg)
5. Click the**Restart Explorer** button that appears.

## Enjoy an Old School Context Menu on Windows 11

 The desktop context menu lets you quickly access areas like the personalization menu, display settings, and much more. In Windows 11, you get the new "Show more options" entry in the context menu. But if you prefer the old design, you can quickly disable the "Show more options" entry from the context using either of the above methods.


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
<li><a href="https://win11.techidaily.com/awaken-clandestine-windows-11-search-sentinel/"><u>Awaken Clandestine Windows 11 Search Sentinel</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-devices-performance-with-quick-android-apk-installation-in-windows-11/"><u>Boost Your Device's Performance with Quick Android APK Installation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-error-x80072f30-in-microsoft-store-on-windows/"><u>Breaking Down Error X80072F30 in Microsoft Store on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bask-in-the-best-of-microsofts-winstore-treasures/"><u>Bask in the Best of Microsoft’s WinStore Treasures</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-limits-why-16gb-ram-is-key-for-modern-pcs/"><u>Beyond Limits: Why 16GB RAM Is Key for Modern PCs</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-comparative-study-vidma-vs-standard-screen-recording/"><u>[Updated] In 2024, Comparative Study  Vidma vs Standard Screen Recording</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-night-owls-techniques-for-long-exposure-iphone-pics/"><u>2024 Approved  Night Owls' Techniques for Long-Exposure iPhone Pics</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-spotifys-default-auto-play-on-windows/"><u>Avoid Spotify's Default Auto-Play on Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-ideal-ps2-emulation-software-for-ios-users/"><u>In 2024, Ideal PS2 Emulation Software for IOS Users</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-xiaomi-redmi-12-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Xiaomi Redmi 12 Pattern Lock Screen</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-gmail-password-on-honor-v-purse-devices-by-drfone-android/"><u>How to Reset Gmail Password on Honor V Purse Devices</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-defaults-20-ways-to-personalize-windows-11/"><u>Beyond Defaults: 20 Ways to Personalize Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-direct-linking-spotifys-journey-into-discord-for-2024/"><u>[Updated] Direct Linking  Spotify's Journey Into Discord for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-microsoft-store-hiccup-error-0x00000000-solution/"><u>Avoiding Microsoft Store Hiccup: Error 0X00000000 Solution</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Tecno Spark 20 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-your-virtual-space-windows-11-home/"><u>Accessing Your Virtual Space: Windows 11 Home</u></a></li>
<li><a href="https://extra-tips.techidaily.com/novices-compendium-understanding-pixel-perfection/"><u>Novice's Compendium  Understanding Pixel Perfection</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-system-tray-displaying-cpu-and-memory-usage/"><u>Boosting System Tray: Displaying CPU & Memory Usage</u></a></li>
<li><a href="https://win11.techidaily.com/action-plan-if-powershell-isnt-displayed-by-windows/"><u>Action Plan if PowerShell Isn’t Displayed by Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-wake-up-alerts-win-1011-full-charge-ding/"><u>Boosting Wake-Up Alerts: Win 10/11 FULL CHARGE DING</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-how-regular-are-youtube-monetization-payments/"><u>[Updated] How Regular Are YouTube Monetization Payments?</u></a></li>
<li><a href="https://win11.techidaily.com/blending-elegance-with-utility-the-asus-vivobook-s-15-edition/"><u>Blending Elegance with Utility: The ASUS Vivobook S 15 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/administrative-evolution-reimagining-control-in-a-windows-world/"><u>Administrative Evolution: Reimagining Control in a Windows World</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-tecno-spark-10-pro-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Tecno Spark 10 Pro to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/banish-already-in-use-errors-and-unique-device-naming/"><u>Banish 'Already in Use' Errors and Unique Device Naming</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-precision-in-prose-enhancing-narrative-scripts/"><u>[Updated] Precision in Prose  Enhancing Narrative Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-the-basics-windows-11s-hidden-treasures-revealed/"><u>Beyond the Basics: Windows 11'S Hidden Treasures Revealed</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-free-avi-video-rotators-compared-top-5-choices/"><u>New 2024 Approved Free AVI Video Rotators Compared Top 5 Choices</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-7-ways-to-lock-apps-on-apple-iphone-15-pro-and-ipad-securely-by-drfone-ios/"><u>In 2024, 7 Ways to Lock Apps on Apple iPhone 15 Pro and iPad Securely</u></a></li>
<li><a href="https://win11.techidaily.com/atlasos-resurgence-guide-for-older-tech/"><u>AtlasOS Resurgence Guide for Older Tech</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-user-management-via-windows-terminal/"><u>Advanced User Management via Windows Terminal</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-how-to-fix-plugins-not-working-in-final-cut-pro-x-for-2024/"><u>Updated How to Fix Plugins Not Working in Final Cut Pro X for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-flawless-youtube-viewing-on-chrome-windows/"><u>Achieving Flawless YouTube Viewing on Chrome, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boost-chat-speed-enable-bing-ai-in-windows-11-menu-bar/"><u>Boost Chat Speed: Enable Bing AI in Windows 11 Menu Bar</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-from-video-to-mp3-a-step-by-step-guide-to-preserving-audio-fidelity/"><u>2024 Approved From Video to MP3 A Step-by-Step Guide to Preserving Audio Fidelity</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-windows-notepad-system-disruptions/"><u>Avoiding Windows Notepad System Disruptions</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-motorola-has-native-mov-support-by-aiseesoft-video-converter-play-mov-on-android/"><u>Does Motorola has native MOV support?</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-catalog-of-mp3-sources-featuring-feline-noises/"><u>Updated In 2024, Catalog of MP3 Sources Featuring Feline Noises</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/stardews-ultimate-game-changing-mods-a-curated-list-for-2024/"><u>Stardew's Ultimate Game-Changing Mods  A Curated List for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-application-launch-descriptors/"><u>Breaking Down Application Launch Descriptors</u></a></li>
<li><a href="https://win11.techidaily.com/best-vmms-aligned-with-windows-11-system-requirements/"><u>Best VMMs Aligned with Windows 11 System Requirements</u></a></li>
<li><a href="https://win11.techidaily.com/battle-the-bake-off-effective-tactics-to-reduce-gaming-laptops-temperature/"><u>Battle the Bake-Off: Effective Tactics to Reduce Gaming Laptop’s Temperature</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/a-guide-asus-rog-phone-7-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>A Guide Asus ROG Phone 7 Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-capture-the-essence-extracting-youtube-audio-directly/"><u>[Updated] In 2024, Capture the Essence  Extracting YouTube Audio Directly</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-microsoft-paint-in-windows-11/"><u>Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-customized-windows-cmd/"><u>Boosting Productivity with Customized Windows Cmd</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-cursor-signal-strength-in-win-11-os/"><u>Boosting Cursor Signal Strength in Win 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/bitshield-busted-but-wait-a-beat-before-switch/"><u>BitShield Busted, But Wait a Beat Before Switch</u></a></li>
<li><a href="https://win11.techidaily.com/boost-performance-using-ntfs-file-compression-wisely/"><u>Boost Performance: Using NTFS File Compression Wisely</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Apple iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/activating-prints-with-microsofts-shielded-browsing/"><u>Activating Prints with Microsoft's Shielded Browsing</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/fb-videos-to-audible-pleasures-online-mp3-creation-secrets/"><u>FB Videos to Audible Pleasures  Online MP3 Creation Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-configuration-backup-by-nvidia-cp/"><u>Addressing Missing Configuration Backup by Nvidia CP</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-self-shutting-windows-11-units/"><u>Addressing Self-Shutting Windows 11 Units</u></a></li>
<li><a href="https://win11.techidaily.com/boost-efficiency-navigating-windows-11s-disk-management-quickly/"><u>Boost Efficiency: Navigating Windows 11'S Disk Management Quickly</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-complete-kinetic-review-2023/"><u>[New] Complete Kinetic Review 2023</u></a></li>
<li><a href="https://win11.techidaily.com/adjust-your-user-profiles-home-path-on-win11-os/"><u>Adjust Your User Profiles' Home Path on Win11 OS</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-mastering-the-art-of-tiktok-emojis-a-comprehensive-guide-for-2024/"><u>[Updated] Mastering the Art of TikTok Emojis  A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-lags-7-solutions-to-boost-windows-keyboard-speed/"><u>Banishing Lags: 7 Solutions to Boost Window's Keyboard Speed</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-multiple-zip-archives-in-one-go/"><u>Boosting Productivity with Multiple ZIP Archives in One Go</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-revolutionize-iphone-images-turn-them-sideways-and-upside-down/"><u>[New] In 2024, Revolutionize iPhone Images  Turn Them Sideways & Upside Down</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/brief-basslines-and-rhythms-video-soundscapes-for-2024/"><u>Brief Basslines & Rhythms  Video Soundscapes for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-itel-s23plus-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Itel S23+ For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-maximizing-your-fb-page-visibility-a-step-by-step-guide/"><u>[Updated] 2024 Approved  Maximizing Your FB Page Visibility  A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-add-software-icons-to-windows-desktop/"><u>Boost Productivity: Add Software Icons to Windows Desktop</u></a></li>
</ul></div>
