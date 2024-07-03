---
title: Navigating Win11 22H2 for Older Systems
date: 2024-06-25T11:33:39.685Z
updated: 2024-06-26T11:33:39.685Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Win11 22H2 for Older Systems
excerpt: This Article Describes Navigating Win11 22H2 for Older Systems
keywords: Win11 Upgrade Guide,22H2 Windows Support,Legacy PC Win11,XP/Vista to Win11,Older Systems Win11,Win11 Compatibility,Easy Win11 Installation
thumbnail: https://thmb.techidaily.com/526587f9f9083224ba90b469fae9f684a8ef66dad7a99594a73a26d6b57f4450.jpg
---

## Navigating Win11 22H2 for Older Systems

 If you have installed Windows 11 on unsupported hardware, the upgrade process will be a tough task. When you try to look for an update, Windows 11 shows everything as up to date and has no option to install the 22H2 version.

 While you can use the ISO-based clean install method, the upgrade process lets you install the latest version without deleting your apps and other data. Here’s how to upgrade to Windows 11 22H2 on unsupported hardware using the Windows 11 setup file.

## How to Upgrade to Windows 11 22H2 on Unsupported Hardware

[Windows 11 runs a hardware compatibility check](https://www.makeuseof.com/check-computer-compatible-windows-11-22h2/) during the upgrade process. To perform a successful upgrade, you’ll need to work around this hardware compatibility assessment. To achieve this, we’ll replace the appraiserress.dll file in Windows 11 ISO with the appraiserress.dll from Windows 10 ISO.

 If you have Windows 11 22H2 and Windows 10 ISO available, skip to the third step below. If not, follow all the steps to download the necessary ISOs and then perform an upgrade.

 While these steps shouldn’t cause any issues, it is better to[create a backup of any important Windows 11 data](https://www.makeuseof.com/windows-11-create-complete-backup/) on your system drive just in case something goes wrong and you need to perform a clean install.

## 1\. Download the Windows 11 22H2 ISO

![iso file download windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/iso-file-download-windows-11.jpg)

 You can[legally download the Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) from the Microsoft server directly or using Media Creation Tool. For this guide, we’ll use Media Creation Tool to download the ISO image file.

1. Go to the[Microsoft Software Download page](https://www.microsoft.com/software-download/windows11) .
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

1. Go to[Windows 10 download page](https://www.microsoft.com/en-us/software-download/windows10) .
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
3. Next, extract the Windows 11 ISO to a different folder. You can[use WinRAR to extract](https://www.win-rar.com/start.html?&L=0) the Windows 11 ISO file.  
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
<li><a href="https://win11.techidaily.com/hasten-enablingdisabling-microsofts-bing-assistant-in-taskbar/"><u>Hasten Enabling/Disabling: Microsoft's Bing Assistant in Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/winirq-fixing-killer-soundsystem-problems/"><u>WinIRQ: Fixing Killer Soundsystem Problems</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-avoid-no-permission-on-windows-file-viewing/"><u>Strategies to Avoid 'No Permission' On Windows File Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-silencing-windows-11-operations/"><u>Ultimate Guide: Silencing Windows 11 Operations</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-correcting-security-keys-mismatch-in-windows-11-networks/"><u>Strategies for Correcting Security Keys Mismatch in Windows 11 Networks</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-frustrating-fails-correcting-windows-error-1152/"><u>Avoiding Frustrating Fails: Correcting Windows' Error 1152</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mysteries-of-recurring-anydesk-errors-on-windows/"><u>Unraveling the Mysteries of Recurring AnyDesk Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-and-personalize-windows-11-files-via-added-movecopy/"><u>Streamline and Personalize Windows 11 Files via Added 'Move'/'Copy'</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-utilizing-qr-scanners-in-windows/"><u>The Ultimate Guide to Utilizing QR Scanners in Windows</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-snap-up-humor-kapwings-meme-mastery-tool/"><u>2024 Approved  Snap Up Humor - Kapwing’s Meme Mastery Tool</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/mastering-sound-with-adobe-audition-an-in-depth-look-at-its-core-components/"><u>Mastering Sound with Adobe Audition An In-Depth Look at Its Core Components</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-motorola-g54-5g-by-fonelab-android-recover-call-logs/"><u>How To  Restore Missing Call Logs from Motorola G54 5G</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-the-ultimate-guide-to-hash-tagging-for-brand-success-on-fb/"><u>[New] 2024 Approved  The Ultimate Guide to Hash Tagging for Brand Success on FB</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-spark-engagement-the-ultimate-list-of-video-text-effects/"><u>2024 Approved  Spark Engagement  The Ultimate List of Video Text Effects</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-making-your-twitter-media-a-gif-masterpiece/"><u>[New] 2024 Approved  Making Your Twitter Media A GIF Masterpiece</u></a></li>
<li><a href="https://unlock-android.techidaily.com/6-proven-ways-to-unlock-honor-x50-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Honor X50 Phone When You Forget the Password</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-install-kinemaster-on-mac-a-comprehensive-tutorial/"><u>New 2024 Approved Install KineMaster on Mac A Comprehensive Tutorial</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-activation-lock-from-the-iphone-11-pro-without-previous-owner-by-drfone-ios/"><u>How to Remove Activation Lock From the iPhone 11 Pro Without Previous Owner?</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-transition-tunes-mastering-crossfading-in-music/"><u>In 2024, Transition Tunes  Mastering Crossfading in Music</u></a></li>
</ul></div>
