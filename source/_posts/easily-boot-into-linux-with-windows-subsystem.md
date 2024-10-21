---
title: Easily Boot Into Linux with Windows Subsystem
date: 2024-10-13T22:29:05.355Z
updated: 2024-10-21T11:57:39.832Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easily Boot Into Linux with Windows Subsystem
excerpt: This Article Describes Easily Boot Into Linux with Windows Subsystem
keywords: Linux WSX Access,Easy Linux Start,Windows Sub System,Linux Booting WSX,Linux On Windows,Substitute Linux Entry,Quick Linux Install
thumbnail: https://thmb.techidaily.com/35711b04893827e589108adbb18a73b7e3ecd093c90f2ad47957b85620005c06.png
---

## Easily Boot Into Linux with Windows Subsystem

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
<a href="https://aligracehair.sjv.io/c/5597632/1902273/19272" target="_top" id="1902273">
  <img src="//a.impactradius-go.com/display-ad/19272-1902273" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902273/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://laganoo.pxf.io/c/5597632/1484940/16446" target="_top" id="1484940">
  <img src="//a.impactradius-go.com/display-ad/16446-1484940" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484940/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’re in, click on **Turn Windows features on or off** on the left panel. Then scroll down and check the corresponding box to enable Windows Subsystem for Linux.

![Windows Subsystem for Linux option in Windows Features page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/enable-wsl-windows-10.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137226/26400" target="_top" id="2137226">
  <img src="//a.impactradius-go.com/display-ad/26400-2137226" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137226/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click **OK** to save your changes and hit **Restart now** to finish the process.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151868/7443" target="_top" id="2151868">
  <img src="//a.impactradius-go.com/display-ad/7443-2151868" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151868/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-hitpaw-screen-recorder-review-and-alternative-for-2024/"><u>[New] HitPaw Screen Recorder Review and Alternative for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-investigating-profit-per-viewer-engagement-on-video-platforms/"><u>[New] In 2024, Investigating Profit per Viewer Engagement on Video Platforms</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-pinnacle-speech-to-text-applications/"><u>[New] Pinnacle Speech-to-Text Applications</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-toontech-complete-insight-2024-edition/"><u>[New] ToonTech Complete Insight - 2024 Edition</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-confusion-to-clarity-your-telegram-web-guidebook/"><u>[Updated] From Confusion to Clarity Your Telegram Web Guidebook</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-resolve-deceptive-user-appearance-within-chat-environments/"><u>[Updated] In 2024, Resolve Deceptive User Appearance Within Chat Environments</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-vivo-v30-pro-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Vivo V30 Pro by Name | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-memdump-reports-from-blue-screen-errors/"><u>Exploring Memdump Reports From Blue Screen Errors</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-evaluating-active-presenter-8s-performance/"><u>In 2024, Evaluating Active Presenter 8'S Performance</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-the-same-wallpaper-on-windows-11-always/"><u>Keeping the Same Wallpaper on Windows 11 Always</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-smoothing-out-windows-update-problems/"><u>Strategies for Smoothing Out Windows Update Problems</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-gains-additional-lifespan-with-new-yearly-patches/"><u>Windows 11 Gains Additional Lifespan with New Yearly Patches</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-notes-made-simple-no-software-required/"><u>Windows 11 Notes Made Simple, No Software Required</u></a></li>
</ul></div>

