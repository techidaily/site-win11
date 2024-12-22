---
title: "Windows Feature Switch: On WSL Integration Mode"
date: 2024-12-17T17:11:59.058Z
updated: 2024-12-22T17:18:27.752Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/szUqw4TLvWs?si=srv1OeLOe579gLwj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Requirements for Running WSL on Windows 10

 Before you enable Windows Subsystem for Linux, you should know of the minimum requirements needed to run WSL.

[According to Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install), you should be running Windows 10 (64-bit) version 2004 or higher with Build 19041 or higher.

 All Windows 11 versions can run WSL.

 If you’re not sure of your Windows 10 flavor, it’s easy to [check which version of Windows 10 you have installed](https://www.makeuseof.com/tag/how-to-check-windows-10-version-build/).

 Some older versions of Windows 10 can also work, but you’ll have to manually install WSL.

## How to Enable Windows Subsystem for Linux

 In order to install the Linux bash shell on Windows 10, you first have to enable Windows Subsystem for Linux.

 You’ll know if WSL isn't enabled because you’ll run into the error: “The Windows Subsystem for Linux optional component is not enabled. Please enable it and try again.”

 Here’s how to enable WSL in Windows 10:

 You first need to get into Windows **Programs and Features**.

1. Open Windows 10 **Settings** and select **Apps**.
2. On the right side of the window, under **Related settings**, click on **Programs and Features**.

![Programs and Features option under the Related settings section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/program-and-features-option-in-settings.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click **OK** to save your changes and hit **Restart now** to finish the process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

## WSL1 or WSL2: Which Is Better For You?

 WSL2 is an upgraded version of Windows Subsystem for Linux and is now the default when installing a Linux distribution in Windows. It works with Windows 11 or Windows 10, Version 1903, Build 18362 or higher.

 There are a few differences between the two versions of WSL; chiefly, WSL2 offers better performance in addition to support for full system call compatibility and IPv6 support. Also, WSL2 uses a full Linux kernel inside a managed virtual machine (VM), so you don’t have to set up and manage a VM to run a Linux distro.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Reasons to Switch to WSL1

 While the latest version of WSL offers better performance and a wider range of support, there are reasons you may want to use the older version. This is because WSL1 runs with older versions of VMware and VirtualBox—and WSL2 does not, although it is compatible with the latest versions of VirtualBox and VMware, which both support Hyper-V.

 The main reason to use WSL1 instead of WSL2 is that it offers better performance across OS file systems—a hurdle that can be overcome by creating your project files in the Linux file system.

 With WSL enabled and a Linux distro installed, you’ll be on your way to executing commands.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/new-ultimate-list-greatest-anime-opener-tunes-for-2024/"><u>[New] Ultimate List Greatest Anime Opener Tunes for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-establish-visual-identity-on-facebook/"><u>[Updated] 2024 Approved Establish Visual Identity on Facebook</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-professionals-choice-premium-youtube-cameras/"><u>[Updated] Professionals' Choice Premium YouTube Cameras</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-youtube-to-avi-tutorial-plus-8-best-youtube-to-avi-converters/"><u>2024 Approved YouTube to AVI Tutorial + 8 Best YouTube to AVI Converters</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/explore-ingenious-techniques-for-voice-transformation-at-zero-price-for-2024/"><u>Explore Ingenious Techniques for Voice Transformation at Zero Price for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-variances-a-comparison-between-microsoft-and-standard-windows-accounts/"><u>Exploring Variances: A Comparison Between Microsoft and Standard Windows Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/flattening-windows-11-corner-style/"><u>Flattening Windows 11 Corner Style</u></a></li>
<li><a href="https://some-techniques.techidaily.com/follower-fliers-best-personal-drone-tech-for-2024/"><u>Follower Fliers Best Personal Drone Tech for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/gamings-finest-shooters-a-top-7-list/"><u>Gaming's Finest Shooters - A Top 7 List</u></a></li>
<li><a href="https://win11.techidaily.com/is-your-hardware-upgraded-for-win11-find-out/"><u>Is Your Hardware Upgraded For Win11? Find Out!</u></a></li>
<li><a href="https://win11.techidaily.com/preserving-customization-transferring-powertoys-to-a-new-machine/"><u>Preserving Customization: Transferring PowerToys to a New Machine</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/recommended-best-applications-for-mirroring-your-vivo-v29e-screen-drfone-by-drfone-android/"><u>Recommended Best Applications for Mirroring Your Vivo V29e Screen | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-classic-directx-games-with-dxvk-upgrades/"><u>Refreshing Classic DirectX Games with DXVK Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-microsoft-store-error-0x80073cf3/"><u>Steps to Resolve Microsoft Store Error 0X80073CF3</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-excessive-ntoskrnlexe-process/"><u>Tackling Excessive Ntoskrnl.exe Process</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/top-rated-touchscreen-laptops-professional-reviews-and-testing-insights/"><u>Top-Rated Touchscreen Laptops: Professional Reviews & Testing Insights</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-winupdate-error-x8019/"><u>Troubleshooting WinUpdate Error X8019</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    