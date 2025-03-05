---
title: Reversing Shadow Copy Suspension Error
date: 2025-03-01T21:05:21.945Z
updated: 2025-03-05T01:58:34.847Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reversing Shadow Copy Suspension Error
excerpt: This Article Describes Reversing Shadow Copy Suspension Error
keywords: SyncShadowErrorResolve,ReverseSSSFailure,CorrectShadowPause,FixShadowSyncError,UnfreezeShadowBackup,StopSSSErrorShutdown,ResumeShadowRestore
thumbnail: https://thmb.techidaily.com/6cb4391f5b78a0bded981255e816f25b4a4f4175f4c2d7396281a9558ff75db1.jpg
---

## Reversing Shadow Copy Suspension Error

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-accelerated-adventures-fastest-flash-games-on-devices/"><u>[New] 2024 Approved Accelerated Adventures Fastest Flash Games on Devices</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-ultimate-guide-premier-live-streaming-plus-local-channels-2024/"><u>[New] Ultimate Guide Premier Live Streaming + Local Channels 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-optimizing-video-visibility-with-strategic-tag-selection/"><u>[Updated] In 2024, Optimizing Video Visibility with Strategic Tag Selection</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-top-10-stabilizing-tech-for-youtube-creators-success/"><u>[Updated] In 2024, Top 10 Stabilizing Tech for YouTube Creators' Success</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-top-8-best-4k-blu-ray-players/"><u>2024 Approved Top 8 Best 4K Blu-Ray Players</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-code-of-windowsstore-folder-protection/"><u>Breaking the Code of WindowsStore Folder Protection</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-lock-essential-tpm-hacks-for-windows-11/"><u>Bypassing the Lock: Essential TPM Hacks for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/connect-your-games-across-screens-win-11-and-android-via-google-linkup/"><u>Connect Your Games Across Screens: Win 11 & Android via Google Linkup</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-hyper-v-in-windows-11-steps-to-follow/"><u>Enabling Hyper-V in Windows 11: Steps to Follow</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-update-error-0x80246007-in-windows-11-and-11/"><u>How to Fix the Windows Update Error 0X80246007 in Windows 11 & 11</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-creative-video-ends-top-6-budget-friendly-options/"><u>In 2024, Creative Video Ends Top 6 Budget-Friendly Options!</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-tecno-camon-20-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Tecno Camon 20 Phone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-speeding-up-youtube-quick-video-rendering-and-transfer-tips/"><u>In 2024, Speeding Up YouTube Quick Video Rendering & Transfer Tips</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, What are Location Permissions Life360 On Apple iPhone 13 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-screen-brilliance-adjustments-in-windows-11/"><u>Mastering Screen Brilliance Adjustments in Windows 11</u></a></li>
</ul></div>

