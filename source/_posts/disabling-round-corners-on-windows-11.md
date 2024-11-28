---
title: Disabling Round Corners on Windows 11
date: 2024-11-25T18:13:55.853Z
updated: 2024-11-28T04:10:04.490Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Disabling Round Corners on Windows 11
excerpt: This Article Describes Disabling Round Corners on Windows 11
keywords: Windows 11 Cornerless Editions,Win11 Anti-Round Corners,Edge Design Disablement (Win11),Round Corners Removal Win11,Win11 Sharp Borders,Win11 Sans-Corners UI,Windows 11 Rounded Borderless
thumbnail: https://thmb.techidaily.com/e3cf30b4720656ba32f87d0a36d739d3e594003c967c2e7d28e98120dd95b14e.jpg
---

## Disabling Round Corners on Windows 11

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

## 2\. How to Disable Rounded Corners in Windows 11 Using the Registry Editor

 Don't want to use a third-party tool? No problem. You can also disable rounded corners in Windows 11 by making changes to the Windows Registry. However, it's crucial to exercise caution, as modifying registry files without proper knowledge can be risky.

 Before you proceed, consider [backing up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/), just in case. After that, use these steps to disable rounded corners via the Registry Editor:

1. Press **Win + S** to open the search menu.
2. Type in **registry editor** and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Navigate to **Computer > HKEY\_CURRENT\_USER > Software > Microsoft > Windows > DWM**.
5. Right-click on the **DWM** key and select **New > DWORD (32-bit) Value**. Rename it to **UseWindowFrameStagingBuffer**.
6. Double-click the newly created DWORD and enter **0** in the **Value data** field. Then, click **OK**.
7. [Restart your PC](https://www.makeuseof.com/windows-restart-methods/) to apply the changes.  
![Disable Rounded Corners in Windows 11 via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-rounded-corners-in-windows-11-via-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/new-exclusive-insights-viewing-nba-games-remotely/"><u>[New] Exclusive Insights Viewing NBA Games Remotely</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-step-by-step-creating-a-skype-group-on-both-systems-for-2024/"><u>[New] Step-by-Step Creating a Skype Group on Both Systems for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-cultivating-cash-by-critiquing-consumer-commodities-online/"><u>[Updated] Cultivating Cash by Critiquing Consumer Commodities Online</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-navigating-the-world-of-video-timestamps-on-youtube/"><u>[Updated] Navigating the World of Video Timestamps on YouTube</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-complete-seo-strategy-for-podcast-growth/"><u>2024 Approved The Complete Seo Strategy for Podcast Growth</u></a></li>
<li><a href="https://win11.techidaily.com/cross-device-compatibility-windows-app-supports-apple-and-desktop-oses/"><u>Cross-Device Compatibility: Windows App Supports Apple and Desktop OSes</u></a></li>
<li><a href="https://win11.techidaily.com/dxgidll-gone-unveiling-win11-remedy-steps/"><u>Dxgi.dll Gone? Unveiling Win11 Remedy Steps</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-root-of-windows-defender-error-0x80004004/"><u>Eliminating the Root of Windows Defender Error 0X80004004</u></a></li>
<li><a href="https://driver-install.techidaily.com/m2-ssd-compatibility-tips/"><u>M.2 SSD Compatibility Tips</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-windows-11-taskbar-sizing-techniques/"><u>Perfect Windows 11 Taskbar Sizing Techniques</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/perfecting-the-art-of-ppt-video-creation-for-2024/"><u>Perfecting the Art of PPT Video Creation for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/seamless-setup-installing-the-latest-nahimic-audio-drivers-in-no-time/"><u>Seamless Setup: Installing the Latest Nahimic Audio Drivers in No Time</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-non-empty-directory-error-in-windows-11-and-win11-code-0x80070091/"><u>Taming the Non-Empty Directory Error in Windows 11 & Win11 (Code: 0X80070091)</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/211383492-9780645738636-the-complete-teachings-of-modern-wicca-for-the-seeker/"><u>The Complete Teachings of Modern Wicca For the Seeker | Free Book</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-for-source-unavailable-errors-in-windows-1011/"><u>Troubleshooting Steps for “Source Unavailable” Errors in Windows 10/11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    