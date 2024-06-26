---
title: Powerful Techniques for Unlocking Your System' Writable Files
date: 2024-06-25T11:25:08.092Z
updated: 2024-06-26T11:25:08.092Z
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
<li><a href="https://win11.techidaily.com/connecting-classics-windows-11s-pathway-to-photos-folder/"><u>Connecting Classics: Windows 11'S Pathway to Photos Folder</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-and-customizing-proxies-in-windows-11/"><u>Enabling and Customizing Proxies in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-web-sites-becoming-win-desktops/"><u>The Art of Web Sites Becoming Win Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-accessibility-5-ways-to-open-windows-help-hub/"><u>Enhance Accessibility: 5 Ways to Open Windows Help Hub</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-code-0xc0000142-in-winos/"><u>Resolving Code 0XC0000142 in WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-the-ideal-taskbar-for-your-windows-11-tablet/"><u>Implementing the Ideal Taskbar for Your Windows 11 Tablet</u></a></li>
<li><a href="https://win11.techidaily.com/determining-the-ideal-nearby-networking-method-google-vs-windows/"><u>Determining the Ideal Nearby Networking Method: Google Vs. Windows</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-gopro-quik-worth-it-plus-top-pc-video-editing-alternatives/"><u>New In 2024, GoPro Quik Worth It? Plus, Top PC Video Editing Alternatives</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-unveiling-the-best-voice-to-text-software-for-windows-enthusiasts/"><u>New In 2024, Unveiling the Best Voice-to-Text Software for Windows Enthusiasts</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/easy-steam-recordings-with-team-fortress-2s-latest-update/"><u>Easy Steam Recordings with Team Fortress 2'S Latest Update</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-streamlining-youtube-edits-with-advanced-sony-vegas-techniques/"><u>[New] Streamlining YouTube Edits with Advanced Sony Vegas Techniques</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/how-to-use-vlc-for-professional-screen-recording-for-2024/"><u>How to Use VLC for Professional Screen Recording for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/best-of-the-chill-easy-phone-game-compilation/"><u>Best of the Chill  Easy Phone Game Compilation</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unveiling-best-live-stream-tools-for-gamers/"><u>2024 Approved  Unveiling Best Live-Stream Tools for Gamers</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-jive-and-twist-your-guide-to-popular-simple-tiktok-beats/"><u>[New] 2024 Approved  Jive and Twist  Your Guide to Popular, Simple TikTok Beats</u></a></li>
</ul></div>
