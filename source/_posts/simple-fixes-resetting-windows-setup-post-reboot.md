---
title: "Simple Fixes: Resetting Windows Setup Post-Reboot"
date: 2024-07-13T10:07:21.038Z
updated: 2024-07-14T10:07:21.038Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Simple Fixes: Resetting Windows Setup Post-Reboot"
excerpt: "This Article Describes Simple Fixes: Resetting Windows Setup Post-Reboot"
keywords: WinSetupReset,RebootFixWin,SimpleSystemReset,QuickWindowsFix,PCRebootTroubleshoot,SetupResetTips,WindowsPostReboot
thumbnail: https://thmb.techidaily.com/499d16f8fa9d73db2896cc95dd1103614d6afb1a8c7743ea30004b41e37daeda.jpg
---

## Simple Fixes: Resetting Windows Setup Post-Reboot

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
<li><a href="https://win11.techidaily.com/command-line-how-to-execute-system-file-checker-sfc/"><u>Command Line: How to Execute System File Checker (SFC)</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-monetizing-makeup-tutorial-content/"><u>In 2024, Monetizing Makeup Tutorial Content</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/vdx-quickcapture-evaluation-complete-reviews/"><u>VDX QuickCapture Evaluation  Complete Reviews</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-file-management-with-collective-windows-11-folder-making/"><u>Revolutionize File Management with Collective Windows 11 Folder Making</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-infinix-smart-8-plus-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Infinix Smart 8 Plus without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-agni-2-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve deleted photos on Agni 2 5G</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentiality-of-runtime-brokers-for-modern-os-functionality/"><u>The Essentiality of Runtime Brokers for Modern OS Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/win11-terminal-reset-procedure-essentials/"><u>Win11 Terminal Reset Procedure Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-alternatives-how-to-access-imessage-on-windows/"><u>Exploring Alternatives: How to Access iMessage on Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-instant-access-to-youtube-on-your-idevice-easy-video-uploads-unveiled/"><u>In 2024, Instant Access to YouTube on Your iDevice  Easy Video Uploads Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/discover-why-your-windows-11-icons-are-diminishing/"><u>Discover Why Your Windows 11 Icons Are Diminishing</u></a></li>
<li><a href="https://win11.techidaily.com/1719293621682-mastering-wwinplusprint-functionality-fixes-for-non-operational-printer-on-pc/"><u>Mastering WWin+Print Functionality: Fixes for Non-Operational Printer on PC.</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-fixes-for-non-operational-voice-command-in-win11/"><u>Unveiling Fixes for Non-Operational Voice Command in Win11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-meme-mayhem-the-ultimate-list-of-crazy-tiktok-challenges/"><u>In 2024, Meme Mayhem  The Ultimate List of Crazy TikTok Challenges</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-correcting-unresponsive-video-files/"><u>Tips for Correcting Unresponsive Video Files</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windowsstore-directory-secrets-for-users/"><u>Unveiling WindowsStore Directory Secrets for Users</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-navigating-and-mastering-discords-text-to-speech-tools/"><u>[Updated] In 2024, Navigating and Mastering Discord's Text-to-Speech Tools</u></a></li>
<li><a href="https://win11.techidaily.com/the-starting-line-in-diablo-basic-play-wisdom/"><u>The Starting Line in Diablo: Basic Play Wisdom</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-take-control-how-to-involve-yourself-in-a-friends-live-on-tiktok/"><u>In 2024, Take Control  How to Involve Yourself in a Friend's Live on TikTok</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-key-approaches-to-elevate-handp-facebook-campaigns/"><u>In 2024, Key Approaches to Elevate H&P Facebook Campaigns</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-image-navigation-using-file-explorer-windows/"><u>Effortless Image Navigation Using File Explorer Windows</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-editors-compendium-top-devices-transforming-media-projects/"><u>[Updated] Editor's Compendium  Top Devices Transforming Media Projects</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-install-fail-in-wins-discord-setup/"><u>Understanding and Remedying Install Fail in Win's Discord Setup</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/what-do-you-prefer-more-mkv-file-format-or-mov-increase-your-knowledge-and-learn-more-about-mkv-format-by-ready-the-detailed-article-below-for-2024/"><u>What Do You Prefer More, MKV File Format or MOV? Increase Your Knowledge and Learn More About MKV Format by Ready the Detailed Article Below for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/review-for-dji-phantom-3-standard/"><u>Review for DJI Phantom 3 Standard</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-blank-display-of-startup-items/"><u>Eradicating Blank Display of Startup Items</u></a></li>
<li><a href="https://win11.techidaily.com/toolbox-tutorial-windows-core-components-management/"><u>Toolbox Tutorial: Windows' Core Components Management</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-on-accessing-windows-11-homescreen/"><u>Expert Tips on Accessing Windows 11 Homescreen</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-smooth-team-chats-on-windows-1110/"><u>Ensuring Smooth Team Chats on Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-rescue-deskanywhere-on-win11/"><u>Essential Tips to Rescue DeskAnywhere on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-microsoft-family-safetys-core-functions/"><u>Decoding Microsoft Family Safety's Core Functions</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/hear-the-difference-explore-the-best-voice-changer-software-for-smartphones-for-2024/"><u>Hear the Difference  Explore the Best Voice Changer Software for Smartphones for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-overcome-common-flaws-in-windows-applications/"><u>Essential Tips to Overcome Common Flaws in Windows Applications</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-recording-techniques-gaming-screen-captures-with-intel/"><u>Advanced Recording Techniques: Gaming Screen Captures with Intel</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-srt-subtitle-translation-tools-and-techniques/"><u>New SRT Subtitle Translation Tools and Techniques</u></a></li>
<li><a href="https://android-location-track.techidaily.com/solutions-to-spy-on-gionee-f3-pro-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>Solutions to Spy on Gionee F3 Pro with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/the-essential-differences-between-youtube-and-dailymention/"><u>The Essential Differences Between YouTube and DailyMention</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-restart-file-explorer-in-windows-10-and-11/"><u>4 Ways to Restart File Explorer in Windows 10 and 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-beyond-tube-the-premier-spots-for-online-video-sharing-for-2024/"><u>[Updated] Beyond Tube  The Premier Spots for Online Video Sharing for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-verizon-apple-iphone-se-2020-by-drfone-ios/"><u>How to Unlock Verizon Apple iPhone SE (2020)</u></a></li>
<li><a href="https://win11.techidaily.com/windowed-wonders-enhance-windows-11-explorer-visibility/"><u>Windowed Wonders: Enhance Windows 11 Explorer Visibility</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-learn-how-to-fix-distorted-audio-using-different-methods/"><u>New In 2024, Learn How To Fix Distorted Audio Using Different Methods</u></a></li>
<li><a href="https://extra-information.techidaily.com/elite-cgi-green-screen-tutorial-for-kinemaster-enthusiasts/"><u>Elite CGI  Green Screen Tutorial for Kinemaster Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-incorporation-of-virtual-gaming-archives-into-playnite-on-pc/"><u>Seamless Incorporation of Virtual Gaming Archives Into Playnite on PC</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-deciding-between-discord-and-skype-for-teams/"><u>[Updated] In 2024, Deciding Between Discord and Skype for Teams</u></a></li>
<li><a href="https://win11.techidaily.com/beginning-your-art-with-ms-paint-windows-11-way/"><u>Beginning Your Art with MS Paint - Windows 11 Way</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-stifled-expression-sudden-copyright-breach/"><u>[Updated] Stifled Expression  Sudden Copyright Breach</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-audio-integration-in-canva-videos/"><u>[New] Mastering Audio Integration in Canva Videos</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-correcting-windows-store-failures-error-x80072f30-guide/"><u>Swiftly Correcting Windows Store Failures: Error X80072F30 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-monitor-settings-in-latest-os-version/"><u>Fine-Tune Monitor Settings in Latest OS Version</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-top-methods-to-reconnect-your-usb-wi-fi-on-pcs/"><u>Bridge the Gap: Top Methods to Reconnect Your USB Wi-Fi on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-disappearances-in-system-navigator/"><u>Eradicating Disappearances in System Navigator</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-voice-typing-failure-in-windows-11-error-code-0x80049dd3/"><u>Fixing Voice Typing Failure in Windows 11 (Error Code: 0X80049DD3)</u></a></li>
<li><a href="https://win11.techidaily.com/does-the-geforce-experience-scan-fail-on-windows-heres-how-to-fix-it/"><u>Does the GeForce Experience Scan Fail on Windows? Here’s How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/stop-recurring-file-explorer-autoload/"><u>Stop Recurring File Explorer Autoload</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-top-pick-for-new-dronists-a-deep-look-at-syma-x5c/"><u>In 2024, The Top Pick for New Dronists – A Deep Look at Syma X5C</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-infinix-hot-40-pro-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Infinix Hot 40 Pro PC | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/remove-sony-xperia-1-v-unlock-screen-by-drfone-android-unlock-android-unlock/"><u>Remove Sony Xperia 1 V unlock screen</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-effective-strategies-for-ppt-screen-recordings/"><u>In 2024, Effective Strategies for PPT Screen Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-technique-how-to-execute-a-clean-boot-on-windows-11/"><u>The Ultimate Technique: How to Execute a Clean Boot on Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-decoding-nitro-unveiling-its-premium-status-in-the-realm-of-discord/"><u>[New] 2024 Approved  Decoding Nitro  Unveiling Its Premium Status in the Realm of Discord</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-10-fastest-growing-youtube-channels-to-inspire-you/"><u>[New] 2024 Approved  10 Fastest Growing YouTube Channels to Inspire You</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-addressing-printer-errors-linked-to-domain-services/"><u>Essential Guide: Addressing Printer Errors Linked to Domain Services</u></a></li>
<li><a href="https://win11.techidaily.com/christmas-edition-enhance-windows-11/"><u>Christmas Edition: Enhance Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-voice-and-music-from-bluetooth-headset/"><u>Troubleshooting Windows: Voice & Music From Bluetooth Headset</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-slashing-dropbox-cpu-load-on-windows-devices/"><u>Solutions for Slashing Dropbox CPU Load on Windows Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-toolwiz-evaluation-the-top-choice-in-mobile-editing/"><u>[New] Toolwiz Evaluation  The Top Choice in Mobile Editing?</u></a></li>
</ul></div>
