---
title: Where Are the Blue Screen of Death Log Files Located in Windows? Here's How to Read Them
date: 2024-08-16T00:45:10.489Z
updated: 2024-08-17T00:45:10.489Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Where Are the Blue Screen of Death Log Files Located in Windows? Here's How to Read Them
excerpt: This Article Describes Where Are the Blue Screen of Death Log Files Located in Windows? Here's How to Read Them
keywords: BSoD Log Locations,Find BSoD Files,Reading BSoD Logs,Windows Blue Screen Data,Accessing BSoD Error Files,Analyze BSoD Logs,Extract BSoD Information
thumbnail: https://thmb.techidaily.com/e24af9d0b47d7bf3dcde61ab73ef441dcda155d4ef5a243e1a2546d643282d46.jpg
---

## Where Are the Blue Screen of Death Log Files Located in Windows? Here's How to Read Them

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
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
3. In the following dialog, expand the dropdown for **Logged** and choose the time when you encountered the issue.  
![Check the logged section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/custom-time.jpg)
4. Now, move to the Event Level section and choose **Error**.  
![Event level of the error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/error-event-level.jpg)
5. Expand the dropdown for **Event Logs** and checkmark the box for **Windows Logs**.  
![Choose Windows logs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/windows-logs.jpg)

1. Click **OK** to proceed.
2. You will now be prompted to enter a name and description for the custom view you just created. Enter these details and click **OK**.  
![Create a filter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/name-event-viewer.jpg)
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Once the view is created, you will be presented with a list of errors that occurred during the time frame you selected earlier. You can sort this information further in the Date and time section.  
![Check the Event Viewer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/event-viewer-11.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
4. Next, locate the BSOD using details like the date and time again.
5. Once you find the targeted log, click on it.
6. Check both the General and Details tabs to get information about this error.

 Once you find the error code associated with the crash and the cause, you can look for solutions online, or head over to our guide that discusses [how to fix blue screen errors in Windows](https://www.makeuseof.com/tag/4-tips-fix-blue-screen-error/) if it's a bsod.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
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
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click on **Maintenance** and then select **View reliability history**.  
![Check the reliability history of the system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/view-realability-history.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
4. You should now see a graph showing the reliability data. Look for red cross icons and blue (i) icons in the graph, as they show problematic events.  
![Reliability graph](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/realability-graph.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-discovering-your-favorite-makeup-vloggers-on-youtube-for-2024/"><u>[New] Discovering Your Favorite Makeup Vloggers on YouTube for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-flawless-soundscapes-in-the-world-of-social-media-videos/"><u>[Updated] 2024 Approved  Flawless Soundscapes in the World of Social Media Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-fusion-functionality-combining-watch-mac-access/"><u>[Updated] Fusion Functionality  Combining Watch, Mac Access</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-cloud-storage-top-picks-revealed/"><u>[Updated] Mastering Cloud Storage – Top Picks Revealed</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-how-to-make-fortnite-thumbnail-for-free-and-easy/"><u>2024 Approved  How to Make Fortnite Thumbnail for Free and Easy</u></a></li>
<li><a href="https://win11.techidaily.com/30-days-in-football-fantasy-how-to-play-ocm-for-no-charge/"><u>30 Days in Football Fantasy: How to Play OCM for No Charge</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-repair-the-net-framework-on-windows/"><u>5 Ways to Repair the .NET Framework on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/8-things-to-remember-before-you-clean-install-windows/"><u>8 Things to Remember Before You Clean Install Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-microsoft-family-safety-tools/"><u>A Deep Dive Into Microsoft Family Safety Tools</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-downloads-utorrents-secrets-to-speedier-win-os-files/"><u>Accelerating Downloads: UTorrent's Secrets to Speedier WIN OS Files</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-keystrokes-mastery-via-typingaid/"><u>Accelerating Keystrokes: Mastery via TypingAid</u></a></li>
<li><a href="https://win11.techidaily.com/access-banishment-4-streamlined-steps-for-stripping-win11-of-users/"><u>Access Banishment: 4 Streamlined Steps for Stripping Win11 of Users</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-phone-dialer-in-windows-11/"><u>Accessing Phone Dialer in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/activatedeactivate-fingerwriting-in-windows-system/"><u>Activate/Deactivate Fingerwriting in Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-nvidia-software-connection-failure-in-os-x/"><u>Addressing NVIDIA Software Connection Failure in OS X</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-secure-boot-grayout-windows-bios-fix-guide/"><u>Addressing Secure Boot Grayout: Windows BIOS Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-unsuccessful-java-vm-startup/"><u>Addressing the Unsuccessful Java VM Startup</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-desktop-date-and-time-a-win-1011-guide/"><u>Adjusting Desktop Date & Time: A Win 10/11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/automatic-empty-recycle-bin-in-windows-step-by-step/"><u>Automatic Empty Recycle Bin in Windows Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-update-failure-code-0x800f0845/"><u>Avoiding Update Failure - Code 0X800F0845</u></a></li>
<li><a href="https://win11.techidaily.com/bargain-bonanza-black-friday-612-for-lifelong-win10-life/"><u>Bargain Bonanza: Black Friday - $6.12 for Lifelong Win10 Life</u></a></li>
<li><a href="https://win11.techidaily.com/battle-the-bake-off-effective-tactics-to-reduce-gaming-laptops-temperature/"><u>Battle the Bake-Off: Effective Tactics to Reduce Gaming Laptop’s Temperature</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-error-x80072f30-in-microsoft-store-on-windows/"><u>Breaking Down Error X80072F30 in Microsoft Store on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-exepe-file-formats/"><u>Breaking Down Windows EXE/PE File Formats</u></a></li>
<li><a href="https://win11.techidaily.com/1719362389609-determining-cpu-version-on-windows-here-are-8-ways/"><u>Determining CPU Version on Windows – Here Are 8 Ways</u></a></li>
<li><a href="https://fox-glue.techidaily.com/ditch-dullness-boosting-speed-in-android-videos/"><u>Ditch Dullness  Boosting Speed in Android Videos</u></a></li>
<li><a href="https://win11.techidaily.com/1719369059725-streamline-facebook-messenger-on-your-pc-now/"><u>Streamline Facebook Messenger On Your PC Now!</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/trouble-with-iphone-15-plus-swipe-up-try-these-11-solutions-drfone-by-drfone-ios/"><u>Trouble with iPhone 15 Plus Swipe-Up? Try These 11 Solutions | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/understanding-instagram-video-count-constraints-for-2024/"><u>Understanding Instagram  Video Count Constraints for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-how-to-mute-audio-from-video-for-2024/"><u>Updated How to Mute Audio From Video for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-mastering-audio-transitions-2-methods-for-fading-in-and-out-in-final-cut-pro/"><u>Updated Mastering Audio Transitions 2 Methods for Fading In and Out in Final Cut Pro</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>