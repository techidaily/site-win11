---
title: Correcting Windows' 0X0000011B Operation Errors
date: 2024-09-11T09:30:07.920Z
updated: 2024-09-12T09:30:07.920Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Windows' 0X0000011B Operation Errors
excerpt: This Article Describes Correcting Windows' 0X0000011B Operation Errors
keywords: Windows Error Code Fix,Operating System X011B,Boot Error Resolution,OS Correction,WinError Fix Guide,Troubleshoot Windows Error,BSOD Recovery Steps
thumbnail: https://thmb.techidaily.com/41df33583a82ea2d9923ca08fb1de828ddad2dc59980553349e15164e2adbb30.jpg
---

## Correcting Windows' 0X0000011B Operation Errors

 A new security patch released by Microsoft may have caused printers shared over the network to malfunction, resulting in the operation failed 0x0000011B error. The error has primarily affected Windows 10 21H1 build running computers. However, you may also experience it on Windows 11 systems.

 You can fix the error by installing the latest patch for the bug in the Windows update section. If not, here are other troubleshooting steps to fix the error and get your printer working again.

 Note that all the fixes must be applied to the host system that has the printer connected to it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115913/19272" target="_top" id="2115913">
  <img src="//a.impactradius-go.com/display-ad/19272-2115913" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115913/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Restart the Print Spooler Service

 A common troubleshooting step to fix issues with your printer is to restart the print spooler service. It is an essential service that handles the print job between your computer and printer. If the[print spooler service is not running](https://www.makeuseof.com/print-spooler-service-not-running-windows/) , you can manually start it from the Services snap-in. Here’s how to do it.

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** .
3. In the**Service** snap-in, locate the**Print Spooler** service.  
![print spooler service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/print-spooler-service-properties.jpg)
4. Next, right-click on the service and select**Properties** .  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137213/26400" target="_top" id="2137213">
  <img src="//a.impactradius-go.com/display-ad/26400-2137213" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137213/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![print spooler service startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/print-spooler-service-startup-type-automatic.jpg)
5. In the**Properties** dialog, open the**General** tab.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135397/19272" target="_top" id="2135397">
  <img src="//a.impactradius-go.com/display-ad/19272-2135397" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135397/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![restart print spooler service 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/restart-print-spooler-service-1.jpg)
6. Click the**Startup type** drop-down and set it to**Automatic** .
7. Click**Apply** and**OK** to save the changes.
8. Right-click on**Print** **Spooler** again and click**Restart** .
9. Once the Print Spooler service is up and running, create a new print job and check for any improvements.

<!-- affiliate ads begin -->
<span id="1975648">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975648%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975648/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Install All the Pending Windows Updates

![check windows 10 updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-windows-10-updates.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115931/19272" target="_top" id="2115931">
  <img src="//a.impactradius-go.com/display-ad/19272-2115931" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115931/19272" style="position:absolute;visibility:hidden;" border="0" />
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
4. Click on the**The printer that I want isn’t listed** option. If you don't see the option immediately, wait for a few seconds after clicking on the**Add a printer or scanner** option.
5. In the**Add Printer** dialog, select **Add a local printer or network printer with manual settings.**  
![add local printer network printer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/add-local-printer-network-printer.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134240/18498" target="_top" id="2134240">
  <img src="//a.impactradius-go.com/display-ad/18498-2134240" border="0" alt="https://techidaily.com" width="540" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134240/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
5. Rename the**DWORD value** as**RpcAuthnLevelPrivacyEnabled.**  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![registry editor modify rpcauthlevelprivacyenabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled.jpg)
6. Right-click on the**RpcAuthnLevelPrivacyEnabled** value and select**Modify** .
7. Type**0** in the**Value data** field and click**OK** to save the changes.  
![registry editor modify rpcauthlevelprivacyenabled 0 disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-modify-rpcauthlevelprivacyenabled-0-disabled.jpg)
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115916/19272" target="_top" id="2115916">
  <img src="//a.impactradius-go.com/display-ad/19272-2115916" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115916/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![control panel uninstall programs view installed updatges](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/control-panel-uninstall-programs-view-installed-updatges.jpg)
4. Click on**View installed updates** under**Programs and Features** . This will open the**Uninstall updates** section in the**Settings** app. Alternatively, go to **Settings > Windows Update > Update history > Uninstall updates** to access the same.  
![uninstall windows updates](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/uninstall-windows-updates.jpg)
5. Locate the problematic update (**KB5005565**) and click on**Uninstall** .

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Click**Uninstall** again to confirm the action. Wait for the update to uninstall and restart your PC to apply the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115909/19272" target="_top" id="2115909">
  <img src="//a.impactradius-go.com/display-ad/19272-2115909" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115909/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-activity-recording.techidaily.com/new-low-cost-recorders-guide-to-webcasting-wisdom/"><u>[New] Low-Cost Recorder's Guide to Webcasting Wisdom</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-comparative-analysis-of-winning-drawing-software/"><u>[Updated] Comparative Analysis of Winning Drawing Software</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-mastering-mobile-media-3-key-steps-to-stabilize-iphone-videos/"><u>[Updated] Mastering Mobile Media  3 Key Steps to Stabilize iPhone Videos</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-realme-gt-5-pro-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Realme GT 5 Pro Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/convenient-windows-11-tips-easy-rdc-entry/"><u>Convenient Windows 11 Tips: Easy RDC Entry</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-disms-potential-in-win11-system-restoration/"><u>Decoding Dism's Potential in Win11 System Restoration</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-window-11s-task-management-filtering-and-theme-transformation/"><u>Expert Tips for Window 11'S Task Management: Filtering and Theme Transformation</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-unsupported-devices-in-windows-installation/"><u>Fixing Unsupported Devices in Windows Installation</u></a></li>
<li><a href="https://win11.techidaily.com/from-batch-to-exe-windows-file-conversion/"><u>From Batch to EXE: Windows File Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/get-a-fresh-start-for-your-screens-history/"><u>Get a Fresh Start for Your Screen's History</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-windows-11s-tracking-features/"><u>How to Disable Windows 11'S Tracking Features</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-samsung-galaxy-f54-5g-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Samsung Galaxy F54 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-harnessing-hashtags-elevating-your-youtube-gaming-series/"><u>In 2024, Harnessing Hashtags  Elevating Your YouTube Gaming Series</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mememirth-your-joy-jolt-app/"><u>In 2024, MemeMirth  Your Joy Jolt App</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-perfecting-your-video-conferencing-experience-with-slack-and-filmora/"><u>In 2024, Perfecting Your Video Conferencing Experience with Slack & Filmora</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-sharing-excellence-twitch-live-to-your-facebook-circle/"><u>In 2024, Sharing Excellence  Twitch Live to Your Facebook Circle</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-stack-videos-in-your-youtube-queue/"><u>In 2024, Stack Videos in Your YouTube Queue</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-fixes-for-disabled-hard-drives-on-windows-11-systems/"><u>Innovative Fixes for Disabled Hard Drives on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/instant-access-merge-your-onedrive-and-microsoft-account/"><u>Instant Access: Merge Your OneDrive & Microsoft Account</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-to-eliminate-microsoft-store-error-0x80072efd/"><u>Master Plan to Eliminate Microsoft Store Error 0X80072EFD</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-file-timeline-windows-11s-archive-access/"><u>Mastery of File Timeline: Windows 11'S Archive Access</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-full-screen-capture-efficiency-with-these-fixes-in-windows/"><u>Maximize Full-Screen Capture Efficiency with These Fixes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-free-disk-space-in-windows-with-these-7-tips/"><u>Maximizing Free Disk Space in Windows with These 7 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-interruptnothandled-blue-screen-on-w10w11/"><u>Overcoming INTERRUPT_NOT_HANDLED Blue Screen on W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-onedrive-obstacles-a-comprehensive-approach/"><u>Overcoming OneDrive Obstacles: A Comprehensive Approach</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-upload-obstacles-with-onedrive-on-win-11/"><u>Overcoming Upload Obstacles with OneDrive on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unnoticed-windows-11-camera-use/"><u>Preventing Unnoticed Windows 11 Camera Use</u></a></li>
<li><a href="https://win11.techidaily.com/rebuild-windows-11-second-screen-fixes/"><u>Rebuild Windows 11 Second Screen Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/retrieve-past-cortana-interactions-in-windows-files/"><u>Retrieve Past Cortana Interactions in Windows Files</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-windows-11-after-password-hurdle/"><u>Reviving Windows 11 After Password Hurdle</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-repairing-windows-file-systems/"><u>Step-By-Step Guide to Repairing Windows File Systems</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-the-could-not-called-issue-with-malwarebytes/"><u>Steps to Resolve the Could Not Called Issue with Malwarebytes</u></a></li>
<li><a href="https://win11.techidaily.com/surgical-solutions-to-windows-11-login-screen-problems/"><u>Surgical Solutions to Windows 11 Login Screen Problems</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-switch-scores-language-barriers-down-with-windows-hotkeys/"><u>Swiftly Switch Scores: Language Barriers Down with Windows Hotkeys</u></a></li>
<li><a href="https://win11.techidaily.com/synching-your-way-to-digital-unity-android-plus-windows/"><u>Synching Your Way to Digital Unity: Android + Windows</u></a></li>
<li><a href="https://win11.techidaily.com/top-10-must-have-apps-to-replace-windows-11-essentials/"><u>Top 10 Must-Have Apps to Replace Windows 11 Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/unbinding-and-bypassing-resistant-print-spoolers-on-windows/"><u>Unbinding & Bypassing Resistant Print Spoolers on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/uncovering-solutions-to-temp-extraction-hurdles-in-win-oses/"><u>Uncovering Solutions to 'Temp Extraction Hurdles in Win OSes'</u></a></li>
<li><a href="https://win11.techidaily.com/unfreezing-the-vds-startup-sequence-in-windows/"><u>Unfreezing the VDS Startup Sequence in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-shadowed-interface-opening-windows-private-individuality-analyzer/"><u>Unveiling the Shadowed Interface: Opening Windows' Private Individuality Analyzer</u></a></li>
<li><a href="https://win11.techidaily.com/win10win11-restoring-write-access-to-corrupted-folders/"><u>Win10/Win11: Restoring Write Access to Corrupted Folders</u></a></li>
<li><a href="https://win11.techidaily.com/winupdates-troubleshooting-guide-for-error-x80246007/"><u>WinUpdates Troubleshooting Guide for Error X80246007</u></a></li>
</ul></div>
