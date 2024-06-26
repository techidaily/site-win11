---
title: "Purging Power Users: The Guide to Default Settings"
date: 2024-06-25T10:26:40.463Z
updated: 2024-06-26T10:26:40.463Z
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
<li><a href="https://win11.techidaily.com/how-to-fix-this-app-has-been-blocked-by-your-system-administrator-error-in-windows/"><u>How to Fix This App Has Been Blocked by Your System Administrator Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-unseen-power-in-photo-erasing-on-windows/"><u>The Unseen Power in Photo Erasing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-mitigating-roblox-error-403-for-pc-users/"><u>Understanding & Mitigating Roblox Error 403 for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-11-tablet-bar-accessibility/"><u>Maximizing Windows 11 Tablet Bar Accessibility</u></a></li>
<li><a href="https://win11.techidaily.com/the-best-file-sharing-software-on-windows-os/"><u>The Best File-Sharing Software on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-your-touchscreen-experience-on-a-windows-11-machine/"><u>Maximize Your Touchscreen Experience on a Windows 11 Machine</u></a></li>
<li><a href="https://win11.techidaily.com/countering-dxgideviceremoved-failsafe-techniques/"><u>Countering DXGI_DEVICE_REMOVED Failsafe Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/diminish-windows-volume-amplification-effects/"><u>Diminish Windows Volume Amplification Effects</u></a></li>
<li><a href="https://win11.techidaily.com/changing-windows-read-only-settings-easily/"><u>Changing Windows Read-Only Settings Easily</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-chromebooks-finest-top-10-free-video-editors-you-need-to-try/"><u>New In 2024, Chromebooks Finest Top 10 Free Video Editors You Need to Try</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-unlock-better-communication-navigating-through-the-top-7-android-voice-enhancement-software-for-2024/"><u>New Unlock Better Communication Navigating Through the Top 7 Android Voice Enhancement Software for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-asus-rog-phone-8-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Asus ROG Phone 8 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-20-essentials-every-new-creator-should-own-for-2024/"><u>[Updated] 20 Essentials Every New Creator Should Own for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-balancing-content-creation-and-employment/"><u>2024 Approved  Balancing Content Creation and Employment</u></a></li>
<li><a href="https://change-location.techidaily.com/ultimate-guide-to-catch-the-regional-located-pokemon-for-samsung-galaxy-a25-5g-drfone-by-drfone-virtual-android/"><u>Ultimate Guide to Catch the Regional-Located Pokemon For Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-pioneering-techniques-to-improve-your-fb-video-ad-effectiveness/"><u>[Updated] 2024 Approved  Pioneering Techniques to Improve Your FB Video Ad Effectiveness</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-iphone-7-plus-online-without-jailbreak-by-drfone-ios/"><u>In 2024, How to Unlock SIM Card on iPhone 7 Plus online without jailbreak</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/flip-the-script-mastering-instagram-video-replay/"><u>Flip the Script  Mastering Instagram Video Replay</u></a></li>
<li><a href="https://extra-hints.techidaily.com/journey-into-the-future-of-video-clarity-in-depth-vce-22-review/"><u>Journey Into the Future of Video Clarity - In-Depth VCE 2.2 Review</u></a></li>
</ul></div>
