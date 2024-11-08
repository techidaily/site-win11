---
title: "Win 11: Method to Rectify Missing Time Remaining Gauge"
date: 2024-10-31T17:46:23.523Z
updated: 2024-11-07T22:42:36.807Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1997657/19272" target="_top" id="1997657">
  <img src="//a.impactradius-go.com/display-ad/19272-1997657" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997657/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Double-click the new DWORD and set the Value data to**1** . Click**Ok** to close the window.  
![Changing value data in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/registry-battery-dword.jpg)
6. Repeat the previous two steps to create two more DWORD values called**EnergyEstimationDisabled** and**UserBatteryDischargeEstimator** .

<!-- affiliate ads begin -->
<span id="1983588">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983588.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983588">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983588.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983588%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983588/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. You don't need to change the Value data for these, as they should default to a 0 value.

 Close the Registry Editor and restart your laptop. When you hover over the battery icon in the System Tray, it should show the estimated time remaining. And while you're at it, check out[how to add shortcuts to the System Tray](https://www.makeuseof.com/windows-11-add-shortcuts-menu-to-system-tray/) to make it even more useful.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151892/7443" target="_top" id="2151892">
  <img src="//a.impactradius-go.com/display-ad/7443-2151892" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151892/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-glue.techidaily.com/new-fully-encompassed-angle-gearing-for-2024/"><u>[New] Fully Encompassed Angle Gearing for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-the-gamers-blueprint-securing-memorable-moments-with-4-methods/"><u>[Updated] The Gamers' Blueprint Securing Memorable Moments with 4 Methods</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-next-gen-escapades-upcoming-best-playstation-vr-games-to-try/"><u>2024 Approved Next-Gen Escapades Upcoming Best PlayStation VR Games to Try</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/hevchdh2-65-4k8k/"><u>高效能HEVC壓縮技術：免費HD影片H.2 65 解碼器提供4K/8K播放功能</u></a></li>
<li><a href="https://tech-haven.techidaily.com/easy-local-installation-tips-for-getting-started-with-llama-2/"><u>Easy Local Installation Tips for Getting Started with LLAMA 2</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expert-picks-safest-and-most-reliable-mobile-devices-for-children-today/"><u>Expert Picks: Safest and Most Reliable Mobile Devices for Children Today</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-windows-11-status-bar-with-a-weather-icon/"><u>Personalize Windows 11 Status Bar with a Weather Icon</u></a></li>
<li><a href="https://win11.techidaily.com/reactivation-guide-for-apps-from-the-microsoft-store/"><u>Reactivation Guide for Apps From the Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/resurrect-your-disappearing-apps-top-6-techniques-for-win-1011/"><u>Resurrect Your Disappearing Apps: Top 6 Techniques for Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-data-wins-prime-encryption-software-154-chars/"><u>Secure Your Data: Win's Prime Encryption Software (154 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-microsoft-edge-shortcut-keeps-appearing-on-your-desktop/"><u>What to Do if Microsoft Edge Shortcut Keeps Appearing on Your Desktop</u></a></li>
</ul></div>

