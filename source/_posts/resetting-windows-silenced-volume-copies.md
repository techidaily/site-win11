---
title: Resetting Windows' Silenced Volume Copies
date: 2024-11-04T21:38:34.256Z
updated: 2024-11-07T19:46:07.052Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Windows' Silenced Volume Copies
excerpt: This Article Describes Resetting Windows' Silenced Volume Copies
keywords: Reset Volume Silence,Windows Volume Control,Copying Silent Windows,Restore Audio Settings,Fix Noisy Sound,System Volume Adjust,Disable Silent Copies
thumbnail: https://thmb.techidaily.com/92d4d3774b8fd498c6cfb488cbb5cb9a7cceb0aea3bc2d6cdbbe36e4703b4b56.jpg
---

## Resetting Windows' Silenced Volume Copies

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948895/19272" target="_top" id="1948895">
  <img src="//a.impactradius-go.com/display-ad/19272-1948895" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948895/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148649/16836" target="_top" id="2148649">
  <img src="//a.impactradius-go.com/display-ad/16836-2148649" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148649/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016148/19272" target="_top" id="2016148">
  <img src="//a.impactradius-go.com/display-ad/19272-2016148" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016148/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557746/17382" target="_top" id="1557746">
  <img src="//a.impactradius-go.com/display-ad/17382-1557746" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557746/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-get-into-the-game-starting-an-apple-powered-sports-network/"><u>[New] 2024 Approved Get Into the Game Starting an Apple-Powered Sports Network</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-crafting-the-perfect-day-for-podcast-release/"><u>[New] Crafting the Perfect Day for Podcast Release</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-free-tips-embedding-moving-images-in-written-content/"><u>[Updated] Free Tips Embedding Moving Images in Written Content</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-speeding-up-tiktok-videos-made-simple/"><u>[Updated] In 2024, Speeding Up TikTok Videos Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/convert-websites-to-windows-desktop-applications/"><u>Convert Websites to Windows Desktop Applications</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-honor-90-pro-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Honor 90 Pro Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-a24-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Samsung Galaxy A24 PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-zte-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on ZTE Phones</u></a></li>
<li><a href="https://win11.techidaily.com/installation-procedures-for-powertoys-in-win11/"><u>Installation Procedures for PowerToys in Win11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-the-permissions-puzzle-bypassing-trustedinstaller-on-your-windows-10-pc/"><u>Mastering the Permissions Puzzle: Bypassing TrustedInstaller on Your Windows 10 PC</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-bsod-when-using-vmware-in-windows-11/"><u>Remedying BSOD when Using VMware in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-no-login-issue-on-windows-1011-screens/"><u>Resolving No-Login Issue on Windows 10/11 Screens</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-standard-operations-in-managed-organizational-browsers-chromeedge/"><u>Restoring Standard Operations in Managed Organizational Browsers (Chrome/Edge)</u></a></li>
<li><a href="https://win11.techidaily.com/seven-steps-to-unlocking-windows-11-memory-safety/"><u>Seven Steps to Unlocking Windows 11 Memory Safety</u></a></li>
<li><a href="https://win11.techidaily.com/top-priority-notes-techniques-for-enhanced-productivity-in-windows/"><u>Top Priority Notes Techniques for Enhanced Productivity in Windows</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshoot-your-iphone-when-it-stops-vibrating-in-silentring-mode-discover-8-solutions/"><u>Troubleshoot Your iPhone When It Stops Vibrating in Silent/Ring Mode – Discover 8 Solutions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    