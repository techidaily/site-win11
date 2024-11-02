---
title: Resolving Issues with Windows Activity Monitor
date: 2024-10-31T18:05:22.545Z
updated: 2024-11-02T02:48:09.607Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Issues with Windows Activity Monitor
excerpt: This Article Describes Resolving Issues with Windows Activity Monitor
keywords: Fixing WM ACTivity,Monitor Win Troubleshoot,Activity Monitor Solve,Windows Performance Check,Resolve ActMon Errors,Tune Up WM Performance,Optimize ActMon Use
thumbnail: https://thmb.techidaily.com/b0d6f56b3e6efb0ac5881b741c9c12ef541c2aef549de1d2cc8ab07a2bd3f133.jpg
---

## Resolving Issues with Windows Activity Monitor

 Performance Monitor is a system monitoring tool on Windows that you can use to view real-time statistics about the applications you are running. But sometimes this tool fails to work correctly. If you're facing such a problem on your computer, here are a few fixes you can try to solve it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Reboot your Computer

 Whether you're experiencing performance issues such as slow startup times, or if Performance Monitor isn't working on your system, a simple reboot might do the trick.

 Rebooting Windows clears out any conflicting programs or services that may be causing PerfMon to not work properly. It removes any unnecessary data stored in memory that might be responsible for the issue.

To restart your computer, follow these steps:

1. Open the**Start** menu.
2. Click on the Power button, then select**Restart** .

 Once the computer has restarted, open Performance Monitor and check if the issue has been resolved.

## 2\. Restart the Performance Logs and Alerts service

 If rebooting your computer doesn't fix the problem, you can try restarting the Performance Logs and Alerts service. This service is responsible for monitoring system performance settings and generating alert messages when something is wrong.

To restart this service, follow these steps:

1. Press**Win + R** on your keyboard to open the Run command
2. Type**services.msc** in the dialog box and press**Enter** .
3. In the Services window, scroll down to**Performance Logs & Alerts** service.
4. Right-click on the service and select the**Restart** option.  
![Restart Performance service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restart-performance-service.jpg)

 After you follow the above steps, check if Performance Monitor is working correctly.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136548/16384" target="_top" id="2136548">
  <img src="//a.impactradius-go.com/display-ad/16384-2136548" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136548/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Run the System File Checker

 The System File Checker is a handy Windows tool that can scan for and fix corrupted system files. It is useful when the Performance Monitor isn't working due to a corrupt system file.

To run the System File Checker, follow these steps:

1. Click on the Start menu.
2. Type**cmd** in the search bar, then press**Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. If UAC appears on the screen, click**Yes** to grant access. You can learn more about this handy tool with our[beginner's guide to the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) .  
![Run SFC Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-sfc-command.jpg)
4. In the Command Prompt, type the following command and press**Enter** :  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868495/19272" target="_top" id="1868495">
  <img src="//a.impactradius-go.com/display-ad/19272-1868495" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868495/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

sfc /scannow
5. The scan will check for any corrupted system files and repair them.

 After the scan is complete, restart your computer and check if Performance Monitor is working properly.

## 4\. Check for a Windows Update

 In some cases, outdated versions of Windows can cause Performance Monitor problems. To ensure your system is running the latest version of Windows, follow these steps:

1. Press**Win + I** on your keyboard to open System Settings. We also have an in-depth tutorial on[accessing the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Click**Windows Update** in the left pane.  
![Check for Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/check-for-updates.jpg)
3. Then click the**Check for updates** button.

<!-- affiliate ads begin -->
<span id="1492813">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1492813.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1492813">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1492813.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1492813%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1492813/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If any available updates are found, Windows will download and install them automatically. After the updates have been installed, restart your computer and check if Performance Monitor is now working correctly.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151868/7443" target="_top" id="2151868">
  <img src="//a.impactradius-go.com/display-ad/7443-2151868" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151868/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Perform a System Restore

 In case you have run out of options, you may want to try a system restore. This way, your computer will be restored to the state it was in before the program stopped working.

To perform a system restore, follow these steps:

1. Press**Win + Q** on your keyboard.
2. Type**System Restore** in the search bar and click on**Create a restore point** .
3. In the System Properties window, click the**System Restore** button.  
![Run System Restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-system-restore.jpg)
4. Choose a restore point, then click**Next** .
5. Follow the on-screen instructions to perform a system restore.

 Upon completion of the restoration process, make sure Performance Monitor is working properly.

## Get Hassle Free Performance and Health Monitoring

 Like any other program, Performance Monitor can have glitches and other issues that prevent it from working correctly. The steps in this article will help you fix these issues and get Performance Monitor up and running again.

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
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-vocal-excellence-techniques-for-capturing-flawless-audio/"><u>[Updated] 2024 Approved Vocal Excellence Techniques for Capturing Flawless Audio</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-expedited-srt-to-txt-conversion-2023s-efficient-method/"><u>[Updated] In 2024, Expedited SRT to TXT Conversion 2023'S Efficient Method</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-quick-shift-video-techniques-mastering-transitions/"><u>2024 Approved Quick-Shift Video Techniques Mastering Transitions</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-the-metaverse-vs-omniverse-showdown-a-comprehensive-overview/"><u>2024 Approved The Metaverse Vs. Omniverse Showdown A Comprehensive Overview</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/1721267365192-boost-your-sites-performance-using-cookiebot-technology-get-started-now/"><u>Boost Your Site's Performance Using Cookiebot Technology - Get Started Now</u></a></li>
<li><a href="https://win11-tips.techidaily.com/deciphering-7-indicative-windows-activities-of-malware/"><u>Deciphering 7 Indicative Windows Activities of Malware</u></a></li>
<li><a href="https://win11.techidaily.com/forecasting-with-finesse-windows-11s-prime-weather-tools/"><u>Forecasting with Finesse: Windows 11'S Prime Weather Tools</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-ai-assistance-in-development-an-introduction-to-microsoft-copilot/"><u>Leveraging AI Assistance in Development: An Introduction to Microsoft Copilot</u></a></li>
<li><a href="https://win11.techidaily.com/method-to-reset-windows-11-search-bar-aesthetics/"><u>Method to Reset Windows 11 Search Bar Aesthetics</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-to-try-connections-glitch-on-windows-pcs/"><u>Quick Fix to 'Try Connections' Glitch on Windows PCs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/reclaiming-hidden-correspondence-a-step-by-step-process-for-google-mail-users/"><u>Reclaiming Hidden Correspondence: A Step-by-Step Process for Google Mail Users</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-disk-management-virtual-disk-hiccups/"><u>Rectifying Disk Management Virtual Disk Hiccups</u></a></li>
<li><a href="https://win11.techidaily.com/the-link-between-edge-and-irrelevant-taskers/"><u>The Link Between Edge and Irrelevant Taskers</u></a></li>
</ul></div>

