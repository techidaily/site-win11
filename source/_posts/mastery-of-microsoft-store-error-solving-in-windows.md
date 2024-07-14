---
title: Mastery of Microsoft Store Error Solving in Windows
date: 2024-07-13T10:38:23.094Z
updated: 2024-07-14T10:38:23.094Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastery of Microsoft Store Error Solving in Windows
excerpt: This Article Describes Mastery of Microsoft Store Error Solving in Windows
keywords: MSStoreErrorSolverWin,WinMSStoreTroubleshoot,WindowsStoreErrorFix,FixWindowsMSStoreError,ResolveMSStoreInWin,MasteringMSStroryWin,ErrorSolvingWinMSStor
thumbnail: https://thmb.techidaily.com/1f2f4c22410ca8169af4ae6d02cdc0eba714608bc6ab4df470b116ebdad1c1fb.jpg
---

## Mastery of Microsoft Store Error Solving in Windows

 Error 0x80073D26 is an issue that users have widely reported occurring when trying to install or play Xbox Game Pass titles via Microsoft Store. When this issue arises, users get redirected to install the Gaming Services app in the Microsoft Store. Users then see the “Something unexpected happened” error 0x80073D26 message when they try to install (or update) Gaming Services.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows

## 1\. Run the Windows Store App Troubleshooting Tool

 This isn’t the most likely solution for error 0x80073D26, but it’s worth trying since Microsoft Store is a UWP app. Running the Windows Store App troubleshooter might detect a Microsoft Store issue and provide a fix. These are the steps for running the Windows Store App troubleshooting utility:

1. Open Settings and click **System** to view that tab.
2. Next, select **Troubleshoot** to reach three troubleshooting navigation options.
3. Bring up the list of troubleshooting tools by clicking **Other trouble-shooters**.
4. Then click **Run** to launch the Windows Store Apps troubleshooting tool.  
![The Run button for the Windows App Store troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-app-store-troubleshooter.jpg)
5. Apply all troubleshooting suggestions provided within Windows Store Apps window.  
![The Windows Store Apps window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-store-app-troubleshooter.jpg)

 You can run the same troubleshooter tool in Windows 10, but the steps for accessing it are a bit different. Click **Update & Security** \> **Troubleshoot** \> **Additional troubleshooters** in Windows 10’s Settings app. Then select **Windows Store Apps** \> **Run the troubleshooter** to get troubleshooting.

## 2\. Repair and Reset the Microsoft Store App

 Accumulated and corrupted Microsoft Store cache data is a potential cause for error 0x80073D26\. Resetting the Microsoft Store app via Settings or the Command Prompt will clear the app’s data. Try applying both methods in this guide to resetting Microsoft Store. Also, select the **Repair** option for the Microsoft Store just above its **Reset** button in Settings to see if that resolves the issue.

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

## 3\. Edit the Registry

 One of the most widely confirmed fixes for error 0x80073D26 is to enter the Registry and delete the GamingServices and GamingServicesNet Registry keys. Although confirmed to work, we still recommend users [back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before deleting keys. Then follow these steps for editing the registry:

1. Open the Windows Run accessory by right-clicking **Start** on your taskbar and selecting the **Run** option.
2. Input the **regedit** Run command and click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Copy and paste this key location in the registry address bar:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
4. Right-click the **GamingServices** subkey within the Services key to select **Delete** \> **Yes**.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-option-1.jpg)
5. Click the **GamingServicesNet** key with the mouse’s right button and select the **Delete** \> **Yes** options.
6. Exit Registry Editor and restart your PC.

## 5\. Reinstall the Microsoft Gaming Service

 One of Microsoft’s official resolutions for error 0x80073D26 is to reinstall Gaming Service. This potential solution involves entering three PowerShell commands that will remove the Gaming Service app along with associated registry entries. These are the steps for applying this potential fix:

1. Activate Windows Search by pressing **Win + S**.
2. Enter **PowerShell** inside the file search tool.
3. Open PowerShell with admin rights by right-clicking that app in the search results and selecting **Run as Administrator**.
4. Next, remove the Gaming Service app by entering this command and hitting **Enter**:  
`Get-AppxPackage *gaming services* -allusers | remove-appxpackage -allusers`  
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
5. Then input these separate commands, pressing **Return** after each:  
`Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServices" -recurse  

Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServicesNet" -recurse` 
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
6. Close out of PowerShell to restart Windows.
7. Reopen Powershell and execute the following command:  
`start ms-windows-store://pdp/?productid=9MWPM2CQNLHN`
8. Then click the **Get** button for installing Gaming Service.

## 5\. Perform Some Generic Windows Fixes for Errors

 Windows is by no means impervious to errors. Fortunately, there are some tricks you can apply to almost every error, including this one.

### Repair System Files

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

 To begin with, try repairing system files to see if there are any issues. You can do that by executing a System File Checker scan within the Command Prompt. That tool will check for and repair corrupted system files detected when you run its command. To apply this potential fix, follow the instructions in our [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide.

### Set Windows to Clean Boot

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-tab.jpg)

 Another possibility is that a software conflict might be causing error 0x80073D26 to occur on your PC. Setting Windows to clean boot by disabling third-party startup items will likely eliminate such a potential cause. That will stop third-party apps and services that could be conflicting with the Microsoft Store from automatically starting.

 To apply this fix, check out this guide about [clean-booting Windows 10 or 11](https://www.makeuseof.com/clean-boot-windows-11/). Disable startup programs in Task Manager and services in MS Config as covered within that guide; then restart your PC and try installing Microsoft Store games again to see if the issue persists.

### Reinstall the Microsoft Store

![The remove Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-microsoft-store-command.jpg)

 Some users might need to reinstall the Microsoft Store to fix error 0x80073D26\. Such a resolution might be necessary for fixing wider issues with the Microsoft Store app other potential solutions don’t address.

 There isn’t a standard uninstall option available for Microsoft Store. So, you’ll have to reinstall that app with two PowerShell commands. Our guide about [how to reinstall the Microsoft Store](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) tells you how to apply this potential fix.

### Perform an In-Place Windows Upgrade

 Some Microsoft Store users have also fixed error 0x80073D26 by performing an in-place Windows upgrade. An in-place upgrade is a method for installing the latest Windows 11/10 version without losing any installed software or user files.

 This will likely fix the 0x80073D26 error because it will refresh all of the system's registry entries, the system files, and also upgrade Windows to the latest version.

 Performing a Windows 11 in-place upgrade is relatively straightforward. All you need to do is download the latest Windows 11 ISO file, open it up, and launch the setup wizard from there. Our article about [performing an in-place upgrade of Windows 11](https://www.makeuseof.com/in-place-upgrade-windows-11/) includes full guidelines for how to do this.

![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-11-setup-window2.jpg)

 You can also perform a Windows 10 in-place upgrade much the same. One difference is that you’ll need to download a Windows 10 Setup file by clicking **Download tool** on the [Microsoft Windows 10 download webpage](https://www.microsoft.com/en-gb/software-download/windows10). Then select **Upgrade this PC** now in the Windows 10 Setup wizard to install the latest version of the OS.

## Enjoy the Best Xbox Game Pass Games Available on the Microsoft Store

 It’s very likely the potential resolutions covered in this guide will fix error 0x80073D26, as some of them are widely confirmed to work. Hopefully, you can get this error fixed and get back into gaming.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-raw-footage-to-professionals-finest-a-gopro-journey/"><u>In 2024, From Raw Footage to Professionals' Finest  A Gopro Journey</u></a></li>
<li><a href="https://win11.techidaily.com/pioneering-techniques-for-effective-qr-scanning-on-pcs/"><u>Pioneering Techniques for Effective QR Scanning on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-file-examination-in-win1011-with-new-tool-integration/"><u>Elevate File Examination in Win10/11 with New Tool Integration</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-absent-bluetooth-listings-on-pc-device-manager/"><u>Fixing Absent Bluetooth Listings on PC Device Manager</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-understanding-the-social-tv-landscape-rokus-role/"><u>[Updated] 2024 Approved  Understanding the Social TV Landscape  Roku's Role</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-the-mechanics-guaranteeing-a-glitch-free-gaming-experience/"><u>Mastery of the Mechanics: Guaranteeing a Glitch-Free Gaming Experience</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-linuxs-power-to-boost-android-on-windows/"><u>Leveraging Linux's Power to Boost Android on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-update-issue-0xca00a009/"><u>Overcoming Windows Update Issue #0xCA00A009</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-samsung-galaxy-s24-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any Samsung Galaxy S24 Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-single-board-compatible-with-windows/"><u>Exclusive Single-Board Compatible with Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fresh-start-on-walls-top-3-techniques/"><u>Fresh Start on Walls: Top 3 Techniques</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-oppo-find-x7-photos-an-easy-method-explained-by-fonelab-android-recover-photos/"><u>How to Restore Deleted Oppo Find X7 Photos  An Easy Method Explained.</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-selections-of-innovative-vtuber-sound-tools/"><u>2024 Approved  Expert Selections of Innovative Vtuber Sound Tools</u></a></li>
<li><a href="https://win11.techidaily.com/deciphered-doorkeeper-no-swift-shift-to-new-solution/"><u>Deciphered Doorkeeper? No Swift Shift to New Solution</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-exploration-of-neglected-windows-11-capabilities/"><u>In-Depth Exploration of Neglected Windows 11 Capabilities</u></a></li>
<li><a href="https://screen-capture.techidaily.com/expert-review-dynamic-action-recording-tools-for-2024/"><u>Expert Review  Dynamic Action Recording Tools for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-eyeball-enticer-titan-master/"><u>In 2024, Eyeball Enticer Titan Master</u></a></li>
<li><a href="https://win11.techidaily.com/modify-mouse-indicator-for-personalized-windows-experience/"><u>Modify Mouse Indicator for Personalized Windows Experience</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-display-driver-found-on-windows-11/"><u>Overcoming No Display Driver Found on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-upgrade-error-0xc004f050/"><u>How to Fix the Windows Upgrade Error 0Xc004f050</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-streamlining-your-discord-experience-bulk-deletion-made-simple/"><u>[Updated] In 2024, Streamlining Your Discord Experience  Bulk Deletion Made Simple</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-fine-tune-youtube-video-pacing-desktopmobile-for-2024/"><u>[New] Fine-Tune YouTube Video Pacing - Desktop/Mobile for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-amplify-your-content-mastering-trending-tiktok-hashtags/"><u>[Updated] Amplify Your Content  Mastering Trending TikTok HashTags</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-samsung-galaxy-m54-5g-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Samsung Galaxy M54 5G Pattern Lock Screen</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-strategies-for-background-blur-perfection-using-windows-11-photos-app/"><u>In-Depth Strategies for Background Blur Perfection Using Windows 11 Photos App</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-file-write-error-in-windows-11-os/"><u>Resolving File Write Error in Windows 11 OS</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-complete-guide-to-change-video-resolution-in-filmora/"><u>Updated Complete Guide to Change Video Resolution in Filmora</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-spot-and-defeat-keygen-malware-in-your-windows-os-environment/"><u>How to Spot & Defeat Keygen Malware in Your Windows OS Environment</u></a></li>
<li><a href="https://win11.techidaily.com/neutralizing-windows-update-triggers/"><u>Neutralizing Windows Update Triggers</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-external-hard-drive-access-in-windows/"><u>Controlling External Hard Drive Access in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correcting-discord-setup-mistakes-in-win-11/"><u>Guide to Correcting Discord Setup Mistakes in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/securing-your-pc-transferring-preferences-from-one-to-another/"><u>Securing Your PC: Transferring Preferences From One to Another</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-inspecting-and-cleaning-windows-logs/"><u>Mastering the Art of Inspecting & Cleaning Windows Logs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-effortless-mp4-conversion-from-facebook-hd-content-all-for-free/"><u>2024 Approved  Effortless MP4 Conversion From Facebook HD Content – All For Free</u></a></li>
<li><a href="https://techidaily.com/top-iphone-11-message-recovery-software-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Top iPhone 11 Message Recovery Software | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolving-common-fall-guys-connectivity-issues-windows/"><u>Quick Guide to Resolving Common Fall Guys Connectivity Issues (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-functionality-of-law-filters-for-windows-users/"><u>Decoding the Functionality of LAW Filters for Windows Users</u></a></li>
<li><a href="https://extra-information.techidaily.com/become-a-master-of-virtual-persona-design-metaverse-edition/"><u>Become a Master of Virtual Persona Design - Metaverse Edition</u></a></li>
<li><a href="https://win11.techidaily.com/guide-on-stopping-discords-autostart-and-updating-habits/"><u>Guide on Stopping Discord's Autostart & Updating Habits</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-transform-your-videos-a-beginners-guide-to-editing-with-windows-movie-maker/"><u>In 2024, Transform Your Videos A Beginners Guide to Editing with Windows Movie Maker</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-blue-screen-wins-unhandled-exception/"><u>How to Address Blue Screen: Win's Unhandled Exception</u></a></li>
<li><a href="https://win11.techidaily.com/first-steps-in-windows-11-here-are-top-8-blunders-to-evade/"><u>First Steps in Windows 11? Here Are Top 8 Blunders to Evade</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/leading-the-pack-2023s-8-facebook-movie-downloads/"><u>Leading the Pack  2023'S #8 Facebook Movie Downloads</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-from-beats-to-pages-the-ultimate-guide-to-online-mp3-conversion-to-text/"><u>New 2024 Approved From Beats to Pages The Ultimate Guide to Online MP3 Conversion to Text</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-economics-of-youtube-marketing-strategies/"><u>In 2024, The Economics of YouTube Marketing Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-tech-connection-winpc-galaxy-with-flow-app/"><u>Empowering Tech Connection - WinPC, Galaxy with Flow App</u></a></li>
<li><a href="https://article-posts.techidaily.com/elite-15-luts-transforming-gopro-action-footage-for-2024/"><u>Elite 15 LUTs Transforming GoPro Action Footage for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-integrate-streamlabs-with-ease-into-your-macs-obs/"><u>[New] Integrate Streamlabs with Ease Into Your Mac’s OBS</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-effortlessly-connect-camera-roll-to-snapchat-sharing-platforms-for-2024/"><u>[New] Effortlessly Connect Camera Roll to Snapchat Sharing Platforms for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-8-ways-to-live-stream-pre-recorded-video/"><u>Updated 2024 Approved 8 Ways To Live Stream Pre-Recorded Video</u></a></li>
<li><a href="https://win11.techidaily.com/must-remember-tips-for-clean-installation-of-windows/"><u>Must-Remember Tips for Clean Installation of Windows</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-workday-the-top-5-apps-to-skyrocket-windows-efficiency/"><u>Optimize Your Workday: The Top 5 Apps to Skyrocket Windows Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-fixing-error-0x80073cf3-on-marketplace/"><u>Deciphering and Fixing Error 0X80073CF3 on Marketplace</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-find-your-next-vector-the-best-10-pics-sites-for-2024/"><u>[New] Find Your Next Vector  The Best 10 Pics Sites for 2024</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-motorola-g24-power-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Motorola G24 Power Hard Reset | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-adept-principles-for-youtube-participants-for-2024/"><u>[New] Adept Principles for YouTube Participants for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-improve-auditory-experience-through-crossfade-adjustments/"><u>In 2024, Improve Auditory Experience Through Crossfade Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/getting-started-the-windows-11-guide-to-altering-fax-cover-pages/"><u>Getting Started: The Windows 11 Guide to Altering Fax Cover Pages</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-fix-slow-playback-issues-in-davinci-resolve-finding-the-best-solutions/"><u>How To Fix Slow Playback Issues in DaVinci Resolve Finding the Best Solutions</u></a></li>
</ul></div>
