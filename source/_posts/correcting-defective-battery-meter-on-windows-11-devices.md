---
title: Correcting Defective Battery Meter on Windows 11 Devices
date: 2025-01-18T09:22:17.839Z
updated: 2025-01-24T18:34:53.360Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Defective Battery Meter on Windows 11 Devices
excerpt: This Article Describes Correcting Defective Battery Meter on Windows 11 Devices
keywords: Win11 Battery Fault Fix,W11 Battery Sensor Repair,Windows Battery Calibration,Power Meter Correction Win11,Correcting Battery Errors Win11,Optimize Win11 Battery Readout,Battery Health Improvement Win11
thumbnail: https://thmb.techidaily.com/f35affd0446f81f879a70f50fd131f599003c290d87b21cce9966af54d527118.jpg
---

## Correcting Defective Battery Meter on Windows 11 Devices

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-essential-free-layering-and-editing-apps-mobile-edition-top-10/"><u>[New] 2024 Approved Essential Free Layering & Editing Apps - Mobile Edition (Top 10)</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-integrating-visuals-smoothly-mastering-snap-camera-in-microsoft-teams-for-2024/"><u>[New] Integrating Visuals Smoothly Mastering Snap Camera in Microsoft Teams for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-most-liked-prime-videos-amongst-twittersphere/"><u>[New] Most Liked Prime Videos Amongst Twittersphere</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-ultimate-guide-9-essential-360-degree-recording-techniques/"><u>[Updated] 2024 Approved Ultimate Guide 9 Essential 360-Degree Recording Techniques</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-unleash-potential-with-informed-tagging-on-youtube/"><u>[Updated] In 2024, Unleash Potential with Informed Tagging on YouTube</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-unleashing-clarity-with-eizos-coloredge-cg318-4k/"><u>[Updated] Unleashing Clarity with EIZO's ColorEdge CG318-4K</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-wi-fi-connectivity-fixing-incomplete-network-commands-on-pc/"><u>Enhancing Wi-Fi Connectivity: Fixing Incomplete Network Commands on PC</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-windows-11-a-compreenas-list-of-must-have-modifications/"><u>Fine-Tuning Windows 11: A Compreenas List of Must-Have Modifications</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-the-character-map-in-windows-11/"><u>How to Open the Character Map in Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-refine-visuals-effortlessly-editing-videos-using-storyremix-in-windows-11/"><u>In 2024, Refine Visuals Effortlessly Editing Videos Using StoryRemix in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/speed-sensors-windows-based-methods-for-examining-network-rate/"><u>Speed Sensors: Windows-Based Methods for Examining Network Rate</u></a></li>
<li><a href="https://win11.techidaily.com/unpackaging-problems-solved-fixing-windows-package-not-open-errors/"><u>Unpackaging Problems Solved: Fixing Windows Package Not Open Errors</u></a></li>
</ul></div>

