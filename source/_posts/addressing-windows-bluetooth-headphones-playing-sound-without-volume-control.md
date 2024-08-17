---
title: Addressing Windows Bluetooth Headphones Playing Sound Without Volume Control
date: 2024-08-15T23:44:27.854Z
updated: 2024-08-16T23:44:27.854Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Windows Bluetooth Headphones Playing Sound Without Volume Control
excerpt: This Article Describes Addressing Windows Bluetooth Headphones Playing Sound Without Volume Control
keywords: Bluetooth Headphones Volume Control,Windows Audio Playback Issues,Noise on Bluetooth Devices,Uncontrolled Sound Volume,Headphone Sound Glitches,Fixing Bluetooth Device Noise,Windows Volume Management
thumbnail: https://thmb.techidaily.com/9f78d218ca56a8e977ac9c156c6d3df029b653f49542887406f9b6531aa186a8.jpg
---

## Addressing Windows Bluetooth Headphones Playing Sound Without Volume Control

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
## 2\. Enable Bluetooth Services in Device Properties

 Your headset or speaker offers distinct services which are enabled by default. However, if disabled, one or more Bluetooth functions can stop working for your audio device. To fix the issue, open the Bluetooth device properties using the Control Panel and review the services.

 Here’s how to do that:

1. Press **Win + R** to open **Run**.  
![control printers run box windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/control-printers-run-box-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
7. Compare the version with the one available on your computer. Download the newer version if available. Run the installer and complete the installation.
8. During installation, your Bluetooth devices, including the headphone, keyboard, and mouse, may stop working temporarily. Wait for a few minutes for the changes to apply. Sometimes, a restart may be necessary to finish installing the update.

 Similarly, the download page may also offer older versions of the driver. If you have the latest version installed, try to download an older version to perform a downgrade. Useful if the rollback driver option isn’t available in Device Manager.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing the Bluetooth Headset or Speaker Showing a "Voice Only" Error

 Incorrect Bluetooth service configuration is a common reason your Bluetooth device shows as connected as voice only. You can configure the device’s properties to enable these services. If the issue persists, check for driver issues by installing a new driver update or performing a driver rollback.

 However, if a quick reconnect doesn’t help, the problem may be due to a buggy audio driver, incorrect audio device configuration, and stopped audio services. Here we show you a few troubleshooting tips to help you resolve this problem on Windows and get your Bluetooth headset working again.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-elevate-your-recordings-doing-without-a-microphone/"><u>[New] In 2024, Elevate Your Recordings  Doing Without a Microphone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-image-enhancement-101-text-addition-for-pc-and-mac-users/"><u>[New] In 2024, Image Enhancement 101  Text Addition for PC and Mac Users</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-sharpsight-screen-snag-report/"><u>[Updated] 2024 Approved  SharpSight Screen Snag Report</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-social-media-mastery-surpassing-the-competition-in-popularity-rankings/"><u>[Updated] In 2024, Social Media Mastery  Surpassing the Competition in Popularity Rankings</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-adopting-a-simple-yet-powerful-approach-to-advertising-content/"><u>2024 Approved  Adopting a Simple Yet Powerful Approach to Advertising Content</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-motorola-moto-g73-5g-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-google-pixel-fold-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Google Pixel Fold without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/access-a-world-of-literature-for-free-with-these-17-book-download-portals/"><u>Access a World of Literature for Free with These 17 Book Download Portals</u></a></li>
<li><a href="https://win11.techidaily.com/comparing-untapped-windows-features-reliability-and-performance/"><u>Comparing Untapped Windows Features: Reliability & Performance</u></a></li>
<li><a href="https://win11.techidaily.com/conceal-or-show-taskbars-date-and-clock-in-win-11/"><u>Conceal or Show Taskbar's Date & Clock in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/concealment-command-challenge-the-invisible-start-menu-shutdown/"><u>Concealment Command Challenge: The Invisible Start Menu Shutdown</u></a></li>
<li><a href="https://win11.techidaily.com/delaying-microsoft-edge-tabs-a-win11-guide/"><u>Delaying Microsoft Edge Tabs: A Win11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-disk-identities-c-vs-d-a-review/"><u>Demystifying Disk Identities (C vs D): A Review</u></a></li>
<li><a href="https://win11.techidaily.com/diving-into-the-oled-world-asus-s15s-unique-appeal/"><u>Diving Into the OLED World: ASUS S15's Unique Appeal</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-supercharge-your-startup-with-windows-11/"><u>Essential Steps to Supercharge Your Startup with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/get-the-xbox-app-working-again-on-your-windows-laptop/"><u>Get the Xbox App Working Again on Your Windows Laptop</u></a></li>
<li><a href="https://win11.techidaily.com/guaranteeing-successful-windows-11-updates/"><u>Guaranteeing Successful Windows 11 Updates</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-swift-control-panel-navigation-in-windows/"><u>Guide to Swift Control Panel Navigation in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-stalled-status-on-qbittorrent-for-windows/"><u>How to Fix the Stalled Status on qBittorrent for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reset-split-screen-errors-in-windows/"><u>How to Reset Split Screen Errors in WIndows</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-tecno-camon-30-pro-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Tecno Camon 30 Pro 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-action-plan-reactivating-your-menu-items/"><u>Immediate Action Plan: Reactivating Your Menu Items</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-samsung-galaxy-a54-5g-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Samsung Galaxy A54 5G to iPhone | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-detailed-review-of-doctorsim-unlock-service-for-iphone-13-pro-max-by-drfone-ios/"><u>In 2024, Detailed Review of doctorSIM Unlock Service For iPhone 13 Pro Max</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-nokia-c12-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Nokia C12 Phone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-prime-selection-of-360-videography-tools/"><u>In 2024, Prime Selection of 360° Videography Tools</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-top-9-fb-scraper-apps-for-films/"><u>In 2024, Top 9 FB Scraper Apps for Films</u></a></li>
<li><a href="https://win11.techidaily.com/learn-the-art-of-handling-several-zipped-items-with-one-command/"><u>Learn the Art of Handling Several Zipped Items with One Command</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-win11-for-a-smoother-jump-into-programs-on-startup/"><u>Optimizing Win11 for a Smoother Jump Into Programs on Startup</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-operation-7x09-on-win10/"><u>Overcoming Operation 7X09 on Win10</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-printer-service-not-running-issue-in-win/"><u>Overcoming Printer Service Not Running Issue in Win</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-image-failure-error-0x80780119/"><u>Overcoming Windows' Image Failure: Error 0X80780119</u></a></li>
<li><a href="https://win11.techidaily.com/prime-windows-11-tools-for-unmatched-video-scripting-and-edits/"><u>Prime Windows 11 Tools for Unmatched Video Scripting & Edits</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-the-clicks-defeating-silent-spaces-on-pc/"><u>Reclaiming the Clicks: Defeating Silent Spaces on PC</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-windows-operating-edition-epoch/"><u>Revealing Windows Operating Edition Epoch</u></a></li>
<li><a href="https://win11.techidaily.com/revitalizing-vintage-directx-apps-by-harnessing-dxvk-power/"><u>Revitalizing Vintage DirectX Apps by Harnessing DXVK Power</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-non-genuine-alert-on-windows-pc/"><u>Sidestep Non-Genuine Alert on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/signs-your-pc-struggles-when-to-consider-clean-slate/"><u>Signs Your PC Struggles, When to Consider Clean Slate</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-strategies-for-definitions-in-win11/"><u>Speedy Strategies for Definitions in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-approach-to-configure-win11s-dns-client-service/"><u>Step-by-Step Approach to Configure Win11's DNS Client Service</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reinstate-the-mia-dxgidll-in-windows-11/"><u>Steps to Reinstate the MIA Dxgi.dll in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-files-using-powerrename-in-powertoys/"><u>Streamline Your Files: Using PowerRename in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-file-system-problems-in-windows-11-os/"><u>Tackling File System Problems in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-exe-opening-conundrum-with-ease/"><u>Tackling Windows EXE Opening Conundrum with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/taming-false-antivirus-alarms-a-windows-chrome-fix/"><u>Taming False Antivirus Alarms: A Windows Chrome Fix</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-timely-purge-of-steam-dns-cache-on-pc/"><u>Techniques for Timely Purge of Steam DNS Cache on PC</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-motorola-g54-5g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Motorola G54 5G Reset Code | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-rectifying-windows-msvcr110dll-gap/"><u>Tips for Rectifying Windows' msvcr110.dll Gap</u></a></li>
<li><a href="https://win11.techidaily.com/top-solutions-when-your-windows-security-is-down/"><u>Top Solutions When Your Windows Security Is Down</u></a></li>
<li><a href="https://win11.techidaily.com/win-centric-tips-for-switching-mkv-format-to-mp4/"><u>Win-Centric Tips for Switching MKV Format to MP4</u></a></li>
<li><a href="https://win11.techidaily.com/window-navigation-optimization-adding-this-pc-icons/"><u>Window Navigation Optimization: Adding 'This PC' Icons</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wizardry-six-routes-to-property-insight/"><u>Windows Wizardry: Six Routes to Property Insight</u></a></li>
</ul></div>
