---
title: "Optimize Disk Space: Clear Temporary Windows Files Now!"
date: 2024-07-13T11:08:07.938Z
updated: 2024-07-14T11:08:07.938Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Optimize Disk Space: Clear Temporary Windows Files Now!"
excerpt: "This Article Describes Optimize Disk Space: Clear Temporary Windows Files Now!"
keywords: Optimize Disk Usage,Delete Temp Files,Free Up Storage,Clear Cache Data,Speedup Computer,Unclutter System,Reduce RAM Use
thumbnail: https://thmb.techidaily.com/bdbc1bb211547c18c849de30d5eb74ca5d67d9e0fc552f041d0a6f6f88d073bb.jpg
---

## Optimize Disk Space: Clear Temporary Windows Files Now

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
<li><a href="https://win11.techidaily.com/4-ways-to-run-the-program-compatibility-troubleshooter-on-windows/"><u>4 Ways to Run the Program Compatibility Troubleshooter on Windows</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-supreme-seminar-strategist-summit/"><u>[New] Supreme Seminar Strategist Summit</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-outlook-preview-setup-on-windows-11/"><u>A Comprehensive Guide to Outlook Preview Setup on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/8-things-to-remember-before-you-clean-install-windows/"><u>8 Things to Remember Before You Clean Install Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719380925919-keyboard-woes-tackle-win10-key-problems-now/"><u>Keyboard Woes? Tackle WIN10 Key Problems Now</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-inaccessible-screen-resolution-settings-on-windows/"><u>8 Ways to Fix Inaccessible Screen Resolution Settings on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719358387590-troubleshoot-frozen-shift-key-on-pc/"><u>Troubleshoot Frozen Shift Key on PC.</u></a></li>
<li><a href="https://win11.techidaily.com/7-essential-steps-overcome-windows-update-setbacks/"><u>7 Essential Steps: Overcome Windows Update Setbacks</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-samsung-galaxy-z-flip-5-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Samsung Galaxy Z Flip 5? | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-snapchats-visual-language-mastering-the-art-of-gifting-with-gifs-for-2024/"><u>[Updated] Snapchat's Visual Language  Mastering the Art of Gifting with Gifs for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/first-moments-that-foster-interest-in-audios-for-2024/"><u>First Moments that Foster Interest in Audios for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-workflow-fine-tuning-mouse-clicks/"><u>Accelerate Your Workflow: Fine-Tuning Mouse Clicks</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/surpassing-peers-standing-out-in-the-vimeo-staffs-choices-for-2024/"><u>Surpassing Peers  Standing Out in the Vimeo Staff's Choices for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-tips-for-youtube-thumbnail-size-aspect-ratio-included/"><u>2024 Approved  Tips for YouTube Thumbnail Size [Aspect Ratio Included]</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-steam-download-rates-overcoming-sluggish-pace/"><u>Accelerate Steam Download Rates: Overcoming Sluggish Pace</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-master-pip-feature-while-consuming-youtube-videos-on-iphones/"><u>In 2024, Master PIP Feature While Consuming YouTube Videos on iPhones</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-open-the-file-or-folder-properties-in-windows/"><u>6 Ways to Open the File or Folder Properties in Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-prime-drone-selections-to-enhance-gopro-videos/"><u>[Updated] Prime Drone Selections to Enhance GoPro Videos</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-best-samsung-galaxy-a25-5g-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Samsung Galaxy A25 5G Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-rectify-a-wrongly-setup-temp-folder-in-win11/"><u>A Step-by-Step Guide to Rectify a Wrongly Setup Temp Folder in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/a-window-to-creativity-best-drawing-apps-for-win10/"><u>A Window to Creativity: Best Drawing Apps for Win10</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/expert-recommendations-the-finest-skype-recorders-of-2023/"><u>Expert Recommendations  The Finest Skype Recorders of 2023</u></a></li>
<li><a href="https://win11.techidaily.com/5-early-warnings-to-consider-windows-restart/"><u>5 Early Warnings to Consider Windows Restart</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-allstream-worldwide-selective-local-channel-selection/"><u>[Updated] AllStream Worldwide  Selective Local Channel Selection</u></a></li>
<li><a href="https://win11.techidaily.com/a-windows-users-guide-for-web-site-app-conversion/"><u>A Windows User's Guide for Web Site App Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/1719370883063-master-compatibility-fixes-without-the-troubleshooter/"><u>Master Compatibility Fixes Without the Troubleshooter.</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/stream-perfecting-tweets-with-correct-video-formats/"><u>Stream-Perfecting Tweets with Correct Video Formats</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-quickly-opens-sticky-notes-in-windows-11/"><u>A Guide to Quickly Opens Sticky Notes in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-microsoft-should-improve-the-windows-11-taskbar/"><u>6 Ways Microsoft Should Improve the Windows 11 Taskbar</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-proven-hashtags-for-youtube-audience-surge/"><u>In 2024, Proven #Hashtags for YouTube Audience Surge</u></a></li>
<li><a href="https://win11.techidaily.com/7-techniques-to-lower-desktop-wm-energy-usage/"><u>7 Techniques to Lower Desktop WM Energy Usage</u></a></li>
<li><a href="https://win11.techidaily.com/a-deeper-dive-into-group-policies-with-the-gpresult-command/"><u>A Deeper Dive Into Group Policies with the GPResult Command</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-repair-the-net-framework-on-windows/"><u>5 Ways to Repair the .NET Framework on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719361199591-navigating-and-fixing-non-operational-printer-feature-via-wwinplusp-in-windows/"><u>Navigating and Fixing Non-Operational Printer Feature via WWin+P in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-layer-of-simplicity-in-windows-photos-app-deletion/"><u>A New Layer of Simplicity in Windows Photos App Deletion</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-smart-choices-the-ultimate-list-of-educator-friendly-recording-tools/"><u>[New] In 2024, Smart Choices  The Ultimate List of Educator-Friendly Recording Tools</u></a></li>
<li><a href="https://win11.techidaily.com/1719348593153-conquer-non-compatibilities-easy-steps-for-windows-xp-users/"><u>Conquer Non-Compatibilities: Easy Steps for Windows XP Users.</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-ig-beats-unleashed-an-insiders-guide-to-music-integration/"><u>[Updated] IG Beats Unleashed  An Insider’s Guide to Music Integration</u></a></li>
<li><a href="https://win11.techidaily.com/a-roadmap-to-resolve-file-creation-issues-windows-error-30005/"><u>A Roadmap to Resolve File Creation Issues - Windows Error 30005</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-oppo-a38-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Oppo A38 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-finding-documents-with-windows-11-taskbar-search-feature/"><u>Accelerate Finding Documents with Windows 11 Taskbar Search Feature</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-guide-to-understanding-group-policies-windows-via-3-views/"><u>A Detailed Guide to Understanding Group Policies (Windows) via 3 Views</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-reset-the-windows-11-settings-app/"><u>3 Ways to Reset the Windows 11 Settings App</u></a></li>
<li><a href="https://win11.techidaily.com/5-stealthy-ways-win11-accesses-your-details/"><u>5 Stealthy Ways Win11 Accesses Your Details</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-unveiling-tiktoks-anime-phenomenon-a-kaleidoscope-of-choreography-melodies-and-memes/"><u>[Updated] In 2024, Unveiling TikTok's Anime Phenomenon  A Kaleidoscope of Choreography, Melodies & Memes</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-vivo-y17s-by-drfone-android/"><u>How to Bypass FRP from Vivo Y17s?</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-stopping-blued-in-windows-10/"><u>A Step-by-Step Guide to Stopping Blued in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/1719382719080-optimal-start-menu-no-commercials-here/"><u>Optimal Start Menu: No Commercials Here</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/methods-to-transfer-from-apple-iphone-6s-to-android-drfone-by-drfone-transfer-from-ios/"><u>Methods to Transfer from Apple iPhone 6s to Android | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/6-costly-misconceptions-about-affordable-windows-codes/"><u>6 Costly Misconceptions About Affordable Windows Codes</u></a></li>
<li><a href="https://win11.techidaily.com/1719362597425-navigating-networked-notebooks-effortless-file-sharing-with-c/"><u>Navigating Networked Notebooks: Effortless File Sharing with C:</u></a></li>
<li><a href="https://win11.techidaily.com/5-ingenious-cmd-puzzles-to-perplex-and-pleasure/"><u>5 Ingenious CMD Puzzles to Perplex and Pleasure</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-permanently-vanish-language-sign-on-win11-ui/"><u>A Guide to Permanently Vanish Language Sign on Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-keygen-malware-and-its-destructive-path-in-windows/"><u>A Deep Dive Into Keygen Malware & Its Destructive Path in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-fixes-to-try-when-waterfox-is-not-loading-webpages-on-windows/"><u>7 Fixes to Try When Waterfox Is Not Loading Webpages on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-adding-secure-websites-in-windows-11/"><u>A Step-by-Step Guide to Adding Secure Websites in Windows 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/nexus-of-delight-kid-focused-gaming-guide-for-2024/"><u>Nexus of Delight  Kid-Focused Gaming Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719369512280-ifas-best-laptops-of-2023-now/"><u>IFA's Best Laptops of 2023, Now</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-productivity-with-essential-windows-11-methods/"><u>Accelerate Productivity with Essential Windows 11 Methods</u></a></li>
</ul></div>
