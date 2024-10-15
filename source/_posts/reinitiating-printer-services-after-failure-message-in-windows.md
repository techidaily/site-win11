---
title: Reinitiating Printer Services After Failure Message in Windows
date: 2024-10-09T16:13:56.923Z
updated: 2024-10-15T21:53:41.555Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinitiating Printer Services After Failure Message in Windows
excerpt: This Article Describes Reinitiating Printer Services After Failure Message in Windows
keywords: Fixing Printer Errors,Resolving Print Failures,Clearing Winprint Error,Restarting Printer Services,Uninstall/Reinstall Printer Drivers,Eradicating Windows Printer Message,Printer Restart Guide in Windows
thumbnail: https://thmb.techidaily.com/861e642d844db4b2f3d772a017498464c5809d87279c75b02518b1d6b111bfc3.jpg
---

## Reinitiating Printer Services After Failure Message in Windows

 The Print Spooler is a little application built into your operating system. It allows you to send multiple print jobs to a queue without waiting for the initial print job to complete. If the print spooler service stops working, you’ll encounter the print spooler service is not running error on Windows.

 It is a common error associated with print jobs. However, the reasons for the error can vary. You may encounter this error when setting up a new printer, after installing an update, or upgrading your router. In any case, here are a few troubleshooting steps to help you resolve this error in Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How "The Print Spooler Service Is Not Running” Error Message Appears

 Here are the different types of print spooler errors you can encounter:

* "Windows cannot connect to the printer. The local print spooler service is not running."
* "Operation could not be completed. The print spooler service is not running."

 Whichever error you encounter, the solutions for fixing them are the same.

<!-- affiliate ads begin -->
<span id="1983446">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983446.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983446">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983446.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983446%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983446/22993" style="position:absolute;visibility:hidden;" border="0" />
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
6. Select the printer you want to troubleshoot and click **Next**.
7. Wait for the scan to complete and check if it finds any problem. Then, apply the recommended fixes if available.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136621/26400" target="_top" id="2136621">
  <img src="//a.impactradius-go.com/display-ad/26400-2136621" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136621/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Restart Print Spooler Service

![print spooler service restart](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/print-spooler-service-restart.jpg)

 You can check and rerun the print spooler service in the Services snap-in to fix the print spooler service is not running error. Here's how to do it:

1. Press the **Win** key and type **services**.
2. Click on **Services** to open the snap-in.
3. Next, locate the **Print Spooler** service from the list of services.
4. Right-click on the service, select **Restart** and wait for the process to complete.
5. Give a new print job and check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043639/7443" target="_top" id="2043639">
  <img src="//a.impactradius-go.com/display-ad/7443-2043639" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043639/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Set the Print Spooler Service Startup Type to Automatic

 By default, the print spooler service is set to start automatically when the system reboots. However, if you have set it to start manually, the service can stop working. You can change the startup type for the print spooler service using the Services snap-in.

 To change startup type for print spooler service:

1. Press **Win + R** to open **Run**.
2. Type **services.msc** and click **OK** to open the **Services** snap-in.
3. Here, locate the **Print Spooler** service.  
![print spooler service properties services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/print-spooler-service-properties-services.jpg)
4. Right-click on **Print Spooler** and select **Properties**.

<!-- affiliate ads begin -->
<span id="1912746">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1912746.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20231-1912746">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1912746.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmindmanager.sjv.io%2Fc%2F5597632%2F1912746%2F20231'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1912746/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148642/16836" target="_top" id="2148642">
  <img src="//a.impactradius-go.com/display-ad/16836-2148642" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148642/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997690/19272" target="_top" id="1997690">
  <img src="//a.impactradius-go.com/display-ad/19272-1997690" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997690/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Once done, enable the **Windows Defender Firewall** protection.

 If you use your printer frequently, disabling Windows Defender Firewall is not a feasible solution. You’ll need to investigate the issue further to allow the connection through the Firewall.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049369/7443" target="_top" id="2049369">
  <img src="//a.impactradius-go.com/display-ad/7443-2049369" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049369/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://article-posts.techidaily.com/new-discovering-the-best-free-videodownloaders-for-pinterest/"><u>[New] Discovering the Best Free Videodownloaders for Pinterest</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-integrating-apple-tunes-with-visual-media/"><u>[New] Integrating Apple Tunes with Visual Media</u></a></li>
<li><a href="https://win11.techidaily.com/1-successfully-streaming-mkv-files-on-xbox-series-xs-a-comprehensive-guide/"><u>1. Successfully Streaming MKV Files on Xbox Series X|S: A Comprehensive Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-family-bonding-through-film-the-ultimate-classics-list/"><u>2024 Approved Family Bonding Through Film The Ultimate Classics List</u></a></li>
<li><a href="https://win-amazing.techidaily.com/acer-aspire-e15-secure-the-best-windows-10-drivers-today/"><u>Acer Aspire E15 - Secure the Best Windows 10 Drivers Today</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-nubia-z50s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Nubia Z50S Pro? | Dr.fone</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-joshis-success-youtube-earnings-strategy/"><u>In 2024, Joshi's Success YouTube Earnings Strategy</u></a></li>
<li><a href="https://games-able.techidaily.com/master-mobile-gaming-performance-explore-two-fps-assessment-methods/"><u>Master Mobile Gaming Performance: Explore Two FPS Assessment Methods</u></a></li>
<li><a href="https://extra-tips.techidaily.com/superior-scriptwriting-for-soundtracks/"><u>Superior Scriptwriting for Soundtracks</u></a></li>
<li><a href="https://win11.techidaily.com/top-ranking-avcision-ultimate-guide-to-convert-dvds-to-avis-on-windows-10-and-11/"><u>Top-Ranking AVCision: Ultimate Guide to Convert DVDs to AVIs on Windows 10 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-asfmp4-conversion-tools-speeding-up-file-format-switching-with-best-practices/"><u>Ultimate ASF/MP4 Conversion Tools: Speeding Up File Format Switching with Best Practices</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-techniques-for-securely-acquiring-1440p-video-streams-from-youtube/"><u>Ultimate Techniques for Securely Acquiring 1440P Video Streams From YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/watch-on-the-go-how-to-effortlessly-save-movies-tv-episodes-and-songs-for-offline-enjoyment/"><u>Watch On the Go: How to Effortlessly Save Movies, TV Episodes & Songs for Offline Enjoyment</u></a></li>
<li><a href="https://win11.techidaily.com/wma-to-mp3-or-other-formats-the-easy-free-way-of-converting-your-music-without-spending-a-dime/"><u>WMA to MP3 or Other Formats - The Easy, FREE Way of Converting Your Music Without Spending a Dime</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/your-device-uninterrupted-revealing-the-top-7-android-adblockers/"><u>Your Device, Uninterrupted Revealing the Top 7 Android AdBlockers</u></a></li>
<li><a href="https://win11.techidaily.com/youtube-live-screen-recording-techniques-ideal-privacy-tips/"><u>YouTube Live Screen Recording Techniques - Ideal Privacy Tips</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    