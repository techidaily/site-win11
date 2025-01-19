---
title: "Windows Feature Switch: On WSL Integration Mode"
date: 2025-01-16T17:10:24.713Z
updated: 2025-01-19T02:07:23.196Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click **OK** to save your changes and hit **Restart now** to finish the process.

### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

## WSL1 or WSL2: Which Is Better For You?

 WSL2 is an upgraded version of Windows Subsystem for Linux and is now the default when installing a Linux distribution in Windows. It works with Windows 11 or Windows 10, Version 1903, Build 18362 or higher.

 There are a few differences between the two versions of WSL; chiefly, WSL2 offers better performance in addition to support for full system call compatibility and IPv6 support. Also, WSL2 uses a full Linux kernel inside a managed virtual machine (VM), so you don’t have to set up and manage a VM to run a Linux distro.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-skills.techidaily.com/new-quintessential-filters-to-perfect-ocean-shoots/"><u>[New] Quintessential Filters to Perfect Ocean Shoots</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-uplifting-movies-a-top-10-list-of-inspiration/"><u>[Updated] In 2024, Uplifting Movies A Top 10 List of Inspiration</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-mastery-in-making-gifs-into-stickers-on-messaging-platforms-with-this-guide/"><u>[Updated] Mastery in Making Gifs Into Stickers on Messaging Platforms with This Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unleash-your-creative-edge-with-adjustable-story-videos/"><u>[Updated] Unleash Your Creative Edge with Adjustable Story Videos</u></a></li>
<li><a href="https://win11.techidaily.com/a-simple-guide-to-mouse-customization-for-better-trail-control/"><u>A Simple Guide to Mouse Customization for Better Trail Control</u></a></li>
<li><a href="https://win11.techidaily.com/altering-the-look-of-window-11s-search-field/"><u>Altering the Look of Window 11'S Search Field</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/apple-iphone-14-plus-screen-mirroring-you-must-know-drfone-by-drfone-ios/"><u>Apple iPhone 14 Plus Screen Mirroring You Must Know | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/enhance-videos-on-vimeo-with-top-video-editors-for-2024/"><u>Enhance Videos on Vimeo with Top Video Editors for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-glitch-nvidia-experiences-x0001-in-w11/"><u>Fixing Glitch: Nvidia Experience's X0001 in W11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/hands-on-evaluation-is-the-apple-studio-display-a-must-have-or-just-an-expensive-luxury-for-mac-pro-users/"><u>Hands-On Evaluation: Is the Apple Studio Display a Must-Have or Just an Expensive Luxury for Mac Pro Users?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-file-download-failures-in-windows-1011/"><u>How to Resolve File Download Failures in Windows 10/11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-two-ways-to-sync-contacts-from-vivo-y100t-to-gmail-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Two Ways to Sync Contacts from Vivo Y100t to Gmail | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-printer-uninstallation-without-recovery-options/"><u>Mastering Printer Uninstallation without Recovery Options</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-sound-error-on-audacity-in-win1011/"><u>Resolving Sound Error on Audacity in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-system-use-with-6-advanced-trackers-for-win-users/"><u>Streamline System Use with 6 Advanced Trackers for Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-sluggish-windows-printer/"><u>Troubleshoot Sluggish WIndows Printer</u></a></li>
<li><a href="https://discover-help.techidaily.com/ultimate-lenovo-tab-examination-unleashing-the-titans-of-portable-computing/"><u>Ultimate Lenovo Tab Examination: Unleashing the Titans of Portable Computing</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveiling-the-potential-of-the-amplifi-hd-wireless-router-system-eliminate-your-homes-dead-zones-for-good/"><u>Unveiling the Potential of the Amplifi HD Wireless Router System: Eliminate Your Home's Dead Zones for Good</u></a></li>
<li><a href="https://win11.techidaily.com/win11-quick-fixes-for-photoshop-not-launching/"><u>Win11: Quick Fixes for Photoshop Not Launching</u></a></li>
</ul></div>

