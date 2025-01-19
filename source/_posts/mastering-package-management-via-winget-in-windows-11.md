---
title: Mastering Package Management via Winget in Windows 11
date: 2025-01-12T20:00:56.454Z
updated: 2025-01-19T09:56:02.811Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Package Management via Winget in Windows 11
excerpt: This Article Describes Mastering Package Management via Winget in Windows 11
keywords: Winget Power Tools,Win11 Winget Guide,Efficient Dependency Control,Streamline App Installation,Simplified Package Management,Automated Windows Updates,Modern SDK Integration
thumbnail: https://thmb.techidaily.com/20ff4f86f64949aeed71ebab473532ee23ffbe18dd68a783845f09bf91d3afe4.jpg
---

## Mastering Package Management via Winget in Windows 11

 Winget is a command-line tool that can download and install app packages from MS Store and the apps available in its repository. Windows users yearned for a dedicated package manager built into the OS until Microsoft decided to give them one. It is better than using an additional package manager but not all users love the terminal.

 If you have used Winget even once, you know that knowing the correct commands is of absolute importance if you want to avoid errors. But what if you had a GUI version of Winget? WingetUI is one such app that slaps a coat of UI on Winget. Curious? Let’s begin.

## What Is WingetUI, and How Is It Different From Winget?

 WingetUI is a GUI implementation of the [Winget](https://www.makeuseof.com/how-to-download-install-and-use-the-windows-package-manager-winget/)tool that makes it super easy to manage app packages. It also supports Scoop and Chocolatey and can act as GUI forefront for all these three tools. If you'd like to know more about those, check out our [comparison between Chocolatey and Windows Package Manager](https://www.makeuseof.com/chocolatey-vs-windows-package-manager/), and [how to install Scoop on Windows](https://www.makeuseof.com/windows-install-scoop/).

 Currently, WingetUI offers more than 4700 packages for Winget. If you combine the package list for all three package managers (including Chocolatey and [Scoop](https://www.makeuseof.com/windows-install-scoop/)), the numbers stand at a staggering 14000\.

 So, you can directly access 14000 packages without leaving the app and will have to rarely search the web. WingetUI can help you to manage all the installed packages, discover and install new ones, [batch install multiple packages](https://www.makeuseof.com/export-import-apps-winget-in-windows-11/), export or import package list, search for packages inside the app, and more.

 The fun doesn’t stop there. You can switch to dark mode in the app, and it even notifies you about the app updates whenever you launch the app and can even auto-update them. Furthermore, you can even view the package details, and its commands, and can share the packages with your friends.

## How to Download and Install WingetUI on Windows11

 WingetUI is available on GitHub and also has a dedicated website to keep you updated about the new features. However, you will find the download links on [GitHub](https://github.com/marticliment/WingetUI/releases/latest), Softpedia, and Uptodown only. Download the installer file from any of these hosts and then install it on your PC. Make note that WingetUI only works with Windows 10 and Windows 11 (64-bit versions only).

 After the installation completes, the app will ask you to select the package managers you want to use. Select the **Enable Winget** option for now, and click on the **Apply and Start WingetUI** button.

![Install WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-wingetui.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Manage App Packages Using WingetUI on Windows 11

 WingetUI divides the whole app into three sections: Discover Packages, Software Updates, and Installed packages. You can view all the available packages in the app using the Discover Packages section, while the Software Updates section list all the app that have a new version available. Lastly, the Installed Packages section allows you to manage the app packages on your PC.

 Here are the following things you can do using WingetUI:

### 1\. Browse List

 To browse the app list, click on the **Discover Packages** button on the top. WingetUI will list all the available packages with the source Winget. You will also see a counter indicating the total number of apps listed in the repository.

 Click on the search bar and type the name of the app package that you want to install on your PC. It will list all the available versions of the app package along with its package ID and version.

![Browse List in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/browse-list-in-wingetui.jpg)

### 2\. Install a Package

 To install a package, you will have to use the Discover Package tab:

1. After searching and locating the package, click on it to select it.
2. Then, right-click on it to open the context menu. Before starting the installation, you must configure the installation.
3. Select the **Package details** option from the context menu.  
![Install a Package in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui.jpg)
4. Check the **source** of the package. Also, check the **image gallery** to get an idea of the app’s UI.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Move down to the **Installation options**. Keep the **Skip hash check** and **Interactive installation** unchecked. If you enable the interactive installation, you will have to manually perform the installation which can take longer.

1. Some apps cannot install on your PC without administrator rights. So, select the **Run as admin** checkbox.  
![Install a Package in WingetUI 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-2.jpg)
2. You can also select a particular version of the app you are trying to install. Expand the **Version to install** dropdown list. You can select any version from here. Keep the **Ignore future updates for this package** option untouched.  
![Install a Package in WingetUI 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-3.jpg)
3. Next, you can pick the **package architecture**: x64, x86, or arm65, depending upon your OS and CPU architecture.
4. Lastly, pick the **Scope** of the package installation. If you want to do a machine-wide install, pick the **local machine** option. Or pick the **Current user** if you want to install the app only for one user profile.  
![Install a Package in WingetUI 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-4.jpg)
5. Click on the **Install** button. UAC will pop up. Click on the **Yes** button.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Install a Package in WingetUI 5](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/install-a-package-in-wingetui-5.jpg)

 You will see the installation status at the button of the WingetUI window. Windows will produce a notification when the installation completes.

### 2\. Uninstall a Package

 Repeat the following steps to uninstall a package using WingetUI:

1. Switch to the **Installed Packages** tab. Right-click on the package you want to uninstall.
2. Select the **Uninstall as administrator** option.  
![unInstall a Package in WingetUI 5](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/uninstall-a-package-in-wingetui-5.jpg)
3. UAC will pop up. Click on the **Yes** button.
4. WingetUI will remove the installed package.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Batch Install or Uninstall Packages

 Batch installation and uninstallation are a breeze with WingetUI. Here’s how to do it:

1. Individually select each package you want to install.
2. Then click on the **Install the selected packages** button on the top.  
![batch Install a Package in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/batch-install-a-package-in-wingetui.jpg)
3. WingetUI will install these apps one by one.

 To batch uninstall packages, repeat the following steps:

1. Switch to the **Installed Packages** tab. Then, click and select all the packages you want to remove from your PC.
2. Click on the **Uninstall selected packages** button to remove the selected packages one by one.  
![batch unInstall Packages in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/batch-uninstall-packages-in-wingetui.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 4\. Import Export Packages List

 You can create a custom package export list and store them in a JSON or Txt file. Here’s how:

1. Firstly, select all the packages you want to export either from the **Discover Packages** section or the **Installed Packages** section.
2. Then, click on the **Export selected packages to a file** option.  
![Export Packages List in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/export-packages-list-in-wingetui.jpg)
3. Enter a **name** for the export file and save it to any location on your PC.  
![Export Packages List in WingetUI 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/export-packages-list-in-wingetui-2.jpg)
4. You can later import this file to another PC or even your PC using Winget or Winget UI.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Repeat the following steps to import a Winget JSON file in WingetUI:

1. Switch to the **Discover Packages** section in the app.
2. Click on the **Import packages from a file** option.
3. **Browse** your PC for the Winget import file and select it. Click on the **Open** button.  
![import Packages List in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/import-packages-list-in-wingetui.jpg)
4. WingetUI will automatically start installing all the packages listed in the import file.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 5\. Check Software Updates

 Switch to the **Software Updates** section. WingetUI will list all the packages which have an update available. To update a single app, right-click on it and select the **Update as administrator** option.

![Check Software Updates in WingetUI](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/check-software-updates-in-wingetui.jpg)

 If you want to update all packages at once, click on the **tick mark** icon to select all the packages. Then, click on the **Update selected packages** button.

![Check Software Updates in WingetUI 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/check-software-updates-in-wingetui-2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## No More Terminal Woes

 WingetUi makes it easy for the average Joe to manage app packages on a Windows PC. There is a similar web-based GUI package manager called Winstall for batch-installing apps, but it only generates codes for it. You will have to manually run the commands in the Terminal. So, you can use WingetUI instead if you want zero interaction with Windows Terminal.

 If you have used Winget even once, you know that knowing the correct commands is of absolute importance if you want to avoid errors. But what if you had a GUI version of Winget? WingetUI is one such app that slaps a coat of UI on Winget. Curious? Let’s begin.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-the-complete-guide-to-creating-memorable-youtube-outros/"><u>[Updated] In 2024, The Complete Guide to Creating Memorable YouTube Outros</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-the-videographers-minecraft-6-proven-ways-to-document-gameplay/"><u>[Updated] In 2024, The Videographer's Minecraft 6 Proven Ways to Document Gameplay</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-livestream-landscape-analysis-fb-live-vs-yt-live-and-tweettv/"><u>2024 Approved Livestream Landscape Analysis FB LIVE Vs. YT Live & TweetTV</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-guide-to-the-compact-ps5-whats-new-in-pricing-release-plans-and-tech-specifications/"><u>Comprehensive Guide to the Compact PS5: What's New in Pricing, Release Plans & Tech Specifications</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unallocated-vram-on-hogwarts-legacy-platform/"><u>Correcting Unallocated VRAM on Hogwarts Legacy Platform</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1723808030911-desktop-icon-disappearance-troubles-heres-how-to-fix-them-for-windows-11/"><u>Desktop Icon Disappearance Troubles? Here's How to Fix Them for Windows 11!</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-advanced-methods-to-archive-your-whatsapp-chat/"><u>In 2024, Advanced Methods to Archive Your WhatsApp Chat</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Tecno Camon 20? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Vivo V30 Pro? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/key-to-the-past-windows-11s-historical-files-retrieval/"><u>Key to the Past: Windows 11’S Historical Files Retrieval</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-winservicesexe-a-comprehensive-guide/"><u>Mastering Winservices.exe: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-eliminating-not-attached-usb-error-from-your-virtualbox/"><u>Quick Guide: Eliminating 'Not Attached USB Error' From Your VirtualBox</u></a></li>
<li><a href="https://win11.techidaily.com/severing-non-primary-users-in-the-windows-ecosystem/"><u>Severing Non-Primary Users in the Windows Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-tricks-for-unfreezing-right-click-menus-on-windows/"><u>Top 6 Tricks for Unfreezing Right-Click Menus on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win-11s-bluetooth-woes-try-these-9-simple-cures/"><u>Win 11'S Bluetooth Woes? Try These 9 Simple Cures</u></a></li>
</ul></div>

