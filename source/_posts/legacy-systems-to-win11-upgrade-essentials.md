---
title: Legacy Systems to Win11 Upgrade Essentials
date: 2024-08-16T00:12:04.965Z
updated: 2024-08-17T00:12:04.965Z
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
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
## 3\. Modify the Windows 11 ISO to Bypass Hardware Check During the Upgrade

 The following steps involve extracting the Windows 10 ISO and copying the appraiserress.dll file. Next, move the copied DLL file to the Windows 11 ISO’s sources folder. Here’s how to do it.

1. Right-click on the**Windows 10 ISO** file and select**Mount** . This will create a new virtual DVD Drive and open the ISO folder.  
![mount windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/mount-windows-10-iso.jpg)
2. Open the**Sources** folder and locate the**appraiserres.dll** file. Copy the**DLL** file and move it to a different folder.  
![copy appraiserres dll windows 10 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/copy-appraiserres-dll-windows-10-iso.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
3. Next, extract the Windows 11 ISO to a different folder. You can [use WinRAR to extract](https://www.win-rar.com/start.html?&L=0) the Windows 11 ISO file.  
![extract windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/extract-windows-11-iso.jpg)
4. Open the Windows 11 ISO's extracted folder and then the**Source** folder.
5. Next, copy and paste the**appraiserres.dll** file copied from Windows 10 ISO into Windows 11 ISO's**Sources** folder.

1. Select**Replace the file in the destination** to confirm the action.  
![replace the file in the destination appraiserrs ll windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/replace-the-file-in-the-destination-appraiserrs-ll-windows-11-iso.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
2. Next, disconnect your PC from the Internet. This prevents the setup from downloading updated files during installation and overwriting the modified dll file.
3. Once the Internet is disabled, open the extracted Windows 11 ISO folder and double-click on the**Setup file** . Click**Yes** if prompted by UAC.
4. In the**Windows 11 Setup** dialog, click on**Change how Setup downloads updates.**  
![windows 11 setup not right now updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-not-right-now-updates.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Next, select**Note right now.** This will prevent the Windows setup from finding and installing newer updates causing the upgrade process to fail on unsupported hardware.  
![windows 11 setup choose what to install](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-11-setup-choose-what-to-install.jpg)
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-game-capture-made-easy-with-5-methods-on-windows-11/"><u>[New] 2024 Approved  Game Capture Made Easy with 5 Methods on Windows 11</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-high-end-video-resizer-unparalleled-definition/"><u>[New] 2024 Approved  High-End Video Resizer  Unparalleled Definition</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-elite-zero-price-countdown-creators-for-2024/"><u>[New] Elite Zero-Price Countdown Creators for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-from-hd-to-breathtaking-eizos-newest-4k-display/"><u>[New] From HD to Breathtaking  EIZO's Newest 4K Display</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-mastering-youtube-clips-beginnings-and-conclusions-on-a-budget/"><u>[New] Mastering YouTube Clips  Beginnings & Conclusions on a Budget</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-premium-mobile-experience-with-best-gb-emulators-for-2024/"><u>[New] Premium Mobile Experience with Best GB Emulators for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-pewdiepies-annual-earnings-breakdown/"><u>[Updated] PewDiePie's Annual Earnings Breakdown</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-the-future-awaits-elevate-your-fb-chronicles-for-free-for-2024/"><u>[Updated] The Future Awaits  Elevate Your FB Chronicles for FREE for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-delete-a-drive-partition-on-windows/"><u>4 Ways to Delete a Drive Partition on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-view-the-registry-file-contents-on-windows-11/"><u>6 Ways to View the Registry File Contents on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-simple-guide-to-finding-out-what-model-you-run-on-windows/"><u>A Simple Guide to Finding Out What Model You Run on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-windows-11-shortcuts/"><u>A Step-by-Step Approach to Windows 11 Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/a-universal-companion-windows-now-app-for-iosmac-and-windows-devices/"><u>A Universal Companion: Windows Now App for iOS/Mac and Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/accessible-configuration-of-win11-connectivity-options/"><u>Accessible Configuration of Win11 Connectivity Options</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-the-character-visualization-tool/"><u>Accessing the Character Visualization Tool</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-a-pristine-windows-11-workspace/"><u>Achieve a Pristine Windows 11 Workspace</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-3d-audio-with-dolby-atmos-on-windows/"><u>Achieving 3D Audio with Dolby Atmos on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/adding-external-disk-to-explorers-sidebar/"><u>Adding External Disk to Explorer's Sidebar</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-audio-output-not-found-in-windows/"><u>Addressing Audio Output Not Found in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-malfunctions-in-windows-batch-file-systems/"><u>Addressing Malfunctions in Windows Batch File Systems</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tactics-make-windows-11-search-invisible/"><u>Advanced Tactics: Make Windows 11 Search Invisible</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-organizing-files-in-win-os-max-156/"><u>Advanced Tips for Organizing Files in Win OS (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-energy-drain-auto-shutdown-at-idle-in-win11/"><u>Avoiding Energy Drain: Auto-Shutdown at Idle in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-microsoft-store-crashes-solving-0x80072f30-error/"><u>Avoiding Microsoft Store Crashes: Solving 0X80072F30 Error</u></a></li>
<li><a href="https://win11.techidaily.com/awaken-clandestine-windows-11-search-sentinel/"><u>Awaken Clandestine Windows 11 Search Sentinel</u></a></li>
<li><a href="https://win11.techidaily.com/boost-chat-speed-enable-bing-ai-in-windows-11-menu-bar/"><u>Boost Chat Speed: Enable Bing AI in Windows 11 Menu Bar</u></a></li>
<li><a href="https://win11.techidaily.com/boot-barriers-busted-5-proven-steps-for-secure-boot-fixes/"><u>Boot Barriers Busted: 5 Proven Steps for Secure Boot Fixes</u></a></li>
<li><a href="https://driver-install.techidaily.com/complete-tech-makeover-reinstalling-your-video-driver/"><u>Complete Tech Makeover: Reinstalling Your Video Driver</u></a></li>
<li><a href="https://win11.techidaily.com/1719337262601-cure-frozen-shift-key-woes-quickly/"><u>Cure Frozen Shift Key Woes Quickly.</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-fixes-how-to-recover-forgotten-icloud-password-on-your-iphone-14-pro-by-drfone-ios/"><u>Easy Fixes How To Recover Forgotten iCloud Password On your iPhone 14 Pro</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-tecno-spark-10-pro-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Tecno Spark 10 Pro FRP Bypass With Best Methods</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/essential-80s-movie-marathon-the-ultimate-guide/"><u>Essential '80S Movie Marathon: The Ultimate Guide</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-the-two-factor-authentication-on-iphone-12-pro-max-by-drfone-ios/"><u>How To Remove the Two Factor Authentication On iPhone 12 Pro Max</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Xiaomi Redmi Note 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-track-apple-iphone-12-location-by-number-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Track Apple iPhone 12 Location by Number | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/lock-your-infinix-zero-30-5g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Infinix Zero 30 5G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://data-wizards.techidaily.com/mastering-the-removal-of-interlace-errors/"><u>Mastering the Removal of Interlace Errors</u></a></li>
<li><a href="https://extra-resources.techidaily.com/revolutionary-metaverse-tech-highlights-of-top-8-helmets/"><u>Revolutionary Metaverse Tech  Highlights of Top 8 Helmets</u></a></li>
</ul></div>
