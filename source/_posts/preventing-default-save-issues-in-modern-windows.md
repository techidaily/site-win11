---
title: Preventing Default Save Issues in Modern Windows
date: 2024-12-10T23:48:31.278Z
updated: 2024-12-12T17:18:26.461Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preventing Default Save Issues in Modern Windows
excerpt: This Article Describes Preventing Default Save Issues in Modern Windows
keywords: WinSaveProtect,FixDefaultSaveWin,PreventWindowsSaves,StopSaveErrorWin,SecureDefaultSave,EliminateSaveFailures,WindowsSaveGuard
thumbnail: https://thmb.techidaily.com/41b376d29e85724c5481e57f7a36ad6deb299d08d21887a298dcedb2ce73aa51.jpg
---

## Preventing Default Save Issues in Modern Windows

 Users have reported error 0x80070005 or 0x80070539 arises when they try to set new apps to save to different external drive locations with Settings. Those error codes have the same message that says, “We couldn’t set your default save location.” This means users can’t change the default save location for apps.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Set Your User Account to Administrator

 If you’re utilizing a standard Windows account, [change your user account type](https://www.makeuseof.com/ways-to-change-user-account-windows-10/) to an administrative one. A standard user account will prevent you from applying any more complicated system changes. Changing the save location for apps is something you might need admin privileges for.

![The Account type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-account-type-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Select the **Full control permission** setting.  
![The Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-option.jpg)
5. Then select the **OK** options on the Permission Entry and Advanced Security Settings windows.

 Close all remaining open windows. Then, restart your PC and try changing the default save location.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Set a New Default Save Location in Windows 11/10

 Many users have needed to fix error 0x80070005 and have done so by applying the potential solutions in this guide. The WpSystem folder is often the source of the error, and resolution two is the most widely confirmed method for fixing this issue.

 However, some users have also fixed the issue by applying the less widely cited fourth method.

 Is that error also preventing you from changing where new apps save to? If it is, this is how you can fix error codes 0x80070005 or 0x80070539 on Windows 11/10\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-share-tunes-mp3-from-fb/"><u>[New] 2024 Approved Share Tunes MP3 From FB</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-share-wisdom-top-strategies-for-video-sharing-on-instagram/"><u>[New] Share Wisdom Top Strategies for Video Sharing on Instagram</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-optimal-recording-is-30fps-or-60fps-superior-for-videos-for-2024/"><u>[Updated] Optimal Recording Is 30Fps or 60Fps Superior for Videos for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/command-prompt-access-for-admin-tasks-on-pc/"><u>Command Prompt Access for Admin Tasks on PC</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-data-size-and-space-usage-with-win11s-ntfs-features/"><u>Controlling Data Size & Space Usage with Win11's NTFS Features</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-issues-with-elevated-user-roles-and-privileges/"><u>Correcting Issues with Elevated User Roles and Privileges</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-contacts-from-oppo-find-x6-by-fonelab-android-recover-contacts/"><u>How to recover deleted contacts from Oppo Find X6.</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-by-checkra1n-even-from-apple-iphone-11-pro-if-youve-tried-everything-by-drfone-ios/"><u>In 2024, How To Bypass iCloud By Checkra1n Even From Apple iPhone 11 Pro If Youve Tried Everything</u></a></li>
<li><a href="https://extra-support.techidaily.com/inside-the-world-of-toolwiz-an-in-depth-software-review-for-2024/"><u>Inside the World of Toolwiz An In-Depth Software Review for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/mastering-technology-choices-why-experts-agree-apples-ipad-pro-201e-11-inch-is-unbeatable/"><u>Mastering Technology Choices: Why Experts Agree, Apple's iPad Pro (201E, 11-Inch) Is Unbeatable</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-efficiency-with-widget-driven-hardware-insights/"><u>Maximize Efficiency with Widget-Driven Hardware Insights</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-gameplay-smart-adjustments-for-amd-gpu-performance-on-pc/"><u>Optimize Gameplay: Smart Adjustments for AMD GPU Performance on PC</u></a></li>
<li><a href="https://win11.techidaily.com/sniping-in-windows-10-prtsc-vs-snip-and-sketch-showdown/"><u>Sniping in Windows 10: PrtSc Vs. Snip & Sketch Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/speed-up-typing-on-win-11-combat-keyboard-lag-effectively/"><u>Speed Up Typing on Win 11: Combat Keyboard Lag Effectively</u></a></li>
<li><a href="https://solve-manuals.techidaily.com/step-by-step-guide-to-moving-whatsapp-messages-between-two-iphone-devices-by-bypassing-the-icloud-route/"><u>Step-by-Step Guide to Moving WhatsApp Messages Between Two iPhone Devices by Bypassing the iCloud Route</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-correcting-messages-not-rendering-in-discord/"><u>Steps for Correcting Messages Not Rendering in Discord</u></a></li>
<li><a href="https://win11.techidaily.com/tricks-to-tackle-frozen-power-settings-on-windows-11/"><u>Tricks to Tackle Frozen Power Settings on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unmatched-comfort-and-efficiency-leading-windows-laptops/"><u>Unmatched Comfort & Efficiency - Leading Windows Laptops</u></a></li>
</ul></div>

