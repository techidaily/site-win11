---
title: Managing System Resources for Effective Remote Device Operations
date: 2025-01-02T17:20:49.548Z
updated: 2025-01-06T18:07:02.785Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Managing System Resources for Effective Remote Device Operations
excerpt: This Article Describes Managing System Resources for Effective Remote Device Operations
keywords: Resource Management,Remote Device Control,Effective Operation,System Performance,Resource Allocation,Devices Efficiency,Remote System Optimization
thumbnail: https://thmb.techidaily.com/c856d755f3f7d2c0f103fd6d2cd384857bef4cae5585cde42e136d87338a8911.jpg
---

## Managing System Resources for Effective Remote Device Operations

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-auroras-hdv-does-it-elevate-your-home-cinema/"><u>[New] 2024 Approved Aurora's HDV Does It Elevate Your Home Cinema?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-leveraging-obs-for-top-notch-social-media-streaming/"><u>[Updated] Leveraging OBS for Top-Notch Social Media Streaming</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-plunge-into-the-magic-9-premium-full-length-christmas-movies-for-free-for-2024/"><u>[Updated] Plunge Into the Magic 9 Premium Full-Length Christmas Movies for Free for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-high-definition-excellence-selecting-the-top-youtube-converters/"><u>2024 Approved High Definition Excellence Selecting the Top YouTube Converters</u></a></li>
<li><a href="https://win11.techidaily.com/digital-doodles-your-desktop-art-journey-in-windows-11/"><u>Digital Doodles: Your Desktop Art Journey in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/dxgidll-missing-solve-it-with-these-win11-fixes/"><u>Dxgi.dll Missing? Solve It with These Win11 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-gateway-to-managing-printers-in-windows/"><u>Exploring the Gateway to Managing Printers in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-customize-win11-connection-protocols/"><u>How to Customize Win11 Connection Protocols</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-vivo-y28-5g-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Vivo Y28 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/introducing-the-revolutionary-apple-airpods-pro-now-with-enhanced-tracking-and-usb-c-charging-features-detailed-review/"><u>Introducing the Revolutionary Apple AirPods Pro: Now with Enhanced Tracking & USB-C Charging Features - Detailed Review</u></a></li>
<li><a href="https://win11.techidaily.com/minimizing-wmi-service-resource-consumption/"><u>Minimizing WMI Service Resource Consumption</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/211385531-9798368815183-moon-man-3/"><u>Moon Man #3 | Free Book</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-failed-system-call-in-windows-devices/"><u>Resolving 'Failed System Call' In Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-issue-of-dark-pixels-on-windows-steam/"><u>Tackling the Issue of Dark Pixels on Windows Steam</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-of-windows-best-webp-image-viewers/"><u>The Ultimate List of Windows' Best WebP Image Viewers</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-honor-by-drfone-android/"><u>Three Ways to Sim Unlock Honor</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/ultimate-list-of-iphone-text-backup-apps-learn-how-stellar-leads-the-way/"><u>Ultimate List of iPhone Text Backup Apps – Learn How Stellar Leads the Way!</u></a></li>
</ul></div>

