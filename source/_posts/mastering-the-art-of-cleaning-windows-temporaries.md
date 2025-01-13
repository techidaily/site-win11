---
title: Mastering the Art of Cleaning Windows' Temporaries
date: 2025-01-12T10:08:11.288Z
updated: 2025-01-13T02:37:08.892Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Wait for the above command to run and delete the temporary files.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Restart your PC after this and try to delete temporary files once again.

## 5\. Boot Into Safe Mode

 It's possible that a third-party program or background service is preventing Windows from erasing temporary files on your system. Booting your PC in safe mode can help you avoid any interference, as Windows will only run with essential drivers and services.

 Use one of the many ways to [boot into safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) and try to delete temporary files one more time.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-posts.techidaily.com/new-2024-approved-devices-needed-for-documenting-trips/"><u>[New] 2024 Approved Devices Needed for Documenting Trips</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-high-revenue-video-visionaries/"><u>[New] In 2024, High-Revenue Video Visionaries</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-exploring-platform-variations-youtube-vs-dailymention/"><u>[Updated] 2024 Approved Exploring Platform Variations YouTube Vs. DailyMention</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-quick-fit-enhance-your-photo-posts-with-automated-mac-video-scaling/"><u>[Updated] In 2024, Quick Fit Enhance Your Photo Posts with Automated Mac Video Scaling</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-tips-for-enhanced-dns-configuration-in-windows-11/"><u>Cutting-Edge Tips for Enhanced DNS Configuration in Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/fix-nokia-xr21-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Nokia XR21 Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-realme-12-5g-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Realme 12 5G | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-install-voice-assistant-powered-chatgpt-on-your-android-device-with-voicegpt-app/"><u>How to Install Voice Assistant Powered ChatGPT on Your Android Device with VoiceGPT App</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-program-resizing-techniques-via-pc-keys-on-windows-11/"><u>Mastering Program Resizing Techniques via PC Keys on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-file-management-tools-enhancements/"><u>Mastering Windows File Management Tools Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/method-for-ceasing-copilot-functionality/"><u>Method for Ceasing Copilot Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-to-find-wordpad/"><u>Navigating Through Windows to Find WordPad</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-windows-experience-overcome-incompatibilities-now/"><u>Revolutionize Windows Experience: Overcome Incompatibilities Now!</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/rising-sea-levels-are-not-just-coastal-concerns/"><u>Rising Sea Levels Are Not Just Coastal Concerns</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-chrome-on-windows-11-with-ease/"><u>Setting Up Chrome on Windows 11 with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-reversing-roblox-software-failures/"><u>Techniques for Reversing Roblox Software Failures</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://solve-howtos.techidaily.com/ultimate-tutorial-mastering-optical-media-burning-using-yls-windows-tools/"><u>Ultimate Tutorial: Mastering Optical Media Burning Using YL's Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-your-full-potential-the-ultimate-windows-productivity-pack/"><u>Unleash Your Full Potential: The Ultimate Windows Productivity Pack</u></a></li>
</ul></div>

