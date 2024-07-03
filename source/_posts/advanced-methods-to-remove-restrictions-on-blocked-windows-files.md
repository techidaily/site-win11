---
title: Advanced Methods to Remove Restrictions on Blocked Windows Files
date: 2024-06-25T11:37:40.469Z
updated: 2024-06-26T11:37:40.469Z
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
<li><a href="https://win11.techidaily.com/master-the-art-of-tracking-and-managing-network-data-using-netstat-in-win11/"><u>Master the Art of Tracking and Managing Network Data Using Netstat in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-system-palette-placing-this-pc-on-screen/"><u>Personalized System Palette: Placing 'This PC' On Screen</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-handle-no-device-drivers-issue-in-system-setup/"><u>Steps to Handle 'No Device Drivers' Issue in System Setup</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-resolving-errors-in-windows-installer/"><u>Understanding and Resolving Errors in Windows Installer</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-onedrive-servers-errors-easily/"><u>Navigating Through OneDrive Servers Errors Easily</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-winning-streak-with-fps-techniques/"><u>Elevating Your Winning Streak with FPS Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-and-restoring-faulty-media-playback/"><u>Resetting and Restoring Faulty Media Playback</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-optimal-msoffice-functionality-on-w11/"><u>Achieving Optimal MSOffice Functionality on W11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-simple-tricks-make-3d-gif-production-of-inspiration-pop-up/"><u>In 2024, Simple Tricks Make 3D GIF Production of Inspiration Pop Up</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-passcode-from-apple-iphone-11-pro-max-complete-guide-by-drfone-ios/"><u>How To Remove Passcode From Apple iPhone 11 Pro Max? Complete Guide</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-unlock-the-power-of-social-sharing-for-your-youtube-videos/"><u>2024 Approved  Unlock the Power of Social Sharing for Your YouTube Videos</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-leading-the-pack-in-multi-media-posting-on-instagram/"><u>[Updated] In 2024, Leading the Pack in Multi-Media Posting on Instagram</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-from-components-to-creativity-building-a-professional-4k-pc/"><u>In 2024, From Components to Creativity  Building a Professional 4K PC</u></a></li>
<li><a href="https://some-techniques.techidaily.com/excellence-collection-highest-quality-webcam-supports-for-2024/"><u>Excellence Collection  Highest Quality Webcam Supports for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/streamlining-your-editing-workflow-with-final-cut-pro-tips-for-2024/"><u>Streamlining Your Editing Workflow with Final Cut Pro Tips for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-unleash-your-creativity-simple-video-editing-with-microsoft-on-windows/"><u>2024 Approved Unleash Your Creativity Simple Video Editing with Microsoft on Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-ways-to-transfer-text-messages-from-vivo-s17e-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>2 Ways to Transfer Text Messages from Vivo S17e to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
</ul></div>
