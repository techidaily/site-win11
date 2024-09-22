---
title: Mastery of Max & Min CPU Indicators on Windows
date: 2024-09-15T04:59:22.437Z
updated: 2024-09-21T23:16:51.900Z
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
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-tecno-camon-30-pro-5g-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Tecno Camon 30 Pro 5G without App | Dr.fone</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/effective-methods-for-removing-or-disabling-facebook-from-your-android-device/"><u>Effective Methods for Removing or Disabling Facebook From Your Android Device</u></a></li>
<li><a href="https://win11.techidaily.com/explore-the-power-of-hot-keys-in-windows-11/"><u>Explore the Power of Hot Keys in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/find-forgotten-control-panel-elements-in-win11-configuration/"><u>Find Forgotten Control Panel Elements in Win11 Configuration</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/here-are-different-ways-to-find-pokemon-go-trainer-codes-to-add-to-your-account-on-apple-iphone-14-drfone-by-drfone-virtual-ios/"><u>Here are Different Ways to Find Pokemon Go Trainer Codes to Add to Your Account On Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>In 2024, What are Location Permissions Life360 On Honor X50i? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-windows-experience-with-media-player/"><u>Jumpstart Your Windows Experience with Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/make-windows-11-edge-less/"><u>Make Windows 11 Edge-Less</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mouse-mystery-solve-non-waking-windows-1011-devices/"><u>Mouse Mystery: Solve Non-Waking Windows 10/11 Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/top-5-elgato-stream-deck-models-explained/"><u>Top 5 Elgato Stream Deck Models Explained</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094414/7443" target="_top" id="2094414">
  <img src="//a.impactradius-go.com/display-ad/7443-2094414" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094414/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

