---
title: Mastering the Art of Cleaning Windows' Temporaries
date: 2024-12-15T16:54:00.740Z
updated: 2024-12-22T17:24:26.834Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Wait for the above command to run and delete the temporary files.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Rid of Temporary Files on Windows

 Clearing temporary files is a great way to free up storage space without deleting any of your apps or important data.

 We hope that one of the above tips was helpful and you were able to delete the temporary files without any problems.

 While temporary files are typically harmless, you may have your own reasons for deleting them. Here are some useful tips that should help remove any stubborn temporary files on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-accessing-global-hitters-the-1-6-short-video-downloaders/"><u>[Updated] 2024 Approved Accessing Global Hitters The #1-#6 Short Video Downloaders</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-unveiling-a-pros-approach-to-time-stamping-for-youtube-enthusiasts-for-2024/"><u>[Updated] Unveiling a Pro's Approach to Time Stamping for YouTube Enthusiasts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-windows-11-software-removal-primer-top-11-approaches-114-chars/"><u>A Windows 11 Software Removal Primer: Top 11 Approaches (114 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/adding-directories-to-your-windows-11-quick-access-menu/"><u>Adding Directories to Your Windows 11 Quick Access Menu</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-incompatible-format-in-windows-vlc-error/"><u>Addressing Incompatible Format in Windows VLC Error</u></a></li>
<li><a href="https://win11.techidaily.com/adjust-your-window-to-wins-cli-default-actions/"><u>Adjust Your Window to Win's CLI: Default Actions</u></a></li>
<li><a href="https://win11.techidaily.com/app-elegance-overlooked-as-they-deplete-your-pcs-power/"><u>App Elegance Overlooked as They Deplete Your PC's Power</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-rdc-usability-in-the-latest-os/"><u>Boosting RDC Usability in the Latest OS</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windowss-perplexing-pink-problems/"><u>Breaking Down WINDOWS's Perplexing Pink Problems</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ing-the-core-contrasts-between-youtube-and-dailymention/"><u>Decoding the Core Contrasts Between YouTube and DailyMention</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Motorola Edge 40? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-nokia-c32-drfone-by-drfone-virtual-android/"><u>In 2024, Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/phantom-3-vs-phantom-4-complete-comparison-for-2024/"><u>Phantom 3 Vs. Phantom 4 Complete Comparison for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/public-melodies-for-calmness/"><u>Public Melodies for Calmness</u></a></li>
<li><a href="https://win11-tips.techidaily.com/redesign-windows-11-for-an-echo-of-the-90s/"><u>Redesign Windows 11 for an Echo of the 90S</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-anthems-persistent-boot-hurdle-issue/"><u>Resolving Anthem's Persistent Boot Hurdle Issue</u></a></li>
<li><a href="https://win11.techidaily.com/1719285802254-say-goodbye-to-troubleshooting-woes-on-vistawindows-7/"><u>Say Goodbye to Troubleshooting Woes on Vista/Windows 7.</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    