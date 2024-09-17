---
title: Make Windows 11 Edge-Less
date: 2024-09-09T20:37:10.829Z
updated: 2024-09-16T17:23:44.351Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Make Windows 11 Edge-Less
excerpt: This Article Describes Make Windows 11 Edge-Less
keywords: Win11RemoveEdgeBar,EliminateWindows11Edges,DisableWindows11Edge,Win11NoEdgeInterface,RemoveWindows11BrowserBar,Windows11WithoutEdge,EdgeFreeWin11Tip
thumbnail: https://thmb.techidaily.com/718d1853d85918e9d3b7531d3e7e5d446b8b2d7ecc9512a603cf6d88a4e79188.jpg
---

## Make Windows 11 Edge-Less

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

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

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-pixelpress-mastering-the-art-of-screen-recording/"><u>[New] 2024 Approved 'PixelPress' Mastering the Art of Screen Recording</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-streamlined-screens-on-chrome-os/"><u>[Updated] 2024 Approved Streamlined Screens on Chrome OS</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-how-to-stream-a-pre-recorded-video-live-on-facebook-for-2024/"><u>[Updated] How to Stream A Pre-Recorded Video Live on Facebook for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-mastering-volume-transitions-in-lumafusion/"><u>[Updated] Mastering Volume Transitions in Lumafusion</u></a></li>
<li><a href="https://win11.techidaily.com/pciphoneandroid/"><u>動画中の指定された音を消す - PC、iPhone、Android向けガイド</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/bring-back-disappearing-video-icon-on-fb-watch/"><u>Bring Back Disappearing Video Icon on FB Watch</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-oppo-reno-10-proplus-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Oppo Reno 10 Pro+ 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-innovations-in-balancing-exposures-for-perfect-pictures/"><u>In 2024, Innovations in Balancing Exposures for Perfect Pictures</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unveiling-hidden-secrets-for-advanced-win10-users/"><u>In 2024, Unveiling Hidden Secrets for Advanced Win10 Users</u></a></li>
<li><a href="https://win11.techidaily.com/mp3wavwindowsmac/"><u>MP3ファイルをWAV形式にアップコンバートする手軽かつ効果的な方法：Windows、Mac両用のフリーソフトウェア・無料サイト推薦</u></a></li>
<li><a href="https://win11.techidaily.com/mp4iphoneandroid/"><u>MP4形式ビデオを着信音として使うiPhone/Androidの方法解説</u></a></li>
<li><a href="https://win11.techidaily.com/new-advanced-dvd-ripping-tool-launched-by-wonderfox-fully-compatible-with-modern-mobile-gadgets/"><u>New Advanced DVD Ripping Tool Launched by WonderFox: Fully Compatible with Modern Mobile Gadgets</u></a></li>
<li><a href="https://win11.techidaily.com/no-luck-with-internet-dvd-burners-explore-our-top-recommended-replacements/"><u>No Luck with Internet DVD Burners? Explore Our Top Recommended Replacements!</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-challenges-with-starting-a-hosted-network-on-windows-10-solved/"><u>Overcoming Challenges with Starting a Hosted Network on Windows 10 (Solved)</u></a></li>
</ul></div>

