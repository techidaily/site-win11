---
title: Troubleshooting Non-Operational Windows Print Service
date: 2024-07-13T10:17:54.948Z
updated: 2024-07-14T10:17:54.948Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Non-Operational Windows Print Service
excerpt: This Article Describes Troubleshooting Non-Operational Windows Print Service
keywords: Fix Windows Printers,Restart Print Service,Enable Print Protocol,Resolve Printer Errors,Unblock Printing,Activate Windows Prints,Troubleshoot Print Issue
thumbnail: https://thmb.techidaily.com/38800d1bcd9a0db51e74a8d6e9d259f45c0a81d4cc5911dccf11c067ddd27a33.jpg
---

## Troubleshooting Non-Operational Windows Print Service

 The Print Spooler is a little application built into your operating system. It allows you to send multiple print jobs to a queue without waiting for the initial print job to complete. If the print spooler service stops working, you’ll encounter the print spooler service is not running error on Windows.

 It is a common error associated with print jobs. However, the reasons for the error can vary. You may encounter this error when setting up a new printer, after installing an update, or upgrading your router. In any case, here are a few troubleshooting steps to help you resolve this error in Windows.

## How "The Print Spooler Service Is Not Running” Error Message Appears

 Here are the different types of print spooler errors you can encounter:

* "Windows cannot connect to the printer. The local print spooler service is not running."
* "Operation could not be completed. The print spooler service is not running."

 Whichever error you encounter, the solutions for fixing them are the same.

## 1\. Run the Printer Troubleshooter

 The built-in Printer troubleshooter in Windows 10 and 11 lets you [find and fix printing problems](http://www.makeuseof.com/windows-11-printer-not-working/). The troubleshooter scans the system for common print problems and automatically resolves them. It can check and restart the print spooler service if stopped.

1. Press **Win + I** to open **Settings**.
2. Open the **System** tab in the left pane.
3. In the right pane, scroll down and click on **Troubleshoot**.  
![windows 11 troubleshoot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-11-troubleshoot.jpg)
4. Next, click on **Other troubleshooters.**
5. Next, click the **Run** button for the **Printer** option. The troubleshooter will scan the system and try to detect any issues.  
![windows 11 printer troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/windows-11-printer-troubleshooter.jpg)
6. Select the printer you want to troubleshoot and click **Next**.
7. Wait for the scan to complete and check if it finds any problem. Then, apply the recommended fixes if available.

## 2\. Restart Print Spooler Service

![print spooler service restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/print-spooler-service-restart.jpg)

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
4. Right-click on **Print Spooler** and select **Properties**.
5. In the pop-up dialog that opens, click the drop-down for **Startup type** and select **Automatic.**  
![print spooler service properties services startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/print-spooler-service-properties-services-startup-type-automatic.jpg)
6. Click **Apply** and **OK** to save the changes.
7. If it is already set to **Automatic**, then select **Disabled**. Click **Apply** and **OK** to save the changes.
8. Now open the Print Spooler service properties and set the **Startup type** to **Automatic**.
9. Click **OK** and **Apply** to save the changes.
10. Close the Services snap-in and restart your PC. Next, create a print job and check if the error printer spooler service is not running is resolved.

## 4\. Clear the Print Spooler Files

 Too many pending or corrupted print jobs can trigger the print spooler service not running error. To resolve this, you can delete the print spooler files manually and restart the service. Here’s how to do it.

1. Press **Win + R** to open **Run**.
2. Type **services.msc** and click **OK**.
3. Locate and select the **Print Spooler** service in the Services snap-in.
4. Right-click on **Print Spooler** and select **Stop**.  
![print spooler service stop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/print-spooler-service-stop.jpg)
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
4. Finally, click on **Open Windows Security.**
5. Open the **Firewall & network protection** tab in the left pane.  
![firewall and network protection windows defender](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/firewall-and-network-protection-windows-defender.jpg)
6. Click on your currently active network **(Public / Private).**
7. Toggle the switch under **Microsoft Defender Firewall** to turn off **Firewall**. Click **Yes** if prompted by **UAC**.  
![turn off Microsoft defender firewall](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/turn-off-Microsoft-defender-firewall.jpg)
8. With the Firewall disabled, create a new print job, and see if it completes successfully.
9. Once done, enable the **Windows Defender Firewall** protection.

 If you use your printer frequently, disabling Windows Defender Firewall is not a feasible solution. You’ll need to investigate the issue further to allow the connection through the Firewall.

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-error-0x8007007e/"><u>Troubleshooting Windows Error 0X8007007E</u></a></li>
<li><a href="https://win11.techidaily.com/stop-windows-update-pushes-instantly-with-these-methods/"><u>Stop Windows Update Pushes Instantly With These Methods</u></a></li>
<li><a href="https://extra-skills.techidaily.com/inspirational-movies-for-momentum-and-self-belief-for-2024/"><u>Inspirational Movies for Momentum and Self-Belief for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-discovering-top-foodie-influencers-on-tiktok/"><u>[Updated] Discovering Top Foodie Influencers on TikTok</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-the-security-questions-of-your-apple-id-from-your-iphone-12-mini-by-drfone-ios/"><u>In 2024, How To Reset the Security Questions of Your Apple ID From Your iPhone 12 mini</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-steps-to-activate-windows-media-player/"><u>Simplified Steps to Activate Windows Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-low-power-modes/"><u>Understanding Windows' Low-Power Modes</u></a></li>
<li><a href="https://win11.techidaily.com/breakthrough-restore-microsofts-pc-manager-on-win/"><u>Breakthrough: Restore Microsoft's PC Manager on Win</u></a></li>
<li><a href="https://win11.techidaily.com/simple-fixes-resetting-windows-setup-post-reboot/"><u>Simple Fixes: Resetting Windows Setup Post-Reboot</u></a></li>
<li><a href="https://win11.techidaily.com/changing-nat-types-for-better-connection-performance-in-win1110/"><u>Changing NAT Types for Better Connection Performance in Win11/10</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-in-depth-analysis-complete-revamp-of-facetune-app/"><u>2024 Approved  In-Depth Analysis  Complete Revamp of Facetune App</u></a></li>
<li><a href="https://extra-hints.techidaily.com/speeding-up-periscope-live-broadcasting-tips/"><u>Speeding Up Periscope Live Broadcasting Tips</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-premium-audio-alerts-excellent-sites-compilation/"><u>2024 Approved  Premium Audio Alerts  Excellent Sites Compilation</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-dialer-on-windows-11/"><u>Accessing Dialer on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-changing-picture-preview-size/"><u>Windows 11: Changing Picture Preview Size</u></a></li>
<li><a href="https://extra-tips.techidaily.com/revolutionize-your-streaming-experience-top-18-webcam-tools-explored/"><u>Revolutionize Your Streaming Experience  Top 18 Webcam Tools Explored</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-harness-the-power-of-engagement-in-instagram-videos/"><u>2024 Approved  Harness the Power of Engagement in Instagram Videos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-resolve-windows-upgrade-failures-and-errors/"><u>How to Resolve Windows Upgrade Failures and Errors</u></a></li>
<li><a href="https://win11.techidaily.com/windows-revenue-strategies-for-microsofts-profits/"><u>Windows Revenue Strategies for Microsoft's Profits</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-storytelling-revolution-free-cross-platform-social-sensations/"><u>[Updated] In 2024, Storytelling Revolution  FREE, Cross-Platform Social Sensations</u></a></li>
<li><a href="https://win11.techidaily.com/clear-windows-11-cache-cutting-out-the-clutter/"><u>Clear Windows 11 Cache: Cutting Out the Clutter</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-essential-moves-for-every-aspiring-tiktoker/"><u>[Updated] In 2024, Essential Moves for Every Aspiring TikToker</u></a></li>
<li><a href="https://win11.techidaily.com/5-steps-to-clear-windows-not-supported-error-hurdle/"><u>5 Steps to Clear Windows' 'Not Supported' Error Hurdle</u></a></li>
<li><a href="https://win11.techidaily.com/quick-remedies-for-unsynchronized-google-drive-on-pc/"><u>Quick Remedies for Unsynchronized Google Drive on PC</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-maximizing-lenovo-experience-through-effective-recording/"><u>[Updated] Maximizing Lenovo Experience Through Effective Recording</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-fcpx-pro-tips-how-to-achieve-rock-solid-video-stability-for-2024/"><u>Updated FCPX Pro Tips How to Achieve Rock-Solid Video Stability for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tapping-into-windows-settings-for-cpu-states/"><u>Tapping Into Windows Settings for CPU States</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-8-solutions-to-fix-find-my-friends-location-not-available-on-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 8 Solutions to Fix Find My Friends Location Not Available On Vivo Y200e 5G | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-unlocking-composite-power-with-blend-mode-knowledge/"><u>[New] Unlocking Composite Power with Blend Mode Knowledge</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-visuals-adding-value-with-3-strategic-video-descriptions-for-2024/"><u>Instagram Visuals  Adding Value with 3 Strategic Video Descriptions for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/digital-canvas-on-windows-desktops-tips-and-tricks/"><u>Digital Canvas on Windows Desktops: Tips & Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/stepping-up-to-full-operating-system-windows-for-steam-deck/"><u>Stepping Up to Full Operating System: Windows for Steam Deck</u></a></li>
<li><a href="https://win11.techidaily.com/secure-uniqueness-5-ways-to-avoid-local-name-clashes-on-windows/"><u>Secure Uniqueness: 5 Ways to Avoid Local Name Clashes on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/disentangling-same-account-issues-on-a-device/"><u>Disentangling Same-Account Issues on a Device</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11-error-code-0x0000011b/"><u>Resolving Windows 11 Error Code: 0X0000011B</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/the-ultimate-guide-to-calculating-screen-aspect-ratios-for-2024/"><u>The Ultimate Guide to Calculating Screen Aspect Ratios for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-windows-11-a-guide-to-taskbar-search-functionality/"><u>Dive Into Windows 11: A Guide to Taskbar Search Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-your-desktops-aesthetic-essential-theme-tips-for-win11/"><u>Transforming Your Desktop's Aesthetic: Essential Theme Tips for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-new-home-for-onedrive-folder-in-windows/"><u>Configuring New Home for OneDrive Folder in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/easing-frustrations-with-a-fix-to-non-working-pen-devices-in-windows/"><u>Easing Frustrations with a Fix to Non-Working Pen Devices in Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-explore-the-10-most-influential-makeup-personalities-online/"><u>[New] 2024 Approved  Explore the 10 Most Influential Makeup Personalities Online</u></a></li>
</ul></div>
