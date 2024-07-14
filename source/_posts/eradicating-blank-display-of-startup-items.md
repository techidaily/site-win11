---
title: Eradicating Blank Display of Startup Items
date: 2024-07-13T09:53:12.653Z
updated: 2024-07-14T09:53:12.653Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eradicating Blank Display of Startup Items
excerpt: This Article Describes Eradicating Blank Display of Startup Items
keywords: Removing Startup Clutter,Disable Unnecessary Apps,Optimize Boot Windows,Clean Startup Settings,Minimize Launch Delays,Speed Up System Boot,Eliminate Background Programs
thumbnail: https://thmb.techidaily.com/38a7a5c0a5123e7708eb11aa967d228491b39460885352e6b8c3f7846969574b.jpg
---

## Eradicating Blank Display of Startup Items

 While using the Windows Task Manager, you may suddenly come across an error message that reads, “There are no startup items to display in Task Manager.” It's a confusing error message, but don't fret; it's very easy to fix.

 Let’s check out the best ways to fix Task Manager's "no startup items" error.

## 1\. Restart File Explorer

 Restarting File Explorer is one of the easiest ways to resolve this issue. The best way to do this is to restart your Windows PC completely.

 If that doesn’t resolve the problem, or you'd rather not restart your PC, you can restart File Explorer through these steps:

1. Press**Win + X** to open the Quick Access menu.
2. Select**Task Manager** from the options.
3. Right-click on the**Windows Explorer** option and then select**Restart** .

![Restarting the Windows File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Restarting-the-Windows-File-Explorer.jpg)

## 2\. Create a New Startup Folder

 In some cases, you’d run into the issue at hand if the startup folder is corrupted. So, the best way to resolve the problem is to create a new startup folder.

Now, here are the steps for creating a new startup folder on Windows:

1. Press**Win + E** to open File Explorer.
2. Copy-paste the command into the File Explorer address bar and press**Enter** :

`C:\Users\%username%\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\`

From there, follow these steps:

1. Locate and delete the**Startup folder** .
2. Create a new startup folder by right-clicking on a blank space and selecting**New > Folder** .
3. Name the folder as**Startup** and press**Enter** .

![Selecting the Startup folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/selecting-the-startup-folder.jpg)

Finally, restart your device to save these changes.

## 3\. Perform a Check Disk Scan

![An illustration of a lens scanning digital devices](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-a-lens-scanning-digital-devices.jpg)

 There’s a possibility that the issue at hand might be caused by system issues. In such instances, scanning and repairing your device’s hard drive could help.

 Here’s how you can resolve the problem using a Check Disk (CHKDSK) scan:

1. Type**Command Prompt** in the Start menu search bar.
2. Right-click on the**Best match** result and select**Run as administrator** .
3. Type the following command and then press**Enter** to scan and repair your hard drive:

`chkdsk C: /f`

 If your Windows operating system (OS) is installed on a different drive, then replace**C:** in the command with the letter of the relevant drive.

Finally, restart your device when the scan is complete.

## 4\. Scan and Repair Windows Using the DISM and SFC Tools

![Computer antivirus illustration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/08/Computer-antivirus-illustration.jpg)

 If a normal disk scan doesn’t help, then you’d need to scan and repair your hard drive using advanced tools such as DISM and SFC. As we covered in our guide on [how to repair corrupted files with built-in Windows tools](https://www.makeuseof.com/windows-built-in-repair-tools/) , DISM and SFC are handy services that can help repair Windows errors.

Let’s start by checking out how you can run the DISM tool:

1. Press**Ctrl + Shift + Esc** to open the Task Manager.
2. Click**File** in the top-left corner and select**Run new task** .
3. Type**CMD** and then check the**Create this task with administrative privileges** box.
4. Press**OK** to run the Command Prompt.
5. Type the following command and press**Enter** :

`DISM /Online /Cleanup-Image /ScanHealth`

 Wait for the process to complete. From there, type the following command and press**Enter** :

`DISM /Online /Cleanup-Image /RestoreHealth`

Finally, restart your device once the DISM scan is complete.

Now, you can run the SFC tool through these steps:

1. Open the**Command Prompt** by following the previous steps.
2. Type the following command and press**Enter** to run the scan:

`sfc /scannow`

Wait for the scan to complete and then restart your device.

## 5\. Run the System Maintenance Troubleshooter

![An illustration of someone configuring settings on a PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-someone-configuring-settings-on-a-PC.jpg)

 Still struggling to resolve the issue? If so, you might be experiencing a system maintenance problem. In this case, you could tackle the error by running the System Maintenance troubleshooter.

Here are the steps you need to follow:

1. Type**Perform recommended maintenance tasks automatically** in the Start menu search bar and press**Enter** .
2. Click the**Next** button and then follow the on-screen instructions.

![Running the System Maintenance Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Running-the-System-Maintenance-Troubleshooter-on-Windows.jpg)

Wait for the process to complete and then restart your PC.

## 6\. Temporarily Disable the Windows Defender Firewall

 In some instances, temporarily disabling the Windows Defender Firewall could tackle the problem. However, don’t forget to re-enable the tool later.

Now, here are the steps for disabling the Windows Defender Firewall:

1. Type**Control Panel** in the Start menu search bar and select the**Best match** .
2. Click the**View by** drop-down menu and then select**Large icons** .
3. Select**Windows Defender Firewall** from the options.
4. Click the**Turn Windows Defender Firewall on and off** option.

![Selecting the Turn Defender Firewall on or off option on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Selecting-the-Turn-Defender-Firewall-on-or-off-option-on-Windows.jpg)

 Locate the**Domain** ,**Private** , and**Public network settings** and then check the**Turn off Windows Defender Firewall** boxes next to them. Finally, press**OK** and then restart your computer.

![Turning off the Defender Firewall on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/Turning-off-the-Defender-Firewall-on-Windows.jpg)

## 7\. Use a System Restore Point

 Using a system restore point can help you tackle the issue at hand. However, this approach will only help if you’ve already learned [how to create a system restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) and made one.

 During the restoration process, the system restore tool will revert your PC to a previous state. As such, this tool will help only if the Task Manager error only started appearing recently.

 Here’s how you can tackle the issue at hand using a restore point:

1. Type "Create a restore point" in the Start menu search bar and select the**Best match** .
2. Click the**System Protection** tab and then select**System Restore** from the options.
3. Press**Next** to continue.
4. Select**Show more restore points** and then pick a restore point.
5. Click**Next** and then click**Finish** to finalize the process.

![Using a Restore Point on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/Using-a-Restore-Point-on-Windows.jpg)

## 8\. Update Your Device

 In some instances, updating your Windows device might be the best solution. Ideally,[you should always update Windows to the latest version](https://www.makeuseof.com/windows-update-new-version-releases-reasons/) , but if you've put it off for a while, try updating your PC.

Here are the steps for updating Windows:

1. Type**Settings** in the Start menu search bar and select the**Best match** .
2. Select**Update & Security** from the options.
3. Select the**Windows Update** option on the left.
4. Click the**Check for updates** button on the right and then follow the on-screen steps.

![Checking for Windows PC updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/03/9-Checking-for-Windows-PC-updates.jpg)

## You’ve Successfully Resolved Your Task Manager Issues

 The Task Manager is a reliable tool that helps you close slow programs and improve your PC’s performance. However, this tool also often runs into various problems. If it's experiencing issues with startup programs, you can easily resolve the error using any of the solutions in this article.

 If the issue persists, then maybe it’s time to start exploring some Task Manager alternatives.


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
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-is-mega-mewtwo-the-strongest-pokemon-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Is Mega Mewtwo The Strongest Pokémon On Apple iPhone 13 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-battery-life-win-1011-tips/"><u>Ace Your Battery Life: Win 10/11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11s-system32-folder/"><u>Accessing Windows 11'S System32 Folder</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-ctrl-lock-up-in-windows-11-environments/"><u>Addressing Ctrl Lock-Up in Windows 11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-operational-windows-rules-in-office-365/"><u>Addressing Non-Operational Windows Rules in Office 365</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-frozen-menu-items-in-windows-11-desktop/"><u>Addressing Frozen Menu Items in Windows 11 Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/activating-the-action-center-mixer-for-clear-windows-sounds/"><u>Activating the Action Center Mixer for Clear Windows Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-how-windows-11-manages-your-files-a-look-at-its-recovery-system/"><u>Analyzing How Windows 11 Manages Your Files: A Look at Its Recovery System</u></a></li>
<li><a href="https://win11.techidaily.com/android-ios-direct-pc-file-access/"><u>Android-iOS: Direct PC File Access</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-operation-failed-0x0000011b-in-windows/"><u>Overcoming Operation Failed 0X0000011B in Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-windows-10-video-trimmer-showdown-top-10-free-options/"><u>New Windows 10 Video Trimmer Showdown Top 10 Free Options</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-cannot-locate-gpeditmsc-error-in-windows/"><u>Addressing the Cannot Locate Gpedit.msc Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-11-no-response-to-click-events/"><u>Tackling Windows 11: No Response to Click Events</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11s-unresponsive-wi-fi-detection/"><u>Addressing Windows 11'S Unresponsive Wi-Fi Detection</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failure-in-recent-windows-discord-upgrades/"><u>Addressing Failure in Recent Windows Discord Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-correcting-error-0x80004004-on-defender/"><u>Deciphering and Correcting Error 0X80004004 on Defender</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-win-1011s-error-0x8007045d/"><u>Addressing Win 10/11'S Error 0X8007045D</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-ms-store-error-x7326/"><u>Addressing Windows 11 MS Store Error X7326</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-device-not-found-problems-in-windows/"><u>Addressing 'Device Not Found' Problems in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-action-plan-9-steps-to-stop-wwe-crashes-in-windows/"><u>Accelerated Action Plan: 9 Steps to Stop WWE Crashes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-your-download-experience-with-epic-launcher/"><u>Accelerating Your Download Experience with Epic Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-windows-partition-management-tactics/"><u>Advanced Windows Partition Management Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-disk-fragmentation-issue/"><u>Addressing Windows Disk Fragmentation Issue</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-unsuccessful-java-vm-startup/"><u>Addressing the Unsuccessful Java VM Startup</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/lens-legends-top-six-selecting-high-quality-4k-dslrs-for-2024/"><u>Lens Legends' Top Six  Selecting High-Quality 4K DSLRs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/alternative-solutions-starting-your-software-on-windows-effortlessly/"><u>Alternative Solutions: Starting Your Software on Windows Effortlessly</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/accidental-tiktok-refresh-recover-your-content/"><u>Accidental TikTok Refresh - Recover Your Content?</u></a></li>
<li><a href="https://win11.techidaily.com/keyboardmouse-wake-issues-fix-for-win11-users/"><u>Keyboard/Mouse Wake Issues: Fix for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-playback-how-to-start-windows-media-player/"><u>Initiating Playback - How to Start Windows Media Player</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-back-lost-contacts-from-zero-30-5g-by-fonelab-android-recover-contacts/"><u>How to get back lost contacts from Zero 30 5G.</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-windowed-app-repositioning-techniques/"><u>Avoidance of Windowed App Repositioning Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failed-downloads-in-windows-environments/"><u>Addressing Failed Downloads in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-tabs-on-pc-login-separating-goals-from-errors/"><u>Keeping Tabs on PC Login: Separating Goals From Errors</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/conquer-joining-on-tiktok-with-confidence-and-flair-for-2024/"><u>Conquer Joining on TikTok with Confidence and Flair for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-full-compatibility-with-ios-events-in-windows/"><u>Achieving Full Compatibility with iOS Events in Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-14-pro-to-other-iphone-12-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 14 Pro to other iPhone 12 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/audioscape-refresh-on-windows-the-driver-upgrade-path/"><u>Audioscape Refresh on Windows: The Driver Upgrade Path</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-top-7-must-try-iphone-vr-experiences-you-cant-miss-for-2024/"><u>[Updated] Top 7 Must-Try iPhone VR Experiences You Can’t Miss for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-type-speed-cutting-down-lag-on-windows-11/"><u>Accelerating Type Speed: Cutting Down Lag on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-chkdsk-sfc-and-dism-for-system-repairing/"><u>Decoding CHKDSK, SFC & DISM for System Repairing</u></a></li>
<li><a href="https://win11.techidaily.com/augment-win11-notebook-with-smart-companion/"><u>Augment Win11 Notebook with Smart Companion</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-internal-portaudio-errors-in-audacity-windows-11/"><u>Addressing Internal PortAudio Errors in Audacity (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cannot-preview-error-with-microsoft-office-outlook/"><u>Resolving 'Cannot Preview' Error with Microsoft Office Outlook</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-cut-mkv-files-for-free-top-10-editor-recommendations/"><u>Updated Cut MKV Files for Free Top 10 Editor Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-common-setbacks-when-launching-csgo-on-w11/"><u>Avoiding Common Setbacks When Launching CS:GO on W11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-pioneering-the-future-workplace-through-virtual-tech/"><u>In 2024, Pioneering the Future Workplace Through Virtual Tech</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-for-managing-packages-via-winget-on-win11/"><u>Advanced Techniques for Managing Packages via Winget on Win11</u></a></li>
</ul></div>
