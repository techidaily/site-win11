---
title: Resetting RAM Settings for Optimal Speed
date: 2024-12-06T18:51:42.335Z
updated: 2024-12-13T03:19:11.561Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting RAM Settings for Optimal Speed
excerpt: This Article Describes Resetting RAM Settings for Optimal Speed
keywords: RAM Reset Guide,Speed Optimize RAM,RAM Configuration Tips,RAM Performance Boost,Speed Up RAM Mode,Memory Tuning Methods,RAM Speed Settings
thumbnail: https://thmb.techidaily.com/95716cb061a5dae526d57500a8951c520e1cad5f6661b79a6595a67d8bfbaed5.jpg
---

## Resetting RAM Settings for Optimal Speed

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

## What Is Virtual Memory and How Does It Work?

 Virtual memory, also known as a paging file, is a technology used in computers to allow programs to use more memory than what's physically available on it. When you run out of RAM, your operating system relies on virtual memory to continue running programs.

 The computer creates a special file called a page or swap file on the hard drive. It stores some data temporarily removed from RAM and written to the hard drive. This way, the computer can access more memory than what's installed.

 Although virtual memory allows programs to operate smoothly, it can also hurt overall performance. For example, if your computer runs out of RAM, it will use more of the hard drive to store data. This also significantly slows overall performance as HDDs and SSDs are much slower than RAM.

 Let's now see how to reset Virtual Memory on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jnITUsxMz5s?si=ohwRVH6eWhVnC6Xf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Use the System Properties window

 If you want to reset virtual memory settings on your Windows device, you can use the System Properties window. To do this, press **Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 In the text box, type **sysdm.cpl**, and hit Enter. A system properties window will open up. Then, go to the **Advanced** tab and click the **Settings** button in the Performance section.

![How to Reset Virtual Memory on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/how-to-reset-virtual-memory-on-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This will open up the Performance Options window, where you can manage virtual memory settings. For this, switch to the **Advanced** tab and click on **Change** in the Virtual Memory section.

![Reset Page Size](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-page-size.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 On the next screen, uncheck the **Automatically manage paging file size for all drives** checkbox and select the drive you want to configure virtual memory. Normally, this will be the drive on which Windows is installed.

 Set the custom size for virtual memory. Then, check the **No paging file** radio button and click **Set**. If you see a warning message, click **Yes** to confirm.

 After following the above steps, click **OK** to save your changes. Now close the System Properties and Settings windows and restart your computer. The new virtual memory settings should now be in effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-explore-affordable-cross-platform-video-chat-platforms-for-windowsmac/"><u>[New] 2024 Approved Explore Affordable, Cross-Platform Video Chat Platforms for Windows/Mac</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-how-to-elevate-your-social-influence-the-six-step-guide-to-instagram-verified-status/"><u>[New] How to Elevate Your Social Influence The Six-Step Guide to Instagram Verified Status</u></a></li>
<li><a href="https://win-howtos.techidaily.com/all-checks-passed-just-a-non-responsive-component/"><u>All Checks Passed: Just a Non-Responsive Component</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-nvidia-disp-settings-not-present-fault/"><u>Correcting Nvidia Disp Settings Not Present Fault</u></a></li>
<li><a href="https://win11.techidaily.com/easy-sticknotes-setup-for-optimal-note-taking-in-win11win10/"><u>Easy StickNotes Setup for Optimal Note-Taking in Win11/Win10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-repair-an-unresponsive-aoc-monitor-connection-on-windows-10/"><u>How to Repair an Unresponsive AOC Monitor Connection on Windows 10</u></a></li>
<li><a href="https://data-wizards.techidaily.com/1720669299489-inadequate-video-editing-results-from-stellar-tools/"><u>Inadequate Video Editing Results From Stellar Tools</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-terminal-resurfacing-techniques/"><u>Mastering Windows Terminal Resurfacing Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-precise-assessment-of-cpu-utilization-in-windows/"><u>Methods for Precise Assessment of CPU Utilization in Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-unlock-fcps-full-potential-top-5-editing-secrets-revealed/"><u>New Unlock FCPs Full Potential Top 5 Editing Secrets Revealed</u></a></li>
<li><a href="https://extra-tips.techidaily.com/no-cost-screen-record-the-ultimate-win11-tools-1-5-listing/"><u>No-Cost Screen Record The Ultimate Win11 Tools #1-5 Listing</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-steam-interface-failure-issue/"><u>Remedying Steam Interface Failure Issue</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/speedy-setup-obtain-your-hp-envy-5055-driver-software-now/"><u>Speedy Setup: Obtain Your HP Envy 5055 Driver Software Now</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reset-and-stabilize-windows-post-restart/"><u>Steps to Reset and Stabilize Windows Post-Restart</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-failures-repairing-windows-11s-cloud-functionality/"><u>Tackling Failures: Repairing Windows 11'S Cloud Functionality</u></a></li>
</ul></div>

