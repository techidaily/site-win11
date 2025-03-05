---
title: Managing System Resources for Effective Remote Device Operations
date: 2025-02-26T16:14:25.303Z
updated: 2025-03-05T04:59:45.568Z
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

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

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
<li><a href="https://youtube-data.techidaily.com/024-approved-the-essential-manual-for-youtube-to-gif-conversion-online/"><u>[New] 2024 Approved The Essential Manual for YouTube-to-GIF Conversion Online</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-freedom-in-sound-extracting-audio-magic-with-pazera-for-2024/"><u>[Updated] Freedom in Sound Extracting Audio Magic with Pazera for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-innovative-strategies-for-logging-overwatch-skirmishes/"><u>[Updated] Innovative Strategies for Logging Overwatch Skirmishes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-sifting-through-the-differences-igtv-vs-youtube-in-a-direct-comparison-for-2024/"><u>[Updated] Sifting Through the Differences IGTV Vs. YouTube in a Direct Comparison for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/device-discreprancies-fix-your-phone-paced-web-experience/"><u>Device Discreprancies: Fix Your Phone-Paced Web Experience</u></a></li>
<li><a href="https://win11.techidaily.com/essential-no-cost-techniques-for-increasing-windows-drive-size/"><u>Essential, No-Cost Techniques for Increasing Windows Drive Size</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/gratuit-online-konverteren-van-mod-naar-wma-proficient-takken-met-movavi/"><u>Gratuit Online Konverteren Van MOD Naar WMA: Proficiënt Takken Met Movavi</u></a></li>
<li><a href="https://screen-capture.techidaily.com/high-quality-video-calling-solutions-top-10-best-apps-ranked/"><u>High-Quality Video Calling Solutions Top 10 Best Apps Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-league-offline-on-pc/"><u>How to Prevent League Offline on PC</u></a></li>
<li><a href="https://win11.techidaily.com/mending-winget-glitches-on-modern-windows/"><u>Mending Winget Glitches on Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-restriction-error-disable-limited-admin-power/"><u>Overcoming Restriction Error: Disable 'Limited Admin Power'</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-guide-to-speedy-shutdown-on-windows-10-systems/"><u>Quick Fix Guide to Speedy Shutdown on Windows 10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-to-build-secure-hardware-removal-icon/"><u>Step-by-Step to Build Secure Hardware Removal Icon</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-obs-recording-glitch-on-windows/"><u>Steps to Overcome OBS Recording Glitch on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-customizing-the-visibility-of-mouse-cursors-in-win-11/"><u>Unleash Potential: Customizing the Visibility of Mouse Cursors in Win 11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/when-travel-becomes-pricey-how-southwest-air-squeezed-extra-costs-during-high-stress-moments/"><u>When Travel Becomes Pricey: How Southwest Air Squeezed Extra Costs During High Stress Moments</u></a></li>
<li><a href="https://driver-error.techidaily.com/win11s-high-disk-usage-explained-and-solved/"><u>Win11's High Disk Usage Explained & Solved</u></a></li>
</ul></div>

