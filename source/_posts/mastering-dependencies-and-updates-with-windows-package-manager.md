---
title: Mastering Dependencies & Updates with Windows Package Manager
date: 2024-10-10T20:01:40.711Z
updated: 2024-10-15T17:50:54.414Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Dependencies & Updates with Windows Package Manager
excerpt: This Article Describes Mastering Dependencies & Updates with Windows Package Manager
keywords: PM Dependency Mastery,Win Update Strategies,Managing WPM Packages,Updating System Tools,Dependencies in WPM,Windows Package Control,Optimizing WPM Deps
thumbnail: https://thmb.techidaily.com/cbb1e3102bf892cff8d3ec0a8653b920867c497d12f1be8e2ab6e11d350e85ee.jpg
---

## Mastering Dependencies & Updates with Windows Package Manager

 As Windows has developed over the years, we’ve seen Microsoft introduce some of Linux’s functionality into the Windows ecosystem. In addition to Windows 10 and 11 supporting a Linux subsystem through WSL 2, they also feature a package manager called the Windows Package Manager (or winget for short).

 So what exactly is the Windows Package Manager, and how do you use it? Read on as we answer all of your burning questions below.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is a Package Manager?

 All modern apps and any projects that you build will utilize existing frameworks, libraries, and tools. If you’re building a simple React app, you’re going to require Node.js, ReactJS, and other libraries or tools for your project to function correctly. The underlying third-party software that essentially helps your project function is called dependencies.

 As you can imagine, managing the installation and updation of multiple dependencies within a project can become quite frustrating. You also need to make sure that your system is compatible with third-party software. If you were to integrate and update each third-party software manually, you’d be wasting a good chunk of your valuable time managing the software dependencies.

 To solve this problem (among others), developers came up with the ingenious idea of a package manager—a single tool that can manage all your project dependencies. Package managers typically perform several essential features such as:

* Finding the correct source files for your platform.
* Ensuring source files are free of malware and other security vulnerabilities.
* Integrating dependencies into your project.
* Allowing seamless installation, updation, and removal of software dependencies.

 Package managers also have a vast catalog of tools you can choose from and install with just a single command on the terminal.

Some examples of popular package managers include:

* Homebrew.
* Node Package Manager (NPM).
* Yarn.
* Advanced Packaging Tool (APT).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Is the Windows Package Manager?

 The Windows Package Manager, or winget as it is commonly referred to, is Microsoft’s version of a Linux-style package manager. Winget was released in 2020 as an open-source command-line utility package manager and contains a wide range of available applications for users to install from. Like other widely used package managers, Microsoft has made sure that the Windows Package Manager is free and available on GitHub.

![remove reinstall microsoft store windows 11](https://thmb.techidaily.com/99bb08ac4320921b1ffab3e5a5166b4c117aac2cf8ab3a2d0b2277eb6b26d486.jpg)

 By using the Windows Package Manager, you can easily install, update, and delete applications with just a single command in the terminal. Say goodbye to the days of downloading setup files and manually installing each application.

 Winget utilizes a YAML package manifest format that makes it easy to understand and configure. Developers typically use the YAML manifest format to bundle their applications to be compatible with the Windows Package Manager.

 Previously, Windows users had to rely on Chocolatey—a third-party package manager specialized for Windows OS. Chocolatey is quite powerful and widely adopted by the larger Windows fraternity. On the other hand, most Windows users are not familiar or comfortable with the Windows Package Manager yet; we hope this guide will help change that.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016134/19272" target="_top" id="2016134">
  <img src="//a.impactradius-go.com/display-ad/19272-2016134" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016134/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Set Up Windows Package Manager on Windows 11

 The Windows Package Manager does not come pre-installed on Windows, so you’ll have to download it manually. Fortunately, the installation process is straightforward and shouldn’t pose any hurdles.

 Microsoft requires your Windows system to run Windows 10 1709 or later to use winget. You will also have to[log in using your Microsoft Account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) and ensure you’re logged in on the Microsoft Store app as well.

 There are two main ways of installing the Windows Package Manager on Windows 11.

### How to Install Winget Using the Microsoft Store

 The easiest way to install the Windows Package Manager is through the Microsoft Store. You can download the Windows Package Manager through Microsoft’s official App Installer to do so:

1. Launch the**Microsoft Store** using the**Start menu** .
2. Search for**App Installer** and select the best match.  
![app installer win11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-installer.jpg)
3. Click on the**Install** button if you see it. Otherwise,**App Installer** already exists on your PC, and you will just have to make sure it’s updated.

### How to Install Winget Through PowerShell

 If you’re having issues in the Microsoft Store, you should consider installing winget using Windows PowerShell. Once you’ve connected to the internet, follow the below steps:

1. From the**Start** menu, search for**PowerShell** , and select**Run as administrator** .
2. In the command line, paste the below command and press**Enter**  
`Invoke-WebRequest -Uri https://aka.ms/winget -OutFile winget.zip; Expand-Archive winget.zip -DestinationPath $Env:ProgramFiles\WindowsPowerShell\Modules\`
3. Once the installation is completed, type the following command and press**Enter** to verify your installation.

## How to Use Winget on Windows 11

 Now that you’ve set up winget, you’ll have to learn how to use commands associated with the winget tool, including downloading, config configuring, and viewing installed applications.

### 1\. How to Download New Applications

 There’s a vast range of available applications within winget, and you can download apps such as Google Chrome, 7-Zip, etc.

To download an application using winget, use the following command:

`winget install <APP_NAME>`

### 2\. How to Browse for Applications

 If you’re looking for a new app to install but don’t know how to browse the available apps, you can use the search feature of winget. One method is to use the search command of winget within the command line. Enter a search query with the below command, and you’ll get a list of available apps that satisfy your search criteria.

![winget search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-search.jpg)

For example, to search for zipping programs, you can type:

`winget search zip`

 Alternatively, you can use a[third-party tool](https://winstall.app/) that provides an easy-to-use user interface for winget.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115951/19272" target="_top" id="2115951">
  <img src="//a.impactradius-go.com/display-ad/19272-2115951" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115951/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. How to View Installed Applications

 You can view applications that have been installed on your PC through:

`winget list`

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080312/19272" target="_top" id="2080312">
  <img src="//a.impactradius-go.com/display-ad/19272-2080312" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080312/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 4\. How to View Application Details

![winget show](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-show.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123749/7443" target="_top" id="2123749">
  <img src="//a.impactradius-go.com/display-ad/7443-2123749" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123749/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To look into the installation details and software version of a specific app, you can use the following command:

`winget show <APP_NAME>`

## Are Package Managers Worth the Hassle on Windows?

 Winget is incredible at installing applications on your Windows 11 PC. You no longer need to hunt for malware-free download links on the internet; simply open up a terminal and download the application you need via winget.

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
<li><a href="https://fox-boxes.techidaily.com/updated-integrating-color-grading-techniques-with-luts-for-2024/"><u>[Updated] Integrating Color Grading Techniques with Luts for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-personal-growth-reflections-for-digital-platforms/"><u>[Updated] Personal Growth Reflections for Digital Platforms</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-5-creative-tiktok-caption-ideas-for-maximum-impact/"><u>2024 Approved 5 Creative TikTok Caption Ideas for Maximum Impact</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-gpos-on-single-user-accounts-using-the-latest-windows-oses/"><u>Configuring GPOs on Single-User Accounts Using the Latest Windows OSes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/delving-into-digital-overlay-technologies/"><u>Delving Into Digital Overlay Technologies</u></a></li>
<li><a href="https://vp-tips.techidaily.com/digiartys-final-user-license-agreement-for-winxdvd-secure-your-legal-rights/"><u>Digiarty's Final User License Agreement for WinXDVD - Secure Your Legal Rights</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-icon-clarity-fix-window-11-diminution/"><u>Enhance Icon Clarity: Fix Window 11 Diminution</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-get-started-comprehensive-linksys-wusb6300-drivers-setup-and-downloads/"><u>How to Get Started: Comprehensive Linksys WUSB6300 Drivers Setup and Downloads</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-saving-your-focus-a-guide-to-quieting-naysayers-on-google-video-calls/"><u>In 2024, Saving Your Focus A Guide to Quieting Naysayers on Google Video Calls</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-top-5-ps2-simulators-to-transform-your-ios-gaming/"><u>In 2024, Top 5 PS2 Simulators to Transform Your iOS Gaming</u></a></li>
<li><a href="https://discover-fantastic.techidaily.com/jalan-diapedakan-untuk-mungkin-kembali-dataset-apapun-di-android-atau-ios-setelah-reset-pabrik/"><u>Jalan Diapedakan Untuk Mungkin Kembali Dataset Apapun Di Android Atau iOS Setelah Reset Pabrik</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-disguising-taskbar-search-in-windows-11/"><u>Mastery: Disguising Taskbar Search in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-update-anomalies-steps-for-success/"><u>Overcoming Windows Update Anomalies: Steps for Success</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-the-not-valid-warning-in-win11/"><u>Resolving the ‘Not Valid’ Warning in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-update-failure-winerror-x8019/"><u>Resolving Update Failure - WinError X8019</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-restore-disrupted-remote-play-service/"><u>Steps to Restore Disrupted Remote Play Service</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-minimize-cpu-load-from-tiworkerexe-applications/"><u>Techniques to Minimize CPU Load From TiWorker.exe Applications</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ultimate-selection-for-top-tier-hdr-cameras/"><u>Ultimate Selection for Top-Tier HDR Cameras</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-a-compreenas-complete-guide-for-leveraging-hdr-capabilities/"><u>Windows 11: A Compreenas Complete Guide for Leveraging HDR Capabilities</u></a></li>
</ul></div>

