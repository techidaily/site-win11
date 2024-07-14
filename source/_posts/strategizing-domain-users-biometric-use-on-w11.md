---
title: Strategizing Domain Users' Biometric Use on W11
date: 2024-07-13T11:00:40.188Z
updated: 2024-07-14T11:00:40.188Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategizing Domain Users' Biometric Use on W11
excerpt: This Article Describes Strategizing Domain Users' Biometric Use on W11
keywords: Biometrics for Domains,User Authentication,Secure Login Systems,Identity Verification Tech,Advanced Access Controls,Innovative Domain Security,W11 Biometric Integration
thumbnail: https://thmb.techidaily.com/8f13b229b4309cc607ca12c22275ed95f06f33bc5a9a2ad4f10fdb3f8f16d4fd.jpeg
---

## Strategizing Domain Users' Biometric Use on W11

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

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

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
<li><a href="https://win11.techidaily.com/refreshing-window-icons-on-windows/"><u>Refreshing Window Icons on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/upgrade-your-task-management-easy-run-tool-integration-on-windows/"><u>Upgrade Your Task Management: Easy Run Tool Integration on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/from-blank-canvases-to-dynamic-displays-on-win-1011/"><u>From Blank Canvases to Dynamic Displays on Win 10/11</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-gionee-f3-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/pro-tips-show-more-pins-on-windows-11-start/"><u>Pro Tips: Show More Pins on Windows 11 Start</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-bandicut-video-editor-download-and-review-for-2024/"><u>New Bandicut Video Editor Download and Review for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/pro-tips-for-maximizing-speed-and-efficiency-in-3d-painting/"><u>Pro Tips for Maximizing Speed and Efficiency in 3D Painting</u></a></li>
<li><a href="https://change-location.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-determining-the-right-price-point-for-youtubers/"><u>[Updated] 2024 Approved  Determining the Right Price Point for YouTubers</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-not-recognized-fix-for-windows-users/"><u>Overcoming Device Not Recognized: Fix for Windows Users</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-transform-your-tiktok-profile-with-these-cutting-edge-pfps/"><u>[New] In 2024, Transform Your TikTok Profile with These Cutting-Edge PFPs</u></a></li>
<li><a href="https://win11.techidaily.com/insightful-analysis-hibernations-role-in-windows/"><u>Insightful Analysis: Hibernation's Role in Windows</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/0-free-youtube-channels-for-exceptional-art-creation-for-2024/"><u>Top 10 FREE YouTube Channels for Exceptional Art Creation for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-the-fn-key-operations-and-tips/"><u>Utilizing the FN Key: Operations and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-io-errors-in-photo-import-from-apple-devices/"><u>Essential Fixes for I/O Errors in Photo Import From Apple Devices</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functioning-automated-rules-in-microsoft-outlook/"><u>Restoring Functioning Automated Rules in Microsoft Outlook</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-flickering-camera-lights-to-financial-highlights/"><u>[New] In 2024, From Flickering Camera Lights to Financial Highlights</u></a></li>
<li><a href="https://win11.techidaily.com/windows-cab-files-explained-formatting-and-implementation/"><u>Windows CAB Files Explained: Formatting and Implementation</u></a></li>
<li><a href="https://win11.techidaily.com/from-start-menu-to-control-panel-a-guide/"><u>From Start Menu to Control Panel: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/making-your-windows-11-pin-more-secure-and-elongated/"><u>Making Your Windows 11 PIN More Secure & Elongated</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-enabling-windows-11-toolbar-elements/"><u>Guide to Enabling Windows 11 Toolbar Elements</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-non-automatic-timezone-change/"><u>Overcoming Windows' Non-Automatic Timezone Change</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/meme-magic-iphone-edition-for-2024/"><u>Meme Magic  IPhone Edition for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-logic-x-layers-building-audio-bridges-with-crossfades/"><u>In 2024, Logic X Layers  Building Audio Bridges with Crossfades</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-best-microphone-combinations-for-superior-4k-audio-and-visuals/"><u>In 2024, Best Microphone Combinations for Superior 4K Audio and Visuals</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-and-fixing-the-windows-update-hurdles/"><u>Breaking Down and Fixing the Windows Update Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-no-logging-in-run-commands-on-pcs/"><u>Fixing No Logging in Run Commands on PCs</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-ranking-the-top-hand-drawn-whiteboard-animation-software/"><u>2024 Approved Ranking the Top Hand-Drawn Whiteboard Animation Software</u></a></li>
<li><a href="https://win11.techidaily.com/harness-the-power-of-github-desktop-for-windows-os-devops/"><u>Harness the Power of GitHub Desktop for Windows OS DevOps</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-infinix-zero-30-5g-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Infinix Zero 30 5G Phone</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-nvidias-geforce-error-x0001-on-windows-1011/"><u>Steps to Fix Nvidia's GeForce Error X0001 on Windows 10/11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-crafting-dynamic-youtube-content-as-animated-gifs-without-downloads/"><u>In 2024, Crafting Dynamic YouTube Content as Animated GIFs Without Downloads</u></a></li>
<li><a href="https://win11.techidaily.com/cure-for-mcuicntexe-entry-point-loss-in-windows-systems/"><u>Cure for McUICnt.exe Entry Point Loss in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-code-0x0000004e-hiccups/"><u>Resolving Windows Code 0X0000004E Hiccups</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-comprehensible-guide-to-efficient-zoom-capturing/"><u>[Updated] In 2024, Comprehensible Guide to Efficient Zoom Capturing</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/crafting-high-impact-video-marketing-content-on-youtube-for-2024/"><u>Crafting High Impact Video Marketing Content on YouTube for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/free-mindset-audio-selection/"><u>Free Mindset Audio Selection</u></a></li>
<li><a href="https://win11.techidaily.com/expertly-navigate-and-enhance-text-via-the-snipping-tool/"><u>Expertly Navigate and Enhance Text via the Snipping Tool</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-periscope-broadcasts-setting-up-for-success/"><u>In 2024, Periscope Broadcasts  Setting Up for Success</u></a></li>
</ul></div>
