---
title: Addressing Plugged Inspection Failure for PC Sound Devices
date: 2024-06-25T11:39:50.880Z
updated: 2024-06-26T11:39:50.880Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Plugged Inspection Failure for PC Sound Devices
excerpt: This Article Describes Addressing Plugged Inspection Failure for PC Sound Devices
keywords: PC Audio Faults,Sound Device Issues,Inspect Pc Sounds,Plug-In Errors PC,PC Audio Checkup,Sound Devices Diagnostics,Inspected PC Audio
thumbnail: https://thmb.techidaily.com/485101ae8f555e145174a15eda6071c25617b2b00c96089d339b8e4537366b75.jpg
---

## Addressing Plugged Inspection Failure for PC Sound Devices

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

 If the troubleshooter left a good impression on you, check out our[guide to every troubleshooter on Windows 11](https://www.makeuseof.com/windows-11-troubleshooters/) for more of them.

## 2\. Perform an Audio Device Driver Rollback

 If a Windows or driver update has messed up your audio device, you can perform a driver rollback to reinstall the last known good driver. You can use the Device Manager to[roll back a driver in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) .

 To roll back an audio device driver, follow our guide on[how to roll back a driver in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) . You'll likely find your audio drivers in the**Sound, video, and game controllers** section of Device Manager.

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

 Alternatively, you can also manually reinstall the existing drivers for your audio device. Check out[how to update Windows, Apps, and drivers](https://www.makeuseof.com/tag/update-windows-software-guide/) for more information.

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
<li><a href="https://win11.techidaily.com/accelerated-startup-launching-windows-and-notebooks-effortlessly/"><u>Accelerated Startup: Launching Windows and Notebooks Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/command-prompt-jamboree-discovering-5-entertaining-techniques/"><u>Command Prompt Jamboree: Discovering 5 Entertaining Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steam-service-failure-in-windows-11/"><u>Troubleshooting Steam Service Failure in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/break-down-drives-hdd-vs-ssd-explained/"><u>Break Down Drives: HDD vs SSD Explained</u></a></li>
<li><a href="https://win11.techidaily.com/key-apps-to-bring-your-windows-pc-and-android-together/"><u>Key Apps to Bring Your Windows PC and Android Together</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-addressing-windows-onedrive-errors-and-restoring-folder-integration/"><u>Quick Guide: Addressing Windows OneDrive Errors and Restoring Folder Integration</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-startup-options-your-ultimate-guidebook/"><u>Decoding Windows Startup Options: Your Ultimate Guidebook</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-6-oddities-in-windows-11-design/"><u>Decoding the 6 Oddities in Windows 11 Design</u></a></li>
<li><a href="https://win11.techidaily.com/quick-access-diskspace-tools-for-windows-context-menu/"><u>Quick Access DiskSpace: Tools for Window's Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/managing-safe-browsing-in-microsofts-win11/"><u>Managing Safe Browsing in Microsoft’s Win11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-unlocking-speech-from-melody-top-3-online-methods-for-mp3-to-text-conversion/"><u>New Unlocking Speech From Melody Top 3 Online Methods for MP3-to-Text Conversion</u></a></li>
<li><a href="https://extra-skills.techidaily.com/inshot-unpacked-editors-edition-detailed-review-for-2024/"><u>InShot Unpacked  Editor's Edition Detailed Review for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-tecno-camon-20-premier-5g-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Tecno Camon 20 Premier 5G Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/superior-stabilized-mounts-for-dslr-and-mobiles/"><u>Superior Stabilized Mounts for DSLR and Mobiles</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-youtube-free-conversion-hack-turn-hd-fb-videos-into-high-res-mp4-for-free/"><u>In 2024, YouTube-Free Conversion Hack  Turn HD FB Videos Into High-Res MP4 For Free</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-vivo-y28-5g-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Vivo Y28 5G phone? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-twitreact-wisdom-a-complete-reference-book-for-2024/"><u>[New] TwitReact Wisdom  A Complete Reference Book for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-premium-sporting-cameras-for-adventure/"><u>2024 Approved  Premium Sporting Cameras for Adventure</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-insearchofimprovedcameratech-beyond-mycam-for-2024/"><u>[New] InSearchOfImprovedCameraTech Beyond MyCam for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-streamline-your-recordings-zooms-leading-transcription-apps-reviewed-for-2024/"><u>[New] Streamline Your Recordings  Zoom's Leading Transcription Apps Reviewed for 2024</u></a></li>
</ul></div>
