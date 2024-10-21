---
title: Showcasing Peak and Base States of Your CPU in Windows
date: 2024-10-19T04:59:43.298Z
updated: 2024-10-21T02:37:47.386Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Showcasing Peak and Base States of Your CPU in Windows
excerpt: This Article Describes Showcasing Peak and Base States of Your CPU in Windows
keywords: PeakCPUStateWindows,BaseCPUStatesPC,WindowsCPUPeakView,BaseStateCPUWin,HighPerformanceCPU,CPUHeatMapWin,TemperatureBaseState
thumbnail: https://thmb.techidaily.com/b5066dad0b601fca3256158753d40238cd5a1c7754394d186d31755e512b1e70.jpg
---

## Showcasing Peak and Base States of Your CPU in Windows

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
<a href="https://appsumo.8odi.net/c/5597632/2049390/7443" target="_top" id="2049390">
  <img src="//a.impactradius-go.com/display-ad/7443-2049390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049388/7443" target="_top" id="2049388">
  <img src="//a.impactradius-go.com/display-ad/7443-2049388" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049388/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137379/7443" target="_top" id="2137379">
  <img src="//a.impactradius-go.com/display-ad/7443-2137379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 For the maximum processor state, enter the below file path in the Registry Editor's address bar to get to its key:

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\893dee8e-2bef-41e0-89c6-b55d0929964c`

 Double-click the**Attributes** entry to modify it, and then change**Value data** to**1** to hide the maximum processor state or**2** to show it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006946/19272" target="_top" id="2006946">
  <img src="//a.impactradius-go.com/display-ad/19272-2006946" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006946/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://snapchat-videos.techidaily.com/new-discover-snapchats-biggest-drawings-and-effects-for-2024/"><u>[New] Discover Snapchat's Biggest Drawings & Effects for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-reviewing-the-powerhouse-of-magixs-photo-toolkit/"><u>[Updated] Reviewing the Powerhouse of MAGIX's Photo Toolkit</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-role-of-competitive-intelligence-in-effective-market-research/"><u>[Updated] The Role of Competitive Intelligence in Effective Market Research</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-a-list-makeup-tutorials-who-to-watch/"><u>2024 Approved A-List Makeup Tutorials Who to Watch ?</u></a></li>
<li><a href="https://games-able.techidaily.com/2024s-elite-vr-devices-unveiled-in-depth-evaluations-and-ratings-from-industry-experts-cnet/"><u>2024'S Elite VR Devices Unveiled: In-Depth Evaluations and Ratings From Industry Experts | CNET</u></a></li>
<li><a href="https://win11.techidaily.com/command-center-transformation-the-terminal-takes-priority/"><u>Command Center Transformation: The Terminal Takes Priority</u></a></li>
<li><a href="https://win11.techidaily.com/easy-troubleshooting-techniques-for-renaming-folders-issue-on-windows-11/"><u>Easy Troubleshooting Techniques for Renaming Folders Issue on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/erase-unnecessary-highlighted-icon-on-win11/"><u>Erase Unnecessary Highlighted Icon on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/flip-and-turn-images-6-easy-techniques-on-your-win11-pc/"><u>Flip and Turn Images: 6 Easy Techniques on Your Win11 PC</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-6-by-drfone-ios/"><u>How to Unlock iPhone 6?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimizing-workflows-task-scheduler-and-batch-files/"><u>Optimizing Workflows: Task Scheduler & Batch Files</u></a></li>
<li><a href="https://win11.techidaily.com/quick-windows-navigation-made-simple-with-key-combinations/"><u>Quick Windows Navigation Made Simple with Key Combinations</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-integrity-to-nonworking-troubleshooters-in-modern-windows/"><u>Restoring Integrity to Nonworking Troubleshooters in Modern Windows</u></a></li>
<li><a href="https://fox-that.techidaily.com/the-seven-main-issues-leading-to-delayed-wi-fi-on-phones-explained/"><u>The Seven Main Issues Leading to Delayed Wi-Fi on Phones Explained</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-rectifying-windows-error-0x80071a90/"><u>Understanding and Rectifying Windows Error: 0X80071A90</u></a></li>
<li><a href="https://article-helps.techidaily.com/unleashing-visual-treasures-a-pexels-search-guide-for-2024/"><u>Unleashing Visual Treasures A Pexels Search Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-how-to-manually-adjust-your-clock-region/"><u>Windows: How to Manually Adjust Your Clock Region</u></a></li>
</ul></div>

