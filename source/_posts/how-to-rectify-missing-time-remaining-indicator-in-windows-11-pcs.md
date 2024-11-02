---
title: How to Rectify Missing Time Remaining Indicator in Windows 11 PCs
date: 2024-10-31T00:46:38.487Z
updated: 2024-11-01T16:21:53.306Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Rectify Missing Time Remaining Indicator in Windows 11 PCs
excerpt: This Article Describes How to Rectify Missing Time Remaining Indicator in Windows 11 PCs
keywords: Windows 11 Timer Fix,Time Remain Indicator Correction,Win11 Time Error Resolution,Missing Time Display in Win11,PCs Time Alert Issue,Rectify Win11 Time Loss,Windows 11 Timer Glitch Fix
thumbnail: https://thmb.techidaily.com/d00f8f89497ceffd0abb3141cb4e3658817be8d659619b87570cab49fe038d18.jpg
---

## How to Rectify Missing Time Remaining Indicator in Windows 11 PCs

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
<a href="https://aligracehair.sjv.io/c/5597632/1925549/19272" target="_top" id="1925549">
  <img src="//a.impactradius-go.com/display-ad/19272-1925549" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925549/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1934188/19272" target="_top" id="1934188">
  <img src="//a.impactradius-go.com/display-ad/19272-1934188" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934188/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087408/7443" target="_top" id="2087408">
  <img src="//a.impactradius-go.com/display-ad/7443-2087408" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087408/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-the-ultimate-wirecast-playbook-for-engaging-youtube-streamers/"><u>[Updated] 2024 Approved The Ultimate WireCast Playbook for Engaging YouTube Streamers</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-for-beginners-best-film-and-point-shoot-cameras-reviewed/"><u>[Updated] In 2024, For Beginners Best Film and Point-Shoot Cameras Reviewed</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-quick-guide-to-achieving-video-freeze-effects-on-snapchat-for-2024/"><u>[Updated] Quick Guide to Achieving Video Freeze Effects on Snapchat for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/decode-widows-code-to-unfreeze-handbrake/"><u>Decode Widows' Code to Unfreeze HandBrake</u></a></li>
<li><a href="https://win11.techidaily.com/from-basic-to-winning-converting-batch-to-executable/"><u>From Basic to Winning: Converting Batch to Executable</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-oppo-k11x-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Oppo K11x Data? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/1722995368995-rust-graphical-anomaly-resolved/"><u>Rust Graphical Anomaly - Resolved</u></a></li>
<li><a href="https://win-comparisons.techidaily.com/ssd-performanceprobleme-in-windows-11-aufdecken-und-beheben-warum-ihre-festplatte-schlaft/"><u>SSD-Performanceprobleme in Windows 11 Aufdecken Und Beheben - Warum Ihre Festplatte Schläft</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-how-to-enhance-your-workflow-via-menus/"><u>The Blueprint: How to Enhance Your Workflow via Menus</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-file-compression-via-cli/"><u>The Essential Guide to File Compression via CLI</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-assembling-a-taskbar-on-windows-11-slate/"><u>The Ultimate Guide to Assembling a Taskbar on Windows 11 Slate</u></a></li>
<li><a href="https://win11.techidaily.com/window-terminal-design-your-own-palette/"><u>Window Terminal: Design Your Own Palette</u></a></li>
</ul></div>

