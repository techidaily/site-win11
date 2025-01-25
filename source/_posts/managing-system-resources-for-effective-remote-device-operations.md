---
title: Managing System Resources for Effective Remote Device Operations
date: 2025-01-21T06:37:08.549Z
updated: 2025-01-25T09:02:00.565Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, check Task Manager to see if the service is still consuming too much RAM.

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-how-to-quickly-craft-perfect-subtitles-and-captions-for-facebook-video-feeds/"><u>[New] 2024 Approved How To Quickly Craft Perfect Subtitles and Captions for Facebook Video Feeds</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-instagram-highlights-download-methods-and-creating-tips/"><u>[New] 2024 Approved Instagram Highlights Download Methods and Creating Tips</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-seamless-integration-utilizing-instagrams-music-stickers-expertise/"><u>[Updated] 2024 Approved Seamless Integration Utilizing Instagram's Music Stickers Expertise</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-swiftly-flip-your-iphone-video-clips/"><u>[Updated] In 2024, Swiftly Flip Your iPhone Video Clips</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-dive-deep-with-these-6-extraordinary-metaverse-models/"><u>2024 Approved Dive Deep with These 6 Extraordinary Metaverse Models</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-code-0x887a0006-for-gpu-stalls-windows/"><u>Addressing Code 0X887A0006 for GPU Stalls Windows</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-fixing-the-perplexing-windows-net-error-0x800704b3/"><u>Deciphering and Fixing the Perplexing Windows Net Error 0X800704B3</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-stacked-elements-at-pcs-action-bar/"><u>Fixing Stacked Elements at PC's Action Bar</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-unveiling-and-managing-windows-10-actions/"><u>Guide to Unveiling & Managing Windows 10 Actions</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-windows-11s-sticky-notes-on-all-your-devices/"><u>How to Use Windows 11'S Sticky Notes on All Your Devices</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-full-guide-to-iphone-13-pro-max-icloud-bypass-by-drfone-ios/"><u>In 2024, Full guide to iPhone 13 Pro Max iCloud Bypass</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-speedrunning-in-subway-surfers-with-these-pro-tips-7-16/"><u>Mastering Speedrunning in 'Subway Surfers' With These Pro Tips #7-#16</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-a-dormant-wired-controller-on-windows-pc/"><u>Reactivating a Dormant Wired Controller on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-application-was-unable-to-start-in-win1011/"><u>Solving The Application Was Unable to Start in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-for-detecting-missing-disk-on-windows/"><u>Tactics for Detecting Missing Disk on Windows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-essential-vimeo-video-editor-tutorial-achieve-stellar-results-with-our-expert-editing-techniques/"><u>The Essential Vimeo Video Editor Tutorial - Achieve Stellar Results with Our Expert Editing Techniques</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-6-troubleshooting-steps-for-unpairing-issues-with-your-apple-watch/"><u>Top 6 Troubleshooting Steps for Unpairing Issues with Your Apple Watch</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-window-glow-on-windows-11-computers/"><u>Transforming Window Glow on Windows 11 Computers</u></a></li>
<li><a href="https://win11.techidaily.com/unclutter-your-taskbar-separate-groups/"><u>Unclutter Your Taskbar: Separate Groups</u></a></li>
</ul></div>

