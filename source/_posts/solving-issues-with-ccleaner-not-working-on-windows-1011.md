---
title: Solving Issues with CCleaner Not Working on Windows 10/11
date: 2024-07-13T10:05:04.407Z
updated: 2024-07-14T10:05:04.407Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Solving Issues with CCleaner Not Working on Windows 10/11
excerpt: This Article Describes Solving Issues with CCleaner Not Working on Windows 10/11
keywords: CCleaner Windows Troubleshooting,Fixing CCleaner Errors 10/11,Win10 CCleaner Fix Guide,Resolve CCleaner Not Started,CCleaner on Windows 10 Issue,CCleaner Not Working Solution,Troubleshoot CCleaner 11
thumbnail: https://thmb.techidaily.com/74045d9d6303c7a70563d004d7c7b11c2909530a50d24fd1a27318344d95b256.jpg
---

## Solving Issues with CCleaner Not Working on Windows 10/11

 CCleaner is one of the most widely utilized third-party system maintenance software packages for Windows 10 and 11 PCs. However, some users have reported on help forums they can’t utilize CCleaner because it’s not working for them. The CCleaner window doesn’t open when that software isn’t working.

 Many users report CCleaner not responding when they click to open that software. However, this Piriform software can also fail to start with error messages. This is how you can fix CCleaner not working on your Windows 11/10 PC.

## 1\. Try Opening CCleaner From Its Installation Directory

 Many users open CCleaner with desktop, taskbar, or Start menu shortcuts. However, CCleaner might not launch because of an issue with its shortcut. So, try opening CCleaner directly from its installation folder to see if that makes any difference. To do so, you’ll need to double-click the **CCleaner64.exe** application file within the software’s installation directory.

![The CCleaner.exe file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/ccleaner-exe-file.jpg)

 If you can launch CCleaner from the installation directory, there must be an issue with the shortcut for opening that software. In this case, set up a new Windows desktop shortcut by right-clicking the CCleaner EXE file and selecting **Send to (Desktop)**. Then try opening the software with the new CCleaner shortcut.

## 2\. Run CCleaner With Administrator Rights

 It’s not usually an essential requirement to run CCleaner with admin rights for that software to work. However, sometimes CCleaner can fail to start because of permissions issues that running it as an administrator might address. You can quickly see if this potential resolution works by right-clicking CCleaner’s shortcut or the EXE file in the installation directory and selecting **Run as administrator**.

 If that works, set CCleaner to always run with elevated privileges. Then you won’t need to manually select to run CCleaner with admin rights every time you need to open it. This guide about [how to always run apps as an administrator](https://www.makeuseof.com/tag/always-run-apps-administrator-windows/) includes instructions for permanently setting programs to start with elevated privileges.

![The RUn this program as an administrator checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/run-this-program-as-adminstrator-option.jpg)

## 3\. Delete the CCleanerx64 Registry Key

 Many users have confirmed they’ve fixed CCleaner not working by deleting a CCleanerx64 registry key. Although a confirmed fix, we still recommend backing up the Windows registry before deleting keys. Then erase the CCleaner registry key as follows:

1. First, hold the **Windows** logo key and press **R** to start the Run accessory.
2. Type **regedit** into Run’s **Open** command box and click **O**K.
3. Then go to this registry location either by entering it into the address bar or by clicking the keys in the sidebar:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options`  
![The Image File Execution Options registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-image-file-executions-key.jpg)
4. Right-click on the **CCleaner64.exe** key and select **Delete**.  
![The Delete context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/delete-ccleaner.jpg)
5. Select **Yes** on the Confirm Key Delete window prompt.
6. Click the Registry Editor app’s **X** Close window button and try opening CCleaner.

## 4\. Add CCleaner to Your Antivirus Software’s Exceptions List

 Antivirus programs that flag CCleaner as unwanted software can block that app from running. That’s more likely considering that this Piriform software has had its malware incidents in the past. Microsoft Defender was widely reported to flag CCleaner as unwanted software in 2020\. Some users have also confirmed disabling Trend Micro antivirus fixed CCleaner not working on their PCs.

 So, you might need to add CCleaner’s installation folder to your antivirus software’s exceptions list to fix that app not working. Our [guide to setting Windows Security exclusions](https://www.makeuseof.com/windows-11-security-exclusions/) provides guidelines for whitelisting software from the Microsoft Defender antivirus. If you utilize a third-party security app, add CCleaner to that software’s antivirus exclusion list.

![The Add an exclusion button in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/add-an-exclusion-button.jpg)

## 5\. Disable Your Active Firewalls

 CCleaner needs internet connectivity for updates, bug reporting, and its online features. Therefore, firewall blocks can be another cause for CCleaner not working. Disabling your PC’s firewall will ensure that it isn’t blocking CCleaner’s internet connectivity.

 This guide for [disabling Microsoft Defender Firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) provides full instructions for turning off that firewall protection. Users with third-party firewalls installed can select to turn them off via their settings tabs. If you’ve installed third-party antivirus software, disable its firewall component if it has one.

![The Turn off Windows Defender Firewall options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/turn-off-windows-defender-firewall3.jpg)

 Run CCleaner after turning off the firewall on your PC. The firewall was most likely causing the issue if the CCleaner software works when it's disabled. Add CCleaner to your firewall’s allowed app list to utilize that software with the firewall enabled. Our article about [allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) tells you how to add programs to Microsoft Defender Firewall’s allowed list.

## 6\. Run CCleaner After Clean-Booting Windows

 An app conflicting with the Piriform software could be another possible reason for CCleaner not working on your PC. Clean-booting Windows 11/10 will likely eliminate that potential cause. Setting a clean boot will disable most third-party startup programs and services that run in the background. Clean boot is like entering Windows safe mode, but it doesn’t disable any device drivers.

 To apply this possible solution for CCleaner not working, follow the instructions in this [how-to perform a clean boot](https://www.makeuseof.com/clean-boot-windows-11/) guide. Restart Windows after disabling startup items via Task Manager and MSConfig, and then try opening CCleaner again. If the CCleaner software works after the clean boot, a disabled app or service is likely the culprit.

![The Services tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/services-tab4.jpg)

 What you do then is up to you. You can leave the boot setup as set or try to find out what was conflicting with the CCleaner software. To find what’s causing the issue, re-enable disabled startup items in a one-at-a-time fashion before every reboot until CCleaner stops working again. Then either permanently disable or uninstall the conflicting service or app.

## 7\. Reinstall CCleaner

 If CCleaner still isn’t working after applying the other troubleshooting methods in this guide, you might have to reinstall the software. This will refresh all CCleaner’s files and registry entries. You can remove CCleaner with most of the methods outlined in this article about [uninstalling Windows software](https://www.makeuseof.com/windows-11-different-ways-to-uninstall-software/). We recommend uninstalling with one of the best uninstaller utilities to remove all leftover debris.

![The Uninstall option for CCleaner](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/programs-and-features-applet.jpg)

 You can reinstall a CCleaner UWP or desktop app. To get the desktop app, click **Free Download** on this [CCleaner page](https://www.anrdoezrs.net/links/7251228/type/dlg/sid/UUmuoUeUpU2029956/https://www.ccleaner.com/ccleaner/download?ppc%5Fcode=012&ppc=a&gclsrc=aw.ds&gclid=CjwKCAjwu4WoBhBkEiwAojNdXkgjDRZcy77PTMyhMnePxm%5FBXllDabqSn%5FMd9yAkWVbfhL5dYhBFjBoCYbYQAvD%5FBwE). Double-click the **ccsetup615.exe** file in the folder it downloads to view the setup window. Then you can click **Install** within the setup wizard to reinstall CCleaner.

 If you want to try the UWP app instead, open the [CCleaner Microsoft Store page](https://apps.microsoft.com/store/detail/ccleaner/XPFCWP0SQWXM3V), click on the **Get in Store app**, and **Open Microsoft Store** options to access an installation option for CCleaner. Press the **Install** button for the app.

## Clean Up Your PC With CCleaner Again

 There’s no guaranteed way to fix CCleaner not working. However, the troubleshooting methods above will probably kick-start the CCleaner software for Windows 11/10 in most cases. Then you can clean up your Windows 11/10 PC with all the tools CCleaner has to offer again.

 Many users report CCleaner not responding when they click to open that software. However, this Piriform software can also fail to start with error messages. This is how you can fix CCleaner not working on your Windows 11/10 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/the-windows-bar-evolution-story-1985present/"><u>The Windows Bar Evolution Story (1985–Present)</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-your-pc-display-interactive-and-lively-windows-11-walls/"><u>Revitalize Your PC Display: Interactive and Lively Windows 11 Walls</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-an-authentic-evaluation-of-recordcast-services/"><u>[Updated] An Authentic Evaluation of RecordCast Services</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-operation-warhammer-40k-boltgun-windows-stutter-fixes/"><u>Smooth Operation Warhammer 40K Boltgun: Windows Stutter Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-gaps-in-file-explorer-indexing/"><u>Correcting Gaps in File Explorer Indexing</u></a></li>
<li><a href="https://win11.techidaily.com/privacy-hacked-no-more-winning-encryption-tools-ranked-149-chars/"><u>Privacy Hacked No More: Winning Encryption Tools Ranked (149 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-top-9-changes-in-win11-february-2023/"><u>Unveiling the Top 9 Changes in Win11 February 2023</u></a></li>
<li><a href="https://win11.techidaily.com/decorate-your-screen-space-saving-spotlight-images-as-walls/"><u>Decorate Your Screen Space: Saving Spotlight Images as Walls</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-heat-in-windows-11-pcs/"><u>Troubleshooting Heat in Windows 11 PCs</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-wheres-the-community-twitch-and-youtube-side-by-side-for-2024/"><u>[New] Where's the Community? Twitch & YouTube Side by Side for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-the-best-free-video-trimmers-with-no-watermark-output/"><u>2024 Approved The Best Free Video Trimmers with No Watermark Output</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-11-glitches-solutions-guide/"><u>Unraveling WINDOWS 11 Glitches: Solutions Guide</u></a></li>
<li><a href="https://win11.techidaily.com/curing-store-failures-the-quick-fix-for-error-code-x00000000-in-windows-11/"><u>Curing Store Failures: The Quick Fix for Error Code X00000000 in Windows 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-activation-lock-on-mac-for-apple-iphone-14-plus-by-drfone-ios/"><u>In 2024, How To Bypass iCloud Activation Lock on Mac For Apple iPhone 14 Plus?</u></a></li>
<li><a href="https://win11.techidaily.com/recording-games-simply-mastering-screen-captures-with-intel-tools/"><u>Recording Games Simply: Mastering Screen Captures with Intel Tools</u></a></li>
<li><a href="https://win11.techidaily.com/aligning-your-preferences-with-nvidia-driver-choices/"><u>Aligning Your Preferences with Nvidia Driver Choices</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-breakdown-of-windows-startup-setup-options/"><u>A Step-by-Step Breakdown of Windows Startup Setup Options</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-restrictions-disabling-signatures-adding-unsigned-drivers/"><u>Navigating Windows' Restrictions: Disabling Signatures, Adding Unsigned Drivers</u></a></li>
<li><a href="https://apple-account.techidaily.com/why-apple-account-disabled-on-your-apple-iphone-12-pro-max-how-to-fix-by-drfone-ios/"><u>Why Apple Account Disabled On your Apple iPhone 12 Pro Max? How to Fix</u></a></li>
<li><a href="https://win11.techidaily.com/phoenix-rise-revive-gaming-pcs-with-atlasos/"><u>Phoenix Rise: Revive Gaming PCs with AtlasOS</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-overclocked-cpus-for-gaming-users/"><u>Troubleshooting Overclocked CPUs for Gaming Users</u></a></li>
<li><a href="https://win11.techidaily.com/the-power-and-essence-of-wintoys-an-uncomplicated-yet-comprehensive-explanation/"><u>The Power & Essence of 'WinToys': An Uncomplicated, Yet Comprehensive Explanation</u></a></li>
<li><a href="https://win11.techidaily.com/window-lockscreen-tips-engage-or-mute-spotlight-images/"><u>Window Lockscreen Tips: Engage or Mute Spotlight Images</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-fix-windows-11-when-you-cant-rename-folders/"><u>8 Ways to Fix Windows 11 When You Can’t Rename Folders</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-alt-code-not-responding-on-windows-pc/"><u>Overcoming ALT Code Not Responding on Windows PC</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/essential-recording-tools-top-5-webcam-capturers-for-2024/"><u>Essential Recording Tools - Top 5 Webcam Capturers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-global-communication-hotkeys-for-windows-language-switch/"><u>Optimizing Global Communication: Hotkeys for Windows Language SwitcH</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-asus-rog-phone-7-ultimatewithwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Asus ROG Phone 7 Ultimatewith/without a PC</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-global-scripts-a-windows-font-guide/"><u>Unleashing Global Scripts: A Windows Font Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-streamlabs-vs-obs-assessing-the-leading-livestream-tools-for-2024/"><u>[New] Streamlabs Vs. OBS  Assessing the Leading Livestream Tools for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-dynamic-unpriced-visual-bonding-games/"><u>[Updated] Dynamic Unpriced Visual Bonding Games</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-increase-win11-icons-size/"><u>Techniques to Increase Win11 Icons Size</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-take-notes-on-windows-11-without-downloading-software/"><u>5 Ways to Take Notes on Windows 11 Without Downloading Software</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-game-hub-error-code-0x800700e9-on-microsoft-devices/"><u>Resolving Game Hub Error Code 0X800700E9 on Microsoft Devices</u></a></li>
<li><a href="https://win11.techidaily.com/top-7-windows-photo-management-tools-an-essential-guide/"><u>Top 7 Windows Photo Management Tools: An Essential Guide</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-dual-logins-eliminating-mixed-account-errors/"><u>Conquering Dual Logins: Eliminating Mixed Account Errors</u></a></li>
<li><a href="https://win11.techidaily.com/triggering-driver-verifier-on-windows-11-pc/"><u>Triggering Driver Verifier on Windows 11 PC</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-streams-to-statements-decoding-the-3-step-process-for-calculating-youtube-earnings/"><u>[Updated] 2024 Approved  From Streams to Statements  Decoding the 3-Step Process for Calculating YouTube Earnings</u></a></li>
<li><a href="https://win11.techidaily.com/re-engaging-with-ms-store-a-stepwise-approach-to-windows-pcs/"><u>Re-Engaging with MS Store: A Stepwise Approach to Windows PCs</u></a></li>
<li><a href="https://extra-resources.techidaily.com/windows-media-player-guide-to-cd-ripping-and-burning/"><u>Windows Media Player Guide to CD Ripping and Burning</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-experience-microsoft-store-file-types-msixbundle/"><u>Streamline Your Experience: Microsoft Store File Types (MSixBundle)</u></a></li>
<li><a href="https://youtube-help.techidaily.com/exclusive-catalogue-free-to-use-stock-media-sites-for-2024/"><u>Exclusive Catalogue  Free-to-Use Stock Media Sites for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenating-inactive-recycle-bin-icon-on-win11/"><u>Rejuvenating Inactive Recycle Bin Icon on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-chrome-for-smooth-youtube-streaming/"><u>Optimizing Chrome for Smooth YouTube Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/1719365130359-mastery-over-malfunctioning-windows-easy-fixes-at-hand/"><u>Mastery Over Malfunctioning Windows: Easy Fixes at Hand</u></a></li>
<li><a href="https://extra-tips.techidaily.com/expert-tips-for-utilizing-funimate-downloader/"><u>Expert Tips for Utilizing Funimate Downloader</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-top-8-best-video-grabbers-for-windows-10/"><u>[Updated] In 2024, Top 8 Best Video Grabbers for Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/quick-resolution-for-windows-dism-failure-code-0x800f082f/"><u>Quick Resolution for Windows' DISM Failure Code: 0X800F082F</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-out-on-youtube-logo-tips-for-visibility-for-2024/"><u>Stand Out on YouTube  Logo Tips for Visibility for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-limited-use-of-chatgpt-in-pc/"><u>Optimizing Limited Use of ChatGPT in PC</u></a></li>
</ul></div>
