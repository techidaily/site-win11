---
title: Demystifying Processor Limits in Power Options Menu
date: 2024-07-02T13:01:37.120Z
updated: 2024-07-03T13:01:37.120Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Demystifying Processor Limits in Power Options Menu
excerpt: This Article Describes Demystifying Processor Limits in Power Options Menu
keywords: CPU Thresholds Explained,Power Limit Insights,Optimal Battery Settings,Performance Curve Analysis,Processor Capability Guide,Energy Efficiency Controls,Maxing Out Devices
thumbnail: https://thmb.techidaily.com/0f034b01e896bfeb1b76fcb002ff3f08bf8065e806075d9660abdc53bcbc29eb.jpg
---

## Demystifying Processor Limits in Power Options Menu

 Have you ever tried to tweak the minimum and maximum processor states on your Windows PC, only to find them hidden? Or perhaps you want to hide the options to prevent others from tampering with them?

 Whichever you're trying to do, we're here to help by showing you how to add or remove them in the Power Options menu.

## How to Show or Hide the Minimum or Maximum Processor State Using Command Prompt

 To use Command Prompt to show or hide these power states, press**Win + R** to open Windows Run. Then, enter**cmd** in the text box and hit the**Enter** key on your keyboard. You can also use one of the many [ways to open the Command Prompt on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .

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

 You can also show or hide these options using the Registry Editor. However, before you do so, create a restore point as a backup in case you make a mistake and need to return your Windows computer to a previously-working state. Check out [how to create a restore point in Command Prompt](https://www.makeuseof.com/windows-create-restore-point-command-prompt-powershell/) for more information.

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
<li><a href="https://win11.techidaily.com/guide-accessing-windows-11s-security-settings/"><u>Guide: Accessing Windows 11'S Security Settings</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-setting-up-bings-chat-for-windows-11-users/"><u>Streamline Setting Up Bing's Chat for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-the-power-of-java-sdk-on-windows-11/"><u>Unleashing the Power of Java SDK on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-distinctions-of-windows-terminal-vs-powershell/"><u>Unraveling The Distinctions of Windows Terminal Vs. PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-tracking-and-managing-network-data-using-netstat-in-win11/"><u>Master the Art of Tracking and Managing Network Data Using Netstat in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/system-fixes-for-error-0x800700e1-in-windows-11/"><u>System Fixes for Error 0X800700E1 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-recurring-audiotrack-flaw-the-fix-for-code-9999/"><u>Tackling Windows' Recurring Audiotrack Flaw: The Fix for Code 9999</u></a></li>
<li><a href="https://win11.techidaily.com/inside-the-windows-world-crafting-and-examining-system-data/"><u>Inside the Windows World: Crafting and Examining System Data</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-password-policy-setting-new-limit-post-failed-logins/"><u>Revamping Password Policy: Setting New Limit Post Failed Logins</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-saving-hurdles-with-steps-to-fix-pubg/"><u>Overcoming Saving Hurdles with Steps to Fix PUBG</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/crafting-visual-wonders-home-made-effects-demystified-for-2024/"><u>Crafting Visual Wonders  Home-Made Effects Demystified for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-wpt-file-electronically-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to sign .wpt file electronically</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-best-budget-tiktok-cuts-and-enhancements-for-macs/"><u>2024 Approved  Best Budget TikTok Cuts and Enhancements for Macs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/game-changing-displays-the-creme-de-la-creme-of-4k-monitors/"><u>Game-Changing Displays  The Crème De La Crème of 4K Monitors</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-to-create-datamoshing-effect-to-your-footage-in-after-effects-for-2024/"><u>New How to Create Datamoshing Effect to Your Footage in After Effects for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-masterclass-softening-auditory-peaks-gently-in-logic-pro/"><u>2024 Approved  Masterclass  Softening Auditory Peaks Gently in Logic Pro</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-tales-best-yt-storytellers-for-23/"><u>Top Tales  Best YT Storytellers for '23</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-honor-90-gt-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-asus-rog-phone-8-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-your-apple-iphone-se-apple-id-on-macbook-by-drfone-ios/"><u>How To Change Your Apple iPhone SE Apple ID on MacBook</u></a></li>
</ul></div>
