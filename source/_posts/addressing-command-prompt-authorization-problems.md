---
title: Addressing Command Prompt Authorization Problems
date: 2024-07-13T11:19:37.894Z
updated: 2024-07-14T11:19:37.894Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Command Prompt Authorization Problems
excerpt: This Article Describes Addressing Command Prompt Authorization Problems
keywords: CP Auth Issue Resolution,Command Prompt Permissions,Access Command Window,Manage Cmd User Rights,Fix Cmd Security Errors,Authorize Cmd Usage,Secure Command Prompt Access
thumbnail: https://thmb.techidaily.com/ab4dfc265d3ec072f529482c24c8089138367c7bb9b170bcd6c98cca628f2064.jpg
---

## Addressing Command Prompt Authorization Problems

 Windows offers a Run as administrator option that allows users to run applications and programs with administrator privileges. You can also use it to troubleshoot computer issues. But what if this feature malfunctions, depriving you of administrator rights?

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.

## What Causes Run as Administrator Not Working?

 Before you start fixing things, you must understand what causes this issue. In general, you may experience Run as administrator not working due to the following reasons:

* Group Policy or User Account Control (UAC) blocks the application or program you’re trying to run.
* The user account associated with your device isn’t an administrator account and therefore doesn’t have the necessary privileges.
* Corrupt system files or registry entries could prevent you from running administrator programs.
* Malware infection on your computer could disrupt the feature.

 Now that you know the potential causes of this issue, let’s look at ways to fix it. ​​​

## 1\. Restart Your Computer

 If you’re having trouble running applications with administrative privileges, [restarting your computer](https://www.makeuseof.com/windows-restart-methods/) will likely solve the issue. This simple solution flushes out any temporary issues and puts the system in its default state.

## 2\. Check Your Account Type

 Not all user accounts are equal. To run programs with administrative privileges, you must have an administrator account. So, [head to the Control Panel](https://www.makeuseof.com/windows-open-control-panel/) and [check your account type](https://www.makeuseof.com/check-windows-account-admin-rights/). If it’s not labeled as an administrator account, switch to a different one or create a new account.

## 3\. Check User Account Control Settings

 The Windows User Account Control (UAC) prevents malicious programs from installing on your computer. This security feature can stop you from using elevated privileges.

 To ensure the issue isn’t related to UAC, head to the Control Panel and check your User Account Settings. If it is set to the highest level, bring it down to the default. Here's how to do it:

1. Press **Win + S** simultaneously to open the search box.
2. Type **Control Panel** in the search box and press Enter. This will open the Control Panel window.
3. View items by **Large icons** in the Control Panel and click on **User Accounts**.
4. In the right pane, click on **Change User Account Control settings**. Doing this will open the User Account Control Settings window.
5. Here you’ll see a slider with four options: **Always notify**, **Default**, **Notify me only when applications try to make changes to my computer**, and **Never notify**.  
![User Account Control Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/user-account-control-settings.jpg)
6. Drag the slider to **Default**, then click **OK**. It will set your UAC to the default level and enable you to run applications with elevated privileges.

 Now, close the window and restart your PC. After that, try running the application with the Run as administrator feature and see if it works.

## 4\. Change Group Policy Settings

 Is the Run as administrator function not working despite trying the suggestions above? It's likely that group policy settings block the feature. To fix this, head to the Local Group Policy Editor and check the settings.

 Here’s what you need to do:

1. Press **Win + R** simultaneously to open the Run dialogue box.
2. Type **gpedit.msc** in the text field and press **Enter**. This will open the Local Group Policy Editor window on your computer screen.
3. From the left navigation panel, go to the following path:  
Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options
4. In the right pane, you'll see a list of different security options. Scroll to the bottom and double-click on the **User Account Control: Run all administrators in Admin Approval Mode** policy.  
![Run all administrators in admin approved](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/run-all-administrators-in-admin-approved.jpg)
5. Doing this will open another window. Here, select the **Disabled** option and click **Apply** \> **OK**.  
![Disable User Account Control in Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-user-account-control-in-group-policy.jpg)
6. Close the Local Group Policy Editor and restart your computer.

 After restarting, try running a program with elevated privileges. It should work now. Don't forget to re-enable the Admin Approval Mode setting once you're finished troubleshooting.

## 5\. Clean up the Context Menu

 When you right-click on a program or file, you often see the Run as administrator option in the context menu. If it's missing, you should look at your context menu entries for clutter.

 This solution involves editing the Windows registry. A single mistake can cause serious problems. So proceed cautiously and [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before applying any changes.

 Follow these steps to clean up the context menu:

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the text field and press Enter. Doing this will open the Windows Registry Editor.
3. If the UAC window pops up, click **Yes** to grant administrative privileges.
4. In the Registry Editor window, navigate to the following path:  
Computer\HKEY_CLASSES_ROOT\*\shellex\ContextMenuHandlers
5. Next, expand the **ContextMenuHandlers** folder and look for any suspicious entries. If you find any, delete them.  
![Clean the Context Menu Items](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clean-the-context-menu-items.jpg)
6. Now exit the Registry Editor and restart your computer.

 Once your computer reboots, you will see the Run as administrator option in the context menu. Try running a program with elevated privileges and see if it works.

## 6\. Try Some Generic Fixes

 Besides the fixes mentioned above, some generic solutions work in any situation. Try these out if you’re still having issues running applications with elevated privileges:

* [Repair Corrupted System Files](https://www.makeuseof.com/windows-built-in-repair-tools/): It restores your computer’s corrupted and missing system files. Use them to repair the root cause of the issue.
* [Perform a Clean Boot](https://www.makeuseof.com/clean-boot-windows-11/): When you start Windows in a clean boot state, the operating system will only run essential services and programs. It identifies any third-party software causing the issue.
* [Create a New Administrator User Account](https://www.makeuseof.com/tag/windows-administrator-account-everything-need-know/): If all else fails, try creating a new administrator user account and logging in. This ascertains if your existing account is corrupted or not.

## Troubleshooting Run as Administrator on Windows

 We hope this guide helped you solve the Run as administrator not working on Windows issue. Despite the prevalence of this problem, it’s relatively easy to fix if you know what to do.

 If none of the troubleshooting steps worked, try running a system scan using an advanced antivirus program. Some malicious programs prevent you from running as an administrator. A complete system scan should find and remove any malicious software on your computer, so you can start using it again.

 That’s where this guide comes into play. So, let’s look at what you can do to fix Run as administrator not working on Windows.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/reducing-windows-installer-cpu-spikes/"><u>Reducing Windows Installer CPU Spikes</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-graphics-restoration-on-latest-windows-oses/"><u>Simplifying Graphics Restoration on Latest Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-user-experience-including-wordpad-shortcuts-to-11s-menu-bar/"><u>Elevating User Experience: Including WordPad Shortcuts to 11'S Menu Bar</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-video-driver-crash-on-win1110/"><u>Addressing Video Driver Crash on Win11/10</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-winservicesexe-a-comprehensive-guide/"><u>Mastering Winservices.exe: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-language-of-windows-updates/"><u>Decoding the Language of Windows Updates</u></a></li>
<li><a href="https://games-able.techidaily.com/the-comfort-of-a-work-desk-over-chairs/"><u>The Comfort of a Work Desk Over Chairs</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-exploring-biggest-fifa-footage-trends-in-graphics/"><u>In 2024, Exploring Biggest FIFA Footage Trends in Graphics</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-hidden-gems-unlocking-full-potential/"><u>Windows 11'S Hidden Gems: Unlocking Full Potential</u></a></li>
<li><a href="https://win11.techidaily.com/5-hacks-for-accessing-windows-repair-options/"><u>5 Hacks for Accessing Windows Repair Options</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-step-by-step-process-to-fuse-several-audio-tracks-into-one-cohesive-piece-for-2024/"><u>Updated Step-by-Step Process to Fuse Several Audio Tracks Into One Cohesive Piece for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-secrets-of-windows-11s-app-collection/"><u>Unveiling the Secrets of Windows 11'S App Collection</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-potential-of-openais-ai-for-voice-to-text-in-windows/"><u>Unlocking the Potential of OpenAI's AI for Voice-to-Text in Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-key-principles-for-high-impact-job-interviews/"><u>In 2024, Key Principles For High-Impact Job Interviews</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-ultimate-guide-to-nubia-z50s-pro-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>The Ultimate Guide to Nubia Z50S Pro Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-editing-profile-paths-in-w11/"><u>Quick Guide to Editing Profile Paths in W11</u></a></li>
<li><a href="https://win11.techidaily.com/usb-wi-fi-anomalies-on-windows-heres-the-solution-guide-you-need/"><u>USB Wi-Fi Anomalies on Windows? Here's the Solution Guide You Need</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-exploring-huawei-p10s-network-performance-and-coverage/"><u>[New] Exploring Huawei P10's Network Performance & Coverage</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/elevating-your-instagram-presence-with-optimized-video-sizes-for-2024/"><u>Elevating Your Instagram Presence with Optimized Video Sizes for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/iphone-6-data-recovery-software-to-recover-lost-ios-data-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>iPhone 6® Data Recovery Software to Recover Lost iOS® Data | Stellar</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-divided-footage-delight-top-cam-discussion/"><u>[Updated] In 2024, Divided Footage Delight  Top Cam Discussion?</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-predominant-rainmeter-malfunctions-in-windows/"><u>Remedying Predominant Rainmeter Malfunctions in Windows</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-create-a-blockbuster-easy-movie-making-for-everyone-for-2024/"><u>Updated Create a Blockbuster Easy Movie Making for Everyone for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/covert-strategies-to-erase-taskbars-language-bar-win11/"><u>Covert Strategies to Erase Taskbar's Language Bar, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-maze-of-windows-11s-error-codes/"><u>Navigating Through the Maze of Windows 11'S Error Codes</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unallocated-vram-on-hogwarts-legacy-platform/"><u>Correcting Unallocated VRAM on Hogwarts Legacy Platform</u></a></li>
<li><a href="https://change-location.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-samsung-galaxy-a25-5g-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-temporary-directory-error-win-error-1152/"><u>Fixing 'Temporary Directory Error' - Win Error 1152</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-unleash-your-creativity-a-comprehensive-guide-to-jaycut-free-video-editing/"><u>2024 Approved Unleash Your Creativity A Comprehensive Guide to Jaycut Free Video Editing</u></a></li>
<li><a href="https://win11.techidaily.com/windows-customizable-spotlight-picture-guide/"><u>Windows Customizable Spotlight Picture Guide</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-best-picks-essential-websites-for-free-text-enhancements-for-2024/"><u>[New] Best Picks  Essential Websites for Free Text Enhancements for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-zte-blade-a73-5g-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your ZTE Blade A73 5G Device</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-for-windows-users-generative-erase-wonders/"><u>Clean Slate for Windows Users: Generative Erase Wonders</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-digital-space-adjusting-windows-11-program-shortcuts/"><u>Mastering Your Digital Space: Adjusting Windows 11 Program Shortcuts</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlock-iphone-7-without-passcode-easily-drfone-by-drfone-ios/"><u>Unlock iPhone 7 Without Passcode Easily | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-demystifying-t-series-income-streams-via-youtube-platforms/"><u>[New] Demystifying T-Series Income Streams via YouTube Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-windows-update-problems-quickly/"><u>Break Free From Windows Update Problems Quickly</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-ispoofer-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Xiaomi Redmi Note 12T Pro? | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-unleash-the-power-of-high-definition-best-video-quality-boosters/"><u>Updated In 2024, Unleash the Power of High-Definition Best Video Quality Boosters</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-sound-off-with-flair-enhancing-high-pitched-vocalization-in-video-content-creation/"><u>Updated Sound Off with Flair Enhancing High-Pitched Vocalization in Video Content Creation</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-google-pixel-8-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-top-5-high-quality-low-speed-video-gear/"><u>[New] Top 5 High-Quality Low-Speed Video Gear</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-maximize-social-status-top-8-apps-for-gaining-more-fb-fans/"><u>2024 Approved  Maximize Social Status  Top 8 Apps for Gaining More FB Fans</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-windows-photography-errors/"><u>Mastering the Art of Fixing Windows Photography Errors</u></a></li>
<li><a href="https://win11.techidaily.com/precision-note-taking-adopting-obsidian-written-canvas/"><u>Precision Note-Taking: Adopting Obsidian' Written Canvas</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-installation-of-ai-tools-in-windows/"><u>Efficient Installation of AI Tools in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-the-lost-link-a-comprehensive-guide-to-reinstating-defective-adapters-in-windows/"><u>Reviving the Lost Link: A Comprehensive Guide to Reinstating Defective Adapters in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/key-to-the-past-windows-11s-historical-files-retrieval/"><u>Key to the Past: Windows 11’S Historical Files Retrieval</u></a></li>
<li><a href="https://win11.techidaily.com/reintroduce-missing-5ghz-connection-in-windows-11-effective-fixes-here/"><u>Reintroduce Missing 5GHz Connection in Windows 11: Effective Fixes Here</u></a></li>
<li><a href="https://win11.techidaily.com/windows-without-bitlocker-here-are-4-steps-to-stay-secure/"><u>Windows Without Bitlocker? Here Are 4 Steps to Stay Secure</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-2024-approved-burn-photos-to-dvd-how-to-burn-photos-to-dvd-with-transitions-and-music/"><u>New 2024 Approved Burn Photos to DVD | How to Burn Photos to DVD with Transitions and Music</u></a></li>
<li><a href="https://win11.techidaily.com/5-simple-ways-to-tell-if-your-pc-needs-restarting/"><u>5 Simple Ways to Tell if Your PC Needs Restarting</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-windows-11-sign-in-complexity/"><u>Simplifying Windows 11 Sign-In Complexity</u></a></li>
<li><a href="https://win11.techidaily.com/severing-non-primary-users-in-the-windows-ecosystem/"><u>Severing Non-Primary Users in the Windows Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-pin-update-guide/"><u>Mastering Windows PIN Update Guide</u></a></li>
<li><a href="https://win11.techidaily.com/devhome-the-comprehensive-resource-for-w11-enthusiasts/"><u>DevHome: The Comprehensive Resource for W11 Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/establishing-enduring-trash-settings-in-the-windows-environment/"><u>Establishing Enduring Trash Settings in the Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-mkv-conversion-to-mp4-in-windows-systems/"><u>Simplifying MKV Conversion to MP4 in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-inaccessible-printmanagement-service-in-os/"><u>Dealing with Inaccessible 'PrintManagement' Service in OS</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-technique-to-effortlessly-install-win11-with-workstation-17/"><u>Unveiling the Technique to Effortlessly Install Win11 with Workstation 17</u></a></li>
</ul></div>
