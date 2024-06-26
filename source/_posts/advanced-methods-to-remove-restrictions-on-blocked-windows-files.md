---
title: Advanced Methods to Remove Restrictions on Blocked Windows Files
date: 2024-06-25T10:29:34.048Z
updated: 2024-06-26T10:29:34.048Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Advanced Methods to Remove Restrictions on Blocked Windows Files
excerpt: This Article Describes Advanced Methods to Remove Restrictions on Blocked Windows Files
keywords: Unblock Windows Files,Eliminate File Blocking Windows,Clear Restriction Windows Files,Bypass Blocked Windows Content,Override Windows File Limits,Disable Windows Filters,Freeze Windows Permissions
thumbnail: https://thmb.techidaily.com/cbb1e3102bf892cff8d3ec0a8653b920867c497d12f1be8e2ab6e11d350e85ee.jpg
---

## Advanced Methods to Remove Restrictions on Blocked Windows Files

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
<li><a href="https://win11.techidaily.com/resuming-lost-link-fixes-for-disconnected-google-drive-on-pc/"><u>Resuming Lost Link: Fixes for Disconnected Google Drive on PC</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-0x800713f-problem-repair-windows-11s-mail-service/"><u>Tackling 0X800713F Problem: Repair Windows 11'S Mail Service</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-speech-recognition-launch-failures-in-windows-os/"><u>Overcoming Speech Recognition Launch Failures in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-error-e8024002e-for-smooth-updates/"><u>Overcoming Error E:8024002E for Smooth Updates</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-to-counteract-accelerated-mice/"><u>Adjusting Windows to Counteract Accelerated Mice</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-infinitely-stop-microsoft-defender-in-windows/"><u>How to Infinitely Stop Microsoft Defender in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win11-addressing-inaudible-wireless-speaker-issues/"><u>Win11: Addressing Inaudible Wireless Speaker Issues</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-sound-error-on-audacity-in-win1011/"><u>Resolving Sound Error on Audacity in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-email-notifications-glitches-on-windows-devices/"><u>Addressing Email Notifications Glitches on Windows Devices</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-classroom-visuals-cutting-edge-video-edits-for-teachers/"><u>[Updated] Classroom Visuals  Cutting Edge Video Edits for Teachers</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-tecno-spark-10-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Tecno Spark 10 5G | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-redmi-a2plus-support-mkv-video-files-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Does Redmi A2+ support MKV video files?</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-6-to-other-iphone-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 6 to other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/metaverse-bonding-discovering-the-top-10-shared-games-for-2024/"><u>Metaverse Bonding  Discovering the Top 10 Shared Games for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-peak-content-performance-the-ultimate-list-of-powerful-tiktok-captions/"><u>[Updated] 2024 Approved  Peak Content Performance  The Ultimate List of Powerful TikTok Captions</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-ranking-the-finest-five-screen-snipers-in-windows/"><u>In 2024, Ranking the Finest Five Screen Snipers in Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/perfect-pictures-quick-pixlr-tricks-for-beginners-for-2024/"><u>Perfect Pictures  Quick Pixlr Tricks for Beginners for 2024</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-how-to-use-capcut-translate-to-transform-video-content-for-2024/"><u>Updated How To Use CapCut Translate to Transform Video Content for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-premium-selection-complimentary-internet-services-for-sound-normalization/"><u>New 2024 Approved Premium Selection Complimentary Internet Services for Sound Normalization</u></a></li>
</ul></div>
