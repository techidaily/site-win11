---
title: Tips to Stop Random Microsoft Store Launches
date: 2024-12-31T16:13:26.060Z
updated: 2025-01-06T18:24:19.213Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips to Stop Random Microsoft Store Launches
excerpt: This Article Describes Tips to Stop Random Microsoft Store Launches
keywords: Stopping MS Store Crashes,Preventing Unexpected Windows Store,Avoiding MSTray Errors,Fixing Spontaneous MS Apps Launch,Troubleshoot Unpredictable Microsoft Store,Stop Sudden Windows 10 Apps Start,Cease Random Storeware Activation
thumbnail: https://thmb.techidaily.com/f9a5463fbd0c790fcad5c9ca24a63fabc5c5b34da6ae2629a7d19232172ec8eb.jpg
---

## Tips to Stop Random Microsoft Store Launches

 The Microsoft Store has come a long way since its introduction to Windows 8\. Every app, game, or movie available on the store is certified, so you don’t have to worry about infecting your computer with malware.

 But what if Windows keeps opening the Microsoft Store for no apparent reason? If you’ve run into the same issue, this guide should help you fix it.

##

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Close Microsoft Store's Background Processes

 Windows might keep opening the Microsoft Store if there’s a process still running in the background. To fix it, you should use Task Manager to stop any background activity.

 Press**Ctrl + Shift + Esc** to bring up Task Manager. There, right-click**Microsoft Store** and select**End task** .

![Close Windows Store with Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/task-manager-1.jpg)

##

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Restart the Microsoft Store Services

 There’s a chance that the Microsoft Store keeps acting up because of a service malfunction. The Microsoft Store Install Service is the one that works in the background to keep the store working.

 This is why restarting the service might be enough to fix Microsoft Store.

1. In the Start menu search bar, search for**services** and select**Run as administrator** .
2. In the Services window, locate and open**Microsoft Store Install Service** .
3. Click**Stop > Start** to restart it.
4. Restart your computer and monitor if Microsoft Store keeps opening.

![Restart Microsoft Store service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/store-service-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Re-register Microsoft Store

 If nothing worked until now, you could re-register the Microsoft Store app. To do it, launch PowerShell with administrative rights and paste this code:

`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}<strong> </strong>`

 Then, press**Enter** to run it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Apply Generic Fixes for Microsoft Store Issues

 You may encounter this problem if the cache has become corrupted. As such, check out[how to fix a damaged Microsoft Store cache](https://www.makeuseof.com/ways-to-fix-damaged-microsoft-store-cache/) for more ways to fix this annoying problem.

 Similarly, a virus may be causing the Microsoft Store to open. Check out[how to remove malware using a Microsoft Defender offline scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) and give your PC a deep clean.

## Fix the Microsoft Store App Opening Itself

 Having the Microsoft Store app open by itself can be very disruptive, especially if it opens on top of all windows. Hopefully, one of these solutions worked and Microsoft Store has stopped launching by itself.

 If you’ve had enough and uninstalled it, you can still get Microsoft apps without the Microsoft Store.

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
<li><a href="https://extra-support.techidaily.com/new-iphone-and-android-edition-compile-the-most-useful-top-8-edits-tools/"><u>[New] IPhone and Android Edition Compile the Most Useful Top 8 Edits Tools</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-optimal-method-for-integrating-gopro-footage-into-360-degree-films/"><u>[New] Optimal Method for Integrating GoPro Footage Into 360-Degree Films</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-how-to-choose-a-live-streaming-platform-with-10-tips/"><u>[Updated] 2024 Approved How to Choose a Live Streaming Platform with 10 Tips?</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-premier-selection-of-11-costless-yt-moniker-makers/"><u>[Updated] The Premier Selection of 11 Costless YT Moniker Makers</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-essential-list-6-free-online-platforms-for-youtube-short-downloads/"><u>2024 Approved Essential List 6 Free Online Platforms for YouTube Short Downloads</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-sound-problem-windows-another-application-interference/"><u>Correcting Sound Problem: Windows 'Another Application' Interference</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-windows-account-access-lockouts/"><u>Fine-Tuning Windows Account Access Lockouts</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-windows-setups-small-powerful-computers/"><u>Ideal Windows Setups: Small, Powerful Computers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-leveraging-connected-networks-fb-to-whatsapp-video-sharing-strategies/"><u>In 2024, Leveraging Connected Networks FB to WhatsApp Video Sharing Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-typical-anydesk-windows-hiccups/"><u>Navigating Typical AnyDesk Windows Hiccups</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-picks-leading-capture-cards-for-enthusiast-streamers/"><u>Proven Picks Leading Capture Cards for Enthusiast Streamers</u></a></li>
<li><a href="https://win11.techidaily.com/raising-sound-levels-restoring-bt-speaker-functionality/"><u>Raising Sound Levels: Restoring BT Speaker Functionality</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/alize-your-day-with-these-top-10-yoga-videos-for-2024/"><u>Revitalize Your Day with These Top 10 Yoga Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steering-clear-of-fatigue-post-winning-life-with-windows/"><u>Steering Clear of Fatigue Post Winning Life with Windows</u></a></li>
<li><a href="https://some-approaches.techidaily.com/step-by-step-guide-transforming-avi-files-into-m4v-format/"><u>Step-by-Step Guide: Transforming AVI Files Into M4V Format</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-incorporating-your-own-lock-pattern-on-windows/"><u>Step-by-Step: Incorporating Your Own Lock Pattern on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/triumphant-three-column-widget-setup-in-the-latest-win11-version/"><u>Triumphant Three-Column Widget Setup in the Latest Win11 Version</u></a></li>
<li><a href="https://win11.techidaily.com/winfix-methods-to-overcome-missing-msvcrt120dll-errors/"><u>Winfix: Methods to Overcome Missing Msvcrt120dll Errors</u></a></li>
</ul></div>

