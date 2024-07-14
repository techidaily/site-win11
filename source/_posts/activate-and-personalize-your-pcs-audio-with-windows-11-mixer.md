---
title: Activate and Personalize Your PC's Audio with Windows 11 Mixer
date: 2024-07-13T11:16:44.132Z
updated: 2024-07-14T11:16:44.132Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activate and Personalize Your PC's Audio with Windows 11 Mixer
excerpt: This Article Describes Activate and Personalize Your PC's Audio with Windows 11 Mixer
keywords: Windows 11 Sound Control,Personalized PC Audio,Activating Windows 11 Mixer,Customize PC Audio Settings,Enhance PC Audio Quality,Windows 11 Audio Manager,Tailor PC Sound Experience
thumbnail: https://thmb.techidaily.com/61dcd74c9ca257bd7a3583ce0e08424eaf979002cdc0aa0e847be271477f189f.jpg
---

## Activate and Personalize Your PC's Audio with Windows 11 Mixer

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
<li><a href="https://some-approaches.techidaily.com/updated-streamlining-video-playback-with-safaris-pip/"><u>[Updated] Streamlining Video Playback with Safari's PIP</u></a></li>
<li><a href="https://win11.techidaily.com/windows-ui-stability-solutions-for-recurring-crashes/"><u>Windows UI Stability: Solutions for Recurring Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-engage-terminal-in-quake-mode/"><u>How to Engage Terminal in Quake Mode</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-strategies-to-cut-down-system-energy-usage-games/"><u>Efficient Strategies to Cut Down System Energy Usage Games</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-rename-your-user-account-directory/"><u>Win 11: Rename Your User Account Directory</u></a></li>
<li><a href="https://win11.techidaily.com/quick-methods-to-nullify-laptops-built-in-input-device/"><u>Quick Methods to Nullify Laptop's Built-In Input Device</u></a></li>
<li><a href="https://win11.techidaily.com/the-key-to-seamless-slide-showouts-top-tips-for-powerpoint-printing-on-windows/"><u>The Key to Seamless Slide Showouts: Top Tips for PowerPoint Printing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-post-zestful-days-of-life-on-windows-pcs/"><u>Reviving Post-Zestful Days of Life on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-customize-windows-menu-for-instant-removal/"><u>Swift Solutions: Customize Windows Menu for Instant Removal</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-eliminating-server-glitches-impacting-ms-store-on-win-1111/"><u>Quick Fix: Eliminating Server Glitches Impacting MS Store on Win 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-rectify-non-detected-windows-proxies/"><u>Tips to Rectify Non-Detected Windows Proxies</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-rectify-windows-11s-zero-a00f-app-mishap/"><u>Strategies to Rectify Windows 11’S Zero-A00F APP Mishap</u></a></li>
<li><a href="https://win11.techidaily.com/silence-ended-resurrecting-dormant-slack-notifications-in-windows-11/"><u>Silence Ended? Resurrecting Dormant Slack Notifications in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-proxy-configuration-in-win-11/"><u>Mastery of Proxy Configuration in Win 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-the-lore-of-roguelites-amidst-classic-rpgs/"><u>[Updated] In 2024, The Lore of Roguelites Amidst Classic RPGs</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-realme-c53-drfone-by-drfone-android/"><u>How to Screen Mirroring Realme C53? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/peek-inside-the-persona-machine-how-to-launch-windows-secret-self-analysis-engine/"><u>Peek Inside the Persona Machine: How to Launch Windows’ Secret Self-Analysis Engine</u></a></li>
<li><a href="https://win11.techidaily.com/win11-steps-to-correct-steam-file-privileges-failure/"><u>Win11 Steps to Correct Steam File Privileges Failure</u></a></li>
<li><a href="https://win11.techidaily.com/winning-fps-tools-the-top-6-counter-app-picks/"><u>Winning FPS Tools: The Top 6 Counter App Picks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-exception-handling-breaking-point-strategies/"><u>Mastering Exception Handling: Breaking Point Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-smoothly-integrate-icloud-with-your-windows-machine/"><u>How to Smoothly Integrate iCloud with Your Windows Machine</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/a-filmmakers-dream-the-8-best-no-fee-video-editors-on-the-market/"><u>A Filmmaker's Dream  The 8 Best No-Fee Video Editors on the Market</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-file-inspection-6-steps-for-windows/"><u>The Art of File Inspection: 6 Steps for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-measures-to-mend-ms-store-malfunctions-in-windows-os/"><u>Masterful Measures to Mend MS Store Malfunctions in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-education-elements-into-windows-ui/"><u>Infuse Education Elements Into Windows UI</u></a></li>
<li><a href="https://win11.techidaily.com/rebooting-your-typing-routine-9-fixes-for-broken-keyboard-commands-on-windows/"><u>Rebooting Your Typing Routine: 9 Fixes for Broken Keyboard Commands on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/instituting-new-pdf-reader-as-standard/"><u>Instituting New PDF Reader as Standard</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-automatic-network-proxy-fixes/"><u>Mastering Windows' Automatic Network Proxy Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/installing-kali-linux-effortlessly-on-a-windows-pc/"><u>Installing Kali Linux Effortlessly on a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-the-volume-mixer-in-the-action-center-in-windows-11/"><u>How to Enable the Volume Mixer in the Action Center in Windows 11</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-earning-through-snaps-a-guide/"><u>[New] In 2024, Earning Through Snaps  A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-browsing-game-master-microsoft-edge-gestures-on-windows-11/"><u>Step-Up Your Browsing Game: Master Microsoft Edge Gestures on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/stealthy-controls-for-displaying-windows-clock/"><u>Stealthy Controls for Displaying Windows Clock</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-essentials-in-windows-photo-editing-keys/"><u>Mastering the Essentials in Windows Photo Editing Keys</u></a></li>
<li><a href="https://win11.techidaily.com/struggling-with-game-installs-xbox-app-solutions/"><u>Struggling with Game Installs: Xbox App Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-ubiquitous-blue-screen-enigma/"><u>Overcoming the Ubiquitous Blue Screen Enigma</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-vivo-x100-pro-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Vivo X100 Pro FRP Android 10/11/12/13</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-silent-audio-during-powerpoint-presentations/"><u>Solutions to Silent Audio During PowerPoint Presentations</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-exclusive-roundup-leading-fb-video-content/"><u>2024 Approved  Exclusive Roundup  Leading FB Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-gpo-report-generation-via-gpresult/"><u>Mastering GPO Report Generation via GPResult</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-poco-m6-pro-4g-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Poco M6 Pro 4G Devices | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-bringing-back-the-glitter-integrating-instagram-effects-to-past-media/"><u>[Updated] 2024 Approved  Bringing Back the Glitter  Integrating Instagram Effects to Past Media</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/is-optimal-hdr-with-aurora-worth-it-in-2024/"><u>Is Optimal HDR with Aurora Worth It, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/purify-your-pc-go-bare-with-tiny11/"><u>Purify Your PC: Go Bare with Tiny11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-speed-up-download-speeds-in-utorrent-for-windows/"><u>How to Speed Up Download Speeds in uTorrent for Windows</u></a></li>
</ul></div>
