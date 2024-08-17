---
title: Addressing High RAM Demand of User Service on Platforms
date: 2024-08-15T23:18:34.173Z
updated: 2024-08-16T23:18:34.173Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing High RAM Demand of User Service on Platforms
excerpt: This Article Describes Addressing High RAM Demand of User Service on Platforms
keywords: High RAM Usage,User Service Limit,Platform Performance,RAM Management Strategies,Optimized Service Efficiency,Enhancing System Speed,Resource Allocation Balance
thumbnail: https://thmb.techidaily.com/1c82bb77bafb99b9b6611b5302d1fb010d446c70d3f6bad7daef0045c02e4cb1.png
---

## Addressing High RAM Demand of User Service on Platforms

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
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)
<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-information.techidaily.com/new-best-software-and-techniques-for-film-from-photos/"><u>[New] Best Software and Techniques for Film From Photos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-prime-acoustic-collectors-at-schools-for-2024/"><u>[New] Prime Acoustic Collectors at Schools for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-stay-controlled-online-guide-to-blocking-distracting-youtube-channels/"><u>[New] Stay Controlled Online  Guide to Blocking Distracting YouTube Channels</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-captivating-hearts-and-minds-top-20-innovative-tiktok-captions/"><u>[Updated] 2024 Approved  Captivating Hearts and Minds  Top 20 Innovative TikTok Captions</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-all-about-stardew-valley-on-the-mysterious-ginger-island/"><u>[Updated] In 2024, All About Stardew Valley on the Mysterious Ginger Island</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-unlock-the-power-scriptwriting-for-popular-vlogs/"><u>[Updated] In 2024, Unlock the Power  Scriptwriting for Popular Vlogs</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-proven-performers-the-best-of-8-mirrorless-cameras-for-video-creators/"><u>[Updated] Proven Performers  The Best of 8 Mirrorless Cameras for Video Creators</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-airwaves-to-your-iphone-mastery-of-podcast-downloads/"><u>2024 Approved  From Airwaves to Your iPhone  Mastery of Podcast Downloads</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-plunge-into-a-live-stream-on-tiktok-with-ease/"><u>2024 Approved  Plunge Into a Live Stream on TikTok with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/4-easy-ways-to-create-a-new-folder-in-windows-11/"><u>4 Easy Ways to Create a New Folder in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-blueprint-for-an-enhanced-taskbar-in-microsofts-next-windows-release/"><u>A Blueprint for an Enhanced Taskbar in Microsoft's Next Windows Release</u></a></li>
<li><a href="https://fox-info.techidaily.com/best-windows-sketchpad-selections-cost-free-and-premium-plans-for-2024/"><u>Best Windows Sketchpad Selections  Cost-Free & Premium Plans for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-and-correcting-not-working-error-in-windows/"><u>Breaking Down and Correcting 'Not Working' Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-onedrive-and-microsoft-id-for-pc-users/"><u>Bridging the Gap: OneDrive & Microsoft ID for PC Users</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/building-captivating-online-media-summaries/"><u>Building Captivating Online Media Summaries</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-server-stumbled-glitches-win-1111-store-correction-guide/"><u>Bypassing 'Server Stumbled' Glitches: Win 11/11 Store Correction Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-driverpowerstatefailure-a-complete-repair-manual/"><u>Bypassing DRIVER_POWER_STATE_FAILURE: A Complete Repair Manual</u></a></li>
<li><a href="https://win11.techidaily.com/crack-the-ms-pc-manager-install-issue-on-windows-xp/"><u>Crack the MS PC Manager Install Issue on Windows XP</u></a></li>
<li><a href="https://win11.techidaily.com/decrypting-wacatacbml-trojan-a-step-by-step-windows-cleanup/"><u>Decrypting Wacatac.B!ml Trojan: A Step-by-Step Windows Cleanup</u></a></li>
<li><a href="https://program-issues.techidaily.com/effective-strategies-for-resolving-the-terminal-ark-system-crashes/"><u>Effective Strategies for Resolving the Terminal 'Ark' System Crashes</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/efficiently-unshare-content-on-tiktok-mastering-the-undo-feature/"><u>Efficiently Unshare Content on TikTok: Mastering the Undo Feature</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/elevate-content-appeal-with-these-essential-5-tiktok-caption-techniques/"><u>Elevate Content Appeal with These Essential 5 TikTok Caption Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/essential-reasons-why-pcs-outshine-macs-9/"><u>Essential Reasons Why PCs Outshine Macs (#9)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/expert-endorsed-srs-conversions-for-macwin-users/"><u>Expert-Endorsed SRS Conversions for Mac/Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/five-smart-choices-of-windows-devices/"><u>Five Smart Choices of Windows Devices</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/from-making-dreams-real-steps-towards-becoming-a-vtuber-for-2024/"><u>From Making Dreams Real  Steps Towards Becoming a VTuber for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/guide-to-modernize-your-msi-bravos-drivers/"><u>Guide to Modernize Your MSI Bravo's Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-customize-your-outlook-calendar-on-windows/"><u>How to Customize Your Outlook Calendar on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-extend-a-volume-on-windows-without-erasing-personal-data/"><u>How to Extend a Volume on Windows Without Erasing Personal Data</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-upscale-your-old-videos-with-madvr-for-windows/"><u>How to Upscale Your Old Videos With MadVR for Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-xiaomi-redmi-note-12-4g-fix-now-drfone-by-drfone-virtual-android/"><u>In 2024, 3uTools Virtual Location Not Working On Xiaomi Redmi Note 12 4G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-mastering-video-capturing-across-devices-and-platforms/"><u>In 2024, Mastering Video Capturing Across Devices and Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-settings-managing-device-permissions/"><u>Navigating Windows Settings: Managing Device Permissions</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-2024-approved-how-to-make-an-adorable-video-for-your-babys-first-year/"><u>New 2024 Approved How to Make an Adorable Video for Your Babys First Year</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unwanted-windows-start-up-in-bios-landing/"><u>Overcoming Unwanted Windows Start-Up in BIOS Landing</u></a></li>
<li><a href="https://win11.techidaily.com/rearranging-display-panel-configurations/"><u>Rearranging Display Panel Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unable-to-open-error-in-geforce-experience-windows/"><u>Resolving Unable to Open Error in GeForce Experience Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restarting-routine-efficiently-installing-windows-11/"><u>Restarting Routine: Efficiently Installing Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-error-code-0x80070570-repair-corrupted-filesdirectories/"><u>Reversing Error Code 0X80070570: Repair Corrupted Files/Directories</u></a></li>
<li><a href="https://win11.techidaily.com/risks-and-precautions-deleting-windows-bt-folder/"><u>Risks & Precautions: Deleting Windows ~BT Folder</u></a></li>
<li><a href="https://win11.techidaily.com/silence-non-pertinent-windows-advisory-messages/"><u>Silence Non-Pertinent Windows Advisory Messages</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-error-0xfffffff-with-ease/"><u>Solving Windows' Error 0xFFFFFFF with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-file-format-alterations-on-your-pc/"><u>Streamline File Format Alterations on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-deletion-with-windows-context-add-ons/"><u>Streamlining Deletion with Windows Context Add-Ons</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-notification-interface-in-win-11/"><u>Tailoring Your Notification Interface in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-future-is-now-microsofts-new-ai-enhanced-taskbar-for-windows-11-users/"><u>The Future Is Now: Microsoft’s New AI-Enhanced Taskbar for Windows 11 Users</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/the-viral-trend-you-need-to-try-here-it-is/"><u>The Viral Trend You Need to Try - Here It Is</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-apple-iphone-14-pro-max-drfone-by-drfone-virtual-ios/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Apple iPhone 14 Pro Max | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-entertainment-localized-live-streams-in-the-digital-age-2024/"><u>Top Entertainment  Localized Live Streams in the Digital Age, 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/twilight-assessment-diverse-ideas/"><u>Twilight Assessment  Diverse Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-tech-appbrowser-rule/"><u>Understanding Windows Tech: App/Browser Rule</u></a></li>
<li><a href="https://extra-information.techidaily.com/unearthing-the-untouched-public-domains-hidden-gems/"><u>Unearthing the Untouched  Public Domain's Hidden Gems</u></a></li>
</ul></div>
