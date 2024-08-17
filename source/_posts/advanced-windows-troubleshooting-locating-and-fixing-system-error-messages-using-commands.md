---
title: "Advanced Windows Troubleshooting: Locating & Fixing System Error Messages Using Commands"
date: 2024-08-15T23:19:50.368Z
updated: 2024-08-16T23:19:50.368Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Advanced Windows Troubleshooting: Locating & Fixing System Error Messages Using Commands"
excerpt: "This Article Describes Advanced Windows Troubleshooting: Locating & Fixing System Error Messages Using Commands"
keywords: WinTroubleshootCommands,ErrorMsgFixWindows,WindowsErrorSolution,TroubleshootWinErrors,FixSystemWMessages,CommandsForWinErrors,SystemMessageResolve
thumbnail: https://thmb.techidaily.com/33493674183189bab67b88de79a85b9996c293935f6ec3a823ac568973956aae.jpg
---

## Advanced Windows Troubleshooting: Locating & Fixing System Error Messages Using Commands

 Encountering random errors and crashes while using the operating system without an explanation can be frustrating. It also makes it harder to find the appropriate solutions, because you have no clue what caused the problem in the first place.

 In this guide, we will show you how you can use the Command Prompt utility to identify potential culprits behind annoying Windows errors. We will also discuss how you fix the issue using CMD as well.

## How to Diagnose Windows Errors in the Command Prompt

 To solve a problem in Windows, such as an update error or a Blue Screen of Death, it's important to identify the potential causes of the issue. Windows comes with several utilities that can help you with this, one of which is Command Prompt.

 Below, we have discussed different ways of using Command Prompt to look up Windows error codes.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
### 1\. Use the NET HELPMSG Command

 The NET HELPMSG command helps convert error codes into strings, which you can use to find relevant solutions for the problem. However, this command can only help you with system error codes, which are specific numerical values. This means you cannot use it for BSOD errors like the INACCESSIBLE\_BOOT\_DEVICE error.

Moreover, the numerical value of the error code must also be precise.

Here is how you can use this command:

1. Press the**Win + R** keys together to open a Run dialog.
2. Type "cmd" in Run and press the**Ctrl + Shift + Enter** keys together to open Command Prompt with administrative privileges.
3. Click**Yes** in the User Account Control prompt.
4. Once you are inside the Command Prompt window, type the command mentioned below and hit**Enter** to execute it. Replace <error code> with the numerical value of the code.  
`NET HELPMSG <error code>`
5. For instance, if the error code you want lookup is 8242, your command will be:  
`NET HELPMSG 8242​​​`  
![Execute the net helpmsg command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/net-helpmsg-error.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->

 Once you have the details on the error code, you can either look for solutions online or jump to the solutions listed later in this guide.

### 2\. Use the CertUtil Command

 Another easy way to look up error descriptions using the Command Prompt is by using the CertUtil command. This command is typically used for managing certificates and certificate services, but can also be a helpful tool in finding short explanations for the error codes.

Here is how you can use it:

1. Open Command Prompt using the steps we have described above.
2. In the Command Prompt window, execute the command below. Replace <error code> with the error code you are encountering:  
`CertUtil /error <error code>`
3. So for instance, if you are encountering the update error 0x80070002, your command will be:  
`CertUtil /error 0x80070002​​​​`  
![Execute the entered command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/certutil-command.jpg)

 You should now be presented with a description of the error message. You can use this detail to identify the culprit and eliminate it.

### 3\. Access the Event Viewer

 When you encounter an error on Windows, a log file for the error is created in the Event Viewer. This log file contains the details of the event, including the time and date it occurred, the error code associated with it, and the source of the event.

 You can [access the Event Viewer using the Command Prompt](https://www.makeuseof.com/windows-open-event-viewer/) to identify the culprit behind the error, and then proceed with the relevant solutions to fix the problem.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Resolve the Problem Using the Command Prompt

 Once you have identified the problem, you can use the Command Prompt utility to fix it as well. Windows comes with a set of troubleshooting utilities that can you can run via this command-line interface to resolve system issues once and for all.

 Here are some common ways you can use the Command Prompt to diagnose and resolve various issues with your Windows operating system.

### 1\. Fix Any Corruption Errors

 There are a number of problems that may result from corruption errors and bugs within the operating system, such as frequent crashes and freezes, boot problems, data loss, and slow performance.

 The easiest way to fix such issues is by [running the built-in SFC and DISM tools](https://www.makeuseof.com/windows-built-in-repair-tools/) via Command Prompt.

![Run SFC and DISM scans](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/scannow-restorehealth-cmd-1.jpg)

 SFC or the System File Checker works by scanning the protected system files to check their integrity. It will compare the files to a stable version stored in the Windows component store or the installation media. If a problem with the file is identified, the utility will automatically replace the file with its healthier counterpart and generate a report based on it.

 DISM, on the other hand, can be used to repair a wide range of issues, including system files, problematic drivers, and a corrupt Windows image. It is considered to be more advanced and powerful than SFC.

 Once you have completed an SFC scan, you can check the log file for more detailed information as well. Simply execute this command:

`findstr /c:"[SR]" %windir%\logs\cbs\cbs.log >"%userprofile%\Desktop\sfcdetails.txt`

 Doing so will create a log file named sfcdetails.txt on your desktop, listing all the issues found during the scan.

### 2\. Uninstall Windows Updates

 There are times when an update you install on the system turns out to be buggy or corrupt, leading to different issues within the system.

 Since Windows provides you with the option to uninstall updates, you can use Command Prompt to achieve this.

 Simply open Command Prompt as an administrator and execute the command listed below to view a list of installed updates:

`wmic qfe list brief /format:table`

 To uninstall one, execute the following command. Replace <HotFixID> with the ID number of the update that you want to uninstall.

`wusa /uninstall /kb:<HotFixID>`

![Uninstall the update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-update-cmd.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. Fix Boot Issues

 If you are having trouble booting into Windows, or the boot time is just painfully slow, the issue is likely to be related to the boot sector or boot configuration data (BCD).

You can use the bootrec command to repair these via Command Prompt.

Here is how you can do that:

1. [Boot into WinRE](https://www.makeuseof.com/ways-to-boot-into-the-windows-recovery-environment/) and head over to Repair your computer.
2. Navigate to**Troubleshoot** \>**Advanced options** .  
![WinRE-Advanced-Options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/winre-advanced-options.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
3. Choose**Command Prompt** from the list of options available.
4. Once you are in the Command Prompt window, execute the following commands:  
`bootrec /fixmbr bootrec /fixboot bootrec /rebuildbcd`
5. If you are prompted with Add installation to boot list?, type Y and hit Enter.
6. Once all the commands are executed, you can exit Command Prompt by typing exit and hitting Enter.
7. Restart your computer, and you should be able to boot into Windows successfully!

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
## The Command Prompt to the Rescue

 Having knowledge of certain Windows tools can come in handy when dealing with various computer-related issues. One such utility that can help you find solutions is Command Prompt and knowing how to use it can save you both time and frustration.

 We highly recommend backing up your essential data before making any changes to your operating system, just to be safe. With a little patience and some troubleshooting skills, you can get rid of annoying Windows errors for good.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-free-open-source-video-conferencing-solutions-the-ultimate-list-for-corporates-and-schools/"><u>[New] 2024 Approved  Free, Open Source Video Conferencing Solutions  The Ultimate List for Corporates & Schools</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-address-tweets-stuck-while-watching-online/"><u>[New] In 2024, Address  Tweets Stuck While Watching Online</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-video-size-for-standout-instagram-content-for-2024/"><u>[New] Mastering Video Size for Standout Instagram Content for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-8-step-formula-for-captivating-your-instagram-audience-with-reels-for-2024/"><u>[New] The 8-Step Formula for Captivating Your Instagram Audience with Reels for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-ultimate-selection-best-idevice-custom-alerts/"><u>[Updated] In 2024, Ultimate Selection  Best iDevice Custom Alerts</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-the-complete-guide-to-proficient-use-of-screenrec-software-for-2024/"><u>[Updated] The Complete Guide to Proficient Use of ScreenRec Software for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlock-the-power-of-social-sharing-for-your-youtube-videos/"><u>[Updated] Unlock the Power of Social Sharing for Your YouTube Videos</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-enhancing-imagery-with-smart-layers-in-photoshop/"><u>2024 Approved  Enhancing Imagery with Smart Layers in Photoshop</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-saving-face-to-face-with-hangouts/"><u>2024 Approved  Saving Face-to-Face with Hangouts</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-select-8-dynamic-backgrounds-for-your-mbp/"><u>2024 Approved  Select 8 Dynamic Backgrounds for Your MBP</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-unparalleled-background-music-compilation/"><u>2024 Approved  Unparalleled Background Music Compilation</u></a></li>
<li><a href="https://win11.techidaily.com/breakthrough-strategies-expert-methods-for-decoding-qr-codes-on-pcs/"><u>Breakthrough Strategies: Expert Methods for Decoding QR Codes on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/breakthrough-restoring-access-to-shared-windows-data/"><u>Breakthrough: Restoring Access to Shared Windows Data</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-onedrive-to-windows-microsoft-services/"><u>Bridging OneDrive to Windows Microsoft Services</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-restoring-your-tab-on-a-pc/"><u>Bridging the Gap: Restoring Your Tab on a PC</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-back-the-search-box-in-win11-task-management/"><u>Bringing Back the Search Box in Win11 Task Management</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-blocked-windows-defender-in-win-11/"><u>Bypass Blocked Windows Defender in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-buffering-in-chrome-for-seamless-youtube-playback/"><u>Bypass Buffering in Chrome for Seamless YouTube Playback</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-pin-check-error-on-w11w10-bluetooth-devices/"><u>Bypass Pin Check Error on W11/W10 Bluetooth Devices</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-the-cant-add-your-folder-now-immediate-fixes-for-onedrive-on-pc/"><u>Bypass the 'Can't Add Your Folder Now': Immediate Fixes for OneDrive on PC</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-windows-alert-for-unverified-adobe/"><u>Bypass Windows Alert for Unverified Adobe</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-session-verification-error-with-steams-vac/"><u>Bypassing “Session Verification” Error with Steam’s VAC</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-error-code-0xa00f425d-on-windows-1011-camera/"><u>Bypassing Error Code: 0XA00F425D on Windows 10/11 Camera</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-limited-it-administrator-power-error-on-windows/"><u>Bypassing Limited IT Administrator Power Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-obstacles-fixing-microsoft-office-activation-issues/"><u>Bypassing Obstacles: Fixing Microsoft Office Activation Issues</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-obstacles-fixing-windows-11-login-hitches/"><u>Bypassing Obstacles: Fixing Windows 11 Login Hitches</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-read-only-settings-for-windows-folders/"><u>Bypassing Read-Only Settings for Windows Folders</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-default-settings-forcefully-remove-print-devices/"><u>Bypassing the Default Settings: Forcefully Remove Print Devices</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-10-and-11s-vital-parts-required-errors/"><u>Bypassing Windows 10 & 11'S 'Vital Parts Required' Errors</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-signature-checks-for-easy-updates/"><u>Bypassing Windows' Signature Checks for Easy Updates</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-the-windows-1111-store-fault-x800704cf/"><u>Ceasing the Windows 11/11 Store Fault X800704CF</u></a></li>
<li><a href="https://win11.techidaily.com/chatgpt-windows-integration-tutorial/"><u>ChatGPT Windows Integration Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-intel-graphic-spec-limitations-a-guide-to-improvement/"><u>Circumventing Intel Graphic Spec Limitations: A Guide to Improvement</u></a></li>
<li><a href="https://win11.techidaily.com/classic-game-catch-up-storing-vintage-games-in-w11-folder/"><u>Classic Game Catch-Up: Storing Vintage Games in W11 Folder</u></a></li>
<li><a href="https://win11.techidaily.com/clear-and-clean-automating-your-files-end-of-life-in-windows/"><u>Clear and Clean: Automating Your Files' End of Life in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-roadblocks-for-seamless-amd-software-setup/"><u>Clearing Roadblocks for Seamless AMD Software Setup</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-camera-app-glitches-on-windows-11s-f429f-issue/"><u>Clearing Up Camera App Glitches on Windows 11'S F429F Issue</u></a></li>
<li><a href="https://win11.techidaily.com/closing-the-gap-between-pc-and-androids-pace/"><u>Closing The Gap Between PC and Android's Pace</u></a></li>
<li><a href="https://win11.techidaily.com/code-crash-confounder-no-more-your-quick-fix-guide-to-windows/"><u>Code Crash Confounder No More: Your Quick Fix Guide to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/coherent-ideas-at-a-glance-via-obsidian-canvas/"><u>Coherent Ideas at a Glance via Obsidian Canvas</u></a></li>
<li><a href="https://win11.techidaily.com/combat-lossed-graphics-a-guide-for-overwatch-2-players/"><u>Combat Lossed Graphics: A Guide for Overwatch 2 Players</u></a></li>
<li><a href="https://win11.techidaily.com/combat-strategies-for-operational-error-740-in-windows-devices/"><u>Combat Strategies for Operational Error #740 in Windows Devices</u></a></li>
<li><a href="https://article-files.techidaily.com/from-cluttered-to-clear-a-canva-guide-for-borders-removal-for-2024/"><u>From Cluttered to Clear  A Canva Guide for Borders Removal for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/from-views-to-revenue-simplifying-the-process-with-a-3-step-framework-for-monitoring-youtube-income/"><u>From Views to Revenue  Simplifying the Process with a 3-Step Framework for Monitoring YouTube Income</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-find-lost-iphone-11-pro-max-backup-files-on-windows-pc-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to find lost iPhone 11 Pro Max Backup files on Windows PC? | Stellar</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-excel-2010-files-stellar-by-stellar-guide/"><u>How to Repair Corrupt Excel 2010 Files | Stellar</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-breaking-free-from-quik-exploring-the-best-pc-video-editors-for-gopro-users/"><u>In 2024, Breaking Free From Quik Exploring the Best PC Video Editors for GoPro Users</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-full-guide-to-unlock-your-infinix-hot-40-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Infinix Hot 40</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-leave-a-life360-group-on-oppo-reno-9a-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How To Leave a Life360 Group On Oppo Reno 9A Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-streaming-tweets-on-whatsapp-a-2023-guide/"><u>In 2024, Streaming Tweets on WhatsApp  A 2023 Guide</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-unlock-the-magic-for-fbs-10-music-vids-recipe-book/"><u>In 2024, Unlock the Magic for FB's #10 Music Vids Recipe Book</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/insta-friends-lost-tracking-your-unfollowers-for-2024/"><u>Insta Friends Lost  Tracking Your Unfollowers for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/maximizing-engagement-with-strategic-editing-on-instagram-videos-for-2024/"><u>Maximizing Engagement with Strategic Editing on Instagram Videos for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-compact-guide-to-transforming-vocal-identity-quickly-in-pubg-for-2024/"><u>The Compact Guide to Transforming Vocal Identity Quickly in PUBG for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-successful-syncing-of-your-firestick-remote/"><u>Ultimate Guide: Successful Syncing of Your Firestick Remote</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unlocking-color-grading-with-luts-in-pscc/"><u>Unlocking Color Grading with LUTs in PSCC</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-how-to-add-motion-blur-in-davinci-resolve-in-2024/"><u>Updated How To Add Motion Blur In Davinci Resolve, In 2024</u></a></li>
</ul></div>
