---
title: "Navigating PC Power Options: CPU States at The Forefront"
date: 2024-09-11T09:43:18.791Z
updated: 2024-09-12T09:43:18.791Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating PC Power Options: CPU States at The Forefront"
excerpt: "This Article Describes Navigating PC Power Options: CPU States at The Forefront"
keywords: CPU State Control,Power Save Modes,Performance Tuning,Energy Efficiency,System Stability,PC Power Settings,Battery Life Optimization
thumbnail: https://thmb.techidaily.com/494747ec004285de2aadee4c9fc771562b4f42ca29ed6aecefce800cf9eedde4.jpg
---

## Navigating PC Power Options: CPU States at The Forefront

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137227/26400" target="_top" id="2137227">
  <img src="//a.impactradius-go.com/display-ad/26400-2137227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137227/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

To show the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c -ATTRIB_HIDE`

To hide the minimum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR 893dee8e-2bef-41e0-89c6-b55d0929964c +ATTRIB_HIDE`

To show the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec -ATTRIB_HIDE`

To hide the maximum processor state, enter the below command:

`powercfg -attributes SUB_PROCESSOR bc5038f7-23e0-4960-96da-33abaf5935ec +ATTRIB_HIDE`

 After you have typed in the command you want in the CMD window, hit the**Enter** key on your keyboard to run it.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<span id="1531879">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531879.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531879">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531879.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531879%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531879/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

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

## Add or Remove the Minimum and Maximum Processor States From Power Options

 Setting the minimum or maximum processor state on your Windows computer is vital to helping you get the performance you want from it. If you can’t see these options in the Power Options menu, you can easily reveal them with either Command Prompt or the Registry Editor. And after you’re done tweaking the states, you can hide them for their protection.

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
<li><a href="https://article-tips.techidaily.com/21-edition-synopsis-unraveling-the-future-of-online-betting-with-vegas-pro-for-2024/"><u>'21 Edition Synopsis – Unraveling the Future of Online Betting with Vegas Pro for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-mac-users-choice-why-screenflow-dominates-the-market-for-2024/"><u>[New] Mac Users' Choice Why ScreenFlow Dominates the Market for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-decoding-youtube-shorts-all-you-need-to-understand/"><u>[Updated] 2024 Approved Decoding YouTube Shorts All You Need to Understand</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-how-to-add-music-to-vimeo-videos/"><u>[Updated] How to Add Music to Vimeo Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-streamlining-media-files-from-xmltxt-to-srt-mastery/"><u>[Updated] In 2024, Streamlining Media Files From XML/TXT to SRT Mastery</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-virtual-revolution-ready-heres-a-list-of-top-7-must-haves/"><u>[Updated] Virtual Revolution Ready? Here's a List of Top 7 Must-Haves</u></a></li>
<li><a href="https://win11.techidaily.com/enable-rgb-control-for-windows-11-display/"><u>Enable RGB Control for Windows 11 Display</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-visibility-and-efficiency-using-a-90-degree-display-shift/"><u>Enhance Visibility & Efficiency Using a 90-Degree Display Shift</u></a></li>
<li><a href="https://win11.techidaily.com/expert-techniques-mastering-your-workflow-with-mspcm-on-w11/"><u>Expert Techniques: Mastering Your Workflow with MSPCM on W11</u></a></li>
<li><a href="https://win11.techidaily.com/fix-uninstall-issues-with-epic-games-hub-on-windows-11/"><u>Fix Uninstall Issues with Epic Games Hub on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-iphone-images-not-working-with-windows-systems/"><u>Fixes for iPhone Images Not Working with Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/free-windows-chatbot-embrace-gpt-liberation/"><u>Free Windows ChatBot: Embrace GPT Liberation</u></a></li>
<li><a href="https://win11.techidaily.com/getting-rid-of-windows-11s-official-store/"><u>Getting Rid of Windows 11'S Official Store</u></a></li>
<li><a href="https://win11.techidaily.com/guaranteeing-a-smooth-installation-amd-installer-success/"><u>Guaranteeing a Smooth Installation: AMD Installer Success</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-vivo-v29e-to-pc-drfone-by-drfone-android/"><u>How to Screen Mirroring Vivo V29e to PC? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-lava-storm-5g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Lava Storm 5G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-lava-blaze-pro-5g-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Lava Blaze Pro 5G Devices | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Samsung Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://win11.techidaily.com/leverage-powertoys-to-speed-up-rename-tasks/"><u>Leverage PowerToys to Speed Up Rename Tasks</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/live-streaming-on-tiktokmusically/"><u>Live Streaming on TikTok/Musical.ly</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-memory-metrics-for-windows-users/"><u>Mastery over Memory Metrics for Windows Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/mediasphere-app-user-experience-report-for-2024/"><u>MediaSphere App User Experience Report for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/purchase-bitraser-drive-wipeout-the-ultimate-data-sanitization-software/"><u>Purchase BitRaser Drive Wipeout: The Ultimate Data Sanitization Software</u></a></li>
<li><a href="https://win11.techidaily.com/recognize-invisible-drives-and-fix-windows-errors/"><u>Recognize Invisible Drives & Fix Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-group-policies-a-proactive-compliance-strategy/"><u>Refreshing Group Policies: A Proactive Compliance Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/reigniting-windows-11-triggering-start-with-a-windows-7-code/"><u>Reigniting Windows 11: Triggering Start with a Windows 7 Code</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolution-guide-fixing-issues-with-non-launching-steam-titles-on-windows-10/"><u>Resolution Guide: Fixing Issues with Non-Launching Steam Titles on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/retro-to-revitalized-atlasos-for-old-pcs/"><u>Retro to Revitalized: AtlasOS for Old PCs</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-crashing-resource-monitor-app-in-win11/"><u>Reviving Your Crashing Resource Monitor App in Win11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/seamless-compatibility-finding-and-installing-new-toshiba-drivers-for-windows/"><u>Seamless Compatibility: Finding and Installing New Toshiba Drivers for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-integration-of-vbox-in-your-windows-environment/"><u>Seamless Integration of VBox in Your Windows Environment</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/socialmediarecorder-toolkit-for-2024/"><u>SocialMediaRecorder Toolkit for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-alleviate-wlanextexes-power-drain/"><u>Steps to Alleviate WLANEXT.EXE's Power Drain</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-avoiding-random-keypress-responses/"><u>Strategies for Avoiding Random Keypress Responses</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-development-github-desktop-and-windows-11-synergy/"><u>Streamlining Development: GitHub Desktop & Windows 11 Synergy</u></a></li>
<li><a href="https://win11.techidaily.com/the-basics-of-managing-windows-11-volume-levels/"><u>The Basics of Managing Windows 11 Volume Levels</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-windows-to-dos-compilation/"><u>The Ultimate Windows To-Dos Compilation</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/top-5-affordable-video-effecting-sites-online/"><u>Top 5 Affordable Video Effecting Sites Online</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transforming-ai-dialogue-10-cutting-edge-customizations-that-outperform-standard-chatgpt/"><u>Transforming AI Dialogue: 10 Cutting-Edge Customizations That Outperform Standard ChatGPT</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/unleash-pro-level-video-editing-on-windows-8-and-beyond/"><u>Unleash Pro-Level Video Editing on Windows 8 and Beyond</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/verizon-5g-unveiled-a-glimpse-at-the-telecommunications-revolution/"><u>Verizon 5G Unveiled: A Glimpse at the Telecommunications Revolution</u></a></li>
<li><a href="https://win11.techidaily.com/win11-designing-hotkeys-for-audio-level-management/"><u>Win11: Designing Hotkeys for Audio Level Management</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-9-methods-to-halt-system-functions/"><u>Windows 11: 9 Methods to Halt System Functions</u></a></li>
</ul></div>

