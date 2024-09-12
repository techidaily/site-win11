---
title: Make Windows 11 Edge-Less
date: 2024-09-11T09:44:37.510Z
updated: 2024-09-12T09:44:37.510Z
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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123476/16836" target="_top" id="2123476">
  <img src="//a.impactradius-go.com/display-ad/16836-2123476" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123476/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

<!-- affiliate ads begin -->
<span id="1424529">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424529.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424529">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424529.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424529%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424529/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you complete the above steps, a PowerShell window should appear and disable rounded corners on your PC. Here’s a glimpse of how your windows will look once the rounded corners are disabled.

![Square Corners in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/square-corners-in-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115933/19272" target="_top" id="2115933">
  <img src="//a.impactradius-go.com/display-ad/19272-2115933" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115933/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1743243">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1743243.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19272-1743243">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1743243.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Faligracehair.sjv.io%2Fc%2F5597632%2F1743243%2F19272'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1743243/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2115950/19272" target="_top" id="2115950">
  <img src="//a.impactradius-go.com/display-ad/19272-2115950" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115950/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-crafting-engaging-content-for-facebook-live-for-2024/"><u>[New] Crafting Engaging Content for Facebook Live for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-crafting-a-winning-sponsorship-proposal-for-youtube-creators/"><u>[Updated] Crafting a Winning Sponsorship Proposal for Youtube Creators</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-font-power-boosters-secrets-to-stellar-video-thumbnails/"><u>[Updated] In 2024, Font Power Boosters Secrets to Stellar Video Thumbnails</u></a></li>
<li><a href="https://win11.techidaily.com/convergence-mastery-the-ultimate-win-11-file-guide/"><u>Convergence Mastery: The Ultimate Win 11 File Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/cultivating-a-visionary-channel-with-best-video-ideas/"><u>Cultivating a Visionary Channel with Best Video Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-aggregatorhostexe-purpose-and-security/"><u>Demystifying Windows' AggregatorHost.exe: Purpose & Security</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-management-utilize-keyboard-shortcuts-for-window-control/"><u>Efficient Management: Utilize Keyboard Shortcuts for Window Control</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-memory-efficiency-with-edge-webview2-fixes/"><u>Enhancing Memory Efficiency with Edge WebView2 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-implementing-google-play-in-win11-os/"><u>Guide to Implementing Google Play in Win11 OS</u></a></li>
<li><a href="https://fox-info.techidaily.com/how-to-create-360-degree-photosimages-with-fisheye-lens-for-2024/"><u>How to Create 360 Degree Photos/Images with Fisheye Lens for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-it-tecno-spark-10-4g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Tecno Spark 10 4G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-guide-to-develop-personalized-window-11-lock-patterns/"><u>In-Depth Guide to Develop Personalized Window 11 Lock Patterns</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/insights-on-instagram-maximum-video-length-for-2024/"><u>Insights on Instagram Maximum Video Length for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/interpreting-and-correcting-comexception-discrepancies/"><u>Interpreting and Correcting COMException Discrepancies</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-glitches-the-top-10-tools/"><u>Mastering Windows Glitches: The Top 10 Tools</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-windows-palette-a-step-by-step-guide/"><u>Perfecting Windows Palette: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/preserve-personal-files-while-extending-windows-storage/"><u>Preserve Personal Files While Extending Windows Storage</u></a></li>
<li><a href="https://win11.techidaily.com/priorities-in-purchasing-your-first-windows-notebook/"><u>Priorities in Purchasing Your First Windows Notebook</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/professional-insights-on-the-huion-inspiroy-g1ve-graphics-pad-outstanding-durability-and-performance-metrics/"><u>Professional Insights on the Huion Inspiroy G1ve Graphics Pad: Outstanding Durability and Performance Metrics</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-dealing-with-windows-exception-breakpoint-failure/"><u>Quick Fixes for Dealing with Windows Exception Breakpoint Failure</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-windows-auto-lock-setting/"><u>Quick Guide to Windows Auto-Lock Setting</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-smooth-copy-paste-functionality-chromeedgefirefox/"><u>Restoring Smooth Copy-Paste Functionality (Chrome/Edge/Firefox)</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-vintage-windows-file-layouts/"><u>Resurrecting Vintage Windows File Layouts</u></a></li>
<li><a href="https://win11.techidaily.com/safe-deletion-practices-for-windows-bt-folders/"><u>Safe Deletion Practices for Windows ~BT Folders</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/spotlight-on-highly-praised-instagram-after-effects-plugins-for-2024/"><u>Spotlight on Highly Praised Instagram After Effects Plugins for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/switching-highlight-features-with-ease-in-windows-11/"><u>Switching Highlight Features with Ease in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-insiders-guide-to-tackling-regular-windows-rainmeter-issues/"><u>The Insider's Guide to Tackling Regular Windows Rainmeter Issues</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-methods-to-disable-gpu-aided-prioritization-on-widno/"><u>Uncovering Methods to Disable GPU-Aided Prioritization on WIDNO</u></a></li>
<li><a href="https://win11.techidaily.com/unexplored-windows-11-treasures-to-enhance-your-experience/"><u>Unexplored Windows 11 Treasures to Enhance Your Experience</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secret-to-flawless-steam-logins-rustwindows-edition/"><u>Unlocking the Secret to Flawless Steam Logins: Rust/Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/use-external-tools-explore-third-party-software-like-flux-redshift-or-display-temp-to-customize-display-behavior-according-to-time-of-day-and-ambient-light-32/"><u>Use External Tools: Explore Third-Party Software Like f.lux, Redshift, or Display Temp to Customize Display Behavior According to Time of Day and Ambient Light Conditions.</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-tips-manage-file-explorer-folders-visibility/"><u>Windows 11 Tips: Manage File Explorer Folders Visibility</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    