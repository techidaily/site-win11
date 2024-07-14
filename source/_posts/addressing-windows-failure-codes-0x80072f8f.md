---
title: "Addressing Windows Failure Codes: 0X80072f8f"
date: 2024-07-13T10:32:51.193Z
updated: 2024-07-14T10:32:51.193Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Addressing Windows Failure Codes: 0X80072f8f"
excerpt: "This Article Describes Addressing Windows Failure Codes: 0X80072f8f"
keywords: Win Error Code Fixation,Resolve 0X80072f8F,Windows Failure Diagnosis,Debugging XP Error,Xbox Error Correction,Windows Error Solver,Zeroing Out Error Halt
thumbnail: https://thmb.techidaily.com/fb8053ac7214659fa378f042df998d4365da978dd3a640439d6ee68045b0a185.jpg
---

## Addressing Windows Failure Codes: 0X80072f8f

 The Windows Media Creation Tool prepares installation media for upgrading your PC or creating a USB drive to perform a clean Windows installation. It is the perfect tool to make sure you are using the latest Windows version and is quite easy to use.

 However, there are times when users can run into errors while using the Media Creation Tool. One such error is the error code 0x80072f8f – 0x20000, which appears when users attempt to launch the MediaCreationTool.exe file.

 Below, you will find several effective troubleshooting methods that will help you fix this issue in no time.

## 1\. Run the Media Creation Tool as an Administrator

 Certain programs and processes on Windows operating system need administrative privileges to perform their jobs properly. If they are not allowed these extra permissions, you are likely to run into error codes such as this one.

 So, the first thing that you need to do if you encounter the error code 0x80072f8f - 0x20000 upon attempting to use the Media Creation Tool is to launch the file as an administrator. If insufficient permissions are causing the problem, this should fix it without you having to go through any of the complex troubleshooting methods.

Follow these steps to run the file as administrator:

1. Right-click on the targeted file and select**Run as administrator** from the context menu.  
![Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/run-as-administrator-1.jpg)
2. Click**Yes** in the confirmation prompt and check if the file runs without any issues now.  
![Yes button in UAC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/user-account-control-yes.jpg)

 If the error persists, it indicates that there is another cause behind it. In that case, proceed with the next method.

## 2\. Use a Different USB Port

 Often, faulty ports cause issues during the creation of the installation media. There are [several ways to test if the USB port is faulty](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) . You can begin by switching to another port and checking if the USB works fine there.

 You can also try using the same USB on another device and see if it works fine there.

## 3\. Modify the Windows Registry

 Making some changes in the Windows Registry to allow Media Creation Tool to run smoothly is another potential fix that you can try.

 Windows Registry is an administrative-level, powerful utility that stores information about the programs and processes of your operating system. The information here is stored as keys and values. You can modify the relevant keys/values to customize the processes of your system, which is exactly what we are going to do in this method.

 However, before you proceed with this method, we highly recommend [creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will help you restore the current state of your system in case anything goes wrong during the process.

When you have created a backup, follow these steps.

1. Press**Win** +**R** to open a Run dialog.
2. Type**regedit** in Run and click**Enter** .  
![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/regedit.jpg)
3. Once you are inside the Registry Editor, navigate to the location mentioned below:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsUpdate\Auto Update`
4. Right-click in an empty area in the right pane and select**New** \>**DWORD (32-bit) Value** from the context menu.  
![New DWORD value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/auto-update-new-dword.jpg)
5. Name this value as**AllowOSUpgrade** .  
![AllowOSUpgrade value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/allow-os-upgrade.jpg)
6. Double-click on**AllowOSUpgrade** and type**1** under Value data.  
![Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/allow-os-upgrade-value-data.jpg)
7. Hit**OK** and close the Registry Editor.

 You can now restart your PC and upon reboot, check if the Media Creation Tool works fine.

## 4\. Delete the Content of the Software Distribution Folder

 Another solution that worked for users was deleting the contents of the Software Distribution folder. This folder contains temporary files that might be interfering with the process of the Media Creation Tool.

 If this scenario is applicable, deleting the contents of the Software Distribution folder by following the steps below should do the trick for you.

1. Launch File Explorer and navigate to the location below:  
`C:\Windows\SoftwareDistribution\Download`  
![Software Distribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/software-distribution-download.jpg)
2. Select all the contents of the Download folder and right-click on them.
3. Click on the**bin icon** in the context menu to delete them.  
![Delete icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/delete-download.jpg)
4. Once you delete the files, type**cmd** in the search area of the taskbar and select**Run as administrator** .
5. Type the following command in the Command Prompt window and hit**Enter** .  
`wuauclt.exe /updatenow`  
![wuauclt.exe command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/wuauclt-exe-updatenow.jpg)
6. Then, restart your PC and try launching Media Creation Tool again.

## 5\. Enable Relevant Services

 Programs and processes on the Windows operating system require relevant services to be functioning to work. If any of the relevant services are disabled or corrupt, the program will fail to function.

 For instance, the Windows Update process requires the Windows Update service to run. If the settings of this service are not configured properly, you will fail to install the latest updates.

 Similarly, Media Creation Tool is related to the following services, and they should be working fine for you to use it:

* Windows Update
* Background Intelligent Transfer Service
* Server
* Workstation
* TCP/IP NetBIOS Helper
* IKE and AuthIP IPsec Keying Modules

 In this method, we will make sure that these services are configured accurately, and we will be using the Windows Update service to demonstrate the steps.

1. Open a Run dialog by pressing**Win** +**R keys** .
2. Type**services.msc** in the dialog and hit**Enter** . This should launch Windows Services.
3. In the following window, right-click on the**Windows Update** service and choose**Properties** from the context menu.
4. ![Windows update service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/services-windows-update-properties.jpg)
5. In the Properties dialog, change the Startup type to**Automatic** .  
![Startup type as automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/startup-type-automatic.jpg)
6. If the service is stopped, click on the**Start button** and select**Apply** \>**OK** to save the changes.  
![Start button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/start-service-status.jpg)
7. Repeat the same steps for the rest of the above-mentioned services.

 Once done, check if you can run the Media Creation Tool without any issues now.

## 8\. Perform a Clean Boot

 The issue can also arise due to a driver or software conflict within the system. To check if this is the case, you can perform a clean boot to launch the system with a minimal set of drivers and startup programs. If the issue does not appear in this mode, then it implies that a background process or driver is indeed causing the problem. You can then take necessary steps to remove it from the system.

Here is how you can perform a clean boot in Windows:

1. Press the Win + R keys together to open Run.
2. Type msconfig in the text field of Run and click Enter.
3. In the System Configuration window, head over to the**Services** tab and checkmark the box for**Hide all Microsoft services** .  
![Hide all Microsoft services option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/msconfig-hide-all-msservices.jpg)
4. Click on the**Disable all button** .
5. Now, navigate to the**Startup** tab and click on**Open Task Manager** .  
![Open the Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/startup-open-task-manager.jpg)
6. In the Startup tab, right-click on all the items and choose**Disable** .  
![Click on the Disable button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disable-program.jpg)
7. Once done, close the Task Manager and go back to the System Configuration window.
8. Click**Apply** \>**OK** to save the changes.
9. Finally, restart your computer.

 If the error code 0x80072f8f - 0x20000 is not present after a clean boot, it suggests that the issue was caused by a software or driver conflict. If this situation is applicable, you can either manually remove the recently installed software that you think might be leading to the issue, or [perform a system restore](https://www.makeuseof.com/tag/windows-system-restore-works/) to return to an older functioning state of the system.

## 7\. Disable Your Antivirus

 If you are using a third-party antivirus in Windows, there is a chance that it is blocking the process of Media Creation Tool because of a false alarm. To check if this is the case, you can disable or uninstall your antivirus and then run the Media Creation Tool.

 If the antivirus program is the culprit, then we recommend switching to another similar service for better performance.

## Media Creation Tool Error, Now Resolved

 Media Creation Tool is undoubtedly one of the most useful and easy-to-use tools offered by Microsoft for Windows. The troubleshooting methods listed above will hopefully allow you to use it without any issues. If the error appears again, you can reach out to the official Microsoft support team and report the problem to them. Hopefully, they will be able to identify the exact cause of the issue and suggest you a fix accordingly.


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
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-streamlined-recording-of-academic-sessions-on-macs/"><u>[Updated] Streamlined Recording of Academic Sessions on Macs</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steam-service-failure-in-windows-11/"><u>Troubleshooting Steam Service Failure in Windows 11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-the-essence-of-a-memorable-video-conclusion-in-vimeo-for-2024/"><u>[New] The Essence of a Memorable Video Conclusion in Vimeo for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-ultimate-mac-device-visuals-and-acoustics-in-one/"><u>2024 Approved  Ultimate Mac Device  Visuals & Acoustics in One</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-cross-platform-soundtrack-strategy-for-facebook-profiles/"><u>[New] Cross-Platform Soundtrack Strategy for Facebook Profiles</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-freebies-best-media-centers-for-windows-users/"><u>Top 7 Freebies: Best Media Centers for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-broken-usb-connections-on-windows-systems/"><u>Tackling Broken USB Connections on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-deletion-warning-settings-on-pcs/"><u>Navigating Deletion Warning Settings on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-requested-operation-requires-elevation-error-740-on-windows-10-and-11/"><u>How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-redirecting-onedrive-storage-location/"><u>Win 11 - Redirecting OneDrive Storage Location</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-note-placement-in-the-windows-desktop/"><u>Navigating Note Placement in the Windows Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-implications-of-removing-windows-11s-taskbar-chatting-capability-on-you/"><u>Unpacking the Implications of Removing Windows 11'S Taskbar Chatting Capability on You</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-directory-is-not-empty-error-0x80070091-in-windows-11-and-11/"><u>How to Fix the “Directory Is Not Empty” Error 0X80070091 in Windows 11 & 11</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ultimate-guide-to-get-the-meltan-box-pokemon-go-for-realme-gt-5-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate guide to get the meltan box pokemon go For Realme GT 5 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-troubles-with-admin-managed-chromeedge-browsers-for-workstations/"><u>Navigating Troubles with Admin-Managed Chrome/Edge Browsers for Workstations</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-how-to-convert-time-lapse-to-normal-video/"><u>Updated How to Convert Time-Lapse to Normal Video</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-file-explorers-gallery-view-capability/"><u>Unlocking File Explorer's Gallery View Capability</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-removing-the-isdonedll-issue-on-w11/"><u>Quick Fix Guide: Removing the ISDone.dll Issue on W11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-elevated-commands-always-access-terminal-as-admin/"><u>Mastering Elevated Commands: Always Access Terminal as Admin</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-quick-and-painless-podcast-go-live-technique/"><u>In 2024, The Quick and Painless Podcast Go Live Technique</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-video-editing-mastery-top-picks-for-apple-users-for-2024/"><u>Updated Video Editing Mastery Top Picks for Apple Users for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/why-and-how-to-choose-effective-encoders-on-your-pc/"><u>Why and How to Choose Effective Encoders on Your PC</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-audience-wow-factor-how-to-create-spectacular-live-streams/"><u>[Updated] Audience Wow Factor  How to Create Spectacular Live Streams</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-why-steam-cant-synch-files-in-pc-settings/"><u>Unraveling Why Steam Can't Synch Files in PC Settings</u></a></li>
<li><a href="https://win11.techidaily.com/saving-yourself-from-install-error-in-discord-set-up/"><u>Saving Yourself From Install Error in Discord Set-Up</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-correct-video-brightness-issues-with-these-top-rated-editors-for-2024/"><u>Updated Correct Video Brightness Issues with These Top-Rated Editors for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quickfire-tips-for-unbeatable-win-cs-speed/"><u>Quickfire Tips for Unbeatable Win CS Speed</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-user-administration-in-windows-11/"><u>Streamlining User Administration in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-nonexistent-hardware-warning-in-windows/"><u>Overcoming Nonexistent Hardware Warning in WIndows</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-pcs-idle-state-with-scheduled-shutdowns/"><u>Optimize Your PC's Idle State with Scheduled Shutdowns</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-understanding-and-implementing-discord-text-styles/"><u>[Updated] In 2024, Understanding & Implementing Discord Text Styles</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-elevate-your-youtube-livestream-game-plan/"><u>[New] 2024 Approved  Elevate Your YouTube Livestream Game Plan</u></a></li>
<li><a href="https://win11.techidaily.com/reinvent-the-way-you-handle-aging-pcs-less-windows/"><u>Reinvent the Way You Handle Aging PCs: Less Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/quick-steps-to-elevate-low-quality-webcam-vids/"><u>Quick Steps to Elevate Low-Quality WebCam Vids</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-11-pro-passcode-screen-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 11 Pro Passcode Screen? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-motorola-moto-g-stylus-2023-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Motorola Moto G Stylus (2023)? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-mastery-in-artificially-inspired-visuals-using-paint-cocreator-on-win11/"><u>Step-by-Step Mastery in Artificially Inspired Visuals Using Paint Cocreator on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-bluetooth-mouse-blackout-on-windows-systems/"><u>Overcoming Bluetooth Mouse Blackout on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-browser-blues-overcome-site-blockades-with-these-tips/"><u>Microsoft Browser Blues? Overcome Site Blockades with These Tips</u></a></li>
</ul></div>
