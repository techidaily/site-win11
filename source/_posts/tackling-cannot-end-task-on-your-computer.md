---
title: Tackling 'Cannot End Task' On Your Computer
date: 2024-06-25T11:24:20.031Z
updated: 2024-06-26T11:24:20.031Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling 'Cannot End Task' On Your Computer
excerpt: This Article Describes Tackling 'Cannot End Task' On Your Computer
keywords: Fixing Task Stops Error,Resolve Cannot End Task,Stop Task Failure Help,Unblock Task Completion,Troubleshoot Can't Finish Task,Cease Task Error Remediation,Terminate Task Problem Solving
thumbnail: https://thmb.techidaily.com/9083264d1e9ed82c0a8d3858961cbcacf8dd6e0e896428761bc70aaa3b066e45.jpg
---

## Tackling 'Cannot End Task' On Your Computer

 Task Manager is a handy system utility for terminating unwanted apps and processes on Windows. Although it usually works as expected, there are times when Task Manager malfunctions and displays the "unable to terminate process" error on Windows.

 If you’re unable to terminate apps or processes due to this error, here are some ways you can either fix the error message or bypass it using a different method outside of Windows' Task Manager.

## 1\. Use the Alt + F4 Keyboard Shortcut

 At times, temporary glitches with an app or program can trigger the “unable to terminate process” error on Windows. If it’s nothing major, you should be able to close the unresponsive program with the**Alt + F4** keyboard shortcut. Switch to the app or program you want to close and press**Alt + F4** together on your keyboard to close it.

 Check out[how to force close a program without the Task Manager](https://www.makeuseof.com/tag/how-to-kill-unresponsive-programs-without-the-task-manager/) for more ways to close an app without using this tool.

## 2\. Open Task Manager as an Administrator

 Not running Task Manager as an administrator could prevent you from terminating certain system processes. If that’s the case, use the following steps to open Task Manager with elevated rights and then try to terminate the process again.

1. Click the magnifying icon on the taskbar to open the search menu.
2. Type**Task Manager** in the box and select**Run as administrator** .
3. When the[User Account Control (UAC)](https://www.makeuseof.com/tag/user-account-control-windows-10/) prompt appears, select**Yes** to continue.
4. Right-click on the process you want to terminate and select**End task** from the context menu.  
![Close Process Using Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/close-process-using-task-manager.jpg)

## 3\. Use the Taskkill Command to Terminate the Process

 Using the Task Manager isn’t the only way to terminate processes on Windows. If you’re comfortable using Command Prompt, you can run the "taskkill" command to easily stop an unwanted process on Windows.

 In order to terminate a process with the taskkill command, you’ll need to know the exact name of the process. To find out, switch to the**Details** tab in the Task Manager window and locate the process you want to kill. Note down its name from the first column.

![Details Tab in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/details-tab-in-task-manager.jpg)

 Once you have the name of the process, use the following steps to terminate it.

1. Press**Win + S** to open the search menu.
2. Type**Command Prompt** in the box and select**Run as administrator** .
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press**Enter** to terminate the process. Make sure you replace**ProcessName** in the following command with the actual name of the process noted earlier.  
`taskkill /IM "ProcessName" /T /F`  
![Terminate Process With Taskkill Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/terminate-process-with-taskkill-command.jpg)

 Once you run the above command, you should see a confirmation message indicating that the process was terminated successfully.

## 4\. Terminate the Process With WMIC

 WMIC (or Windows Management Instrumentation Command-line) is another powerful tool for terminating processes on Windows. Again, you'll need to know the exact name of the process you want to kill. Once you have that, use the following steps to terminate the process with WMIC.

1. Use any of your preferred methods to[open Command Prompt with administrative privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) .
2. Paste the following command in the console, replace**ProcessName** with the actual name of the process you want to terminate, and press**Enter** .  
`wmic process where name='processname.exe' delete`  
![Terminate Process With WMIC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/terminate-process-with-wmic.jpg)

## 5\. Use a Task Manager Alternative

 Finally, if none of the solutions help with the "unable to terminate process" error, you can consider using a[Task Manager alternative on Windows](https://www.makeuseof.com/tag/5-powerful-alternatives-windows-task-manager/) . If you're looking for something with more power, Process Explorer is a solid choice.

1. [Download Process Explorer](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) on your computer.
2. Double-click the**procexp64.exe** to open Process Explorer.
3. Locate the process you want to terminate. Right-click on it and select**Kill Process** from the resulting menu.  
![Kill Process Using Process Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/kill-process-using-process-explorer.jpg)

## Your Tasks, Terminated Successfully

 By applying the fixes in the article, you should be able to fix the “unable to terminate process” error on Windows. However, be cautious when terminating processes via Task Manager, as some may cause your system to freeze or crash if terminated.


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
<li><a href="https://win11.techidaily.com/breaking-down-windows-11-overcoming-5ghz-wi-fi-barriers/"><u>Breaking Down Windows 11: Overcoming 5GHz Wi-Fi Barriers</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-winning-streak-with-fps-techniques/"><u>Elevating Your Winning Streak with FPS Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/stealth-mode-hiding-or-revealing-windows-protection-sectors/"><u>Stealth Mode: Hiding or Revealing Windows Protection Sectors</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-most-effective-windows-to-do-apps/"><u>Navigating the Most Effective Windows To-Do Apps</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-tweak-controlled-chromeedge-configurations-for-work-computers/"><u>Steps to Tweak Controlled Chrome/Edge Configurations for Work Computers</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-education-elements-into-windows-ui/"><u>Infuse Education Elements Into Windows UI</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-windows-11-when-you-cant-rename-folders/"><u>8 Ways to Fix Windows 11 When You Can’t Rename Folders</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/mastering-youtube-thumbnails-with-ease/"><u>Mastering YouTube Thumbnails with Ease</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-creating-professional-videos-with-adobe-presenter/"><u>[New] Creating Professional Videos with Adobe Presenter</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-fiscal-horizons-exploring-mr-beasts-income-for-2024/"><u>[Updated] Fiscal Horizons  Exploring Mr. Beast's Income for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-cutting-edge-editing-meets-online-video-sharing/"><u>[Updated] 2024 Approved  Cutting-Edge Editing Meets Online Video Sharing</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-inverting-image-hues-in-photoshop/"><u>2024 Approved  Inverting Image Hues in Photoshop</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-maximizing-iphone-hdr-quality-with-post-production-tricks-in-premiere-pro/"><u>In 2024, Maximizing iPhone HDR Quality with Post-Production Tricks in Premiere Pro</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unleash-creativity-essential-tips-for-lut-production/"><u>In 2024, Unleash Creativity  Essential Tips for LUT Production</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/identifying-video-centric-dialogues/"><u>Identifying Video-Centric Dialogues</u></a></li>
</ul></div>
