---
title: "Flat Faces for Windows: Cutting Corners Off"
date: 2024-10-16T19:21:40.673Z
updated: 2024-10-20T19:32:08.662Z
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
<a href="https://appsumo.8odi.net/c/5597632/2144272/7443" target="_top" id="2144272">
  <img src="//a.impactradius-go.com/display-ad/7443-2144272" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144272/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettide.pxf.io/c/5597632/2141684/17092" target="_top" id="2141684">
  <img src="//a.impactradius-go.com/display-ad/17092-2141684" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141684/17092" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094428/7443" target="_top" id="2094428">
  <img src="//a.impactradius-go.com/display-ad/7443-2094428" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094428/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-skills.techidaily.com/new-professionals-picks-the-top-5-drones-to-invest-in/"><u>[New] Professional's Picks The Top 5 Drones to Invest In</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-pro-converter-mp4-videos-for-social-media-fb-focus/"><u>2024 Approved Pro Converter MP4 Videos for Social Media (FB Focus)</u></a></li>
<li><a href="https://win11.techidaily.com/9-proven-remedies-for-perfectly-printing-your-powerpoint-presentations-in-windows/"><u>9 Proven Remedies for Perfectly Printing Your PowerPoint Presentations in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-remedy-onedrives-blob-tag-inaccuracy-error/"><u>A Guide to Remedy OneDrive's Blob Tag Inaccuracy Error</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-30005-for-unsuccessful-file-generation/"><u>Addressing Windows Error 30005 for Unsuccessful File Generation</u></a></li>
<li><a href="https://win11.techidaily.com/augment-win11-notebook-with-smart-companion/"><u>Augment Win11 Notebook with Smart Companion</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-dynamic-backgrounds-in-windows-11-display/"><u>Avoid Dynamic Backgrounds in Windows 11 Display</u></a></li>
<li><a href="https://win11.techidaily.com/banish-the-bluescreen-error-in-win11-with-these-simple-fixes/"><u>Banish the Bluescreen Error in Win11 with These Simple Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/blueprint-for-winapp-and-web-browser-mastery/"><u>Blueprint for WinApp and Web Browser Mastery</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-best-4-elon-musk-voice-generators-to-make-you-sound-like-the-billionaire/"><u>In 2024, Best 4 Elon Musk Voice Generators to Make You Sound Like the Billionaire</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-leverage-seo-power-secrets-of-effective-youtube-backlink-building/"><u>In 2024, Leverage SEO Power Secrets of Effective YouTube Backlink Building</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-the-ultimate-guide-to-real-time-audio-recording-in-the-digital-age/"><u>In 2024, The Ultimate Guide to Real-Time Audio Recording in the Digital Age</u></a></li>
<li><a href="https://techidaily.com/is-your-xiaomi-redmi-note-12-pro-4g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Xiaomi Redmi Note 12 Pro 4G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/rainbow-six-siege-now-working-how-i-fixed-it/"><u>Rainbow Six Siege Now Working - How I Fixed It!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unveiling-this-years-prime-pc-vr-tech-for-2024/"><u>Unveiling This Year's Prime PC VR Tech for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    