---
title: "Overcoming Windows Error: 0X80780119 System Image Issue"
date: 2024-12-19T17:20:10.097Z
updated: 2024-12-22T17:42:54.262Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Overcoming Windows Error: 0X80780119 System Image Issue"
excerpt: "This Article Describes Overcoming Windows Error: 0X80780119 System Image Issue"
keywords: Fixing WinError 0X80780119,Resolve WinError 0X80780119,Overcoming WinError Image Issue,System Image Error Fix,Solving Windows System Problem,Eradicating WinError 0X80780119,Tackling WinError in Windows
thumbnail: https://thmb.techidaily.com/6e815c1b64efb14276b71fc721777a9cc6b2edabdceffdbe6557dc25c31661ee.jpg
---

## Overcoming Windows Error: 0X80780119 System Image Issue

 Creating a system image backup is essential in protecting your data and ensuring system recoverability, but the process of doing so might not always go smoothly. One such error that the users often encounter is the System Restore error 0x80780119, which prevents the users from completing the backup process.

 Below, we take a look at the common causes of this issue and discuss the different solutions you can try to get rid of this error for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Are You Unable to Create a System Image?

 If you are unable to create a system image due to the error 0x80780119, it might be because of one or more of the following reasons:

* **Insufficient disk space**: Restore points take up space in the drive they are saved, and so to create new restore points on your computer, you must have sufficient disk space available. In case you are running out of space on your system, you are likely to face the error at hand.
* **Incorrect backup settings**: Your backup settings must be configured correctly. If there is an issue with these settings, the System Restore will encounter issues while creating a restore point.
* **External drive issues**: If you are using an external drive for backup, it is essential to ensure that it is connected to the system properly and is functioning. In case there is an issue with the external drive due to any of these problems, the System Restore utility might return the error 0x80780119\.
* **Corrupt system files**: The critical system files that are essential to create restore points and use the System Restore utility might have gotten corrupt, which is leading to the error under discussion.
* **Antivirus interruption**: If you are using a security program on your computer, there is a chance that it is blocking the restore tool from functioning properly. This typically happens when you are using a third-party antivirus solution.

 Regardless of what might be resulting in the problem in your case, the solutions we have listed below are sure to help you get the restore utility back on track. Proceed with the solutions one by one and follow the steps carefully for successful execution.

## 1\. Free Up Disk Space

 When you create a restore point in Windows, the system requires sufficient space on the destination drive to store all the backup files. If you do not have enough space, the System Restore is likely to return errors like the 0x80780119 error.

 This is why, before moving onto the complex troubleshooting methods, we recommend you ensure you have sufficient space available on the destination drive. If you are low on space, you can free it up by removing unnecessary files. Here are a few areas to focus on:

* **Temporary files**: Temporary files and other unnecessary data can be cleaned up by [using the Disk Cleanup tool](https://www.makeuseof.com/tag/best-way-clean-windows-10-step-step-guide/). It will list down all such files, and you can then specify which to remove. Simply type “Disk Cleanup” in the search area on your taskbar and click **Open** to launch the utility.
* **Downloads folder**: Access the Download folder in File Explorer and delete all the files you no longer need.
* **Uninstall unused programs**: If there are apps that you do not use anymore, head over to the Control Panel to uninstall them from the system. This will free up a great amount of space that can be used by the System Restore utility.

 In case you have large files or folders that you do not want to remove but also don’t need immediately, you can consider moving them to an external drive to free up space.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Check and Repair Disk Errors

 You might also be facing the system restore issue due to disk errors in the system.

 During the backup process, the system needs to read data from the targeted disk and write it to the backup destination. If there is an issue with the disk, the system may have issues reading the data or might write corrupted data in the backup file, which can result in different errors.

 Additionally, your disk might have bad sectors which cannot store data properly and might also prevent the system from reading data during the backup process.

 To ensure this isn’t the case in your situation, it is best to check the disk for errors using the built-in utilities offered by Windows. The first tool that we recommend[using is the CHKDSK utility](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/) which can be used via Command Prompt. It works by scanning the system and checking the integrity of the disk. If a problem is identified, CHKDSK will attempt to fix it automatically.

 Alternatively, you can head over to the File Explorer and follow these steps:

1. In File Explorer, head over to the root of the drive you want to check and right-click on it.
2. Choose **Properties** from the context menu.
3. In the Properties dialog, navigate to the **Tools** tab and move to the **Error checking** section.
4. Click on the **Check** button here and wait for the system to complete the scan. This may take some time, depending upon the size of your disk.  
![Run the error checking tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/error-checking-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If any issues are found, Windows will prompt you to repair them. Follow the on-screen instructions to proceed.

## 3\. Enable System Protection

 Several users also noticed that they were facing the problem due to the system protection feature being disabled for the targeted drive. If you have this option disabled in your system, we suggest enabling it and checking if that makes any difference.

 Here is how you can do that:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Navigate to **System** \> **About**.
3. Head over to the **Device specifications** section and click on the **System protection** option.  
![Click on the System protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-protection-options.jpg)
4. In the following dialog, head over to the **System Protection** tab.
5. Choose the targeted drive and click on the **Configure** button.  
![Click on the Configure button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/configure-button.jpg)
6. Enable the **Turn on system protection** option and click **Apply** \> **OK** to save the changes.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable system protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/enable-system-protection.jpg)

 You can now close the System Protection dialog and check if the issue is resolved.

## 4\. Delete USN Journal

 The USN Journal (Update Sequence Number Journal) is a feature in the NTFS file system that tracks all the changes made on a disk. It is stored in the reserved partition and over time, it can consume a significant amount of your disk space, which may be preventing a restore point from being created.

 You can reclaim this disk space by deleting the USN Journal. Doing so will also eliminate the possibility of any conflicts that might be arising due to inconsistencies between the journal and the files being backed up.

 Here is how you can do that:

1. Type "Create and format hard disk partitions" in Windows search and click **Open**.
2. In the following window, right-click on the **System Reserved** volume and choose **Change Drive Letter and Paths** from the context menu.
3. Now, click on the **Add** button.
4. In the next dialog, choose **Assign the following drive letter** and click **OK**.  
![Change the USB Drive Letter Using Disk Management](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-the-usb-drive-letter-using-disk-management.jpg)
5. Once done, press the **Win** \+ **R** keys together to open Run.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Type "cmd" in Run and click **Ctrl** \+ **Shift** \+ **Enter** to open Command Prompt as an administrator.
7. Confirm your action in the UAC prompt.
8. Execute the following commands in Command Prompt one by one:  
`fsutil usn queryjournal F:fsutil usn deletejournal /N /D F:`

 After the commands are executed, you can close Command Prompt and check if the issue is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Create a Backup Without Any More Errors on Windows

 Ensuring the protection of your data should be your foremost priority, and a system image backup plays a vital role in safeguarding against unforeseen data loss. With the solutions above, you should be able to get the System Restore utility up and running in no time. However, if the problem persists, you can consider reporting the issue to Microsoft and try the specific solutions they suggest. Till then, you can switch to a third-party backup tool to safeguard your data.

 Below, we take a look at the common causes of this issue and discuss the different solutions you can try to get rid of this error for good.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-mastering-youtube-to-mpeg-format-change/"><u>[New] 2024 Approved Mastering YouTube to MPEG Format Change</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-introducing-efficient-speech-to-text-utilization-in-powerpoint/"><u>[New] Introducing Efficient Speech-to-Text Utilization in PowerPoint</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-slack-vs-discord-selecting-teams-ideal-chat-platform/"><u>[Updated] Slack Vs. Discord Selecting Teams' Ideal Chat Platform</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-verify-pin-bluetooth-issue-on-windows-systems/"><u>Eliminating Verify Pin Bluetooth Issue on Windows Systems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-android-adb-drivers-installed-on-windows-computers/"><u>Get the Latest Android ADB Drivers Installed on Windows Computers</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-ispoofer-on-vivo-t2x-5g-drfone-by-drfone-virtual-android/"><u>How to use iSpoofer on Vivo T2x 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-fixes-for-elevate-required-errors-in-windows-1011/"><u>Immediate Fixes for Elevate Required Errors in Windows 10/11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-poco-c50-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Poco C50 to iPhone | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-enhance-productivity-mac-screen-capture-made-simple-using-shortcut-keys/"><u>In 2024, Enhance Productivity Mac Screen Capture Made Simple Using Shortcut Keys</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-samsung-galaxy-f04-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-windows-11-serene-stop-background-jobs/"><u>Keeping Windows 11 Serene: Stop Background Jobs</u></a></li>
<li><a href="https://win11.techidaily.com/learn-the-rope-engaging-with-windows-11-insider-program/"><u>Learn the Rope: Engaging with Windows 11 Insider Program</u></a></li>
<li><a href="https://win11.techidaily.com/making-waves-in-windows-11-overcoming-xbox-stranding-issues/"><u>Making Waves in Windows 11, Overcoming Xbox Stranding Issues</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-deadly-wow-glitch-on-new-windows-os/"><u>Overcoming the Deadly WoW Glitch on New Windows OS</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-to-installing-epson-xp-430-printer-drivers-on-windows-operating-systems/"><u>Step-by-Step Guide to Installing Epson XP- 430 Printer Drivers on Windows Operating Systems</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-windows-app-configuration-issue/"><u>Strategies for Fixing Windows App Configuration Issue</u></a></li>
<li><a href="https://howto.techidaily.com/tecno-phantom-v-flip-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Tecno Phantom V Flip Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unable-to-administer-pc-windows-solutions-unveiled/"><u>Unable To Administer PC: Windows Solutions Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-file-management-eliminating-onedrive-synchronization-issues/"><u>Winning at File Management: Eliminating OneDrive Synchronization Issues</u></a></li>
</ul></div>

