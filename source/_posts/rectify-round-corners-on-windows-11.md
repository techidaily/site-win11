---
title: Rectify Round Corners on Windows 11
date: 2024-09-05T08:26:25.359Z
updated: 2024-09-06T08:26:25.359Z
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

<!-- affiliate ads begin -->
<span id="1328679">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328679.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328679">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328679.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328679%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328679/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Rectify Round Corners on Windows 11

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121335/18498" target="_top" id="2121335">
  <img src="//a.impactradius-go.com/display-ad/18498-2121335" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121335/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Disable Rounded Corners in Windows 11 Using a Third-Party Tool

**Win11DisableOrRestoreRoundedCorners** is an open-source tool available on GitHub that can help you disable rounded corners on your Windows 11 PC. Since this tool modifies your PC's system files to remove the rounded corners, it's a good idea to [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before using it.

1. Head over to GitHub’s website to [download the Win11DisableOrRestoreRoundedCorners tool](https://github.com/valinet/Win11DisableRoundedCorners/releases).
2. Double-click the downloaded executable file to run it.
3. If you see the Microsoft Defender SmartScreen window, click on **More info** and then select **Run anyway**.
4. Select **Yes** when the User Account Control (UAC) prompt appears.  
![Microsoft Defender SmartScreen Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/microsoft-defender-smartscreen-window.jpg)

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123901/26106" target="_top" id="2123901">
  <img src="//a.impactradius-go.com/display-ad/26106-2123901" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123901/26106" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137225/26400" target="_top" id="2137225">
  <img src="//a.impactradius-go.com/display-ad/26400-2137225" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137225/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136626/26400" target="_top" id="2136626">
  <img src="//a.impactradius-go.com/display-ad/26400-2136626" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136626/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<span id="1424527">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424527.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424527">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424527.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424527%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424527/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-amazons-all-star-series-most-retweeted-and-watched-originals/"><u>[New] In 2024, Amazon's All-Star Series  Most Retweeted & Watched Originals</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-silent-watchers-best-instagram-apps/"><u>[New] The Silent Watchers' Best Instagram Apps</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-vlc-screen-recorder-review-and-using-guide/"><u>[New] VLC Screen Recorder Review and Using Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-effortless-subtitling-and-cc-addition-techniques-for-youtube-users/"><u>[Updated] 2024 Approved  Effortless Subtitling & CC Addition Techniques for YouTube Users</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-the-gradual-glide-out-technique-for-audio-in-adobe-premiere-pro/"><u>[Updated] The Gradual Glide Out Technique for Audio in Adobe Premiere Pro</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-mp4-enhancement-the-ultimate-srt-integration/"><u>2024 Approved  Mastering MP4 Enhancement  The Ultimate SRT Integration</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-oppo-reno-10-proplus-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-solving-windows-steams-e84-glitches/"><u>Comprehensive Guide to Solving Windows Steam's E84 Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-nvidia-experience-error-setting-retrieval-woes-in-windows-1011/"><u>Correcting NVIDIA Experience Error - Setting Retrieval Woes in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/erase-ms-defender-logs-a-guide-to-cleansing-on-windows-oses/"><u>Erase MS Defender Logs: A Guide to Cleansing on Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-roblox-fatal-app-failures-in-windows/"><u>Fixing Roblox Fatal App Failures in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-app-blocks-system-function-problem-on-your-pc/"><u>Fixing the App Blocks System Function Problem on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reactivating-and-fixing-secure-boot-grayout-issue-in-bios/"><u>Guide to Reactivating and Fixing Secure Boot Grayout Issue in BIOS</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reinstating-deleted-windows-update-service/"><u>Guide to Reinstating Deleted Windows Update Service</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-size-constraints-essential-tips-for-resizable-gifs-on-discowin11/"><u>How to Bypass Size Constraints: Essential Tips for Resizable GIFs on DiscoWin11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-malwarebytes-unable-to-connect-to-service-error-in-windows-11-and-11/"><u>How to Fix Malwarebytes’ “Unable to Connect to Service” Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-switch-from-standard-home-page-in-windows-11/"><u>How to Switch From Standard Home Page in Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-prime-15-web-based-editing-platforms-reviewed-all-free/"><u>In 2024, Prime 15 Web-Based Editing Platforms Reviewed, All FREE</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-control-rgb-lighting-in-windows-11/"><u>Learn to Control RGB Lighting in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-keystrokes-an-effective-guide-to-mending-windows-shortcut-malfunctions/"><u>Master Your Keystrokes: An Effective Guide to Mending Windows Shortcut Malfunctions</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-ip-retrieval-via-command-line/"><u>Mastering: Windows IP Retrieval via Command Line</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-store-fixes-handling-error-code-0x80072f17/"><u>Microsoft Store Fixes: Handling Error Code 0X80072F17</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-process-of-turning-esd-files-into-windows-isos/"><u>Navigating the Process of Turning ESD Files Into Windows ISOs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-xbox-games-download-failures/"><u>Overcoming Xbox Games Download Failures</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-win11s-data-harvest-routines/"><u>Peering Into Win11’s Data Harvest Routines</u></a></li>
<li><a href="https://win11.techidaily.com/re-gain-control-over-your-windows-hello-fingerprint-setup/"><u>Re-Gain Control Over Your Windows Hello Fingerprint Setup</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-insufficient-vm-ram-issue/"><u>Resolving Windows: Insufficient VM RAM Issue</u></a></li>
<li><a href="https://win11.techidaily.com/rotate-window-viewing-angle-windows-style/"><u>Rotate Window Viewing Angle Windows-Style</u></a></li>
<li><a href="https://win11.techidaily.com/starting-driver-verifier-on-windows-11/"><u>Starting Driver Verifier on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-gpu-load-and-strain-in-windows-our-top-6-tool-list/"><u>Tackling GPU Load & Strain in Windows: Our Top 6 Tool List</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-4-ways-for-apple-iphone-6-to-mac-mirroring-drfone-by-drfone-ios/"><u>Top 4 Ways for Apple iPhone 6 to Mac Mirroring | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-for-broken-windows-google-nearby-share/"><u>Troubleshooting Guide for Broken Windows Google Nearby Share</u></a></li>
<li><a href="https://win11.techidaily.com/turning-onoff-win-10-and-11-phishing-alerts/"><u>Turning On/Off Win 10 & 11 Phishing Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-your-creative-potential-using-paint-cocreator-to-make-ai-images-on-windows-11/"><u>Unleashing Your Creative Potential: Using Paint Cocreator to Make AI Images on Windows 11</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-how-to-watch-nba-live-stream-free-anywhere/"><u>Updated How To Watch NBA Live Stream Free Anywhere</u></a></li>
<li><a href="https://win11.techidaily.com/vanishing-act-the-art-of-eliminating-taskbar-linguistics/"><u>Vanishing Act: The Art of Eliminating Taskbar Linguistics</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-crafting-a-distinctive-user-interface/"><u>Windows 11: Crafting a Distinctive User Interface</u></a></li>
<li><a href="https://win11.techidaily.com/windows-voice-conversion-made-easy-using-whisper/"><u>Windows Voice Conversion Made Easy Using Whisper</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>