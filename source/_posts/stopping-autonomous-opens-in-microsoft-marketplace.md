---
title: Stopping Autonomous Opens in Microsoft Marketplace
date: 2025-01-05T17:39:02.324Z
updated: 2025-01-06T20:28:44.265Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stopping Autonomous Opens in Microsoft Marketplace
excerpt: This Article Describes Stopping Autonomous Opens in Microsoft Marketplace
keywords: Open Marketplace Risks,Disabling Automation Tools,Safe Microsoft Store,Preventing Unauthorized Opens,Control Autonomous Programs,Secure Store Integrity,Blocking Unsolicited Software
thumbnail: https://thmb.techidaily.com/39891eff73508b464f66ea96b5a005498dc7a497b224e926f9156c826add0320.jpeg
---

## Stopping Autonomous Opens in Microsoft Marketplace

 The Microsoft Store has come a long way since its introduction to Windows 8\. Every app, game, or movie available on the store is certified, so you don’t have to worry about infecting your computer with malware.

 But what if Windows keeps opening the Microsoft Store for no apparent reason? If you’ve run into the same issue, this guide should help you fix it.

##

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Close Microsoft Store's Background Processes

 Windows might keep opening the Microsoft Store if there’s a process still running in the background. To fix it, you should use Task Manager to stop any background activity.

 Press**Ctrl + Shift + Esc** to bring up Task Manager. There, right-click**Microsoft Store** and select**End task** .

![Close Windows Store with Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/task-manager-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://win11.techidaily.com/customizing-mouse-pointer-settings-in-windows-11/"><u>Customizing Mouse Pointer Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/effective-approaches-to-bypass-resistant-pin-locks-on-pcs/"><u>Effective Approaches to Bypass Resistant PIN Locks on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-clear-windows-arp-caches-for-optimal-performance-130-chars-exceeds-limit-adjusted-to-fit-better-optimal-windows-arp-clearing/"><u>Efficiently Clear Windows ARP Caches for Optimal Performance (130 Chars, Exceeds Limit, Adjusted to Fit Better: Optimal Windows ARP Clearing</u></a></li>
<li><a href="https://network-issues.techidaily.com/escape-from-tarkov-graphics-bug-for-amd-users-quick-fix/"><u>Escape From Tarkov Graphics Bug for AMD Users [Quick Fix]</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/guide-successfully-transferring-your-favorite-videos-to-ipod-with-movavi/"><u>Guide: Successfully Transferring Your Favorite Videos to iPod with Movavi</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-migrate-android-data-from-samsung-galaxy-xcover-6-pro-tactical-edition-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Migrate Android Data From Samsung Galaxy XCover 6 Pro Tactical Edition to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://win-excellent.techidaily.com/how-to-record-your-beyond-live-broadcasts-effectively-on-screen/"><u>How to Record Your Beyond Live Broadcasts Effectively on Screen</u></a></li>
<li><a href="https://win11.techidaily.com/improving-workflow-with-swift-android-studio-performance-tweaks/"><u>Improving Workflow with Swift Android Studio Performance Tweaks</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Apple iPhone 13 Pro Max | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/overcome-apex-legends-challenge-clear-error-code-vect23-with-these-proven-steps/"><u>Overcome Apex Legends Challenge: Clear Error Code Vect(23) with These Proven Steps</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-mystery-of-windows-object-info/"><u>Unlock the Mystery of Windows Object Info</u></a></li>
</ul></div>

