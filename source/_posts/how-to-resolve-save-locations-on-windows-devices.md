---
title: How to Resolve Save Locations on Windows Devices
date: 2024-06-25T09:44:42.969Z
updated: 2024-06-26T09:44:42.969Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Resolve Save Locations on Windows Devices
excerpt: This Article Describes How to Resolve Save Locations on Windows Devices
keywords: WIN OS SavingLoc Fix,Windows SaveLocation Troubleshoot,Solve Windows StorageError,Restore Save Locations Windows,Microsoft SaveSettings Patch,Windows StoragePath Resolution,Correct Devices'SaveFolders
thumbnail: https://thmb.techidaily.com/c6591acb23ce2eaadb3a7b28c6ae2b6f75e1be51903da30b25fcaaa8ed089bda.jpg
---

## How to Resolve Save Locations on Windows Devices

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

## 2\. Rename the WindowsApps Directory

 This error can arise because the WindowsApps folder where apps save is corrupted. Renaming the WindowsApps folder on the drive or partition you want to save apps can address such an issue. To do so, rename that folder as follows:

1. If you’re trying to set apps to save on an external drive, connect that hard drive to your PC.
2. [Open the File Explorer folder navigator](https://www.makeuseof.com/windows-open-file-explorer/) and click **This PC**.
3. Double-click the drive/partition you want to set as your default save location for apps.
4. Then, right-click on the WindowsApps folder and select its **Rename** context menu option. You should find that directory within the drive’s root directory.  
![The Rename option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-button.jpg)
5. Rename the folder to **WindowsApps.old** and press **Enter**.
6. Thereafter, try changing the default save location for apps again via Settings.

 If that still doesn’t work, then proceed to the next resolution.

## 3\. Delete or Rename the WpSystem Folder

 Many users confirm that renaming or deleting the WpSystem folder fixes error 0x80070005\. WpSystem is a folder created to store app data. Try renaming that folder to **WpSystem.old** on the drive you can’t set to be a save location for apps, as outlined for the previous method. The WpSystem will be in the same directory as the WindowsApps folder.

 Alternatively, delete the WpSystem folder. You can [erase a file or folder in Explorer](https://www.makeuseof.com/windows-11-delete-select-files/) by right-clicking it and selecting **Delete**. If you can’t find that folder or this potential solution doesn’t work, try the next resolution.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/delete-option.jpg)

## 4\. Set Full System Permission for the System Volume Folder

 Setting full permission for the System Volume folder is another confirmed fix for error 0x80070005\. Follow these steps to set full permission for the System Volume directory:

1. Go into File Explorer and click the three-dot **See more** menu > **Options**. In Windows 10, click **Options** on the **View** tab.
2. Select **View** on the Folder Options window.
3. Deselect the **Hide protected operating system files (Recommended)** option.  
![The Hide protected operating system files checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-protected-operating-system-files.jpg)
4. Select the **Show hidden files, folders and drives** radio button.
5. Click **Apply** to save the new Explorer settings.

1. Select the drive you need to set as the default save location for apps.
2. Right-click the System Volume Information folder and select **Properties**.
3. Click **Security > Advanced** to bring up an Advanced Security Settings window.  
![The Security tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/security-tab.jpg)
4. Press the **Continue** button.
5. Next, click **Add** to view a Permission Entry window.

1. Click the **Select a principal** option.
2. Input **SYSTEM** inside the object name box.  
![The Select User or Group window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-group.jpg)
3. Click on the **OK** button.
4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/unlock-textual-form-from-vocal-input-in-windows-via-whisper/"><u>Unlock Textual Form From Vocal Input in Windows via Whisper</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-dialer-on-windows-11/"><u>Accessing Dialer on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ten-terminal-tricks-you-can-try-today/"><u>Ten Terminal Tricks You Can Try Today</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-the-email-fault-caused-by-0x800713f-on-win11/"><u>Steps to Solve the Email Fault Caused by 0X800713F on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-straighten-out-window-corners/"><u>How to Straighten Out Window Corners</u></a></li>
<li><a href="https://win11.techidaily.com/an-effective-guide-to-fix-error-0xc0000001-on-windows-pcs/"><u>An Effective Guide to Fix Error 0XC0000001 on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/audio-amplifiers-4-essential-tools-that-push-pc-sounds-past-100/"><u>Audio Amplifiers: 4 Essential Tools that Push PC Sounds Past 100%%</u></a></li>
<li><a href="https://win11.techidaily.com/switching-windows-default-pdf-viewer/"><u>Switching Windows' Default PDF Viewer</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-malwarebytess-failed-execution-calls-on-windows-1011/"><u>Tackling Malwarebytes's Failed Execution Calls on Windows 10/11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-inhibit-surprise-youtube-recommendations/"><u>In 2024, Inhibit Surprise YouTube Recommendations</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-tutorial-for-activating-icloud-from-apple-iphone-12-pro-safe-and-legal-by-drfone-ios/"><u>Easy Tutorial for Activating iCloud from Apple iPhone 12 Pro Safe and Legal</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-excel-2000-by-digital-signature-by-ldigisigner-sign-a-excel-sign-a-excel/"><u>How to sign Excel 2000 by digital signature</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-exploring-the-top-8-facebook-extractors-for-films/"><u>In 2024, Exploring the Top 8 Facebook Extractors for Films</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-calculator-projected-profits-from-youtube/"><u>[New] 2024 Approved  Calculator  Projected Profits From YouTube</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-easy-to-follow-guide-recording-non-root-android-sounds/"><u>2024 Approved  Easy-to-Follow Guide  Recording Non-Root Android Sounds</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-unlock-potential-a-list-of-must-try-bots-in-discord/"><u>In 2024, Unlock Potential  A List of Must-Try Bots in Discord</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-music-on-asus-rog-phone-7-ultimate-by-fonelab-android-recover-music/"><u>How to restore wiped music on Asus ROG Phone 7 Ultimate</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-from-iphone-14-pro-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code From iPhone 14 Pro</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-bandicam-demystified-a-clearer-understanding-of-2023-functionality/"><u>2024 Approved  Bandicam Demystified  A Clearer Understanding of 2023 Functionality</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>