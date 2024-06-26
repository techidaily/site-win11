---
title: Powerful Techniques for Unlocking Your System' Writable Files
date: 2024-06-25T09:51:36.138Z
updated: 2024-06-26T09:51:36.138Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Powerful Techniques for Unlocking Your System' Writable Files
excerpt: This Article Describes Powerful Techniques for Unlocking Your System' Writable Files
keywords: File Access Mastery,Write Lock Solutions,System File Editors,Power Unlocking Tools,Secure Write Permissions,Techniques for File Control,User-Defined Writeability
thumbnail: https://thmb.techidaily.com/41df33583a82ea2d9923ca08fb1de828ddad2dc59980553349e15164e2adbb30.jpg
---

## Powerful Techniques for Unlocking Your System' Writable Files

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

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
<li><a href="https://win11.techidaily.com/masterful-maneuvers-to-navigate-stalled-windows-install-steps/"><u>Masterful Maneuvers to Navigate Stalled Windows Install Steps</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-window-pc-always-unlocked/"><u>Keep Your Window PC Always Unlocked</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-stalker-unveiled-preventive-measures-against-wacatacbml/"><u>The Silent Stalker Unveiled: Preventive Measures Against Wacatac.B!ml</u></a></li>
<li><a href="https://win11.techidaily.com/from-chaos-to-clarity-manage-all-open-windows-win1110/"><u>From Chaos to Clarity: Manage All Open Windows (Win11/10)</u></a></li>
<li><a href="https://win11.techidaily.com/from-emulator-to-operating-system-windows-for-steam-deck/"><u>From Emulator to Operating System: Windows for Steam Deck</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-see-what-is-taking-up-too-much-disk-space-on-your-windows-pc/"><u>How to See What Is Taking Up Too Much Disk Space on Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/pro-guide-how-to-locate-and-setup-shortcuts-near-win11s-power-icon/"><u>Pro Guide: How to Locate & Setup Shortcuts Near Win11's Power Icon</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-efficiency-utilizing-windows-11s-taskbar-search/"><u>Dive Into Efficiency: Utilizing Windows 11'S Taskbar Search</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-best-image-aspect-ratio-converters-on-the-web/"><u>New 2024 Approved Best Image Aspect Ratio Converters on the Web</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-lava-blaze-pro-5g-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Lava Blaze Pro 5G to Outlook | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-something-you-should-know-about-twistedwave-audio-editor/"><u>In 2024, Something You Should Know About TwistedWave Audio Editor</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-elevate-your-tiktok-experience-with-proficient-voicework/"><u>In 2024, Elevate Your TikTok Experience with Proficient Voicework</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-the-ultimate-blueprint-for-successful-discord-live-streams/"><u>[Updated] In 2024, The Ultimate Blueprint for Successful Discord Live Streams</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-the-leading-voice-alteration-and-production-software-for-aspiring-sopranos-and-tenors-for-2024/"><u>New The Leading Voice Alteration and Production Software for Aspiring Sopranos & Tenors for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/5-quick-methods-to-bypass-realme-v30-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Realme V30 FRP</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-samsung-galaxy-a14-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Samsung Galaxy A14 4G | Dr.fone</u></a></li>
</ul></div>
