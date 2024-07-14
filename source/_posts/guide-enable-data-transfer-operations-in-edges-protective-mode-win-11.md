---
title: "Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11"
date: 2024-07-13T10:01:32.333Z
updated: 2024-07-14T10:01:32.333Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11"
excerpt: "This Article Describes Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11"
keywords: Edge Security Guide,Win11 Protective Mode,Data Transfer Operations,Edge Mode Settings,Enable Data Share,Win11 Networking,Edge Secure Transfer
thumbnail: https://thmb.techidaily.com/4db798dc8e85e2daadf391573bc5ef81d7d7a8b53e675ec2733be93146fbbb0f.jpg
---

## Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on [how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  
![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

## 2\. How to Enable Copy and Paste Using Registry Editor

 The Windows Registry is another method you can use to copy and paste within Application Guard for Edge on your Windows 11 PC. But, please be aware that editing the registry can have severe consequences if done incorrectly. To be safe,[back up the registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you begin making any changes.

 Follow these steps to enable copy and paste using the Windows Registry Editor:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type "regedit" in the text box and press the Enter key.
3. If UAC prompts appear on the screen, click**Yes** to confirm your action.
4. In the Registry Editor window, navigate to the following location:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Hvsi`
5. If you don't find the Hvsi key there, you will need to create it. To do this, right-click on Microsoft and select**New > Key** .

1. In the box that appears, give it the name**Hvsi** , and then hit Enter to save the file.
2. Now right-click on**Hvsi** and select**New > DWORD (32-bit) Value** .  
![Creating a new DWORD (32-bit) Value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-dword-enableclipboard-key.jpg)
3. Put**EnableClipboard** as the name for the new DWORD key, then press Enter.
4. Click twice on the newly created DWORD key to open a pop-up window.
5. Be sure the**Hexadecimal** base is selected, and set the Value data to**1** .  
![Enable Copy and Paste with Application Guard for Edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-with-application-guard-for-edge.jpg)
6. Finally, click**OK** to save your changes.

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

## Copy and Paste Now Works With Edge Application Guard

 With Application Guard for Edge, your device can remain secure while browsing the web. Unfortunately, certain functionalities such as copy and paste are disabled by default - but don't worry! This guide will explain two methods to activate them quickly and easily.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/unveiling-fixes-for-defenders-error-code-0x80004004/"><u>Unveiling Fixes for Defender’s Error Code: 0X80004004</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-budgeting-outlay-the-expense-of-rendering-songs-visually/"><u>[Updated] In 2024, Budgeting Outlay  The Expense of Rendering Songs Visually</u></a></li>
<li><a href="https://win11.techidaily.com/skilled-tactics-bypassing-windows-11s-security-measures/"><u>Skilled Tactics: Bypassing Windows 11'S Security Measures</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-your-window-11-experience-with-these-6-desired-android-apps/"><u>Revamp Your Window 11 Experience with These 6 Desired Android Apps</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-windows-essence-crafting-and-evaluating-system-data/"><u>Peering Into Windows Essence: Crafting & Evaluating System Data</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-media-player-disruptions/"><u>Overcoming Windows Media Player Disruptions</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionary-driver-solutions-at-no-cost-to-optimize-windows-cars/"><u>Revolutionary Driver Solutions at No Cost to Optimize Windows Cars</u></a></li>
<li><a href="https://win11.techidaily.com/rescue-your-browser-fix-google-chrome-in-w11-today/"><u>Rescue Your Browser: Fix Google Chrome in W11 Today!</u></a></li>
<li><a href="https://win11.techidaily.com/rebooting-strategies-your-file-explorer-fixes/"><u>Rebooting Strategies: Your File Explorer Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/reorient-your-windows-a-guide-to-90-degree-display-adjustment/"><u>Reorient Your Windows: A Guide to 90-Degree Display Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/transformational-taskbar-update-windows-system-resources-in-view/"><u>Transformational Taskbar Update: Windows System Resources in View</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-optimal-cost-free-girl-voice-overhaul-web-application-for-2024/"><u>New Optimal Cost-Free Girl Voice Overhaul Web Application for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-there-are-several-video-players-that-you-can-use-to-watch-videos-on-your-pc-to-have-a-better-experience-viewing-videos-and-enhancing-them-across-a-s/"><u>Updated There Are Several Video Players that You Can Use to Watch Videos on Your PC. To Have a Better Experience Viewing Videos and Enhancing Them Across a Similar Platform, You Can Try Out VLC Media Player for PC</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-choosing-your-camera-companion-for-editing-hero-session-x-vs-cube/"><u>2024 Approved  Choosing Your Camera Companion for Editing  Hero Session X V/S Cube</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-cooldown-chart-on-nokia-c210-drfone-by-drfone-virtual-android/"><u>Pokémon Go Cooldown Chart On Nokia C210 | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-questions-about-intermittent-video-playback-at-photobooth/"><u>2024 Approved  Questions About Intermittent Video Playback at Photobooth</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-quickly-fix-bluetooth-not-working-on-vivo-y28-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Quickly Fix Bluetooth Not Working on Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-windows-compatible-webp-viewer-tools/"><u>Top 4 Windows-Compatible WebP Viewer Tools</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-workflow-mastering-window-commands-and-shortcuts/"><u>Streamline Your Workflow: Mastering Window Commands & Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-video-memory-crashes-in-hogwarts-legacy-windows-edition/"><u>Remedying Video Memory Crashes in 'Hogwarts: Legacy' Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/underrated-windows-11-themes-worth-appreciating/"><u>Underrated Windows 11 Themes Worth Appreciating</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-settings-app-overview/"><u>Windows 11 Settings App Overview</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-or-enable-smartfilter-on-modern-windows-os/"><u>Turn Off or Enable SmartFilter on Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/modify-homescreen-without-altering-windows-11-start-menu/"><u>Modify Homescreen without Altering Windows 11 Start Menu</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-your-gameplay-fixed-windows-wow-connectivity/"><u>Winning Back Your Gameplay: Fixed Windows WoW Connectivity</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-voice-modulation-made-easy-ranking-the-best-audio-alteration-apps-on-smartphones-for-2024/"><u>[Updated] Voice Modulation Made Easy  Ranking the Best Audio Alteration Apps on Smartphones for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-10-best-youtube-keyword-tools-to-get-more-views-for-2024/"><u>[Updated] 10 Best YouTube Keyword Tools to Get More Views for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-13-pro-3-ways-to-unlock-by-drfone-ios/"><u>In 2024, How To Unlock Apple iPhone 13 Pro 3 Ways To Unlock</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-shifting-printer-preferences-in-windows/"><u>Overcoming Shifting Printer Preferences in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-vanished-hardware-on-windows/"><u>Resolving Vanished Hardware on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-top-free-must-have-for-win11/"><u>Unleash Potential: Top Free Must-Have for Win11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/boosting-bank-balance-effective-tactics-for-mobile-video-money-making-for-2024/"><u>Boosting Bank Balance  Effective Tactics for Mobile Video Money-Making for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-harnessing-real-time-trends-for-visionary-video-ideas/"><u>In 2024, Harnessing Real-Time Trends for Visionary Video Ideas</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-from-words-to-voices-scriptwriting-for-successful-podcasts-for-2024/"><u>[Updated] From Words to Voices  Scriptwriting for Successful Podcasts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win11-22h2-for-older-systems/"><u>Navigating Win11 22H2 for Older Systems</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-windows-11-zoom-failure-1132/"><u>Unblocking Windows 11 Zoom Failure #1132</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-become-the-brand-you-want-with-our-exclusive-set-of-free-graphics/"><u>In 2024, Become the Brand You Want With Our Exclusive Set of FREE Graphics</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-jailbreak-icloud-locked-apple-iphone-12-pro-max-by-drfone-ios/"><u>In 2024, How to jailbreak iCloud locked Apple iPhone 12 Pro Max</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-11s-hidden-data-files/"><u>Navigating Through Windows 11'S Hidden Data Files</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-0x80040610-restoring-smooth-functionality-to-outlook/"><u>Tackling Error 0X80040610: Restoring Smooth Functionality to Outlook</u></a></li>
</ul></div>
