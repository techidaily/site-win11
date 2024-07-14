---
title: Addressing the Save Issue in Windows OSes
date: 2024-07-13T11:19:04.667Z
updated: 2024-07-14T11:19:04.667Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing the Save Issue in Windows OSes
excerpt: This Article Describes Addressing the Save Issue in Windows OSes
keywords: Fix Windows Errors,Solve OS Glitches,Windows Stability Tips,Stop OS Crashes,Enhance OS Performance,Debugging Windows,Optimize PC Software
thumbnail: https://thmb.techidaily.com/07be777ce45c307461ad22ca534398f5c53e5285da087031d4c184f1389088d2.jpg
---

## Addressing the Save Issue in Windows OSes

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-11-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 11 & 11</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/uncover-the-top-7-android-alternatives-for-ad-free-browsing-for-2024/"><u>Uncover the Top 7 Android Alternatives for Ad-Free Browsing for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-vanquish-xps-mysterious-printer-error-xfddddf/"><u>How to Vanquish XP's Mysterious Printer Error XFDDDDF</u></a></li>
<li><a href="https://win11.techidaily.com/stabilizing-clicks-avoid-accelerated-movement-in-win-1011/"><u>Stabilizing Clicks: Avoid Accelerated Movement in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-steam-audio-issues/"><u>Fixing Common Steam Audio Issues</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-apples-calendar-in-a-win1011-setup/"><u>Leveraging Apple's Calendar in a Win10/11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-sidestep-no-uninstall-issue-on-windows-oses/"><u>How to Sidestep No Uninstall Issue on Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-valorant-gameplay-fps-fixes-and-tips/"><u>Elevate Valorant Gameplay: FPS Fixes and Tips</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Oppo Reno 10 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-icon-diminution-issues-on-windows-11/"><u>Reverse Icon Diminution Issues on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-nvidia-settings-failure-to-save/"><u>Overcoming NVIDIA Settings Failure to Save</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-mending-deskanywhere-on-windows-11/"><u>Methods for Mending DeskAnywhere on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/esd-files-demystified-creating-iso-versions-for-windows-systems/"><u>ESD Files Demystified: Creating ISO Versions for Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-slow-windows-edge-w10-w11/"><u>Quick Fixes for Slow Windows Edge (W10, W11)</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-flash-dead-samsung-galaxy-f54-5g-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Samsung Galaxy F54 5G Safely | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-filmmakers-toolbox-in-depth-guide-to-cinematic-techniques-in-24/"><u>2024 Approved  The Filmmaker’s Toolbox  In-Depth Guide to Cinematic Techniques in '24</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-infinitely-stop-microsoft-defender-in-windows/"><u>How to Infinitely Stop Microsoft Defender in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-pause-bring-back-lost-sounds-to-tech-gadgets/"><u>Resetting Pause: Bring Back Lost Sounds to Tech Gadgets</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-best-practices-for-documenting-live-streamed-sporting-matches/"><u>[New] 2024 Approved  Best Practices for Documenting Live-Streamed Sporting Matches</u></a></li>
<li><a href="https://win11.techidaily.com/expert-techniques-for-fast-utorrent-downloads-on-windows/"><u>Expert Techniques for Fast uTorrent Downloads on Windows</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-movie-magic-for-video-editing-enthusiasts/"><u>In 2024, Movie Magic for Video Editing Enthusiasts</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/boost-visibility-with-a-bespoke-youtube-channel-url-for-2024/"><u>Boost Visibility with a Bespoke YouTube Channel URL for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/handling-missing-component-in-windows-lsassexe/"><u>Handling Missing Component in Windows' lsass.exe</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11-remote-desktop-troubleshoot-internal-errors/"><u>Resolving Windows 11 Remote Desktop: Troubleshoot Internal Errors</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-unveiling-ipads-full-potential-a-timelapse-journey-begins-here/"><u>[Updated] Unveiling iPad's Full Potential  A Timelapse Journey Begins Here</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-clearing-microsoft-protection-archives/"><u>Mastering the Art of Clearing Microsoft Protection Archives</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-bluescreenview-a-step-by-step-tutorial/"><u>Exploring BlueScreenView - A Step-By-Step Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-gaming-displays-from-going-opaque-on-win-os/"><u>Preventing Gaming Displays From Going Opaque on WIN OS</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-photo-management-winning-windows-applications/"><u>Efficient Photo Management: Winning Windows Applications</u></a></li>
<li><a href="https://win11.techidaily.com/reignite-f-keys-the-ultimate-guide-to-fixing-windows-10/"><u>Reignite F-Keys: The Ultimate Guide to Fixing Windows 10</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-activation-lock-from-the-apple-iphone-7-plus-without-previous-owner-by-drfone-ios/"><u>In 2024, How to Remove Activation Lock From the Apple iPhone 7 Plus Without Previous Owner?</u></a></li>
<li><a href="https://win11.techidaily.com/handling-camera-allocation-conflict-on-windows-os/"><u>Handling Camera Allocation Conflict on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/paving-the-way-for-progress-updating-windows-drivers/"><u>Paving the Way for Progress: Updating Windows Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-switch-for-regedit-on-win11/"><u>Mastering the Switch for RegEdit on Win11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-erase-an-iphone-xs-without-apple-id-password-by-drfone-ios/"><u>In 2024, How To Erase an iPhone XS Without Apple ID Password?</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-the-context-menu-with-divine-commands/"><u>Infuse the Context Menu with Divine Commands</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-softening-edges-strategic-lighting-for-content-creators/"><u>[New] Softening Edges  Strategic Lighting for Content Creators</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-download-your-cortana-data-on-windows/"><u>How to Download Your Cortana Data on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/essential-knowledge-setting-windows-filter-keys/"><u>Essential Knowledge: Setting Windows Filter Keys</u></a></li>
</ul></div>
