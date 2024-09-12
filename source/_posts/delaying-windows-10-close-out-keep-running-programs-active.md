---
title: "Delaying Windows 10 Close-Out: Keep Running Programs Active"
date: 2024-09-11T09:33:47.171Z
updated: 2024-09-12T09:33:47.171Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Delaying Windows 10 Close-Out: Keep Running Programs Active"
excerpt: "This Article Describes Delaying Windows 10 Close-Out: Keep Running Programs Active"
keywords: Win10 StayActive,DelayCloseWin10,ExtendRunningWindows,ProgramsKeepRunning,Windows10DelayExit,ActiveProgramsInWin10,PostponeWin10Shutdown
thumbnail: https://thmb.techidaily.com/5f1dd72a960c69600ce9688063aeb5e7a932b178d483ab7dbc13cbf4ab650189.jpg
---

## Delaying Windows 10 Close-Out: Keep Running Programs Active

 Sometimes, when shutting down, restarting, or logging off from your Windows 10 machine, you may get an error message that interrupts or even cancels the operation. To prevent this from happening, you can make Windows wait longer when logging off.

 Making the system give it a little while longer could actually save you time. Here’s what you should do, should you be faced with this situation.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<span id="1975503">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975503.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975503">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975503.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975503%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975503/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Why Does Windows Show an Error Message While Logging Off?

 It may be that you have quite a few tasks running simultaneously, each possibly with unsaved data. If this is the case, each task or application attempts to save data before Windows logs off. This could be one reason for the error message. As a remedy, you may want to extend the time allotted for signing off to allow all tasks to finish what they are doing.

 Alternatively, it could just be a problem task. This may be true if it is a recurring issue. In this case, and if you’re sure none of the applications you are using will lose data, you could make Windows force a sign-off more quickly.

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Should You Try First?

 The method described here basically forces Windows to wait longer while shutting down or logging off. However, if you have a misbehaving program interfering with Windows log-off, it could be something to look into. There are fixes you should try first if there is an[app preventing Windows from shutting down or logging off](https://www.makeuseof.com/this-app-preventing-windows-shutting-down-restarting-signing-out-error/) .

 If none of those options works, you can adjust how long Windows waits before logging off, which gives any running or buggy apps more time to sort themselves out.

## Make Windows Wait Longer When Logging Off

 There are two processes that you can turn to. With the first, WaitToKillAppTimeout, Windows grants apps 20 seconds to save data and close. If apps don’t respond, Windows considers them “hung.” HungAppTimeout, the second, tells Windows how many seconds to wait before considering apps to be hung and offering a force-close solution.

 Changing both these values involves[editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) , so be wary, and[make a backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) copy before you tinker with it.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1A. How to Set WaitToKillAppTimeout for Just Your User Account

 Do this to change how long Windows waits for apps when logging off just from your user account.

1. Open the Registry editor. See[how to open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) for more information.
2. Navigate to the following folder in the registry:  
`HKEY_CURRENT_USER\Control Panel\Desktop`
3. In the pane on the right, look for the string named**WaitToKillAppTimeout** .
4. If you don’t see it, you’ll need to create it by right-clicking in any empty space in the pane and selecting**New > String Value** . Rename it**WaitToKillAppTimeout** .
5. Double-click this string to edit its value, which is in milliseconds. (1000 milliseconds equals one second.) By default, the value data is set to 20,000 (or 20 seconds).
6. Increase this value to make Windows wait on running apps longer before shutting down or logging off. (Decreasing its value will log you off more quickly.)

### 1B. How to Change WaitToKillAppTimeout for All Users

This will apply altered log-off rules to all users on the PC.

1. Open the Registry editor.
2. Navigate to the following folder in the registry:  
`HKEY_USERS\.DEFAULT\Control Panel\Desktop`
3. Follow steps three to six from method 1A to change how long Windows waits for apps to finish closing properly when logging off for all users.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132162/7443" target="_top" id="2132162">
  <img src="//a.impactradius-go.com/display-ad/7443-2132162" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132162/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2A. How to Set HungAppTimeout for Just Your User Account

 Doing this will change how long Windows waits for apps that it considers hung. This is just for your user account.

1. Open the Registry Editor.
2. Navigate to the following folder in the Registry:  
`HKEY_CURRENT_USER\Control Panel\Desktop`
3. In the pane on the right, look for the string named**HungAppTimeout** .
4. If the string doesn’t exist, create it by right-clicking in any empty space in the pane and choosing**New > String Value** . Rename it**HungAppTimeout** .
5. Double-click this string to edit its value – again, in milliseconds. (1000 milliseconds equals 1 second.) By default, the value data is set to 5000.
6. Increase this value to make Windows afford more time to hung apps and wait longer when shutting down or logging off. (Reduce this value to log off more quickly.)

<!-- affiliate ads begin -->
<span id="1975636">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975636.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975636">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975636.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975636%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975636/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2B. How to Change HungAppTimeout for All Users

This will allow you to change the default value for all users.

1. Open the Registry Editor.
2. Navigate to the following folder in the registry:  
`HKEY_USERS\.DEFAULT\Control Panel\Desktop`
3. Follow steps 3 to 6 from method 2A to change how long Windows waits when logging off for all users.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123478/16836" target="_top" id="2123478">
  <img src="//a.impactradius-go.com/display-ad/16836-2123478" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123478/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Give Apps More Time to Close When Logging Off

 If apps keep interrupting Windows when you shut down or log off, it would be wise to give them a little more time to finish up and close properly. That way, they won’t interrupt the log-off process and have you intervene manually.

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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-tips-for-extending-instagram-videos-beyond-limits/"><u>[New] 2024 Approved Tips for Extending Instagram Videos Beyond Limits</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-comprehensive-review-of-slomo-video-capture-tool/"><u>[New] Comprehensive Review of SloMo Video Capture Tool</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-maximizing-buzz-making-hype-on-twitter-videos-for-2024/"><u>[New] Maximizing Buzz Making Hype on Twitter Videos for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-10-cool-features-that-make-you-love-filmora-video-editor/"><u>[Updated] 10 Cool Features That Make You Love Filmora Video Editor</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-harness-the-power-of-instagrams-hidden-features/"><u>[Updated] 2024 Approved Harness the Power of Instagram's Hidden Features</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-exemplary-cloud-services-for-biz-needs-for-2024/"><u>[Updated] Exemplary Cloud Services for Biz Needs for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-quick-fit-enhance-your-photo-posts-with-automated-mac-video-scaling/"><u>[Updated] Quick Fit Enhance Your Photo Posts with Automated Mac Video Scaling</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-swift-valorant-image-crafting-professionally-done-on-the-fly/"><u>[Updated] Swift Valorant Image Crafting Professionally Done on the Fly</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-viewership-volume-the-financial-impact-of-one-million-views/"><u>[Updated] Viewership Volume The Financial Impact of One Million Views</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-leading-6-fiscal-sensible-options-in-high-res-projection/"><u>2024 Approved Leading 6 Fiscal Sensible Options in High-Res Projection</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-play-and-save-nvidias-simple-screen-recorder/"><u>2024 Approved Play and Save NVIDIA's Simple Screen Recorder</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-non-compliance-overcoming-intel-hd-graphics-errors/"><u>Addressing Non-Compliance: Overcoming Intel HD Graphics Errors</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-portable-executable-pe-syntax/"><u>Decoding Windows Portable Executable (PE) Syntax</u></a></li>
<li><a href="https://win11.techidaily.com/digital-artistic-solutions-like-procreate-for-windows/"><u>Digital Artistic Solutions Like Procreate For Windows</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-ease-of-disk-management-access-on-win-1011/"><u>Discover the Ease of Disk Management Access on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-workday-6-time-management-apps-on-windows/"><u>Elevate Your Workday: 6 Time Management Apps on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-accelerated-gpu-task-order-in-windows/"><u>Eliminating Accelerated GPU Task Order in Windows</u></a></li>
<li><a href="https://fox-that.techidaily.com/expert-tips-for-diagnosing-and-repairing-failed-imessage-delivery-on-iphone/"><u>Expert Tips for Diagnosing and Repairing Failed iMessage Delivery on iPhone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-adjust-administrative-controlled-options-in-windows-11-os/"><u>How to Adjust Administrative Controlled Options in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-onedrive-cloud-operation-was-unsuccessful-error-in-windows-11-and-11/"><u>How to Fix the OneDrive Cloud Operation Was Unsuccessful Error in Windows 11 & 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-vivo-y100i-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Vivo Y100i Location on Skout | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-the-two-factor-authentication-on-iphone-xr-by-drfone-ios/"><u>In 2024, How To Remove the Two Factor Authentication On iPhone XR</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-is-fake-gps-location-pro-and-is-it-good-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What is Fake GPS Location Pro and Is It Good On Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/integrate-and-setup-windows-hello-with-a-fingerprint/"><u>Integrate and Setup: Windows Hello with a Fingerprint</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-facebook-messages-overcoming-window-snags/"><u>Mastering Facebook Messages: Overcoming Window Snags</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixed-windows-pin-issues/"><u>Mastering the Art of Fixed Windows PIN Issues</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11s-tool-accessibility-settings/"><u>Mastering Windows 11'S Tool Accessibility Settings</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/memes-mastermind-for-2024/"><u>Memes Mastermind for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-pathways-to-windows-performance-reports/"><u>Quick Pathways to Windows Performance Reports</u></a></li>
<li><a href="https://android-unlock.techidaily.com/remove-the-lock-screen-fingerprint-of-your-samsung-galaxy-f54-5g-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Samsung Galaxy F54 5G</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-android-tablet-and-w11-duo-display-setup/"><u>Seamless Android Tablet & W11 Duo Display Setup</u></a></li>
<li><a href="https://win11.techidaily.com/securely-implementing-execution-policies-in-windows-powershell/"><u>Securely Implementing Execution Policies in Windows PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/simplicity-and-clarity-in-the-newest-w11-start/"><u>Simplicity & Clarity in the Newest W11 Start</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-settle-windows-laptop-latency-after-external-monitors-addition/"><u>Swiftly Settle Window's Laptop Latency After External Monitors Addition</u></a></li>
<li><a href="https://win11.techidaily.com/thaw-frozen-handbrake-on-windows/"><u>Thaw Frozen HandBrake on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-your-inner-artist-creating-captivating-ai-visuals-with-paint-cocreator-and-windows-11/"><u>Unleash Your Inner Artist: Creating Captivating AI Visuals with Paint Cocreator & Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-power-of-system-preferences/"><u>Unlock the Power of System Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11s-credentials-top-11-techniques/"><u>Unlocking Windows 11'S Credentials: Top 11 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-guide-to-steganographic-hiding-techniques-for-archives/"><u>Win10/11 Guide to Steganographic Hiding Techniques for Archives</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-network-conundrum-defeat-error-0x800704b3/"><u>Win10/11 Network Conundrum: Defeat Error 0X800704B3</u></a></li>
<li><a href="https://win11.techidaily.com/workspace-efficiency-attach-gmail-to-desktop-border/"><u>Workspace Efficiency: Attach Gmail to Desktop Border</u></a></li>
</ul></div>

