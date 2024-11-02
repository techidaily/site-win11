---
title: "Revealing the Extremes: Processor Stages in Windows"
date: 2024-10-28T18:57:37.708Z
updated: 2024-11-01T16:47:02.810Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revealing the Extremes: Processor Stages in Windows"
excerpt: "This Article Describes Revealing the Extremes: Processor Stages in Windows"
keywords: Windows CPU Stages,Processing Windows Specs,Windows Execution Cycles,Windows Core Tech,Windows Microarchitecture,Windows Performance Factors,Windows Chip Analysis
thumbnail: https://thmb.techidaily.com/0c878b30db98d758dc708e36a3a1a79c906ed9e88e0726b5c47115417927372d.jpg
---

## Revealing the Extremes: Processor Stages in Windows

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many[ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

![Cmd in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/win11-cmd.jpg)

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
<a href="https://aligracehair.sjv.io/c/5597632/1938682/19272" target="_top" id="1938682">
  <img src="//a.impactradius-go.com/display-ad/19272-1938682" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938682/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<span id="1983446">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983446.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983446">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983446.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983446%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983446/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538">
  <img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068412/7443" target="_top" id="2068412">
  <img src="//a.impactradius-go.com/display-ad/7443-2068412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068412/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

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
<li><a href="https://youtube-zero.techidaily.com/ed-how-to-remove-youtube-videos/"><u>[Updated] How to Remove YouTube Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-rage-raid-and-rebel-without-a-gta-tale/"><u>[Updated] Rage, Raid and Rebel Without a GTA Tale</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1-crafting-multiple-network-interfaces-on-macos-a-guide-to-enhanced-connectivity-options/"><u>1. Crafting Multiple Network Interfaces on macOS: A Guide to Enhanced Connectivity Options</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-keyboard-input-lag-on-windows-11-and-11/"><u>7 Ways to Fix Keyboard Input Lag on Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-phone-dialer-in-windows-11/"><u>Accessing Phone Dialer in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-operational-windows-11-taskbar/"><u>Addressing Non-Operational Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-sync-failures-with-microsoft-to-do/"><u>Addressing Sync Failures with Microsoft To Do</u></a></li>
<li><a href="https://win11.techidaily.com/adjust-screen-direction-on-windows-pc/"><u>Adjust Screen Direction on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/altwindirstat-reigniting-your-file-systems-potential-on-windows/"><u>AltWinDirStat: Reigniting Your File System's Potential on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/automating-productivity-with-to-do-and-ifttt/"><u>Automating Productivity with To-Do and IFTTT</u></a></li>
<li><a href="https://some-approaches.techidaily.com/discover-the-ultimate-selection-the-best-14-audio-transformation-applications-available-for-free/"><u>Discover the Ultimate Selection: The Best 14 Audio Transformation Applications Available for Free</u></a></li>
<li><a href="https://buynow-info.techidaily.com/dissecting-the-delightfully-chaotic-world-of-overcooked-2/"><u>Dissecting the Delightfully Chaotic World of Overcooked 2</u></a></li>
<li><a href="https://win11.techidaily.com/1719219819181-explore-the-full-capabilities-of-windows-snip-and-sketch-tool/"><u>Explore the Full Capabilities of Windows' Snip & Sketch Tool.</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-snapping-success-how-to-choose-the-best-camera-views-on-iphone/"><u>In 2024, Snapping Success How to Choose the Best Camera Views on iPhone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-youtube-thumbnail-design-on-macos-unveiled/"><u>In 2024, YouTube Thumbnail Design on macOS Unveiled</u></a></li>
<li><a href="https://extra-information.techidaily.com/leap-into-the-future-a-guide-for-windows-11-installation/"><u>Leap Into the Future A Guide for Windows 11 Installation</u></a></li>
<li><a href="https://games-able.techidaily.com/remedying-the-cross-platform-steam-sync-issue/"><u>Remedying the Cross-Platform Steam Sync Issue</u></a></li>
</ul></div>

