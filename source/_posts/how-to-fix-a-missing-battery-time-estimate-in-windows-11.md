---
title: How to Fix a Missing Battery Time Estimate in Windows 11
date: 2024-06-25T11:22:12.275Z
updated: 2024-06-26T11:22:12.275Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix a Missing Battery Time Estimate in Windows 11
excerpt: This Article Describes How to Fix a Missing Battery Time Estimate in Windows 11
keywords: Windows 11 Battery Time,Fixed Missing Battery,Restore Windows Timestamp,Estimating Battery Life,Solve Watts Time Loss,Correct Battery Duration,Unseen Power Countdown Fix
thumbnail: https://thmb.techidaily.com/0ce905cbb913b2eefe4db5c72014c9485f061b0fd3b1b129c677df4a5fe1e713.jpg
---

## How to Fix a Missing Battery Time Estimate in Windows 11

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
<li><a href="https://win11.techidaily.com/the-silent-whisperer-guide-to-win11-menu-hiding/"><u>The Silent Whisperer Guide to Win11 Menu Hiding</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-text-glyphs-in-windows-11/"><u>Discovering Text Glyphs in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-cortana-integration-vivetool-approach/"><u>Optimizing Cortana Integration: ViveTool Approach</u></a></li>
<li><a href="https://win11.techidaily.com/solving-common-closed-captions-issues-in-win11/"><u>Solving Common Closed Captions Issues in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-boot-on-windows-sound-service-reboot-needs/"><u>Troubleshooting Boot-On Windows Sound Service Reboot Needs</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-correcting-type-mistakes-in-windows-11-zerox-error/"><u>Solutions for Correcting Type Mistakes in Windows 11 Zerox Error</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-installer-errors-in-windows-10-and-11/"><u>Overcoming Windows Installer Errors in Windows 10 & 11</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/alidating-your-channels-ad-based-income-for-2024/"><u>[New] Validating Your Channel’s Ad-Based Income for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-nubia-red-magic-8s-pro-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Nubia Red Magic 8S Pro</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-guide-how-to-check-icloud-activation-lock-status-on-your-iphone-13-by-drfone-ios/"><u>In 2024, New Guide How To Check iCloud Activation Lock Status On Your iPhone 13</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-infinix-hot-40-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Infinix Hot 40</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-cutting-edge-audio-capture-gear-top-7-list-2023-edition/"><u>2024 Approved  Cutting-Edge Audio Capture Gear  Top 7 List, 2023 Edition</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-sculpting-brilliance-a-deep-dive-into-hdr-in-lightroom/"><u>2024 Approved  Sculpting Brilliance  A Deep Dive Into HDR in Lightroom</u></a></li>
<li><a href="https://extra-tips.techidaily.com/snap-clean-top-10-apps-to-sharpen-your-digital-world/"><u>Snap Clean  Top 10 Apps to Sharpen Your Digital World</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-itel-s23plus-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Itel S23+ | Dr.fone</u></a></li>
</ul></div>
