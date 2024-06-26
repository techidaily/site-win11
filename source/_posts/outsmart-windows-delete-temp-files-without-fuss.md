---
title: "Outsmart Windows: Delete Temp Files Without Fuss"
date: 2024-06-25T09:50:46.718Z
updated: 2024-06-26T09:50:46.718Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Outsmart Windows: Delete Temp Files Without Fuss"
excerpt: "This Article Describes Outsmart Windows: Delete Temp Files Without Fuss"
keywords: Deleting TempFiles Easy,Uninstall Windows Carelessly,Eliminate System Junk,Bypass Windows Trash,Clear TempSpace Hassle-Free,Erase Files No Fuss,Forget Temp Waste Quickly
thumbnail: https://thmb.techidaily.com/2a29084ef28c5d6ebf693615660d627bf6405cc5a8ac614e41f7b335143de3df.jpg
---

## Outsmart Windows: Delete Temp Files Without Fuss

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
<li><a href="https://win11.techidaily.com/understanding-windows-aggregatorhostexe-functions-and-safe-practices/"><u>Understanding Windows' AggregatorHost.exe: Functions & Safe Practices</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-secrets-of-windows-11s-app-collection/"><u>Unveiling the Secrets of Windows 11'S App Collection</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-recovery-mode-on-microsoft-devices/"><u>Accessing Recovery Mode on Microsoft Devices</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-windows-error-0x80073d26/"><u>Unraveling the Mystery of Windows' Error 0X80073D26</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-beginners-guide-to-github-desktop-for-windows-users/"><u>A Compreenas Beginners Guide to GitHub Desktop for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-n-series-pros-and-cons/"><u>Deciphering Windows N Series: Pros & Cons</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-samsung-flow-linking-winpc-and-galaxy-device/"><u>Mastering Samsung Flow: Linking WinPC & Galaxy Device</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-remedying-install-fail-in-wins-discord-setup/"><u>Understanding and Remedying Install Fail in Win's Discord Setup</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-strategies-for-effective-use-of-classroom-media-for-2024/"><u>[New] Strategies for Effective Use of Classroom Media for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-cultivating-the-culture-of-creativity-within-youtube-shorts-for-2024/"><u>[Updated] Cultivating the Culture of Creativity Within YouTube Shorts for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-understanding-googles-audio-streaming-service-a-guide-to-the-podcast-application/"><u>In 2024, Understanding Googles Audio Streaming Service A Guide to the Podcast Application</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-mdm-on-iphone-6s-with-ease-via-third-tools-by-drfone-ios-unlock-ios-unlock/"><u>How to Bypass MDM on iPhone 6s with Ease Via third Tools?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-building-brand-presence-a-guide-to-planning-instagram-videos/"><u>[Updated] 2024 Approved  Building Brand Presence  A Guide to Planning Instagram Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/1716069407985-new-in-2024-how-to-manual-for-creating-an-inclusive-and-productive-skype-chat-room-accessible-by-both-windows-and-mac-users/"><u>[New] In 2024, How-To Manual for Creating an Inclusive and Productive Skype Chat Room Accessible by Both Windows & Mac Users.</u></a></li>
<li><a href="https://android-unlock.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-lava-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Lava Fingerprint Lock</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-bridging-devices-friend-up-with-discord/"><u>[New] In 2024, Bridging Devices  Friend Up with Discord</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-kickstart-your-film-journey-essential-camera-shot-knowledge/"><u>[Updated] Kickstart Your Film Journey  Essential Camera Shot Knowledge</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>