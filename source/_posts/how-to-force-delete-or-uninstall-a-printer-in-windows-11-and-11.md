---
title: How to Force Delete or Uninstall a Printer in Windows 11 & 11
date: 2024-07-13T10:53:27.461Z
updated: 2024-07-14T10:53:27.461Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Force Delete or Uninstall a Printer in Windows 11 & 11
excerpt: This Article Describes How to Force Delete or Uninstall a Printer in Windows 11 & 11
keywords: Windows Printer Removal Guide,Uninstalling Windows Print Devices,Forced Printer Uninstallation (Windows),Remove Windows 11 Printers Quickly,Windows 11 Printer Deletion Steps,Force Delete Windows 11 Printers,Uninstall Windows 11 Print Drivers
thumbnail: https://thmb.techidaily.com/9878ff62b08356ff78ffb4d4ce5fd0c27ab1ffdc4dd530f388b0fa3845feed6f.jpg
---

## How to Force Delete or Uninstall a Printer in Windows 11 & 11

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/comparing-windows-n-variants-whats-worth-it/"><u>Comparing Windows N Variants: What's Worth It?</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-mouse-properties-on-windows-11/"><u>10 Ways to Open Mouse Properties on Windows 11</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-highlighting-youtubes-creme-de-la-creme-makeup-influencers/"><u>[New] In 2024, Highlighting YouTube's Crème De La Crème Makeup Influencers</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-computer-written-record-with-ms-audits/"><u>Streamlining Your Computer’ Written Record with MS Audits</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-win-ratio-valorant-optimization-guide/"><u>Enhancing Win Ratio: Valorant Optimization Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/expertly-selected-8-filters-for-virtual-showcases-for-2024/"><u>Expertly Selected 8 Filters for Virtual Showcases for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-back-lost-photos-from-htc-u23-by-fonelab-android-recover-photos/"><u>How to get back lost photos from HTC U23.</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-devices-in-the-dormant-system-state/"><u>Controlling Devices in the Dormant System State</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-best-showcasing-book-trailers/"><u>[New] Best Showcasing Book Trailers</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-pinnacle-audio-blending-tools-for-distinct-online-media-presentations/"><u>New In 2024, Pinnacle Audio Blending Tools for Distinct Online Media Presentations</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/swiftly-blur-your-iphone-shots-with-these-4-tricks/"><u>Swiftly Blur Your iPhone Shots with These 4 Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/1719218317457-gpt4all-windows-guide-to-free-on-premise-chatbots/"><u>GPT4All Windows Guide to Free, On-Premise ChatBots.</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-faster-downloads-in-microsofts-app-stores/"><u>Mastering Faster Downloads in Microsoft's App Stores</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-looking-beyond-vegas-pro-10-outstanding-video-editing-software-for-mac/"><u>New In 2024, Looking Beyond Vegas Pro 10 Outstanding Video Editing Software for Mac</u></a></li>
<li><a href="https://win11.techidaily.com/managing-intermittent-default-printer-choice/"><u>Managing Intermittent Default Printer Choice</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-windows-alignment-combat-overscan-effects/"><u>Perfect Windows Alignment: Combat Overscan Effects</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-boosting-tiktok-video-playback-speeds/"><u>[New] In 2024, Boosting TikTok Video Playback Speeds</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-wwinplusprint-functionality-fixes-for-non-operational-printer-on-pc/"><u>Mastering WWin+Print Functionality: Fixes for Non-Operational Printer on PC</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-ending-the-gpsvc-hang-up-loop/"><u>Strategies for Ending the GPSVC Hang-Up Loop</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-11-sandbox-initialization/"><u>Navigating Through Windows 11 Sandbox Initialization</u></a></li>
<li><a href="https://win11.techidaily.com/delve-into-artificially-inspired-visuals-how-to-use-paint-cocreator-win11/"><u>Delve Into Artificially Inspired Visuals: How to Use Paint Cocreator (Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-windows-11s-mail-app-converting-html-in-emails-back-to-plain-text/"><u>Solutions for Windows 11'S Mail App: Converting HTML in Emails Back to Plain Text</u></a></li>
<li><a href="https://win11.techidaily.com/1719303345531-dealing-with-dysfunctional-print-via-wwin-command-on-windows/"><u>Dealing with Dysfunctional Print via WWin Command on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-disabled-usb-wi-fi-adapters-in-windows/"><u>How To Reactivate Disabled USB Wi-Fi Adapters in Windows</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-for-beginners-the-top-8-versatile-cameras-under-400/"><u>In 2024, For Beginners  The Top 8 Versatile Cameras Under $400</u></a></li>
<li><a href="https://extra-skills.techidaily.com/perfect-shots-no-hassle-leading-smartphone-tripods-for-2024/"><u>Perfect Shots, No Hassle  Leading Smartphone Tripods for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-7-best-voice-editing-apps-for-android-users/"><u>New 7 Best Voice Editing Apps for Android Users</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-guide-to-audacitys-professional-tracking/"><u>The Ultimate Guide to Audacity's Professional Tracking</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/how-to-dub-a-video-video-dubbing/"><u>How to Dub a Video Video Dubbing</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-message-rendering-issues-in-discord-desktop/"><u>Addressing Message Rendering Issues in Discord Desktop</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-infinix-zero-5g-2023-turbo-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Infinix Zero 5G 2023 Turbo | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/xbox-one-screen-recording-easy-steps-for-gamers-for-2024/"><u>Xbox One Screen Recording  Easy Steps for Gamers for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-honor-90-pro-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-honor-x50i-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Honor X50i FRP</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-connect-with-telnet-three-steps-for-windows-users/"><u>Efficiently Connect with Telnet: Three Steps for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-control-key-operability-with-ease-on-windows-11/"><u>Restoring Control Key Operability with Ease on Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-samsung-galaxy-m14-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Samsung Galaxy M14 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-microphone-use-a-deep-dive-into-win-11/"><u>Conquering Microphone Use: A Deep Dive Into Win 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-lava-agni-2-5g-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Lava Agni 2 5G | Dr.fone</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-the-art-of-engaging-crafting-compelling-reddit-content/"><u>[Updated] In 2024, The Art of Engaging  Crafting Compelling Reddit Content</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-video-sequences-fixing-delay-on-windows/"><u>Speeding Up Video Sequences: Fixing Delay on Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-se-to-androidios-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone SE To Android/iOS? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-photo-ordering-software-roundup/"><u>Essential Windows Photo Ordering Software Roundup</u></a></li>
<li><a href="https://win11.techidaily.com/revive-the-good-old-windows-photo-viewer-in-win1111-os/"><u>Revive the Good Old Windows Photo Viewer in Win11/11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/remote-procedure-call-woes-five-quick-solutions/"><u>Remote Procedure Call Woes - Five Quick Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-microsoft-m365-flaw-error-30015-26/"><u>Mitigating Microsoft M365 Flaw: Error 30015-26</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-microsoft-stores-error-x80131500/"><u>Troubleshooting Microsoft Store's Error X80131500</u></a></li>
</ul></div>
