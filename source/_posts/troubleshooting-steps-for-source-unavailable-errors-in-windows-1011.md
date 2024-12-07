---
title: Troubleshooting Steps for “Source Unavailable” Errors in Windows 10/11
date: 2024-11-30T06:57:42.961Z
updated: 2024-12-07T06:00:55.269Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Steps for “Source Unavailable” Errors in Windows 10/11
excerpt: This Article Describes Troubleshooting Steps for “Source Unavailable” Errors in Windows 10/11
keywords: Windows Source Error Fix,Unavailability Troubleshoot,Fixing Sources Error,Solve PC Source Issue,Clearing Windows Source Errors,Removing Source Not Found,Resolving Windows Source Error
thumbnail: https://thmb.techidaily.com/cb769af3708fc15b594c9ede31a115d7b902d54d4fbcec56dcebaeb9d186f784.jpg
---

## Troubleshooting Steps for “Source Unavailable” Errors in Windows 10/11

 Users often need to copy (or transfer) files to or from external drives connected to Windows PCs. However, some users can’t do so because of an error that says, “Can’t read from the source file or disk.”

 This Windows error message can sometimes pop up when users try to copy certain files from or to external USB drives. As such, here is how you can fix the “Cannot read from the source file or disk” error.

## 1\. Check if the File Names Include Unsupported Characters

 Unsupported file name characters can cause the “Cannot read from the source file” error. Mac computers enable users to save files with characters like ?, <, >, :, \*, /, \\, |, and “. However, Windows 11 and 10 don’t support any of those characters for file names. Thus, users can’t copy files from external drives that include those characters onto a Windows PC.

 So, check if any files you’re trying to copy from an external drive include those characters. If you find any that do, right-click the files and select **Rename**. Then delete all unsupported characters from their file names. Or remove all kinds of special characters.

![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/rename-option-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Run a Check Disk Scan

 Running a Check Disk scan is a widely confirmed fix for the “Cannot read from the source file” error. That highlights this error is often caused by bad disk sectors on drives. Running a Check Disk scan via the Command Prompt for the drive that includes the files will usually remedy such a cause. Our [how to run a CHKDSK scan](https://www.makeuseof.com/sir-mini-how-to-run-chkdsk-in-windows-10/#:~:text=In%20Command%20Prompt%2C%20type%20chkdsk,to%20get%20stuck%20on%20occasion.) article tells you how to apply this potential fix.

![The CHKDSK command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-chkdsk-command2.jpg)

## 3\. Try a Different USB Cable or Port for External Drives

 Another possible cause for the “Cannot read from the source file or disk” error is that there’s an issue with your USB cable or a port on your PC. So, connect your external drive to a different USB port to see if that makes a difference. If you have an alternative USB cable available, try connecting the drive to your PC with it.

## 4\. Compress the Files You’re Trying to Copy Into a ZIP Folder

 Some users have been able to fix the “Cannot read from the source file or disk” error by compressing the files they need to copy into ZIP archives. Doing so will reduce the overall size of one or more files to copy. You can set up a ZIP archive before copy files onto a drive by following the instructions in our article about [creating ZIP files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/).

![The Send to option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-send-to-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Check the Permissions for the Affected Files

 You might need to fix the “Cannot read from the source file or disk” because one of the files you’re trying to copy doesn’t have full control permissions set. You can check and fix permissions for affected files as follows:

1. First, bring up Explorer (press**Win + E**) and navigate to the folder that includes the files you need to copy.
2. Right-click a file you need to copy and select **Properties**.
3. Then select **Edit** on the **Security** tab.  
![The Edit button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-edit-button.jpg)
4. Next, select the checkbox labeled **Full control** with the **Allow** column.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-full-control-checkbox.jpg)
5. Press **Apply** to save the file’s permission settings.
6. Click **OK** to exit.

 If you can’t see your account username within the Group box, you’ll need to add it. To do so, click **Add** on the **Security** tab to bring up a Select Users or Group window; then click **Advanced** \> **Find now** to select your user account. Click **OK** to add the selected account.

![The Find now option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-find-now-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Access Files on Mac-Formatted Drives With Third-Party Software

 The “Can’t read from the source file” error can also occur because of file system incompatibility on source drives. For example, Mac-formatted HFS or APFS drives aren’t compatible with Windows PCs.

 You can check the file system of any connected drive by right-clicking it in File Explorer and selecting **Properties**. Then check the File system detail on the General tab. NTFS and FAT32 file systems are fine for Windows, but HFS and APFS aren’t.

![The File system detail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-file-system-detail.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you’re trying to copy files from Mac-formatted drives, you can access them with third-party software. Software packages like MacDrive, UFS Explorer, and Paragon HFS+ enable users to access files on Mac-formatted drives on Windows PCs. Our article about [reading Mac-formatted drives on Windows](https://www.makeuseof.com/tag/4-ways-read-mac-formatted-drive-windows/) provides details on how to apply this potential resolution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Copy Files Between Drives on Your Windows PC Again

 Applying those solutions will usually resolve the “Cannot read from the source file” error on Windows. Then you can copy all the files you need between your Windows PC and external drives.

 One other resolution for this error recommended by some users is to utilize data recovery software. Such software provides another way to copy or transfer files from one drive to another. Stellar Data Recovery, Recuva, MiniTool Data Recovery, and Disk Drill are among the best data recovery software to utilize for that purpose.

 This Windows error message can sometimes pop up when users try to copy certain files from or to external USB drives. As such, here is how you can fix the “Cannot read from the source file or disk” error.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-video-capture.techidaily.com/new-farmers-fields-the-essential-10-agriculture-titles-for-playmates/"><u>[New] Farmers' Fields The Essential 10 Agriculture Titles for Playmates</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-pre-purchase-key-facts-every-drone-buyer-should-know/"><u>[New] Pre-Purchase Key Facts Every Drone Buyer Should Know</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-inside-track-to-premiere-pro-full-screen-viewing/"><u>[Updated] 2024 Approved Inside Track to Premiere Pro Full Screen Viewing</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-rise-in-popularity-top-10-instagram-hashtags-for-now-for-2024/"><u>[Updated] Rise in Popularity Top 10 Instagram Hashtags for Now for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-the-dreamcolor-spectrum-redefined-insight-into-the-z32x-monitor-for-2024/"><u>[Updated] The DreamColor Spectrum Redefined Insight Into the Z32X Monitor for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-update-malfunction-windows-0x80246007-issue/"><u>Correcting Update Malfunction: Windows' 0X80246007 Issue</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-successful-onedrive-operations-on-win-1011/"><u>Enhancing Successful OneDrive Operations on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/expand-your-gaming-library-in-playnite/"><u>Expand Your Gaming Library in Playnite</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fixing-ghost-recon-breakpoint-resolving-crashes-swiftly-and-effectively/"><u>Fixing Ghost Recon Breakpoint: Resolving Crashes Swiftly and Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/flawless-window-display-arranging-tasks-effortlessly-win11/"><u>Flawless Window Display: Arranging Tasks Effortlessly (Win11)</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Nubia Red Magic 8S Pro+? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-time-display-taskbar-clock-and-date-controls/"><u>Mastering Time Display: Taskbar Clock & Date Controls</u></a></li>
<li><a href="https://extra-support.techidaily.com/srgb-efficiency-against-basic-rgb-for-2024/"><u>Srgb Efficiency Against Basic Rgb for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-gameplay-overcoming-valorant-lag-issues/"><u>Transform Your Gameplay: Overcoming Valorant Lag Issues</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-secrets-of-winning-ps1-games-on-windows-with-duckstations-wisdom/"><u>Unlock the Secrets of Winning PS1 Games on Windows with Duckstation's Wisdom</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-windows-consoles-potential-again/"><u>Unlocking Your Windows Console's Potential Again</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-how-to-create-a-movie-in-minutes-a-quick-start-guide/"><u>Updated 2024 Approved How to Create a Movie in Minutes A Quick Start Guide</u></a></li>
</ul></div>

