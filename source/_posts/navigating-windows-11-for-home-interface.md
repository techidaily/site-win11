---
title: Navigating Windows 11 for Home Interface
date: 2024-09-11T09:43:31.574Z
updated: 2024-09-12T09:43:31.574Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Windows 11 for Home Interface
excerpt: This Article Describes Navigating Windows 11 for Home Interface
keywords: Win11 Home Setup,Win11 UI Guide,Win11 Interior Tips,User Interface Win11,Navigate Win11 Basics,Windows 11 Interface Usage,Home Win11 Navigation
thumbnail: https://thmb.techidaily.com/0e72ae7670739d2aa724a5c1676e3ea5eb7af36bcb7980843f57c620d01dbd2b.jpg
---

## Navigating Windows 11 for Home Interface

 Microsoft introduced the Settings app in Windows 8 and has since worked to improve the overall usability of the app. Its design has undergone several changes and the new one in Windows 11 looks much better due to the better UI and feature organization.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What's Wrong With the Old Settings App?

 The old Settings app directly opens the System section when you launch it. This section contains the most common settings like Display, Sound, Storage, Troubleshooting, and more. But you will still have to use the left side menu to access common settings such as Network, Personalization, Bluetooth, One Drive, and more.

![Current Settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/current-settings-app-1.jpg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134503/19576" target="_top" id="2134503">
  <img src="//a.impactradius-go.com/display-ad/19576-2134503" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134503/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Microsoft noticed this issue and created a new Home section in the revamped Settings app. At the time of writing, you can only find this new Settings app in the Windows Insider program.

 The new Home section brings all the common settings under one roof, so the users don't have to dive deep into the Settings app to change a network or personalization setting.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135353/19272" target="_top" id="2135353">
  <img src="//a.impactradius-go.com/display-ad/19272-2135353" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135353/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable the Home Section in the Settings App

 Repeat the following steps to enable and use the Home section in the Settings App:

### 1\. Download the Latest Insider Build and ViveTool

 The new Settings app with a Home section is available in the Windows Insider Dev build 23493\. So, you must update your PC enrolled in the Dev channel to the build version 23493 or above. If you don't want to enroll your PC into the Windows Insider program or want to try out the build in a virtual machine, there’s an easy way.

 You can [use UPP DUMP to download Windows Insider builds without enrolling in the Windows Insider program](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/). After the download completes, you will have to perform an in-place upgrade or create a bootable USB drive to install the Dev build on your PC.

 The enhanced Settings app with the included Home section isn't directly available in build 243943\. So, you must use Vivetool to enable the experimental feature. All you need to do is [download ViveTool from GitHub](https://github.com/thebookisclosed/ViVe/releases).

 After the download completes, navigate to the download location using File Explorer and extract the contents of the archive to a folder named "**Vive**". Move the folder containing the Vivetool to the **C** drive.

### 2\. Enable the Home Section in the Settings App

 After updating your Windows PC and installing Vivetool, repeat the following steps:

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **cmd** in the text box and press the **Ctrl + Shift + Enter** keys simultaneously.
2. The User Account Control window will pop up. Click on the **Yes** button.
3. First, you need to switch to the drive where you extracted the Vivetool. Type **cd c:\\** in the Command Prompt window and press the **Enter** key to execute the command.
4. Now, you need to switch to the folder where Vivetool is present. Since we extracted the tool to a folder named “**Vive**” our command becomes: **cd vive**.
5. Type **vivetool** and press the **Enter** key to check if the tool runs perfectly or not.  
![Enable the New Home Section in the Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app.jpg)
6. Now, type the following commands and press the **Enter** key to execute them one by one:  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135367/19272" target="_top" id="2135367">
  <img src="//a.impactradius-go.com/display-ad/19272-2135367" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135367/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`vivetool /enable /id:42058345  
vivetool /enable /id:42058313`
7. **Close** the Command Prompt window.  
![Enable the New Home Section in the Settings App 2-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/enable-the-new-home-section-in-the-settings-app-2-1.jpg)
8. **Restart** your PC to apply the changes made by the Vivetool in the Settings app.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136612/26400" target="_top" id="2136612">
  <img src="//a.impactradius-go.com/display-ad/26400-2136612" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136612/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Does the Enhanced Settings App Look Like?

 We compared the experimental and the old Settings app, and there are a few noticeable changes. For example, you automatically land on the Home section every time you open the enhanced Settings app.

 As a result, it is easier to access commonly uses settings. For instance, the top section shows your current internet connection, alongside a Windows Update check button.

![New and old settings app side by side-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-and-old-settings-app-side-by-side-1.jpg)

 Below that, there is a card that displays the recommended settings. You also get a bird’s eye view of the total available storage space in your Outlook account. There’s also a much-needed personalization card that you can use to change the themes and color mode of your Windows PC.

 If you haven’t completed a crucial security setup for your Microsoft account, you will see a reminder on the Home Page. Apart from that, Microsoft brazenly promotes its Microsoft service as a separate card. You cannot rearrange or remove tiles, so you are stuck with the layout and the promotional stuff from Microsoft.

![New home section in the settings app-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/new-home-section-in-the-settings-app-1.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123470/16836" target="_top" id="2123470">
  <img src="//a.impactradius-go.com/display-ad/16836-2123470" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123470/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Still, it is a much-needed overhaul from the existing Settings app, which will improve the overall user experience. Microsoft is also trying out a Home section in the File Explorer app.

## A Revamped Settings App on Windows

 Microsoft’s take on the new Home section in the Settings app is a change we would definitely want to see in the stable builds in the upcoming months. But there are major changes arriving to the File Explorer and other Windows apps like the Photos app which recently got an update to support the dark mode and some zoom and usability improvements.

 However, it isn't just a cosmetic change because many utilities and Control Panel items are migrated to the Settings app. Microsoft also released a different version of the Settings app which incorporates a new Home section and a layout that will help you access the most commonly used settings. Let’s learn how to enable it on your PC.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-recordings.techidaily.com/new-avoiding-unwanted-accounts-on-insta-for-2024/"><u>[New] Avoiding Unwanted Accounts on Insta for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-a-bite-into-tiktoks-most-engaging-dishes/"><u>[New] In 2024, A Bite Into TikTok's Most Engaging Dishes</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-unveiling-the-top-8-instagram-schedulers-for-iphone-and-android-users-for-2024/"><u>[New] Unveiling the Top 8 Instagram Schedulers for iPhone and Android Users for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-top-3-voice-capturing-ipad-apps-reviewed/"><u>[Updated] 2024 Approved TOP 3 Voice Capturing iPad Apps Reviewed</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-discovering-your-favorite-makeup-vloggers-on-youtube-for-2024/"><u>[Updated] Discovering Your Favorite Makeup Vloggers on YouTube for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-quick-fixes-the-hands-on-guide-to-generating-timely-captions-on-fb-media-for-2024/"><u>[Updated] Quick Fixes The Hands-On Guide to Generating Timely Captions on FB Media for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-elevate-your-articles-with-proper-slug-lines/"><u>2024 Approved Elevate Your Articles with Proper Slug Lines</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-tips-for-dealing-with-system-calls-in-windows/"><u>Comprehensive Tips for Dealing With System Calls in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-win11s-systray-with-caps-lock-and-num-key-icons/"><u>Customizing Win11's SysTray with Caps Lock & Num Key Icons</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-how-to-bypass-nubia-red-magic-8s-pro-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass Nubia Red Magic 8S Pro FRP Android 10/11/12/13</u></a></li>
<li><a href="https://tech-revival.techidaily.com/explore-6-economical-open-source-options-similar-to-phi-era-for-your-projects/"><u>Explore 6 Economical Open Source Options Similar to Phi Era for Your Projects</u></a></li>
<li><a href="https://win11.techidaily.com/file-organization-breakthroughs-with-simultaneous-window-folders/"><u>File Organization Breakthroughs with Simultaneous Window Folders</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-netflix-app-when-it-stops-working-in-windows/"><u>How to Fix the Netflix App When It Stops Working in Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-videos-from-asus-rog-phone-8-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Videos from Asus ROG Phone 8 to iPad | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-graphics-enhancement-in-windows-11s-shielded-browsing/"><u>Innovative Graphics Enhancement in Windows 11'S Shielded Browsing</u></a></li>
<li><a href="https://win11.techidaily.com/is-the-windows-settings-app-crashing-try-these-fixes/"><u>Is the Windows Settings App Crashing? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-customizing-desktop-pictures-in-windows/"><u>Master the Art of Customizing Desktop Pictures in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-error-correction-windows-11-wow-mishaps/"><u>Mastering Error Correction: Windows 11 WoW Mishaps</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-speech-to-text-the-whisper-desktop-way/"><u>Mastering Speech-to-Text: The Whisper Desktop Way</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-reactivate-nonfunctional-nvidia-cp/"><u>Methods to Reactivate Nonfunctional Nvidia CP</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-ai-hub-revolutionizing-retail-shopping/"><u>Microsoft AI Hub: Revolutionizing Retail Shopping</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-epic-launcher-errors-a-windows-fix-guide/"><u>Overcoming Epic Launcher Errors: A Windows Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-store-error-code-x00000000/"><u>Overcoming Windows 11 Store Error Code X00000000</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-resetting-synapse-for-smooth-operation/"><u>Quick Guide: Resetting Synapse for Smooth Operation</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-for-windows-11s-software-folder-restarts/"><u>Quick-Fix Guide for Windows 11'S Software Folder Restarts</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cmd-prompt-lack-of-admin-privileges/"><u>Resolving Cmd Prompt Lack of Admin Privileges</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-d3d11-compatible-graphics-errors-in-win11win10/"><u>Resolving D3D11 Compatible Graphics Errors in Win11/Win10</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-disk-read-error-on-windows-os/"><u>Resolving Disk Read Error on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-installing-kali-into-your-windows-ecosystem/"><u>Step by Step: Installing Kali Into Your Windows Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-dns-flushing-in-modern-windows/"><u>Step-by-Step DNS Flushing in Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-setting-up-and-using-microsofts-code-assistant/"><u>Step-by-Step: Setting Up and Using Microsoft's Code Assistant</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-the-roblox-must-close-warning-in-windows/"><u>Steps to Eliminate the 'Roblox Must Close' Warning in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/stream-gaming-secrets-integrating-intelligence-with-intel/"><u>Stream Gaming Secrets: Integrating Intelligence with Intel</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-background-services-on-windows/"><u>Streamlining Background Services on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-camera-non-storage-feedback/"><u>Tackling Windows Camera Non-Storage Feedback</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-companion-for-new-diablo-players/"><u>The Essential Companion for New Diablo Players</u></a></li>
<li><a href="https://win11.techidaily.com/the-skillful-technique-to-obscure-window-11-search/"><u>The Skillful Technique to Obscure Window 11 Search</u></a></li>
<li><a href="https://win11.techidaily.com/track-down-absent-control-settings-on-your-new-pc/"><u>Track Down Absent Control Settings on Your New PC</u></a></li>
<li><a href="https://win11.techidaily.com/transform-workflow-efficiency-mastering-flow-launcher-basics/"><u>Transform Workflow Efficiency: Mastering Flow Launcher Basics</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-persistent-windows-volume-mixer/"><u>Troubleshooting Non-Persistent Windows Volume Mixer</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-error-0x800f082f-with-dism/"><u>Troubleshooting Windows Error 0X800F082F with DISM</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-mastering-github-desktop-for-windows-based-developers/"><u>Tutorial: Mastering GitHub Desktop for Windows-Based Developers</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-giants-identifying-heavy-disk-space-usage-on-pcs/"><u>Uncovering Giants: Identifying Heavy Disk Space Usage on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unearthing-the-hidden-potential-of-windows-monitoring-systems/"><u>Unearthing the Hidden Potential of Windows Monitoring Systems</u></a></li>
<li><a href="https://win11.techidaily.com/win-operating-system-customize-how-you-handle-file-deletions/"><u>Win Operating System: Customize How You Handle File Deletions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    