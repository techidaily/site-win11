---
title: How to Turn Off Hardware Scheduler for Graphics in WINOS
date: 2024-12-02T20:51:52.994Z
updated: 2024-12-07T01:10:37.871Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Turn Off Hardware Scheduler for Graphics in WINOS
excerpt: This Article Describes How to Turn Off Hardware Scheduler for Graphics in WINOS
keywords: Graphic Scheduler Disable Windows,Stop GPU Scheduler WIN OS,Halt Graphics Scheduling Windows,End Hardware Scheduler Windows,Turn Off Win Graphics Scheduler,Deactivate Windows GPU Timer,Disengage Graphics Scheduler Windows
thumbnail: https://thmb.techidaily.com/2ce87a986250d8398be45eae1ecaf9f012f12535b14ea9611940de411cb7abe5.jpg
---

## How to Turn Off Hardware Scheduler for Graphics in WINOS

 If you were looking for new ways to get more out of your hardware, chances are you’ve enabled the Hardware accelerated GPU scheduling feature on your computer. While it’s supposed to improve your computer’s performance, it might have a negative effect, if your GPU is a bit older.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is Hardware Accelerated GPU Scheduling?

 Hardware-accelerated GPU scheduling is a feature designed to reduce the load on your CPU during intensive tasks. Usually, the CPU assigns the graphics-intensive data to the GPU, so games, media-playing apps, or editing software run smoothly. To do so, the CPU gathers, assigns, and sets the priority for each task so the GPU can render it.

 When the hardware-accelerated GPU scheduling feature is enabled, the dedicated GPU-based scheduler will handle the high-priority tasks. This way, the CPU can execute more tasks in the same amount of time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Disable Hardware Accelerated GPU Scheduling

 If the cons outweigh the pros, it’s time to disable Windows GPU scheduling. We’ll walk you through two different methods, so you can choose the one that works best for you.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mK1lEBRm_1w?si=FSaM0OKO0XBCgjtT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

### Disable Hardware Accelerated GPU Scheduling Through Windows Registry

 If your graphics driver is outdated or corrupted, the hardware accelerated feature might be missing from the Settings menu. If you don’t have the time to replace or [update the graphics driver](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) right now, you can still disable hardware-accelerated GPU scheduling through Windows Registry.

1. Press **Win + R** to bring up a Run dialog.
2. Type **regedit** and press **Enter**.
3. In the Registry Editor window, head to **HKEY\_LOCAL\_MACHINE > SYSTEM > CurrentControlSet > Control > GraphicsDrivers**.
4. In the right pane, open the **HwSchMode** value.
5. Set **Value data** to **1**.
6. Click **OK** and restart your computer.

![How to disable hardware accelerated GPU scheduling through Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/registry-acc-1.jpg)

## GPU Scheduling Is Good, but It’s Not Perfect

 We’ve taken a look at how Hardware accelerated GPU scheduling works and when you should disable it. As we’ve mentioned, it may cause system issues, so it might be better to turn it off and look for alternatives. Fortunately, Windows comes with more built-in features to help you improve your gaming experience.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/new-win-10s-top-10-video-cam-applications/"><u>[New] Win 10'S Top 10 Video Cam Applications</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-revolutionizing-screen-experience-lgs-2023-bp550/"><u>2024 Approved Revolutionizing Screen Experience - LG's 2023 BP550</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-self-how-to-start-windows-personalized-introspection-engine/"><u>Delving Into Self: How to Start Windows' Personalized Introspection Engine</u></a></li>
<li><a href="https://tech-haven.techidaily.com/effortless-disconnection-how-to-detach-a-microsoft-account-from-windows-10-in-minutes/"><u>Effortless Disconnection: How To Detach a Microsoft Account From Windows 10 in Minutes</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-pip-navigating-netflixs-floating-screen-functionality/"><u>In 2024, Mastering PIP Navigating Netflix's Floating Screen Functionality</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-strategies-for-effective-whiteboard-interaction-during-online-engagement-across-multiple-systems/"><u>In 2024, Strategies for Effective Whiteboard Interaction During Online Engagement Across Multiple Systems</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-solve-xp709-error/"><u>Methods to Solve XP709 Error</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-internet-disconnections-keeping-lele-online/"><u>Overcoming Internet Disconnections: Keeping LeLë Online</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-1011-sound-flaw-code-0xd36b4/"><u>Overcoming Window's 10/11 Sound Flaw: Code 0Xd36b4</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-window-explorer-tab-disappearances/"><u>Repairing Window Explorer Tab Disappearances</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-your-computers-double-clicking-technique/"><u>Revolutionize Your Computer's Double-Clicking Technique</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-role-of-a-chief-artificial-intelligence-officer-steps-to-achieve-the-position/"><u>The Role of a Chief Artificial Intelligence Officer – Steps to Achieve the Position</u></a></li>
<li><a href="https://extra-hints.techidaily.com/your-simple-route-to-youtubes-srt-extraction/"><u>Your Simple Route to YouTube's SRT Extraction</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    