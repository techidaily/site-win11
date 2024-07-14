---
title: Effortless Windows Temp File Deletion Guide
date: 2024-07-13T10:14:04.841Z
updated: 2024-07-14T10:14:04.841Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/stop-recurring-file-explorer-autoload/"><u>Stop Recurring File Explorer Autoload</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-rectifying-bluetooth-pin-related-disconnects/"><u>Mastering the Art of Rectifying Bluetooth PIN-Related Disconnects</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-ms-paint-within-windows-11/"><u>Initiating MS Paint Within Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentiality-of-runtime-brokers-for-modern-os-functionality/"><u>The Essentiality of Runtime Brokers for Modern OS Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-install-fail-in-wins-discord-setup/"><u>Understanding and Remedying Install Fail in Win's Discord Setup</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-flawless-filming-ipad-timelapse-techniques/"><u>[Updated] In 2024, Flawless Filming  IPad Timelapse Techniques</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-laughs-in-a-click-building-hilarious-memes/"><u>[New] Laughs in a Click  Building Hilarious Memes</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-failed-security-codes-in-game-launcher-windows-edition/"><u>Quick Fixes for Failed Security Codes in Game Launcher Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/1719293621682-mastering-wwinplusprint-functionality-fixes-for-non-operational-printer-on-pc/"><u>Mastering WWin+Print Functionality: Fixes for Non-Operational Printer on PC.</u></a></li>
<li><a href="https://win11.techidaily.com/win11-terminal-reset-procedure-essentials/"><u>Win11 Terminal Reset Procedure Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/experts-choice-10-error-finder-apps-for-pc/"><u>Expert's Choice: 10 Error Finder Apps for PC</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-revolutionize-your-obs-studio-videos-best-practices/"><u>[Updated] Revolutionize Your OBS Studio Videos  Best Practices</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-correcting-windows-store-failures-error-x80072f30-guide/"><u>Swiftly Correcting Windows Store Failures: Error X80072F30 Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-socialsnatcher-grab-and-save-twitter-vids-in-a-flash/"><u>[Updated] In 2024, SocialSnatcher  Grab and Save Twitter Vids in a Flash</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-file-management-with-collective-windows-11-folder-making/"><u>Revolutionize File Management with Collective Windows 11 Folder Making</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-winerror-with-code-0x8019/"><u>Resolving WinError with Code 0X8019</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-inoperative-windows-11-speech-recognition/"><u>Resolving Inoperative Windows 11 Speech Recognition</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-fixes-for-non-operational-voice-command-in-win11/"><u>Unveiling Fixes for Non-Operational Voice Command in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-handle-out-of-space-files-warning/"><u>How to Handle Out of Space Files Warning</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-error-x70-on-windows-file-and-folder-restoration-guide/"><u>Eradicating Error X70 on Windows: File and Folder Restoration Guide</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-overcoming-windows-11s-rename-limitations/"><u>Essential Fixes: Overcoming Windows 11'S Rename Limitations</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-absence-of-battery-life-duration-in-pcs-running-win-11/"><u>Overcoming the Absence of Battery Life Duration in PCs Running Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-end-persistent-login-error-alerts-on-pc/"><u>Methods to End Persistent Login Error Alerts on PC</u></a></li>
<li><a href="https://win11.techidaily.com/the-starting-line-in-diablo-basic-play-wisdom/"><u>The Starting Line in Diablo: Basic Play Wisdom</u></a></li>
<li><a href="https://win11.techidaily.com/windowed-wonders-enhance-windows-11-explorer-visibility/"><u>Windowed Wonders: Enhance Windows 11 Explorer Visibility</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-amd-graphics-driver-updates-in-the-windows-ecosystem/"><u>Mastery of AMD Graphics Driver Updates in the Windows Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-voice-and-music-from-bluetooth-headset/"><u>Troubleshooting Windows: Voice & Music From Bluetooth Headset</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-vectors-decoded-for-newbies-diverse-forms-and-tool-options/"><u>2024 Approved  Vectors Decoded for Newbies  Diverse Forms and Tool Options</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-verdict-on-video-clips-a-deep-dive-into-inshots-performance/"><u>[New] The Verdict on Video Clips  A Deep Dive Into InShot's Performance</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-personalizing-your-desktop-with-widgets/"><u>Mastering Window 11: Personalizing Your Desktop with Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/toolbox-tutorial-windows-core-components-management/"><u>Toolbox Tutorial: Windows' Core Components Management</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-restart-file-explorer-in-windows-10-and-11/"><u>4 Ways to Restart File Explorer in Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-preventing-heat-in-w11-systems/"><u>Essential Steps for Preventing Heat in W11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/beginning-your-art-with-ms-paint-windows-11-way/"><u>Beginning Your Art with MS Paint - Windows 11 Way</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-incorporation-of-virtual-gaming-archives-into-playnite-on-pc/"><u>Seamless Incorporation of Virtual Gaming Archives Into Playnite on PC</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windowsstore-directory-secrets-for-users/"><u>Unveiling WindowsStore Directory Secrets for Users</u></a></li>
<li><a href="https://win11.techidaily.com/improving-performance-managing-memory-usage-for-connected-services/"><u>Improving Performance: Managing Memory Usage for Connected Services</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-technique-how-to-execute-a-clean-boot-on-windows-11/"><u>The Ultimate Technique: How to Execute a Clean Boot on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-recording-techniques-gaming-screen-captures-with-intel/"><u>Advanced Recording Techniques: Gaming Screen Captures with Intel</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11s-unidentified-usb-port-problems/"><u>Overcoming Windows 11'S Unidentified USB Port Problems</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-correcting-unresponsive-video-files/"><u>Tips for Correcting Unresponsive Video Files</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-capturing-screen-content-via-built-in-recorders-in-the-mate-and-p-series/"><u>2024 Approved  Capturing Screen Content via Built-In Recorders in the Mate and P Series</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-the-ultimate-list-of-free-video-cutter-and-joiner-software-for-beginners/"><u>New 2024 Approved The Ultimate List of Free Video Cutter and Joiner Software for Beginners</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-channel-triumphs-with-trending-hashtags/"><u>2024 Approved  Channel Triumphs with Trending Hashtags</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-slashing-dropbox-cpu-load-on-windows-devices/"><u>Solutions for Slashing Dropbox CPU Load on Windows Devices</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For OnePlus 11 5G | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-easily-record-lenovo-laptop-screen-activity/"><u>[New] 2024 Approved  Easily Record Lenovo Laptop Screen Activity</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-swiftly-address-roblox-error-262/"><u>How to Swiftly Address Roblox Error 262</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-xiaomi-14-ultra-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Xiaomi 14 Ultra.</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-rectify-predominant-windows-anydesk-mishaps/"><u>Essential Steps to Rectify Predominant Windows AnyDesk Mishaps</u></a></li>
</ul></div>
