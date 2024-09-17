---
title: Mastery of Max & Min CPU Indicators on Windows
date: 2024-09-10T20:12:42.124Z
updated: 2024-09-17T09:04:38.389Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastery of Max & Min CPU Indicators on Windows
excerpt: This Article Describes Mastery of Max & Min CPU Indicators on Windows
keywords: CPU Performance Optimization,Max/Min Utilization Monitoring,Windows System Metrics,CPU Load Insights,Resource Efficiency Windows,Thermal Management Techniques,Min-Max Indicator Analysis
thumbnail: https://thmb.techidaily.com/c62b5284641027dfddd7dff7e86c9bcc06523e51b87668f0c388f2d39f0ecdca.jpg
---

## Mastery of Max & Min CPU Indicators on Windows

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

## How to Show or Hide the Minimum or Maximum Processor State Using the Registry Editor

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out[how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

 After creating the system restore point, press**Win + R** to open the Run dialog box. Then, enter**regedit** in the text box and hit the**Enter** key to open the Registry Editor.

![Regedit in Run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/regedit-11-2.jpg)

 On the UAC prompt, click**Yes** to continue.

 To get to the key for the minimum processor state in the Registry editor, copy and paste the following file path into the Registry Editor’s address bar and hit**Enter** :

`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\bc5038f7-23e0-4960-96da-33abaf5935ec`

 Right-click the**Attributes** value in the right panel and select**Modify** .

![modifying the attributes value in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-modify-attributes.jpg)

 Then, set**Value data** to**1** to hide the minimum processor state. To show it, set**Value data** to**2** .

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

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
<li><a href="https://screen-capture.techidaily.com/new-apowersoft-screenshot-suite-comprehensive-free-analysis/"><u>[New] Apowersoft Screenshot Suite Comprehensive Free Analysis</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-xsplit-archive-detailed-video-game-analyses/"><u>[Updated] 2024 Approved XSplit Archive Detailed Video Game Analyses</u></a></li>
<li><a href="https://games-able.techidaily.com/alternative-graphics-cards-to-nvidias-rtx-4060-ti/"><u>Alternative Graphics Cards to Nvidia's RTX 4060 Ti</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-realme-11-proplus-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Realme 11 Pro+ Back to Operation | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/mastering-the-art-of-implementing-audio-decline-techniques/"><u>Mastering the Art of Implementing Audio Decline Techniques</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/scrutinizing-selfies-on-instagram-validation-necessary-for-2024/"><u>Scrutinizing Selfies on Instagram Validation Necessary for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-the-top-12-leading-youtube-to-mp4-converter-tools/"><u>Ultimate Guide: The Top 12 Leading YouTube to MP4 Converter Tools</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-techniques-for-changing-a-videos-fps-from-60-to-24/"><u>Ultimate Techniques for Changing a Video's FPS From 60 to 24</u></a></li>
<li><a href="https://win11.techidaily.com/users-guide-to-the-leading-free-tool-for-downloading-vimeo-content-without-hassle/"><u>User's Guide to the Leading Free Tool for Downloading Vimeo Content Without Hassle</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136627/26400" target="_top" id="2136627">
  <img src="//a.impactradius-go.com/display-ad/26400-2136627" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136627/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

