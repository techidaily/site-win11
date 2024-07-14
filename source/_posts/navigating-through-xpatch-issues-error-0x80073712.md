---
title: "Navigating Through XPatch Issues: Error 0X80073712"
date: 2024-07-13T10:20:43.444Z
updated: 2024-07-14T10:20:43.444Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigating Through XPatch Issues: Error 0X80073712"
excerpt: "This Article Describes Navigating Through XPatch Issues: Error 0X80073712"
keywords: XPatch Fix #0X80073712,XPatch Error Code 0X80073712,Overcoming XPatch Error 73712,Resolve XPatch 0X73712 Error,XPatch Issue #0X80073712,Fixing Xpatch Error 73712,XPatch Problem 0X80073712 Solution
thumbnail: https://thmb.techidaily.com/bd1f3164b21938808543fb77a181f9a976b01572cf9b49cfe1852edc61f82d53.jpg
---

## Navigating Through XPatch Issues: Error 0X80073712

 Microsoft frequently releases updates to fix security issues, and introduce new features and stability to the Windows OS. But not all updates install smoothly on your system and trigger an error code while doing so. Many users share their woes with the 0x80073712 update error code with the error message that some files are missing from the system.

 If you experience the same update error code and are unable to install the latest Windows update, don’t worry. We will list out all the possible fixes that you can try to resolve the 0x80073712 error code.

## 1\. Use the Windows Troubleshooter

 Before jumping onto major fixes, leverage the in-built troubleshooter on Windows 10 and 11\. It tries to find out existing problems with Windows Update and try to fix them. Repeat the following steps:

1. Press**Win + I** to launch the settings app.
2. Navigate to the**System > Troubleshoot** section.
3. Click on the**Other Troubleshooter** option.
4. Locate the**Windows Update troubleshooter** option from the list.
5. Then, click on the**Run** button to start the troubleshooter.  
![Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-update-troubleshooter.jpg)
6. Wait for the Windows Update troubleshooter to identify problems. Click on the**Next** button.
7. Close the troubleshooter window and reattempt the Windows update installation.

## 2\. Perform a Complete system shutdown

 Windows OS enables the fast startup option by default. Even if you restart your system, or shut it down, it preserves the system state using hibernate. So, you need to perform a complete system shutdown and then power it back on to close and restart all background services.

Here’s how to perform a complete system shutdown:

1. Press**Win + X** to launch the Power user menu. Scroll down and select the**Terminal (Admin)** option from the list.
2. The Terminal app will open with an instance of a command prompt with admin privileges.
3. Type the**shutdown /s /f /t 0** command and press the**enter** key.
4. Your system will power off. It will take a tad bit longer that a normal shutdown procedure.
5. Now, restart your Windows PC and try to install the Windows update.

## 3\. Restart Windows Update services

 Windows Update uses a bunch of background services to fetch and download updates. If these services aren’t running automatically, you will encounter an error. These include**Windows Update Service** ,**Windows Installer Service** ,**Cryptographic Services** , and**Background Intelligent Transfer Service** .

Repeat the following steps to start the necessary services:

1. Press**Win + R** to [launch the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**services.msc** and press the**enter** key
2. Services utility will launch on your system. Now locate the**Background Intelligent Transfer** service in the list.
3. Double-click on the BITS service to open the**properties** window. Set the**Startup Type** as**Automatic** and click on the**Apply** button.  
![Disabling Windows Update Services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disabling-windows-update-services.jpg)
4. Click on the**OK** button and close the Properties windows. Now, right-click on the service and select the**Start** option from the context menu.
5. Similarly, set all the services as automatic and manually start them.
6. **Close** the Services window and reattempt the Windows update.

## 4\. Run the Disk Cleanup Tool

 Disk Cleanup can wipe the delivery optimization files, old Windows update files as well as the Temp folder. If files in these locations are corrupted, they can interfere with the normal update process. Here’s how to run disk cleanup on Windows:

1. Press**Win + S** to open the search utility in Windows.
2. Type**cleanmgr.exe** and press the enter key to open the Disk Cleanup tool.
3. It will select the system drive (C) by default. Click on the**OK** button to continue.
4. Select the checkboxes of files that you want the tool to clean up. Then, click on the**Clean up system files** button.  
![Disk Cleanup App in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disk-cleanup-app-in-windows-11.jpg)
5. Disk Cleanup will close and redirect you to pick the appropriate drive. Click on the**OK** button.
6. Lastly, click on the**Delete files** button.

## 5\. Rename the SoftwareDistribution Folder

 Windows update stores its content in the SoftwareDistribution folder. Since it is located inside the Windows folder in the C drive, you mustn’t delete it. Instead, you can rename the folder to force the update service to recreate the folder again.

Repeat the following steps:

1. Open the Start menu and search CMD. Press Ctrl + Shift + Enter to open the command prompt with admin privileges.
2. Type the following commands to stop all the Windows update-related services:  
 net stop wuauserv net stop cryptSvc net stop bits net stop msiserver  
![Rename the SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder.jpg)
3. Once these services stop running, type**cls** in the command prompt windows. Then enter the following commands:  
 ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old ren C:\\Windows\\System32\\catroot2 Catroot2.old  
![Rename the SoftwareDistribution Folder 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-2.jpg)
4. Both the above commands rename the**SoftwareDistribution** folder and**Catroot2** folder.
5. Now, you need to restart all the Windows services you stopped in step 3\. Enter the following commands:  
net start wuauserv net start cryptSvc net start bits net start msiserver  
![Rename the SoftwareDistribution Folder 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/rename-the-softwaredistribution-folder-3.jpg)
6. Lastly,**restart** your system and visit the following folder location:**C:\\Windows** . You will notice that there is a new SoftwareDistribution folder in that location.
7. Open the Windows update in Settings and try to download and install updates.

## 6\. Delete the Pending.xml file

 The pending.xml file contains all the pending Windows update tasks. Oftentimes, it can interfere with installing new updates because there are already multiple incomplete old update tasks. So, you must delete this file and proceed with the Windows update.

Retrace the following steps to delete the pending.xml file:

1. Log in with an administrator account. Then, press**Win + E** to launch the file explorer.
2. Navigate to the**C:\\Windows\\WinSxS** folder.
3. Locate the**pending.xml** in the**WinSxS** folder and right-click on it.
4. Press the**Shift** key and click on the**Delete** option.
5. Restart your computer.

## 7\. Manually Download Windows Updates

 If you are unable to download a specific Windows update using the Settings page, consider a direct download and install approach. Visit the Microsoft Update Catalog website and search for the KB update you want to download. However, you first have to check the corresponding update number which is failing to download and install on your system.

![Manually Download Windows Updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/manually-download-windows-updates.jpg)

## 8\. Reset Windows

 Resetting Windows is the last resort you have if none of the above methods work in your favor. However, before learning [how to perform a Windows system reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) , try out general fixes such as [SFC, CHKDSK, and DISM](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) scans on your system. Also,[disable Windows Defender](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and try updating your system before hitting the reset button.

## Update Windows Without Hiccups

 Windows updates can be tricky to install sometimes. Use the inbuilt troubleshooter to identify and fix problems. After that restart, all the crucial Windows update services and run the Disk Cleanup tool. If everything else fails, try doing a manual update or performing a Windows Reset.


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
<li><a href="https://win11.techidaily.com/ceasing-erratic-mouse-movement-in-windows/"><u>Ceasing Erratic Mouse Movement in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-and-resolving-steam-service-disruptions-in-windows-11/"><u>Unraveling & Resolving Steam Service Disruptions in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/pinpoint-and-prevent-windows-drive-vanishing/"><u>Pinpoint and Prevent Windows Drive Vanishing</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/innovative-use-of-instagram-filters-in-your-photo-posts-for-2024/"><u>Innovative Use of Instagram Filters in Your Photo Posts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-security-basics-in-windows-11-setup/"><u>Restoring Security Basics in Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-11-taskbar-discrepan-marketplace/"><u>Rectifying Windows 11 Taskbar Discrepan Marketplace</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-language-gurus-selection-of-top-30-tools-to-translate-videos/"><u>[New] The Language Guru’s Selection of Top 30 Tools to Translate Videos</u></a></li>
<li><a href="https://youtube-data.techidaily.com/he-art-of-flawless-audio-capture-mic-free-for-2024/"><u>[New] The Art of Flawless Audio Capture, Mic-Free for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unblocked-windows-reviving-context-menus-swiftly/"><u>Unblocked Windows: Reviving Context Menus Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-memory-efficiency-for-device-interaction-windows/"><u>Streamlining Memory Efficiency for Device Interaction Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-exploring-seamless-approaches-to-finding-discord-groups-for-2024/"><u>[Updated] Exploring  Seamless Approaches to Finding Discord Groups for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-robloxs-restrictive-error-403-on-pc/"><u>Unraveling Roblox's Restrictive Error 403 on PC</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Xiaomi Redmi Note 12R | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-unleash-your-creativity-best-lightweight-video-editing-apps/"><u>2024 Approved Unleash Your Creativity Best Lightweight Video Editing Apps</u></a></li>
<li><a href="https://win11.techidaily.com/stepping-past-the-steam-file-access-hurdle/"><u>Stepping Past the Steam “File Access” Hurdle</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-enhancement-in-wt-with-personalized-schemes/"><u>Aesthetic Enhancement in WT with Personalized Schemes</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-image-adjustment-the-six-essential-techniques/"><u>Windows 11 Image Adjustment: The Six Essential Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/wrapping-windows-games-in-christmas-carols/"><u>Wrapping Windows Games in Christmas Carols</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-quick-solutions-for-cursor-on-black-screen/"><u>Win10/11: Quick Solutions for Cursor on Black Screen</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-infinix-hot-40-pro-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed Guide on Faking Your Location in Mozilla Firefox On Infinix Hot 40 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-reinitializing-unwanted-apps/"><u>Mastering Window 11: Reinitializing Unwanted Apps</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-access-control-personalized-windows-pin-creation/"><u>Revolutionize Access Control: Personalized Windows Pin Creation</u></a></li>
<li><a href="https://win11.techidaily.com/provide-examples-from-real-life-where-understanding-another-cultures-perspective-could-lead-to-better-communication-and-relationships/"><u>Provide Examples From Real Life Where Understanding Another Culture's Perspective Could Lead to Better Communication and Relationships.</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-screen-snafus-with-sonic-frontiers-securing-smooth-play-on-w11/"><u>Navigating Screen Snafus with Sonic Frontiers - Securing Smooth Play on W11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-blueprints-to-locate-top-tier-videographers/"><u>[New] 2024 Approved  Blueprints to Locate Top-Tier Videographers</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-on-space-spotlight-on-large-files-in-windows/"><u>Cutting Down on Space: Spotlight on Large Files in Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/delete-gmail-account-withwithout-password-on-realme-10t-5g-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Realme 10T 5G</u></a></li>
<li><a href="https://win11.techidaily.com/1719376947968-regain-your-account-in-microsoft-store-now/"><u>Regain Your Account in Microsoft Store, Now!</u></a></li>
<li><a href="https://win11.techidaily.com/converting-from-pin-to-password-a-windows-11-users-guide-for-enhanced-security/"><u>Converting From PIN to Password: A Windows 11 User's Guide for Enhanced Security</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-error-code-0xa00f425d-in-windows-1e11-camera/"><u>Correcting Error Code: 0XA00F425D in Windows 1E11 Camera</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-wacatacbml-understanding-and-neutralizing-threats-on-windows/"><u>Breaking Down Wacatac.B!ml: Understanding and Neutralizing Threats on Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-ranked-instagram-tunes-and-secrets-for-exceptional-call-alerts/"><u>2024 Approved  Top-Ranked Instagram Tunes & Secrets for Exceptional Call Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-stalker-unveiled-preventive-measures-against-wacatacbml/"><u>The Silent Stalker Unveiled: Preventive Measures Against Wacatac.B!ml</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-itel-p55t-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Itel P55T to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-transcoding-ttml-and-ssa-into-easy-to-use-srt-format/"><u>[Updated] Transcoding TTML & SSA Into Easy-to-Use SRT Format</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-solving-error-0x80073d26-in-xbox-app/"><u>Mastering the Art of Solving Error 0X80073D26 in Xbox App</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-nokia-g42-5g-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Nokia G42 5G to New Phone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-history-top-removed-and-evolved-characteristics/"><u>Windows History: Top Removed and Evolved Characteristics</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-how-to-rotate-a-video-on-vlc-media-player/"><u>[New] In 2024, How to Rotate A Video on VLC Media Player</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-batch-save-presentations-in-video-format-for-2024/"><u>[Updated] Batch Save Presentations in Video Format for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-rectify-slow-windows-app-connections-for-peak-performance/"><u>Swiftly Rectify Slow Windows App Connections for Peak Performance</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-network-drive-setup-a-comprehensive-walkthrough/"><u>Win11's Network Drive Setup: A Comprehensive Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-control-set-active-hours-to-avoid-surprises-on-windows-11/"><u>Cutting Edge Control: Set Active Hours to Avoid Surprises on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-stop-background-programs/"><u>Mastering Window 11: Stop Background Programs</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-ignite-interest-captivate-views-elevate-likes-on-your-unboxings/"><u>[Updated] Ignite Interest, Captivate Views  Elevate Likes on Your Unboxings</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-beatbox-recorder-a-compreeved-guide-for-2024/"><u>[New] BeatBox Recorder  A Compreeved Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-image-clarity-with-windows-11s-enhanced-photo-app/"><u>Maximizing Image Clarity with Windows 11'S Enhanced Photo App</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-system-performance-wins-top-diagnostic-list/"><u>Smooth System Performance: Win's Top Diagnostic List</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-boosting-viewership-mastery-in-youtube-shorts-design/"><u>In 2024, Boosting Viewership  Mastery in YouTube Shorts Design</u></a></li>
<li><a href="https://win11.techidaily.com/1719193162154-unlocking-the-secrets-to-fixing-non-working-win-plus-printer/"><u>Unlocking The Secrets to Fixing Non-Working Win + Printer.</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/on-the-road-and-recorded-essential-helmet-cams-unveiled-for-bikers-gear-for-2024/"><u>On the Road & Recorded - Essential Helmet Cams Unveiled for Bikers' Gear for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-computing-10-top-alternatives-to-windows-defaults/"><u>Redefining Computing: 10 Top Alternatives to Windows' Defaults</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-12-prominent-vivo-y100i-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Vivo Y100i Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-google-chrome-glitch-on-windows-11-now/"><u>Break Free From Google Chrome Glitch on Windows 11 Now!</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/dazzling-deception-youtubes-editors-magic-showcase-for-2024/"><u>Dazzling Deception  YouTube's Editors Magic Showcase for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-perfect-sync-blueprint-for-android-plus-microsoft-os/"><u>The Perfect Sync Blueprint for Android + Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-connection-error-restoring-mb-link-on-windows-11/"><u>Overcoming Connection Error: Restoring MB Link on Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-bygone-beauty-iphone-x-portrait-moments/"><u>In 2024, Bygone Beauty  IPhone X Portrait Moments</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/craft-your-story-with-immersive-youtube-video-editing-tips-for-2024/"><u>Craft Your Story with Immersive YouTube Video Editing Tips for 2024</u></a></li>
</ul></div>
