---
title: Mending Failed Volume Backup in Microsoft OS
date: 2024-09-05T08:26:27.087Z
updated: 2024-09-06T08:26:27.087Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Mending Failed Volume Backup in Microsoft OS

 If the Volume Shadow Copy service isn't working, you'll see error messages when you try to use Backup and Restore or System Restore in Windows. We'll show you how you can fix Volume Shadow Copy when it's not working on a Windows PC, so you can get your backups going once more.

## 1\. Enable and Start Volume Shadow Copy Services

 VSS errors can often arise because the Volume Shadow Copy and Microsoft Software Shadow Copy Provider services aren’t enabled or running. For example, many users have confirmed enabling those services can fix VSS error codes 0x81000202 and 0x81000203, which affect the System Restore tool. So, you may be able to resolve numerous Volume Shadow Copy errors by enabling VSS services like this:

1. First, press the **Windows** logo key + **S** and enter a Services search phrase to find that app.
2. Click **Services** inside the search results.
3. Double-click the **Volume Shadow Copy Service**.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/services-window.jpg)
4. Click the drop-down menu labeled **Startup type** and select **Automatic** if the service is set differently.  
<!-- affiliate ads begin -->
<span id="1983573">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983573.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983573">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983573.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983573%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983573/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aidotcom.pxf.io/c/5597632/2129043/19576" target="_top" id="2129043">
  <img src="//a.impactradius-go.com/display-ad/19576-2129043" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129043/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<span id="1975658">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975658.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975658">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975658.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975658%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975658/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

<!-- affiliate ads begin -->
<span id="1498635">
					<video width="320" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1498635.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17326-1498635">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1498635.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:200px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fancheer.sjv.io%2Fc%2F5597632%2F1498635%2F17326'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1498635/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123476/16836" target="_top" id="2123476">
  <img src="//a.impactradius-go.com/display-ad/16836-2123476" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123476/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136617/26400" target="_top" id="2136617">
  <img src="//a.impactradius-go.com/display-ad/26400-2136617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136617/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

## Back up and Restore Windows Again

 These solutions can potentially resolve many variable Volume Shadow Copy Service error messages and codes that pop up during system backup and restore operations. With Volume Shadow Copy fixed, you can back up and restore Windows with built-in system tools again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/024-approved-tag-tactics-amplifying-your-gaming-content-online/"><u>[New] 2024 Approved  Tag Tactics  Amplifying Your Gaming Content Online</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-premier-apps-for-extracting-and-saving-youtube-videos-on-android/"><u>[New] 9 Premier Apps for Extracting and Saving YouTube Videos on Android</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-comprehensively-capturing-your-messenger-conversations/"><u>[New] In 2024, Comprehensively Capturing Your Messenger Conversations</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-infinite-frontier-the-best-sci-fi-films-that-redefine-universes-for-2024/"><u>[New] Infinite Frontier  The Best Sci-Fi Films That Redefine Universes for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unleash-potential-with-latest-windows-10-apps-and-games/"><u>[New] Unleash Potential with Latest Windows 10 Apps and Games</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-stand-out-on-social-media-discover-a-hundredplus-creative-frameworks-for-your-snap-stories/"><u>[Updated] 2024 Approved  Stand Out on Social Media  Discover a Hundred+ Creative Frameworks for Your Snap Stories</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-unleash-your-creative-vision-a-guide-to-android-editors/"><u>[Updated] 2024 Approved  Unleash Your Creative Vision  A Guide to Android Editors</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-accelerating-streamed-instagram-content-mobile-hacks/"><u>[Updated] In 2024, Accelerating Streamed Instagram Content  Mobile Hacks</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-mastering-pip-macos-sierras-guide-to-multimedia-magic-for-2024/"><u>[Updated] Mastering PIP  MacOS Sierra's Guide to Multimedia Magic for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-dichotomy-of-digital-immersion-in-vr/"><u>[Updated] The Dichotomy of Digital Immersion in VR</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722874815669-achieving-cross-platform-messaging-integrating-imessage-into-android/"><u>Achieving Cross-Platform Messaging: Integrating iMessage Into Android</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719581197529-be-a-polyglot-in-minutes-enjoy-a-staggering-95-savings/"><u>Be a Polyglot in Minutes - Enjoy a Staggering 95%% Savings</u></a></li>
<li><a href="https://buynow-help.techidaily.com/brilliant-imagery-unleashed-with-the-49-ultra-hd-4k-samsung-tv-an-exclusive-review-of-model-xbr-49x90/"><u>Brilliant Imagery Unleashed with the 49 Ultra HD, 4K Samsung TV - An Exclusive Review of Model XBR-49X90 #</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-phantom-hardware-listings-on-windows-system/"><u>Correcting Phantom Hardware Listings on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-folder-dimensions-with-powershell-scripts/"><u>Deciphering Folder Dimensions with PowerShell Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-the-workings-of-windows-sound-graph-separation/"><u>Delving Into the Workings of Windows' Sound Graph Separation</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/direct-from-instagram-masterful-techniques-for-igtv-video-transferring-for-2024/"><u>Direct From Instagram  Masterful Techniques for IGTV Video Transferring for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/discover-how-windows-outclasses-linux-in-gaming/"><u>Discover How Windows Outclasses Linux in Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-taskbar-functionality-on-windows-11/"><u>Elevate Taskbar Functionality on Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/exploring-the-potential-of-verizons-revolutionary-5g-technology/"><u>Exploring the Potential of Verizon's Revolutionary 5G Technology</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-to-windows-help-top-5-routes-uncovered/"><u>Fast Track to Windows Help - Top 5 Routes Uncovered</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-11s-discord-javascript-crisis-a-step-by-step-approach/"><u>Fixing Windows 11'S Discord JavaScript Crisis: A Step-by-Step Approach</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722976194775-free-corsair-icue-software-downloads-for-windows-users-enhance-your-gaming-setup/"><u>Free Corsair iCUE Software Downloads for Windows Users: Enhance Your Gaming Setup!</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/game-on-select-sandbox-adventures-await/"><u>Game On  Select Sandbox Adventures Await</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-edge-off-windows-11-shapes/"><u>How to Edge Off: Windows 11 Shapes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-nokia-105-classic-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Nokia 105 Classic to Outlook | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/innovate-taskbar-functionality-with-additional-folders-in-11/"><u>Innovate Taskbar Functionality with Additional Folders in 11</u></a></li>
<li><a href="https://win11.techidaily.com/is-the-xbox-app-not-working-on-windows-try-these-fixes/"><u>Is the Xbox App Not Working on Windows? Try These Fixes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/key-top-5-ultra-light-action-recording-models/"><u>Key Top 5 Ultra-Light Action Recording Models</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-change-of-guard-swapping-your-windows-11-logon-method/"><u>Navigating the Change of Guard: Swapping Your Windows 11 Logon Method</u></a></li>
<li><a href="https://win11.techidaily.com/no-more-compatibility-woes-fix-your-programs-in-windows/"><u>No More Compatibility Woes: Fix Your Programs in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-limitations-maximizing-ram-in-windows/"><u>Overcoming Limitations: Maximizing RAM In Windows</u></a></li>
<li><a href="https://win11.techidaily.com/propel-your-productivity-top-5-must-have-windows-11-apps/"><u>Propel Your Productivity: Top 5 Must-Have Windows 11 Apps</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-easy-fixes-to-reinstall-overlooked-windows-apps/"><u>Quick and Easy Fixes to Reinstall Overlooked Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-missing-windows-quick-fixes-for-windows-1011/"><u>Reviving Missing Windows: Quick Fixes for Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-digital-life-weekly-windows-backups/"><u>Securing Your Digital Life: Weekly Windows Backups</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-techniques-to-purge-image-borders/"><u>Simplified Techniques to Purge Image Borders</u></a></li>
<li><a href="https://win11.techidaily.com/starting-storytelling-voice-commands-in-windows-11/"><u>Starting Storytelling: Voice Commands in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-mitigating-the-failed-lunar-client-launch-errors/"><u>Strategies for Mitigating the Failed Lunar Client Launch Errors</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-fix-disk-read-error-in-windows/"><u>Strategies to Fix Disk Read Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-for-xps-xffffffff-printer-failure/"><u>Swift Solutions for XP's XFFFFFFFF Printer Failure</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-for-unlocking-blank-login-portals-on-win1011/"><u>Tactics for Unlocking Blank Login Portals on Win10/11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-hidden-perils-navigating-the-pitfalls-of-ai-in-therapy-and-counseling/"><u>Unveiling the Hidden Perils: Navigating the Pitfalls of AI in Therapy and Counseling</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-size-spectrum-of-your-windows-apps/"><u>Unveiling the Size Spectrum of Your Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/user-hesitation-the-hold-back-on-windows-11-upgrade/"><u>User Hesitation: The Hold Back on Windows 11 Upgrade</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>