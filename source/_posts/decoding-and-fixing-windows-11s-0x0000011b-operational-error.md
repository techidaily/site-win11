---
title: Decoding and Fixing Windows 11'S 0X0000011B Operational Error
date: 2024-08-28T00:54:54.012Z
updated: 2024-08-29T00:54:54.012Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Decoding and Fixing Windows 11'S 0X0000011B Operational Error
excerpt: This Article Describes Decoding and Fixing Windows 11'S 0X0000011B Operational Error
keywords: Windows 11 Error Code X0000011B,Resolve X0000011B in Win11,Fixing XP11 Operational Error,Addressing Win11 Error 11B,Overcoming Win11 Error 11B,Troubleshoot Win11 11B Code,Remedy Windows 11 X0000011B
thumbnail: https://thmb.techidaily.com/4bb09ddf21259f8aa35372dd3bddaab5a52e4c2f70a7e62b027db40747b04fa4.jpeg
---

## Decoding and Fixing Windows 11'S 0X0000011B Operational Error

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

 If it’s a widespread issue, you’ll likely receive a bug fix via Windows update. So, begin with checking if a new Windows update is available. These are often small hotfixes released to fix widespread issues.

To check and install Windows updates:

1. Press**Win + I** to open the**Settings** app.
2. In the left pane, open the**Windows Update** tab. Open**Update & Security** on Windows 10.
3. Click on**Check for updates** . Windows will look for pending updates and list them here.
4. Click on**Download & install** to install the updates.
5. Once installed, restart your PC and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## 3\. Install the Printer Manually via the Local Port

 A little complicated, yet a working solution to fix the operation failed error 0x0000011B is to[add your printer manually to Windows](https://www.makeuseof.com/windows-11-add-wired-wireless-printer/) for the local port. Here’s how to do it.

1. Press**Win + I** to open**Settings** .
2. Next, click on**Devices** and then open the**Printers & scanners** tab.
3. Next, click on**Add a printer or scanner** . Windows will scan for available printers.  
![the printer that i want isnt listed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-printer-that-i-want-isnt-listed.jpg)
4. Click on the**The printer that I want isn’t listed** option. If you don't see the option immediately, wait for a few seconds after clicking on the**Add a printer or scanner** option.
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
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
5. Rename the**DWORD value** as**RpcAuthnLevelPrivacyEnabled.**  
![registry editor modify rpcauthlevelprivacyenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled.jpg)
6. Right-click on the**RpcAuthnLevelPrivacyEnabled** value and select**Modify** .
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Type**0** in the**Value data** field and click**OK** to save the changes.  
![registry editor modify rpcauthlevelprivacyenabled 0 disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled-0-disabled.jpg)
8. Close**Registry Editor** and restart your PC to apply the changes.
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
9. After the restart, try to use your shared printer and check if the error is resolved.

## 5\. Uninstall Recently Installed Updates

 Assuming the issue is triggered after you installed a Windows security update, uninstalling the update should undo the changes and fix the error. You can uninstall some individual updates from the Windows updates section. This feature is specifically available to undo issues that may have occurred after installing an update.

 Note that the concerned update (KB5005565) was released to fix a print spooler vulnerability on Windows OS. Uninstalling the update can leave your computer vulnerable again. Use this as a last resort if none of the above methods helped resolve the error.

To uninstall Windows updates:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**  
![control panel uninstall programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs.jpg)
3. Next, click on**Programs** .  
![control panel uninstall programs view installed updatges](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs-view-installed-updatges.jpg)
4. Click on**View installed updates** under**Programs and Features** . This will open the**Uninstall updates** section in the**Settings** app. Alternatively, go to **Settings > Windows Update > Update history > Uninstall updates** to access the same.  
<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![uninstall windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-windows-updates.jpg)
5. Locate the problematic update (**KB5005565**) and click on**Uninstall** .
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
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


