---
title: Reverting System Backups to Standard Configurations
date: 2024-06-25T10:07:33.392Z
updated: 2024-06-26T10:07:33.392Z
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
<li><a href="https://win11.techidaily.com/techniques-to-address-code-3-error-in-nvidia-opengl-win1011/"><u>Techniques to Address Code 3 Error in Nvidia OpenGL (Win10/11)</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-your-windows-experience-adding-contextual-items/"><u>Upgrading Your Windows Experience: Adding Contextual Items</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-windows-clippy-with-compatibility-fixes/"><u>Revamp Windows Clippy with Compatibility Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/diminish-windows-volume-amplification-effects/"><u>Diminish Windows Volume Amplification Effects</u></a></li>
<li><a href="https://win11.techidaily.com/steering-clear-of-fullscreen-failures-with-sonic-adventure-w11-edition/"><u>Steering Clear of Fullscreen Failures with Sonic Adventure, W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/yearly-best-offer-buy-now-at-612-for-eternal-win10-life/"><u>Yearly Best Offer: Buy Now at $6.12 for Eternal Win10 Life</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-synapse-glitches-in-1011-windows-edition/"><u>Repairing Synapse Glitches in 10/11 Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-missed-emotions-easy-emoji-15-integration-for-win11/"><u>Avoid Missed Emotions: Easy Emoji 15 Integration for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/dispel-limitations-escalating-internet-speed-past-100mbps-in-windows/"><u>Dispel Limitations: Escalating Internet Speed Past 100Mbps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/beginning-your-art-with-ms-paint-windows-11-way/"><u>Beginning Your Art with MS Paint - Windows 11 Way</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-breeze-be-gone-cutting-edge-techniques-to-purge-wind-interference-in-audio-streams/"><u>2024 Approved Breeze Be Gone Cutting-Edge Techniques to Purge Wind Interference in Audio Streams</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-ios-screen-recording-a-no-nonsense-approach-for-2024/"><u>[New] IOS Screen Recording  A No-Nonsense Approach for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/tiktok-mayhem-the-hottest-10-unusual-game-picks-for-2024/"><u>TikTok Mayhem  The Hottest 10 Unusual Game Picks for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/innovative-av-producers-the-ultimate-web-watchlist-for-2024/"><u>Innovative AV Producers  The Ultimate Web Watchlist for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-snapshot-hits-must-have-filters-to-enhance-your-snap/"><u>[Updated] 2024 Approved  Snapshot Hits  Must-Have Filters to Enhance Your Snap</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/detailed-insights-into-youtubes-perfected-aspect-ratios/"><u>Detailed Insights Into YouTube's Perfected Aspect Ratios</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-unlock-the-power-of-polyphonic-automation-in-audacity-with-free-plugins/"><u>New 2024 Approved Unlock the Power of Polyphonic Automation in Audacity with Free Plugins</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-guide-to-sierras-icloud-drives-and-shares/"><u>The Ultimate Guide to Sierra's iCloud Drives & Shares</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-vivo-y100t-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Vivo Y100t without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-go-from-gaming-to-socializing-streaming-xbox-to-fb-live/"><u>2024 Approved  Go From Gaming to Socializing  Streaming Xbox to FB Live</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>