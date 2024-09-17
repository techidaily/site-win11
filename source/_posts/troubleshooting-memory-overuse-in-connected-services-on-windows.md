---
title: Troubleshooting Memory Overuse in Connected Services on Windows
date: 2024-09-11T03:40:07.743Z
updated: 2024-09-17T07:50:55.507Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Memory Overuse in Connected Services on Windows
excerpt: This Article Describes Troubleshooting Memory Overuse in Connected Services on Windows
keywords: Memory Woes,Service Overload Fix,Windows Memory Issue,Optimize Windows Usage,Reduce PC Memory Waste,Clear Windows Glitches,Enhance Connected Services
thumbnail: https://thmb.techidaily.com/965071db1f866296dbd6b7c6cdfb4395621995dd58483ee49e8397ad83cab217.jpg
---

## Troubleshooting Memory Overuse in Connected Services on Windows

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

<!-- affiliate ads begin -->
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Free Your RAM From Connected Devices Platform User Service

 No process is entitled to consume too much RAM on your computer. And if you find that Connected Devices Platform User Service is doing just that, you can disable it, delete the ActivitiesCache.db file, or see if there's something wrong with your hardware. Hopefully, one of those things will help stop the process hogging the RAM.

 When it consumes too much RAM, it means something could be wrong with the process or your connected devices. Below, we'll show you how to stop Connected Devices Platform User Service from hogging your physical memory.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-efficiency-in-exporting-photos-from-device-to-share-via-snapchat/"><u>[New] In 2024, Efficiency in Exporting Photos From Device to Share via Snapchat</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-the-nuances-of-video-sound-design/"><u>[New] Mastering the Nuances of Video Sound Design</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-streamline-your-content-with-these-4-instagram-looping-hacks/"><u>[Updated] Streamline Your Content with These 4 Instagram Looping Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/cultivating-a-rich-comic-reading-experience-with-win11/"><u>Cultivating a Rich Comic-Reading Experience with Win11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-enhancing-visual-impact-editing-videos-for-instagram/"><u>In 2024, Enhancing Visual Impact Editing Videos for Instagram</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-how-to-eliminate-live-sharing-on-devices/"><u>In 2024, How to Eliminate Live Sharing on Devices</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/making-your-mark-on-facebooks-algorithmic-landscape/"><u>Making Your Mark on Facebook's Algorithmic Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-non-loading-messages-issue-in-windows-discord/"><u>Overcoming Non-Loading Messages Issue in Windows Discord</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/pulse-picking-playlists-hot-tracks-for-viral-youtube-shorts-for-2024/"><u>Pulse-Picking Playlists Hot Tracks for Viral YouTube Shorts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-links-at-the-touch-of-a-button-microsoft-store-uwp-apps/"><u>Quick Links at the Touch of a Button: Microsoft Store UWP Apps</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-onedrive-login-issues-in-windows-systems/"><u>Resolving OneDrive Login Issues in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-resolving-mysterious-recording-issue-in-obs-on-windows-11/"><u>Strategies for Resolving Mysterious Recording Issue in OBS on Windows 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-and-resolving-league-of-legends-network-errors-quickly/"><u>Troubleshooting and Resolving League of Legends Network Errors Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-update-error-x712-on-pcs/"><u>Unraveling Update Error X712 on PCs</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-unlock-free-sound-effects-for-your-fcp-projects-top-resources-and-tutorials/"><u>Updated In 2024, Unlock Free Sound Effects for Your FCP Projects Top Resources & Tutorials</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    