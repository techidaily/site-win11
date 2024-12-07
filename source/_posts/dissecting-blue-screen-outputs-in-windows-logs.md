---
title: Dissecting Blue Screen Outputs in Windows Logs
date: 2024-11-30T19:38:07.725Z
updated: 2024-12-06T19:59:13.596Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Dissecting Blue Screen Outputs in Windows Logs
excerpt: This Article Describes Dissecting Blue Screen Outputs in Windows Logs
keywords: Blu-Screen Analysis,Winlog Examination,Error Logs Study,System Crash Findings,BSO Interpretation,OS Failure Insights,Display Fault Diagnosis
thumbnail: https://thmb.techidaily.com/e61ec8b8b6fcdc5ae49f80ff7f35fd26c15f5f9f26e0670f639723e26a96ce2a.jpeg
---

## Dissecting Blue Screen Outputs in Windows Logs

 When your computer crashes and you face a Blue Screen of Death (BSOD), your system saves the details of the crash as a BSOD log, in a pre-defined location in Windows. This information gives you details about when the crash happened, what caused it, and sometimes even what to do to fix the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Where Are the BSOD Log Files Located in Windows?

 You can find the BSOD log files in the Event Viewer, Control Panel, and Registry Editor in Windows. Below, we have listed the detailed steps for finding these files in all three of these utilities.

### 1\. Find and Read the BSOD Log Files in the Event Viewer

 The Event Viewer is a tool developed by Microsoft for users to view system and program-related events in Windows. These events can include system errors, warnings, informational messages, and more. In other words, every issue you encounter (whether a minor glitch or a major crash) will be logged in the Event Viewer for later investigation and sharing with Microsoft.

 You can check out our detailed guide on [what the Event Viewer is and how it can be useful](https://www.makeuseof.com/windows-event-viewer-guide/) if you are unfamiliar with it.

 Here is how you can find the BSOD log files in the Event Viewer:

1. Right-click on the Windows icon in the taskbar and choose **Event Viewer** from the context menu.  
![Choose Event Viewer in the context menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer.jpg)
2. Head over to the **Action** menu located at the top, and choose **Create Custom View** from the context menu.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  
![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
4. Next, locate the BSOD using details like the date and time again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Upon reboot, you should be able to view the log files without any problems.

### 3\. Find and Read the BSOD Log Files in the Control Panel

 The third way of finding and reading the BSOD log files is via the Control Panel. This approach offers a graphical representation of the log files using the Windows Reliability Monitor, unlike the methods we have explored previously.

 The Reliability Monitor, which is different than the Performance Monitor (see [Reliability Monitor vs. Performance Monitor](https://www.makeuseof.com/reliability-monitor-vs-performance-monitor/)) will show you a timeline of important system events that occurred on your computer including BSOD occurrences, software installations, application crashes, and other relevant events.

 Here is how you can use it to identify and fix problems that may affect your system:

1. Type Control Panel in the search area of the taskbar and click **Open**.
2. In the following window, choose **System and Security** \> **Security and Maintenance**.  
![Security and maintenance settings in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/security-maintenance.jpg)
3. Click on **Maintenance** and then select **View reliability history**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-links.techidaily.com/new-simplifying-transition-workflows-audacitys-crossfade-capabilities/"><u>[New] Simplifying Transition Workflows Audacity's Crossfade Capabilities</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-tailoring-text-features-in-ae-compositions/"><u>[New] Tailoring Text Features in AE Compositions</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-streamlining-success-strategies-for-daily-vlog-authenticity/"><u>[Updated] Streamlining Success Strategies for Daily Vlog Authenticity</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-charge-alert-customization-for-win-users/"><u>Cutting-Edge Charge Alert Customization for WIN Users</u></a></li>
<li><a href="https://solve-howtos.techidaily.com/dealing-with-device-driver-issues-steps-for-recovery-and-restoration-by-yl-tech-solutions/"><u>Dealing with Device Driver Issues: Steps for Recovery and Restoration by YL Tech Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/dodging-delayed-wow-update-cycles/"><u>Dodging Delayed WoW Update Cycles</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/final-cut-pro-color-correction-for-film-and-video-professionals/"><u>Final Cut Pro Color Correction for Film and Video Professionals</u></a></li>
<li><a href="https://win11.techidaily.com/guides-to-reinstall-non-operational-store-applications/"><u>Guides to Reinstall Non-Operational Store Applications</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changefake-your-motorola-razr-40-ultra-location-on-viber-drfone-by-drfone-virtual-android/"><u>How to Change/Fake Your Motorola Razr 40 Ultra Location on Viber | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-plate-to-screen-perfecting-the-art-of-food-cinema/"><u>In 2024, From Plate to Screen Perfecting the Art of Food Cinema</u></a></li>
<li><a href="https://win11.techidaily.com/key-tips-for-a-more-effective-windows-11-search-experience/"><u>Key Tips for a More Effective Windows 11 Search Experience</u></a></li>
<li><a href="https://fox-glue.techidaily.com/leading-15-no-cost-image-editing-apps-top-picks-of-2023-for-2024/"><u>Leading 15 No-Cost Image Editing Apps - Top Picks of 2023 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-overcome-silent-microphone-on-pc-while-recording/"><u>Methods to Overcome Silent Microphone on PC While Recording</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-automatic-start-of-spotify-in-windows/"><u>Preventing Automatic Start of Spotify in Windows</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/revolutionizing-gameplay-with-innovative-file-logging-tools-for-2024/"><u>Revolutionizing Gameplay with Innovative File Logging Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-correct-incompatible-system-post-upgrade-error/"><u>Steps to Correct 'Incompatible System' Post-Upgrade Error</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-roku-closed-captioning-feature-that-refuses-to-activate/"><u>Troubleshooting Roku Closed Captioning Feature That Refuses to Activate</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-eliminating-windows-error-0x8007251d/"><u>Understanding and Eliminating Windows Error 0X8007251D</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-potential-a-guide-to-powertoys-locksmith-features/"><u>Unlock Potential: A Guide to PowerToys' Locksmith Features</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    