---
title: Eliminating Pre-Use Disk Formatting Notice on Windows
date: 2024-06-25T11:32:41.356Z
updated: 2024-06-26T11:32:41.356Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Eliminating Pre-Use Disk Formatting Notice on Windows
excerpt: This Article Describes Eliminating Pre-Use Disk Formatting Notice on Windows
keywords: Win Disk Cleanup Guide,Remove Format Warning,Bypass FS Initialization,Windows File System Alert,Erase Pre-Use Notifications,Disable Formatting Notice,Skip Disk Setup on Windows
thumbnail: https://thmb.techidaily.com/6b70f639163cfe01d6518c08ef2693a5f686b7373d5c47d7a53f258bef450907.jpg
---

## Eliminating Pre-Use Disk Formatting Notice on Windows

 We use external flash drives and hard disks on a regular basis for file transfer and sharing. While cloud sharing is gaining popularity, physical disk sharing is still best suited for large or personal files. You can connect multiple USB devices on your system at the same time and move data from one drive to others.

 But some users encounter the "You Need To Format The Disk In Drive before you can use it" error. It forces you to format the disk before you can use it. However, it isn’t a sensible option if you have important files on the disk. We will list multiple methods using which you can reassess your disk drive. Let’s begin.

## What Are the Reasons Behind the Error Message?

 You can see the “Format Disk in drive” message due to one or more of the following reasons:

1. The USB drive or the port is malfunctioning.
2. The device drivers of the disk are corrupt or outdated.
3. Malware is preventing access to the disk.
4. Core system files have gone missing or corrupt.
5. A third-party app is conflicting with system apps and services.

## Methods to Fix the “You Need to Format the Disk in Drive Before You Can Use It” Error

 Try out the following methods to fix the disk error message and save your data stored on it:

###

### 1\. Check the USB Drive

 If connecting the USB drive to any USB port on your system produces the same error, then unplug it. Connect it to another computer and check if it shows up in Device Manager and you can access the file contents without any issues. If it works, create a copy of all your data on that system for backup purposes.

### 2\. Perform a Complete Shutdown

[Microsoft enables Fast Start-up](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/) in newer versions of the Windows operating system by default. It hibernates the system and kernel-level processes so your system boots up faster after a shutdown.

 But if the core system services encounter a glitch and stop working properly, you will see the error message every time. So, performing a complete shutdown can help in restarting all core services.

Repeat the following steps:

1. Press**Win + R** to launch the Run command box.
2. Type**cmd** in the text input box and press**Ctrl + Shift + Enter** to open Command Prompt with administrator privileges.
3. Input the following command and press the enter key:**shutdown /s /f /t 0**  
![Perform a Complete Shutdown](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/perform-a-complete-shutdown.jpg)
4. It will take longer than usual for your system to shut down. Power it on again and open File Explorer.
5. Click on the USB disk and check if you are able to access the files on it.

### 3\. Do a Clean Boot

 Third-party applications and services can interfere with system apps and impede their normal functioning. So,[perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) of your system. It will disable all the third-party services and programs from running at startup. If you are able to access the disk now, repeat the clean boot process while enabling third-party services one by one to isolate the culprit program.

### 4\. Change the USB Drive Letter Using Disk Management

 Changing the drive letter could help in resolving the USB drive error on your system and make it accessible. Repeat the following steps to change the drive letter:

1. Press**Win + R** to open the Run dialog box. Type**diskmgmt.msc** and press the enter key.
2. In the Disk Management window, find your USB disk drive and right-click on it.
3. Select the**Change Drive Letter and Paths** option from the context menu.
4. Click on the**Change** button. Then, click on the**arrow** button to expand the drop-down list and select a drive letter from it.  
![Change the USB Drive Letter Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-the-usb-drive-letter-using-disk-management.jpg)
5. Lastly, click on the**OK** button. Reconfirm your decision and click on the**Yes** button to change the Drive letter.
6. You will see a system notification informing you about the Drive letter change and mounting the drive.
7. Press**Win + E** to open the File Explorer and check whether the USB drive is accessible or not.

### 5\. Scan the Hard Disk Using CHKDSK

 It is possible for the USB disk to contain bad files and sectors; due to which Windows asks you to format it before usage. But you can leverage the inbuilt CHKDSK utility to scan the USB disk for errors and fix them for you. It will scan all the files on the disk and repair the drive. You can either use the[command prompt method or Run CheckDisk](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) using the Properties window in File Explorer.

### 6\. Run an SFC and DISM Scan

 If the check disk doesn’t do any good, and you still have the error, it is possible that your system files are missing or corrupt.[Start with an SFC scan](https://www.makeuseof.com/system-file-checker-sfc-windows/) to check and replace any corrupt system files. Follow that up with a[DISM scan to fix the Windows installation image](https://www.makeuseof.com/difference-between-chkdsk-sfc-and-dism-in-windows-10/) . Make sure you have an active internet connection to run the DISM scan without any issues.

### 7\. Use a Linux Installation Media to Access the USB Disk Drive

 This method is more of a workaround to not lose your data. If you don’t have a second system nearby, you can[create a Linux installation media](https://www.makeuseof.com/tag/install-ubuntu-computer-using-usb-flash-drive/) and use the Try Ubuntu mode to mount and access the contents of the USB disk. It will save the effort of searching for another computer, and you can successfully create a backup of the USB disk.

 To access the USB disk using Linux installation media repeat the following steps:

1. Plug the Linux installation media into your system.
2. Press the**Esc** key and power on your system to enter the boot devices menu. Select the Linux installation media and boot it up.
3. In the Grub menu, select the**Try or install Ubuntu** option. Wait for the setup Window to launch and then click on the**Try Ubuntu** option.
4. Go to the left-hand side menu and click on the**Files** app.  
![Use a Linux Installation Media to Access the USB Disk Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/use-a-linux-installation-media-to-access-the-usb-disk-drive.jpg)
5. Click on the USB disk name in the navigation pane to open it. Now, you can copy these files to another location on your hard drive or an external hard disk.
6. After you finish copying the contents of the USB disk, click on the power icon and choose the Power off option to close the Try Ubuntu mode.

### 8\. Try Generic Fixes for Drive Formatting Issues

 If none of those worked, it's time to apply more general fixes before diving into more drastic measures. There are a few different error messages related to storage drive formatting issues that Windows can throw, and all of them share some common fixes.

 As such, check out[how to fix format disk errors on Windows without formatting your drive](<http://How> to Fix Format Disk Errors Without Formatting Your Hard Drive on Windows) for more tips.

### 9\. Reset Windows

 If nothing seems to work, and you see the error with every USB disk you try to connect to the system, consider a complete Windows reset. It will remove all your system files and installed apps (though you can choose to keep personal files on the system drive).

 However, before[performing a System Reset](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) , try[System Restore](https://www.makeuseof.com/windows-reset-system-restore-difference/) using any available System Restore points. If that fails, and a reset doesn't seem to work, you can[factory reset your Windows computer](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) .

## Access USB Disk Contents Without Formatting

 It is a bad idea to click on the Format button when File Explorer prompts you to do it to access the USB disk. Firstly, try to check the hardware malfunctions and salvage the data on the USB disk. You can use another system or create a Linux installation media to access files on the USB disk.

 If SFC and DISM fail to repair the system, and you still see the error with every USB disk you connect to your system, reset your Windows computer.

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
<li><a href="https://win11.techidaily.com/steps-for-troubleshooting-xbox-audio-failures-in-pcs/"><u>Steps for Troubleshooting Xbox Audio Failures in PCs</u></a></li>
<li><a href="https://win11.techidaily.com/the-guide-to-creating-a-unique-terminal-theme/"><u>The Guide to Creating a Unique Terminal Theme</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-ubiquitous-blue-screen-enigma/"><u>Overcoming the Ubiquitous Blue Screen Enigma</u></a></li>
<li><a href="https://win11.techidaily.com/best-7-free-players-for-your-pcs-viewing-pleasure-win/"><u>Best 7 Free Players for Your PC's Viewing Pleasure (Win)</u></a></li>
<li><a href="https://win11.techidaily.com/chrome-alert-disabling-windows-edition-tips/"><u>Chrome Alert Disabling: Windows Edition Tips</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-error-0x0000004e-on-windows-11-systems/"><u>Conquering Error 0X0000004E on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-game-bar-errors-due-to-weak-hardware/"><u>Fixing Game Bar Errors Due to Weak Hardware</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-efficiency-setting-up-shortcuts-for-fixed-text-paste-and-copy/"><u>Boost Your Efficiency: Setting Up Shortcuts for Fixed Text Paste & Copy</u></a></li>
<li><a href="https://win11.techidaily.com/struggling-with-game-installs-xbox-app-solutions/"><u>Struggling with Game Installs: Xbox App Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-error-windows-security-cut-by-admin-policies/"><u>Deciphering Error: Windows Security Cut by Admin Policies</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-say-goodbye-to-aspect-ratio-confusion-the-ultimate-facebook-video-guide/"><u>New Say Goodbye to Aspect Ratio Confusion The Ultimate Facebook Video Guide</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-the-pathway-to-reinvention-step-by-step-guide-on-altering-your-tiktok-handle/"><u>[New] In 2024, The Pathway to Reinvention  Step-by-Step Guide on Altering Your TikTok Handle</u></a></li>
<li><a href="https://discord-videos.techidaily.com/discords-best-sound-experience-unlocked-by-advanced-bot-technologies-for-2024/"><u>Discord's Best Sound Experience Unlocked by Advanced Bot Technologies for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-the-art-of-adding-audio-to-visual-content-for-facebook-sharing/"><u>[New] In 2024, The Art of Adding Audio to Visual Content for Facebook Sharing</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-the-use-of-telegram-in-a-step-by-step-approach/"><u>2024 Approved  Mastering the Use of Telegram in a Step-by-Step Approach</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-unwatermark-your-tiktok-videos-top-online-tools-and-tricks-for-2024/"><u>New Unwatermark Your TikTok Videos Top Online Tools and Tricks for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlock-apple-id-from-your-iphone-x-without-security-questions-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID From your iPhone X without Security Questions?</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-final-cut-pro-x-jump-cuts-take-your-editing-to-the-next-level/"><u>Updated In 2024, Final Cut Pro X Jump Cuts Take Your Editing to the Next Level</u></a></li>
<li><a href="https://howto.techidaily.com/tecno-spark-20c-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Tecno Spark 20C Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
</ul></div>
