---
title: Mastering the Art of Cleaning Windows' Temporaries
date: 2024-12-30T17:07:31.296Z
updated: 2025-01-06T20:05:58.683Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Cleaning Windows' Temporaries
excerpt: This Article Describes Mastering the Art of Cleaning Windows' Temporaries
keywords: Window Cleaning Tips,Clearing Temporary Streaks,Efficient Glass Washing,Drying Windows Safely,Removing Smudges Quickly,Spotless Window Care,Stainless Window Shine
thumbnail: https://thmb.techidaily.com/8eb93e1b1b19fd0df7a5c4a69b010fd291b98c2d5042e30f7996e1ded01bfda5.jpg
---

## Mastering the Art of Cleaning Windows' Temporaries

 Temporary files, as the name implies, aren’t meant to stick around on your Windows computer forever. Although Windows makes it simple to delete temporary files, there can be times when these files refuse to leave.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC after this and try to delete temporary files once again.

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-http.techidaily.com/new-ffmpeg-analysis-maintaining-audio-format-integrity/"><u>[New] FFmpeg Analysis Maintaining Audio Format Integrity</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-pioneering-sustainability-transforming-metropolitan-environments/"><u>[Updated] In 2024, Pioneering Sustainability Transforming Metropolitan Environments</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-tool-for-video-cuts-full-review-of-vivacut-24-edition/"><u>[Updated] The Ultimate Tool for Video Cuts Full Review of VivaCut '24 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-access-denied-phenomenon/"><u>Demystifying Windows' 'Access Denied' Phenomenon</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-iphone-12s-latest-feature-improved-qi-charging-that-works-without-magsafe-news/"><u>Discover iPhone 12'S Latest Feature: Improved Qi Charging that Works without MagSafe News</u></a></li>
<li><a href="https://win11.techidaily.com/effective-methods-to-correct-post-update-malfunctions/"><u>Effective Methods to Correct Post-Update Malfunctions</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-msvcr120dll-absence-errors-on-pc/"><u>Essential Fixes for 'Msvcr120_dll' Absence Errors on PC</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-samsung-galaxy-xcover-7-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Samsung Galaxy XCover 7 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/linux-uncomplicated-without-wsl/"><u>Linux Uncomplicated, Without WSL</u></a></li>
<li><a href="https://win11.techidaily.com/master-linux-development-top-wsl-2-tips-for-windows-oses/"><u>Master Linux Development: Top WSL 2 Tips for Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-challenges-of-a-non-working-windows-notepad/"><u>Overcoming the Challenges of a Non-Working Windows Notepad</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-realme-12-pro-5g-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Realme 12 Pro 5G to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-windows-productivity-tools-a-to-do-guide/"><u>Top 6 Windows Productivity Tools: A To-Do Guide</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-from-clip-to-cohesive-mastering-color-in-fcp/"><u>Updated In 2024, From Clip to Cohesive Mastering Color in FCP</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/zdnet-unveils-clues-to-apples-upcoming-iphone-revolution-through-their-latest-acquisition-signaling-a-leap-towards-ai-integration/"><u>ZDNet Unveils Clues to Apple's Upcoming iPhone Revolution Through Their Latest Acquisition, Signaling a Leap Towards AI Integration</u></a></li>
</ul></div>

