---
title: "Expert Advice: Regaining Original Windows Configs"
date: 2024-07-13T10:02:33.162Z
updated: 2024-07-14T10:02:33.162Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Expert Advice: Regaining Original Windows Configs"
excerpt: "This Article Describes Expert Advice: Regaining Original Windows Configs"
keywords: Windows Restore Tips,Revert Settings Windows,Default Windows Configures,Windows Initial Setup Guide,WinXP Recovery Steps,Original Windows XP Hacks,Regain Windows Defaults Quickly
thumbnail: https://thmb.techidaily.com/f07aba0aa676c9e76b44feb60efd0a45624266536fcc9c86e32c630adb095a41.jpg
---

## Expert Advice: Regaining Original Windows Configs

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
<li><a href="https://win11.techidaily.com/regain-lost-dxgidll-with-effective-win11-tactics/"><u>Regain Lost Dxgi.dll with Effective Win11 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-admin-oversight-of-chromium-and-microsoft-edge-browsing-experience/"><u>Revamping Admin-Oversight of Chromium & Microsoft Edge Browsing Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-no-sound-during-system-tests/"><u>Remedy for No Sound During System Tests</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-huawei-nova-y71-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Huawei Nova Y71? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-make-the-most-of-your-apple-iphone-8-lock-screen-with-notifications-by-drfone-ios/"><u>How to Make the Most of Your Apple iPhone 8 Lock Screen with Notifications?</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-keyboard-method-to-resize-programs/"><u>Navigating Windows 11'S Keyboard Method to Resize Programs</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-freezing-and-black-steam-in-winos/"><u>Troubleshooting Freezing & Black Steam in WinOS</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/navigating-the-leading-live-church-broadcast-services/"><u>Navigating the Leading Live Church Broadcast Services</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-how-to-install-and-use-snapchat-on-your-mac/"><u>[Updated] How to Install and Use Snapchat on Your Mac?</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-disconnected-remote-resources-in-windows/"><u>Strategies to Address Disconnected Remote Resources in Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-optimize-iphoneandroid-video-quality-in-online-platforms/"><u>[New] In 2024, Optimize iPhone/Android Video Quality in Online Platforms</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-crafting-perfect-slack-filmo-meeting-experiences/"><u>In 2024, Crafting Perfect Slack-Filmo Meeting Experiences</u></a></li>
<li><a href="https://win11.techidaily.com/streaming-windows-network-shares-from-smartphones/"><u>Streaming Windows Network Shares From Smartphones</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-chorus-chronicles-storytelling-with-musical-themes/"><u>[New] Chorus Chronicles  Storytelling with Musical Themes</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-find-lost-iphone-7-backup-files-on-windows-pc-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to find lost iPhone 7 Backup files on Windows PC? | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/linux-perfection-bypassing-wsl/"><u>Linux Perfection: Bypassing WSL</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-game-changers-gear-essentials-every-business-needs-to-stay-ahead-of-the-curve/"><u>2024 Approved  Game Changers Gear  Essentials Every Business Needs to Stay Ahead of the Curve</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-spotting-sham-followers-on-business-pages/"><u>[Updated] Spotting Sham Followers on Business Pages</u></a></li>
<li><a href="https://win11.techidaily.com/review-of-surface-laptop-go-3s-new-cpu-unchanged-shortcomings/"><u>Review of Surface Laptop Go 3'S New CPU - Unchanged Shortcomings</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-camguard-elite-mesh-patch/"><u>[New] In 2024, CamGuard Elite Mesh Patch</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/simplified-playlist-crafting-for-youtube-fans-on-desktop-and-mobile-devices/"><u>Simplified Playlist Crafting for YouTube Fans on Desktop & Mobile Devices</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-complete-examination-screenflow-full-features-for-mac/"><u>[Updated] 2024 Approved  Complete Examination  ScreenFlow Full Features for Mac</u></a></li>
<li><a href="https://win11.techidaily.com/top-notch-windows-11-skins-no-one-knows/"><u>Top-Notch Windows 11 Skins No One Knows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-windows-11-top-20-optimizations-guide/"><u>Mastering Your Windows 11: Top 20 Optimizations Guide</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-unlocking-the-potentials-of-streamlabs-obs-for-2024/"><u>[New] Unlocking the Potentials of Streamlabs OBS for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-infinix-gt-10-pro-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Infinix GT 10 Pro Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-quick-tips-to-produce-quality-thumbnails-fast/"><u>[Updated] Quick Tips to Produce Quality Thumbnails Fast</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-new-row-insertion-issues-in-excel-windows/"><u>Strategies for Fixing New Row Insertion Issues in Excel Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-to-silent-tab-disabling-in-windows-11/"><u>Navigating to Silent Tab Disabling in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-into-your-windows-11-screen/"><u>Breathing Life Into Your Windows 11 Screen</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-accessing-cloud-drives-from-windows-drive-letters/"><u>Effortlessly Accessing Cloud Drives: From Windows Drive Letters</u></a></li>
<li><a href="https://win11.techidaily.com/regulating-pcs-to-prevent-windows-11-overheats/"><u>Regulating PCs to Prevent Windows 11 Overheats</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-revolutionizing-podcast-titles-leading-10-ai-generators/"><u>[Updated] Revolutionizing Podcast Titles  Leading 10 AI Generators</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-tech-gear-review-vr-treadmills-showdown/"><u>2024 Approved  Tech Gear Review  VR Treadmills Showdown</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-a-deeper-dive-into-ios-visual-data-repository/"><u>[New] A Deeper Dive Into IO's Visual Data Repository</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-potential-a-complete-walkthrough-of-wpm-on-windows-os/"><u>Unlock Full Potential: A Complete Walkthrough of WPM on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/is-voice-access-not-working-on-windows-11-heres-how-to-fix-it/"><u>Is Voice Access Not Working on Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-samsung-galaxy-m34-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Samsung Galaxy M34 by Name | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-guide-to-creating-a-unique-terminal-theme/"><u>The Guide to Creating a Unique Terminal Theme</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-create-slide-masking-effect-introfilmora/"><u>New Create Slide Masking Effect Intro【Filmora】</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-mouse-click-rate-with-just-a-few-tweaks/"><u>Skyrocket Mouse Click Rate with Just a Few Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-approach-to-sound-channel-division/"><u>Understanding Windows’ Approach to Sound Channel Division</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-hidden-icons-in-windows-11/"><u>Guiding Through Hidden Icons in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-program-format-pe/"><u>Demystifying Windows Program Format (PE)</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-quick-fixes-for-five-common-defender-disruptions/"><u>Troubleshooting Guide: Quick Fixes For Five Common Defender Disruptions</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-professional-framing-adding-bb-and-letterbox-overlays-to-fb-videos/"><u>[Updated] In 2024, Professional Framing  Adding BB and Letterbox Overlays to FB Videos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-rapid-ascension-harness-likes-and-videos-for-insta-success/"><u>2024 Approved  Rapid Ascension  Harness Likes & Videos for Insta Success</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-an-inclusive-easeus-recexperts-review/"><u>In 2024, An Inclusive EaseUS RecExperts Review</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-convert-your-streaming-top-free-video-to-audio-tools/"><u>[Updated] 2024 Approved  Convert Your Streaming  Top Free Video to Audio Tools</u></a></li>
<li><a href="https://win11.techidaily.com/windows-np-settings-a-simple-fix-guide/"><u>Windows NP Settings: A Simple Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-xbox-game-pass-x8007e9-error-in-windows/"><u>Solutions for Xbox Game Pass X8007E9 Error in Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/1716069219253-new-2024-approved-the-ultimate-cut-for-quality-offline-ipad-gaming/"><u>[New] 2024 Approved  The Ultimate Cut for Quality Offline iPad Gaming!</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-users-from-adjusting-windows-time-and-date/"><u>Stopping Users From Adjusting Windows Time and Date</u></a></li>
<li><a href="https://win11.techidaily.com/smoothing-out-irregularities-a-guide-to-correction-of-windows-charmap-issues/"><u>Smoothing Out Irregularities: A Guide to Correction of Windows CharMap Issues</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-rectifying-webcam-error-code-a00f4289-on-windows-11/"><u>Deciphering and Rectifying Webcam Error Code A00F4289 on Windows 11</u></a></li>
</ul></div>
