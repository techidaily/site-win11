---
title: Tackling the Zero-Empty Directories Issue in Windows 11 & 11
date: 2024-07-13T10:34:37.443Z
updated: 2024-07-14T10:34:37.443Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling the Zero-Empty Directories Issue in Windows 11 & 11
excerpt: This Article Describes Tackling the Zero-Empty Directories Issue in Windows 11 & 11
keywords: Win11 EmptyDirs Fix,W11 Empty Directory Troubleshoot,Windows 11 Directories Cleanup,Resolve Windows 11 Dir Issues,Zero-Empty Directories in W11,Tackling W11 EmptyDirs Problem,Fixing Empty Folders in Win11
thumbnail: https://thmb.techidaily.com/cb833d2c06ebc2c32cdbed9ef9e234accd8f5206773825bdc531095627fac7c4.jpg
---

## Tackling the Zero-Empty Directories Issue in Windows 11 & 11

 Error 0x80070091 is a File Explorer issue that occurs for some users when they try to delete folders in Windows 11/10\. The error message says, “The directory is not empty," and you can't delete the folder that throws the error.

 The 0x80070091 message suggests that the error occurs because a folder isn’t empty. Yet, you should be able to erase directories that contain files without any issues. Furthermore, that error can also arise for empty folders. If you’re seeing the same folder error 0x80070091 in Windows, try applying these potential fixes.

## 1\. Try Erasing the Folder With the Command Prompt

 The Command Prompt gives users another way to delete folders in Windows 11/10\. So, you might be able to erase an affected folder without issues by using the Command Prompt. Using the Command Prompt might be more of a workaround, but at least you’ll get the folder deleted if works.

 Run Command Prompt with elevated (administrative) rights. Our guide about [running Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) includes numerous methods for launching that app. Then input this command and press**Enter** to delete an affected folder:

`rmdir /s "folder path"`

 You’ll need to replace**folder path** in that command with the location of whatever directory you need to delete. The location should include a drive letter and a full path for the directory like in this example:

`rmdir /s "C:\Users\New folder"`

![The delete folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-folder-command.jpg)

## 2\. Restart Windows File Explorer

 Restarting File Explorer can resolve issues that occur with that file manager. However, closing and reopening the Explorer window doesn’t restart the file manager. You’ll need to restart the Explorer process via Task Manager like this:

1. To view Task Manager, press**Ctrl** +**Shift** +**Esc** simultaneously.
2. Select File Explorer on the**Processes** tab.  
![The Restart option for File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-options-for-file-explorer.jpg)
3. Press the**Restart** button for the selected Explorer process.

## 3\. Scan System Files With an SFC Scan

 Error 0x80070091 can be caused by some corrupted system files that need repairing. Running an SFC scan might both detect and repair corrupted system files and fix error 0x80070091 in the process. You can scan with SFC as instructed in our post for [running the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) .

![The SFC command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/sfc-scannow-command.jpg)

## 4\. Check for Errors With a Disk Scan

 The 0x80070091 error is often due to corrupted or bad hard drive sectors. A lot of users have said they’ve resolved that issue by using the Check Disk (CHKDSK) utility for repairing bad drive sectors. This is how you can check for and repair bad sectors with Check Disk:

1. Open up the Command Prompt window with administrative rights.
2. Type in this Check Disk command and press**Enter:**  
`chkdsk /f /r C:`
3. Press**Y** to schedule the scan for a restart.  
![The chkdsk scan command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/chkdsk-scan-command.jpg)
4. Click**Start** and select**Power** \>**Restart** to reboot.

 If the folder the 0x80070091 error occurs for isn’t on the C: drive, you’ll need to modify the above command. Replace**C:** with the letter of the storage drive that includes the affected folder.

## 5\. Modify the Affected Folder’s Permissions

 Error 0x80070091 can arise because of insufficient folder permission. You might need to set an affected folder to full permission to resolve error 0x80070091\. To do that, change the folder’s permission settings as follows:

1. Open Explorer and right-click the affected folder to select**Properties** .  
![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/properties-option.jpg)
2. Click the window’s**Security** tab.
3. Next, press the**Advanced** button.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/security-tab.jpg)
4. Click**Change** beside the owner’s name.  
![The Advanced Security Settings window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-security-settings-window.jpg)
5. Enter your Windows user account name inside the object name text box.  
![The Select a User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/select-a-user-or-group.jpg)
6. Then select the**Check Names** option and**OK** .
7. Click**Replace owner on subcontainers and objects** to select that setting.
8. Press the Advanced Security Settings window’s**Apply** and**OK** buttons.

## 6\. Run an Antivirus Scan

 Malware could also feasibly be causing error 0x80070091 on your PC. If you’re still trying to fix that issue after going through all the potential fixes above, run an antivirus scan with Windows Security or alternative third-party software. This is how to run a scan with the Windows Security app.

1. Double-click a**Windows Security** (shield) icon in the system tray part of the taskbar.
2. Click**Virus & threat protection** \>**Scan options** to view all options for scanning.  
![The Scan options navigation link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-scan-options-link.jpg)
3. Select the most thorough**Full Scan** option, which could take more than an hour to finish.  
![The Full scan option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-scan-option.jpg)
4. Press**Scan now** to start the antivirus scanning.
5. Then wait to see if the scan detects anything, and select**Remove** if it does.
6. Click**Start actions** to apply.

## Delete Your Folders in File Explorer Again With These Fixes

 You’ll probably be able to delete the folders for which error 0x80070091 occurred after applying those potential solutions. If that error persists, the Windows registry on your PC could be corrupted. To resolve such registry issues, you might need to perform a system restore or even reset Windows 11/10.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/how-to-resolve-file-download-failures-in-windows-1011/"><u>How to Resolve File Download Failures in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-sound-error-on-audacity-in-win1011/"><u>Resolving Sound Error on Audacity in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-shortage-of-usb-interface-points-in-windows/"><u>Fixing Shortage of USB Interface Points in Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win10-fall-crisis-brightened-screens-now/"><u>Win10 Fall Crisis: Brightened Screens Now</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-code-0xc0000142-in-winos/"><u>Resolving Code 0XC0000142 in WINOS</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-learn-to-make-a-flawless-square-video-in-imovie-for-instagram/"><u>[Updated] In 2024, Learn to Make a Flawless Square Video in iMovie for Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-printer-uninstallation-without-recovery-options/"><u>Mastering Printer Uninstallation without Recovery Options</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-fixes-for-windows-11-taskbar-loss/"><u>Guiding Fixes for Windows 11 Taskbar Loss</u></a></li>
<li><a href="https://win11.techidaily.com/smart-pc-enhancement-add-gmail-bar-to-taskbar-border/"><u>Smart PC Enhancement: Add Gmail Bar to Taskbar Border</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-jump-into-action-on-tiktok-live-easy-methods-revealed-for-2024/"><u>[New] Jump Into Action on TikTok Live  Easy Methods Revealed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-system-use-with-6-advanced-trackers-for-win-users/"><u>Streamline System Use with 6 Advanced Trackers for Win Users</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-your-step-by-step-pathway-to-youtube-video-enhancement/"><u>2024 Approved  Your Step-By-Step Pathway to YouTube Video Enhancement</u></a></li>
<li><a href="https://win11.techidaily.com/get-rid-of-unwanted-files-setting-up-scheduled-deletions-on-win11/"><u>Get Rid of Unwanted Files: Setting Up Scheduled Deletions on Win11</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-fix-invisible-facebook-watch-icon-now-fixed-for-2024/"><u>[New] Fix  Invisible Facebook Watch Icon, Now Fixed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-past-windows-0x80242016-update-fails/"><u>Navigating Past Windows' 0X80242016 Update Fails</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-one-sided-windows-headphone-sound-loss/"><u>Fixing One-Sided Windows Headphone Sound Loss</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-unveil-the-magic-of-media-rotation-using-vlc-players-features/"><u>[New] Unveil the Magic of Media Rotation Using VLC Player's Features</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-1011s-recycle-bin-issues/"><u>Navigating Through Windows 10/11'S Recycle Bin Issues</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/how-to-create-video-with-music-for-free-for-2024/"><u>How to Create Video with Music for FREE for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-discover-the-best-snapchat-video-edits-on-android-and-iphone/"><u>[New] Discover the Best Snapchat Video Edits on Android and iPhone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/podcasts-intros-hook-up-listeners-with-podcast-intro-script-for-2024/"><u>Podcasts Intros  Hook Up Listeners With Podcast Intro Script for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/macs-visual-excellence-10-list-of-ultimate-screens/"><u>Mac's Visual Excellence  #10 List of Ultimate Screens</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-fatal-application-hiccups-windows-edition/"><u>Overcoming Fatal Application Hiccups: Windows Edition</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-apps-and-online-tools-to-track-samsung-galaxy-s23-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Samsung Galaxy S23 Phone With/Without IMEI Number</u></a></li>
<li><a href="https://win11.techidaily.com/powerful-techniques-for-unlocking-your-system-writable-files/"><u>Powerful Techniques for Unlocking Your System' Writable Files</u></a></li>
<li><a href="https://win11.techidaily.com/from-chaos-to-clarity-manage-all-open-windows-win1110/"><u>From Chaos to Clarity: Manage All Open Windows (Win11/10)</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-studio-2-the-artists-dream-device-unveiled/"><u>Surface Laptop Studio 2: The Artist's Dream Device Unveiled</u></a></li>
<li><a href="https://fix-guide.techidaily.com/poco-m6-pro-5g-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Poco M6 Pro 5G Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-ignite-passion-an-essential-guide-to-10-motivational-films/"><u>In 2024, Ignite Passion  An Essential Guide to 10 Motivational Films</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-lava-agni-2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Lava Agni 2 5G | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-top-5-best-windows-movie-maker-for-mac/"><u>New 2024 Approved Top 5 Best Windows Movie Maker for Mac</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-screens-boost-your-pcs-performance-with-hotkeys/"><u>Streamlined Screens: Boost Your PC's Performance with Hotkeys</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-microsofts-safe-mode-only-constraint/"><u>Navigating Through Microsoft's Safe Mode Only Constraint</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-step-into-cinematic-quality-using-instagrams-chroma-keying-effect/"><u>2024 Approved  Step Into Cinematic Quality  Using Instagram’s Chroma Keying Effect</u></a></li>
<li><a href="https://extra-resources.techidaily.com/balancing-dynamics-with-controlled-decays-for-2024/"><u>Balancing Dynamics with Controlled Decays for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-insights-new-folder-formation-in-windows-11/"><u>Innovative Insights: New Folder Formation in Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-tips-to-keep-tiktok-videos-on-mobile-devices/"><u>[New] In 2024, Tips to Keep TikTok Videos on Mobile Devices</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-glitch-nvidia-experiences-x0001-in-w11/"><u>Fixing Glitch: Nvidia Experience's X0001 in W11</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-ultimate-platforms-for-animated-3d-creation/"><u>[Updated] Ultimate Platforms for Animated 3D Creation</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-filmoras-secrets-to-captivating-youtube-trailers/"><u>[New] 2024 Approved  Filmora's Secrets to Captivating YouTube Trailers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/from-virtual-anonymity-to-facebook-fame-how-to-expand-your-audience-for-2024/"><u>From Virtual Anonymity to Facebook Fame  How to Expand Your Audience for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-tecno-spark-10-pro-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Tecno Spark 10 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/sketch-mastery-for-desktop-users-in-windows-11/"><u>Sketch Mastery for Desktop Users in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/instructional-manual-restoring-originality-in-windows-11-search/"><u>Instructional Manual: Restoring Originality in Windows 11 Search</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-lock-from-apple-iphone-se-by-drfone-ios/"><u>In 2024, How to Bypass iCloud Lock from Apple iPhone SE</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-video-stabilization-made-easy-a-premiere-pro-tutorial/"><u>Updated 2024 Approved Video Stabilization Made Easy A Premiere Pro Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/paint-your-thoughts-desktop-design-mastery-in-windows/"><u>Paint Your Thoughts: Desktop Design Mastery in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-startup-changing-boot-timeout-in-windows-11/"><u>Optimize Startup: Changing Boot Timeout in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/from-a-simple-pin-a-comprehensive-approach-to-switching-passwords-in-windows-11/"><u>From a Simple PIN: A Comprehensive Approach to Switching Passwords in Windows 11</u></a></li>
</ul></div>
