---
title: Addressing Windows 11 MS Store Error X7326
date: 2024-07-13T11:22:07.175Z
updated: 2024-07-14T11:22:07.175Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Windows 11 MS Store Error X7326
excerpt: This Article Describes Addressing Windows 11 MS Store Error X7326
keywords: WinX7326Error,MSStoreX7326,Windows11InstallIssue,X7326MSStoreError,FixWindows11Error,StoreErrorW11,ResolveWinX7326
thumbnail: https://thmb.techidaily.com/3a3db1628b8f2814d2040ecfe00634d164ea4b5f3058a85b825026993cb96502.jpg
---

## Addressing Windows 11 MS Store Error X7326

 Error 0x80073D26 is an issue that users have widely reported occurring when trying to install or play Xbox Game Pass titles via Microsoft Store. When this issue arises, users get redirected to install the Gaming Services app in the Microsoft Store. Users then see the “Something unexpected happened” error 0x80073D26 message when they try to install (or update) Gaming Services.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows

## 1\. Run the Windows Store App Troubleshooting Tool

 This isn’t the most likely solution for error 0x80073D26, but it’s worth trying since Microsoft Store is a UWP app. Running the Windows Store App troubleshooter might detect a Microsoft Store issue and provide a fix. These are the steps for running the Windows Store App troubleshooting utility:

1. Open Settings and click **System** to view that tab.
2. Next, select **Troubleshoot** to reach three troubleshooting navigation options.
3. Bring up the list of troubleshooting tools by clicking **Other trouble-shooters**.
4. Then click **Run** to launch the Windows Store Apps troubleshooting tool.  
![The Run button for the Windows App Store troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-app-store-troubleshooter.jpg)
5. Apply all troubleshooting suggestions provided within Windows Store Apps window.  
![The Windows Store Apps window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-store-app-troubleshooter.jpg)

 You can run the same troubleshooter tool in Windows 10, but the steps for accessing it are a bit different. Click **Update & Security** \> **Troubleshoot** \> **Additional troubleshooters** in Windows 10’s Settings app. Then select **Windows Store Apps** \> **Run the troubleshooter** to get troubleshooting.

## 2\. Repair and Reset the Microsoft Store App

 Accumulated and corrupted Microsoft Store cache data is a potential cause for error 0x80073D26\. Resetting the Microsoft Store app via Settings or the Command Prompt will clear the app’s data. Try applying both methods in this guide to resetting Microsoft Store. Also, select the **Repair** option for the Microsoft Store just above its **Reset** button in Settings to see if that resolves the issue.

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

## 3\. Edit the Registry

 One of the most widely confirmed fixes for error 0x80073D26 is to enter the Registry and delete the GamingServices and GamingServicesNet Registry keys. Although confirmed to work, we still recommend users [back up the Windows Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before deleting keys. Then follow these steps for editing the registry:

1. Open the Windows Run accessory by right-clicking **Start** on your taskbar and selecting the **Run** option.
2. Input the **regedit** Run command and click **OK** to [launch the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Copy and paste this key location in the registry address bar:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services`
4. Right-click the **GamingServices** subkey within the Services key to select **Delete** \> **Yes**.  
![The Delete registry key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/delete-option-1.jpg)
5. Click the **GamingServicesNet** key with the mouse’s right button and select the **Delete** \> **Yes** options.
6. Exit Registry Editor and restart your PC.

## 5\. Reinstall the Microsoft Gaming Service

 One of Microsoft’s official resolutions for error 0x80073D26 is to reinstall Gaming Service. This potential solution involves entering three PowerShell commands that will remove the Gaming Service app along with associated registry entries. These are the steps for applying this potential fix:

1. Activate Windows Search by pressing **Win + S**.
2. Enter **PowerShell** inside the file search tool.
3. Open PowerShell with admin rights by right-clicking that app in the search results and selecting **Run as Administrator**.
4. Next, remove the Gaming Service app by entering this command and hitting **Enter**:  
`Get-AppxPackage *gaming services* -allusers | remove-appxpackage -allusers`  
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
5. Then input these separate commands, pressing **Return** after each:  
`Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServices" -recurse  

Remove-Item -Path "HKLM:\System\CurrentControlSet\Services\GamingServicesNet" -recurse` 
![The remove-app package command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-app-package-command.jpg)
6. Close out of PowerShell to restart Windows.
7. Reopen Powershell and execute the following command:  
`start ms-windows-store://pdp/?productid=9MWPM2CQNLHN`
8. Then click the **Get** button for installing Gaming Service.

## 5\. Perform Some Generic Windows Fixes for Errors

 Windows is by no means impervious to errors. Fortunately, there are some tricks you can apply to almost every error, including this one.

### Repair System Files

![The Reset button for Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/repair-button-1.jpg)

 To begin with, try repairing system files to see if there are any issues. You can do that by executing a System File Checker scan within the Command Prompt. That tool will check for and repair corrupted system files detected when you run its command. To apply this potential fix, follow the instructions in our [how to run the System File Checker tool](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide.

### Set Windows to Clean Boot

![The Services tab in MSConfig](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-services-tab.jpg)

 Another possibility is that a software conflict might be causing error 0x80073D26 to occur on your PC. Setting Windows to clean boot by disabling third-party startup items will likely eliminate such a potential cause. That will stop third-party apps and services that could be conflicting with the Microsoft Store from automatically starting.

 To apply this fix, check out this guide about [clean-booting Windows 10 or 11](https://www.makeuseof.com/clean-boot-windows-11/). Disable startup programs in Task Manager and services in MS Config as covered within that guide; then restart your PC and try installing Microsoft Store games again to see if the issue persists.

### Reinstall the Microsoft Store

![The remove Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/remove-microsoft-store-command.jpg)

 Some users might need to reinstall the Microsoft Store to fix error 0x80073D26\. Such a resolution might be necessary for fixing wider issues with the Microsoft Store app other potential solutions don’t address.

 There isn’t a standard uninstall option available for Microsoft Store. So, you’ll have to reinstall that app with two PowerShell commands. Our guide about [how to reinstall the Microsoft Store](https://www.makeuseof.com/remove-reinstall-microsoft-store-windows-11/) tells you how to apply this potential fix.

### Perform an In-Place Windows Upgrade

 Some Microsoft Store users have also fixed error 0x80073D26 by performing an in-place Windows upgrade. An in-place upgrade is a method for installing the latest Windows 11/10 version without losing any installed software or user files.

 This will likely fix the 0x80073D26 error because it will refresh all of the system's registry entries, the system files, and also upgrade Windows to the latest version.

 Performing a Windows 11 in-place upgrade is relatively straightforward. All you need to do is download the latest Windows 11 ISO file, open it up, and launch the setup wizard from there. Our article about [performing an in-place upgrade of Windows 11](https://www.makeuseof.com/in-place-upgrade-windows-11/) includes full guidelines for how to do this.

![The Windows 11 Setup window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-11-setup-window2.jpg)

 You can also perform a Windows 10 in-place upgrade much the same. One difference is that you’ll need to download a Windows 10 Setup file by clicking **Download tool** on the [Microsoft Windows 10 download webpage](https://www.microsoft.com/en-gb/software-download/windows10). Then select **Upgrade this PC** now in the Windows 10 Setup wizard to install the latest version of the OS.

## Enjoy the Best Xbox Game Pass Games Available on the Microsoft Store

 It’s very likely the potential resolutions covered in this guide will fix error 0x80073D26, as some of them are widely confirmed to work. Hopefully, you can get this error fixed and get back into gaming.

 Players can’t enjoy their Xbox Game Pass titles because of error 0x80073D26, which makes this an annoying issue for Xbox Game Pass users. This is how you can fix the Microsoft Store error 0x80073D26 in Windows



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-lessons.techidaily.com/unveiling-top-techniques-for-vhs-image-transformation/"><u>Unveiling Top Techniques for VHS Image Transformation</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-cleanup-banishing-bloatware-on-win11/"><u>Accelerated Cleanup: Banishing Bloatware on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-email-checking-add-gmail-to-your-windows-side/"><u>Accelerated Email Checking: Add Gmail to Your Window's Side</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-navigating-gameplay-preservation-in-windows-10-for-2024/"><u>[New] Navigating Gameplay Preservation in Windows 10 for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/how-to-create-and-use-adjustment-layers-in-after-effects/"><u>How to Create and Use Adjustment Layers in After Effects</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-workflow-creating-windows-shortcuts-for-uwp/"><u>Accelerating Workflow: Creating Windows Shortcuts for UWP</u></a></li>
<li><a href="https://win11.techidaily.com/alter-display-angle-in-windows-settings/"><u>Alter Display Angle in Windows Settings</u></a></li>
<li><a href="https://fox-helps.techidaily.com/comprehensive-tutorial-for-periscope-proficiency/"><u>Comprehensive Tutorial for Periscope Proficiency</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-mobile-devices-for-windows-mic-input/"><u>Amplify Mobile Devices for Windows Mic Input</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-evening-enchantments-in-motion-reviewing-childrens-narrative-videos/"><u>2024 Approved  Evening Enchantments in Motion  Reviewing Children's Narrative Videos</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-increase-your-tiktok-presence-using-hashtags-effectively/"><u>[Updated] In 2024, Increase Your TikTok Presence  Using Hashtags Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/address-windows-missing-camera-mystery-in-device-manager/"><u>Address Windows' Missing Camera Mystery in Device Manager</u></a></li>
<li><a href="https://win11.techidaily.com/assess-if-your-system-qualifies-for-new-windows-11/"><u>Assess if Your System Qualifies for New Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-empty-folder-warning-windows/"><u>Addressing Empty Folder Warning Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-strategies-keeping-epic-launcher-non-freezing/"><u>Avoidance Strategies: Keeping Epic Launcher Non-Freezing</u></a></li>
<li><a href="https://win11.techidaily.com/altering-monitors-order-in-windows/"><u>Altering Monitors' Order in Windows</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-effortlessly-run-apps-and-videos-together-in-chrome/"><u>[Updated] How to Effortlessly Run Apps & Videos Together In Chrome</u></a></li>
<li><a href="https://win11.techidaily.com/acceleration-at-fingertips-3-ways-to-enhance-mouse-double-click-speed/"><u>Acceleration at Fingertips: 3 Ways to Enhance Mouse Double-Click Speed</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-0x0-failure-in-win11-setup-procedures/"><u>Avoid 0X0 Failure in Win11 Setup Procedures</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-best-14-text-animation-examples/"><u>In 2024, Best 14 Text Animation Examples</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-high-quality-youtube-recording-techniques-for-2024/"><u>[New] High-Quality YouTube Recording Techniques for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/automation-bane-keep-your-windows-backdrop-steady/"><u>Automation Bane: Keep Your Windows Backdrop Steady</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-sync-failures-with-microsoft-to-do/"><u>Addressing Sync Failures with Microsoft To Do</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-ram-demand-of-user-service-on-platforms/"><u>Addressing High RAM Demand of User Service on Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-alt-code-malfunctions-48-characters/"><u>Addressing Windows ALT Code Malfunctions (48 Characters)</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/achieving-professional-grade-slow-motions-in-your-tiktok-content/"><u>Achieving Professional-Grade Slow Motions in Your TikTok Content</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-the-account-lockout-counter-following-unsuccessful-logins-in-w10w11/"><u>Adjusting the Account Lockout Counter Following Unsuccessful Logins in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-synchronized-data-across-your-multiple-windows-desktops-with-aoemi/"><u>Achieve Synchronized Data Across Your Multiple Windows Desktops With AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-cannot-access-errors-for-files-in-win1011/"><u>Addressing 'Cannot Access' Errors for Files in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-wsl-2s-error-4294967295-on-a-win-os/"><u>Addressing WSL 2'S ERROR 4294967295 on a Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-software-removal-crafting-wins-context-menu-aids/"><u>Accelerating Software Removal: Crafting Win's Context Menu Aids</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-11-spatial-audio-setup-guide/"><u>Activating Windows 11: Spatial Audio Setup Guide</u></a></li>
<li><a href="https://win11.techidaily.com/adept-methods-for-switching-file-types-in-windows/"><u>Adept Methods for Switching File Types in Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-nokia-g310-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Nokia G310? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-on-your-iphone-se-2022-by-drfone-ios/"><u>In 2024, New Multiple Ways How To Remove iCloud Activation Lock On your iPhone SE (2022)</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-2024-approved-top-10-animated-photo-collage-apps-you-should-know/"><u>Updated 2024 Approved Top 10 Animated Photo Collage Apps You Should Know</u></a></li>
<li><a href="https://win11.techidaily.com/administrative-task-mastery-initiating-task-manager-in-win11/"><u>Administrative Task Mastery: Initiating Task Manager in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-system-awakening-tweak-windows-11-boot-timeout/"><u>Accelerating System Awakening: Tweak Windows 11 Boot Timeout</u></a></li>
<li><a href="https://win11.techidaily.com/automating-windows-11-app-installation-a-guide-to-winstall/"><u>Automating Windows 11 App Installation: A Guide to Winstall</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-phone-dialer-in-windows-11/"><u>Accessing Phone Dialer in Windows 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-guffaw-generation-generating-7-hilarious-video-moments-online/"><u>In 2024, Guffaw Generation  Generating 7 Hilarious Video Moments Online</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-clock-display-window-10-and-11-guide/"><u>Adjusting Clock Display: Window 10 & 11 Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-motorola-edge-40-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Motorola Edge 40 via a USB Cable | Dr.fone</u></a></li>
</ul></div>
