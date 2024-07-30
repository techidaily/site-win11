---
title: Remedying the Conflict Between Apps and Computer's Default Audio
date: 2024-07-29T15:48:50.676Z
updated: 2024-07-30T15:48:50.676Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Remedying the Conflict Between Apps and Computer's Default Audio
excerpt: This Article Describes Remedying the Conflict Between Apps and Computer's Default Audio
keywords: Fixing Audio Conflicts,Resolve App-Audio Clash,Eliminate Audio Disputes,Harmonize App Sound Output,Sync Apps & Computer Audio,Reduce Default Audio Conflict,Balance App Audio Settings
thumbnail: https://thmb.techidaily.com/6cbefc5821941765c64c748053e1b0a5829fef1524e233743a9045ce3a1167e9.jpg
---

## Remedying the Conflict Between Apps and Computer's Default Audio

 The audio device on your Windows computer can simultaneously play audio from multiple sources. However, at times, the audio stops playing with the error "this device is being used by another application".

 This is error is often a case of incorrectly configured Windows Audio service. Other times, the audio issue is due to a corrupt audio device driver. Here we show you how to troubleshoot the "this device is being used by another application" error and restore audio on Windows.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
## 1\. Run the Windows Audio Troubleshooter

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
![Windows 11 settings troubleshoot other troubleshooters playing audio run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-troubleshoot-other-troubleshooters-playing-audio-run.jpg)

 Windows has a built-in audio troubleshooter to find and fix issues with playing audio. The troubleshooter looks for common audio issues and tries to fix them automatically.

To run the audio troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, click on**Troubleshoot** .
3. Click on**Other troubleshooters** .
4. Next, click the**Run** button for**Playing Audio** . Wait for the audio troubleshooter to scan for issues. Then select the affected audio device and click**Next** .
5. Follow the on-screen instructions and check if the error is resolved.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. Disable Exclusive Mode for the Audio Device

 By default, Windows applications can take exclusive control of the audio device. While enabling this option shouldn’t cause any issues, some apps may prevent the device from being used by other audio services. To fix the problem, disable exclusive mode to stop applications from taking exclusive control of the audio device.

To disable Exclusive Mode for the audio device on Windows:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, click on**Sound** .
3. Scroll down and click on**More sound settings** .  
![more sound settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/more-sound-settings-windows-11.jpg)
4. Select the audio device in the**Sound** dialog and click the**Properties** button.
5. Open the**Advanced** tab in the**Properties** dialog.  
![disable exclusive mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-exclusive-mode.jpg)
6. Uncheck the **Allow application to take exclusive control of this device** and**Give exclusive mode application priority** options.
7. Click**Apply** and**OK** to save the changes.

 Restart your computer and check if the error is resolved and if the audio device is working again.

## 3\. Change Windows Audio Service Startup Type

 Windows Audio service is responsible for managing audio devices connected to your computer. If the service is disabled or not running, your audio device can stop working.

 By default, it is set to start automatically as you power on your device. Check if the Startup type for Windows Audio is set to Manually. If yes, reconfigure it to start automatically to fix audio problems.

To change the Windows Audio service Startup type:

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** to open the**Services** snap-in.
3. In the**Services** window, locate and double-click on**Windows Audio** service.  
![windows audio service properties services snap in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service-properties-services-snap-in.jpg)
4. Click the**Startup** type drop-down and select**Automatic** .
5. Click**Apply** and**OK** to save the changes.  
![windows audio service startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service-startup-type-automatic.jpg)
6. If the service is not running, right-click on**Windows Audio** and select**Start** .
7. Close the Services snap-in and restart your PC. After the restart, your audio device should start working again.

## 4\. Disable and Re-Enable the Sound Output Device

 You can temporarily disable and re-enable the audio device to fix any glitches causing the device to malfunction. You can [disable the audio device](https://www.makeuseof.com/enable-disable-sound-output-devices-in-windows/) using the Settings app and Device Manager.

 To disable the audio device, right-click on the audio device and select**Disable device** in**Device Manager** . Next, right-click on the audio device and**Enable Device** . Close Device Manager and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 5\. Uninstall and Reinstall the Audio Device and Driver

![Uninstalling an audio device in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/uninstalling-audio-device-windows-11.jpg)

 You can also troubleshoot your audio problems by uninstalling the audio device and the associated drivers. Reinstalling the audio device can help if the sound problem is due to corrupt audio drivers.

To uninstall your audio device on Windows:

1. Press**Win + X** to open the**WinX menu** .
2. Select**Device Manager** for the menu.
3. In Device Manager, expand the**Audio inputs and output section** .
4. Right-click on your audio device and select**Uninstall device** .
5. Read the warning and click**Uninstall** to confirm the action. Wait for the device to uninstall.

 You may see a yellow exclamation mark on the uninstalled audio device. To reinstall the driver, click on**File** and select**Scan for hardware changes** . This should reinstall the sound device and driver. If not, restart your computer. As the system restarts, Windows will reinstall the missing audio device driver and restore sound on your computer.

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Perform a Driver Rollback

 If you have an external sound card and have installed an update, try a driver rollback. A new driver update can sometimes create more problems than it intends to fix. You can use the device driver rollback feature in Device Manager to undo the changes and reinstall the older version of the driver.

 You can [roll back a driver using Windows Device Manager](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) . In Device Manager, expand the**Sound, Video, and Game Controllers** section. Next, access your external sound card properties to perform a rollback.

 If the Roll Back Driver option is greyed out, it means the option is unavailable for the selected device. In this instance, uninstall the existing audio device driver and download an older version of the driver from your sound card manufacturer's website. Your sound card manufacturer may also have a newer driver version available. If available, install the latest version and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## 7\. Install Pending Windows Updates

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![windows 11 view update history](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/winodws-11-view-update-history.jpg)

 If it is a Windows-specific issue, installing pending Windows updates can fix the problem. Check the Windows updates page for newer updates and install them to see if that helps resolve the issue.

 To install Windows update, go to**Settings > Windows Update** and click**Check for updates** . Windows will populate the screen with all the pending updates. You can install the updates or selectively install any audio device updates.

## 8\. Check for Third-Party App Conflict

![volume mixer windows 11 view audio applications](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/volume-mixer-windows-11-view-audio-applications.jpg)

 If the issue persists, check if there is a third-party app conflict. You can use Volume Mixer to view applications accessing the audio devices and close the problematic app to fix the problem. Here’s how to do it.

1. Press**Win + R** to open Run.
2. Type**sndvol** and click**OK** to open Volume Mixer.
3. The**Application** column will show all the apps using your audio device.

 To close the app, open the system tray, right-click the app icon, and select**Quit** . You can also force close the app using Task Manager. If the issue persists, uninstall the problematic app to restore the audio to your computer.

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing the Audio Device in Use By Another Application Error

 This error is often the result of an audio device driver problem. To fix the error, check if a new driver is available. If not, perform a rollback to install the previous driver version. Also, disable exclusive application access to audio devices and configure the Windows Audio service to start automatically.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-how-can-you-air-facebook-videos-on-your-television-set/"><u>[New] How Can You Air Facebook Videos on Your Television Set?</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-a-beginners-guide-to-sony-vegas-and-youtube-cutting/"><u>[Updated] 2024 Approved  A Beginner's Guide to Sony Vegas and YouTube Cutting</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-tech-savvy-tips-to-ensure-perfect-call-recording-on-facetime/"><u>[Updated] 2024 Approved  Tech-Savvy Tips to Ensure Perfect Call Recording on FaceTime</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-from-start-to-end-mastering-the-art-of-fading-in-pro/"><u>2024 Approved  From Start to End  Mastering the Art of Fading in Pro</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-the-ultimate-guide-to-mov-file-handling-in-windows-11/"><u>2024 Approved  The Ultimate Guide to MOV File Handling in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-code-0x800704b3-on-windows-pcs/"><u>Addressing Error Code 0X800704B3 on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-windows-credential-entry-attempts/"><u>Analyzing Windows Credential Entry Attempts</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-with-descriptive-folders-in-windows-11/"><u>Boosting Productivity with Descriptive Folders in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-disallowed-label-on-windows-programs/"><u>Clearing Disallowed Label on Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/corrective-guide-to-browser-paste-issues-on-windows/"><u>Corrective Guide to Browser Paste Issues on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/critical-hardware-scan-tools/"><u>Critical Hardware Scan Tools</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-error-code-0xc0000001-on-windows/"><u>Decoding and Fixing Error Code 0XC0000001 on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-dev-drive-setup-in-windows-11-development-space/"><u>Demystifying Dev Drive Setup in Windows 11 Development Space</u></a></li>
<li><a href="https://win11.techidaily.com/digital-fortifications-essential-tactics-for-access-control/"><u>Digital Fortifications: Essential Tactics for Access Control</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-audio-excellence-with-5-free-windows-apps/"><u>Elevate Audio Excellence with 5 Free Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/essential-4-password-guardians-elevating-windows-11-security/"><u>Essential 4 Password Guardians Elevating Windows 11 Security</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-infinix-note-30-vip-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-go-joystick-on-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Samsung Galaxy F14 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/humor-and-memes-galore-iphones/"><u>Humor & Memes Galore, iPhones</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expert-tips-for-enhancing-your-gopro-cinematic-vision/"><u>In 2024, Expert Tips for Enhancing Your GoPro Cinematic Vision</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-on-iphone-7-plus-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email On iPhone 7 Plus? Heres the Best Fixes</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-full-guide-to-bypass-infinix-note-30i-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Infinix Note 30i FRP</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-open-your-apple-iphone-11-without-a-home-button-by-drfone-ios/"><u>In 2024, How To Open Your Apple iPhone 11 Without a Home Button</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-the-path-to-personalization-adjusting-snapchat-videos-pace/"><u>In 2024, The Path to Personalization  Adjusting Snapchat Videos' Pace</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-vlog-edit-mastery-harnessing-the-power-of-jump-cuts/"><u>In 2024, Vlog Edit Mastery  Harnessing the Power of Jump Cuts</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Vivo V27 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-installation-windows-cab-files-unpacked-and-utilized/"><u>Initiating Installation: Windows CAB Files Unpacked and Utilized</u></a></li>
<li><a href="https://win11.techidaily.com/instant-repair-tactics-for-windows-photo-app-malfunctions/"><u>Instant Repair Tactics for Windows Photo App Malfunctions</u></a></li>
<li><a href="https://win11.techidaily.com/interpreting-drive-labels-the-candd-dynamics/"><u>Interpreting Drive Labels: The C&D Dynamics</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-photo-slideshows-and-spot-corrections-on-win11s-gallery/"><u>Mastering Photo Slideshows & Spot Corrections on Win11's Gallery</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-advanced-audacity-methods-for-high-fidelity-computer-audio-recording-2023-guidebook-for-2024/"><u>New Advanced Audacity Methods for High-Fidelity Computer Audio Recording (2023 Guidebook) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-restricted-administrator-error-in-winsec/"><u>Overcoming Restricted Administrator Error in WinSec</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-code-4-spotify-error-on-w10w11-systems/"><u>Overcoming the Code 4 Spotify Error on W10/W11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/proven-steps-for-clearer-images-using-windows-11s-background-blur-feature-in-the-app/"><u>Proven Steps for Clearer Images Using Windows 11'S Background Blur Feature in the App</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-disregard-must-have-components-issue-in-win10win11/"><u>Quick Guide to Disregard Must-Have Components Issue in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-error-x0001-with-nvidia-experience-w11/"><u>Remedying Error X0001 with Nvidia Experience, W11</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-non-functional-installation-of-ccleaner-on-windows-1011/"><u>Repairing Non-Functional Installation of CCleaner on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/resizing-desktop-picture-summaries-in-win11/"><u>Resizing Desktop Picture Summaries in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-headphone-connection-errors-in-windows-1011/"><u>Resolving Headphone Connection Errors in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-best-video-edits-and-scripting-tools-in-windows-11/"><u>The Ultimate List: Best Video Edits & Scripting Tools in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-the-way-you-use-windows-11s-search-feature/"><u>Transforming the Way You Use Windows 11'S Search Feature</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-alt-codes-in-windows/"><u>Troubleshooting Non-Responsive ALT Codes in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tweaking-the-lockout-threshold-post-failed-access-on-w10w11/"><u>Tweaking the Lockout Threshold Post-Failed Access on W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/1719380495510-unravel-and-solve-your-windows-update-puzzle-fast/"><u>Unravel and Solve Your Windows Update Puzzle Fast</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-6-factors-that-favor-windows-11/"><u>Unraveling 6 Factors That Favor Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-group-policy-settings-an-exploration-in-3-dimensions/"><u>Unraveling Windows Group Policy Settings: An Exploration in 3 Dimensions</u></a></li>
<li><a href="https://win11.techidaily.com/win11-and-ad-ds-strategies-for-printer-troubleshooting/"><u>Win11 & AD DS: Strategies for Printer Troubleshooting</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-advanced-taskbar-attachments/"><u>Windows 11: Advanced Taskbar Attachments</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-lan-play-fixes-for-no-connection-woes/"><u>Winning at LAN Play: Fixes for No Connection Woes</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/x-sound-engineer-edition-pc/"><u>X-Sound Engineer Edition - PC</u></a></li>
</ul></div>
