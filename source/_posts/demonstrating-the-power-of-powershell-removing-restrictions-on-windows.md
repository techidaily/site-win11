---
title: "Demonstrating the Power of PowerShell: Removing Restrictions on Windows"
date: 2024-06-25T11:34:26.787Z
updated: 2024-06-26T11:34:26.787Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Demonstrating the Power of PowerShell: Removing Restrictions on Windows"
excerpt: "This Article Describes Demonstrating the Power of PowerShell: Removing Restrictions on Windows"
keywords: PowerShell Mastery,Unlock Windows Potential,PowerShell Enhancement,Overcoming OS Limitations,Elevate System Management,Streamline Server Control,Optimize OS Functionality
thumbnail: https://thmb.techidaily.com/ef0c500c1ff8cdea11d6b2ce7132e969a27a23353363cc6a48d15e2d1d290c96.jpg
---

## Demonstrating the Power of PowerShell: Removing Restrictions on Windows

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
<li><a href="https://win11.techidaily.com/how-to-fix-windows-this-device-is-being-used-by-another-application-audio-error/"><u>How to Fix Windows' This Device Is Being Used by Another Application Audio Error</u></a></li>
<li><a href="https://win11.techidaily.com/open-windows-ease-of-access-center-top-5-tactics/"><u>Open Windows Ease of Access Center: Top 5 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unwanted-keystrokes-during-typing/"><u>Preventing Unwanted Keystrokes During Typing</u></a></li>
<li><a href="https://win11.techidaily.com/1719271419179-navigate-through-windows-woes-with-simple-fixes/"><u>Navigate Through Windows Woes with Simple Fixes!</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-rectify-ge-share-function-failures/"><u>Guide to Rectify GE Share Function Failures</u></a></li>
<li><a href="https://win11.techidaily.com/winoses-mastery-of-local-policies-applied-to-single-users/"><u>WinOSes: Mastery of Local Policies Applied to Single Users</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-interface-effective-process-filtering-and-customizing-themes-in-w11/"><u>Navigating the Interface: Effective Process Filtering & Customizing Themes in W11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-black-screen-during-games-on-win/"><u>Resolving Black Screen During Games on WIN</u></a></li>
<li><a href="https://win11.techidaily.com/winirq-fixing-killer-soundsystem-problems/"><u>WinIRQ: Fixing Killer Soundsystem Problems</u></a></li>
<li><a href="https://win11.techidaily.com/must-know-factors-a-consumers-checklist-for-buying-a-win-laptop/"><u>Must-Know Factors: A Consumer's Checklist for Buying a Win Laptop</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-simplifying-the-process-of-creating-a-high-quality-rss-feed/"><u>2024 Approved  Simplifying the Process of Creating a High-Quality RSS Feed</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-mastering-the-art-of-cinematic-content-on-instagram-for-2024/"><u>[Updated] Mastering the Art of Cinematic Content on Instagram for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-top-10-hindi-video-translators-with-step-by-step-guidance/"><u>Updated Top 10 Hindi Video Translators with Step-by-Step Guidance</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-are-youtube-engagement-strategies-justifiable/"><u>2024 Approved  Are YouTube Engagement Strategies Justifiable?</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-in-2024-movie-magic-maker-upgrade-your-home-videos-to-hollywood-quality/"><u>Updated In 2024, Movie Magic Maker Upgrade Your Home Videos to Hollywood Quality</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-stop-the-frenzy-fixing-a-mistaken-tiktok-reload/"><u>In 2024, Stop the Frenzy – Fixing a Mistaken TikTok Reload</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-redesign-instant-twitter-video-view/"><u>[Updated] Redesign Instant Twitter Video View</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagrams-top-25-leaders-in-digital-influence-for-2024/"><u>Instagram's Top 25 Leaders in Digital Influence for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-streamlined-techniques-for-transforming-vids-on-pinterest-to-mp3s/"><u>In 2024, Streamlined Techniques for Transforming Vids on Pinterest to MP3s</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/budget-friendly-recorder-choices-for-youtube-vloggers/"><u>Budget-Friendly Recorder Choices for YouTube Vloggers</u></a></li>
</ul></div>
