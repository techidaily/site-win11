---
title: "Simple Fixes: Resetting Windows Setup Post-Reboot"
date: 2024-06-25T10:01:59.492Z
updated: 2024-06-26T10:01:59.492Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Simple Fixes: Resetting Windows Setup Post-Reboot"
excerpt: "This Article Describes Simple Fixes: Resetting Windows Setup Post-Reboot"
keywords: WinSetupReset,RebootFixWin,SimpleSystemReset,QuickWindowsFix,PCRebootTroubleshoot,SetupResetTips,WindowsPostReboot
thumbnail: https://thmb.techidaily.com/499d16f8fa9d73db2896cc95dd1103614d6afb1a8c7743ea30004b41e37daeda.jpg
---

## Simple Fixes: Resetting Windows Setup Post-Reboot

 Imagine you’ve just spent hours tweaking your Windows settings—and then you reboot. What you find is that all changes you made have been reset to default settings. Before you give up and reset your computer to factory defaults, give these solutions a shot.

 In this article, we’ll explain what causes the issue and how you can fix it.

## Why Does Windows Reset Its Settings on Reboot?

 The Windows settings reset on reboot for several reasons. The most common cause is a user profile change, either due to a system update or a user’s action. In other cases, a running background application can corrupt user profiles. This can happen if an application crashes or is not updated. It’s also possible that malware is responsible for the issue.

 Sometimes, if there is a system error or a hardware issue like a faulty hard drive, Windows settings may reset when the computer restarts. This could happen due to an unforeseen power outage.

## How to Fix Windows Settings Resetting Upon Reboot

 The best way to fix Windows settings resetting upon reboot is to identify the cause of the problem and take corrective action. Here are some tips to get your settings back.

### 1\. Look Out for Suspicious Programs

 The first step is to check for malicious programs and other suspicious applications that may be causing your issue. If you find any, remove them immediately and check if it solves the problem. Here's how to do it.

1. Right-click on your Taskbar area and select**Task Manager** from the context menu. You can also press**Ctrl + Shift + Esc** if you prefer using shortcut keys.  
![Look Out for Suspicious Programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/look-out-for-suspicious-programs.jpg)
2. In the Task Manager window, switch to the**Processes** tab and look for any unfamiliar program or process that is hogging up your system resources.
3. Once you find a suspicious program, right-click on it and select**End task** to terminate the process.
4. Now go to the Windows Control Panel and uninstall the program.

 After uninstalling the program, restart your computer and check if the settings reset issue is resolved.

### 2\. Run Automatic Startup Repair

 If Windows continues to reset its settings upon reboot, you should try running the Automatic Startup Repair feature. This will help fix any system errors or corrupted files that may be causing the issue.

To run Automatic Startup Repair, follow these steps:

1. Press**Win + I** to open the Settings window.
2. From the left-hand menu, click the**System** tab.
3. On the right side of the window, scroll down and click the**Recovery** option.  
![Advanced startup in Recovery options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-startup-in-recovery-options.jpg)
4. Next to**Advanced startup** , click the**Restart now** button.
5. When your PC restarts, select**Troubleshoot** from the Choose an option screen.
6. Select**Advanced options** and then click**Startup Repair** .  
![Startup repair in Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/startup-repair-1.jpg)

 Follow the on-screen instructions to run the automatic repair tool. After you complete the above process, restart your computer and check if it solves the issue.

### 3\. Check Your User Profile

 If the issue persists, check your user profile and make sure it’s not corrupt. If your user profile is corrupted, Windows will reset the settings when you restart. Here’s how to check it:

 Press**Windows + R** to open the Run command. In the dialog box, type**regedit** , and press Enter. If the User Account Control (UAC) window appears, click**Yes** to grant administrative privileges. This will launch the Registry Editor.

On the next screen, navigate to the following path:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList`

 In the**ProfileList** folder, you should see several profiles starting with**S-1-5** . Each of these profiles corresponds to a user account on your computer. Now you have to identify which profile belongs to your user account.

 To do this, click on each**S-1-5 profile** and look for**ProfileImagePath** in the right pane. Check if anyone of them matches your username.

![Modify Registry to repair user profile](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/modify-registry-to-repair-user-profile.jpg)

 Once you find the correct profile, double-click on the**State** field and change the value from**1 to 0** . Similarly, change the**RefCount** field from**1 to 0** .

 In case the RefCount field is missing in the right pane, you’ll have to create it manually. For this, right-click on the right pane and select**New > DWORD (32-bit) Value** . Name the new value**RefCount** and press**Enter** .

 Then double-click on the newly created RefCount and enter**0** in the Value data field. Click**OK** to save your changes and exit Registry Editor. After this, restart your computer and check whether the settings reset problem is fixed.

### 4\. Create a New User Profile

 If you weren’t able to repair the corrupt profile in the Registry Editor, you may have to[create a new user profile on Windows](https://www.makeuseof.com/windows-11-create-local-user-account/) . Creating a new user profile does not delete the old one, so all your data will remain intact, but you will have to reconfigure your settings. After creating it, log out of your current user account and switch to the newly created one. Check if this fixes the settings reset issue.

### 5\. Uninstall Recent Updates

 Microsoft releases Windows updates periodically to keep your system secure. But sometimes these updates fail to install properly and cause various issues. If you recently installed any programs or updates, uninstall them to check if that fixes the problem.

 You can also try rolling back any drivers that might be causing the issue. To do this, right-click on Start and select**Device Manager** . In the Device Manager window, find the device you want to roll back and right-click on it. Select**Properties** from the context menu and then click on the**Driver** tab.

 Click**Roll Back Driver** and then follow the instructions on-screen to complete the process. After rolling back the driver, restart your computer to apply the changes and check if it solves the settings reset issue.

### 6\. Perform Some Generic Windows Fixes

 There are some general Windows-based fixes you can apply to fix this issue.

[Running your Windows computer in a Clean Boot state](https://www.makeuseof.com/clean-boot-windows-11/) is another way to fix the reset settings problem. Clean Boot helps you identify any third-party applications that might be causing the issue. It stops all non-Microsoft services and programs from running during startup, which helps you pinpoint the cause of the issue.

 If the methods mentioned earlier don't fix the issue,[consider doing a System Restore](https://www.makeuseof.com/windows-11-create-restore-point/) . This will take your computer back to a previous state when it was functioning well.

 Keep in mind that all files and applications installed after the selected restore point will be deleted. To avoid losing important data, create a backup before performing a System Restore.

## Fixing Windows Settings Reset on Reboot

 The Windows settings reset on reboot issue can occur for a number of reasons, including corrupt user profiles, corrupted installed programs or updates, and driver issues. This guide provides several methods to fix this issue. Check out these solutions and see which one work for you.


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
<li><a href="https://win11.techidaily.com/windows-ui-stability-solutions-for-recurring-crashes/"><u>Windows UI Stability: Solutions for Recurring Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-slashing-dropbox-cpu-load-on-windows-devices/"><u>Solutions for Slashing Dropbox CPU Load on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-files-navigate-smaller-with-windows-explorer/"><u>Simplifying Files: Navigate Smaller with Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/capturing-uac-alerts-a-windows-screenshot-guide/"><u>Capturing UAC Alerts: A Windows ScreenShot Guide</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-chat-disappearance-in-windows-11-what-it-entails-for-users/"><u>Taskbar Chat Disappearance in Windows 11: What It Entails for Users</u></a></li>
<li><a href="https://win11.techidaily.com/restore-peace-of-mind-with-these-5-family-safety-fixes/"><u>Restore Peace of Mind with These 5 Family Safety Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-cease-windows-11-alarms-and-notifications/"><u>Swiftly Cease Windows 11 Alarms and Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-to-windows-11s-auto-hdr-techniques/"><u>Essential Guide to Windows 11'S Auto HDR Techniques</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-perfected-acoustic-parameters-for-electronics-optimization-for-2024/"><u>Updated Perfected Acoustic Parameters for Electronics Optimization for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/024-approved-navigating-the-rules-of-youtube-video-documentation/"><u>[New] 2024 Approved  Navigating the Rules of YouTube Video Documentation</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-masterful-mp4-transformation-tools-facebook-edition/"><u>[Updated] 2024 Approved  Masterful MP4 Transformation Tools (Facebook Edition)</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-low-cost-aerial-photography-top-5-drones-under-500/"><u>[New] Low-Cost Aerial Photography  Top 5 Drones Under $500</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-resolve-your-apple-iphone-xs-max-keeps-asking-for-outlook-password-drfone-by-drfone-ios/"><u>In 2024, Resolve Your Apple iPhone XS Max Keeps Asking for Outlook Password | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-5-innovative-strategies-for-crafting-youtube-titles-and-tags/"><u>[Updated] 2024 Approved  5 Innovative Strategies for Crafting YouTube Titles & Tags</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-top-ranked-free-os-recording-solutions-examined/"><u>[Updated] In 2024, Top-Ranked Free OS Recording Solutions Examined</u></a></li>
<li><a href="https://extra-tips.techidaily.com/steady-shots-how-to-avoid-lens-cloudiness/"><u>Steady Shots  How to Avoid Lens Cloudiness</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-from-boring-to-breathtaking-insta-video-tips-for-2024/"><u>[New] From Boring to Breathtaking  Insta Video Tips for 2024</u></a></li>
</ul></div>
