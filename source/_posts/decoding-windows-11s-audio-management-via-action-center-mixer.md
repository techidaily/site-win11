---
title: Decoding Windows 11'S Audio Management via Action Center Mixer
date: 2024-11-22T19:39:56.300Z
updated: 2024-11-27T20:10:25.331Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decoding Windows 11'S Audio Management via Action Center Mixer
excerpt: This Article Describes Decoding Windows 11'S Audio Management via Action Center Mixer
keywords: Windows 11 Audio Hub,Mixer Control Menu,Action Center Sound,PC Auditory Settings,OS Audio Management,Digital Mixer Interface,Windows Audio Tuning
thumbnail: https://thmb.techidaily.com/9ed1822c884a606f5ae36981b782d8b43a1eaddd1153302103151c40c41208fa.jpg
---

## Decoding Windows 11'S Audio Management via Action Center Mixer

 Remember the old volume mixer which you could access from the system tray notifications? Windows 11 seems to be missing that ever since its release. When you click on the Volume icon in the Action Center, you only see an option to change the sound output device. There are no means to directly access the volume mixer from there. But Microsoft isn’t done with the volume settings on Windows 11.

 In a new experimental feature, Microsoft is revamping the sound settings in the Action Center. You will be able to switch output devices and adjust the volume of each of the apps listed in the Volume Mixer. Wondering how to get the feature on your system? Here's how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Do You Need a Volume Mixer in Action Center?

 The present state of volume settings in Windows 11 is quite lackluster. You can only adjust the volume of the system and cycle between multiple audio devices. For opening any other settings, even something as trivial as a volume mixer: you need to dive deep into system sound settings.

 It is baffling how Microsoft missed something so crucial in Windows 11\. These missing volume settings gave rise to apps like[EarTrumpet](https://apps.microsoft.com/store/detail/9NBLGGH516XP?hl=en-us&gl=US&ranMID=24542&ranEAID=nOD%2FrLJHOac&ranSiteID=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&epi=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&activetab=pivot%3Aoverviewtab&ranMID=43674&ranEAID=RIg0ReKk7DI&ranSiteID=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&epi=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&irgwc=1&OCID=AID2200057%5Faff%5F7795%5F1243925&tduid=%28ir%5F%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00%29%287795%29%281243925%29%28RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ%29%28%29&irclickid=%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00) which offered rich sound customization settings. Along with that, you can even access the old volume mixers, adjust the sound levels of each app, and map shortcuts.

![Old Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/old-volume-settings-in-action-center.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 However, Microsoft is slowly identifying such missing features in Windows 11 and is adding an inbuilt solution for it. Recently,[Microsoft began testing an RGB lighting feature](https://www.makeuseof.com/enable-rgb-lighting-controls-windows-11/) that will eliminate the need for third-party customization apps. So, it is pretty clear that Microsoft wants to reduce the reliance on third-party apps for vital system features and tweaks.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable the Volume Mixer in Windows 11's Action Center

 To enable the volume mixer in Windows 11, you will need to do the following:

### 1\. Download the Latest Windows Insider Build and ViVeTool

 Currently, the volume mixer feature is an experimental feature hidden in Windows Insider build 25295\. So, you must install this Windows Insider build or a higher version to enable this feature. We recommend[using UUP Dump to download Windows Insider builds without subscribing to Windows Insider](https://www.makeuseof.com/windows-11-download-insider-iso-without-insider-program/) .

 Microsoft recently expanded the Insider program with a new Canary channel, and it makes it difficult to downgrade to another channel. So, you can use UPP Dump to avoid this program and get builds directly.

 You will also need to download[ViVeTool from GitHub](https://github.com/thebookisclosed/ViVe/releases) to enable the experimental volume mixer feature. It is a command-line tool that can both activate and deactivate experimental Windows features. However, extract the tool to an easily accessible location in the C drive.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-conference-call-to-online-showcase-google-meet-on-youtube/"><u>[New] 2024 Approved From Conference Call to Online Showcase Google Meet on YouTube</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-symphony-silhouette-audio-studio-mac/"><u>[New] Symphony Silhouette Audio Studio Mac</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unveiling-the-secrets-to-successful-zoom-calls-with-android/"><u>[New] Unveiling the Secrets to Successful Zoom Calls with Android</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-lava-yuva-3-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Lava Yuva 3 PC | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/age-of-empires-iv-stability-solutions-ending-game-crashes-on-personal-computers/"><u>Age of Empires IV Stability Solutions: Ending Game Crashes on Personal Computers</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-the-slowdowns-swift-solutions-to-lag-in-star-wars-battlefront-2-windows-pc-edition/"><u>Conquer the Slowdowns: Swift Solutions to Lag in Star Wars Battlefront 2 Windows PC Edition</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-safe-browsing-environment-on-windows-11/"><u>Crafting a Safe Browsing Environment on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-file-retrieval-with-windows-nas/"><u>Cross-Platform File Retrieval with Windows NAS</u></a></li>
<li><a href="https://win11.techidaily.com/excellent-non-windows-options-to-replace-the-windows-snipping-tool/"><u>Excellent Non-Windows Options to Replace the Window’s Snipping Tool</u></a></li>
<li><a href="https://extra-tips.techidaily.com/from-raw-renders-to-rich-realities-grading-in-post-production/"><u>From Raw Renders to Rich Realities Grading in Post-Production</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-error-0x0000011b-on-your-windows-11-pc/"><u>How to Rectify Error 0X0000011B on Your Windows 11 PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-tecno-camon-30-pro-5g-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Tecno Camon 30 Pro 5G</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-is-fake-gps-location-pro-and-is-it-good-on-xiaomi-redmi-k70-pro-drfone-by-drfone-virtual-android/"><u>In 2024, What is Fake GPS Location Pro and Is It Good On Xiaomi Redmi K70 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-issues-with-failed-updater-for-win11-v22h2-version/"><u>Mitigating Issues with Failed Updater for WIN11 V22H2 Version</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-access-blockage-issues-with-these-win-strategies/"><u>Resolving Access Blockage Issues with These Win Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-non-working-file-segmentation-fixes/"><u>Reversing Non-Working File Segmentation Fixes</u></a></li>
<li><a href="https://solve-news.techidaily.com/simple-guide-mastering-the-art-of-selecting-the-perfect-dvd-name-from-the-complete-collection-series/"><u>Simple Guide: Mastering the Art of Selecting the Perfect DVD Name From 'The Complete Collection' Series</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-lenovos-latest-innovation-a-revolutionary-tablet-focused-on-core-performance/"><u>Unveiling Lenovo's Latest Innovation: A Revolutionary Tablet Focused on Core Performance</u></a></li>
<li><a href="https://win11.techidaily.com/where-are-the-blue-screen-of-death-log-files-located-in-windows-heres-how-to-read-them/"><u>Where Are the Blue Screen of Death Log Files Located in Windows? Here's How to Read Them</u></a></li>
</ul></div>

