---
title: "No Plug, Just Play: Connect DualShock 3 to PC"
date: 2024-07-13T11:00:22.732Z
updated: 2024-07-14T11:00:22.732Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes No Plug, Just Play: Connect DualShock 3 to PC"
excerpt: "This Article Describes No Plug, Just Play: Connect DualShock 3 to PC"
keywords: DualShock PS3,PS3 Controller,DualShock PC,PS3 Portable,No Plug Play,Direct USB Link,Console Connect
thumbnail: https://thmb.techidaily.com/03446fa7c6c4437cc78cf994a5cd500e9e19b7398656e9b5a14acb95e0d9c21d.jpg
---

## No Plug, Just Play: Connect DualShock 3 to PC

 Your PS3 is probably gathering dust by now, so why not put it to good use... or, at least, its controllers? Use them on your PC and give them a new life.

 Although it was possible to use PS3 joypads on PCs in the past, the process was finicky, and their wireless functionality was wonky. That was until DsHidMini entered the scene. Here's how you can use a PS3 DualShock controller on your PC, both through a USB connection and wirelessly through Bluetooth

## What Is DsHidMini?

 DsHidMini is an open-source solution for connecting and configuring many types of joypads to a PC. As such, if you have your old PS3 or PS4 DualShock controllers around, why not put them to use with this app?

 DsHidMini enables your PC to recognize them and provides XInput emulation. With Xinput being the modern standard for joypads under Windows, you'll be able to use your PlayStation controller with most modern games.

## Getting the Necessary Software for Using Your PS3 Controller on a PC

 By combining two pieces of software, DsHidMini, and BthPS3, you can have your PC detect your DualShock controller effortlessly both when connected with a USB cable and wirelessly through Bluetooth.

 Note, though, that for this guide, we take the existence of correctly working Bluetooth functionality for granted. If your PC lacks Bluetooth support, check our buyer's guide on [the best Bluetooth adapters you can grab today](https://www.makeuseof.com/best-bluetooth-adapters/) . Then, check our guide on [how to add Bluetooth to any computer](https://www.makeuseof.com/add-bluetooth-pc/) .

### Download and Install DsHidMini and BthPS3

 DsHidMini suggests installing BthPS3 to have your DualShock controllers correctly detected and connected to your PC. This guide will follow that suggestion, especially since we want them to work wirelessly.

1. Start by downloading the first piece of software from [DsHidMini's GitHub page](https://github.com/ViGEm/DsHidMini) .  
![DsHidMini GitHub Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-github-page.jpg)
2. Do the same with a visit at [BthPS3's GitHub page](https://github.com/ViGEm/BthPS3) .  
![BthPS3 GitHub Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-github-page.jpg)
3. In both cases, you'll find the downloadable files by clicking on the link under**Installation** , then checking out the links under**Assets** . Most people should go for the x64 versions. If you're still using an older 32-bit version of Windows, get the x86 files.  
![BthPS3 GitHub Assets Links](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-github-assets-links.jpg)
4. Click on**BthPS3's MSI file** that you've downloaded to install the Bluetooth driver. "MSI" stands for Microsoft Software Installer. Unlike executable installers, MSI relies on the "official" installation libraries bundled with Windows. If you meet any problems during that step, check our guide on [how to fix issues with the Windows Installer package](https://www.makeuseof.com/windows-installer-package-fix-issues/) .  
![BthPS3 Installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-installation.jpg)
5. After BthPS3's successful installation, you'll see it as a new device under the**Bluetooth** category in**Device Manager** . The easiest way to access the Device Manager is by using the**Windows Key** +**X** shortcut and selecting it from the menu that shows up.  
![BthPS3 Installed Bluetooth Driver in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-installed-bluetooth-driver-in-device-manager.jpg)
6. DsHidMini's installation is a tad more complicated since it comes in a compressed archive. Open**Windows File Explorer** , and pay a visit to the folder where you saved DsHidMini's downloaded archive. All modern versions of Windows support the ZIP archive format, so you can right-click on the file and choose**Extract** . However, we used WinRAR instead simply because we had it installed, and it's somewhat faster. In both cases, the result is the same.  
![Extracting DsHidMini Archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/extracting-dshidmini-archive.jpg)
7. Look inside the extracted archive's folder, and you'll see two more folders:**x64** and**x86** . Enter the one matching your Windows architecture. As mentioned above, most people nowadays should go for**x64** .  
![DsHidMini Extracted Archive Contents](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-extracted-archive-contents.jpg)
8. Inside that folder, you'll find another subfolder named**dshidmini** . Enter that one, too.  
![DsHidMini Extracted Archive Contents x64](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-extracted-archive-contents-x64.jpg)
9. Right-click on the**dshidmini.inf** file, and choose**Install** from the menu that shows up. When that step completes, install the**igfilter.inf** the same way.  
![DsHidMini Extracted Archive Contents x64 dshidmini inf install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-extracted-archive-contents-x64-dshidmini-inf-install.jpg)

 Theoretically, that's everything you need for your DualShock to work with your PC. Practically, as is Windows' tradition, it wouldn't hurt to restart once to ensure the drivers are correctly installed, activated, and work as they should.

## How to Pair and Configure Your PS3 DualShock

 The next step is to "pair" your controller with your PC. However, that process is somewhat unconventional compared to how you usually connect Bluetooth devices to your PC.

1. Connect your DualShock joypad to your PC using a mini-USB cable. Your joypad should begin charging.
2. Pay a visit to the folder with DsHidMini's extracted files. Double-click on the**DSHMC.exe** to run it.  
![DSHMC.exe File In File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-exe-file-in-file-explorer.jpg)
3. You should see your "PlayStation controller" detected on the left side of the app's window. Now, if you run Steam with its outstanding controller support, it should detect and configure your joypad for use in modern games. As for wireless? Unplug the cable, and your joypad should keep working as if nothing happened.  
![DSHMC.exe Controller Detected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-exe-controller-detected.jpg)
4. DsHidMini will have your controller recognized as an**XInput** device by default to maximize compatibility with modern software. But what if you want to use it on an older title that uses the older**DirectInput** standard or to have emulators like PPSSPP, PCSX2, and RPCS3 recognize it as an actual PlayStation controller? Close DSHMC.exe, then right-click on it and re-run it, but this time choose**Run as Administrator** . When its window shows up again, click on your controller on the left, and you'll see more details about it on the right and some options you can tweak.  
![DSHMC Configuration As Admin](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-configuration-as-admin.jpg)
5. You can change the HID device mode from**XInput** to another mode compatible with the software where you want to use your controller. You can also tweak its**Idle disconnect** period or define after how much time of inactivity the controller should disconnect and turn off.  
![DSHMC Change HID Mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshmc-exe-change-hid-mode.jpg)

## How to Remove Remnants of Old Drivers

 If your joypad isn't correctly detected, did you use another solution in the past to have it work under Windows, like Sony's official driver or ScpToolkit? If yes, the problem might be a conflict between those and the DsHidMini and BthPS3 combo.

 Removing the older drivers and software is somewhat complicated. Plus, the process varies based on the driver and software used. So, we won't go over it in detail but offer a "generic guide" covering the basic steps for most cases.

 Run the**Command Prompt** or**PowerShell** with Administrative rights. Then, use the commands, in sequence, if you were using ScpToolkit:

`taskkill /F /IM ScpServer.exe  
taskkill /F /IM ScpMonitor.exe  
taskkill /F /IM ScpTrayApp.exe  
sc stop Ds3Service  
sc delete Ds3Service`

 These will stop and remove all active processes and services for PlayStation joypad-enabling software you might have used in the past.

 Now, press**Win** +**X** and choose**Device Manager** . Find and remove any mention of a "PlayStation controller" under**Human Interface Devices** if you were using the official Sony drivers.

 For ScpToolkit, look under**libusbK USB Devices** instead, and right-click and**Uninstall** any entry you see. Also, check for and, if found, uninstall the drivers for any "Bluetooth Dongle", "DualShock controller", or "PlayStation controller" under**Universal Serial Bus devices** .

 Then, download [DriverStore Explorer from its GitHub page](https://github.com/lostindark/DriverStoreExplorer/releases/tag/v0.11.79) . Extract its archive and run the app. Enable**Force Deletion** on the right. Seek any**libusbK USB Devices** , a standalone**scpvbus.inf** , or**bluetoothhost.inf** and**ds3controller.inf** if using ScpToolkit.

 Look for**sixaxis.inf** instead if using the official Sony driver. In both cases, place a checkmark next to any of those entries you'll find, and then click on**Delete Drivers** on the right.

 Afterward, exit the app, restart your PC, and let Windows re-detect any hardware and install the default drivers. Then, repeat the steps we covered above to install BthPS3 and DsHidMini from scratch.

## How to Use Your PS3 DualShock in Games

 Your controller should work now in most modern games that support Xbox joypads and for most joypad-enabled titles running under Steam.

 When that's not the case, run DSHMC.exe as an administrator and change the HID mode used by your joypad to the one supported by the game or app where you want to use it.

 An easy way to find the HID mode to choose for a particular title is to check if there's information about it at [PCGamingWiki](https://www.pcgamingwiki.com/wiki/Main%5FPage) .

## Using Classic PS3 Joypads on Your Modern-Day Games for Windows

 Reusing your older joypads on your PC is the smartest choice. Apart from the fact you won't have to pay a dime to do it, they're great performers, tried and tested, and you're already familiar with them.

 Worst case scenario, you might have to buy a Bluetooth dongle for your PC, which would still come at a fraction of the cost of a brand-new controller.


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
<li><a href="https://screen-mirror.techidaily.com/how-can-i-screen-mirroring-apple-iphone-xs-to-tvlaptop-drfone-by-drfone-ios/"><u>How Can I Screen Mirroring Apple iPhone XS to TV/Laptop? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/protecting-your-privacy-how-to-remove-apple-id-from-apple-iphone-x-by-drfone-ios/"><u>Protecting Your Privacy How To Remove Apple ID From Apple iPhone X</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-to-unlock-your-windows-pin/"><u>Efficient Methods to Unlock Your Windows PIN</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-breakthrough-turned-breach-windows-hellos-future/"><u>Biometric Breakthrough Turned Breach: Windows Hello's Future?</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-resolving-installation-hurdles-in-windows-1011/"><u>Understanding & Resolving Installation Hurdles in Windows 10/11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Poco M6 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-elite-discord-capture-apps-on-the-go-recording-made-easy-for-2024/"><u>[New] Elite Discord Capture Apps  On-the-Go Recording Made Easy for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-the-aspiring-asmr-producers-guide-to-video-excellence/"><u>[Updated] The Aspiring ASMR Producer's Guide to Video Excellence</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-fine-tuning-frequency-flux-innovative-approaches-to-minimize-noise-in-audacity/"><u>In 2024, Fine-Tuning Frequency Flux Innovative Approaches to Minimize Noise in Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-internal-audio-faults-in-audacity-wos-edition/"><u>Dissecting Internal Audio Faults in Audacity, WOS Edition</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-on-photo-corrections-stripping-backdrops/"><u>Expert Advice on Photo Corrections: Stripping Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/charting-a-course-for-change-windows-11-explore-evolution/"><u>Charting a Course for Change: Windows 11 Explore Evolution</u></a></li>
<li><a href="https://win11.techidaily.com/removing-intrusive-edge-toolbar-items/"><u>Removing Intrusive Edge Toolbar Items</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-chrome-download-errors-on-windows-systems/"><u>Fixing Chrome Download Errors on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-and-solving-roblox-errors-tied-to-account-restrictions/"><u>Unveiling and Solving Roblox Errors Tied to Account Restrictions</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-leveraging-likes-and-comments-enhancing-engagement-on-instagram-stories/"><u>In 2024, Leveraging Likes and Comments  Enhancing Engagement on Instagram Stories</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-pairings-winning-webp-viewers-and-windows-devices/"><u>Top 4 Pairings: Winning WebP Viewers & Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-check-your-public-ip-address-using-command-prompt-in-windows-1110/"><u>How to Check Your Public IP Address Using Command Prompt in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/ace-at-tech-how-to-revitalize-your-pcs-apps/"><u>Ace at Tech: How to Revitalize Your PC's Apps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-xpatch-fixes-for-error-0x80073712/"><u>Mastering Windows XPatch Fixes for Error 0X80073712</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-detecting-changes-in-your-instagram-network/"><u>[New] Detecting Changes in Your Instagram Network</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-oppo-reno-10-pro-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Oppo Reno 10 Pro 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tactical-steps-to-evade-windows-account-prompts/"><u>Tactical Steps to Evade Windows Account Prompts</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/the-best-free-video-editing-tools-for-avi-format-for-2024/"><u>The Best Free Video Editing Tools for AVI Format for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-1011-installer-errors/"><u>Navigating Through Windows 10/11 Installer Errors</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-capture-and-record-a-new-era-of-iphoneipad-recording/"><u>[New] In 2024, Capture & Record  A New Era of iPhone/iPad Recording</u></a></li>
<li><a href="https://win11.techidaily.com/booting-into-safety-6-ways-to-enter-windows-11s-safe-mode/"><u>Booting Into Safety: 6 Ways to Enter Windows 11'S Safe Mode</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/make-your-content-stand-out-with-instagrams-procedural-slow-mo-journey/"><u>Make Your Content Stand Out with Instagram’s Procedural Slow Mo Journey</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-microsofts-zero-error-in-windows-11-shop/"><u>Rectifying Microsoft's Zero-Error in Windows 11 Shop</u></a></li>
<li><a href="https://games-able.techidaily.com/twitch-decoded-a-comprehensive-overview-of-live-broadcasts/"><u>Twitch Decoded: A Comprehensive Overview of Live Broadcasts</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-code-0x80246007-from-windows-update-on-w10w11/"><u>Eliminating Error Code 0X80246007 From Windows Update on W10/W11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-the-entrepreneurs-must-haves-essential-items-for-kickstarting-success/"><u>[Updated] 2024 Approved  The Entrepreneur's Must-Haves  Essential Items for Kickstarting Success</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-accelerated-steps-to-unsettle-youtube-playlists/"><u>[Updated] 2024 Approved  Accelerated Steps to Unsettle YouTube Playlists</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-esd-and-its-transformation-into-iso-format-for-pcs/"><u>Understanding ESD and Its Transformation Into ISO Format for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-finding-fixes-for-systemsettingsexe-in-win11/"><u>Tips for Finding Fixes for SystemSettings.exe in Win11</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-newcomers-notebook-navigating-through-pixel-perfect-videos/"><u>The Newcomer’s Notebook  Navigating Through Pixel-Perfect Videos</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-era-of-taskbars-proposing-key-improvements-to-microsofts-design/"><u>A New Era of Taskbars: Proposing Key Improvements to Microsoft's Design</u></a></li>
<li><a href="https://win11.techidaily.com/traversing-through-system-failsafe-files-after-blue-screen/"><u>Traversing Through System Failsafe Files After Blue Screen</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-tales-for-twilight-film-analysis/"><u>[Updated] Tales for Twilight  Film Analysis</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/cold-games-2022s-ultimate-snowboard-dueling-display/"><u>Cold Games  2022'S Ultimate Snowboard Dueling Display</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-essential-elements-missing-windows-error/"><u>Overcoming 'Essential Elements Missing' Windows Error</u></a></li>
<li><a href="https://win11.techidaily.com/regain-missing-windows-storage-access/"><u>Regain Missing Windows Storage Access</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-vivo-y100a-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Vivo Y100A? Fixed | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/elite-8-blu-ray-player-rankings-for-4k-quality/"><u>Elite 8 Blu-Ray Player Rankings for 4K Quality</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-connect-your-content-from-twitch-to-facebook/"><u>[Updated] In 2024, Connect Your Content  From Twitch to Facebook</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Xiaomi Redmi Note 12T Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reactivate-deactivated-menu-items-on-windows/"><u>Steps to Reactivate Deactivated Menu Items on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/minimalist-pc-large-space-slight-lag/"><u>Minimalist PC - Large Space, Slight Lag</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-performance-and-functionality-with-alomwares-tools/"><u>Optimize Performance & Functionality with AlomWare's Tools</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-try-connecting-error-on-windows-11-devices/"><u>Conquering Try Connecting Error on Windows 11 Devices</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-oppo-reno-10-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
</ul></div>
