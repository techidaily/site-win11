---
title: "Streamline and Configure Your PC Audio Output: Windows 11 Mixer Guide"
date: 2024-11-03T23:11:08.730Z
updated: 2024-11-07T21:45:07.442Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Streamline and Configure Your PC Audio Output: Windows 11 Mixer Guide"
excerpt: "This Article Describes Streamline and Configure Your PC Audio Output: Windows 11 Mixer Guide"
keywords: PC Audio Streamlining,Windows 11 Sound Control,Mixer Setup Guide,Audio Configuration W11,Optimize PC Outputs,Enhance Windows Audio,Navigate Sound Settings
thumbnail: https://thmb.techidaily.com/1b74b748e6b2e328a07a7b57a377bfde7d1cf69849bc4b8a8c3c123bbebb43d1.jpg
---

## Streamline and Configure Your PC Audio Output: Windows 11 Mixer Guide

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

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997722/19272" target="_top" id="1997722">
  <img src="//a.impactradius-go.com/display-ad/19272-1997722" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997722/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2151869/7443" target="_top" id="2151869">
  <img src="//a.impactradius-go.com/display-ad/7443-2151869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137201/26400" target="_top" id="2137201">
  <img src="//a.impactradius-go.com/display-ad/26400-2137201" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137201/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/994842/11832" target="_top" id="994842">
  <img src="//a.impactradius-go.com/display-ad/11832-994842" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/994842/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-decoding-dimensions-the-key-to-perfect-aspect-ratios-in-video/"><u>[Updated] 2024 Approved Decoding Dimensions The Key to Perfect Aspect Ratios in Video</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-swift-screen-tape-with-sound-included/"><u>[Updated] In 2024, Swift Screen Tape with Sound Included</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-transformative-youtube-decks-via-tailored-templates/"><u>[Updated] Transformative Youtube Decks via Tailored Templates</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-extensive-analysis-djis-latest-uav-inspire-1/"><u>2024 Approved Extensive Analysis DJI's Latest UAV, Inspire 1</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-top-ten-viewers-favorites-in-a-single-day-on-youtube/"><u>2024 Approved Top Ten Viewers' Favorites in a Single Day on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-consistent-note-taking-space-in-windows-11/"><u>Creating a Consistent Note-Taking Space in Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/decoding-tech-tangles-chatgpt-for-pc-recovery/"><u>Decoding Tech Tangles - ChatGPT for PC Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/display-diversity-adjusting-each-monitors-aesthetic-in-win-1011/"><u>Display Diversity: Adjusting Each Monitor's Aesthetic in WIN 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-developer-skills-with-github-desktop-on-windows-oses/"><u>Elevate Your Developer Skills with GitHub Desktop on Windows OSes</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-tecno-phantom-v-flip-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Tecno Phantom V Flip Phone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-patching-with-4-essentials/"><u>Mastering Windows Patching with 4 Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/preserving-your-digital-post-its-in-windows/"><u>Preserving Your Digital Post-Its in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restore-the-lost-search-feature-in-windows-11s-tm-environment/"><u>Restore the Lost Search Feature in Windows 11'S TM Environment</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-password-less-windows-11-rdp/"><u>The Ultimate Guide to Password-Less Windows 11 RDP</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-automatic-fixes-for-wake-up-sound-issues/"><u>The Ultimate Guide: Automatic Fixes for Wake-Up Sound Issues</u></a></li>
<li><a href="https://discover-exceptional.techidaily.com/ultimate-guide-saving-your-files-prior-to-a-full-windows-11-os-reboot/"><u>Ultimate Guide: Saving Your Files Prior to a Full Windows 11 OS Reboot</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-what-is-sora-by-openai-everything-you-need-to-know-for-2024/"><u>Updated What Is Sora by OpenAI Everything You Need To Know for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1723808167884-windows-11-download-fast-and-easily/"><u>Windows 11 Download Fast & Easily!</u></a></li>
<li><a href="https://win11.techidaily.com/winning-choices-top-windows-tools-for-video-conversion/"><u>Winning Choices: Top Windows Tools For Video Conversion</u></a></li>
</ul></div>

