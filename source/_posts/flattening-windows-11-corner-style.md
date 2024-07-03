---
title: Flattening Windows 11 Corner Style
date: 2024-06-25T11:45:23.151Z
updated: 2024-06-26T11:45:23.151Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Flattening Windows 11 Corner Style
excerpt: This Article Describes Flattening Windows 11 Corner Style
keywords: Win11 Modernize,Flat UI Window,Cornerless PC Aesthetic,Unified Windows Design,Sleek Windows Edge,Streamlined WS11 Interface,Simplified Windows Style
thumbnail: https://thmb.techidaily.com/4f7878f35a5617dd30422b38a025795d7b590bfdd2ba7a274f89a9a6584223ab.jpg
---

## Flattening Windows 11 Corner Style

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

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

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/restoring-windows-services-command-line-tool-with-these-7-steps/"><u>Restoring Window's Services Command Line Tool with These 7 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/transformative-tips-for-a-productive-win-11-bar/"><u>Transformative Tips for a Productive Win 11 Bar</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-windows-security-add-safe-websites-now/"><u>Optimize Windows Security: Add Safe Websites Now</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-conflicting-camera-requests-windows-error-0xa00f4243/"><u>Mitigating Conflicting Camera Requests (Windows, Error 0xA00F4243)</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-fix-non-opening-photoshop-on-latest-windows-11/"><u>Guides to Fix Non-Opening Photoshop on Latest Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-education-elements-into-windows-ui/"><u>Infuse Education Elements Into Windows UI</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-lost-dll-mfc71u-on-windows/"><u>Troubleshooting Lost DLL: Mfc71u on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-pathway-restrictions-in-windows/"><u>Overcoming Device Pathway Restrictions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-look-at-windows-11-admin-interface/"><u>In-Depth Look at Windows 11 Admin Interface</u></a></li>
<li><a href="https://win11.techidaily.com/1719380495510-unravel-and-solve-your-windows-update-puzzle-fast/"><u>Unravel and Solve Your Windows Update Puzzle Fast</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-crafting-emotional-depth-utilizing-piano-melodies-for-movie-soundtracks-for-2024/"><u>Updated Crafting Emotional Depth Utilizing Piano Melodies for Movie Soundtracks for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-honor-play-40c-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Honor Play 40C? | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-unleash-your-creativity-a-guide-to-android-video-editing-apps/"><u>Updated Unleash Your Creativity A Guide to Android Video Editing Apps</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Honor Play 7T? | Dr.fone</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-trending-beats-navigating-the-world-of-viral-tiktok-raps/"><u>[New] 2024 Approved  Trending Beats  Navigating the World of Viral TikTok Raps</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgotten-the-voicemail-password-of-motorola-edge-40-neo-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Motorola Edge 40 Neo? Try These Fixes</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-firecapture-extensions-for-ff-users/"><u>[New] FireCapture Extensions for FF Users</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>What is the best Pokemon for pokemon pvp ranking On Apple iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-seamless-integration-of-luts-for-enhanced-cinematography/"><u>2024 Approved  Seamless Integration of LUTs for Enhanced Cinematography</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-tecno-spark-20-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Tecno Spark 20 | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>