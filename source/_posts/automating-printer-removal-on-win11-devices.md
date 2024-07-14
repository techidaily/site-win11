---
title: Automating Printer Removal on Win11 Devices
date: 2024-07-13T11:23:28.024Z
updated: 2024-07-14T11:23:28.024Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Automating Printer Removal on Win11 Devices
excerpt: This Article Describes Automating Printer Removal on Win11 Devices
keywords: Win11 Printer Auto-Remove,Win11 Device Printing Automation,Remote Win11 Printer Disconnect,Win11 Printer Management Tools,Efficient Win11 Printer Unhook,Windows 11 Print Shutdown,Win11 Printer Self-Removal Feature
thumbnail: https://thmb.techidaily.com/a6603b4c8e64882a75258ea91034b33184d3edc319264524a7b728bfe67ef7f7.jpg
---

## Automating Printer Removal on Win11 Devices

 Often, you will need to remove and reconnect your printer for troubleshooting purposes. Also, removing old and unused devices helps you keep your connected device list organized in Windows 11 and 10\.

 You can remove any connected printer from the Settings panel. If that does not work, you can use the Command Prompt and other ways to remove the printer. Here, we show you the many ways to delete a printer on Windows computers.

## 1\. How to Remove a Printer From Windows via Settings

 You can easily [add or remove printers](https://www.makeuseof.com/tag/printer-setup-windows-10/) from the Settings app. Here’s how to do it:

1. Press **Win + I** to open **Settings**.
2. Open the **Bluetooth & devices** tab in the left pane.  
![Printers and Scanners Settings in Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/printers-and-scanners-Windows-settings.jpg)
3. Scroll down and click on **Printers & scanners**. This will list all the printers connected to your computer.
4. Click on the printer device that you want to remove.  
![Remove Printer Option in Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/remove-printer-settings.jpg)
5. Click the **Remove** button in the top right corner and click **Yes** to confirm the action.

 If you encounter an error, stop the Print Spooler service in the Services snap-in and try again!

## How to Stop the Print Spooler Service

 If Windows fails to remove the printer with an error, try to stop the Print Spooler service and remove the printer. Print Spooler is an essential printer service that communicates the print job between your PC and the printer. However, it can sometimes interfere and prevent you from uninstalling the printer.

 To stop the print spooler service:

1. Press **Win + R** to open **Run**.
2. Typ**e services.msc** and click **OK** to open the **Services snap-in.**
3. In the Services window, locate the **Print Spooler service.**
4. Right-click on **Print Spooler** and select **Stop**.  
![Print Spooler Service Stop Option in Services MMC on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/print-spooler-service-stop-1.jpg)
5. Minimize the **Services** window.
6. Now open the **Windows Settings pane**l, go to **Bluetooth & devices > Scanners and Printer**, and try to remove your printer device.
7. Once the printer is removed, go back to the **Services** window.  
![Print Spooler Service Start Option in Services MMC on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/print-spooler-service-start-1.jpg)
8. Right-click on **Print Spooler** and select **Start**.

[Restarting the Printer Spooler service](https://www.makeuseof.com/windows-restart-print-spooler-service/) is necessary. If disabled, you may encounter the [printer spooler service is not running](https://www.makeuseof.com/print-spooler-service-not-running-windows/) error on your PC.

## 2\. Remove the Printer Software to Delete the Printer

![Remove HP Printer Software in Windows 11 Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/hp-printer-remove-software.jpg)

 If the deleted printer option still appears, you can remove the printer driver associated with the device to uninstall it completely. You can remove the driver using the Apps & feature tab in Windows 10 and 11\.

 To remove the printer drivers:

1. Press **Win + I** to open **Settings**.
2. Click on the **Apps** tab in the left pane. The app list may take a few seconds to populate, so wait till all the apps are listed.
3. Under the **App list**, you can scroll through or search for the printer driver.
4. When you find the printer driver, click the **three-dots menu.**
5. Select **Uninstall** and then click on **Uninstall** again to confirm the action.
6. Wait for the driver to uninstall, then look for any other drive or software associated with the printer and remove them too.
7. Once uninstalled, restart your PC.

## 3\. Remove the Printer Using the Control Panel

 You can use the classic Control Panel to manage your printers. Removing the printer from the Control Panel should work if the printer wasn’t removed correctly during the uninstallation process.

 To remove the printer using the Control Panel:

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the Control Panel. You can also search for the app using the Windows search bar.
3. In the Control Panel, go to **Hardware and Sound.**  
![Windows 11 Control Panel Showing the Hardware and Sound Option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/control-panel-hardware-and-sound.jpg)
4. Next, click on **Devices and Printers.**
5. Under the **Printers** section, locate and select the printer device you want to remove.  
![Remove Printer Option in Windows 11 Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/remove-printer-ccontrol-panel.jpg)
6. Right-click on the printer and select **Remove Device.**
7. Click **Yes** to confirm the action.

## 4\. Remove the Printer Using Windows' Print Server Properties

 Sometimes, removing the printer device does not remove the drivers completely and can [cause your printer to stop working](https://www.makeuseof.com/windows-11-printer-not-working/). In such a situation, you can use the Print Server Properties dialog to remove the installed printer drivers.

 To uninstall the printer drivers:

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK**.
3. In the Control Panel window, go to **Hardware and Sound > Devices and Printers.**  
![Hardware and Sound Option in Windows 11 Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/control-panel-hardware-and-sound-1.jpg)
4. Select any available printer and click on **Print server properties.**  
![Print Server Properties Option in Windows 11 Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/print-server-properties.jpg)
5. Open the **Drivers** tab in the **Print Server Properties** dialog.
6. Under **Installed printer drivers**, select the printer driver to uninstall and click **Remove**.  
![Print Server Properties Dialog in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/remove-printer-driver-prin-server-properties.jpg)
7. Next, select the **Remove driver and driver package** option.
8. Click **OK** to confirm the action and remove the driver.
9. Restart your PC to complete the driver removal process.

## 5\. Uninstall the Printer Using the Device Manager

 Device Manager lets you manage all your peripheral and internal devices connected to your system. You can [use the device manager to troubleshoot your Windows system](https://www.makeuseof.com/how-to-use-device-manager-windows-10/), update the driver, add a new device, and remove connected devices.

 To remove the printer using Device Manager:

1. Press **Win + X** to open the WinX menu.
2. Click on **Device Manager** from the context menu.
3. In Device Manager, click on **View** and select **Show hidden devices.**  
![Device Manager App With Show Hidden Devices Selected in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/device-manager-show-hidden-devices.jpg)
4. Next, expand the **Printers** section to view your printer.
5. Right-click on the printer and select **Uninstall device.**  
![Uninstall Printer Option Selected in Device Manager on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/uninstall-printer-device-manager.jpg)
6. Select the **Delete the driver software for this device** option and click **Uninstall**.
7. If the **Printers** section is unavailable, expand the **Print queues** section and repeat the steps to remove the printer.
8. Close Device Manager and restart your computer to complete the uninstall process.

## 6\. How to Uninstall a Printer Using the Command Prompt

![Command Prompt with Remove Printer Command in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/remove-printer-command-prompt.jpg)

 If you prefer the Command Prompt over the traditional UI, you can delete the printer from your PC using the dl command.

 To uninstall the printer use the Command Prompt:

1. Press Win and type **cmd** in the **Windows search bar.**
2. Right-click on the **Command Prompt** option and select **Run as administrator.**
3. In the Command Prompt window, type the following command to view all the installed printers on your PC:  
`wmic printer get name`
4. To delete a printer, type the following command:  
`printui.exe /dl /n "Your_Printer_Name"`
5. In the above command, replace **Your\_Printer\_Name** with the name of your printer.
6. Hit **Enter** to execute the command.

## 7\. Remove the Printer Drive Using Print Management

 Print Management is a Windows utility controlling printers, drivers, ports, and servers. You can use the tool to remove printer drivers from your Windows computer. The Print Management utility is not available in the Home edition of the Windows operating system.

 To remove printer driver using Print Management:

1. Press **Win + R** to open **Run**.
2. Type **printmanagement**.**msc** and click **OK** to open **Print Management**.  
![Open Print Management Using Run Dialog in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/open-print-management.jpg)
3. In the left pane, expand the **Print Servers** section,
4. Click on your **Local Printer** server name to expand it.
5. Next, select **Printers** to view all the installed printers.  
![Delete a Printer Using the Print Management Snap-in On Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/delete-printer-print-management-windows.jpg)
6. In the right pane, select and right-click on the printer you want to remove.
7. Select **Delete** and click **Yes** to confirm the action.

## 8\. Delete a Printer Driver with PowerShell

![PowerShell Console Running the Remove Printer Command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-printer-powershell.jpg)

 Alternatively, you can delete the printer driver package using PowerShell as an alternative to Print Management. This is also a quicker way to remove multiple printers in your Windows computer.

 To remove a printer driver using PowerShell:

1. Press the **Win** key and type **powershell**.
2. Right-click on **Windows PowerShell** and select **Run as administrator**.
3. In the PowerShell dialog, type the following command and press Enter to view the list of printers installed on your computer:  
`Get-PrinterDriver | Format-List Name`
4. Once you have the list of printers installed, type the following command to remove the printer you want to delete:  
`Remove-PrinterDriver -Name "Printer-Name"`
5. In the above command, replace Printer-Name with the printer name you want to remove.

## The Many Ways to Remove a Printer in Windows 10 and 11

 You can easily remove a printer in Windows using the Settings panel. However, if the deleted printer keeps reappearing, you can use the print server properties, Command Prompt, or delete the printer software to remove the printer altogether.

 You can remove any connected printer from the Settings panel. If that does not work, you can use the Command Prompt and other ways to remove the printer. Here, we show you the many ways to delete a printer on Windows computers.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/batch-operations-brilliance-shutting-down-windows-instances/"><u>Batch Operations Brilliance: Shutting Down Windows Instances</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-navigating-snapchats-video-slowdown-feature/"><u>[New] Navigating Snapchat's Video Slowdown Feature</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-apple-iphone-14-drfone-by-drfone-virtual-ios/"><u>3 Ways to Change Location on Facebook Marketplace for Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boost-speed-identifying-your-gpu-on-windows-11-os/"><u>Boost Speed: Identifying Your GPU on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/bolstering-user-engagement-with-context-menu-update-options/"><u>Bolstering User Engagement with Context Menu Update Options</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-10-and-11-climate-choices/"><u>Best Windows 10 & 11 Climate Choices</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-choreographed-vocal-harmony-on-tiktok-for-2024/"><u>[Updated] Choreographed Vocal Harmony on TikTok for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-mastering-screen-recordings-on-windows-10-systems/"><u>[New] 2024 Approved  Mastering Screen Recordings on Windows 10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-barrier-5-apps-to-increase-volume-on-windows-past-100/"><u>Breaking the Barrier: 5 Apps to Increase Volume on Windows Past 100%%</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-activation-error-0x8007251d-fixes-and-tips/"><u>Breaking Down Windows Activation Error 0X8007251D: Fixes and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-forgotten-island-xbox-hiccup/"><u>Breaking Free From the Forgotten Island Xbox Hiccup</u></a></li>
<li><a href="https://win11.techidaily.com/black-and-white-brilliance-a-guide-for-the-shadows/"><u>Black & White Brilliance: A Guide for the Shadows</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-realme-narzo-n55-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Realme Narzo N55 Devices</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/1716069978023-new-2024-approved-pc-and-macs-best-screenshot-apps-ranked/"><u>[New] 2024 Approved  PC and Mac's Best Screenshot Apps Ranked!</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-to-overcome-steam-sync-error-on-windows/"><u>Best Practices to Overcome Steam Sync Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-11-taskbar-efficiency/"><u>Boosting Windows 11 Taskbar Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-glitches-enabling-latest-emojis-on-windows-11/"><u>Avoiding Glitches: Enabling Latest Emojis on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-key-steps-to-tackle-windows-blue-screen/"><u>Breaking Down Key Steps to Tackle Windows Blue Screen</u></a></li>
<li><a href="https://win11.techidaily.com/beating-back-corrupt-files-error-code-0x80070570-solutions-for-windows-11/"><u>Beating Back Corrupt Files Error Code 0X80070570: Solutions for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-display-with-w11s-auto-hdr-feature/"><u>Boost Your Display with W11's Auto HDR Feature</u></a></li>
<li><a href="https://win11.techidaily.com/boosted-app-opening-top-techniques-for-windows-11/"><u>Boosted App Opening: Top Techniques for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-sevenzeronine-in-windows/"><u>Addressing Error SevenZeroNine in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-save-location-blunders-on-windows-devices/"><u>Avoiding Save Location Blunders on Windows Devices</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-transforming-viewers-into-revenue-youtube-money-secrets-unveiled/"><u>[New] In 2024, Transforming Viewers Into Revenue  YouTube Money Secrets Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-protected-windowsapps-folder-boundary/"><u>Avoidance of Protected WindowsApps Folder Boundary</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expert-tips-finding-the-best-text-design-resources/"><u>2024 Approved  Expert Tips  Finding the Best Text Design Resources</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failure-glitches-a-guide-for-fixing-windows-office-issues/"><u>Addressing Failure Glitches: A Guide for Fixing Windows Office Issues</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-mastering-audio-mute-on-tiktok-quick-and-easy-techniques/"><u>Updated In 2024, Mastering Audio Mute on TikTok Quick and Easy Techniques</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/instant-social-boost-top-15-trustworthy-iosandroid-followers-tools-for-2024/"><u>Instant Social Boost  Top 15 Trustworthy iOS/Android Followers Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-powershell-with-admin-privileges-on-windows-11/"><u>Accessing PowerShell with Admin Privileges on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-critical-roblox-programming-mistakes/"><u>Addressing Critical Roblox Programming Mistakes</u></a></li>
<li><a href="https://win11.techidaily.com/best-value-car-performance-software-for-windows-top-5-revealed/"><u>Best Value Car Performance Software for Windows - Top 5 Revealed</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-10-essential-vlog-editing-hacks-for-novice-creators/"><u>[Updated] 2024 Approved  10 Essential Vlog Editing Hacks for Novice Creators</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-odds-tackling-installer-errors-in-win11-successfully/"><u>Beating the Odds: Tackling Installer Errors in Win11 Successfully</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-the-ultimate-guide-to-thriving-in-google-meet-chats/"><u>[New] 2024 Approved  The Ultimate Guide to Thriving in Google Meet Chats</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-media-stream-efficiency-taming-vlc-lags/"><u>Boosting Media Stream Efficiency: Taming VLC Lags</u></a></li>
<li><a href="https://win11.techidaily.com/breakdown-of-windows-error-message-30005s-complexity/"><u>Breakdown of Windows Error Message 30005'S Complexity</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-rapid-clicks-turn-off-mouse-accel-in-win-11/"><u>Avoiding Rapid Clicks: Turn Off Mouse Accel in Win 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-oppo-f25-pro-5g-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Oppo F25 Pro 5G? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/airplane-mode-heres-your-guide-for-win11/"><u>Airplane Mode? Here's Your Guide for Win11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-slow-down-or-speed-up-top-video-editing-software-with-speed-adjustment/"><u>2024 Approved Slow Down or Speed Up Top Video Editing Software with Speed Adjustment</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-a-damaged-video-file-of-find-x7-using-video-repair-utility-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair a Damaged video file of Find X7 using Video Repair Utility on Mac?</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-digital-vault-for-internet-streams-a-recording-blueprint-for-2024/"><u>[Updated] Digital Vault for Internet Streams  A Recording Blueprint for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/beat-windows-11-blues-top-11-pitfalls-and-remedies/"><u>Beat Windows 11 Blues - Top 11 Pitfalls & Remedies</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-exepe-file-formats/"><u>Breaking Down Windows EXE/PE File Formats</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-from-viewers-to-earnings-youtube-earning-basics/"><u>[New] From Viewers to Earnings  YouTube Earning Basics</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-a-look-at-four-game-changing-paint-additions/"><u>Breaking Barriers: A Look at Four Game-Changing Paint Additions</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-windows-11-on-outdated-devices/"><u>Breaking Barriers: Windows 11 on Outdated Devices</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-blueprint-to-windows-11-installation/"><u>Beginner's Blueprint to Windows 11 Installation</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-classic-gameplay-seamlessly-adding-achievements-using-retroarch/"><u>Boosting Classic Gameplay - Seamlessly Adding Achievements Using Retroarch</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-nubia-z50-ultra-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Nubia Z50 Ultra FRP Android 10/11/12/13</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-chromebook-video-editing-software-top-10-online-options/"><u>In 2024, Chromebook Video Editing Software Top 10 Online Options</u></a></li>
<li><a href="https://network-issues.techidaily.com/advanced-display-settings-lacking-in-windows-11/"><u>Advanced Display Settings Lacking in Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-swift-skim-windows-file-compilation/"><u>2024 Approved  Swift Skim Windows File Compilation</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-iphone-hacks-for-minimalist-video-presentation/"><u>[Updated] IPhone Hacks for Minimalist Video Presentation</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>