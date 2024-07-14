---
title: Troubleshooting Gaps in System's Startup List
date: 2024-07-13T10:21:09.158Z
updated: 2024-07-14T10:21:09.158Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Gaps in System's Startup List
excerpt: This Article Describes Troubleshooting Gaps in System's Startup List
keywords: Startup Error Solving,Systems Boot Issues Fix,Repairing System Fail-to-Start,Resolve Booting Delays,Addressing System Start Gaps,Troubleshoot Boot List Lapses,Fix Startup Loopbacks
thumbnail: https://thmb.techidaily.com/f51042103ff6c3f87c92a84096e29bdaf9eccd433a92cd047a35aea4a9510783.jpg
---

## Troubleshooting Gaps in System's Startup List

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
<li><a href="https://win11.techidaily.com/decoding-the-functionality-of-law-filters-for-windows-users/"><u>Decoding the Functionality of LAW Filters for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-spot-and-defeat-keygen-malware-in-your-windows-os-environment/"><u>How to Spot & Defeat Keygen Malware in Your Windows OS Environment</u></a></li>
<li><a href="https://win11.techidaily.com/first-steps-in-windows-11-here-are-top-8-blunders-to-evade/"><u>First Steps in Windows 11? Here Are Top 8 Blunders to Evade</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-inspecting-and-cleaning-windows-logs/"><u>Mastering the Art of Inspecting & Cleaning Windows Logs</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-file-examination-in-win1011-with-new-tool-integration/"><u>Elevate File Examination in Win10/11 with New Tool Integration</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-strategies-for-background-blur-perfection-using-windows-11-photos-app/"><u>In-Depth Strategies for Background Blur Perfection Using Windows 11 Photos App</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mirthful-melodies-top-downloads-for-tones-for-2024/"><u>Mirthful Melodies  Top Downloads for Tones for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-upgrade-error-0xc004f050/"><u>How to Fix the Windows Upgrade Error 0Xc004f050</u></a></li>
<li><a href="https://win11.techidaily.com/guide-on-stopping-discords-autostart-and-updating-habits/"><u>Guide on Stopping Discord's Autostart & Updating Habits</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-the-pros-way-of-recording-movs-effectively-on-windows-10/"><u>[Updated] 2024 Approved  The Pro's Way of Recording MOVs Effectively on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correcting-discord-setup-mistakes-in-win-11/"><u>Guide to Correcting Discord Setup Mistakes in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/deciphered-doorkeeper-no-swift-shift-to-new-solution/"><u>Deciphered Doorkeeper? No Swift Shift to New Solution</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-blending-words-with-pictures-adding-text-to-images-windowsmac/"><u>2024 Approved  Blending Words with Pictures  Adding Text to Images, Windows/Mac</u></a></li>
<li><a href="https://win11.techidaily.com/modify-mouse-indicator-for-personalized-windows-experience/"><u>Modify Mouse Indicator for Personalized Windows Experience</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-absent-bluetooth-listings-on-pc-device-manager/"><u>Fixing Absent Bluetooth Listings on PC Device Manager</u></a></li>
<li><a href="https://win11.techidaily.com/getting-started-the-windows-11-guide-to-altering-fax-cover-pages/"><u>Getting Started: The Windows 11 Guide to Altering Fax Cover Pages</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-decrypting-the-mystery-understanding-unlisted-content-on-youtube-for-2024/"><u>[Updated] Decrypting the Mystery  Understanding 'Unlisted' Content on YouTube for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fresh-start-on-walls-top-3-techniques/"><u>Fresh Start on Walls: Top 3 Techniques</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-journey-into-the-art-of-long-exposure-a-comprehensive-guide-to-gopro-timelapses/"><u>2024 Approved  Journey Into the Art of Long-Exposure  A Comprehensive Guide to GoPro Timelapses</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-address-blue-screen-wins-unhandled-exception/"><u>How to Address Blue Screen: Win's Unhandled Exception</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-linuxs-power-to-boost-android-on-windows/"><u>Leveraging Linux's Power to Boost Android on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/in-depth-exploration-of-neglected-windows-11-capabilities/"><u>In-Depth Exploration of Neglected Windows 11 Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-tech-connection-winpc-galaxy-with-flow-app/"><u>Empowering Tech Connection - WinPC, Galaxy with Flow App</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-external-hard-drive-access-in-windows/"><u>Controlling External Hard Drive Access in Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/enhancing-videos-pc-and-mobile-filter-integration/"><u>Enhancing Videos  PC & Mobile Filter Integration</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-fixing-error-0x80073cf3-on-marketplace/"><u>Deciphering and Fixing Error 0X80073CF3 on Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-the-mechanics-guaranteeing-a-glitch-free-gaming-experience/"><u>Mastery of the Mechanics: Guaranteeing a Glitch-Free Gaming Experience</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-spearheading-social-media-select-the-best-video-editors-for-ig/"><u>2024 Approved  Spearheading Social Media  Select the Best Video Editors for IG</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-htc-u23-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For HTC U23 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-single-board-compatible-with-windows/"><u>Exclusive Single-Board Compatible with Windows</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-revolutionize-your-online-audio-with-these-5-methods/"><u>[New] 2024 Approved  Revolutionize Your Online Audio with These 5 Methods</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-about-vivo-v27-frp-bypass-by-drfone-android/"><u>In 2024, About Vivo V27 FRP Bypass</u></a></li>
</ul></div>
