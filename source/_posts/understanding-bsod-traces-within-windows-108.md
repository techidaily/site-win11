---
title: Understanding BSOD Traces Within Windows 10/8
date: 2024-06-25T11:25:16.075Z
updated: 2024-06-26T11:25:16.075Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding BSOD Traces Within Windows 10/8
excerpt: This Article Describes Understanding BSOD Traces Within Windows 10/8
keywords: BSOD Analysis,Win10 Crash Diags,Blue Screen Debugging,Windows BSoD Errors,BSoD Trace Exploration,Debug BSoD Issue,System BSoD Solutions
thumbnail: https://thmb.techidaily.com/4ddb75c55f41c22a4f3ada299a0f1a1093c8ca9e10e43f8a8e61a1ff732d1283.jpg
---

## Understanding BSOD Traces Within Windows 10/8

 When your computer crashes and you face a Blue Screen of Death (BSOD), your system saves the details of the crash as a BSOD log, in a pre-defined location in Windows. This information gives you details about when the crash happened, what caused it, and sometimes even what to do to fix the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

## Where Are the BSOD Log Files Located in Windows?

 You can find the BSOD log files in the Event Viewer, Control Panel, and Registry Editor in Windows. Below, we have listed the detailed steps for finding these files in all three of these utilities.

### 1\. Find and Read the BSOD Log Files in the Event Viewer

 The Event Viewer is a tool developed by Microsoft for users to view system and program-related events in Windows. These events can include system errors, warnings, informational messages, and more. In other words, every issue you encounter (whether a minor glitch or a major crash) will be logged in the Event Viewer for later investigation and sharing with Microsoft.

 You can check out our detailed guide on [what the Event Viewer is and how it can be useful](https://www.makeuseof.com/windows-event-viewer-guide/) if you are unfamiliar with it.

 Here is how you can find the BSOD log files in the Event Viewer:

1. Right-click on the Windows icon in the taskbar and choose **Event Viewer** from the context menu.  
![Choose Event Viewer in the context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer.jpg)
2. Head over to the **Action** menu located at the top, and choose **Create Custom View** from the context menu.  
![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  
![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  
![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
4. Next, locate the BSOD using details like the date and time again.
5. Once you find the targeted log, click on it.
6. Check both the General and Details tabs to get information about this error.

 Once you find the error code associated with the crash and the cause, you can look for solutions online, or head over to our guide that discusses [how to fix blue screen errors in Windows](https://www.makeuseof.com/tag/4-tips-fix-blue-screen-error/) if it's a bsod.

### 2\. Find and Read the BSOD Log Files in the Registry Editor

 In case using the Event Viewer does not work for you for some reason, you can use another Windows utility to locate and study the BSOD log files—the Registry Editor.

 Windows Registry Editor is an administrative-level utility that lets you control how Windows operates and interacts with hardware and software. The Registry stores information related to the hardware and software components of your system. This information in the Registry is stored in the form of keys and values, and by modifying these with the dedicated Registry Editor, you can customize the operations of your system.

 Listed below are the steps for finding the BSOD log files in the Registry Editor. Make sure you are logged into your system as an administrator before you proceed.

1. Press the **Win + R** keys to open Run.
2. Type "regedit" in Run and press **Ctrl + Shift + Enter** to launch the Registry Editor as an administrator.
3. Now, select **Yes** in the User Account Prompt.
4. Once you are inside the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\CrashControl`
5. Next, move to the right pane and right-click on an empty space anywhere.
6. Choose **New** \> **DWORD (32-bit) Value**.  
![Create a new DWORD value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/dword-policies.jpg)
7. Name this value as **DisplayParameters** and double-click on it.
8. Under Value data, type 1 and click **OK**.  
![Change the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/value-data-1.jpg)
9. Once done, restart your PC.

 Upon reboot, you should be able to view the log files without any problems.

### 3\. Find and Read the BSOD Log Files in the Control Panel

 The third way of finding and reading the BSOD log files is via the Control Panel. This approach offers a graphical representation of the log files using the Windows Reliability Monitor, unlike the methods we have explored previously.

 The Reliability Monitor, which is different than the Performance Monitor (see [Reliability Monitor vs. Performance Monitor](https://www.makeuseof.com/reliability-monitor-vs-performance-monitor/)) will show you a timeline of important system events that occurred on your computer including BSOD occurrences, software installations, application crashes, and other relevant events.

 Here is how you can use it to identify and fix problems that may affect your system:

1. Type Control Panel in the search area of the taskbar and click **Open**.
2. In the following window, choose **System and Security** \> **Security and Maintenance**.  
![Security and maintenance settings in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/security-maintenance.jpg)
3. Click on **Maintenance** and then select **View reliability history**.  
![Check the reliability history of the system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/view-realability-history.jpg)
4. You should now see a graph showing the reliability data. Look for red cross icons and blue (i) icons in the graph, as they show problematic events.  
![Reliability graph](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/realability-graph.jpg)
5. Click on each of the icons to view its details. Keep repeating the process to locate the event you are looking for.

 You will be presented with information like the faulting application path, its name, fault module timestamp, exception code, etc. If this app caused a BSOD crash, then you can try ending its process via the Task Manager or uninstalling the app if it is not necessary.

 It is also a good idea to copy this information and send it to Microsoft for review if you cannot find a solution online.

## Learn How to Read Your BSOD Log Files and Resolve Your Crashes

 ​​​​​​Windows blue screen errors are nothing new, but since they only display messages like "Your PC encountered a problem" without describing the cause, it can be difficult to find a fix. Understanding how to read BSOD log files can not only help you identify the exact cause of the problem but also help you find the right solution.

 Whenever a component causes your system to crash, you can disable it and switch to a better alternative to avoid the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/strategies-to-resolve-windows-high-dpi-screen-scaling/"><u>Strategies to Resolve Windows High DPI Screen Scaling</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-command-prompt-for-ultimate-control/"><u>Configuring Command Prompt for Ultimate Control</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-windows-experience-filter-key-settings/"><u>Customize Your Windows Experience: Filter Key Settings</u></a></li>
<li><a href="https://win11.techidaily.com/bring-task-manager-above-all-step-guide/"><u>Bring Task Manager Above All: Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-lost-volume-preferences-after-software-changes/"><u>Restoring Lost Volume Preferences After Software Changes</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-memory-caching-in-windows-os/"><u>Breaking Down Memory Caching in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-updates-error-0x80242016-fix/"><u>Mastering Windows Updates' Error 0X80242016 Fix</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-frequent-rainmeter-setbacks-an-easy-guide/"><u>Decoding and Fixing Frequent Rainmeter Setbacks: An Easy Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-unraveling-instagrams-video-time-restrictions-for-2024/"><u>[New] Unraveling Instagram's Video Time Restrictions for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-exploring-8-signature-free-game-sounds-that-are-a-must-have/"><u>2024 Approved Exploring 8 Signature Free Game Sounds That Are a Must-Have</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-top-8-3d-websites-with-stunning-gold-text-visuals/"><u>[Updated] 2024 Approved  Top 8 3D Websites with Stunning Gold Text Visuals</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-unpacked-strategies-for-optimal-viewing-of-live-videos/"><u>[Updated] Unpacked Strategies for Optimal Viewing of Live Videos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-samsung-vs-lg-battle-of-360-degree-cameras/"><u>In 2024, Samsung Vs LG  Battle of 360-Degree Cameras</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713962802533-updated-do-you-wish-to-know-how-ffmpeg-can-remove-audio-from-a-video-if-yes-keep-scrolling-this-guide-to-remove-audio-from-video-with-ffmpeg-and-other-alter/"><u>Updated Do You Wish to Know How FFmpeg Can Remove Audio From a Video? If Yes, Keep Scrolling This Guide to Remove Audio From Video with FFmpeg and Other Alternative Software for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/restore-missing-app-icon-on-honor-play-40c-step-by-step-solutions-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Restore Missing App Icon on Honor Play 40C Step-by-Step Solutions | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-unveiling-techniques-for-targeted-youtube-video-download/"><u>[New] Unveiling Techniques for Targeted YouTube Video Download</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/unlock-free-content-with-these-top-7-tools-for-instagram-video-editing/"><u>Unlock Free Content with These Top 7 Tools for Instagram Video Editing</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>