---
title: "Reducing System Idleness: Altering Boot Timeout in Win11"
date: 2025-01-03T17:33:05.272Z
updated: 2025-01-06T20:56:56.409Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reducing System Idleness: Altering Boot Timeout in Win11"
excerpt: "This Article Describes Reducing System Idleness: Altering Boot Timeout in Win11"
keywords: Win11 Booting Speed,Reduce System Latency,Optimize Windows Startup,Modify Boot Delay,Minimize Idle Windows,Enhance PC Boot Time,Quickstart Win11
thumbnail: https://thmb.techidaily.com/c35bb55569306b5428a10bd1ab44596d5c722993db7a19d5db6d527a1da8e1b4.png
---

## Reducing System Idleness: Altering Boot Timeout in Win11

 When you turn on your dual-boot system, Windows waits for a while, allowing you to choose the operating system you want to load. However, the default wait time may be too short, giving you little time to decide.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

## 1\. Change Boot Menu Timeout Using the Settings App

 The quickest way to configure the boot menu timeout is via the Settings app. Here's a step-by-step instructions to do that:

1. Press the **Win + I** hotkey to open the **Settings app**.
2. Choose **System** from the left sidebar and **About** from the right pane.
3. Choose **System protection**.  
![System protection option in the Settings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection.jpg)
4. Switch to the **Advanced** tab and click the **Settings** button under the **Startup and Recovery** section.
5. Click the drop-down icon under the **Default operating system** option and choose your default OS.
6. Check the **Time to display list of operating systems** option and select the timeout value. The value can range from **0** to **999**.  
![Time to display list of operating systems option in System Protection window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/time-to-display-list-of-operating-systems-option.jpg)
7. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Change Boot Menu Timeout Using System Configuration

 The System Configuration app, aka msconfig, is a built-in Windows utility that lets you [control your system's startup programs](https://www.makeuseof.com/optimize-startup-programs-windows-11/) and services. You can also use it to adjust various system settings, including the boot menu timeout. To change the boot menu timeout using the System Configuration app, follow the below instructions:

1. Press the **Win** key to open the **Start Menu,** type **System Configuration** in the search bar, and select the same from the result.
2. Switch to the **Boot** tab.
3. Enter the value (seconds) in the **Timeout** section and check the **Make all boot settings permanent** option.  
![Timeout option in msconfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timeout-option.jpg)
4. Click **Apply.**
5. Click **Yes** to confirm your changes.  
![Yes option in msconfig window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/yes-option-1.jpg)
6. Choose the **Restart** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Change Boot Menu Timeout Using the Command Prompt

 If you're an advanced Windows user, you can use Command Prompt to configure the boot menu timeout on your Windows PC. Here's how:

1. Open the Start Menu, type **Command Prompt** in the search bar, and choose **Run as administrator** from the right pane. If this method doesn't work, check out other ways to [launch Command Prompt in Windows](https://www.makeuseof.com/windows-11-open-command-prompt/).
2. In the elevated Command Prompt window, type the following command and press Enter. This will display the current time for which the boot menu appears.  
`bcdedit`
3. Type the following command and press Enter to change the timeout. Make sure to replace **`SECONDS`**with the new timeout.  
`bcdedit /timeout SECONDS`  
![Timeout change command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/timout-change-command.jpg)

 That's it! From the next boot, the boot manager will appear for the specified duration of time.

## 4\. Change Boot Menu Timeout Using the Boot Options

 Another efficient way to configure the boot menu timeout is through the Boot Manager. The Boot Manager, also known as the Boot Loader, is responsible for launching your operating system when you turn on your computer. Not only that, it enables you to select a specific operating system if you are using multiple operating systems on your device.

 To modify the boot menu timeout through the Boot Manager, follow these instructions:

1. Open the Start Menu, click the **Power icon** and choose **Restart** from the context menu. If this method doesn't work, try any other [ways to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/).
2. In the Boot Manager, click on **Change defaults or choose other options**.  
![Change defaults or choose other options in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-defaults-or-choose-other-options.jpg)
3. Select the **Change the timer** option.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Change the timer option in the Boot menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-timer.jpg)
4. Choose a time between the given options.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Choose time in the Boot Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/choose-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control Your System Boot Menu on Windows

 Optimizing the boot menu timeout in Windows is a simple yet effective way to manage your system's startup time. By adjusting the duration for which the boot menu appears, you can ensure that you have adequate time to select your preferred operating system.

 Fortunately, you can configure the wait time as per your choice. In this article, we'll explore four quick ways to change the boot menu timeout in Windows 11\. So, let's begin.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-2024-approved-easy-photo-fixes-an-introduction-to-snapseed/"><u>[New] 2024 Approved Easy Photo Fixes An Introduction to Snapseed</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-innovative-color-correction-strategies-using-luts-in-adobe-premiere-pro/"><u>[New] 2024 Approved Innovative Color Correction Strategies Using LUTs in Adobe Premiere Pro</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-mastering-video-size-adjustments-on-igtv/"><u>[New] 2024 Approved Mastering Video Size Adjustments on IGTV</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-sdr-vs-hdr-the-superiority-of-high-dynamic-range-in-video-production/"><u>[Updated] SDR Vs. HDR The Superiority of High Dynamic Range in Video Production</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-vivo-s18-pro-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Vivo S18 Pro</u></a></li>
<li><a href="https://win-able.techidaily.com/comprehensive-fix-for-pc-players-stop-samurai-warriors-5-from-freezing-or-crashing-now/"><u>Comprehensive Fix for PC Players - Stop Samurai Warriors 5 From Freezing or Crashing Now!</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-installation-of-chrome-on-windows-11-pcs/"><u>Efficient Installation of Chrome on Windows 11 PCs</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-turn-off-find-my-apple-iphone-x-when-phone-is-broken-by-drfone-ios/"><u>How to Turn Off Find My Apple iPhone X when Phone is Broken?</u></a></li>
<li><a href="https://change-location.techidaily.com/ipogo-will-be-the-new-ispoofer-on-vivo-y200-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Vivo Y200? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-based-roblox-availability-error/"><u>Overcoming Windows-Based Roblox Availability Error</u></a></li>
<li><a href="https://win11.techidaily.com/regain-control-rejuvenating-your-hesitant-windows-11-pc/"><u>Regain Control: Rejuvenating Your Hesitant Windows 11 Pc</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-taskbar-invisibility-while-full-screen/"><u>Solutions for Taskbar Invisibility While Full-Screen</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-protect-your-windows-skipping-bitlocker/"><u>Strategies to Protect Your Windows, Skipping BitLocker</u></a></li>
</ul></div>

