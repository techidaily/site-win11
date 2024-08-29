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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-sj6-mastery-showdown-sjcam-vs-xiaomis-yi-pro-4k/"><u>[New] 2024 Approved  SJ6 Mastery Showdown  SJCam Vs. Xiaomi's Yi Pro 4K</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-streaming-console-adventures-pc-setup-and-methods/"><u>[New] In 2024, Streaming Console Adventures  PC Setup and Methods</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-navigating-new-realms-todays-vr-tomorrows-trials/"><u>[New] Navigating New Realms  Today's VR, Tomorrow's Trials</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-what-is-360-video-for-2024/"><u>[New] What Is 360° Video for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-streamline-your-playtime-with-nvidia/"><u>[Updated] 2024 Approved  Streamline Your Playtime with NVIDIA</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-excellence-in-motion-best-4k-cameras-unveiled/"><u>[Updated] Excellence in Motion  Best 4K Cameras Unveiled</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-chromes-best-deals-on-screen-recorder-free-tools/"><u>[Updated] In 2024, Chrome's Best Deals on Screen Recorder Free Tools</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-selecting-the-top-cameras-for-smooth-twitch-broadcasts/"><u>[Updated] In 2024, Selecting the Top Cameras for Smooth Twitch Broadcasts</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-total-clarification-googles-podcast-application-simplified/"><u>2024 Approved  Total Clarification  Google's Podcast Application Simplified</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-motorola-g54-5g-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Motorola G54 5G PC | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-samsung-galaxy-s24-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/bienvenue-en-france-mots-francais-du-reconnaitre/"><u>Bienvenue en France: Mots Français Du Reconnaître</u></a></li>
<li><a href="https://buynow-info.techidaily.com/comprehensive-apple-homepod-mini-evaluation-sound-quality-and-intelligent-assistant-features/"><u>Comprehensive Apple HomePod Mini Evaluation: Sound Quality & Intelligent Assistant Features</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-file-system-interactions-with-new-commands/"><u>Customizing File System Interactions with New Commands</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/deciding-factors-in-finding-the-perfect-tv/"><u>Deciding Factors in Finding the Perfect TV</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-hidden-windows-programs/"><u>Enabling Hidden Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-three-column-widgets-on-windows-11-os/"><u>Enabling Three-Column Widgets on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-conquering-windows-11-display-preferences/"><u>Expert Guide: Conquering Windows 11 Display Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-character-map-not-working-on-windows/"><u>How to Fix the Character Map Not Working on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-restore-file-explorers-classic-ribbon-interface-in-windows-11/"><u>How to Restore File Explorer’s Classic Ribbon Interface in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-honor-v-purse-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Honor V Purse to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/increase-proficiency-with-these-6-expertly-designed-trackers/"><u>Increase Proficiency with These 6 Expertly Designed Trackers</u></a></li>
<li><a href="https://win11.techidaily.com/introducing-top-4-windows-programs-for-webp-image-viewer/"><u>Introducing Top 4 Windows Programs for WebP Image Viewer</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-data-transfer-success-on-modern-windows-os/"><u>Mastering Data Transfer Success on Modern Windows OS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/online-screenshots-and-screen-recorders-guide/"><u>Online Screenshots & Screen Recorders Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-external-display-not-recognized-problem-in-windows/"><u>Overcoming External Display Not Recognized Problem in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-permissions-obstacles-for-os-installation/"><u>Overcoming Permissions Obstacles for OS Installation</u></a></li>
<li><a href="https://win11.techidaily.com/proven-methods-to-stop-display-glitches-on-windows-1011/"><u>Proven Methods to Stop Display Glitches on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-1011-store-error-code-0x800704cf/"><u>Rectifying Windows 10/11 Store Error: Code 0X800704CF</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-installer-rights-troubles-on-modern-oses/"><u>Remedying Installer Rights Troubles on Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-recovering-a-disabled-delete-functionality/"><u>Solutions for Recovering a Disabled Delete Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/stop-active-use-of-cortana-in-windows-11/"><u>Stop Active Use of Cortana in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-illusion-of-choice-confronting-microphone-and-camera-shackles/"><u>The Illusion of Choice: Confronting Microphone and Camera Shackles</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-samsung-galaxy-f14-5g-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Samsung Galaxy F14 5G Device</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-taming-troublesome-updates/"><u>The Ultimate Guide to Taming Troublesome Updates</u></a></li>
<li><a href="https://win11.techidaily.com/title-customize-icon-spacing-on-modern-and-classic-windows-oses/"><u>Title: Customize Icon Spacing on Modern & Classic Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-windows-side-by-side-conflict/"><u>Troubleshooting: Resolving 'Windows Side-by-Side Conflict'</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-correcting-a-missing-msvcr110dll/"><u>Understanding & Correcting a Missing Msvcr110.dll</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-cure-for-hyper-v-error-code-0x8009030e/"><u>Unlocking Windows: Cure for Hyper-V Error Code 0X8009030E</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-next-gen-phone-integration/"><u>Unveiling Windows 11'S Next-Gen Phone Integration</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-update-impact-on-linux-subsystem/"><u>Windows 11 Update: Impact on Linux Subsystem</u></a></li>
<li><a href="https://win11.techidaily.com/windows-glitches-end-self-scrolling-panels-here/"><u>Windows Glitches? End Self-Scrolling Panels Here</u></a></li>
<li><a href="https://win11.techidaily.com/windows-graphics-scheduler-control-explained/"><u>Windows Graphics Scheduler Control Explained</u></a></li>
</ul></div>
