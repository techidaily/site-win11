---
title: Quick Fixes for Dormant Radeon Software Interface
date: 2024-07-13T11:05:29.977Z
updated: 2024-07-14T11:05:29.977Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Fixes for Dormant Radeon Software Interface
excerpt: This Article Describes Quick Fixes for Dormant Radeon Software Interface
keywords: Radeon Update Quickly,Revive GPU Driver,Resume Graphics Pause,Fixed Radeon Interface,Improve Radeon Graphics,Reactivate Software Now,Boost Dormant Radeon
thumbnail: https://thmb.techidaily.com/71005eecdd2fec9bde2d87e54e71962fc2dc07f266aaf5068a5f2270c6aff62a.jpeg
---

## Quick Fixes for Dormant Radeon Software Interface

 Users who need to fix AMD Radeon Software not working can’t open that app and access its settings. Are you among those users? If so, you can fix AMD Radeon Software not opening on a Windows PC with the resolutions below.

## 1\. Run AMD Radeon Software as an Administrator

 Users typically select to run AMD Radeon Software without admin rights from the context menu. Instead, try running AMD Radeon Software as an administrator to see if that helps. You can do that by pressing the **Windows** logo button + **S**, inputting **AMD** in the search box, and selecting **Run as administrator** for the AMD app found.

![The Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/run-as-administrator-option.jpg)

 If that works, permanently set AMD Radeon Software to run with elevated privileges. To do so, follow the steps in this article about [always running apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/). However, note that you can’t permanently set the AMD Radeon Software MS Store app to run as administrator.

## 2\. End the RadeonSoftware Process Tree

 First, check if Task Manager shows a process for AMD Radeon Software. If it does, that effectively means the app is already running in the background. Terminating the process tree for AMD Radeon Software might then fix the issue. You can close the RadeonSoftware process tree like this:

1. Press the **Ctrl** \+ **Shift** \+ **Esc** keyboard key combination to activate Task Manager.
2. Select Task Manager’s **Details** tab.
3. Look for and right-click **RadeonSoftware.exe** to select the **End process tree** option.  
![The End process tree option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/end-process-tree-option.jpg)
4. Click on the **End process tree** button to confirm.

## 3\. Delete the CN Folder

 Corrupted profile data often causes the AMD Radeon Software to stop working. You can fix that by deleting the CN folder, which contains Radeon profile data. Erasing that folder rebuilds the profile. This is how you can delete the CN folder:

1. Utilize the **Windows key + R** keyboard shortcut to access the Run dialog.
2. Type **%appdata%** into Run and click **OK** to access a Roaming directory.
3. Click AppData in Explorer’s folder location bar.
4. Open the Local subfolder inside the AppData folder.
5. Click the AMD folder to go inside it.  
![the-CN-folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/the-cn-folder.jpg)
6. Right-click the CN folder and select **Delete**.

 Alternatively, you can try erasing a specific file within the CN folder, which users have also confirmed works. To do that, open the CN folder to view its contents. Right-click the **gmdb.blb** file in that directory and select Delete.

## 4\. Disable and Re-enable the AMD Radeon Graphics Adapter

 Disabling and re-enabling the AMD graphics adapter is another potential resolution users confirm can kick-start AMD Radeon Software. You can disable and re-enable the AMD graphics adapter on your PC as follows:

1. First, [open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) (press the **Windows key** \+ **X** hotkey and select the shortcut for that tool).
2. Double-click the **Display adapters** category to extend it.
3. Right-click the AMD Radeon graphics card to select **Disable device**.  
![The Disable device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/disable-device-option.jpg)
4. Click on **Yes** when asked to confirm the selected option.
5. Wait a minute and right-click the AMD Radeon graphics card again to select **Enable device**.

## 5\. Update AMD Graphics Driver

 A faulty or old AMD driver on your PC could be a possible cause for the Radeon software not working. You can fix that by installing the latest AMD driver for your PC’s graphics card.

 Check out our guide to [updating graphics drivers on Windows](https://www.makeuseof.com/update-graphics-drivers-in-windows-10/) for further details about how to apply this potential fix.

![A Download option for an AMD graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/amd-driver-download-page.jpg)

## 6\. Restore the Previous AMD Driver Installed on Your PC

 Sometimes buggy new graphics drivers can cause issues, which is why NVIDIA and AMD release hotfixes. If your PC already has the latest AMD driver, restoring the previous one installed could be a viable solution for some users.

 You can do that by selecting a **Roll Back Driver** option, as covered in our guide on [rolling back graphics drivers on Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/).

![The Roll Back Driver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/roll-back-driver-option.jpg)

## 7\. Set Windows 11/10 to Clean Boot

 A conflicting background program could be another factor for AMD Radeon not opening. The best way to remedy this possible cause is to configure your PC to clean boot and restart it. This will disable third-party apps and services automatically starting with Windows.

 To apply a clean boot, you’ll need to remove apps and services from the startup with Task Manager and MSConfig. Our article about [performing a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) includes specific instructions for how you can disable the required startup items. Restart your PC after disabling the startup items and select to open AMD Radeon.

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/services-tab-in-msconfig.jpg)

## 8\. Edit the CN Registry Key

 Editing the **CN** registry key is resolution confirmed to fix the “Radeon Settings and Driver versions do not match” error message some users see when they try to start AMD Radeon. This registry fix involves entering a new value for the **DriverVersion** string in the **CN** key. These are the steps for applying this registry fix:

1. First, open the **Display adapters** category within Device Manager, as instructed for steps one and two of this guide’s fourth resolution.
2. Click the AMD graphics card with the right mouse button and select **Properties**.
3. Select **Driver** on the tab bar.
4. Drag the cursor over the driver number on that tab and press **Ctrl** \+ **C** to copy.  
![A driver version number](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/driver-version-detail.jpg)
5. Close the properties window and Device Manager tool.

 Now, [open the Registry Editor on Windows](https://www.makeuseof.com/windows-11-open-registry-editor/) before continuing.

1. Clear the registry address bar to input the following key location there:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\AMD\CN`
2. Double-click the **DriverVersion** string in the **CN** registry key.  
![The Value data box for the DriverVersion string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/value-data-box.jpg)
3. Clear the **Value data** box.
4. Press the **Ctrl** \+ **V** hotkey to paste the copied driver version number into the **Value data** box.  
![The Value data box for the DriverVersion string](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/value-data-box.jpg)
5. Select **OK** in the Edit String window.

## 9\. Reinstall the AMD Radeon Software

 Reinstalling AMD Radeon Software can also fix variable issues that prevent that app from starting. You can remove AMD Radeon with the Control Panel or Settings methods in our guide to [uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). Or you can utilize a third-party uninstaller app to remove that software and thoroughly erase its leftovers.

 To reinstall that app, open this [AMD Radeon Software Microsoft Store page](https://apps.microsoft.com/detail/amd-radeon-software/9NZ1BJQN6BHL?hl=en-US&gl=US). Click the **Install** and **Open in Microsoft Store** buttons; select **Get** to install the AMD Radeon Software.

![The AMD Radeon Software page on Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/amd-radeon-software.jpg)

## Utilize Your AMD Radeon Software Again

 AMD Radeon Software is undoubtedly important to access for configuring graphical settings. The potential resolutions in this guide have enabled many users to fix AMD Radeon not working and access its settings again. So, applying those Windows 11/10 fixes will probably kick-start AMD Radeon on your PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-poco-c55-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Poco C55 to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unbelievable-judgment-and-backup-recommendations/"><u>[New] Unbelievable Judgment & Backup Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/blocking-snipping-tool-activation-by-pressing-prtscn-on-windows-11-devices/"><u>Blocking Snipping Tool Activation by Pressing PrtScn on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-stop-discord-initial-launch-and-searching-at-boot/"><u>Techniques: Stop Discord Initial Launch & Searching at Boot</u></a></li>
<li><a href="https://win11.techidaily.com/the-convenience-of-uwp-shortcuts-in-windows-11/"><u>The Convenience of UWP Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-0x80d03801-issue-in-windows-shop/"><u>Remedying 0X80D03801 Issue in Windows Shop</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-the-definitive-list-of-iphone-image-markers-apps/"><u>2024 Approved  The Definitive List of iPhone Image Markers Apps</u></a></li>
<li><a href="https://win11.techidaily.com/10-routes-to-windows-diagnostics-hub/"><u>10 Routes to Windows Diagnostics Hub</u></a></li>
<li><a href="https://win11.techidaily.com/sweeping-away-windows-access-errors-effectively/"><u>Sweeping Away Windows' Access Errors Effectively</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-the-best-screen-capture-apps-a-guide-for-educators/"><u>In 2024, The Best Screen Capture Apps  A Guide for Educators</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-pc-experience-on-windows-11-devices/"><u>Tailoring Your PC Experience on Windows 11 Devices</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-insta-photo-and-video-reposts/"><u>[New] Mastering Insta Photo & Video Reposts</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-5-car-locator-apps-for-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>Top 5 Car Locator Apps for Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/restore-peace-of-mind-with-these-5-family-safety-fixes/"><u>Restore Peace of Mind with These 5 Family Safety Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/selecting-the-best-downloader-choco-vs-windows-package-tool/"><u>Selecting the Best Downloader: Choco Vs. Windows Package Tool</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-pc-three-methods-for-a-clean-windows-boot/"><u>Revitalize PC: Three Methods for a Clean Windows Boot</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tip-converting-esd-to-iso-without-compromising-data-integrity-on-windows/"><u>Tech Tip: Converting ESD to ISO without Compromising Data Integrity on Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oneplus-nord-n30-se-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from OnePlus Nord N30 SE to Outlook | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-essential-tips-for-quality-screencasting-for-2024/"><u>[Updated] Essential Tips for Quality Screencasting for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-error-codes-when-installing-windows-apps/"><u>Understanding Error Codes When Installing Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unresponsive-windows-11-printer-ports-and-devices/"><u>Tackling Unresponsive Windows 11 Printer Ports & Devices</u></a></li>
<li><a href="https://win11.techidaily.com/secure-clipchamp-install-on-windows-11-with-these-steps/"><u>Secure ClipChamp Install on Windows 11 with These Steps</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-instantaneous-folder-upload-failures-in-the-windows-onedrive-environment/"><u>Quick Fixes for Instantaneous Folder Upload Failures in the Windows OneDrive Environment</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-11-taskbar-datetime-visibility/"><u>Adjusting Windows 11 Taskbar Date/Time Visibility</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-normal-operations-of-netflix-window/"><u>Re-Establishing Normal Operations of Netflix Window</u></a></li>
<li><a href="https://win11.techidaily.com/windows-adjusting-user-permissions-for-regular-accounts/"><u>Windows: Adjusting User Permissions for Regular Accounts</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-studio-review-the-quest-for-perfection-continues/"><u>Surface Laptop Studio Review: The Quest for Perfection Continues</u></a></li>
<li><a href="https://win11.techidaily.com/admin-controls-simplified-managing-users-and-groups-in-homes/"><u>Admin Controls Simplified: Managing Users & Groups in Homes</u></a></li>
<li><a href="https://win11.techidaily.com/whats-behind-yourphoneexe-in-modern-windows-systems/"><u>What's Behind YourPhone.exe in Modern Windows Systems?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/comparing-m1-laptop-performance-in-air-vs-pro/"><u>Comparing M1 Laptop Performance in Air Vs. Pro</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-10-final-cut-pro-plug-ins/"><u>[Updated] 10 Final Cut Pro-Plug-Ins</u></a></li>
</ul></div>
