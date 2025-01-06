---
title: Navigating Disabling GPGPU Task Ordering in WinOS
date: 2025-01-03T18:23:59.437Z
updated: 2025-01-06T19:27:56.303Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Disabling GPGPU Task Ordering in WinOS
excerpt: This Article Describes Navigating Disabling GPGPU Task Ordering in WinOS
keywords: GPUTaskOrderWinOS,DisableGPGPUWin,WindowsGPUOptimization,OSGPUControlTask,GPGPUWindowsManagement,TaskOrderingDisablingWin,OptimizeGPUTasksWinOS
thumbnail: https://thmb.techidaily.com/45a1f9697d2bdeb16116c56d8bb656d37d6c88757987caf5e6bad0d2243c55f0.jpg
---

## Navigating Disabling GPGPU Task Ordering in WinOS

 If you were looking for new ways to get more out of your hardware, chances are you’ve enabled the Hardware accelerated GPU scheduling feature on your computer. While it’s supposed to improve your computer’s performance, it might have a negative effect, if your GPU is a bit older.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is Hardware Accelerated GPU Scheduling?

 Hardware-accelerated GPU scheduling is a feature designed to reduce the load on your CPU during intensive tasks. Usually, the CPU assigns the graphics-intensive data to the GPU, so games, media-playing apps, or editing software run smoothly. To do so, the CPU gathers, assigns, and sets the priority for each task so the GPU can render it.

 When the hardware-accelerated GPU scheduling feature is enabled, the dedicated GPU-based scheduler will handle the high-priority tasks. This way, the CPU can execute more tasks in the same amount of time.

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

## How to Disable Hardware Accelerated GPU Scheduling

 If the cons outweigh the pros, it’s time to disable Windows GPU scheduling. We’ll walk you through two different methods, so you can choose the one that works best for you.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Disable Hardware Accelerated GPU Scheduling Through Windows Settings

 The easiest way to disable the Hardware Accelerated GPU Scheduling feature is through Windows Settings. Here’s how you can do it on a Windows 11 computer:

1. Press **Win + I** to bring up the Settings menu.
2. Go to **System > Display**.
3. From the **Related settings** list, click on **Graphics**.
4. Click **Change default graphics settings**.
5. At the top of the page, turn off the toggle for **Hardware-accelerated GPU scheduling**.
6. Reboot your system.

![The Optimizations for windowed games setting option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/optimizations-for-windowed-games-setting.jpg)

 If you’re using Windows 10, here’s how you can disable the GPU hardware scheduling feature:

1. Right-click the **Start** button and select **Settings**.
2. Head to **System > Display**.
3. From the **Multiple Displays** menu, click on **Graphics settings**.
4. Turn off the toggle below **Hardware-accelerated GPU scheduling**.
5. Restart your computer for the change to take place.

![How to disable hardware accelerated gpu-scheduling in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-acc-win10-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-affordable-setups-tailored-obs-for-budget-computers/"><u>[New] 2024 Approved Affordable Setups Tailored OBS for Budget Computers</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-empower-your-imagery-free-lut-techniques-for-ar/"><u>[Updated] In 2024, Empower Your Imagery Free LUT Techniques for AR</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-keep-your-videos-secure-youtube-to-mp4-downloading-safely/"><u>[Updated] In 2024, Keep Your Videos Secure - YouTube-to-MP4 Downloading Safely</u></a></li>
<li><a href="https://extra-tips.techidaily.com/creating-stunning-canon-time-lapse-videos/"><u>Creating Stunning Canon Time-Lapse Videos</u></a></li>
<li><a href="https://android-unlock.techidaily.com/downloading-samfw-frp-tool-30-for-huawei-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Huawei</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enhancing-your-watchlist-through-chatgpt-advice/"><u>Enhancing Your Watchlist Through ChatGPT Advice</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-from-twitter-to-whatsapp-a-guide-to-sharing-online-videos/"><u>In 2024, From Twitter to WhatsApp A Guide to Sharing Online Videos</u></a></li>
<li><a href="https://games-able.techidaily.com/mapping-out-steams-screenshot-stashes/"><u>Mapping Out Steam's Screenshot Stashes</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-bluetooth-device-usage-focus-on-sound-outputs-alone/"><u>Maximizing Windows Bluetooth Device Usage - Focus on Sound Outputs Alone</u></a></li>
<li><a href="https://win11.techidaily.com/quieten-windows-acoustic-overlays/"><u>Quieten Windows' Acoustic Overlays</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-the-isarcextract-bug-on-your-w11-system/"><u>Resolving the ISArcExtract Bug on Your W11 System</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-re-activating-stalled-asana-windows-integration/"><u>Strategies for Re-Activating Stalled Asana Windows Integration</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-user-policy-application-in-modern-windows/"><u>Streamlining User Policy Application in Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-transformation-in-windows-history-1985-2023/"><u>Taskbar Transformation in Windows History (1985-2023)</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-ultimate-guide-to-understanding-style-and-capability-with-fitbit-charge-4/"><u>The Ultimate Guide to Understanding Style & Capability with Fitbit Charge 4</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-reviving-winget-in-w11/"><u>The Ultimate Guide: Reviving Winget in W11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-know-how-pinpointing-exact-ram-type/"><u>Windows Know-How: Pinpointing Exact RAM Type</u></a></li>
</ul></div>

