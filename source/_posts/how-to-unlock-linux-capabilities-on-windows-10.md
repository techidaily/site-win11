---
title: How to Unlock Linux Capabilities on Windows 10
date: 2024-08-16T00:33:21.872Z
updated: 2024-08-17T00:33:21.872Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Unlock Linux Capabilities on Windows 10
excerpt: This Article Describes How to Unlock Linux Capabilities on Windows 10
keywords: Unlock Linux on Windows,Windows Linux Extension,Gain Linux Powers W10,Enhance W10 Linux Ability,Linux Capability Access,Linux Features for Windows,Windows Boost Linux Tools
thumbnail: https://thmb.techidaily.com/8443124490dd4d26d174966fed147fd5721a9572389508714a7b16fe1b9aa1b0.jpg
---

## How to Unlock Linux Capabilities on Windows 10

### Key Takeaways

* You must enable Windows Subsystem for Linux (WSL) before you can install a Linux distribution on a Windows PC.
* Not all Windows 10 versions are compatible with WSL, but all Windows 11 versions are.
* The updated WSL2 is more convenient and gives better performance, but you can switch to WSL1 to suit specific needs.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Requirements for Running WSL on Windows 10

 Before you enable Windows Subsystem for Linux, you should know of the minimum requirements needed to run WSL.

[According to Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install), you should be running Windows 10 (64-bit) version 2004 or higher with Build 19041 or higher.

 All Windows 11 versions can run WSL.

 If you’re not sure of your Windows 10 flavor, it’s easy to [check which version of Windows 10 you have installed](https://www.makeuseof.com/tag/how-to-check-windows-10-version-build/).

 Some older versions of Windows 10 can also work, but you’ll have to manually install WSL.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Enable Windows Subsystem for Linux

 In order to install the Linux bash shell on Windows 10, you first have to enable Windows Subsystem for Linux.

 You’ll know if WSL isn't enabled because you’ll run into the error: “The Windows Subsystem for Linux optional component is not enabled. Please enable it and try again.”

 Here’s how to enable WSL in Windows 10:

 You first need to get into Windows **Programs and Features**.

1. Open Windows 10 **Settings** and select **Apps**.
2. On the right side of the window, under **Related settings**, click on **Programs and Features**.

![Programs and Features option under the Related settings section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/program-and-features-option-in-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->

 Click **OK** to save your changes and hit **Restart now** to finish the process.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## WSL1 or WSL2: Which Is Better For You?

 WSL2 is an upgraded version of Windows Subsystem for Linux and is now the default when installing a Linux distribution in Windows. It works with Windows 11 or Windows 10, Version 1903, Build 18362 or higher.

 There are a few differences between the two versions of WSL; chiefly, WSL2 offers better performance in addition to support for full system call compatibility and IPv6 support. Also, WSL2 uses a full Linux kernel inside a managed virtual machine (VM), so you don’t have to set up and manage a VM to run a Linux distro.

### Reasons to Switch to WSL1

 While the latest version of WSL offers better performance and a wider range of support, there are reasons you may want to use the older version. This is because WSL1 runs with older versions of VMware and VirtualBox—and WSL2 does not, although it is compatible with the latest versions of VirtualBox and VMware, which both support Hyper-V.

 The main reason to use WSL1 instead of WSL2 is that it offers better performance across OS file systems—a hurdle that can be overcome by creating your project files in the Linux file system.

 With WSL enabled and a Linux distro installed, you’ll be on your way to executing commands.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/new-fostering-creativity-the-most-innovative-6-nft-services/"><u>[New] Fostering Creativity  The Most Innovative 6 NFT Services</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-illustrating-a-novel-tiktok-end-slide-for-2024/"><u>[New] Illustrating A Novel TikTok End Slide for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-step-by-step-guide-to-crafting-unique-iphone-tones-for-2024/"><u>[New] Step-by-Step Guide to Crafting Unique iPhone Tones for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-dial-in-to-youtube-chat-no-huge-follower-requirement/"><u>2024 Approved  Dial in to YouTube Chat, No Huge Follower Requirement</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-foundations-of-mixing-adobe-auditions-fade-in-technique/"><u>2024 Approved  Foundations of Mixing  Adobe Audition’s Fade In Technique</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-photo-keepers-companion-unlimited-free-options-and-elite-subscription-saviors/"><u>2024 Approved  The Photo Keeper’s Companion  Unlimited Free Options & Elite Subscription Saviors</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-realme-gt-neo-5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Realme GT Neo 5 | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/adjusted-disk-control-response/"><u>Adjusted Disk Control Response</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-through-torrent-lag-on-your-pc-with-qbittorrent/"><u>Breaking Through Torrent Lag on Your PC with qBittorrent</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-new-life-into-your-steam-games-milestones/"><u>Breathing New Life Into Your Steam Games' Milestones</u></a></li>
<li><a href="https://win11.techidaily.com/brightening-up-your-cursor-windows-tips-and-tricks/"><u>Brightening Up Your Cursor: Windows Tips & Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-chromes-glitch-enabling-flawless-filesync-on-windows/"><u>Bypass Chrome’s Glitch: Enabling Flawless Filesync on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-blurriness-9-ways-to-fine-tune-your-windows-display/"><u>Bypassing Blurriness: 9 Ways to Fine-Tune Your Windows Display</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-support-issue-in-windows-the-essential-fixes-list/"><u>Bypassing Support Issue in Windows: The Essential Fixes List</u></a></li>
<li><a href="https://win11.techidaily.com/capturing-your-cortana-story-in-windows-files/"><u>Capturing Your Cortana Story in Windows Files</u></a></li>
<li><a href="https://win11.techidaily.com/cautionary-tales-the-perils-of-affordable-windows-activation-codes/"><u>Cautionary Tales: The Perils of Affordable Windows Activation Codes</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-edge-symbols-regular-occurrence/"><u>Ceasing Edge Symbols' Regular Occurrence</u></a></li>
<li><a href="https://win11.techidaily.com/choosing-your-preferred-package-manager-for-windows-devices/"><u>Choosing Your Preferred Package Manager for Window's Devices</u></a></li>
<li><a href="https://win11.techidaily.com/circumnavigate-power-management-to-prevent-usb-sleep/"><u>Circumnavigate Power Management to Prevent USB Sleep</u></a></li>
<li><a href="https://win11.techidaily.com/clarifying-and-resolving-the-mystery-of-error-0x8007251d-in-windows/"><u>Clarifying and Resolving the Mystery of Error 0X8007251d in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/classic-ui-redesign-for-file-explorer-in-w11/"><u>Classic UI Redesign for File Explorer in W11</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-reset-user-permissions-to-basics-in-windows-11/"><u>Clean Slate: Reset User Permissions to Basics in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clear-and-concise-views-mastering-compact-explorer-layout/"><u>Clear and Concise Views: Mastering Compact Explorer Layout</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-obstacles-to-the-microsoft-store-on-windows-11/"><u>Clearing Obstacles to the Microsoft Store on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-path-to-smooth-ps-on-windows/"><u>Clearing the Path to Smooth PS on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-local-device-misnaming-on-windows-systems/"><u>Clearing Up Local Device Misnaming on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-windows-bluetooth-connectivity-issues/"><u>Clearing Up Windows Bluetooth Connectivity Issues</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-can-we-bypass-infinix-gt-10-pro-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Infinix GT 10 Pro FRP?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-do-you-unlock-your-iphone-se-2020-learn-all-4-methods-by-drfone-ios/"><u>In 2024, How Do You Unlock your iPhone SE (2020)? Learn All 4 Methods</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instagrams-best-captured-moments-made-available-to-iphone-for-2024/"><u>Instagram's Best Captured Moments Made Available to iPhone for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/mobile-operating-system-for-windows-samsung/"><u>Mobile Operating System for Windows (Samsung)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/navigating-srt-in-windows-macos-environments/"><u>Navigating SRT in Windows, macOS Environments</u></a></li>
<li><a href="https://techidaily.com/vivo-t2-5g-music-recovery-recover-deleted-music-from-vivo-t2-5g-by-fonelab-android-recover-music/"><u>Vivo T2 5G Music Recovery - Recover Deleted Music from Vivo T2 5G</u></a></li>
</ul></div>
