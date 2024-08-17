---
title: A Step-by-Step Walkthrough for Installing Apps via WPM on Windows 11
date: 2024-08-15T23:26:23.349Z
updated: 2024-08-16T23:26:23.349Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Step-by-Step Walkthrough for Installing Apps via WPM on Windows 11
excerpt: This Article Describes A Step-by-Step Walkthrough for Installing Apps via WPM on Windows 11
keywords: Windows 11 App Installs Guide,WPM App Setup on Windows,WPM App Installation Steps,Using WPM for Windows Apps,Simple WPM App Installation,Installing Apps via WPM Win11,Step-by-Step WPM App Install
thumbnail: https://thmb.techidaily.com/c465b3961d0e8ae791649e84e8128b1614e8e09e935ed979e13eb915c45489fc.jpg
---

## A Step-by-Step Walkthrough for Installing Apps via WPM on Windows 11

 As Windows has developed over the years, we’ve seen Microsoft introduce some of Linux’s functionality into the Windows ecosystem. In addition to Windows 10 and 11 supporting a Linux subsystem through WSL 2, they also feature a package manager called the Windows Package Manager (or winget for short).

 So what exactly is the Windows Package Manager, and how do you use it? Read on as we answer all of your burning questions below.

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## What Is the Windows Package Manager?

 The Windows Package Manager, or winget as it is commonly referred to, is Microsoft’s version of a Linux-style package manager. Winget was released in 2020 as an open-source command-line utility package manager and contains a wide range of available applications for users to install from. Like other widely used package managers, Microsoft has made sure that the Windows Package Manager is free and available on GitHub.

![remove reinstall microsoft store windows 11](https://thmb.techidaily.com/99bb08ac4320921b1ffab3e5a5166b4c117aac2cf8ab3a2d0b2277eb6b26d486.jpg)

 By using the Windows Package Manager, you can easily install, update, and delete applications with just a single command in the terminal. Say goodbye to the days of downloading setup files and manually installing each application.

 Winget utilizes a YAML package manifest format that makes it easy to understand and configure. Developers typically use the YAML manifest format to bundle their applications to be compatible with the Windows Package Manager.

 Previously, Windows users had to rely on Chocolatey—a third-party package manager specialized for Windows OS. Chocolatey is quite powerful and widely adopted by the larger Windows fraternity. On the other hand, most Windows users are not familiar or comfortable with the Windows Package Manager yet; we hope this guide will help change that.

## How to Set Up Windows Package Manager on Windows 11

 The Windows Package Manager does not come pre-installed on Windows, so you’ll have to download it manually. Fortunately, the installation process is straightforward and shouldn’t pose any hurdles.

 Microsoft requires your Windows system to run Windows 10 1709 or later to use winget. You will also have to [log in using your Microsoft Account](https://www.makeuseof.com/windows-switch-local-account-to-microsoft-account/) and ensure you’re logged in on the Microsoft Store app as well.

 There are two main ways of installing the Windows Package Manager on Windows 11.

### How to Install Winget Using the Microsoft Store

 The easiest way to install the Windows Package Manager is through the Microsoft Store. You can download the Windows Package Manager through Microsoft’s official App Installer to do so:

1. Launch the**Microsoft Store** using the**Start menu** .
2. Search for**App Installer** and select the best match.  
![app installer win11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/app-installer.jpg)
3. Click on the**Install** button if you see it. Otherwise,**App Installer** already exists on your PC, and you will just have to make sure it’s updated.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### How to Install Winget Through PowerShell

 If you’re having issues in the Microsoft Store, you should consider installing winget using Windows PowerShell. Once you’ve connected to the internet, follow the below steps:

1. From the**Start** menu, search for**PowerShell** , and select**Run as administrator** .
2. In the command line, paste the below command and press**Enter**  
`Invoke-WebRequest -Uri https://aka.ms/winget -OutFile winget.zip; Expand-Archive winget.zip -DestinationPath $Env:ProgramFiles\WindowsPowerShell\Modules\`
3. Once the installation is completed, type the following command and press**Enter** to verify your installation.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Use Winget on Windows 11

 Now that you’ve set up winget, you’ll have to learn how to use commands associated with the winget tool, including downloading, config configuring, and viewing installed applications.

### 1\. How to Download New Applications

 There’s a vast range of available applications within winget, and you can download apps such as Google Chrome, 7-Zip, etc.

To download an application using winget, use the following command:

`winget install <APP_NAME>`

### 2\. How to Browse for Applications

 If you’re looking for a new app to install but don’t know how to browse the available apps, you can use the search feature of winget. One method is to use the search command of winget within the command line. Enter a search query with the below command, and you’ll get a list of available apps that satisfy your search criteria.

![winget search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-search.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

For example, to search for zipping programs, you can type:

`winget search zip`

 Alternatively, you can use a [third-party tool](https://winstall.app/) that provides an easy-to-use user interface for winget.

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
### 3\. How to View Installed Applications

 You can view applications that have been installed on your PC through:

`winget list`

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 4\. How to View Application Details

![winget show](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/winget-show.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-top-action-capturing-software-guide/"><u>[New] 2024 Approved  Top Action-Capturing Software Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-capturing-moments-expert-tips-on-downloading-social-media-lives/"><u>[Updated] 2024 Approved  Capturing Moments  Expert Tips on Downloading Social Media Lives</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-13-key-tactics-for-enhanced-visibility-in-facebook-videography/"><u>[Updated] In 2024, 13 Key Tactics for Enhanced Visibility in Facebook Videography</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-interrupt-free-live-streaming-your-2023-solution-to-facebooks-glitches/"><u>[Updated] In 2024, Interrupt-Free Live Streaming  Your 2023 Solution to Facebook's Glitches</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-flight-finesse-crafting-the-top-10-endurance-drone-lineup/"><u>2024 Approved  Flight Finesse  Crafting the Top 10 Endurance Drone Lineup</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-niche-networking-smaller-bizs-video-strategies/"><u>2024 Approved  Niche Networking  Smaller Biz's Video Strategies</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-music-files-on-honor-magic-6-by-fonelab-android-recover-music/"><u>Complete guide for recovering music files on Honor Magic 6</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-configuration-with-microsofts-pc-manager-on-w11/"><u>Conquer Configuration with Microsoft's PC Manager on W11</u></a></li>
<li><a href="https://win11.techidaily.com/consistent-connections-avoiding-disruptions-in-windows/"><u>Consistent Connections: Avoiding Disruptions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-unique-snap-configurations-in-win-os/"><u>Crafting Unique Snap Configurations in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-win-11-boot-drive-essential-tips-for-3-techniques/"><u>Creating a Win 11 Boot Drive – Essential Tips for 3 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-usefulness-of-pagefilesys-backup-storage/"><u>Decoding Windows’ Usefulness of Pagefile.sys Backup Storage</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/1722705990081-delving-into-the-world-of-the-acer-chromebook-prise-and-it-can-be-reused-for-other-projects-that-require-similar-functionality/"><u>Delving Into the World of the Acer Chromebook Prise, and It Can Be Reused for Other Projects that Require Similar Functionality.</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/direct-playback-of-fb-videos-on-home-entertainment-systems/"><u>Direct Playback of FB Videos on Home Entertainment Systems</u></a></li>
<li><a href="https://win11.techidaily.com/end-hibernation-hurdles-with-easy-fixes-for-win/"><u>End Hibernation Hurdles with Easy Fixes for Win</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-pc-display-with-best-time-clock-screen-savers/"><u>Enhance PC Display with Best Time Clock Screen Savers</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-battery-status-notifications-on-windows-os/"><u>Enhancing Battery Status Notifications on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-shared-connectivity-options-google-versus-windows/"><u>Exploring Shared Connectivity Options: Google Versus Windows</u></a></li>
<li><a href="https://win11.techidaily.com/high-res-quests-ultimate-guide-to-playing-adventures-in-hd-using-scummvm/"><u>High-Res Quests: Ultimate Guide to Playing Adventures in HD Using ScummVM</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Motorola Moto G14 | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-poco-m6-pro-4g-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Poco M6 Pro 4G Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-google-pixel-8-device-by-drfone-android/"><u>In 2024, What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Google Pixel 8 Device</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixed-overcoming-application-crash-error/"><u>Mastering the Art of Fixed: Overcoming 'Application Crash' Error</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-error-correction-for-rpc-failures/"><u>Mastering Windows Error Correction for RPC Failures</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-teams-screen-share-issues-quick-fixes/"><u>Microsoft Teams Screen Share Issues: Quick Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-chrome-file-uploading-woes-a-guide-for-windows-devices/"><u>Navigate Chrome File Uploading Woes: A Guide for Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-package-open-failures-in-win11win10-systems/"><u>Navigating Package Open Failures in Win11/Win10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unwanted-keystrokes-during-typing/"><u>Preventing Unwanted Keystrokes During Typing</u></a></li>
<li><a href="https://win11.techidaily.com/regain-control-fixing-wi-fi-mouse-malfunctions-in-windows/"><u>Regain Control: Fixing Wi-Fi Mouse Malfunctions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-external-monitor-not-responding-in-windows-os/"><u>Resolving External Monitor Not Responding in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/steam-and-internet-connectivity-woes-on-pc-heres-a-fix/"><u>Steam & Internet Connectivity Woes on PC? Here's a Fix</u></a></li>
<li><a href="https://win11.techidaily.com/stop-spacing-out-sounds-fixes-to-unmute-keyboard-volume/"><u>Stop Spacing Out Sounds: Fixes to Unmute Keyboard Volume</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-setting-up-bings-chat-for-windows-11-users/"><u>Streamline Setting Up Bing's Chat for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-sync-windows-plus-android-via-flow-app/"><u>Streamlining Sync: Windows + Android via Flow App</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remediation-for-elusive-obs-studio-issue-on-win-11-pcs/"><u>Swift Remediation for Elusive OBS Studio Issue on Win 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-network-link-disruptions-in-winmc-minecraft/"><u>Tackling Network Link Disruptions in WinMC Minecraft</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-utilizing-qr-scanners-in-windows/"><u>The Ultimate Guide to Utilizing QR Scanners in Windows</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-oneplus-nord-n30-se-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset OnePlus Nord N30 SE? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-overcoming-a-non-functional-search-in-windows-11s-environment/"><u>Tips for Overcoming a Non-Functional Search in Windows 11’S Environment</u></a></li>
<li><a href="https://media-tips.techidaily.com/transforming-video-experience-top-tools-for-adjusting-audio-bitrates/"><u>Transforming Video Experience: Top Tools for Adjusting Audio Bitrates</u></a></li>
<li><a href="https://win11.techidaily.com/transition-to-open-source-enable-linux-subsystem-for-windows/"><u>Transition to Open Source: Enable Linux Subsystem for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/typingpros-guide-to-swift-typing-using-typingaid/"><u>TypingPros Guide to Swift Typing Using TypingAid</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-new-browsing-potential-with-gesture-controls-in-microsoft-written-by-ai/"><u>Unlocking New Browsing Potential with Gesture Controls in Microsoft' Written by AI</u></a></li>
<li><a href="https://win11.techidaily.com/unravel-windows-mysteries-get-the-support-you-need/"><u>Unravel Windows Mysteries: Get the Support You Need!</u></a></li>
<li><a href="https://win11.techidaily.com/unyielding-security-seven-ways-to-shield-your-system/"><u>Unyielding Security: Seven Ways to Shield Your System</u></a></li>
<li><a href="https://win11.techidaily.com/windows-define-custom-idle-timeframe/"><u>Windows: Define Custom Idle Timeframe</u></a></li>
</ul></div>
