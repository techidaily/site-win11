---
title: "Flat Faces for Windows: Cutting Corners Off"
date: 2024-10-23T04:39:36.353Z
updated: 2024-10-27T05:21:35.948Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Flat Faces for Windows: Cutting Corners Off"
excerpt: "This Article Describes Flat Faces for Windows: Cutting Corners Off"
keywords: FlatFaceWindowsCuts,FacialContourWindows,WindowsFacialShaping,ShortcutsForWindowsFaces,ContouredWindowsFaces,QuickWindowsSkinTuneup,EfficientWindowsFacialEdit
thumbnail: https://thmb.techidaily.com/892778263385515e7b518ee32371993d4538db30fcfa28225c01631f4b2e459e.jpg
---

## Flat Faces for Windows: Cutting Corners Off

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
<a href="https://aligracehair.sjv.io/c/5597632/1997695/19272" target="_top" id="1997695">
  <img src="//a.impactradius-go.com/display-ad/19272-1997695" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997695/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://laganoo.pxf.io/c/5597632/1528688/16446" target="_top" id="1528688">
  <img src="//a.impactradius-go.com/display-ad/16446-1528688" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528688/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to reverse the above change later, repeat the same steps mentioned earlier and change the value data for the **UseWindowFrameStagingBuffer** to **1**.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137218/26400" target="_top" id="2137218">
  <img src="//a.impactradius-go.com/display-ad/26400-2137218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137218/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://arkmc.pxf.io/c/5597632/352557/5172" target="_top" id="352557">
  <img src="//a.impactradius-go.com/display-ad/5172-352557" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/352557/5172" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-ultimate-6-film-compiler-tools/"><u>[New] 2024 Approved Ultimate 6 Film Compiler Tools</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-step-by-step-blueprint-for-impressive-photographic-mosaics/"><u>[New] Step-by-Step Blueprint for Impressive Photographic Mosaics</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2023s-leading-skype-capture-tools-the-ultimate-ranking-for-2024/"><u>[Updated] 2023'S Leading Skype Capture Tools The Ultimate Ranking for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-pro-tips-to-capture-stunning-and-breathtaking-gopro-time-lapse-video/"><u>[Updated] 2024 Approved Pro Tips to Capture Stunning and Breathtaking GoPro Time-Lapse Video</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-cpu-temperatures-on-windows-11-machines/"><u>Decreasing CPU Temperatures on Windows 11 Machines</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-download-updated-software-for-your-hp-deskjet-2700-all-in-one-ink-jet-printer-enhanced-performance/"><u>Easy Download: Updated Software for Your HP Deskjet 2700 All-in-One Ink Jet Printer (Enhanced Performance)</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-managing-directx-on-your-system/"><u>Efficiently Managing DirectX on Your System</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-driving-experience-the-most-effective-5-free-tools-for-pcs/"><u>Enhance Driving Experience: The Most Effective 5 Free Tools for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-runtime-broker-purpose-and-impact-on-pcs/"><u>Exploring Runtime Broker: Purpose and Impact on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/fourfold-path-to-permanently-delete-a-disk-partition-on-windows/"><u>Fourfold Path to Permanently Delete a Disk Partition on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-gamers-manual-to-prevent-data-loss-with-epic-backup/"><u>The Gamer's Manual to Prevent Data Loss with Epic Backup</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-on-hyper-v-simplified-your-win11-how-to/"><u>Turning On Hyper-V Simplified - Your Win11 How-To</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unveiling-the-features-and-performance-of-garmin-forerunner-265/"><u>Unveiling The Features and Performance of Garmin Forerunner 265</u></a></li>
</ul></div>

