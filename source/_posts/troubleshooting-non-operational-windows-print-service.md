---
title: Troubleshooting Non-Operational Windows Print Service
date: 2024-06-25T11:31:35.623Z
updated: 2024-06-26T11:31:35.623Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-resolving-common-anydesk-errors-on-windows/"><u>Mastering the Art of Resolving Common AnyDesk Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-backspace-abnormalities-in-modern-os/"><u>Overcoming Backspace Abnormalities in Modern OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-schedule-with-winning-windows-to-dos/"><u>Mastering Your Schedule with Winning Windows To-Dos</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-vmware-freeze-up-in-windows-11/"><u>Resolving VMware Freeze-Up in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enthrall-homes-embrace-the-spirit-of-yuletide/"><u>Enthrall Homes, Embrace the Spirit of Yuletide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-system-call-failed-error-on-windows-10-and-11/"><u>How to Fix the “System Call Failed” Error on Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-blue-screen-error/"><u>Strategies for Overcoming Blue Screen Error</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-address-dying-function-keys-adjusting-screen-brightness/"><u>Solutions to Address Dying Function Keys Adjusting Screen Brightness</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-image-quality-with-auto-hdr-in-w11/"><u>Maximizing Image Quality with Auto HDR in W11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-streamline-your-social-media-mastering-automatic-video-playback/"><u>In 2024, Streamline Your Social Media  Mastering Automatic Video Playback</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-best-screenshots-software-series/"><u>[New] Best Screenshots Software Series</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-totally-tune-out-mastering-the-art-of-muting-media-on-internet-platforms/"><u>New Totally Tune-Out Mastering the Art of Muting Media on Internet Platforms</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/essential-guide-recording-google-meets-securely-for-2024/"><u>Essential Guide  Recording Google Meets Securely for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-navigating-the-world-of-in-game-voice-changing-software/"><u>New Navigating the World of In-Game Voice Changing Software</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-exploring-screenflow-features-a-mac-developers-perspective/"><u>2024 Approved  Exploring ScreenFlow Features – A Mac Developer's Perspective</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-art-of-package-revelation/"><u>[Updated] The Art of Package Revelation</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-free-video-watermarking-made-easy-top-5-programs-for-2024/"><u>New Free Video Watermarking Made Easy Top 5 Programs for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-unlock-final-cut-pro-at-a-steal-explore-student-discounts-for-2024/"><u>New Unlock Final Cut Pro at a Steal Explore Student Discounts for 2024</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-in-2024-how-to-translate-videos-in-tamil-for-a-wider-reach/"><u>New In 2024, How To Translate Videos in Tamil for a Wider Reach</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>