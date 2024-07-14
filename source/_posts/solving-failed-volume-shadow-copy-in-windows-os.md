---
title: Solving Failed Volume Shadow Copy in Windows OS
date: 2024-07-13T10:38:42.384Z
updated: 2024-07-14T10:38:42.384Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving Failed Volume Shadow Copy in Windows OS
excerpt: This Article Describes Solving Failed Volume Shadow Copy in Windows OS
keywords: Fix VSS Errors,WinOS Volume Recovery,ShadowCopy Correction,Restore ShadowBackup,Resolve VssError,Windows VSS Failure Fixed,Shadow Copy Success Guide
thumbnail: https://thmb.techidaily.com/19a61f5995d579c8b7ad201fc517afd84cc338957aeb2d8c12a802a23a178f47.jpg
---

## Solving Failed Volume Shadow Copy in Windows OS

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

## 1\. Enable and Start Volume Shadow Copy Services

 VSS errors can often arise because the Volume Shadow Copy and Microsoft Software Shadow Copy Provider services aren’t enabled or running. For example, many users have confirmed enabling those services can fix VSS error codes 0x81000202 and 0x81000203, which affect the System Restore tool. So, you may be able to resolve numerous Volume Shadow Copy errors by enabling VSS services like this:

1. First, press the **Windows** logo key + **S** and enter a Services search phrase to find that app.
2. Click **Services** inside the search results.
3. Double-click the **Volume Shadow Copy Service**.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/services-window.jpg)
4. Click the drop-down menu labeled **Startup type** and select **Automatic** if the service is set differently.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-type-drop-down-menu.jpg)
5. Press **Start** in the Volume Shadow Copy Service window.
6. Click on the service window’s **Apply** and **OK** buttons to set the changed options.
7. Repeat steps three to six for the Microsoft Software Shadow Copy Provider service.
8. Also, check that the RPC Endpoint Mapper and DCOM Server Process dependency services for Volume Shadow Copy are enabled and running.

 Restart those shadow copy services if they’re already set as required. You can do that by right-clicking on those services and selecting the Restart context menu options for them.

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://change-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Apple iPhone 14 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-master-10-social-media-movies/"><u>[New] In 2024, Master 10 Social-Media Movies</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-mute-reactivate-slack-alerts-in-win-11/"><u>Troubleshoot Mute: Reactivate Slack Alerts in Win 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-riding-the-wave-of-solitary-podcast-popularity/"><u>2024 Approved  Riding the Wave of Solitary Podcast Popularity</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-cinematic-brilliance-through-masterful-application-of-luts-from-cg-central/"><u>2024 Approved  Cinematic Brilliance Through Masterful Application of Luts From CG Central</u></a></li>
<li><a href="https://win11.techidaily.com/7-noteworthy-changes-in-the-windows-11-file-explorer/"><u>7 Noteworthy Changes in the Windows 11 File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unsuccessful-message-loads-on-discord-pc/"><u>Troubleshooting Unsuccessful Message Loads on Discord PC</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-elite-suites-3d-modeling-and-animation-synergy/"><u>2024 Approved  Elite Suites  3D Modeling & Animation Synergy</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-exploring-options-for-advanced-livestreaming-setups/"><u>2024 Approved  Exploring Options for Advanced Livestreaming Setups</u></a></li>
<li><a href="https://win11.techidaily.com/top-tips-for-effective-app-packages-control-using-winget-on-win11/"><u>Top Tips for Effective App Packages Control Using Winget on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-creativity-discovering-the-latest-in-microsoft-paint/"><u>Elevate Creativity: Discovering the Latest in Microsoft Paint</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-search-failures-immediately/"><u>Addressing Windows 11 Search Failures Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-frustrating-fails-correcting-windows-error-1152/"><u>Avoiding Frustrating Fails: Correcting Windows' Error 1152</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/selective-guide-to-prime-no-cost-screenshots-macwindows-for-2024/"><u>Selective Guide to Prime No-Cost Screenshots, Mac/Windows for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-ignite-your-startups-growth-with-these-top-social-media-tips/"><u>2024 Approved  Ignite Your Startup's Growth with These Top Social Media Tips</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-music-from-90-by-fonelab-android-recover-music/"><u>Possible solutions to restore deleted music from 90</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-the-fcpx-fix-it-handbook-solving-common-problems/"><u>2024 Approved The FCPX Fix-It Handbook Solving Common Problems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-could-not-create-the-java-virtual-machine-error-on-windows/"><u>How to Fix the “Could Not Create the Java Virtual Machine” Error on Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/navigating-the-complexities-of-mac-and-mixer-streaming-for-2024/"><u>Navigating the Complexities of MAC and Mixer Streaming for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-imovie-rhythms-a-sound-experts-handbook/"><u>[Updated] IMovie Rhythms  A Sound Expert's Handbook</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-keep-windows-11s-search-bar-unseen/"><u>How to Keep Windows 11'S Search Bar Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-n-series-pros-and-cons/"><u>Deciphering Windows N Series: Pros & Cons</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-shadowed-sojourn-versus-luminous-journey-black-vs-silver/"><u>2024 Approved  Shadowed Sojourn Versus Luminous Journey  BLACK vs SILVER</u></a></li>
<li><a href="https://win11.techidaily.com/direct-pc-access-through-smb-protocols-mobile/"><u>Direct PC Access Through SMB Protocols (Mobile)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-error-code-0x80d03801-in-microsoft-store-on-windows-pc/"><u>How to Fix Error Code 0X80d03801 in Microsoft Store on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/win11-and-dxgidll-quick-fixes-for-the-missing-file/"><u>Win11 & Dxgi.dll: Quick Fixes for the Missing File</u></a></li>
<li><a href="https://win11.techidaily.com/access-and-conquer-mastering-windows-11-printer-control-max-50-chars/"><u>Access and Conquer: Mastering Windows 11 Printer Control (Max 50 Chars)</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-tweak-twitter-video-clip-cover/"><u>[Updated] In 2024, Tweak Twitter Video Clip Cover</u></a></li>
<li><a href="https://win11.techidaily.com/winirq-fixing-killer-soundsystem-problems/"><u>WinIRQ: Fixing Killer Soundsystem Problems</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-idea-to-execution-an-essential-guide-to-youtube-shorts-template-design/"><u>[New] 2024 Approved  From Idea to Execution  An Essential Guide to YouTube Shorts Template Design</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-open-exes-without-issues/"><u>Troubleshooting Windows: Open EXEs Without Issues</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-file-lifecycle-in-windows-11-set-up-autodelete-protocols/"><u>Efficient File Lifecycle in Windows 11: Set Up Autodelete Protocols</u></a></li>
<li><a href="https://win11.techidaily.com/get-across-taskbar-and-tile-adjustments-fast/"><u>Get Across Taskbar & Tile Adjustments Fast</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-handling-windows-updater-problems-focusing-on-error-0x80070003/"><u>Decoding and Handling Windows Updater Problems: Focusing on Error 0X80070003</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-comprehensive-guide-for-effective-video-capturing/"><u>2024 Approved  Comprehensive Guide for Effective Video Capturing</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oppo-a1x-5g-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Oppo A1x 5G to Other Android Devices Devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-nullifying-windows-tracking-mechanism/"><u>Techniques for Nullifying Windows' Tracking Mechanism</u></a></li>
</ul></div>
