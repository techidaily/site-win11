---
title: Essential Advice to Supercharge Your WSL 2 and Docker Use
date: 2024-08-15T23:39:07.699Z
updated: 2024-08-16T23:39:07.699Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Advice to Supercharge Your WSL 2 and Docker Use
excerpt: This Article Describes Essential Advice to Supercharge Your WSL 2 and Docker Use
keywords: WSL2 Optimization Tips,Docker Performance Guide,Efficient WSL2 Usage,Supercharge Docker Setup,Enhance WSL2 Speed,Docker Management Basics,Advanced WSL2 Configurations
thumbnail: https://thmb.techidaily.com/a6dbe934550b4e8e63b5bdb5b2859a1cbef0d47ae79e9b219910350b66fadbff.jpg
---

## Essential Advice to Supercharge Your WSL 2 and Docker Use

 The Windows Subsystem for Linux 2 is a phenomenal tool on Windows 10 and 11, and integrates with Docker seamlessly. As developers, it's essential to understand what these software offers and how you can make the most out of your Docker-WSL 2 setup.

## What Is Docker?

 Docker is an open-source platform that allows developers to efficiently build, deploy and run their applications within a container. All dependencies are bundled up so your project can easily be deployed in any environment.

 Docker is very popular among many containerization platforms because it is reliable, functional, and highly scalable. It runs on the Docker engine, an essential DevOps tool that provides a clean and lightweight environment for testing and deployment. Docker is similar to a virtual machine but virtualizes the operating system rather than the underlying hardware.

![Microservice architecture](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microservice-architecture.jpg)

 For software developers, Docker streamlines workflow by creating individual containers for different microservices that include the necessary dependencies, libraries, and configurations. Each microservice container is isolated and individually scalable.

## How to Use Docker on WSL 2

 Docker is compatible with all major operating systems, such as Windows, macOS, and Linux. If you’re on Windows 10 or 11, you can use Docker via Docker Desktop and [integrate it with the Windows Subsystem for Linux 2](https://www.makeuseof.com/how-to-install-docker-windows-10-11/) for improved performance. You can download Docker Desktop for Windows from the [official Docker website](https://www.docker.com/products/docker-desktop/) .

![newly built image on docker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/newly-built-image-on-docker.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->

 The Windows Subsystem for Linux (WSL) is a valuable feature that allows Windows users to run Linux distributions like Ubuntu and Kali without setting up a virtual machine or dual-boot.

 This also means that [Windows users can directly use Linux command-line tools](https://www.makeuseof.com/run-linux-commands-windows-wsl-2/) , applications, and utilities without extra installation steps. The most recent version of WSL, WSL 2, provides greater stability and a dedicated Linux kernel.

 Since Docker containers are robust, you can even configure them to host your server; nginx docker containers are commonly used as web servers. Additionally, you can use Docker in several other ways:

* Run Linux distros easily
* Set up a web server for learning or testing purposes
* Portable deploy applications
* Bundle the application into a single image file
* Simplified CI/CD pipeline

 You must become familiar with the best practices for utilizing Docker with Windows Subsystem for Linux 2, just like you would with any other platform or tool. As a developer, I can say from personal experience that you'll become much more productive and efficient once you integrate the following tips into your workflow.

## 1\. Integrate VS Code with WSL 2

 Visual Studio Code is a popular IDE that’s loved due to its incredible features, community, and extensions. As a developer, the ability to use Visual Studio Code for app development on a Windows platform while also running those apps on a Linux kernel is an incredibly advantageous and almost unbelievable feature.

![wsl extension in VS Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-extension.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->

 When you integrate VS Code into the Windows Subsystem for Linux, you can take advantage of its specialized Linux kernel to enhance cross-platform compatibility. You can further streamline your workflow by utilizing the integrated terminal within VS Code with WSL 2.

 To [set up VS Code with WSL 2 on Windows](https://www.makeuseof.com/how-to-set-up-vs-code-with-wsl-2-windows-10-11/) , you can configure the**WSL** extension from the VS Code Marketplace and get things going.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Utilize the WSL 2 File System

 To properly run your Docker containers, it's vital that you rely on the file system of your WSL 2 distro and not heavily depend on the native Windows file system. Throughout my experience of working with Docker containers on WSL 2, I’ve discovered it’s better to store your project files within WSL.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Use Native Linux Scripts

 Many containerized projects that you’ll work on will probably come with scripts for automation on Linux. Typically, these scripts are first developed for Linux, and Windows developers aren’t a priority.

 With WSL 2, your entire team can use the same Linux automation scripts, and you don’t have to worry about maintaining Windows-compatible automation scripts for your team.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Configure BuildKit for Improved Security and Performance

 BuildKit is an open-source toolkit that improves the traditional Docker build process in terms of performance and security; it's directly integrated with Docker, so you don’t need to install it separately.

 When you enable the**BuildKit** by default, you’re making sure that your containers are being built with the BuildKit toolkit, giving you better security, concurrency, flexibility, and caching.

 To enable BuildKit by default, you should make the following changes to the \~/.profile config file:

`export DOCKER_BUILDKIT=1.`

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Set Up Resource Limits

 When you integrate the WSL 2 backend with Docker Desktop, you give Docker access to all your CPU resources. Doing so helps improve performance for containers that are resource heavy.

 However, in some cases, a container might allocate a lot of excess memory, causing critical OS processes to crash. You’re more likely to experience this when using database containers or a caching microservice.

 Fortunately, you can configure Docker containers to limit the system memory and CPU usage. You should always be careful while configuring the system memory, even a minor mistake can have significant consequences. You can refer to the [official Docker documentation](https://docs.docker.com/config/containers/resource%5Fconstraints/) for a more detailed guide on limiting the memory and CPU resources consumed by a Docker container.

## 6\. Recover Cached Memory

 If you’re running a Docker container in WSL 2, its memory should be freed once the container terminates. Unfortunately, the operating system kernel tends to maintain data in the cache; this means that the effective memory reclaimed by the WSL 2 won’t be sufficient.

 You can recover all of the memory that is unnecessarily being utilized as a cache by running the following command via root in WSL 2:

`echo 1 > /proc/sys/vm/drop_caches`

## Get Smarter With WSL 2

 The WSL 2 is the best feature for Windows-based developers, completely changing how developers use Docker. Developers must understand the best practices for using Docker with WSL to improve performance, security, and workflow flexibility.

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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-critical-analysis-leading-screencast-applications-of-today/"><u>[New] 2024 Approved  Critical Analysis  Leading Screencast Applications of Today</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-going-from-end-to-start-the-instagram-video-technique/"><u>[New] 2024 Approved  Going From End to Start  The Instagram Video Technique</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-unveiling-the-best-skype-recorders-of-this-year/"><u>[New] Unveiling the Best Skype Recorders of This Year</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-from-zero-to-hero-rising-in-popularity-with-vimeo-experts/"><u>2024 Approved  From Zero to Hero  Rising in Popularity with Vimeo Experts</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-innovation-at-play-the-best-professional-360-degree-cameras-2023-update/"><u>2024 Approved  Innovation at Play  The Best Professional 360-Degree Cameras - 2023 Update</u></a></li>
<li><a href="https://win11.techidaily.com/boost-quality-with-these-5-free-windows-editors/"><u>Boost Quality with These 5 FREE Windows Editors</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-dxgi-error-by-reattaching-devices-in-windows/"><u>Bypassing DXGI ERROR by Reattaching Devices in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-glitch-0x80072746-a-fix-guide-for-windows-mail/"><u>Bypassing Glitch 0X80072746: A Fix Guide for Windows Mail</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-persistent-login-challenges-with-ms-teams/"><u>Eliminating Persistent Login Challenges with MS Teams</u></a></li>
<li><a href="https://win11.techidaily.com/epic-sign-in-solutions-for-non-responsive-launcher/"><u>Epic Sign-In Solutions for Non-Responsive Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/essential-role-of-windows-batch-files-in-os-functioning/"><u>Essential Role of Windows Batch Files in OS Functioning</u></a></li>
<li><a href="https://win11.techidaily.com/from-iphone-to-desktop-bridging-imessage-between-devices/"><u>From iPhone to Desktop: Bridging iMessage Between Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-this-computer-doesnt-meet-minimum-requirements-intel-hd-graphics-error/"><u>How to Fix the This Computer Doesn’t Meet Minimum Requirements Intel HD Graphics Error</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-increase-dedicated-video-ram-vram-in-windows-11-and-11/"><u>How to Increase Dedicated Video RAM (VRAM) in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-locate-pcs-current-window-background-file/"><u>How to Locate PC's Current Window Background File</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-honor-magic-5-lite-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Honor Magic 5 Lite to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-nubia-z50s-pro-lock-screen-password-by-drfone-android/"><u>In 2024, How To Change Nubia Z50S Pro Lock Screen Password?</u></a></li>
<li><a href="https://win11.techidaily.com/leading-edge-lives-beyond-windows-11-expectations/"><u>Leading-Edge Lives: Beyond Windows 11 Expectations</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-maneuvers-for-concealing-windows-11s-control-icon/"><u>Masterful Maneuvers for Concealing Windows 11'S Control Icon</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-customization-adding-contextual-options-in-win-11/"><u>Mastering Window Customization: Adding Contextual Options in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-administrator-settings-in-windows-security/"><u>Navigating Administrator Settings in Windows Security</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/passfab-apple-iphone-12-pro-backup-unlocker-top-4-alternatives-drfone-by-drfone-ios/"><u>PassFab Apple iPhone 12 Pro Backup Unlocker Top 4 Alternatives | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/prime-windows-experience-select-top-optimizers-ranked/"><u>Prime Windows Experience: Select Top Optimizers Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/prioritizing-improvement-in-windows-11/"><u>Prioritizing Improvement in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/pushing-boundaries-exploring-win-and-ps1-synergy-via-duckstation/"><u>Pushing Boundaries: Exploring WIN and PS1 Synergy via Duckstation</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-restoring-previous-windows-configurations/"><u>Quick Guide to Restoring Previous Windows Configurations</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-apple-iphone-xs-max-drfone-by-drfone-virtual-ios/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Apple iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-browsing-copy-pasting-shortfalls-across-oses/"><u>Remedying Browsing Copy-Pasting Shortfalls Across OSes</u></a></li>
<li><a href="https://win11.techidaily.com/setting-alternative-pdf-printer-in-windows/"><u>Setting Alternative PDF Printer in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-sailing-through-full-screen-issues-sonic-style-on-w11/"><u>Smooth Sailing Through Full-Screen Issues, Sonic Style on W11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-restore-functionality-of-missing-steamuidll/"><u>Steps to Restore Functionality of Missing Steamui.dll</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-11-bypassing-hiccups-and-blockades/"><u>Streamlining Windows 11: Bypassing Hiccups & Blockades</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-androidpc-junctioning/"><u>The Ultimate Guide to Android/PC Junctioning</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-realme-note-50-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Realme Note 50 for Streaming | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-android-and-iphone-apps-for-free-photo-overlay-artistry-for-2024/"><u>Top Android & iPhone Apps for FREE Photo Overlay Artistry for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tranquil-technology-effortless-windows-11-shutdown/"><u>Tranquil Technology: Effortless Windows 11 Shutdown</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-your-digital-sketchpad-launching-ms-paint-on-win11/"><u>Unveiling Your Digital Sketchpad: Launching MS Paint on Win11</u></a></li>
</ul></div>
