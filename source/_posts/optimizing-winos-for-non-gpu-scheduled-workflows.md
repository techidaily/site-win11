---
title: Optimizing WinOS for Non-GPU Scheduled Workflows
date: 2024-10-31T22:08:03.703Z
updated: 2024-11-07T23:05:15.581Z
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

## Should You Disable Hardware Accelerated GPU Scheduling?

![Discrete GPU made by NVIDIA](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Discrete-GPU-by-NVIDIA.jpg)

 Most of the time, [GPU hardware scheduling is worth turning on in Windows](https://www.makeuseof.com/windows-10-gpu-hardware-scheduling-worth-turning-on/), especially if your computer isn’t equipped with one of the latest GPU models. But enabling the GPU scheduling feature can also backfire, and have a negative impact on your computer’s performance. For example, on an older GPU, it might cause latency between the frames or even significant lag while gaming.

 Also, GPU scheduling is known for causing conflict with Windows services, such as dxgmms2.sys, which helps render graphics, especially during gaming sessions. So, if you keep running into the [dxgmms2.sys error in Windows 11](https://www.makeuseof.com/windows-11-dxgmms2-sys-error-fix/), you’ll have to disable the Hardware- accelerated GPU scheduling feature.

 In addition to this, the feature might encounter compatibility issues with specific hardware or software. So, you have to turn off GPU scheduling to keep your computer running smoothly.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036501/19272" target="_top" id="2036501">
  <img src="//a.impactradius-go.com/display-ad/19272-2036501" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036501/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable Hardware Accelerated GPU Scheduling

 If the cons outweigh the pros, it’s time to disable Windows GPU scheduling. We’ll walk you through two different methods, so you can choose the one that works best for you.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047361/19272" target="_top" id="2047361">
  <img src="//a.impactradius-go.com/display-ad/19272-2047361" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047361/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134233/18498" target="_top" id="2134233">
  <img src="//a.impactradius-go.com/display-ad/18498-2134233" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134233/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1172027/12108" target="_top" id="1172027">
  <img src="//a.impactradius-go.com/display-ad/12108-1172027" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1172027/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## GPU Scheduling Is Good, but It’s Not Perfect

 We’ve taken a look at how Hardware accelerated GPU scheduling works and when you should disable it. As we’ve mentioned, it may cause system issues, so it might be better to turn it off and look for alternatives. Fortunately, Windows comes with more built-in features to help you improve your gaming experience.

 In this case, should you disable it? But how can you turn off Hardware accelerated GPU scheduling in Windows 10 and 11?

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-helps.techidaily.com/new-choreograph-cheeky-comics-via-giphy/"><u>[New] Choreograph Cheeky Comics via Giphy</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-aesthetic-alignment-for-online-glamour-content/"><u>[New] In 2024, Aesthetic Alignment for Online Glamour Content</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-bridging-communication-gaps-utilizing-zoom-with-gmail-mail/"><u>[Updated] 2024 Approved Bridging Communication Gaps Utilizing Zoom with Gmail Mail</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-streamline-your-screens-youtube-video-resizing-tricks/"><u>[Updated] Streamline Your Screens YouTube Video Resizing Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-passwords-identifying-win-11-writers-of-change/"><u>Cutting-Edge Passwords: Identifying Win 11' Writers of Change</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-ntoskrnlexes-high-cpu-usage-on-windows/"><u>How to Fix Ntoskrnl.exe's High CPU Usage on Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-tecno-spark-go-2023-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Tecno Spark Go (2023) to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-track-apple-iphone-se-2020-location-by-number-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Track Apple iPhone SE (2020) Location by Number | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/is-the-new-ios-17-update-essential-for-your-iphone-or-ipad/"><u>Is the New iOS 17 Update Essential for Your iPhone or iPad?</u></a></li>
<li><a href="https://win11.techidaily.com/notifypcswitchtonightshiftmodewin/"><u>NotifyPC:SwitchToNightShiftModeWin</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-ps1-gaming-on-pc-via-duckstations-tips/"><u>Optimal PS1 Gaming on PC via Duckstation's Tips</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-process-from-cr2-to-jpg-using-windows-software/"><u>Simplified Process: From CR2 to JPG Using Windows Software</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-power-of-personal-storytelling-in-video-content-for-2024/"><u>The Power of Personal Storytelling in Video Content for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/turn-up-the-volume-on-muted-slack-alerts-in-win-11/"><u>Turn Up the Volume on Muted Slack Alerts in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/unplugged-windows-11-a-step-by-step-tutorial/"><u>Unplugged Windows 11: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveil-the-power-players-a-review-of-the-best-consoles-available/"><u>Unveil the Power Players: A Review of the Best Consoles Available</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-the-mechanism-disabling-dim-display-option/"><u>Unveiling the Mechanism: Disabling 'Dim Display' Option</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-group-policy-settings-with-minimal-disruption/"><u>Upgrading Group Policy Settings with Minimal Disruption</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-sticky-notes-opener-hacks/"><u>Windows 11 Sticky Notes: Opener Hacks</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    