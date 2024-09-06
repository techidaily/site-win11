---
title: "Unlocking Blue Screen Mysteries: Where Are the Logs?"
date: 2024-09-05T08:39:44.718Z
updated: 2024-09-06T08:39:44.718Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129739/7443" target="_top" id="2129739">
  <img src="//a.impactradius-go.com/display-ad/7443-2129739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129739/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Create a custom view in the Event viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/create-custom-view.jpg)
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115938/19272" target="_top" id="2115938">
  <img src="//a.impactradius-go.com/display-ad/19272-2115938" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115938/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  
![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123509/26400" target="_top" id="2123509">
  <img src="//a.impactradius-go.com/display-ad/26400-2123509" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123509/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
4. Next, locate the BSOD using details like the date and time again.
<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Once you find the targeted log, click on it.
6. Check both the General and Details tabs to get information about this error.

 Once you find the error code associated with the crash and the cause, you can look for solutions online, or head over to our guide that discusses [how to fix blue screen errors in Windows](https://www.makeuseof.com/tag/4-tips-fix-blue-screen-error/) if it's a bsod.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136613/26400" target="_top" id="2136613">
  <img src="//a.impactradius-go.com/display-ad/26400-2136613" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136613/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<!-- affiliate ads begin -->
<span id="1265663">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1265663.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/4482-1265663">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1265663.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmartinic.evyy.net%2Fc%2F5597632%2F1265663%2F4482'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1265663/4482" style="position:absolute;visibility:hidden;" border="0" />
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
![Check the reliability history of the system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/view-realability-history.jpg)
4. You should now see a graph showing the reliability data. Look for red cross icons and blue (i) icons in the graph, as they show problematic events.  
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139118/17108" target="_top" id="2139118">
  <img src="//a.impactradius-go.com/display-ad/17108-2139118" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139118/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://digital-screen-recording.techidaily.com/new-achieving-seamless-group-discussions-in-google-chat-for-2024/"><u>[New] Achieving Seamless Group Discussions in Google Chat for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ree-youtube-image-saver-compilation/"><u>[New] Free YouTube Image Saver Compilation</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-how-to-transition-your-facebook-vids-into-stellar-hd-for-2024/"><u>[Updated] How to Transition Your Facebook Vids Into Stellar HD for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-sifting-through-cloud-costs-for-maximum-savings/"><u>[Updated] Sifting Through Cloud Costs for Maximum Savings</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-timely-team-setups-adjusting-backdrop-beforeafter-calls/"><u>[Updated] Timely Team Setups  Adjusting Backdrop Before/After Calls</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-googles-revolutionary-approach-to-speech-interpretation/"><u>2024 Approved  Google's Revolutionary Approach to Speech Interpretation</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unveiling-5-excellent-mac-livestream-software/"><u>2024 Approved  Unveiling 5 Excellent Mac Livestream Software</u></a></li>
<li><a href="https://win11.techidaily.com/correct-mend-f-keys-on-windows-11-regain-control/"><u>Correct: Mend F Keys on Windows 11, Regain Control</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-realme-c67-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Realme C67 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/easily-modify-windows-11-highlight-features/"><u>Easily Modify Windows 11 Highlight Features</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-game-optimal-adventure-play-in-full-hd-via-windows-and-scummvm/"><u>Elevate Your Gaming Game: Optimal Adventure Play in Full HD via Windows & ScummVM</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-pcs-space-top-7-free-volume-enhancers-for-windows/"><u>Elevate Your PC's Space: Top 7 Free Volume Enhancers for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-vlc-experience-fixing-lag-and-buffering-issues/"><u>Enhancing VLC Experience: Fixing Lag and Buffering Issues</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-filing-techniques-max-156/"><u>Essential Windows Filing Techniques (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/five-gone-windows-feature-retrospective/"><u>Five Gone: Windows Feature Retrospective</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-error-code-0x80070522-secure-privilege-protocol-in-windows/"><u>Fixing Error Code 0X80070522: Secure Privilege Protocol in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-discord-overlay-failure-a-step-by-step-guide/"><u>Fixing Windows Discord Overlay Failure: A Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-itel-s23plus-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Itel S23+ Without Password | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-sidestep-windows-11-screensaver-quickly/"><u>How to Sidestep Windows 11 Screensaver Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-actions-to-mend-windows-office-errors/"><u>Immediate Actions to Mend Windows Office Errors</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-gionee-f3-pro-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Gionee F3 Pro to Apple TV | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-repair-tool-access-crafting-shortcuts-for-win-1011/"><u>Mastering Repair Tool Access: Crafting Shortcuts for Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/mimicking-macos-layout-in-windows-5-essential-tweaks/"><u>Mimicking macOS Layout in Windows: 5 Essential Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-high-load-on-cpu-by-wlanextexe/"><u>Mitigating High Load on CPU by Wlanext.exe</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-xbox-console-choices-and-installation/"><u>Navigating Xbox Console Choices and Installation</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-the-most-advanced-linux-audio-editors-reviewed-find-your-ideal-tool/"><u>New 2024 Approved The Most Advanced Linux Audio Editors Reviewed Find Your Ideal Tool</u></a></li>
<li><a href="https://win11.techidaily.com/playnite-enhancement-embracing-emulated-titles/"><u>Playnite Enhancement: Embracing Emulated Titles</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/pokemon-go-cooldown-chart-on-honor-90-lite-drfone-by-drfone-virtual-android/"><u>Pokémon Go Cooldown Chart On Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/polish-language-jumpstarting-guide/"><u>Polish Language Jumpstarting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-errors-validating-windows-11-temporary-folder/"><u>Preventing Errors: Validating Windows 11 Temporary Folder</u></a></li>
<li><a href="https://buynow-info.techidaily.com/professional-artists-choice-the-ultimate-review-of-huion-inspiroy-g10t-for-impeccable-design-and-performance/"><u>Professional Artists' Choice - The Ultimate Review of Huion Inspiroy G10T for Impeccable Design & Performance</u></a></li>
<li><a href="https://win11.techidaily.com/propelling-linux-with-powerful-windows-integration/"><u>Propelling Linux with Powerful Windows Integration</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolve-windows-os-not-found-issue/"><u>Quick Guide to Resolve Windows OS Not Found Issue</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/save-big-on-high-performance-chips-premium-deals-for-intel-and-amd-cpus-this-year/"><u>Save Big on High-Performance Chips: Premium Deals for Intel and AMD CPUs This Year</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocketing-android-studio-speed-on-your-windows-machine/"><u>Skyrocketing Android Studio Speed on Your Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-diagnostics-error-on-pc/"><u>Solutions for Fixing 'Diagnostics Error' On PC</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-tweaking-proxy-settings-in-windows-11/"><u>Step-by-Step Guide to Tweaking Proxy Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-journey-through-original-diablo/"><u>Step-by-Step Journey Through Original Diablo</u></a></li>
<li><a href="https://win11.techidaily.com/the-hidden-dangers-opting-for-budgeted-windows-auth-keys/"><u>The Hidden Dangers: Opting for Budgeted Windows Auth Keys</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-affordable-drivers-to-elevate-your-windows-system/"><u>Top 5 Affordable Drivers to Elevate Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/top-strategies-for-a-smoothly-running-google-drive-in-windows/"><u>Top Strategies for a Smoothly Running Google Drive in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-11-resolving-unreachable-network-issues/"><u>Troubleshooting Windows 11: Resolving Unreachable Network Issues</u></a></li>
<li><a href="https://win11.techidaily.com/uninstalling-wsl-an-all-inclusive-guide/"><u>Uninstalling WSL: An All-Inclusive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-productivity-dragging-and-dropping-tabs-windows-11-style/"><u>Unleashing Productivity: Dragging and Dropping Tabs, Windows 11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/why-and-how-to-ditch-integrated-video-on-windows/"><u>Why and How to Ditch Integrated Video on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-slowdown-beneath-calm-exteriors-lurk-resource-hogging-tools/"><u>Windows 11 Slowdown: Beneath Calm Exteriors Lurk Resource Hogging Tools</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-work-select-time-management-tools-for-enhanced-efficiency/"><u>Winning at Work: Select Time Management Tools for Enhanced Efficiency</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>