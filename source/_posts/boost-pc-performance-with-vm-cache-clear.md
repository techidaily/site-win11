---
title: Boost PC Performance with VM Cache Clear
date: 2024-06-25T11:37:45.908Z
updated: 2024-06-26T11:37:45.908Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Boost PC Performance with VM Cache Clear
excerpt: This Article Describes Boost PC Performance with VM Cache Clear
keywords: Boost PC Speed,Enhance Computer PERF,Optimize System BOOST,Increase PC EFFICIENCY,Accelerate PC SPEED,Improve System PERFORMANCE,Enhance CPU Performance
thumbnail: https://thmb.techidaily.com/a8a2eae7840110809ce01981ae6ddd7381e7680b0d93e29805eecd4b92108f79.jpg
---

## Boost PC Performance with VM Cache Clear

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

## What Is Virtual Memory and How Does It Work?

 Virtual memory, also known as a paging file, is a technology used in computers to allow programs to use more memory than what's physically available on it. When you run out of RAM, your operating system relies on virtual memory to continue running programs.

 The computer creates a special file called a page or swap file on the hard drive. It stores some data temporarily removed from RAM and written to the hard drive. This way, the computer can access more memory than what's installed.

 Although virtual memory allows programs to operate smoothly, it can also hurt overall performance. For example, if your computer runs out of RAM, it will use more of the hard drive to store data. This also significantly slows overall performance as HDDs and SSDs are much slower than RAM.

 Let's now see how to reset Virtual Memory on Windows.

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

## Reset Virtual Memory To Get Better Performance

 Resetting virtual memory settings improves Windows computer performance. This guide introduces three methods to learn how to reset virtual memory on Windows. Give it a try and see which methods work best for you. If you face any issues while doing this, you can always use system restore to revert to the previous settings.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/discover-your-ip-command-prompt-guide-for-pcs/"><u>Discover Your IP: Command Prompt Guide for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-windows-11-search-backup-procedure/"><u>Navigate to Windows 11 Search Backup Procedure</u></a></li>
<li><a href="https://win11.techidaily.com/1719301836134-clear-and-confident-windows-viewing-top-6-fixes-now/"><u>Clear and Confident Windows Viewing: Top 6 Fixes Now!</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-11-desktop-tips-on-interactive-and-dynamic-walls/"><u>Transform Windows 11 Desktop: Tips on Interactive and Dynamic Walls</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-infinitely-stop-microsoft-defender-in-windows/"><u>How to Infinitely Stop Microsoft Defender in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/winirq-fixing-killer-soundsystem-problems/"><u>WinIRQ: Fixing Killer Soundsystem Problems</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-overcoming-onedrive-errors-on-windows/"><u>Winning at Overcoming OneDrive Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/powerful-tactics-for-using-windows-explorer-not-ls/"><u>Powerful Tactics for Using Windows Explorer, Not LS</u></a></li>
<li><a href="https://win11.techidaily.com/stop-flickering-mouse-immediate-troubleshooting-guide/"><u>Stop Flickering Mouse - Immediate Troubleshooting Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-newcomer-to-pro-a-step-by-step-creator-hub-guidebook/"><u>[New] In 2024, From Newcomer to Pro  A Step-by-Step Creator Hub Guidebook</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/essential-guide-to-choosing-among-top-recorders-for-2024/"><u>Essential Guide to Choosing Among Top Recorders for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/cinematic-cadence-top-cameras-for-elegant-slow-movement/"><u>Cinematic Cadence  Top Cameras for Elegant Slow Movement</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-the-comprehensible-approach-to-multisnapping-videos/"><u>In 2024, The Comprehensible Approach to Multisnapping Videos</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-snapshot-savvy-the-gif-journey-on-snapchat-for-2024/"><u>[New] Snapshot Savvy  The GIF Journey on Snapchat for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-updated-youtube-income-guidelines/"><u>2024 Approved  Updated YouTube Income Guidelines</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/react-and-relate-harness-the-power-of-alternate-perspectives-for-compelling-youtube-vids-2-pov-method-for-2024/"><u>React and Relate - Harness the Power of Alternate Perspectives for Compelling YouTube Vids (2 POV Method) for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-how-to-enable-grid-view-on-google-meet-to-see-every-participant-for-2024/"><u>[Updated] How to Enable Grid View on Google Meet to See Every Participant for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-perfecting-vlog-shots-how-to-use-a-tripod-like-a-pro-for-2024/"><u>[Updated] Perfecting Vlog Shots  How to Use a Tripod Like a Pro for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-capture-perfection-on-the-switch-console/"><u>2024 Approved  Capture Perfection on the Switch Console</u></a></li>
</ul></div>
