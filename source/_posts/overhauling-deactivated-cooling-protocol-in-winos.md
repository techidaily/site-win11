---
title: Overhauling Deactivated Cooling Protocol in WinOS
date: 2024-11-25T01:02:49.632Z
updated: 2024-11-27T19:59:27.282Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overhauling Deactivated Cooling Protocol in WinOS
excerpt: This Article Describes Overhauling Deactivated Cooling Protocol in WinOS
keywords: WinOS Cooling Overhaul,Deactivate OS Cooling Fix,Revitalize Windows Cooling,Cooling System Overhaul OS,Reinstating Windows Cooling,Enhanced WinOS Temp Control,Optimizing Deactivated Cooling Windows
thumbnail: https://thmb.techidaily.com/e46847f4d730c4e71d01b69ffbbf4867ec32380919d66b5ed5af5b5df6bd28ce.jpg
---

## Overhauling Deactivated Cooling Protocol in WinOS

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Bringing Back the System Cooling Policy on Windows

 Now that the system cooling policy has returned you can tweak it to your liking. We have even shown you how to hide it again in case you don’t want others messing with it. If these methods don’t work, you might have another problem with your computer.

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
<li><a href="https://article-posts.techidaily.com/new-2024-approved-premium-ios-photo-and-video-shows-from-ix-to-ios12/"><u>[New] 2024 Approved Premium iOS Photo & Video Shows From IX to IOS12</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-groundbreaking-6-modern-mc-residentials-for-2024/"><u>[New] Groundbreaking 6 Modern MC Residentials for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-5-tips-for-enhancing-photo-colors-effortlessly/"><u>[Updated] 5 Tips for Enhancing Photo Colors Effortlessly</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/best-source-to-get-dell-network-adapter-driver-for-win7-operating-system/"><u>Best Source to Get Dell Network Adapter Driver for Win7 Operating System</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-management-of-terminals-focus-mode-entryexit-rituals/"><u>Effortless Management of Terminal's Focus Mode Entry/Exit Rituals</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-freeze-frames-at-games-start/"><u>Eliminating Freeze Frames at Game's Start</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-network-fluctuations-in-steam-streams/"><u>Fixing Network Fluctuations in Steam Streams</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-infinix-note-30-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Infinix Note 30 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ink-your-window-world-windows-1011-art-guide/"><u>Ink Your Window World: Windows 10/11 Art Guide</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-galaxy-with-windows-11-a-dex-users-guide/"><u>Integrating Galaxy With Windows 11: A DeX User's Guide</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-your-window-11-capabilities-quickly/"><u>Maximize Your Window 11 Capabilities Quickly</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/no-remote-no-problem-guide-to-navigate-roku-by-other-means/"><u>No Remote, No Problem: Guide to Navigate Roku by Other Means</u></a></li>
<li><a href="https://tech-haven.techidaily.com/siri-or-chatgpt-discover-what-sets-them-apart-in-voice-assistant-technology/"><u>Siri or ChatGPT? Discover What Sets Them Apart in Voice Assistant Technology</u></a></li>
<li><a href="https://win11.techidaily.com/sync-up-your-system-to-see-sd-card-again-in-windows-explorer/"><u>Sync Up Your System to See SD Card Again in Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/the-costly-shortcuts-of-substandard-windows-auth-codes-explored/"><u>The Costly Shortcuts of Substandard Windows Auth Codes Explored</u></a></li>
<li><a href="https://win11.techidaily.com/time-capsule-exploration-file-history-in-windows-11/"><u>Time Capsule Exploration: File History in Windows 11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/twist-and-tell-the-art-of-angling-your-videos-for-instagram-audiences-for-2024/"><u>Twist & Tell The Art of Angling Your Videos for Instagram Audiences for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-infinix-zero-5g-2023-turbo-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Infinix Zero 5G 2023 Turbo | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/update-your-blue-snowball-drivers-on-windows-a-step-by-step-guide-for-enhanced-connectivity/"><u>Update Your Blue Snowball Drivers on Windows - A Step-by-Step Guide for Enhanced Connectivity</u></a></li>
</ul></div>

