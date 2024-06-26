---
title: Resetting Your Windows Backup Preferences
date: 2024-06-25T10:06:48.515Z
updated: 2024-06-26T10:06:48.515Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resetting Your Windows Backup Preferences
excerpt: This Article Describes Resetting Your Windows Backup Preferences
keywords: Reset Windows Backup,Change Backup Options,Adjust Windows Save Settings,Alter Backup Preferences,Modify Windows Restore,Setback Configuration,Personalize Windows Save
thumbnail: https://thmb.techidaily.com/67bd9eb22eb0b577554d0f90d5db30aca97e4f163bbbccbbc666c03d517f249c.jpg
---

## Resetting Your Windows Backup Preferences

 System failure or data loss can cause huge amounts of damage and that’s why Windows offers a backup feature to protect your critical data. If your backups corrupt or otherwise function incorrectly, you can reset Windows Backup to its default settings. This guide will teach you some methods to reset Windows Backup to its default on Windows.

## How Do I Know if I Need to Reset Windows Backup?

 You may need to reset Windows Backup if your backups aren't working, taking too long to create, or you can't access the stored files. If you are experiencing these issues, resetting Windows Backup may resolve them.

 For this, either use the Command Prompt or create a batch file. The steps for both methods are outlined below and should help you get your backups running again.

## Is Resetting Window Backup Risky?

 While resetting Windows Backup is generally safe, there are some risks associated with it.

 Firstly, you may lose all existing backups if you reset Windows Backup. To ensure you don't lose data, [create a backup of the existing Windows files](https://www.makeuseof.com/tag/backup-windows-files-folders/) before resetting Windows Backup.

 Furthermore, the reset may affect some third-party apps. It's wise to check with your software vendor before resetting Windows Backup.

 If something goes wrong during the reset, you may have a corrupted backup configuration. In such cases, reinstall the operating system and start from scratch.

 Overall, resetting Windows Backup helps resolve existing issues, but take the necessary precautions to avoid potential risks.

## How to Reset Windows Backup to Its Factory Settings

 Now you know how to proceed with caution, here's how to reset Windows Backup to its factory settings.

### 1\. Using Command Prompt

 If your current backup configuration isn't working, reset Windows Backup to its default settings. To get started, [run the Command Prompt with admin access](https://www.makeuseof.com/windows-run-command-prompt-admin/). In the Command Prompt window, run the following command:

`reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f`

 This will reset to the default configuration and remove all existing backups.

 After that, copy and paste the following command into the Command Prompt window and press **Enter**:

`reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup`

 This will recreate the WindowsBackup entry in the registry editor. Next, type in and run the below command to delete the Automatic Backup scheduled task on Windows:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f`

 Finally, execute the below command to delete the backup monitor scheduled task:

`schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 After executing the above commands, restart your computer. This will reset Windows Backup to its default settings.

### 2\. Creating a Batch File

 If you're not comfortable with the command line interface, reset Windows Backup by creating a batch file.

 To do this, [open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and paste the below code.

`<code>reg delete HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup /f  
reg add HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsBackup  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\AutomaticBackup" /f  
schtasks /delete /tn "Microsoft\Windows\WindowsBackup\Windows Backup Monitor" /f`

 Click the **File** menu and select **Save as**. On the Save as dialog, type **reset-backup.bat** as the file name. Then choose **All Files** from the drop-down menu next to the Save as type. From the left panel, select **Desktop** and click the **Save** button.

 Now, close the Notepad window and right-click on the batch file. From the context menu, select **Run as administrator**. This will reset Windows Backup to its default settings.

 Lastly, restart your computer and you're done. These are two methods to reset Windows Backup to its default settings.

## Get Your Backups Working Again on Windows

 Whether you use the command line interface or create a batch file, it's easy to reset Windows Backup. Just remember to restart your computer after the process completes successfully.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/elevating-your-batch-scripts-creating-windows-exes/"><u>Elevating Your Batch Scripts: Creating Windows EXEs</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-computing-enable-hyper-v-in-windows-11-homes/"><u>Boost Your Computing: Enable Hyper-V in Windows 11 Homes</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-geforce-0x0001-in-windows-1011-environment/"><u>Addressing GeForce 0X0001 in Windows 10/11 Environment</u></a></li>
<li><a href="https://win11.techidaily.com/permanent-elimination-guide-for-wsl-on-windows-11-systems/"><u>Permanent Elimination Guide for WSL on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/from-minuscule-to-monumental-boosting-windows-11-icon-sizes/"><u>From Minuscule to Monumental - Boosting Windows 11 Icon Sizes</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-quick-access-tools-into-the-win11-taskbar-easily/"><u>Incorporating Quick Access Tools Into the Win11 Taskbar Easily</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-revamped-widget-picker-in-win11/"><u>Configuring Revamped Widget Picker in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/solving-mbs-service-connection-failures-on-windows-11/"><u>Solving MB's Service Connection Failures on Windows 11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-make-facebook-videos-extend-the-wallpaper/"><u>[Updated] 2024 Approved  Make Facebook Videos Extend the Wallpaper</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-itel-p40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Itel P40 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-h-265-hevc-video-on-xiaomi-redmi-13c-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Issues playing H.265 HEVC video on Xiaomi Redmi 13C</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/from-capture-to-share-expert-insights-into-screen-recording-software-for-2024/"><u>From Capture to Share  Expert Insights Into Screen Recording Software for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-comprehensive-guide-to-cross-posting-youtube-video-on-fb-for-2024/"><u>[New] Comprehensive Guide to Cross-Posting YouTube Video on FB for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/itunes-recording-proven-techniques-for-success/"><u>ITunes Recording Proven Techniques for Success</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-flixfortress-over-a-hundred-channels-of-fortitude/"><u>[New] FlixFortress  Over a Hundred Channels of Fortitude</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-screen-recorder-showdown-features-and-prices-compared-for-2024/"><u>[Updated] Screen Recorder Showdown  Features and Prices Compared for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-the-verdict-on-vllo-performance/"><u>[New] The Verdict on VLLO Performance</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>