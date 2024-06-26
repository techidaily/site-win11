---
title: Restoring Missing Thermal Policy in Windows Environment
date: 2024-06-25T09:46:40.831Z
updated: 2024-06-26T09:46:40.831Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Missing Thermal Policy in Windows Environment
excerpt: This Article Describes Restoring Missing Thermal Policy in Windows Environment
keywords: Thermal Policy Restore,Windows Heat Settings,Policy Policy Revival,Thermal Management Fix,Window Temperature Control,Policies Recovery Guide,System Temp Regulation
thumbnail: https://thmb.techidaily.com/29d02750ad0cb057d82cf1dca19da27d5429074e0ee73dae3abc4f97673bc3bc.jpg
---

## Restoring Missing Thermal Policy in Windows Environment

 Normally, you should be able to find and set the system cooling policy in the Power Options menu. However, if you find that it's missing, you can bring it back using PowerShell or by making a simple registry tweak.

Here’s how to do that.

## How to Fix a Missing System Cooling Policy Using PowerShell

 For this method, start by pressing**Win + S** to bring up Windows search. Type**powershell** in the search box and click on**Windows PowerShell** in the search results.

 Next, enter the below command in PowerShell and then hit the**Enter** key to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F -ATTRIB_HIDE`

 Now you can go ahead and set the policy. If you need a refresher on how to do that, please read our guide on[what the Windows system cooling policy is and how to set it](https://www.makeuseof.com/what-is-the-system-cooling-policy-on-windows-and-how-do-you-set-it/) .

![Power Options menu on Windows with the System cooling policy expanded](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-options-windows-system-cooling.jpg)

 If you want to hide it again after you’ve set it, you can enter the following command and then press**Enter** to run it:

`powercfg -attributes SUB_PROCESSOR 94D3A615-A899-4AC5-AE2B-E4D8F634367F +ATTRIB_HIDE`

 If you go back to the Power Options menu, you’ll find that it’s gone.

## How to Fix a Missing System Cooling Policy Using the Windows Registry

 Another way to fix the system cooling policy missing from Power Options is by editing the Windows Registry. Before you proceed, please make a copy of it so you have something to restore if something goes wrong. To do that please read our guide on[how to backup and restore the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) .

 Next, click on an empty part of the desktop and select**New > Text document** and name it**add-system-cooling-policy.reg** . You’ve basically[created a registry file on Windows](https://www.makeuseof.com/windows-registry-file-guide/) here.

![creating a text document on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/creating-text-doc-windows-11.jpg)

In the text document, enter the following code:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000002`

 Save the file by clicking**File > Save** . Next, double-click on the registry file and then click**Yes** on the UAC prompt. In the pop-up, click**Yes** to merge the keys and values in the registry file with the Windows Registry.

![message to continue merging a registry file with the windows registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/message-continue-merge-reg-gile.jpg)

 You should now see the system cooling policy in the Power Options menu.

 To remove the system cooling policy again after you’ve made your changes, create another registry file named**add-system-cooling-policy.reg** . Then, paste the below text into the document and save it:

`Windows Registry Editor Version 5.00[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\54533251-82be-4824-96c1-47b60b740d00\94d3a615-a899-4ac5-ae2b-e4d8f634367f]"Attributes"=dword:00000001`

 Once you run this file, the system cooling policy will be hidden again in the Power Options menu.

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
<li><a href="https://win11.techidaily.com/reclaim-your-lost-windows-secrets-for-restoring-hidden-panes-on-win-1011-with-ease/"><u>Reclaim Your Lost Windows! Secrets for Restoring Hidden Panes on Win 10/11 with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-stop-discord-initial-launch-and-searching-at-boot/"><u>Techniques: Stop Discord Initial Launch & Searching at Boot</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-and-restoring-faulty-media-playback/"><u>Resetting and Restoring Faulty Media Playback</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-an-idle-windows-control-panel/"><u>Solutions for an Idle Windows Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-swiftly-address-roblox-error-262/"><u>How to Swiftly Address Roblox Error 262</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-gaming-displays-from-going-opaque-on-win-os/"><u>Preventing Gaming Displays From Going Opaque on WIN OS</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-fixing-microsoft-store-installation-errors/"><u>Steps for Fixing Microsoft Store Installation Errors</u></a></li>
<li><a href="https://win11.techidaily.com/quick-insights-for-placement-of-software-shortcuts-on-taskbar/"><u>Quick Insights for Placement of Software Shortcuts on Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-lan-gaming-challenges-on-pc-winsminecraft/"><u>Overcoming LAN Gaming Challenges on PC, WinsMinecraft</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unresponsive-windows-11-printer-ports-and-devices/"><u>Tackling Unresponsive Windows 11 Printer Ports & Devices</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-vivo-s17t-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Vivo S17t? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unexpected-vertical-tilt-in-instagram-vids-why/"><u>[New] Unexpected Vertical Tilt in Instagram Vids? Why?</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-the-ultimate-list-top-10-intro-creator-tools-online-free-and-paid/"><u>New In 2024, The Ultimate List Top 10 Intro Creator Tools Online Free & Paid</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-master-the-art-of-social-media-success-with-these-10-facebook-tips/"><u>In 2024, Master the Art of Social Media Success with These 10 Facebook Tips</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/discover-the-top-7-free-youtube-tag-extractor-vendors/"><u>Discover the Top 7 Free YouTube Tag Extractor Vendors</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-insights-into-instagram-video-constraint/"><u>[New] Insights Into Instagram Video Constraint</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-unveiling-the-ideal-youtube-subset-of-viewers/"><u>In 2024, Unveiling the Ideal YouTube Subset of Viewers</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/the-fastest-way-to-rotate-a-video-tips-and-tricks-for-2024/"><u>The Fastest Way to Rotate a Video Tips and Tricks for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-top-video-invitation-creators-for-mobile-devices/"><u>In 2024, Top Video Invitation Creators for Mobile Devices</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-twit-favorites-of-the-year-amazon-primes-peak-series/"><u>2024 Approved  Twit-Favorites of the Year  Amazon Prime's Peak Series</u></a></li>
</ul></div>
