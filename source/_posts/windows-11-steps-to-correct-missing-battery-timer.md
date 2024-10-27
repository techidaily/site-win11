---
title: "Windows 11: Steps to Correct Missing Battery Timer"
date: 2024-10-23T01:59:56.975Z
updated: 2024-10-27T09:46:57.084Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: Steps to Correct Missing Battery Timer"
excerpt: "This Article Describes Windows 11: Steps to Correct Missing Battery Timer"
keywords: Windows 11 Power Fix,Timer Battery Error,Fix PC Time Issue,Battery Setting Correction,Win11 Timing Update,Restore Battery Display,Windows Timer Adjustment
thumbnail: https://thmb.techidaily.com/988b0aa2e48e125d13283fa19f222d53a696ba967b4ae3ee4ad76e4ed04670c1.jpg
---

## Windows 11: Steps to Correct Missing Battery Timer

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100530/7443" target="_top" id="2100530">
  <img src="//a.impactradius-go.com/display-ad/7443-2100530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014859/22899" target="_top" id="2014859">
  <img src="//a.impactradius-go.com/display-ad/22899-2014859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014859/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918719/19272" target="_top" id="1918719">
  <img src="//a.impactradius-go.com/display-ad/19272-1918719" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918719/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-the-ls-showdown-tech-titans-clashing-in-real-time/"><u>[New] In 2024, The LS Showdown Tech Titans Clashing in Real Time</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-top-5-budget-friendly-methods-for-live-feed-recordings-for-2024/"><u>[New] Top 5 Budget-Friendly Methods for Live Feed Recordings for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-securing-students-learning-mac-based-lecture-recording/"><u>[Updated] 2024 Approved Securing Students' Learning Mac-Based Lecture Recording</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-ad-ds-printing-woes-on-win-10-and-11-devices/"><u>Conquering AD DS Printing Woes on WIN 10 & 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/embellish-your-windows-11-display-lively-and-animated-walls/"><u>Embellish Your Windows 11 Display: Lively and Animated Walls</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-performance-resurrecting-slow-excel-operations-on-windows/"><u>Enhance Performance: Resurrecting Slow Excel Operations on Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-infinix-smart-8-hd-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Infinix Smart 8 HD FRP Bypass With Best Methods</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-simulate-gps-movement-with-location-spoofer-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>In 2024, How To Simulate GPS Movement With Location Spoofer On Sony Xperia 1 V? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-low-vram-errors-in-magical-education-game-hogwarts/"><u>Overcoming Low VRAM Errors in Magical Education Game 'Hogwarts'</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-tasks-get-your-pcs-outlook-preview/"><u>Simplifying Tasks: Get Your PC's Outlook Preview</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-the-port-reset-error-on-your-usb-device-in-windows-11-a-step-by-step-guide/"><u>Solving the Port Reset Error on Your USB Device in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-incomplete-ryzen-master-driver-installations/"><u>Troubleshooting Incomplete Ryzen Master Driver Installations</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/unlimited-entertainment-on-the-road-using-hotel-or-dorm-mobile-hotspots-with-your-roku-device/"><u>Unlimited Entertainment on the Road: Using Hotel or Dorm Mobile Hotspots with Your Roku Device</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-potential-a-quick-fix-for-windows-pin/"><u>Unlock Potential: A Quick Fix for Windows PIN</u></a></li>
</ul></div>

