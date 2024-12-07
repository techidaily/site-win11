---
title: "Unlocking Blue Screen Mysteries: Where Are the Logs?"
date: 2024-12-02T00:52:42.025Z
updated: 2024-12-06T22:04:05.300Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Blue Screen Mysteries: Where Are the Logs?"
excerpt: "This Article Describes Unlocking Blue Screen Mysteries: Where Are the Logs?"
keywords: BlueScreenTroubleshooting,WindowsLogRecovery,SystemErrorAnalysis,ErrorCodeInterpretation,DiagnosticToolGuide,BSoDHelpSteps,LogFilesSearchTips
thumbnail: https://thmb.techidaily.com/39056fd18de68ad167dab8918139616b0085a3cc76b52ba12d66889ac85fb462.jpg
---

## Unlocking Blue Screen Mysteries: Where Are the Logs?

 When your computer crashes and you face a Blue Screen of Death (BSOD), your system saves the details of the crash as a BSOD log, in a pre-defined location in Windows. This information gives you details about when the crash happened, what caused it, and sometimes even what to do to fix the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

## Where Are the BSOD Log Files Located in Windows?

 You can find the BSOD log files in the Event Viewer, Control Panel, and Registry Editor in Windows. Below, we have listed the detailed steps for finding these files in all three of these utilities.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Find and Read the BSOD Log Files in the Event Viewer

 The Event Viewer is a tool developed by Microsoft for users to view system and program-related events in Windows. These events can include system errors, warnings, informational messages, and more. In other words, every issue you encounter (whether a minor glitch or a major crash) will be logged in the Event Viewer for later investigation and sharing with Microsoft.

 You can check out our detailed guide on [what the Event Viewer is and how it can be useful](https://www.makeuseof.com/windows-event-viewer-guide/) if you are unfamiliar with it.

 Here is how you can find the BSOD log files in the Event Viewer:

1. Right-click on the Windows icon in the taskbar and choose **Event Viewer** from the context menu.  
![Choose Event Viewer in the context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer.jpg)
2. Head over to the **Action** menu located at the top, and choose **Create Custom View** from the context menu.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  
![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
4. Next, locate the BSOD using details like the date and time again.
5. Once you find the targeted log, click on it.
6. Check both the General and Details tabs to get information about this error.

 Once you find the error code associated with the crash and the cause, you can look for solutions online, or head over to our guide that discusses [how to fix blue screen errors in Windows](https://www.makeuseof.com/tag/4-tips-fix-blue-screen-error/) if it's a bsod.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Reliability graph](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/realability-graph.jpg)
5. Click on each of the icons to view its details. Keep repeating the process to locate the event you are looking for.

 You will be presented with information like the faulting application path, its name, fault module timestamp, exception code, etc. If this app caused a BSOD crash, then you can try ending its process via the Task Manager or uninstalling the app if it is not necessary.

 It is also a good idea to copy this information and send it to Microsoft for review if you cannot find a solution online.

## Learn How to Read Your BSOD Log Files and Resolve Your Crashes

 ​​​​​​Windows blue screen errors are nothing new, but since they only display messages like "Your PC encountered a problem" without describing the cause, it can be difficult to find a fix. Understanding how to read BSOD log files can not only help you identify the exact cause of the problem but also help you find the right solution.

 Whenever a component causes your system to crash, you can disable it and switch to a better alternative to avoid the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-banishing-bogus-buddies-from-instagram-social-structure/"><u>[Updated] 2024 Approved Banishing Bogus Buddies From Instagram Social Structure</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-essential-streamers-guide-top-10-sports-apps-for-real-time-action/"><u>[Updated] In 2024, Essential Streamers' Guide Top 10 Sports Apps for Real-Time Action</u></a></li>
<li><a href="https://win-rankings.techidaily.com/webpgif8-webpgif/"><u>人気のWebPとGIFフォルト自動変換無料ツールトップ8 - WebP・GIF対応スイチャーソフト</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-non-compatibilities-easy-steps-for-windows-xp-users/"><u>Conquer Non-Compatibilities: Easy Steps for Windows XP Users</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-error-messages-solving-windows-crashes-easily/"><u>Decoding Error Messages: Solving Windows Crashes Easily</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/elevate-professionalism-in-resume-crafting-chatgpt-techniques/"><u>Elevate Professionalism in Resume Crafting (ChatGPT Techniques)</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-0x0000011b-failure-on-win-1011/"><u>Fixing 0X0000011B Failure on Win 10/11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-harness-iphones-full-potential-for-landscapes-for-2024/"><u>How to Harness iPhone's Full Potential for Landscapes for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-resolving-the-mystery-of-missing-shorts-thumbnails-on-youtube/"><u>In 2024, Resolving the Mystery of Missing Shorts Thumbnails on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-event-viewer-troubleshooting/"><u>Navigating Windows Event Viewer Troubleshooting</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-errors-in-onedrive-cloud-operations-win/"><u>Overcoming Errors in OneDrive Cloud Operations Win</u></a></li>
<li><a href="https://android-unlock.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-vivo-t2-pro-5g-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Vivo T2 Pro 5G</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-powerpoints-print-functionality-9-tips-for-windows-users/"><u>Streamlining PowerPoint's Print Functionality: 9 Tips for Windows Users</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-s-top-free-mkv-splitters-trim-and-edit-with-ease/"><u>Updated In 2024, S Top Free MKV Splitters Trim and Edit with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/what-makes-the-updated-outlook-so-worth-it-top-9-reasons/"><u>What Makes the Updated Outlook So Worth It? - Top 9 Reasons</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-home-settings-made-simple/"><u>Windows 11 Home Settings Made Simple</u></a></li>
</ul></div>

