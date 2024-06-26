---
title: Correcting Failed Execution of Defrag Utility
date: 2024-06-25T10:12:03.751Z
updated: 2024-06-26T10:12:03.751Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Failed Execution of Defrag Utility
excerpt: This Article Describes Correcting Failed Execution of Defrag Utility
keywords: Defrag Fail Fix,Error Defrag Tool,Execute Defrag Correction,Defrag Issue Resolve,Utility Defrag Troubleshoot,Correcting Defrag Malfunction,Restart Failed Defrag Scan
thumbnail: https://thmb.techidaily.com/03b50fa097007316bd728c0f1505911c6985b5446ee8e6c9838cd48c592632a7.png
---

## Correcting Failed Execution of Defrag Utility

 The Disk Defragmenter tool is a Windows user's best friend. This tool fixes fragmentation issues so that your hard drive runs smoother, but it itself sometimes comes across problems of its own. If you're having trouble with your disk defragmenter, there are a few things you can do to resolve the problem.

 In this article, you will learn how to fix the Disk Defragmenter so it works properly again.

## What Is the Disk Defragmenter? Why Does It Stop Working?

 The Disk Defragmenter tool rearranges files on your hard drive so that they are stored in a contiguous manner. This helps to improve file access speed and overall system performance. Disk fragmentation can occur over time as you add, remove, and modify files on your hard drive.

 Although a disk defragmenter is an important tool for keeping your computer running smoothly, sometimes it does not work as it should. Here are a few things that can cause the disk defragmenter to stop working:

1. The tool won't work if you have a solid-state drive (SSD). SSDs don't need to be defragmented because they don't have the same type of moving parts that traditional hard drives do.
2. Another possibility is that you have a virus or malware on your computer that's interfering with the disk defragmenter. You can try running a virus scan to see if that fixes the problem.
3. Corrupt system files can also cause the service to malfunction. In such a case, it may be worthwhile running an SFC (System File Checker) scan as a way to diagnose the problem.

 Now we know what causes the Disk Defragmenter to stop working, it's time to look at some solutions that may help you fix the problem.

## 1\. Check Disk Defragmenter's Status

 If your computer is running slowly, one potential reason could be that the Disk Defragmenter service is not running properly. This service helps to optimize your hard drive by rearranging files so that they can be read more quickly and efficiently.

 To check if the Disk Defragmenter service is running properly, follow the steps:

1. Open the Services app (see[ways to open the Services app on Windows](https://www.makeuseof.com/windows-11-open-services-app/) ).
2. Scroll down to the "Optimise drives" service and double-click on it.
3. Click on the drop-down menu and set the Start type to "Manual."
4. Make sure the Service status is "Running." If it is not, then click on**Start** to run it.  
![Set Optimise drives Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Set-Optimise-drives-Properties.jpg)
5. Click**Apply > OK** to save it.

 After making the above changes, check if it solves the problem. If not, move on to the next solution.

## 2\. Run the System File Checker tool

 Another way to fix your disk defragmenter is to run the System File Checker tool. This tool will scan all of your system files and replace any that are corrupt or missing.

To run the System File Checker, follow these steps:

1. Press**Win + X** on your keyboard to open the Power User menu.
2. Select the**Run** option from the menu list.
3. In the Run command dialog box, type "cmd" and press**Ctrl + Shift + Enter** at the same time.
4. When UAC appears on the screen, select**Yes** to approve administrator access.
5. Once you're in the Command Prompt window, type "sfc /scannow", and press**Enter** .

 It may take a while for the scan to complete, so be patient. Once the scan is complete, restart your computer and try running Disk Defragmenter again. It should now work properly.

![SFC and DISM Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/SFC-and-DISM-Scan.jpg)

 If you're still having trouble with your Disk Defragmenter tool after running an SFC scan, you may need to use the DISM utility. To do this, open the Command Prompt as an administrator and run the below command line:

`DISM /Online /Cleanup-Image /ScanHealth\nDism.exe /online /cleanup-image /restorehealth`

 Once the scan is complete, restart your computer and try defragmenting again.

## 3\. Run the CHKDSK Utility

 If your computer's Disk Defragmenter is still not working, you can try[running the CHKDSK utility](http://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) . This is a computer program designed to check the integrity of your hard drive, identify errors, and fix them.

To run the CHKDSK utility, follow the below steps:

1. Press the Windows key and search for "Command Prompt".
2. Right-click on the search result and select**Run as administrator** .
3. Click**Yes** if UAC prompts on your computer screen. This will open a Command Prompt with admin access.  
![Run chkdsk command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-chkdsk-command.jpg)
4. When you're in Command Prompt, type the following command and press Enter:  
`chkdsk C: /f`

 In the command above,**"C:"** represents your drive, so you should replace it with the letter that refers to your drive.

 Once the scanning process is completed, and you have been informed that your drive has been scanned, try to defragment it again.

 As it turns out, it may take several minutes for the scan to complete, depending on the size of your partition and sometimes it seems to get stuck. However, you should let it complete its task uninterrupted.

## 4\. Close All Third-Party Applications

 Some third-party applications may interfere with Disk Defragmenter if they are running. In such a case, close all third-party programs and see if that helps the defragmenter to run properly.

 If you close all active windows and find that the defragmenter is still having issues, there might be a background process interfering with it. As such, you can try ending some third-party processes and see if that fixes it.

1. Press**Ctrl + Shift + Esc** on your keyboard to open the Task Manager.
2. On the Processes tab, find a non-essential third-party service and right-click on it.
3. Then select**End task** from the context menu.  
![Close Programs Via Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Close-Programs-Via-Task-Manager.jpg)

 After closing one, check if the disk defragmenter works again. If it does, the service you just closed is the culprit. Now you can either update, re-install, or even uninstall the problematic app so it stops interfering with Disk Defragmenter.

## Fixing Windows Disk Defragmenter's Opening Issues

 Disk defragmentation can improve the situation by rearranging files so that they can be evenly distributed throughout the drive. However, sometimes the Disk Defragmenter tool doesn't work as expected. If you encounter this problem, the methods described above should help you resolve it.


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
<li><a href="https://win11.techidaily.com/transform-windows-11-desktop-tips-on-interactive-and-dynamic-walls/"><u>Transform Windows 11 Desktop: Tips on Interactive and Dynamic Walls</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-on-accessing-windows-11-homescreen/"><u>Expert Tips on Accessing Windows 11 Homescreen</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-with-our-top-5-budget-drivers-for-pcs/"><u>Unleash Potential with Our Top 5 Budget Drivers for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-blackout-getting-out-of-dark-mode/"><u>Bypassing The Blackout: Getting Out Of Dark Mode</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-custom-audio-commands-in-the-latest-windows-os/"><u>Crafting Custom Audio Commands in the Latest Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-gpu-usage-in-windows-desktop-window/"><u>Decreasing Excessive GPU Usage in Windows Desktop Window</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-ways-to-remove-search-icon-art/"><u>Efficient Ways to Remove Search Icon Art</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-digital-space-adjusting-windows-11-program-shortcuts/"><u>Mastering Your Digital Space: Adjusting Windows 11 Program Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-implications-of-removing-windows-11s-taskbar-chatting-capability-on-you/"><u>Unpacking the Implications of Removing Windows 11'S Taskbar Chatting Capability on You</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-xiaomi-civi-3-disney-100th-anniversary-edition-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Xiaomi Civi 3 Disney 100th Anniversary Edition Phone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-reverberating-success-a-compilation-of-8-exemplary-cinematic-audio-effects/"><u>Updated In 2024, Reverberating Success A Compilation of 8 Exemplary Cinematic Audio Effects</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/convert-with-ease-pure-mp4s-from-your-favorite-tiktoks-for-2024/"><u>Convert with Ease  Pure MP4s From Your Favorite TikToks for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-fundamentals-of-sports-video-editing/"><u>In 2024, The Fundamentals of Sports Video Editing</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-motorola-moto-g-5g-2023-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Motorola Moto G 5G (2023) to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/accelerate-video-processing-for-youtube-uploads-for-2024/"><u>Accelerate Video Processing for YouTube Uploads for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-maximizing-visibility-on-twitter-campaigns/"><u>[Updated] 2024 Approved  Maximizing Visibility on Twitter Campaigns</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/creating-instagram-virality-video-edition-for-2024/"><u>Creating Instagram Virality  Video Edition for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-elevate-your-online-presence-audios-for-your-channel/"><u>[Updated] Elevate Your Online Presence  Audios for Your Channel</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-alternatives-and-step-by-step-guide-for-apowersoft-audio-recorder/"><u>In 2024, Alternatives and Step by Step Guide for Apowersoft Audio Recorder</u></a></li>
</ul></div>
