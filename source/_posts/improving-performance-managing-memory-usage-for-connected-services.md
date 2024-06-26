---
title: "Improving Performance: Managing Memory Usage for Connected Services"
date: 2024-06-25T11:24:45.271Z
updated: 2024-06-26T11:24:45.271Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/bridge-the-gap-top-methods-to-reconnect-your-usb-wi-fi-on-pcs/"><u>Bridge the Gap: Top Methods to Reconnect Your USB Wi-Fi on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-your-esc-key-woes-in-a-flash-with-this-guide/"><u>Reboot Your Esc Key Woes in a Flash With This Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-printer-uninstallation-without-recovery-options/"><u>Mastering Printer Uninstallation without Recovery Options</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-for-beginning-your-steam-gamers-journey-anew/"><u>The Blueprint for Beginning Your Steam Gamers' Journey Anew</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-secrets-of-devhome-in-windows-11/"><u>Deciphering the Secrets of DevHome in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-prevalent-windows-rainmeter-troubles/"><u>Navigating Through Prevalent Windows Rainmeter Troubles</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategies-for-warhammer-40k-players-stop-pc-lag-issues/"><u>Winning Strategies for Warhammer 40K Players - Stop PC Lag Issues</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-can-affordable-view-count-gains-be-achieved-naturally/"><u>[Updated] Can Affordable View Count Gains Be Achieved Naturally?</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-the-security-questions-of-your-apple-id-on-your-apple-iphone-6s-by-drfone-ios/"><u>In 2024, How To Reset the Security Questions of Your Apple ID On Your Apple iPhone 6s</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-screen-capturers-best-top-12-recommendations/"><u>[New] 2024 Approved  Screen Capturer's Best  Top 12 Recommendations</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-from-twitter-to-facebook-sending-your-tweets/"><u>[New] From Twitter to Facebook  Sending Your Tweets</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-your-oppo-a18-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Oppo A18 Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/taking-down-the-veil-youtubes-most-elusive-videos-for-2024/"><u>Taking Down the Veil  YouTube's Most Elusive Videos for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-elite-list-of-mac-tech-for-live-recording/"><u>[New] In 2024, Elite List of Mac Tech for Live Recording</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-breaking-the-mold-unique-anime-creatives-dominating-tiktok/"><u>[New] In 2024, Breaking the Mold  Unique Anime Creatives Dominating TikTok</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>