---
title: How to Make Non-Loading Drivers Functional on Windows 11
date: 2024-06-25T09:50:36.467Z
updated: 2024-06-26T09:50:36.467Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Make Non-Loading Drivers Functional on Windows 11
excerpt: This Article Describes How to Make Non-Loading Drivers Functional on Windows 11
keywords: Fixing Loading Drivers in Win11,Driver Load Problems Windows 11,Boot Failure,Enabling Non-Loading Drivers,Troubleshoot Unloaded Drivers,Boot Issue,Activating Windows Drivers
thumbnail: https://thmb.techidaily.com/d8e6bf944e6c6a44077570ad300a1fab74b99e0c0b2c51be60c5944e75e29423.jpg
---

## How to Make Non-Loading Drivers Functional on Windows 11

 Windows loads drivers every time you power on your PC. However, some users face the "A driver can't load on this device" error after they boot to the desktop. This error can arise while installing an unsigned driver or due to a meddlesome application.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

## 1\. Check for Optional Windows Updates

 Optional updates can contain driver updates for your device components. So, you must check for available driver updates in the Windows Update Settings. Repeat the following steps:

1. Press **Win + I** to launch the Settings app.
2. Click on the **Windows Update** icon.
3. Now click on the **Advanced options**.
4. Scroll down to the **Additional Options** section. Click on the **Optional Updates** option.
5. Check if any optional updates related to the device you are facing issues with are available. Download and install it.  
![Install optional updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/install-optional-updates.jpg)
6. **Close** the Settings app.

 You can also visit the device manufacturer’s website to download the latest updated drivers, which will be digitally signed. These should pose no issues during installation.

## 2\. Disable the Memory Integrity Feature

 Memory Integrity is a security feature that leverages virtualization to protect unauthorized programs from making changes to important security processes. But this security setting can prevent a driver from loading old or unsigned drivers from running on your PC.

 So, you must disable Memory Integrity. Repeat the following steps:

1. Press **Win + I** to open the Settings app.
2. Click on the **Privacy & security** option in the left-hand side menu.
3. Now, click on the **Windows Security** option.
4. Scroll down and click on the **Device Security** option.
5. Navigate to the Core Isolation section. Click on the **Core isolation details** option.
6. Disable the **toggle** present below the **Memory Integrity** option.  
![Disable Memory Integrity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/disable-memory-integrity.jpg)
7. **Restart** your PC to apply the changes.

 Now, check if the “a driver cannot load on this device” still pops up.

## 3\. Uninstall Any Recent System Updates

 If you are encountering an issue with a driver after installing a recent Windows update, you should consider removing that from your PC. Rolling back the update won’t remove any of your personal files.

 Check our guide on [ways to manually uninstall Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) for more information. But remember that it is not possible to remove all installed updates.

## 4\. Modify the System Registry

 Corrupt registry entries for the device can also be a reason for the hardware device encountering the driver issue. So, you must modify the system registry and remove those corrupt entries for the device.

 Make sure to manually export a [backup of your PC registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) onto a removable drive, so you always have the option to revert to the last working configuration.

 Repeat the following steps:

1. Right-click on the **Start** button to open the **Power User menu**. Click on the **Device Manager** option.
2. Locate the device facing driver issues and double-click on it to open its **Properties**.
3. Switch to the **Details** tab.
4. Click on the drop-down tab and click on the **Class GUID** option. It will display the GUID. **Copy** it to the clipboard.  
![Checking GUID in Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/checking-guid-in-device-manager.jpg)
5. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **Regedit** and press the **Ctrl + Shift + Enter** keys to open the Registry editor.
6. Paste the following path into the address bar and press the **Enter** key:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Class\`
7. Press **Ctrl + F** to open the **Find** window. **Paste** the copied GUID and click on the **Find Next** option.
8. Go to the right-hand side pane of the found GUID key. Find the **UpperFilters** value.
9. Right-click on it and select the **Delete** option.  
![Modify the System Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/modify-the-system-registry.jpg)
10. Similarly, find the **LowerFilters** value and then delete it as well. Some devices may not have this value.
11. **Restart** your PC for the changes to take effect.

## 5\. Reinstall or Remove the Concerned Application

 Some users face an eny.sys driver issue which controls RGB lighting on PCs. This is a problem for many MSI and ASUS PC users. It is not a system utility and if it encounters an error every time, you must reinstall the concerned RGB-lighting-controlled application.

 Reinstalling the latest version will ensure that the application comes with signed drivers and fixes the driver issues with Windows 11 PCs. Here’s how to do it:

1. Right-click on the **Start** button to open the **Power User menu**.
2. Click on the **Installed apps** option.
3. Find the concerned RGB-controlling application and click on the **ellipsis** icon. Select the **Uninstall** option.
4. Click on the **Uninstall** button.  
![Remove a meddlesome application](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-a-meddlesome-application.jpg)

 After removing the app, restart your PC and check if the error pops up now. Now, visit the app manufacturer's website and download the recent version of the RGB-control app. Install it and check if it causes the driver error. If that is the case, then you must remove the application.

## 6\. Use System Restore

 System Restore is an excellent utility baked into Windows that helps you fix issues in one go. It will roll back your PC to an earlier state when there were no abrupt issues with your PC.

 Check our guide on [how to use System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) and revert to an earlier PC state without losing your personal files. However, all the installed apps and updates after the restore point will be removed, if you adopt this route.

## Your Driver Issues on Windows 11, Fixed

 These are the best methods you can use to fix the "A driver can't load on this device" error on your Windows 11 PC. Update all the device drivers, install optional updates, and disable memory integrity. After that, modify the system registry and remove the meddlesome RGB application to get rid of this problem.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/keep-your-window-pc-always-unlocked/"><u>Keep Your Window PC Always Unlocked</u></a></li>
<li><a href="https://win11.techidaily.com/explore-5-innovative-windows-folder-strategies/"><u>Explore 5 Innovative Windows Folder Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-comic-file-access-in-modern-windows/"><u>Streamlining Comic File Access in Modern Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-teams-stalling-in-w11w10-systems/"><u>Fixing Microsoft Teams Stalling in W11/W10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-boosting-productivity-in-project-management-tools/"><u>Expert Tips for Boosting Productivity in Project Management Tools</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-access-to-windows-odbc-settings/"><u>Mastering Access to Windows' ODBC Settings</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-management-using-mspcm-toolbar-in-w11-os/"><u>Efficient Management Using MSPCM Toolbar in W11 OS</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/2024-approved-everything-that-you-need-to-know-about-video-montages-ideas-techniques-and-software/"><u>2024 Approved Everything That You Need to Know About Video Montages- Ideas, Techniques, and Software</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Samsung Galaxy XCover 7 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-celebrating-the-hottest-instagram-after-effects-plugins/"><u>[Updated] In 2024, Celebrating the Hottest Instagram After Effects Plugins</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-peer-into-the-future-with-apeaksofts-screen-capture-trends-2023/"><u>[New] Peer Into the Future with Apeaksoft’s Screen Capture Trends 2023</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-xiaomi-redmi-note-12-pro-5g-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Xiaomi Redmi Note 12 Pro 5G phone? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-converting-soundcloud-to-mp3-like-a-pro-insider-tips/"><u>New 2024 Approved Converting Soundcloud to MP3 Like a Pro Insider Tips</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-remove-your-apple-id-permanently-from-iphone-xr-by-drfone-ios/"><u>In 2024, How To Delete iCloud Account Remove Your Apple ID Permanently From iPhone XR</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-frame-rate-considerations-for-high-quality-videos-for-2024/"><u>[Updated] Frame Rate Considerations for High-Quality Videos for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-step-by-step-instructions-for-fb-live-broadcasts-for-2024/"><u>[Updated] Step-by-Step Instructions for FB Live Broadcasts for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>