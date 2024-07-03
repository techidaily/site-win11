---
title: Guidance to Reconnect Controlled Audio From Windows' Bluetooth Devices
date: 2024-06-25T11:29:42.933Z
updated: 2024-06-26T11:29:42.933Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Guidance to Reconnect Controlled Audio From Windows' Bluetooth Devices
excerpt: This Article Describes Guidance to Reconnect Controlled Audio From Windows' Bluetooth Devices
keywords: Reconnecting Bluetooth Audio,Windows Bluetooth Connectivity,Restore Audio Links,Bluetooth Pairing Guide,Controlled Audio Retrieval,Windows Audio Matching,Bluetooth Device Sync
thumbnail: https://thmb.techidaily.com/5dda734007d0cce4f616f2328d041526d598c5a6fb318adf671f70aacd812852.jpg
---

## Guidance to Reconnect Controlled Audio From Windows' Bluetooth Devices

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
<li><a href="https://win11.techidaily.com/eliminating-the-hurdles-of-error-0x80040610-a-comprehensive-approach/"><u>Eliminating the Hurdles of Error 0X80040610: A Comprehensive Approach</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-system-call-failure-in-win1011-systems/"><u>Remedying System Call Failure in Win10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-interface-with-fn-key-modifications/"><u>Enhancing User Interface with FN Key Modifications</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-hyper-v-error-0x8009030e/"><u>Overcoming Windows Hyper-V Error 0X8009030E</u></a></li>
<li><a href="https://win11.techidaily.com/activate-and-optimize-windows-powershell-script-policies/"><u>Activate and Optimize Windows PowerShell Script Policies</u></a></li>
<li><a href="https://win11.techidaily.com/solve-yellow-tint-issue-in-windows-monitorage/"><u>Solve Yellow Tint Issue in Windows Monitorage</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-the-nuances-of-winstall-for-grouped-windows-11-installs/"><u>Navigate the Nuances of Winstall for Grouped Windows 11 Installs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-discovering-the-significance-of-blue-icons-on-fb-messaging-app/"><u>[New] 2024 Approved  Discovering the Significance of Blue Icons on FB Messaging App</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-fix-iphone-se-could-not-be-activatedreached-issue-by-drfone-ios/"><u>In 2024, How To Fix iPhone SE Could Not Be Activated/Reached Issue</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-htc-u23-pro-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart HTC U23 Pro Without Power Button | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-trail-the-echoes-of-de-follows-in-instagram-land/"><u>[New] 2024 Approved  Trail the Echoes of De-Follows in Instagram Land</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-a-practical-approach-to-creating-captivating-youtube-shorts-templates/"><u>[Updated] A Practical Approach to Creating Captivating YouTube Shorts Templates</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/androidiphones-finest-top-10-cost-effective-image-enhancers-ranked/"><u>Android/iPhone's Finest – Top 10 Cost-Effective Image Enhancers Ranked</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-xs-to-other-iphone-11-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone XS To Other iPhone 11 devices? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-vivo-g2-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Vivo G2 Phone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>