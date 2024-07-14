---
title: Correcting Faulty Windows Update Error
date: 2024-07-13T10:31:46.769Z
updated: 2024-07-14T10:31:46.769Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Faulty Windows Update Error
excerpt: This Article Describes Correcting Faulty Windows Update Error
keywords: Fix Windows Update Issue,Resolve Updater Errors,Stop Window Update Failures,End System Update Problems,Eliminate Update Crashes,Correct Windows Update Glitch,Solve Update Faults Effectively
thumbnail: https://thmb.techidaily.com/d108669ab03559524bb77121c4032c30df350e077c8698244c3203b72aed2547.jpg
---

## Correcting Faulty Windows Update Error

 BriWindows Update is a critical component of the Windows operating system that keeps your system up to date with the latest security patches and bug fixes. Although these updates are generally helpful, they can result in Windows malfunctioning or displaying error messages.

 Windows Update Error Code 0x80190001 is one such error that appears when you try to install a system update. In this article, we'll look at what causes Windows Update Error 0x80190001 and how to fix it.

## What Causes Windows Update Error 0x80190001?

 Windows Update Error 0x80190001 occurs most often when trying to download and install Windows Updates. It can make your computer feel outdated, slow, and unresponsive since it won't receive important security updates.

 Common causes of this error may include incorrect time and date settings, corrupted or faulty system files, and incompatible third-party security software. In this article, we'll discuss each of these issues in more detail so that you can get your Windows Updates running again.

Here are a few things you can try if you encounter this error.

## 1\. Restart Your Computer

 A corrupted system file is often the cause of the Windows Update Error. To fix the issue and get your system running again, restarting your computer is always a good start.

 It’s important to note that simply clicking “Restart” in Windows will not reset all the memory caches and processes. Instead, you may need to perform a hard reboot. For this, you will need to hold down the power button on your device for 3-4 seconds until it completely shuts off.

 After that, you should wait for 30 seconds and then hit the power button again to turn on the computer. Upon restarting, check to see if Windows Update has now started working correctly.

## 2\. Run Windows Update Troubleshooter

 The Windows Update Troubleshooter is an important tool to have. This program works to detect, diagnose and resolve any potential system update issues, ensuring that your computer runs smoothly and securely.

To try it, follow these steps:

1. Press**Win + I** on your keyboard to [open System Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**System** from the left side of the screen.
3. Then go to**Troubleshoot > Other troubleshooters** .  
![Run Windows Update Troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Run-Windows-Update-Troubleshooter.jpg)
4. Click the**Run** option next to Windows Update.

 It may take some time for troubleshooting to be completed, so don't worry if it takes longer than expected. After completing the above steps, try installing updates on Windows.

## 3\. Check Your Date & Time

 Incorrect dates and times can interfere with Windows Update, so make sure your system's time and date are accurate. Here's how to do this:

1. Right-click on**Start** and select**Settings** from the menu list.
2. From the left pane, select the**Time & language** option.
3. Click**Date & time** on the right.
4. Turn on the toggle next to "Set the time automatically".

 You should also double-check your time zone so that Windows knows when the updates should be installed - otherwise, it may ignore them.

## 4\. Run an SFC and DISM Scan

 If you’re still having trouble installing a Windows update, chances are you have corrupted or missing system files. To resolve this, you must first run SFC and DISM.

 An SFC (System File Checker) scan will detect any corrupted system files and attempt to repair them, while a DISM (Deployment Image Servicing and Management) scan will check for any broken Windows components that need repairing.

 Both scans are relatively quick and straightforward processes that don’t require any advanced technical knowledge. All you need to do is open Command Prompt as an administrator and follow these steps:

1. Run Command Prompt as an administrator (see [how to run Command Prompt as an administrator](<http://How> to Run the Command Prompt as an Administrator in Windows) ).
2. If UAC appears, click**Yes** to grant privileges.
3. Type the command in the Command Prompt window:**sfc /scannow** .
4. Then press**Enter** on your keyboard.  
![SFC and DISM Scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/SFC-and-DISM-Scan.jpg)

 The process will take a few minutes to complete. If you wish, you can do other things while the system scans the data. Once the process is completed, try updating Windows again.

 If the problem persists, you should run the Deployment Image Servicing and Management command line tool to restore system files and repair any corrupted system images. Here are the steps to follow:

1. Open Command Prompt with admin access as above.
2. Type the following command and press**Enter** to execute:  
DISM /Online /Cleanup-Image /ScanHealthDism.exe /online /cleanup-image /restorehealth

 You may have to wait for a while for the process to complete. After you run the DISM command, restart your computer to see if the issue has been resolved.

## 5\. Clear the SoftwareDistribution Folder

 Clearing the SoftwareDistribution folder will delete all temporary files created when Windows updates are downloaded and installed. This will free up space on your computer and potentially resolve any errors you are experiencing. Here's how to do this:

1. Press**Win + R** to open the Run dialog box.
2. Type "cmd" in the text box and press**Ctrl + Shift + Enter** on your keyboard.
3. When UAC appears on the screen, click**Yes** to continue. This will open Command Prompt with admin access
4. In the Command Prompt, type these commands then press**Enter** each time:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
5. After executing those commands, open Windows File Explorer.
6. Browse to the following path:**C:\\Windows\\SoftwareDistribution** .
7. Delete all content inside the SoftwareDistribution folder. Now you need to restart any services that were previously stopped.
8. In order to do this, run the following commands from an elevated Command Prompt.  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`

 Restart your computer after you have completed the above steps. You should now be able to update Windows.

​​​​

## 6\. Perform a Clean Boot

 Performing a clean boot helps eliminate software conflicts and can be an effective way of resolving Windows Update errors like 0x80190001\. So, try this out if none of the above solutions work.

1. Click on Start and search for**System Configuration** .
2. Select the**Best match** from the search results.
3. In the System Configuration window, go to the**General** tab.
4. Check for**Selective startup** .  
![Perform-a-Clean-Boot-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Perform-a-Clean-Boot-1.jpg)
5. Remove the check mark from**Load startup items** .

1. On the Services tab, select**Hide all Microsoft services** .  
![Hide all Microsoft services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Hide-all-Microsoft-services.jpg)
2. Then click**Disable all** .
3. Click**Apply** to save your changes.
4. Now switch to the Startup tab and click the**Open Task Manager** link.  
![Open Task Manager Via Startup tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Open-Task-Manager-Via-Startup-tab.jpg)
5. On the**Startup** tab, right-click each service and disable it.
6. To save your changes, click**OK** in the System Configuration window,

 Once you have finished the steps above, restart your computer and try updating Windows again. If you find this method helpful, it means the problem lies with one of the services you disabled. As such, enable each service one by one and identify the one causing the problem.

## Fixing Windows Update Error 0x80190001

 Windows Update Error 0x80190001 can be a frustrating issue to deal with, causing your system to become insecure and out of date. Fortunately, this article contains several strategies to help you identify and resolve this issue.

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
<li><a href="https://win11.techidaily.com/aesthetic-revamp-for-windows-11-status-area-include-a-chosen-weather-symbol/"><u>Aesthetic Revamp for Windows 11 Status Area: Include a Chosen Weather Symbol</u></a></li>
<li><a href="https://win11.techidaily.com/winning-against-access-denied-a-comprehensive-guide-to-5-solutions/"><u>Winning Against 'Access Denied': A Comprehensive Guide to 5 Solutions</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-google-meet-on-youtube-streaming-made-easy-step-by-step/"><u>[New] Google Meet on YouTube  Streaming Made Easy, Step by Step</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-a-comprehensive-overview-of-discord-stickers/"><u>[Updated] 2024 Approved  A Comprehensive Overview of Discord Stickers</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-desktop-on-windows-11-with-vibrant-backdrops/"><u>Transform Your Desktop on Windows 11 with Vibrant Backdrops</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-change-your-apple-id-password-on-your-apple-iphone-se-2020-by-drfone-ios/"><u>In 2024, How To Change Your Apple ID Password On your Apple iPhone SE (2020)</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-sign-out-problem-due-to-malware-intrusion/"><u>Remedying Windows Sign-Out Problem Due to Malware Intrusion</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-strategic-sharing-of-tiktok-content-on-twitter/"><u>[New] Strategic Sharing of TikTok Content on Twitter</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-unleash-your-adventure-essential-tactics-for-saving-your-vr-gaming-experience/"><u>[Updated] Unleash Your Adventure  Essential Tactics for Saving Your VR Gaming Experience</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-pasting-snippets-via-crafted-keybinds-in-windows-11-and-11/"><u>Effortless Pasting Snippets via Crafted Keybinds in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/busted-byteguardian-wait-weigh-your-worthiness/"><u>Busted ByteGuardian? Wait, Weigh Your Worthiness</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-az-capture-extraordinaire-thorough-app-reviews-for-2024/"><u>[Updated] AZ Capture Extraordinaire  Thorough App Reviews for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-d3d11-hardware-error-in-w11w10-environments/"><u>Fixing D3D11 Hardware Error in W11/W10 Environments</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-advanced-tips-for-bordered-instagram-photography/"><u>[Updated] 2024 Approved  Advanced Tips for Bordered Instagram Photography</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-free-video-watermark-software-our-top-recommendations/"><u>Updated Free Video Watermark Software Our Top Recommendations</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-sneak-peeks-into-instagrams-latest-hacks/"><u>[New] Sneak Peeks Into Instagram's Latest Hacks</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-mastering-thumbnail-extraction-from-youtube-on-multiple-platforms/"><u>In 2024, Mastering Thumbnail Extraction From Youtube on Multiple Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-error-pitfalls-with-anydesk-on-windows-platforms/"><u>Avoiding Error Pitfalls with AnyDesk on Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-the-memory-integrity-feature-grayed-out-on-windows-11/"><u>7 Ways to Fix the Memory Integrity Feature Grayed Out on Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/nokia-g310-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Nokia G310 Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-a-roadmap-for-monetization-success-on-youtube-via-adsense/"><u>[Updated] In 2024, A Roadmap for Monetization Success on YouTube via AdSense</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-xbox-mic-in-windows-11/"><u>Troubleshooting Non-Functional Xbox Mic in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/handling-glitches-in-microsofts-nearby-sharing-service/"><u>Handling Glitches in Microsoft's Nearby Sharing Service</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-cpu-consumption-by-dropbox-on-windows-pcs/"><u>Decreasing Excessive CPU Consumption by Dropbox on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/windows-update-unpopular-version-11-among-users/"><u>Windows Update – Unpopular Version 11 Among Users</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/inverting-image-hues-in-photoshop/"><u>Inverting Image Hues in Photoshop</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-breaking-down-instagrams-per-video-ceiling/"><u>[New] 2024 Approved  Breaking Down Instagram's Per-Video Ceiling</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-erroneous-non-existing-device-alert-on-win-11/"><u>Overcoming Erroneous Non-Existing Device Alert on Win 11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-to-make-a-slideshow-on-iphone-for-2024/"><u>New How to Make a Slideshow on iPhone for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-discoverability-of-lost-network-elements-in-winos/"><u>Enhancing Discoverability of Lost Network Elements in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-activate-superior-control-over-windows-11-task-management/"><u>How to Activate Superior Control Over Windows 11 Task Management</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-not-found-the-ultimate-list/"><u>Overcoming Windows Not Found: The Ultimate List</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-streamlining-your-storytelling-adding-captions-on-instagram/"><u>[Updated] Streamlining Your Storytelling  Adding Captions on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-map-a-network-drive-in-windows-11/"><u>How to Map a Network Drive in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ease-system-load-cutting-back-on-malware-scanning-power/"><u>Ease System Load: Cutting Back on Malware Scanning Power</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-the-ultimate-list-best-free-video-special-effects-apps-for-ios-and-android/"><u>New The Ultimate List Best Free Video Special Effects Apps for iOS and Android</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-your-emulated-games-into-playnite-on-windows/"><u>How to Add Your Emulated Games Into Playnite on Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-show-wi-fi-password-on-nubia-by-drfone-android/"><u>How to Show Wi-Fi Password on Nubia</u></a></li>
<li><a href="https://win11.techidaily.com/from-obscured-space-to-optimization-windows-guide-for-reclaiming-disk/"><u>From Obscured Space to Optimization: Windows Guide for Reclaiming Disk</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-vivo-by-fonelab-android-recover-contacts/"><u>Possible solutions to restore deleted contacts from Vivo .</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unlocking-your-creative-potential-embrace-these-top-10-iphone-image-rules/"><u>2024 Approved  Unlocking Your Creative Potential  Embrace These Top 10 iPhone Image Rules</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/youtubes-creative-commons-a-guide-for-videographers/"><u>YouTube’s Creative Commons  A Guide for Videographers</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensively-unveiling-windows-11s-narrator-commands/"><u>Comprehensively Unveiling Windows 11'S Narrator Commands</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-unlocking-idevice-screen-playback-perfection-for-2024/"><u>[Updated] Unlocking iDevice Screen Playback Perfection for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-s-hottest-adobe-premiere-title-templates-20-free-downloads/"><u>Updated S Hottest Adobe Premiere Title Templates 20 Free Downloads</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-behind-the-lens-wisdom-the-best-cinemagraph-tips/"><u>[Updated] Behind-the-Lens Wisdom  The Best Cinemagraph Tips</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-streamline-memory-management-via-mematic/"><u>[New] Streamline Memory Management via Mematic</u></a></li>
<li><a href="https://win11.techidaily.com/guidance-to-reconnect-controlled-audio-from-windows-bluetooth-devices/"><u>Guidance to Reconnect Controlled Audio From Windows' Bluetooth Devices</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-solutions-workarounds-when-renaming-folders-is-impossible-on-win-11/"><u>Innovative Solutions: Workarounds When Renaming Folders Is Impossible on Win 11</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-from-raw-to-richness-creating-and-merging-impressive-hdr-photos/"><u>2024 Approved  From Raw to Richness  Creating & Merging Impressive HDR Photos</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-guide-for-crafting-engaging-shareable-youtube-shorts/"><u>2024 Approved  The Ultimate Guide for Crafting Engaging, Shareable YouTube Shorts</u></a></li>
<li><a href="https://win11.techidaily.com/handling-dxgierrordeviceremoved-in-win-10-and-11/"><u>Handling DXGI_ERROR_DEVICE_REMOVED in Win 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-jamboree-discovering-5-entertaining-techniques/"><u>Command Prompt Jamboree: Discovering 5 Entertaining Techniques</u></a></li>
<li><a href="https://review-topics.techidaily.com/quick-fixes-to-repair-microsoft-excel-2019-content-related-error-stellar-by-stellar-guide/"><u>Quick Fixes to Repair Microsoft Excel 2019 Content related error | Stellar</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-detailed-review-of-doctorsim-unlock-service-for-apple-iphone-se-drfone-by-drfone-ios/"><u>In 2024, Detailed Review of doctorSIM Unlock Service For Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-pathway-errors-with-windows-devices/"><u>Addressing Pathway Errors with Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/activate-direct-search-within-windows-11s-task-manager-interface/"><u>Activate Direct Search Within Windows 11'S Task Manager Interface</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-windows-camera-conflict-error-0xa00f4243/"><u>Remedying Windows' Camera Conflict Error 0xA00F4243</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/smooth-decline-techniques-for-controlled-audio-reduction/"><u>Smooth Decline Techniques for Controlled Audio Reduction</u></a></li>
<li><a href="https://win11.techidaily.com/xbox-games-on-windows-avoid-common-setup-pitfalls/"><u>Xbox Games on Windows: Avoid Common Setup Pitfalls</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-quick-recording-tips-mastering-screen-captures-on-hp-systems/"><u>[New] 2024 Approved  Quick Recording Tips  Mastering Screen Captures on HP Systems</u></a></li>
<li><a href="https://win11.techidaily.com/escape-heavy-requirements-tiny11-delight/"><u>Escape Heavy Requirements: Tiny11 Delight</u></a></li>
<li><a href="https://win11.techidaily.com/7-w11-ui-aspects-that-seem-out-of-place/"><u>7 W11 UI Aspects That Seem Out of Place</u></a></li>
<li><a href="https://win11.techidaily.com/a-slumberful-cycle-for-your-pcs-life/"><u>A Slumberful Cycle for Your PC's Life</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-tiktok-unboxing-hacks-spin-your-video-into-a-viral-hit/"><u>2024 Approved  TikTok Unboxing Hacks  Spin Your Video Into a Viral Hit</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-top-7-watermark-free-video-combining-tools/"><u>In 2024, Top 7 Watermark-Free Video Combining Tools</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-leave-a-life360-group-on-honor-x50-gt-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How To Leave a Life360 Group On Honor X50 GT Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-conflicting-apps-camera-use-windows-error-0xa00f4243/"><u>Addressing Conflicting Apps' Camera Use: Windows Error 0xA00F4243</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-key-differences-between-windows-terminal-and-powershell/"><u>Understanding Key Differences Between Windows Terminal and PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/harness-the-power-of-shortcut-creation-on-windows-11/"><u>Harness the Power of Shortcut Creation on Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-ultimate-guide-to-unlocking-apple-watch-or-apple-iphone-12-mini-from-icloud-by-drfone-ios/"><u>The Ultimate Guide to Unlocking Apple Watch Or Apple iPhone 12 mini from iCloud</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-best-vivo-y100a-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Vivo Y100A Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-wi-fi-showing-limited-access-in-windows-11/"><u>9 Ways to Fix Wi-Fi Showing Limited Access in Windows 11</u></a></li>
</ul></div>
