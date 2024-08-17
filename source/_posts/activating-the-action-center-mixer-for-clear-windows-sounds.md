---
title: Activating the Action Center Mixer for Clear Windows Sounds
date: 2024-08-15T23:14:05.004Z
updated: 2024-08-16T23:14:05.004Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Activating the Action Center Mixer for Clear Windows Sounds
excerpt: This Article Describes Activating the Action Center Mixer for Clear Windows Sounds
keywords: Window Sound Mixer,Activate Mixer,Action Center Mixing,Clear Audio Windows,Mixer Enablement,Windows Sounds Control,Activation of Mixer
thumbnail: https://thmb.techidaily.com/3546fd9956a8b6a73b831712e52723669b090c846a7d2596697ef888fa555dd7.jpg
---

## Activating the Action Center Mixer for Clear Windows Sounds

 Remember the old volume mixer which you could access from the system tray notifications? Windows 11 seems to be missing that ever since its release. When you click on the Volume icon in the Action Center, you only see an option to change the sound output device. There are no means to directly access the volume mixer from there. But Microsoft isn’t done with the volume settings on Windows 11.

 In a new experimental feature, Microsoft is revamping the sound settings in the Action Center. You will be able to switch output devices and adjust the volume of each of the apps listed in the Volume Mixer. Wondering how to get the feature on your system? Here's how.

## Why Do You Need a Volume Mixer in Action Center?

 The present state of volume settings in Windows 11 is quite lackluster. You can only adjust the volume of the system and cycle between multiple audio devices. For opening any other settings, even something as trivial as a volume mixer: you need to dive deep into system sound settings.

 It is baffling how Microsoft missed something so crucial in Windows 11\. These missing volume settings gave rise to apps like [EarTrumpet](https://apps.microsoft.com/store/detail/9NBLGGH516XP?hl=en-us&gl=US&ranMID=24542&ranEAID=nOD%2FrLJHOac&ranSiteID=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&epi=nOD%5FrLJHOac-kFXVOqcgmh%5FMcUkQutiXeg&irgwc=1&OCID=AID2200057%5Faff%5F7593%5F1243925&activetab=pivot%3Aoverviewtab&ranMID=43674&ranEAID=RIg0ReKk7DI&ranSiteID=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&epi=RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ&irgwc=1&OCID=AID2200057%5Faff%5F7795%5F1243925&tduid=%28ir%5F%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00%29%287795%29%281243925%29%28RIg0ReKk7DI-SCKmwfBirhtH6ExPZ%5FEJzQ%29%28%29&irclickid=%5Fwdc06dt9wokfbgsgxdjh3vgezv2x6gcmodrafe9c00) which offered rich sound customization settings. Along with that, you can even access the old volume mixers, adjust the sound levels of each app, and map shortcuts.

![Old Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/old-volume-settings-in-action-center.jpg)

 However, Microsoft is slowly identifying such missing features in Windows 11 and is adding an inbuilt solution for it. Recently,[Microsoft began testing an RGB lighting feature](https://www.makeuseof.com/enable-rgb-lighting-controls-windows-11/) that will eliminate the need for third-party customization apps. So, it is pretty clear that Microsoft wants to reduce the reliance on third-party apps for vital system features and tweaks.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=32667153&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.coolmuster.com/uploads/image/20201228/feature02.png" border="0"></a>
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
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Restart your system to allow the changes to take effect.
9. Log in and press**Win + A** to open Action Center. You will notice a new volume mixer icon next to the volume bar. Click on it to reveal the complete sound settings. Both the Spatial Audio and volume mixer will be present inside.  
![New Volume Settings in Action Center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/new-volume-settings-in-action-center.jpg)
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-thorough-scrutiny-bublcams-panoramic-innovation/"><u>[New] 2024 Approved  Thorough Scrutiny  Bublcam's Panoramic Innovation</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-top-30-tiktok-names-for-higher-engagement-and-visibility/"><u>[New] 2024 Approved  Top 30 TikTok Names for Higher Engagement and Visibility</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-all-encompassing-az-screenshot-tool-app-evaluations-for-2024/"><u>[New] All-Encompassing AZ Screenshot Tool  App Evaluations for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-getting-started-with-obs-on-apple-a-comprehensive-guide/"><u>[New] Getting Started with OBS on Apple  A Comprehensive Guide</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-mastering-video-quality-with-yi-4k-action-camera-for-2024/"><u>[New] Mastering Video Quality with Yi 4K Action Camera for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-idea-to-internet-fame-becoming-a-vtuber/"><u>[Updated] In 2024, From Idea to Internet Fame  Becoming a VTuber?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-jumpstart-your-fitness-journey-essential-exercise-tunes/"><u>[Updated] Jumpstart Your Fitness Journey  Essential Exercise Tunes</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-obsudio-screen-recorder-analysis-your-best-choices-explored/"><u>[Updated] Obsudio Screen Recorder Analysis  Your Best Choices Explored</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-optimizing-video-sequences-blend-modes-application-for-2024/"><u>[Updated] Optimizing Video Sequences  Blend Modes Application for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-streamlining-video-content-in-zoom-with-custom-filters/"><u>[Updated] Streamlining Video Content in Zoom With Custom Filters</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-guide-to-night-photos-on-iphones/"><u>[Updated] The Ultimate Guide to Night Photos on iPhones</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unveiling-the-best-storytelling-schools-1-8-guide/"><u>[Updated] Unveiling the Best Storytelling Schools - #1-#8 Guide</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-precise-age-settings-the-essential-guide-for-tiktok-profiles/"><u>2024 Approved  Precise Age Settings  The Essential Guide for TikTok Profiles</u></a></li>
<li><a href="https://ai-topics.techidaily.com/2024-approved-what-is-an-ai-art-generator/"><u>2024 Approved What Is an AI Art Generator?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-itel-a70-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Itel A70 | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/a-user-friendly-approach-eliminating-errors-related-to-absent-or-damaged-mapi-32-dll-files/"><u>A User-Friendly Approach: Eliminating Errors Related to Absent or Damaged MAPI 32 DLL Files</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/apple-iphone-11-pro-asking-for-passcode-after-ios-1714-update-what-to-do-drfone-by-drfone-ios/"><u>Apple iPhone 11 Pro Asking for Passcode after iOS 17/14 Update, What to Do? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-the-def5-error-code-in-onedrive-w11-style/"><u>Confronting the Def5 Error Code in OneDrive, W11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-thx-audio-malfunction-in-windows/"><u>Correcting THX Audio Malfunction in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-mending-the-windows-performance-sensor/"><u>Diagnosing and Mending the Windows Performance Sensor</u></a></li>
<li><a href="https://fox-glue.techidaily.com/elevate-chromebooks-speech-profile-curated-list-of-top-web-tools/"><u>Elevate Chromebook's Speech Profile  Curated List of Top Web Tools</u></a></li>
<li><a href="https://extra-resources.techidaily.com/elite-sound-to-text-conversion-technology/"><u>Elite Sound to Text Conversion Technology</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-adjusting-directory-displays-on-windows-11/"><u>Expert Guide to Adjusting Directory Displays on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-vivo-y27s-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Vivo Y27s | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixed-silent-outlook-alerts-in-windows-environment/"><u>Fixed Silent Outlook Alerts in Windows Environment</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719580476815-get-ahead-of-the-game-snag-a-lifetime-savings-deal-with-mondly/"><u>Get Ahead of the Game: Snag a Lifetime Savings Deal with Mondly</u></a></li>
<li><a href="https://win11.techidaily.com/guaranteeing-smooth-audio-transmission-in-steam/"><u>Guaranteeing Smooth Audio Transmission in Steam</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-recover-offline-content-servers-for-valve-games/"><u>Guidelines to Recover Offline Content Servers for Valve Games</u></a></li>
<li><a href="https://win11.techidaily.com/halt-windows-application-tracking-feature/"><u>Halt Windows Application Tracking Feature</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-turn-off-games-for-you-recommendations-on-windows-11/"><u>How to Turn Off Games for You Recommendations on Windows 11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-xr-passcode-screen-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone XR Passcode Screen? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/hush-your-background-processes-in-win11/"><u>Hush Your Background Processes in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/illuminating-creativity-with-dark-themes-in-paint/"><u>Illuminating Creativity with Dark Themes in Paint</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-actions-against-windows-11-search-failures/"><u>Immediate Actions Against Windows 11 Search Failures</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-effortlessly-connect-with-these-10-affordable-video-conferencing-services/"><u>In 2024, Effortlessly Connect with These 10 Affordable Video Conferencing Services</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-exclusive-farewell-to-game-costs/"><u>In 2024, Exclusive Farewell to Game Costs</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-itel-p40plus-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Itel P40+ FRP In 3 Different Ways</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-find-my-iphone-without-apple-id-on-your-iphone-6s-by-drfone-ios/"><u>In 2024, How to Remove Find My iPhone without Apple ID On your iPhone 6s?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-xiaomi-redmi-note-13-proplus-5g-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Xiaomi Redmi Note 13 Pro+ 5G Phone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-premium-photographic-archives/"><u>In 2024, Premium Photographic Archives</u></a></li>
<li><a href="https://win11.techidaily.com/increase-windows-storage-securely/"><u>Increase Windows Storage Securely</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-windows-calculator-top-focused/"><u>Keeping Windows Calculator Top-Focused</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-disk-space-with-compression-in-windows-11/"><u>Maximizing Disk Space with Compression in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-expiring-windows-license-issues-in-w10-and-w11/"><u>Mitigating Expiring Window's License Issues in W10 & W11</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/omotn-t1-tablet-support-a-cost-effective-and-reliable-solution-for-users/"><u>Omotn T1 Tablet Support: A Cost-Effective and Reliable Solution for Users</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-savings-tap-into-w11-pro-offers/"><u>Optimize Savings: Tap Into W11 Pro Offers</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-your-pc-with-windows-visual-treasures-in-backgrounds/"><u>Personalizing Your PC with Windows' Visual Treasures in Backgrounds</u></a></li>
<li><a href="https://win11.techidaily.com/prepping-pc-enabling-tpm-secure-boot-with-windows-11/"><u>Prepping PC: Enabling TPM, Secure Boot with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ram-cache-insight-and-clearing-methods-for-win-users/"><u>RAM Cache Insight & Clearing Methods for Win Users</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reconstructed-windows-log-a-guide-to-clearing-defender-data/"><u>Reconstructed Windows Log: A Guide to Clearing Defender Data</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolved-overcoming-frame-rate-drops-and-boosting-gameplay-in-lost-ark/"><u>Resolved: Overcoming Frame Rate Drops and Boosting Gameplay in Lost Ark</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-faulty-troubleshooting-tools-in-windows-1011/"><u>Resolving Faulty Troubleshooting Tools in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-network-not-available-in-windows-os/"><u>Resolving Network Not Available in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/shadows-no-more-restore-your-lost-windows-on-win10win11/"><u>Shadows No More: Restore Your Lost Windows on Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/skirt-sie-on-windows-installing-and-updating-unsigned-drivers/"><u>Skirt SIE on Windows: Installing and Updating Unsigned Drivers</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-solution-overcoming-uncorrectable-system-memory-problems-with-whea/"><u>Step by Step Solution: Overcoming Uncorrectable System Memory Problems with WHEA</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-fix-for-coredll-absent-mistake-on-your-computer/"><u>Step-by-Step Fix for Core.DLL Absent Mistake on Your Computer</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-steps-to-revise-your-windows-account-pin/"><u>Streamlined Steps to Revise Your Windows Account Pin</u></a></li>
<li><a href="https://win11.techidaily.com/structure-your-thoughts-visual-notes-in-obsidian/"><u>Structure Your Thoughts: Visual Notes in Obsidian</u></a></li>
<li><a href="https://win11.techidaily.com/the-6-best-tools-to-stress-test-your-gpu-on-windows/"><u>The 6 Best Tools to Stress Test Your GPU on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-underrated-tools-comparing-windows-monitoring-systems/"><u>The Underrated Tools: Comparing Windows' Monitoring Systems</u></a></li>
<li><a href="https://win11.techidaily.com/transform-laggard-video-quality-with-windows-madvr/"><u>Transform Laggard Video Quality with Windows MadVR</u></a></li>
<li><a href="https://win11.techidaily.com/tweak-improve-keyboard-shortcut-responsiveness-win-11-style/"><u>Tweak: Improve Keyboard Shortcut Responsiveness, Win 11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-perpetual-inactivity-in-windows-11s-defender-feature/"><u>Unlocking Perpetual Inactivity in Windows 11'S Defender Feature</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11-files-how-to-correctly-handle-access-denied-errors/"><u>Unlocking Windows 11 Files: How to Correctly Handle Access Denied Errors</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-essential-tools-your-guide-to-zero-cost-win11-power/"><u>Unveiling Essential Tools: Your Guide to Zero-Cost Win11 Power</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unveiling-the-10-best-free-os-agnostic-video-solutions/"><u>Unveiling the 10 Best Free OS-Agnostic Video Solutions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-nokia-c02-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Nokia C02? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-image-scaling-find-your-perfect-size-with-these-six-tips/"><u>Windows 11 Image Scaling: Find Your Perfect Size With These Six Tips</u></a></li>
<li><a href="https://win11.techidaily.com/windows-12x-steam-deck-step-by-step-guide/"><u>Windows 12X Steam Deck: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/windows-photos-magic-mastering-ctrl-combinations/"><u>Windows Photos Magic: Mastering Ctrl Combinations</u></a></li>
</ul></div>
