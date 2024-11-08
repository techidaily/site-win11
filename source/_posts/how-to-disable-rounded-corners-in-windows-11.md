---
title: How to Disable Rounded Corners in Windows 11
date: 2024-11-03T23:19:45.192Z
updated: 2024-11-07T18:52:13.073Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Disable Rounded Corners in Windows 11
excerpt: This Article Describes How to Disable Rounded Corners in Windows 11
keywords: Windows Edge Style Change,Win11 Corner Adjustment,Remove Windows Rounded Edges,Square Window Mode Windows 11,Disable Windows Capsule Corners,Round Edge Removal Windows,Edge Shape Alteration Windows 11
thumbnail: https://thmb.techidaily.com/57a4dd5881ee89a7ccb05cda2bbc7d01f9c197463ce070f6b273e0abf69dbbe5.jpg
---

## How to Disable Rounded Corners in Windows 11

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151888/7443" target="_top" id="2151888">
  <img src="//a.impactradius-go.com/display-ad/7443-2151888" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151888/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094421/7443" target="_top" id="2094421">
  <img src="//a.impactradius-go.com/display-ad/7443-2094421" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094421/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068426/7443" target="_top" id="2068426">
  <img src="//a.impactradius-go.com/display-ad/7443-2068426" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068426/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-avoiding-common-pitfalls-in-pc-based-youtube-video-editing-for-2024/"><u>[New] Avoiding Common Pitfalls in PC-Based YouTube Video Editing for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-decoding-the-new-era-of-video-editing-with-vivacut/"><u>[Updated] Decoding the New Era of Video Editing with VivaCut</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-step-by-step-method-to-personalize-iphone-ringtones/"><u>[Updated] In 2024, Step-By-Step Method to Personalize iPhone Ringtones</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-instavision-blend-androidplusios-video-tiles/"><u>[Updated] InstaVision Blend Android+iOS Video Tiles</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-elevated-command-window-a-comprehensive-tutorial/"><u>Fixing Non-Elevated Command Window: A Comprehensive Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/gain-instant-administrator-entry-with-terminal-anytime/"><u>Gain Instant Administrator Entry with Terminal Anytime</u></a></li>
<li><a href="https://fox-links.techidaily.com/implement-xps-video-editing-suite-instantly-for-2024/"><u>Implement XP's Video Editing Suite Instantly for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-infinix-smart-7-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Infinix Smart 7 to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/insightful-insights-essential-windows-11-weather-apps-guide/"><u>Insightful Insights: Essential Windows 11 Weather Apps Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/pattern-locks-are-unsafe-secure-your-honor-90-pro-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your Honor 90 Pro Phone Now with These Tips</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-messages-from-motorola-moto-g04-by-fonelab-android-recover-messages/"><u>Possible solutions to restore deleted messages from Motorola Moto G04</u></a></li>
<li><a href="https://win11.techidaily.com/productivity-boost-quick-access-via-pinned-gmail-windows-side/"><u>Productivity Boost: Quick Access via Pinned Gmail Window's Side</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-1110s-d3d11-compatible-gpu-riddle/"><u>Unraveling Windows 11/10'S D3D11 Compatible GPU Riddle</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win10win11-troubleshooting-hardware-recognition-issues/"><u>Win10/Win11: Troubleshooting Hardware Recognition Issues</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    