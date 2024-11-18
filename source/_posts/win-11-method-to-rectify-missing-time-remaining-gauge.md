---
title: "Win 11: Method to Rectify Missing Time Remaining Gauge"
date: 2024-11-14T19:56:24.326Z
updated: 2024-11-18T07:35:55.591Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win 11: Method to Rectify Missing Time Remaining Gauge"
excerpt: "This Article Describes Win 11: Method to Rectify Missing Time Remaining Gauge"
keywords: Fix Missing Timer Gauge,Resolve Time Lag Issue,Update Clock Display,Realign Game Timer,Correct Gauge Accuracy,Rectify Elapsed Time Gauge,Mend Timing Error
thumbnail: https://thmb.techidaily.com/c8c0a761aab973c79a26bc00df92df723a573173c058dc152cef52dc4b741fd1.jpg
---

## Win 11: Method to Rectify Missing Time Remaining Gauge

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
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2087409/7443" target="_top" id="2087409">
  <img src="//a.impactradius-go.com/display-ad/7443-2087409" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087409/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948881/19272" target="_top" id="1948881">
  <img src="//a.impactradius-go.com/display-ad/19272-1948881" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948881/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106655/12108" target="_top" id="2106655">
  <img src="//a.impactradius-go.com/display-ad/12108-2106655" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106655/12108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-humorous-harmonics-optimal-ringtone-sites/"><u>[New] 2024 Approved Humorous Harmonics Optimal Ringtone Sites</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-optimizing-mac-ipad-iphone-browsing-via-pip/"><u>[Updated] 2024 Approved Optimizing Mac, iPad, iPhone Browsing via PIP</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-exploring-top-ios-psp-emulation-tools-for-gamers/"><u>[Updated] Exploring Top iOS PSP Emulation Tools for Gamers</u></a></li>
<li><a href="https://article-tips.techidaily.com/efficient-windows-file-review-methods-for-2024/"><u>Efficient Windows File Review Methods for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-tecno-spark-go-2023-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Tecno Spark Go (2023) Phone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-audio-service-requiring-a-restart-on-boot/"><u>How to Fix the Windows Audio Service Requiring a Restart on Boot</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-hard-drive-capacities-leveraging-windows-diskusage-command-skills/"><u>Navigating Hard Drive Capacities: Leveraging Windows' DiskUsage Command Skills</u></a></li>
<li><a href="https://win11.techidaily.com/paving-the-path-to-seamless-device-symbiosis/"><u>Paving the Path to Seamless Device Symbiosis</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/prime-streamer-gear-essential-livestream-tools-unveiled/"><u>Prime Streamer Gear Essential Livestream Tools Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/safeguarding-saved-gaming-milestones-with-epic-support/"><u>Safeguarding Saved Gaming Milestones with Epic Support</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-windows-shutters-and-hangouts/"><u>The Ultimate Guide to Windows Shutters and Hangouts</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-contacts-on-motorola-moto-g-stylus-5g-2023-without-backup-by-fonelab-android-recover-contacts/"><u>The way to recover deleted contacts on Motorola Moto G Stylus 5G (2023) without backup.</u></a></li>
<li><a href="https://win-exclusive.techidaily.com/ultimate-selection-of-top-10-security-apps-to-protect-your-windowsandroid-systems-from-hacks/"><u>Ultimate Selection of Top 10 Security Apps to Protect Your Windows/Android Systems From Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-reclaiming-your-sound-settings/"><u>Win10/11: Reclaiming Your Sound Settings</u></a></li>
</ul></div>

