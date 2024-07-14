---
title: Legacy Systems to Win11 Upgrade Essentials
date: 2024-07-13T10:22:47.427Z
updated: 2024-07-14T10:22:47.427Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Legacy Systems to Win11 Upgrade Essentials
excerpt: This Article Describes Legacy Systems to Win11 Upgrade Essentials
keywords: LegacyUpgradeWin11,Win11LegacyBoost,SystemWin11Migration,Win11OldSystems,UpgradeWin11Legacy,WinTransitionLegacy,OldOSToWin11Upgrade
thumbnail: https://thmb.techidaily.com/7e37922976a0cd02bd45d34c10fef6f069d63ae07942af07cd489ff374cb4abd.png
---

## Legacy Systems to Win11 Upgrade Essentials

 If you have installed Windows 11 on unsupported hardware, the upgrade process will be a tough task. When you try to look for an update, Windows 11 shows everything as up to date and has no option to install the 22H2 version.

 While you can use the ISO-based clean install method, the upgrade process lets you install the latest version without deleting your apps and other data. Here’s how to upgrade to Windows 11 22H2 on unsupported hardware using the Windows 11 setup file.

## How to Upgrade to Windows 11 22H2 on Unsupported Hardware

[Windows 11 runs a hardware compatibility check](https://www.makeuseof.com/check-computer-compatible-windows-11-22h2/) during the upgrade process. To perform a successful upgrade, you’ll need to work around this hardware compatibility assessment. To achieve this, we’ll replace the appraiserress.dll file in Windows 11 ISO with the appraiserress.dll from Windows 10 ISO.

 If you have Windows 11 22H2 and Windows 10 ISO available, skip to the third step below. If not, follow all the steps to download the necessary ISOs and then perform an upgrade.

 While these steps shouldn’t cause any issues, it is better to [create a backup of any important Windows 11 data](https://www.makeuseof.com/windows-11-create-complete-backup/) on your system drive just in case something goes wrong and you need to perform a clean install.

## 1\. Download the Windows 11 22H2 ISO

![iso file download windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/iso-file-download-windows-11.jpg)

 You can [legally download the Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) from the Microsoft server directly or using Media Creation Tool. For this guide, we’ll use Media Creation Tool to download the ISO image file.

1. Go to the [Microsoft Software Download page](https://www.microsoft.com/software-download/windows11) .
2. Click on**Download Now** under**Create Windows 11 Installation Media.**
3. Run the**mediacreationtool.exe** file and accept the license terms.
4. Review the selected language and edition. To change the language, uncheck**Use the recommended options for this PC** and select your preferred language.
5. Click**Next** .
6. Select the**ISO file** option in the**Choose which media to use** dialog.
7. Select the download location and click**Save** . Make sure the selected partition has enough space available.
8. Media Creation Tool will start downloading the ISO to your local drive. This process may take some time, depending on your Internet connection. So wait for the download to complete.
9. Once the download is complete, click**Finish** and follow the next step to download Windows 10 ISO.

## 2\. Download a Windows 10 ISO

![windows 10 download ISO preference](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-10-download-iso-preference.jpg)

 You’ll need to modify the Windows 11 ISO by replacing the appraiserress.dll with a version available in Windows 10 ISO. This DLL file is responsible for performing a hardware check during an upgrade.

To download Windows 10 ISO:

1. Go to [Windows 10 download page](https://www.microsoft.com/en-us/software-download/windows10) .
2. Click the**Download Now** button under**Create Windows 10 installation media** .
3. Run the**mediacreationtool.exe** file to open Windows 10 Setup dialog.
4. Click on**Accept** .
5. In the**What do you want to do** screen, select**Create installation media** and click**Next** .
6. Check if the language, edition, and architecture preferences are set correctly. If not, click on**Use the recommended options for this** **device** and set your preferences.
7. Next, select the**ISO file** option and click**Next** .
8. Select the download location and click**Save** .
9. The downloading process may take several minutes to complete. So wait for the process to complete and click**Finish** once done.

 Once you have both the ISO files saved, follow the next step to extract and modify the Windows 11 ISO.

## 3\. Modify the Windows 11 ISO to Bypass Hardware Check During the Upgrade

 The following steps involve extracting the Windows 10 ISO and copying the appraiserress.dll file. Next, move the copied DLL file to the Windows 11 ISO’s sources folder. Here’s how to do it.

1. Right-click on the**Windows 10 ISO** file and select**Mount** . This will create a new virtual DVD Drive and open the ISO folder.  
![mount windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/mount-windows-10-iso.jpg)
2. Open the**Sources** folder and locate the**appraiserres.dll** file. Copy the**DLL** file and move it to a different folder.  
![copy appraiserres dll windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-appraiserres-dll-windows-10-iso.jpg)
3. Next, extract the Windows 11 ISO to a different folder. You can [use WinRAR to extract](https://www.win-rar.com/start.html?&L=0) the Windows 11 ISO file.  
![extract windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/extract-windows-11-iso.jpg)
4. Open the Windows 11 ISO's extracted folder and then the**Source** folder.
5. Next, copy and paste the**appraiserres.dll** file copied from Windows 10 ISO into Windows 11 ISO's**Sources** folder.

1. Select**Replace the file in the destination** to confirm the action.  
![replace the file in the destination appraiserrs ll windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/replace-the-file-in-the-destination-appraiserrs-ll-windows-11-iso.jpg)
2. Next, disconnect your PC from the Internet. This prevents the setup from downloading updated files during installation and overwriting the modified dll file.
3. Once the Internet is disabled, open the extracted Windows 11 ISO folder and double-click on the**Setup file** . Click**Yes** if prompted by UAC.
4. In the**Windows 11 Setup** dialog, click on**Change how Setup downloads updates.**  
![windows 11 setup not right now updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-not-right-now-updates.jpg)
5. Next, select**Note right now.** This will prevent the Windows setup from finding and installing newer updates causing the upgrade process to fail on unsupported hardware.  
![windows 11 setup choose what to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-choose-what-to-install.jpg)
6. In the**Choose what to keep** screen, select**Keep personal files and apps.**
7. Click**Next** and then click on**Accept** .  
![windows 11 setup ready to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-ready-to-install.jpg)
8. Next, click on**Install** to install Windows 11 version 22H2 while keeping your personal files and apps.
9. Leave your computer idle until the installation process is complete. After the restart, you’ll have the latest Windows 11 22H2 running on your computer.

To check your Windows specification:

![check windows specification windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/check-windows-specification-windows-11.jpg)

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**About** .
3. Under Windows specifications, you’ll see**Version 22H2** if the upgrade was successful.

## 4\. Go Back to the Previous Version

![go back windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/go-back-windows-11.jpg)

 If you run into an issue after the upgrade, you can use the**Go back** option to undo the update and restore the earlier version of Windows 11\. However, the "Go back" option is only available for seven days since the upgrade. After that, the option will be greyed out.

To go back to the previous version:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Recovery** .
3. Click on**Go back** under**Recovery options** . Then, follow the on-screen instructions to uninstall the Windows 22H2 update.

## Installing Windows 11 22H2 on Unsupported Hardware

 It is easy to bypass the Windows 11 system hardware requirements when you want to perform a clean install. However, to perform an upgrade, you’ll need to modify the appraiserress.dll file and then run the setup.

 While the upgrade is possible for now, the lack of future automatic Windows updates makes maintaining the PC a complicated task. If upgrading to Windows 11 is not a must, you can stick to Windows 10 on older hardware, which will continue to receive support until late 2025.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/how-to-rescue-your-windows-mail-app-from-the-clutches-of-0x800713f/"><u>How to Rescue Your Windows Mail App From the Clutches of 0X800713F</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-function-key-modifications-in-windows-1011/"><u>Effortless Function Key Modifications in Windows 10/11</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-oppo-a79-5g-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Oppo A79 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-blank-spaces-in-windows-explorer/"><u>Eliminating Blank Spaces in Windows Explorer</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-a-step-by-step-strategy-for-dominating-the-digital-marketing-arena/"><u>[New] A Step-by-Step Strategy for Dominating the Digital Marketing Arena</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-inaugural-vision-preservation-review-and-alternate-suggestions-for-2024/"><u>[Updated] Inaugural Vision Preservation Review & Alternate Suggestions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-windows-for-contactless-entry-methods/"><u>Setting Up Windows For Contactless Entry Methods</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-fatal-error-code-0x8007007e/"><u>Addressing Windows Fatal Error: Code 0X8007007E</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-workflow-creating-windows-11-folders-en-masse/"><u>Accelerate Workflow: Creating Windows 11 Folders En Masse</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-functional-cortana-on-windows-11/"><u>Addressing Non-Functional Cortana on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fix-unrecognized-app-warning-during-windows-setup/"><u>Fix Unrecognized App Warning During Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/designing-a-secure-hardware-removal-window-tip/"><u>Designing a Secure Hardware Removal Window Tip</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-failed-onedrive-cloud-sync/"><u>Strategies for Fixing Failed OneDrive Cloud Sync</u></a></li>
<li><a href="https://win11.techidaily.com/security-simplified-defaults-in-windows-11-setup/"><u>Security Simplified: Defaults in Windows 11 Setup</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-quick-steps-to-capture-ios-audio-files-for-2024/"><u>[New] Quick Steps to Capture iOS Audio Files for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/top-best-video-editor-with-music-for-pc-users/"><u>Top Best Video Editor with Music For PC Users</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-guide-to-the-latest-tiktok-screen-art/"><u>[New] Guide to the Latest TikTok Screen Art</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-xiaomi-redmi-note-12t-pro-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Xiaomi Redmi Note 12T Pro without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-not-empty-directory-problem-in-windows-os/"><u>Steps to Overcome Not Empty Directory Problem in Windows OS</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-simplified-steps-for-saving-gotomeeting-sessions/"><u>[New] 2024 Approved  Simplified Steps for Saving GoToMeeting Sessions</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-smartphone-accessories-for-making-videos/"><u>2024 Approved  Smartphone Accessories for Making Videos</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-masterful-guide-integrating-youtube-and-social-media-platforms-fb/"><u>2024 Approved  Masterful Guide  Integrating YouTube and Social Media Platforms FB</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-narrative-noble-order-honors-hexagon/"><u>[New] Narrative Noble Order - Honor's Hexagon</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-glass-idleness-techniques-guide/"><u>Mastering Windows Glass Idleness Techniques Guide</u></a></li>
<li><a href="https://win11-tips.techidaily.com/harmonize-window-11-settings-for-clear-prime-video-texts/"><u>Harmonize Window 11 Settings for Clear Prime Video Texts</u></a></li>
<li><a href="https://win11.techidaily.com/precision-steps-restoring-your-windows-11-search-efficiency/"><u>Precision Steps: Restoring Your Window's 11 Search Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-pcs-archives-functionality/"><u>Enhance Your PC's Archives Functionality</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-top-8-android-tools-for-professional-music-production-for-2024/"><u>New Top 8 Android Tools for Professional Music Production for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/proven-methods-to-improve-zoom-efficiency-on-a-chromebook/"><u>Proven Methods to Improve Zoom Efficiency on a Chromebook</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-command-prompt-gimmicks-unleashed/"><u>Top 5 Command Prompt Gimmicks Unleashed</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-unlock-fb-potential-with-2023s-top-free-tools-for-posts/"><u>[Updated] Unlock FB Potential with 2023’S Top-Free Tools for Posts</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solution-to-interrupt-error-in-windows-11-screensaver/"><u>Swift Solution to INTERRUPT ERROR in Windows 11 Screensaver</u></a></li>
<li><a href="https://win11.techidaily.com/wired-for-security-swiftly-repairing-windows-features/"><u>Wired for Security: Swiftly Repairing Windows Features</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-from-studio-to-stage-stream-your-mp3-tunes-on-youtube/"><u>[Updated] From Studio to Stage  Stream Your MP3 Tunes on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-gameplay-preventing-minecraft-freezes/"><u>Secure Your Gameplay: Preventing Minecraft Freezes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-guidance-to-creating-a-3d-text-art-effect-in-adobe-illustrator/"><u>[New] Guidance to Creating a 3D Text Art Effect in Adobe Illustrator</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-best-practices-for-filming-and-sharing-immersive-content-on-fb/"><u>[Updated] 2024 Approved  Best Practices for Filming and Sharing Immersive Content on FB</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-value-airborne-inventors-budget-friendly-flight-tools/"><u>[Updated] In 2024, Value Airborne Inventors  Budget-Friendly Flight Tools</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-dismantling-a-blocked-update/"><u>Deciphering and Dismantling a Blocked Update</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-device-unreachable-errors/"><u>Resolving Windows Device Unreachable Errors</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/detailed-guide-taking-full-screen-photos-with-android-for-2024/"><u>Detailed Guide  Taking Full-Screen Photos with Android for 2024</u></a></li>
</ul></div>
