---
title: Biometric Management for Windows 11, Domain-Based
date: 2024-08-15T23:46:27.603Z
updated: 2024-08-16T23:46:27.603Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Biometric Management for Windows 11, Domain-Based
excerpt: This Article Describes Biometric Management for Windows 11, Domain-Based
keywords: Win11 Biometrics Secure,Domain-Based Biometric,Windows Security Key,PC Biometric Access,Windows 11 Identity,Domain Authentication,Windows ID Management
thumbnail: https://thmb.techidaily.com/0f08e68155172a78a589fb6b8f18fbb5a0a1a4069ed8867faff7b1ab4f999000.jpg
---

## Biometric Management for Windows 11, Domain-Based

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/new-exploring-the-depths-of-adobe-cloud-storages-plus-top-non-adobe-choices/"><u>[New] Exploring the Depths of Adobe Cloud Storages, Plus Top Non-Adobe Choices</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-god-of-thunder-returns-epic-dawn/"><u>[New] God of Thunder Returns  Epic Dawn</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-film-lovers-answers-repository/"><u>[New] In 2024, Film Lovers' Answers Repository</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-the-complete-picture-toolwizs-app-masterclass/"><u>[New] In 2024, The Complete Picture  Toolwiz's App Masterclass</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-understanding-youtubes-earnings-structure/"><u>[New] Understanding YouTube's Earnings Structure</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-fashion-filming-simplified-for-macos-users/"><u>[Updated] Fashion Filming Simplified for MacOS Users</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-hush-harmony-techniques-for-taming-unwanted-voices-on-gchat/"><u>[Updated] Hush Harmony  Techniques for Taming Unwanted Voices on GChat</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-tailored-interventions/"><u>[Updated] In 2024, Tailored Interventions</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-youtube-mastery-how-to-add-structure-and-subdivisions-for-enhanced-content/"><u>[Updated] In 2024, YouTube Mastery  How to Add Structure and Subdivisions for Enhanced Content</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-learn-how-to-optimize-your-screen-record-with-screencastify/"><u>[Updated] Learn How to Optimize Your Screen Record with Screencastify</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-mastering-igtv-sharing-via-insta-stories/"><u>[Updated] Mastering IGTV Sharing via Insta Stories</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-streamline-iphone-videos-size-and-length-optimization/"><u>2024 Approved  Streamline iPhone Videos  Size & Length Optimization</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-understanding-ffpm-in-firefox-today/"><u>2024 Approved  Understanding FFPM in Firefox Today</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-bypass-activation-lock-from-iphone-13-mini-by-drfone-ios/"><u>3 Effective Ways to Bypass Activation Lock from iPhone 13 mini</u></a></li>
<li><a href="https://win11.techidaily.com/5-simple-ways-to-unlock-startup-repairs-in-windows/"><u>5 Simple Ways to Unlock Startup Repairs in Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/achieve-synchronicity-with-your-browser-and-fbs-autoplay-feature/"><u>Achieve Synchronicity with Your Browser and FB's Autoplay Feature</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-git-proficiency-with-github-desktop-on-windows-11/"><u>Boost Your Git Proficiency with Github Desktop on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/discover-your-device-the-ultimate-guide-for-model-names/"><u>Discover Your Device: The Ultimate Guide for Model Names</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-redesigned-windows-11-widget-pickers/"><u>Enabling Redesigned Windows 11 Widget Pickers</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-edge-browsing-experience-on-win10w11/"><u>Enhance Your Edge Browsing Experience on Win10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-fix-windows-key-problems/"><u>Essential Steps to Fix Windows Key Problems</u></a></li>
<li><a href="https://win-forum.techidaily.com/expedite-windows-11s-startup-time-with-advanced-techniques-from-revo-uninstaller/"><u>Expedite Windows 11'S Startup Time with Advanced Techniques From Revo Uninstaller</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-accurate-mac-location-techniques-in-windows-11/"><u>Expert Insights: Accurate MAC Location Techniques in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-11s-foundation-a-deep-dive-into-its-registry/"><u>Exploring Windows 11'S Foundation: A Deep Dive Into Its Registry</u></a></li>
<li><a href="https://win11.techidaily.com/from-digital-tunes-to-physical-form-transforming-your-mp3s-on-pc-using-imgburn-windows/"><u>From Digital Tunes to Physical Form: Transforming Your MP3s on PC Using ImgBurn (Windows)</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-lava-storm-5g-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Lava Storm 5G to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-nvidia-cp-access-denied-in-win1110/"><u>How to Overcome NVidia CP Access Denied in Win11/10</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-tecno-spark-10-4g-by-fonelab-android-recover-video/"><u>How to recover old videos from your Tecno Spark 10 4G</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-13-pro-max-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 13 Pro Max without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-passfab-iphone-13-pro-backup-unlocker-top-4-alternatives-drfone-by-drfone-ios/"><u>In 2024, PassFab iPhone 13 Pro Backup Unlocker Top 4 Alternatives | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-ultimate-vr-selection-top-8-must-have-titles/"><u>In 2024, Ultimate VR Selection  Top 8 Must-Have Titles</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-unleashing-creativity-quick-lens-building-on-snapchat/"><u>In 2024, Unleashing Creativity  Quick Lens Building on Snapchat</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-maneuvers-to-navigate-stalled-windows-install-steps/"><u>Masterful Maneuvers to Navigate Stalled Windows Install Steps</u></a></li>
<li><a href="https://win11.techidaily.com/max-out-your-games-on-windows-the-amd-optimization-guide/"><u>Max Out Your Games on Windows: The AMD Optimization Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-spotify-connection-failures-on-win11/"><u>Navigating Through Spotify Connection Failures on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-detection-issues-with-razer-on-windows-11/"><u>Overcoming Device Detection Issues with Razer on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdles-of-reverting-folders-to-read-only/"><u>Overcoming the Hurdles of Reverting Folders to Read-Only</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-error-codes-0xc0000001-guide/"><u>Overcoming Windows Error Codes - 0xC0000001 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-footage-the-ultimate-selection-of-video-cutters-on-win11/"><u>Perfect Your Footage: The Ultimate Selection of Video Cutters on Win11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/prime-video-broadcast-software-choice-for-2024/"><u>Prime Video Broadcast Software Choice for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/purging-power-users-the-guide-to-default-settings/"><u>Purging Power Users: The Guide to Default Settings</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quick-and-simple-guide-how-to-update-your-windows-laptops-battery-drivers/"><u>Quick and Simple Guide: How to Update Your Windows Laptop's Battery Drivers</u></a></li>
<li><a href="https://fix-guide.techidaily.com/quick-fixes-for-why-is-my-oppo-f23-5g-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Oppo F23 5G Black and White | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolving-intermittent-audio-dropping-issues-in-windows-11-a-comprehensive-guide/"><u>Resolving Intermittent Audio Dropping Issues in Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-lost-thx-audio-functionality-in-windows/"><u>Restoring Lost THX Audio Functionality in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-the-email-fault-caused-by-0x800713f-on-win11/"><u>Steps to Solve the Email Fault Caused by 0X800713F on Win11</u></a></li>
<li><a href="https://some-tips.techidaily.com/strategies-for-lengthening-gopros-electric-life-for-2024/"><u>Strategies for Lengthening GoPro's Electric Life for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-webcam-shutdown/"><u>Strategies for Overcoming Webcam Shutdown</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-connection-between-win-code-and-microsoft-services/"><u>Streamlining Connection Between WIN Code and Microsoft Services</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-geforce-failures-head-on-today/"><u>Tackle Windows GeForce Failures Head-On Today</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-amd-195-error-in-windows-installations/"><u>Tackling AMD 195 Error in Windows Installations</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-common-management-tool-hurdles-in-windows-11/"><u>Tackling Common Management Tool Hurdles in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-need-privilege-escalation-issue-fixing-error-740/"><u>Tackling Need Privilege Escalation Issue: Fixing Error 740</u></a></li>
<li><a href="https://win11.techidaily.com/teams-growth-without-the-heavy-load/"><u>Teams Growth Without the Heavy Load</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-fix-wrongly-entered-characters-in-windows/"><u>Tips to Fix Wrongly Entered Characters in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-methods-for-eliminating-windows-errors/"><u>Top 8 Methods for Eliminating Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-techniques-windows-sandbox-lacks-hyprocvisor/"><u>Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tutorial-to-change-nokia-c12-pro-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>Tutorial to Change Nokia C12 Pro IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-correcting-windows-install-errors-win11/"><u>Understanding and Correcting Windows Install Errors (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-potential-of-batch-files-via-exes/"><u>Unlock the Potential of Batch Files via EXEs</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-quietude-in-quarter-notes-advanced-methods-for-drum-ditching-in-digital-music/"><u>Updated 2024 Approved Quietude in Quarter Notes Advanced Methods for Drum Ditching in Digital Music</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-windows-11-to-advanced-auditory-features-dolby-atmos/"><u>Upgrading Windows 11 to Advanced Auditory Features (Dolby Atmos)</u></a></li>
</ul></div>
