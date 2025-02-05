---
title: Mastering the Art of Cleaning Windows' Temporaries
date: 2025-01-28T05:04:09.572Z
updated: 2025-02-03T19:52:06.178Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Wait for a few moments until the Disk Cleanup tool clears all the temporary files.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Use Command Prompt

 If the Disk Cleanup utility fails to delete some or all of the temporary files on Windows, you can try using the Command Prompt instead. Don’t worry, the process isn’t as complex as it might sound.

 Follow these steps to continue:

1. Right-click on the **Start icon** and select **Terminal (Admin)** from the list.
2. Select **Yes** when the User Account Control (UAC) prompt appears.
3. Copy and paste the following command into the console and hit **Enter**.  
del /q /f /s %temp%\* && del /s /q C:\Windows\temp\*  
![Delete Temp Files Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-temp-files-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC after this and try to delete temporary files once again.

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-blue.techidaily.com/new-decoding-the-art-of-iphones-and-podcasts-downloading/"><u>[New] Decoding the Art of iPhones and Podcasts Downloading</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-expert-tips-for-safaris-picture-and-window-sharing-feature/"><u>[New] Expert Tips for Safari's Picture and Window Sharing Feature</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-transforming-youtube-content-using-the-power-of-imovie/"><u>2024 Approved Transforming YouTube Content Using the Power of iMovie</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-effect-of-disabling-windows-11s-taskbar-chat-on-users/"><u>Decoding The Effect Of Disabling Windows 11'S Taskbar Chat on Users</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-and-fixing-the-application-couldnt-start-error-code/"><u>Dissecting and Fixing The Application Couldn't Start Error Code</u></a></li>
<li><a href="https://tech-hub.techidaily.com/elevating-chatgpt-explore-how-custom-gpt-models-deliver-breakthrough-performance/"><u>Elevating ChatGPT: Explore How Custom GPT Models Deliver Breakthrough Performance</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/exploring-the-world-of-computer-components-with-toms-hardware/"><u>Exploring the World of Computer Components with Tom's Hardware</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-your-graphics-driver-on-windows-11-and-11/"><u>How to Reset Your Graphics Driver on Windows 11 & 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ideal-steadicams-for-captivating-high-quality-shoots-on-your-dslr-camera/"><u>Ideal Steadicams for Captivating, High-Quality Shoots on Your DSLR Camera</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-oneplus-open-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track OnePlus Open without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-full-tutorial-to-bypass-your-poco-x6-pro-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Poco X6 Pro Face Lock?</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-optimizedusageofyourwebcamrecorder/"><u>In 2024, OptimizedUsageOfYourWebcamRecorder</u></a></li>
<li><a href="https://win11.techidaily.com/old-play-new-display-channeling-vintage-games-to-windows-11-folder/"><u>Old Play, New Display: Channeling Vintage Games to Windows 11 Folder</u></a></li>
<li><a href="https://win11.techidaily.com/solving-msvcr120dll-absence-in-windows-systems/"><u>Solving MSVCR120.dll Absence in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/staying-chill-while-playing-top-laptop-heat-management-strategies/"><u>Staying Chill While Playing: Top Laptop Heat Management Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-pcs-potential-tackling-servers-issues/"><u>Unlocking PC's Potential: Tackling Servers Issues</u></a></li>
<li><a href="https://win11.techidaily.com/workaround-for-ignoring-protected-windows-app-block/"><u>Workaround for Ignoring Protected Windows App Block</u></a></li>
</ul></div>

