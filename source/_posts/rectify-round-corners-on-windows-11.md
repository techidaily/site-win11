---
title: Rectify Round Corners on Windows 11
date: 2024-12-15T17:04:04.726Z
updated: 2024-12-22T16:20:39.389Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectify Round Corners on Windows 11
excerpt: This Article Describes Rectify Round Corners on Windows 11
keywords: Corner Precision Fix,Windows 11 Edge Adjust,W11 Rounded Edges Fix,Sharp Corners Round Out,Clear Corners Win11,Corner Smoothening Win11,Edge Defining Windows 11
thumbnail: https://thmb.techidaily.com/39891eff73508b464f66ea96b5a005498dc7a497b224e926f9156c826add0320.jpeg
---

## Rectify Round Corners on Windows 11

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## 3\. How to Disable Rounded Corners in Windows 11 via Device Manager

 Another way to remove rounded corners in Windows 11 is by disabling the graphics driver on your PC. However, it is important to consider a few caveats. Firstly, disabling the graphics driver will result in reduced display performance, lower screen resolutions, and the deactivation of any visual effects. Secondly, this will also prevent you from running any graphics-intensive applications or games on your PC.

 If you are fine with these trade-offs, use these steps to disable rounded corners via Device Manager.

1. Press **Win + X** to open the Power User menu.
2. Select **Device Manager** from the list.
3. Double-click on **Display adapters** to expand it.
4. Right-click on your display driver and select **Disable device**.  
![Disable Graphics Driver on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/disable-graphics-driver-on-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

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
<li><a href="https://fox-direct.techidaily.com/new-discovering-free-high-quality-slide-show-patterns/"><u>[New] Discovering Free, High-Quality Slide Show Patterns</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-elite-green-tech-in-the-world-of-screen-capture/"><u>[New] In 2024, Elite Green Tech in the World of Screen Capture</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-migrating-from-spotify-to-a-personalized-youtube-music-list/"><u>[Updated] 2024 Approved Migrating From Spotify to a Personalized YouTube Music List</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-cut-mark-clutter-quickly-tiktok-overlay-remover/"><u>[Updated] Cut Mark Clutter Quickly TikTok Overlay Remover</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-words-best-writing-software-for-windows-users/"><u>Conquer Words: Best Writing Software for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-could-not-start-the-windows-search-service-error/"><u>How to Fix the Windows Could Not Start the Windows Search Service Error</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-lenovo-thinkphone-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Lenovo ThinkPhone Phones? | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exclusive-list-best-10-gopro-case-models-reviewed/"><u>In 2024, Exclusive List Best 10 GoPro Case Models Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-mastery-for-efficient-project-delivery/"><u>Keyboard Mastery for Efficient Project Delivery</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-multiplayer-tactics-a-guide-to-team-up-hunts-in-monster-hunter-world/"><u>Mastering Multiplayer Tactics: A Guide to Team-Up Hunts in Monster Hunter World</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-lockout-no-admin-pass-needed/"><u>Overcoming Windows 11 Lockout: No Admin Pass Needed</u></a></li>
<li><a href="https://fox-zero.techidaily.com/passos-faceis-e-detalhados-para-clonar-seu-disco-rigido-padrao-hdd-para-um-ssd-moderno-m2-reconhecido-pelo-sistema/"><u>Passos Fáceis E Detalhados Para Clonar Seu Disco Rígido Padrão (HDD) Para Um SSD Moderno M.ˈ2 Reconhecido Pelo Sistema</u></a></li>
<li><a href="https://win11.techidaily.com/pathway-backup-reactivating-windows-11-troubleshooting-tools/"><u>Pathway Backup: Reactivating Windows 11 Troubleshooting Tools</u></a></li>
<li><a href="https://win11.techidaily.com/reconcile-your-win-plus-print-discrepinasions-with-effective-solutions/"><u>Reconcile Your Win + Print Discrepinasions with Effective Solutions.</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-unlocking-admin-powers/"><u>Step-by-Step Guide: Unlocking Admin Powers</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-win32keygen-virus-impact-and-comprehensive-removal-procedures/"><u>Understanding Win32/Keygen Virus: Impact and Comprehensive Removal Procedures</u></a></li>
<li><a href="https://win11.techidaily.com/windows-storage-for-captured-content/"><u>Windows Storage for Captured Content</u></a></li>
</ul></div>

