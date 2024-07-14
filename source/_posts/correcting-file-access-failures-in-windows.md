---
title: Correcting File Access Failures in Windows
date: 2024-07-13T10:09:49.978Z
updated: 2024-07-14T10:09:49.978Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting File Access Failures in Windows
excerpt: This Article Describes Correcting File Access Failures in Windows
keywords: Fix File Permissions Win,Resolve Access Errors Win,Rectify File Unauthorized Win,Tackle Access Denied Windows,Overcome Read/Write Fails Win,Mend Open File Issues Win,Solve File IO Problems Win
thumbnail: https://thmb.techidaily.com/7886b93aef2a0639ec1e094763681d9231c505608c149e23de7fcb6df36e4813.JPG
---

## Correcting File Access Failures in Windows

 Are you encountering the "Windows cannot access the specified device, path, or file." error on Windows 10 or 11? This issue usually appears when you try to run an EXE application or open a document. When this error happens, you can't run some programs or access some documents, limiting your computer's usefulness.

 So, how do you solve the "cannot access the specified device" error? Check out some of the troubleshooting steps you can take below.

## 1\. Run the App as an Administrator

 Some programs, for a variety of reasons, need administrator privileges to perform specific tasks. In fact in certain situations, you might not be able to open them either.

 In your case, the "Windows Cannot Access the Specified Device, Path or File” error might be the result of this error as well. So if you are looking to fix this error, running it as an administrator will be your best bet. Here’s how you can get started:

1. Right-click on the app you want to run.
2. From the context menu, select **Run as administrator**.

 If the issue was the lack of administrator privileges, your app will run by the end of these steps.

## 2\. Disable Potentially Unwanted App Blocking

 Unwanted app blocking is a [Windows Security](https://www.makeuseof.com/windows-11-quick-security-guide/) feature that prevents low-reputation apps and software from running. That feature can cause the "cannot access the specified device" error when enabled. You can check if unwanted app blocking is enabled and disable it as follows:

1. Double-click the shield (Windows Security) icon inside the system tray area on the right of the taskbar. You may also need to click a small up arrow on the taskbar to see the system tray icons.
2. Select the **App & browser control** tab in Windows Security.
3. Then click the **Reputation-based protection** **settings** link to view more settings.  
![The Reputation-based protection settings option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reputation-based-settings-option.jpg)
4. Deselect the **Block apps** checkbox if that feature is enabled.  
![The Block apps checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-block-apps-checkbox.jpg)

## 3\. Deselect the "Unblock File" Setting

 Sometimes [Windows blocks access to files or folders](https://www.makeuseof.com/windows-askadmin-guide/) downloaded from untrusted online sources, which can cause the "cannot access the specified device" error. When that happens, you'll see an **Unblock** checkbox on an affected files properties window. This is how you can deselect the "unblock file" setting:

 Make sure that you trust the file's source before doing this. If you unblock an infected file, it can damage your computer and cause file loss.

1. Right-click **Start** (the taskbar button) and select the **File Explorer** option from the menu.  
![The File Explorer shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/file-explorer.jpg)
2. Open a folder that includes a file for which the error occurs.
3. Right-click the affected file and select **Properties**.  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/properties-option.jpg)
4. Click **General** if the properties window doesn't open with that tab by default.
5. Then uncheck the selected **Unblock** checkbox if you can see one.  
![The Unblock checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/unblock-checkbox.jpg)
6. Select **Apply** to save the new file settings.
7. Click **OK** to close the file's properties window.

## 4\. Edit the File's Permissions

 Another cause of the "cannot access the specified device" error message is insufficient file permissions. That's something you can remedy by editing the permissions for affected files. So, try editing an affected file's permissions as follows:

1. Bring up a directory with a file that throws up the "cannot access the specified device" error.
2. Click an affected file with the right mouse button and select its **Properties** option.
3. Select **Security** in the properties window.
4. Then select the Windows user account you signed into.
5. Press the **Edit** button.
6. Select your Windows user account on the permissions window that opens.
7. Deselect (uncheck) all selected **Deny** permission checkboxes.  
![The Deny checkboxes for file permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/deny-checkboxes.jpg)
8. Select **Apply** to set the new permission settings.
9. Press the **OK** buttons on all windows.

## 5\. Recreate a Program's Shortcut

 If the "cannot access the specified device" error occurs when you try to run a program shortcut, the issue might lie within the shortcut itself. In this case, setting up a new shortcut for affected software could resolve the issue. This is how to do so on your desktop:

1. Right-click any part of the desktop without overlapping icons to select **New**.
2. Click **Shortcut** to bring up a tool for adding desktop shortcuts.  
![The Shortcut option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/shortcut-option.jpg)
3. Then click **Browse** to select an EXE file the error occurs for and press the **OK** button.  
![The Create Shortcut tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/create-shortcut-window.jpg)
4. Select **Next** and input a shortcut title in the text box.
5. Click **Finish** to add the new program shortcut.
6. Right-click the program's old shortcut to select **Delete** (the trash can button in Windows 11).

## 6\. Double-Check the File's Location

 Do you install software and save some files to an external or network drive? If so, it could be the case that the access error is occurring because a file is on a drive that's not currently accessible.

 Double-check the locations of the files you're trying to run or open by right-clicking desktop shortcuts for them and selecting **Properties**. Then you can check the path for the shortcut in the **Targe**t box shown directly below.

![The Target box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-target-box.jpg)

 That **Target** box will show whether the file is on another drive. If it is, connect the external drive that includes the file to your PC to access it. Double-check that the file specified hasn't been deleted if the **Target** box references the local C: drive. To do that, open the folder path specified in File Explorer.

 Should you discover a shortcut's file has been deleted, you might be able to retrieve it. Open the Recycle Bin to see if the file is in it. If so, right-click the file and select **Restore**.

## 7\. Enable Admin Permissions With the Group Policy Editor

 Users have confirmed enabling admin approval mode in Group Policy Editor can resolve this file access error. However, Group Policy Editor is only available in Windows 11 and 10 Pro and Enterprise editions. If you can utilize Group Policy Editor, try enabling admin approval mode as follows:

1. [Open Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/) and select **Computer Configuration** in that utility.
2. Double-click **Windows Settings** to expand that configuration category.
3. Then double-click **Security Settings** \> **Local Policies** \> **Security Options** in Group Policy Editor's sidebar.  
![The Local Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/group-policy-editor.jpg)
4. Double-click the **Admin Approval Mode for Built-in Administrator** account policy.
5. Then select the **Enabled** radio button.  
![The Admin Approval Mode policy setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-admin-approval-mode-policy-settings.jpg)
6. Click **Apply** to set the policy.
7. Select **OK** to exit the window for the policy setting and close the Group Policy Manager utility.

## 8\. Set Up a Windows Security Exclusion Affected Software or File

 As Windows Security blocks can cause this error, we recommend users add affected files to that antivirus app's exclusion list. Doing so will exclude the file from Defender's antivirus protection. Check out our guide to [whitelisting files in Microsoft (formerly Windows) Defender](https://www.makeuseof.com/how-to-whitelist-files-windows-defender/) for details about how to apply this potential solution.

![Add an exclusion button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-an-exclusion-button.jpg)

## 9\. Temporarily Disable Any Active Third-Party Security Software

 Some third-party antivirus apps share similar app-blocking features to Windows Security. Thus, alternative security software can also feasibly cause the same issue to occur much the same. So, try turning off any third-party antivirus software installed on your PC before attempting to run affected EXE software.

![A laptop computer is seen on a desk during an antivirus scan](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/manual-antivirus-scan.jpg)

 How exactly you turn off different third-party antivirus apps varies slightly. However, most have context menus from which you can select to disable their shields. Click the system tray icon for your antivirus software with the right mouse button to view its context menu. Then choose an option for disabling its antivirus shield from there.

 Should this potential solution work, you'll know what's causing it. However, don't leave your antivirus software disabled. Add affected files to the security software's exceptions list.

## 10\. Repair or Reinstall the File

 If you are facing this issue due to corruption in the file, then repairing or reinstalling it is your best bet. Using the Control Panel will be your best bet in this case. Here's how you can do it:

1. Head to the **Start menu** search bar, type in 'control panel', and select the best match.
2. From there, head to the **Programs**.
3. Then, select **Programs and Features**.
4. Right-click on any program and select **Uninstall/Change**.

![control panel on windows pc](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/control-panel-on-windows-pc.jpg)

 Depending on the app, you will get an option to either uninstall the app or change its settings. That's it—from there just follow the on-screen instructions, and you will be done in no time. If you installed the app, make sure you get it from a trusted source again and then see if you are facing the same error again.

## Get the "Cannot Access the Specified Device" Error Sorted in Windows 10 and 11

 We don't promise guaranteed solutions, but the potential resolutions here will likely resolve the "cannot access the specified device" error on your PC. Many users have sorted that file access issue out in Windows by applying the above fixes.

 So, how do you solve the "cannot access the specified device" error? Check out some of the troubleshooting steps you can take below.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/strategies-to-address-windows-exception-breakpoint-errors/"><u>Strategies to Address Windows Exception Breakpoint Errors</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nokia-c22-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Nokia C22 Phone without PIN</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-rediscovering-missing-panes-top-tips-and-hacks-for-windows-users/"><u>The Ultimate Guide to Rediscovering Missing Panes: Top Tips and Hacks for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/timeless-windows-syncing-the-digital-second-hand/"><u>Timeless Windows: Syncing the Digital Second Hand</u></a></li>
<li><a href="https://win11.techidaily.com/launch-into-productivity-must-have-ms-store-picks/"><u>Launch Into Productivity: Must-Have MS Store Picks</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-pictures-files-from-motorola-moto-g-stylus-2023-by-fonelab-android-recover-pictures/"><u>How To  Restore Missing Pictures Files from Motorola Moto G Stylus (2023).</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-drive-detect-and-delete-null-space-in-windows/"><u>Streamline Your Drive: Detect and Delete Null Space in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-recover-lost-access-to-ubisofts-launcher/"><u>Steps to Recover Lost Access to Ubisoft's Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-steam-content-unavailable-glitches/"><u>Bypassing Steam Content Unavailable Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/how-regular-windows-backup-prolongs-peace-of-mind/"><u>How Regular Windows Backup Prolongs Peace of Mind</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-dolby-atmos-in-windows-11-pro/"><u>How to Install Dolby Atmos in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-address-dying-function-keys-adjusting-screen-brightness/"><u>Solutions to Address Dying Function Keys Adjusting Screen Brightness</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-farm-fun-and-fellowship-the-ultimate-agritainment-guide-for-2024/"><u>[Updated] Farm Fun & Fellowship  The Ultimate Agritainment Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/trimming-early-edges-methods-to-stop-tab-preload-on-windows-11/"><u>Trimming Early Edges: Methods to Stop Tab Preload on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-instructions-for-setting-up-dolby-atmos-in-windows-1111/"><u>In-Depth Instructions for Setting Up Dolby Atmos in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-nvidia-geforce-notaxc0f1103f-error/"><u>Correcting Windows Nvidia GeForce NotaXC0F1103F Error</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-page-denial-challenges/"><u>Overcoming Windows Page Denial Challenges</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-league-of-legends-disconnecting-on-windows/"><u>How to Fix League of Legends Disconnecting on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/sidestepping-error-0x80070522-on-windows-by-accessing-client-rights/"><u>Sidestepping Error 0X80070522 on Windows by Accessing Client Rights</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-optimizing-windows-lockscreen-with-spotlight/"><u>Tips for Optimizing Windows Lockscreen with Spotlight</u></a></li>
<li><a href="https://youtube-web.techidaily.com/levating-video-sharing-from-youtube-to-insta-for-2024/"><u>[New] Elevating Video Sharing  From YouTube to Insta for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-securely-verifying-your-youtube-access-details/"><u>[Updated] Securely Verifying Your YouTube Access Details</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-over-malfunctioning-windows-snippers/"><u>Regaining Control Over Malfunctioning Windows Snippers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-final-cut-pro-x-mastery-crafting-instagrams-desired-format/"><u>2024 Approved  Final Cut Pro X Mastery  Crafting Instagram's Desired Format</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-past-fatal-js-error-in-discord-on-modern-windows-11/"><u>Navigating Past Fatal JS Error in Discord on Modern Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/averting-steam-library-write-errors-on-modern-windows-pcs/"><u>Averting Steam Library Write Errors on Modern Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-store-error-0x800704cf-in-win11/"><u>Troubleshooting Store Error 0X800704CF in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-full-screen-display-defeating-windows-overscan/"><u>Optimize Full-Screen Display: Defeating Windows Overscan</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-xiaomi-redmi-note-13-5g-frp-by-drfone-android/"><u>The Updated Method to Bypass Xiaomi Redmi Note 13 5G FRP</u></a></li>
<li><a href="https://fox-helps.techidaily.com/from-dull-to-dynamic-top-11-techniques-for-improved-colors/"><u>From Dull to Dynamic  Top 11 Techniques for Improved Colors</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-efficient-screen-recording-on-lenovo-systems/"><u>2024 Approved  Efficient Screen Recording on Lenovo Systems</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-hello-fingerprint-malfunctions-easily/"><u>Navigating Windows Hello Fingerprint Malfunctions Easily</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-lock-from-your-iphone-15-pro-and-ipad-by-drfone-ios/"><u>In 2024, How to Unlock iCloud lock from your iPhone 15 Pro and iPad?</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-mobile-app-match-android-plus-windows-pc-edition/"><u>Perfect Mobile App Match: Android + Windows PC Edition</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-full-power-of-task-manager-with-admin-rights-in-win11/"><u>Unleash Full Power of Task Manager with Admin Rights in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-dormant-slack-alerts-on-modern-windows-pcs/"><u>Reinstating Dormant Slack Alerts on Modern Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-turn-off-corner-shaping/"><u>Mastering Windows 11: Turn Off Corner Shaping</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-fix-inaudible-microphone-during-screen-recordings/"><u>Techniques to Fix Inaudible Microphone During Screen Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unauthorized-user-error-in-windows-1111/"><u>Overcoming Unauthorized User Error in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-working-state-for-ccleaner-in-windows-1011-systems/"><u>Enabling Working State for CCleaner in Windows 10/11 Systems</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-spotify-promotion-a-comprehensive-guide-for-2024/"><u>Mastering Spotify Promotion  A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-lava-blaze-2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Lava Blaze 2 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-landscape-of-winapp-and-browser-mastery/"><u>Navigating the Landscape of WinApp and Browser Mastery</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-cutting-edge-stabilizing-gadgets-for-youtube-videography/"><u>[New] In 2024, Cutting Edge Stabilizing Gadgets for YouTube Videography</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-resource-utilization-in-wsl-android/"><u>Best Practices for Resource Utilization in WSL-Android</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-windows-8-avi-file-editor-simple-and-efficient-video-editing/"><u>Updated Windows 8 AVI File Editor Simple and Efficient Video Editing</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-maximize-your-fcpx-experience-10-free-plugins-to-try/"><u>New Maximize Your FCPX Experience 10 Free Plugins to Try</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-windows-activation-error-0x8007251d-and-how-do-you-fix-it/"><u>What Is the Windows Activation Error 0X8007251D and How Do You Fix It?</u></a></li>
<li><a href="https://win11.techidaily.com/post-install-windows-heres-how-to-get-online/"><u>Post-Install Windows? Here's How to Get Online</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-avoiding-edgenuitys-grasp-tips-for-quickly-skipping-video-lessons/"><u>2024 Approved  Avoiding Edgenuity's Grasp  Tips for Quickly Skipping Video Lessons</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-microsoft-family-safety/"><u>A Beginner's Guide to Microsoft Family Safety</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-free-video-enhancement-tools-to-reduce-shaky-footage/"><u>Updated 2024 Approved Free Video Enhancement Tools to Reduce Shaky Footage</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-an-enhanced-run-tool-to-windows-10-and-11/"><u>How to Add an Enhanced Run Tool to Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-legacy-windows-photo-viewer-features-in-win11/"><u>Restoring Legacy Windows Photo Viewer Features in Win11</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-snipping-edits-imovies-size-changing-secrets/"><u>[New] Snipping Edits  IMovie’s Size-Changing Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-windows-11-taskbar-performance/"><u>Optimizing Windows 11 Taskbar Performance</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-windows-11-search-backup-procedure/"><u>Navigate to Windows 11 Search Backup Procedure</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-overcoming-obscured-visual-space-on-youtube/"><u>2024 Approved  Overcoming Obscured Visual Space on YouTube</u></a></li>
<li><a href="https://screen-capture.techidaily.com/hands-on-methods-mirror-video-frames-using-vlc/"><u>Hands-On Methods  Mirror Video Frames Using VLC</u></a></li>
</ul></div>
