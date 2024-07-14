---
title: Clearing Up No Sound on Connected Devices, Windows Edition
date: 2024-07-13T10:20:12.843Z
updated: 2024-07-14T10:20:12.843Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Clearing Up No Sound on Connected Devices, Windows Edition
excerpt: This Article Describes Clearing Up No Sound on Connected Devices, Windows Edition
keywords: No Sound Fix,Silent PCs,Clear Audio Issues,Deafen Windows,Fix Devices Sound,Stop Device Silence,Resume PC Volume
thumbnail: https://thmb.techidaily.com/877cc6ce606cb4f4b4e6d66d093a7f03e00e14887d19a1aafa40b745d8b4ce71.jpg
---

## Clearing Up No Sound on Connected Devices, Windows Edition

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
<li><a href="https://extra-information.techidaily.com/enhancing-video-quality-with-accurate-camera-adjustments/"><u>Enhancing Video Quality with Accurate Camera Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/30-days-in-football-fantasy-how-to-play-ocm-for-no-charge/"><u>30 Days in Football Fantasy: How to Play OCM for No Charge</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/how-i-got-free-after-effects-templates-slideshow-with-simple-trick-for-2024/"><u>How I Got Free After Effects Templates Slideshow with Simple Trick for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-6-proven-ways-to-unlock-vivo-x-flip-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Vivo X Flip Phone When You Forget the Password</u></a></li>
<li><a href="https://win11.techidaily.com/1719325788950-windows-users-create-a-self-hosted-free-chatgpt-copy-with-gpt4all/"><u>Windows Users, Create a Self-Hosted Free ChatGPT Copy with GPT4All.</u></a></li>
<li><a href="https://unlock-android.techidaily.com/best-zte-nubia-z60-ultra-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best ZTE Nubia Z60 Ultra Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprerante-tale-to-transform-your-windows-11-desk/"><u>A Comprerante Tale to Transform Your Windows 11 Desk</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-5-low-cost-pinterest-video-download-software/"><u>2024 Approved  Top 5 Low-Cost Pinterest Video Download Software</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-breaking-down-tseries-income-strategy-on-youtube-platform/"><u>[Updated] 2024 Approved  Breaking Down TSeries' Income Strategy on YouTube Platform</u></a></li>
<li><a href="https://win11.techidaily.com/6-disappearing-windows-traits-explained/"><u>6 Disappearing Windows Traits Explained</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-guide-to-the-windows-startup-settings/"><u>A Complete Guide to the Windows Startup Settings</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-the-top-10-most-accessible-costless-lut-tools-unveiled/"><u>[Updated] In 2024, The Top 10 Most Accessible, Costless LUT Tools Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/a-scholarly-approach-to-embracing-hdr-in-windows-11-workflows/"><u>A Scholarly Approach to Embracing HDR in Windows 11 Workflows</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-check-which-intel-processor-generation-you-have-on-windows/"><u>8 Ways to Check Which Intel Processor Generation You Have on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/7-strong-arguments-against-switching-from-win10-to-win11-immediately/"><u>7 Strong Arguments Against Switching From Win10 to Win11 Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-for-restoring-windows-hello-fingerprint-functionality/"><u>7 Key Steps for Restoring Windows Hello Fingerprint Functionality</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-oppo-a38-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Oppo A38 Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-youtube-ad-elimination-techniques-for-chrome-and-safari-users/"><u>In 2024, YouTube Ad Elimination Techniques for Chrome & Safari Users</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-upgrading-virtualbox-v70-in-win11/"><u>A Beginner's Guide to Upgrading VirtualBox v7.0 in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-create-multiple-folders-at-once-in-windows-11-and-11/"><u>3 Ways to Create Multiple Folders at Once in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-unveiling-affordable-windows-10-mastery/"><u>A Complete Unveiling: Affordable Windows 10 Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/7-expert-moves-for-restoring-the-functionality-of-windows-services-control-panel/"><u>7 Expert Moves for Restoring the Functionality of Windows Services Control Panel</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-contacts-files-from-note-30-pro-by-fonelab-android-recover-contacts/"><u>How To  Restore Missing Contacts Files from Note 30 Pro.</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-reestablishing-connection-with-dormant-obs-camera/"><u>2024 Approved  Reestablishing Connection with Dormant OBS Camera</u></a></li>
<li><a href="https://win11.techidaily.com/8-apps-for-changing-the-createdmodified-date-on-a-file-on-windows/"><u>8 Apps for Changing the Created/Modified Date on a File on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/5-exceptional-windows-compatible-file-sharing-software/"><u>5 Exceptional Windows-Compatible File Sharing Software</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-support-tasks-map-windows-troubleshooting-tools/"><u>Accelerate Support Tasks: Map Windows Troubleshooting Tools</u></a></li>
<li><a href="https://win11.techidaily.com/a-compre-written-by-derek-walsh-phd-dr-jeffrey-l-gardiner-phd-and-david-c-muller-phd-from-their-book-understanding-the-psychology-of-religion-exploring-god-33/"><u>A Compre Written by Derek Walsh, PhD; Dr. Jeffrey L. Gardiner, PhD; and David C. Muller, PhD; From Their Book Understanding the Psychology of Religion: Exploring God Wise</u></a></li>
<li><a href="https://win11.techidaily.com/1719370951528-xbox-not-launching-fix-it-with-these-tips/"><u>Xbox Not Launching? Fix It with These Tips!</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-youtubes-first-visual-hook-creating-personalized-thumbnails/"><u>[New] YouTube's First Visual Hook  Creating Personalized Thumbnails</u></a></li>
<li><a href="https://win11.techidaily.com/1719367274054-overcoming-snip-and-sketchs-screen-shot-limitations-4-essential-fixes/"><u>Overcoming Snip & Sketch's Screen Shot Limitations: 4 Essential Fixes</u></a></li>
</ul></div>
