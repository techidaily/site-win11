---
title: Addressing V22H2 Update Installation Obstacle in Win11
date: 2024-07-13T11:16:53.860Z
updated: 2024-07-14T11:16:53.860Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing V22H2 Update Installation Obstacle in Win11
excerpt: This Article Describes Addressing V22H2 Update Installation Obstacle in Win11
keywords: Win11 V22H2 Update Issue,Win11 Compatibility Challenge,Overcoming Win11 Updates,Resolving Win11 Installation Obstacles,Fixing Windows 11 Version 22H2 Issues,Win11 V22H2 Update Guide,Steps for Win11 Latest Update
thumbnail: https://thmb.techidaily.com/3631238ca7c06e0c64e4d00a9d13c9e8220b196fb6f2fa2e2f0075e18f87eaf2.jpg
---

## Addressing V22H2 Update Installation Obstacle in Win11

 Microsoft released its first Windows 11 build version update in September 2022\. The 22H2 update has added a slew of new Windows 11 features and options. Many users are now installing that update via Settings.

 However, some users have reported in forums that they can’t upgrade Windows 11 to the 22H2 version. Those users have said that updates get stuck at percentage marks when they try to download and install them from Settings. Some users see error codes like 0x800f0806 for that update. This is how you can fix the Windows 11 22H2 update not installing.

## 1\. Run Windows 11’s Troubleshooter for Updates

 The Windows Update troubleshooter is there to check for and resolve issues with the update process. That troubleshooter isn’t guaranteed to fix all update errors, but it might fix Windows 11’s 22H2 update not installing for some users at least. You can run the Windows Update troubleshooter in the following steps:

1. Press**Win** +**I** to open**Settings** .
2. Select the**System** tab’s**Troubleshoot** option.
3. Click**Other trouble-shooters** to reach the troubleshooting utilities.
4. Select**Run** for the Windows Update troubleshooter.  
![The Run button for Windows Update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-run-button-for-windows-update-1.jpg)
5. Wait for the troubleshooter to detect issues and display an outcome. It will usually automatically apply fixes for detected issues.

## 2\. Disconnect Non-Essential External Hardware and Peripherals From PC

 It's recommended that users unplug non-essential hardware from PCs before attempting to upgrade to a new Windows 11 version. Doing so will ensure that there aren't any non-essential hardware devices that can potentially interrupt or conflict with the upgrade process. You'll still need your mouse and keyboard of course, but disconnect all the following non-essential peripherals:

* Headphones
* External storage drives
* Printers
* Scanners
* Speakers (they're not essential)
* Gamepads
* USB Hubs
* Webcams
* Microphones
* Secondary monitors (you only need one)

## 3\. Run a System File and Deployment Image Scan

 System file corruption can cause Windows update errors to arise. You can check for and remedy corrupted files by running a System File Checker scan in the Command Prompt. It’s also recommended to run a Deployment Image Servicing and Management scan to check the system image before that. This is how to run both scanning tools in Windows 11.

1. Open the file search tool with the**Windows** +**S** hotkey.
2. Search for Command Prompt by inputting**cmd** in the text box.
3. Right-click Command Prompt inside the search tool’s results to select a**Run as administrator** option.
4. Start by inputting this command and pressing**Enter** :  
`DISM.exe /Online /Cleanup-image /Restorehealth`
5. Then run the SFC tool by typing in the following command and pressing**Return** :  
`sfc /scannow`
6. Wait for the SFC scan to show an outcome message in the Command Prompt.

## 4\. Free Up Some Drive Storage Space

 You’ll need at least 64 gigabytes of drive storage space available for the Windows 11 22H2 update. So, check your hard drive has enough space for the 22H2 update before installing it.

 If it doesn’t, free up the required drive storage space for the update by erasing superfluous files and uninstalling Windows software. Check out our [Cleanup recommendations guide](https://www.makeuseof.com/free-storage-space-with-cleanup-recommendations/) for further details about how to create storage space via Settings.

![Cleanup recommendations in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/cleanup-recommendations-1.jpg)

## 5\. Check If the Dependency Services for Windows Update are Enabled

 The Windows Update service has some service dependencies that need to be enabled and running. Windows 11 22H2 update issues will likely arise if necessary prerequisite services are disabled. You can make sure the Windows Module Installer, BITS, and CryptSvc services are enabled like this:

1. Open Windows 11’s Services utility. You can check out our [how-to-open Services guide](https://www.makeuseof.com/windows-11-open-services-app/) for further instructions.
2. Double-click**Windows Module Installer** to view a properties window for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/windows-modules-installer-1.jpg)
3. Select the**Automatic** start option for the service on its**Startup type** drop-down menu.
4. Click**Start** on the properties window if the service isn’t running.  
![The Windows Modules Installer service properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/a-service-properties-window-1.jpg)
5. Select**Apply** \>**OK** to set the service’s settings.
6. Repeat the previous four steps for the Background Intelligent Transfer Service, Cryptographic Service, and Windows Update services.

## 6\. Make Sure .NET Framework 3.5 is Enabled

 The .NET Framework 3.5 feature also needs to be enabled for the Windows Update service to work. That should be enabled by default in Windows 11, but some users may still need to turn on .NET Framework 3.5\. This is how you can make sure .NET Framework 3.5 is enabled in Windows 11:

1. Open the file and app search utility by pressing the**Windows** +**S** key combo.
2. Enter**Windows features** in the**Type here to search** box.
3. Click the**Turn Windows features on or off** applet in the search tool.
4. Select the**.NET Framework 3.5** checkbox if that feature isn’t enabled.  
![The Windows Features window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-windows-features-window-1.jpg)
5. Also, click the**.NET Framework 4.8** checkbox if it’s not selected.
6. Press the**OK** button in the Windows Features window.
7. Then click**Yes** to install.
8. Restart Windows 11 after installing the feature.

## 7\. Reset the Components for Windows Update

 Windows 11 22H2 update issues can also arise because of corrupted update components. You can repair the update components by resetting them. This troubleshooting method involves restarting update services and refreshing the catroot2 and SoftwareDistribution folders by renaming them. You can reset components for Windows updates with the Command Prompt like this:

1. Open Command Prompt with elevated permissions, as outlined in steps one to three of method two.
2. Then stop four services by inputting and executing the following commands:  
`net stop wuauserv  
net stop bits  
net stop cryptSvc  
net stop msiserver`
3. Next, rename the SoftwareDistribution folder by executing this command:  
`ren C:\Windows\SoftwareDistribution SoftwareDistribution.old`  
![The ren SoftwareDistribution command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-ren-softwaredistribution-command-1.jpg)
4. Input this rename catroot2 command and press**Return** :  
`ren C:\Windows\System32\catroot2 Catroot2.old`  
![The ren catroot2 folder command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-ren-catroot2-folder-1.jpg)
5. Then restart the services with these commands:  
`net start wuauserv  
net start bits  
net start cryptSvc  
net start msiserver`
6. Close Command Prompt, and select**Restart** on your Start menu.

## 8\. Turn Off Third-Party Antivirus Utilities

 Some third-party antivirus utilities can mistakenly interfere with the update process for Windows 11’s 22H2 update. To stop this from happening, disable real-time scanning for third-party antivirus software.

 If you have a third-party antivirus tool installed, right-click its system tray icon and select a context menu option to turn off its shield for a few hours; then try upgrading Windows 11 to the 22H2 version with the antivirus software disabled.

 AVG and Avast are two antivirus software packages that often generate Windows update errors. Those antivirus tools have also been incompatible with some Windows 10 builds. If you have either of those two installed, consider uninstalling them instead of merely disabling their shields.

## 9\. Disable Kernel DMA Protection

 Some users have said the Kernel DMA Protection security feature in Windows 11 causes the 22H2 update to fail when enabled. If that feature is enabled on your desktop or laptop, disabling it could fix the Windows 11 22H2 not installing. To check if Kernel DMA Protection is enabled,[open the System Information app](https://www.makeuseof.com/windows-11-check-system-information/) and look for that feature in the**System Summary** section.

![The Kernel DMA Protection system detail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-kernal-dma-system-detail-1.jpg)

 The only way to turn off Kernel DMA Protection is to disable a setting for it in the BIOS (Basic Input Output System). You can access Basic Input Output System settings on Windows 11/10 PCs as outlined within our guide on [how to enter the BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) . Look for and disable a Kernel DMA Protection setting on a**Security** tab within the BIOS.

## 10\. Update Your PC's Drivers

 Outdated device drivers can cause Windows upgrade issues. So, we recommend that you generally update device drivers on your PC. The quickest way to do that is to utilize a driver updater tool like Driver Booster.

 A Driver Booster scan will show you what devices on your PC have antiquated drivers. You can also select an**Update Now** option in that software to update the drivers for listed devices. Our [Driver Booster guide](https://www.makeuseof.com/update-windows-drivers-driver-booster-8/) includes instructions for updating drivers with that software.

![Driver Booster 8](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/driver-booster2.jpg)

 Alternatively, you may be able to install some new drivers with optional Windows updates. This is how you can check available optional updates in Windows 11:

1. [Open Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) and its**Windows Update** tab.
2. Select**Advanced options** to bring up some configuration settings for updates.
3. Click**Optional updates** to see if there are any driver updates available.
4. Select the checkboxes for driver updates there.
5. Click the**Download and install** option for selected driver updates.

## 11\. Install the 22H2 Update via the Installation Assistant

 This final resolution is more of a workaround than a fix for the 22H2 update not installing via Settings. Instead of using Settings, try upgrading with the Windows 11 Installation Assistant. We have a full guide that tells you [how to use the Installation Assistant](https://www.makeuseof.com/windows-11-installation-assistant-guide/) for updating Windows 11.

![The Windows 11 Update Assistant](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-windows-11-update-assistant.jpg)

## Discover the Windows 11 2022 Update

 Those possible solutions will likely resolve most 22H2 update errors for the majority of users. The resolutions on Microsoft’s [Windows update troubleshooting](https://support.microsoft.com/en-us/windows/troubleshoot-problems-updating-windows-188c2b0f-10a7-d72f-65b8-32d177eb136c#WindowsVersion=Windows%5F11) page might also help some users fix Windows 11’s 22H2 update not installing. With that issue fixed, you can discover all the interesting new features and options in the Windows 11 2022 Update.

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
<li><a href="https://win11.techidaily.com/adjusting-overheating-prevention-on-windows-pcs/"><u>Adjusting Overheating Prevention on Windows PCs</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-infinix-zero-30-5g-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/eradicate-stranded-status-from-xbox-console-experience-on-pc/"><u>Eradicate ‘Stranded’ Status From Xbox Console Experience on PC</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/exclusive-guide-to-the-leading-top-10-fb-videos-downloader-for-android/"><u>Exclusive Guide to the Leading Top 10 FB Videos Downloader for Android</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-the-key-to-mastering-tiktok-a-user-friendly-manual-for-applewindows-computers-for-2024/"><u>[Updated] The Key to Mastering TikTok  A User-Friendly Manual for Apple/Windows Computers for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/quick-steps-to-record-iphoneipad-screens-for-online-videos-for-2024/"><u>Quick Steps to Record iPhone/iPad Screens for Online Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-completely-get-rid-of-wsl-on-windows-11-pcs/"><u>How To Completely Get Rid of WSL on Windows 11 PCs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-premier-visual-experience-top-10-screen-selections-for-mac/"><u>2024 Approved  Premier Visual Experience  Top 10 Screen Selections for Mac</u></a></li>
<li><a href="https://extra-information.techidaily.com/giggle-genesis-creepy-clones-with-a-smile/"><u>Giggle Genesis  Creepy Clones with a Smile</u></a></li>
<li><a href="https://games-able.techidaily.com/xboxs-quick-resume-an-essential-advantage/"><u>Xbox's Quick Résumé - An Essential Advantage?</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-desk-customization-displaying-this-pc-image/"><u>Aesthetic Desk Customization: Displaying 'This PC' Image</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inaccessible-remove-functionality-on-windows-11-os/"><u>Fixing Inaccessible Remove Functionality on Windows 11 OS</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-5-ways-to-record-facetime-calls-for-2024/"><u>[New] 5 Ways to Record FaceTime Calls for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-full-circle-from-vocaloids-to-live-streamers-success/"><u>[New] Full Circle  From Vocaloids to Live Streamers' Success</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-11s-random-shutdown-phenomenon/"><u>Fix Windows 11'S Random Shutdown Phenomenon</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/sharing-tiktok-on-twitter-quickly-for-2024/"><u>Sharing TikTok on Twitter Quickly for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-detect-and-stop-mspy-from-spying-on-your-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Stop mSpy from Spying on Your Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/update-your-hardware-drivers-with-device-manager-on-windows-1110-by-drivereasy-guide/"><u>Update your hardware drivers with Device Manager on Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/discuss-the-limits-of-cultural-relativism-when-might-it-be-challenging-or-problematic-to-apply/"><u>Discuss the Limits of Cultural Relativism: When Might It Be Challenging or Problematic to Apply?</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-previewable-files-issue-in-outlook-for-personal-computers/"><u>Fixing Non-Previewable Files Issue in Outlook for Personal Computers</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-efficiency-essential-7-strategies-in-windows-11/"><u>Maximizing Efficiency: Essential 7 Strategies in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/coding-a-deity-command-into-system-menu/"><u>Coding a Deity Command Into System Menu</u></a></li>
<li><a href="https://win11.techidaily.com/winupgrade-hurdles-overcoming-error-code-xc004f050/"><u>WinUpgrade Hurdles: Overcoming Error Code Xc004f050</u></a></li>
<li><a href="https://win11.techidaily.com/clarifying-windows-memory-management-via-pagefilesys-files/"><u>Clarifying Windows' Memory Management via Pagefile.sys Files</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-potential-of-painting-with-microsoft-paint-on-windows-11/"><u>Unlock the Potential of Painting with Microsoft Paint on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-work-and-play-in-windows-11-schedules/"><u>Balancing Work and Play in Windows 11 Schedules</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-how-to-upload-and-post-gifs-onto-instagram-4-steps/"><u>[Updated] In 2024, How To Upload and Post GIFs Onto Instagram [4 Steps]</u></a></li>
<li><a href="https://win11.techidaily.com/executing-chatgpt-on-windows-systems/"><u>Executing ChatGPT on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/microphone-missing-reclaim-your-voice-in-windows-google-meet/"><u>Microphone Missing? Reclaim Your Voice in Windows Google Meet</u></a></li>
<li><a href="https://win11.techidaily.com/yourphone-in-windows-98-should-you-exercranize-it/"><u>YourPhone in Windows 9/8: Should You Exercranize It?</u></a></li>
<li><a href="https://win11.techidaily.com/ftdibussys-in-the-windows-ecosystem-a-dive-into-memory-shields/"><u>Ftdibus.sys in the Windows Ecosystem: A Dive Into Memory Shields</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-crafting-engaging-videos-with-adobe-captivate/"><u>[Updated] 2024 Approved  Crafting Engaging Videos with Adobe Captivate</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-your-gameplay-fixed-windows-wow-connectivity/"><u>Winning Back Your Gameplay: Fixed Windows WoW Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-common-onedrive-issues-on-pc/"><u>Conquering Common OneDrive Issues on PC</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-settings-app-overview/"><u>Windows 11 Settings App Overview</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/pinnacle-studio-for-mac-top-replacement-video-editors-to-consider-for-2024/"><u>Pinnacle Studio for Mac Top Replacement Video Editors to Consider for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-pristine-windows-image-display/"><u>Mastering the Art of Pristine Windows Image Display</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-quick-access-tools-into-the-win11-taskbar-easily/"><u>Incorporating Quick Access Tools Into the Win11 Taskbar Easily</u></a></li>
<li><a href="https://win11.techidaily.com/instantaneous-app-opener-tips-for-windows-11/"><u>Instantaneous App Opener Tips for Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-still-using-pattern-locks-with-samsung-galaxy-a15-5g-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Samsung Galaxy A15 5G? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-discovering-expert-seed-selection-for-valheimers/"><u>[Updated] Discovering Expert Seed Selection for Valheimers</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-native-pdf-displayer/"><u>Adjusting Windows' Native PDF Displayer</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-oppo-k11x-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Oppo K11x to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-tray-ui-show-number-keys-scroll-lock-windows-11/"><u>Customizing Tray UI: Show Number Keys, Scroll Lock Windows 11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/dealing-with-self-viewer-phenomenon-on-facebook-chats/"><u>Dealing with Self-Viewer Phenomenon on Facebook Chats</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-removing-unexpected-dark-screens-on-windows/"><u>Methods for Removing Unexpected Dark Screens on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-winuac-new-techniques-for-administrators/"><u>Enhancing WinUAC: New Techniques for Administrators</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-the-not-responsive-window-software-problem/"><u>Mastery over the Not Responsive Window Software Problem</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-elevate-your-gameplay-records-with-advanced-methods-on-w11-for-2024/"><u>[New] Elevate Your Gameplay Records with Advanced Methods on W11 for 2024</u></a></li>
</ul></div>
