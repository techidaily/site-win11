---
title: Bypassing 'Service Failed' Errors on Disk Management
date: 2025-02-10T21:10:57.390Z
updated: 2025-02-16T02:50:54.935Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing 'Service Failed' Errors on Disk Management
excerpt: This Article Describes Bypassing 'Service Failed' Errors on Disk Management
keywords: Disable Service Fails,Disk Error Bypass,Fix Service Fail,Manage Disk No Error,Override Service Fail,Remove Disk Errors,Eliminate System Break,Service Fail Resolve,Disk Error Fixing,No-Error Management,Bypass System Fails,Avoiding Disk Disruption,Stop Service Interruptions,Remove System Crashes
thumbnail: https://thmb.techidaily.com/a08727f11a7832f787474e1a64a135e87ab43cd2d3040a1084f509333c65c397.jpg
---

## Bypassing 'Service Failed' Errors on Disk Management

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
4. Select the **Automatic** setting on the **Startup type** menu.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
5. Press **Start** within the Virtual Disk Properties window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-posts.techidaily.com/updated-comprehensive-guide-to-advanced-fcp-features-for-2024/"><u>[Updated] Comprehensive Guide to Advanced FCP Features for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-free-video-fiddling-unleash-potential-with-vimeo-editing-for-2024/"><u>[Updated] Free Video Fiddling Unleash Potential with Vimeo Editing for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-tap-into-tagging-techniques-for-6kplus-youtube-vistas-for-2024/"><u>[Updated] Tap Into #Tagging Techniques for $6K+ YouTube Vistas for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-master-the-art-of-time-extension-creating-stunningly-slow-mo-video-online/"><u>2024 Approved Master the Art of Time Extension Creating Stunningly Slow-Mo Video Online</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-drive-space-a-comprehensible-guide-to-using-diskusage-commands/"><u>Decoding Drive Space: A Comprehensible Guide to Using DiskUsage Commands</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-to-rectify-server-stumbled-issues-on-windows/"><u>Efficient Methods to Rectify Server Stumbled Issues on Windows</u></a></li>
<li><a href="https://solve-lab.techidaily.com/expert-tips-on-fixing-memory-glitches-a-comprehebly-by-yl-software-experts/"><u>Expert Tips on Fixing Memory Glitches: A Comprehebly by YL Software Experts</u></a></li>
<li><a href="https://some-tips.techidaily.com/get-the-cutting-edge-13-inch-macbook-air-m2-for-a-record-low-this-cyber-monday-tech-insights-revealed/"><u>Get the Cutting-Edge 13-Inch MacBook Air (M2) for a Record Low This Cyber Monday – Tech Insights Revealed!</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-bypassing-missing-windows-logins-on-pcs/"><u>Guide to Bypassing Missing Windows Logins on PCs</u></a></li>
<li><a href="https://some-techniques.techidaily.com/hot-hands-on-10-must-have-vr-peripherals-for-2024/"><u>Hot Hands-On 10 Must-Have VR Peripherals for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/inside-scoop-on-the-upcoming-iphone-cost-guesswork-projected-release-moment-and-technical-insights/"><u>Inside Scoop on the Upcoming iPhone 지판: Cost Guesswork, Projected Release Moment & Technical Insights</u></a></li>
<li><a href="https://win11.techidaily.com/insights-on-ignoring-notifications-risks-of-silencing-wins-11/"><u>Insights on Ignoring Notifications: Risks of Silencing Wins 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/installing-fresh-canon-mg3000-drivers-for-optimal-print-performance/"><u>Installing Fresh Canon MG3000 Drivers for Optimal Print Performance</u></a></li>
<li><a href="https://win11.techidaily.com/open-local-group-policy-quick-and-secure-methods-on-win11/"><u>Open Local Group Policy: Quick and Secure Methods on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-eradicating-directdraw-failures-on-win1011-systems/"><u>Quick Guide: Eradicating DirectDraw Failures on WIN10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-winerror-0xc0000005-in-windows-systems/"><u>Resolving WinError 0Xc0000005 in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-resuming-lost-remote-access-in-windows/"><u>Strategies for Resuming Lost Remote Access in Windows</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/s-that-you-should-know-about-youtube-keyword-research-for-2024/"><u>Things That You Should Know About YouTube Keyword Research for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win11-anomaly-correction-controlling-a-roaming-pointer/"><u>Win11 Anomaly Correction: Controlling a Roaming Pointer</u></a></li>
</ul></div>

