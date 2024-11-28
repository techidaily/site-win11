---
title: How to Reset Virtual Memory on Windows 11
date: 2024-11-21T01:45:06.255Z
updated: 2024-11-28T01:00:39.684Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reset Virtual Memory on Windows 11
excerpt: This Article Describes How to Reset Virtual Memory on Windows 11
keywords: Windows Memory Reset Guide,Virtual Mem Re-Set W11,Win11 Memory Settings,Reset Windows Pagefile,Manage VRAM Windows 11,System RAM Recovery,Pagefile Size Adjustment
thumbnail: https://thmb.techidaily.com/9778babca71d8c322c58ebdc5b0f6b1ae6df8f808a7e29b4ee7032e1868f5ab0.jpg
---

## How to Reset Virtual Memory on Windows 11

 Are you having trouble with virtual memory on Windows 11? Resetting virtual memory on Windows can improve system performance or free up extra hard drive space. So, we'll show you exactly how to reset the virtual memory on your Windows 11 computer.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Use Group Policy Editor

 You can also use the Local Group Policy Editor to reset virtual memory settings on your Windows device. But remember that this method is only available on Pro and Enterprise editions.

 If you're using a Home edition, you should first [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 To get started, open the Run dialog box and type **gpedit.msc** into the text box. Then click **OK** or press Enter to open the Local Group Policy Editor window.

![Clear virtual memory pagefile Using Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/clear-virtual-memory-pagefile-using-group-policy.jpg)

 Then navigate to the following location:

Local Computer Policy > Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Option

 Scroll down and double-click **Shutdown: Clear virtual memory pagefile** policy. In the Properties window, select Enabled and then click **Apply**. Next, click **OK** to save it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Use Registry Editor

 If you don't have access to the Local Group Policy Editor, you can also use the Registry Editor to reset virtual memory settings on Windows. Before proceeding, you should [create a backup of the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) in case something gets wrong.

![Reset Virtual Memory Using Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-virtual-memory-using-registry.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To get started, search for **Registry Editor** in the Start menu and click on it. Once you open the Registry Editor, navigate to the following path:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management

 Next, double-click on the **ClearPageFileAtShutdown** key and set its value to **1**. Click on the **OK** button to save your changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-direct.techidaily.com/new-in-2024-xs-100-is-journey-into-the-world-of-professional-filming/"><u>[New] In 2024, XS 100 I's Journey Into the World of Professional Filming</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-seamless-media-switching-your-ultimate-guide-for-srt-conversion-for-2024/"><u>[New] Seamless Media Switching Your Ultimate Guide for SRT Conversion for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-serene-soundtracks-copyright-free-legal-meditation-music/"><u>[New] Serene Soundtracks – Copyright-Free, Legal Meditation Music</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-unleash-your-tiktok-potential-50plus-powerful-quotes-reviewed/"><u>[Updated] In 2024, Unleash Your TikTok Potential 50+ Powerful Quotes Reviewed</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1726221856146-avi-movavi/"><u>網路上無限Avi格式影片換流器 – Movavi</u></a></li>
<li><a href="https://solve-hot.techidaily.com/cookiebot-driven-solutions-enhance-your-websites-performance/"><u>Cookiebot-Driven Solutions: Enhance Your Website's Performance</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-remote-connections-tips-for-windows-11-users/"><u>Decoding Remote Connections: Tips for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-scope-windows-terminal-vs-powershells-features/"><u>Exploring The Scope: Windows Terminal Vs. PowerShell's Features</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-lava-agni-2-5g-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Lava Agni 2 5G to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/is-vonage-still-dominant-in-the-competitive-voip-arena/"><u>Is Vonage Still Dominant in the Competitive VoIP Arena?</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-non-initialized-disk-errors-in-windows-810/"><u>Navigating Through Non-Initialized Disk Errors in Windows 8/10</u></a></li>
<li><a href="https://fake-location.techidaily.com/prevent-cross-site-tracking-on-samsung-galaxy-z-flip-5-and-browser-drfone-by-drfone-virtual-android/"><u>Prevent Cross-Site Tracking on Samsung Galaxy Z Flip 5 and Browser | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-windows-error-0x80041015-in-ms-office/"><u>Strategies to Overcome Windows Error 0X80041015 in MS Office</u></a></li>
<li><a href="https://win11.techidaily.com/sustaining-classic-machines-in-a-new-age-windows-11-through-to-go-and-rufus/"><u>Sustaining Classic Machines in a New Age: Windows 11 Through To Go and Rufus</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-battery-status-updates-for-windows-devices/"><u>Tailored Battery Status Updates for Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/the-insiders-manual-locking-and-unlocking-fn-key-in-windows/"><u>The Insider's Manual: Locking and Unlocking FN Key in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/time-management-for-the-modern-office-top-8-window-timer-apps/"><u>Time Management for the Modern Office: Top 8 Window Timer Apps</u></a></li>
</ul></div>

