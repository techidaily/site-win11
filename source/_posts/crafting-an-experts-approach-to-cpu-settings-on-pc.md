---
title: Crafting an Expert's Approach to CPU Settings on PC
date: 2024-09-12T08:24:14.175Z
updated: 2024-09-17T05:42:18.855Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Crafting an Expert's Approach to CPU Settings on PC
excerpt: This Article Describes Crafting an Expert's Approach to CPU Settings on PC
keywords: Expert PC CPU Tuning,Masterful CPU Configuration,Professional PC Optimization,Skilled CPU Adjustment,Top PC Settings Guide,Proficient CPU Setup,Elite PC Performance Tips
thumbnail: https://thmb.techidaily.com/445d6c97ace4ef05d63cde4f33374d4b0783e76d1e91d61e1ddb527be75674b2.jpg
---

## Crafting an Expert's Approach to CPU Settings on PC

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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-3-steps-to-create-professional-gopro-vlogs-ultimate-tutorial/"><u>[New] 2024 Approved 3 Steps to Create Professional Gopro Vlogs Ultimate Tutorial</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-essential-tips-for-iphone-360-videography/"><u>[Updated] In 2024, Essential Tips for iPhone 360 Videography</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-navigating-device-specific-zoom-configurations/"><u>2024 Approved Navigating Device-Specific Zoom Configurations</u></a></li>
<li><a href="https://techtrends.techidaily.com/1725288912186-dvd/"><u>DVDの自由なコピーが一挙両論！この記事で解明する、日本人向け最強ソフトウェア</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-from-motorola-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from Motorola FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/professional-ipod-video-format-maker-easily-transform-videos-into-compatible-formats-for-ipod-ipod-touch-and-more/"><u>Professional IPod Video Format Maker - Easily Transform Videos Into Compatible Formats for iPod, iPod Touch & More</u></a></li>
<li><a href="https://win11.techidaily.com/quick-track-to-success-5-straightforward-strategies-to-speed-up-your-youtube-content-sharing-process/"><u>Quick-Track to Success: 5 Straightforward Strategies to Speed up Your YouTube Content Sharing Process</u></a></li>
<li><a href="https://win11.techidaily.com/simple-guide-to-transforming-your-pds-videos-from-cyberlinks-powerdirector-into-popular-codecs-such-as-mp4-avi-or-wmv/"><u>Simple Guide to Transforming Your PDS Videos From Cyberlink's PowerDirector Into Popular Codecs Such as MP4, AVI or WMV</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1743243">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1743243.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19272-1743243">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1743243.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Faligracehair.sjv.io%2Fc%2F5597632%2F1743243%2F19272'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1743243/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

