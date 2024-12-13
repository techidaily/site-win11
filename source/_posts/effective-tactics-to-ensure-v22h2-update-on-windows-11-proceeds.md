---
title: Effective Tactics to Ensure V22H2 Update on Windows 11 Proceeds
date: 2024-12-06T05:10:04.801Z
updated: 2024-12-12T23:51:19.225Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Effective Tactics to Ensure V22H2 Update on Windows 11 Proceeds
excerpt: This Article Describes Effective Tactics to Ensure V22H2 Update on Windows 11 Proceeds
keywords: Win11V22H2Update,H2UpdWin11Pro,V22TacticsWin,UpdateWin11Pro,ProcedureWinUpdate,H2WindowsTactic,WindowsV22Update
thumbnail: https://thmb.techidaily.com/13632811731c559bc127701456401507af159186a9de22e1aa59a5e7f9127b24.jpg
---

## Effective Tactics to Ensure V22H2 Update on Windows 11 Proceeds

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

 If it doesn’t, free up the required drive storage space for the update by erasing superfluous files and uninstalling Windows software. Check out our[Cleanup recommendations guide](https://www.makeuseof.com/free-storage-space-with-cleanup-recommendations/) for further details about how to create storage space via Settings.

![Cleanup recommendations in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/cleanup-recommendations-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 5\. Check If the Dependency Services for Windows Update are Enabled

 The Windows Update service has some service dependencies that need to be enabled and running. Windows 11 22H2 update issues will likely arise if necessary prerequisite services are disabled. You can make sure the Windows Module Installer, BITS, and CryptSvc services are enabled like this:

1. Open Windows 11’s Services utility. You can check out our[how-to-open Services guide](https://www.makeuseof.com/windows-11-open-services-app/) for further instructions.
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 9\. Disable Kernel DMA Protection

 Some users have said the Kernel DMA Protection security feature in Windows 11 causes the 22H2 update to fail when enabled. If that feature is enabled on your desktop or laptop, disabling it could fix the Windows 11 22H2 not installing. To check if Kernel DMA Protection is enabled,[open the System Information app](https://www.makeuseof.com/windows-11-check-system-information/) and look for that feature in the**System Summary** section.

![The Kernel DMA Protection system detail](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-kernal-dma-system-detail-1.jpg)

 The only way to turn off Kernel DMA Protection is to disable a setting for it in the BIOS (Basic Input Output System). You can access Basic Input Output System settings on Windows 11/10 PCs as outlined within our guide on[how to enter the BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) . Look for and disable a Kernel DMA Protection setting on a**Security** tab within the BIOS.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 10\. Update Your PC's Drivers

 Outdated device drivers can cause Windows upgrade issues. So, we recommend that you generally update device drivers on your PC. The quickest way to do that is to utilize a driver updater tool like Driver Booster.

 A Driver Booster scan will show you what devices on your PC have antiquated drivers. You can also select an**Update Now** option in that software to update the drivers for listed devices. Our[Driver Booster guide](https://www.makeuseof.com/update-windows-drivers-driver-booster-8/) includes instructions for updating drivers with that software.

![Driver Booster 8](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/driver-booster2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Alternatively, you may be able to install some new drivers with optional Windows updates. This is how you can check available optional updates in Windows 11:

1. [Open Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) and its**Windows Update** tab.
2. Select**Advanced options** to bring up some configuration settings for updates.
3. Click**Optional updates** to see if there are any driver updates available.
4. Select the checkboxes for driver updates there.
5. Click the**Download and install** option for selected driver updates.

## 11\. Install the 22H2 Update via the Installation Assistant

 This final resolution is more of a workaround than a fix for the 22H2 update not installing via Settings. Instead of using Settings, try upgrading with the Windows 11 Installation Assistant. We have a full guide that tells you[how to use the Installation Assistant](https://www.makeuseof.com/windows-11-installation-assistant-guide/) for updating Windows 11.

![The Windows 11 Update Assistant](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/the-windows-11-update-assistant.jpg)

## Discover the Windows 11 2022 Update

 Those possible solutions will likely resolve most 22H2 update errors for the majority of users. The resolutions on Microsoft’s[Windows update troubleshooting](https://support.microsoft.com/en-us/windows/troubleshoot-problems-updating-windows-188c2b0f-10a7-d72f-65b8-32d177eb136c#WindowsVersion=Windows%5F11) page might also help some users fix Windows 11’s 22H2 update not installing. With that issue fixed, you can discover all the interesting new features and options in the Windows 11 2022 Update.

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
<li><a href="https://facebook-clips.techidaily.com/new-discovering-social-medias-top-5-innovations-in-fb/"><u>[New] Discovering Social Media’s Top 5 Innovations in FB</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unleashing-3d-text-a-photoshop-technique/"><u>[New] Unleashing 3D Text A Photoshop Technique</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-navigating-mobile-recorders-to-capture-snapchat-moments/"><u>[Updated] 2024 Approved Navigating Mobile Recorders to Capture Snapchat Moments</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-beat-fiends-exploring-the-most-popular-rap-songs-on-tiktok/"><u>[Updated] In 2024, Beat Fiends Exploring the Most Popular Rap Songs on TikTok</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-how-to-upload-video-to-facebook-from-pc-and-android/"><u>[Updated] In 2024, How to Upload Video to Facebook From PC and Android</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tools-to-convert-videos-on-your-pc-windows/"><u>Essential Tools to Convert Videos on Your PC, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-code-xc0000142-errors-in-windows/"><u>Fixing Code XC0000142 Errors in Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-itel-p40-phone-forgot-password-by-drfone-android-unlock-android-unlock/"><u>How to Unlock Itel P40 Phone Forgot Password</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-innovate-personalized-digital-chuckle-comedy/"><u>In 2024, Innovate Personalized Digital Chuckle Comedy</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Samsung Galaxy F54 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/managing-overclocking-for-enjoyable-power-efficient-gaming/"><u>Managing Overclocking for Enjoyable, Power-Efficient Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-context-menu-customization-for-firewall-control-in-windows-11/"><u>Mastering Context Menu Customization for Firewall Control in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-secure-data-exchange-the-5-best-windows-programs/"><u>Mastering Secure Data Exchange: The 5 Best Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-0xc0351000-issue-finding-hyprocvisor-in-sandbox/"><u>Mitigating 0xC0351000 Issue: Finding Hyprocvisor in Sandbox</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-print-problem-fixes-on-your-windows-11-pc/"><u>Navigate Through Print Problem Fixes on Your Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-how-to-resize-apps-using-just-your-pc-keys-on-windows-11/"><u>Quick Fixes: How to Resize Apps Using Just Your PC Keys on Windows 11</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/1723175689342-revamp-your-rig-the-perfect-match-between-arctics-latest-36-cooler-and-intel-socket-lga1-groove/"><u>Revamp Your Rig: The Perfect Match Between Arctic's Latest 36 Cooler and Intel Socket LGA1 Groove</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/revitalize-your-aging-android-device-top-5-fresh-tricks/"><u>Revitalize Your Aging Android Device: Top 5 Fresh Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/windows-in-the-world-of-microcomputers/"><u>Windows in the World of Microcomputers</u></a></li>
</ul></div>

