---
title: Best Ways to Restore Default Window Options on System Startup
date: 2024-07-13T11:23:45.714Z
updated: 2024-07-14T11:23:45.714Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Best Ways to Restore Default Window Options on System Startup
excerpt: This Article Describes Best Ways to Restore Default Window Options on System Startup
keywords: Windows Customization (Startup),Default Window Settings,Restoring Windows State,Window Options Reinstate,Override UI Defaults,System Start Preferences,Change Startup Windows View
thumbnail: https://thmb.techidaily.com/5f19d12263b1224bd46b49560f2a184a0c0f8c0d56bb43f9e5c26e9a6768a6cd.jpg
---

## Best Ways to Restore Default Window Options on System Startup

 Imagine you’ve just spent hours tweaking your Windows settings—and then you reboot. What you find is that all changes you made have been reset to default settings. Before you give up and reset your computer to factory defaults, give these solutions a shot.

 In this article, we’ll explain what causes the issue and how you can fix it.

## Why Does Windows Reset Its Settings on Reboot?

 The Windows settings reset on reboot for several reasons. The most common cause is a user profile change, either due to a system update or a user’s action. In other cases, a running background application can corrupt user profiles. This can happen if an application crashes or is not updated. It’s also possible that malware is responsible for the issue.

 Sometimes, if there is a system error or a hardware issue like a faulty hard drive, Windows settings may reset when the computer restarts. This could happen due to an unforeseen power outage.

## How to Fix Windows Settings Resetting Upon Reboot

 The best way to fix Windows settings resetting upon reboot is to identify the cause of the problem and take corrective action. Here are some tips to get your settings back.

### 1\. Look Out for Suspicious Programs

 The first step is to check for malicious programs and other suspicious applications that may be causing your issue. If you find any, remove them immediately and check if it solves the problem. Here's how to do it.

1. Right-click on your Taskbar area and select**Task Manager** from the context menu. You can also press**Ctrl + Shift + Esc** if you prefer using shortcut keys.  
![Look Out for Suspicious Programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/look-out-for-suspicious-programs.jpg)
2. In the Task Manager window, switch to the**Processes** tab and look for any unfamiliar program or process that is hogging up your system resources.
3. Once you find a suspicious program, right-click on it and select**End task** to terminate the process.
4. Now go to the Windows Control Panel and uninstall the program.

 After uninstalling the program, restart your computer and check if the settings reset issue is resolved.

### 2\. Run Automatic Startup Repair

 If Windows continues to reset its settings upon reboot, you should try running the Automatic Startup Repair feature. This will help fix any system errors or corrupted files that may be causing the issue.

To run Automatic Startup Repair, follow these steps:

1. Press**Win + I** to open the Settings window.
2. From the left-hand menu, click the**System** tab.
3. On the right side of the window, scroll down and click the**Recovery** option.  
![Advanced startup in Recovery options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/advanced-startup-in-recovery-options.jpg)
4. Next to**Advanced startup** , click the**Restart now** button.
5. When your PC restarts, select**Troubleshoot** from the Choose an option screen.
6. Select**Advanced options** and then click**Startup Repair** .  
![Startup repair in Windows 10.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/startup-repair-1.jpg)

 Follow the on-screen instructions to run the automatic repair tool. After you complete the above process, restart your computer and check if it solves the issue.

### 3\. Check Your User Profile

 If the issue persists, check your user profile and make sure it’s not corrupt. If your user profile is corrupted, Windows will reset the settings when you restart. Here’s how to check it:

 Press**Windows + R** to open the Run command. In the dialog box, type**regedit** , and press Enter. If the User Account Control (UAC) window appears, click**Yes** to grant administrative privileges. This will launch the Registry Editor.

On the next screen, navigate to the following path:

`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList`

 In the**ProfileList** folder, you should see several profiles starting with**S-1-5** . Each of these profiles corresponds to a user account on your computer. Now you have to identify which profile belongs to your user account.

 To do this, click on each**S-1-5 profile** and look for**ProfileImagePath** in the right pane. Check if anyone of them matches your username.

![Modify Registry to repair user profile](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/modify-registry-to-repair-user-profile.jpg)

 Once you find the correct profile, double-click on the**State** field and change the value from**1 to 0** . Similarly, change the**RefCount** field from**1 to 0** .

 In case the RefCount field is missing in the right pane, you’ll have to create it manually. For this, right-click on the right pane and select**New > DWORD (32-bit) Value** . Name the new value**RefCount** and press**Enter** .

 Then double-click on the newly created RefCount and enter**0** in the Value data field. Click**OK** to save your changes and exit Registry Editor. After this, restart your computer and check whether the settings reset problem is fixed.

### 4\. Create a New User Profile

 If you weren’t able to repair the corrupt profile in the Registry Editor, you may have to [create a new user profile on Windows](https://www.makeuseof.com/windows-11-create-local-user-account/) . Creating a new user profile does not delete the old one, so all your data will remain intact, but you will have to reconfigure your settings. After creating it, log out of your current user account and switch to the newly created one. Check if this fixes the settings reset issue.

### 5\. Uninstall Recent Updates

 Microsoft releases Windows updates periodically to keep your system secure. But sometimes these updates fail to install properly and cause various issues. If you recently installed any programs or updates, uninstall them to check if that fixes the problem.

 You can also try rolling back any drivers that might be causing the issue. To do this, right-click on Start and select**Device Manager** . In the Device Manager window, find the device you want to roll back and right-click on it. Select**Properties** from the context menu and then click on the**Driver** tab.

 Click**Roll Back Driver** and then follow the instructions on-screen to complete the process. After rolling back the driver, restart your computer to apply the changes and check if it solves the settings reset issue.

### 6\. Perform Some Generic Windows Fixes

 There are some general Windows-based fixes you can apply to fix this issue.

[Running your Windows computer in a Clean Boot state](https://www.makeuseof.com/clean-boot-windows-11/) is another way to fix the reset settings problem. Clean Boot helps you identify any third-party applications that might be causing the issue. It stops all non-Microsoft services and programs from running during startup, which helps you pinpoint the cause of the issue.

 If the methods mentioned earlier don't fix the issue,[consider doing a System Restore](https://www.makeuseof.com/windows-11-create-restore-point/) . This will take your computer back to a previous state when it was functioning well.

 Keep in mind that all files and applications installed after the selected restore point will be deleted. To avoid losing important data, create a backup before performing a System Restore.

## Fixing Windows Settings Reset on Reboot

 The Windows settings reset on reboot issue can occur for a number of reasons, including corrupt user profiles, corrupted installed programs or updates, and driver issues. This guide provides several methods to fix this issue. Check out these solutions and see which one work for you.


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
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Samsung Galaxy A23 5G | Dr.fone</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-effortless-online-subtitles-the-leading-free-services-for-2024/"><u>[Updated] Effortless Online Subtitles  The Leading Free Services for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-the-art-of-angle-alteration-mastering-the-rotation-ritual-on-instagram/"><u>In 2024, The Art of Angle Alteration  Mastering the Rotation Ritual on Instagram</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-melodic-marvels-device-spotlight/"><u>[Updated] Melodic Marvels  Device Spotlight</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-size-limit-snag-in-discord-windows-11-edition/"><u>Breaking Free From the Size Limit Snag in Discord (Windows 11 Edition)</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-your-asus-rog-phone-8-pro-lock-screen-password-by-drfone-android/"><u>How to Reset your Asus ROG Phone 8 Pro Lock Screen Password</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-here-is-a-list-of-some-of-the-best-slow-motion-video-editing-software-in-the-market-today-keep-reading-and-tell-us-which-video-editor-/"><u>Updated 2024 Approved Here Is a List of some of the Best Slow Motion Video Editing Software in the Market Today. Keep Reading and Tell Us Which Video Editor You Are Using to Make a Slow Motion Video</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-from-video-to-audio-a-guide-to-youtube-downloading/"><u>Updated From Video to Audio A Guide to YouTube Downloading</u></a></li>
<li><a href="https://win11.techidaily.com/automating-printer-removal-on-win11-devices/"><u>Automating Printer Removal on Win11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-a-look-at-four-game-changing-paint-additions/"><u>Breaking Barriers: A Look at Four Game-Changing Paint Additions</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-pc-wins-best-performance-fixes-ranked/"><u>Boost Your PC: Win's Best Performance Fixes Ranked</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-top-5-tools-for-viewing-insta-stories-unseen/"><u>[New] In 2024, Top 5 Tools for Viewing Insta Stories Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/boost-windows-performance-and-functionality-via-improved-run-toolset/"><u>Boost Windows Performance and Functionality via Improved Run Toolset</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-bug-fixing-windows-scheduler-failures/"><u>Beat the Bug: Fixing Windows Scheduler Failures</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-premier-fb-video-mp4-downloader-no-ads-no-wait/"><u>[Updated] 2024 Approved  Premier FB Video MP4 Downloader - No Ads, No Wait</u></a></li>
<li><a href="https://win11.techidaily.com/batch-operations-brilliance-shutting-down-windows-instances/"><u>Batch Operations Brilliance: Shutting Down Windows Instances</u></a></li>
<li><a href="https://win11.techidaily.com/boost-speed-identifying-your-gpu-on-windows-11-os/"><u>Boost Speed: Identifying Your GPU on Windows 11 OS</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-access-free-melodies-for-video-production-enthusiasts/"><u>Updated In 2024, Access Free Melodies for Video Production Enthusiasts</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-srt-to-sub-transforming-playback-sequences/"><u>In 2024, From SRT to SUB  Transforming Playback Sequences</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-top-7-tips-for-mastering-windows-11-49/"><u>Boosting Productivity: Top 7 Tips for Mastering Windows 11 (49)</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-webm-to-mp3-converter-roundup-top-picks-and-reviews/"><u>New 2024 Approved WebM to MP3 Converter Roundup Top Picks and Reviews</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Samsung Galaxy A54 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/a-comprehensive-guide-to-the-best-makeup-tutorials-on-youtube/"><u>A Comprehensive Guide to the Best Makeup Tutorials on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-to-overcome-steam-sync-error-on-windows/"><u>Best Practices to Overcome Steam Sync Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/blackview-mp60-mini-pc-expandable-storage-but-unremarkable-performance/"><u>Blackview MP60 Mini PC: Expandable Storage but Unremarkable Performance</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-youtube-to-mp4-made-easy-find-your-ideal-converter/"><u>New In 2024, YouTube to MP4 Made Easy Find Your Ideal Converter</u></a></li>
<li><a href="https://win11.techidaily.com/best-fit-choosing-the-perfect-vms-for-your-windows-11-pc/"><u>Best Fit: Choosing the Perfect VMs for Your Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-ide-performance-android-studio-tips/"><u>Accelerating IDE Performance: Android Studio Tips</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-display-with-w11s-auto-hdr-feature/"><u>Boost Your Display with W11's Auto HDR Feature</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-system-speed-implementing-a-smart-enhanced-run-feature/"><u>Boosting System Speed: Implementing a Smart Enhanced Run Feature</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-monitors-brightness-with-top-software-select/"><u>Boosting Windows Monitors' Brightness with Top Software Select</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/plate-pleasures-iconic-international-dishes-unveiled/"><u>Plate Pleasures  Iconic International Dishes Unveiled</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-the-art-of-online-podcast-filming-for-2024/"><u>[New] The Art of Online Podcast Filming for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-classic-gameplay-seamlessly-adding-achievements-using-retroarch/"><u>Boosting Classic Gameplay - Seamlessly Adding Achievements Using Retroarch</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-11-taskbar-efficiency/"><u>Boosting Windows 11 Taskbar Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-ordinary-displays-elevate-your-screen-with-customized-themes-on-win11/"><u>Beyond Ordinary Displays: Elevate Your Screen with Customized Themes on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/begin-your-windows-journey-with-a-voice-guide/"><u>Begin Your Windows Journey with a Voice Guide</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-2024-approved-leap-to-the-top-with-these-8-fast-track-tiktok-steps/"><u>[New] 2024 Approved  Leap to the Top with These 8 Fast-Track TikTok Steps</u></a></li>
<li><a href="https://win11.techidaily.com/becoming-an-admin-in-windows-control-settings/"><u>Becoming an Admin in Windows Control Settings</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-nokia-c12-pro-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Nokia C12 Pro in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-blueprint-to-windows-11-installation/"><u>Beginner's Blueprint to Windows 11 Installation</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-1011-how-to-bypass-pin-locks/"><u>Breaking Down Windows 10/11: How to Bypass PIN Locks</u></a></li>
<li><a href="https://win11.techidaily.com/breakdown-of-windows-error-message-30005s-complexity/"><u>Breakdown of Windows Error Message 30005'S Complexity</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-novelties-the-next-gen-of-windows-11/"><u>Beyond Novelties: The Next Gen of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/beat-windows-11-blues-top-11-pitfalls-and-remedies/"><u>Beat Windows 11 Blues - Top 11 Pitfalls & Remedies</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-top-web-based-audio-visualizers-for-videos/"><u>In 2024, Top Web-Based Audio Visualizers for Videos</u></a></li>
<li><a href="https://fox-direct.techidaily.com/leveraging-the-power-of-windows-11s-auto-hdr-enhancement-for-2024/"><u>Leveraging the Power of Windows 11'S Auto HDR Enhancement for 2024</u></a></li>
</ul></div>
