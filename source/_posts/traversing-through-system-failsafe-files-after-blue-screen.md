---
title: Traversing Through System Failsafe Files After Blue Screen
date: 2024-07-13T10:44:08.019Z
updated: 2024-07-14T10:44:08.019Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Traversing Through System Failsafe Files After Blue Screen
excerpt: This Article Describes Traversing Through System Failsafe Files After Blue Screen
keywords: BSFS File Paths,System Recovery Sequence,Safe Mode Bootloader,Blue Screen Diagnostic,Windows Failover Options,OS Error Handling,Failsafe Restart Protocol
thumbnail: https://thmb.techidaily.com/5b80927e68923eec1d1361008f6bde3827f135dcc6188baf767c77fe55f4ad9e.png
---

## Traversing Through System Failsafe Files After Blue Screen

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
<li><a href="https://win11.techidaily.com/1719347165719-restore-order-in-your-keyboard-chaos-with-these-9-fixes-for-broken-windows-shortcuts-and-combinations/"><u>Restore Order in Your Keyboard Chaos with These 9 Fixes for Broken Windows Shortcuts and Combinations.</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-solving-directdraw-mistakes/"><u>A Step-by-Step Approach to Solving DirectDraw Mistakes</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-windows-11-shortcuts/"><u>A Step-by-Step Approach to Windows 11 Shortcuts</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-honor-x50iplus-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Honor X50i+ Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719347210677-access-display-settings-right-click-on-the-desktop-and-select-display-settings/"><u>Access Display Settings: Right-Click on the Desktop and Select Display Settings.</u></a></li>
<li><a href="https://win11.techidaily.com/27-tips-for-personalizing-your-windows-11-experience/"><u>27 Tips for Personalizing Your Windows 11 Experience</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-get-your-favorite-youtube-tracks-as-mp3s-a-guide/"><u>Updated 2024 Approved Get Your Favorite YouTube Tracks as MP3s A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/8-strategies-to-solve-vmware-booting-woes-on-win11/"><u>8 Strategies to Solve VMware Booting Woes on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/1719351823246-fresh-start-for-stuck-chrome-try-these-remedies-for-win11/"><u>Fresh Start for Stuck Chrome: Try These Remedies For Win11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-optimal-alternatives-excluding-obs-for-recording/"><u>[New] 2024 Approved  Optimal Alternatives Excluding OBS for Recording</u></a></li>
<li><a href="https://win11.techidaily.com/1719322467309-troubleshooting-chrome-stuck-in-w11-quick-fixes/"><u>Troubleshooting: Chrome Stuck in W11? Quick Fixes!</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-cropping-and-styling-tips-for-standout-instagram-videos/"><u>[Updated] Cropping and Styling Tips for Standout Instagram Videos</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-microphone-experience-with-win-11s-voice-shortcuts/"><u>Accelerate Your Microphone Experience with Win 11'S Voice Shortcuts</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/trouble-with-apple-iphone-se-2020-swipe-up-try-these-11-solutions-drfone-by-drfone-ios/"><u>Trouble with Apple iPhone SE (2020) Swipe-Up? Try These 11 Solutions | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-itel-p55plus-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Itel P55+ without App | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/ideal-soundtracks-the-15-ultimate-music-selections-for-diverse-film-projects-for-2024/"><u>Ideal Soundtracks The 15 Ultimate Music Selections for Diverse Film Projects for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-elevating-user-experience-with-personalized-youtube-card-implementation/"><u>2024 Approved  Elevating User Experience with Personalized YouTube Card Implementation</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-guide-to-accessing-the-windows-iscsi-initiator/"><u>A Practical Guide to Accessing the Windows iSCSI Initiator</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-should-past-facebook-actions-follow-you-today-investigate/"><u>[Updated] In 2024, Should Past Facebook Actions Follow You Today? Investigate</u></a></li>
<li><a href="https://win11.techidaily.com/6-android-apps-perfect-for-a-windows-11-enthusiast/"><u>6 Android Apps Perfect for a Windows 11 Enthusiast</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-google-drive-not-syncing-on-windows/"><u>7 Ways to Fix Google Drive Not Syncing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/5-tips-for-opening-windows-help-and-support-promptly/"><u>5 Tips for Opening Windows Help and Support Promptly</u></a></li>
<li><a href="https://win11.techidaily.com/22h2-windows-fixes-for-recurring-issues/"><u>22H2 Windows Fixes for Recurring Issues</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-breakdown-of-entering-and-exiting-terminals-zen-space/"><u>A Step-by-Step Breakdown of Entering & Exiting Terminal's Zen Space</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-essential-windows-saver-techniques/"><u>A Guide to Essential Windows Saver Techniques</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-online-photo-editing-best-free-background-blur-software/"><u>Updated In 2024, Online Photo Editing Best Free Background Blur Software</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-capture-save-and-access-your-shots-seamlessly-with-free-and-paid-cloud-options/"><u>2024 Approved  Capture, Save and Access Your Shots Seamlessly with Free & Paid Cloud Options</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-locked-motorola-moto-e13-phone-by-drfone-android/"><u>How to Reset a Locked Motorola Moto E13 Phone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unleash-your-vision-establishing-an-entrepreneurial-video-haven-on-phone/"><u>In 2024, Unleash Your Vision  Establishing an Entrepreneurial Video Haven on Phone</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-keyboard-shortcuts-not-working-in-windows/"><u>9 Ways to Fix Keyboard Shortcuts Not Working in Windows</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-top-6-web-based-tiktok-to-audio-converter-free/"><u>[Updated] In 2024, Top 6 Web-Based TikTok to Audio Converter Free</u></a></li>
<li><a href="https://win11.techidaily.com/5-fun-tricks-you-can-do-in-command-prompt/"><u>5 Fun Tricks You Can Do in Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-extracting-device-ids-from-windows-pcs/"><u>A Step-by-Step Approach: Extracting Device IDs From Windows PCs</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-advanced-tips-for-minecraft-gaming-streams/"><u>[Updated] 2024 Approved  Advanced Tips for Minecraft Gaming Streams</u></a></li>
<li><a href="https://win11.techidaily.com/1719347016533-unlock-your-computers-print-command-solutions-for-faulty-wwinplusp-operations/"><u>Unlock Your Computer's Print Command: Solutions for Faulty WWin+P Operations.</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-look-at-windows-iscsi-initiator/"><u>A Comprehensive Look at Windows iSCSI Initiator</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-honor-v-purse-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Honor V Purse | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-policy-settings-with-windows-11-expertise/"><u>Accelerate Policy Settings with Windows 11 Expertise</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-elevating-youtube-live-with-high-quality-webcam-cameras-for-2024/"><u>[New] Elevating YouTube Live with High-Quality Webcam Cameras for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-samsung-galaxy-a25-5g-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Samsung Galaxy A25 5G FRP</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-find-your-ideal-android-movie-maker-a-step-by-step-guide/"><u>New 2024 Approved Find Your Ideal Android Movie Maker A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-solution-to-eradicate-error-code-740-on-win-11/"><u>A Step-by-Step Solution to Eradicate Error Code 740 on Win 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-unlocking-the-potential-of-discord-streams/"><u>[New] Unlocking the Potential of Discord Streams</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-from-followers-to-brand-ambassadors-the-five-pillars-of-influencer-success-for-2024/"><u>[New] From Followers to Brand Ambassadors  The Five Pillars of Influencer Success for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/transforming-views-uncover-the-best-video-hacks-for-success-for-2024/"><u>Transforming Views  Uncover the Best Video Hacks for Success for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/how-to-reinstall-qualcomm-atheros-wireless-network-adapter-driver/"><u>How to Reinstall Qualcomm Atheros Wireless Network Adapter Driver</u></a></li>
<li><a href="https://win11.techidaily.com/4-keys-to-reviving-a-device-stuck-in-night-setting/"><u>4 Keys to Reviving a Device Stuck in Night Setting</u></a></li>
<li><a href="https://win11.techidaily.com/a-deeper-look-at-windows-11-efficiency-mastering-processes-and-customizing-themes/"><u>A Deeper Look at Windows 11 Efficiency: Mastering Processes and Customizing Themes</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-the-15-most-effective-snapchat-posts-of-the-year/"><u>[Updated] 2024 Approved  The 15 Most Effective Snapchat Posts of the Year</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-choosing-the-perfect-video-to-audio-converter-key-criteria-to-consider/"><u>New Choosing the Perfect Video to Audio Converter Key Criteria to Consider</u></a></li>
<li><a href="https://win11.techidaily.com/1719375739489-relaunch-google-chrome-on-win11-fixes-and-tips-here/"><u>Relaunch Google Chrome on Win11 – Fixes and Tips Here.</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-guide-to-hdr-on-windows-11/"><u>A Complete Guide to HDR on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-fixing-discrepancies-in-to-do-app/"><u>A Comprehensive Guide to Fixing Discrepancies in To-Do App</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-navigating-with-precision-updating-status-and-avatars-in-discord-for-2024/"><u>[New] Navigating with Precision  Updating Status & Avatars in Discord for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-for-winning-website-conversion/"><u>A Step-by-Step for Winning Website Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/1719334307866-skip-wsl-save-time/"><u>Skip WSL, Save Time</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-the-desktop-window-managers-high-gpu-usage-on-windows-11/"><u>7 Ways to Fix the Desktop Window Manager's High GPU Usage on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719364992381-unraveling-windows-11-writable-error-fix-it-now/"><u>Unraveling Windows 11' Writable Error: Fix It Now!</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-meme-mastery-in-the-metaverse-a-comedic-journey/"><u>2024 Approved  Meme Mastery in the Metaverse  A Comedic Journey</u></a></li>
<li><a href="https://win11.techidaily.com/9-proven-remedies-for-perfectly-printing-your-powerpoint-presentations-in-windows/"><u>9 Proven Remedies for Perfectly Printing Your PowerPoint Presentations in Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-superrich-streamers-of-the-world/"><u>2024 Approved  Superrich Streamers of the World</u></a></li>
</ul></div>
