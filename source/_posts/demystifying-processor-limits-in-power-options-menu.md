---
title: Demystifying Processor Limits in Power Options Menu
date: 2024-06-25T10:24:35.113Z
updated: 2024-06-26T10:24:35.114Z
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
<li><a href="https://win11.techidaily.com/sidestep-mandatory-components-not-available-in-win10win11/"><u>Sidestep Mandatory Components Not Available in WIN10/WIN11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-security-basics-in-windows-11-setup/"><u>Restoring Security Basics in Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/3-keyways-to-refresh-file-explorer-in-win1011/"><u>3 Keyways to Refresh File Explorer in WIN10/11</u></a></li>
<li><a href="https://win11.techidaily.com/want-to-use-windows-11-without-bloatware-and-stern-hardware-requirements-try-tiny11/"><u>Want to Use Windows 11 Without Bloatware and Stern Hardware Requirements? Try Tiny11</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-scripting-techniques-upgraded-file-system-interactions/"><u>Advanced Scripting Techniques: Upgraded File System Interactions</u></a></li>
<li><a href="https://win11.techidaily.com/windows-photos-shortcuts-for-the-savvy-editor/"><u>Windows Photos Shortcuts for the Savvy Editor</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-another-app-is-using-the-camera-already-0xa00f4243-error-on-windows/"><u>How to Fix the Another App Is Using the Camera Already 0xA00F4243 Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-past-security-checks-on-your-wins-system/"><u>How to Clear Past Security Checks on Your Wins System</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-unlimited-free-face-creation-top-online-resources/"><u>New Unlimited Free Face Creation Top Online Resources</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-does-purchasing-likes-impact-long-term-success-in-2024/"><u>[New] How Does Purchasing Likes Impact Long-Term Success, In 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-realme-c67-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Realme C67 5G? | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-discovering-the-best-8-bluetooth-audio-processors-for-clear-streaming-sound/"><u>Updated In 2024, Discovering the Best 8 Bluetooth Audio Processors for Clear Streaming Sound</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-leveraging-seo-in-youtube-a-title-and-tags-guidebook/"><u>[New] Leveraging SEO in Youtube  A Title & Tags Guidebook</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-the-ultimate-technique-for-uniform-audio-amplitude-in-vlc-a-detailed-walkthrough/"><u>New The Ultimate Technique for Uniform Audio Amplitude in VLC A Detailed Walkthrough</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-the-giggle-factor-comparing-humor-in-tiktok-and-snapchat-videos/"><u>In 2024, The Giggle Factor  Comparing Humor in TikTok and Snapchat Videos</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/snapchat-chronicles-unveiled-an-array-of-more-than-a-hundred-inspiring-title-concepts/"><u>Snapchat Chronicles Unveiled  An Array of More Than a Hundred Inspiring Title Concepts</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/exploring-adsense-revenue-streams-on-youtube-for-every-1k-watcher/"><u>Exploring AdSense Revenue Streams on YouTube for Every 1K Watcher</u></a></li>
</ul></div>
