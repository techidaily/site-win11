---
title: Restoring Security Basics in Windows 11 Setup
date: 2024-07-13T09:50:36.416Z
updated: 2024-07-14T09:50:36.416Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Security Basics in Windows 11 Setup
excerpt: This Article Describes Restoring Security Basics in Windows 11 Setup
keywords: Win11 Security Setup,Windows Base Secure,WinSetup Safety,Basic Win11 Protect,Windows Basics Safe,Secure Win11 Start,Fundamentals of Win11 Guard
thumbnail: https://thmb.techidaily.com/f3b9ebc545f359ab98a545c4a62ebaee9fb8e9ec48b8af506bc5428bdf5f9d0e.jpg
---

## Restoring Security Basics in Windows 11 Setup

 Having issues with apps or programs not running properly on your Windows computer? Resetting Windows Update permissions could be the solution you need. Similarly, if you're troubleshooting user profile problems, you can restore user permissions.

 This article covers three different methods to reset all user permissions – using the Icacls command, the Secedit command, and the Subinacl tool.

Let's now explore them in detail.

## 1\. Run the Icacls Command

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to [take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then [open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

`icacls * /t /q /c /reset`

 Now press Enter on your keyboard to execute the command. This will reset all user permissions to default for every folder, subfolder, and file within the current working directory.

In the above command, here are the parameters explained:

* \* – This is a wildcard character that includes all folders within the current directory.
* /t – It targets all the subfolders and files within the current folder.
* /q – Run command without displaying success messages.
* /c – Continues the operation even if errors occur.
* /reset – This parameter resets the permission options to their default values.

## 2\. Run the Secedit command

 Windows provides the Secedit command to configure and analyze system security. To reset all user permissions using this command, run the command prompt with admin access, then type in the following command:

![Run the Secedit command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/run-the-secedit-command.jpg)

`secedit /configure /cfg %windir%\inf\defltbase.inf /db defltbase.sdb /verbose`

 Now press Enter to execute the command. Wait for the process to finish and restart your computer. This will reset the user permissions to the default system settings.

## 3\. Run the Subinacl Tool

 If you're not comfortable using the command prompt, you may use the Subinacl tool. This is a command-line utility from Microsoft that can be used to reset user permissions. Here's how to do it:

1. [Download the Subinacl tool from Microsoft's webpage](https://web.archive.org/web/20190830103837/http://www.microsoft.com/en-us/download/confirmation.aspx?id=23510) . When you open the page, the download starts automatically. If not, wait 30 seconds and click the link.
2. Once downloaded, double-click on the installer package. This will open the installation wizard.  
![Open the installation wizard](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/open-the-installation-wizard.jpg)
3. Click on**Next** and then accept the license agreement terms.  
![Install the Subinacl tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/install-the-subinacl-tool.jpg)
4. Next, copy and paste the following path into the Destination folder:  
`C:\Windows\System32`  
 Note: If you have installed Windows on a different drive, use that path instead.
5. Now click on**Install now** and wait for the Subinacl tool to be installed. This may take several minutes, so be patient.

1. When the installation is complete,[open Notepad](https://www.makeuseof.com/windows-11-open-notepad/) and type in the following commands:  
`subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=administrators=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=administrators=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=administrators=f  
subinacl /subdirectories %SystemDrive% /grant=administrators=f  
subinacl /subkeyreg HKEY_LOCAL_MACHINE /grant=system=f  
subinacl /subkeyreg HKEY_CURRENT_USER /grant=system=f  
subinacl /subkeyreg HKEY_CLASSES_ROOT /grant=system=f  
subinacl /subdirectories %SystemDrive% /grant=system=f`
2. On the Save As window, set the File name to**Reset.cmd** and then select**All Files** from the drop-down menu next to it.  
![Reset Windows Update permissions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reset-windows-update-permissions.jpg)
3. Next, select**Desktop** from the left pane and click on**Save** .
4. Now double-click on it to reset the user permissions to default.
5. This may take a while to complete the procedure, so wait for it to finish.

 Once done, close any running program, and then restart your computer. Your Windows Update permissions will be reset to their default settings. These are three different methods you can use to reset the user permission settings on Windows.

## Restore User Permissions to Default on Windows

 User permissions play a crucial role in computer security. If you're experiencing user permission issues, you must reset them to their default settings. This guide helps you reset all user permissions on Windows using three different methods. You can use the ICACLS command, Secedit command, or Subinacl tool, depending on your preference.


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
<li><a href="https://youtube-video-recordings.techidaily.com/movie-substitutes-that-shook-up-my-world-7-choices/"><u>Movie Substitutes That Shook Up My World - #7 Choices</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-file-sync-in-multiple-windows-systems-using-aoemi/"><u>The Essential Guide to File Sync in Multiple Windows Systems Using AOEMi</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/turn-windows-10-screen-back-normally/"><u>Turn Windows 10 Screen Back Normally</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-ultimate-capture-device-tailored-to-win11-systems/"><u>[New] 2024 Approved  Ultimate Capture Device, Tailored to Win11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-choosing-windows-photos-tools/"><u>The Ultimate Guide to Choosing Windows Photos Tools</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-network-preferences-with-windows-11-proxies/"><u>Navigating Your Network Preferences with Windows 11 Proxies</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-web-based-video-editing-platforms-for-vertical-content-creators-for-2024/"><u>Updated Web-Based Video Editing Platforms for Vertical Content Creators for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-window-interruptions-turn-off-non-critical-suggestions/"><u>Reduce Window Interruptions: Turn Off Non-Critical Suggestions</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-downloading-dynamism-techniques-for-preserving-online-lives-for-2024/"><u>[Updated] Downloading Dynamism  Techniques for Preserving Online Lives for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/seamlessly-manage-your-task-scheduling-on-pc/"><u>Seamlessly Manage Your Task Scheduling on PC</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-innovative-approach-for-rotating-and-interlacing-multiple-videographies-android/"><u>In 2024, Innovative Approach for Rotating & Interlacing Multiple Videographies (Android)</u></a></li>
<li><a href="https://win11.techidaily.com/revive-your-speaker-settings-fixing-winvolume-failures/"><u>Revive Your Speaker Settings: Fixing WinVolume Failures</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/tiktoks-hidden-treasures-grab-em-all-for-free/"><u>TikTok's Hidden Treasures  Grab 'Em All for Free</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-rdp-access-quickly-in-the-latest-windows/"><u>Unlock RDP Access Quickly in the Latest Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-notes-with-obsidians-visual-approach/"><u>Streamlining Notes with Obsidian's Visual Approach</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-capabilities-with-easy-installation-of-msixbundle-packages/"><u>Unlock Windows Capabilities with Easy Installation of MSixBundle Packages</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-twitters-viral-spotlight-top-10-tiktoks-of-the-week/"><u>[Updated] Twitter's Viral Spotlight  Top 10 TikToks of the Week</u></a></li>
<li><a href="https://win11.techidaily.com/pivot-to-new-life-for-your-outdated-tech-without-windows/"><u>Pivot to New Life for Your Outdated Tech Without Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-windows-cab-files-purpose-and-installation-tactics/"><u>The Essentials of Windows CAB Files: Purpose & Installation Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-eliminating-not-attached-usb-error-from-your-virtualbox/"><u>Quick Guide: Eliminating 'Not Attached USB Error' From Your VirtualBox</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-in-2024-what-is-the-best-fps-for-youtube-videos/"><u>New In 2024, What Is the Best FPS for YouTube Videos?</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-audio-output-on-microsofts-read-aloud-functionality/"><u>Resetting Audio Output on Microsoft's Read Aloud Functionality</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-how-to-record-and-save-screens-like-a-pro-with-your-dell/"><u>[Updated] In 2024, How to Record and Save Screens Like a Pro with Your Dell</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-sculpt-satirical-scenes-with-giphy/"><u>2024 Approved  Sculpt Satirical Scenes with Giphy</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-requires-elevation-puzzle-win-11s-error-740-solution/"><u>Unraveling the Requires Elevation Puzzle: Win 11'S Error #740 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-non-operational-snipviewer-keys/"><u>Quick Fixes for Non-Operational SnipViewer Keys</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-how-to-become-a-youtube-partner/"><u>[New] In 2024, How to Become A YouTube Partner</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-context-selection-by-omitting-show-more/"><u>Optimize Context Selection by Omitting Show More</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-masterclass-setting-up-your-first-facebook-page-for-2024/"><u>[Updated] Masterclass  Setting Up Your First Facebook Page for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-unresponsive-audio-devices-in-windows/"><u>Troubleshooting Unresponsive Audio Devices in Windows</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-free-location-spoofers-to-fake-gps-location-on-your-vivo-x-fold-2-drfone-by-drfone-virtual/"><u>In 2024, 10 Free Location Spoofers to Fake GPS Location on your Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reattach-absent-drives-in-windows/"><u>Steps to Reattach Absent Drives in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-world-of-windowed-activity-archives/"><u>Navigating the World of Windowed Activity Archives</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-not-an-empty-directory-error-code-0x80070091-in-win11-and-11/"><u>Rectifying Not an Empty Directory Error Code 0X80070091 in Win11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategic-access-to-system-fixes-windows-10-and-11-key-setups/"><u>Strategic Access to System Fixes: Windows 10 & 11 Key Setups</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-address-code-3-error-in-nvidia-opengl-win1011/"><u>Techniques to Address Code 3 Error in Nvidia OpenGL (Win10/11)</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-full-potential-of-windows-customizations-via-winbubble/"><u>Unleash the Full Potential of Windows Customizations via WinBubble</u></a></li>
<li><a href="https://win11.techidaily.com/steering-clear-of-fullscreen-failures-with-sonic-adventure-w11-edition/"><u>Steering Clear of Fullscreen Failures with Sonic Adventure, W11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-system-checks-a-guide-for-updating-context-menus/"><u>Streamlining System Checks: A Guide for Updating Context Menus</u></a></li>
</ul></div>
