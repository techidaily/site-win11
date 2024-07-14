---
title: Addressing Windows Bluetooth Headphones Playing Sound Without Volume Control
date: 2024-07-13T10:50:05.305Z
updated: 2024-07-14T10:50:05.305Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-honor-magic-6-pro-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Honor Magic 6 Pro FRP</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-flip-the-script-instagrams-video-trick/"><u>In 2024, Flip the Script  Instagram's Video Trick</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-handp-a-comprehensive-strategy-for-fb-health-marketing/"><u>Mastering H&P  A Comprehensive Strategy for FB Health Marketing</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unveil-windows-xp-professional-for-video-production-for-2024/"><u>Unveil Windows XP Professional for Video Production for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/comprehensive-study-on-razers-camera-quality-for-2024/"><u>Comprehensive Study on Razer's Camera Quality for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-can-you-unlock-apple-iphone-15-after-forgetting-the-passcode-by-drfone-ios/"><u>In 2024, Can You Unlock Apple iPhone 15 After Forgetting the Passcode?</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-solving-error-code-31-in-windows-systems/"><u>Understanding and Solving Error Code 31 in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-win-11-boot-drive-essential-tips-for-3-techniques/"><u>Creating a Win 11 Boot Drive – Essential Tips for 3 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-uninstall-programs-without-admin-privileges-on-windows/"><u>How to Uninstall Programs Without Admin Privileges on WINDOWS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-the-concealed-aspects-understanding-the-unique-stories-of-followers/"><u>[New] In 2024, The Concealed Aspects  Understanding the Unique Stories of Followers</u></a></li>
<li><a href="https://win11.techidaily.com/unravel-windows-mysteries-get-the-support-you-need/"><u>Unravel Windows Mysteries: Get the Support You Need!</u></a></li>
<li><a href="https://win11.techidaily.com/the-forgotten-windows-11-theme-archive/"><u>The Forgotten Windows 11 Theme Archive</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unwanted-keystrokes-during-typing/"><u>Preventing Unwanted Keystrokes During Typing</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-windows-streams-stopping-abrupt-download-drops/"><u>Optimize Windows Streams: Stopping Abrupt Download Drops</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-the-most-talented-lego-stop-motion-artists-this-year/"><u>2024 Approved The Most Talented Lego Stop Motion Artists This Year</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-overcoming-a-non-functional-search-in-windows-11s-environment/"><u>Tips for Overcoming a Non-Functional Search in Windows 11’S Environment</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/tailor-made-viewing-pace-on-youtube-at-your-fingertips-for-2024/"><u>Tailor-Made Viewing Pace on YouTube at Your Fingertips for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-chrome-file-uploading-woes-a-guide-for-windows-devices/"><u>Navigate Chrome File Uploading Woes: A Guide for Windows Devices</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-from-novice-to-master-an-insiders-guide-to-boomerang-excellence-for-2024/"><u>[Updated] From Novice to Master  An Insider's Guide to Boomerang Excellence for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-2023-best-facebook-video-downloader-and-addons-for-firefox/"><u>[Updated] 2024 Approved  2023 | Best Facebook Video Downloader And Addons for Firefox</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-pc-display-with-best-time-clock-screen-savers/"><u>Enhance PC Display with Best Time Clock Screen Savers</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-automatic-detect-of-proxy-issues/"><u>Fixing Windows' Automatic Detect of Proxy Issues</u></a></li>
<li><a href="https://win11.techidaily.com/securing-access-how-to-use-windows-11s-security-interface/"><u>Securing Access: How to Use Windows 11'S Security Interface</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-tweet-views-triumph-discovering-the-top-10-video-tweets/"><u>[Updated] 2024 Approved  Tweet Views Triumph  Discovering the Top 10 Video Tweets</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-excellence-in-separating-silence-and-signal-audio-extraction-from-videos-for-modern-tech/"><u>New 2024 Approved Excellence in Separating Silence and Signal Audio Extraction From Videos for Modern Tech</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-setting-up-bings-chat-for-windows-11-users/"><u>Streamline Setting Up Bing's Chat for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-restore-screen-share-in-teams/"><u>Steps to Restore Screen Share in Teams</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-boost-sound-level-for-twitters-quiet-vids/"><u>[New] Boost Sound Level for Twitter's Quiet Vids</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-impressive-analysis-and-rival-proposals/"><u>In 2024, Impressive Analysis & Rival Proposals</u></a></li>
<li><a href="https://win11.techidaily.com/a-detailed-exploration-of-win11s-voice-control-shortcuts/"><u>A Detailed Exploration of Win11's Voice Control Shortcuts</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-tecno-camon-20-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Tecno Camon 20 Phone FRP Lock</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-insta-live-with-obs-broadcast/"><u>[New] Insta Live with OBS Broadcast</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-shared-connectivity-options-google-versus-windows/"><u>Exploring Shared Connectivity Options: Google Versus Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-utilizing-qr-scanners-in-windows/"><u>The Ultimate Guide to Utilizing QR Scanners in Windows</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-twittervidstowebm-direct-media-conversion/"><u>[New] In 2024, TwitterVidsToWebM  Direct Media Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/windows-define-custom-idle-timeframe/"><u>Windows: Define Custom Idle Timeframe</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-google-pixel-fold-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve deleted photos on Google Pixel Fold</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-xbox-audio-hurdles-with-windows-11-system-upgrades/"><u>Overcoming Xbox Audio Hurdles with Windows 11 System Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/taking-out-trash-onedrive-from-your-pcs-file-explorer/"><u>Taking Out Trash: OneDrive From Your PC's File Explorer</u></a></li>
<li><a href="https://ai-voice.techidaily.com/updated-voicemod-ai-review-transforming-your-voice-in-real-time-for-2024/"><u>Updated Voicemod AI Review Transforming Your Voice in Real Time for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>How to Hide/Fake Snapchat Location on Your Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-error-correction-for-rpc-failures/"><u>Mastering Windows Error Correction for RPC Failures</u></a></li>
<li><a href="https://win11.techidaily.com/windows-program-commands-keybinding-setup/"><u>Windows Program Commands: Keybinding Setup</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remediation-for-elusive-obs-studio-issue-on-win-11-pcs/"><u>Swift Remediation for Elusive OBS Studio Issue on Win 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/stop-spacing-out-sounds-fixes-to-unmute-keyboard-volume/"><u>Stop Spacing Out Sounds: Fixes to Unmute Keyboard Volume</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-meizu-21-pro-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Meizu 21 Pro to Protect Your Individual Information</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-sync-windows-plus-android-via-flow-app/"><u>Streamlining Sync: Windows + Android via Flow App</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-finding-the-perfect-dj-template-video-download-for-your-events/"><u>[Updated] 2024 Approved  Finding the Perfect DJ Template Video Download for Your Events</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-convert-twitter-video-to-audiomp4webm-for-2024/"><u>[Updated] Convert Twitter Video to Audio/MP4/WebM for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/regain-control-fixing-wi-fi-mouse-malfunctions-in-windows/"><u>Regain Control: Fixing Wi-Fi Mouse Malfunctions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/end-hibernation-hurdles-with-easy-fixes-for-win/"><u>End Hibernation Hurdles with Easy Fixes for Win</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Tecno Spark 20? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-exclusive-free-mcb-banner-designs/"><u>[Updated] 2024 Approved  Exclusive Free MCB Banner Designs</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inaccessible-window-resolutions-8-simple-steps/"><u>Fixing Inaccessible Window Resolutions: 8 Simple Steps</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-network-link-disruptions-in-winmc-minecraft/"><u>Tackling Network Link Disruptions in WinMC Minecraft</u></a></li>
<li><a href="https://network-issues.techidaily.com/putting-a-stop-to-windows-glare-surge/"><u>Putting a Stop to Window's Glare Surge</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-gauging-influence-tracking-metrics-that-predict-igtv-performance/"><u>[New] Gauging Influence  Tracking Metrics that Predict IGTV Performance</u></a></li>
<li><a href="https://win11.techidaily.com/turn-on-school-inspired-themes-for-win-11/"><u>Turn On School-Inspired Themes for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixed-overcoming-application-crash-error/"><u>Mastering the Art of Fixed: Overcoming 'Application Crash' Error</u></a></li>
<li><a href="https://win11.techidaily.com/consistent-connections-avoiding-disruptions-in-windows/"><u>Consistent Connections: Avoiding Disruptions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unyielding-security-seven-ways-to-shield-your-system/"><u>Unyielding Security: Seven Ways to Shield Your System</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/valorant-portraits-professional-thumbnails-made-in-a-flash-in-2024/"><u>Valorant Portraits - Professional Thumbnails Made in a Flash, In 2024</u></a></li>
</ul></div>
