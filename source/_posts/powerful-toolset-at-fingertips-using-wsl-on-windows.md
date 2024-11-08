---
title: "Powerful Toolset at Fingertips: Using WSL on Windows"
date: 2024-11-05T17:40:44.390Z
updated: 2024-11-07T21:22:14.037Z
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

## Requirements for Running WSL on Windows 10

 Before you enable Windows Subsystem for Linux, you should know of the minimum requirements needed to run WSL.

[According to Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install), you should be running Windows 10 (64-bit) version 2004 or higher with Build 19041 or higher.

 All Windows 11 versions can run WSL.

 If you’re not sure of your Windows 10 flavor, it’s easy to [check which version of Windows 10 you have installed](https://www.makeuseof.com/tag/how-to-check-windows-10-version-build/).

 Some older versions of Windows 10 can also work, but you’ll have to manually install WSL.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136624/26400" target="_top" id="2136624">
  <img src="//a.impactradius-go.com/display-ad/26400-2136624" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136624/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable Windows Subsystem for Linux

 In order to install the Linux bash shell on Windows 10, you first have to enable Windows Subsystem for Linux.

 You’ll know if WSL isn't enabled because you’ll run into the error: “The Windows Subsystem for Linux optional component is not enabled. Please enable it and try again.”

 Here’s how to enable WSL in Windows 10:

 You first need to get into Windows **Programs and Features**.

1. Open Windows 10 **Settings** and select **Apps**.
2. On the right side of the window, under **Related settings**, click on **Programs and Features**.

![Programs and Features option under the Related settings section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/program-and-features-option-in-settings.jpg)

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

 Click **OK** to save your changes and hit **Restart now** to finish the process.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148649/16836" target="_top" id="2148649">
  <img src="//a.impactradius-go.com/display-ad/16836-2148649" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148649/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## WSL1 or WSL2: Which Is Better For You?

 WSL2 is an upgraded version of Windows Subsystem for Linux and is now the default when installing a Linux distribution in Windows. It works with Windows 11 or Windows 10, Version 1903, Build 18362 or higher.

 There are a few differences between the two versions of WSL; chiefly, WSL2 offers better performance in addition to support for full system call compatibility and IPv6 support. Also, WSL2 uses a full Linux kernel inside a managed virtual machine (VM), so you don’t have to set up and manage a VM to run a Linux distro.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082539/7443" target="_top" id="2082539">
  <img src="//a.impactradius-go.com/display-ad/7443-2082539" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082539/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-direct.techidaily.com/new-elevate-your-gaming-experience-discovering-kinemasters-potential/"><u>[New] Elevate Your Gaming Experience - Discovering KineMaster's Potential</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-visuals-and-audio-top-5-video-creators-guide/"><u>[New] Mastering Visuals and Audio Top 5 Video Creators' Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-amplify-reach-todays-most-effective-instagram-tag-strategies/"><u>[Updated] 2024 Approved Amplify Reach Today's Most Effective Instagram Tag Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-desktops-on-win-11-the-drawing-guide/"><u>Enhancing Desktops on Win 11 - The Drawing Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/find-your-next-upgrade-buying-amd-ryzen-7-9700x-and-ryzen-5-9600x-cpus/"><u>Find Your Next Upgrade: Buying AMD Ryzen 7 9700X and Ryzen 5 9600X CPUs</u></a></li>
<li><a href="https://win11.techidaily.com/free-the-windowed-dialogues-with-freedomgpt/"><u>Free the Windowed Dialogues: With FreedomGPT</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-instantly-enabledisable-bings-assistive-chat/"><u>How to Instantly Enable/Disable Bing's Assistive Chat</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On Honor Magic Vs 2? | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-amplify-visual-impact-mastering-the-art-of-applying-luts-with-obs-studio/"><u>In 2024, Amplify Visual Impact Mastering the Art of Applying LUTs with OBS Studio</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-installation-techniques-for-win11-and-workstation-17/"><u>Mastering Installation Techniques for Win11 and Workstation 17</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-missing-heat-flow-management-in-pcs/"><u>Restoring Missing Heat Flow Management in PCs</u></a></li>
<li><a href="https://win11.techidaily.com/secure-windows-with-these-5-firewall-adjustments/"><u>Secure Windows with These 5 Firewall Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/stop-diminished-size-of-your-windows-11-desktop-icons/"><u>Stop Diminished Size of Your Windows 11 Desktop Icons</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-best-free-messaging-apps-on-android-a-comprehensive-top-10-list/"><u>The Best Free Messaging Apps on Android: A Comprehensive Top 10 List</u></a></li>
<li><a href="https://apple-account.techidaily.com/the-easy-way-to-remove-an-apple-id-from-your-macbook-for-your-iphone-xs-by-drfone-ios/"><u>The Easy Way to Remove an Apple ID from Your MacBook For your iPhone XS</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-security-top-7-password-tools-reviewed/"><u>Unlock Windows Security: Top 7 Password Tools Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-riddle-of-where-windows-houses-your-apps/"><u>Unraveling the Riddle of Where Windows Houses Your Apps</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/windows-11-laptop-backup-strategies-three-effective-approaches-covering-files-and-os/"><u>Windows 11 Laptop Backup Strategies: Three Effective Approaches Covering Files and OS</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-honor-magic5-ultimate-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Honor Magic5 Ultimate | Dr.fone</u></a></li>
</ul></div>

