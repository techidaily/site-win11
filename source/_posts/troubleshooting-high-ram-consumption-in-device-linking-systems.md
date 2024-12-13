---
title: Troubleshooting High RAM Consumption in Device Linking Systems
date: 2024-12-09T18:30:23.683Z
updated: 2024-12-13T00:26:17.675Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Disable Connected Devices Platform User Service

 The simplest way to stop Connected Devices Platform User Service from using too much RAM is to disable it. However, this might cause some unexpected behavior on your computer. And if that happens, you can always enable it again.

 To disable Connected Devices Platform User Service, press **Win + R** to bring up Windows Run. Enter **services.msc** in the text box and then press the **Enter** key on your keyboard.

![services msc Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/services-msc-Windows-11.jpg)

 Find the **Disable Connected Devices Platform User Service** in the list of services and double-click on it. Click on the **Startup type** dropdown and select **Disabled**. Then, under **Service status** in the same window, click on **Stop**.

![the-connected-device-platform-user-service-properties-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-connected-device-platform-user-service-properties-windows.jpg)

 Now, check Task Manager to see if the service is still consuming too much RAM.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Remove the ActivitiesCache.db file

 Some users have reported that deleting the ActivitiesCache.db file on their computer has helped solve the problem. To delete it, start by disabling the Connected Devices Platform User Service, as discussed above. Then, press **Win + R** to open Windows Run, copy and paste **%localappdata%\\ConnectedDevicesPlatform\\** in the text, and then hit the **Enter** key.

![navigating-to-the-connecteddevicesplatform-folder-in-windows-run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/navigating-to-the-connecteddevicesplatform-folder-in-windows-run.jpg)

 This will open the **ConnectedDevicesPlatform** folder. You'll see several files and folders in there, so open each of the folders and delete the **ActivitiesCache.db** file in all of them.

![the-activitiescab-file-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-activitiescab-file-on-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you do, restart your computer and see if Connected Devices Platform User Service is still causing RAM consumption issues.

## 3\. Check for Issues With Your Computer's Hardware

 Sometimes, the problem could arise due to one of your connected devices experiencing a problem. To check if your connected devices are functioning properly, open Device Manager by pressing **Win + R**, enter **devmgmt.msc** in the text box, and then hit the **Enter** key on your keyboard.

![devmgmt.msc in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/devmgmt-msc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Device Manager, double-click the device you suspect is causing issues. This will open its properties window.

 In the **General** tab of the Properties window, make sure it says **This device is working properly** under **Device status**.

![the-properties-window-of-a-device-on-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/10/the-properties-window-of-a-device-on-windows.jpg)

 If it doesn't, you will see an error message and a code. Take note of both so you can start troubleshooting the problem. You can start by using [one of the troubleshooters on Windows](https://www.makeuseof.com/run-troubleshooter-windows-10-11/) to check for and fix the hardware problem you're seeing.

 If all the steps above don't work then you might need to [use a system restore point](https://www.makeuseof.com/use-system-restore-windows/) that you created before it started using too much RAM. And if that doesn't work as well, you might have to reset your Windows computer

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-information.techidaily.com/new-beijings-ice-arena-olympic-moments-2022/"><u>[New] Beijing's Ice Arena Olympic Moments, 2022</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-get-close-or-farther-with-ease-on-instagram-stories/"><u>[New] Get Close or Farther with Ease on Instagram Stories</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-essential-guide-to-storing-with-adobe-including-what-not-to-miss-elsewhere-for-2024/"><u>[Updated] Essential Guide to Storing with Adobe, Including What Not To Miss Elsewhere for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastery-in-motion-a-thorough-review-of-magix-vpxs-features/"><u>2024 Approved Mastery in Motion A Thorough Review of Magix VPX's Features</u></a></li>
<li><a href="https://tech-revival.techidaily.com/best-generative-ai-assistants-of-2021-comparing-notion-with-microsofts-gpt-3-chatgpt/"><u>Best Generative AI Assistants of 2021: Comparing Notion with Microsoft's GPT-3 (ChatGPT)</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-monitor-resolution-in-the-latest-os-update/"><u>Enhance Monitor Resolution in the Latest OS Update</u></a></li>
<li><a href="https://win11.techidaily.com/guaranteeing-secure-winvpn-link-establishment/"><u>Guaranteeing Secure WinVPN Link Establishment</u></a></li>
<li><a href="https://discover-able.techidaily.com/how-did-mao-zedong-shape-todays-china-analysis-by-yl-computing-and-yl-software-experts/"><u>How Did Mao Zedong Shape Today's China?: Analysis by YL Computing & YL Software Experts</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-android-tabs-with-w11-a-dual-screen-guide/"><u>Maximizing Android Tabs with W11: A Dual-Screen Guide</u></a></li>
<li><a href="https://win11.techidaily.com/no-more-stuck-how-to-ditch-the-epic-games-hub-in-w11/"><u>No More Stuck: How to Ditch the Epic Games Hub in W11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/premium-best-ten-spotifys-superior-recording-tools-for-2024/"><u>Premium Best Ten Spotify's Superior Recording Tools for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/quick-deck-revamp-the-ultimate-ssd-cloning-method/"><u>Quick Deck Revamp: The Ultimate SSD Cloning Method</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/swift-film-techniques-for-at-home-creators/"><u>Swift Film Techniques for At-Home Creators</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-global-communication-hotkey-based-language-switching-in-winos/"><u>Unlock Global Communication: Hotkey-Based Language Switching in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-esd-conversion-secrets-to-formatting-as-an-iso-file/"><u>Windows ESD Conversion: Secrets to Formatting as an ISO File</u></a></li>
<li><a href="https://win11.techidaily.com/windows-memory-strategies-understanding-and-cleansing/"><u>Windows Memory Strategies: Understanding and Cleansing</u></a></li>
</ul></div>

