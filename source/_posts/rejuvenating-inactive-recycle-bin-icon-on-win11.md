---
title: Rejuvenating Inactive Recycle Bin Icon on Win11
date: 2024-07-13T10:28:10.256Z
updated: 2024-07-14T10:28:10.256Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rejuvenating Inactive Recycle Bin Icon on Win11
excerpt: This Article Describes Rejuvenating Inactive Recycle Bin Icon on Win11
keywords: Win11 Recycle Fix,Recharge Bin Icon,Revive Recycling Icons,Update Recycle Icon,Restore Bin Image,Icon Reactivation Win11,Win11 Bin Icon Rejuvenate
thumbnail: https://thmb.techidaily.com/c72cccdf9cacc0fda207b45b24ab86cf2fde475b85a4b94012ab008856dbcd1d.jpg
---

## Rejuvenating Inactive Recycle Bin Icon on Win11

 The Recycle Bin has been a staple on Windows for a long time, but not everyone wants it on the desktop. You can disable it via the Desktop Icon Settings, but there is a bug where if you try to re-enable it, the "Recycle Bin" option is grayed out and cannot be toggled.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.

## 1\. How to Bring Back the Recycle Bin Using the Group Policy Editor

 The Group Policy Editor lets you show or hide the Recycle Bin icon from the desktop. Check if you have modified and accidentally disabled the Recycle Bin group policy recently. If so you can set the Remove Recycle Bin icon from the desktop policy to "Not Configured" which will restore it.

 You may not find the Local Group Policy Editor in Windows Home Edition. However, you can run a batch script to [enable Group Policy Editor on the Windows Home edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) or skip to the Registry Editor-based fix in the next step.

 To restore the Recycle Bin icon using the Group Policy Editor:

1. Press **Win + R** to open **Run**.
2. Type **gpedit.msc** and click **OK** to open the **Group Policy Editor**.  
![gpedit msc windows 11 run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/gpedit-msc-windows-11-run.jpg)
3. Next, navigate to the following location:  
`User Configuration > Administrative Templates > Desktop`
4. In the right pane, locate and double-click on the **Remove Recycle Bin icon from the desktop** option to open its properties.  
![edit remove recycle bin icon from settings gpedit policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy.jpg)
5. In the **Properties** dialog, select **Not Configured**.  
![edit remove recycle bin icon from settings gpedit policy not configured](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-remove-recycle-bin-icon-from-settings-gpedit-policy-not-configured.jpg)
6. Click **Apply** and **OK** to save the changes.

 Close the Group Policy Editor and check your desktop to see if you can access the Recycle Bin. If not, make sure the Recycle Bin is set to show in Desktop Icon Settings.

 To enable Recycle Bin in Desktop Icon Settings:

1. Press **Win + I** to open **Settings**.
2. Next, open the **Personalization** tab in the left panel.
3. Click on **Themes**.  
![desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/desktop-icon-settings-windows-11.jpg)
4. Click on **Desktop icon settings** under the **Related settings** section.
5. In the **Desktop Icon Settings** dialog, select **Recycle Bin**.  
![enable recycle bin desktop icon settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/enable-recycle-bin-desktop-icon-settings-windows-11.jpg)
6. Click **Apply** and **OK** to save the changes.

 If you can’t access Group Policy Editor or if the issue persists, you can use the Registry Editor to fix this problem.

## 2\. Modify the Recycle Bin Registry Settings

 Another way to resolve and restore the grayed-out Recycle Bin icon in the Desktop settings is via the Windows Registry. You can modify the registry entry value responsible for the settings and configurations of Recycle Bin working to restore the functionality.

 Making modifications to the Windows registry involves tweaking settings that may harm your device if performed incorrectly. We recommend you [create a Windows restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [take a Windows registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before attempting to modify the Windows registry.

 To modify the Recycle Bin registry value:

1. Press **Win + R** to open **Run**.
2. Type **regedit** and click **OK**. Click **Yes** if prompted by **User Account Control**.
3. In the Registry Editor, navigate to the following location. You can copy and paste the path in the editor for quicker navigation:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\NonEnum`
4. In the right pane, locate the **{645FF040-5081-101B-9F08-00AA002F954E}** DWORD (32-bit) value.  
![registry editor nonnum new dword value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value.jpg)
5. If it does not exist, you’ll need to create a new value. To do this, right-click on the **NonEnum** subkey folder in the left pane and select **New > DWORD (32-bit) Value**.
6. Rename the value as **{645FF040-5081-101B-9F08-00AA002F954E}**.
7. Next, double-click on the new DWORD value to open its properties.  
![registry editor nonnum new dword value edit 0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/registry-editor-nonnum-new-dword-value-edit-0.jpg)
8. Type **0** in the Value data field and click **OK** to save the changes.
9. Close Registry Editor and restart your computer. Sometimes, you’ll need to restart your computer for the new registry modifications to work.

 If the issue persists, try to [create a new user account with administrative rights](https://www.makeuseof.com/windows-11-create-local-user-account/), [perform a system restore](https://www.makeuseof.com/use-system-restore-windows/), or [repair corrupted Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/).

## Get Access to the Recycle Bin Desktop Icon Setting Again

 An incorrectly modified group policy can gray out the Recycle Bin icon in the Desktop Icon Settings dialog. Fortunately, it's an easy fix, and you should now have your Recycle Bin back to how you like it.

 Fortunately, you can fix the issue by reverting specific changes in the Registry Editor or the Group Policy Editor.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-sculpt-the-perfect-youtube-moniker-tips-and-tricks-for-2024/"><u>[Updated] How to Sculpt the Perfect YouTube Moniker  Tips & Tricks for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-precision-editing-embedding-times-in-video-posts/"><u>[New] Precision Editing  Embedding Times in Video Posts</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-overcome-ppt-save-blunders-6-quick-fixes-windows-users-need/"><u>Swiftly Overcome PPT Save Blunders: 6 Quick Fixes Windows Users Need</u></a></li>
<li><a href="https://win11.techidaily.com/whats-next-for-failed-updates-code-0x800f0845/"><u>What's Next for Failed Updates - Code 0X800f0845?</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-how-to-vlog-a-ultimate-guide-for-beginners/"><u>Updated How to Vlog? A Ultimate Guide for Beginners</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-chat-disappearance-in-windows-11-what-it-entails-for-users/"><u>Taskbar Chat Disappearance in Windows 11: What It Entails for Users</u></a></li>
<li><a href="https://fox-helps.techidaily.com/selecting-the-ultimate-steadicams-for-flawless-dslr-shoots-for-2024/"><u>Selecting the Ultimate Steadicams for Flawless DSLR Shoots for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-privacy-disabling-windows-trackers/"><u>Unlock Privacy: Disabling Windows Trackers</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-tricks-for-unfreezing-right-click-menus-on-windows/"><u>Top 6 Tricks for Unfreezing Right-Click Menus on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/burying-your-data-secretive-drive-practices/"><u>Burying Your Data: Secretive Drive Practices</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-best-approach-for-managing-cc-rights-and-usage-for-2024/"><u>[Updated] Best Approach for Managing CC Rights & Usage for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-handle-no-device-drivers-issue-in-system-setup/"><u>Steps to Handle 'No Device Drivers' Issue in System Setup</u></a></li>
<li><a href="https://win11.techidaily.com/dive-deep-into-hdr-visualization-with-windows-11/"><u>Dive Deep Into HDR Visualization with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-pitfalls-with-d3d11-compatible-gpus-in-win11win10/"><u>Avoiding Pitfalls with D3D11-Compatible GPUs in Win11/Win10</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-unlocked-effective-tpm-deactivation/"><u>Windows 11 Unlocked: Effective TPM Deactivation</u></a></li>
<li><a href="https://win11.techidaily.com/essential-note-taking-software-the-winning-seven/"><u>Essential Note-Taking Software: The Winning Seven</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-clustered-icon-issue-in-windows-11-taskbar/"><u>Troubleshooting Clustered Icon Issue in Windows 11 Taskbar</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-expert-advice-on-creating-impactful-hdr-portraits-for-2024/"><u>[Updated] Expert Advice on Creating Impactful HDR Portraits for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-tutorial-syncing-airpods-with-windows/"><u>Ultimate Tutorial: Syncing AirPods with Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-auto-update-shutdown-guide/"><u>Windows Auto-Update Shutdown Guide</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-overcoming-file-access-barriers-using-powershell/"><u>Efficiently Overcoming File Access Barriers Using PowerShell</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-get-the-cinematic-look-free-slow-motion-video-editing-with-filmora/"><u>Updated In 2024, Get the Cinematic Look Free Slow Motion Video Editing with Filmora</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unauthorized-nvidia-panel-errors-in-ws1110/"><u>Correcting Unauthorized Nvidia Panel Errors in WS11/10</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/simple-guide-sharing-tweets-with-imagesvideos-directly-to-twitter-for-2024/"><u>Simple Guide  Sharing Tweets with Images/Videos Directly to Twitter for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-infinix-smart-7-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-excessive-usage-of-computational-resources-by-unrealcefsubprocess/"><u>Addressing Excessive Usage of Computational Resources by UnrealCEFSubprocess</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-non-loading-dll-in-windows-steam/"><u>Strategies for Fixing Non-Loading Dll in Windows Steam</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-get-the-apple-id-verification-code-on-apple-iphone-15-in-the-best-ways-by-drfone-ios/"><u>In 2024, How To Get the Apple ID Verification Code On Apple iPhone 15 in the Best Ways</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-secure-entry-into-windows-admin-console/"><u>Steps for Secure Entry Into Windows' Admin Console</u></a></li>
<li><a href="https://win11.techidaily.com/take-control-of-your-system-utilizing-alomware-tools-effectively/"><u>Take Control of Your System: Utilizing AlomWare Tools Effectively</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-avoiding-lost-frames-during-video-capture-in-obs/"><u>In 2024, Avoiding Lost Frames During Video Capture in OBS</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-make-your-own-cartoons-top-rated-mobile-apps/"><u>2024 Approved Make Your Own Cartoons Top-Rated Mobile Apps</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-gif-size-barrier-on-discord-for-win11-users/"><u>Breaking Down the GIF Size Barrier on Discord for Win11 Users</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/cant-play-mov-files-on-galaxy-f54-5g-by-aiseesoft-video-converter-play-mov-on-android/"><u>Can't play .mov files on Galaxy F54 5G</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-a-spectrum-of-style-the-finest-photo-frame-software/"><u>2024 Approved  A Spectrum of Style  The Finest Photo Frame Software</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-microsoft-excel-2000-error-code-0x800a03ec-by-stellar-guide/"><u>How to Fix Microsoft Excel 2000 Error Code 0x800A03EC?</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-incorporating-folders-in-win11-ui/"><u>Techniques for Incorporating Folders in Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-blank-screen-issues-after-attempting-to-connect/"><u>Tackling Blank Screen Issues After Attempting to Connect</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-potential-setting-up-the-jdk-in-windows-11-efficiently/"><u>Unlocking Potential: Setting Up the JDK in Windows 11 Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-win11s-notepad-with-virtuoso-helper/"><u>Accelerate Win11's Notepad with Virtuoso Helper</u></a></li>
<li><a href="https://win11.techidaily.com/win-11s-bluetooth-woes-try-these-9-simple-cures/"><u>Win 11'S Bluetooth Woes? Try These 9 Simple Cures</u></a></li>
<li><a href="https://win11.techidaily.com/the-unseen-power-in-photo-erasing-on-windows/"><u>The Unseen Power in Photo Erasing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-networking-with-python-servers-on-windows-os/"><u>Advanced Networking with Python Servers on Windows OS</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-decoding-the-most-current-tiktok-movements/"><u>[Updated] In 2024, Decoding the Most Current TikTok Movements</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/2024-approved-facebook-live-shopping-a-comprehensive-guide/"><u>2024 Approved Facebook Live Shopping A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fix-for-invisible-second-screen-on-windows-11/"><u>Fix for Invisible Second Screen on Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-beginners-blueprint-for-yourwebcamrecord/"><u>[Updated] 2024 Approved  Beginner's Blueprint for YourWebcamRecord</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-ultimate-guide-to-managing-fast-forward-functions/"><u>The Ultimate Guide to Managing Fast Forward Functions</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-unlocking-the-secrets-of-srt-systems/"><u>[New] Unlocking the Secrets of SRT Systems</u></a></li>
</ul></div>
