---
title: Unveiling BSOD Log Files in Microsoft OS
date: 2024-09-01T04:36:55.868Z
updated: 2024-09-02T04:36:55.868Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling BSOD Log Files in Microsoft OS
excerpt: This Article Describes Unveiling BSOD Log Files in Microsoft OS
keywords: BSOD Logs Decoded,Windows Blue Screen Analysis,Debugging BSOD Errors,MSOS BSOD Troubleshooting,BSOD Data Files Extraction,Microsoft OS Crash Reports,Unraveling BSOD Codes
thumbnail: https://thmb.techidaily.com/4c1a39277ea3313859b9362ca2031ca0eab790234cc40f347849f915f7ea8138.jpg
---

## Unveiling BSOD Log Files in Microsoft OS

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

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
8. Under Value data, type 1 and click **OK**.  
![Change the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/value-data-1.jpg)
9. Once done, restart your PC.
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
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
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Check the reliability history of the system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/view-realability-history.jpg)
4. You should now see a graph showing the reliability data. Look for red cross icons and blue (i) icons in the graph, as they show problematic events.  
![Reliability graph](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/realability-graph.jpg)
5. Click on each of the icons to view its details. Keep repeating the process to locate the event you are looking for.
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->

 You will be presented with information like the faulting application path, its name, fault module timestamp, exception code, etc. If this app caused a BSOD crash, then you can try ending its process via the Task Manager or uninstalling the app if it is not necessary.

 It is also a good idea to copy this information and send it to Microsoft for review if you cannot find a solution online.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
## Learn How to Read Your BSOD Log Files and Resolve Your Crashes

 ​​​​​​Windows blue screen errors are nothing new, but since they only display messages like "Your PC encountered a problem" without describing the cause, it can be difficult to find a fix. Understanding how to read BSOD log files can not only help you identify the exact cause of the problem but also help you find the right solution.

 Whenever a component causes your system to crash, you can disable it and switch to a better alternative to avoid the problem.

 In this guide, we will first discuss where are the BSOD files located in Windows and then how to identify them. Once you have located a BSOD file, we will show you how to read it properly to understand the potential causes of the error and resolve the problem.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-masterclass-emulation-best-ps3-clones-on-your-computer/"><u>[New] 2024 Approved  Masterclass Emulation  Best PS3 Clones on Your Computer</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-exploring-the-world-of-youtube-channel-naming-innovative-ideas-for-vloggers-and-filmmakers-no-more-than-156-characters-for-2024/"><u>[New] Exploring the World of YouTube Channel Naming  Innovative Ideas For Vloggers & Filmmakers (No More than 156 Characters) for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-pro-gamers-equipment-showcase-series/"><u>[New] In 2024, Pro Gamer's Equipment Showcase Series</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-navigating-the-dynamics-of-instagram-highlight-categories/"><u>[New] Navigating the Dynamics of Instagram Highlight Categories</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-pinnacle-of-editing-reviewing-movavi-pro-video-2024plus/"><u>[New] The Pinnacle of Editing  Reviewing Movavi Pro Video 2024+</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-advanced-zoom-strategies-for-clarity-in-web-meetings/"><u>[Updated] Advanced Zoom Strategies for Clarity in Web Meetings</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-highest-quality-capture-options-for-2024/"><u>[Updated] Highest Quality Capture Options for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-effortless-mp4-conversion-from-facebook-hd-content-all-for-free/"><u>[Updated] In 2024, Effortless MP4 Conversion From Facebook HD Content – All For Free</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-investigating-the-effectiveness-of-vsdcs-screen-capture-tech/"><u>[Updated] In 2024, Investigating the Effectiveness of VSDC's Screen Capture Tech</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-viewsplit-diagnostics/"><u>[Updated] In 2024, ViewSplit Diagnostics</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-simplify-passport-photography-with-these-top-10-low-cost-solutions/"><u>[Updated] Simplify Passport Photography with These Top 10 Low-Cost Solutions</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-the-ultimate-srt-download-blueprint-from-youtube/"><u>[Updated] The Ultimate SRT Download Blueprint From YouTube</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-techniques-for-accelerating-playback-on-spotify/"><u>2024 Approved  Techniques for Accelerating Playback on Spotify</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-lava-yuva-3-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Lava Yuva 3 to Roku | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/comparing-steam-and-gog-game-distribution-analysis/"><u>Comparing Steam & GOG: Game Distribution Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-windows-ram-cache/"><u>Comprehensive Guide to Window’s RAM Cache</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-erasing-your-windows-11-actions-trail/"><u>Decoding and Erasing Your Windows 11 Actions Trail</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-vcplusplus-distribution-essence/"><u>Decoding VC++ Distribution Essence</u></a></li>
<li><a href="https://win11.techidaily.com/ease-into-windows-11-troubleshooting-update-issue-0x30017/"><u>Ease Into Windows 11: Troubleshooting Update Issue #0X30017</u></a></li>
<li><a href="https://win11.techidaily.com/easing-expiry-headache-fixing-windows-license-alarms/"><u>Easing Expiry Headache: Fixing Windows License Alarms</u></a></li>
<li><a href="https://win11.techidaily.com/empowered-windows-operations-advanced-run-enhancements-guide/"><u>Empowered Windows Operations: Advanced Run Enhancements Guide</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-effective-email-delivery-feedback-on-windows-machines/"><u>Enabling Effective Email Delivery Feedback on Windows Machines</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-accessibility-custom-pin-lengths-for-windows-users/"><u>Enhance Accessibility: Custom PIN Lengths for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/essential-preparations-what-you-need-prior-to-windows-overhaul/"><u>Essential Preparations: What You Need Prior To Windows Overhaul</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-for-simultaneous-wi-fi-and-ethernet-use-in-windows/"><u>Expert Advice for Simultaneous Wi-Fi & Ethernet Use in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-efficient-installation-of-msixbundle-and-apppackages-from-microsoft-store/"><u>Fast Track: Efficient Installation of MSixbundle & Apppackages From Microsoft Store</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-tecno-spark-10-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/get-the-best-of-linux-ditch-wsl/"><u>Get the Best of Linux - Ditch WSL</u></a></li>
<li><a href="https://win11.techidaily.com/harness-tdarr-to-multiply-windows-pc-video-conversion-efficiency/"><u>Harness Tdarr to Multiply Window's PC Video Conversion Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-error-code-0x80004004-in-defender/"><u>How to Address Error Code 0X80004004 in Defender</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-front-seat-escapades-beyond-athletic-viewing/"><u>In 2024, Front Seat Escapades Beyond Athletic Viewing</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-heimdalls-vigil-gods-clash-in-ragnarok/"><u>In 2024, Heimdall's Vigil  Gods Clash in Ragnarok</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-smooth-gameplay-essential-tips-to-resolve-2024s-dota-2-latency-problems/"><u>Mastering Smooth Gameplay: Essential Tips to Resolve 2024'S Dota 2 Latency Problems</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-vector-editing-without-acid-pro-for-2024/"><u>Mastering Vector Editing without ACID Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-win11-startup-efficiency/"><u>Maximizing Win11 Startup Efficiency</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-in-this-article-you-will-find-ten-of-the-best-and-most-trusted-video-editing-applications-that-do-support-4k-videos-including-both-free-4k-and-paid-4k-v/"><u>New In This Article, You Will Find Ten of the Best and Most Trusted Video Editing Applications that Do Support 4K Videos, Including Both Free 4K and Paid 4K Video Editing Software for You to Choose</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-spotify-crash-in-windows-11-without-it-help/"><u>Overcoming Spotify Crash in Windows 11 without IT Help</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-taskbar-concealment-when-maximizing-browser/"><u>Overcoming Taskbar Concealment When Maximizing Browser</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-mcuicnt-execution-error-on-modern-windows-pcs/"><u>Overhauling McUICnt Execution Error on Modern Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/pros-choice-top-video-trimming-apps-for-windows-pcs/"><u>Pro's Choice: Top Video Trimming Apps for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/quantifying-storage-quotient-for-windows-programs/"><u>Quantifying Storage Quotient for Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-stopping-windows-11-from-running/"><u>Quick Fixes: Stopping Windows 11 From Running</u></a></li>
<li><a href="https://win11.techidaily.com/reimagining-vintage-windows-pcs-for-elders/"><u>Reimagining Vintage Windows PCs for Elders</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-steams-unavailable-content-servers-issue-on-pc/"><u>Resolving Steam's Unavailable Content Servers Issue on PC</u></a></li>
<li><a href="https://win11.techidaily.com/revert-to-regular-contrast-on-windows/"><u>Revert to Regular Contrast on Windows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/safe-smart-conversations-engage-in-secure-duckduckgo-chat-and-companion-services/"><u>Safe, Smart Conversations: Engage in Secure DuckDuckGo Chat & Companion Services</u></a></li>
<li><a href="https://win11.techidaily.com/separating-the-sincere-from-the-spoof-in-the-windows-store/"><u>Separating the Sincere From the Spoof in the Windows Store</u></a></li>
<li><a href="https://win11.techidaily.com/smartly-sorted-7-preferred-windows-photos-apps/"><u>Smartly Sorted: 7 Preferred Windows Photos Apps</u></a></li>
<li><a href="https://win11.techidaily.com/staying-ahead-insights-into-windows-11s-enhanced-security-updates/"><u>Staying Ahead: Insights Into Windows 11'S Enhanced Security Updates</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-elevate-taskmanager-on-desktop/"><u>Strategies to Elevate TaskManager on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-performance-via-virtual-memory-adjustment-in-windows-11/"><u>Streamlining Performance via Virtual Memory Adjustment in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-ux-a-blueprint-of-essential-taskbar-amendments-in-windows-11/"><u>Streamlining UX: A Blueprint of Essential Taskbar Amendments in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-eliminate-autominimize-effects/"><u>Streamlining Windows: Eliminate AutoMinimize Effects</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/success-wnddevice-init-succeeded/"><u>Success: WndDevice Init Succeeded</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-perfect-balance-an-in-depth-look-at-the-google-pixel-4a-review/"><u>The Perfect Balance: An In-Depth Look at the Google Pixel 4a Review</u></a></li>
<li><a href="https://win11.techidaily.com/the-windows-11-22h2-moment-update-could-bring-7-exciting-features/"><u>The Windows 11 22H2 Moment Update Could Bring 7 Exciting Features</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-9-strategies-using-chatgpt-to-enhance-your-novel-writing-process/"><u>Top 9 Strategies: Using ChatGPT to Enhance Your Novel Writing Process</u></a></li>
<li><a href="https://win11.techidaily.com/transition-to-nighttime-paints-dark-aesthetics/"><u>Transition to Nighttime: Paint's Dark Aesthetics</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-the-ultimate-guide-to-windows-powertoy-features/"><u>Unleash Potential: The Ultimate Guide to Windows PowerToy Features</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-code-mastery-reclaiming-your-windows-1011-key/"><u>Unlock Code Mastery: Reclaiming Your Windows 10/11 Key</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-power-of-bulk-directory-formation-on-windows-10-and-11-systems/"><u>Unlock the Power of Bulk Directory Formation on Windows 10 & 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/win11-image-camouflage-techniques-for-zip-files/"><u>Win11 Image Camouflage Techniques for ZIP Files</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>