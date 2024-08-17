---
title: Fixes for Frozen Windows Volume Backup Service
date: 2024-08-16T00:28:14.236Z
updated: 2024-08-17T00:28:14.236Z
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
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->

## 3\. Run the Check Disk Utility

 Drive issues can cause Windows system backup VSS errors to occur, with codes like 0x807800A1 or 0x80042315\. In this case, running the Check Disk utility to scan for and address hard drive issues, such as bad sectors, is a potential fix for the Volume Shadow Copy Service not working. Check out this [guide to running the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) for further details about how you can apply this potential resolution.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/chkdsk-scan-command.jpg)

## 4\. Disable Antivirus Shields

 Sometimes third-party antivirus software can interfere with and prevent Volume Shadow Copy from functioning correctly. So, try disabling third-party antivirus shields before attempting to back up or restore Windows. The usual way to do that is to right-click on an antivirus app’s system tray icon and select a disable/turn off shield protection option from there.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->

 Don’t leave your antivirus shield permanently disabled. If possible, select to disable it for a few hours before attempting the backup or system restoration operation again. Or manually re-enable your antivirus if you can’t select a temporary option.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Disable Any Active Firewalls

 It’s also recommended to disable the firewall component of a third-party antivirus utility before attempting to perform a VSS operation. Turning off an antivirus shield won’t disable a firewall component. Look for firewall settings within your antivirus software’s tabs to see if it includes one. If it does, select to turn off the firewall.

 Try turning off the Windows firewall if you haven’t installed a third-party antivirus utility or firewall software. Check out this guide to [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) for instructions for turning off that security component.

![The Turn off Windows Defender Firewall option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-firewall-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Set Windows to Perform a Clean Boot

![The Startup type](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/startup-tab.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->

 Conflicting background apps or services are another potential cause of Volume Shadow Copy errors. Third-party backup utilities with snapshot managers are the most likely software packages to conflict with the Volume Shadow Copy Service. If you know you’ve installed a third-party backup manager, uninstalling it could be the best way to ensure it doesn’t cause any conflicts.

 However, you can [perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) to stop third-party apps and services from starting with Windows to prevent conflicts from arising. This involves disabling startup items and services with Task Manager and MSConfig and restarting Windows. Then try utilizing the Windows Backup and Restore or System Restore tools after clean booting your PC to see if the VSS error persists.

 If it does, this means something you disabled during the clean boot is causing the problem. Now you can slowly re-enable each app until the problem reappears, then either uninstall or update the offending app.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-bitrecorder-analysis-with-other-solutions/"><u>[New] 2024 Approved  BitRecorder Analysis with Other Solutions</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-stealth-instagram-story-viewing-guide-for-desktops-android-and-ios/"><u>[New] 2024 Approved  Stealth Instagram Story Viewing Guide for Desktops, Android & iOS</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-efficiency-in-action-rapid-removal-of-youtube-discussions/"><u>[New] In 2024, Efficiency in Action  Rapid Removal of YouTube Discussions</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-ultimate-list-watching-nba-in-real-time/"><u>[New] The Ultimate List  Watching NBA in Real-Time</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-venture-into-virtual-laughs-top-20plus-funny-metaverse-creations/"><u>[New] Venture Into Virtual Laughs  Top 20+ Funny Metaverse Creations</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-accessing-global-hitters-the-1-6-short-video-downloaders-for-2024/"><u>[Updated] Accessing Global Hitters  The #1-#6 Short Video Downloaders for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-becoming-a-video-marketing-vanguard-on-facebook-with-these-20-methods/"><u>[Updated] In 2024, Becoming a Video Marketing Vanguard on Facebook with These 20 Methods</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-evaluating-tseries-business-model-with-youtube-viewership-metrics/"><u>[Updated] In 2024, Evaluating TSeries' Business Model with YouTube Viewership Metrics</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-the-first-time-filmmakers-guide-to-gear-selection/"><u>[Updated] In 2024, The First-Time Filmmaker's Guide to Gear Selection</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-structuring-tutorials-for-clarity-on-youtube/"><u>[Updated] Structuring Tutorials for Clarity on YouTube</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-flawless-frameworks-premium-webcams-for-your-podcasts/"><u>2024 Approved  Flawless Frameworks  Premium Webcams for Your Podcasts</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-invest-in-quality-top-5-handhoced-stabilizers-review/"><u>2024 Approved  Invest in Quality  Top 5 Handhoced Stabilizers Review</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-make-every-story-stand-out-6-top-rated-apps-for-android-and-iphone/"><u>2024 Approved  Make Every Story Stand Out  6 Top-Rated Apps for Android & iPhone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-honor-x7b-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Honor X7b Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/7-game-changing-windows-11-additions-in-moment-22h2/"><u>7 Game-Changing Windows 11 Additions in Moment #22H2</u></a></li>
<li><a href="https://win11.techidaily.com/7-windows-utilities-to-update-file-timestamps/"><u>7 Windows Utilities To Update File Timestamps</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-rectifying-mmc-snap-in-failures/"><u>A Guide to Rectifying MMC Snap-In Failures</u></a></li>
<li><a href="https://win11.techidaily.com/accessible-controls-filter-key-management-in-windows/"><u>Accessible Controls: Filter Key Management in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-fixing-device-disabled-error-code-22-on-windows-11/"><u>Addressing and Fixing Device Disabled (Error Code 22) on Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-play-mp4-files-on-redmi-note-12r-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Can't play MP4 files on Redmi Note 12R</u></a></li>
<li><a href="https://win11.techidaily.com/changing-file-formats-on-windows-os/"><u>Changing File Formats on Windows OS</u></a></li>
<li><a href="https://extra-hints.techidaily.com/closing-credits-creations-affordable-premium-and-more/"><u>Closing Credits Creations  Affordable, Premium & More</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-access-denial-mysteries/"><u>Deciphering Windows Access Denial Mysteries</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-windows-system-update-warnings/"><u>Disabling Windows System Update Warnings</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-voice-typing-hiccup-with-windows-error-code-x80049dd3-solution/"><u>Eliminating the Voice Typing Hiccup with Window's Error Code X80049DD3 Solution</u></a></li>
<li><a href="https://hardware-help.techidaily.com/enhance-scanning-with-the-new-software-version-download-for-canoscan-lide-220/"><u>Enhance Scanning with the New Software Version: Download for CanoScan LiDE 220</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/expedited-srt-to-txt-conversion-2023s-efficient-method-for-2024/"><u>Expedited SRT to TXT Conversion  2023'S Efficient Method for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-operational-intel-wi-fi-ax201-on-pcs/"><u>Fixing Non-Operational Intel Wi-Fi AX201 on PCs</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/flourish-in-social-settings-mastering-verbal-exchanges/"><u>Flourish in Social Settings: Mastering Verbal Exchanges</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/gunners-gratitude-discovering-our-top-7-shooter-games-for-2024/"><u>Gunner's Gratitude  Discovering Our Top 7 Shooter Games for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/how-to-add-music-in-premiere-pro-for-2024/"><u>How To Add Music In Premiere Pro for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-brothers-mfc-l2700-dw-drivers-seamlessly-windows-users-ultimate-solution/"><u>How to Install Brother's MFC-L2700 DW Drivers Seamlessly: Windows Users’ Ultimate Solution</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-discover-the-ultimate-top-5-iphone-applications-for-podcasts/"><u>In 2024, Discover the Ultimate Top 5 iPhone Applications for Podcasts</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-essential-srt-knowledge-for-all-levels/"><u>In 2024, Essential SRT Knowledge for All Levels</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-infinix-hot-30-5g-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Infinix Hot 30 5G Pattern Lock Screen</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-oppo-k11-5g-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Oppo K11 5G</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-professional-stability-systems-for-youtube-filmmakers/"><u>In 2024, Professional Stability Systems for YouTube Filmmakers</u></a></li>
<li><a href="https://extra-hints.techidaily.com/innovative-srt-conversion-tactics-for-pc-and-mac/"><u>Innovative SRT Conversion Tactics for PC and Mac</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-removing-false-device-notifications/"><u>Mastering the Art of Removing False Device Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-restoring-ccleaner-on-win11/"><u>Mastering the Art: Restoring CCleaner on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-integrating-dynamic-desktop-backgrounds/"><u>Mastering Windows 11: Integrating Dynamic Desktop Backgrounds</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-warhammer-40k-boltgun-stopping-stutter-issues-on-pc/"><u>Mastery Over Warhammer 40K Boltgun: Stopping Stutter Issues on PC</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-mouse-precision-and-reduce-system-lag/"><u>Maximize Mouse Precision and Reduce System Lag</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-top-6-free-video-watermark-software/"><u>New Top 6 Free Video Watermark Software</u></a></li>
<li><a href="https://win11.techidaily.com/nine-no-go-areas-for-novice-windows-11-users/"><u>Nine No-Go Areas for Novice Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-legacy-computer-for-windows-11-via-to-go-and-rufus/"><u>Optimize Your Legacy Computer for Windows 11 via To Go & Rufus</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-marketplace-colour-glitches/"><u>Rectifying Windows Marketplace Colour Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-failures-restoring-java-on-windows-devices/"><u>Resolving Failures: Restoring Java on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-lost-volume-preferences-after-software-changes/"><u>Restoring Lost Volume Preferences After Software Changes</u></a></li>
<li><a href="https://win11.techidaily.com/secure-and-efficient-storage-controlling-ntfs-compression-in-win11/"><u>Secure & Efficient Storage: Controlling NTFS Compression in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/secure-uninterrupted-usage-in-your-windows-dashboard/"><u>Secure Uninterrupted Usage in Your Windows Dashboard</u></a></li>
<li><a href="https://win11.techidaily.com/simple-steps-to-wireless-gaming-setup-dualshock-on-pc/"><u>Simple Steps to Wireless Gaming: Setup DualShock on PC</u></a></li>
<li><a href="https://win11.techidaily.com/smoothing-windows-11-update-combat-error-0x30017/"><u>Smoothing Windows 11 Update: Combat Error 0X30017</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-instructions-fully-removing-wsl/"><u>Step-By-Step Instructions: Fully Removing WSL</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-11-cannot-open-for-writing/"><u>Steps to Overcome Windows 11: Cannot Open For Writing</u></a></li>
<li><a href="https://fox-that.techidaily.com/still-want-to-silence-that-noise-fix-an-iphones-broken-mute-feature-here/"><u>Still Want to Silence That Noise? Fix an iPhone's Broken Mute Feature Here</u></a></li>
<li><a href="https://win11.techidaily.com/tech-renaissance-atlasos-for-obsolete-systems/"><u>Tech Renaissance: AtlasOS for Obsolete Systems</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tango-dancing-devices-androidwindows-synchro/"><u>Tech Tango: Dancing Devices - Android/Windows Synchro</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-forgotten-directx-apps-with-dxvk-support/"><u>Transforming Forgotten DirectX Apps with DXVK Support</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-1011s-aural-output-via-audacity/"><u>Troubleshooting Windows 10/11'S Aural Output, via Audacity</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-recommended-games-on-windows-11-screen/"><u>Turn Off Recommended Games on Windows 11 Screen</u></a></li>
<li><a href="https://win11.techidaily.com/unclouding-your-display-secrets-to-a-sharp-windows-11-screen/"><u>Unclouding Your Display: Secrets to a Sharp Windows 11 Screen</u></a></li>
<li><a href="https://win11.techidaily.com/unmatched-assistance-best-free-tools-for-a-win11-revamp/"><u>Unmatched Assistance: Best Free Tools for a Win11 Revamp</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-workings-of-windows-component-services/"><u>Unveiling the Workings of Windows Component Services</u></a></li>
<li><a href="https://win11.techidaily.com/win1110-nat-transition-altering-type-effectively/"><u>Win11/10 NAT Transition: Altering Type Effectively</u></a></li>
</ul></div>
