---
title: Unleashing Full-Scale Development with WSL in Windows 10
date: 2024-12-06T02:52:14.829Z
updated: 2024-12-07T11:19:07.447Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unleashing Full-Scale Development with WSL in Windows 10
excerpt: This Article Describes Unleashing Full-Scale Development with WSL in Windows 10
keywords: WSL Dev Boost,WSL Windows 10,Linux on Windows,WSL Coding,Enhanced WSL,Full-Scale WSL,Linux Power Win
thumbnail: https://thmb.techidaily.com/51c7e118bec96598bc9d2d2c18cf903e1dca3cd5201c33fd6a45fd74bf88fe0d.jpg
---

## Unleashing Full-Scale Development with WSL in Windows 10

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* You must enable Windows Subsystem for Linux (WSL) before you can install a Linux distribution on a Windows PC.
* Not all Windows 10 versions are compatible with WSL, but all Windows 11 versions are.
* The updated WSL2 is more convenient and gives better performance, but you can switch to WSL1 to suit specific needs.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NTQGoOOiJzs?si=zbZwflEfXgBY3qbs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click **OK** to save your changes and hit **Restart now** to finish the process.

### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-crafting-captivating-youtube-thumbnails-a-sizing-guide/"><u>[Updated] 2024 Approved Crafting Captivating YouTube Thumbnails A Sizing Guide</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-beyond-basic-filters-elevating-your-snapchat-game/"><u>[Updated] Beyond Basic Filters Elevating Your Snapchat Game</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-become-a-travel-vlogger-the-ultimate-guide-of-travel-vlogging/"><u>[Updated] In 2024, How To Become A Travel Vlogger | The Ultimate Guide of Travel Vlogging</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-decades-most-ingenious-frames-and-organizers-24/"><u>[Updated] The Decade's Most Ingenious Frames & Organizers '24</u></a></li>
<li><a href="https://win11.techidaily.com/discreet-transfers-the-art-of-secure-file-movement-in-windows-10/"><u>Discreet Transfers: The Art of Secure File Movement in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/explaining-and-fixing-windows-defender-error-0x80004004/"><u>Explaining & Fixing Windows Defender Error 0X80004004</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-instant-recording-sight-and-sound-fused/"><u>In 2024, Instant Recording Sight & Sound Fused</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-uniting-your-soundtrack-sets-from-different-spaces/"><u>In 2024, Uniting Your Soundtrack Sets From Different Spaces</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-motorola-moto-g23-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Motorola Moto G23 Phone FRP Lock</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-steam-login-problems-fixes/"><u>Mastering Windows Steam Login Problems Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-control-of-freeze-shift-keys/"><u>Reclaim Control of Freeze Shift Keys</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/social-media-mirrors-the-science-of-true-ig-selfies-for-2024/"><u>Social Media Mirrors The Science of True IG Selfies for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    