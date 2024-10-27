---
title: "Navigating PC Power Options: CPU States at The Forefront"
date: 2024-10-21T09:27:26.870Z
updated: 2024-10-27T09:56:12.845Z
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
<a href="https://aligracehair.sjv.io/c/5597632/1868571/19272" target="_top" id="1868571">
  <img src="//a.impactradius-go.com/display-ad/19272-1868571" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868571/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135353/19272" target="_top" id="2135353">
  <img src="//a.impactradius-go.com/display-ad/19272-2135353" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135353/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111982/7443" target="_top" id="2111982">
  <img src="//a.impactradius-go.com/display-ad/7443-2111982" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111982/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557746/17382" target="_top" id="1557746">
  <img src="//a.impactradius-go.com/display-ad/17382-1557746" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557746/17382" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-mastering-the-art-of-audio-with-zoom-your-complete-guidebook/"><u>[New] Mastering the Art of Audio with Zoom Your Complete Guidebook</u></a></li>
<li><a href="https://win11.techidaily.com/easypathtodarkviewinwinnotepadapp/"><u>EasyPathToDarkViewInWinNotepadApp</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-nonstop-window-upgrades/"><u>Eliminating Nonstop Window Upgrades</u></a></li>
<li><a href="https://tech-revival.techidaily.com/fast-and-easy-steps-to-transform-your-m4v-files-to-mkv-format/"><u>Fast and Easy Steps to Transform Your M4V Files to MKV Format</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-error-0x800f0922-on-windows-11-updates-step-by-step/"><u>Fixing Error 0X800F0922 on Windows 11 Updates: Step-by-Step</u></a></li>
<li><a href="https://some-guidance.techidaily.com/fixing-imovies-audio-video-desynchronization-problem-a-step-by-step-guide-including-visual-assistance/"><u>Fixing iMovie's Audio-Video Desynchronization Problem: A Step-by-Step Guide Including Visual Assistance</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-motorola-edgeplus-2023-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Motorola Edge+ (2023) | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unlock-xps-movie-magic-software-essentials/"><u>In 2024, Unlock XP's Movie Magic Software Essentials</u></a></li>
<li><a href="https://article-helps.techidaily.com/lifecast-your-show-a-basic-podcast-streaming-strategy/"><u>Lifecast Your Show A Basic Podcast Streaming Strategy</u></a></li>
<li><a href="https://extra-tips.techidaily.com/pixel-perfection-portfolio-best-animation-transformation-tools/"><u>Pixel Perfection Portfolio Best Animation Transformation Tools</u></a></li>
<li><a href="https://win11.techidaily.com/redressing-taskbar-icon-anomalies/"><u>Redressing Taskbar Icon Anomalies</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-data-organization-quickly-open-disk-management-in-win11/"><u>Simplify Data Organization: Quickly Open Disk Management in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-drawing-game-a-compilation-of-top-7-windows-11-artists/"><u>Step Up Your Drawing Game: A Compilation of Top 7 Windows 11 Artists</u></a></li>
<li><a href="https://win11.techidaily.com/stepping-around-windows-11s-tpm-and-secure-boot-rufus-guide/"><u>Stepping Around Windows 11'S TPM & Secure Boot: Rufus Guide</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-new-and-improved-amazon-echo-show-10-third-generation-mobile-screen-experience-reviewed/"><u>The New and Improved Amazon Echo Show 10: Third Generation Mobile Screen Experience Reviewed</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-voice-modification-tools-essential-choices-for-vtuber-creators-for-2024/"><u>Top Voice Modification Tools Essential Choices for VTuber Creators for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-teamsters-freeze-in-w11-and-w10/"><u>Troubleshooting Teamsters Freeze in W11 & W10</u></a></li>
</ul></div>

