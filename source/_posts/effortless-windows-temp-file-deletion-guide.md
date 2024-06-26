---
title: Effortless Windows Temp File Deletion Guide
date: 2024-06-25T11:30:27.724Z
updated: 2024-06-26T11:30:27.724Z
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
<li><a href="https://win11.techidaily.com/opera-stuck-swift-solutions-for-a-smooth-windows-patch/"><u>Opera Stuck? Swift Solutions for a Smooth Windows Patch</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-classic-directx-games-with-dxvk-upgrades/"><u>Refreshing Classic DirectX Games with DXVK Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/determine-your-pcs-wattage-usage-on-windows-system/"><u>Determine Your PC's Wattage Usage on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-enhance-text-via-snip-tool-features/"><u>Step-by-Step: Enhance Text via Snip Tool Features</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-remote-desktop-failures-in-current-windows/"><u>Addressing Remote Desktop Failures in Current Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-uncover-gpo-settings/"><u>Mastering Windows: Uncover GPO Settings</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-n-a-comparative-study-for-it-pros/"><u>Unveiling Windows N: A Comparative Study for IT Pros</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-password-protectionists-for-the-modern-windows-user/"><u>Masterful Password Protectionists for the Modern Windows User</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-experience-with-these-ultimate-strategies-for-win-11/"><u>Elevate Your Gaming Experience with These Ultimate Strategies for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-most-impressive-windows-10-sketch-software-lineup/"><u>The Most Impressive Windows 10 Sketch Software Lineup</u></a></li>
<li><a href="https://extra-resources.techidaily.com/microsoft-azure-unlocking-speech-to-text-potential/"><u>Microsoft Azure  Unlocking Speech-to-Text Potential</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-additional-tips-about-sinnoh-stone-for-infinix-note-30-drfone-by-drfone-virtual-android/"><u>In 2024, Additional Tips About Sinnoh Stone For Infinix Note 30 | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-mastering-image-dimensions-how-to-calculate-the-perfect-ratio/"><u>New 2024 Approved Mastering Image Dimensions How to Calculate the Perfect Ratio</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/did-your-apple-iphone-se-passcode-change-itself-unlock-it-now-by-drfone-ios/"><u>Did Your Apple iPhone SE Passcode Change Itself? Unlock It Now</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-deciphering-hand-tracking-methodologies/"><u>In 2024, Deciphering Hand Tracking Methodologies</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-quick-hits-on-twittersphere-video-vanguard/"><u>In 2024, Quick Hits on Twittersphere  Video Vanguard</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-nokia-c12-pro-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Nokia C12 Pro Device</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-starry-nights-in-focus-advice-on-night-portraiture/"><u>[Updated] Starry Nights in Focus  Advice on Night Portraiture</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-larger-print-formats-same-sharpness-levels/"><u>2024 Approved  Larger Print Formats, Same Sharpness Levels</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-anonymous-sharing-simplified-blurring-techniques-for-videos/"><u>[New] In 2024, Anonymous Sharing Simplified  Blurring Techniques for Videos</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>