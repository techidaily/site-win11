---
title: Fixing Screen Unresponsive Message in Windows 11/11
date: 2024-07-13T10:39:23.099Z
updated: 2024-07-14T10:39:23.099Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Screen Unresponsive Message in Windows 11/11
excerpt: This Article Describes Fixing Screen Unresponsive Message in Windows 11/11
keywords: Windows 11 Responsiveness Fix,Fix Unresponsive Window Error,Resolve MSG Error in Win11,Screen Freeze Issue in Windows 11,Remedy Unresponsive Message,Address Win11 SysMsg Problems,Correcting Disabled Input on Win11
thumbnail: https://thmb.techidaily.com/c89ca4d2db8c8241f93b3a96e44489938109c01f6c557fc5515bb23aae45515d.JPG
---

## Fixing Screen Unresponsive Message in Windows 11/11

 The “display driver failed to start” error message usually appears when you try to launch a game on Windows. The error message appears in the form of a Windows notification above the system tray area. When this error occurs, it causes your screen to go completely black. Sometimes it will recover, but sometimes it will require a hard reset.

 When this error is at its worst, it can prevent you from playing your favorite games. As such, here is how you can fix the “display driver failed to start” error on a Windows 10 or 11 PC.

## 1\. Perform Some Display Driver-Related Fixes

 The error message points to your display driver as the main culprit. As such, before you try anything else, you can try these display driver-related fixes to see if they do the job.

### Roll Back the Latest Graphics Driver Update

![The Roll Back Driver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/roll-back-driver-button.jpg)

 If your graphics card’s driver has recently been updated, try rolling back to the old GPU driver. A **Roll Back Driver** option is usually only available for a short time (typically a few days) after updating a driver. Check out our guide to [rolling back drivers in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) for further details about how to apply this potential resolution.

### Install the Latest Driver for Your PC’s Graphics Card

 People plagued with this error message have confirmed that updating your graphics drivers is a good solution for the “display driver failed to start” error. And while Windows usually handles driver updates through Windows Update, it sometimes won't update NVIDIA and AMD GPU drivers.

 You can update your graphics card’s driver yourself with the methods discussed in our guide to [updating GPU drivers on Windows](http://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

### Reinstall Your Graphics Driver

 If your PC’s GPU already has the newest graphics driver available, consider reinstalling the graphics driver. It's best to do a clean install to ensure your GPU's driver is back to its factory defaults.

 Check out [how to cleanly install and reinstall GPU drivers on Windows](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/) for more information.

## 2\. Utilize the Hardware and Devices Troubleshooter

 Windows has a Hardware and Devices troubleshooter that can help resolve the “display driver failed to start” error. This troubleshooting tool is no longer available within Settings or Control Panel, but it is still accessible via Command Prompt.

 You can access and run the Hardware and Devices troubleshooting utility like this:

1. First, locate the Command Prompt by pressing **Win + S**, typing "cmd," and clicking on **Command Prompt**.
2. Enter and execute the Hardware and Devices command:  
`msdt.exe -id DeviceDiagnostic`
3. Click **Next** to start the troubleshooting.  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-and-devices-troubleshooter-troubleshooter-2.jpg)
4. Select **Apply this fix** to rectify any issues Windows finds.

## 3\. Lower the Windows Visual Effect Settings

 Windows has various visual effect settings that can affect performance. Having too many visual effects enabled can potentially cause issues on PCs with more limited GPUs.

 So, it’s recommended to select the "adjust for best performance" mode in the visual effect settings like this:

1. Right-click **Start**, select **Search**, and input "advanced system settings" in the text box.
2. Press the **Settings** button in the **Performance** category.  
![The Advanced tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/advanced-tab-2.jpg)
3. Click the **Adjust for best performance** radio button, which will deselect most if not all of the effect checkboxes.  
![The "adjust for best performance" button selected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adjust-for-best-performance-radio-button.jpg)
4. Select **Apply** to set the new performance settings.
5. Click the Performance Options window’s **OK** button.

## 4\. Edit the GraphicsDrivers Registry Key

 Some users have got the “display driver failed to start” error fixed by editing the GraphicsDriver registry key. This tweaking involves adding a new **TdrDelay** DWORD value to that key for extending Timeout Detection Delay.

 You can edit the GraphicsDriver registry key like this:

1. Open the Run dialog with **Win + R** and enter "regedit".
2. Click **OK** or press **Enter** to open the Registry Editor window.
3. Then enter this GraphicsDrivers key location inside the registry address bar:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\GraphicsDrivers`
4. Right-click **GraphicsDrivers** and select the **New** context menu option.
5. Select **DWORD (32-bit) Value** to add a new entry.  
![The New > DWORD options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dword-32-bit-value-2.jpg)
6. Type **TdrDelay** within the new DWORD’s text box.
7. Double-click the **TdrDelay** DWORD.
8. Input a value of **5** in the data box and select **OK**.  
![The Value data box the TdrDelay](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/value-data-box-2.jpg)
9. Now close the Registry Editor and reboot your PC.

## 5\. Roll Back Windows to a Previous Restore Point

![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-restore-window.jpg)

 If you have System Restore enabled, restoring Windows to an earlier date is worth a try if nothing else has worked so far. Rolling back Windows will undo every system change made after a selected date.

 As such, you can use System Restore to put your PC "back in time" to a moment when the error didn't occur. It does mean you may lose some apps or data, so be sure to back up anything you want to keep.

 Our guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) provides step-by-step instructions for how to roll back Windows 10 and 11\. Select a restore point date created before you needed to fix the “display driver failed to start” error.

 If this fixes the problem, be careful when re-installing the apps and drivers that got wiped during the restore. If you do, keep tabs on what you reinstalled and when. If the "display driver failed to start" error resurfaces, uninstall everything you recently reinstalled.

## 6\. Perform a Windows Factory Reset

 If System Restore is not an option or it doesn't resolve the issue, you can try a factory reset as the last resort. Performing a factory reset will likely fix the “display driver failed to start” error. However, factory resetting a PC deletes all the apps that weren't pre-installed with Windows. So, be prepared to reinstall all third-party apps you installed yourself.

![The Keep my Files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/keep-my-files-option.jpg)

 You can apply a factory reset with the Reset this PC utility. That tool includes a **Keep my files** option you can select to keep files in your user folders (Documents, Pictures, Videos, etc). Our guide for [factory resetting Windows 10 and 11](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer) provides details on how to access and utilize that tool.

## Enjoy Your Windows Gaming Again

 Applying those potential solutions will almost certainly be enough to fix the “display driver failed to start” error in most cases. However, you may need to try applying more than one of them to find one that works on your PC. Then you can get back to playing all your favorite Windows games again without further issues.

 When this error is at its worst, it can prevent you from playing your favorite games. As such, here is how you can fix the “display driver failed to start” error on a Windows 10 or 11 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-approaches.techidaily.com/new-masterclass-in-virtual-reality-critical-oculus-player-insights/"><u>[New] Masterclass in Virtual Reality  Critical Oculus Player Insights</u></a></li>
<li><a href="https://extra-hints.techidaily.com/exclusive-roundup-high-quality-zero-price-livestream-software-list/"><u>Exclusive Roundup  High-Quality, Zero-Price LiveStream Software List</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-youthful-wealth-wonders-a-look-at-ryans-online-riches/"><u>[Updated] 2024 Approved  Youthful Wealth Wonders  A Look at Ryan's Online Riches</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-to-apple-iphone-14-pro-drfone-by-drfone-ios/"><u>In 2024, How to Mirror PC to Apple iPhone 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-processor-limits-in-power-options-menu/"><u>Demystifying Processor Limits in Power Options Menu</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-failure-codes-0x80072f8f/"><u>Addressing Windows Failure Codes: 0X80072f8f</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-excessive-use-of-windows-module-installer/"><u>Overcoming Excessive Use of Windows Module Installer</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-failed-driver-loading-issues-in-the-latest-os/"><u>Overcoming Failed Driver Loading Issues in the Latest OS</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-screenmaster-mastering-window-recordings-on-spring/"><u>[Updated] In 2024, ScreenMaster  Mastering Window Recordings on Spring</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-workflow-with-top-windows-to-do-apps/"><u>Enhance Your Workflow with Top Windows To-Do Apps</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-hunt-down-gamers-a-steams-journey/"><u>How to Hunt Down Gamers: A Steam's Journey</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-synapse-glitches-on-w11-and-w10/"><u>How to Mend Synapse Glitches on W11 and W10</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-resolving-non-operational-wsresetexe-in-windows/"><u>Troubleshooting: Resolving Non-Operational WSReset.exe in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-disruptive-discord-js-error-in-windows-environments/"><u>Overcoming Disruptive Discord JS Error in Windows Environments</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-no-smudges-on-screens-keeping-your-gopro-crisp/"><u>[Updated] No Smudges on Screens  Keeping Your GoPro Crisp</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-driving-engagement-and-returns-animated-advertising-on-facebook/"><u>[Updated] 2024 Approved  Driving Engagement and Returns  Animated Advertising on Facebook</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Samsung Galaxy A54 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-overlooked-windows-extras-a-step-by-step-manual/"><u>Enabling Overlooked Windows Extras: A Step-by-Step Manual</u></a></li>
<li><a href="https://win11.techidaily.com/1719352195023-quick-fixes-for-your-windows-hurdles-and-complications/"><u>Quick Fixes for Your Windows Hurdles & Complications</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-melodies-for-success-best-top-10-music-for-podcast-startups/"><u>In 2024, Melodies for Success  Best Top 10 Music for Podcast Startups</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-xiaomi-13t-drfone-by-drfone-virtual-android/"><u>How can I get more stardust in pokemon go On Xiaomi 13T? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-non-persistent-nvidia-panel-changes/"><u>Correcting Non-Persistent Nvidia Panel Changes</u></a></li>
<li><a href="https://win11.techidaily.com/winning-smoothly-eradicate-lags-from-star-wars-bf2-on-pc/"><u>Winning Smoothly: Eradicate Lags From Star Wars BF2 on PC</u></a></li>
<li><a href="https://win11.techidaily.com/windows-basics-easy-access-aids-for-novices/"><u>Windows Basics: Easy-Access Aids for Novices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-invalid-profile-on-windows-11-systems/"><u>How to Tackle 'Invalid Profile' On Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-mending-the-internal-error-in-rdp-on-windows-11-and-11-pro/"><u>Guide to Mending the Internal Error in RDP on Windows 11 & 11 Pro</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-mastering-reverse-image-scanning-on-instagram-photos/"><u>[New] 2024 Approved  Mastering Reverse Image Scanning on Instagram Photos</u></a></li>
<li><a href="https://win11.techidaily.com/circumvent-unauthorized-windows-login-errors-easy-guide/"><u>Circumvent Unauthorized Windows Login Errors (Easy Guide)</u></a></li>
<li><a href="https://win11.techidaily.com/opening-editing-and-personalizing-your-win11-fax-cover-page/"><u>Opening, Editing & Personalizing Your Win11 Fax Cover Page</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-pinnacle-5-iphone-apps-for-auditory-escapades/"><u>In 2024, Pinnacle 5 iPhone Apps for Auditory Escapades</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-insufficient-ram-warning-for-hogwarts-simulator/"><u>Fixing Insufficient RAM Warning for Hogwarts Simulator</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-optimal-programs-making-movies-from-picture-files/"><u>In 2024, Optimal Programs  Making Movies From Picture Files</u></a></li>
<li><a href="https://win11.techidaily.com/guide-accessing-and-opening-verifier-manager-w11/"><u>Guide: Accessing and Opening Verifier Manager W11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-unterminated-process-failures-in-windows/"><u>How to Resolve Unterminated Process Failures in Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-stepwise-instructions-preserve-your-memories-by-uploading-to-snapchat/"><u>[New] Stepwise Instructions  Preserve Your Memories by Uploading to Snapchat</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-the-complete-guide-to-designing-personalized-instagram-ringtone/"><u>In 2024, The Complete Guide to Designing Personalized Instagram Ringtone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-vpn-network-disconnection-on-a-remote-work-pc/"><u>Fixing VPN Network Disconnection on a Remote Work PC</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-building-relationships-one-post-at-a-time-on-fb/"><u>In 2024, Building Relationships One Post at a Time on FB</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-prior-to-starting-the-window-operating-system-renewal/"><u>Key Steps Prior to Starting the Window Operating System Renewal</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/reel-it-in-techs-video-harvest/"><u>Reel It In  Tech's Video Harvest</u></a></li>
<li><a href="https://extra-information.techidaily.com/android-technique-transpose-digital-media-order-for-2024/"><u>Android Technique  Transpose Digital Media Order for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/troubleshoot-snapchat-camera-zoomed-in-issue/"><u>Troubleshoot Snapchat Camera Zoomed in Issue</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-system-safe-spotting-hidden-threats-in-windows/"><u>Keep Your System Safe: Spotting Hidden Threats in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mending-microsoft-outlook-glitches-on-windows-devices/"><u>Mending Microsoft Outlook Glitches on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-powertoys-reset-on-new-machine/"><u>Navigating PowerToys: Reset on New Machine</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-from-honor-magic-5-pro-by-drfone-android/"><u>How to Bypass FRP from Honor Magic 5 Pro?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-unsung-heroes-of-canvas-open-source-paintings/"><u>2024 Approved  The Unsung Heroes of Canvas  Open-Source Paintings</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-missing-file-updates-error-on-windows-error-code-0x80070003/"><u>Navigating Through Missing File Updates Error on Windows (Error Code: 0X80070003)</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-new-folders-into-explorers-interface/"><u>Incorporating New Folders Into Explorer's Interface</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-restoring-windows-11-search-efficiency/"><u>Essential Tips: Restoring Windows 11 Search Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-11-writable-driver-verifier/"><u>Activating Windows 11' Writable Driver Verifier</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-do-youtube-channels-get-paid-regularly-in-2024/"><u>[Updated] How Do YouTube Channels Get Paid Regularly, In 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-windows-10s-finest-film-and-multimedia-editing-apps-guide-for-2024/"><u>[New] Windows 10'S Finest Film and Multimedia Editing Apps Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-metered-connection-for-wifi-networks-on-win11/"><u>Configuring Metered Connection for Wifi Networks on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-11-and-11-desktop-context-menu-not-working/"><u>How to Fix the Windows 11 & 11 Desktop Context Menu Not Working</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-exclusive-list-best-mac-gif-recorders/"><u>2024 Approved  Exclusive List  Best Mac GIF Recorders</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-effective-streaming-across-platforms-including-facebook-and-twitch/"><u>[Updated] 2024 Approved  Effective Streaming Across Platforms, Including Facebook and Twitch</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-coherencecore-the-innovative-approach-to-synchronized-sound-design-in-adobe-premiere-pro-2023/"><u>2024 Approved CoherenceCore The Innovative Approach to Synchronized Sound Design in Adobe Premiere Pro 2023</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-and-set-up-windows-sandbox-in-windows-11/"><u>How to Enable and Set Up Windows Sandbox in Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/pixel-problems-non-existent-videos-on-a6400-for-2024/"><u>Pixel Problems  Non-Existent Videos on A6400 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/win-friendly-methods-to-resolve-error-1-in-games/"><u>Win-Friendly Methods to Resolve Error 1 in Games</u></a></li>
<li><a href="https://win11.techidaily.com/from-iphone-to-desktop-syncing-ios-calendar-with-windows-1011/"><u>From iPhone to Desktop: Syncing iOS Calendar with Windows 10/11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-the-ultimate-chromebook-video-editors-guide-using-windows-and-mac-apps/"><u>2024 Approved The Ultimate Chromebook Video Editors Guide Using Windows and Mac Apps</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-easily-uninstall-applications-in-win-11/"><u>Breaking Barriers: Easily Uninstall Applications in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-special-traits-of-ai-machines/"><u>Understanding the Special Traits of AI Machines</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-pictolaugh-design-humor-graphics/"><u>[Updated] PictoLaugh  Design Humor Graphics</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/turn-your-meet-webinar-into-an-interactive-participant-showcase-for-2024/"><u>Turn Your Meet Webinar Into an Interactive Participant Showcase for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-update-checks-with-these-9-fixes-on-windows-setup/"><u>Accelerate Update Checks with These 9 Fixes on Windows Setup</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-youtube-to-mp3-conversion-made-easy-top-tools-and-tricks/"><u>Updated 2024 Approved YouTube to MP3 Conversion Made Easy Top Tools and Tricks</u></a></li>
</ul></div>
