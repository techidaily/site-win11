---
title: Restoring Security Basics in Windows 11 Setup
date: 2024-06-25T11:24:00.600Z
updated: 2024-06-26T11:24:00.600Z
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

 The Icacls command allows you to view, modify, and reset file system permissions on files and folders. To reset Windows Update permissions using this command, you will first have to[take ownership of the folders on Windows](https://www.makeuseof.com/windows-10-11-own-folder/) . Then[open an elevated Command Prompt on Windows](https://www.makeuseof.com/windows-run-command-prompt-admin/) and type in the following command:

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
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-compatibility-with-photoshop/"><u>Steps to Overcome Windows Compatibility with Photoshop</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-visibility-in-windows-network-guard-area/"><u>Mastery over Visibility in Windows' Network Guard Area</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-modify-win11s-network-preferences/"><u>Guide to Modify Win11's Network Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-restore-functionality-of-missing-steamuidll/"><u>Steps to Restore Functionality of Missing Steamui.dll</u></a></li>
<li><a href="https://win11.techidaily.com/full-method-to-turn-off-wsl-in-windows-1011/"><u>Full Method to Turn Off WSL in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/12-unnecessary-windows-programs-and-apps-you-should-uninstall/"><u>12 Unnecessary Windows Programs and Apps You Should Uninstall</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-tricks-for-mass-folder-creation-at-a-click-in-windows-oses/"><u>The Ultimate Tricks for Mass Folder Creation at a Click in Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-re-establish-bluetooth-linkage-on-windows-1011/"><u>How To Re-Establish Bluetooth Linkage on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-non-complying-windows-scripts/"><u>Essential Fixes for Non-Complying Windows Scripts</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-migrate-android-data-from-lava-blaze-curve-5g-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Migrate Android Data From Lava Blaze Curve 5G to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-elite-video-solutions-for-gameplay/"><u>[New] 2024 Approved  Elite Video Solutions for Gameplay</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-comparative-study-of-vlc-and-alternatives/"><u>[New] Comparative Study of VLC & Alternatives</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-tips-and-tricks-to-tell-if-your-iphone-14-pro-is-unlocked-by-drfone-ios/"><u>In 2024, Tips And Tricks To Tell if Your iPhone 14 Pro Is Unlocked</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/easy-steps-for-arranging-a-google-meeting-for-2024/"><u>Easy Steps for Arranging a Google Meeting for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-convenient-tactics-for-transferring-imovie-projects-to-vimeo/"><u>[Updated] 2024 Approved  Convenient Tactics for Transferring iMovie Projects to Vimeo</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-command-your-chats-with-flair-pinning-made-simple-in-discord-for-2024/"><u>[Updated] Command Your Chats with Flair  Pinning Made Simple in Discord for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/streamlined-upload-procedures-for-media-center-videos-to-vimeo-for-2024/"><u>Streamlined Upload Procedures for Media Center Videos to Vimeo for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-calculating-image-size-and-aspect-ratio-like-a-pro/"><u>New Calculating Image Size and Aspect Ratio Like a Pro</u></a></li>
<li><a href="https://extra-skills.techidaily.com/maximize-ms-edge-usage-understanding-and-using-picture-in-picture-for-2024/"><u>Maximize MS Edge Usage  Understanding and Using Picture-in-Picture for 2024</u></a></li>
</ul></div>
