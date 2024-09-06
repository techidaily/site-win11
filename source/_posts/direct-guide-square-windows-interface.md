---
title: "Direct Guide: Square Windows' Interface"
date: 2024-09-05T08:28:39.544Z
updated: 2024-09-06T08:28:39.544Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Direct Guide: Square Windows' Interface"
excerpt: "This Article Describes Direct Guide: Square Windows' Interface"
keywords: Window Interface Basics,Square Windows Setup,Windows Design Guide,Interactive Window UI,Navigating Square Windows,Simple Window Navigation,Optimizing Square UI
thumbnail: https://thmb.techidaily.com/3cd047344d86e8920c72e515095d66dfd7e255dbcb41fa2030513ad2ed26d835.jpg
---

## Direct Guide: Square Windows' Interface

 With Windows 11, Microsoft brought several visual changes to its desktop operating system, including the notable addition of rounded corners for windows, menus, and dialog boxes. While the new design update has been widely embraced by many users, there are those who prefer a more traditional look with sharp corners.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135413/19272" target="_top" id="2135413">
  <img src="//a.impactradius-go.com/display-ad/19272-2135413" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135413/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Note that this tool will not disable rounded corners in the Start menu or some modern apps. If you want to revert the changes later, simply run the downloaded EXE file again.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120866/26400?prodsku=mars" target="_top" id="2120866">
  <img src="//a.impactradius-go.com/display-ad/26400-2120866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120866/26400?prodsku=mars" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2115936/19272" target="_top" id="2115936">
  <img src="//a.impactradius-go.com/display-ad/19272-2115936" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115936/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once the graphics driver is disabled, you should see square corners on all windows and menus in Windows 11\. If you want to undo this change later, simply enable the graphics driver via Device Manager.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123737/7443" target="_top" id="2123737">
  <img src="//a.impactradius-go.com/display-ad/7443-2123737" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123737/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disabling Rounded Corners in Windows 11 Is Easy

 Using a third-party tool is arguably the most convenient way to remove rounded corners in Windows 11\. However, if you prefer to rely on the native methods, you can use the Registry Editor or Device Manager instead.

 Disabling rounded corners isn’t the only way to get the classic look of previous Windows versions. You can also use a third-party tool like the ExplorerPatcher to make Windows 11 look like Windows 10\.

 The good news is that it is possible to disable rounded corners in Windows 11, and this guide will walk you through three easy methods for the same.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-simplifying-multi-platform-group-chat-creation-on-skype-a-step-by-step-approach/"><u>[New] 2024 Approved  Simplifying Multi-Platform Group Chat Creation on Skype  A Step by Step Approach</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-unlocking-the-potential-of-filters-and-masks-for-online-conferencing/"><u>[New] 2024 Approved  Unlocking the Potential of Filters and Masks for Online Conferencing</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-syncing-your-soundtrack-import-music-into-inshot/"><u>[New] Syncing Your Soundtrack  Import Music Into InShot</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-open-source-video-tools-for-every-desktop-environment/"><u>[New] Top Open Source Video Tools for Every Desktop Environment</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-pros-technique-for-consolidated-photo-and-video-upload-to-ig/"><u>[Updated] The Pro's Technique for Consolidated Photo and Video Upload to IG</u></a></li>
<li><a href="https://screen-capture.techidaily.com/advanced-screen-recording-of-facetime-dialogues-for-2024/"><u>Advanced Screen Recording of FaceTime Dialogues for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/command-line-power-procure-system-insight-immediits/"><u>Command-Line Power: Procure System Insight Immediits</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-11-to-filter-kids-web-activity/"><u>Configuring Windows 11 to Filter Kids' Web Activity</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-unsupported-windows-interfaces-an-expert-guide/"><u>Conquer Unsupported Windows Interfaces: An Expert Guide</u></a></li>
<li><a href="https://win11.techidaily.com/cure-voice-command-issues-reactivation-techniques-for-win11/"><u>Cure Voice Command Issues: Reactivation Techniques for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-path-to-exceptional-windows-wallpapers/"><u>Decoding the Path to Exceptional Windows Wallpapers</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-power-within-wintoys-an-in-depth-user-friendly-guide-for-windows-os-users/"><u>Discover the Power Within WinToys: An In-Depth, User-Friendly Guide for Windows OS Users</u></a></li>
<li><a href="https://win11.techidaily.com/expose-hidden-components-in-windows-11-display/"><u>Expose Hidden Components in Windows 11 Display</u></a></li>
<li><a href="https://win11.techidaily.com/fast-focus-furious-fighting-efficient-gameplay-fixes-for-bf2/"><u>Fast Focus, Furious Fighting: Efficient Gameplay Fixes for BF2</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-your-windows-sleep-timer/"><u>Fine-Tune Your Window's Sleep Timer</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-external-monitor-not-detected-issue-in-windows/"><u>Fixing External Monitor Not Detected Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inactive-notifications-from-phone-link-app-in-windows-environment/"><u>Fixing Inactive Notifications From Phone Link App in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/future-on-display-the-premium-laptops-at-ifa-2023/"><u>Future on Display: The Premium Laptops at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/get-the-most-out-of-wsl-2-on-modern-windows-dev-systems/"><u>Get the Most Out of WSL 2 on Modern Windows Dev Systems</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-fixing-roblox-error-code-403-on-pc/"><u>Guide to Fixing Roblox Error Code 403 on PC</u></a></li>
<li><a href="https://win11.techidaily.com/hands-on-steps-for-buying-adobe-reader-in-microsoft-store/"><u>Hands-On Steps for Buying Adobe Reader in Microsoft Store</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/keyways-to-activate-windows-11s-backup-and-restore-options/"><u>Keyways to Activate Windows 11'S Backup and Restore Options</u></a></li>
<li><a href="https://win11.techidaily.com/live-microphone-input-addressing-recording-issues-with-obs-w11-edition/"><u>Live Microphone Input: Addressing Recording Issues with OBS, W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-or-minimize-windows-11-taskbar/"><u>Maximize or Minimize Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-asana-setbacks-a-guide-for-windows-users/"><u>Navigating Asana Setbacks: A Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/notetaking-without-installation-in-windows-11/"><u>Notetaking Without Installation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/old-meets-new-again-seven-core-windows-characteristics-evolving/"><u>Old Meets New Again: Seven Core Windows Characteristics Evolving</u></a></li>
<li><a href="https://win11.techidaily.com/reconnect-and-stay-connected-eight-ways-to-enhance-win11-point/"><u>Reconnect and Stay Connected: Eight Ways to Enhance Win11' Point</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-unresponsive-xbox-on-windows-with-ease/"><u>Resolve Unresponsive Xbox on Windows with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-alerts-on-desktop-applets/"><u>Restoring Alerts on Desktop Applets</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-installation-blockers-for-effective-win-11-uninstalls/"><u>Sidestep Installation Blockers for Effective Win 11 Uninstalls</u></a></li>
<li><a href="https://win11.techidaily.com/solving-frustrating-asana-issues-with-a-step-by-step-guide/"><u>Solving Frustrating Asana Issues with a Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/stop-chromes-spontaneous-tab-triggers-on-windows-desktop/"><u>Stop Chrome's Spontaneous Tab Triggers on Windows Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-decrease-cpu-strain-from-tiworkerexe-processes/"><u>Strategies to Decrease CPU Strain From TiWorker.exe Processes</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solution-to-fixing-windows-error-0xc00000f/"><u>Swift Solution to Fixing Windows Error 0Xc00000f</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unsupported-device-format-required-in-windows/"><u>Tackling Unsupported Device: Format Required in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-rotating-images-on-win11/"><u>The Ultimate Guide to Rotating Images on Win11</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-guide-fixing-non-functional-turtle-beach-stealth-70-microphone/"><u>Troubleshooting Guide: Fixing Non-Functional Turtle Beach Stealth 70 Microphone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-one-side-headphone-output-in-windows-10/"><u>Troubleshooting One-Side Headphone Output in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-reactivating-lost-pin-access-in-windows-11/"><u>Troubleshooting: Reactivating Lost Pin Access in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-of-old-computers-without-windows/"><u>Unleash Potential of Old Computers Without Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-power-of-efficient-directory-creation-with-newest-windows-oses/"><u>Unleash the Power of Efficient Directory Creation with Newest Windows OSes</u></a></li>
<li><a href="https://techtrends.techidaily.com/verizons-role-and-achievements-in-advancing-todays-5g-infrastructure/"><u>Verizon's Role and Achievements in Advancing Today's 5G Infrastructure</u></a></li>
<li><a href="https://win11.techidaily.com/win-wise-utorrent-speeding-up-downloads-made-simple/"><u>Win-Wise uTorrent: Speeding Up Downloads Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/win11-icons-how-to-ditch-the-focused-wallpaper-symbol/"><u>Win11 Icons: How to Ditch the Focused Wallpaper Symbol</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/youtube-music-a-guide-to-coherence-for-2024/"><u>YouTube Music  A Guide to Coherence for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>