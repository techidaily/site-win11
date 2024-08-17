---
title: Navigate Auto-Updates & Change AMD GPU Drives in Win10
date: 2024-08-16T00:46:09.912Z
updated: 2024-08-17T00:46:09.912Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate Auto-Updates & Change AMD GPU Drives in Win10
excerpt: This Article Describes Navigate Auto-Updates & Change AMD GPU Drives in Win10
keywords: Windows Auto-Update Guide,Nvidia GPU Installation,Changing AMD Graphics,Update Driver on Windows,Radeon Drivers for PC,Graphic Card Settings Win10,Manage GPU in Windows 10
thumbnail: https://thmb.techidaily.com/3546fd9956a8b6a73b831712e52723669b090c846a7d2596697ef888fa555dd7.jpg
---

## Navigate Auto-Updates & Change AMD GPU Drives in Win10

 AMD Software Adrenaline Edition on Windows lets you manage your AMD graphics card, game stats, perform driver updates, and more. Sometimes, after an update, it may fail to launch with the error Windows update has replaced your AMD graphics driver.

 The full error reads Windows update may have automatically replaced your AMD graphics driver. This error is due to a conflict between the AMD Software Adrenaline Edition driver and the UWP AMD graphics driver installed by Windows.

 To fix the problem, you’ll need to stop Windows from installing AMD Radeon drivers automatically and perform a manual reinstall. Here’s how to do it.

## Why Does Windows Automatically Replace Your AMD Graphics Drivers?

 By default, the Windows operating system installs the[Microsoft Basic Display Adapter](https://www.makeuseof.com/microsoft-basic-display-adapter-guide/) during the initial setup. It provides display graphics capabilities so that you can set up your new computer and install the necessary drivers.

 This basic display driver lets you configure your discrete graphics with the latest drivers using AMD Software. It also acts as a backup when your discrete GPU driver faults causing[black screen issues on Windows](https://www.makeuseof.com/fix-black-screen-on-windows-10-11/) .

 However, this error occurs when Windows updates install the UWP (Universal Windows Platform) driver for your AMD Radeon GPU. Since two versions of the same driver are installed, when you try to open the AMD Software Adrenaline Edition app it will trigger an error.

 AMD has addressed this issue and provided a quick fix. To fix the error, you'll need to stop Windows from automatically installing the AMD graphics drivers. Then, reinstall the AMD graphics driver using AMD software.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## 1\. Roll Back the AMD Graphics Driver

![amd radeon display adapter driver roll back](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-display-adapter-driver-roll-back.jpg)

 An easy way to fix Windows replacing your AMD graphics error is to roll back the AMD graphics driver. A driver rollback removes the current driver and reinstalls the previous version saved on your computer. Fortunately, you can[roll back device drivers using the Windows Device Manager](http://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) .

 In Device Manager, look for and expand the**Display Adapters** section. Here, select the**AMD Radeon (TM) graphics** device and perform a driver rollback. Once done, restart your computer and check for any improvements. If the**Roll Back Driver** option is greyed out, you can't perform a rollback for the selected device.

 Once the error is resolved, you'll need to stop Windows from automatically downloading AMD drivers. If not, you’ll likely encounter the same error after each Windows update.

 You can[stop automatic driver updates on Windows](https://www.makeuseof.com/windows-stop-automatic-driver-updates/) using device installation settings,**Group Policy Editor** , and the**Windows Registry** . With the device installation settings for automatic driver download set to off, Windows won't download and install AMD graphics drivers automatically.

## 2\. Repair and Reinstall the AMD Software Driver

![amd radeon software installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-radeon-software-installer.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->

 You can reinstall the AMD Software driver using the existing driver. This may fix temporary issues with the driver causing the conflict. Follow these steps to repair and reinstall the AMD graphics driver:

1. Press**Win + E** to open File Explorer and navigate to the following location:  
`C:\AMD\RadeonInstaller\RadeonInstaller\Radeon_Folder_with_verison_name`
2. Next, double-click to run the**Setup.exe** file.  
![run amd setup exe repair graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/run-amd-setup-exe-repair-graphics-driver.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
3. In the**AMD Radeon Software Installer** dialog, select the driver version to install.
4. Click**Install** and wait for the driver to install.

 If you encounter an AMD error 195, temporarily[disable Windows Defender Firewall](https://www.makeuseof.com/how-to-turn-off-windows-defender/) and**Real-Time Threat Protection** and try again.

## 3\. Reinstall the AMDSoftware Graphics Driver

![amd software adrenaline edition uninstall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/amd-software-adrenaline-edition-uninstall.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->

 If the issue persists, try to remove and reinstall the AMD Software graphics driver. Once uninstalled, you can download the latest driver using the AMD Software.

To uninstall the AMD graphics driver:

1. Press**Win + I** to open**Settings** .
2. Open the**Apps** tab and click**Installed Apps** .
3. Next, search for**AMD Software** .  
![unisntall amd graphics driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/unisntall-adm-graphics-driver.jpg)
4. Click**Uninstall** and then**Uninstall** again to confirm the action.
5. Select**AMD Radeon Graphics** and click**Uninstall** .

 The AMD Software will start removing the driver from your computer. This process may take some time, and your monitor or display may flicker during the process. If it does, don't fret; it's just Windows getting used to the changes to your display drivers.

 Once done, click on**Finish** and restart your PC.

 When you uninstall a display driver, your secondary monitor can stop working. This will happen if your monitor's HDMI cable is directly connected to the port on your dedicated graphics unit. Your secondary display should work again as you reinstall the graphics driver.

 After the restart, you can[update your AMD Radeon graphics driver](https://www.makeuseof.com/update-amd-radeon-graphics-driver-windows-11/) using AMD Software. Install the driver and restart your PC to see if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
## 4\. Use a System Restore Point

 A restore point helps you recover your computer when a bad Windows update or driver installation causes the system to malfunction. You can use a restore point to undo the changes without affecting your data and files.

 Unfortunately, using a System Restore point requires you made one in the past. If you haven't made any, now's a good time to get into the habit of making them. Check out[how to make a System Restore point on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) for more information.

To undo the recent changes using a restore point:

1. Press**Win + R** to open**Run** .
2. Type**rstrui.exe** and click**OK** .  
![select restore point](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/select-restore-point.jpg)
3. In the**System Restore** dialog, select the**Recommended** **restore** option. If not, select the**Choose a different restore point** option**.**
4. Select a**restore point** and click**Next** .  
![select restore point windows 11 finish](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/select-restore-point-windows-11-finish.jpg)
5. Read the description and click**Finish** .
6. System Restore will restart and restore your PC to the state it was in before the date of the selected restore point.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
## Fixing the Windows Update May Have Automatically Replaced Your AMD Driver

 This error occurs if multiple versions of the same AMD Radeon graphics driver are installed on your computer. To fix the issue, perform a driver rollback for your AMD Radeon graphics in Device Manager. Once done, change the device installation setting to prevent Windows from automatically installing the OEM driver for your GPU.


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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-step-by-step-guide-to-refine-igtv-titles-and-descs/"><u>[New] 2024 Approved  Step-by-Step Guide to Refine IGTV Titles & Descs</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-structuring-complex-topics-in-youtube-content-a-chapter-by-chapter-approach/"><u>[New] 2024 Approved  Structuring Complex Topics in YouTube Content  A Chapter by Chapter Approach</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-a-curated-selection-of-top-6-nft-maker-applications/"><u>[Updated] 2024 Approved  A Curated Selection of Top 6 NFT Maker Applications</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-global-elite-top-12-tools-with-no-time-limit/"><u>[Updated] 2024 Approved  Global Elite  Top 12 Tools With No Time Limit</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-excellent-alternatives-top-5-to-replace-twitter-for-2024/"><u>[Updated] Excellent Alternatives  Top 5 to Replace Twitter for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-stellar-background-choices-for-effective-video-conferencing/"><u>2024 Approved  Stellar Background Choices for Effective Video Conferencing</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-facts-you-need-to-know-about-screen-mirroring-itel-a60s-drfone-by-drfone-android/"><u>3 Facts You Need to Know about Screen Mirroring Itel A60s | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bluetooth-trouble-heres-how-to-restore-it-on-your-pc-running-windows-10/"><u>Bluetooth Trouble? Here's How to Restore It on Your PC Running Windows 10</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/break-language-barriers-with-easy-online-and-autonomous-learning-options/"><u>Break Language Barriers with Easy Online & Autonomous Learning Options</u></a></li>
<li><a href="https://article-helps.techidaily.com/dji-mavic-pro-review-a-new-era-of-aerial-photography-for-2024/"><u>DJI Mavic Pro Review  A New Era of Aerial Photography for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-call-history-from-huawei-nova-y71-by-fonelab-android-recover-call-logs/"><u>Easy steps to recover deleted call history from Huawei Nova Y71</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-navigation-in-files-windows-11s-tab-system/"><u>Effortless Navigation in Files: Windows 11'S Tab System</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/elevating-your-unbox-sessions-secrets-for-more-views-and-likes-on-tiktok-for-2024/"><u>Elevating Your Unbox Sessions  Secrets for More Views and Likes on TikTok for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-real-time-performance-of-yuzu-emulator/"><u>Enhance Real-Time Performance of Yuzu Emulator</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-locked-or-disabled-from-iphone-6-7-mehtods-you-cant-miss-by-drfone-ios/"><u>In 2024, Apple ID Locked or Disabled From iPhone 6? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-20-mobiles-transforming-dji-aerial-video-art/"><u>In 2024, Top 20 Mobiles Transforming DJi Aerial Video Art</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-unleash-the-potential-of-your-webcam-for-slideshows/"><u>In 2024, Unleash the Potential of Your Webcam for Slideshows</u></a></li>
<li><a href="https://win11.techidaily.com/master-artistic-creation-with-windows-11-make-amazing-ai-images-using-paint-tool-sai/"><u>Master Artistic Creation with Windows 11: Make Amazing AI Images Using Paint Tool SAI</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-cross-device-use-harnessing-the-power-of-dex/"><u>Optimizing Cross-Device Use: Harnessing the Power of DeX</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-the-account-lockout-threshold-post-failed-attempts-win-11/"><u>Optimizing the Account Lockout Threshold Post Failed Attempts, Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-systemtray-to-showcase-number-keys/"><u>Personalizing SystemTray to Showcase Number Keys</u></a></li>
<li><a href="https://win11.techidaily.com/pinnacle-speed-5-expertly-engineered-pc-enhancements/"><u>Pinnacle Speed: 5 Expertly Engineered PC Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-easy-opening-mouse-properties-in-win11/"><u>Quick and Easy: Opening Mouse Properties in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-not-found-rockalldlldll-on-windows/"><u>Rectifying 'Not Found' Rockalldll.dll on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-onedrive-access-issue-in-windows-os-quickly/"><u>Resolve OneDrive Access Issue in Windows OS Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-combat-windows-camera-loss-of-media/"><u>Strategies to Combat Windows Camera Loss of Media</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-failed-task-execution-in-windows-with-error-0x8007000f/"><u>Tackling Failed Task Execution in Windows with Error 0X8007000f</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-for-resolving-widespread-rainmeter-challenges/"><u>The Ultimate Guide for Resolving Widespread Rainmeter Challenges</u></a></li>
<li><a href="https://win11.techidaily.com/transform-data-handling-visual-analyzer-for-disk-storage-on-windows/"><u>Transform Data Handling: Visual Analyzer for Disk Storage on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tricks-for-dealing-with-unyielding-power-controls-in-windows-11/"><u>Tricks for Dealing with Unyielding Power Controls in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unearthing-windows-11s-subdued-bar-scanner/"><u>Unearthing Windows 11'S Subdued Bar Scanner</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-win11-sefx-archive-techniques/"><u>Unlocking Win11 SEFx Archive Techniques</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unveiling-lgs-monitor-magic-a-comprehensible-review-of-4k-tech-for-2024/"><u>Unveiling LG's Monitor Magic  A Comprehensible Review of 4K Tech for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-approach-to-turn-off-gpgpu-prioritization-on-winos/"><u>Unveiling the Approach to Turn Off GPGPU Prioritization on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/upgrading-virtualbox-to-70-in-win11-a-comprehensive-tutorial/"><u>Upgrading VirtualBox to 7.0 in Win11: A Comprehensive Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/visualizing-data-footprint-in-windows-os/"><u>Visualizing Data Footprint in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-10s-best-encryption-software-compared-153-chars/"><u>Windows 10'S Best Encryption Software, Compared (153 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/xbox-not-launching-fix-it-with-these-tips/"><u>Xbox Not Launching? Fix It with These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/your-way-your-window-customize-windows-11-today/"><u>Your Way, Your Window: Customize Windows 11 Today</u></a></li>
</ul></div>
