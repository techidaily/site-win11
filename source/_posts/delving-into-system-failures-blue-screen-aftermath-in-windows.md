---
title: "Delving Into System Failures: Blue Screen Aftermath in Windows"
date: 2024-07-13T10:50:12.786Z
updated: 2024-07-14T10:50:12.786Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Delving Into System Failures: Blue Screen Aftermath in Windows"
excerpt: "This Article Describes Delving Into System Failures: Blue Screen Aftermath in Windows"
keywords: Windows BlueScreenTrouble,Fixing BlueScreenError,WinBlueCrashIssues,Windows CrashDiagnosis,SystemBlueFailFixes,ErrorScreenWindowsRecovery,Resolving WinBlueCritical
thumbnail: https://thmb.techidaily.com/623365f2ffae0d2d8c9a44d31ae5f64f961d3fb3d2838be2d2e5cf0ae63c28b6.jpg
---

## Delving Into System Failures: Blue Screen Aftermath in Windows

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/procedure-opening-driver-verifier-for-fault-analysis/"><u>Procedure: Opening Driver Verifier for Fault Analysis</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-realme-c51-device-sim-by-drfone-android/"><u>Easily Unlock Your Realme C51 Device SIM</u></a></li>
<li><a href="https://win11.techidaily.com/declutter-your-computer-finding-and-purging-windows-empties/"><u>Declutter Your Computer: Finding & Purging Windows' Empties</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-prohibited-application-red-flag-in-windows/"><u>Fixing the Prohibited Application Red Flag in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-resolution-of-windows-activation-flaw-0x803f700f/"><u>Mastering the Resolution of Windows Activation Flaw 0X803F700f</u></a></li>
<li><a href="https://video-capture.techidaily.com/superior-mac-hd-recorders-with-in-built-sound-capture/"><u>Superior Mac HD Recorders with In-Built Sound Capture</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-enhanced-google-chats-essential-techniques-4-ways/"><u>[New] In 2024, Enhanced Google Chats  Essential Techniques, 4 Ways</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-xiaomi-13t-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Xiaomi 13T Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/advancing-windows-experience-the-significance-of-16gb-ram/"><u>Advancing Windows Experience: The Significance of 16GB RAM</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-skypes-sound-solution-purifying-your-talks/"><u>2024 Approved  Skype's Sound Solution  Purifying Your Talks</u></a></li>
<li><a href="https://win11.techidaily.com/windows-update-halted-by-error-2e-solutions-here/"><u>Windows Update Halted by Error 2E? Solutions Here</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-list-of-windows-most-reliable-usage-monitors/"><u>Exclusive List of Windows' Most Reliable Usage Monitors</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-the-feel-personalizing-touchpad-settings-in-windows-11/"><u>Fine-Tune the Feel: Personalizing Touchpad Settings in Windows 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/masterclass-in-screenshotting-professional-level-techniques-using-mobizen-for-2024/"><u>Masterclass in Screenshotting  Professional-Level Techniques Using Mobizen for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-supreme-reconciliation-of-vr-realms/"><u>[New] In 2024, Supreme Reconciliation of VR Realms</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-inability-to-install-windows-store-apps/"><u>Resolving Inability to Install Windows Store Apps</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-management-for-windows-11-domain-based/"><u>Biometric Management for Windows 11, Domain-Based</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-from-tube-to-chat-sharing-video-content-from-youtube-and-twitter-directly/"><u>[Updated] 2024 Approved  From Tube to Chat  Sharing Video Content From YouTube & Twitter Directly</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-120plus-original-title-concepts-for-unique-and-memorable-snapchat-stories/"><u>2024 Approved  120+ Original Title Concepts for Unique and Memorable Snapchat Stories</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-perfect-your-channel-imagery-youtube-thumbnail-dos-and-donts/"><u>[Updated] Perfect Your Channel Imagery  YouTube Thumbnail Do's & Don'ts</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-error-xc0000142-in-microsoft-oses/"><u>Remedying Error XC0000142 in Microsoft OSes</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-device-engagement-in-power-save-mode/"><u>Maximizing Device Engagement in Power Save Mode</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-find-my-iphone-without-apple-id-on-your-apple-iphone-6-plus-by-drfone-ios/"><u>In 2024, How to Remove Find My iPhone without Apple ID On your Apple iPhone 6 Plus?</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-errors-with-windows-event-logger/"><u>Overcoming Errors with Windows Event Logger</u></a></li>
<li><a href="https://win11.techidaily.com/proven-tools-to-assist-in-making-your-pc-to-mac-os-transition-easier/"><u>Proven Tools to Assist in Making Your PC-to-Mac OS Transition Easier</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-and-resolve-windows-error-code-0xc00000f-quickly/"><u>Avoid and Resolve Windows Error Code: 0Xc00000f Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-gain-entry-windowsstore-apps-explorer/"><u>How To Gain Entry: WindowsStore Apps Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secrets-of-username-modification-in-windows-11/"><u>Unlocking the Secrets of UserName Modification in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ready-for-success-testing-your-meeting-tech-on-windows/"><u>Ready for Success: Testing Your Meeting Tech on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-regain-windows-11-help-application-use/"><u>Steps to Regain Windows 11 Help Application Use</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-auto-play-in-spotify-for-windows-pcs/"><u>Disabling Auto-Play in Spotify for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/revel-in-rich-software-diversity-on-windows/"><u>Revel in Rich Software Diversity on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-no-powershell-on-windows-system/"><u>Troubleshooting: No PowerShell on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/quicken-real-time-update-of-task-manager-in-win-11/"><u>Quicken Real-Time Update of Task Manager in Win 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-the-guide-to-growing-instagram-video-audiences/"><u>[Updated] In 2024, The Guide to Growing Instagram Video Audiences</u></a></li>
<li><a href="https://win11.techidaily.com/your-quick-reference-to-fixing-windows-photo-application/"><u>Your Quick Reference to Fixing Window's Photo Application</u></a></li>
<li><a href="https://win11.techidaily.com/safeguarding-data-update-windows-11-user-passwords/"><u>Safeguarding Data: Update Windows 11 User Passwords</u></a></li>
<li><a href="https://win11.techidaily.com/old-wallpapers-no-more-discover-three-solutions/"><u>Old Wallpapers No More! Discover Three Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/the-essence-of-devhome-transforming-your-w11-experience/"><u>The Essence of DevHome: Transforming Your W11 Experience</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-to-do-management-in-the-microsoft-ecosystem/"><u>Mastering To-Do Management in the Microsoft Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-soundscape-windows-11-spatial-tips/"><u>Elevate Your Soundscape: Windows 11 Spatial Tips</u></a></li>
</ul></div>
