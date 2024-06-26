---
title: Tapping Into Windows Settings for CPU States
date: 2024-06-25T11:28:27.789Z
updated: 2024-06-26T11:28:27.789Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tapping Into Windows Settings for CPU States
excerpt: This Article Describes Tapping Into Windows Settings for CPU States
keywords: Windows CPUSet,CPU States Control,Manage Windows Cpu,Accessing Windows Cpustates,Optimizing Windows CPUs,Cpu Settings Window,Windows CPU Management
thumbnail: https://thmb.techidaily.com/e663bf23b6887cb8279b82d66477ecb71e4a937f5292de883673cace9e11db92.jpg
---

## Tapping Into Windows Settings for CPU States

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
<li><a href="https://win11.techidaily.com/stalling-windows-auto-updates-four-methods/"><u>Stalling Windows Auto-Updates: Four Methods</u></a></li>
<li><a href="https://win11.techidaily.com/solving-rdp-connectivity-issues-in-win10plus/"><u>Solving RDP Connectivity Issues in Win10+</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-not-found-the-ultimate-list/"><u>Overcoming Windows Not Found: The Ultimate List</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-and-resolving-read-only-windows-folder-problems/"><u>Navigating and Resolving Read-Only Windows Folder Problems</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-correction-processes-for-faulty-win11-registry-data/"><u>Guiding Through Correction Processes for Faulty Win11 Registry Data</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-strategies-for-windows-pct-success/"><u>Top 4 Strategies for Windows PCT Success</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-xbox-live-games-access-failures-on-windows-os/"><u>Troubleshooting: Xbox Live Games Access Failures on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/handling-camera-allocation-conflict-on-windows-os/"><u>Handling Camera Allocation Conflict on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/revive-the-shield-5-key-fixes-for-windows-family-protection/"><u>Revive the Shield: 5 Key Fixes for Windows Family Protection</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-win32keygen-threat-symptoms-damage-and-removal-guide/"><u>Unraveling Win32/Keygen Threat: Symptoms, Damage, & Removal Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-infinix-note-30-5g-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Infinix Note 30 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-investigating-new-horizons-past-manycams-realm/"><u>[Updated] Investigating New Horizons Past ManyCam's Realm</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-beginners-guide-to-solo-youtube-broadcasting-from-yourphone/"><u>[New] Beginner's Guide to Solo YouTube Broadcasting From Yourphone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-oppo-a59-5g-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Oppo A59 5G to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-showmore-screen-recorder-review-2023/"><u>[New] 2024 Approved  ShowMore Screen Recorder Review 2023</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-vivo-s17-pro-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Vivo S17 Pro | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-ultimate-screenshot-saver-windows-11-version-for-2024/"><u>[Updated] Ultimate Screenshot Saver  Windows 11 Version for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-creating-ootd-masterpieces-for-tiktok-with-macos/"><u>[New] Creating OOTD Masterpieces for TikTok with MacOS</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-vimeo-create-how-to-edit-videos-on-vimeo-for-free-for-2024/"><u>[Updated] Vimeo Create  How to Edit Videos on Vimeo for Free for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-constructing-chat-hangout-zones-on-whatsapp/"><u>[New] Constructing Chat Hangout Zones on WhatsApp</u></a></li>
</ul></div>
