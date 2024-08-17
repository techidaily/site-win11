---
title: Restoring Functionality of Disabled Print Spooler in WinOS
date: 2024-08-16T00:47:01.651Z
updated: 2024-08-17T00:47:01.651Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Functionality of Disabled Print Spooler in WinOS
excerpt: This Article Describes Restoring Functionality of Disabled Print Spooler in WinOS
keywords: Fix Windows Spooler Errors,Print Service Restoration,Spooler Repair Guide,Enable Printer Spooling,Resolve Printer Crashes,WinOS Spooler Troubleshooting,Reinstate Printer Functionality
thumbnail: https://thmb.techidaily.com/ac0768cd06937c4c888756e7c488f5bb27ac1d6ad36698509cc3575ae5a17b1c.jpg
---

## Restoring Functionality of Disabled Print Spooler in WinOS

 The Print Spooler is a little application built into your operating system. It allows you to send multiple print jobs to a queue without waiting for the initial print job to complete. If the print spooler service stops working, you’ll encounter the print spooler service is not running error on Windows.

 It is a common error associated with print jobs. However, the reasons for the error can vary. You may encounter this error when setting up a new printer, after installing an update, or upgrading your router. In any case, here are a few troubleshooting steps to help you resolve this error in Windows.

## How "The Print Spooler Service Is Not Running” Error Message Appears

 Here are the different types of print spooler errors you can encounter:

* "Windows cannot connect to the printer. The local print spooler service is not running."
* "Operation could not be completed. The print spooler service is not running."

 Whichever error you encounter, the solutions for fixing them are the same.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
## 1\. Run the Printer Troubleshooter

 The built-in Printer troubleshooter in Windows 10 and 11 lets you [find and fix printing problems](http://www.makeuseof.com/windows-11-printer-not-working/). The troubleshooter scans the system for common print problems and automatically resolves them. It can check and restart the print spooler service if stopped.

1. Press **Win + I** to open **Settings**.
2. Open the **System** tab in the left pane.
3. In the right pane, scroll down and click on **Troubleshoot**.  
![windows 11 troubleshoot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-11-troubleshoot.jpg)
4. Next, click on **Other troubleshooters.**
5. Next, click the **Run** button for the **Printer** option. The troubleshooter will scan the system and try to detect any issues.  
![windows 11 printer troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-11-printer-troubleshooter.jpg)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select the printer you want to troubleshoot and click **Next**.
7. Wait for the scan to complete and check if it finds any problem. Then, apply the recommended fixes if available.

## 2\. Restart Print Spooler Service

![print spooler service restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/print-spooler-service-restart.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->

 You can check and rerun the print spooler service in the Services snap-in to fix the print spooler service is not running error. Here's how to do it:

1. Press the **Win** key and type **services**.
2. Click on **Services** to open the snap-in.
3. Next, locate the **Print Spooler** service from the list of services.
4. Right-click on the service, select **Restart** and wait for the process to complete.
5. Give a new print job and check if the error is resolved.

## 3\. Set the Print Spooler Service Startup Type to Automatic

 By default, the print spooler service is set to start automatically when the system reboots. However, if you have set it to start manually, the service can stop working. You can change the startup type for the print spooler service using the Services snap-in.

 To change startup type for print spooler service:

1. Press **Win + R** to open **Run**.
2. Type **services.msc** and click **OK** to open the **Services** snap-in.
3. Here, locate the **Print Spooler** service.  
![print spooler service properties services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/print-spooler-service-properties-services.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Right-click on **Print Spooler** and select **Properties**.
5. In the pop-up dialog that opens, click the drop-down for **Startup type** and select **Automatic.**  
![print spooler service properties services startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/print-spooler-service-properties-services-startup-type-automatic.jpg)
6. Click **Apply** and **OK** to save the changes.
7. If it is already set to **Automatic**, then select **Disabled**. Click **Apply** and **OK** to save the changes.
8. Now open the Print Spooler service properties and set the **Startup type** to **Automatic**.
9. Click **OK** and **Apply** to save the changes.
10. Close the Services snap-in and restart your PC. Next, create a print job and check if the error printer spooler service is not running is resolved.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 4\. Clear the Print Spooler Files

 Too many pending or corrupted print jobs can trigger the print spooler service not running error. To resolve this, you can delete the print spooler files manually and restart the service. Here’s how to do it.

1. Press **Win + R** to open **Run**.
2. Type **services.msc** and click **OK**.
3. Locate and select the **Print Spooler** service in the Services snap-in.
4. Right-click on **Print Spooler** and select **Stop**.  
![print spooler service stop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/print-spooler-service-stop.jpg)
<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Next, press **Win + E** to open File Explorer.
6. Navigate to the following location. You can copy and paste the following path in the File Explorer address bar for quick navigation:  
C:\Windows\System32\spool\PRINTERS
7. Here, clear all the files inside the Printers folder. Click **Yes** if prompted by **User Account Control (UAC).** Do Not Delete the **PRINTERS** folder, but only the files inside the folder.  
![delete printer spooler service files](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/delete-printer-spooler-service-files.jpg)
8. Close File Explorer and go back to the **Services** snap-in.  
![print spooler service start](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/print-spooler-service-start.jpg)
9. Select and right-click on the **Print Spooler** service and select **Start**.

 Now create a new print job and check if the error is resolved. If not, disconnect and reconnect the printer to see if that helps.

## 5\. Check Windows Defender Firewall

 If your printer is connected to a network, it is possible that Windows Defender Firewall is preventing the connection resulting in the error. You can confirm this case by [temporarily disabling Windows Defender Firewall](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and creating a new print job.

 To disable Windows Defender Firewall:

1. Press **Win + I** to open **Settings**.
2. Open the **Privacy & security** tab in the left pane.
3. Next, click on **Windows Security.**  
![Open Windows Security Windows 11 Settings 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/Open-Windows-Security-Windows-11-Settings-1.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
4. Finally, click on **Open Windows Security.**
5. Open the **Firewall & network protection** tab in the left pane.  
![firewall and network protection windows defender](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/firewall-and-network-protection-windows-defender.jpg)
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click on your currently active network **(Public / Private).**
7. Toggle the switch under **Microsoft Defender Firewall** to turn off **Firewall**. Click **Yes** if prompted by **UAC**.  
![turn off Microsoft defender firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/turn-off-Microsoft-defender-firewall.jpg)
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. With the Firewall disabled, create a new print job, and see if it completes successfully.
9. Once done, enable the **Windows Defender Firewall** protection.

 If you use your printer frequently, disabling Windows Defender Firewall is not a feasible solution. You’ll need to investigate the issue further to allow the connection through the Firewall.

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Update Your Printer Driver

![update drive printer device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/update-drive-printer-device-manager.jpg)

 Outdated or corrupted [computer drivers](https://www.makeuseof.com/computer-drivers-what-are-they-why-should-you-update/) can cause your connected device to malfunction. Try updating your printer driver to see if that helps resolve the error. You can update the generic printer driver using the Device Manager. Here’s how to do it.

1. Press **Win + I** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open **Device Manager.**
3. In Device Manager, expand the **Print queues** section.
4. Right-click on your printer and select **Update driver.**
5. Next, select **Search automatically for drivers**. Windows will scan for a new driver update and download and install it if available.

 If no new updates are available, use your printer manufacturer’s website to download the latest driver for your printer model.

## 7\. Uninstall and Reinstall the Printer Driver

 You can also uninstall the printer driver to perform a clean install of your printer. To remove a printer, first, you need to remove the device from the Settings and then remove the driver.

 To uninstall a printer:

1. Press **Win + I** to open **Settings**.
2. In the left pane, click on **Bluetooth & devices.**  
![bluetooth and devices printers scanners](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/bluetooth-and-devices-prnters-scanners.jpg)
3. Next, click on **Printers & scanners.**
4. Now locate and click on your printer.  
![uninstall printer settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/uninstall-printer-settings.jpg)
5. Click the **Remove** button in the top right corner and click **Yes** to confirm the action.

 Once done, restart your PC. After the restart, download the latest drivers for your printer from the manufacturer's website and complete the setup.

## Fixing the "Print Spooler Service Is Not Running" Error

 Often you can fix issues with the print spooler service by restarting the service or deleting the print queue files. However, if the issue persists, investigate your system for new changes, such as Windows updates or system file corruption.

 It is a common error associated with print jobs. However, the reasons for the error can vary. You may encounter this error when setting up a new printer, after installing an update, or upgrading your router. In any case, here are a few troubleshooting steps to help you resolve this error in Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-tips.techidaily.com/new-constructing-the-ideal-home-computer-for-advanced-video-editing/"><u>[New] Constructing the Ideal Home Computer for Advanced Video Editing</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-8-strategies-livestreaming-webinars-without-costs/"><u>[New] In 2024, 8 Strategies  Livestreaming Webinars Without Costs</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-top-3-techniques-converting-pin-videos-to-mp3s/"><u>[New] Top 3 Techniques  Converting Pin Videos To MP3s</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-5-simplified-steps-for-sequential-youtube-video-viewing-free/"><u>[Updated] 2024 Approved  5 Simplified Steps for Sequential YouTube Video Viewing (Free)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-posting-a-youtube-video-via-insta-stories-a-step-by-step-guide/"><u>[Updated] 2024 Approved  Posting a YouTube Video via Insta Stories  A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-avoiding-darkness-with-lightrooms-dynamic-range-technique/"><u>[Updated] Avoiding Darkness with Lightroom’s Dynamic Range Technique</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-how-to-save-and-archive-google-voice-chats-for-2024/"><u>[Updated] How to Save and Archive Google Voice Chats for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-transform-tiktok-videos-innovative-background-updates/"><u>2024 Approved  Transform TikTok Videos  Innovative Background Updates</u></a></li>
<li><a href="https://techtrends.techidaily.com/complete-starfleet-adventure-timeline-best-way-to-experience-all-films/"><u>Complete Starfleet Adventure Timeline: Best Way to Experience All Films</u></a></li>
<li><a href="https://tech-haven.techidaily.com/corporate-challenges-five-reasons-to-question-ai-dialogue-systems/"><u>Corporate Challenges: Five Reasons to Question AI Dialogue Systems</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unallocated-vram-on-hogwarts-legacy-platform/"><u>Correcting Unallocated VRAM on Hogwarts Legacy Platform</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-unauthorized-nvidia-panel-errors-in-ws1110/"><u>Correcting Unauthorized Nvidia Panel Errors in WS11/10</u></a></li>
<li><a href="https://win11.techidaily.com/covert-strategies-to-erase-taskbars-language-bar-win11/"><u>Covert Strategies to Erase Taskbar's Language Bar, Win11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/effective-fixes-for-your-2ve-wia-device-solving-usb-compatibility-glitches-on-hp-260ci-model/"><u>Effective Fixes for Your 2Ve WIA Device - Solving USB Compatibility Glitches on HP 260Ci Model</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-user-experience-including-wordpad-shortcuts-to-11s-menu-bar/"><u>Elevating User Experience: Including WordPad Shortcuts to 11'S Menu Bar</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-to-edit-text-in-image-photo-text-editor-online-and-app/"><u>How to Edit Text in Image? [Photo Text Editor Online and App]</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-realme-11-pro-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Realme 11 Pro Phones with/without a PC</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-best-spy-watches-for-your-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Best Spy Watches For your Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/key-to-the-past-windows-11s-historical-files-retrieval/"><u>Key to the Past: Windows 11’S Historical Files Retrieval</u></a></li>
<li><a href="https://win11.techidaily.com/making-windows-alt-codes-function-again-51-characters/"><u>Making Windows ALT Codes Function Again (51 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-windows-photography-errors/"><u>Mastering the Art of Fixing Windows Photography Errors</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-pin-update-guide/"><u>Mastering Windows PIN Update Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-winservicesexe-a-comprehensive-guide/"><u>Mastering Winservices.exe: A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-digital-space-adjusting-windows-11-program-shortcuts/"><u>Mastering Your Digital Space: Adjusting Windows 11 Program Shortcuts</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-fresh-beginnings-selecting-the-best-8-soundtracks-to-start-videos/"><u>New In 2024, Fresh Beginnings Selecting the Best 8 Soundtracks to Start Videos</u></a></li>
<li><a href="https://fix-guide.techidaily.com/quick-fixes-for-why-is-my-oppo-reno-10-5g-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Oppo Reno 10 5G Black and White | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-eliminating-not-attached-usb-error-from-your-virtualbox/"><u>Quick Guide: Eliminating 'Not Attached USB Error' From Your VirtualBox</u></a></li>
<li><a href="https://win11.techidaily.com/reintroduce-missing-5ghz-connection-in-windows-11-effective-fixes-here/"><u>Reintroduce Missing 5GHz Connection in Windows 11: Effective Fixes Here</u></a></li>
<li><a href="https://win11.techidaily.com/severing-non-primary-users-in-the-windows-ecosystem/"><u>Severing Non-Primary Users in the Windows Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-windows-11-sign-in-complexity/"><u>Simplifying Windows 11 Sign-In Complexity</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-prepare-win11-in-vmware-17-player/"><u>Step-by-Step Guide to Prepare Win11 in VMware 17 Player</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-non-loading-dll-in-windows-steam/"><u>Strategies for Fixing Non-Loading Dll in Windows Steam</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-edge-of-innovation-secure-these-7-must-have-devices-for-2024/"><u>The Edge of Innovation  Secure These 7 Must-Have Devices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-tricks-for-unfreezing-right-click-menus-on-windows/"><u>Top 6 Tricks for Unfreezing Right-Click Menus on Windows</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-honor-x8b-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Honor X8b Screen | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-privacy-disabling-windows-trackers/"><u>Unlock Privacy: Disabling Windows Trackers</u></a></li>
<li><a href="https://win11.techidaily.com/whats-next-for-failed-updates-code-0x800f0845/"><u>What's Next for Failed Updates - Code 0X800f0845?</u></a></li>
<li><a href="https://win11.techidaily.com/win-11s-bluetooth-woes-try-these-9-simple-cures/"><u>Win 11'S Bluetooth Woes? Try These 9 Simple Cures</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>