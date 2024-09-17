---
title: Showcasing Peak and Base States of Your CPU in Windows
date: 2024-09-13T23:35:45.807Z
updated: 2024-09-17T05:42:44.440Z
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
<li><a href="https://article-files.techidaily.com/new-beyond-hd-an-in-depth-analysis-of-eizos-cg318-4k/"><u>[New] Beyond HD An In-Depth Analysis of EIZO's CG318-4K</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-a-comparative-journey-through-the-top-10-tv-streamers/"><u>[Updated] 2024 Approved A Comparative Journey Through the Top 10 TV Streamers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-enhance-footage-quality-with-premium-handheld-stabilizers/"><u>[Updated] In 2024, Enhance Footage Quality with Premium Handheld Stabilizers</u></a></li>
<li><a href="https://win11.techidaily.com/1-ultimate-guide-downloading-youtube-content-onto-your-ipad/"><u>1. Ultimate Guide: Downloading YouTube Content Onto Your iPad</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/wonderfoxs-limited-time-deal-earn-high-value-ripper-pro-licenses-discounted-3995-7990-during-this-months-movie-campaign-join-now/"><u>WonderFox's Limited-Time Deal: Earn High-Value Ripper Pro Licenses (Discounted @$3995-$7990) During This Month’s Movie Campaign – Join Now!</u></a></li>
<li><a href="https://win11.techidaily.com/1726026812283-tiktok/"><u>パーフェクトなTikTok動画の縦横サイズ及び製作技術</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115935/19272" target="_top" id="2115935">
  <img src="//a.impactradius-go.com/display-ad/19272-2115935" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115935/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

