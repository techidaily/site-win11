---
title: "Steps to Turn On Content Transfer Within Windows 11'S Shielded Mode: Microsoft Edge App Guard"
date: 2024-09-05T08:33:26.950Z
updated: 2024-09-06T08:33:26.950Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Steps to Turn On Content Transfer Within Windows 11'S Shielded Mode: Microsoft Edge App Guard"
excerpt: "This Article Describes Steps to Turn On Content Transfer Within Windows 11'S Shielded Mode: Microsoft Edge App Guard"
keywords: Win11 EdgeAppGuard ContentTransfer,Activate EdAppGuard Shielding,Enable Windows 11 TransferMode,TurnOn AppGuard Mode Shield,StepWin11 ContentTransferShield,Initiate Shielded EdgeContent,StartEdgeGuard Transfers
thumbnail: https://thmb.techidaily.com/453561a8ca0d834b48f18b90c63e8754b707ad468e25eb7e04a5333cdbe19d66.jpg
---

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Steps to Turn On Content Transfer Within Windows 11'S Shielded Mode: Microsoft Edge App Guard

 Looking to improve the security of your device? Microsoft Edge's Application Guard feature is an ideal solution, as it creates a virtualized atmosphere and blocks malicious websites. However, copy and paste functionality is disabled by default in this setting for extra precautionary measures.

 If you would like to switch on copy and paste within Application Guard for Edge on Windows 11, then this guide will assist you in doing so.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. How to Enable Copy and Paste via Windows Settings

 To enable copy and paste in Application Guard for Edge, follow the steps below:

1. Right-click on Start and select**Settings** from the menu list. For more information, check out our guide on[how to open the Settings window](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Privacy & security** from the left pane.
3. Then click the**Windows Security** option on the right-hand side.
4. On the following screen, select**App & browser control** .
5. Go to the Isolated browsing section and click the link "Change Applications Guard settings."  
![Change Application Guard Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/change-application-guard-settings.jpg)
6. Search for the**Copy and paste** option, then click the toggle to enable it.  
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123473/16836" target="_top" id="2123473">
  <img src="//a.impactradius-go.com/display-ad/16836-2123473" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123473/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Enable Copy and Paste via Windows Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/enable-copy-and-paste-via-windows-settings.jpg)
7. The UAC prompt will appear on the screen. Click**Yes** to continue.

 Once you’ve completed the steps, restart your computer for the changes to work. Now, you can securely transfer data between a virtualized environment and your device without any worries about security risks - malicious websites and applications will be blocked even with this setting enabled.

 If you ever need to disable copy and paste in Application Guard for Edge, you can follow the same steps mentioned above. Just be sure to toggle off the Copy and Paste setting from the Isolated browsing menu instead.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129740/7443" target="_top" id="2129740">
  <img src="//a.impactradius-go.com/display-ad/7443-2129740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115912/19272" target="_top" id="2115912">
  <img src="//a.impactradius-go.com/display-ad/19272-2115912" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115912/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve completed the steps, close any running applications and restart your computer

 If you'd like to turn off this feature, just repeat the aforementioned steps, but set the Value data to**0** and click**OK** . That's all it takes for your changes to be put into effect!

 Now that you've read the above steps, you should have a clear understanding of how to enable and disable copy and paste within Application Guard for Edge on Windows 11.

<!-- affiliate ads begin -->
<span id="1993645">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993645.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993645">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993645.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993645%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993645/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-vocal-lens-capture-microphone-inputs/"><u>[New] 2024 Approved  Vocal Lens Capture  Microphone Inputs</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-bypassing-common-drone-mistakes-with-this-essential-checklist/"><u>[New] Bypassing Common Drone Mistakes with This Essential Checklist</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-the-leading-free-software-for-quality-desktop-recording/"><u>[New] In 2024, The Leading Free Software for Quality Desktop Recording</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-iphone-users-learn-simple-screen-recording-now-in-2024/"><u>[New] Iphone Users, Learn Simple Screen Recording Now, In 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-creating-captivating-360-footage-for-social-media-sharing/"><u>[Updated] In 2024, Creating Captivating 360 Footage for Social Media Sharing</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-how-to-captivate-with-instagrams-live-feature/"><u>[Updated] In 2024, How to Captivate with Instagram's Live Feature</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-simplified-methods-to-screen-record-instagrams-story-feature/"><u>[Updated] In 2024, Simplified Methods to Screen Record Instagram's Story Feature</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-syma-x5c-review-best-drone-for-beginner/"><u>[Updated] In 2024, Syma X5C Review  Best Drone for Beginner</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-optical-character-recognition-ocr-understanding-image-based-text-capture-with-copernic-software/"><u>A Deep Dive Into Optical Character Recognition (OCR): Understanding Image-Based Text Capture with Copernic Software</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-video-files-on-edge-2023-by-fonelab-android-recover-video/"><u>Complete guide for recovering video files on Edge 2023</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-pc-conflicts-with-pct-guide/"><u>Conquer PC Conflicts with PCT Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/correcting-dark-screens-on-mobile-devices/"><u>Correcting Dark Screens on Mobile Devices</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-disabling-the-mystery-of-0x8007045d-on-windows-11/"><u>Decoding and Disabling the Mystery of 0X8007045d on Windows 11</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/easy-and-speed-share-youtube-playlists-now/"><u>Easy & Speed  Share YouTube Playlists Now</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-integrating-msixbundle-and-msix-extensions-into-windows/"><u>Essential Guide: Integrating Msixbundle & MSIX Extensions Into Windows</u></a></li>
<li><a href="https://win11.techidaily.com/family-fortification-the-top-5-corrections-for-safe-haven/"><u>Family Fortification: The Top 5 Corrections for Safe Haven</u></a></li>
<li><a href="https://win11.techidaily.com/find-your-inbox-efficiency-discover-faster-email-recovery-with-outlook-and-copernics-lightning-quick-search/"><u>Find Your Inbox Efficiency: Discover Faster Email Recovery with Outlook and Copernic's Lightning-Quick Search</u></a></li>
<li><a href="https://win11.techidaily.com/1723809008305-find-your-inbox-efficiency-discover-faster-email-recovery-with-outlook-and-copernics-lightning-quick-search/"><u>Find Your Inbox Efficiency: Discover Faster Email Recovery with Outlook and Copernic's Lightning-Quick Search!</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-steams-unauthorized-files-problem-in-win11/"><u>Fixing Steam's Unauthorized Files Problem in Win11</u></a></li>
<li><a href="https://driver-install.techidaily.com/free-downloads-for-optimized-performance-on-gaomon-s620/"><u>Free Downloads for Optimized Performance on Gaomon S620</u></a></li>
<li><a href="https://win11.techidaily.com/getting-around-a-non-opening-windows-command-prompt/"><u>Getting Around a Non-Opening Windows Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/handling-printer-id-clashes-in-windows/"><u>Handling Printer ID Clashes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correctly-handle-read-only-folders-on-windows/"><u>How to Correctly Handle Read-Only Folders on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-broken-registry-items-in-windows-11/"><u>How to Fix Broken Registry Items in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-github-desktop-in-windows-11-and-11/"><u>How to Use GitHub Desktop in Windows 11 and 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-tecno-pova-6-pro-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Tecno Pova 6 Pro 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-pattern-locks-are-unsafe-secure-your-samsung-galaxy-m14-5g-phone-now-with-these-tips-by-drfone-android/"><u>In 2024, Pattern Locks Are Unsafe Secure Your Samsung Galaxy M14 5G Phone Now with These Tips</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/1715860799617-in-2024-playcapture-pro-your-own-screen-recorder-free/"><u>In 2024, PlayCapture Pro  Your Own Screen Recorder, Free!</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-step-into-the-details-the-quickest-ways-to-zoom-in-minecraft/"><u>In 2024, Step Into the Details  The Quickest Ways to ZOOM in Minecraft</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-picks-for-online-classical-tone-downloads/"><u>In 2024, Top Picks for Online Classical Tone Downloads</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intro-to-digital-art-accessing-microsoft-paint-in-windows-11/"><u>Intro to Digital Art: Accessing Microsoft Paint in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/linux-flourish-windows-subsystem-effect/"><u>Linux Flourish: Windows Subsystem Effect?</u></a></li>
<li><a href="https://win11.techidaily.com/lowering-pc-resource-demand-fixing-wmi-usage-issues/"><u>Lowering PC Resource Demand: Fixing WMI Usage Issues</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-maze-of-full-screen-issues-fix-sonic-adventure-crashes-win-on-windows-11/"><u>Master the Maze of Full-Screen Issues: Fix Sonic Adventure Crashes, Win! On Windows 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/mastering-obs-and-zoom-integration-tips/"><u>Mastering OBS & Zoom  Integration Tips</u></a></li>
<li><a href="https://win11.techidaily.com/1723809006534-mastering-social-media-growth-with-seamless-menu-expand-functions-on-fb-li-yt-top-level-navigation-essentials/"><u>Mastering Social Media Growth with Seamless Menu Expand Functions on FB, LI, YT - Top-Level Navigation Essentials!</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-fixing-windows-1011-filesystem-issues/"><u>Navigating and Fixing Windows 10/11 Filesystem Issues</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-apple-iphone-13-pro-max-by-drfone-ios/"><u>New Multiple Ways How To Remove iCloud Activation Lock From your Apple iPhone 13 Pro Max</u></a></li>
<li><a href="https://win-answers.techidaily.com/ntdlldll-malfunction-no-more-comprehensive-fix-guide-for-windows-1110-users/"><u>ntdll.dll Malfunction No More: Comprehensive Fix Guide for Windows 11/10 Users</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-downloads-a-guide-to-the-microsoft-store/"><u>Optimize Your Downloads: A Guide to the Microsoft Store</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/professional-ppt-recording-tactics-and-tricks-for-2024/"><u>Professional PPT Recording Tactics and Tricks for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/protecting-yourself-from-fraudgpt-a-guide-to-staying-safe-in-the-digital-world/"><u>Protecting Yourself From FraudGPT: A Guide to Staying Safe in the Digital World</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-round-corners-on-windows-11/"><u>Rectify Round Corners on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/renaming-microsoft-account-admin-for-enhanced-security/"><u>Renaming Microsoft Account Admin for Enhanced Security</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-stream-disconnection-in-remote-pc-mode/"><u>Resolving Stream Disconnection in Remote PC Mode</u></a></li>
<li><a href="https://win11.techidaily.com/shake-off-frozen-clicks-top-6-tips-for-windows-users/"><u>Shake Off Frozen Clicks: Top 6 Tips for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocketing-output-5-essential-windows-productivity-hacks/"><u>Skyrocketing Output: 5 Essential Windows Productivity Hacks</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-how-to-fix-your-pc-when-it-gets-stuck-during-the-boot-process/"><u>Solution: How to Fix Your PC When It Gets Stuck During the Boot Process</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-win11-cc-troubleshooting-made-easy/"><u>Step-by-Step Guide: Win11 CC Troubleshooting Made Easy</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-quick-systemsettings-fix-on-windows-11/"><u>Strategies for Quick SystemSettings Fix on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-stranded-site-stories-seven-windows-workarounds-for-access-issues/"><u>The Stranded Site Stories: Seven Windows Workarounds for Access Issues</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-5-risks-of-relying-on-chatgpt-for-health-consultations/"><u>Top 5 Risks of Relying on ChatGPT for Health Consultations</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-adjusting-creation-and-modification-dates-in-windows/"><u>Understanding and Adjusting Creation & Modification Dates in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-full-potential-chromium-setup-for-windows-11/"><u>Unleash Full Potential: Chromium Setup for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11-potential-mastering-the-run-command-enhancement/"><u>Unlock Windows 11 Potential: Mastering the Run Command Enhancement</u></a></li>
<li><a href="https://driver-download.techidaily.com/up-to-date-driver-support-for-your-hp-deskjet-3700-printer/"><u>Up-to-Date Driver Support for Your HP DeskJet 3700 Printer</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-extract-audio-from-mp4-the-best-mp4-to-mp3-converters-this-year/"><u>Updated Extract Audio From MP4 The Best MP4 to MP3 Converters This Year</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/winning-strategies-with-fifa-19-why-its-a-leader-in-sports-gaming/"><u>Winning Strategies with FIFA 19: Why It's a Leader in Sports Gaming</u></a></li>
</ul></div>
