---
title: Ignoring the Windows LSA Protection Deactivation
date: 2024-07-13T09:59:32.942Z
updated: 2024-07-14T09:59:32.942Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ignoring the Windows LSA Protection Deactivation
excerpt: This Article Describes Ignoring the Windows LSA Protection Deactivation
keywords: Windows Security Compliance,LSA Deactivation Risks,SysAdmin Caution Advised,Microsoft Windows Hardening,LSA Security Breach,Operating System Safeguards,Mitigate OS Vulnerabilities
thumbnail: https://thmb.techidaily.com/0838ac8f5f2d8f067138531cc9f4dfd905cfa9adb1733f1b9948bd185f0bb490.jpg
---

## Ignoring the Windows LSA Protection Deactivation

 Have you seen a warning saying, "Local Security Authority protection is off. Your device may be vulnerable" in the Core isolation settings of the Windows Security app? If so, the Local Security Authority (LSA) protection feature, which protects your login credentials, is turned off on your system.

 The feature could be off for numerous reasons; a problematic Windows update, the presence of malware in your system, interference from a recently installed third-party app, problems with the Windows Security app, improper Registry Editor settings, and more. If you want to fix this issue and activate the feature again, apply the following solutions.

## 1\. Perform Some Preliminary Checks

 First off, perform the following basic fixes to ensure temporary issues haven't caused the feature to turn off:

* Close all apps currently running on your device. Then, restart your device.
* Try to manually enable the feature in Core isolation settings. For that, open the Windows Security app, navigate to the **Device Security** tab, and turn on the toggle under **Local Security Authority Protection**.
* If the feature is already enabled in the security settings, but the warning message still appears, disable it once, re-enable it again, and restart your device.
* Temporarily turn off third-party security software you use to ensure its interference does not turn off the feature.

 If none of the above fixes resolves the issue, begin applying the remaining fixes.

## 2\. Ensure the Warning Isn't Just a False Flag

 Some users who encountered the error under discussion reported that the warning was simply a false flag triggered due to a Windows update issue. In other words, the warning appeared even though the feature was already enabled and functioning well.

 Therefore, you should ensure that the warning you have received isn't just a false alarm and that the feature is turned off. Follow these steps to check that:

1. Open the **Event Viewer** app by searching for **"Event Viewer"** in Windows Search.
2. On the left-hand sidebar, navigate to **Applications and Services Logs > Microsoft > Windows > LSA**.
3. Find the event with **ID 5004** associated with LSA protection and ensure it is enabled and operational.

 If there is no event with this ID in the Event Viewer app, the feature could be disabled. So, apply the remaining fixes and see if they fix the issue.

## 3\. Install Any Pending Windows Updates

![A Windows laptop installing updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Install-Windows-11-Updates.jpg)

 Several users on a [Microsoft Community forum thread](https://answers.microsoft.com/en-us/windows/forum/all/the-local-security-authority-protection-is-off/6bd9dad0-9d25-4b6e-b101-eeacac9d3b3a) reported that the bug that turns off the Local Security Authority protection feature originated with a Windows update released in March 2023, specifically, the Update for Microsoft Defender antivirus antimalware platform KB5007651\.

 Fortunately, Microsoft has listened to the concerns of the users and fixed this issue in new updates. However, you will have to update your operating system to the latest version to fix this. Therefore, refer to our guide on [how to update Windows manually](https://www.makeuseof.com/update-windows-manually/), install the pending updates and check if that fixes the problem.

 In case that doesn't resolve the issue, uninstall the KB5007651 update. Refer to our guide on [how to uninstall any Windows update](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) if you don't know how. If that doesn't resolve the issue, as some users continue to encounter it despite updating their operating system, apply the remaining fixes.

## 4\. Uninstall Recently Installed Third-Party Applications

 Have you recently installed a third-party app, especially from a shady source, and subsequently experienced the error mentioned above in the Windows Security app? If that is the case, the app could be malicious, designed to steal your login credentials, which could be why it has turned off this security feature.

 If you remember the app you installed recently, follow our guide on [how to uninstall any software on Windows](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/) to remove it. If you don't remember, open the Settings app and navigate to **Apps > Installed apps**. Here, sort the apps according to the **Date installed**, find the latest app, and uninstall it.

![Sort Installed Apps by Date Installed in the Windows Setiings app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sort-installed-apps-by-date-installed-in-the-windows-setiings-app.jpg)

## 5\. Repair and Reset the Windows Security Application

 The problematic Windows Security app can also turn off this security feature. If you've tweaked the app's settings recently, you're also more likely to get the "Local Security Authority protection is off" error. Repairing and resetting the Windows Security app is the best way to rule out these possibilities.

![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)

 Resetting the app will restore its original default settings, eliminating the possibility that misconfigured settings are causing the problem. Repairing the app will fix any underlying issue with its functionality. Refer to our guide on [how to reset a Windows app](https://www.makeuseof.com/windows-reset-app/) (or [repair it)](https://www.makeuseof.com/windows-repair-apps-programs/) if this is your first time doing so.

## 6\. Ensure Malware Isn't Responsible for Deactivating the Feature

 Malware designed to find a loophole in your device's security can also turn off this feature to access your credentials and hand them over to threat actors. Considering how serious this threat can be, ensuring your device is virus-free is essential. Running the [Windows Defender malware scan](https://www.makeuseof.com/how-to-remove-malware-using-microsoft-defenders-offline-scan/) is probably the best way to find any threats.

 If any threats are detected, take the recommended actions to remove them. Once this is done, return to Core isolation settings and check if the warning has disappeared.

## 7\. Use Other Methods to Enable Local Security Authority Protection

 If none of the above fixes and checks have resolved the issue, the toggle to enable this feature is grayed out in Windows Security, and enabling the feature from the Windows Security app does not eradicate the warning, use the alternative ways to enable Local Security Authority protection.

 There are mainly two alternative ways to enable this feature on Windows: using the Local Group Policy Editor, a Windows utility for managing group policy settings, and using the Registry Editor, which lets us access and edit the Windows operating system configuration settings.

 Our guide on [how to enable Local Security Authority protection](https://www.makeuseof.com/windows-11-enable-local-security-authority-protection/) explains the process to enable this security feature using each of these methods.

 Misconfiguring the Windows Registry Editor settings can completely ruin your system's performance and even make it unbootable. So, don't forget to [create a Windows Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes there.

## Enable LSA to Foolproof Your Security

 Buggy Windows updates often give rise to unforeseen problems now and then. The "Local Security Authority protection is off. Your device may be vulnerable" error can also result from a faulty Windows update. Hopefully, you can now take the necessary steps to ensure the warning isn't a false alarm and resolve the problem using the recommended fixes.

 If the issue persists, use the abovementioned alternative methods to enable the LSA feature forcefully.

 The feature could be off for numerous reasons; a problematic Windows update, the presence of malware in your system, interference from a recently installed third-party app, problems with the Windows Security app, improper Registry Editor settings, and more. If you want to fix this issue and activate the feature again, apply the following solutions.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/reviving-off-view-apps-in-win-1011-the-ultimate-guide-to-6-recovery-methods/"><u>Reviving Off-View Apps in Win 10/11: The Ultimate Guide to 6 Recovery Methods</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-elevating-your-android-experience-through-recording/"><u>2024 Approved  Elevating Your Android Experience Through Recording</u></a></li>
<li><a href="https://win11.techidaily.com/1719347376759-efficient-methods-to-tackle-programming-problems-on-vistawindows-7/"><u>Efficient Methods to Tackle Programming Problems on Vista/Windows 7.</u></a></li>
<li><a href="https://win11.techidaily.com/in-a-nutshell-how-to-spot-your-pcs-ram-quickly/"><u>In a Nutshell: How to Spot Your PC's RAM Quickly</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/avchd-on-galaxy-z-flip-5-convert-mts-for-galaxy-z-flip-5-by-aiseesoft-video-converter-play-mts-on-android/"><u>AVCHD on Galaxy Z Flip 5-convert MTS for Galaxy Z Flip 5</u></a></li>
<li><a href="https://win11.techidaily.com/1719343225911-epic-launcher-uninstallation-hurdles-bust-them-on-windows-11/"><u>Epic Launcher Uninstallation Hurdles, Bust Them On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-visual-disk-space-insights-into-windows-cli/"><u>Incorporating Visual Disk Space Insights Into Windows CLI</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-effective-strategies-for-removing-youtube-media-from-computers/"><u>[New] In 2024, Effective Strategies for Removing YouTube Media From Computers</u></a></li>
<li><a href="https://win11.techidaily.com/quick-pc-revival-unearthing-windows-best-eight-methods/"><u>Quick PC Revival: Unearthing Windows' Best Eight Methods</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-professional-advice-how-to-attach-srt-to-video-media-2024/"><u>[New] Professional Advice  How to Attach SRT to Video Media 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-top-10-anime-movies-of-all-time/"><u>New Top 10 Anime Movies of All Time</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-tackle-black-screens-on-windows-11/"><u>Quick-Fix Guide to Tackle Black Screens on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/adapting-windows-lockscreen-for-user-preferences/"><u>Adapting Windows Lockscreen for User Preferences</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-honor-100-pro-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/stop-windows-11-from-self-restarting-frequently/"><u>Stop Windows 11 From Self-Restarting Frequently</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-upgrading-minecraft-stability-via-ram-adjustment-for-2024/"><u>[Updated] Upgrading Minecraft Stability via RAM Adjustment for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-screen-snapshotting-4-key-strategies-for-windows-users/"><u>Mastering the Art of Screen Snapshotting: 4 Key Strategies for Windows Users.</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-efficiency-in-the-digital-age-with-these-best-windows-tools/"><u>Boosting Efficiency in the Digital Age with These Best Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/removing-personal-data-from-the-windows-login-area/"><u>Removing Personal Data From the Windows Login Area</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-customize-windows-10-and-11-with-winbubble/"><u>8 Ways to Customize Windows 10 and 11 With WinBubble</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-video-editing-software-for-pc-users-windows/"><u>Top 8 Video Editing Software for PC Users (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-1011-failure-codes/"><u>Overcoming Windows 10/11 Failure Codes</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-dormant-radeon-software-interface/"><u>Quick Fixes for Dormant Radeon Software Interface</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-permissions-to-prevent-read-only-mode/"><u>Mastering File Permissions to Prevent Read-Only Mode</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-top-5-audio-mixers-compatible-with-mac-computers/"><u>Updated 2024 Approved Top 5 Audio Mixers Compatible with Mac Computers</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/elevate-your-tiktok-score-with-these-10-key-tools-for-2024/"><u>Elevate Your TikTok Score with These 10 Key Tools for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-essential-screen-capture-techniques-for-powerpoint-presentations/"><u>[Updated] 2024 Approved  Essential Screen Capture Techniques for PowerPoint Presentations</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-turn-social-media-audio-into-mp3/"><u>[Updated] 2024 Approved  Turn Social Media Audio Into MP3</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sound-system-issue-with-windows-general-device/"><u>Overcoming Sound System Issue with Windows General Device</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-your-devices-aesthetics-using-microsoft-store-themes/"><u>Optimizing Your Device's Aesthetics Using Microsoft Store Themes</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-photo-perfection-on-iphones-and-androids-blurring-basics/"><u>[Updated] Photo Perfection on iPhones & Androids  Blurring Basics</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-file-access-error-on-windows-a-step-by-step-guide/"><u>Resolving File Access Error on Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-chrome-profile-errors-for-windows-users/"><u>Unraveling Chrome Profile Errors for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unexpected-reference-to-token-in-win10win11/"><u>Correcting Unexpected Reference to Token in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/win11-error-fixer-correcting-code-0x0000011b/"><u>Win11 Error Fixer: Correcting Code 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-macos-with-cross-platform-windows-features/"><u>Enhancing macOS with Cross-Platform Windows Features</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-email-notification-shortcom-written-exercise/"><u>Repairing Email Notification Shortcom Written Exercise:</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mastering-the-art-of-shorts-to-mp4-conversion-for-2024/"><u>Mastering the Art of Shorts to MP4 Conversion for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-file-management-skills-multi-zip-extraction-techniques/"><u>Elevate Your File Management Skills: Multi-Zip Extraction Techniques</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-nokia-g310-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Nokia G310? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-the-gap-find-missing-devices-in-dm/"><u>Bridge the Gap: Find Missing Devices In DM</u></a></li>
<li><a href="https://win11.techidaily.com/freezing-wi-fi-mouse-how-to-reset-and-restore-functionality-in-windows/"><u>Freezing Wi-Fi Mouse? How to Reset and Restore Functionality in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/powershell-pro-tips-for-win-ipmac-extraction/"><u>PowerShell Pro Tips for Win IP/MAC Extraction</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-cloud-file-retrieval-methods/"><u>Cross-Platform Cloud File Retrieval Methods</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-essential-compliance-rules-for-thriving-on-youtube/"><u>[Updated] Essential Compliance Rules for Thriving on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-guide-to-revive-windows-11s-essential-directories/"><u>Tailored Guide to Revive Windows 11'S Essential Directories</u></a></li>
<li><a href="https://win11.techidaily.com/the-beginners-handbook-to-github-desktop-and-windows-integration/"><u>The Beginner's Handbook to GitHub Desktop & Windows Integration</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-skyrocket-viewer-numbers-with-the-top-12-effective-tactics/"><u>2024 Approved  Skyrocket Viewer Numbers with the Top 12 Effective Tactics</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-uncovered-the-best-mac-speech-recognition-apps-you-never-knew-existed/"><u>2024 Approved Uncovered The Best Mac Speech Recognition Apps You Never Knew Existed</u></a></li>
<li><a href="https://win11.techidaily.com/activate-and-optimize-windows-powershell-script-policies/"><u>Activate and Optimize Windows PowerShell Script Policies</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-repeated-edge-desktop-additions/"><u>Stopping Repeated Edge Desktop Additions</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-process-termination-errors-effortlessly/"><u>Bypassing Process Termination Errors Effortlessly</u></a></li>
</ul></div>
