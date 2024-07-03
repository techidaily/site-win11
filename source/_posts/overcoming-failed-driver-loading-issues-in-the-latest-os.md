---
title: Overcoming Failed Driver Loading Issues in the Latest OS
date: 2024-06-25T11:36:04.819Z
updated: 2024-06-26T11:36:04.819Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Failed Driver Loading Issues in the Latest OS
excerpt: This Article Describes Overcoming Failed Driver Loading Issues in the Latest OS
keywords: Fixing Drivers Errors,OS Boot Failure Resolution,Addressing Loaded Driver Problems,Solving Driver Reload Mishaps,Correcting Load Driver Issues,Troubleshooting OS Startup Glitches,Enhancing System Boot Success
thumbnail: https://thmb.techidaily.com/1b9c0ec4aac0a389de35bac2a472d37b33435d994c1a8448795d8b564ff658a3.jpg
---

## Overcoming Failed Driver Loading Issues in the Latest OS

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
<li><a href="https://win11.techidaily.com/how-to-clear-unidentified-devices-issue-in-win-11/"><u>How to Clear Unidentified Devices Issue in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-experience-microsoft-store-file-types-msixbundle/"><u>Streamline Your Experience: Microsoft Store File Types (MSixBundle)</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-0x00000001-restoring-xbox-playability/"><u>Remedy for 0X00000001: Restoring Xbox Playability</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-issue-code-0x80071a90/"><u>Decoding Windows Issue: Code 0X80071a90</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-toolbar-in-microsoft-pc-manager-on-windows-11/"><u>How to Use the Toolbar in Microsoft PC Manager on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unshackle-chromiums-network-access-via-windows-settings-blockers/"><u>Unshackle Chromium's Network Access via Windows Settings Blockers</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-curse-of-wow-error-132-a-step-by-step-approach/"><u>Beating the Curse of WoW Error #132: A Step-by-Step Approach</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/2024-approved-track-your-every-step-top-motion-tracking-apps/"><u>2024 Approved Track Your Every Step Top Motion Tracking Apps</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-essential-info-for-tweeting-videos-aspect-ratios-required-for-2024/"><u>[Updated] Essential Info for Tweeting Videos  Aspect Ratios Required for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/cyberspace-celebs-top-youtube-personalities-by-views/"><u>Cyberspace Celebs  Top YouTube Personalities by Views</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-vcr-video-vault-extensive-reviews-and-summary/"><u>[New] 2024 Approved  VCR Video Vault  Extensive Reviews & Summary</u></a></li>
<li><a href="https://some-approaches.techidaily.com/streamlining-business-with-azure-speech-services-for-2024/"><u>Streamlining Business with Azure Speech Services for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-boosting-instagram-visibility-the-ultimate-guide-to-puzzle-feeds/"><u>[Updated] 2024 Approved  Boosting Instagram Visibility  The Ultimate Guide to Puzzle Feeds</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-data-from-apple-iphone-15-to-new-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How To Transfer Data from Apple iPhone 15 to New iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/leverage-timestamps-tactics-to-skyrocket-video-views-for-2024/"><u>Leverage Timestamps  Tactics to Skyrocket Video Views for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>