---
title: Instructions for Setting Windows Backups Against Original Standards
date: 2024-06-25T11:36:31.066Z
updated: 2024-06-26T11:36:31.066Z
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
<li><a href="https://win11.techidaily.com/how-to-troubleshoot-common-issues-with-closed-captioning-in-windows-11/"><u>How to Troubleshoot Common Issues with Closed Captioning in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-choosing-windows-photos-tools/"><u>The Ultimate Guide to Choosing Windows Photos Tools</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-stop-background-programs/"><u>Mastering Window 11: Stop Background Programs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-the-google-play-store-on-windows-11/"><u>How to Install the Google Play Store on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719343225911-epic-launcher-uninstallation-hurdles-bust-them-on-windows-11/"><u>Epic Launcher Uninstallation Hurdles, Bust Them On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-image-adjustment-the-six-essential-techniques/"><u>Windows 11 Image Adjustment: The Six Essential Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-frozen-ctrl-key-functionality-in-windows-11-pcs/"><u>Addressing Frozen CTRL Key Functionality in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/locating-post-bsod-error-logs-in-windows-explorer/"><u>Locating Post-BSOD Error Logs in Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-quick-guide-to-open-sticky-notes/"><u>Windows 11: Quick Guide to Open Sticky Notes</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-deciphering-screens-a-comprehensive-review-of-recording-apps/"><u>2024 Approved  Deciphering Screens  A Comprehensive Review of Recording Apps</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-25-essential-no-cost-photography-tools-for-creatives/"><u>[New] 25 Essential No-Cost Photography Tools for Creatives</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-oppo-find-n3-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Oppo Find N3 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-advanced-photo-editing-canvas-backdrop-eradication/"><u>In 2024, Advanced Photo Editing  Canvas Backdrop Eradication</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-vivo-y36i-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Vivo Y36i Phone Pattern Lock</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-beginners-blueprint-zoom-clustered-conferencing/"><u>[Updated] Beginner's Blueprint  Zoom Clustered Conferencing</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/5-most-effective-methods-to-unlock-apple-iphone-8-in-lost-mode-drfone-by-drfone-ios/"><u>5 Most Effective Methods to Unlock Apple iPhone 8 in Lost Mode | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/enhancing-video-storytelling-incorporating-audio-elements-for-2024/"><u>Enhancing Video Storytelling Incorporating Audio Elements for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-syncopating-youtube-melodies-with-visuals/"><u>In 2024, Syncopating YouTube Melodies with Visuals</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/aspect-ratio-made-simple-the-best-online-calculators/"><u>Aspect Ratio Made Simple The Best Online Calculators</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>