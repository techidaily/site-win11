---
title: Mastering the Process to Remove WSL From Windows
date: 2024-08-15T23:50:32.999Z
updated: 2024-08-16T23:50:32.999Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Process to Remove WSL From Windows
excerpt: This Article Describes Mastering the Process to Remove WSL From Windows
keywords: Removing WSL Windows,Uninstall WSL Steps,WSL Disablement Guide,Turn Off Windows WSL,Eliminate WSL Process,Deleting WSL Instance,Cease WSL Windows Function
thumbnail: https://thmb.techidaily.com/df6d6f7af97a6f2a263dcbc0519760a864ba0996ca5b9b75ea6d971b44c71c22.jpg
---

## Mastering the Process to Remove WSL From Windows

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.

## Why Uninstall Windows Subsystem for Linux?

 WSL is a very handy tool that allows you to easily run Linux distros in a virtual environment on your Windows computer. Although it doesn't have much impact on storage space, if you have no interest in using Linux, there's no need to have it installed.

 There are also [good alternatives to WSL](https://www.makeuseof.com/dont-need-microsoft-windows-subsystem-for-linux/) for running Linux available, and you might decide to use one of those instead of the Microsoft solution. Not only would you not need WSL, but there is also a slight risk of conflict between the Windows Subsystem and your alternative choice.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Remove All Installed Linux Distros on Windows

 This step won't be relevant to everyone, but if you have installed any Linux distros, you should remove them first. This helps to ensure that no files associated with the Linux installations remain on your computer when you uninstall WSL.

1. You can find your installed Linux distros listed with your other installed apps in **Settings > Apps > Installed Apps**.
2. Uninstall each of the Linux Distros, such as Ubuntu, in exactly the same way you would [uninstall any other Windows app](https://www.makeuseof.com/ways-to-uninstall-apps-windows-11/).

![Ubuntu in the Windows 11 apps list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-remove.jpg)

 If the computer came to you with the apps already installed, you might not know what is or isn't a Linux distribution. Here are some of the [most common Linux distros](https://www.makeuseof.com/linux-distros-for-beginners-intermediate-and-advanced-users/), but you can also simply do a Google search for the name of the app you are unsure about.

 When all versions of Linux have been uninstalled, you can move on to the next step in the process.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
## Uninstall the WSL Components

 With all versions of Linux removed, you can remove the WSL app and its related components. As with the previous step, you can remove WSL in the same way you would remove any other app.

 Go to **Settings > Apps > Apps & Features**. Scroll down to the bottom of your apps list to find Windows Subsystem for Linux. Click the **More** button and select **Uninstall**. On Windows 10, click on the app name and then click **Uninstall**.

![Uninstalling WSL components in Windows settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-components.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->

 If you see any additional WSL components, such as the WSL update or WSLg Preview, uninstall these in the same way.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Uninstall WSL and Virtual Machine Platform

 The final part of the process is to uninstall the WSL core files and disable the option in the Windows Optional Features panel.

1. Open the Windows Features panel by going to **Settings > Apps > Optional Features > More Windows Features**. You can also search for **Windows Features** and click **Turn Windows features on or off**.
2. Scroll down the list of features to find and deselect the **Windows Subsystem for Linux** option.
3. If you don't need to run any other virtual environments, you can also deselect the **Virtual Machine Platform** option.
4. Click **Ok**, and then restart your computer.

![Removing WSL in the Windows Features panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/wsl-core-files.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 WSL should now be completely removed from your computer. It will receive no automatic updates, and you won't be able to interact with it in any way. If you need it in the future, here's how to [install WSL through the Microsoft Store](https://www.makeuseof.com/install-windows-subsystem-for-windows-microsoft-store/) on a Windows PC.

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
## Removing WSL From Your Windows PC

 You can install WSL on your Windows computer with a single command. Uninstalling it, if you no longer need or want it on your PC, is not quite as simple. By following the three simple steps detailed here, you can ensure that all WSL files and components are removed.

 If you don't want or need Windows Subsystem for Linux on your computer, you can remove it. However, that process can include more than just clicking the uninstall button in Windows Settings. It isn't difficult, but it's important to remove files in the correct order.

 Here are the steps you need to follow to completely remove WSL from your Windows PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/024-approved-a-step-by-step-guide-for-earning-with-youtube-shorts/"><u>[New] 2024 Approved  A Step-by-Step Guide for Earning with YouTube Shorts</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-all-about-kinemaster-androids-ultimate-gaming-companion/"><u>[New] All About KineMaster  Android's Ultimate Gaming Companion</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-djis-aviation-innovation-meets-gaming-mavic-air-versus-spark/"><u>[New] In 2024, DJI’s Aviation Innovation Meets Gaming  Mavic Air Versus Spark</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-proactive-copyright-verification-for-your-tiktok-videos/"><u>[New] In 2024, Proactive Copyright Verification for Your TikTok Videos</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-top-free-video-call-apps-versatile-use-on-windows-and-macos/"><u>[New] In 2024, Top Free Video Call Apps  Versatile Use on Windows & MacOS</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/athways-to-youtube-stardom-in-video-games-for-2024/"><u>[New] Pathways to YouTube Stardom in Video Games for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-vocalists-choice-the-finest-9-online-mic-recorders/"><u>[New] Vocalist's Choice  The Finest 9 Online Mic Recorders</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-nvidia-graphics-cards-not-detected-in-windows-111087/"><u>[SOLVED] Nvidia Graphics Cards Not Detected in Windows 11/10/8/7</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-best-tech-in-cards-for-4k-video-editing/"><u>[Updated] Best Tech in Cards  For 4K Video Editing</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-eradicating-youtube-content-in-a-device-friendly-way/"><u>[Updated] Eradicating YouTube Content in a Device-Friendly Way</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-exclusive-guide-ranking-most-effective-ig-money-makers/"><u>[Updated] In 2024, Exclusive Guide  Ranking Most Effective IG Money Makers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-29-how-to-record-free-webinars-with-ease-and-precision/"><u>2024 Approved  29 How-To  Record Free Webinars with Ease and Precision</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-bring-the-chuckles-home-creating-memes-on-demand/"><u>2024 Approved  Bring the Chuckles Home  Creating Memes on Demand</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-spotlight-on-starlets-snippet/"><u>2024 Approved  Spotlight on Starlet's Snippet</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-small-business-video-marketing-playbook/"><u>2024 Approved  The Small Business Video Marketing Playbook</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/assessing-hero9-black-the-gopros-top-tier-device/"><u>Assessing HERO9 Black - The GoPro's Top-Tier Device</u></a></li>
<li><a href="https://fox-access.techidaily.com/best-camcorders-for-deer-stalking-success-for-2024/"><u>Best Camcorders for Deer Stalking Success for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-git-proficiency-with-github-desktop-on-windows-11/"><u>Boost Your Git Proficiency with Github Desktop on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-wsl-2-streamline-docker-usage/"><u>Boosting WSL 2: Streamline Docker Usage</u></a></li>
<li><a href="https://buynow-info.techidaily.com/comprehensive-analysis-of-the-stanley-j5c09-powerful-storage-unit-unveiled/"><u>Comprehensive Analysis of the Stanley J5C09 - Powerful Storage Unit Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/deciding-on-ideal-nvidia-drivers-gaming-vs-production-sector/"><u>Deciding on Ideal Nvidia Drivers: Gaming vs Production Sector</u></a></li>
<li><a href="https://win11.techidaily.com/discover-your-device-the-ultimate-guide-for-model-names/"><u>Discover Your Device: The Ultimate Guide for Model Names</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-edge-browsing-experience-on-win10w11/"><u>Enhance Your Edge Browsing Experience on Win10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-continuity-with-powertoys-settings-transfer/"><u>Ensuring Continuity with PowerToys Settings Transfer</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-fix-windows-key-problems/"><u>Essential Steps to Fix Windows Key Problems</u></a></li>
<li><a href="https://win11.techidaily.com/essential-sync-software-windows-and-android-unite/"><u>Essential Sync Software: Windows & Android Unite</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-accurate-mac-location-techniques-in-windows-11/"><u>Expert Insights: Accurate MAC Location Techniques in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-11s-foundation-a-deep-dive-into-its-registry/"><u>Exploring Windows 11'S Foundation: A Deep Dive Into Its Registry</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-it-realme-gt-5-pro-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Realme GT 5 Pro Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-nvidia-cp-access-denied-in-win1110/"><u>How to Overcome NVidia CP Access Denied in Win11/10</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-your-infinix-smart-7-hd-lock-screen-password-by-drfone-android/"><u>How to Reset your Infinix Smart 7 HD Lock Screen Password</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-complete-mastery-over-picsart-the-ultimate-users-guide/"><u>In 2024, Complete Mastery over PicsArt  The Ultimate User's Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-motorola-moto-g73-5g-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Motorola Moto G73 5G to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-get-and-use-pokemon-go-promo-codes-on-poco-x5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Get and Use Pokemon Go Promo Codes On Poco X5 Pro | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-google-chrome-from-tracking-your-location-on-google-pixel-fold-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop Google Chrome from Tracking Your Location On Google Pixel Fold? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-rewind-and-play-instagrams-backwards-videos-unveiled/"><u>In 2024, Rewind and Play  Instagram's Backwards Videos Unveiled</u></a></li>
<li><a href="https://extra-tips.techidaily.com/learn-how-to-solve-youtube-video-distorted-issue/"><u>Learn How to Solve YouTube Video Distorted Issue</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/leveraging-periscope-for-real-time-engagement-for-2024/"><u>Leveraging Periscope for Real-Time Engagement for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/locating-post-bsod-error-logs-in-windows-explorer/"><u>Locating Post-BSOD Error Logs in Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-maneuvers-to-navigate-stalled-windows-install-steps/"><u>Masterful Maneuvers to Navigate Stalled Windows Install Steps</u></a></li>
<li><a href="https://win-blog.techidaily.com/mastering-the-field-again-mlb-the-show-21-server-problems-solved/"><u>Mastering the Field Again: MLB The Show 21 Server Problems Solved</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-0xc00000f-errors-in-windows-os/"><u>Navigating Through 0Xc00000f Errors in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-spotify-connection-failures-on-win11/"><u>Navigating Through Spotify Connection Failures on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-detection-issues-with-razer-on-windows-11/"><u>Overcoming Device Detection Issues with Razer on Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-persistent-freezing-in-overwatch-solutions-that-work/"><u>Overcoming Persistent Freezing in Overwatch: Solutions That Work</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdles-of-reverting-folders-to-read-only/"><u>Overcoming the Hurdles of Reverting Folders to Read-Only</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-error-codes-0xc0000001-guide/"><u>Overcoming Windows Error Codes - 0xC0000001 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-footage-the-ultimate-selection-of-video-cutters-on-win11/"><u>Perfect Your Footage: The Ultimate Selection of Video Cutters on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/purging-power-users-the-guide-to-default-settings/"><u>Purging Power Users: The Guide to Default Settings</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-over-your-pcs-touchpad-gestures/"><u>Regaining Control Over Your PC's Touchpad Gestures</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-honor-90-pro-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on Honor 90 Pro</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-nokia-c12-plus-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Nokia C12 Plus</u></a></li>
<li><a href="https://win11.techidaily.com/stay-true-to-tech-avoiding-impostor-apps-on-windows-platform/"><u>Stay True to Tech: Avoiding Impostor Apps on Windows Platform</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-the-email-fault-caused-by-0x800713f-on-win11/"><u>Steps to Solve the Email Fault Caused by 0X800713F on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-webcam-shutdown/"><u>Strategies for Overcoming Webcam Shutdown</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-connection-between-win-code-and-microsoft-services/"><u>Streamlining Connection Between WIN Code and Microsoft Services</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-geforce-failures-head-on-today/"><u>Tackle Windows GeForce Failures Head-On Today</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-amd-195-error-in-windows-installations/"><u>Tackling AMD 195 Error in Windows Installations</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-fix-wrongly-entered-characters-in-windows/"><u>Tips to Fix Wrongly Entered Characters in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-methods-for-eliminating-windows-errors/"><u>Top 8 Methods for Eliminating Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-missing-second-display-on-w11/"><u>Troubleshooting Missing Second Display on W11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-techniques-windows-sandbox-lacks-hyprocvisor/"><u>Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-correcting-windows-install-errors-win11/"><u>Understanding and Correcting Windows Install Errors (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-windows-11-to-advanced-auditory-features-dolby-atmos/"><u>Upgrading Windows 11 to Advanced Auditory Features (Dolby Atmos)</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-a-detailed-settings-app-tour/"><u>Windows 11: A Detailed Settings App Tour</u></a></li>
</ul></div>
