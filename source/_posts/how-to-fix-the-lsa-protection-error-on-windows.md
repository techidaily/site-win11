---
title: How to Fix the LSA Protection Error on Windows
date: 2024-07-13T09:47:12.488Z
updated: 2024-07-14T09:47:12.488Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the LSA Protection Error on Windows
excerpt: This Article Describes How to Fix the LSA Protection Error on Windows
keywords: Fix LSA Error,Resolve LSA Win Issue,Stop LSA Failure,Eradicate Windows LSA Errors,Cure LSA Problems Windows,Eliminate LSA Error on PC,Overcome LSA Windows Error
thumbnail: https://thmb.techidaily.com/1ee4d598dddce3a6246087c27cdd3992445e17b0d9a8038ff04440aee38e00e3.jpg
---

## How to Fix the LSA Protection Error on Windows

 LSA protection is a vital security feature on Windows that prevents unauthorized access to system resources. However, corrupt system files or malware infections may lead to an error stating "this change requires you to restart your device". This error persists even after enabling Local Security Authority (LSA) protection or restarting the computer.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.

## What Causes the LSA Protection Error?

 The exact cause of the “this change requires you to restart your device” error can vary, but it may be due to corrupted system files or malware infections. Malware can install malicious services and components that interfere with Windows' smooth functioning, including disabling Local Security Authority (LSA) protection. It can also occur if antivirus software incorrectly removes system files and causes instability.

 This error is usually triggered when Windows attempts to enable Local Security Authority (LSA) protection and fails. In some cases, the error may also appear after you enabled LSA protection and restarted your computer.

## 1\. Restart Your PC

 As the error message suggests, you first restart your Windows system. This minor step can fix several system-level errors and is worth a try. Restarting your computer involves shutting down all running programs and starting it up again.

## 2\. Scan for Malicious Programs

 If restarting the computer doesn't solve the issue, check your system for malicious software. Malware infections may corrupt system files and prevent LSA protection from working.

 To check if any malicious programs are on your system, do the following.

1. Press **Win + Q** on your keyboard to open the Taskbar search window.
2. Type **Windows Security** in the search bar and hit Enter.
3. On the left pane of Windows Security, click the **Virus & threat protection** tab.
4. Click **Scan options** on the right side of the screen.  
![Full Scan Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/full-scan-windows-security.jpg)
5. Select **Full scan** and click **Scan now**.

 Now wait for the scan to finish. If malicious programs are detected, Windows Security will remove them from your system automatically.

## 3\. Change the Group Policy Settings

 If the above steps don't help, you might need to configure LSA manually. It involves editing the Local Group Policy Editor and setting some specific settings. However, this tool only works with Windows 11 Professional and Enterprise editions.

 So, if you're running Windows Home Edition, you won't have access to Local Group Policy. To make this work, [enable the Local Group Policy Editor in Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/), then follow these steps:

1. Press **Win + R** on your keyboard to open the Run dialogue box.
2. Type **gpedit.msc** in the search box and hit Enter.
3. In the Local Group Policy Editor, expand **Computer Configuration** on the left side.
4. Then navigate to the following:  
Administrative Templates > System > Local Security Authority
5. Double-click **Configure LSASS to run as a protected process** in the right pane.  
![Change the Group Policy Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-the-group-policy-settings.jpg)
6. Now, in the window that appears, alter the settings from **Not Configured** to **Enabled**.
7. Under the Options section, click the drop-down menu for **Configure LSASS to run as a protected process** and select **Enabled with UEFI Lock**.  
![Set as Enabled with UEFI Lock](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/set-as-enabled-with-uefi-lock.jpg)
8. Now click **Apply > OK** to save the changes.

 After making the above changes, restart your computer and check if the error is resolved.

## 4\. Tweak the Registry Editor

 If you're running Windows Home edition, you can tweak the Registry Editor to modify Local Security Authority protection values. The steps are pretty straightforward, but be aware that making incorrect changes to the registry can cause serious problems. To be safe, [back up the Windows Registry data](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

1. Press **Win + R** on your keyboard to open the Run command.
2. Type **regedit** in the dialog box and press the Enter key.
3. If UAC prompts appear on the screen, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following location:  
Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa  
 You can also copy and paste the given path into the address bar at the top of the Registry window. Then, hit Enter to jump directly to the folder.
5. In the right pane, double-click on **RunAsPPL** to open Edit DWORD (32-bit) Value.  
![Change RunAsPPL regsitry values](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/change-runasppl-regsitry-values.jpg)
6. Change the Value data from 0 to **2** and click **OK**.
7. Similarly, find the **RunAsPPLBoot** key and set its value to **2**.  
 If you don't find the **RunAsPPL** and **RunAsPPLBoot** keys in the LSA folder, you'll need to create them manually. To do this, right-click on the LSA folder and select **New > DWORD (32-bit) Value**. Name the new value **RunAsPPL** and set its value to 2\. Then repeat this process for the **RunAsPPLBoot** key.

 Once you're done, close the Registry Editor and restart your computer. This should fix the problem.

## 5\. Reset the Windows Security App

 Windows Security is an integrated antivirus program built into the Windows OS. It's responsible for scanning your system and removing malicious content. If there's something wrong with the Windows Security app, it might trigger this error. To fix the issue, reset the app and see if it helps. Here's how to do it:

1. Press **Win + I** on your keyboard to open the system settings.
2. Select **Apps** on the left side of the window.
3. Click **Installed apps** in the right pane
4. Scroll down the list of apps until you see **Windows Security**. You can also type Windows Security into the search bar to find it quickly.
5. Now click the three dots icon and select **Advanced options** from the menu.
6. On the next page, scroll down to the **Reset** section and click **Reset**.  
![Reset Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/reset-windows-security.jpg)
7. If the confirmation window pops up, click **Reset** to continue.

 Wait for the reset process to finish and restart your computer. After restarting, check if the error is still present.

## 6\. Perform Some Generic Fixes

 There are also some generic fixes to resolve the issue. First, [run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) command to repair incorrect or damaged system files. You may also want to use the Deployment Image Servicing and Management tool to diagnose issues with local system images. If the problem persists, try [updating Windows to the latest version](https://www.makeuseof.com/update-windows-manually/) to resolve any glitches or bugs.

 Some antivirus and security programs can be too aggressive in protecting your system. They could prevent access to the LSA feature, leading to this problem. To be sure, you can [temporarily disable your security software](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and check if it solves the issue.

## Fixing the LSA Protection Error on Windows

 Local Security Authority protection safeguards unauthorized access to system resources, such as passwords or other sensitive information. However, this feature might not work as expected due to LSA Protection Error. Thanks to the potential solutions discussed in this guide, solving the problem is easy.

 It suggests an underlying problem that requires resolution to restore system security. If you have the same problem, these solutions might help.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-windows-photography-errors/"><u>Mastering the Art of Fixing Windows Photography Errors</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-user-experience-including-wordpad-shortcuts-to-11s-menu-bar/"><u>Elevating User Experience: Including WordPad Shortcuts to 11'S Menu Bar</u></a></li>
<li><a href="https://win11.techidaily.com/three-methods-for-exploring-windows-policy-settings/"><u>Three Methods for Exploring Windows Policy Settings</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/there-we-introduce-you-3-simple-options-for-recording-video-games-with-ease-for-2024/"><u>There We Introduce You 3 Simple Options for Recording Video Games with Ease for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unallocated-vram-on-hogwarts-legacy-platform/"><u>Correcting Unallocated VRAM on Hogwarts Legacy Platform</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-installation-of-ai-tools-in-windows/"><u>Efficient Installation of AI Tools in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/5-simple-ways-to-tell-if-your-pc-needs-restarting/"><u>5 Simple Ways to Tell if Your PC Needs Restarting</u></a></li>
<li><a href="https://win11.techidaily.com/key-to-the-past-windows-11s-historical-files-retrieval/"><u>Key to the Past: Windows 11’S Historical Files Retrieval</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-ultimate-resource-for-artists-identifying-the-top-10-free-online-creative-communities/"><u>[Updated] The Ultimate Resource for Artists  Identifying the Top 10 Free Online Creative Communities</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-canvas-and-chroma-mastering-color-interaction/"><u>In 2024, Canvas and Chroma  Mastering Color Interaction</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-hidden-gems-unlocking-full-potential/"><u>Windows 11'S Hidden Gems: Unlocking Full Potential</u></a></li>
<li><a href="https://win11.techidaily.com/covert-strategies-to-erase-taskbars-language-bar-win11/"><u>Covert Strategies to Erase Taskbar's Language Bar, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-video-driver-crash-on-win1110/"><u>Addressing Video Driver Crash on Win11/10</u></a></li>
<li><a href="https://unlock-android.techidaily.com/best-vivo-g2-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Vivo G2 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11.techidaily.com/windows-without-bitlocker-here-are-4-steps-to-stay-secure/"><u>Windows Without Bitlocker? Here Are 4 Steps to Stay Secure</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-the-ultimate-android-and-ios-picks-for-insta-friendships/"><u>2024 Approved  The Ultimate Android & iOS Picks for Insta-Friendships</u></a></li>
<li><a href="https://win11.techidaily.com/usb-wi-fi-anomalies-on-windows-heres-the-solution-guide-you-need/"><u>USB Wi-Fi Anomalies on Windows? Here's the Solution Guide You Need</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-performance-in-shooter-games-through-sensitivity-tweaks/"><u>Boosting Performance in Shooter Games Through Sensitivity Tweaks</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-speedy-tactics-for-disorganized-youtube-song-listings/"><u>In 2024, Speedy Tactics for Disorganized YouTube Song Listings</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-potential-of-openais-ai-for-voice-to-text-in-windows/"><u>Unlocking the Potential of OpenAI's AI for Voice-to-Text in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-customizable-spotlight-picture-guide/"><u>Windows Customizable Spotlight Picture Guide</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/re-high-quality-sounds-for-media-creators/"><u>Acquire High-Quality Sounds for Media Creators</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-language-of-windows-updates/"><u>Decoding the Language of Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-secrets-of-windows-11s-app-collection/"><u>Unveiling the Secrets of Windows 11'S App Collection</u></a></li>
<li><a href="https://win11.techidaily.com/devhome-the-comprehensive-resource-for-w11-enthusiasts/"><u>DevHome: The Comprehensive Resource for W11 Enthusiasts</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-asus-rog-phone-8-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unhindered-microsoft-store-operation-on-windows-11/"><u>Unhindered Microsoft Store Operation on Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-secrets-to-smoothly-resolving-youtube-short-issues/"><u>In 2024, Secrets to Smoothly Resolving YouTube Short Issues</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-experts-guide-to-backward-video-playback-on-snap/"><u>2024 Approved  Expert's Guide to Backward Video Playback on Snap</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-windows-update-problems-quickly/"><u>Break Free From Windows Update Problems Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-temporary-directory-error-win-error-1152/"><u>Fixing 'Temporary Directory Error' - Win Error 1152</u></a></li>
<li><a href="https://win11.techidaily.com/5-hacks-for-accessing-windows-repair-options/"><u>5 Hacks for Accessing Windows Repair Options</u></a></li>
<li><a href="https://win11.techidaily.com/tracing-the-footprints-of-your-latest-window-use/"><u>Tracing the Footprints of Your Latest Window Use</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-technique-to-effortlessly-install-win11-with-workstation-17/"><u>Unveiling the Technique to Effortlessly Install Win11 with Workstation 17</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-inaccessible-printmanagement-service-in-os/"><u>Dealing with Inaccessible 'PrintManagement' Service in OS</u></a></li>
<li><a href="https://win11.techidaily.com/clean-slate-for-windows-users-generative-erase-wonders/"><u>Clean Slate for Windows Users: Generative Erase Wonders</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-pin-update-guide/"><u>Mastering Windows PIN Update Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-dynamic-display-and-distribution/"><u>[New] In 2024, Dynamic Display and Distribution</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-mastering-video-editing-a-step-by-step-guide-to-windows-movie-maker/"><u>New In 2024, Mastering Video Editing A Step-by-Step Guide to Windows Movie Maker</u></a></li>
<li><a href="https://win11.techidaily.com/establishing-enduring-trash-settings-in-the-windows-environment/"><u>Establishing Enduring Trash Settings in the Windows Environment</u></a></li>
</ul></div>
