---
title: "The Watchful Reboot: Steps to Fix Windows Time Service Failures"
date: 2024-12-07T12:05:41.202Z
updated: 2024-12-13T02:10:38.598Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes The Watchful Reboot: Steps to Fix Windows Time Service Failures"
excerpt: "This Article Describes The Watchful Reboot: Steps to Fix Windows Time Service Failures"
keywords: Windows Time Fixed,Reboot Time Service,Stop Time Errors,Windows Time Repair,TimeService Fix Guide,Time Sync Resolution,Watchful Window Tick
thumbnail: https://thmb.techidaily.com/1e30b9de50d4ae50235fbe2427c86509d2c0711d92ede6d59da5c3ba818ec4d8.jpg
---

## The Watchful Reboot: Steps to Fix Windows Time Service Failures

 Start your Windows computer and notice that the time is wrong. It might be a minor issue, or you accidentally changed the setting. But what if Windows Time Service is missing entirely?

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Reboot Your PC

 Restart your computer before attempting any major troubleshooting. While it may sound simple, restarting the computer resolves minor errors and glitches that prevent the service from running. It flushes out temporary files and refreshes the operating system to ensure everything works correctly.

1. Press **Alt + F4** to bring up the Shutdown dialog
2. Select **Restart** from the drop-down menu and then hit **OK**.

 Once the computer restarts, check if Windows Time Service is available. If it's still missing, move on to the next step.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Change the Time Server

 If restarting the computer does not work, you must change the time server. Changing the time server synchronizes your system clock with an online one, displaying your computer's correct date and time.

 Follow the steps to change the time server:

1. Press the **Windows key** to open the Start Menu.
2. Type **control panel** in the search box and click the result. This opens the Control Panel window.
3. Select **View by: Large icons** and click **Date and Time**.
4. Switch to the **Internet Time** tab and click **Change settings**.
5. Check the **Synchronize with an Internet time server** box and select a time server from the drop-down menu.  
![Change the Time Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/change-the-time-server.jpg)
6. Click the **Update now** button to synchronize your computer with the time server.
7. Once completed, click **OK** to save the changes and exit.

 After these steps, you should see the Windows Time Service running on your system. Check the time to ensure it is correct and make further adjustments.

## 3\. Add More Time Servers

 If the Windows Time Service is still missing, you can try adding more time servers to the list. Multiple time servers increase the chance of finding an active server and keeping your system in sync. If one server goes down, your computer can automatically switch to another.

 The solution requires editing the Windows registry. Even a small mistake can damage your system, so proceed with caution. To avoid data loss, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing.

 To add time servers, do the following:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and click **OK**.
3. If the UAC window pops up on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following directory.  
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DateTime\Servers  
 Copy and paste the path into the Registry Editor address bar and press Enter. This will take you to the Location key.
5. From the left navigation panel, right-click the Servers folder and select **New** \> **String Value**.  
![Add More Time Servers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/add-more-time-servers.jpg)
6. Name the new value **Server N**, and replace **N** with a number starting from 1.  

 You can't have the same number twice. That means if there are already 3 values named _Server 1_, _Server 2_, and _Server 3_, you must call the new one as **Server 4**.
7. Double-click the newly created value and add a time server address in the Value data field.
8. Here are some time server addresses:  
`time.windows.com  

time.nist.gov  

time-a-wwv.nist.gov  

time-c-wwv.nist.gov  

ntp-wwv.nist.gov`

 After adding the time server, click **OK** and close the Registry Editor window. Now restart your computer to apply the changes and check if Windows Time Service is available.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Re-register the Windows Time Service

 If the above steps fail, you can try re-registering the Windows Time Service. Re-registering a service refreshes its configuration and forces it to start again. Doing this may fix the missing Windows Time Service and recover clock synchronization.

 To re-register the Windows Time Service, follow these steps:

1. Press the **Win + S** keys to open the Windows Search.
2. Type **cmd** in the search box and simultaneously press **Ctrl + Shift + Enter**. This opens the Command Prompt with administrative privileges.
3. If the UAC window pops up, click **Yes** to grant permission.
4. Type the following command in the Command Prompt and press Enter:  
net stop w32time
5. This command will stop the Windows Time Service. Now type the following command to unregister the service and press **Enter**:  
w32tm /unregister
6. After that, run the following command to register the service:  
w32tm /register
7. Next, type the following command and hit **Enter**. This starts the Windows Time Service.  
net start w32time

 After performing these steps, close the Command Prompt window and restart your system. You should see that the Windows Time Service is running, and your clock syncs with the time server.

## 5\. Repair Corrupted System Files

![SFC Command Preview](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sfc-command-preview.jpg)

 Corrupt system files can also cause Windows services to fail. So, if the Windows Time Service is still missing, try repairing corrupt system files. You can do this using the System File Checker tool. This tool scans your system for missing files and repairs the errors it finds.

 Wait for the scan to complete, and restart your computer. After that, check if the Windows Time Service is still missing. If it is, try running the Deployment Image Servicing and Management tool. This tool repairs corrupted system files and restores your Windows installation's health.

 If you're not sure how to run either of these tools, check out how to repair corrupt Windows files with its built-in tools for instructions.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 6\. Scan for Malware

 Sometimes, malware is to blame for Windows services acting a little odd. As such, it's worth [running a full system scan](https://www.makeuseof.com/scan-for-viruses-without-buying-antivirus-software/) and removing all detected threats.

![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you feel your PC isn't as secure as it could be, you could try downloading one of the [best antivirus apps for Windows](http://www.makeuseof.com/windows-11-antivirus-apps/). These will both actively block malicious program from installing themselves on your PC, and remove any that are currently infesting your computer.

 For those who prefer a command-line approach, you can [use Windows PowerShell to scan Windows for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/).

## Restore the Missing Windows Time Service

 Hopefully, one or more of these tips worked for you. Missing Windows services can be a huge pain, but hopefully, one of these methods has brought back the Windows Time Service back to working order.

 Fortunately, restoring the Windows Time Service is not complicated. This guide will discuss quickly restoring the missing Windows Time Service and setting the correct time on your computer.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-desktop-and-mobile-solutions-how-to-rotate-videos-for-instagram-for-2024/"><u>[New][Desktop & Mobile Solutions] How to Rotate Videos for Instagram for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-get-youtube-posters-at-zero-price-top-free-downloading-tool/"><u>[Updated] Get YouTube Posters at Zero Price - Top Free Downloading Tool</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-the-path-to-perfected-video-covers-update-guide-and-tips/"><u>[Updated] In 2024, The Path to Perfected Video Covers Update Guide & Tips</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-making-your-slides-come-alive-with-youtube-in-ppt/"><u>[Updated] Making Your Slides Come Alive with YouTube in PPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/70-fte-as-of-2015-16/"><u>70 (FTE) (as of 2015-16)</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-issues-with-elevated-user-roles-and-privileges/"><u>Correcting Issues with Elevated User Roles and Privileges</u></a></li>
<li><a href="https://fox-search.techidaily.com/das-umfassende-leitfaden-fur-die-wiedergewinnung-von-after-effects-projektdateien-finden-sie-ihre-verlorenen-projekte-mit-diesen-tipps-und-tricks/"><u>Das Umfassende Leitfaden Für Die Wiedergewinnung Von After Effects-Projektdateien: Finden Sie Ihre Verlorenen Projekte Mit Diesen Tipps Und Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tools-to-convert-videos-on-your-pc-windows/"><u>Essential Tools to Convert Videos on Your PC, Windows</u></a></li>
<li><a href="https://win-popular.techidaily.com/exploring-the-reasons-behind-chinas-division-in-the-era-of-ming-insights-by-yl-computing-and-yl-software/"><u>Exploring the Reasons Behind China's Division in the Era of Ming - Insights by YL Computing & YL Software</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-code-xc0000142-errors-in-windows/"><u>Fixing Code XC0000142 Errors in Windows</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-samsung-galaxy-s23-fe-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Samsung Galaxy S23 FE Phones</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-context-menu-customization-for-firewall-control-in-windows-11/"><u>Mastering Context Menu Customization for Firewall Control in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-0xc0351000-issue-finding-hyprocvisor-in-sandbox/"><u>Mitigating 0xC0351000 Issue: Finding Hyprocvisor in Sandbox</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-gameplay-smart-adjustments-for-amd-gpu-performance-on-pc/"><u>Optimize Gameplay: Smart Adjustments for AMD GPU Performance on PC</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/qualcomm-x-series-processors-set-to-triple-dell-xps-13plus-laptop-lifespans-at-half-the-price-of-intel-counterparts/"><u>Qualcomm X Series Processors Set to Triple Dell XPS 13+ Laptop Lifespans at Half the Price of Intel Counterparts</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-how-to-resize-apps-using-just-your-pc-keys-on-windows-11/"><u>Quick Fixes: How to Resize Apps Using Just Your PC Keys on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/speed-up-typing-on-win-11-combat-keyboard-lag-effectively/"><u>Speed Up Typing on Win 11: Combat Keyboard Lag Effectively</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-chromes-loading-problems-tips-and-tricks-for-optimal-performance/"><u>Troubleshooting Chrome's Loading Problems: Tips & Tricks for Optimal Performance</u></a></li>
<li><a href="https://win11.techidaily.com/unmatched-comfort-and-efficiency-leading-windows-laptops/"><u>Unmatched Comfort & Efficiency - Leading Windows Laptops</u></a></li>
</ul></div>

