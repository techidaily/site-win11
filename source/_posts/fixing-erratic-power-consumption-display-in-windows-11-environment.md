---
title: Fixing Erratic Power Consumption Display in Windows 11 Environment
date: 2024-12-10T09:50:54.285Z
updated: 2024-12-13T08:20:25.465Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Erratic Power Consumption Display in Windows 11 Environment
excerpt: This Article Describes Fixing Erratic Power Consumption Display in Windows 11 Environment
keywords: Power Consumption Fix,Erratic Display Windows,Windows 11 Energy Usage,PC Power Management,Consume Less Electricity,Optimize Win11 Power,Reduce Windows Battery Drain
thumbnail: https://thmb.techidaily.com/295eb1a512b03cd4604053efc700e515a23fe08d7898031d0786b31b79d36b64.jpg
---

## Fixing Erratic Power Consumption Display in Windows 11 Environment

 Keeping track of how much charge remains in your laptop battery is easy. By default, hovering over the battery icon in the System Tray displays an estimate of battery time remaining, along with a percentage. Occasionally, the time estimate goes missing, leaving you to work out how much usage time you have left by percentage alone.

 Here's how to get that useful battery time remaining estimate showing again if it has vanished from your notebook.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Where Did the Time Estimate Go?

 There are a few possible reasons why the time estimate has disappeared. The change often happens after upgrading to Windows 11, but even simply updating the OS can cause it. A later update may fix the issue, but that isn't always the case.

![battery icon tooltip in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/battery-time.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 It isn't entirely obvious what the root cause is. It could be a conflict in the Registry, which can occur during the update process. It also seems to have been deliberately disabled by Microsoft in some updates. Perhaps because the company is working on power and battery settings for a future update.

## How to Enable the Battery Time Estimate in the Registry

 Whatever the cause of its disappearance, the battery time estimate is still part of the OS. And with a bit of Registry tweaking, it can be brought back into view.

 As always, it is a good idea to[back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you make any changes. This is only a minor edit and shouldn't cause problems, but it's better to be safe than sorry.

1. Click Windows Search and type**Regedit** to find the Registry Editor. You don't need to choose Run as Administrator. Just select the search result.
2. With the Registry Editor open, navigate to: **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Power** .
3. If there is no**Power** key, right-click on**Control** in the navigation panel, and select**New > Key** . Name the new registry key**Power** .  
![power values in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-key.jpg)
4. Right-click the Power key and select**New > DWORD (32-bit) Value** . Set the name of this DWORD as**EnergyEstimationEnabled** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HSFNIAYChbA?si=4TIlsUrYmY5vP2il" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-fundamental-codex-for-online-video-communities/"><u>[New] In 2024, Fundamental Codex for Online Video Communities</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-prime-sixteen-camera-arrays-for-professionals/"><u>[New] Prime Sixteen Camera Arrays for Professionals</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-decoding-youtubes-srt-download-with-3-methods-for-2024/"><u>[Updated] Decoding YouTube's SRT Download with 3 Methods for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-how-to-add-edit-and-optimize-youtube-tagstitledescription-for-more-views-for-2024/"><u>[Updated] How to Add, Edit and Optimize YouTube Tags/Title/Description for More Views for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-gaming-experience-speedy-steam-content-on-windows/"><u>Enhance Gaming Experience: Speedy Steam Content on Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/finding-the-most-economical-streaming-apps-for-your-phone-for-2024/"><u>Finding the Most Economical Streaming Apps for Your Phone for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fix-extra-screen-problems-in-windows-11/"><u>Fix Extra Screen Problems in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-vivo-v29-pro-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Vivo V29 Pro to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/keep-your-computer-up-to-date-install-latest-drivers-for-hp-omen-15/"><u>Keep Your Computer Up-to-Date – Install Latest Drivers for HP Omen 15</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-printer-management-system/"><u>Navigating Through Windows' Printer Management System</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-closed-off-email-in-windows-11/"><u>Restoring Closed-Off Email in Windows 11</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/unlocking-full-potential-saving-and-playing-gifs-on-iphones/"><u>Unlocking Full Potential Saving & Playing GIFs on iPhones</u></a></li>
</ul></div>

