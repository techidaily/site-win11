---
title: "Purging Power Users: The Guide to Default Settings"
date: 2024-06-25T11:36:36.607Z
updated: 2024-06-26T11:36:36.607Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Purging Power Users: The Guide to Default Settings"
excerpt: "This Article Describes Purging Power Users: The Guide to Default Settings"
keywords: Power User Tips,Setting Basics,Default Configs,Admin Guidelines,Security Updates,System Optimization,Default Tweaks
thumbnail: https://thmb.techidaily.com/c097990fd37784ce6293a6224fb832fd4d9a7841c40f79ad9e48ab602a74cd56.jpg
---

## Purging Power Users: The Guide to Default Settings

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
<li><a href="https://win11.techidaily.com/maximize-visual-impact-with-auto-color-settings-in-windows-11/"><u>Maximize Visual Impact with Auto Color Settings in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-into-stalled-win11-license-numbers/"><u>Breathing Life Into Stalled Win11 License Numbers</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-user-administration-in-windows-11/"><u>Streamlining User Administration in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-microsoft-family-safetys-core-functions/"><u>Decoding Microsoft Family Safety's Core Functions</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-process-to-configure-pc-manager/"><u>The Complete Process to Configure PC Manager</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-meaning-behind-windows-patches/"><u>Unraveling the Meaning Behind Window's Patches</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-the-ideal-taskbar-for-your-windows-11-tablet/"><u>Implementing the Ideal Taskbar for Your Windows 11 Tablet</u></a></li>
<li><a href="https://win11.techidaily.com/bitlockers-encryption-is-broken-but-its-still-not-time-to-switch/"><u>BitLocker's Encryption Is Broken, But It's Still Not Time to Switch</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-charge-battlenet-downloads-for-smooth-gaming/"><u>Turbo Charge Battle.net Downloads for Smooth Gaming</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-correcting-muted-voice-in-obs-broadcasts/"><u>[Updated] Correcting Muted Voice in OBS Broadcasts</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-how-to-make-any-fb-video-pop-with-full-screen-mode/"><u>2024 Approved  How to Make Any FB Video Pop with Full-Screen Mode</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-tackle-intermittent-fb-reels-display/"><u>[Updated] 2024 Approved  Tackle Intermittent FB Reels Display</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-quick-ways-to-reshuffle-youtube-tracks-on-pcphonetv/"><u>2024 Approved  Quick Ways to Reshuffle YouTube Tracks on PC/Phone/TV</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-choosing-the-right-time-for-music-top-rated-mp3-to-karaoke-tools-on-and-offline/"><u>New Choosing the Right Time for Music Top-Rated MP3 to Karaoke Tools, On and Offline</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-unveiling-the-best-5-audio-mixers-engineered-for-mac-enthusiasts/"><u>New Unveiling the Best 5 Audio Mixers Engineered for Mac Enthusiasts</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-the-ultimate-guide-to-subtitle-editing-on-mac-alternatives-to-subtitle-edit/"><u>In 2024, The Ultimate Guide to Subtitle Editing on Mac Alternatives to Subtitle Edit</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-revenue-riches-masterful-methods-for-monetizing-on-mobile-youtube/"><u>2024 Approved  Revenue Riches  Masterful Methods for Monetizing on Mobile YouTube</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-elevating-positivity-in-a-constructive-space/"><u>[New] 2024 Approved  Elevating Positivity in a Constructive Space</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-how-to-edit-youtube-videos-in-windows-movie-maker/"><u>[New] 2024 Approved  How to Edit YouTube Videos in Windows Movie Maker</u></a></li>
</ul></div>
