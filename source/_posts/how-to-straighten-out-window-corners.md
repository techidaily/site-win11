---
title: How to Straighten Out Window Corners
date: 2024-06-25T11:28:13.426Z
updated: 2024-06-26T11:28:13.426Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Straighten Out Window Corners
excerpt: This Article Describes How to Straighten Out Window Corners
keywords: Straight Edge Windows,Window Corner Alignment,Fixed Window Edges,Smooth Corner Finish,Ledge Removal Technique,Tips for Corners Precision,Perfect Window Angles
thumbnail: https://thmb.techidaily.com/329d369e5db1c978f66185fe9a5482898ede3269e6a52b60eb890177d543e794.png
---

## How to Straighten Out Window Corners

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
<li><a href="https://win11.techidaily.com/empowering-tech-connection-winpc-galaxy-with-flow-app/"><u>Empowering Tech Connection - WinPC, Galaxy with Flow App</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-world-of-windowed-activity-archives/"><u>Navigating the World of Windowed Activity Archives</u></a></li>
<li><a href="https://win11.techidaily.com/routine-task-for-eliminating-steam-dns-cache-on-pc/"><u>Routine Task for Eliminating Steam DNS Cache on PC</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-wizardry-admin-skills-unveiled/"><u>Command Prompt Wizardry: Admin Skills Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/1719271169588-reclaim-your-browser-quick-fixes-to-unlock-chrome-on-win11/"><u>Reclaim Your Browser: Quick Fixes to Unlock Chrome on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/free-notetaking-on-windows-easy-and-effective/"><u>Free Notetaking on Windows: Easy and Effective</u></a></li>
<li><a href="https://win11.techidaily.com/terminal-insight-discover-public-ip-in-windows-1110/"><u>Terminal Insight: Discover Public IP in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/device-agnostic-operating-system-windows-for-iphonesipads-macs-pcs-launched/"><u>Device-Agnostic Operating System: Windows for iPhones/iPads, Macs, PCs Launched</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-no-server-errors-a-windows-guide-to-apex-success-(156-chars/"><u>Eliminating No-Server Errors: A Windows Guide to Apex Success (<156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-restoring-ccleaner-on-win11/"><u>Mastering the Art: Restoring CCleaner on Win11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-adding-subtitles-a-step-by-step-youtube-video-approach/"><u>In 2024, Adding Subtitles  A Step-by-Step YouTube Video Approach</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-top-10-invisible-observers-of-instagram-stories-for-2024/"><u>[Updated] Top 10 Invisible Observers of Instagram Stories for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-turning-popular-sounds-on-tiktok-into-personal-cellphone-alarms/"><u>[New] Turning Popular Sounds on TikTok Into Personal Cellphone Alarms</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-ultimate-guide-to-unlocking-your-apple-iphone-xs-on-metropcs-by-drfone-ios/"><u>The Ultimate Guide to Unlocking Your Apple iPhone XS on MetroPCS</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/disable-screen-lock-on-xiaomi-redmi-note-12t-pro-by-drfone-android-unlock-android-unlock/"><u>Disable screen lock on Xiaomi Redmi Note 12T Pro</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-pixel-to-perfection-hardware-or-code-for-streamers/"><u>[Updated] Pixel to Perfection  Hardware or Code for Streamers?</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/elevate-your-facebook-ads-game-no-price-tag-for-video-kit-for-2024/"><u>Elevate Your Facebook Ads Game - No Price Tag for Video Kit for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/beyond-illusions-demystifying-the-tri-fold-of-digital-experiences-mr-ar-and-vr-for-2024/"><u>Beyond Illusions  Demystifying the Tri-Fold of Digital Experiences (MR, AR, and VR) for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-pro-tips-for-re-sharing-on-instagram/"><u>2024 Approved  Pro Tips for Re-Sharing on Instagram</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-guide-for-iphone-14-pro-max-lock-screen-drfone-by-drfone-ios/"><u>In 2024, Complete Guide For iPhone 14 Pro Max Lock Screen | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>