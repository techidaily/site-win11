---
title: "Command Line Connections: Utilizing WSL in Windows"
date: 2024-12-03T02:12:07.482Z
updated: 2024-12-07T08:46:35.561Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Command Line Connections: Utilizing WSL in Windows"
excerpt: "This Article Describes Command Line Connections: Utilizing WSL in Windows"
keywords: WSL Basics,WSL Tips,Linux on Windows,Command Prompt Power,Terminal Efficiency,Bash Scripting,Shell Integration
thumbnail: https://thmb.techidaily.com/668fe014e6bae21be4d1f17bf36923c523f3242cbf8f9156a716780e5d4eeb63.jpg
---

## Command Line Connections: Utilizing WSL in Windows

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click **OK** to save your changes and hit **Restart now** to finish the process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-gradual-silence-techniques-in-fl/"><u>[New] 2024 Approved Gradual Silence Techniques in FL</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-premier-microphone-picks-for-blogging-pros/"><u>[Updated] Premier Microphone Picks for Blogging Pros</u></a></li>
<li><a href="https://article-files.techidaily.com/crafting-a-blended-media-experience-with-tunes-for-2024/"><u>Crafting a Blended Media Experience with Tunes for 2024</u></a></li>
<li><a href="https://fox-metric.techidaily.com/discover-the-power-of-icomponent-for-net-custom-controls-and-reusability/"><u>Discover the Power of IComponent for .NET Custom Controls and Reusability</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-storage-analysis-game-with-the-power-of-diskusage-in-windows/"><u>Elevating Your Storage Analysis Game with the Power of DiskUsage in Windows</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-reviews-and-advice-on-cutting-edge-computer-hardware-by-toms-team/"><u>Expert Reviews and Advice on Cutting-Edge Computer Hardware by Tom's Team</u></a></li>
<li><a href="https://win11.techidaily.com/fortifying-the-fortress-stabilizing-windows-dwarf-gameplay/"><u>Fortifying the Fortress: Stabilizing Windows-Dwarf Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-defense-strategies-for-insider-sets/"><u>Implementing Defense Strategies for Insider Sets</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-oppo-a59-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Oppo A59 5G? | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/mastering-the-file-explorer-in-windows-11-tips-and-tricks-for-a-better-experience/"><u>Mastering the File Explorer in Windows 11 - Tips and Tricks for a Better Experience</u></a></li>
<li><a href="https://techtrends.techidaily.com/mp4-to-divx-conversion-a-guide-for-users-of-windows-11-mac-os-and-online-tools/"><u>MP4 to DivX Conversion: A Guide for Users of Windows 11, Mac OS & Online Tools</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obstacles-of-skyrims-sse-on-windows/"><u>Overcoming Obstacles of Skyrim's SSE on Windows</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/samsung-bd-j5900-review-2023-update/"><u>Samsung BD-J5900 Review - 2023 Update</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-devices-with-longer-pins-in-win11/"><u>Securing Your Devices with Longer PINs in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocketing-download-speeds-tips-for-windows-users/"><u>Skyrocketing Download Speeds: Tips for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-errors-during-onedrive-syncs/"><u>Steps to Rectify Errors During OneDrive Syncs</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-reduce-windows-browser-resource-demand/"><u>Techniques to Reduce Windows Browser Resource Demand</u></a></li>
</ul></div>

