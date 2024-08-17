---
title: "Cracking the Code: Locating Blue Screens in Log Files"
date: 2024-08-16T00:53:20.968Z
updated: 2024-08-17T00:53:20.968Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Cracking the Code: Locating Blue Screens in Log Files"
excerpt: "This Article Describes Cracking the Code: Locating Blue Screens in Log Files"
keywords: Blue Screen Analysis,Log File Debugging,Error Codes Locator,System Crash Diagnostics,Code Decrypting Hints,Unraveling System Errors,Syslog Investigation Guide
thumbnail: https://thmb.techidaily.com/1f7a28a8bb8145eaefcf7bd927fe30950467d63b1317d80297e6274f57adb5a8.jpg
---

## Cracking the Code: Locating Blue Screens in Log Files

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
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
2. Head over to the **Action** menu located at the top, and choose **Create Custom View** from the context menu.  
![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  
![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  
![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)
<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
9. Once done, restart your PC.

 Upon reboot, you should be able to view the log files without any problems.

### 3\. Find and Read the BSOD Log Files in the Control Panel

 The third way of finding and reading the BSOD log files is via the Control Panel. This approach offers a graphical representation of the log files using the Windows Reliability Monitor, unlike the methods we have explored previously.

 The Reliability Monitor, which is different than the Performance Monitor (see [Reliability Monitor vs. Performance Monitor](https://www.makeuseof.com/reliability-monitor-vs-performance-monitor/)) will show you a timeline of important system events that occurred on your computer including BSOD occurrences, software installations, application crashes, and other relevant events.

 Here is how you can use it to identify and fix problems that may affect your system:

1. Type Control Panel in the search area of the taskbar and click **Open**.
2. In the following window, choose **System and Security** \> **Security and Maintenance**.  
![Security and maintenance settings in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/security-maintenance.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
3. Click on **Maintenance** and then select **View reliability history**.  
![Check the reliability history of the system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/view-realability-history.jpg)
4. You should now see a graph showing the reliability data. Look for red cross icons and blue (i) icons in the graph, as they show problematic events.  
![Reliability graph](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/realability-graph.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Click on each of the icons to view its details. Keep repeating the process to locate the event you are looking for.

 You will be presented with information like the faulting application path, its name, fault module timestamp, exception code, etc. If this app caused a BSOD crash, then you can try ending its process via the Task Manager or uninstalling the app if it is not necessary.

 It is also a good idea to copy this information and send it to Microsoft for review if you cannot find a solution online.

## Learn How to Read Your BSOD Log Files and Resolve Your Crashes

 ​​​​​​Windows blue screen errors are nothing new, but since they only display messages like "Your PC encountered a problem" without describing the cause, it can be difficult to find a fix. Understanding how to read BSOD log files can not only help you identify the exact cause of the problem but also help you find the right solution.

 Whenever a component causes your system to crash, you can disable it and switch to a better alternative to avoid the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-2023s-approach-tweeting-from-tiktok/"><u>[New] In 2024, 2023'S Approach  Tweeting From TikTok</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-reassert-true-look-corrected-video-error-for-2024/"><u>[New] Reassert True Look  Corrected Video Error for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-steps-to-post-music-on-social-media-stories-for-2024/"><u>[Updated] Steps to Post Music on Social Media Stories for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-top-youtube-concepts-for-channel-motivation-and-creativity/"><u>[Updated] Top YouTube Concepts for Channel Motivation and Creativity</u></a></li>
<li><a href="https://win11.techidaily.com/15-key-improvements-added-to-windows-11s-next-version/"><u>15 Key Improvements Added to Windows 11'S Next Version</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-tactics-for-effective-whatsapp-broadcast-with-facebook-videos/"><u>2024 Approved  Tactics for Effective WhatsApp Broadcast with Facebook Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-transforming-gifs-to-stickers-comprehensive-instruction-for-messaging-apps/"><u>2024 Approved  Transforming GIFs to Stickers  Comprehensive Instruction for Messaging Apps</u></a></li>
<li><a href="https://win11.techidaily.com/3-effective-methods-to-enhance-windows-ram-usage/"><u>3 Effective Methods to Enhance Windows' RAM Usage</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-factory-reset-your-windows-computer/"><u>3 Ways to Factory Reset Your Windows Computer</u></a></li>
<li><a href="https://win11.techidaily.com/4-fixes-to-try-if-windows-wont-use-all-of-your-ram/"><u>4 Fixes to Try if Windows Won't Use All of Your RAM</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-run-the-program-compatibility-troubleshooter-on-windows/"><u>4 Ways to Run the Program Compatibility Troubleshooter on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/5-essential-time-saving-pc-apps-for-dynamic-desktop-screensavers/"><u>5 Essential Time-Saving PC Apps for Dynamic Desktop Screensavers</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-open-the-file-or-folder-properties-in-windows/"><u>6 Ways to Open the File or Folder Properties in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-open-the-sound-settings-in-windows-11/"><u>9 Ways to Open the Sound Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-compre-written-by-chloe-miller/"><u>A Compre Written by Chloe Miller</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-look-at-windows-vulnerability-alerts/"><u>A Comprehensive Look at Windows’ Vulnerability Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-walkthrough-of-ms-error-lookup-in-w11/"><u>A Comprehensive Walkthrough of MS Error Lookup in W11</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-entering-your-folder-of-apps-in-windows-11/"><u>A Step-by-Step Guide to Entering Your Folder of Apps in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-microphone-experience-with-win-11s-voice-shortcuts/"><u>Accelerate Your Microphone Experience with Win 11'S Voice Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-finances-with-windows-11-pro-discounts/"><u>Ace Your Finances with Windows 11 Pro Discounts</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-adobe-acquisition-through-microsofts-marketplace/"><u>Achieving Adobe Acquisition Through Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-ai-assistant-via-vivetool/"><u>Activating Windows AI Assistant via ViveTool</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-critical-roblox-programming-mistakes/"><u>Addressing Critical Roblox Programming Mistakes</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disappearances-in-file-explorer/"><u>Addressing Disappearances in File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-memory-shortage-in-the-magical-school-of-hogwarts-game/"><u>Addressing Memory Shortage in The Magical School of Hogwarts Game</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-printer-disconnection-on-windows-11-devices/"><u>Addressing Printer Disconnection on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-system-restore-problem-code-0x80780119/"><u>Addressing System Restore Problem: Code 0X80780119</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-lock-screen-delay-anomaly/"><u>Addressing Windows Lock Screen Delay Anomaly</u></a></li>
<li><a href="https://win11.techidaily.com/altering-the-native-pdf-reader-setup-in-windows/"><u>Altering the Native PDF Reader Setup in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/alternative-solutions-starting-your-software-on-windows-effortlessly/"><u>Alternative Solutions: Starting Your Software on Windows Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/android-ios-direct-pc-file-access/"><u>Android-iOS: Direct PC File Access</u></a></li>
<li><a href="https://win11.techidaily.com/automating-jpeg-creation-from-heic-images/"><u>Automating JPEG Creation From HEIC Images</u></a></li>
<li><a href="https://win11.techidaily.com/averting-error-22-disable-situation-in-windows-11-settings/"><u>Averting Error 22 Disable Situation in Windows 11 Settings</u></a></li>
<li><a href="https://win11.techidaily.com/away-from-clouds-data-at-your-fingertips-onedrive-tutorial/"><u>Away From Clouds, Data at Your Fingertips - OneDrive Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-utilities-convert-any-media-file/"><u>Best Windows Utilities Convert Any Media File</u></a></li>
<li><a href="https://win11.techidaily.com/boost-performance-using-ntfs-file-compression-wisely/"><u>Boost Performance: Using NTFS File Compression Wisely</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-efficiency-with-dev-drive-on-the-latest-windows-11-release/"><u>Boosting Efficiency with Dev Drive on the Latest Windows 11 Release</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-1011-how-to-bypass-pin-locks/"><u>Breaking Down Windows 10/11: How to Bypass PIN Locks</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/dont-skip-this-weeks-hot-tiktok-tests-for-2024/"><u>Don't Skip This Week's Hot TikTok Tests for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-itel-p55t-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Itel P55T | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/image-enhancement-101-text-addition-for-pc-and-mac-users/"><u>Image Enhancement 101  Text Addition for PC and Mac Users</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-meizu-21-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use GPS Joystick to Fake GPS Location On Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-14-pro-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 14 Pro With an Apple Watch & What to Do if It Doesnt Work | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-infinix-hot-30i-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Infinix Hot 30i Device</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722963875225-latest-steelseries-controller-drivers-available-for-free-get-your-downloads-here/"><u>Latest SteelSeries Controller Drivers Available for Free - Get Your Downloads Here!</u></a></li>
<li><a href="https://win11.techidaily.com/1719361199591-navigating-and-fixing-non-operational-printer-feature-via-wwinplusp-in-windows/"><u>Navigating and Fixing Non-Operational Printer Feature via WWin+P in Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/nows-vr-tech-landscape/"><u>Now’s VR Tech Landscape</u></a></li>
<li><a href="https://facebook.techidaily.com/simplifying-social-gatherings-with-facebook-portal-tv/"><u>Simplifying Social Gatherings with Facebook Portal TV</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/tech-savvy-summit-unveiling-our-top-5-video-capture-tools/"><u>Tech-Savvy Summit  Unveiling Our Top 5 Video Capture Tools</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-ultimate-evaluation-of-the-oneplus-nord-n10-5g-device-definitely-worth-your-attention/"><u>The Ultimate Evaluation of the OnePlus Nord N10 5G Device – Definitely Worth Your Attention</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-10-live-broadcast-gaming-applications-for-2024/"><u>Top 10 Live Broadcast Gaming Applications for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-fixing-a-non-responsive-laptop-trackpad-issue/"><u>Ultimate Guide: Fixing a Non-Responsive Laptop Trackpad Issue</u></a></li>
<li><a href="https://win11.techidaily.com/1719369400663-unleash-the-true-power-of-windows-screen-capture-toolkit/"><u>Unleash the True Power of Windows' Screen Capture Toolkit</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unlocking-audacitys-full-potential-for-professional-audio-for-2024/"><u>Unlocking Audacity's Full Potential for Professional Audio for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/unveiling-your-own-distinctive-tiktok-stream-key/"><u>Unveiling Your Own Distinctive TikTok Stream Key</u></a></li>
<li><a href="https://win-answers.techidaily.com/yakuza-like-a-dragon-now-fully-functional-and-ready-for-gaming-enthusiasts/"><u>Yakuza: Like a Dragon - Now Fully Functional and Ready for Gaming Enthusiasts</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>