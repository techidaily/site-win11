---
title: Instructions for Setting Windows Backups Against Original Standards
date: 2024-06-25T10:26:29.754Z
updated: 2024-06-26T10:26:29.754Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Instructions for Setting Windows Backups Against Original Standards
excerpt: This Article Describes Instructions for Setting Windows Backups Against Original Standards
keywords: Windows Backup Guide,Standard Backup Setup,Restore Original Files,Windows Data Safety,File Recovery Tips,Regular Backup Schedule,Secure Windows Updates
thumbnail: https://thmb.techidaily.com/f7aa9f91ee25ba92e513ec309ccac0797742d37b71585737d9811b8df3523624.jpg
---

## Instructions for Setting Windows Backups Against Original Standards

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
<li><a href="https://win11.techidaily.com/streamlining-connection-between-win-code-and-microsoft-services/"><u>Streamlining Connection Between WIN Code and Microsoft Services</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-re-enable-razer-recognition-by-synapse/"><u>How to Re-Enable Razer Recognition by Synapse</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-transformation-mp3-files-to-windows-compatible-audio-cds-with-imgburn/"><u>Immediate Transformation: MP3 Files to Windows-Compatible Audio CDs with ImgBurn</u></a></li>
<li><a href="https://win11.techidaily.com/method-to-resolve-audacitys-device-open-error-on-pc/"><u>Method to Resolve Audacity's Device Open Error on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-the-closed-folder-conundrum-in-winxpxo11/"><u>How to Overcome the Closed Folder Conundrum in WinXP/XO11</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-chat-disappearance-in-windows-11-what-it-entails-for-users/"><u>Taskbar Chat Disappearance in Windows 11: What It Entails for Users</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-android-studio-on-windows-for-faster-compilation/"><u>Optimizing Android Studio on Windows for Faster Compilation</u></a></li>
<li><a href="https://extra-tips.techidaily.com/pinnacle-promotion-reels/"><u>Pinnacle Promotion Reels</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-creating-accessible-multilingual-content-on-igtv/"><u>[New] 2024 Approved  Creating Accessible Multilingual Content on IGTV</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-quick-advice-preserving-gotomeetings-with-minimal-fuss/"><u>2024 Approved  Quick Advice  Preserving GoToMeetings with Minimal Fuss</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/discreet-snaps-the-secret-of-silent-photo-taking-on-snapchat-for-2024/"><u>Discreet Snaps  The Secret of Silent Photo-Taking on Snapchat for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-the-snapshot-solution-how-to-swiftly-switch-your-gif-for-a-sticker/"><u>[Updated] The Snapshot Solution  How to Swiftly Switch Your GIF for a Sticker</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-installation-walkthrough-for-moviemaker-6-users/"><u>2024 Approved  Installation Walkthrough for Moviemaker 6 Users</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-democracy-dive-top-5-political-gamified-experiences/"><u>[Updated] In 2024, Democracy Dive  Top 5 Political Gamified Experiences</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unveiling-the-bestiary-of-top-ios-gif-tools-for-2024/"><u>Unveiling the Bestiary of Top iOS GIF Tools for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>