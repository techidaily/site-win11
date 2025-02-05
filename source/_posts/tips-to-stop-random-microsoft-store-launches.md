---
title: Tips to Stop Random Microsoft Store Launches
date: 2025-01-28T01:39:32.115Z
updated: 2025-02-04T08:53:07.891Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Close Microsoft Store's Background Processes

 Windows might keep opening the Microsoft Store if there’s a process still running in the background. To fix it, you should use Task Manager to stop any background activity.

 Press**Ctrl + Shift + Esc** to bring up Task Manager. There, right-click**Microsoft Store** and select**End task** .

![Close Windows Store with Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/task-manager-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1KKovVi9epE?si=EF7KA7b4KsEpWA-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Re-register Microsoft Store

 If nothing worked until now, you could re-register the Microsoft Store app. To do it, launch PowerShell with administrative rights and paste this code:

`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}<strong> </strong>`

 Then, press**Enter** to run it.

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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-transforming-android-devices-into-broadcast-powerhouses-with-obs/"><u>[New] 2024 Approved Transforming Android Devices Into Broadcast Powerhouses with OBS</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-go-frame-by-frame-on-youtube-video-5-free-methods/"><u>[New] In 2024, How to Go Frame by Frame on YouTube Video [5 Free Methods]</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-stay-ahead-of-the-curve-with-iphone-and-androids-best-photo-sticker-apps/"><u>[New] Stay Ahead of the Curve with iPhone and Android's Best Photo Sticker Apps</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-stream-power-showdown-vmix-clashes-with-wirecast-for-broadcast-excellence/"><u>[Updated] In 2024, Stream Power Showdown VMix Clashes with Wirecast for Broadcast Excellence</u></a></li>
<li><a href="https://network-issues.techidaily.com/combatting-crazed-windows-7-graphics/"><u>Combatting Crazed Windows 7 Graphics</u></a></li>
<li><a href="https://win11.techidaily.com/direct-os-instructions-replicating-your-drive/"><u>Direct OS Instructions: Replicating Your Drive</u></a></li>
<li><a href="https://fox-helps.techidaily.com/elite-series-for-engaging-typographic-movement-for-2024/"><u>Elite Series for Engaging Typographic Movement for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-google-chromes-inability-to-save-files-on-windows-pc/"><u>Fixing Google Chrome's Inability to Save Files on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/from-dull-to-dynamic-effortless-methods-for-transforming-themes-on-win11/"><u>From Dull to Dynamic: Effortless Methods for Transforming Themes on Win11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/handling-d3dx9-dll-missing-errors-in-windows-a-comprehensive-fix-guide/"><u>Handling D3DX9 DLL Missing Errors in Windows – A Comprehensive Fix Guide</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-graph-gems-2017s-statistical-youtube-surprises/"><u>In 2024, Graph Gems 2017'S Statistical YouTube Surprises</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-understanding-the-zip-to-srt-file-transition/"><u>In 2024, Understanding the Zip to Srt File Transition</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-camera-and-mic-permissions-with-edge-guard/"><u>Mastering Camera & Mic Permissions with Edge Guard</u></a></li>
<li><a href="https://win11.techidaily.com/mystery-red-x-interpretation-of-windows-directory-marks/"><u>Mystery Red X: Interpretation of Windows Directory Marks</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-ms-store-glitches-guide-to-error-0x80072f17/"><u>Overcoming MS Store Glitches: Guide to Error 0X80072f17</u></a></li>
<li><a href="https://win11.techidaily.com/return-to-standard-touch-keyboard-alignment-in-windows-11/"><u>Return to Standard Touch Keyboard Alignment in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/what-are-ai-pcs-and-what-makes-them-different/"><u>What Are AI PCs, and What Makes Them Different?</u></a></li>
<li><a href="https://win11.techidaily.com/why-skip-the-extra-just-linux-no-more-wsl/"><u>Why Skip the Extra? Just Linux! No More WSL</u></a></li>
<li><a href="https://fox-zero.techidaily.com/windows-10-dell/"><u>Windows 10のリカバリーパーティション作成説明: Dell機にて手順集</u></a></li>
</ul></div>

