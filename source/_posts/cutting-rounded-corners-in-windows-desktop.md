---
title: Cutting Rounded Corners in Windows Desktop
date: 2024-10-11T18:29:34.690Z
updated: 2024-10-15T18:16:49.072Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cutting Rounded Corners in Windows Desktop
excerpt: This Article Describes Cutting Rounded Corners in Windows Desktop
keywords: Cut Corners Windows,Rounded Corner Removal,Desktop Edges Trim,Corner Rounding Edit,Windows Edge Shape,Corners Snap Shortcut,Quick Corner Fix Windows
thumbnail: https://thmb.techidaily.com/d3f8a164ff7cec81bd719ff1860ad4b428bdab1ff70424914ce34922d708e742.jpg
---

## Cutting Rounded Corners in Windows Desktop

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
<a href="https://aligracehair.sjv.io/c/5597632/2016143/19272" target="_top" id="2016143">
  <img src="//a.impactradius-go.com/display-ad/19272-2016143" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016143/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868575/19272" target="_top" id="1868575">
  <img src="//a.impactradius-go.com/display-ad/19272-1868575" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868575/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://imp.i110150.net/c/5597632/798161/11305" target="_top" id="798161">
  <img src="//a.impactradius-go.com/display-ad/11305-798161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798161/11305" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-http.techidaily.com/new-assessing-ffmpegs-prowess-in-original-audio-extraction/"><u>[New] Assessing FFmpeg’s Prowess in Original Audio Extraction</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-elevate-viewer-response-crafting-engaging-ig-story-qandas-for-2024/"><u>[New] Elevate Viewer Response Crafting Engaging IG Story Q&As for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-ios-snapshot-spectrum-your-quick-reference/"><u>[New] In 2024, IO's Snapshot Spectrum Your Quick Reference</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-guide-to-free-premiere-pro-template-hacks/"><u>[Updated] The Ultimate Guide to Free Premiere Pro Template Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-how-to-make-uwp-app-shortcuts/"><u>Enhancing Windows 11: How to Make UWP App Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-a-check-for-updates-context-menu-option-in-windows-10-and-11/"><u>How to Add a Check for Updates Context Menu Option in Windows 10 and 11</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-8-plus-to-the-previous-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 8 Plus to the Previous iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-grant-read-permission-on-hidden-outlook-directories-and-files/"><u>How to Grant Read Permission on Hidden Outlook Directories & Files</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-hands-on-guide-flipping-film-with-vlc-software/"><u>In 2024, Hands-On Guide Flipping Film with VLC Software</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-pioneering-adventures-the-ultimate-gaming-list-top-10/"><u>In 2024, Pioneering Adventures The Ultimate Gaming List (Top 10)</u></a></li>
<li><a href="https://win11.techidaily.com/innovating-cleanup-generative-erase-revolutionizes-windows/"><u>Innovating Cleanup: Generative Erase Revolutionizes Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-imessage-for-windows-a-step-by-step-guide/"><u>Mastering iMessage for Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-file-system-failures-a-guide-to-fixes-in-win11/"><u>Navigating File System Failures: A Guide to Fixes in Win11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/premiere-pro-solutions-to-perfect-iphone-hd-video-exposure-balance-for-2024/"><u>Premiere Pro Solutions to Perfect iPhone HD Video Exposure Balance for 2024</u></a></li>
</ul></div>

