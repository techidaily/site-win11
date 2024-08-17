---
title: "Improving Performance: Managing Memory Usage for Connected Services"
date: 2024-08-16T00:40:39.344Z
updated: 2024-08-17T00:40:39.344Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Improving Performance: Managing Memory Usage for Connected Services"
excerpt: "This Article Describes Improving Performance: Managing Memory Usage for Connected Services"
keywords: Memory Management,Service Efficiency,Performance Optimization,Data Usage Control,Connectivity Enhancement,Resource Allocation,Streamlining Services
thumbnail: https://thmb.techidaily.com/b38051c9d12a2b8d1315fdc2f1d84dde69fd749e096f758fd9b3624bcd8211ec.jpg
---

## Improving Performance: Managing Memory Usage for Connected Services

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-guidance.techidaily.com/updated-social-media-synergy-linking-instagram-with-tiktok/"><u>[Updated] Social Media Synergy  Linking Instagram with TikTok</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/5-solutions-for-realme-gt-3-unlock-without-password-by-drfone-android/"><u>5 Solutions For Realme GT 3 Unlock Without Password</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-clandestine-windows-11-taskbar-seeker/"><u>Accessing Clandestine Windows 11 Taskbar Seeker</u></a></li>
<li><a href="https://win11-tips.techidaily.com/advanced-text-hotkeys-setup-for-custom-snip-tapping-in-win11/"><u>Advanced Text Hotkeys Setup for Custom Snip Tapping in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-descriptive-folders-in-windows-11/"><u>Boosting Productivity with Descriptive Folders in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-disallowed-label-on-windows-programs/"><u>Clearing Disallowed Label on Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/continuous-edge-background-on-windows-11-tips/"><u>Continuous Edge Background on Windows 11 - Tips</u></a></li>
<li><a href="https://win11.techidaily.com/diving-into-shortened-terms-alias-and-application-lifecycle/"><u>Diving Into Shortened Terms: Alias & Application Lifecycle</u></a></li>
<li><a href="https://extra-hints.techidaily.com/essential-guide-to-rapid-signature-removal/"><u>Essential Guide to Rapid Signature Removal</u></a></li>
<li><a href="https://win-answers.techidaily.com/fix-frontier-no-longer-crashing-on-your-pc-complete-guide/"><u>Fix Frontier No Longer Crashing on Your PC - Complete Guide!</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-disconnect-error-during-discord-setup-in-windows-os/"><u>Fixing Disconnect Error During Discord Setup in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-win1011-unraveling-error-code-0x800704b3/"><u>Fixing Win10/11: Unraveling Error Code 0X800704B3</u></a></li>
<li><a href="https://win11.techidaily.com/future-proof-your-pc-take-advantage-of-windows-11-h2-update-plan/"><u>Future-Proof Your PC: Take Advantage of Windows 11 H2 Update Plan</u></a></li>
<li><a href="https://win11.techidaily.com/guide-stop-hyber-v-with-ease-in-windows-11-pro/"><u>Guide: Stop Hyber-V with Ease in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-camera-apps-0xa00f429f-error-in-windows-11-and-11/"><u>How to Fix the Camera App’s 0xA00F429F Error in Windows 11 & 11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/how-to-use-aiseesoft-screen-recorder/"><u>How to Use Aiseesoft Screen Recorder</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-vivo-y36i-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Vivo Y36i FRP Locks</u></a></li>
<li><a href="https://win11.techidaily.com/instant-repair-tactics-for-windows-photo-app-malfunctions/"><u>Instant Repair Tactics for Windows Photo App Malfunctions</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-the-efficacy-of-windows-11s-feature-additions/"><u>Investigating the Efficacy of Windows 11'S Feature Additions</u></a></li>
<li><a href="https://tech-revival.techidaily.com/latest-update-unveils-exciting-chatgpt-enhancements-discover-what-matters-most/"><u>Latest Update Unveils Exciting ChatGPT Enhancements – Discover What Matters Most</u></a></li>
<li><a href="https://win11.techidaily.com/path-pursuit-6-efficient-strategies-for-copying-file-and-folder-paths-in-windows-11/"><u>Path Pursuit: 6 Efficient Strategies for Copying File and Folder Paths in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/proven-steps-for-clearer-images-using-windows-11s-background-blur-feature-in-the-app/"><u>Proven Steps for Clearer Images Using Windows 11'S Background Blur Feature in the App</u></a></li>
<li><a href="https://win11.techidaily.com/resizing-desktop-picture-summaries-in-win11/"><u>Resizing Desktop Picture Summaries in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-the-settings-retrieval-unsuccessful-problem-on-windows-11/"><u>Reversing the Settings Retrieval Unsuccessful Problem on Windows 11</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/review-of-criacr-fm-bluetooth-transmitter-model-cp24-small-design-notable-issues/"><u>Review of Criacr FM Bluetooth Transmitter Model CP24: Small Design, Notable Issues</u></a></li>
<li><a href="https://win11.techidaily.com/securely-manage-tasks-as-an-admin-in-windows-11/"><u>Securely Manage Tasks as an Admin in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-effective-rgb-light-settings-in-win11/"><u>Tips for Effective RGB Light Settings in Win11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/top-30-metaverse-memes-crafting-hilarious-digital-delights/"><u>Top 30 Metaverse Memes  Crafting Hilarious Digital Delights</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-power-of-windows-11-quick-selective-copy-and-move/"><u>Unlock the Power of Windows 11: Quick Selective Copy & Move</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-6-factors-that-favor-windows-11/"><u>Unraveling 6 Factors That Favor Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-connectivity-issues-with-spotify-and-windows-11/"><u>Unraveling Connectivity Issues with Spotify & Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-lan-play-fixes-for-no-connection-woes/"><u>Winning at LAN Play: Fixes for No Connection Woes</u></a></li>
</ul></div>
