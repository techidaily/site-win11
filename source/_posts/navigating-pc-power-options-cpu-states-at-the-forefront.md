---
title: "Navigating PC Power Options: CPU States at The Forefront"
date: 2024-09-09T17:57:04.515Z
updated: 2024-09-16T19:32:50.931Z
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-transforming-viewers-experience-the-impact-of-text-on-youtube-media/"><u>[New] 2024 Approved Transforming Viewers' Experience The Impact of Text on YouTube Media</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-tips-for-producing-high-quality-hdr-photographs-with-lightroom/"><u>2024 Approved Tips for Producing High-Quality HDR Photographs with Lightroom</u></a></li>
<li><a href="https://extra-hints.techidaily.com/capturing-perfect-sounds-our-top-6-recommendations-for-livestreamers-for-2024/"><u>Capturing Perfect Sounds Our Top 6 Recommendations for Livestreamers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/delaying-windows-10-close-out-keep-running-programs-active/"><u>Delaying Windows 10 Close-Out: Keep Running Programs Active</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-data-reducing-high-cpu-usage-with-resource-monitor/"><u>Dive Into Data: Reducing High CPU Usage with Resource Monitor</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-best-10-mock-location-apps-worth-trying-on-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>In 2024, Best 10 Mock Location Apps Worth Trying On Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Xiaomi 14 Ultra? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-dimming-features-in-windows-power-settings/"><u>Mastering Dimming Features in Windows Power Settings</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-elevate-your-videos-mastering-lower-thirds-in-fcpx/"><u>New 2024 Approved Elevate Your Videos Mastering Lower Thirds in FCPX</u></a></li>
<li><a href="https://win11.techidaily.com/reactivate-device-usage-post-sleep-in-win11/"><u>Reactivate Device Usage Post-Sleep in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocketing-performance-with-just-six-simple-steps-in-windows/"><u>Skyrocketing Performance with Just Six Simple Steps in Windows</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-solution-for-clearing-up-outriders-sound-interruptions/"><u>Step-by-Step Solution for Clearing Up Outriders' Sound Interruptions</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-applications-of-vcplusplus-release/"><u>Unveiling the Applications of VC++ Release</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120866/26400?prodsku=mars" target="_top" id="2120866">
  <img src="//a.impactradius-go.com/display-ad/26400-2120866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120866/26400?prodsku=mars" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

