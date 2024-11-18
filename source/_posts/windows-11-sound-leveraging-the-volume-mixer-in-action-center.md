---
title: "Windows 11 Sound: Leveraging the Volume Mixer in Action Center"
date: 2024-11-14T22:23:58.483Z
updated: 2024-11-18T02:30:14.313Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2012401/19272" target="_top" id="2012401">
  <img src="//a.impactradius-go.com/display-ad/19272-2012401" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137379/7443" target="_top" id="2137379">
  <img src="//a.impactradius-go.com/display-ad/7443-2137379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Download the Latest Windows Insider Build and ViVeTool

 Currently, the volume mixer feature is an experimental feature hidden in Windows Insider build 25295\. So, you must install this Windows Insider build or a higher version to enable this feature. We recommend[using UUP Dump to download Windows Insider builds without subscribing to Windows Insider](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

 Microsoft recently expanded the Insider program with a new Canary channel, and it makes it difficult to downgrade to another channel. So, you can use UPP Dump to avoid this program and get builds directly.

 You will also need to download[ViVeTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) to enable the experimental volume mixer feature. It is a command-line tool that can both activate and deactivate experimental Windows features. However, extract the tool to an easily accessible location in the C drive.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136545/16384" target="_top" id="2136545">
  <img src="//a.impactradius-go.com/display-ad/16384-2136545" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136545/16384" style="position:absolute;visibility:hidden;" border="0" />
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

9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902304/19272" target="_top" id="1902304">
  <img src="//a.impactradius-go.com/display-ad/19272-1902304" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902304/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-minimca-manorettes-simple-and-sleek-homes-in-mc-world/"><u>[New] 2024 Approved MiniMCA Manorettes Simple & Sleek Homes in MC World</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-getting-your-vlogging-started-key-items-and-software/"><u>[New] Getting Your Vlogging Started Key Items & Software</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-realme-gt-neo-5-by-drfone-android/"><u>10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Realme GT Neo 5</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-finding-the-best-gaming-keys-at-unbeatable-prices-less-than-100/"><u>2024 Approved Finding the Best Gaming Keys at Unbeatable Prices Less than $100</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/easy-steps-for-free-powerpoint-uploads-to-youtube-withwithout-sound/"><u>Easy Steps for Free PowerPoint Uploads to YouTube - With/Without Sound</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-problem-with-this-windows-installer-package-error-on-windows-11-and-11/"><u>How to Fix the Problem With This Windows Installer Package Error on Windows 11 & 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-oppo-a56s-5g-fix-now-drfone-by-drfone-virtual-android/"><u>In 2024, 3uTools Virtual Location Not Working On Oppo A56s 5G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-building-your-own-youtube-organization-toolkit-the-watch-later-way/"><u>In 2024, Building Your Own YouTube Organization Toolkit The Watch Later Way</u></a></li>
<li><a href="https://win11.techidaily.com/revival-strategies-for-net-on-your-pc-max-156/"><u>Revival Strategies for .NET on Your PC (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-typography-across-languages-on-windows-pcs/"><u>Seamless Typography Across Languages on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-stop-microsoft-teams-crashes-tips-for-wins-11-and-10/"><u>Steps to Stop Microsoft Teams Crashes: Tips for Wins 11 & 10</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-troubleshooting-task-sequence-failures-winos-edition/"><u>Strategies for Troubleshooting Task Sequence Failures: WinOS Edition</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unraveling-best-practices-for-effective-fb-healthcare-promos-for-2024/"><u>Unraveling Best Practices for Effective FB Healthcare Promos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-when-youre-unable-to-download-any-files-on-a-windows-10-and-11/"><u>What to Do When You’re Unable to Download Any Files on a Windows 10 & 11</u></a></li>
</ul></div>

