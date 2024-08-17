---
title: Mastering the Biometric Settings of W11 for Domains
date: 2024-08-16T00:34:42.326Z
updated: 2024-08-17T00:34:42.326Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Biometric Settings of W11 for Domains
excerpt: This Article Describes Mastering the Biometric Settings of W11 for Domains
keywords: BioSecure W11 Domain Config,W11 Biometrics Mastery,Enhanced Domain Security,W11 Identity Authentication,Optimize W11 Settings,Advanced Biometric Domains,Tailored W11 Safeguards
thumbnail: https://thmb.techidaily.com/73087a990223851f6a7c5417d3512a4d93ddbbb6cac79840abc644367d7f8449.jpg
---

## Mastering the Biometric Settings of W11 for Domains

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
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-enhancing-video-production-quality-top-5-strategies-for-obs-users/"><u>[New] 2024 Approved  Enhancing Video Production Quality  Top 5 Strategies for OBS Users</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-the-essential-enhancements-for-a-superstar-stardew-fan/"><u>[New] 2024 Approved  The Essential Enhancements for a Superstar Stardew Fan</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-navigating-the-path-to-facebooks-exclusive-verified-marker/"><u>[New] Navigating the Path to Facebook's Exclusive Verified Marker</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-top-5-best-ps2-emulator-for-ios/"><u>[New] Top 5 Best PS2 Emulator for Ios</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-calls-recorded-and-saved-iphone-24-sound-guide/"><u>[Updated] Calls Recorded & Saved  IPhone '24 Sound Guide</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-dialogue-enrichment-system/"><u>[Updated] Dialogue Enrichment System</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-enhancing-speeds-a-safe-guide-for-rapid-music-streaming/"><u>[Updated] Enhancing Speeds  A Safe Guide for Rapid Music Streaming</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-achieve-synchronicity-with-your-browser-and-fbs-autoplay-feature/"><u>[Updated] In 2024, Achieve Synchronicity with Your Browser and FB's Autoplay Feature</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-top-tier-video-capture-tools-for-pc-users/"><u>[Updated] In 2024, Top-Tier Video Capture Tools for PC Users</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-instagrams-hottest-25-minds-in-the-digital-age-for-2024/"><u>[Updated] Instagram's Hottest 25 Minds in the Digital Age for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-past-perspectives-unencumbered-visual-splendors/"><u>[Updated] Past Perspectives  Unencumbered Visual Splendors</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/10-best-free-movies-on-youtube-for-time-killing-2024/"><u>10 Best Free Movies on YouTube for Time Killing 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-snapit-share-it-in-order-on-ig/"><u>2024 Approved  SnapIt, Share It in Order on IG</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-path-not-found-on-pc-networks/"><u>Addressing Path Not Found on PC Networks</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-motorola-moto-g23-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Motorola Moto G23 Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-read-only-shackles-of-windows-11/"><u>Breaking Free From the Read-Only Shackles of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-fixing-winget-on-w11/"><u>Comprehensive Guide to Fixing Winget on W11</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-instructions-eradicating-wsl-from-windows/"><u>Comprehensive Instructions: Eradicating WSL From Windows</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-workspace-incorporating-sketches-into-windows-11/"><u>Customize Your Workspace: Incorporating Sketches Into Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/deleting-windows-bt-directory-purpose-and-process/"><u>Deleting Windows ~BT Directory: Purpose & Process</u></a></li>
<li><a href="https://win11.techidaily.com/easing-frustrations-with-a-fix-to-non-working-pen-devices-in-windows/"><u>Easing Frustrations with a Fix to Non-Working Pen Devices in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/effective-strategies-to-dial-down-memorycpu-in-windows/"><u>Effective Strategies to Dial Down Memory/CPU in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-techniques-for-inspecting-and-cleansing-windows-trail/"><u>Efficient Techniques for Inspecting & Cleansing Windows Trail</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-rgb-customization-on-your-win11-device/"><u>Enabling RGB Customization on Your Win11 Device</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/free-sound-effects-for-video-editing-a-comprehensive-guide-for-final-cut-pro-users/"><u>Free Sound Effects for Video Editing A Comprehensive Guide for Final Cut Pro Users</u></a></li>
<li><a href="https://win11.techidaily.com/freedomgpt-for-pc-running-ai-conversation-tools/"><u>FreedomGPT for PC: Running AI Conversation Tools</u></a></li>
<li><a href="https://win11.techidaily.com/hasten-enablingdisabling-microsofts-bing-assistant-in-taskbar/"><u>Hasten Enabling/Disabling: Microsoft's Bing Assistant in Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-achieve-a-seamless-experience-less-latency-more-fps/"><u>How to Achieve a Seamless Experience: Less Latency, More FPS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-cut-off-others-access-in-the-windows-network/"><u>How to Cut Off Others' Access in the WIndows Network</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-volume-control-slider-not-working-in-windows-11-and-11/"><u>How to Fix the Volume Control Slider Not Working in Windows 11 & 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-vcruntime140dll-missing-error-in-windows-applications/"><u>How To Resolve vcruntime140.dll Missing Error in Windows Applications</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-unbrick-a-dead-infinix-hot-40-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Unbrick a Dead Infinix Hot 40 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-steps-to-clear-up-steam-errors-in-games-on-windows/"><u>Immediate Steps to Clear Up Steam Errors in Games on Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-samsung-galaxy-a15-4g-by-drfone-android/"><u>In 2024, How to Bypass FRP from Samsung Galaxy A15 4G?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-ispoofer-on-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Motorola Moto G14? | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-the-pros-pathway-to-professionalism-making-videos-using-a-phone/"><u>In 2024, The Pro's Pathway to Professionalism  Making Videos Using a Phone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/inspirational-article-leaderboard-maker-for-2024/"><u>Inspirational Article Leaderboard Maker for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-connoisseurs-guide-to-file-details/"><u>Keyboard Connoisseur's Guide to File Details</u></a></li>
<li><a href="https://win11.techidaily.com/mapping-out-gpo-landscape-a-gpresult-perspective/"><u>Mapping Out GPO Landscape: A GPResult Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-effortless-data-purging-in-windows-1011/"><u>Master the Art of Effortless Data Purging in Windows 10/11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-vivo-x100-pro-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Vivo X100 Pro Device</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-troubleshooting-a-guide-to-fixing-windows-11-issues/"><u>Mastering Troubleshooting: A Guide to Fixing Windows 11 Issues</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/navigating-and-interpreting-twitter-archives-for-2024/"><u>Navigating and Interpreting Twitter Archives for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-maze-of-microsoft-powerpoint-prints-on-windows/"><u>Navigating the Maze of Microsoft PowerPoint Prints on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-playstation-services-on-pc-and-laptops/"><u>Quick Fixes for PlayStation Services on PC & Laptops</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-closed-caption-mishaps-in-windows-10/"><u>Resolving Closed Caption Mishaps in Windows 10</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/rotation-revelations-maximizing-media-experience-with-vlc-for-2024/"><u>Rotation Revelations  Maximizing Media Experience with VLC for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-files-navigate-smaller-with-windows-explorer/"><u>Simplifying Files: Navigate Smaller with Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-the-task-of-updating-administrator-name-on-windows-11/"><u>Simplifying the Task of Updating Administrator Name on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/1719298315535-solving-your-full-screen-capture-predicament-with-snip-and-sketch/"><u>Solving Your Full-Screen Capture Predicament with Snip & Sketch.</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-process-implementing-custom-lock-patterns-in-windows-11-devices/"><u>Step-by-Step Process: Implementing Custom Lock Patterns in Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-enhance-text-via-snip-tool-features/"><u>Step-by-Step: Enhance Text via Snip Tool Features</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-compatibility-with-photoshop/"><u>Steps to Overcome Windows Compatibility with Photoshop</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-increase-windows-disk-size-securely/"><u>Strategies to Increase Windows Disk Size Securely</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-resolve-iomap64-bsod-errors-in-windows-108/"><u>Strategies to Resolve IOMap64 BSOD Errors in Windows 10/8</u></a></li>
<li><a href="https://win11.techidaily.com/system-rescue-in-13-easy-to-follow-tips/"><u>System Rescue in 13 Easy-to-Follow Tips</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-guide-to-using-github-desktop-for-windows-11-dev-teams/"><u>Tailored Guide to Using GitHub Desktop for Windows 11 Dev Teams</u></a></li>
<li><a href="https://win11.techidaily.com/the-best-file-sharing-software-on-windows-os/"><u>The Best File-Sharing Software on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-with-snipit-try-these-top-tips-for-repairing/"><u>Trouble with SnipIt? Try These Top Tips for Repairing</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlock-your-audio-cues-with-ease-windows-and-os-x-guide-to-srt-for-2024/"><u>Unlock Your Audio Cues with Ease  Windows & OS X Guide to SRT for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unlocking-free-animation-digitalphysical-realms-for-2024/"><u>Unlocking Free Animation  Digital/Physical Realms for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-success-removing-0x800700e9-from-your-xbox-game-pass-windows-11-setup/"><u>Unlocking Success: Removing 0X800700E9 From Your Xbox Game Pass, Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-familiarity-top-7-reasons-why-you-love-win10/"><u>Unveiling the Power of Familiarity: Top 7 Reasons Why You Love Win10</u></a></li>
<li><a href="https://win11.techidaily.com/want-to-use-windows-11-without-bloatware-and-stern-hardware-requirements-try-tiny11/"><u>Want to Use Windows 11 Without Bloatware and Stern Hardware Requirements? Try Tiny11</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-honor-70-lite-5g-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Honor 70 Lite 5G Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
</ul></div>
