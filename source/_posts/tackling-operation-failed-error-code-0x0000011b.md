---
title: "Tackling Operation Failed Error: Code 0X0000011B"
date: 2024-08-16T00:01:06.403Z
updated: 2024-08-17T00:01:06.403Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tackling Operation Failed Error: Code 0X0000011B"
excerpt: "This Article Describes Tackling Operation Failed Error: Code 0X0000011B"
keywords: OperationsErrorCodeX0011B,Code0x0000011BFailure,OperationFailedX11BError,ErrorCode0X11BOperating,X0000011BOperationFail,0X0000011BErrorTackle,AddressingCode0X11BFailure
thumbnail: https://thmb.techidaily.com/a6017269d4c04c5e1e1b5dd34c08e1f92a0a41c1ec409bdbe7a0807e99cdc6f4.jpg
---

## Tackling Operation Failed Error: Code 0X0000011B

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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Click on the**The printer that I want isn’t listed** option. If you don't see the option immediately, wait for a few seconds after clicking on the**Add a printer or scanner** option.
5. In the**Add Printer** dialog, select **Add a local printer or network printer with manual settings.**  
![add local printer network printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/add-local-printer-network-printer.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Under**Choose a printer por** t, select**Create a new port.**  
![create new port local port add printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/create-new-port-local-port-add-printer.jpg)
2. Click the drop-down for**Type of port** and select**Local Port.**
3. Click**Next** .  
![enter port name printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enter-port-name-printer.jpg)
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Type your network printer file path and the network printer name in the**Enter a port name** field. You can use the username or the IP address for the computer name and then the printer name you want to share.
5. Click**OK** to save the printer.

1. Next, select your printer manufacturer from the list to install the printer driver.
2. Next, select the correct printer driver under the**Printers** column.
3. Click**Next** .
4. Choose a name for your printer driver and click**Install** .
5. Click**Next** and wait for the installation to complete.

 Your newly added printer will now appear under**Device and Printer** in**Control Panel** and the**Settings** app. Give a new print job to see if the error is resolved.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Rename the**DWORD value** as**RpcAuthnLevelPrivacyEnabled.**  
![registry editor modify rpcauthlevelprivacyenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled.jpg)
6. Right-click on the**RpcAuthnLevelPrivacyEnabled** value and select**Modify** .
7. Type**0** in the**Value data** field and click**OK** to save the changes.  
![registry editor modify rpcauthlevelprivacyenabled 0 disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled-0-disabled.jpg)
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Close**Registry Editor** and restart your PC to apply the changes.
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
![uninstall windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-windows-updates.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Locate the problematic update (**KB5005565**) and click on**Uninstall** .
6. Click**Uninstall** again to confirm the action. Wait for the update to uninstall and restart your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://fox-access.techidaily.com/new-first-moments-that-foster-interest-in-audios/"><u>[New] First Moments that Foster Interest in Audios</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-garmin-virb-ultra-30-an-insider-look-at-an-adventure-staple/"><u>[New] Garmin VIRB Ultra 30  An Insider Look at an Adventure Staple</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-nanorecording-app-critique-with-backup-choices-for-2024/"><u>[Updated] NanoRecording App Critique with Backup Choices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-the-system-information-tool-on-windows/"><u>10 Ways to Open the System Information Tool on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/14-unveiling-windows-11-post-update-feature-list/"><u>14 Unveiling Windows 11: Post-Update Feature List</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-slide-swivel-and-shift-mastering-the-rotation-ritual-for-stunning-photos-on-insta-sites/"><u>2024 Approved  Slide, Swivel and Shift  Mastering the Rotation Ritual for Stunning Photos on Insta Sites</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-sound-in-obs-studio-resolving-no-audio-on-win-11/"><u>Amplify Sound in OBS Studio - Resolving No Audio on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-dxgierror-post-device-disconnect/"><u>Avoidance of DXGI_Error Post Device Disconnect</u></a></li>
<li><a href="https://win11.techidaily.com/clashing-cybersecurity-the-case-against-multiple-antiviruses-on-windows/"><u>Clashing Cybersecurity: The Case Against Multiple Antiviruses on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clear-communication-how-to-test-microphone-on-windows-pre-call/"><u>Clear Communication: How to Test Microphone on Windows Pre-Call</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-data-metering-settings-for-wi-fi-in-windows-11/"><u>Configuring Data Metering Settings for Wi-Fi in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/critical-guide-restoring-lost-logins-in-windows-11/"><u>Critical Guide: Restoring Lost Logins in Windows 11</u></a></li>
<li><a href="https://network-issues.techidaily.com/curbing-computer-glare-anomalies-successful/"><u>Curbing Computer Glare Anomalies Successful</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-gaming-power-drain-from-wm/"><u>Cutting Down Gaming Power Drain From WM</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-techniques-pin-free-windows-projecting/"><u>Cutting Edge Techniques: PIN-Free Windows Projecting</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-explore-tab-glitches-in-modern-os/"><u>Disabling Explore Tab Glitches in Modern OS</u></a></li>
<li><a href="https://win11.techidaily.com/dxgidll-lost-files-restore-with-smart-windows-11-fixes/"><u>Dxgi.dll Lost Files? Restore with Smart Windows 11 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-photo-management-winning-windows-applications/"><u>Efficient Photo Management: Winning Windows Applications</u></a></li>
<li><a href="https://win11.techidaily.com/essential-knowledge-setting-windows-filter-keys/"><u>Essential Knowledge: Setting Windows Filter Keys</u></a></li>
<li><a href="https://win11.techidaily.com/expert-techniques-for-fast-utorrent-downloads-on-windows/"><u>Expert Techniques for Fast uTorrent Downloads on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-bluescreenview-a-step-by-step-tutorial/"><u>Exploring BlueScreenView - A Step-By-Step Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/handling-camera-allocation-conflict-on-windows-os/"><u>Handling Camera Allocation Conflict on Windows OS</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-pictures-files-from-nokia-xr21-by-fonelab-android-recover-pictures/"><u>How To  Restore Missing Pictures Files from Nokia XR21.</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-dxgierrordeviceremoved-error-in-windows-11-and-11/"><u>How to Fix the DXGI_ERROR_DEVICE_REMOVED Error in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-infinitely-stop-microsoft-defender-in-windows/"><u>How to Infinitely Stop Microsoft Defender in Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-xiaomi-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Xiaomi</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-xs-apples-new-iphone-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone XS, Apples New iPhone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-apples-calendar-in-a-win1011-setup/"><u>Leveraging Apple's Calendar in a Win10/11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-nvidia-settings-failure-to-save/"><u>Overcoming NVIDIA Settings Failure to Save</u></a></li>
<li><a href="https://win11.techidaily.com/paving-the-way-for-progress-updating-windows-drivers/"><u>Paving the Way for Progress: Updating Windows Drivers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/prime-color-balancer-suite-for-2024/"><u>Prime Color Balancer Suite for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-slow-windows-edge-w10-w11/"><u>Quick Fixes for Slow Windows Edge (W10, W11)</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-fixing-unsupported-devices-warning/"><u>Quick Guide: Fixing Unsupported Devices Warning</u></a></li>
<li><a href="https://win11.techidaily.com/reimagining-display-technology-an-in-depth-exploration-of-windows-11s-hdr/"><u>Reimagining Display Technology: An In-Depth Exploration of Windows 11'S HDR</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-pause-bring-back-lost-sounds-to-tech-gadgets/"><u>Resetting Pause: Bring Back Lost Sounds to Tech Gadgets</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-compatibility-of-brightness-controls-via-fn-key-win-11/"><u>Restoring Compatibility of Brightness Controls via Fn Key Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-icon-diminution-issues-on-windows-11/"><u>Reverse Icon Diminution Issues on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-printer-force-delete-on-windows-11/"><u>Step-by-Step Printer Force Delete on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-alter-mouse-trail-and-size-on-win11/"><u>Step-by-Step: Alter Mouse Trail & Size on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-exception-breaking-point-on-microsoft-os/"><u>Steps to Eliminate Exception Breaking Point on Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-inactive-windows-lock-screen-timer/"><u>Troubleshooting Inactive Windows Lock Screen Timer</u></a></li>
<li><a href="https://win11.techidaily.com/unclogging-windows-chrome-problems/"><u>Unclogging Windows Chrome Problems</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-potential-with-our-top-5-budget-drivers-for-pcs/"><u>Unleash Potential with Our Top 5 Budget Drivers for PCs</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/venturing-to-israel-top-9-essentials-and-phrasebook-basics/"><u>Venturing to Israel: Top 9 Essentials and Phrasebook Basics</u></a></li>
</ul></div>
