---
title: Activating the Action Center Volume Mixing in Windows 11
date: 2024-08-15T23:15:20.163Z
updated: 2024-08-16T23:15:20.163Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activating the Action Center Volume Mixing in Windows 11
excerpt: This Article Describes Activating the Action Center Volume Mixing in Windows 11
keywords: Window 11 Sound Control,Activate Windows 11 Mixer,Enable Windows 11 Actions,Windows 11 Volume Mute,Adjust Windows 11 Mixer,Windows 11 Action Center,Toggle Windows 11 Sound
thumbnail: https://thmb.techidaily.com/acf1543a08c93a8277bd32ca8ca0045c1e81ebd5061ccbafdfe3582cd05fb8bf.jpg
---

## Activating the Action Center Volume Mixing in Windows 11

 Remember the old volume mixer which you could access from the system tray notifications? Windows 11 seems to be missing that ever since its release. When you click on the Volume icon in the Action Center, you only see an option to change the sound output device. There are no means to directly access the volume mixer from there. But Microsoft isn’t done with the volume settings on Windows 11.

 In a new experimental feature, Microsoft is revamping the sound settings in the Action Center. You will be able to switch output devices and adjust the volume of each of the apps listed in the Volume Mixer. Wondering how to get the feature on your system? Here's how.

## Why Do You Need a Volume Mixer in Action Center?

 The present state of volume settings in Windows 11 is quite lackluster. You can only adjust the volume of the system and cycle between multiple audio devices. For opening any other settings, even something as trivial as a volume mixer: you need to dive deep into system sound settings.

 It is baffling how Microsoft missed something so crucial in Windows 11\. These missing volume settings gave rise to apps like [EarTrumpet](https://apps.microsoft.com/store/detail/9NBLGGH516XP?hl=en-us&gl=US&ranMID=24542&ranEAID=nOD%2FrLJHOac&ranSiteID=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&epi=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&activetab=pivot%3Aoverviewtab&ranMID=43674&ranEAID=RIg0ReKk7DI&ranSiteID=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&epi=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&irgwc=1&OCID=AID2200057%5Faff%5F7795%5F1243925&tduid=%28ir%5F%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00%29%287795%29%281243925%29%28RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ%29%28%29&irclickid=%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00) which offered rich sound customization settings. Along with that, you can even access the old volume mixers, adjust the sound levels of each app, and map shortcuts.

![Old Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/old-volume-settings-in-action-center.jpg)

 However, Microsoft is slowly identifying such missing features in Windows 11 and is adding an inbuilt solution for it. Recently,[Microsoft began testing an RGB lighting feature](https://www.makeuseof.com/enable-rgb-lighting-controls-windows-11/) that will eliminate the need for third-party customization apps. So, it is pretty clear that Microsoft wants to reduce the reliance on third-party apps for vital system features and tweaks.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
### 1\. Download the Latest Windows Insider Build and ViVeTool

 Currently, the volume mixer feature is an experimental feature hidden in Windows Insider build 25295\. So, you must install this Windows Insider build or a higher version to enable this feature. We recommend [using UUP Dump to download Windows Insider builds without subscribing to Windows Insider](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

 Microsoft recently expanded the Insider program with a new Canary channel, and it makes it difficult to downgrade to another channel. So, you can use UPP Dump to avoid this program and get builds directly.

 You will also need to download [ViVeTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) to enable the experimental volume mixer feature. It is a command-line tool that can both activate and deactivate experimental Windows features. However, extract the tool to an easily accessible location in the C drive.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. Enable Volume Mixer in Windows Using ViVeTool

After you have the ViVeTool ready, repeat the following steps:

1. Press the**Win** key to open the Start menu. Type**cmd** and press the**Ctrl + Shift + Enter** key.
2. UAC will pop up. Click on the**Yes** button to [open the Command Prompt with administrator privileges](https://www.makeuseof.com/how-to-always-open-command-prompt-as-administrator-windows/) .
3. Now, you need to navigate to the location where the ViVeTool folder exists. We extracted the tool to a folder named ViVeTool in**C** drive for easy access, and suggest you do the same. Otherwise, you have to change the directory multiple time to get to the tool’s folder.
4. Type the**cd C:\\** command and press the enter key to go to the main C drive directory.
5. After that, type**cd ViVeTool** command and press the enter key. Now, you are in the directory where ViVeTool executable file is present.
6. Type the following command and press the enter key to enable the hidden volume mixer:  
vivetool /enable /id:42106010
7. You will see a “**Successfully set feature configuration(s)** ” message. Type the**exit** command and press the enter key to close the command prompt window.  
![Enabling New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/enabling-new-volume-settings-in-action-center.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
8. Restart your system to allow the changes to take effect.
9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-tips.techidaily.com/new-10-free-legal-chants-and-sounds-for-meditation-practice/"><u>[New] 10 Free Legal Chants and Sounds for Meditation Practice</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-break-free-from-linearity-mastering-jump-cut-transitions/"><u>[New] 2024 Approved  Break Free From Linearity  Mastering Jump Cut Transitions</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-explore-top-8-zero-cost-3d-vids-plugins-for-windows-and-mac-os/"><u>[New] 2024 Approved  Explore Top 8 Zero-Cost 3D Vids Plugins For Windows & Mac OS</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-how-to-disable-live-recording-in-quicktime-player/"><u>[New] 2024 Approved  How to Disable Live Recording in QuickTime Player</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-boost-your-imagery-title-placement-techniques-on-video-clips-with-photos/"><u>[New] Boost Your Imagery  Title Placement Techniques on Video Clips with Photos</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-new-download-tool-facebook-videos-for-all-oses/"><u>[New] New Download Tool  Facebook Videos for All OSes</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-samsung-galaxy-a15-5g-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Samsung Galaxy A15 5G Activity | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-windows-11-features-youre-probably-not-using-but-should/"><u>7 Windows 11 Features You’re Probably Not Using (but Should)</u></a></li>
<li><a href="https://win11.techidaily.com/9-essential-fixes-for-troublesome-email-notifications-in-windows/"><u>9 Essential Fixes for Troublesome Email Notifications in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-developers-journey-github-desktop-in-the-era-of-win-11/"><u>A Developer's Journey: GitHub Desktop in the Era of Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-guide-activatedeactivate-windows-low-power-mode/"><u>A Quick Guide: Activate/Deactivate Windows' Low-Power Mode</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-to-creativity-best-drawing-apps-for-win10/"><u>A Window to Creativity: Best Drawing Apps for Win10</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-productivity-with-essential-windows-11-methods/"><u>Accelerate Productivity with Essential Windows 11 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-3d-paint-process-with-these-tips/"><u>Accelerate Your 3D Paint Process with These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/activating-hidden-taskbar-query-function-in-windows-11/"><u>Activating Hidden Taskbar Query Function in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/add-ons-for-the-classics-mastering-achievements-via-retroarch-software-guide/"><u>Add-Ons for the Classics: Mastering Achievements via Retroarch Software Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-msvcr110dll-disappearance/"><u>Addressing msvcr110.dll Disappearance</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-systemsettings-issue-on-windows-11/"><u>Addressing SystemSettings Issue on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/alert-essential-windows-processes-to-watch-for-malware/"><u>Alert: Essential Windows Processes to Watch for Malware</u></a></li>
<li><a href="https://win11.techidaily.com/an-overview-of-cab-files-in-windows-and-how-to-install-them/"><u>An Overview of CAB Files in Windows and How to Install Them</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-windows-unlicensed-adobe-errors/"><u>Avoid Windows 'Unlicensed' Adobe Errors</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-power-and-performance-in-windows-systems/"><u>Balancing Power and Performance in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-tutorial-starting-windows-media-player/"><u>Beginner's Tutorial: Starting Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-renaming-administrators-in-windows-11-pro/"><u>Best Practices for Renaming Administrators in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/best-vmms-aligned-with-windows-11-system-requirements/"><u>Best VMMs Aligned with Windows 11 System Requirements</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-manual-inputs-embracing-ai-in-windows-operations/"><u>Beyond Manual Inputs: Embracing AI in Windows Operations</u></a></li>
<li><a href="https://win11.techidaily.com/big-data-in-bare-minipcs-little-prowess/"><u>Big Data in Bare MiniPCs, Little Prowess</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-vm-capabilities-upgrading-to-virtualbox-70-in-win11/"><u>Boost Your VM Capabilities: Upgrading to VirtualBox 7.0 in Win11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-honor-x7b-get-deleted-photos-back-with-ease-and-safety-by-fonelab-android-recover-photos/"><u>How to Honor X7b Get Deleted photos Back with Ease and Safety?</u></a></li>
<li><a href="https://win-amazing.techidaily.com/igfx-module-error-resolved-working-solution-unveiled/"><u>IGFX Module Error Resolved: Working Solution Unveiled</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-vivo-s18-pro-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Vivo S18 Pro Pattern Lock Screen</u></a></li>
<li><a href="https://buynow-info.techidaily.com/1722781532171-is-the-tp-link-archer-ax6000-a-better-choice-than-the-nighthawk-ax12-review-insights/"><u>Is the TP-Link Archer AX6000 a Better Choice Than the Nighthawk AX12? Review Insights!</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-discover-a-world-of-free-guitar-inspiration-imagery-and-music-downloads/"><u>New Discover a World of Free Guitar Inspiration Imagery & Music Downloads</u></a></li>
<li><a href="https://driver-download.techidaily.com/overcoming-samsung-blu-ray-compatibility-and-functionality-problems/"><u>Overcoming Samsung Blu Ray Compatibility and Functionality Problems</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/retro-reflection-self-portraits-with-x-phone-for-2024/"><u>Retro Reflection  Self-Portraits with X Phone for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/smooth-operation-of-usbasp-on-varied-windows-platforms-unlocked-solved/"><u>Smooth Operation of USBasp on Varied Windows Platforms Unlocked [SOLVED]</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unveiling-the-most-effective-web-subtitle-editors/"><u>Unveiling the Most Effective Web Subtitle Editors</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-knowing-all-ways-to-slow-down-video-with-adobe-premiere-pro/"><u>Updated 2024 Approved Knowing All Ways To Slow Down Video With Adobe Premiere Pro</u></a></li>
<li><a href="https://win11.techidaily.com/1719320103482-windows-xbox-not-working-fix-it-fast/"><u>Windows Xbox Not Working? Fix It Fast!</u></a></li>
</ul></div>
