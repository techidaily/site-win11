---
title: "Resolving Windows: Speakers Not Detected Issue"
date: 2024-07-13T10:18:43.286Z
updated: 2024-07-14T10:18:43.286Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resolving Windows: Speakers Not Detected Issue"
excerpt: "This Article Describes Resolving Windows: Speakers Not Detected Issue"
keywords: Fix Speaker Detection,Resolve Audio Errors,Unplugged Sound Issue,PC Speaker No Signal,Windows Audible Failure,Detecting USB Speakers,Audio Output Troubleshoot
thumbnail: https://thmb.techidaily.com/94367d0839b4e8bd552f4ff0b46203c6692aa9dd549da1507965a6ba4039d0e6.png
---

## Resolving Windows: Speakers Not Detected Issue

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
<li><a href="https://win11.techidaily.com/a-primer-on-locating-and-navigating-components-management-console/"><u>A Primer on Locating & Navigating Components Management Console</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-the-ultimate-toolwiz-photo-experience-analyzed-2023-for-2024/"><u>[New] The Ultimate Toolwiz Photo Experience, Analyzed 2023 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/7-ultimate-remedies-for-a-disconnected-usb-wi-fi-adapter-in-windows/"><u>7 Ultimate Remedies for a Disconnected USB Wi-Fi Adapter in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/betrayed-by-touch-the-latest-vulnerabilities-in-windows-fingerprint-tech/"><u>Betrayed by Touch: The Latest Vulnerabilities in Windows Fingerprint Tech</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-a-smooth-operational-flow-for-wsl-after-win-11s-installation/"><u>Ensuring a Smooth Operational Flow for WSL After Win 11'S Installation</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-lowering-sounds-strength-progressively-with-lumafusion/"><u>[Updated] Lowering Sounds' Strength Progressively with Lumafusion</u></a></li>
<li><a href="https://fox-info.techidaily.com/essential-tips-for-creating-films-with-movie-maker-in-w11-for-2024/"><u>Essential Tips for Creating Films with Movie Maker in W11 for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-oneplus-nord-ce-3-5gfrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your OnePlus Nord CE 3 5GFRP Lock</u></a></li>
<li><a href="https://win11.techidaily.com/wintime-discrepents-resolved/"><u>WinTime Discrepents Resolved</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-stepwise-strategies-for-enhancing-yt-game-coverage-through-effective-hashing/"><u>[New] Stepwise Strategies for Enhancing YT Game Coverage Through Effective Hashing</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-ultimate-tips-for-instagram-video-reverse-playback/"><u>2024 Approved  Ultimate Tips for Instagram Video Reverse Playback</u></a></li>
<li><a href="https://win11.techidaily.com/basics-on-windows-exepe-files-an-overview/"><u>Basics on Windows EXE/PE Files: An Overview</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-live-sound-excellence-unveiled-our-top-picks-for-streaming-quality/"><u>[New] Live Sound Excellence Unveiled  Our Top Picks for Streaming Quality</u></a></li>
<li><a href="https://win11.techidaily.com/embracing-apples-messaging-on-your-windows-machine/"><u>Embracing Apple's Messaging on Your Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/delving-deep-into-windows-booting-mechanics-and-settings/"><u>Delving Deep Into Windows' Booting Mechanics and Settings</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-systray-information-showcasing-cpu-and-ram-in-ui/"><u>Elevate SysTray Information: Showcasing CPU & RAM in UI</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-a-comprehensive-guide-to-successful-fb-cover-video-strategies/"><u>In 2024, A Comprehensive Guide to Successful FB Cover Video Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/curated-list-best-weather-trackers-for-w10w11/"><u>Curated List: Best Weather Trackers for W10/W11</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-12-impressive-ai-video-ideas-for-creating-engaging-video-content-for-2024/"><u>New 12 Impressive AI Video Ideas for Creating Engaging Video Content for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719817661009-asus-cam-not-working-heres-how-to-fix-it/"><u>Asus Cam Not Working? Here's How To Fix It!</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-maintaining-access-to-your-tiktok-videos-with-tech-tools/"><u>In 2024, Maintaining Access to Your TikTok Videos with Tech Tools</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-tecno-phantom-v-fold-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Tecno Phantom V Fold without Losing Data | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/comparing-local-data-exchange-protocols-google-and-windows-showdown/"><u>Comparing Local Data Exchange Protocols: Google & Windows Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-workflow-microsofts-innovative-ai-integration-for-windows-11-taskbar/"><u>Accelerating Workflow: Microsoft's Innovative AI Integration for Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-workspace-drawing-on-windows-desktop/"><u>Elevate Your Workspace: Drawing on Windows Desktop</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-ideal-6-screen-recorders-for-mac-users-for-2024/"><u>[New] Ideal 6 Screen Recorders for Mac Users for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-discover-the-best-animation-creators-for-every-level-of-expertise-for-2024/"><u>Updated Discover the Best Animation Creators for Every Level of Expertise for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-make-movies-for-free-top-online-video-makers/"><u>New 2024 Approved Make Movies for Free Top Online Video Makers</u></a></li>
<li><a href="https://screen-recording.techidaily.com/capturing-perfect-voices-3-ipad-solutions/"><u>Capturing Perfect Voices  3 iPad Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/easing-windows-safety-blocks-set-by-high-ranking-admins/"><u>Easing Windows Safety Blocks Set By High-Ranking Admins</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-converting-cr2-photos-to-jpeg-format/"><u>Windows Guide: Converting CR2 Photos to JPEG Format</u></a></li>
<li><a href="https://ai-video.techidaily.com/2024-approved-how-to-use-korean-to-english-video-translators-for-creators/"><u>2024 Approved How To Use Korean to English Video Translators for Creators</u></a></li>
<li><a href="https://win11.techidaily.com/concealing-the-windows-11-taskbars-search-icon/"><u>Concealing the Windows 11 Taskbar's Search Icon</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-optimal-strategies-for-editing-and-upgrading-youtube-profiles/"><u>2024 Approved  Optimal Strategies for Editing and Upgrading YouTube Profiles</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-end-non-registered-user-sessions-on-windows-11/"><u>A Step-by-Step Guide to End Non-Registered User Sessions on WIndows 11</u></a></li>
<li><a href="https://win11.techidaily.com/configure-your-windows-11-to-suit-your-auditory-preferences/"><u>Configure Your Windows 11 to Suit Your Auditory Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/3-keyways-to-refresh-file-explorer-in-win1011/"><u>3 Keyways to Refresh File Explorer in WIN10/11</u></a></li>
</ul></div>
