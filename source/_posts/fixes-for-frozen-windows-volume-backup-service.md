---
title: Fixes for Frozen Windows Volume Backup Service
date: 2024-06-25T11:28:16.727Z
updated: 2024-06-26T11:28:16.727Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixes for Frozen Windows Volume Backup Service
excerpt: This Article Describes Fixes for Frozen Windows Volume Backup Service
keywords: Freeze Fix,Backup Unfreeze,Restart Services,Safe Recovery,Stop Frozen Sound,Resume Backup,Volume Service Fix
thumbnail: https://thmb.techidaily.com/15a61f0827860e342a65d573fdf8ef935cbe188b573d2796a1411e612ad84808.jpg
---

## Fixes for Frozen Windows Volume Backup Service

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/rethink-reviving-windows-or-beyond/"><u>Rethink Reviving: Windows or Beyond?</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-storage-potential-with-windows-iscsi-initiator/"><u>Unlocking Storage Potential with Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11.techidaily.com/frame-perfecting-eliminating-lags-with-these-9-windows-strategies/"><u>Frame Perfecting: Eliminating Lags with These 9 Windows Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-nuances-of-color-management-in-windows/"><u>Navigating the Nuances of Color Management in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/curb-the-constant-reopening-of-windows-file-explorer/"><u>Curb the Constant Reopening of Windows' File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ms-store-repairs-overcoming-server-slip-ups-on-windows-os/"><u>Mastering MS Store Repairs: Overcoming Server Slip-Ups on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-legacy-windows-photo-viewer-features-in-win11/"><u>Restoring Legacy Windows Photo Viewer Features in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-color-management-not-working-on-windows/"><u>How to Fix Color Management Not Working on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-alt-code-not-responding-on-windows-pc/"><u>Overcoming ALT Code Not Responding on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-ink-to-paper-translation-selecting-best-windows-tabs/"><u>Ideal Ink-to-Paper Translation: Selecting Best Windows Tabs</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/transform-your-devices-display-into-a-high-quality-record-for-2024/"><u>Transform Your Device's Display Into a High-Quality Record for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-change-frame-rate-in-premiere-pro/"><u>Updated How to Change Frame Rate in Premiere Pro</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-elevate-your-online-presence-with-obs-on-youtube-and-twitch/"><u>[New] Elevate Your Online Presence with OBS on YouTube & Twitch</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-the-power-of-smart-lock-a-beginners-guide-for-samsung-galaxy-s23-users-by-drfone-android/"><u>In 2024, Unlocking the Power of Smart Lock A Beginners Guide for Samsung Galaxy S23 Users</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-top-15-must-see-tiktok-innovations/"><u>[New] 2024 Approved  Top 15 Must-See TikTok Innovations</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-insiders-guide-to-creating-viral-instagram-reels/"><u>The Insider’s Guide to Creating Viral Instagram Reels</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/how-to-reverse-a-video-on-snapchat/"><u>How to Reverse a Video on Snapchat?</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/maximizing-youtube-experience-through-a-subscription/"><u>Maximizing YouTube Experience Through a Subscription</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-motorola-edge-40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-breaking-down-the-barriers-to-knowing-your-fans-for-2024/"><u>[Updated] Breaking Down the Barriers to Knowing Your Fans for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>