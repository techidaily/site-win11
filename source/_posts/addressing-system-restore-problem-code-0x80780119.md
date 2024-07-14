---
title: "Addressing System Restore Problem: Code 0X80780119"
date: 2024-07-13T11:17:54.775Z
updated: 2024-07-14T11:17:54.775Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Addressing System Restore Problem: Code 0X80780119"
excerpt: "This Article Describes Addressing System Restore Problem: Code 0X80780119"
keywords: System_Restore_Error,ErrorCode0X80780119,Restore_FunctionalityIssue,OS_System_Failure,Software_RepairTips,Code_RecoverySolution,Windows_BackupProblem
thumbnail: https://thmb.techidaily.com/0d1e6d469f4667c3d31e2ee564e25a93a1f4e0a1835558608501c466657ed85d.png
---

## Addressing System Restore Problem: Code 0X80780119

 Creating a system image backup is essential in protecting your data and ensuring system recoverability, but the process of doing so might not always go smoothly. One such error that the users often encounter is the System Restore error 0x80780119, which prevents the users from completing the backup process.

 Below, we take a look at the common causes of this issue and discuss the different solutions you can try to get rid of this error for good.

## Why Are You Unable to Create a System Image?

 If you are unable to create a system image due to the error 0x80780119, it might be because of one or more of the following reasons:

* **Insufficient disk space**: Restore points take up space in the drive they are saved, and so to create new restore points on your computer, you must have sufficient disk space available. In case you are running out of space on your system, you are likely to face the error at hand.
* **Incorrect backup settings**: Your backup settings must be configured correctly. If there is an issue with these settings, the System Restore will encounter issues while creating a restore point.
* **External drive issues**: If you are using an external drive for backup, it is essential to ensure that it is connected to the system properly and is functioning. In case there is an issue with the external drive due to any of these problems, the System Restore utility might return the error 0x80780119\.
* **Corrupt system files**: The critical system files that are essential to create restore points and use the System Restore utility might have gotten corrupt, which is leading to the error under discussion.
* **Antivirus interruption**: If you are using a security program on your computer, there is a chance that it is blocking the restore tool from functioning properly. This typically happens when you are using a third-party antivirus solution.

 Regardless of what might be resulting in the problem in your case, the solutions we have listed below are sure to help you get the restore utility back on track. Proceed with the solutions one by one and follow the steps carefully for successful execution.

## 1\. Free Up Disk Space

 When you create a restore point in Windows, the system requires sufficient space on the destination drive to store all the backup files. If you do not have enough space, the System Restore is likely to return errors like the 0x80780119 error.

 This is why, before moving onto the complex troubleshooting methods, we recommend you ensure you have sufficient space available on the destination drive. If you are low on space, you can free it up by removing unnecessary files. Here are a few areas to focus on:

* **Temporary files**: Temporary files and other unnecessary data can be cleaned up by [using the Disk Cleanup tool](https://www.makeuseof.com/tag/best-way-clean-windows-10-step-step-guide/). It will list down all such files, and you can then specify which to remove. Simply type “Disk Cleanup” in the search area on your taskbar and click **Open** to launch the utility.
* **Downloads folder**: Access the Download folder in File Explorer and delete all the files you no longer need.
* **Uninstall unused programs**: If there are apps that you do not use anymore, head over to the Control Panel to uninstall them from the system. This will free up a great amount of space that can be used by the System Restore utility.

 In case you have large files or folders that you do not want to remove but also don’t need immediately, you can consider moving them to an external drive to free up space.

## 2\. Check and Repair Disk Errors

 You might also be facing the system restore issue due to disk errors in the system.

 During the backup process, the system needs to read data from the targeted disk and write it to the backup destination. If there is an issue with the disk, the system may have issues reading the data or might write corrupted data in the backup file, which can result in different errors.

 Additionally, your disk might have bad sectors which cannot store data properly and might also prevent the system from reading data during the backup process.

 To ensure this isn’t the case in your situation, it is best to check the disk for errors using the built-in utilities offered by Windows. The first tool that we recommend [using is the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) which can be used via Command Prompt. It works by scanning the system and checking the integrity of the disk. If a problem is identified, CHKDSK will attempt to fix it automatically.

 Alternatively, you can head over to the File Explorer and follow these steps:

1. In File Explorer, head over to the root of the drive you want to check and right-click on it.
2. Choose **Properties** from the context menu.
3. In the Properties dialog, navigate to the **Tools** tab and move to the **Error checking** section.
4. Click on the **Check** button here and wait for the system to complete the scan. This may take some time, depending upon the size of your disk.  
![Run the error checking tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/error-checking-tool.jpg)

 If any issues are found, Windows will prompt you to repair them. Follow the on-screen instructions to proceed.

## 3\. Enable System Protection

 Several users also noticed that they were facing the problem due to the system protection feature being disabled for the targeted drive. If you have this option disabled in your system, we suggest enabling it and checking if that makes any difference.

 Here is how you can do that:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Navigate to **System** \> **About**.
3. Head over to the **Device specifications** section and click on the **System protection** option.  
![Click on the System protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection-options.jpg)
4. In the following dialog, head over to the **System Protection** tab.
5. Choose the targeted drive and click on the **Configure** button.  
![Click on the Configure button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/configure-button.jpg)
6. Enable the **Turn on system protection** option and click **Apply** \> **OK** to save the changes.  
![Enable system protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-system-protection.jpg)

 You can now close the System Protection dialog and check if the issue is resolved.

## 4\. Delete USN Journal

 The USN Journal (Update Sequence Number Journal) is a feature in the NTFS file system that tracks all the changes made on a disk. It is stored in the reserved partition and over time, it can consume a significant amount of your disk space, which may be preventing a restore point from being created.

 You can reclaim this disk space by deleting the USN Journal. Doing so will also eliminate the possibility of any conflicts that might be arising due to inconsistencies between the journal and the files being backed up.

 Here is how you can do that:

1. Type "Create and format hard disk partitions" in Windows search and click **Open**.
2. In the following window, right-click on the **System Reserved** volume and choose **Change Drive Letter and Paths** from the context menu.
3. Now, click on the **Add** button.
4. In the next dialog, choose **Assign the following drive letter** and click **OK**.  
![Change the USB Drive Letter Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-the-usb-drive-letter-using-disk-management.jpg)
5. Once done, press the **Win** \+ **R** keys together to open Run.
6. Type "cmd" in Run and click **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.
7. Confirm your action in the UAC prompt.
8. Execute the following commands in Command Prompt one by one:  
`fsutil usn queryjournal F:fsutil usn deletejournal /N /D F:`

 After the commands are executed, you can close Command Prompt and check if the issue is resolved.

## Create a Backup Without Any More Errors on Windows

 Ensuring the protection of your data should be your foremost priority, and a system image backup plays a vital role in safeguarding against unforeseen data loss. With the solutions above, you should be able to get the System Restore utility up and running in no time. However, if the problem persists, you can consider reporting the issue to Microsoft and try the specific solutions they suggest. Till then, you can switch to a third-party backup tool to safeguard your data.

 Below, we take a look at the common causes of this issue and discuss the different solutions you can try to get rid of this error for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/minimizing-edges-process-count-in-windows/"><u>Minimizing Edge's Process Count in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-original-directory-display-preferences/"><u>Regaining Original Directory Display Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/a-fresh-start-for-your-computers-firewall-settings/"><u>A Fresh Start for Your Computer's Firewall Settings</u></a></li>
<li><a href="https://win11.techidaily.com/resurrect-your-xbox-on-a-slow-pc-steps-to-take/"><u>Resurrect Your Xbox on a Slow PC: Steps to Take</u></a></li>
<li><a href="https://extra-information.techidaily.com/innovative-photo-display-solutions/"><u>Innovative Photo Display Solutions</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-activate-grid-in-google-meet-for-full-participant-display-for-2024/"><u>[New] Activate Grid in Google Meet for Full-Participant Display for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-force-delete-or-uninstall-a-printer-in-windows-11-and-11/"><u>How to Force Delete or Uninstall a Printer in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-mail-readability-removing-html-from-email-text/"><u>Enhancing Windows 11 Mail Readability: Removing HTML From Email Text</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-extend-windows-10-shutdown-for-ongoing-processes/"><u>Strategies to Extend Windows 10 Shutdown for Ongoing Processes</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-top-picks-perfect-mics-for-creator-pros/"><u>[Updated] In 2024, Top Picks  Perfect Mics for Creator Pros</u></a></li>
<li><a href="https://win11.techidaily.com/beneath-the-surface-steps-to-engage-with-windows-covert-personality-explorer/"><u>Beneath the Surface: Steps to Engage with Windows’ Covert Personality Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missing-action-buttons-on-windows-11-pc/"><u>Overcoming Missing Action Buttons on Windows 11 PC</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-realme-gt-5-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Realme GT 5 Device</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-modify-win11s-network-preferences/"><u>Guide to Modify Win11's Network Preferences</u></a></li>
<li><a href="https://extra-skills.techidaily.com/navigating-the-complexities-of-photo-hdr-in-photoshop-for-2024/"><u>Navigating the Complexities of Photo-HDR in Photoshop for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/cure-for-mcuicntexe-entry-point-loss-in-windows-systems/"><u>Cure for McUICnt.exe Entry Point Loss in Windows Systems</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-techniques-for-downloading-pinterest-videos-as-mp3s/"><u>[Updated] Techniques for Downloading Pinterest Videos as MP3s</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-samsung-galaxy-xcover-7-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Samsung Galaxy XCover 7</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-m4a-file-editor-top-5-free-tools-for-2024/"><u>Updated M4A File Editor Top 5 Free Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-about-to-expire-message-on-microsoft-os/"><u>Bypassing the About To Expire Message on Microsoft OS</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-no-hassle-just-tones-5-free-online-generators/"><u>New In 2024, No Hassle, Just Tones 5 Free Online Generators</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-tech-triumphs-cutting-edge-vr-devices-reviewed/"><u>2024 Approved  Tech Triumphs  Cutting-Edge VR Devices Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-windows-assistance-entry/"><u>Mastering the Art of Windows Assistance Entry</u></a></li>
<li><a href="https://win11.techidaily.com/1719334729837-fix-unusable-compatibility-center-on-vista7-pcs-fast/"><u>Fix Unusable Compatibility Center on Vista/7 PCs Fast</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-a-microsoft-account-and-a-local-account-are-different-on-windows/"><u>6 Ways a Microsoft Account and a Local Account Are Different on Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-rage-quarters-and-swords-nintendo-switch-fighting-classics/"><u>In 2024, Rage Quarters & Swords  Nintendo Switch Fighting Classics</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-smooth-operator-3-techniques-to-stabilize-footage-in-ae-for-2024/"><u>Updated Smooth Operator 3 Techniques to Stabilize Footage in AE for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-ultimate-guide-to-advanced-techniques-in-youtube-video-editing-for-2024/"><u>The Ultimate Guide to Advanced Techniques in YouTube Video Editing for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-the-ultimate-tracker-gauging-youtube-popularity-for-financial-insights/"><u>[Updated] 2024 Approved  The Ultimate Tracker  Gauging YouTube Popularity for Financial Insights</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-use-of-windows-module-installer-worker/"><u>Decreasing Excessive Use of Windows Module Installer Worker</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-canva-imagery-top-10-pro-level-techniques/"><u>[New] Mastering Canva Imagery  Top 10 Pro-Level Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/pixelprecision-snag-9-tactics-to-reinstate-it/"><u>PixelPrecision Snag? 9 Tactics to Reinstate It</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-ultimate-guide-to-podcast-scriptwriting-with-10plus-free-examples/"><u>In 2024, The Ultimate Guide to Podcast Scriptwriting (With 10+ Free Examples)</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-password-policy-setting-new-limit-post-failed-logins/"><u>Revamping Password Policy: Setting New Limit Post Failed Logins</u></a></li>
<li><a href="https://win11.techidaily.com/disable-dim-display-feature-via-control-panel-quick-guide/"><u>Disable Dim Display Feature via Control Panel Quick Guide</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-insta-personality-showcase-100-crafted-caption-ideas/"><u>[New] Insta Personality Showcase - 100 Crafted Caption Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-efficiency-quick-access-to-system-restore-in-windows-11/"><u>Unlocking Efficiency: Quick Access to System Restore in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-tray-interface-with-numeric-and-caps-indicators/"><u>Personalize Tray Interface with Numeric and Caps Indicators</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-system-top-5-tips-for-mastering-windows-folders/"><u>Supercharge Your System: Top 5 Tips for Mastering Windows Folders</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-tune-up-discover-windows-best-speed-solutions/"><u>Turbo Tune-Up: Discover Windows' Best Speed Solutions</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-realme-11x-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Realme 11X 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-viral-content-showdown-is-the-time-for-likee-to-surpass-tiktok-nearing/"><u>2024 Approved  Viral Content Showdown  Is the Time for Likee to Surpass TikTok Nearing?</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-oppo-a78-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Oppo A78 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11.techidaily.com/managing-safe-browsing-in-microsofts-win11/"><u>Managing Safe Browsing in Microsoft’s Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mysteries-of-sam-errors-windows-edition/"><u>Unraveling the Mysteries of SAM Errors, Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unknown-hardware-in-windows-1110/"><u>Troubleshooting Unknown Hardware in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-uninstall-microsoft-edge-from-windows-11/"><u>How to Uninstall Microsoft Edge From Windows 11</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-overwatch-playback-techniques-explained/"><u>[Updated] Overwatch Playback Techniques Explained</u></a></li>
</ul></div>
