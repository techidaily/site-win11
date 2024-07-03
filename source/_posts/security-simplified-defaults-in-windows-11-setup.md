---
title: "Security Simplified: Defaults in Windows 11 Setup"
date: 2024-06-25T11:40:29.041Z
updated: 2024-06-26T11:40:29.041Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Security Simplified: Defaults in Windows 11 Setup"
excerpt: "This Article Describes Security Simplified: Defaults in Windows 11 Setup"
keywords: Win11SecureDefault,SecureWinSetup,Windows11Basics,SafeWindows11,DefSecConfigWin11,DefaultsWin11Security,EnhanceWindows11Secure
thumbnail: https://thmb.techidaily.com/a65a2d3fb958e05df694286812a1e2454a9d6c6ff463421241eb49561be7ce4c.jpg
---

## Security Simplified: Defaults in Windows 11 Setup

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
<li><a href="https://win11.techidaily.com/steps-to-eliminate-windows-1011-camera-app-error-a00f429f/"><u>Steps to Eliminate Windows 10/11 Camera App Error A00F429F</u></a></li>
<li><a href="https://win11.techidaily.com/essential-4-password-guardians-elevating-windows-11-security/"><u>Essential 4 Password Guardians Elevating Windows 11 Security</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-group-policy-management-in-windows-108/"><u>Simplifying Group Policy Management in Windows 10/8</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-enhancing-interface-through-ms-store-themes/"><u>Effortlessly Enhancing Interface Through MS Store Themes</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-a-stopped-netflix-window-program/"><u>Solutions for a Stopped Netflix Window Program</u></a></li>
<li><a href="https://win11.techidaily.com/windows-methods-for-engaging-wordpad/"><u>Windows Methods for Engaging WordPad</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-access-issues-with-these-top-5-windows-fixes-on-security-keys/"><u>Unlock Access Issues with These Top 5 Windows Fixes on Security Keys</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/the-complete-tiktok-element-encyclopedia-2023/"><u>The Complete TikTok Element Encyclopedia, 2023</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-track-apple-iphone-se-by-phone-number-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Track Apple iPhone SE by Phone Number | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-boost-your-gameplay-auditory-experience-add-music-to-kinemaster-strategically/"><u>In 2024, Boost Your Gameplay Auditory Experience Add Music to KineMaster Strategically</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-deciding-between-30fps-and-60fps-whats-best-for-video/"><u>2024 Approved  Deciding Between 30Fps and 60Fps  What's Best For Video?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-standout-6-platforms-empowering-biz-marketing/"><u>In 2024, Standout 6 Platforms Empowering Biz Marketing</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-essential-recording-tools-top-5-webcam-capturers-for-2024/"><u>[Updated] Essential Recording Tools - Top 5 Webcam Capturers for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-iphone-14-pro-backup-password-never-set-but-still-asking-heres-the-fix-drfone-by-drfone-ios/"><u>In 2024, iPhone 14 Pro Backup Password Never Set But Still Asking? Heres the Fix | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-streaming-superstars-the-leading-subscriber-crew/"><u>In 2024, Streaming Superstars  The Leading Subscriber Crew</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-melodic-accompaniment-to-frame-the-24-birthday-spectacle-for-2024/"><u>Updated Melodic Accompaniment to Frame the 24 Birthday Spectacle for 2024</u></a></li>
</ul></div>
