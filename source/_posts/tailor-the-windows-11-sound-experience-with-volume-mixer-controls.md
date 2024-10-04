---
title: Tailor the Windows 11 Sound Experience with Volume Mixer Controls
date: 2024-10-02T20:22:20.157Z
updated: 2024-10-04T07:00:23.633Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tailor the Windows 11 Sound Experience with Volume Mixer Controls
excerpt: This Article Describes Tailor the Windows 11 Sound Experience with Volume Mixer Controls
keywords: Win11 Sound Tailor,Volume Mixer Control,Windows Audio Tuning,Optimize Windows Sounds,Master Win11 Sounds,Enhance Win11 Audio,Adjust Win11 Volume
thumbnail: https://thmb.techidaily.com/2e153e0e621bce9ac8484d65d8c4dd2eb6f5a3b85fbf991174fd2d0ac26c3edd.png
---

## Tailor the Windows 11 Sound Experience with Volume Mixer Controls

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
<a href="https://laganoo.pxf.io/c/5597632/1484910/16446" target="_top" id="1484910">
  <img src="//a.impactradius-go.com/display-ad/16446-1484910" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484910/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2151883/7443" target="_top" id="2151883">
  <img src="//a.impactradius-go.com/display-ad/7443-2151883" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151883/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1167086/14483" target="_top" id="1167086">
  <img src="//a.impactradius-go.com/display-ad/14483-1167086" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1167086/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134218/18498" target="_top" id="2134218">
  <img src="//a.impactradius-go.com/display-ad/18498-2134218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134218/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-links.techidaily.com/new-in-2024-pro-whatsapp-tips-unlocking-untapped-potentials/"><u>[New] In 2024, Pro-WhatsApp Tips Unlocking Untapped Potentials</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-advice-on-achieving-high-quality-gopro-videos/"><u>[Updated] Expert Advice on Achieving High-Quality GoPro Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-quick-start-guide-to-editing-with-snapseed/"><u>2024 Approved Quick Start Guide to Editing with Snapseed</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-usb-device-unrecognized-error-complete-guide-and-solutions/"><u>Fixing 'USB Device Unrecognized' Error - Complete Guide & Solutions</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-easily-get-or-update-your-konica-minolta-printers-latest-drivers/"><u>How To Easily Get or Update Your Konica Minolta Printer's Latest Drivers</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-smartphone-strategies-launching-successful-youtubers-from-the-start/"><u>In 2024, Smartphone Strategies Launching Successful YouTubers From the Start</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-windowsgif/"><u>Microsoft Windowsインターフェース内で簡単に動く画像(GIF)を制作するためのガイド</u></a></li>
<li><a href="https://win11.techidaily.com/oggm4a/"><u>Ogg形式へのM4Aファイル変換手順</u></a></li>
<li><a href="https://win11.techidaily.com/pcwindowsmac/"><u>PC内部オーディオ収録のプロフェッショナルガイド「Windows/Mac」</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-converting-your-videos-from-vimeo-to-mov-format-on-windows/"><u>Quick Guide: Converting Your Videos From Vimeo to MOV Format on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-google-drive-file-downloads-top-14-solutions/"><u>Resolving 'Google Drive File Downloads' - Top 14 Solutions</u></a></li>
<li><a href="https://facebook.techidaily.com/rethinking-release-dates-oculus-quest-iii-postponed/"><u>Rethinking Release Dates: Oculus Quest III Postponed</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-mov-to-mp4-transformation-top-video-converters-reviewed/"><u>Seamless MOV to MP4 Transformation: Top Video Converters Reviewed</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-nokia-c22-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-setting-up-the-au-addon-for-iptv-streaming-in-kodi-with-over-30-australian-free-tv-channel-options/"><u>Step-by-Step Guide: Setting Up the AU Addon for IPTV Streaming in Kodi with Over 30 Australian Free TV Channel Options</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-shrinking-flac-file-size-without-losing-quality/"><u>Step-by-Step Guide: Shrinking FLAC File Size Without Losing Quality</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-vanguard-audio-visual-makers-virtual-showcase/"><u>The Vanguard Audio-Visual Makers' Virtual Showcase</u></a></li>
</ul></div>

