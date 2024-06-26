---
title: Correcting Windows Bluetooth Device - Unable to Use Buttons or Mute
date: 2024-06-25T11:32:20.193Z
updated: 2024-06-26T11:32:20.193Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Correcting Windows Bluetooth Device - Unable to Use Buttons or Mute
excerpt: This Article Describes Correcting Windows Bluetooth Device - Unable to Use Buttons or Mute
keywords: Windows Bluetooth Troubleshooting,Fix Windows Bluetooth Connection,Resolve Button Issues on Bluetooth Devices (Windows),Windows Bluetooth Unresponsive Fix,Mute Issue in Windows Bluetooth,Enable Buttons on Windows Bluetooth,Reconnect Bluetooth to Windows Device
thumbnail: https://thmb.techidaily.com/45a1460bb3d83c14f6fab217fbb0ba6456c10cd4af0bd545fe595145134aa150.jpg
---

## Correcting Windows Bluetooth Device - Unable to Use Buttons or Mute

 When you connect your Bluetooth headphone or speaker to your Windows computer, it may show the status as connected as "voice only" or "music only." This is nothing a quick "disconnect and reconnect" troubleshooting method can’t usually solve.

 However, if a quick reconnect doesn’t help, the problem may be due to a buggy audio driver, incorrect audio device configuration, and stopped audio services. Here we show you a few troubleshooting tips to help you resolve this problem on Windows and get your Bluetooth headset working again.

## 1\. Run the Windows Bluetooth Troubleshooter

![Run Bluetooth troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/bluetooth-troubleshooter-1.jpg)

 Windows 10 and 11 feature a built-in troubleshooter to find and fix common Bluetooth issues. It is an automated tool but works differently on Windows 10 and 11\.

 To run the Bluetooth troubleshooter:

1. Press **Win + I** to open **Settings**.
2. In the **System** tab, scroll down and click on **Troubleshooter**.
3. Select the **Other troubleshooters** option.  
![bluetooth troubleshooter get help automatic diagnostic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/bluetooth-troubleshooter-get-help-automatic-diagnostic.jpg)
4. Click **Run** for the **Bluetooth** option.
5. The troubleshooter will scan the system for issues and recommend applicable fixes automatically. Follow the on-screen instructions to apply the fixes.
6. On the newer iteration of Windows 11, this will open the **Get Help** app seeking your consent to run the troubleshooter. Click **Yes** and then follow the on-screen instructions. You can skip some steps, like checking for Windows updates, by selecting the **No** option.

 Let the Get Help app try all available fixes until the issue is fixed.

## 2\. Enable Bluetooth Services in Device Properties

 Your headset or speaker offers distinct services which are enabled by default. However, if disabled, one or more Bluetooth functions can stop working for your audio device. To fix the issue, open the Bluetooth device properties using the Control Panel and review the services.

 Here’s how to do that:

1. Press **Win + R** to open **Run**.  
![control printers run box windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/control-printers-run-box-windows.jpg)
2. Type **control Printer** and click **OK** to open the **Bluetooth & devices** tab in the **Settings** app.
3. Next, click on **Devices**.  
![bluetooth and devices devices windows 11 settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/bluetooth-and-devices-devices-windows-11-settings.jpg)
4. Scroll down and click **More devices** **and printer settings**. This should open **Devices and Printers** in the Control Panel.
5. Alternatively, copy and paste the following in the **Run** dialog to open **Device and Printers**.  
`shell:::{A8A91A66-3A7D-4424-8D24-04E180695C7A}`
6. Next, right-click on your **Bluetooth headset** or **speaker** and select **Properties**.
7. Open the **Services** tab in the **Properties** dialog.
8. Under **Bluetooth services**, select all the options. You’ll usually have the following options. Enable them all:  
`Audio Sink  
Handsfree Telephony  
Remote Control  
Remotely Controllable Device`
9. Click **Apply** and **OK** to save the changes.

 Close the Control Panel, and your Bluetooth audio device should start to work now. If not, perform a restart and check for any improvements.

## 3\. Check and Enable the Windows Bluetooth Services

 Windows OS uses multiple Bluetooth-related services that help it connect to other Bluetooth devices and transmit audio. This is in addition to the services enabled above.

 If any of these services are stopped or incorrectly configured, your Bluetooth headphone or speaker can start malfunctioning. To fix the problem, check the status of all the essential Bluetooth-associated services and restart them if necessary.

 You can check the status of services and restart them from the Services snap-in. To check and restart Bluetooth services:

1. Press **Win + R** to open **Run**.
2. Type **services.msc** and click **OK** to open the Services snap-in.  
![Services Shortcode In Run Dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/opening-sevices-from-run_dialog.jpg)
3. In the Services snap-in, locate the following services and check if the status shows **Running**.  
`Bluetooth Audio Gateway Service  
Bluetooth Support Service  
Bluetooth User Support Service`
4. If not, right-click on **Bluetooth Audio Gateway Service** and select **Restart**.  
![restart bluetooth services services snap in windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/restart-bluetooth-services-services-snap-in-windows.jpg)
5. Once done, check the other two services. If not running, restart the services one by one.
6. Close the Services snap-in and check for any improvements.

 If the issue persists, [disable any audio enhancements on Windows](https://www.makeuseof.com/disable-audio-enhancements-windows/). While intended to improve your listening experience, these enhancements can also cause audio issues. Turning off these enhancements can help you resolve the problem with your audio devices.

## 4\. Check Your Bluetooth Device Driver for Issues

 An outdated or buggy Bluetooth driver is a common cause of a malfunctioning Bluetooth device on Windows computers. Try to update the driver, perform a roll back or uninstall the driver to see if it resolves the issue.

* **Update the driver**: You can [find and replace outdated drivers on Windows using Device Manager](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/). In Device Manager, expand the **Bluetooth** section and locate your Bluetooth adapter. On most computers, you may find an **Intel Bluetooth Wireless Bluetooth** device. Find the device and check if a new driver update is available.
* **Roll back a recent driver update**: New but buggy driver update can also cause the Bluetooth adapter to act up. To fix the issue, you can [perform a driver rollback for the Bluetooth adapter](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) to install the previous driver version. While a handy option, its availability can differ depending on when the driver was installed.
* **Reinstall the Bluetooth adapter driver:** A reinstall may be necessary if a corrupt or partially installed driver causes Bluetooth-related problems. To [uninstall Bluetooth drivers in Windows](https://www.makeuseof.com/windows-11-uninstall-drivers/), you can use the Device Manager or the Command Prompt. Restart your PC and Windows should reinstall the driver.

## 5\. Update the Bluetooth Driver Manually From the Manufacturer’s Website

 While some driver updates may be available via Windows updates, you will likely receive the latest update from the device manufacturer's website. In this instance, check your Bluetooth device manufacturer's website to see if a new update is available.

 To manually download and install the latest Bluetooth device driver update:

1. Press **Win + R** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open Device Manager.
3. In Device Manager, expand the **Bluetooth** section. Here locate your Bluetooth device's make. In this instance, we have an **Intel (R) Wireless Bluetooth (R)** device.  
![device manager driver version detials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/device-manager-driver-version-detials.jpg)
4. Double-click on the Bluetooth device entry to open its properties.
5. Next, open the **Driver** tab. Note down the Driver version. You’ll need this to see if a newer driver version is available.
6. Since we have an Intel Bluetooth Wireless device, we’ll open the [Intel Wireless Bluetooth for Windows page](https://www.intel.com/content/www/us/en/download/18649/intel-wireless-bluetooth-for-windows-10-and-windows-11.html). The page lists the latest version of the driver available for download. In case of a different Bluetooth device manufacturer, visit the manufacturer's website and locate downloads for the device.  
![download bluetooth driver manually](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/download-bluetooth-driver-manually.jpg)
7. Compare the version with the one available on your computer. Download the newer version if available. Run the installer and complete the installation.
8. During installation, your Bluetooth devices, including the headphone, keyboard, and mouse, may stop working temporarily. Wait for a few minutes for the changes to apply. Sometimes, a restart may be necessary to finish installing the update.

 Similarly, the download page may also offer older versions of the driver. If you have the latest version installed, try to download an older version to perform a downgrade. Useful if the rollback driver option isn’t available in Device Manager.

## Fixing the Bluetooth Headset or Speaker Showing a "Voice Only" Error

 Incorrect Bluetooth service configuration is a common reason your Bluetooth device shows as connected as voice only. You can configure the device’s properties to enable these services. If the issue persists, check for driver issues by installing a new driver update or performing a driver rollback.

 However, if a quick reconnect doesn’t help, the problem may be due to a buggy audio driver, incorrect audio device configuration, and stopped audio services. Here we show you a few troubleshooting tips to help you resolve this problem on Windows and get your Bluetooth headset working again.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/navigating-windows-11-security-new-passwords/"><u>Navigating Windows 11 Security: New Passwords</u></a></li>
<li><a href="https://win11.techidaily.com/coding-a-deity-command-into-system-menu/"><u>Coding a Deity Command Into System Menu</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-process-for-downloading-adobe-on-microsoft-store/"><u>The Complete Process for Downloading Adobe on Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/game-resurrection-applying-retroarchs-shaders-to-vintage-games/"><u>Game Resurrection: Applying RetroArch's Shaders to Vintage Games</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-repairing-disk-errors-issue-on-windows/"><u>How to Fix the Repairing Disk Errors Issue on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-management-for-windows-11-domain-based/"><u>Biometric Management for Windows 11, Domain-Based</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-insufficient-ram-warning-for-hogwarts-simulator/"><u>Fixing Insufficient RAM Warning for Hogwarts Simulator</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-take-against-lunar-client-start-up-failure-notice/"><u>Actions to Take Against Lunar Client Start-Up Failure Notice</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-with-file-explorer-on-win11-effective-repair-methods/"><u>Trouble with File Explorer on Win11? Effective Repair Methods</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-microsoft-m365-flaw-error-30015-26/"><u>Mitigating Microsoft M365 Flaw: Error 30015-26</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/get-noticed-with-these-20-eye-catching-adobe-premiere-intro-templates-free-download-for-2024/"><u>Get Noticed with These 20 Eye-Catching Adobe Premiere Intro Templates Free Download for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unleash-the-potential-of-your-video-with-best-thumbnail-fonts/"><u>[New] Unleash the Potential of Your Video with Best Thumbnail Fonts</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/izing-content-how-much-adsense-pays-you-per-thousand-video-hits/"><u>Monetizing Content  How Much AdSense Pays You Per Thousand Video Hits?</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-the-ultimate-guide-to-vlog-video-editing-best-software-for-creators/"><u>Updated 2024 Approved The Ultimate Guide to Vlog Video Editing Best Software for Creators</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-quick-fixes-for-a-larger-tiktok-following-must-know-hacks/"><u>[New] Quick Fixes for a Larger TikTok Following  Must-Know Hacks</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-preserve-audio-perfection-how-to-convert-video-to-mp3-without-quality-loss/"><u>Updated 2024 Approved Preserve Audio Perfection How to Convert Video to MP3 without Quality Loss</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-unmissable-experiences-in-digital-playfields-for-2024/"><u>[New] Unmissable Experiences in Digital Playfields for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-photo-preservation-101-digitalization-of-ancestral-prints/"><u>In 2024, Photo Preservation 101  Digitalization of Ancestral Prints</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-basics-of-visual-storytelling/"><u>In 2024, Basics of Visual Storytelling</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-fine-tuning-audacitys-decibel-settings-for-perfect-balance/"><u>In 2024, Fine-Tuning Audacitys Decibel Settings for Perfect Balance</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>