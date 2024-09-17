---
title: Troubleshooting Inactive Shadow Copy on PC
date: 2024-09-14T04:27:51.056Z
updated: 2024-09-17T02:31:01.388Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Inactive Shadow Copy on PC
excerpt: This Article Describes Troubleshooting Inactive Shadow Copy on PC
keywords: Fix Shadow Backup Error,Reactivate Snapshots PC,Reset Shadow Services,Enable Shadow Copy,Restore System Backups,Revive Inactive Copies,Shadow Copy Failure Remedies
thumbnail: https://thmb.techidaily.com/f4b94a6052a83b6c87620891bae2ef1d10a06ae6e718f7d201b09964291e2b88.jpg
---

## Troubleshooting Inactive Shadow Copy on PC

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139108/17108" target="_top" id="2139108">
  <img src="//a.impactradius-go.com/display-ad/17108-2139108" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139108/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115950/19272" target="_top" id="2115950">
  <img src="//a.impactradius-go.com/display-ad/19272-2115950" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115950/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-the-quintessential-browsers-screen-recorder-guide-for-professionals/"><u>[New] In 2024, The Quintessential Browsers' Screen Recorder Guide for Professionals</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-10-groundbreaking-final-cut-pro-extensions-for-2024/"><u>[Updated] 10 Groundbreaking Final Cut Pro Extensions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/download-and-maximize-your-mobile-experience-with-factory-pros-hd-video-conversion-guide/"><u>Download & Maximize Your Mobile Experience with Factory Pro's HD Video Conversion Guide</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-techniques-for-downloading-vevo-video-content/"><u>Effortless Techniques for Downloading Vevo Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-youtube-downloads-top-tools-for-saving-your-favorite-videos/"><u>Effortless YouTube Downloads: Top Tools for Saving Your Favorite Videos</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-convert-shn-files-with-our-leading-audio-converter-now-supports-mp3-flac-and-wav-formats/"><u>Effortlessly Convert SHN Files with Our Leading Audio Converter - Now Supports MP3, FLAC & WAV Formats!</u></a></li>
<li><a href="https://win11.techidaily.com/free-trial-of-factory-pro-mp4-video-converter-with-secure-payment-option/"><u>Free Trial of Factory Pro MP4 Video Converter with Secure Payment Option</u></a></li>
<li><a href="https://win11.techidaily.com/free-video-editing-tips-how-to-insert-texts-without-any-watermark-issues/"><u>Free Video Editing Tips: How to Insert Texts Without Any Watermark Issues</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-amd-radeon-rx-t-6800-drivers-supported-on-multiple-windows-versions/"><u>Get Your AMD Radeon RX T 6800 Drivers: Supported on Multiple Windows Versions</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-system-up-to-date-latest-dolby-driver-software-for-win111081/"><u>Get Your System Up to Date: Latest Dolby Driver Software for Win11/10/8.1</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-changing-audio-format-from-m4a-to-wav-in-windows-10/"><u>Guide to Changing Audio Format From M4A to WAV in Windows 10</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-apex-keys-tracker-models-for-easy-access/"><u>The Apex Keys Tracker Models for Easy Access</u></a></li>
<li><a href="https://technical-tips.techidaily.com/understanding-the-distinctions-between-signal-vs-whatsapp-encryption/"><u>Understanding The Distinctions Between Signal Vs. WhatsApp Encryption</u></a></li>
<li><a href="https://fox-that.techidaily.com/unlocking-the-secrets-to-optimizing-iphone-amos-battery-efficiency-and-health-issues/"><u>Unlocking the Secrets to Optimizing iPhone Amo's Battery Efficiency and Health Issues</u></a></li>
<li><a href="https://fox-info.techidaily.com/virtually-vivacious-top-humorous-memes-for-the-metaverse-enthusiasts/"><u>Virtually Vivacious Top Humorous Memes for the Metaverse Enthusiasts</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    