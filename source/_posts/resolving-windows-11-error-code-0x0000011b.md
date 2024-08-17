---
title: "Resolving Windows 11 Error Code: 0X0000011B"
date: 2024-08-16T00:28:37.719Z
updated: 2024-08-17T00:28:37.719Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving Windows 11 Error Code: 0X0000011B"
excerpt: "This Article Describes Resolving Windows 11 Error Code: 0X0000011B"
keywords: Fix Win11 Error 0X0000011B,Uninstall Windows 11 Error 11,Troubleshoot Win11 Error X11B,Resolve Win11 Error Code 011B,Correct Win11 Error 11BX,Addressing Windows Error 0X011B,Overcoming Win11 Error 011B
thumbnail: https://thmb.techidaily.com/640d7e8ae71734e741d90b60c7027d369bb73ea6dc95cbde06bedc68934e5552.jpg
---

## Resolving Windows 11 Error Code: 0X0000011B

 A new security patch released by Microsoft may have caused printers shared over the network to malfunction, resulting in the operation failed 0x0000011B error. The error has primarily affected Windows 10 21H1 build running computers. However, you may also experience it on Windows 11 systems.

 You can fix the error by installing the latest patch for the bug in the Windows update section. If not, here are other troubleshooting steps to fix the error and get your printer working again.

 Note that all the fixes must be applied to the host system that has the printer connected to it.

## 1\. Restart the Print Spooler Service

 A common troubleshooting step to fix issues with your printer is to restart the print spooler service. It is an essential service that handles the print job between your computer and printer. If the [print spooler service is not running](https://www.makeuseof.com/print-spooler-service-not-running-windows/) , you can manually start it from the Services snap-in. Here’s how to do it.

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

 If it’s a widespread issue, you’ll likely receive a bug fix via Windows update. So, begin with checking if a new Windows update is available. These are often small hotfixes released to fix widespread issues.

To check and install Windows updates:

1. Press**Win + I** to open the**Settings** app.
2. In the left pane, open the**Windows Update** tab. Open**Update & Security** on Windows 10.
3. Click on**Check for updates** . Windows will look for pending updates and list them here.
4. Click on**Download & install** to install the updates.
5. Once installed, restart your PC and check for any improvements.

## 3\. Install the Printer Manually via the Local Port

 A little complicated, yet a working solution to fix the operation failed error 0x0000011B is to [add your printer manually to Windows](https://www.makeuseof.com/windows-11-add-wired-wireless-printer/) for the local port. Here’s how to do it.

1. Press**Win + I** to open**Settings** .
2. Next, click on**Devices** and then open the**Printers & scanners** tab.
3. Next, click on**Add a printer or scanner** . Windows will scan for available printers.  
![the printer that i want isnt listed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-printer-that-i-want-isnt-listed.jpg)
4. Click on the**The printer that I want isn’t listed** option. If you don't see the option immediately, wait for a few seconds after clicking on the**Add a printer or scanner** option.
5. In the**Add Printer** dialog, select **Add a local printer or network printer with manual settings.**  
![add local printer network printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/add-local-printer-network-printer.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->

1. Under**Choose a printer por** t, select**Create a new port.**  
![create new port local port add printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-new-port-local-port-add-printer.jpg)
2. Click the drop-down for**Type of port** and select**Local Port.**
3. Click**Next** .  
![enter port name printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enter-port-name-printer.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
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

 Note that modifying your Windows Registry involves risk. We recommend you [back up your Windows registry](http://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a system restore](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps below.

Next, follow these steps to disable CVE-2021-1678 mitigation:

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open Registry Editor.
3. In Registry Editor, navigate to the following location. Copy and paste the registry path for quick navigation:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Print`
4. Next, right-click on**Print > New > DWORD (32-bit) Value.**  
![create new dword 32 bit value registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-new-dword-32-bit-value-registry-editor.jpg)
5. Rename the**DWORD value** as**RpcAuthnLevelPrivacyEnabled.**  
![registry editor modify rpcauthlevelprivacyenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
6. Right-click on the**RpcAuthnLevelPrivacyEnabled** value and select**Modify** .
7. Type**0** in the**Value data** field and click**OK** to save the changes.  
![registry editor modify rpcauthlevelprivacyenabled 0 disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled-0-disabled.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Close**Registry Editor** and restart your PC to apply the changes.
9. After the restart, try to use your shared printer and check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Uninstall Recently Installed Updates

 Assuming the issue is triggered after you installed a Windows security update, uninstalling the update should undo the changes and fix the error. You can uninstall some individual updates from the Windows updates section. This feature is specifically available to undo issues that may have occurred after installing an update.

 Note that the concerned update (KB5005565) was released to fix a print spooler vulnerability on Windows OS. Uninstalling the update can leave your computer vulnerable again. Use this as a last resort if none of the above methods helped resolve the error.

To uninstall Windows updates:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**  
![control panel uninstall programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs.jpg)
<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
3. Next, click on**Programs** .  
![control panel uninstall programs view installed updatges](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs-view-installed-updatges.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
4. Click on**View installed updates** under**Programs and Features** . This will open the**Uninstall updates** section in the**Settings** app. Alternatively, go to **Settings > Windows Update > Update history > Uninstall updates** to access the same.  
![uninstall windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-windows-updates.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-peepsnapper-screen-grab-examination-and-replacements/"><u>[New] 2024 Approved  PeepSnapper Screen Grab Examination & Replacements</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-achieving-professional-audio-in-home-recording-studios/"><u>[New] Achieving Professional Audio in Home Recording Studios</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-the-hidden-pathway-to-logging-in-depth-whatsapp-chats/"><u>[Updated] 2024 Approved  The Hidden Pathway to Logging In-Depth WhatsApp Chats</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-apeak-recording-assessment-top-software-showdown/"><u>[Updated] Apeak Recording Assessment  Top Software Showdown</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-leveraging-snap-camera-for-better-online-interaction-on-google-meet/"><u>[Updated] In 2024, Leveraging Snap Camera for Better Online Interaction on Google Meet</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-the-finest-6-video-snaggers-for-mac-users-now/"><u>[Updated] The Finest 6 Video Snaggers for Mac Users Now</u></a></li>
<li><a href="https://win11.techidaily.com/4-futuristic-windows-features-outgrowing-cortana/"><u>4 Futuristic Windows Features Outgrowing Cortana</u></a></li>
<li><a href="https://win11.techidaily.com/a-buyers-blueprint-essential-steps-for-your-win-pc-purchase/"><u>A Buyer’s Blueprint: Essential Steps for Your Win PC Purchase</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-look-at-triggering-system-restore-in-windows-11/"><u>A Detailed Look at Triggering System Restore in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-type-speed-cutting-down-lag-on-windows-11/"><u>Accelerating Type Speed: Cutting Down Lag on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/acceleration-at-fingertips-3-ways-to-enhance-mouse-double-click-speed/"><u>Acceleration at Fingertips: 3 Ways to Enhance Mouse Double-Click Speed</u></a></li>
<li><a href="https://win11.techidaily.com/1719347210677-access-display-settings-right-click-on-the-desktop-and-select-display-settings/"><u>Access Display Settings: Right-Click on the Desktop and Select Display Settings.</u></a></li>
<li><a href="https://win11.techidaily.com/activating-local-administrator-tools-in-windows-1110-home/"><u>Activating Local Administrator Tools in Windows 11/10 Home</u></a></li>
<li><a href="https://win11.techidaily.com/adapt-window-placement-for-windows-os/"><u>Adapt Window Placement for Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/adapting-to-new-horizons-migrating-apps-for-a-windows-11-laptop/"><u>Adapting to New Horizons: Migrating Apps for a Windows 11 Laptop</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-command-prompt-authorization-problems/"><u>Addressing Command Prompt Authorization Problems</u></a></li>
<li><a href="https://win11.techidaily.com/aligning-chromes-timeline-error-on-windows-machines/"><u>Aligning Chrome's Timeline Error on Windows Machines</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-clutter-mastering-the-deletion-of-drive-partitions-in-win-os/"><u>Avoiding Clutter: Mastering the Deletion of Drive Partitions in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-unending-enter-password-interruptions-in-windows/"><u>Avoiding Unending Enter Password Interruptions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/black-out-bliss-with-microsofts-basic-brush/"><u>Black-Out Bliss with Microsoft's Basic Brush</u></a></li>
<li><a href="https://win11.techidaily.com/blueprint-for-efficiently-updating-windows-solo/"><u>Blueprint for Efficiently Updating Windows Solo</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-game-loading-times-for-epic-universe/"><u>Boosting Game Loading Times for Epic Universe</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-pc-speed-post-media-downloads-on-w11/"><u>Boosting PC Speed Post Media Downloads on W11</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-windows-11-on-outdated-devices/"><u>Breaking Barriers: Windows 11 on Outdated Devices</u></a></li>
<li><a href="https://win11.techidaily.com/1719366214502-efficient-support-paths-for-common-windows-concerns/"><u>Efficient Support Paths for Common Windows Concerns!</u></a></li>
<li><a href="https://techidaily.com/full-guide-to-hard-reset-your-infinix-smart-8-plus-drfone-by-drfone-reset-android-reset-android/"><u>Full Guide to Hard Reset Your Infinix Smart 8 Plus | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-gt-5-pro-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Realme GT 5 Pro Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-advanced-procedures-for-livestreaming-sporting-spectacles/"><u>In 2024, Advanced Procedures for Livestreaming Sporting Spectacles</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-7-without-swiping-up-6-ways-drfone-by-drfone-ios/"><u>In 2024, How To Unlock Apple iPhone 7 Without Swiping Up? 6 Ways | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-maintain-peaceful-posting-dismiss-ig-recommendations/"><u>In 2024, Maintain Peaceful Posting  Dismiss IG Recommendations</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-minuscule-cinematic-design/"><u>In 2024, Minuscule Cinematic Design</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721464522471-iphone-home-button-troubles-here-are-5-fast-solutions/"><u>IPhone Home Button Troubles? Here Are 5 Fast Solutions</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-achieving-cinematic-color-in-final-cut-pro/"><u>New Achieving Cinematic Color in Final Cut Pro</u></a></li>
<li><a href="https://review-topics.techidaily.com/online-signatures-for-xltm-documents-by-ldigisigner-sign-a-excel-sign-a-excel/"><u>Online signatures for .xltm documents</u></a></li>
<li><a href="https://win11.techidaily.com/1719228805701-quick-jot-down-techniques-in-windows-11-no-apps/"><u>Quick Jot-Down Techniques in Windows 11, No Apps!</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tips-and-tricks-to-tell-if-your-iphone-11-pro-max-is-unlocked-by-drfone-ios/"><u>Tips And Tricks To Tell if Your iPhone 11 Pro Max Is Unlocked</u></a></li>
<li><a href="https://activate-lock.techidaily.com/top-7-icloud-activation-bypass-tools-for-your-apple-iphone-14-plus-by-drfone-ios/"><u>Top 7 iCloud Activation Bypass Tools For your Apple iPhone 14 Plus</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-the-ultimate-guide-to-removing-tiktok-watermarks-for-free/"><u>Updated The Ultimate Guide to Removing TikTok Watermarks for Free</u></a></li>
</ul></div>
