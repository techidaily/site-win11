---
title: Mending Failed Volume Backup in Microsoft OS
date: 2024-12-20T16:56:07.214Z
updated: 2024-12-22T16:15:38.943Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mending Failed Volume Backup in Microsoft OS
excerpt: This Article Describes Mending Failed Volume Backup in Microsoft OS
keywords: Fix Volume Restore Failure,Windows Volume Recovery,SQL Server Backup Errors,Restoring Data Mistakes,Repairing VSS Failures,Microsoft Backup Issues,OS Volume Correction Steps
thumbnail: https://thmb.techidaily.com/481d06bf1b3256f57ab62815340fcc460dfe18ec5f4531d4ca28b88dc8e90d86.jpg
---

## Mending Failed Volume Backup in Microsoft OS

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Enable and Start Volume Shadow Copy Services

 VSS errors can often arise because the Volume Shadow Copy and Microsoft Software Shadow Copy Provider services aren’t enabled or running. For example, many users have confirmed enabling those services can fix VSS error codes 0x81000202 and 0x81000203, which affect the System Restore tool. So, you may be able to resolve numerous Volume Shadow Copy errors by enabling VSS services like this:

1. First, press the **Windows** logo key + **S** and enter a Services search phrase to find that app.
2. Click **Services** inside the search results.
3. Double-click the **Volume Shadow Copy Service**.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/services-window.jpg)
4. Click the drop-down menu labeled **Startup type** and select **Automatic** if the service is set differently.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-type-drop-down-menu.jpg)
5. Press **Start** in the Volume Shadow Copy Service window.
6. Click on the service window’s **Apply** and **OK** buttons to set the changed options.
7. Repeat steps three to six for the Microsoft Software Shadow Copy Provider service.
8. Also, check that the RPC Endpoint Mapper and DCOM Server Process dependency services for Volume Shadow Copy are enabled and running.

 Restart those shadow copy services if they’re already set as required. You can do that by right-clicking on those services and selecting the Restart context menu options for them.

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://win-blog.techidaily.com/avatar-frontiers-of-pandora-game-optimization-expert-tips-to-enhance-fps-and-eliminate-screen-tearing-issues/"><u>'Avatar: Frontiers of Pandora' Game Optimization: Expert Tips to Enhance FPS & Eliminate Screen-Tearing Issues</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-pushing-boundaries-nikons-d500-in-4k-landscape/"><u>[New] Pushing Boundaries Nikon's D500 in 4K Landscape</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-how-to-optimize-your-media-with-simple-video-spin-techniques-in-vlc/"><u>[Updated] How to Optimize Your Media with Simple Video Spin Techniques in VLC</u></a></li>
<li><a href="https://change-location.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-black-screen-post-boot-windows/"><u>Correcting Black Screen Post-Boot Windows</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-resolving-complex-windows-update-issues/"><u>Decoding & Resolving Complex Windows Update Issues</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-resource-busy-on-windows-11-pcs/"><u>Eliminating Resource Busy on Windows 11 PCs</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Honor Magic 5 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-fbx-for-the-aspiring-gamer-filmmaker/"><u>In 2024, FBX for the Aspiring Gamer Filmmaker</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-text-messages-from-oppo-reno-11f-5g-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Text Messages from Oppo Reno 11F 5G to New Phone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/no-sd-card-detected-fixing-file-explorer-issue/"><u>No SD Card Detected: Fixing File Explorer Issue</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-easy-speech-capture-techniques-for-the-modern-windows-user/"><u>Quick and Easy: Speech Capture Techniques for the Modern Windows User</u></a></li>
<li><a href="https://win-able.techidaily.com/resident-evil-village-how-i-overcame-the-pesky-mouse-glitches/"><u>Resident Evil Village - How I Overcame The Pesky Mouse Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-navigation-noteworthy-updates-to-windows-11-filesystem/"><u>Revolutionizing Navigation: Noteworthy Updates to Windows 11 Filesystem</u></a></li>
<li><a href="https://win11.techidaily.com/specifying-disk-types-effortlessly-via-windows/"><u>Specifying Disk Types Effortlessly via Windows</u></a></li>
<li><a href="https://win11.techidaily.com/speed-dials-for-your-control-panel-entry/"><u>Speed Dials for Your Control Panel Entry</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-rules-for-running-several-youtube-accounts-is-it-allowed/"><u>The Rules For Running Several YouTube Accounts - Is It Allowed?</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-inverted-keyboard-usage-on-windows/"><u>Troubleshooting Inverted Keyboard Usage on Windows</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/when-corporate-image-clashes-with-staff-sentiment-the-backlash-against-united-airlines-sexy-branding/"><u>When Corporate Image Clashes with Staff Sentiment: The Backlash Against United Airlines' Sexy Branding</u></a></li>
</ul></div>

