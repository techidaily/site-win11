---
title: "Win11 Audit: Steps for Default User Permission Reset"
date: 2024-06-25T10:06:10.705Z
updated: 2024-06-26T10:06:10.705Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win11 Audit: Steps for Default User Permission Reset"
excerpt: "This Article Describes Win11 Audit: Steps for Default User Permission Reset"
keywords: Win11 PrivilegeReset,AdminUserAuditWin,DefaultPermResetWin,Win11UserPermission,AuditDefaultPrivileges,ResetWin11UserRights,Win11AccessControl
thumbnail: https://thmb.techidaily.com/934c09a684ad314c00e00ed21a2e7539ae4858551b2266da80c837988bee503d.jpg
---

## Win11 Audit: Steps for Default User Permission Reset

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
<li><a href="https://win11.techidaily.com/restart-windows-paper-processor/"><u>Restart Windows' Paper Processor</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-battlenet-desktop-client-successfully/"><u>How to Reactivate Battle.net Desktop Client Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-overscan-in-windows-enhance-screen-fit/"><u>Fixing Overscan in Windows - Enhance Screen Fit</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-screen-interaction-proficient-use-of-windows-narrator-shortcuts/"><u>Streamlined Screen Interaction: Proficient Use of Windows Narrator Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-winget-a-guide-for-windows-11-users/"><u>Reviving Winget: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-missing-window-panes-with-win11-6-tips/"><u>Reclaiming Missing Window Panes with Win11 (6 Tips)</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-gpu-functionality-in-windows-10-and-11-easy-fixes/"><u>Refreshing GPU Functionality in Windows 10 & 11 Easy Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-vm-management-hosting-linux-on-a-windows-system-with-hyper-v/"><u>Efficient VM Management: Hosting Linux on a Windows System with Hyper-V</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-capture-clarity-top-10-photo-lens-selections/"><u>[Updated] Capture Clarity  Top 10 Photo Lens Selections</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/come-and-pick-best-mov-to-gif-converters-for-2024/"><u>Come And Pick! Best MOV to GIF Converters for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-affordable-subscriber-boost-buy-and-sell-youtube-views-for-2024/"><u>[Updated] Affordable Subscriber Boost  Buy & Sell YouTube Views for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-srt-file-conversion-simplified-with-os-support/"><u>[Updated] SRT File Conversion Simplified with OS Support</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-activation-lock-and-icloud-account-from-apple-iphone-12-pro-by-drfone-ios/"><u>How to Unlock iCloud Activation Lock and iCloud Account From Apple iPhone 12 Pro?</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/igtv-to-fb-broadcast-optimal-sharing-strategies/"><u>IGTV to FB Broadcast  Optimal Sharing Strategies</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-15-best-game-recording-software-for-youtuber-for-2024/"><u>[Updated] 15 Best Game Recording Software for YouTuber for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-rise-and-shine-wondershare-filmora-easter-sale-brings-you-unbeatable-offers/"><u>2024 Approved Rise and Shine Wondershare Filmora Easter Sale Brings You Unbeatable Offers</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-10plus-royalty-free-5-second-countdown-footage-hd-and-4k-clips-included/"><u>Updated In 2024, 10+ Royalty-Free 5 Second Countdown Footage HD & 4K Clips Included</u></a></li>
</ul></div>
