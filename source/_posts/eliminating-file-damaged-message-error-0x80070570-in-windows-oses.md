---
title: Eliminating 'File Damaged' Message (Error 0X80070570) in Windows OSes
date: 2024-08-16T00:37:25.750Z
updated: 2024-08-17T00:37:25.750Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating 'File Damaged' Message (Error 0X80070570) in Windows OSes
excerpt: This Article Describes Eliminating 'File Damaged' Message (Error 0X80070570) in Windows OSes
keywords: File Error X070 Fix,Eliminate OS Error,X070 File Issue,Remove Windows Error,Clear Data Corruption,XP0X OS Fault Removal,Unblocking Files in Windows
thumbnail: https://thmb.techidaily.com/26d450fdec75a3cb5316781ad73e34df68fc7b736cd85313bb608d818166317c.jpg
---

## Eliminating 'File Damaged' Message (Error 0X80070570) in Windows OSes

 Error 0x80070570 is a Windows issue that sometimes pops up when you try to delete files on external hard drives. This error also occurs when users try to transfer files between PCs and external drives. The error 0x80070570 message says, “The file or directory is corrupted and unreadable.”

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.

## 1\. Repair System Files With an SFC Scan

 Some users have confirmed repairing system files resolved error 0x80070570 on their PCs. System File Checker is a command-line tool with which you can check for and repair corrupted system files that might be causing file operation issues. Check out our guide to [utilizing System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) for details about how to run an SFC scan within the Command Prompt.

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command2.jpg)

## 2\. Utilize the Check Disk Tool

 Drive file system issues often cause error 0x80070570\. The most widely confirmed solution for that error is to run a CHKDSK scan of the drive you can’t delete files on or transfer files to. The CHKDSK tool can repair file system errors on the drive it’s scanning.

![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/chkdsk-scan-command.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->

 Our [guide to running CHKDSK on Windows](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,let%20it%20do%20its%20work.) tells you how to initiate a Check Disk scan. You’ll need to run the Check Disk scan for the drive that includes the files you can’t delete or copy to. If that’s an external drive, you’ll need to connect the storage device to the PC and specify its letter within the command. For example, a CHKDSK command for scanning an external E: drive would be:

`chkdsk /r E:`

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Try Moving Files to a Different Location

 If error 0x80070570 when you’re trying to transfer a file, try moving (or copying) the file into a different folder location on the target drive. You can do that by right-clicking an affected file and selecting either **Cut** or **Copy**. Then right-click inside a different folder location and select **Paste** to see if the error occurs.

## 4\. Turn Off Real-Time Antivirus Shields

 Another possible factor for error 0x80070570 occurring is your PC’s antivirus shield is hindering the file operation. That could happen if your antivirus software wrongly flags files you’re trying to transfer between drives as suspicious. So, try temporarily disabling your antivirus shield before performing the required file operation.

![The Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/real-time-protection-option.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you don’t have third-party security software, turn off Windows Security’s real-time antivirus shield, as covered in our article about [disabling Microsoft Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/). .

 Users with third-party antivirus utilities will need to turn off their antivirus shields via the apps’ system tray context menus. Right-click the antivirus app’s icon in the system tray and select a disable or turn off shield protection setting.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Perform a Startup Repair

 This resolution is recommended if error 0x80070570 occurs when trying to delete files on the C: hard drive or transfer them there. Startup Repair is primarily a utility for fixing Windows startup issues. However, that tool can remedy corrupted system files and C: drive issues. This is how you can utilize Startup Repair:

1. First, [bring up the Advanced Startup Options menu](https://www.makeuseof.com/windows-11-access-advanced-startup-options/) via the Settings app.
2. Select **Startup Repair** within the Advanced options menu.  
![The Start-up Repair option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/start-up-repair.jpg)
3. Next, select your Windows user account.
4. Input your user account password.
5. Select **Continue** to initiate the repair.

## 6\. Format an External Drive

 Formatting an affected external drive to which you can’t transfer files or delete data because of error 0x80070570 is suggested only as a last resort. Applying this potential fix will wipe all data on the drive, so do not format your PC’s C: drive. However, some users have confirmed formatting affected external drives fixes error 0x80070570\.

![The format drive utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-format-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->

 You can format an external drive with the Windows Disk Management utility or in File Explorer. Connect the drive to your PC, and then follow the steps in this guide on [how to format a USB drive](https://www.makeuseof.com/tag/format-usb-drive/) to do this within File Explorer.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Perform the Required File Operations Again on Windows

 The potential error 0x80070570 solutions covered here have worked for many Windows 11/10 users. Repairing drive errors with the CHKDSK tool usually does the trick. You could also utilize a third-party utility like Hard Disk Sentinel and HDDScan to check for and repair drive issues. With error 0x80070570 fixed, you can copy or delete files as required again.

 Consequently, you can’t delete or copy files on drives affected by error 0x80070570\. It is an error code that predates Windows 8, but many users still encounter this issue on the latest Windows desktop platforms. As such, here is how you can fix error 0x80070570 on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/024-approved-visual-vocabulary-complimentary-youtube-art-tools/"><u>[New] 2024 Approved  Visual Vocabulary  Complimentary YouTube Art Tools</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-fb-ad-forecast-2024-essentials-you-cant-ignore/"><u>[New] FB Ad Forecast 2024  Essentials You Can't Ignore</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-ultimate-lighting-checklist-for-video-creators/"><u>[New] The Ultimate Lighting Checklist for Video Creators</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-creation-to-consumption-igtv-vs-youtube-explained-for-you/"><u>[Updated] 2024 Approved  From Creation to Consumption  IGTV Vs. YouTube Explained for You</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-capture-and-preserve-sound-on-windows-10/"><u>[Updated] Capture and Preserve Sound on Windows 10</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-platform-prowess-finding-your-future-in-obstwitch/"><u>[Updated] In 2024, Platform Prowess  Finding Your Future in OBS/Twitch</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-youtube-monetization-does-youtube-pay-monthly/"><u>[Updated] YouTube Monetization  Does YouTube Pay Monthly?</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-basics-of-slug-lines-explained/"><u>2024 Approved  The Basics of Slug Lines Explained</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-visual-impact-discover-these-essential-font-tools-for-tiktoks-2023/"><u>2024 Approved  Visual Impact  Discover These Essential Font Tools for TikTok's 2023</u></a></li>
<li><a href="https://win11.techidaily.com/5-key-strategies-for-overcoming-onedrive-errors/"><u>5 Key Strategies for Overcoming OneDrive Errors</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-system32-folder-on-windows-11/"><u>Accessing System32 Folder on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-discreprancies-in-power-usage-display-for-win-11-systems/"><u>Addressing Discreprancies in Power Usage Display for Win 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-empty-directory-issue-in-windows-11-error-0x80070091/"><u>Addressing Non-Empty Directory Issue in Windows 11: Error #0X80070091</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-ms-store-error-x7326/"><u>Addressing Windows 11 MS Store Error X7326</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-pictures-from-vivo-y100a-by-fonelab-android-recover-pictures/"><u>Best Android Data Recovery - Retrieve Lost Pictures from Vivo Y100A.</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-with-these-8-window-study-secrets/"><u>Boost Productivity with These 8 Window Study Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-breakdown-rehabilitating-win11s-ccleaner/"><u>Breaking the Breakdown: Rehabilitating Win11's CCleaner</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-new-life-into-vintage-films-with-madvr-for-windows/"><u>Breathe New Life Into Vintage Films with MadVR for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-platforms-windows-now-on-apples-ios-and-microsoft-devices/"><u>Bridging Platforms: Windows Now on Apple's iOS and Microsoft Devices</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-windows-11s-bluetooth-9-effective-fixes-at-hand/"><u>Bring Back Windows 11'S Bluetooth: 9 Effective Fixes at Hand</u></a></li>
<li><a href="https://win11.techidaily.com/browsing-made-lighter-top-7-windows-apps-for-less-memory-use/"><u>Browsing Made Lighter: Top 7 Windows Apps for Less Memory Use</u></a></li>
<li><a href="https://win11.techidaily.com/budget-blues-identifying-the-risks-of-low-cost-windows-licensing/"><u>Budget Blues: Identifying the Risks of Low-Cost Windows Licensing</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-frozen-windows-pin-with-easy-fixes/"><u>Bypass Frozen Windows Pin with Easy Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-non-responsive-power-switches-on-windows-11/"><u>Bypass Non-Responsive Power Switches on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-obstacles-quick-fixes-for-stuck-windows-apps/"><u>Bypass Obstacles: Quick Fixes for Stuck Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-chrome-blackout-a-step-by-step-guide/"><u>Bypassing Chrome Blackout: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-httptoomanyreq-error-quick-fixes-for-app-overloads/"><u>Bypassing HTTP_TOO_MANY_REQ Error: Quick Fixes for App Overloads</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-unknown-not-initialized-in-windows-operating-systems/"><u>Bypassing Unknown Not Initialized in Windows Operating Systems</u></a></li>
<li><a href="https://win11.techidaily.com/cant-sign-into-onedrive-on-windows-try-these-fixes/"><u>Can't Sign Into OneDrive on Windows? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/capture-notes-effortlessly-on-windows-11/"><u>Capture Notes Effortlessly on Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/capture-the-essence-of-movement-in-iphone-photography-for-2024/"><u>Capture the Essence of Movement in iPhone Photography for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/change-your-visual-preference-in-winterm/"><u>Change Your Visual Preference in WinTerm</u></a></li>
<li><a href="https://win11.techidaily.com/character-inspection-the-win11-way/"><u>Character Inspection: The Win11 Way</u></a></li>
<li><a href="https://win11.techidaily.com/charting-a-new-journey-away-from-lost-at-sea-xbox-errors/"><u>Charting a New Journey Away From Lost at Sea Xbox Errors</u></a></li>
<li><a href="https://win11.techidaily.com/chilly-warm-up-your-windows-11-with-holiday-hacks/"><u>Chilly Warm-Up Your Windows 11 with Holiday Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-on-windows-11-a-synopsis-of-app-removal-techniques-107-chars/"><u>Clean Slate on Windows 11: A Synopsis of App Removal Techniques (107 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-temporary-files-and-cache-from-spotify-app/"><u>Clearing Temporary Files and Cache From Spotify App</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-obstacles-winning-against-xps-print-error-xfddddf/"><u>Clearing the Obstacles: Winning Against XP's Print Error XFDDDDF</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-failed-to-launch-errors-with-your-pcs-display/"><u>Clearing Up “Failed to Launch” Errors with Your PC’s Display</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-dual-windows-devices-with-ms-error/"><u>Clearing Up Dual Windows Devices with MS Error</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-iomap64-blue-screen-of-death-issues-quickly/"><u>Clearing Up IOMap64 Blue Screen of Death Issues Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-local-device-misnaming-on-windows-systems/"><u>Clearing Up Local Device Misnaming on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-the-stuck-gpsvc-delay-mystery/"><u>Clearing Up the Stuck GPSVC Delay Mystery</u></a></li>
<li><a href="https://win11.techidaily.com/code-of-shadows-mastering-invisibles-in-win11/"><u>Code of Shadows: Mastering Invisibles in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/combat-the-vanishing-disk-space-paradox-on-windows/"><u>Combat the Vanishing Disk Space Paradox on Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-honor-x50-gt-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-apple-iphone-6s-plus-official-method-to-unlock-your-apple-iphone-6s-plus-by-drfone-ios/"><u>How To Unlock Apple iPhone 6s Plus Official Method to Unlock Your Apple iPhone 6s Plus</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-boost-your-channels-following-by-a-thousand/"><u>In 2024, Boost Your Channels' Following by a Thousand</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-realme-v30-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Realme V30</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-mastering-iphone-creating-and-editing-low-speed-video-clips/"><u>In 2024, Mastering iPhone  Creating & Editing Low-Speed Video Clips</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-stepwise-approach-to-exceptional-gopro-footage/"><u>In 2024, Stepwise Approach to Exceptional GoPro Footage</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-nubia-red-magic-8s-pro-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Nubia Red Magic 8S Pro</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ating-youtubes-algorithm-as-a-game-streamer-for-2024/"><u>Navigating YouTube's Algorithm as a Game Streamer for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-free-online-glitch-effect-software-the-best-options-for-designers/"><u>New 2024 Approved Free Online Glitch Effect Software The Best Options for Designers</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-6-best-voice-changers-for-chromebook-deserve-a-try/"><u>New In 2024, 6 Best Voice Changers for Chromebook Deserve a Try</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-samsung-galaxy-xcover-6-pro-tactical-edition-device-by-drfone-android/"><u>What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Samsung Galaxy XCover 6 Pro Tactical Edition Device</u></a></li>
</ul></div>
