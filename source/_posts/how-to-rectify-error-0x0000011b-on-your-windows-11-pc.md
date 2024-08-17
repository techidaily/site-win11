---
title: How to Rectify Error 0X0000011B on Your Windows 11 PC
date: 2024-08-16T00:45:14.140Z
updated: 2024-08-17T00:45:14.140Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Rectify Error 0X0000011B on Your Windows 11 PC
excerpt: This Article Describes How to Rectify Error 0X0000011B on Your Windows 11 PC
keywords: Fixing Windows Error X0000011B,Resolve WinError 0X11B,Remedy WinX11 Error 0X11B,Correct 0X0000011B PC Issue,Fixing Windows X Error,Troubleshoot 0X11B Error WinPC,Solve Windows 11 Error X0000011B
thumbnail: https://thmb.techidaily.com/08b59308ea1479863a214168a367629cf0b1393331c870e52c284f342d82b8ac.jpeg
---

## How to Rectify Error 0X0000011B on Your Windows 11 PC

 A new security patch released by Microsoft may have caused printers shared over the network to malfunction, resulting in the operation failed 0x0000011B error. The error has primarily affected Windows 10 21H1 build running computers. However, you may also experience it on Windows 11 systems.

 You can fix the error by installing the latest patch for the bug in the Windows update section. If not, here are other troubleshooting steps to fix the error and get your printer working again.

 Note that all the fixes must be applied to the host system that has the printer connected to it.

## 1\. Restart the Print Spooler Service

 A common troubleshooting step to fix issues with your printer is to restart the print spooler service. It is an essential service that handles the print job between your computer and printer. If the[print spooler service is not running](https://www.makeuseof.com/print-spooler-service-not-running-windows/) , you can manually start it from the Services snap-in. Here’s how to do it.

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** .
3. In the**Service** snap-in, locate the**Print Spooler** service.  
![print spooler service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/print-spooler-service-properties.jpg)
4. Next, right-click on the service and select**Properties** .  
![print spooler service startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/print-spooler-service-startup-type-automatic.jpg)
5. In the**Properties** dialog, open the**General** tab.  
![restart print spooler service 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-print-spooler-service-1.jpg)
6. Click the**Startup type** drop-down and set it to**Automatic** .
7. Click**Apply** and**OK** to save the changes.
8. Right-click on**Print** **Spooler** again and click**Restart** .
9. Once the Print Spooler service is up and running, create a new print job and check for any improvements.

## 2\. Install All the Pending Windows Updates

![check windows 10 updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-windows-10-updates.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->

 If it’s a widespread issue, you’ll likely receive a bug fix via Windows update. So, begin with checking if a new Windows update is available. These are often small hotfixes released to fix widespread issues.

To check and install Windows updates:

1. Press**Win + I** to open the**Settings** app.
2. In the left pane, open the**Windows Update** tab. Open**Update & Security** on Windows 10.
3. Click on**Check for updates** . Windows will look for pending updates and list them here.
4. Click on**Download & install** to install the updates.
5. Once installed, restart your PC and check for any improvements.

## 3\. Install the Printer Manually via the Local Port

 A little complicated, yet a working solution to fix the operation failed error 0x0000011B is to[add your printer manually to Windows](https://www.makeuseof.com/windows-11-add-wired-wireless-printer/) for the local port. Here’s how to do it.

1. Press**Win + I** to open**Settings** .
2. Next, click on**Devices** and then open the**Printers & scanners** tab.
3. Next, click on**Add a printer or scanner** . Windows will scan for available printers.  
![the printer that i want isnt listed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-printer-that-i-want-isnt-listed.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
4. Click on the**The printer that I want isn’t listed** option. If you don't see the option immediately, wait for a few seconds after clicking on the**Add a printer or scanner** option.
5. In the**Add Printer** dialog, select **Add a local printer or network printer with manual settings.**  
![add local printer network printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/add-local-printer-network-printer.jpg)

1. Under**Choose a printer por** t, select**Create a new port.**  
![create new port local port add printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-new-port-local-port-add-printer.jpg)
2. Click the drop-down for**Type of port** and select**Local Port.**
3. Click**Next** .  
![enter port name printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enter-port-name-printer.jpg)
4. Type your network printer file path and the network printer name in the**Enter a port name** field. You can use the username or the IP address for the computer name and then the printer name you want to share.
5. Click**OK** to save the printer.

1. Next, select your printer manufacturer from the list to install the printer driver.
2. Next, select the correct printer driver under the**Printers** column.
3. Click**Next** .
4. Choose a name for your printer driver and click**Install** .
5. Click**Next** and wait for the installation to complete.

 Your newly added printer will now appear under**Device and Printer** in**Control Panel** and the**Settings** app. Give a new print job to see if the error is resolved.

## 4\. Disable the CVE-2021-1678 Registry Fix

 The problematic security update included a security fix to patch the Printer Spooler Spoofing vulnerability dubbed CVE-2021-1678\. However, the new changes seem to have triggered the 0x0000011B operation failed error.

 To fix the error without uninstalling the security update, you’ll need to create a new registry entry to disable the feature. Here’s how to do it.

 Note that modifying your Windows Registry involves risk. We recommend you[back up your Windows registry](http://www.makeuseof.com/tag/backup-restore-windows-registry/) and[create a system restore](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

Next, follow these steps to disable CVE-2021-1678 mitigation:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor.
3. In Registry Editor, navigate to the following location. Copy and paste the registry path for quick navigation:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Print`
4. Next, right-click on**Print > New > DWORD (32-bit) Value.**  
![create new dword 32 bit value registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-new-dword-32-bit-value-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
5. Rename the**DWORD value** as**RpcAuthnLevelPrivacyEnabled.**  
![registry editor modify rpcauthlevelprivacyenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled.jpg)
6. Right-click on the**RpcAuthnLevelPrivacyEnabled** value and select**Modify** .
7. Type**0** in the**Value data** field and click**OK** to save the changes.  
![registry editor modify rpcauthlevelprivacyenabled 0 disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled-0-disabled.jpg)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Close**Registry Editor** and restart your PC to apply the changes.
9. After the restart, try to use your shared printer and check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Uninstall Recently Installed Updates

 Assuming the issue is triggered after you installed a Windows security update, uninstalling the update should undo the changes and fix the error. You can uninstall some individual updates from the Windows updates section. This feature is specifically available to undo issues that may have occurred after installing an update.

 Note that the concerned update (KB5005565) was released to fix a print spooler vulnerability on Windows OS. Uninstalling the update can leave your computer vulnerable again. Use this as a last resort if none of the above methods helped resolve the error.

To uninstall Windows updates:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**  
![control panel uninstall programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs.jpg)
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Next, click on**Programs** .  
![control panel uninstall programs view installed updatges](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs-view-installed-updatges.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
4. Click on**View installed updates** under**Programs and Features** . This will open the**Uninstall updates** section in the**Settings** app. Alternatively, go to **Settings > Windows Update > Update history > Uninstall updates** to access the same.  
![uninstall windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-windows-updates.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
5. Locate the problematic update (**KB5005565**) and click on**Uninstall** .
6. Click**Uninstall** again to confirm the action. Wait for the update to uninstall and restart your PC to apply the changes.

## Fixing the 0x0000011b Printing Error on Windows

 This error has largely affected Windows 10 computers. To fix the issue, try to install all the pending Windows updates that may include a hotfix. You can also add the printer manually to a local port or edit the registry entry to disable the problematic setting. If nothing works, uninstalling the security update may be the last resort. However, doing so can put your computer at risk of print spooler spoofing vulnerability.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-boosting-income-through-effective-video-marketing-for-2024/"><u>[New] Boosting Income Through Effective Video Marketing for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-cutting-edge-stabilizing-gadgets-for-youtube-videography/"><u>[New] Cutting Edge Stabilizing Gadgets for YouTube Videography</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-from-social-media-giant-to-premium-format-mastering-insta-to-mp4-2-ways/"><u>[New] In 2024, From Social Media Giant to Premium Format  Mastering Insta-to-MP4 2 Ways</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-vlc-screencasting-live-feed-webcam-integration-for-2024/"><u>[New] VLC  Screencasting Live Feed – Webcam Integration for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-captivate-your-market-the-blueprint-for-effective-instagram-video-plans/"><u>[Updated] 2024 Approved  Captivate Your Market  The Blueprint for Effective Instagram Video Plans</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-cinematic-capture-top-picks-from-video-experts/"><u>[Updated] 2024 Approved  Cinematic Capture  Top Picks From Video Experts</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-the-windows-network-connections-tool/"><u>10 Ways to Open the Windows Network Connections Tool</u></a></li>
<li><a href="https://apple-account.techidaily.com/3-ways-of-how-to-get-someones-apple-id-off-iphone-13-mini-without-password-by-drfone-ios/"><u>3 Ways of How to Get Someones Apple ID Off iPhone 13 mini without Password</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-open-the-startup-repair-tool-on-windows/"><u>5 Ways to Open the Startup Repair Tool on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-use-windows-11-more-efficiently/"><u>7 Ways to Use Windows 11 More Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-keyboard-shortcuts-not-working-in-windows/"><u>9 Ways to Fix Keyboard Shortcuts Not Working in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-adding-virtual-gaming-archives-into-playnite/"><u>A Comprehensive Guide to Adding Virtual Gaming Archives Into Playnite</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-guide-to-understanding-group-policies-windows-via-3-views/"><u>A Detailed Guide to Understanding Group Policies (Windows) via 3 Views</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-collaboration-the-5-top-windows-fs-software-picks/"><u>Accelerated Collaboration: The 5 Top Windows FS Software Picks</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-11-spatial-audio-setup-guide/"><u>Activating Windows 11: Spatial Audio Setup Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-no-supported-issue-during-os-setup-and-update/"><u>Addressing 'No Supported' Issue During OS Setup and Update</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-not-sufficient-usb-issue-in-windows/"><u>Addressing “Not Sufficient USB” Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/altering-system-index-for-optimization/"><u>Altering System Index for Optimization</u></a></li>
<li><a href="https://win11.techidaily.com/automate-app-colors-with-the-help-of-windows-11-features/"><u>Automate App Colors with the Help of Windows 11 Features</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-mismatch-of-speaker-assignment-due-to-another-app/"><u>Avoiding Mismatch of Speaker Assignment Due to Another App</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-windows-notepad-system-disruptions/"><u>Avoiding Windows Notepad System Disruptions</u></a></li>
<li><a href="https://win11.techidaily.com/banish-stubborn-epic-launcher-guide-for-win-11-users/"><u>Banish Stubborn Epic Launcher: Guide for Win 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/bitlocker-less-protection-4-effective-methods-for-win-users/"><u>BitLocker-Less Protection: 4 Effective Methods for Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/blueprint-for-dominance-in-windows-appbrowser-arena/"><u>Blueprint for Dominance in Windows' App/Browser Arena</u></a></li>
<li><a href="https://win11.techidaily.com/bootable-backup-a-self-reliant-approach/"><u>Bootable Backup: A Self-Reliant Approach</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-application-launch-descriptors/"><u>Breaking Down Application Launch Descriptors</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-realme-narzo-60-5g-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Realme Narzo 60 5G to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-what-you-want-to-know-about-two-factor-authentication-for-icloud-from-your-apple-iphone-se-2022-by-drfone-ios/"><u>In 2024, What You Want To Know About Two-Factor Authentication for iCloud From your Apple iPhone SE (2022)</u></a></li>
<li><a href="https://win11.techidaily.com/1719254323833-overcome-shift-key-stickiness-in-windows-os/"><u>Overcome Shift Key Stickiness in Windows OS.</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Oppo Find X6 Pro? | Dr.fone</u></a></li>
<li><a href="https://os-tips.techidaily.com/safe-laptop-restart-techniques-for-windows-and-mac-users-no-data-lost/"><u>Safe Laptop Restart Techniques for Windows and Mac Users: No Data Lost</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-your-laptop-microphone-issues-a-comprehensive-guide/"><u>Troubleshooting Your Laptop Microphone Issues - A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/1719339382074-unlock-frozen-shift-on-windows-pcs/"><u>Unlock Frozen Shift on Windows PCs.</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/unlocking-potential-with-facebooks-live-a-comprehensive-guide-for-creators-for-2024/"><u>Unlocking Potential with Facebook’s LIVE  A Comprehensive Guide for Creators for 2024</u></a></li>
</ul></div>
