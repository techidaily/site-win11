---
title: "Efficiently Develop with WSL 2: Core Practices for Dev on Windows"
date: 2024-12-18T16:39:02.542Z
updated: 2024-12-22T16:31:27.981Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Efficiently Develop with WSL 2: Core Practices for Dev on Windows"
excerpt: "This Article Describes Efficiently Develop with WSL 2: Core Practices for Dev on Windows"
keywords: WSL Development,WSL Dev Tips,Windows Coding,WSL Dev Pros,Efficient WSL Dev,WinDev Strategies,WSL Code Practices
thumbnail: https://thmb.techidaily.com/775033cec734e193d493811f769dcaa65d428fba2286e40a488d59f8b08228ae.png
---

## Efficiently Develop with WSL 2: Core Practices for Dev on Windows

 Microsoft has introduced nifty features to Windows 10 and 11 in recent years, but for the developer community, the Windows Subsystem for Linux 2 is probably one that stands out. Building on the original WSL, the newer WSL 2 brings more power and reliability for developers. Developers must know how to leverage the most out of WSL 2.

 Read on as we discuss some of the best practices for using the Windows Subsystem for Linux 2.

## What Is Windows Subsystem for Linux 2?

 The Windows Subsystem for Linux 2 (WSL 2) is a Linux kernel built into Windows 10 and 11\. One of today's most valuable features is the Windows Subsystem for Linux (WSL). It lets Windows users run Linux distributions such as Ubuntu and Kali on Windows without having to dual-boot or[configure a specialized virtual machine](https://www.makeuseof.com/linux-virtual-machine-or-wsl/) .

 Without the need for further installation work, Windows users can instantly access the Linux command-line tools, programs, and utilities. Initially launched with Windows 10, the latest version–WSL 2, offers much more stability and power.

 In addition to being able to operate the Linux terminal, Windows users can even[run Linux GUI applications with WSL 2 on Windows](https://www.makeuseof.com/how-to-run-linux-gui-apps-with-wsl2/) with improved support for file I/O performance and OS functionality.

## How Does the Windows Subsystem for Linux Benefit Developers?

![A laptop sitting on a desk with code open on the screen.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/laptop-with-code-on-the-screen.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 As a developer, you can benefit from WSL by developing cross-platform applications without worrying about dedicated VM setup or leaving the Windows ecosystem. It also provides developers with a powerful Linux kernel that is directly integrated within Windows 10/11.

Here are some of the other important WSL 2 benefits for developers:

* Easily access Linux tools and utilities: Developers can directly use Linux command-line tools such as awk, sed, grep, iftop, etc., without a dedicated VM or container.
* Simple setup: Windows Subsystem for Linux 2 is effortless to install. You can directly get it through the Microsoft Store; you’re also free to choose from a list of supported Linux distributions.
* Improved performance: WSL 2 provides optimum performance as it uses a lightweight virtual machine; this gives your applications faster boot times and allows efficient resource utilization.
* Seamless integration with Windows: Since WSL 2 is directly integrated with the Windows OS, developers can run Linux and Windows apps simultaneously, utilize shared file directories and even configure VS Code to work with apps running on WSL 2\. Thanks to WSL 2, there is a significant reduction in the dev environment complexity and additional overhead.
* Enhanced Docker integration: You can natively run Docker containers on WSL 2 by enabling the WSL-2 backend setting in Docker Desktop; this will help improve the compatibility of your Docker apps and enhance overall performance.

 Configuring the WSL 2 development environment will ensure you’re able to use a consistent environment across multiple devices and platforms, which can, in turn, reduce the possibility of errors and improve reliability. You will also be able to become more productive in utilizing the Windows Subsystem for Linux 2 on Windows 10 and 11.

 For users new to WSL 2, following the best practices to establish an efficient workflow is essential. On the other hand, if you’re already familiar with WSL 2, these tips will help ensure you’re being as productive as possible.

## 1\. Use the Windows Terminal

 The all-new Windows Terminal is a powerful open-source terminal from the Microsoft Store. Microsoft has designed the Windows Terminal to integrate the WSL 2 directly and automatically configure any Linux distributions as soon as they’re installed. This means you can easily switch between Windows and Linux without having to set up a different environment.

![The Open a new tab menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/command-shell-options-in-windows-terminal.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The Windows Terminal can support multiple shells, such as PowerShell, WSL 2, and Command Prompt. It also offers several productivity features, including multiple tabs, a search bar, and split panes; you can even customize the terminal’s appearance to your liking.

 Since the Windows Terminal is an open-source project, you can rest assured that the community will continuously improve it for enhanced user experience. And if you fall in love with it, check out the[best Windows terminal tips, tricks, and shortcuts](https://www.makeuseof.com/windows-terminal-tips-tricks-shortcuts/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Integrate Visual Studio Code

![Code in VSCode on laptop sitting on the ground](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Code-on-Laptop.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Many developers rely on VS Code, an incredibly versatile IDE (code editor). It offers an integrated terminal, extension support, and has an intuitive interface that is super–customizable. If you’re using WSL 2 for development, you want to integrate WSL 2 with Visual Studio Code for a smooth workflow.

 You can use VS Code with WSL 2 by ensuring you have Visual Studio Code and a WSL 2 Linux distribution on your Windows system. You can install the**Remote - WSL** extension in Visual Studio Code and configure it according to your requirements.

## 3\. Set Up Multiple Profiles

 If you plan on using WSL 2 for work, personal learning, or school, consider creating separate user profiles. This will allow you to keep your apps, configs, and files organized.

 One method to set up multiple profiles is to use the Windows Terminal; once you’ve got it installed on your Windows 10 or 11 PC, navigate to**Settings > Profiles > Add** .

## 4\. Update Packages

 Like any other Linux distribution, you’ll have to ensure the packages and tools you’re using on WSL 2 are constantly updated. Doing so ensures your WSL 2 is secure, reliable, and performing optimally. To update packages on WSL 2, enter the following command:

`sudo apt-get update`

`sudo apt-get upgrade`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Run Containers With Docker

![ubuntu running as a docker container](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/running-_ubunut_in_docker.jpg)

 Docker is an open-source platform that allows developers to efficiently build, deploy and run their applications within a container. All dependencies are bundled up so your project can easily be deployed in any environment.

 You can use Docker on Windows 10 and 11 via Docker Desktop as a standalone application or integrate it with Windows Subsystem for Linux for better performance and efficient resource consumption. We strongly recommend running your containers with WSL 2 for development or testing.

## WSL 2 Is A Win-Win on Windows

 The Windows Subsystem for Linux 2 is incredible and effectively bridges the gap between Linux and Windows ecosystems. As a developer accustomed to Windows, you can leverage WSL 2 to get the best of both Windows and Linux without compromising your productivity or flexibility.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-cloud.techidaily.com/new-eco-editing-essentials-30plus-free-templates-for-ambitious-filmmakers/"><u>[New] Eco-Editing Essentials 30+ Free Templates for Ambitious Filmmakers</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-audio-capture-access-and-assessment/"><u>2024 Approved Audio Capture Access & Assessment</u></a></li>
<li><a href="https://howto.techidaily.com/6-fixes-to-unfortunately-whatsapp-has-stopped-error-popups-on-oppo-a38-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Fixes to Unfortunately WhatsApp has stopped Error Popups On Oppo A38 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-win-11-challenges-the-seamless-gameplay-upgrade-plan-of-7-steps/"><u>Conquer Win 11 Challenges: The Seamless Gameplay Upgrade Plan of 7 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/dive-deep-into-wintoys-the-essential-walkthrough-for-windows-users/"><u>Dive Deep Into 'WinToys': The Essential Walkthrough for Windows Users</u></a></li>
<li><a href="https://discover-help.techidaily.com/easy-guide-finding-files-on-your-pc-with-windows-tips-from-yl-computing/"><u>Easy Guide: Finding Files on Your PC with Windows - Tips From YL Computing</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-experience-maximizing-taskbar-symbol-size/"><u>Enhancing User Experience - Maximizing Taskbar Symbol Size</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-fixing-non-operational-mailcalender-in-w11/"><u>Essential Guide: Fixing Non-Operational Mail/Calender in W11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/essential-guide-protecting-your-privacy-with-a-vpn-on-vision-pro-and-similar-xr-devices-zdnet/"><u>Essential Guide: Protecting Your Privacy with a VPN on Vision Pro and Similar XR Devices | ZDNet</u></a></li>
<li><a href="https://win11.techidaily.com/from-lost-to-found-reinstating-deleted-files-on-pcs/"><u>From Lost to Found: Reinstating Deleted Files on PCs</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-convert-avchd-mts-to-mp4-for-sony-xperia-1-v-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to convert AVCHD MTS to MP4 for Sony Xperia 1 V?</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-installation-access-issues-on-windows-1011/"><u>Overcoming Installation Access Issues on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-non-functional-keys-in-snipping-tool/"><u>Overcoming Non-Functional Keys in Snipping Tool</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/quick-and-simple-steps-uncover-hardware-details-on-a-windows-10-machine/"><u>Quick & Simple Steps: Uncover Hardware Details on a Windows 10 Machine</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-recalibrating-windows-energy-mode/"><u>Tips for Recalibrating Windows Energy Mode</u></a></li>
<li><a href="https://vp-tips.techidaily.com/urgent-top-10-lost-iphone-x-solutions-revealed-for-2024/"><u>Urgent Top 10 Lost iPhone X Solutions Revealed for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/why-its-crucial-to-organize-your-virtual-world-unlock-the-secrets-of-a-neat-digital-existence/"><u>Why It’s Crucial to Organize Your Virtual World: Unlock the Secrets of a Neat Digital Existence</u></a></li>
</ul></div>

