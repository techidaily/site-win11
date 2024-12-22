---
title: "How to Edge Off: Windows 11 Shapes"
date: 2024-12-20T17:54:47.406Z
updated: 2024-12-22T16:26:45.851Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes How to Edge Off: Windows 11 Shapes"
excerpt: "This Article Describes How to Edge Off: Windows 11 Shapes"
keywords: Win11EdgeShapingTips,Windows11EdgeTrim,ProEdgeWinLayout,EdgeToolWindows11,SmoothWindowsEdgeCut,PrecisionEdgesWin11,OptimalWindowEdging
thumbnail: https://thmb.techidaily.com/6f40aa8bc84c668553ff55a3fe7a27d53d5fc34a3d453d8ed3a4e878312705cb.jpg
---

## How to Edge Off: Windows 11 Shapes

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-data.techidaily.com/024-approved-transforming-your-youtube-profile-descriptions/"><u>[New] 2024 Approved Transforming Your YouTube Profile Descriptions</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-expert-advice-on-youtube-short-pitfalls/"><u>[Updated] 2024 Approved Expert Advice on YouTube Short Pitfalls</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-how-to-record-gameplay-on-windows-10/"><u>[Updated] 2024 Approved How to Record Gameplay on Windows 10</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-fix-invisible-facebook-watch-icon-now-fixed/"><u>[Updated] In 2024, Fix Invisible Facebook Watch Icon, Now Fixed</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-pc-query-experience-with-everythingapp/"><u>Enhance Your PC Query Experience with EverythingApp</u></a></li>
<li><a href="https://driver-error.techidaily.com/expert-tips-for-fixing-hp-wireless-keyboard-malfunctions-successfully/"><u>Expert Tips for Fixing HP Wireless Keyboard Malfunctions Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-resetting-erroneous-configurations-in-nvidia-experience/"><u>Guide to Resetting Erroneous Configurations in NVIDIA Experience</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-minisculerecordings-snapshot-scrutiny/"><u>In 2024, MinisculeRecordings Snapshot Scrutiny</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-ispoofer-update-on-xiaomi-redmi-13c-drfone-by-drfone-virtual-android/"><u>In 2024, Will iSpoofer update On Xiaomi Redmi 13C | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-underutilized-windows-system-health-indicators/"><u>Investigating Underutilized Windows' System Health Indicators</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-mute-issues-while-capturing-powerpoint-presentations/"><u>Overcoming Mute Issues While Capturing PowerPoint Presentations</u></a></li>
<li><a href="https://win11.techidaily.com/re-engaging-lost-lan-discovery-on-windows/"><u>Re-Engaging Lost LAN Discovery on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unresizable-gif-problems-a-fix-guide-for-discord-on-win11-pcs/"><u>Tackling Unresizable GIF Problems: A Fix Guide for Discord on Win11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-role-and-purpose-of-runtime-broker-in-computing-systems/"><u>The Role and Purpose of Runtime Broker in Computing Systems</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-5-eco-friendly-smartphones-picking-the-perfect-choice-on-zdnet/"><u>Top 5 Eco-Friendly Smartphones - Picking the Perfect Choice on ZDNet</u></a></li>
</ul></div>

