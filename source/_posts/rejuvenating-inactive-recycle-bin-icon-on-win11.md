---
title: Rejuvenating Inactive Recycle Bin Icon on Win11
date: 2024-06-25T11:34:19.870Z
updated: 2024-06-26T11:34:19.870Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/keep-win10-fresh-actions-for-those-who-skip-11/"><u>Keep Win10 Fresh: Actions for Those Who Skip 11</u></a></li>
<li><a href="https://win11.techidaily.com/taskbar-chat-disappearance-in-windows-11-what-it-entails-for-users/"><u>Taskbar Chat Disappearance in Windows 11: What It Entails for Users</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-landscape-of-windows-filter-keys/"><u>Navigating the Landscape of Windows' Filter Keys</u></a></li>
<li><a href="https://win11.techidaily.com/supercharging-macos-via-external-windows-utilities/"><u>Supercharging macOS via External Windows Utilities</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-nvidia-geforce-notaxc0f1103f-error/"><u>Correcting Windows Nvidia GeForce NotaXC0F1103F Error</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-rescue-deskanywhere-on-win11/"><u>Essential Tips to Rescue DeskAnywhere on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-your-yuzu-gameplay-speed/"><u>Amplify Your Yuzu Gameplay Speed</u></a></li>
<li><a href="https://win11.techidaily.com/leap-ahead-your-in-store-purchase-speed-on-ms-platform/"><u>Leap Ahead Your In-Store Purchase Speed on MS Platform</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-vivid-melodies-for-youtube-content-enhancement/"><u>Updated 2024 Approved Vivid Melodies for YouTube Content Enhancement</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-streamlining-video-uploads-tips-for-transforming-h-vids-for-igtv/"><u>2024 Approved  Streamlining Video Uploads  Tips for Transforming H-Vids for IGTV</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-maximizing-your-zoom-experience-on-chromeos/"><u>In 2024, Maximizing Your Zoom Experience on ChromeOS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-dive-into-creating-alluring-youtube-video-intros-for-2024/"><u>[New] Dive Into Creating Alluring YouTube Video Intros for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/the-best-free-online-movie-making-platforms-for-2024/"><u>The Best Free Online Movie Making Platforms for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-cheap-cam-recorders-that-deliver-big-on-performance/"><u>2024 Approved  Cheap Cam Recorders That Deliver Big on Performance</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-snapslowly-the-art-of-time-lapse-via-samsung/"><u>2024 Approved  SnapSlowly  The Art of Time-Lapse via Samsung</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-with-location-spoofer-on-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/"><u>How To Simulate GPS Movement With Location Spoofer On Samsung Galaxy A23 5G? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-apple-iphone-15-plus-by-drfone-ios/"><u>New Multiple Ways How To Remove iCloud Activation Lock From your Apple iPhone 15 Plus</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>