---
title: Strategies for Dismissing WinOS Hardware Acceleration Scheduling
date: 2024-12-07T13:59:58.558Z
updated: 2024-12-13T12:30:35.712Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies for Dismissing WinOS Hardware Acceleration Scheduling
excerpt: This Article Describes Strategies for Dismissing WinOS Hardware Acceleration Scheduling
keywords: WinSchedWinAccelDismissal,OSHardwareAvoidSchedWin,DisableWinOSAccelerator,SchedulAvoidingWinOS,HardwareOptOutWinSched,WindowsHaltACcelSched,WinOSNoAccelSchedule
thumbnail: https://thmb.techidaily.com/f93eb5bd46514b847ac07d099dc18d72eab724476fd27a01a5370f94ffa41df8.jpg
---

## Strategies for Dismissing WinOS Hardware Acceleration Scheduling

 If you were looking for new ways to get more out of your hardware, chances are you’ve enabled the Hardware accelerated GPU scheduling feature on your computer. While it’s supposed to improve your computer’s performance, it might have a negative effect, if your GPU is a bit older.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is Hardware Accelerated GPU Scheduling?

 Hardware-accelerated GPU scheduling is a feature designed to reduce the load on your CPU during intensive tasks. Usually, the CPU assigns the graphics-intensive data to the GPU, so games, media-playing apps, or editing software run smoothly. To do so, the CPU gathers, assigns, and sets the priority for each task so the GPU can render it.

 When the hardware-accelerated GPU scheduling feature is enabled, the dedicated GPU-based scheduler will handle the high-priority tasks. This way, the CPU can execute more tasks in the same amount of time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

## How to Disable Hardware Accelerated GPU Scheduling

 If the cons outweigh the pros, it’s time to disable Windows GPU scheduling. We’ll walk you through two different methods, so you can choose the one that works best for you.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## GPU Scheduling Is Good, but It’s Not Perfect

 We’ve taken a look at how Hardware accelerated GPU scheduling works and when you should disable it. As we’ve mentioned, it may cause system issues, so it might be better to turn it off and look for alternatives. Fortunately, Windows comes with more built-in features to help you improve your gaming experience.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-direct.techidaily.com/updated-free-memery-masters-explore-and-share-joy-for-2024/"><u>[Updated] Free Memery Masters Explore & Share Joy for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-new-iphone-x-camera-features-you-need-to-know/"><u>2024 Approved New iPhone X Camera Features You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/designing-safe-quick-access-tool-for-hardware-in-win11/"><u>Designing Safe, Quick Access Tool for Hardware in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/emergency-windows-fixes-reanimate-lost-screens-using-6-steps/"><u>Emergency Windows Fixes: Reanimate Lost Screens Using 6 Steps</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/from-slow-to-lightning-fast-upgrade-your-ps5-with-an-ssd-quick-guide/"><u>From Slow to Lightning Fast: Upgrade Your PS5 with an SSD Quick Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/guide-to-reactivating-multiple-silent-audio-streams-easily/"><u>Guide to Reactivating Multiple Silent Audio Streams Easily</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-adding-clear-timestamps-to-your-youtube-channels-live-streams/"><u>In 2024, Adding Clear Timestamps to Your YouTube Channel's Live Streams</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-data-with-microsoft-excel-explore-these-essential-analytical-features/"><u>Mastering Data with Microsoft Excel: Explore These Essential Analytical Features</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-norm-keyboard-shortcuts-to-optimize-windows/"><u>Navigating the Norm: Keyboard Shortcuts to Optimize Windows</u></a></li>
<li><a href="https://fox-http.techidaily.com/quick-click-compilation-top-10-fastest-phone-and-pc-apps-for-2024/"><u>Quick Click Compilation Top 10 Fastest Phone & PC Apps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-steam-sync-errors-on-pc/"><u>Rectifying Steam Sync Errors on PC</u></a></li>
<li><a href="https://android-unlock.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-vivo-y02t-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Vivo Y02T</u></a></li>
<li><a href="https://win11.techidaily.com/the-new-look-of-windows-11-admin-panel/"><u>The New Look of Windows 11 Admin Panel</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/transforming-srt-files-into-text-a-speedy-expertise-guide-for-2024/"><u>Transforming SRT Files Into Text A Speedy Expertise Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/why-you-shouldnt-switch-7-benefits-from-using-win10/"><u>Why You Shouldn't Switch: 7 Benefits From Using Win10</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    