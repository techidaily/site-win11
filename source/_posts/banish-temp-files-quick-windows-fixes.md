---
title: "Banish Temp Files: Quick Windows Fixes"
date: 2024-07-13T11:23:59.931Z
updated: 2024-07-14T11:23:59.931Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Banish Temp Files: Quick Windows Fixes"
excerpt: "This Article Describes Banish Temp Files: Quick Windows Fixes"
keywords: Temp File Removal Guide,Windows Cleanup Tips,Eliminate Temporary Data,Speed Up System Startup,Quick Files Deletion Steps,Optimize Windows Performance,Erase Unwanted System Cache
thumbnail: https://thmb.techidaily.com/1b9c0ec4aac0a389de35bac2a472d37b33435d994c1a8448795d8b564ff658a3.jpg
---

## Banish Temp Files: Quick Windows Fixes

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
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-the-ultimate-guide-overlaying-photos-digitally/"><u>[Updated] In 2024, The Ultimate Guide  Overlaying Photos Digitally</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-unlocking-facebooks-potential-with-top-video-strategies/"><u>[New] In 2024, Unlocking Facebook's Potential with Top Video Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-11-security-upgrading-pin-length/"><u>Boosting Windows 11 Security: Upgrading PIN Length</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-ordinary-displays-elevate-your-screen-with-customized-themes-on-win11/"><u>Beyond Ordinary Displays: Elevate Your Screen with Customized Themes on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/begin-your-windows-journey-with-a-voice-guide/"><u>Begin Your Windows Journey with a Voice Guide</u></a></li>
<li><a href="https://win11.techidaily.com/awakening-obscured-windows-11-query-engine/"><u>Awakening Obscured Windows 11 Query Engine</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-digital-dynamo-the-most-retweeted-tweets-capturing-attention/"><u>2024 Approved  Digital Dynamo  The Most Retweeted Tweets Capturing Attention</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-nubia-red-magic-9-proplus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Nubia Red Magic 9 Pro+ | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-11-taskbar-efficiency/"><u>Boosting Windows 11 Taskbar Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/banish-stubborn-epic-launcher-guide-for-win-11-users/"><u>Banish Stubborn Epic Launcher: Guide for Win 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/automating-printer-removal-on-win11-devices/"><u>Automating Printer Removal on Win11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/break-through-windows-barriers-be-an-admin-now/"><u>Break Through Windows Barriers - Be an Admin Now</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/apparition-camera-control-workshop/"><u>Apparition Camera Control Workshop</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-displaying-notifications-of-phone-link-app-on-pc/"><u>Addressing Non-Displaying Notifications of Phone Link App on PC</u></a></li>
<li><a href="https://win11.techidaily.com/best-ways-to-restore-default-window-options-on-system-startup/"><u>Best Ways to Restore Default Window Options on System Startup</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-connection-dropouts-with-steam-remote/"><u>Addressing Connection Dropouts with Steam Remote</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-1011-how-to-bypass-pin-locks/"><u>Breaking Down Windows 10/11: How to Bypass PIN Locks</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-conflict-over-shared-device-camera-error-0xa00f4243/"><u>Avoiding Conflict Over Shared Device (Camera, Error 0xA00F4243)</u></a></li>
<li><a href="https://win11.techidaily.com/beating-blue-screens-a-guide-to-system-recovery/"><u>Beating Blue Screens: A Guide to System Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-ide-performance-android-studio-tips/"><u>Accelerating IDE Performance: Android Studio Tips</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-system-speed-implementing-a-smart-enhanced-run-feature/"><u>Boosting System Speed: Implementing a Smart Enhanced Run Feature</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-bug-fixing-windows-scheduler-failures/"><u>Beat the Bug: Fixing Windows Scheduler Failures</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-pc-wins-best-performance-fixes-ranked/"><u>Boost Your PC: Win's Best Performance Fixes Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/asuss-innovation-unleashed-exploring-s15-oled-and-bape-edition/"><u>Asus's Innovation Unleashed: Exploring S15 OLED and BAPE Edition</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-realme-narzo-60-5g-to-mac-drfone-by-drfone-android/"><u>How to Mirror Realme Narzo 60 5G to Mac? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boost-windows-performance-and-functionality-via-improved-run-toolset/"><u>Boost Windows Performance and Functionality via Improved Run Toolset</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-size-limit-snag-in-discord-windows-11-edition/"><u>Breaking Free From the Size Limit Snag in Discord (Windows 11 Edition)</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/securing-financial-stability-through-beauty-content/"><u>Securing Financial Stability Through Beauty Content</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/streamlining-your-device-by-clearing-youtube-downloads-for-2024/"><u>Streamlining Your Device by Clearing YouTube Downloads for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-monitors-brightness-with-top-software-select/"><u>Boosting Windows Monitors' Brightness with Top Software Select</u></a></li>
<li><a href="https://win11.techidaily.com/boltgun-performance-tips-to-resolve-on-pc-interruptions/"><u>Boltgun Performance Tips to Resolve On-PC Interruptions</u></a></li>
<li><a href="https://printer-issues.techidaily.com/unraveling-the-mystery-printer-works-after-win-10-patch/"><u>Unraveling the Mystery: Printer Works After Win 10 Patch</u></a></li>
<li><a href="https://win11.techidaily.com/becoming-an-admin-in-windows-control-settings/"><u>Becoming an Admin in Windows Control Settings</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-oppo-reno-11f-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-audio-5-ways-for-above-100-output-on-pcs/"><u>Boosting Audio: 5 Ways for Above-100%% Output on PCs</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-the-best-websites-to-reverse-videos-online/"><u>2024 Approved The Best Websites to Reverse Videos Online</u></a></li>
<li><a href="https://win11.techidaily.com/best-fit-choosing-the-perfect-vms-for-your-windows-11-pc/"><u>Best Fit: Choosing the Perfect VMs for Your Windows 11 PC</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-techniques-to-overcome-blackout-during-obs-fullscreen/"><u>[New] 2024 Approved  Techniques to Overcome Blackout During OBS Fullscreen</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-novelties-the-next-gen-of-windows-11/"><u>Beyond Novelties: The Next Gen of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-top-7-tips-for-mastering-windows-11-49/"><u>Boosting Productivity: Top 7 Tips for Mastering Windows 11 (49)</u></a></li>
<li><a href="https://win11.techidaily.com/blackview-mp60-mini-pc-expandable-storage-but-unremarkable-performance/"><u>Blackview MP60 Mini PC: Expandable Storage but Unremarkable Performance</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>