---
title: Activating the Action Center Volume Mixing in Windows 11
date: 2024-07-13T11:20:52.519Z
updated: 2024-07-14T11:20:52.519Z
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

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

### 1\. Download the Latest Windows Insider Build and ViVeTool

 Currently, the volume mixer feature is an experimental feature hidden in Windows Insider build 25295\. So, you must install this Windows Insider build or a higher version to enable this feature. We recommend [using UUP Dump to download Windows Insider builds without subscribing to Windows Insider](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

 Microsoft recently expanded the Insider program with a new Canary channel, and it makes it difficult to downgrade to another channel. So, you can use UPP Dump to avoid this program and get builds directly.

 You will also need to download [ViVeTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) to enable the experimental volume mixer feature. It is a command-line tool that can both activate and deactivate experimental Windows features. However, extract the tool to an easily accessible location in the C drive.

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
8. Restart your system to allow the changes to take effect.
9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)

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
<li><a href="https://win11.techidaily.com/leading-password-guardians-revolutionizing-windows-11-life/"><u>Leading Password Guardians Revolutionizing Windows 11 Life</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-infinix-hot-30i-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Infinix Hot 30i Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-powershell-experience-execution-policies-demystified/"><u>Optimize Your PowerShell Experience: Execution Policies Demystified</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-samsung-galaxy-a15-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Samsung Galaxy A15 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-vm-experience-seamless-upgrade-to-virtualbox-v70-on-w11-systems/"><u>Elevate Your VM Experience: Seamless Upgrade to VirtualBox v7.0 on W11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-system-restore-a-windows-11-perspective/"><u>Mastery Over System Restore: A Windows 11 Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/invisible-windows-bar-make-it-transparent-on-win11/"><u>Invisible Windows Bar: Make It Transparent on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-read-failure-errors-in-windows-1011/"><u>Overcoming Read Failure Errors in Windows 10/11</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-windows-enthusiasts-guide-to-premium-free-audio-editing-applications/"><u>Updated Windows Enthusiasts Guide to Premium Free Audio Editing Applications</u></a></li>
<li><a href="https://win11.techidaily.com/excellent-windows-pens-tablet-notes-companions/"><u>Excellent Windows Pens' Tablet Notes Companions</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missed-display-after-windows-starts/"><u>Overcoming Missed Display After Windows Starts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/essential-titles-your-gateway-to-open-worlds/"><u>Essential Titles  Your Gateway to Open Worlds</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-file-properties-and-date-adjustments/"><u>Navigating Windows File Properties and Date Adjustments</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-mastering-live-show-recordings-the-modern-way/"><u>In 2024, Mastering Live Show Recordings  The Modern Way</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-art-of-warmth-in-winter-top-5-video-backdrop-choices-for-2024/"><u>The Art of Warmth in Winter  Top 5 Video Backdrop Choices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-num-caps-and-scroll-lock-key-indicators-to-windows-11s-system-tray/"><u>How to Add Num, Caps, and Scroll Lock Key Indicators to Windows 11’S System Tray</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11s-update-failure-code-0x80246007/"><u>Overcoming Windows 11'S Update Failure: Code 0X80246007</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/comprehensive-list-of-top-9-video-meeting-software-on-devices/"><u>Comprehensive List of Top 9 Video Meeting Software on Devices</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-installed-disk-issue-on-windows-11-system/"><u>Fixing Non-Installed Disk Issue on Windows 11 System</u></a></li>
<li><a href="https://win11.techidaily.com/easy-auto-shutdown-techniques-for-idle-windows-pcs/"><u>Easy Auto-Shutdown Techniques for Idle Windows PCs</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-vivo-v30-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Vivo V30 online without jailbreak</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/s-leading-video-editors-for-music-and-sound-design/"><u>S Leading Video Editors for Music and Sound Design</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-combat-frozen-wireless-mice-on-windows-desktops/"><u>How to Combat Frozen Wireless Mice on Windows Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/journey-through-credential-management-fixes/"><u>Journey Through Credential Management Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-activate-black-background-on-wincalc/"><u>Guide to Activate Black Background on WinCalc</u></a></li>
<li><a href="https://win11.techidaily.com/guide-accessing-windows-11s-security-settings/"><u>Guide: Accessing Windows 11'S Security Settings</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-windows-11s-security-and-credentials-panel/"><u>Guide to Windows 11'S Security & Credentials Panel</u></a></li>
<li><a href="https://win11.techidaily.com/enter-the-inner-workings-of-your-pc/"><u>Enter the Inner Workings of Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-sie-and-load-unverified-drivers-in-windows/"><u>How to Bypass SIE & Load Unverified Drivers in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-device-communication-efficiency-by-optimizing-windows-systems/"><u>Enhancing Device Communication Efficiency by Optimizing Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-mastery-for-streamlined-project-planning/"><u>Keyboard Mastery for Streamlined Project Planning</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-white-screens-and-blank-logins-on-windows-1011/"><u>Navigating Through White Screens and Blank Logins on Windows 10/11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-best-guide-for-facebook-video-advertising/"><u>[Updated] 2024 Approved  Best Guide for Facebook Video Advertising</u></a></li>
<li><a href="https://win11.techidaily.com/low-memory-high-performance-comparing-best-windows-browsers/"><u>Low-Memory, High Performance: Comparing Best Windows Browsers</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-navigating-the-landscape-of-high-quality-sound-editing-the-twistedwave-experience-for-2024/"><u>New Navigating the Landscape of High-Quality Sound Editing - The TwistedWave Experience for 2024</u></a></li>
</ul></div>
