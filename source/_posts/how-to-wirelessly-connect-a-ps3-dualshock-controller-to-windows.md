---
title: How to Wirelessly Connect a PS3 DualShock Controller to Windows
date: 2025-01-02T18:01:33.672Z
updated: 2025-01-06T16:52:52.073Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Wirelessly Connect a PS3 DualShock Controller to Windows
excerpt: This Article Describes How to Wirelessly Connect a PS3 DualShock Controller to Windows
keywords: PS3 Controller Wi-Fi Tips,DualShock Ps3 Wireless PC,PS3 Controller for Windows,Bluetooth PS3 DualShock,Connecting PS3 Controllers,PS3 Gamepad Windows Guide,PS3 Remote Play Setup
thumbnail: https://thmb.techidaily.com/ddfdfc8e69381106d1b66c2809b663a8f7e41d96d0a4215acf2250fc3083c5a7.jpg
---

## How to Wirelessly Connect a PS3 DualShock Controller to Windows

 Your PS3 is probably gathering dust by now, so why not put it to good use... or, at least, its controllers? Use them on your PC and give them a new life.

 Although it was possible to use PS3 joypads on PCs in the past, the process was finicky, and their wireless functionality was wonky. That was until DsHidMini entered the scene. Here's how you can use a PS3 DualShock controller on your PC, both through a USB connection and wirelessly through Bluetooth

## What Is DsHidMini?

 DsHidMini is an open-source solution for connecting and configuring many types of joypads to a PC. As such, if you have your old PS3 or PS4 DualShock controllers around, why not put them to use with this app?

 DsHidMini enables your PC to recognize them and provides XInput emulation. With Xinput being the modern standard for joypads under Windows, you'll be able to use your PlayStation controller with most modern games.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Getting the Necessary Software for Using Your PS3 Controller on a PC

 By combining two pieces of software, DsHidMini, and BthPS3, you can have your PC detect your DualShock controller effortlessly both when connected with a USB cable and wirelessly through Bluetooth.

 Note, though, that for this guide, we take the existence of correctly working Bluetooth functionality for granted. If your PC lacks Bluetooth support, check our buyer's guide on[the best Bluetooth adapters you can grab today](https://www.makeuseof.com/best-bluetooth-adapters/) . Then, check our guide on[how to add Bluetooth to any computer](https://www.makeuseof.com/add-bluetooth-pc/) .

### Download and Install DsHidMini and BthPS3

 DsHidMini suggests installing BthPS3 to have your DualShock controllers correctly detected and connected to your PC. This guide will follow that suggestion, especially since we want them to work wirelessly.

1. Start by downloading the first piece of software from[DsHidMini's GitHub page](https://github.com/ViGEm/DsHidMini) .  
![DsHidMini GitHub Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-github-page.jpg)
2. Do the same with a visit at[BthPS3's GitHub page](https://github.com/ViGEm/BthPS3) .  
![BthPS3 GitHub Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-github-page.jpg)
3. In both cases, you'll find the downloadable files by clicking on the link under**Installation** , then checking out the links under**Assets** . Most people should go for the x64 versions. If you're still using an older 32-bit version of Windows, get the x86 files.  
![BthPS3 GitHub Assets Links](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-github-assets-links.jpg)
4. Click on**BthPS3's MSI file** that you've downloaded to install the Bluetooth driver. "MSI" stands for Microsoft Software Installer. Unlike executable installers, MSI relies on the "official" installation libraries bundled with Windows. If you meet any problems during that step, check our guide on[how to fix issues with the Windows Installer package](https://www.makeuseof.com/windows-installer-package-fix-issues/) .  
![BthPS3 Installation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-installation.jpg)
5. After BthPS3's successful installation, you'll see it as a new device under the**Bluetooth** category in**Device Manager** . The easiest way to access the Device Manager is by using the**Windows Key** +**X** shortcut and selecting it from the menu that shows up.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![BthPS3 Installed Bluetooth Driver in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/bthps3-installed-bluetooth-driver-in-device-manager.jpg)
6. DsHidMini's installation is a tad more complicated since it comes in a compressed archive. Open**Windows File Explorer** , and pay a visit to the folder where you saved DsHidMini's downloaded archive. All modern versions of Windows support the ZIP archive format, so you can right-click on the file and choose**Extract** . However, we used WinRAR instead simply because we had it installed, and it's somewhat faster. In both cases, the result is the same.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Extracting DsHidMini Archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/extracting-dshidmini-archive.jpg)
7. Look inside the extracted archive's folder, and you'll see two more folders:**x64** and**x86** . Enter the one matching your Windows architecture. As mentioned above, most people nowadays should go for**x64** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![DsHidMini Extracted Archive Contents](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dshidmini-extracted-archive-contents.jpg)
8. Inside that folder, you'll find another subfolder named**dshidmini** . Enter that one, too.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

 Then, download[DriverStore Explorer from its GitHub page](https://github.com/lostindark/DriverStoreExplorer/releases/tag/v0.11.79) . Extract its archive and run the app. Enable**Force Deletion** on the right. Seek any**libusbK USB Devices** , a standalone**scpvbus.inf** , or**bluetoothhost.inf** and**ds3controller.inf** if using ScpToolkit.

 Look for**sixaxis.inf** instead if using the official Sony driver. In both cases, place a checkmark next to any of those entries you'll find, and then click on**Delete Drivers** on the right.

 Afterward, exit the app, restart your PC, and let Windows re-detect any hardware and install the default drivers. Then, repeat the steps we covered above to install BthPS3 and DsHidMini from scratch.

## How to Use Your PS3 DualShock in Games

 Your controller should work now in most modern games that support Xbox joypads and for most joypad-enabled titles running under Steam.

 When that's not the case, run DSHMC.exe as an administrator and change the HID mode used by your joypad to the one supported by the game or app where you want to use it.

 An easy way to find the HID mode to choose for a particular title is to check if there's information about it at[PCGamingWiki](https://www.pcgamingwiki.com/wiki/Main%5FPage) .

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
<li><a href="https://article-knowledge.techidaily.com/new-paw-some-profits-the-paychecks-of-pewdiepie/"><u>[New] Paw-Some Profits The Paychecks of PewDiePie</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-optimize-playback-settings-in-snapchat-applications/"><u>[Updated] How To Optimize Playback Settings in Snapchat Applications</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-the-art-of-affordable-data-storage-cloud/"><u>[Updated] Mastering the Art of Affordable Data Storage (Cloud)</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-navigating-the-world-of-video-editing-for-youtube-creators/"><u>[Updated] Navigating the World of Video Editing for YouTube Creators</u></a></li>
<li><a href="https://win11-tips.techidaily.com/8-handy-windows-10-and-11-command-shortcuts-you-can-set-up-with-nircmd/"><u>8 Handy Windows 10 & 11 Command Shortcuts You Can Set Up With NirCmd</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/comprehensive-equipment-testing-by-toms-electronic-hub/"><u>Comprehensive Equipment Testing by Tom's Electronic Hub</u></a></li>
<li><a href="https://win11.techidaily.com/enriched-user-experience-embedding-resource-consumption-data/"><u>Enriched User Experience: Embedding Resource Consumption Data</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/how-to-make-money-on-vimeo-your-ultimate-guide-to-vimeo-monetization-for-2024/"><u>How to Make Money on Vimeo Your Ultimate Guide to Vimeo Monetization for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-share-your-winning-forex-trades-with-friends-and-family-on-local-trade-copier-tm-together-by-mt4copier-guide/"><u>How to Share Your Winning Forex Trades With Friends and Family on Local Trade Copier™ Together</u></a></li>
<li><a href="https://win11.techidaily.com/installing-windows-compressed-archive-cab-files-simplified/"><u>Installing Windows Compressed Archive (CAB) Files Simplified</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-windows-11s-dialer/"><u>Navigate to Windows 11'S Dialer</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-system-rename-user-folders-win11-style/"><u>Optimize Your System: Rename User Folders, Win11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-notification-failures-in-outlook-top-strategies-for-windows-users/"><u>Overcoming Notification Failures in Outlook: Top Strategies for Windows Users</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-best-handheld-gaming-consoles-of-2024/"><u>The Best Handheld Gaming Consoles of 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-non-windows-screen-capturing-solutions/"><u>The Ultimate Guide to Non-Windows Screen Capturing Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-restart-non-operational-nvidia-cp-win11/"><u>Tips to Restart Non-Operational NVidia CP, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-code-0x0000004e-in-win11/"><u>Troubleshooting Code 0X0000004E in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-top-windows-based-ndsswitch-games/"><u>Ultimate Guide: Top Windows-Based NDS/Switch Games</u></a></li>
<li><a href="https://article-helps.techidaily.com/unveiling-the-power-of-slug-lines/"><u>Unveiling the Power of Slug Lines</u></a></li>
</ul></div>

