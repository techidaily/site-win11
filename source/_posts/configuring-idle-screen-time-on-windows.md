---
title: Configuring Idle Screen Time on Windows
date: 2024-07-29T15:47:42.714Z
updated: 2024-07-30T15:47:42.714Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring Idle Screen Time on Windows
excerpt: This Article Describes Configuring Idle Screen Time on Windows
keywords: Screen Time Control,Windows Idle Limit,Idle Display Timer,Set Screen Off Time,Configuring Idle Windows,Manage Inactive Screen,Reduce Standby Hours
thumbnail: https://thmb.techidaily.com/bbb97d5449382acc8b92ab96bfb70e5ca97a93f11d2d4de93a06ce4ca47d0742.jpg
---

## Configuring Idle Screen Time on Windows

 PC security is not just about having antivirus software on your computer. You should also restrict access to your documents on your PC while you're away from your machine.

 Read on to explore how you can automatically lock your PC after a set time, even when you leave it unattended.

## How to Keep Your Windows PC Inaccessible While Your Gone

 There are lots of places you could use a PC or laptop. It could be in the office, at a conference venue, or on the go at your favorite café. And there'll be times you just need to get up to attend to something pressing.

 Fortunately, you can set your PC to lock automatically after a custom amount of time without activity. This means you can safely leave your work desk, knowing your work is safe from prying eyes.

 Of course, you can also lock your PC manually when you walk away from it—just press the**Win + L** keys together or**Ctrl + Alt + Del** and then sign out. But you could miss doing that in a rush, or if you're distracted.

 Instead, check out these methods to configure your Windows PC to lock automatically when there is no activity after a specific amount of time.

## 1\. How to Lock Your Windows PC After a Set Time via the Local Security Policy

 Using the Local Security Policy, you can set the exact time in seconds after which your PC will lock itself automatically. Make sure you're signed in as an administrator to automatically lock your PC.

 Local Security Policy is only available in the Windows 10 and 11 Pro, Education, and Enterprise editions. If you're using the Home version, skip to method two.

1. Type**Local Security Policy** in Windows Search. Click the**Local Security Policy** under**Best match** to open it. Alternatively, press the**Win + R** keys together to open the**Run** box. Type**secpol.msc** in the**Open** navigation bar and click**OK** or hit**Enter** to launch it.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Open Local Security Policy via Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/open-local-security-policy-via-run.jpg)
2. Click the down arrow next to**Local Policies** in the left pane to expand it.
3. Click on**Security Options** to open it.
4. The Security Options will open up in the right pane. Now scroll down to the policy named**Interactive logon: Machine inactivity limit** and double-click on it to open its properties.  
<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Machine Inactivity Limit Selected in Security Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-machine-inactivity-limit-in-security-options.jpg)
5. Under the section**Machine will be locked after** , enter the time in seconds after which you want your PC to get locked automatically. This time is the time of machine inactivity or the time when your PC is idle. You can enter the time between**0** to**599940** seconds. For this tutorial, we'll enter**300 seconds** which is five minutes. Now click on**Apply** and then**OK** .
6. Finally, close the Local Security Policy window and restart your computer for the change to take effect.

 Now, when you use your PC, you will experience that your PC will lock itself after your custom timer expires. And if someone tries to unlock your PC while you're gone, it'll ask them for your password, which should keep them at bay until you get back.

 If you ever want to reverse this action and not have your PC lock automatically, just open the**Interactive logon: Machine inactivity limit** policy in**Local Security Policy** . Then just change the time or seconds to**0** —this is the default setting and will not lock your PC automatically.

## 2\. How to Lock Your Windows PC After a Specific Amount of Inactivity via the Registry Editor

 You can tweak settings in the Registry Editor to configure your PC to lock automatically after a set time. And you can do this in Windows Home and all the other Windows editions.

 However, you must be careful while making changes in the registry and should only make the changes as detailed below and not change anything else. It'd be a good idea to create a restore point in Windows before you change your registry settings. If something goes wrong, you can revert your PC to its last working state.

 Now let's go ahead and explore how to lock your PC automatically via the Registry Editor.

1. Type**Registry Editor** in**Windows Search** and select**Registry Editor** under**Best match** . Or use one of the many [ways to open the Registry Editor in Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click on**Yes** on the UAC prompt.
3. In the left pane, use the following path to reach the**System** registry key: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\Policies\\System**  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Navigate to System Key in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/navigate-to-system-key-in-registry-editor.jpg)
4. Click on the**System** key in the left pane and its components will open up in the right pane. Now scroll down to get to the**InactivityTimeoutSecs** DWORD.  
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Scroll to InactivityTimeoutSecs in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/scroll-to-inactivitytimeoutsecs.jpg)
5. Double-click on the**InactivityTimeoutSecs** DWORD to modify its value. Select**Decimal** under**Base** , and under**Value data** , enter a number between**0** to**599940** —this is the time in seconds after which your PC will get locked automatically. Like in the Local Security Policy method, we'll give it a time of**300 seconds** or five minutes. Now tap on**OK** .
6. In case you do not find the**InactivityTimeoutSecs** DWORD in your registry, you can create it. Right-click on the**System** key folder in the left pane or right-click on a space in the right pane of the**System** key. Select**New** , then select**DWORD (32-bit) Value** .  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Create InactivityTimeoutSecs DWORD in System Key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/create-inactivitytimeoutsecs-dword.jpg)  
 A new value will be created in the right pane. Name it**InactivityTimeoutSecs** . Then press**Enter** .
7. Now double-click on**InactivityTimeoutSecs** DWORD, and enter the time after which you want your PC to get locked.
8. Finally, close the Registry Editor and restart your PC to apply the changes.

 Now your PC will get locked if you're not using it or are away from it after the time you have set in the Registry Editor. If you're on a Windows 11 machine, you can also [explore a few other ways to lock your PC](https://www.makeuseof.com/windows-11-ways-to-lock/) .

 To stop your PC from getting locked automatically, modify the**InactivityTimeoutSecs** DWORD value in the Registry Editor by changing the time to**0** seconds.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Work Worry-Free on Your Windows PC With a Custom Time-Out Lock

 Now never be tense about someone getting access to your PC or your work getting stolen while you're away from your PC. Use one of the above methods to automatically lock your PC after a set time.

 You can also explore how to set up Dynamic Lock using your phone to automatically lock your PC when you move away from it.


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
<li><a href="https://youtube-web.techidaily.com/024-approved-mastering-youtubes-seo-landscape-a-keyword-expedition/"><u>[New] 2024 Approved  Mastering YouTube's SEO Landscape  A Keyword Expedition</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-achieving-youtube-success-increasing-followers-quickly/"><u>[New] Achieving YouTube Success  Increasing Followers Quickly</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-comedy-in-a-click-best-funny-short-video-suggestions-for-youtubers-for-2024/"><u>[New] Comedy in a Click  Best Funny Short Video Suggestions for YouTubers for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-dividing-recordings-top-cam-scrutiny-review-for-2024/"><u>[New] Dividing Recordings  Top Cam Scrutiny Review for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-console-capturer-pro-report/"><u>[Updated] 2024 Approved  Console Capturer Pro Report</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-advanced-android-video-and-screenshot-tools-top-5-selection-for-2024/"><u>[Updated] Advanced Android Video & Screenshot Tools, Top 5 Selection for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-detailed-instructions-mastering-the-art-of-uploading-vr-media-to-fb-for-2024/"><u>[Updated] Detailed Instructions  Mastering the Art of Uploading VR Media to FB for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-everyones-guide-to-youtube-success-10-straightforward-video-tips-for-2024/"><u>[Updated] Everyone's Guide to YouTube Success  10 Straightforward Video Tips for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-free-and-easy-building-attractive-youtube-intros-without-expense/"><u>[Updated] In 2024, Free & Easy  Building Attractive YouTube Intros without Expense</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-streamlabs-vs-obs-which-livestream-tool-reigns-supreme/"><u>[Updated] In 2024, Streamlabs Vs. OBS  Which Livestream Tool Reigns Supreme?</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-optimal-screen-reproduction-system-for-youtubing-adepts/"><u>[Updated] Optimal Screen Reproduction System for YouTubing Adepts</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-past-perspectives-unencumbered-visual-splendors/"><u>2024 Approved  Past Perspectives  Unencumbered Visual Splendors</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-the-artistic-science-behind-youtube-live-imagery/"><u>2024 Approved  The Artistic Science Behind YouTube Live Imagery</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/a-comprehensive-guide-to-iphone-6-plus-blacklist-removal-tips-and-tools-by-drfone-ios/"><u>A Comprehensive Guide to iPhone 6 Plus Blacklist Removal Tips and Tools</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-microsoft-edge-speeding-tips-for-windows-1011/"><u>Boosting Microsoft Edge: Speeding Tips for Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/classic-computing-redeemed-by-atlasos/"><u>Classic Computing Redeemed by AtlasOS</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-windows-control-with-administrator-rights/"><u>Conquering Windows Control with Administrator Rights</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-efficient-windows-11-shortcuts-for-uwp-apps/"><u>Crafting Efficient Windows 11 Shortcuts for UWP Apps</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-diskusage-in-windows-strategies-for-effective-drive-space-analysis/"><u>Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-procedure-for-total-disabling-of-windows-subsystem/"><u>Detailed Procedure for Total Disabling of Windows Subsystem</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-windows-alt-key-errors-48-characters/"><u>Diagnosing Windows Alt Key Errors (48 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/ending-failed-operations-fix-code-0x0000011b/"><u>Ending Failed Operations: Fix Code 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-file-system-usability-in-windows-max-156/"><u>Enhancing File System Usability in Windows (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-write-prohibited-files-in-windows-11/"><u>How to Tackle Write-Prohibited Files in Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-perfect-your-projects-topimarker-for-iphone-and-android/"><u>In 2024, Perfect Your Projects  TopiMarker for iPhone & Android</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-oppo-reno-11-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Oppo Reno 11 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-troubleshooting-error-connecting-to-the-apple-id-server-from-iphone-se-by-drfone-ios/"><u>In 2024, Troubleshooting Error Connecting to the Apple ID Server From iPhone SE</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-connectivity-windows-11-and-mobile-devices-unite/"><u>Innovative Connectivity: Windows 11 & Mobile Devices Unite</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-windows-features-for-macos-advantages/"><u>Integrating Windows Features for MacOS Advantages</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/mac-studio-screen-and-sounds-recording-feature/"><u>Mac Studio  Screen & Sounds Recording Feature</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-level-powershell-setup-with-admin-privileges-in-windows-11/"><u>Mastery Level: PowerShell Setup with Admin Privileges in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-hyper-v-setup-for-modern-windows-11/"><u>Navigating Hyper-V Setup for Modern Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-transition-dance-mastering-enterexit-rituals-of-terminals-focused-state/"><u>Navigating the Transition Dance: Mastering Enter/Exit Rituals of Terminal's Focused State</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-your-keyboard-precise-text-pasting-hotkeys/"><u>Personalize Your Keyboard: Precise Text Pasting Hotkeys</u></a></li>
<li><a href="https://win11.techidaily.com/quick-start-guide-for-efficient-note-placement-in-win11win10/"><u>Quick-Start Guide for Efficient Note Placement in Win11/Win10</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/real-time-conversion-of-online-streaming-content-into-gifs-for-2024/"><u>Real-Time Conversion of Online Streaming Content Into GIFs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-stalled-downloads-in-qbittorrent-for-windows/"><u>Reviving Stalled Downloads in qBittorrent for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/skyrim-to-nostalgia-windows-11-reskins-into-98-style/"><u>Skyrim to Nostalgia: Windows 11 Reskins Into 98 Style</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-windows-login-new-pin-creation/"><u>Streamline Your Windows Login: New PIN Creation</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-guide-to-widget-personalization-on-windows-11-pcs/"><u>The Beginner's Guide to Widget Personalization on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-most-impressive-windows-10-sketch-software-lineup/"><u>The Most Impressive Windows 10 Sketch Software Lineup</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-on-oneplus-ace-2v-frp-bypass-by-drfone-android/"><u>Ultimate Guide on OnePlus Ace 2V FRP Bypass</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlock-limitless-creativity-with-free-after-effects-samples-for-2024/"><u>Unlock Limitless Creativity with Free After Effects Samples for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-spiritual-command-center-of-windows-11-os/"><u>Unlocking The Spiritual Command Center of Windows 11 OS</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-xiaomi-civi-3-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Xiaomi Civi 3 Has Black Screen of Death? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/zte-nubia-flip-5g-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>ZTE Nubia Flip 5G Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
</ul></div>
