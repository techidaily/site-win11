---
title: "Windows 11 Sound: Leveraging the Volume Mixer in Action Center"
date: 2024-11-05T22:49:36.328Z
updated: 2024-11-07T22:55:12.145Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11 Sound: Leveraging the Volume Mixer in Action Center"
excerpt: "This Article Describes Windows 11 Sound: Leveraging the Volume Mixer in Action Center"
keywords: Win11SoundVolumeControl,WindowsVolumeMixerTool,ActionCenterAudioAdjust,11WindowsSoundMixer,VolumeMixerSettingsWin11,ManageVolumeInActionWin,AudioLevelsWin11Mixer
thumbnail: https://thmb.techidaily.com/402a192fa8f9a76c25001597879db6a11d907dc8fe3db6a194aec02ff3403057.jpg
---

## Windows 11 Sound: Leveraging the Volume Mixer in Action Center

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
<a href="https://appsumo.8odi.net/c/5597632/2082520/7443" target="_top" id="2082520">
  <img src="//a.impactradius-go.com/display-ad/7443-2082520" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082520/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151868/7443" target="_top" id="2151868">
  <img src="//a.impactradius-go.com/display-ad/7443-2151868" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151868/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Download the Latest Windows Insider Build and ViVeTool

 Currently, the volume mixer feature is an experimental feature hidden in Windows Insider build 25295\. So, you must install this Windows Insider build or a higher version to enable this feature. We recommend[using UUP Dump to download Windows Insider builds without subscribing to Windows Insider](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

 Microsoft recently expanded the Insider program with a new Canary channel, and it makes it difficult to downgrade to another channel. So, you can use UPP Dump to avoid this program and get builds directly.

 You will also need to download[ViVeTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) to enable the experimental volume mixer feature. It is a command-line tool that can both activate and deactivate experimental Windows features. However, extract the tool to an easily accessible location in the C drive.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036481/19272" target="_top" id="2036481">
  <img src="//a.impactradius-go.com/display-ad/19272-2036481" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036481/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2068439/7443" target="_top" id="2068439">
  <img src="//a.impactradius-go.com/display-ad/7443-2068439" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068439/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-web.techidaily.com/024-approved-securing-youtube-tracks-at-no-cost-with-security-in-mind/"><u>[New] 2024 Approved Securing Youtube Tracks at No Cost, with Security in Mind</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ey-players-in-asmr-youtube-world-for-2024/"><u>[New] Key Players in ASMR YouTube World for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-navigating-ffxp-the-user-manual/"><u>[Updated] Navigating FFXP The User Manual</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/building-an-msr-disk-imaging-file-on-hyper-v-essential-tutorial-steps/"><u>Building an MSR Disk Imaging File on Hyper-V: Essential Tutorial Steps</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-store-failures-fast-tackling-0x80072f30-errors/"><u>Fix Windows Store Failures Fast: Tackling 0X80072F30 Errors</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-lock-from-your-apple-iphone-13-and-ipad-by-drfone-ios/"><u>How to Unlock iCloud lock from your Apple iPhone 13 and iPad?</u></a></li>
<li><a href="https://win11.techidaily.com/interactive-device-management-via-windows-interface-elements/"><u>Interactive Device Management via Windows Interface Elements</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-an-eye-out-essential-windows-steps-that-might-hide-viruses/"><u>Keeping an Eye Out: Essential Windows Steps That Might Hide Viruses</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-pc-components-a-journey-through-toms-hardware-wisdom/"><u>Mastering PC Components: A Journey Through Tom's Hardware Wisdom</u></a></li>
<li><a href="https://win11.techidaily.com/modifying-windows-11-shutdown-duration-during-execution/"><u>Modifying Windows 11 Shutdown Duration During Execution</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/playstation-portable-pre-release-guide-insights-into-release-timeline-price-range-tech-details-and-buying-options/"><u>PlayStation Portable Pre-Release Guide: Insights Into Release Timeline, Price Range, Tech Details & Buying Options</u></a></li>
<li><a href="https://win11.techidaily.com/revisiting-microsoft-store-error-code-0x80073cf3/"><u>Revisiting Microsoft Store Error Code: 0X80073CF3</u></a></li>
<li><a href="https://win11.techidaily.com/synergy-in-task-management-to-do-with-ifttt-triggers/"><u>Synergy in Task Management: To-Do with IFTTT Triggers</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-guide-to-font-customization-in-ae/"><u>The Ultimate Guide to Font Customization in AE</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-simplified-image-browsing-setup/"><u>Windows 11: Simplified Image Browsing Setup</u></a></li>
</ul></div>

