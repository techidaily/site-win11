---
title: How to Fix a Missing System Cooling Policy on Windows
date: 2024-06-25T11:39:56.127Z
updated: 2024-06-26T11:39:56.127Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix a Missing System Cooling Policy on Windows
excerpt: This Article Describes How to Fix a Missing System Cooling Policy on Windows
keywords: Windows Cooling Fix,System Policy Repair,Cooling Policy Missing,Fix System Temp Error,Windows Heat Regulation,Missing Cool Policy Fix,Policy Setter for Windows
thumbnail: https://thmb.techidaily.com/e3e57dc288a15eebc6a087ce47534d889b154128f1cec9b763b947b83648c7c9.jpg
---

## How to Fix a Missing System Cooling Policy on Windows

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
<li><a href="https://win11.techidaily.com/fixing-video-buffer-issues-streamlined-vlc-on-pc/"><u>Fixing Video Buffer Issues: Streamlined VLC on PC</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-video-reset-error-on-windows-systems/"><u>Dealing with Video Reset Error on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-a-blank-login-screen-in-windows-11-and-11/"><u>How to Fix a Blank Login Screen in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/learn-9-methods-to-access-and-tweak-windows-sound-settings/"><u>Learn 9 Methods to Access and Tweak Windows Sound Settings</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-windows-photo-management-tools-an-essential-guide/"><u>Top 7 Windows Photo Management Tools: An Essential Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enter-the-inner-workings-of-your-pc/"><u>Enter the Inner Workings of Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-accessing-cloud-drives-from-windows-drive-letters/"><u>Effortlessly Accessing Cloud Drives: From Windows Drive Letters</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-code-0xc00d36b4-in-windows-11/"><u>Troubleshooting Error Code 0xC00D36B4 in Windows 11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-revolutionize-your-online-gaming-with-morphvox-a-voice-changers-handbook/"><u>Updated Revolutionize Your Online Gaming with Morphvox – A Voice Changers Handbook</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-dare-to-be-noteworthy-top-30-innovative-tiktok-usernames/"><u>2024 Approved  Dare to Be Noteworthy  Top 30 Innovative TikTok Usernames</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-breakthrough-techniques-in-youtube-content-creation/"><u>[New] In 2024, Breakthrough Techniques in YouTube Content Creation</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-leverage-your-influence-top-10-igtv-video-tactics-for-brands/"><u>[New] Leverage Your Influence  Top 10 IGTV Video Tactics for Brands</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-free-high-quality-youtube-banner-samples-inside/"><u>[Updated] 2024 Approved  Free High-Quality YouTube Banner Samples Inside!</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-replicating-your-best-self-with-finesse-on-tiktok/"><u>In 2024, Replicating Your Best Self with Finesse on TikTok</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-start-at-vectors-beginning-a-short-overview-of-forms-and-tools/"><u>[Updated] Start at Vector's Beginning  A Short Overview of Forms & Tools</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-elevating-youtube-consumption-strategies-for-organizing-videos-for-future-viewing-for-2024/"><u>[New] Elevating YouTube Consumption  Strategies for Organizing Videos for Future Viewing for 2024</u></a></li>
</ul></div>
