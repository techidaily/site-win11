---
title: "Speeding Up Wake-Up Sequence: Windows 11 Boot Timer Control"
date: 2024-11-30T17:23:38.938Z
updated: 2024-12-06T21:41:02.885Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Speeding Up Wake-Up Sequence: Windows 11 Boot Timer Control"
excerpt: "This Article Describes Speeding Up Wake-Up Sequence: Windows 11 Boot Timer Control"
keywords: Win11 Boot Speed,Wakeup Timer Control,Fast Windows Start,Booting Time Reduction,Timer for Windows Logon,Accelerate Login Times,Windows Boot Optimization
thumbnail: https://thmb.techidaily.com/815fea7976911214190dec2e4ce8ef31c5b56fc35aca9555d7d0112a6571e067.jpg
---

## Speeding Up Wake-Up Sequence: Windows 11 Boot Timer Control

 When you turn on your dual-boot system, Windows waits for a while, allowing you to choose the operating system you want to load. However, the default wait time may be too short, giving you little time to decide.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Change Boot Menu Timeout Using the Settings App

 The quickest way to configure the boot menu timeout is via the Settings app. Here's a step-by-step instructions to do that:

1. Press the **Win + I** hotkey to open the **Settings app**.
2. Choose **System** from the left sidebar and **About** from the right pane.
3. Choose **System protection**.  
![System protection option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection.jpg)
4. Switch to the **Advanced** tab and click the **Settings** button under the **Startup and Recovery** section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click the drop-down icon under the **Default operating system** option and choose your default OS.
6. Check the **Time to display list of operating systems** option and select the timeout value. The value can range from **0** to **999**.  
![Time to display list of operating systems option in System Protection window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/time-to-display-list-of-operating-systems-option.jpg)
7. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/793ViIxl4tI?si=DDBkjPlPX5bZ-f1Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Change Boot Menu Timeout Using System Configuration

 The System Configuration app, aka msconfig, is a built-in Windows utility that lets you [control your system's startup programs](https://www.makeuseof.com/optimize-startup-programs-windows-11/) and services. You can also use it to adjust various system settings, including the boot menu timeout. To change the boot menu timeout using the System Configuration app, follow the below instructions:

1. Press the **Win** key to open the **Start Menu,** type **System Configuration** in the search bar, and select the same from the result.
2. Switch to the **Boot** tab.
3. Enter the value (seconds) in the **Timeout** section and check the **Make all boot settings permanent** option.  
![Timeout option in msconfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timeout-option.jpg)
4. Click **Apply.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Click **Yes** to confirm your changes.  
![Yes option in msconfig window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/yes-option-1.jpg)
6. Choose the **Restart** button.

## 3\. Change Boot Menu Timeout Using the Command Prompt

 If you're an advanced Windows user, you can use Command Prompt to configure the boot menu timeout on your Windows PC. Here's how:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other ways to [launch Command Prompt in Windows](https://www.makeuseof.com/windows-11-open-command-prompt/).
2. In the elevated Command Prompt window, type the following command and press Enter. This will display the current time for which the boot menu appears.  
`bcdedit`
3. Type the following command and press Enter to change the timeout. Make sure to replace **`SECONDS`**with the new timeout.  
`bcdedit /timeout SECONDS`  
![Timeout change command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timout-change-command.jpg)

 That's it! From the next boot, the boot manager will appear for the specified duration of time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Change Boot Menu Timeout Using the Boot Options

 Another efficient way to configure the boot menu timeout is through the Boot Manager. The Boot Manager, also known as the Boot Loader, is responsible for launching your operating system when you turn on your computer. Not only that, it enables you to select a specific operating system if you are using multiple operating systems on your device.

 To modify the boot menu timeout through the Boot Manager, follow these instructions:

1. Open the Start Menu, click the **Power icon** and choose **Restart** from the context menu. If this method doesn't work, try any other [ways to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/).
2. In the Boot Manager, click on **Change defaults or choose other options**.  
![Change defaults or choose other options in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-defaults-or-choose-other-options.jpg)
3. Select the **Change the timer** option.  
![Change the timer option in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-timer.jpg)
4. Choose a time between the given options.  
![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)

## Control Your System Boot Menu on Windows

 Optimizing the boot menu timeout in Windows is a simple yet effective way to manage your system's startup time. By adjusting the duration for which the boot menu appears, you can ensure that you have adequate time to select your preferred operating system.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-top-8-innovative-affordable-online-srt-services-exposed/"><u>[New] 2024 Approved Top 8 Innovative, Affordable Online SRT Services Exposed</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-unlocking-the-secrets-of-google-podcast-uploads/"><u>2024 Approved Unlocking the Secrets of Google Podcast Uploads</u></a></li>
<li><a href="https://win-answers.techidaily.com/bypassing-bugs-in-armored-core-6s-fires-of-rubicon-effective-strategies-for-pc-players/"><u>Bypassing Bugs in Armored Core 6'S 'Fires of Rubicon': Effective Strategies for PC Players</u></a></li>
<li><a href="https://win11.techidaily.com/directx-comprehensible-guide-to-downloading-and-updating/"><u>DirectX: Comprehensible Guide to Downloading and Updating</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-partially-working-windows-headphone-speakers/"><u>Fixing Partially Working Windows Headphone Speakers</u></a></li>
<li><a href="https://facebook.techidaily.com/free-updates-frenzy-top-strategies-to-organize-your-facebook-timings/"><u>Free Updates Frenzy: Top Strategies to Organize Your Facebook Timings</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-channeling-changes-transition-to-youtubes-updated-membership-model/"><u>In 2024, Channeling Changes Transition to YouTube's Updated Membership Model</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/mouse-woes-no-response-in-windows/"><u>Mouse Woes: No Response in Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/newest-wacom-graphic-tablet-drivers-released-download-and-install-now/"><u>Newest Wacom Graphic Tablet Drivers Released: Download & Install Now!</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-enhancing-win-written-works/"><u>The Ultimate Guide to Enhancing Win-Written Works</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-for-rpc-server-unreachable-errors-on-pc/"><u>Troubleshooting Steps for 'RPC Server Unreachable' Errors on PC</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-winning-potential-navigate-fullscreen-challenges-sonic-frontiers-w11/"><u>Unleashing Winning Potential: Navigate Fullscreen Challenges, Sonic Frontiers (W11)</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/unveiling-modern-techniques-for-gesture-interpretation/"><u>Unveiling Modern Techniques for Gesture Interpretation</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    