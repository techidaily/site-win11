---
title: Liberating Your Computer's Files Using PowerShell Skills
date: 2024-12-06T08:34:29.220Z
updated: 2024-12-12T17:55:51.085Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Liberating Your Computer's Files Using PowerShell Skills
excerpt: This Article Describes Liberating Your Computer's Files Using PowerShell Skills
keywords: File Liberation PS,PowerSavePC,PC Data Cleanup,PS Free Files,Secure File Access,Data Extraction PS,Optimize Computer
thumbnail: https://thmb.techidaily.com/60aeb73e6646ca7cba89b069f503754c9115c11cb30cdb412a437151bb1d88f5.jpg
---

## Liberating Your Computer's Files Using PowerShell Skills

 So you’ve downloaded files onto a directory on your PC, but Windows doesn’t trust them? This is understandable because some files from the internet can harm your computer, but what if you know for sure that the files are safe? Luckily there’s an easy PowerShell command you can use to unblock all of them.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How Do I Unblock Multiple Files Using PowerShell on Windows?

 You can easily unblock a file by right-clicking on it and going to**Properties** — If you're on Windows 11, you'll need to click**Show more options** first before you can see the**Properties** option in the context menu. And once you're there, select the**General** tab and tick**Unblock** at the bottom in the**Security** section.

![unblocking a file in Properties on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unblock-file-properties-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 But what if you have more than one file you need to unblock? Doing this one by one can get tedious. Alternatively, you can execute a single PowerShell command to unblock multiple files in a directory. Here is the command structure you need to use:

`dir [path] | unblock-file -confirm`

 Just replace**path** in the square brackets with the file path of the directory that has the blocked files. You can grab the file path of the directory by right-clicking on it and selecting**Copy as path** .

![copying file path on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-as-path-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 With the file path handy, follow the instructions below to use the unblock command in PowerShell:

1. Press**Win + S** to open Windows Search.
2. Type**powershell** in the search box and when the program appears in the search results, right-click on it and select**Run as administrator** . For more ways to open it, please read our guide on[ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/) .
3. Enter the unblock command in PowerShell and hit the**Enter** key to run it. This is what it looks like on our computer:  
![entering the unblock file command in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-command.jpg)
4. You will be asked to confirm each file you want to unblock, so type either**Y** for**Yes** or**N** for**No** and hit the**Enter** key. This confirmation step is due to the**\-confirm** portion of the command. It is completely optional, and you can omit it or type**A** to confirm all the files in the directory.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![confirming files to unblock in PowerShell on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/power-shell-unblock-files-confirm.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 There’s a way you can tell Windows to always trust files you download from the internet. To do that, please read our guide on[how to stop Windows 10 from blocking your downloaded files](https://www.makeuseof.com/stop-windows-10-from-blocking-your-downloaded-files/) . The instructions in the tutorial use the Registry Editor and Local Group Policy Editor, so they should also work on Windows 11.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-essential-tips-for-harnessing-movie-maker-in-windows-8-systems/"><u>[New] 2024 Approved Essential Tips for Harnessing Movie Maker in Windows 8 Systems</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-essential-web-destinations-for-free-background-scores-bgm/"><u>2024 Approved Essential Web Destinations for Free Background Scores (BGM)</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-latest-pl2303-usb-to-serial-adapter-drivers-for-windows-pcs-download-now/"><u>Get the Latest PL2303 USB-to-Serial Adapter Drivers for Windows PCs - Download Now!</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-any-htc-u23-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any HTC U23 Phone Password Using Emergency Call</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-best-practices-for-documenting-chat-history-on-whatsapp/"><u>In 2024, Best Practices for Documenting Chat History on WhatsApp</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-custom-snapping-windows-powertoys-guide/"><u>Mastering Custom Snapping: Windows' PowerToys Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-control-of-file-deletion-prompts/"><u>Mastering the Control of File Deletion Prompts</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-for-missing-devices-from-razers-synapse-in-windows/"><u>Quick Fix for Missing Devices From Razer's Synapse in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/regain-lost-speaker-level-settings-post-system-changes/"><u>Regain Lost Speaker Level Settings Post-System Changes</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-guide-how-to-fix-davinci-resolve-not-launching-in-windows/"><u>Troubleshooting Guide: How to Fix DaVinci Resolve Not Launching in Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/universal-unlock-pattern-for-realme-11-pro-by-drfone-android/"><u>Universal Unlock Pattern for Realme 11 Pro</u></a></li>
</ul></div>

