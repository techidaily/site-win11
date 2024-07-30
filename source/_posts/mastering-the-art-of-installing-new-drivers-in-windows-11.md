---
title: Mastering the Art of Installing New Drivers in Windows 11
date: 2024-07-29T15:48:40.022Z
updated: 2024-07-30T15:48:40.022Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Art of Installing New Drivers in Windows 11
excerpt: This Article Describes Mastering the Art of Installing New Drivers in Windows 11
keywords: Windows Driver Update Guide,Windows 11 Driver Installation,Nvidia Driver Installation W11,AMD Firmware Update Windows 11,Windows Drivers for Optimal Performance,Microsoft Windows Hardware Compatibility,New Driver Installation Tips Windows
thumbnail: https://thmb.techidaily.com/afcb9c2878394644f41c39d4475ac640d665c752413696b921520d8ad80368e6.jpg
---

## Mastering the Art of Installing New Drivers in Windows 11

 Windows loads drivers every time you power on your PC. However, some users face the "A driver can't load on this device" error after they boot to the desktop. This error can arise while installing an unsigned driver or due to a meddlesome application.

 In this guide, we will discuss some methods to resolve this issue and restore your PC drivers to a normal working state.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Uninstall Any Recent System Updates

 If you are encountering an issue with a driver after installing a recent Windows update, you should consider removing that from your PC. Rolling back the update won’t remove any of your personal files.

 Check our guide on [ways to manually uninstall Windows updates](https://www.makeuseof.com/manually-uninstall-windows-10-updates/) for more information. But remember that it is not possible to remove all installed updates.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
![Modify the System Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/modify-the-system-registry.jpg)
10. Similarly, find the **LowerFilters** value and then delete it as well. Some devices may not have this value.
11. **Restart** your PC for the changes to take effect.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-capturing-action-choosing-from-5-leading-game-stream-webcams/"><u>[New] 2024 Approved  Capturing Action  Choosing From 5 Leading Game Stream Webcams</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-the-art-of-video-clarity-with-version-22-vce/"><u>[New] Mastering the Art of Video Clarity with Version 2.2 VCE</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-pro-tiktok-intro-creation-maximizing-your-macs-capabilities/"><u>[New] Pro TikTok Intro Creation  Maximizing Your Mac's Capabilities</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-cutting-edge-videography-bordering-techniques-for-ig/"><u>[Updated] 2024 Approved  Cutting-Edge Videography  Bordering Techniques for IG</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-picks-streaming-tunes-directly-from-youtuberingtones/"><u>[Updated] Top Picks  Streaming Tunes Directly From YoutubeRingtones</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-xiaomi-redmi-13c-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart Xiaomi Redmi 13C Without Power Button | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-oppo-k11x-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/add-on-troubleshooters-for-improved-software-functionality/"><u>Add-On Troubleshooters for Improved Software Functionality</u></a></li>
<li><a href="https://extra-tips.techidaily.com/biometric-battleground-face-id-vs-samsungs-facial-identification-for-2024/"><u>Biometric Battleground  Face ID Vs. Samsung's Facial Identification for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/breezy-video-capture-testimony/"><u>Breezy Video Capture Testimony</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-no-click-spaces-within-windows-11-interface/"><u>Combatting No-Click Spaces Within Windows 11 Interface</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-what-users-find-flawed-in-windows-11/"><u>Deciphering What Users Find Flawed in Windows 11</u></a></li>
<li><a href="https://iphone-location.techidaily.com/does-itools-virtual-location-not-work-on-apple-iphone-14-plusipad-drfone-by-drfone-virtual-ios/"><u>Does iTools virtual location not work On Apple iPhone 14 Plus/iPad? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enriching-context-menu-choices-with-automatic-patch-information/"><u>Enriching Context Menu Choices with Automatic Patch Information</u></a></li>
<li><a href="https://win11.techidaily.com/error-2e-unravelled-enabling-windows-update/"><u>Error 2E Unravelled: Enabling Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tools-for-managing-users-in-command-prompt/"><u>Essential Tools for Managing Users in Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/five-methods-for-protecting-your-pc-avoiding-bitlocker/"><u>Five Methods for Protecting Your PC: Avoiding BitLocker</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-path-not-found-on-pc-systems/"><u>Fixing Path Not Found on PC Systems</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-lava-blaze-2-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Lava Blaze 2 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-overcoming-looks-like-youre-stranded-on-xbox-error/"><u>Guide to Overcoming 'Looks Like You're Stranded' On Xbox Error</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-can-we-bypass-infinix-hot-30i-frp-by-drfone-android/"><u>How Can We Bypass Infinix Hot 30i FRP?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-unidentified-devices-issue-in-win-11/"><u>How to Clear Unidentified Devices Issue in Win 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-enable-usb-debugging-on-a-locked-vivo-v29-pro-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Vivo V29 Pro Phone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-samsung-galaxy-m54-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Samsung Galaxy M54 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-prevent-google-chrome-from-creating-random-tabs/"><u>How To Prevent Google Chrome From Creating Random Tabs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-the-aw-snap-error-in-chrome/"><u>How to Stop the Aw, Snap! Error in Chrome</u></a></li>
<li><a href="https://extra-information.techidaily.com/iconic-story-arcs-in-cinemas-pantheon/"><u>Iconic Story Arcs in Cinema’s Pantheon</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-10-superior-video-capture-software-in-windows-10/"><u>In 2024, 10 Superior Video Capture Software in Windows 10</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-oppo-find-x6-profrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Oppo Find X6 ProFRP Lock</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-zte-nubia-z60-ultra-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On ZTE Nubia Z60 Ultra</u></a></li>
<li><a href="https://win11.techidaily.com/learn-to-turn-off-unsolicited-game-suggestions-for-w11/"><u>Learn to Turn Off Unsolicited Game Suggestions for W11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-github-desktop-on-windows-11-a-complete-guide/"><u>Mastering GitHub Desktop on Windows 11: A Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-writable-registry-for-hidden-themes/"><u>Mastering Windows 11' Writable Registry for Hidden Themes</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-new-world-of-windows-11-avoidance-guide-top-8/"><u>Navigating the New World of Windows 11: Avoidance Guide (Top 8)</u></a></li>
<li><a href="https://win11.techidaily.com/pathways-to-the-authorization-interface-in-windows-11/"><u>Pathways to the Authorization Interface in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-resolving-iomap64-bsod-on-windows-108-devices/"><u>Quick Tips: Resolving IOMap64 BSOD on Windows 10/8 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-google-nearby-sharing-service-in-windows/"><u>Re-Establishing Google Nearby Sharing Service in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-discovery-of-software-installs-for-windows-users/"><u>Seamless Discovery of Software Installs for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-disk-differentiation-hdd-and-ssd-recognition-on-pcs/"><u>Simplifying Disk Differentiation: HDD & SSD Recognition on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-avoid-no-permission-on-windows-file-viewing/"><u>Strategies to Avoid 'No Permission' On Windows File Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-pc-performance-deficiencies-amidst-intel-errors/"><u>Tackling PC Performance Deficiencies Amidst Intel Errors</u></a></li>
<li><a href="https://win11.techidaily.com/the-obsidian-way-to-clean-clear-notes/"><u>The Obsidian Way to Clean, Clear Notes</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-precision-crafting-win11-self-extractables/"><u>The Path to Precision: Crafting Win11 Self-Extractables</u></a></li>
<li><a href="https://win11.techidaily.com/three-methods-to-remove-microsoft-store-from-pcs/"><u>Three Methods to Remove Microsoft Store From PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-recovering-lost-run-data/"><u>Tips for Recovering Lost Run Data</u></a></li>
<li><a href="https://win11.techidaily.com/top-quick-strategies-for-black-screen-in-wins-1011/"><u>Top Quick Strategies for Black Screen in Wins 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/uninstall-simplified-top-methods-for-windows-11-users-111-chars/"><u>Uninstall Simplified: Top Methods for Windows 11 Users (111 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-pc-potential-by-clearing-windows-temp-files/"><u>Unlock Your PC Potential by Clearing Windows Temp Files</u></a></li>
</ul></div>
