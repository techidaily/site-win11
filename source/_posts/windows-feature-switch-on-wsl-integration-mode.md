---
title: "Windows Feature Switch: On WSL Integration Mode"
date: 2025-01-05T20:41:02.859Z
updated: 2025-01-06T18:34:37.835Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* You must enable Windows Subsystem for Linux (WSL) before you can install a Linux distribution on a Windows PC.
* Not all Windows 10 versions are compatible with WSL, but all Windows 11 versions are.
* The updated WSL2 is more convenient and gives better performance, but you can switch to WSL1 to suit specific needs.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

 Click **OK** to save your changes and hit **Restart now** to finish the process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

## WSL1 or WSL2: Which Is Better For You?

 WSL2 is an upgraded version of Windows Subsystem for Linux and is now the default when installing a Linux distribution in Windows. It works with Windows 11 or Windows 10, Version 1903, Build 18362 or higher.

 There are a few differences between the two versions of WSL; chiefly, WSL2 offers better performance in addition to support for full system call compatibility and IPv6 support. Also, WSL2 uses a full Linux kernel inside a managed virtual machine (VM), so you don’t have to set up and manage a VM to run a Linux distro.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-techniques.techidaily.com/new-expert-advice-top-ranked-call-alert-creators/"><u>[New] Expert Advice Top-Ranked Call Alert Creators</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-finding-your-voice-on-youtube-a-guide-to-selective-audiences/"><u>[Updated] Finding Your Voice on YouTube A Guide to Selective Audiences</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-disciplined-device-use-effective-ways-to-remove-youtube-channels/"><u>[Updated] In 2024, Disciplined Device Use Effective Ways to Remove Youtube Channels</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-premier-movie-sneak-peeks-ensemble/"><u>[Updated] Premier Movie Sneak Peeks Ensemble</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-windows-experience-installs-msibundle-and-appxappxpack-files-from-store/"><u>Enhance Your Windows Experience: Installs MsiBundle & Appx/Appxpack Files From Store</u></a></li>
<li><a href="https://win11.techidaily.com/expert-techniques-to-tackle-outlook-error-0x80040610-in-windows/"><u>Expert Techniques to Tackle Outlook Error 0X80040610 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-significance-of-copilot-key-with-windows-11/"><u>Exploring the Significance of Copilot Key with Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-vivo-s18-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Vivo S18</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-windows-11s-biometric-authentication/"><u>Implementing Windows 11'S Biometric Authentication</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-realme-c33-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Realme C33 2023 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/is-facebook-messenger-not-working-on-your-windows-pc-try-these-10-fixes/"><u>Is Facebook Messenger Not Working on Your Windows PC? Try These 10 Fixes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/lock-your-tecno-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Tecno Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-usb-recognition-failures-on-windows-11/"><u>Resolving USB Recognition Failures on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-hibernation-4-techniques-for-windows-users/"><u>Reviving Hibernation: 4 Techniques for Windows Users</u></a></li>
<li><a href="https://win-solutions.techidaily.com/unlock-the-secrets-to-starting-overwatch-2-effortlessly-in-202n-top-7-fix-strategies/"><u>Unlock the Secrets to Starting Overwatch 2 Effortlessly in 202N: Top 7 Fix Strategies</u></a></li>
</ul></div>

