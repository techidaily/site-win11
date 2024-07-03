---
title: Overcoming the Absence of Battery Life Duration in PCs Running Win 11
date: 2024-06-25T11:24:45.607Z
updated: 2024-06-26T11:24:45.607Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming the Absence of Battery Life Duration in PCs Running Win 11
excerpt: This Article Describes Overcoming the Absence of Battery Life Duration in PCs Running Win 11
keywords: Win 11 Power Efficiency,PC Battery Endurance,Extend Windows PC Life,Optimal Win 11 Battery,Minimize Win 11 Drainage,Enhance Win 11 Usability,Prolong Win 11 Runtime
thumbnail: https://thmb.techidaily.com/3616fb63d3712b98cc05f9583f4211869f6e4c453eb6e04c1cfde40ef70bbce3.jpg
---

## Overcoming the Absence of Battery Life Duration in PCs Running Win 11

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
<li><a href="https://win11.techidaily.com/14-unveiling-windows-11-post-update-feature-list/"><u>14 Unveiling Windows 11: Post-Update Feature List</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-set-default-touch-input-placement/"><u>Win 11: Set Default Touch Input Placement</u></a></li>
<li><a href="https://win11.techidaily.com/visual-virtuoso-top-tips-to-overcome-blurry-windows-11-displays/"><u>Visual Virtuoso: Top Tips to Overcome Blurry Windows 11 Displays</u></a></li>
<li><a href="https://win11.techidaily.com/fix-guide-to-troubleshoot-function-keys-in-win-11/"><u>Fix: Guide to Troubleshoot Function Keys in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-disappearances-in-system-navigator/"><u>Eradicating Disappearances in System Navigator</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-setup-for-windows-11-install-craft-usb-in-just-three-ways/"><u>Rapid Setup for Windows 11 Install: Craft USB in Just Three Ways</u></a></li>
<li><a href="https://win11.techidaily.com/finding-essential-data-win-pc-ip-and-mac-via-powershell/"><u>Finding Essential Data: Win PC IP & MAC via PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-mouse-pointer-prominence-in-windows-11/"><u>Enhancing Mouse Pointer Prominence in Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-top-10-budget-friendly-cam-recorder-apps/"><u>[New] In 2024, Top 10 Budget-Friendly Cam Recorder Apps</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-accurate-money-forecasting-apps-for-tiktok-users/"><u>[New] Accurate Money Forecasting Apps for TikTok Users</u></a></li>
<li><a href="https://fix-guide.techidaily.com/poco-x6-pro-screen-unresponsive-heres-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Poco X6 Pro Screen Unresponsive? Heres How to Fix It | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-download-windows-movie-maker-for-free-a-beginners-guide/"><u>Updated 2024 Approved Download Windows Movie Maker for Free A Beginners Guide</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-honor-90-lite-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Honor 90 Lite Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/roductivity-in-duality-employment-and-video-creation/"><u>[New] Productivity in Duality  Employment & Video Creation</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/securing-your-fb-conversations-with-recordings-for-2024/"><u>Securing Your FB Conversations with Recordings for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-apple-iphone-14-drfone-by-drfone-virtual-ios/"><u>In 2024, 5 Hassle-Free Solutions to Fake Location on Find My Friends Of Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-realme-12-proplus-5g-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Realme 12 Pro+ 5G?</u></a></li>
</ul></div>
