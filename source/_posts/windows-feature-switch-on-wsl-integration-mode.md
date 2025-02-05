---
title: "Windows Feature Switch: On WSL Integration Mode"
date: 2025-02-02T04:47:05.248Z
updated: 2025-02-04T00:00:15.200Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Feature Switch: On WSL Integration Mode"
excerpt: "This Article Describes Windows Feature Switch: On WSL Integration Mode"
keywords: Windows Feature,WSL Integration,Linux on Windows,Bash Terminal,Command Line Access,Developer Toolset,OS Compatibility
thumbnail: https://thmb.techidaily.com/30d2a20c84a301395b600ba93cb77523eb9f5d9c595c4e33a41955717da718a0.jpg
---

## Windows Feature Switch: On WSL Integration Mode

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Key Takeaways

* You must enable Windows Subsystem for Linux (WSL) before you can install a Linux distribution on a Windows PC.
* Not all Windows 10 versions are compatible with WSL, but all Windows 11 versions are.
* The updated WSL2 is more convenient and gives better performance, but you can switch to WSL1 to suit specific needs.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

## Requirements for Running WSL on Windows 10

 Before you enable Windows Subsystem for Linux, you should know of the minimum requirements needed to run WSL.

[According to Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install), you should be running Windows 10 (64-bit) version 2004 or higher with Build 19041 or higher.

 All Windows 11 versions can run WSL.

 If you’re not sure of your Windows 10 flavor, it’s easy to [check which version of Windows 10 you have installed](https://www.makeuseof.com/tag/how-to-check-windows-10-version-build/).

 Some older versions of Windows 10 can also work, but you’ll have to manually install WSL.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click **OK** to save your changes and hit **Restart now** to finish the process.

### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## WSL1 or WSL2: Which Is Better For You?

 WSL2 is an upgraded version of Windows Subsystem for Linux and is now the default when installing a Linux distribution in Windows. It works with Windows 11 or Windows 10, Version 1903, Build 18362 or higher.

 There are a few differences between the two versions of WSL; chiefly, WSL2 offers better performance in addition to support for full system call compatibility and IPv6 support. Also, WSL2 uses a full Linux kernel inside a managed virtual machine (VM), so you don’t have to set up and manage a VM to run a Linux distro.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-achieving-excellence-with-central-luts-for-films/"><u>[New] In 2024, Achieving Excellence with Central Luts for Films</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-earning-through-instagram-a-guide-to-attracting-brand-partnerships/"><u>[New] In 2024, Earning Through Instagram A Guide to Attracting Brand Partnerships</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-pursuing-prolonged-iphone-night-sky-captures-for-2024/"><u>[New] Pursuing Prolonged iPhone Night Sky Captures for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/command-turn-off-windows-nvidia-overlay-effects/"><u>Command: Turn Off Windows NVIDIA Overlay Effects</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-thx-spatial-sound-woes-on-windows-systems/"><u>Fixing THX Spatial Sound Woes on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-fixing-windows-11-compatibility-glitches/"><u>Guide to Fixing Windows 11 Compatibility Glitches</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-honor-x8b-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Honor X8b Phone without PIN</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Honor Magic 5 Lite? | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/in-depth-analysis-of-the-newest-apple-tv-4k-release/"><u>In-Depth Analysis of the Newest Apple TV 4K Release</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-storage-the-ultimate-guide-to-file-deleting-in-win11/"><u>Maximizing Storage: The Ultimate Guide to File Deleting in Win11</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-poco-m6-5g-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Poco M6 5G and Browser | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-ready-five-fixed-strategies-for-secure-boot-dilemmas/"><u>Reboot Ready: Five Fixed Strategies for Secure Boot Dilemmas</u></a></li>
<li><a href="https://win11.techidaily.com/seeking-efficiency-the-ultimate-guide-to-low-ram-browser-choices/"><u>Seeking Efficiency: The Ultimate Guide to Low-RAM Browser Choices</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-pc-searches-use-everythingapp/"><u>Streamline Your PC Searches, Use EverythingApp</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/unlock-the-potential-of-facebook-livestreams-with-professional-wirecast/"><u>Unlock the Potential of Facebook Livestreams with Professional Wirecast</u></a></li>
</ul></div>

