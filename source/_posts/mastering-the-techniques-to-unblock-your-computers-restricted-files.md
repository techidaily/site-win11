---
title: Mastering the Techniques to Unblock Your Computer's Restricted Files
date: 2024-10-14T18:27:35.575Z
updated: 2024-10-15T21:37:58.397Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Techniques to Unblock Your Computer's Restricted Files
excerpt: This Article Describes Mastering the Techniques to Unblock Your Computer's Restricted Files
keywords: File Unlocking Guide,Computer Restricted Access,Remove File Blocks,Fix Restricted Files,Unblock PC Files,Overcoming File Lockout,Techniques for Free Files
thumbnail: https://thmb.techidaily.com/b8679192be865a4926b833c7643d484e4a5289f4dc9b662f4833af51354f1cda.jpg
---

## Mastering the Techniques to Unblock Your Computer's Restricted Files

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  
![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148646/16836" target="_top" id="2148646">
  <img src="//a.impactradius-go.com/display-ad/16836-2148646" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148646/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Now You Know How to Unblock Files You Know Are Safe

 With the instruction above unlocking a bunch of downloaded files in a directory should be easier. Keep in mind that you shouldn’t do this on files you don’t trust. The last thing you want to do is put your Windows PC at risk unnecessarily

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
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-transform-your-tech-for-successful-social-media-livestreams/"><u>[New] In 2024, Transform Your Tech for Successful Social Media Livestreams</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-navigating-voice-modding-on-discord-desktop-and-mobile-edition/"><u>[Updated] 2024 Approved Navigating Voice Modding on Discord Desktop & Mobile Edition</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-thorough-evaluation-of-frozen-snack-playback-devices/"><u>[Updated] 2024 Approved Thorough Evaluation of Frozen Snack Playback Devices</u></a></li>
<li><a href="https://win11.techidaily.com/edges-steady-cycle-managing-on-windows-11/"><u>Edge's Steady Cycle: Managing on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-continuous-tab-integrity-in-explorer/"><u>Ensuring Continuous Tab Integrity in Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-11s-enhanced-data-protection-strategy/"><u>Exploring Windows 11'S Enhanced Data Protection Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/extending-windows-10-shutdown-time-tips-for-active-tasks/"><u>Extending Windows 10 Shutdown Time: Tips for Active Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-fix-a-non-responsive-login-screen-in-windows-1011/"><u>Guide to Fix a Non-Responsive Login Screen in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-stopping-discord-initial-launch-and-updates-on-windows/"><u>Guide: Stopping Discord Initial Launch & Updates on Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-guidelines-for-eliminating-obs-fullscreen-freeze/"><u>In 2024, Guidelines for Eliminating OBS Fullscreen Freeze</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-vivo-y100t-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Vivo Y100t? Look No Further | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mirthful-stream-retriever-review/"><u>In 2024, Mirthful Stream Retriever Review</u></a></li>
<li><a href="https://win-exclusive.techidaily.com/in-depth-comparison-test-of-top-dvd-tools-wonderfox-vs-winx-which-wins/"><u>In-Depth Comparison Test of Top DVD Tools: WonderFox VS WinX - Which Wins?</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-microsoft-edges-steady-backstage-in-win11/"><u>Optimizing Microsoft Edge's Steady Backstage in Win11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/share-wisdom-top-strategies-for-video-sharing-on-instagram-for-2024/"><u>Share Wisdom Top Strategies for Video Sharing on Instagram for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-oneplus-ace-2-pro-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My OnePlus Ace 2 Pro Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
</ul></div>

