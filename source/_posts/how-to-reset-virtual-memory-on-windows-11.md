---
title: How to Reset Virtual Memory on Windows 11
date: 2024-09-11T09:30:05.971Z
updated: 2024-09-12T09:30:05.971Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reset Virtual Memory on Windows 11
excerpt: This Article Describes How to Reset Virtual Memory on Windows 11
keywords: Windows Memory Reset Guide,Virtual Mem Re-Set W11,Win11 Memory Settings,Reset Windows Pagefile,Manage VRAM Windows 11,System RAM Recovery,Pagefile Size Adjustment
thumbnail: https://thmb.techidaily.com/9778babca71d8c322c58ebdc5b0f6b1ae6df8f808a7e29b4ee7032e1868f5ab0.jpg
---

## How to Reset Virtual Memory on Windows 11

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137228/26400" target="_top" id="2137228">
  <img src="//a.impactradius-go.com/display-ad/26400-2137228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137228/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Is Virtual Memory and How Does It Work?

 Virtual memory, also known as a paging file, is a technology used in computers to allow programs to use more memory than what's physically available on it. When you run out of RAM, your operating system relies on virtual memory to continue running programs.

 The computer creates a special file called a page or swap file on the hard drive. It stores some data temporarily removed from RAM and written to the hard drive. This way, the computer can access more memory than what's installed.

 Although virtual memory allows programs to operate smoothly, it can also hurt overall performance. For example, if your computer runs out of RAM, it will use more of the hard drive to store data. This also significantly slows overall performance as HDDs and SSDs are much slower than RAM.

 Let's now see how to reset Virtual Memory on Windows.

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123478/16836" target="_top" id="2123478">
  <img src="//a.impactradius-go.com/display-ad/16836-2123478" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123478/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137226/26400" target="_top" id="2137226">
  <img src="//a.impactradius-go.com/display-ad/26400-2137226" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137226/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Reset Virtual Memory To Get Better Performance

 Resetting virtual memory settings improves Windows computer performance. This guide introduces three methods to learn how to reset virtual memory on Windows. Give it a try and see which methods work best for you. If you face any issues while doing this, you can always use system restore to revert to the previous settings.

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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-automating-subtitles-for-social-media-visuals-on-instagram/"><u>[New] 2024 Approved  Automating Subtitles for Social Media Visuals on Instagram</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-expertise-in-app-performance-review/"><u>[New] In 2024, Expertise in App Performance Review</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-innovative-11-audio-devices-for-professionals/"><u>[New] Innovative 11 Audio Devices for Professionals</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-solving-windows-steams-e84-glitches/"><u>Comprehensive Guide to Solving Windows Steam's E84 Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-win-11-widget-features-efficiency-or-frivolous/"><u>Delving Into Win 11 Widget Features - Efficiency or Frivolous?</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-to-uncover-and-clear-windows-usage-tracks/"><u>Efficient Methods to Uncover and Clear Windows Usage Tracks</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-roblox-fatal-app-failures-in-windows/"><u>Fixing Roblox Fatal App Failures in Windows</u></a></li>
<li><a href="https://network-issues.techidaily.com/geforce-rtx210-update-exclusive-for-windows-11-users/"><u>GeForce RTX210 Update: Exclusive for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reactivating-and-fixing-secure-boot-grayout-issue-in-bios/"><u>Guide to Reactivating and Fixing Secure Boot Grayout Issue in BIOS</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reinstating-deleted-windows-update-service/"><u>Guide to Reinstating Deleted Windows Update Service</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-taskbar-power-in-windows-11/"><u>Harnessing Taskbar Power in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-malwarebytes-unable-to-connect-to-service-error-in-windows-11-and-11/"><u>How to Fix Malwarebytes’ “Unable to Connect to Service” Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-sound-error-code-0xc00d36b4-win11/"><u>How to Mend Sound Error: Code 0xC00D36B4, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-switch-from-standard-home-page-in-windows-11/"><u>How to Switch From Standard Home Page in Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3utools-virtual-location-not-working-on-apple-iphone-15-pro-max-fix-now-drfone-by-drfone-virtual-ios/"><u>In 2024, 3uTools Virtual Location Not Working On Apple iPhone 15 Pro Max? Fix Now | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-premium-caller-id-changers-the-magic-app-series/"><u>In 2024, Premium Caller ID Changers  The Magic App Series</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-the-ipogo-get-you-banned-and-how-to-solve-it-on-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Will the iPogo Get You Banned and How to Solve It On Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-control-rgb-lighting-in-windows-11/"><u>Learn to Control RGB Lighting in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-keystrokes-an-effective-guide-to-mending-windows-shortcut-malfunctions/"><u>Master Your Keystrokes: An Effective Guide to Mending Windows Shortcut Malfunctions</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-ip-retrieval-via-command-line/"><u>Mastering: Windows IP Retrieval via Command Line</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-iomap64-freezebsod-in-windows-10-and-8-systems/"><u>Overcoming IOMap64 Freeze/BSOD in Windows 10 & 8 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-xbox-games-download-failures/"><u>Overcoming Xbox Games Download Failures</u></a></li>
<li><a href="https://win11.techidaily.com/panels-in-peril-bring-them-back-with-these-hacks/"><u>Panels in Peril? Bring Them Back with These Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/re-gain-control-over-your-windows-hello-fingerprint-setup/"><u>Re-Gain Control Over Your Windows Hello Fingerprint Setup</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/real-time-media-streamers-app-overview-for-2024/"><u>Real-Time Media Streamer's App Overview for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/restore-your-5ghz-network-visibility-in-windows-11-top-fixes/"><u>Restore Your 5GHz Network Visibility in Windows 11 - Top Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/rotate-window-viewing-angle-windows-style/"><u>Rotate Window Viewing Angle Windows-Style</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/simply-turn-off-your-insta-tv-for-2024/"><u>Simply Turn Off Your Insta TV for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/starting-driver-verifier-on-windows-11/"><u>Starting Driver Verifier on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-no-error-message-in-win11-install/"><u>Steps to Overcome No Error Message in Win11 Install</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-combat-error-0x80072f8f-0x20000/"><u>Strategies to Combat Error 0X80072f8f - 0X20000</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-resuscitate-non-responsive-spotify-app-in-win11/"><u>Strategies to Resuscitate Non-Responsive Spotify App in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-correcting-directdraw-errors-in-win1011/"><u>Swiftly Correcting DirectDraw Errors in WIN10/11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-gpu-load-and-strain-in-windows-our-top-6-tool-list/"><u>Tackling GPU Load & Strain in Windows: Our Top 6 Tool List</u></a></li>
<li><a href="https://win11.techidaily.com/take-your-windows-11-search-to-the-next-level-top-five-insights/"><u>Take Your Windows 11 Search to the Next Level: Top Five Insights</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-tasks-admin-cmd-mode/"><u>Transform Windows Tasks: Admin CMD Mode</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-guide-why-hasnt-alan-wake-2-released-yet/"><u>Troubleshooting Guide: Why Hasn't Alan Wake 2 Released Yet?</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-your-creative-potential-using-paint-cocreator-to-make-ai-images-on-windows-11/"><u>Unleashing Your Creative Potential: Using Paint Cocreator to Make AI Images on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-secrets-to-hd-classic-quests-top-tips-and-tricks-on-windows-plus-scummvm/"><u>Unlock the Secrets to HD Classic Quests: Top Tips and Tricks on Windows + ScummVM</u></a></li>
<li><a href="https://win11.techidaily.com/vanishing-act-the-art-of-eliminating-taskbar-linguistics/"><u>Vanishing Act: The Art of Eliminating Taskbar Linguistics</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/which-screen-recorder-reigns-supreme-obs-or-fraps-for-2024/"><u>Which Screen Recorder Reigns Supreme  OBS or Fraps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-crafting-a-distinctive-user-interface/"><u>Windows 11: Crafting a Distinctive User Interface</u></a></li>
<li><a href="https://win11.techidaily.com/windows-voice-conversion-made-easy-using-whisper/"><u>Windows Voice Conversion Made Easy Using Whisper</u></a></li>
</ul></div>
