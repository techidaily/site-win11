---
title: Resetting Your Windows Backup Preferences
date: 2024-06-25T11:30:07.455Z
updated: 2024-06-26T11:30:07.455Z
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
<li><a href="https://win11.techidaily.com/bypassing-the-about-to-expire-message-on-microsoft-os/"><u>Bypassing the About To Expire Message on Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/winrars-file-consistency-fixing-summation-discrepancies/"><u>WinRAR's File Consistency: Fixing Summation Discrepancies</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-systray-information-showcasing-cpu-and-ram-in-ui/"><u>Elevate SysTray Information: Showcasing CPU & RAM in UI</u></a></li>
<li><a href="https://win11.techidaily.com/secret-start-screen-tactics-vanish-power-buttons-from-windows-11/"><u>Secret Start Screen Tactics: Vanish Power Buttons From Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719249883200-revive-keys-in-crisis-arrows-rescued/"><u>Revive Keys in Crisis: Arrows Rescued!</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-network-preferences-with-windows-11-proxies/"><u>Navigating Your Network Preferences with Windows 11 Proxies</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-read-only-folders-a-step-by-step-guide/"><u>Unlocking Read-Only Folders: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-page-denial-challenges/"><u>Overcoming Windows Page Denial Challenges</u></a></li>
<li><a href="https://win11.techidaily.com/leading-password-guardians-revolutionizing-windows-11-life/"><u>Leading Password Guardians Revolutionizing Windows 11 Life</u></a></li>
<li><a href="https://win11.techidaily.com/transformational-taskbar-update-windows-system-resources-in-view/"><u>Transformational Taskbar Update: Windows System Resources in View</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-power-ranking-10-highest-subscribers-on-youtube/"><u>In 2024, The Power Ranking  10 Highest Subscribers on YouTube</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-motorola-moto-g23-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Motorola Moto G23 online without jailbreak</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-nubia-z50s-pro-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-step-up-your-content-game-top-30-video-plans/"><u>In 2024, Step Up Your Content Game  Top 30 Video Plans</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-discover-the-best-free-wmv-video-editing-solutions/"><u>2024 Approved Discover the Best Free WMV Video Editing Solutions</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-realme-12-5g-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Realme 12 5G Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/realme-data-recovery-recover-lost-data-from-realme-11-proplus-by-fonelab-android-recover-data/"><u>Realme Data Recovery – recover lost data from Realme 11 Pro+</u></a></li>
<li><a href="https://review-topics.techidaily.com/huawei-nova-y71-won-t-play-hevc-h-265-media-how-to-fix-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Huawei Nova Y71 won’t play HEVC H.265 media, how to fix? </u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-meme-matrix-perfect-pratfalls-for-parties/"><u>[New] 2024 Approved  Meme Matrix  Perfect Pratfalls for Parties</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-enliven-youtube-images-a-burst-of-neon-flair/"><u>[New] Enliven YouTube Images  A Burst of Neon Flair</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>