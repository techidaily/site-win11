---
title: Fixing Plugged Inspection Error for Audio Hardware on WinOS
date: 2024-07-13T10:43:32.123Z
updated: 2024-07-14T10:43:32.123Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Plugged Inspection Error for Audio Hardware on WinOS
excerpt: This Article Describes Fixing Plugged Inspection Error for Audio Hardware on WinOS
keywords: WinOS Audio Issue Fix,Windows Sound Hardware Troubleshoot,Audible Inspector Error Resolve,Plugged Inspection Audio WinError,WinOS Audio Diagnostics,Correcting Windows Audio Faults,Inspect Plugin on WinOS
thumbnail: https://thmb.techidaily.com/ddb387910e1ac858898cd3858da4a32a6126aed2333f21b240bf9f3028949436.jpg
---

## Fixing Plugged Inspection Error for Audio Hardware on WinOS

 Sometimes, you may notice a red X on the sound icon on the Windows taskbar. If you hover the cursor over it, it shows a no speaker, or headphones are plugged in error. This error can occur due to issues with the audio driver or Windows audio services.

 To fix the error, run the built-in audio troubleshooter that can find and fix common audio issues with the sound device. If not, you can perform an audio driver rollback or manually reinstall the audio driver to restore your system's audio.

 Here are a few troubleshooting steps to help you fix the no speaker or headphones are plugged in error on Windows.

## 1\. Run the Windows Audio Troubleshooter

 You can troubleshoot sound problems on Windows using the built-in audio troubleshooter. It scans your Windows system for common audio issues and tries to fix them automatically.

To run the troubleshooter:

1. Press**Win + I** to open**Settings** .
2. In the**System** tab, scroll down and click on**Troubleshoot** .
3. Next, click on**Other** **troubleshooters** .  
![Windows 11 troubleshoot other troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-troubleshoot-other-troubleshooter.jpg)
4. Click the**Run** button for**Playing Audio** . It will check your audio service status and prompt you to select your audio device.  
![Windows 11 settings troubleshoot other troubleshooters playing audio run](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-11-settings-troubleshoot-other-troubleshooters-playing-audio-run.jpg)
5. Select your device speaker and click**Next** .
6. Click**NO** ,**Do not open Audio Enhancements** in the**Turn off Sound Effects and Enhancements** dialog.
7. Apply any recommended fixes and check for any improvements.

 If the troubleshooter left a good impression on you, check out our [guide to every troubleshooter on Windows 11](https://www.makeuseof.com/windows-11-troubleshooters/) for more of them.

## 2\. Perform an Audio Device Driver Rollback

 If a Windows or driver update has messed up your audio device, you can perform a driver rollback to reinstall the last known good driver. You can use the Device Manager to [roll back a driver in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) .

 To roll back an audio device driver, follow our guide on [how to roll back a driver in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) . You'll likely find your audio drivers in the**Sound, video, and game controllers** section of Device Manager.

## 3\. Add Network Service and Local Services to the Local Administrator Group

 Another way to fix this error is to add**Network service** and**Local Services** to the Local Administrator Group. Network Service and Local Service are predefined accounts part of the service control manager. Adding these accounts to the Local Administrator Group should help you fix the sound problem on your Windows PC.

 Note that Local Users and Groups is not available on the Windows Home edition. Home users, however, can add Network Service and Local Services to the local administrator group using Command Prompt.

 To add Network Service and Local Services to the Local Administrator Group using Local Users and Groups:

1. Press**Win + X** to open the**WinX** **Menu** .
2. Click on**Computer Management.**
3. In**Computer Management** , click on**Local User and Groups.**  
![computer management windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/computer-management-windows-11.jpg)
4. In the right pane, double-click on**Groups** to view all the local accounts.  
![local users and groups administrator properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/local-users-and-groups-administrator-properties.jpg)
5. Select and right-click on the**Administrators** account and select**Properties** .  
![administrator properties local users and groups](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/administrator-properties-local-users-and-groups.jpg)

1. Click the**Add** button in the**Administrator Properties** dialog.
2. ![administrator properties local users and groups](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/administrator-properties-local-users-and-groups.jpg)
3. Next, type**network service** and click**Check Names** . It should change the object name to**NETWORK SERVICE.**  
![add network service local administrator group](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-network-service-local-administrator-group.jpg)
4. Click**OK** to add network service to the local user group.
5. In the**Administrator Properties** dialog, you'll see**NT Authority\\Network Service added as the member.**
6. Click the**Add** button again and repeat the steps to add**Local Services** to the group as well.
7. Once done, click**Apply** and**OK** to save the changes.

 If you use the Windows Home edition, you can use Command Prompt to add Local Network and Local Services to the local administrator group. Here's how to do it.

![add network service local administrator group command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/add-network-service-local-administrator-group-command-prompt.jpg)

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following to add "local service" to the Local Group Administrator:  
`net localgroup Administrators /add localservice`
4. Next, type the following command to add "network service" to the Local Group Administrator account:  
`net localgroup Administrators /add networkservice`
5. If both the commands are executed successfully, type**exit** and press**Enter** to close Command Prompt.
6. Restart your PC and check if the error is resolved.

## 4\. Uninstall the Audio Device and Driver

 Temporary glitches with the audio device driver can cause this error on Windows. To fix the issue, uninstall the audio device and the associated driver from Device Manager. After the restart, Windows will automatically reinstall the driver to resolve the issue.

To uninstall an audio device:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Device Manager** from the context menu.
3. In Device Manager, expand the**Sound, video, and game controllers** section.
4. Right-click on your audio device, like**Realtek** **Audio** .  
![uninstall audio device device manager 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-audio-device-device-manager-1.jpg)
5. Select**Attempt to remove the driver for this device** option in the**Uninstall Device** dialog.  
![uninstall audio device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-audio-device-device-manager.jpg)
6. Click**Uninstall** to remove the device.
7. Once uninstalled, restart your PC. Windows will automatically install the necessary drivers for your audio device.

 If the issue persists, manually reinstall the audio device driver from the manufacturer.

## 5\. Manually Reinstall the Audio Device Driver

 If the automatic reinstall doesn't work, check if your computer manufacturer or the audio device OEM has a stable driver version available. On a laptop, visit your computer manufacturer's website and download the latest audio drivers. On a desktop, you can download the latest drivers for your sound card from the manufacturer's website.

 Alternatively, you can also manually reinstall the existing drivers for your audio device. Check out [how to update Windows, Apps, and drivers](https://www.makeuseof.com/tag/update-windows-software-guide/) for more information.

 If the issue persists, change the device installation settings and then reinstall the driver. To change device installation settings:

![device installation settings windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/device-installation-settings-windows.jpg)

1. Press the**Win** key, and type**device installation settings.**
2. Next, click on**Change device installation settings** from the search result.
3. Select the**No (your device might not work as expected)** option in the**Device installation settings** dialog.
4. Click**Save Changes** . Click**Yes** if prompted by**User Account Control.**

 With the automatic driver download disabled, reinstall the existing driver to fix the no audio issue.

## Fixing the "No Speaker or Headphones Are Plugged In" Error

 The error often occurs due to a bad driver update. To fix it, you can perform a rollback or manually reinstall the audio device driver. In addition, try to update the audio device driver from the manufacturer's website.


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
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-motorola-edge-40-neo-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve deleted photos on Motorola Edge 40 Neo</u></a></li>
<li><a href="https://win11.techidaily.com/fast-track-windows-11-tackling-lag-and-delay/"><u>Fast-Track Windows 11: Tackling Lag and Delay</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-expert-advice-hassle-free-recordings-with-ios-devices-for-2024/"><u>[Updated] Expert Advice  Hassle-Free Recordings with iOS Devices for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/series-xs-stuck-gaming-nightm-cooked-manual-eject-remedy/"><u>Series X's Stuck Gaming Nightm Cooked! Manual Eject Remedy</u></a></li>
<li><a href="https://win11.techidaily.com/7-obstacles-hindering-windows-11-upgrade-traction/"><u>7 Obstacles Hindering Windows 11 Upgrade Traction</u></a></li>
<li><a href="https://win11.techidaily.com/experience-refined-creativity-with-microsofts-latest-paint-features/"><u>Experience Refined Creativity with Microsoft's Latest Paint Features</u></a></li>
<li><a href="https://win11.techidaily.com/overcome-xbox-app-issues-on-your-windows-system/"><u>Overcome Xbox App Issues on Your Windows System</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-master-the-art-of-budget-friendly-youtubes-intros-and-ends/"><u>[Updated] Master the Art of Budget-Friendly YouTubes Intros and Ends</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-tech-unity-expert-easeus-reviews-for-2024/"><u>[Updated] Tech Unity  Expert EaseUS Reviews for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/videotwitter-audible-direct-download/"><u>VideoTwitter Audible  Direct Download</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-accessing-the-fax-editor-in-win11/"><u>Essential Tips: Accessing the Fax Editor in Win11</u></a></li>
<li><a href="https://extra-support.techidaily.com/professional-photography-enhanced-by-top-luts-in-lightroom-for-2024/"><u>Professional Photography Enhanced by Top LUTs in LightRoom for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/discontinuing-instant-recording-on-quicktime/"><u>Discontinuing Instant Recording on QuickTime</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-steam-cloud-errors-on-windows/"><u>Addressing Steam Cloud Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/beneath-the-surface-steps-to-engage-with-windows-covert-personality-explorer/"><u>Beneath the Surface: Steps to Engage with Windows’ Covert Personality Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-original-directory-display-preferences/"><u>Regaining Original Directory Display Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/moment-update-windows-11-unpacks-future-looking-features/"><u>Moment Update: Windows 11 Unpacks Future-Looking Features</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-your-printer-on-windows-11-step-by-step/"><u>Fixing Your Printer on Windows 11: Step by Step</u></a></li>
<li><a href="https://win11.techidaily.com/minimizing-edges-process-count-in-windows/"><u>Minimizing Edge's Process Count in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-ink-to-paper-translation-selecting-best-windows-tabs/"><u>Ideal Ink-to-Paper Translation: Selecting Best Windows Tabs</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-amateur-to-professional-iphone-filmmaking-8-key-tips/"><u>[Updated] From Amateur to Professional iPhone Filmmaking (8 Key Tips)</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-15-best-youtube-movies-channels-for-you-to-kill-time/"><u>2024 Approved  15 Best YouTube Movies Channels for You to Kill Time</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-uncover-gpo-settings/"><u>Mastering Windows: Uncover GPO Settings</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-lost-data-from-iphone-11-pro-after-ios-update-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Lost Data from iPhone 11 Pro After iOS Update? | Stellar</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oppo-find-x6-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Oppo Find X6 Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://driver-install.techidaily.com/unlocking-hardware-compatibility-with-drivers/"><u>Unlocking Hardware Compatibility with Drivers</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-15-online-here-are-6-easy-ways-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 15 Online? Here are 6 Easy Ways</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-use-of-windows-module-installer-worker/"><u>Decreasing Excessive Use of Windows Module Installer Worker</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-windows-11-start-up-with-these-simple-ideas/"><u>Streamline Windows 11 Start-Up with These Simple Ideas</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missing-action-buttons-on-windows-11-pc/"><u>Overcoming Missing Action Buttons on Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-running-intel-unison-correctly-in-windows-11/"><u>Mastering the Art of Running Intel Unison Correctly in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-photos-from-honor-by-fonelab-android-recover-photos/"><u>How to Rescue Lost Photos from Honor ?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-uninstall-microsoft-edge-from-windows-11/"><u>How to Uninstall Microsoft Edge From Windows 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-about-nubia-red-magic-9-pro-frp-bypass-by-drfone-android/"><u>In 2024, About Nubia Red Magic 9 Pro FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-fall-guys-connection-errors-on-windows/"><u>How to Fix Fall Guys Connection Errors on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/cooler-computing-strategies-for-gamers-systems/"><u>Cooler Computing Strategies for Gamers' Systems</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-apple-id-and-apple-password-from-apple-iphone-8-plus-by-drfone-ios/"><u>In 2024, How to Reset Apple ID and Apple Password From Apple iPhone 8 Plus</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-modify-win11s-network-preferences/"><u>Guide to Modify Win11's Network Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-about-to-expire-message-on-microsoft-os/"><u>Bypassing the About To Expire Message on Microsoft OS</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-shape-the-perception-of-your-digital-dialogue-key-voice-transformation-tools-for-skype-users/"><u>New Shape the Perception of Your Digital Dialogue Key Voice Transformation Tools for Skype Users</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-show-wi-fi-password-on-oppo-find-x7-by-drfone-android/"><u>How to Show Wi-Fi Password on Oppo Find X7</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/navigating-noise-free-auditory-shifts-for-2024/"><u>Navigating Noise-Free Auditory Shifts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-coding-in-windows-a-guide-to-using-microsoft-copilot/"><u>Mastering Coding in Windows: A Guide to Using Microsoft Copilot</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-fuse-sounds-with-slides-a-guide-to-mp3-integration/"><u>[New] Fuse Sounds with Slides  A Guide to MP3 Integration</u></a></li>
<li><a href="https://win11.techidaily.com/combatting-windows-mail-glitches-the-0x80072746-fix-guide/"><u>Combatting Windows Mail Glitches: The 0X80072746 Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-dark-screen-quandary-in-window-8/"><u>Overcoming the Dark Screen Quandary in Window 8</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-security-new-passwords/"><u>Navigating Windows 11 Security: New Passwords</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-exploring-the-functionality-of-vlc-screencaster/"><u>[Updated] Exploring the Functionality of VLC Screencaster</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/tailored-trends-the-pathway-to-a-specialized-youtube-niche/"><u>Tailored Trends  The Pathway to a Specialized Youtube Niche</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-create-epic-lip-syncs-top-rated-apps-for-android-and-ios/"><u>New 2024 Approved Create Epic Lip Syncs Top-Rated Apps for Android and iOS</u></a></li>
<li><a href="https://win11.techidaily.com/1719334729837-fix-unusable-compatibility-center-on-vista7-pcs-fast/"><u>Fix Unusable Compatibility Center on Vista/7 PCs Fast</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-play-mkv-movies-on-redmi-note-12t-pro-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Can I play MKV movies on Redmi Note 12T Pro?</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-tweaking-sound-on-ps5ps4-games/"><u>[New] Tweaking Sound on PS5/PS4 Games</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-mail-readability-removing-html-from-email-text/"><u>Enhancing Windows 11 Mail Readability: Removing HTML From Email Text</u></a></li>
<li><a href="https://win11.techidaily.com/altering-output-displays-in-window-based-os/"><u>Altering Output Displays in Window-Based OS</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-tecno-pova-6-pro-5g-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Tecno Pova 6 Pro 5G Location by Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-digital-age-essential-keys-fan-deal-at-lowest-price-on-windows-11-612lifetime/"><u>Master the Digital Age - Essential Keys Fan Deal at Lowest Price on Windows 11, $6.12/Lifetime</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-bsod-code-0x0000003b-and-troubleshooting-guide/"><u>Navigating Windows BSOD -Code 0X0000003B & Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-tray-interface-with-numeric-and-caps-indicators/"><u>Personalize Tray Interface with Numeric and Caps Indicators</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-top-tier-windows-10-screen-capture-programs-unveiled/"><u>In 2024, Top-Tier Windows 10 Screen Capture Programs Unveiled</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitters-top-picks-most-retweeted-and-binge-watched-series-for-2024/"><u>[Updated] Twitters' Top Picks  Most Retweeted & Binge-Watched Series for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-comedic-edge-how-to-create-viral-video-memes-for-modern-audiences/"><u>[Updated] The Comedic Edge  How to Create Viral Video Memes for Modern Audiences</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-windows-assistance-entry/"><u>Mastering the Art of Windows Assistance Entry</u></a></li>
<li><a href="https://win11.techidaily.com/swift-resolution-to-windows-update-error-code-0xc1900101/"><u>Swift Resolution to Windows Update Error Code 0xC1900101</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/r-growth-strategy-dynamic-description-templates-for-youtube-success-for-2024/"><u>Viewer Growth Strategy  Dynamic Description Templates for YouTube Success for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/darkmodetoggleforwin-basedtexteditor/"><u>DarkModeToggleForWin-basedTextEditor</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-the-complete-lowdown-on-io-image-recording-software/"><u>In 2024, The Complete Lowdown on IO Image Recording Software</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-lava-blaze-curve-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/managing-safe-browsing-in-microsofts-win11/"><u>Managing Safe Browsing in Microsoft’s Win11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/latest-guide-how-to-bypass-vivo-y78-5g-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Vivo Y78 5G FRP Without Computer</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-pro-choice-top-picks-of-10-premium-vimeo-video-download-tools/"><u>2024 Approved  Pro Choice  Top Picks of 10 Premium Vimeo Video Download Tools</u></a></li>
</ul></div>
