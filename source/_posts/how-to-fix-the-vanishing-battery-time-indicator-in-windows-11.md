---
title: How to Fix the Vanishing Battery Time Indicator in Windows 11
date: 2024-06-25T11:39:30.803Z
updated: 2024-06-26T11:39:30.803Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Vanishing Battery Time Indicator in Windows 11
excerpt: This Article Describes How to Fix the Vanishing Battery Time Indicator in Windows 11
keywords: Windows Battery Life,Save Power Mode,Low Battery Alerts,Battery Health Check,Optimize Battery Use,Fix Time Indicator,Manage Battery Settings
thumbnail: https://thmb.techidaily.com/4d82cc5d4830160f77be1be23b3b0d5c8cbc630ac82437e197dd592c77a4c46e.jpg
---

## How to Fix the Vanishing Battery Time Indicator in Windows 11

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .
5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .
7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

## Fix a Missing Battery Time Estimate on Windows

 Not being able to easily see the estimate of battery time remaining probably isn't going to keep you up at night. But it is a handy feature if using your laptop away from a power source. Luckily, a few minutes spent editing the Registry will fix the problem, so you always know how long it will be before your battery dies.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/navigate-and-control-your-network-storage-on-windows-11/"><u>Navigate and Control Your Network Storage on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-windows-a-start-free-of-ads/"><u>Streamlined Windows: A Start Free of Ads</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-source-of-windows-parse-error-0xc00ce556/"><u>Dissecting the Source of Windows' Parse Error 0xC00CE556</u></a></li>
<li><a href="https://win11.techidaily.com/brightening-your-computerenas-dark-background-issue/"><u>Brightening Your Computer'enas Dark Background Issue</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-resolving-roblox-glitches-on-pc/"><u>Guidelines for Resolving Roblox Glitches on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-num-caps-and-scroll-lock-key-indicators-to-windows-11s-system-tray/"><u>How to Add Num, Caps, and Scroll Lock Key Indicators to Windows 11’S System Tray</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-dxgi-error-by-reattaching-devices-in-windows/"><u>Bypassing DXGI ERROR by Reattaching Devices in Windows</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-gmail-password-on-infinix-smart-7-devices-by-drfone-android/"><u>How to Reset Gmail Password on Infinix Smart 7 Devices</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-13t-bootloader-easily-by-drfone-android/"><u>How to Unlock Xiaomi 13T Bootloader Easily</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-itel-a60s-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Itel A60s | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-color-lut-in-video-how-to-color-grade-your-video-for-2024/"><u>New Color Lut in Video -How to Color Grade Your Video for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-ultimate-tutorial-for-adding-gifs-and-emojis-in-instagram-stories/"><u>The Ultimate Tutorial for Adding GIFs & Emojis in Instagram Stories</u></a></li>
<li><a href="https://extra-information.techidaily.com/peak-performance-fps-in-deliberate-movements/"><u>Peak Performance FPS in Deliberate Movements</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-assessing-effectiveness-of-reduced-shaking-in-adobe-photos/"><u>In 2024, Assessing Effectiveness of Reduced Shaking in Adobe Photos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-revolutionizing-the-way-we-see-toolwiz-apps-full-review-2023/"><u>In 2024, Revolutionizing the Way We See  Toolwiz App's Full Review, 2023</u></a></li>
</ul></div>
