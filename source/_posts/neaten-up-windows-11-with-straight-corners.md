---
title: Neaten Up Windows 11 with Straight Corners
date: 2024-12-20T16:38:30.776Z
updated: 2024-12-22T17:28:30.365Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Neaten Up Windows 11 with Straight Corners
excerpt: This Article Describes Neaten Up Windows 11 with Straight Corners
keywords: Wins11 Window Edge,Straight COrner Win,Neat Window Lineup,Window Precision W11,Corner Sharp Windows,W11 Window Snap,Perfect Corners W11
thumbnail: https://thmb.techidaily.com/a69a15798572265a2574284260281ddf651b6e2edc67c914e7a3a40f4a1feb7f.png
---

## Neaten Up Windows 11 with Straight Corners

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-videos.techidaily.com/updated-effective-thumbnails-the-secret-to-video-success/"><u>[Updated] Effective Thumbnails The Secret to Video Success</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-connecting-for-content-roku-and-facebook-live/"><u>[Updated] In 2024, Connecting for Content Roku and Facebook LIVE</u></a></li>
<li><a href="https://media-tips.techidaily.com/complete-apple-tv-nfl-sunday-ticket-202n-installation-manual-secure-your-weekly-football-fix-with-easy-steps/"><u>Complete Apple TV NFL Sunday Ticket 202N Installation Manual: Secure Your Weekly Football Fix with Easy Steps!</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-advice-the-ultimate-techniques-for-purging-cache-on-android-devices/"><u>Expert Advice: The Ultimate Techniques for Purging Cache on Android Devices</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-maximize-your-meeting-recordings-skype-on-any-operating-system/"><u>In 2024, Maximize Your Meeting Recordings Skype on Any Operating System</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-navigating-iphone-the-ringtone-alteration-process/"><u>In 2024, Navigating iPhone The Ringtone Alteration Process</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-turn-off-windows-mobility-center/"><u>Navigate to Turn Off Windows Mobility Center</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-past-deadly-js-error-a-solution-guide-for-win-11-users/"><u>Navigating Past Deadly JS Error: A Solution Guide for Win 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-chromeedgefirefox-copy-pasting-failures/"><u>Quick Fixes for Chrome/Edge/Firefox Copy-Pasting Failures</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-sluggish-or-unresponsive-downloads-on-pc/"><u>Quick Fixes for Sluggish or Unresponsive Downloads on PC</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-restoring-functional-download-feature-in-chrome-windows/"><u>Techniques for Restoring Functional Download Feature in Chrome, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/top-methods-when-windows-security-is-off-limits/"><u>Top Methods When Windows Security Is Off-Limits</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/unveiling-the-secrets-of-creative-commons-licensing-for-2024/"><u>Unveiling the Secrets of Creative Commons Licensing for 2024</u></a></li>
</ul></div>

