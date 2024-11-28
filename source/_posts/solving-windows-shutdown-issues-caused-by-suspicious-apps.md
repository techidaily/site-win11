---
title: Solving Windows Shutdown Issues Caused by Suspicious Apps
date: 2024-11-25T21:06:43.956Z
updated: 2024-11-28T01:56:01.315Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving Windows Shutdown Issues Caused by Suspicious Apps
excerpt: This Article Describes Solving Windows Shutdown Issues Caused by Suspicious Apps
keywords: Fix Windows Shutdown Errors,Stop Windows Freezes,Remove Bad Apps on PC,Solve Shutdown Troubleshooting,Eliminate Suspicious Software,Prevent Windows Crashes,Cleanup PC for Stability
thumbnail: https://thmb.techidaily.com/d72c9b0ad235ae2e33438a2833486adc17771826c6a96da1aa4105529dabc652.jpg
---

## Solving Windows Shutdown Issues Caused by Suspicious Apps

 All you want to do is shut down your PC or log off for the day, but every time you do, you receive an error that says “This app is preventing Windows from shutting down, restarting, or signing out.” There’s pretty much nothing you can do; you just have to wait.

 This can be frustrating and, sadly, there is no silver bullet to this issue. But there are some things you can try.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Does This Error Message Appear?

 This generally happens when there are apps running in the background that needs to be properly shut down. It is advised that you close all running apps before shutting down or logging off.

 Other reasons you may be seeing the “app is preventing Windows shutdown” error include corrupt Windows files or a Windows update still in the process of being downloaded. Some Windows settings can also cause this error to occur.

## What to Do When an App Is Preventing Windows From Shutting Down, Restarting, or Signing Out

 As we said above, there is no "one size fits all" solution, nor is there a way to explicitly tell what's keeping your PC from shutting down cleanly. As such, try each of the following methods until one of them works.

### 1\. Run the System File Checker

 The “app preventing Windows from shutting down” error message may be caused by corrupted system files. The first thing to do is to run the System File Checker on Windows. System File Checker is a tool built into the OS that can scan and restore Windows system files to restore your system to a healthy state.

![the results of an sfc scan in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sfc-scan-results.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 However, it’s advised that you run the DISM tool first. This tool uses Windows Update to make sure that your system files are all in order, so it's a good idea to do a DISM to ensure the SFC scan goes off without a hitch. You can read about both of these tools in our guide on[the difference between CHKDSK, DISM, and SFC](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) .

### 2\. Disable Fast Startup

 Even though it has its advantages, there are many[reasons to disable Windows Fast Startup](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/) . One of these is that it can interfere with how Windows shuts down. With Fast Startup enabled, your computer goes into a state of hibernation, and not a full shutdown, when you turn it off.

![turn off fast boot by clicking on change unavailable settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/03/change-unavailable-settings.png)

 Settings are saved and start-up times are reduced, but as reported on[Windows Learn](https://learn.microsoft.com/en-us/troubleshoot/windows-client/deployment/updates-not-install-with-fast-startup) , it is known to affect Windows updates. So,[turn off Fast Startup on Windows](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) and check whether this solves the problem.

### 3\. Tweak Your Sign-In Options

 With Windows 10, Microsoft included an option to make your life easier when updating to newer builds and versions. This uses your sign-in information to finish setting up your PC after an update. But this can cause problems with shutting down your computer. Follow these steps to change your sign-in options.

1. Click on the Start menu and select**Settings** .
2. Click on**Accounts** and navigate to**Sign-in options** on the left pane.  
![Sign-in options on Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/01-windows-sign-in-options-01.jpg)
3. Scroll down to the**Privacy** section and turn off the option to use your sign-in info to automatically finish setting up your device after an update or restart.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Additionally, you can[block Microsoft sign-ins on Windows 10](https://www.makeuseof.com/windows-block-allow-microsoft-accounts/) altogether.

### 4\. Run the Power Troubleshooter

 Even though turning off or logging off from your PC isn’t a power issue, you can try tackling it via the power troubleshooter. If there’s anything wrong with your PC power options, running this specific fix-it solution might give you an insight into what’s wrong and put you on your way to fixing it.

Here’s how you can run the power troubleshooter on Windows:

1. Access**Settings** via the Start menu.
2. Click on**Update & Security** and navigate to**Troubleshoot** on the left pane.
3. Scroll down to the**Power** section and click on it to expand it.  
![Run the Windows power troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/02-windows-power-troubleshooter.jpg)
4. Click on**Run the troubleshooter** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The system will scan for errors and let you know if there’s something that might need fixing.

### 5\. Manually Kill or Update the Problematic Task

 If you know which tasks are interrupting shutdown, you can manually close them. Use the Task Manager to end any problem tasks. Press**CTRL + Shift + Esc** and end the process before you turn off your PC. To help you find the offending program, you can[use the Windows Event Viewer](https://www.makeuseof.com/windows-event-viewer-guide/) .

 Unfortunately, this might be a temporary fix, as the process may go back to its old habits after you turn off your PC again. As such, if the process is tied to a third-party service you're no longer using, you can uninstall it. Otherwise, check for any updates for the service or re-install it.

 If the problem persists, the[task host may be preventing Windows from shutting down](https://www.makeuseof.com/windows-task-host-preventing-shutdown/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Clean Up Your Shutdown Procedure on Windows

 It isn’t always easy to pinpoint the error that prevents Windows from shutting down or logging off. Resetting things to the way they were before the error started showing up may help solve the problem. Mostly, however, it is likely just third-party apps causing the trouble.

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
<li><a href="https://extra-approaches.techidaily.com/updated-modern-mobile-maximizing-vr360-video-on-android-update-2023/"><u>[Updated] Modern Mobile Maximizing VR/360 Video on Android (Update 2023)</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-technology-gaps-windows-11-legacy-computers-to-go-and-rufus-guide/"><u>Bridging Technology Gaps: Windows 11, Legacy Computers, To Go & Rufus Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-elevating-your-windows-experience-by-reclaiming-offscreen-panes/"><u>Bridging the Gap: Elevating Your Windows Experience by Reclaiming Offscreen Panes</u></a></li>
<li><a href="https://win11.techidaily.com/building-a-lifelayer-trashbin-on-the-windows-1011-environment/"><u>Building a Lifelayer Trashbin on the Windows 10/11 Environment</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-restricted-windows-11-themes-with-skilled-registry-editing/"><u>Bypassing Restricted Windows 11 Themes with Skilled Registry Editing</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-11-security-warning-glitches/"><u>Bypassing Windows 11 Security Warning Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/charting-a-course-to-locate-windows-app-habitats/"><u>Charting a Course to Locate Windows' App Habitats</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-missing-file-alert-in-win-11/"><u>Clearing Up Missing File Alert in Win 11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/crystalclear-conversion-high-res-format-for-2024/"><u>CrystalClear Conversion - High Res Format for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-transformation-for-windows-old-to-new-drivers/"><u>Digital Transformation for Windows: Old to New Drivers</u></a></li>
<li><a href="https://driver-download.techidaily.com/ensure-your-hp-printer-works-perfectly-update-drivers-for-windows-1011/"><u>Ensure Your HP Printer Works Perfectly: Update Drivers for Windows 10/11</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-official-steelseries-engine-software-for-enhanced-keyboard-experience/"><u>Free Download: Official SteelSeries Engine Software for Enhanced Keyboard Experience</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Infinix Smart 8 HD | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/reimagined-computing-with-windows-10s-upgrades-for-2024/"><u>Reimagined Computing with Windows 10’S Upgrades for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/secure-your-wireless-connection-with-free-tp-link-drivers/"><u>Secure Your Wireless Connection with Free TP Link Drivers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/why-consider-chatgpt-for-your-next-health-inquiry/"><u>Why Consider ChatGPT for Your Next Health Inquiry?</u></a></li>
</ul></div>

