---
title: "Outsmart Windows: Delete Temp Files Without Fuss"
date: 2024-07-13T09:53:34.312Z
updated: 2024-07-14T09:53:34.312Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Vivo X Fold 2? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-the-isdonedll-error-in-windows-11-and-11x/"><u>Dealing with the ISDone.dll Error in Windows 11 & 11X</u></a></li>
<li><a href="https://win11.techidaily.com/embracing-deity-interactions-with-your-windows-11-pc/"><u>Embracing Deity Interactions with Your Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-rectify-predominant-windows-anydesk-mishaps/"><u>Essential Steps to Rectify Predominant Windows AnyDesk Mishaps</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-best-choices-8-edits-suites-for-linux-users/"><u>2024 Approved  Best Choices  8 Edits Suites for Linux Users</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-art-of-cozy-cinematography-top-5-winter-scenes-for-2024/"><u>The Art of Cozy Cinematography  Top 5 Winter Scenes for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-inoperative-windows-11-speech-recognition/"><u>Resolving Inoperative Windows 11 Speech Recognition</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-winerror-with-code-0x8019/"><u>Resolving WinError with Code 0X8019</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11s-unidentified-usb-port-problems/"><u>Overcoming Windows 11'S Unidentified USB Port Problems</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-preventing-heat-in-w11-systems/"><u>Essential Steps for Preventing Heat in W11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/experts-choice-10-error-finder-apps-for-pc/"><u>Expert's Choice: 10 Error Finder Apps for PC</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-leveraging-creator-funding-in-youtube-shorts/"><u>[Updated] Leveraging Creator Funding in YouTube Shorts</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-freespace-a-comprehensive-windows-approach/"><u>Enhancing FreeSpace: A Comprehensive Windows Approach</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/improving-performance-managing-memory-usage-for-connected-services/"><u>Improving Performance: Managing Memory Usage for Connected Services</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-absence-of-battery-life-duration-in-pcs-running-win-11/"><u>Overcoming the Absence of Battery Life Duration in PCs Running Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-error-x70-on-windows-file-and-folder-restoration-guide/"><u>Eradicating Error X70 on Windows: File and Folder Restoration Guide</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentiality-of-runtime-brokers-for-modern-os-functionality/"><u>The Essentiality of Runtime Brokers for Modern OS Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-handle-out-of-space-files-warning/"><u>How to Handle Out of Space Files Warning</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-rectifying-bluetooth-pin-related-disconnects/"><u>Mastering the Art of Rectifying Bluetooth PIN-Related Disconnects</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-online-dailymotion-converter-fast-free-and-easy-to-use/"><u>Updated In 2024, Online Dailymotion Converter Fast, Free, and Easy to Use</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-ultimate-action-recorder-an-overview-of-panasonics-hx-a1/"><u>The Ultimate Action Recorder  An Overview of Panasonic's HX-A1</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-13-mini-to-other-iphone-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 13 mini To Other iPhone devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-swiftly-address-roblox-error-262/"><u>How to Swiftly Address Roblox Error 262</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-slashing-dropbox-cpu-load-on-windows-devices/"><u>Solutions for Slashing Dropbox CPU Load on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-desktop-aesthetics-with-a-custom-weather-icon-in-windows-11/"><u>Elevate Desktop Aesthetics with a Custom Weather Icon in Windows 11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-unraveling-instagram-video-anomalies-today/"><u>[New] 2024 Approved  Unraveling Instagram Video Anomalies Today</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-failed-security-codes-in-game-launcher-windows-edition/"><u>Quick Fixes for Failed Security Codes in Game Launcher Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-correcting-windows-store-failures-error-x80072f30-guide/"><u>Swiftly Correcting Windows Store Failures: Error X80072F30 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-personalizing-your-desktop-with-widgets/"><u>Mastering Window 11: Personalizing Your Desktop with Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/stop-recurring-file-explorer-autoload/"><u>Stop Recurring File Explorer Autoload</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-amd-graphics-driver-updates-in-the-windows-ecosystem/"><u>Mastery of AMD Graphics Driver Updates in the Windows Ecosystem</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-oneplus-nord-ce-3-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to OnePlus Nord CE 3 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-incorporation-of-virtual-gaming-archives-into-playnite-on-pc/"><u>Seamless Incorporation of Virtual Gaming Archives Into Playnite on PC</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/gigglegenius-log-in-for-video-adventures-for-2024/"><u>GiggleGenius  Log In for Video Adventures for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-tecno-pova-5-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Tecno Pova 5 Is Unlocked</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-to-tackle-programming-problems-on-vistawindows-7/"><u>Efficient Methods to Tackle Programming Problems on Vista/Windows 7</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-end-persistent-login-error-alerts-on-pc/"><u>Methods to End Persistent Login Error Alerts on PC</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-file-management-with-collective-windows-11-folder-making/"><u>Revolutionize File Management with Collective Windows 11 Folder Making</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-file-handling-in-win-11-by-adding-movecopy-menus/"><u>Elevate Your File Handling in Win 11 by Adding Move/Copy Menus</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-ms-paint-within-windows-11/"><u>Initiating MS Paint Within Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-infinix-hot-40-pro-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Infinix Hot 40 Pro to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastering-gopro-essentials-of-time-lapse-photography/"><u>2024 Approved  Mastering GoPro  Essentials of Time-Lapse Photography</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-how-to-create-a-youtube-intro/"><u>In 2024, How To Create A YouTube Intro</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-overcoming-windows-11s-rename-limitations/"><u>Essential Fixes: Overcoming Windows 11'S Rename Limitations</u></a></li>
</ul></div>
