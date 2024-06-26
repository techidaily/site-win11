---
title: Effortless Windows Temp File Deletion Guide
date: 2024-06-25T10:07:59.973Z
updated: 2024-06-26T10:07:59.973Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effortless Windows Temp File Deletion Guide
excerpt: This Article Describes Effortless Windows Temp File Deletion Guide
keywords: Delete Temp Files Easy,Quick Windows Cleanup,Free Temp File Removal,Safe Windows Trash Clearing,No-Fuss Temp Deletion,Instant Window Cache Purging,Simple Disk Cleanup Guide
thumbnail: https://thmb.techidaily.com/e24c6a589d856da0a108fb73ed8aea987528294a85122e6caa68a425ef40bc26.jpg
---

## Effortless Windows Temp File Deletion Guide

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

## 1\. Use the Disk Cleanup Tool

[Windows offers several options for clearing temporary files](http://www.makeuseof.com/windows-11-delete-temporary-files/) on your PC. If you are unable to delete temporary files via the Settings app or File Explorer, try using the Disk Cleanup tool instead.

 Here are the steps you can follow:

1. Press **Win + S** to access the search menu.
2. Type **disk cleanup** in the box and press **Enter**.
3. Use the drop-down menu to select the drive from which you want to clear temporary files.
4. Click **OK**.
5. Under **Files to delete**, use the checkboxes to select the files you want to remove.
6. Click **OK** to proceed.
7. Click the **Delete Files** to confirm.  
![Delete Temp Files Using Disk Cleanup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-disk-cleanup.jpg)

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

 Wait for the above command to run and delete the temporary files.

## 3\. Empty the SoftwareDistribution Folder

 Windows saves all the downloaded update files in the SoftwareDistribution folder before installing them. If a [Windows system update gets stuck](https://www.makeuseof.com/tag/windows-update-stuck/), the OS will not delete the temporary files associated with it.

 To fix this, you can try emptying the SoftwareDistribution folder manually using these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the box and press **Enter**.
3. In the Services window, locate the **Windows Update** service. Right-click on it and select **Stop**.
4. Press **Win + R** to open the Run dialog box.
5. Type the following path in the text field and hit **Enter**.  
C:\Windows\SoftwareDistribution\Download
6. In the File Explorer window, press **Ctrl + A** to select all the files and click the **trash icon** at the top to delete them.
7. Return to the Services window, right-click on the **Windows Update** service, and select **Start**.  
![Clear SoftwareDistribution Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/clear-softwaredistribution-folder.jpg)

 If you run into issues while emptying the SoftwareDistribution folder, you can [force delete files in Windows](https://www.makeuseof.com/windows-11-delete-stubborn-files/) using Command Prompt or a third-party tool.

## 4\. Edit Registry Files

 By default, the Disk Cleanup utility does not delete temporary files that are less than seven days old. This is because Windows marks these files as active. However, if you want to delete all the temporary files, regardless of their age, you can make changes to the Windows Registry.

 Since editing registry files is slightly risky, make sure to [back up all registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) as a precaution. Once done, follow these steps to edit registry files:

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Explorer > VolumeCaches > Temporary Files**.
5. In the right pane, double-click the **LastAccess** key.
6. Enter **0** in the Value data field.
7. Click **OK**.  
![Edit DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-dword-in-registry.jpg)

 Restart your PC after this and try to delete temporary files once again.

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/keep-your-file-explorer-running-with-helpful-windows-11-tricks/"><u>Keep Your File Explorer Running with Helpful Windows 11 Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-system-resources-through-edges-webview2-controls/"><u>Optimizing System Resources Through Edge's WebView2 Controls</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-9-methods-for-accessing-windows-11s-audio-control-panel/"><u>Navigate 9 Methods for Accessing Windows 11'S Audio Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/cross-platform-synchronization-for-ios-and-windows-calendars/"><u>Cross-Platform Synchronization for iOS & Windows Calendars</u></a></li>
<li><a href="https://win11.techidaily.com/saving-yourself-from-install-error-in-discord-set-up/"><u>Saving Yourself From Install Error in Discord Set-Up</u></a></li>
<li><a href="https://win11.techidaily.com/winexe-enhancement-convert-batch-to-powerful-formats/"><u>WinEXE Enhancement: Convert Batch to Powerful Formats</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-turn-off-auto-start-for-spotify/"><u>Guide to Turn Off Auto-Start for Spotify</u></a></li>
<li><a href="https://win11.techidaily.com/7-proven-methods-to-enhance-your-windows-11-experience/"><u>7 Proven Methods to Enhance Your Windows 11 Experience</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-a-peek-into-the-viral-world-of-stock-photo-memes/"><u>[Updated] 2024 Approved  A Peek Into the Viral World of Stock Photo Memes</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-the-social-image-hoarders-manual-a-guide-to-downloading-and-keeping-gif-images/"><u>In 2024, The Social Image Hoarder's Manual  A Guide to Downloading and Keeping GIF Images</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-ultimate-guide-to-removing-speech-from-recordings-using-adobe-audition-for-2024/"><u>New The Ultimate Guide to Removing Speech From Recordings Using Adobe Audition for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Motorola Moto G14 | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-zte-nubia-z60-ultra-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My ZTE Nubia Z60 Ultra Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-a-step-by-step-guide-to-perfecting-the-art-of-podcast-naming/"><u>[Updated] A Step-by-Step Guide to Perfecting the Art of Podcast Naming</u></a></li>
<li><a href="https://discord-videos.techidaily.com/enhance-your-discord-interaction-mastering-the-art-of-pins-for-2024/"><u>Enhance Your Discord Interaction  Mastering the Art of Pins for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/2024-approved-interested-in-adding-a-cinematic-strobe-light-effect-to-your-movie-or-video-title-follow-the-steps-explained-in-detail-here/"><u>2024 Approved Interested in Adding a Cinematic Strobe Light Effect to Your Movie or Video Title? Follow the Steps Explained in Detail Here</u></a></li>
<li><a href="https://extra-tips.techidaily.com/peaceful-playback-practices-for-pcos-users/"><u>Peaceful Playback Practices for PC/OS Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>