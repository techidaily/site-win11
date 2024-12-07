---
title: Eliminating Accelerated GPU Task Order in Windows
date: 2024-12-04T04:22:51.499Z
updated: 2024-12-07T11:00:56.506Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Accelerated GPU Task Order in Windows
excerpt: This Article Describes Eliminating Accelerated GPU Task Order in Windows
keywords: GPU Task Optimization,Windows Performance Boost,Eliminate GPU Latency,Streamline CPU Workflows,Speed Up Rendering Pace,GPU Process Efficiency,Accelerating System Responsiveness
thumbnail: https://thmb.techidaily.com/9648422bd4a60544ea009a8215c8d33f0ea36e37be4db7347e6bdc7775fbd6e2.jpg
---

## Eliminating Accelerated GPU Task Order in Windows

 If you were looking for new ways to get more out of your hardware, chances are you’ve enabled the Hardware accelerated GPU scheduling feature on your computer. While it’s supposed to improve your computer’s performance, it might have a negative effect, if your GPU is a bit older.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is Hardware Accelerated GPU Scheduling?

 Hardware-accelerated GPU scheduling is a feature designed to reduce the load on your CPU during intensive tasks. Usually, the CPU assigns the graphics-intensive data to the GPU, so games, media-playing apps, or editing software run smoothly. To do so, the CPU gathers, assigns, and sets the priority for each task so the GPU can render it.

 When the hardware-accelerated GPU scheduling feature is enabled, the dedicated GPU-based scheduler will handle the high-priority tasks. This way, the CPU can execute more tasks in the same amount of time.

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

## How to Disable Hardware Accelerated GPU Scheduling

 If the cons outweigh the pros, it’s time to disable Windows GPU scheduling. We’ll walk you through two different methods, so you can choose the one that works best for you.

### Disable Hardware Accelerated GPU Scheduling Through Windows Settings

 The easiest way to disable the Hardware Accelerated GPU Scheduling feature is through Windows Settings. Here’s how you can do it on a Windows 11 computer:

1. Press **Win + I** to bring up the Settings menu.
2. Go to **System > Display**.
3. From the **Related settings** list, click on **Graphics**.
4. Click **Change default graphics settings**.
5. At the top of the page, turn off the toggle for **Hardware-accelerated GPU scheduling**.
6. Reboot your system.

![The Optimizations for windowed games setting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/optimizations-for-windowed-games-setting.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you’re using Windows 10, here’s how you can disable the GPU hardware scheduling feature:

1. Right-click the **Start** button and select **Settings**.
2. Head to **System > Display**.
3. From the **Multiple Displays** menu, click on **Graphics settings**.
4. Turn off the toggle below **Hardware-accelerated GPU scheduling**.
5. Restart your computer for the change to take place.

![How to disable hardware accelerated gpu-scheduling in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-acc-win10-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Disable Hardware Accelerated GPU Scheduling Through Windows Registry

 If your graphics driver is outdated or corrupted, the hardware accelerated feature might be missing from the Settings menu. If you don’t have the time to replace or [update the graphics driver](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) right now, you can still disable hardware-accelerated GPU scheduling through Windows Registry.

1. Press **Win + R** to bring up a Run dialog.
2. Type **regedit** and press **Enter**.
3. In the Registry Editor window, head to **HKEY\_LOCAL\_MACHINE > SYSTEM > CurrentControlSet > Control > GraphicsDrivers**.
4. In the right pane, open the **HwSchMode** value.
5. Set **Value data** to **1**.
6. Click **OK** and restart your computer.

![How to disable hardware accelerated GPU scheduling through Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/registry-acc-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## GPU Scheduling Is Good, but It’s Not Perfect

 We’ve taken a look at how Hardware accelerated GPU scheduling works and when you should disable it. As we’ve mentioned, it may cause system issues, so it might be better to turn it off and look for alternatives. Fortunately, Windows comes with more built-in features to help you improve your gaming experience.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-business-communication-essentials-free-slide-show-tools-for-2024/"><u>[New] Business Communication Essentials – Free Slide Show Tools for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-utilization-of-unused-film-clips-tips-and-tricks/"><u>[New] Utilization of Unused Film Clips Tips and Tricks</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-step-by-step-guide-to-screen-capturing-hulu-content-seamlessly/"><u>[Updated] 2024 Approved Step-by-Step Guide to Screen Capturing Hulu Content Seamlessly</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-problems-with-unknown-usb-devices-in-win-11/"><u>Eliminating Problems with Unknown USB Devices in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-steam-crashes-a-guide-for-windows-11-users/"><u>Eliminating Steam Crashes: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/hidden-panel-wizardry-for-windows-11-users/"><u>Hidden Panel Wizardry for Windows 11 Users</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-xiaomi-redmi-note-13-5g-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Xiaomi Redmi Note 13 5G | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-the-shift-from-rgb-to-srgb-in-digital-imaging/"><u>In 2024, The Shift From Rgb to Srgb in Digital Imaging</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-unlock-your-youtube-shorts-earnings-potential/"><u>In 2024, Unlock Your YouTube Shorts Earnings Potential</u></a></li>
<li><a href="https://win11.techidaily.com/learn-the-art-of-tiling-on-windows-11/"><u>Learn the Art of Tiling on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/setting-safe-mode-activating-tpm-and-secure-boot-before-windows-11-update/"><u>Setting SAFE Mode: Activating TPM & Secure Boot Before Windows 11 Update</u></a></li>
<li><a href="https://win11.techidaily.com/websites-wont-open-strategies-to-overcome-browsers-on-windows/"><u>Websites Won't Open: Strategies to Overcome Browsers on Windows</u></a></li>
</ul></div>

