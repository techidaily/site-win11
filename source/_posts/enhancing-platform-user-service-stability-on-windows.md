---
title: Enhancing Platform User Service Stability on Windows
date: 2024-10-11T18:57:14.175Z
updated: 2024-10-15T16:25:45.961Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enhancing Platform User Service Stability on Windows
excerpt: This Article Describes Enhancing Platform User Service Stability on Windows
keywords: WinServiceStabilityBoost,SecureWinOSUX,UptimeWindowsSys,StableWinPlatformUse,EnhancedWinUserSer,WindowsUXStabilityUp,OptimizedWinOSSys
thumbnail: https://thmb.techidaily.com/ed5ee8baad91072b118b2d67f1083103fa228337347cb369c95ebc26efcbbaf5.jpg
---

## Enhancing Platform User Service Stability on Windows

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139558/4704" target="_top" id="2139558">
  <img src="//a.impactradius-go.com/display-ad/4704-2139558" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139558/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997695/19272" target="_top" id="1997695">
  <img src="//a.impactradius-go.com/display-ad/19272-1997695" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997695/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094414/7443" target="_top" id="2094414">
  <img src="//a.impactradius-go.com/display-ad/7443-2094414" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094414/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043603/7443" target="_top" id="2043603">
  <img src="//a.impactradius-go.com/display-ad/7443-2043603" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043603/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-access.techidaily.com/new-2024-approved-10-top-ios-players-elevating-video-watching-on-devices/"><u>[New] 2024 Approved 10 Top iOS Players Elevating Video Watching on Devices</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-the-premier-selection-of-economical-video-collaboration-tools-businesseducation-edition/"><u>[New] 2024 Approved The Premier Selection of Economical Video Collaboration Tools Business/Education Edition</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ap-into-endless-stock-imagery-through-favorite-4-youtube-vids/"><u>[New] Tap Into Endless Stock Imagery Through Favorite 4 Youtube Vids</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-efficient-deletion-techniques-for-online-discussions/"><u>[Updated] In 2024, Efficient Deletion Techniques for Online Discussions</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamlined-process-for-hassle-free-hdr-shots/"><u>2024 Approved Streamlined Process for Hassle-Free HDR Shots</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-techniques-to-soften-volume-peaks-in-lumafusion/"><u>2024 Approved Techniques to Soften Volume Peaks in Lumafusion</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/a-new-era-of-personal-health-monitoring-fitbit-sense-as-the-superior-alternative-to-apple-watch/"><u>A New Era of Personal Health Monitoring: Fitbit Sense as the Superior Alternative to Apple Watch</u></a></li>
<li><a href="https://win11.techidaily.com/go-direct-to-linux-with-no-wsl/"><u>Go Direct to Linux with No WSL</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-sony-xperia-1-v-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Sony Xperia 1 V</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-1011-gpu-drivers-with-precision/"><u>Navigating Windows 10/11 GPU Drivers with Precision</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-system-streamlined-windows-autoupdate-and-driver-change/"><u>Optimize System: Streamlined Windows Autoupdate & Driver Change</u></a></li>
<li><a href="https://network-issues.techidaily.com/qualcomms-patch-atheros-qca61x4-networking-fixed-in-win11/"><u>Qualcomm's Patch: Atheros QCA61x4 Networking Fixed in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-your-world-effortless-windows-factory-techniques/"><u>Reboot Your World: Effortless Windows Factory Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-non-functional-cut-and-paste-in-windows-11/"><u>Repairing Non-Functional Cut & Paste in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/seven-big-mistakes-new-users-could-make-in-windows-11-to-avoid/"><u>Seven Big Mistakes New Users Could Make in Windows 11 - To Avoid</u></a></li>
<li><a href="https://win11.techidaily.com/win-strategies-accelerating-valorants-sluggish-downloads/"><u>Win Strategies: Accelerating Valorant's Sluggish Downloads</u></a></li>
</ul></div>

