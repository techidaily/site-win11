---
title: "Overcoming Access Barriers in Windows: A PowerShell Solution"
date: 2024-10-22T21:03:57.930Z
updated: 2024-10-27T00:15:14.542Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Access Barriers in Windows: A PowerShell Solution"
excerpt: "This Article Describes Overcoming Access Barriers in Windows: A PowerShell Solution"
keywords: Overcoming Access Issues,Access Solutions Windows,PowerShell Accessibility,Bypassing OS Barriers,Enhanced Window Access,Easy Windows Entry,PowerAccess for PCs
thumbnail: https://thmb.techidaily.com/70c37a7401073f1bcbf47eb7a020f3d12c21a20e9f862ecf54abef66ad7c8a53.jpg
---

## Overcoming Access Barriers in Windows: A PowerShell Solution

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137229/26400" target="_top" id="2137229">
  <img src="//a.impactradius-go.com/display-ad/26400-2137229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137229/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-beyond-vidcon-a-guide-to-the-most-important-youtube-events/"><u>[Updated] 2024 Approved Beyond VidCon - A Guide to the Most Important YouTube Events</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-journey-into-cinematic-precision-with-windows-high-dynamic-range-support/"><u>[Updated] In 2024, Journey Into Cinematic Precision with Windows High-Dynamic Range Support</u></a></li>
<li><a href="https://win11.techidaily.com/compromised-corecipher-evaluate-dont-rush-to-replace/"><u>Compromised CoreCipher? Evaluate, Don't Rush to Replace</u></a></li>
<li><a href="https://fox-tls.techidaily.com/get-video-conversion-downloads-mp4-mov-avi-effortlessly-using-myvidster/"><u>Get Video Conversion Downloads (MP4, MOV, AVI) Effortlessly Using MyVidster.</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-on-apple-iphone-se-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data on Apple iPhone SE? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-dism-commands-to-repair-windows-11-system-images/"><u>How to Use DISM Commands to Repair Windows 11 System Images</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-pitch-perfect-crafting-characters-spoken-language/"><u>In 2024, Pitch Perfect Crafting Characters' Spoken Language</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/lightroom-enthusiasts-ultimate-toolkit-the-1-list-of-top-10-luts-for-2024/"><u>LightRoom Enthusiast’s Ultimate Toolkit The #1 List of Top 10 LUTs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/make-your-window-interface-unforgettable-using-winbubble-tips/"><u>Make Your Window Interface Unforgettable Using WinBubble Tips</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-your-pc-with-these-4-win11-god-mode-tricks/"><u>Maximize Your PC with These 4 Win11 God Mode Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/quick-start-how-to-set-up-outlook-preview-on-windows-1011/"><u>Quick Start: How to Set Up Outlook Preview on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-blue-screen-code-0xc0000142/"><u>Rectifying Blue Screen Code 0XC0000142</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/seeing-beyond-our-elite-rankings-of-camera-lenses-1-10/"><u>Seeing Beyond Our Elite Rankings of Camera Lenses #1-10</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ise-of-a-monetary-maestro-ajeys-youtube-earnings-story-for-2024/"><u>The Rise of a Monetary Maestro Ajey's YouTube Earnings Story for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/troubleshooting-pc-issues-for-sons-of-the-forest-expert-tips-and-tricks/"><u>Troubleshooting PC Issues for 'Sons of the Forest': Expert Tips and Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-best-matches-8-superb-video-editing-apps/"><u>Win11’s Best Matches: 8 Superb Video Editing Apps</u></a></li>
<li><a href="https://win11.techidaily.com/windows-upgrade-wisdom-efficiently-shifting-your-pcs-programming/"><u>Windows Upgrade Wisdom: Efficiently Shifting Your PC's Programming</u></a></li>
</ul></div>

