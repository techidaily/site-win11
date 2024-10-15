---
title: "Direct Access to Linux: Activating the Microsoft Feature"
date: 2024-10-13T20:55:24.782Z
updated: 2024-10-15T17:12:32.592Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Direct Access to Linux: Activating the Microsoft Feature"
excerpt: "This Article Describes Direct Access to Linux: Activating the Microsoft Feature"
keywords: Linux Direct Access,MS Windows Feature,Enable Linux Integration,Microsoft Linux Support,Linux Activation Tips,Linux and Windows Linkage,Unlocking Linux in Windows
thumbnail: https://thmb.techidaily.com/31fd63ab910fdd0bfef9c588934b4c990590f2025d46dff0a5963e90a62a92d8.jpg
---

## Direct Access to Linux: Activating the Microsoft Feature

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137201/26400" target="_top" id="2137201">
  <img src="//a.impactradius-go.com/display-ad/26400-2137201" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137201/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

 Click **OK** to save your changes and hit **Restart now** to finish the process.

### Installing WSL on a Windows Machine

 With WSL enabled on your Windows device, you can [install Windows Subsystem for Linux](https://www.makeuseof.com/tag/linux-bash-shell-on-windows-10/). After that, you can install any supported Linux distro right inside your Windows PC. Choosing a [small, lightweight Linux distro](https://www.makeuseof.com/tag/linux-distro-space/) might be helpful.

 You can also [install a Linux desktop in Windows](https://www.makeuseof.com/tag/linux-desktop-windows-subsystem/) that gives you a graphical UI to work with.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186802/12108" target="_top" id="1186802">
  <img src="//a.impactradius-go.com/display-ad/12108-1186802" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186802/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## WSL1 or WSL2: Which Is Better For You?

 WSL2 is an upgraded version of Windows Subsystem for Linux and is now the default when installing a Linux distribution in Windows. It works with Windows 11 or Windows 10, Version 1903, Build 18362 or higher.

 There are a few differences between the two versions of WSL; chiefly, WSL2 offers better performance in addition to support for full system call compatibility and IPv6 support. Also, WSL2 uses a full Linux kernel inside a managed virtual machine (VM), so you don’t have to set up and manage a VM to run a Linux distro.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Reasons to Switch to WSL1

 While the latest version of WSL offers better performance and a wider range of support, there are reasons you may want to use the older version. This is because WSL1 runs with older versions of VMware and VirtualBox—and WSL2 does not, although it is compatible with the latest versions of VirtualBox and VMware, which both support Hyper-V.

 The main reason to use WSL1 instead of WSL2 is that it offers better performance across OS file systems—a hurdle that can be overcome by creating your project files in the Linux file system.

 With WSL enabled and a Linux distro installed, you’ll be on your way to executing commands.

 If you want to run a Linux terminal on Windows, your best bet would be to enable Windows Subsystem for Linux (WSL), a gateway opener that allows you to install a Linux bash shell on a Windows OS. Once you’ve enabled WSL, you can install a Linux distro.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-the-ultimate-meme-playbook-no-10-essentials/"><u>[New] 2024 Approved The Ultimate Meme Playbook No. 10 Essentials</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ransform-your-videos-secrets-of-effective-youtube-seo-tools-for-2024/"><u>[New] Transform Your Videos Secrets of Effective YouTube SEO Tools for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-how-to-effortlessly-share-vimeo-video-on-instagram/"><u>[Updated] 2024 Approved How to Effortlessly Share Vimeo Video on Instagram</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-superior-gopro-film-production-options/"><u>[Updated] 2024 Approved Superior GoPro Film Production Options</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-samsung-galaxy-a34-5g-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Samsung Galaxy A34 5G</u></a></li>
<li><a href="https://win11.techidaily.com/multi-app-management-the-art-of-simultaneous-close-on-pcs/"><u>Multi-App Management: The Art of Simultaneous Close on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/redefine-your-storage-in-onedrive-within-win-11/"><u>Redefine Your Storage in OneDrive Within Win 11</u></a></li>
<li><a href="https://fox-blue.techidaily.com/skys-dynamic-range-showcase-websites-ranked-1-10-for-2024/"><u>Sky's Dynamic Range Showcase - Websites Ranked 1-10 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/swift-config-activatingdeactivating-ai-in-taskbar-window/"><u>Swift Config: Activating/Deactivating AI in Taskbar Window</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-overcome-office-365-issue-code-30015-26/"><u>Techniques to Overcome Office 365 Issue Code 30015-26</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-foundation-of-fluency-9-essential-english-grammar-strategies-by-an-esl-authority/"><u>The Foundation of Fluency: 9 Essential English Grammar Strategies by an ESL Authority</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-6-causes-behind-frequent-car-battery-failures/"><u>Top 6 Causes Behind Frequent Car Battery Failures</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-the-primary-motives-for-organizations-disallowing-chatgpt/"><u>Unveiling the Primary Motives for Organizations Disallowing ChatGPT</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    