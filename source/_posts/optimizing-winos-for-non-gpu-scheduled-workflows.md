---
title: Optimizing WinOS for Non-GPU Scheduled Workflows
date: 2024-11-14T05:54:10.066Z
updated: 2024-11-18T05:34:22.387Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing WinOS for Non-GPU Scheduled Workflows
excerpt: This Article Describes Optimizing WinOS for Non-GPU Scheduled Workflows
keywords: WinOS Optimization,Non-GPU Tasks,Workflow Enhancement,OS Performance Improvement,GPU-Independent Scheduling,Efficient OS Usage,Windows Productivity Boost
thumbnail: https://thmb.techidaily.com/bb7a936483f9ef78d27c435fd60e8eb11646b876bcc8f6574b11c1b4a0b3d5df.jpg
---

## Optimizing WinOS for Non-GPU Scheduled Workflows

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997657/19272" target="_top" id="1997657">
  <img src="//a.impactradius-go.com/display-ad/19272-1997657" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997657/19272" style="position:absolute;visibility:hidden;" border="0" />
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

 If you’re using Windows 10, here’s how you can disable the GPU hardware scheduling feature:

1. Right-click the **Start** button and select **Settings**.
2. Head to **System > Display**.
3. From the **Multiple Displays** menu, click on **Graphics settings**.
4. Turn off the toggle below **Hardware-accelerated GPU scheduling**.
5. Restart your computer for the change to take place.

![How to disable hardware accelerated gpu-scheduling in Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-acc-win10-1.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972679/19272" target="_top" id="1972679">
  <img src="//a.impactradius-go.com/display-ad/19272-1972679" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972679/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2037345/7443" target="_top" id="2037345">
  <img src="//a.impactradius-go.com/display-ad/7443-2037345" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037345/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-information.techidaily.com/new-androids-very-own-podcasters/"><u>[New] Android's Very Own Podcasters</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-breaking-down-whatsapps-voice-call-features/"><u>[New] Breaking Down WhatsApp's Voice Call Features</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-four-streaming-ways-to-showcase-fb-live-events-on-tv/"><u>[New] In 2024, Four Streaming Ways to Showcase FB Live Events on TV</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-perfecting-instagram-reels-acoustics-with-music-voiceovers/"><u>[New] Perfecting Instagram Reels Acoustics with Music, Voiceovers</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-spotify-how-to-exclude-recommended-podcasts/"><u>[New] Spotify How to Exclude Recommended Podcasts</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-exclusive-selection-of-cutting-edge-online-platforms-for-facebook-covers/"><u>[Updated] Exclusive Selection of Cutting-Edge Online Platforms for Facebook Covers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-screenmaster-mastering-window-recordings-on-spring-for-2024/"><u>[Updated] ScreenMaster Mastering Window Recordings on Spring for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enable-auto-updates-for-windows-and-swap-amd-gpu-drivers/"><u>Enable Auto-Updates for Windows & Swap AMD GPU Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-simplifying-pc-interaction-via-windows-narrators-shortcuts/"><u>Expert Guide to Simplifying PC Interaction via Windows Narrator's Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-resolving-unreachable-launcher-issue-on-pc/"><u>Guide to Resolving Unreachable Launcher Issue on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-decrease-microsoft-edges-background-usage/"><u>How to Decrease Microsoft Edge's Background Usage</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-rituals-mastering-windows-top-8-reboot-routines/"><u>Resetting Rituals: Mastering Windows' Top 8 Reboot Routines</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-preventing-vscode-freeze-on-w11/"><u>Solutions for Preventing VSCode Freeze on W11</u></a></li>
<li><a href="https://win11.techidaily.com/toggle-visibility-for-folder-in-windows-explorer-version-11/"><u>Toggle Visibility for Folder in Windows Explorer, Version 11</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1723862829967-unbeatable-deal-alert-samsung-odyssey-g50a-27-inch-qhd-ips-monitor-drops-to-just-255-at-amazon/"><u>Unbeatable Deal Alert: Samsung Odyssey G50A 27-Inch QHD IPS Monitor Drops to Just $255 at Amazon</u></a></li>
</ul></div>

