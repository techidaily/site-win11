---
title: "Integrating Volume Control: Windows 11'S Mixer Setup Guide"
date: 2024-11-13T18:23:56.750Z
updated: 2024-11-18T04:34:11.459Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Integrating Volume Control: Windows 11'S Mixer Setup Guide"
excerpt: "This Article Describes Integrating Volume Control: Windows 11'S Mixer Setup Guide"
keywords: W11 Volume Control,Windows Mixer Guide,Configuring Audio Levels,Win11 Sound Adjustment,Mastering Windows Audio,Speaker Management W11,Audio Mixer Setup Win11
thumbnail: https://thmb.techidaily.com/264f7e50d992f10f22f440e035402650c9e912cde2fed4f7c2aee477f6b93402.jpg
---

## Integrating Volume Control: Windows 11'S Mixer Setup Guide

 Remember the old volume mixer which you could access from the system tray notifications? Windows 11 seems to be missing that ever since its release. When you click on the Volume icon in the Action Center, you only see an option to change the sound output device. There are no means to directly access the volume mixer from there. But Microsoft isn’t done with the volume settings on Windows 11.

 In a new experimental feature, Microsoft is revamping the sound settings in the Action Center. You will be able to switch output devices and adjust the volume of each of the apps listed in the Volume Mixer. Wondering how to get the feature on your system? Here's how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Do You Need a Volume Mixer in Action Center?

 The present state of volume settings in Windows 11 is quite lackluster. You can only adjust the volume of the system and cycle between multiple audio devices. For opening any other settings, even something as trivial as a volume mixer: you need to dive deep into system sound settings.

 It is baffling how Microsoft missed something so crucial in Windows 11\. These missing volume settings gave rise to apps like[EarTrumpet](https://apps.microsoft.com/store/detail/9NBLGGH516XP?hl=en-us&gl=US&ranMID=24542&ranEAID=nOD%2FrLJHOac&ranSiteID=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&epi=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&activetab=pivot%3Aoverviewtab&ranMID=43674&ranEAID=RIg0ReKk7DI&ranSiteID=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&epi=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&irgwc=1&OCID=AID2200057%5Faff%5F7795%5F1243925&tduid=%28ir%5F%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00%29%287795%29%281243925%29%28RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ%29%28%29&irclickid=%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00) which offered rich sound customization settings. Along with that, you can even access the old volume mixers, adjust the sound levels of each app, and map shortcuts.

![Old Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/old-volume-settings-in-action-center.jpg)

 However, Microsoft is slowly identifying such missing features in Windows 11 and is adding an inbuilt solution for it. Recently,[Microsoft began testing an RGB lighting feature](https://www.makeuseof.com/enable-rgb-lighting-controls-windows-11/) that will eliminate the need for third-party customization apps. So, it is pretty clear that Microsoft wants to reduce the reliance on third-party apps for vital system features and tweaks.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868495/19272" target="_top" id="1868495">
  <img src="//a.impactradius-go.com/display-ad/19272-1868495" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868495/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

### 1\. Download the Latest Windows Insider Build and ViVeTool

 Currently, the volume mixer feature is an experimental feature hidden in Windows Insider build 25295\. So, you must install this Windows Insider build or a higher version to enable this feature. We recommend[using UUP Dump to download Windows Insider builds without subscribing to Windows Insider](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

 Microsoft recently expanded the Insider program with a new Canary channel, and it makes it difficult to downgrade to another channel. So, you can use UPP Dump to avoid this program and get builds directly.

 You will also need to download[ViVeTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) to enable the experimental volume mixer feature. It is a command-line tool that can both activate and deactivate experimental Windows features. However, extract the tool to an easily accessible location in the C drive.

### 2\. Enable Volume Mixer in Windows Using ViVeTool

After you have the ViVeTool ready, repeat the following steps:

1. Press the**Win** key to open the Start menu. Type**cmd** and press the**Ctrl + Shift + Enter** key.
2. UAC will pop up. Click on the**Yes** button to[open the Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Now, you need to navigate to the location where the ViVeTool folder exists. We extracted the tool to a folder named ViVeTool in**C** drive for easy access, and suggest you do the same. Otherwise, you have to change the directory multiple time to get to the tool’s folder.
4. Type the**cd C:\\** command and press the enter key to go to the main C drive directory.
5. After that, type**cd ViVeTool** command and press the enter key. Now, you are in the directory where ViVeTool executable file is present.
6. Type the following command and press the enter key to enable the hidden volume mixer:  
vivetool /enable /id:42106010
7. You will see a “**Successfully set feature configuration(s)** ” message. Type the**exit** command and press the enter key to close the command prompt window.  
![Enabling New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enabling-new-volume-settings-in-action-center.jpg)
8. Restart your system to allow the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049378/7443" target="_top" id="2049378">
  <img src="//a.impactradius-go.com/display-ad/7443-2049378" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006933/19272" target="_top" id="2006933">
  <img src="//a.impactradius-go.com/display-ad/19272-2006933" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006933/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Adjust Your Volume Like A Pro on Windows 11

 Windows 11 uprooted a lot of useful settings and features. Users resorted to registry hacks and third-party programs to fix this issue. However, the new volume mixer attempts to fix that to some extent. Microsoft might improve the volume mixer further to overshadow apps like EarTrumpet, but that’s a very slim possibility.

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
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-essential-camcorder-list-ultimate-expert-review/"><u>[New] 2024 Approved Essential Camcorder List – Ultimate Expert Review</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-androids-gratis-screen-capture-utility/"><u>[New] In 2024, Android's Gratis Screen Capture Utility</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-comprehensive-guide-to-recording-hulu-across-platforms/"><u>[New] In 2024, Comprehensive Guide to Recording Hulu Across Platforms</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-economical-mic-options-for-youtube-vloggers/"><u>[Updated] 2024 Approved Economical Mic Options for YouTube Vloggers</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-understanding-igtv-vs-youtube-a-comprehensive-feature-breakdown/"><u>[Updated] 2024 Approved Understanding IGTV Vs. YouTube A Comprehensive Feature Breakdown</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-unveiled-list-leading-top-10-facebook-video-downloaders-for-android-for-2024/"><u>[Updated] Unveiled List Leading Top 10 Facebook Video Downloaders for Android for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-realme-gt-5-pro-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Realme GT 5 Pro to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/a-beginners-blueprint-for-safelisting-your-email-address-efficiently/"><u>A Beginner's Blueprint for Safelisting Your Email Address Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-system-performance-4-strategies-for-managing-disk-on-windows-11/"><u>Elevate System Performance: 4 Strategies for Managing Disk on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-clear-sound-fixing-xbox-mic-in-windows/"><u>Ensuring Clear Sound: Fixing Xbox Mic in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/flickering-wi-fi-mouse-issues-solutions-for-windows-users/"><u>Flickering Wi-Fi Mouse Issues - Solutions for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reuse-powertoys-configurations-elsewhere/"><u>How to Reuse PowerToys Configurations Elsewhere</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-google-chrome-from-tracking-your-location-on-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop Google Chrome from Tracking Your Location On Oppo A1 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-laptop-functionality-post-monitor-hookup/"><u>Optimize Laptop Functionality Post-Monitor Hookup</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unstable-operating-system-with-df-gameplay/"><u>Overcoming Unstable Operating System with DF Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/prohibiting-date-manipulation-on-windows-machines/"><u>Prohibiting Date Manipulation on Windows Machines</u></a></li>
<li><a href="https://win11.techidaily.com/refurbish-old-films-madvrs-power-for-windows-users/"><u>Refurbish Old Films: MadVR's Power for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-navigating-comic-files-in-win11/"><u>The Essentials of Navigating Comic Files in Win11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Lava Blaze Curve 5G? | Dr.fone</u></a></li>
</ul></div>

