---
title: How to Resolve Save Locations on Windows Devices
date: 2024-06-25T11:23:06.530Z
updated: 2024-06-26T11:23:06.530Z
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
<li><a href="https://win11.techidaily.com/a-fresh-start-for-your-computers-firewall-settings/"><u>A Fresh Start for Your Computer's Firewall Settings</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-exception-handling-error-in-windows-devices/"><u>How to Overcome Exception Handling Error in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/minimalist-pc-large-space-slight-lag/"><u>Minimalist PC - Large Space, Slight Lag</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-error-0x80040610-restoring-smooth-functionality-to-outlook/"><u>Tackling Error 0X80040610: Restoring Smooth Functionality to Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/guide-for-old-ribbon-revival-in-new-windows/"><u>Guide for Old Ribbon Revival in New Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-route-to-purchase-adobe-reader-in-microsoft-marketplace/"><u>Quick Route to Purchase Adobe Reader in Microsoft Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/is-steam-unable-to-connect-to-the-internet-on-windows-heres-how-to-fix-it/"><u>Is Steam Unable to Connect to the Internet on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-luminosity-a-comprehensive-hdr-guide-for-windows-11-users/"><u>Leveraging Luminosity: A Comprehensive HDR Guide for Windows 11 Users</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/making-money-with-youtube-understanding-partner-program/"><u>Making Money with YouTube  Understanding Partner Program</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/transition-your-calls-effortlessly-adopting-green-screens/"><u>Transition Your Calls Effortlessly, Adopting Green Screens</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-essential-guide-to-uploading-high-res-videos-on-youtube/"><u>[New] 2024 Approved  Essential Guide to Uploading High-Res Videos on Youtube</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-chromatic-creativity-enhancing-your-craft/"><u>In 2024, Chromatic Creativity  Enhancing Your Craft</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-essential-tips-for-aspiring-music-video-editors/"><u>In 2024, Essential Tips for Aspiring Music Video Editors</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-essential-ios-video-recorders-reviewed/"><u>2024 Approved  Essential iOS Video Recorders Reviewed</u></a></li>
<li><a href="https://youtube-web.techidaily.com/cketing-to-million-dollar-views-best-hashtags-for-2024/"><u>Skyrocketing to Million-Dollar Views  Best Hashtags for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-the-ultimate-guide-to-navigating-stardews-ginger-island/"><u>[Updated] 2024 Approved  The Ultimate Guide to Navigating Stardew’s Ginger Island</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-essential-guide-incorporating-music-and-effects-into-your-videos/"><u>Updated In 2024, Essential Guide Incorporating Music and Effects Into Your Videos</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>