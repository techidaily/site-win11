---
title: "Powerful Toolset at Fingertips: Using WSL on Windows"
date: 2024-10-31T05:16:54.839Z
updated: 2024-11-02T00:04:43.817Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Powerful Toolset at Fingertips: Using WSL on Windows"
excerpt: "This Article Describes Powerful Toolset at Fingertips: Using WSL on Windows"
keywords: Windows Subsystem (WSL),Powerful Tools,Fingertip Access,WSL for Dev,WSL Toolset,Linux on Win,Development Efficiency
thumbnail: https://thmb.techidaily.com/5ba7b3f6e60e87bd15e4d0d59cd473305f169947afe8b79e803b03fc556698ce.jpg
---

## Powerful Toolset at Fingertips: Using WSL on Windows

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Key Takeaways

* You must enable Windows Subsystem for Linux (WSL) before you can install a Linux distribution on a Windows PC.
* Not all Windows 10 versions are compatible with WSL, but all Windows 11 versions are.
* The updated WSL2 is more convenient and gives better performance, but you can switch to WSL1 to suit specific needs.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137394/7443" target="_top" id="2137394">
  <img src="//a.impactradius-go.com/display-ad/7443-2137394" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Requirements for Running WSL on Windows 10

 Before you enable Windows Subsystem for Linux, you should know of the minimum requirements needed to run WSL.

[According to Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install), you should be running Windows 10 (64-bit) version 2004 or higher with Build 19041 or higher.

 All Windows 11 versions can run WSL.

 If you’re not sure of your Windows 10 flavor, it’s easy to [check which version of Windows 10 you have installed](https://www.makeuseof.com/tag/how-to-check-windows-10-version-build/).

 Some older versions of Windows 10 can also work, but you’ll have to manually install WSL.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130533/26400" target="_top" id="2130533">
  <img src="//a.impactradius-go.com/display-ad/26400-2130533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130533/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1997680/19272" target="_top" id="1997680">
  <img src="//a.impactradius-go.com/display-ad/19272-1997680" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997680/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **OK** to save your changes and hit **Restart now** to finish the process.

### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

## WSL1 or WSL2: Which Is Better For You?

 WSL2 is an upgraded version of Windows Subsystem for Linux and is now the default when installing a Linux distribution in Windows. It works with Windows 11 or Windows 10, Version 1903, Build 18362 or higher.

 There are a few differences between the two versions of WSL; chiefly, WSL2 offers better performance in addition to support for full system call compatibility and IPv6 support. Also, WSL2 uses a full Linux kernel inside a managed virtual machine (VM), so you don’t have to set up and manage a VM to run a Linux distro.

### Reasons to Switch to WSL1

 While the latest version of WSL offers better performance and a wider range of support, there are reasons you may want to use the older version. This is because WSL1 runs with older versions of VMware and VirtualBox—and WSL2 does not, although it is compatible with the latest versions of VirtualBox and VMware, which both support Hyper-V.

 The main reason to use WSL1 instead of WSL2 is that it offers better performance across OS file systems—a hurdle that can be overcome by creating your project files in the Linux file system.

 With WSL enabled and a Linux distro installed, you’ll be on your way to executing commands.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/n-2024-extract-youtube-soundtracks-for-free-with-this-list-of-25-rippers/"><u>[New] In 2024, Extract YouTube Soundtracks for Free With This List of 25 Rippers</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/latform-showdown-vimeos-edge-vs-youtube-and-dailymotion-for-2024/"><u>[New] Platform Showdown Vimeo's Edge vs YouTube & Dailymotion for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-instagram-reels-expertise-from-a-ninja-perspective/"><u>[Updated] 2024 Approved Instagram Reels Expertise From a Ninja Perspective</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-decoding-youtube-exchange-threads/"><u>[Updated] In 2024, Decoding YouTube Exchange Threads</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-optimizing-video-sequences-blend-modes-application-for-2024/"><u>[Updated] Optimizing Video Sequences Blend Modes Application for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-pro-rated-top-8-convertors-for-subtitles-and-srts/"><u>2024 Approved Pro-Rated Top 8 Convertors for Subtitles & SRTs</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-new-life-into-amd-graphics-on-windows-11-with-updated-drivers/"><u>Breathe New Life Into AMD Graphics on Windows 11 with Updated Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-two-email-realms-add-gmail-to-outlook-windows-edition/"><u>Bridging Two Email Realms: Add Gmail to Outlook, Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/building-a-better-interface-new-menu-additions-for-win-11/"><u>Building a Better Interface: New Menu Additions for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-fake-virus-detection-on-windows-chrome-edition/"><u>Bypassing Fake Virus Detection on Windows Chrome Edition</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-ram-limitations-on-your-windows-computer/"><u>Bypassing Ram Limitations on Your Windows Computer</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-windows-store-mishap-with-code-x80072f30-fix/"><u>Bypassing the Windows Store Mishap with Code X80072F30 Fix</u></a></li>
<li><a href="https://win11.techidaily.com/cease-windows-from-activating-spotify-autoplay/"><u>Cease Windows From Activating Spotify Autoplay</u></a></li>
<li><a href="https://win11.techidaily.com/champion-windows-options-for-true-nintendo-switch-experience/"><u>Champion Windows Options for True Nintendo Switch Experience</u></a></li>
<li><a href="https://win11.techidaily.com/chrono-correction-guide-your-chrome-and-pc-sync/"><u>Chrono-Correction Guide: Your Chrome & PC Sync</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effortless-self-measurement-unleashing-the-power-of-the-android-measure-app/"><u>Effortless Self-Measurement: Unleashing the Power of the Android Measure App</u></a></li>
<li><a href="https://extra-information.techidaily.com/expert-tips-for-applying-apple-music-to-your-videos/"><u>Expert Tips for Applying Apple Music to Your Videos</u></a></li>
<li><a href="https://android-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-motorola-moto-g23-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Motorola Moto G23 FRP Locks</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-best-free-video-shrinking-software-for-windows-10-users/"><u>Updated 2024 Approved Best Free Video Shrinking Software for Windows 10 Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    