---
title: Reversing Shadow Copy Suspension Error
date: 2024-12-23T04:38:12.568Z
updated: 2024-12-28T07:20:06.407Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Repair Your System Files With the SFC and DISM Commands

 Corrupted system files can affect Windows services, such as Volume Shadow Copy. So, some users may need to repair system files to fix the Volume Shadow Copy Service when it’s not working. You can do that by running System File Checker and Deployment Image Servicing Management scans, as covered in this article about [repairing corrupt Windows files](https://www.makeuseof.com/windows-built-in-repair-tools/).

![The sfc scannow command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/sfc-scannow-error.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-are-you-prepared-for-the-changed-facebook-algorithm/"><u>[Updated] 2024 Approved Are You Prepared for the Changed Facebook Algorithm?</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-elevate-your-profile-picture-game-with-these-high-end-online-services/"><u>[Updated] Elevate Your Profile Picture Game with These High-End Online Services</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-selective-selections-notable-sites-for-snagging-snapalert-tunes/"><u>[Updated] Selective Selections Notable Sites for Snagging SnapAlert Tunes</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-htc-u23-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your HTC U23 is off? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/crucial-steps-to-idle-your-windowed-machine/"><u>Crucial Steps to Idle Your Windowed Machine</u></a></li>
<li><a href="https://win11.techidaily.com/from-silence-to-sound-windows-11s-tale-beginnings/"><u>From Silence to Sound: Windows 11'S Tale Beginnings</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-latest-sound-card-software-for-your-windows-7-pc-download-now/"><u>Get the Latest Sound Card Software for Your Windows 7 PC - Download Now</u></a></li>
<li><a href="https://some-guidance.techidaily.com/guia-gratuita-para-convertir-archivos-pbm-en-imagenes-jpg-con-movavi/"><u>Guía Gratuita Para Convertir Archivos PBM en Imágenes JPG Con Movavi</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-active-directory-domain-services-printer-error-in-windows-11-and-11/"><u>How to Fix the “Active Directory Domain Services” Printer Error in Windows 11 & 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-hone-your-skills-how-to-seamlessly-post-videos-to-instagram-via-desktop/"><u>In 2024, Hone Your Skills How to Seamlessly Post Videos to Instagram via Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-hurdles-with-handbrake/"><u>Overcoming Windows Hurdles with HandBrake</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-login-failures-8-strategies/"><u>Overcoming Windows Login Failures: 8 Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-uninstalling-and-reinstalling-utorrent-on-windows-1087/"><u>Steps for Uninstalling and Reinstalling uTorrent on Windows 10/8/7</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/strategie-gratuite-per-recuperare-file-persi-o-cancellati-3-anni-fa-scopri-i-tuoi-modi/"><u>Strategie Gratuite per Recuperare File Persi O Cancellati 3 Anni Fa, Scopri I Tuoi Modi!</u></a></li>
<li><a href="https://win11.techidaily.com/sudden-rav-virus-alert-where-it-comes-from-how-to-uninstall/"><u>Sudden Rav Virus Alert - Where It Comes From, How To Uninstall</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-wipe-out-email-at-sign-in/"><u>The Ultimate Guide to Wipe Out Email at Sign-In</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-xc0f1103f-failure-on-geforce-now-and-windows-1011/"><u>Troubleshooting XC0F1103F Failure on GeForce Now & Windows 10/11</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-fixes-for-stuttering-and-crashing-during-zivf-dead-war-saves/"><u>Ultimate Fixes for Stuttering and Crashing During 'ZIVF: Dead War' Saves</u></a></li>
<li><a href="https://win-great.techidaily.com/ultimate-tutorial-mastering-the-art-of-deleting-documents-within-word/"><u>Ultimate Tutorial: Mastering the Art of Deleting Documents Within Word</u></a></li>
</ul></div>

