---
title: Troubleshooting High RAM Consumption in Device Linking Systems
date: 2024-12-04T21:02:57.893Z
updated: 2024-12-07T10:40:18.144Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting High RAM Consumption in Device Linking Systems
excerpt: This Article Describes Troubleshooting High RAM Consumption in Device Linking Systems
keywords: High RAM Fixes,Low Memory Trouble,Link Devices Efficiently,Reduce RAM Usage,Optimize System Performance,Device RAM Issues Solve,Streamline Link Systems
thumbnail: https://thmb.techidaily.com/f1294d51d8e0560c6776b360116bd819890055c0bb65c23b15603692f6dffac9.jpg
---

## Troubleshooting High RAM Consumption in Device Linking Systems

 On every Windows startup, the Connected Devices Platform User service uploads the necessary data that connected devices on your computer need. It also authenticates and facilitates communication between them.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, check Task Manager to see if the service is still consuming too much RAM.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-techniques.techidaily.com/new-freebuy-one-lut-bundle-for-canon-pros/"><u>[New] Free/Buy-One-LUT Bundle for Canon Pros</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/outube-playlists-reconfigured-step-by-step-instructions-for-2024/"><u>[New] YouTube Playlists Reconfigured Step-by-Step Instructions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/emerge-from-slumber-win-os-keyboard-plus-mouse-troubleshooting/"><u>Emerge From Slumber: Win OS, Keyboard + Mouse Troubleshooting</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/cing-engagement-professional-pc-techniques-for-youtube-editors/"><u>Enhancing Engagement Professional PC Techniques for YouTube Editors</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-how-to-turn-your-smartphone-into-a-virtual-reality-vr-headset/"><u>In 2024, How to Turn Your Smartphone Into a Virtual Reality (VR) Headset</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/inside-yokus-island-express-an-unforgettable-journey-through-gaming-excellence/"><u>Inside Yoku's Island Express: An Unforgettable Journey Through Gaming Excellence</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-win-lsa-fault-detection/"><u>Overcoming Win LSA Fault Detection</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/premium-timepieces-for-your-dream-wedding-on-smartphones/"><u>Premium Timepieces for Your Dream Wedding on Smartphones</u></a></li>
<li><a href="https://article-posts.techidaily.com/taking-solo-shots-from-videos-in-windows-10-photos-interface/"><u>Taking Solo Shots From Videos in Windows 10 Photos Interface</u></a></li>
<li><a href="https://win11.techidaily.com/the-powerful-protection-of-the-windows-canary-feature/"><u>The Powerful Protection of the Windows Canary Feature</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-address-failed-opening-of-sound-devices-on-audacity/"><u>Tips to Address Failed Opening of Sound Devices on Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-wi-fi-connectivity-problems-on-windows-11/"><u>Unraveling Wi-Fi Connectivity Problems on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-warfare-a-side-by-side-look-at-w10-and-w11-changes/"><u>Windows Warfare: A Side-by-Side Look at W10 and W11 Changes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    