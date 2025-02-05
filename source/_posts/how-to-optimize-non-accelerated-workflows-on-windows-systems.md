---
title: How to Optimize Non-Accelerated Workflows on Windows Systems
date: 2025-01-31T03:19:17.219Z
updated: 2025-02-04T05:24:44.704Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Optimize Non-Accelerated Workflows on Windows Systems
excerpt: This Article Describes How to Optimize Non-Accelerated Workflows on Windows Systems
keywords: Win Workflow Optimization,Non-Accelerate Workhub,System Efficiency Boost,Streamline Slow Processes,Optimize Non-Speed Tasks,Efficient Windows Tasking,Workflow Enhancement PC
thumbnail: https://thmb.techidaily.com/22c39789b5fe1ed667e7cca081a20115c82b1e4756445b0d8d485b13ec35a1e3.jpg
---

## How to Optimize Non-Accelerated Workflows on Windows Systems

 If you were looking for new ways to get more out of your hardware, chances are you’ve enabled the Hardware accelerated GPU scheduling feature on your computer. While it’s supposed to improve your computer’s performance, it might have a negative effect, if your GPU is a bit older.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

## What Is Hardware Accelerated GPU Scheduling?

 Hardware-accelerated GPU scheduling is a feature designed to reduce the load on your CPU during intensive tasks. Usually, the CPU assigns the graphics-intensive data to the GPU, so games, media-playing apps, or editing software run smoothly. To do so, the CPU gathers, assigns, and sets the priority for each task so the GPU can render it.

 When the hardware-accelerated GPU scheduling feature is enabled, the dedicated GPU-based scheduler will handle the high-priority tasks. This way, the CPU can execute more tasks in the same amount of time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you’re using Windows 10, here’s how you can disable the GPU hardware scheduling feature:

1. Right-click the **Start** button and select **Settings**.
2. Head to **System > Display**.
3. From the **Multiple Displays** menu, click on **Graphics settings**.
4. Turn off the toggle below **Hardware-accelerated GPU scheduling**.
5. Restart your computer for the change to take place.

![How to disable hardware accelerated gpu-scheduling in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-acc-win10-1.jpg)

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-sure.techidaily.com/nleash-potential-prime-times-for-youtube-videos-for-2024/"><u>[New] Unleash Potential Prime Times for Youtube Videos for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-nubia-z50s-pro-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Nubia Z50S Pro</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/complete-guide-to-setting-up-the-latest-doomzday-plugin-in-kodi-ultimate-customization-for-leia-189/"><u>Complete Guide to Setting Up the Latest Doomzday Plugin in Kodi - Ultimate Customization for Leia 18.9</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-samsung-m2070fw-driver-easily-and-quickly/"><u>Download Samsung M2070FW Driver | Easily & Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-security-top-7-windows-defense-methods/"><u>Enhancing Security: Top 7 Windows Defense Methods</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-counteract-uninstallation-restrictions-in-windows-11/"><u>How to Counteract Uninstallation Restrictions in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-failed-system-call-in-windows-os/"><u>How to Overcome 'Failed System Call' In Windows OS</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-motorola-razr-40-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Motorola Razr 40 to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/initial-setup-and-costs/"><u>Initial Setup and Costs</u></a></li>
<li><a href="https://win11.techidaily.com/instant-storage-inspection-in-windows-10-and-11-through-context-menus/"><u>Instant Storage Inspection in Windows 10 & 11 Through Context Menus</u></a></li>
<li><a href="https://review-topics.techidaily.com/motorola-moto-g-5g-2023-won-t-play-mov-videos-how-to-fix-by-aiseesoft-video-converter-play-mov-on-android/"><u>Motorola Moto G 5G (2023) won't play MOV videos, how to fix ?</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-deactivated-cooling-protocol-in-winos/"><u>Overhauling Deactivated Cooling Protocol in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-windows-11-search-the-ultimate-guide-to-11-solutions/"><u>Overhauling Windows 11 Search: The Ultimate Guide to 11 Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/redefine-winterminals-background-design/"><u>Redefine WinTerminal’s Background Design</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-fix-for-the-slow-gpsvc-loop/"><u>Step-by-Step Fix for the Slow GPSVC Loop</u></a></li>
<li><a href="https://win11.techidaily.com/the-fundamentals-of-data-protection-in-windows-notes/"><u>The Fundamentals of Data Protection in Windows Notes</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/the-new-frontier-of-video-conversations-a-2023-guide-to-non-omegle-chat-websites-for-2024/"><u>The New Frontier of Video Conversations A 2023 Guide to Non-Omegle Chat Websites for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722901360003-whats-ahead-at-samsung-unpacked-exclusive-info-on-the-date-latest-product-teasers-and-speculations/"><u>What's Ahead at Samsung Unpacked? Exclusive Info on the Date, Latest Product Teasers, and Speculations !</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/why-i-stopped-looking-elsewhere-and-chose-a-pixel-smartwatch-as-the-ultimate-android-companion/"><u>Why I Stopped Looking Elsewhere and Chose a Pixel Smartwatch as the Ultimate Android Companion</u></a></li>
</ul></div>

