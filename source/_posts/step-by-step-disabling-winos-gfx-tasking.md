---
title: "Step-by-Step: Disabling WinOS GFX Tasking"
date: 2024-11-30T02:35:51.199Z
updated: 2024-12-06T20:18:14.642Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Disabling WinOS GFX Tasking"
excerpt: "This Article Describes Step-by-Step: Disabling WinOS GFX Tasking"
keywords: Windows Graphics Override,Disable OS Graphics Tasking,Stop GPU Command Execution,End WinOS GPU Controls,Block Graphical Output Tasks,Halt GFX Overrides in WinOS,Prevent GPU Settings on PC
thumbnail: https://thmb.techidaily.com/dc54f112c78b3afb0110331eb25c5f493a4d3b2149d6ee352dfe8394d4845198.jpg
---

## Step-by-Step: Disabling WinOS GFX Tasking

 If you were looking for new ways to get more out of your hardware, chances are you’ve enabled the Hardware accelerated GPU scheduling feature on your computer. While it’s supposed to improve your computer’s performance, it might have a negative effect, if your GPU is a bit older.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is Hardware Accelerated GPU Scheduling?

 Hardware-accelerated GPU scheduling is a feature designed to reduce the load on your CPU during intensive tasks. Usually, the CPU assigns the graphics-intensive data to the GPU, so games, media-playing apps, or editing software run smoothly. To do so, the CPU gathers, assigns, and sets the priority for each task so the GPU can render it.

 When the hardware-accelerated GPU scheduling feature is enabled, the dedicated GPU-based scheduler will handle the high-priority tasks. This way, the CPU can execute more tasks in the same amount of time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

## How to Disable Hardware Accelerated GPU Scheduling

 If the cons outweigh the pros, it’s time to disable Windows GPU scheduling. We’ll walk you through two different methods, so you can choose the one that works best for you.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## GPU Scheduling Is Good, but It’s Not Perfect

 We’ve taken a look at how Hardware accelerated GPU scheduling works and when you should disable it. As we’ve mentioned, it may cause system issues, so it might be better to turn it off and look for alternatives. Fortunately, Windows comes with more built-in features to help you improve your gaming experience.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-data.techidaily.com/024-approved-free-yourself-from-video-edges-on-youtube/"><u>[New] 2024 Approved Free Yourself From Video Edges on YouTube</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-top-5-driving-and-race-replicas/"><u>[New] Top 5 Driving & Race Replicas</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-10-exceptional-cost-saving-passport-portrait-maker-applications/"><u>[Updated] 10 Exceptional, Cost-Saving Passport Portrait Maker Applications</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-revolutionizing-video-sharing-alternatives-to-youtube/"><u>[Updated] Revolutionizing Video Sharing Alternatives to YouTube</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-the-complete-itunes-radio-downloading-blueprint/"><u>2024 Approved The Complete iTunes Radio Downloading Blueprint</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-ram-cache-explained/"><u>Demystifying Window's RAM Cache Explained</u></a></li>
<li><a href="https://win11.techidaily.com/essential-win11-navigation-keys-list/"><u>Essential Win11 Navigation Keys List</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-any-vivo-v29-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Vivo V29 Phone Password Using Emergency Call</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-fcpx-power-tools-top-10-plugins-to-boost-your-video-editing-productivity/"><u>In 2024, FCPX Power Tools Top 10 Plugins to Boost Your Video Editing Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/relocating-onedrive-space-in-windows-os/"><u>Relocating OneDrive Space in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/silent-setup-strategies-concealed-menu-options-win-1011/"><u>Silent Setup Strategies: Concealed Menu Options, Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-for-setting-up-the-ms-defender-application-guard-in-edge-browser/"><u>Step-by-Step Guide for Setting Up the MS Defender Application Guard in Edge Browser</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-ihome-zenergy-mattress-side-sleep-enhancer-transforming-slumber-into-invigorating-dawns-product-reviewed/"><u>The IHome Zenergy Mattress-Side Sleep Enhancer: Transforming Slumber Into Invigorating Dawns – Product Reviewed</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-steps-for-pc-players-unable-to-initiate-cod-black-ops-cold-war/"><u>Troubleshooting Steps for PC Players Unable to Initiate Cod: Black Ops Cold War</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    