---
title: Fixing WSL Disruptions After Win 11 Rollout
date: 2024-11-26T21:08:57.059Z
updated: 2024-11-27T20:41:42.353Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing WSL Disruptions After Win 11 Rollout
excerpt: This Article Describes Fixing WSL Disruptions After Win 11 Rollout
keywords: Win 11 WSL Stability,WSL Issue Fixes,Post-Win11 WSL,Win 11 WSL Disruptions,Resolve WSL Win11,WSL Troubleshooting Win11,Win 11 WSL Repair Guide
thumbnail: https://thmb.techidaily.com/641461279d3ad9059bf4fdcda2c6b1609c3c8007cc281a812d3b0157adab9f77.jpg
---

## Fixing WSL Disruptions After Win 11 Rollout

 There are several potential reasons why Windows Subsystem for Linux (WSL) stopped working after your PC was upgraded to Windows 11\. Thankfully, the breakdown is unlikely to be terminal, although you might have to try a few different fixes to get it working once again.

 **MUO VIDEO OF THE DAY**

 **SCROLL TO CONTINUE WITH CONTENT**

 Here are several ways to get the Windows Subsystem for Linux working again after upgrading to Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Check That WSL Is Enabled

 It isn't unusual that upgrading to a newer version of the OS will break some apps and features. So although it might sound obvious, checking WSL hasn't simply been disabled during the upgrade process should be your first step. Here's how to check:

![checking if WSL is enabled in Windows Features](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-enabled.jpg)

1. In Windows Search, type**Turn Windows features on or off** and click the search result that should appear at the top.
2. In the Windows System dialog, scroll down until you see**Windows Subsystem for Linux** .
3. If the checkbox for the feature is not selected, do so now. Then click**Ok** .
4. You might also need to restart your computer before checking to see if that fixed the problem.

 Hopefully, WSL is now working, and you can begin using the tool. If not, read on for some other possible solutions.

 Learn more about the[things you can do with WSL and Linux](https://www.makeuseof.com/pros-cons-windows-subsystem-for-linux/) on your Windows computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Enable Hyper-V and Virtual Machine Platform

 If you want to use a subsystem such as WSL in Windows, you'll also need to enable the virtualization tools. These include Hyper-V and the Virtual Machine Platform.

![Error message in the command line interface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-feature-missing.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If a command line interface opens, telling you a required feature is not installed, when you try to run your Linux distribution, this is likely what it refers to.

1. Search for**Turn Windows features on or off** and click the search result.
2. In Windows Features, scroll down to find**Virtual Machine Platform** and**Windows Hypervisor Platform** .
3. Check the boxes next to each of these features and then click**Ok** .
4. You will need to restart your computer to complete the installation of these tools.

## 3\. Repair the Linux Distribution App

 Your Linux distribution app, such as Ubuntu, Kali, or Debian, could be corrupted or require updating. This can cause WSL to appear to be broken. Repairing Windows apps is very easy.

1. Open**Settings > Apps > App & Features** .
2. Scroll down to the list of your apps to find your Linux distro app.
3. Click the**three dots** to the right of the app name, and select**Advanced options** .  
![Advanced app options in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl.jpg)
4. Click the**Repair** button and follow the on-screen instructions if repairs are necessary.  

![repairing an app in Windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-wsl-app.jpg)

 Check if WSL is working. If not, try uninstalling and reinstalling the Linux distribution app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Force WSL to Open Using the Microsoft Store

 If WSL is enabled but still refuses to open, you can try forcing launch through the Microsoft Store app. This can sometimes fix temporary glitches when opening WSL directly doesn't work.

1. Open the Microsoft Store app and search for**WSL** .
2. On the store page for WSL, you should see an**Open** button. If the button says**Update** , click it to update the app.  
![opening the WSL app in the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/force-open-store.jpg)
3. Click the**Open** button, and the default Linux distro app should launch.

4. If a command line interface window opens instead, it will probably tell you a required feature is missing. See**Enable Hyper-V and Virtual Machine Platform** above.

 If forcing WSL to open doesn't work, try the same with the Linux distro app you are using. Open the Store, search for your distro, and click the**Open** button.

## 5\. Uninstall Recent Updates to Fix WSL

 If WSL stopped working after installing an update, the update could be the cause. You can uninstall the most recent update to see if that fixes the problem.

[Uninstalling Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) isn't a complicated process, even if you have never done it before.

 If, after uninstalling the update, WSL still does not work, it is a good idea to reinstall it. Updates can often include security and performance tweaks, so it is generally recommended to keep Windows updated.

## 6\. Check That Malware Isn't Blocking WSL

 The final thing to try to get WSL working is scanning for malware. The potential for malware to prevent Windows Subsystem for Linux from working is low but not unheard of.

 Run a[full scan in Microsoft Defender](https://www.makeuseof.com/easy-ways-boost-security-microsoft-defender-and-windows-10/) or whichever third-party antivirus software you use. Quarantine or remove any malware your antivirus scan finds. Then restart your computer and try using WSL to see if that was the issue.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fixing WSL After Upgrading to Windows 11

 Upgrading to Windows 11 usually goes smoothly, but apps and features can occasionally break. If you find that WSL is no longer working after upgrading to the newest Windows OS, don't worry, there is usually an easy fix. You might only need to re-enable the feature in the Windows system settings, but if not, running through the other fixes here will usually solve the problem.

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-the-leading-cloud-services-with-best-price/"><u>[New] 2024 Approved The Leading Cloud Services with Best Price</u></a></li>
<li><a href="https://fox-tips.techidaily.com/1-expert-guide-seamlessly-streaming-your-iphone-screen-onto-your-television/"><u>1. Expert Guide: Seamlessly Streaming Your iPhone Screen Onto Your Television</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/boost-your-brand-visibility-with-top-hashtag-strategies/"><u>Boost Your Brand Visibility with Top Hashtag Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-privileged-requirement-not-met-error-on-windows-pcs/"><u>Correcting Privileged Requirement Not Met Error on Windows PCs</u></a></li>
<li><a href="https://data-recovery.techidaily.com/data-salvage-solution-for-windows-devices/"><u>Data Salvage Solution for Windows Devices</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/exploring-new-frontiers-with-vr-game-engines/"><u>Exploring New Frontiers with VR Game Engines</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-wrong-imports-with-ios-pictures-on-windows-1011/"><u>Fixing Wrong Imports with iOS Pictures on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/neglecting-nuances-5-hidden-risks-in-budgeted-windows-keys/"><u>Neglecting Nuances: 5 Hidden Risks in Budgeted Windows Keys</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-application-management-via-windows-package-manager/"><u>Optimizing Application Management via Windows Package Manager</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/optimizing-gameplay-at-30fps-across-gaming-consoles-and-personal-computers/"><u>Optimizing Gameplay at 30FPS Across Gaming Consoles and Personal Computers</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-11s-classic-folder-view/"><u>Reviving Windows 11'S Classic Folder View</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-applied-policies-in-windows-via-3-views/"><u>Understanding Applied Policies in Windows via 3 Views</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/king-the-secrets-elevating-your-youtube-presence-in-gameplay/"><u>Unlocking the Secrets Elevating Your YouTube Presence in Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-worldwide-network-link-in-minecraft-wins/"><u>Unlocking Worldwide Network Link in Minecraft Wins</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-the-professionals-method-for-soundless-iphone-video-editing/"><u>Updated In 2024, The Professionals Method for Soundless iPhone Video Editing</u></a></li>
</ul></div>

