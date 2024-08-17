---
title: How to Fix Windows' This Device Is Being Used by Another Application Audio Error
date: 2024-08-15T23:52:27.325Z
updated: 2024-08-16T23:52:27.325Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix Windows' This Device Is Being Used by Another Application Audio Error
excerpt: This Article Describes How to Fix Windows' This Device Is Being Used by Another Application Audio Error
keywords: Fixing Windows Audio Errors,Resolving Other App Audio Conflict,Removing Windows Audio Issue,Unique App Audio Problem Fix,Clearing Windows Audio Usage,Disabling Concurrent App Audio,Stop Device Occupied by Audio
thumbnail: https://thmb.techidaily.com/bdbc1bb211547c18c849de30d5eb74ca5d67d9e0fc552f041d0a6f6f88d073bb.jpg
---

## How to Fix Windows' This Device Is Being Used by Another Application Audio Error

 The audio device on your Windows computer can simultaneously play audio from multiple sources. However, at times, the audio stops playing with the error "this device is being used by another application".

 This is error is often a case of incorrectly configured Windows Audio service. Other times, the audio issue is due to a corrupt audio device driver. Here we show you how to troubleshoot the "this device is being used by another application" error and restore audio on Windows.

## 1\. Run the Windows Audio Troubleshooter

![Windows 11 settings troubleshoot other troubleshooters playing audio run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-11-settings-troubleshoot-other-troubleshooters-playing-audio-run.jpg)

 Windows has a built-in audio troubleshooter to find and fix issues with playing audio. The troubleshooter looks for common audio issues and tries to fix them automatically.

To run the audio troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, click on**Troubleshoot** .
3. Click on**Other troubleshooters** .
4. Next, click the**Run** button for**Playing Audio** . Wait for the audio troubleshooter to scan for issues. Then select the affected audio device and click**Next** .
5. Follow the on-screen instructions and check if the error is resolved.

## 2\. Disable Exclusive Mode for the Audio Device

 By default, Windows applications can take exclusive control of the audio device. While enabling this option shouldn’t cause any issues, some apps may prevent the device from being used by other audio services. To fix the problem, disable exclusive mode to stop applications from taking exclusive control of the audio device.

To disable Exclusive Mode for the audio device on Windows:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, click on**Sound** .
3. Scroll down and click on**More sound settings** .  
![more sound settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/more-sound-settings-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Select the audio device in the**Sound** dialog and click the**Properties** button.
5. Open the**Advanced** tab in the**Properties** dialog.  
![disable exclusive mode](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-exclusive-mode.jpg)
6. Uncheck the **Allow application to take exclusive control of this device** and**Give exclusive mode application priority** options.
7. Click**Apply** and**OK** to save the changes.

 Restart your computer and check if the error is resolved and if the audio device is working again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Change Windows Audio Service Startup Type

 Windows Audio service is responsible for managing audio devices connected to your computer. If the service is disabled or not running, your audio device can stop working.

 By default, it is set to start automatically as you power on your device. Check if the Startup type for Windows Audio is set to Manually. If yes, reconfigure it to start automatically to fix audio problems.

To change the Windows Audio service Startup type:

1. Press**Win + R** to open**Run** .
2. Type**services.msc** and click**OK** to open the**Services** snap-in.
3. In the**Services** window, locate and double-click on**Windows Audio** service.  
![windows audio service properties services snap in](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service-properties-services-snap-in.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Click the**Startup** type drop-down and select**Automatic** .
5. Click**Apply** and**OK** to save the changes.  
![windows audio service startup type automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-audio-service-startup-type-automatic.jpg)
6. If the service is not running, right-click on**Windows Audio** and select**Start** .
7. Close the Services snap-in and restart your PC. After the restart, your audio device should start working again.

## 4\. Disable and Re-Enable the Sound Output Device

 You can temporarily disable and re-enable the audio device to fix any glitches causing the device to malfunction. You can [disable the audio device](https://www.makeuseof.com/enable-disable-sound-output-devices-in-windows/) using the Settings app and Device Manager.

 To disable the audio device, right-click on the audio device and select**Disable device** in**Device Manager** . Next, right-click on the audio device and**Enable Device** . Close Device Manager and check for any improvements.

## 5\. Uninstall and Reinstall the Audio Device and Driver

![Uninstalling an audio device in Windows 11.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/uninstalling-audio-device-windows-11.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can also troubleshoot your audio problems by uninstalling the audio device and the associated drivers. Reinstalling the audio device can help if the sound problem is due to corrupt audio drivers.

To uninstall your audio device on Windows:

1. Press**Win + X** to open the**WinX menu** .
2. Select**Device Manager** for the menu.
3. In Device Manager, expand the**Audio inputs and output section** .
4. Right-click on your audio device and select**Uninstall device** .
5. Read the warning and click**Uninstall** to confirm the action. Wait for the device to uninstall.

 You may see a yellow exclamation mark on the uninstalled audio device. To reinstall the driver, click on**File** and select**Scan for hardware changes** . This should reinstall the sound device and driver. If not, restart your computer. As the system restarts, Windows will reinstall the missing audio device driver and restore sound on your computer.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 6\. Perform a Driver Rollback

 If you have an external sound card and have installed an update, try a driver rollback. A new driver update can sometimes create more problems than it intends to fix. You can use the device driver rollback feature in Device Manager to undo the changes and reinstall the older version of the driver.

 You can [roll back a driver using Windows Device Manager](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) . In Device Manager, expand the**Sound, Video, and Game Controllers** section. Next, access your external sound card properties to perform a rollback.

 If the Roll Back Driver option is greyed out, it means the option is unavailable for the selected device. In this instance, uninstall the existing audio device driver and download an older version of the driver from your sound card manufacturer's website. Your sound card manufacturer may also have a newer driver version available. If available, install the latest version and check for any improvements.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Install Pending Windows Updates

![windows 11 view update history](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/winodws-11-view-update-history.jpg)

 If it is a Windows-specific issue, installing pending Windows updates can fix the problem. Check the Windows updates page for newer updates and install them to see if that helps resolve the issue.

 To install Windows update, go to**Settings > Windows Update** and click**Check for updates** . Windows will populate the screen with all the pending updates. You can install the updates or selectively install any audio device updates.

## 8\. Check for Third-Party App Conflict

![volume mixer windows 11 view audio applications](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/volume-mixer-windows-11-view-audio-applications.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the issue persists, check if there is a third-party app conflict. You can use Volume Mixer to view applications accessing the audio devices and close the problematic app to fix the problem. Here’s how to do it.

1. Press**Win + R** to open Run.
2. Type**sndvol** and click**OK** to open Volume Mixer.
3. The**Application** column will show all the apps using your audio device.

 To close the app, open the system tray, right-click the app icon, and select**Quit** . You can also force close the app using Task Manager. If the issue persists, uninstall the problematic app to restore the audio to your computer.

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-unleashing-instagrams-filter-power-free-searches-revealed/"><u>[New] 2024 Approved  Unleashing Instagram's Filter Power – Free Searches Revealed</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-direct-video-tweeting-on-phones-avoid-retweets/"><u>[New] In 2024, Direct Video Tweeting on Phones - Avoid Retweets</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-the-complete-gif-makers-manual/"><u>[New] In 2024, The Complete GIF Maker's Manual</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-the-ultimate-strategy-to-turn-your-fb-page-into-cash/"><u>[Updated] 2024 Approved  The Ultimate Strategy to Turn Your FB Page Into Cash</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-becoming-an-expert-at-using-zoom-for-your-windows-pc-win10/"><u>[Updated] Becoming an Expert at Using Zoom for Your Windows PC (Win10)</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-boost-video-influence-techniques-for-exceptional-client-spotlights/"><u>[Updated] Boost Video Influence  Techniques for Exceptional Client Spotlights</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-lenovos-easy-pathway-to-screen-recording-for-2024/"><u>[Updated] Lenovo's Easy Pathway to Screen Recording for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-top-economical-desktop-encoders-under-100/"><u>2024 Approved  Top Economical Desktop Encoders Under $100</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/21-pioneering-metaverse-ventures-for-insightful-discussion/"><u>21 Pioneering Metaverse Ventures for Insightful Discussion</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-honor-90-pro-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-nokia-c02-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Nokia C02 Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/breath-of-life-for-outdated-bios-features/"><u>Breath of Life for Outdated BIOS Features</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-gaps-in-winvpn-fixed-remote-access-errors/"><u>Bridging Gaps in WinVPN: Fixed Remote Access Errors</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-technology-divide-with-winpc-galaxy-flow-link/"><u>Bridging Technology Divide with WinPC-Galaxy Flow Link</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-gap-with-telnet-3-easy-steps-for-wins-users/"><u>Bridging the Gap with Telnet: 3 Easy Steps for Wins Users</u></a></li>
<li><a href="https://win11.techidaily.com/brighten-up-the-grayed-extend-volume-buttons/"><u>Brighten Up the Grayed Extend Volume Buttons</u></a></li>
<li><a href="https://win11.techidaily.com/brightening-up-life-controlling-windows-display-shine/"><u>Brightening Up Life: Controlling Windows Display Shine</u></a></li>
<li><a href="https://win11.techidaily.com/brightening-up-get-rid-of-yellow-on-windows-screens/"><u>Brightening Up: Get Rid of Yellow on Windows Screens</u></a></li>
<li><a href="https://win11.techidaily.com/bring-forlorn-add-ons-back-a-compreenas-seven-points-plan/"><u>Bring Forlorn Add-Ons Back: A Compreenas Seven Points Plan</u></a></li>
<li><a href="https://win11.techidaily.com/bring-life-to-monitors-with-custom-spotlight-backdrops/"><u>Bring Life to Monitors with Custom Spotlight Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/bring-slack-notifications-back-from-the-dead-in-windows-11/"><u>Bring Slack Notifications Back From the Dead in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-forth-hidden-windows-drive/"><u>Bringing Forth Hidden Windows Drive</u></a></li>
<li><a href="https://win11.techidaily.com/brushes-and-pixels-our-top-7-choices-for-sketching-on-win10/"><u>Brushes and Pixels: Our Top 7 Choices for Sketching on Win10</u></a></li>
<li><a href="https://win11.techidaily.com/building-a-win-11-usb-fastest-and-simplest-methods-for-3-ways/"><u>Building a Win 11 USB: Fastest and Simplest Methods for 3 Ways</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-google-chromes-file-transfer-blockade-on-windows/"><u>Bypass Google Chrome's File Transfer Blockade on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-power-management-avoid-hibernation-of-usb-devices/"><u>Bypass Power Management: Avoid Hibernation of USB Devices</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-windows-auto-lock-feature/"><u>Bypass Windows Auto-Lock Feature</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-stranded-status-a-quick-guide-for-xbox-users/"><u>Bypassing ‘Stranded’ Status: A Quick Guide for Xbox Users</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-a-blocked-warcraft-update-process/"><u>Bypassing a Blocked Warcraft Update Process</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-connection-issues-0x00000001-resolution-guide/"><u>Bypassing Connection Issues - 0X00000001 Resolution Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-microsofts-store-crash-code-x800704cf/"><u>Bypassing Microsoft's Store Crash Code X800704CF</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-photocapture-failures-on-windows-11-device/"><u>Bypassing PhotoCapture Failures on Windows 11 Device</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-11-shop-error-code-x800704cf/"><u>Bypassing Windows 11 Shop Error: Code X800704CF</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-11s-operation-failure-error-code-0x0000011b/"><u>Bypassing Windows 11'S Operation Failure (Error Code: 0X0000011B)</u></a></li>
<li><a href="https://win11.techidaily.com/camouflaging-keyboard-actions-on-windows-platforms/"><u>Camouflaging Keyboard Actions on Windows Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/can-pressing-print-screen-start-snip-in-windows-11-block-it/"><u>Can Pressing Print Screen Start Snip in Windows 11? Block It</u></a></li>
<li><a href="https://win11.techidaily.com/changing-default-administrator-in-windows-11-pro/"><u>Changing Default Administrator in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/changing-windows-11-registry-access-settings/"><u>Changing Windows 11 Registry Access Settings</u></a></li>
<li><a href="https://win11.techidaily.com/chronos-remedy-restoring-lost-windows-server-time-functionality/"><u>Chronos' Remedy: Restoring Lost Windows Server Time Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-win11s-security-rufus-techniques/"><u>Circumventing Win11's Security: Rufus Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-windows-restrictions-quickly/"><u>Circumventing Windows Restrictions Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/clear-your-script-crisis-essential-solutions-for-windows-errors/"><u>Clear Your Script Crisis: Essential Solutions for Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-access-denied-errors-fixing-outlook-issues-in-windows-os/"><u>Clearing 'Access Denied' Errors: Fixing Outlook Issues in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-corruption-fix-your-win1011-recycle-error/"><u>Clearing up CORRUPTION! Fix Your WIN10/11 Recycle Error</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-not-written-memory-problems-on-windows/"><u>Clearing Up Not Written Memory Problems on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-the-conflicting-audio-application-problem-in-windows/"><u>Clearing Up the Conflicting Audio Application Problem in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/coherent-windows-icons-for-productivity-boost/"><u>Coherent Windows Icons for Productivity Boost</u></a></li>
<li><a href="https://win11.techidaily.com/combat-code-confusion-skyrim-sse-troubleshoot/"><u>Combat Code Confusion: Skyrim SSE Troubleshoot</u></a></li>
<li><a href="https://location-social.techidaily.com/does-realme-narzo-n53-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Realme Narzo N53 Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>Full Guide to Fix iToolab AnyGO Not Working On Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-from-itel-by-fonelab-android-recover-pictures/"><u>How to recover deleted pictures from Itel .</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-iphone-12-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover iPhone 12 Data From iCloud? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-nokia-g22-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Nokia G22 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-compatible-amd-radeon-drivers-for-windows-7-free-download-and-setup-instructions/"><u>Latest Compatible AMD Radeon Drivers for Windows 7: Free Download and Setup Instructions</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-master-video-editing-on-mac-with-mkvtoolnix-a-step-by-step-guide-2023/"><u>New Master Video Editing on Mac with MKVtoolnix A Step-by-Step Guide 2023</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-vivo-v29e-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Vivo V29e? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/reddit-poster-canvas-ratio-for-2024/"><u>Reddit Poster Canvas Ratio for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unleash-creativity-with-our-top-picks/"><u>Unleash Creativity with Our Top Picks:</u></a></li>
<li><a href="https://video-capture.techidaily.com/unlock-device-agnostic-techniques-for-professional-filming/"><u>Unlock Device-Agnostic Techniques for Professional Filming</u></a></li>
<li><a href="https://ai-voice.techidaily.com/updated-2024-approved-top-5-quandale-dingle-voice-generators/"><u>Updated 2024 Approved Top 5 Quandale Dingle Voice Generators</u></a></li>
</ul></div>
