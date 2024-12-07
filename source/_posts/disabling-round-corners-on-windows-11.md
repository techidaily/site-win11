---
title: Disabling Round Corners on Windows 11
date: 2024-12-01T19:41:07.490Z
updated: 2024-12-07T07:08:42.438Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vca--yEhtdo?si=7ijqjyP-oi3LYze1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-exiting-with-impact-mastering-podcast-conclusions-beyond-the-basics/"><u>[New] 2024 Approved Exiting with Impact Mastering Podcast Conclusions Beyond the Basics</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-financial-gains-the-youtube-money-flow-from-1m-views/"><u>[New] In 2024, Financial Gains The Youtube Money Flow From 1M Views</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-art-of-textual-dimension-mastering-adobe-illustrator/"><u>[New] The Art of Textual Dimension Mastering Adobe Illustrator</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-supercharge-your-videos-with-these-proven-keyword-analyst-tools/"><u>[Updated] Supercharge Your Videos with These Proven Keyword Analyst Tools</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-vivo-v29e-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Vivo V29e For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-oppo-reno-10-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Oppo Reno 10 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ctrlplustab-minimizing-programs-to-system-tray-quickly/"><u>Mastering Ctrl+Tab: Minimizing Programs to System Tray Quickly</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-unveiling-the-6-top-rated-digital-libraries-for-haunting-audio-effects-2e-update/"><u>New Unveiling the 6 Top-Rated Digital Libraries for Haunting Audio Effects (2E Update)</u></a></li>
<li><a href="https://win11.techidaily.com/pioneering-phone-sync-on-windows-11-a-new-era-begins/"><u>Pioneering Phone Sync on Windows 11: A New Era Begins</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/power-up-any-web-session-integrating-agentgpts-ais/"><u>Power Up Any Web Session – Integrating AgentGPT's AIs</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/premier-editing-software-for-vimeo-streams/"><u>Premier Editing Software for Vimeo Streams</u></a></li>
<li><a href="https://driver-download.techidaily.com/quick-and-simple-guide-to-downloading-your-brother-printers-driver/"><u>Quick and Simple Guide to Downloading Your Brother Printer's Driver</u></a></li>
<li><a href="https://win11.techidaily.com/ram-cache-clarity-and-techniques-for-windows-users/"><u>RAM Cache Clarity & Techniques for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/realigning-context-menus-a-windows-users-guide/"><u>Realigning Context Menus: A Windows User's Guide</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-the-dll-loading-problem-in-steamui/"><u>Rectifying the DLL Loading Problem in SteamUI</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-window-11-desktop-systems-user-interface/"><u>Restoring Window 11 Desktop System's User Interface</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-typing-with-powertoys-on-windows/"><u>Supercharge Typing with PowerToys on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11-snip-and-sketch-command/"><u>Unlock Windows 11 Snip & Sketch Command</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-rebooting-ram-settings/"><u>Win 11: Rebooting RAM Settings</u></a></li>
</ul></div>

