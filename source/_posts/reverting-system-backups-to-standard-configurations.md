---
title: Reverting System Backups to Standard Configurations
date: 2024-06-25T11:30:15.723Z
updated: 2024-06-26T11:30:15.723Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reverting System Backups to Standard Configurations
excerpt: This Article Describes Reverting System Backups to Standard Configurations
keywords: Backup Reversion,Config Standardization,Restore Defaults,Config Reset,Save Initial Setup,Base Configuration,Customized Settings Return
thumbnail: https://thmb.techidaily.com/57fc80a0532998e9a3fa34c3a10aaf11a38c8a2570d6f12d0969979c5207b72c.jpg
---

## Reverting System Backups to Standard Configurations

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
<li><a href="https://win11.techidaily.com/reactivating-lost-ms-store-access-on-windows-11-and-11/"><u>Reactivating Lost MS Store Access on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reinstate-missing-mfc71udll-in-windows/"><u>How to Reinstate Missing Mfc71u.dll in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11s-printer-interface-max-52-chars/"><u>Streamline Windows 11'S Printer Interface (Max 52 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-game-bar-errors-due-to-weak-hardware/"><u>Fixing Game Bar Errors Due to Weak Hardware</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-sleep-state-in-windows-11s-usb-cores/"><u>How to Prevent Sleep State in Windows 11'S USB Cores</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-route-from-gaming-archives-to-windows-memories/"><u>The Essential Route From Gaming Archives to Windows Memories</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-concurrent-wi-fi-and-ethernet-on-windows-pcs/"><u>Mastering Concurrent Wi-Fi and Ethernet on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-file-system-usability-in-windows-max-156/"><u>Enhancing File System Usability in Windows (Max 156)</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-infinix-smart-8-pro-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Samsung Galaxy A05s? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-magixs-masterpiece-an-in-depth-look-at-video-pro-x/"><u>2024 Approved  Magix's Masterpiece  An In-Depth Look at Video Pro X</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-snapchat-cameos-catch-up-with-the-trendiest-trick/"><u>[Updated] Snapchat Cameos  Catch Up with the Trendiest Trick</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/picture-perfectionism-top-tools-and-sites-for-superior-photo-frames-for-2024/"><u>Picture Perfectionism  Top Tools & Sites for Superior Photo Frames for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-the-ultimate-guide-to-popular-sound-capture-software/"><u>Updated The Ultimate Guide to Popular Sound Capture Software</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-samsung-galaxy-a14-5g-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Samsung Galaxy A14 5G FRP</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-motorola-defy-2-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Motorola Defy 2</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-photos-from-realme-c33-2023-by-fonelab-android-recover-photos/"><u>How to Rescue Lost Photos from Realme C33 2023?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>