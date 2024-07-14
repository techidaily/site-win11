---
title: "Addressing Secure Boot Grayout: Windows BIOS Fix Guide"
date: 2024-07-13T11:20:40.591Z
updated: 2024-07-14T11:20:40.591Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Addressing Secure Boot Grayout: Windows BIOS Fix Guide"
excerpt: "This Article Describes Addressing Secure Boot Grayout: Windows BIOS Fix Guide"
keywords: Secure Boot Resolution,BIOS Security Tips,Guarded Boot Processes,System Boot Safeguards,Windows Boot Integrity,BIOS Update Guide,Fix Grayout Issues
thumbnail: https://thmb.techidaily.com/fa134e33a19af2a6d89131747e3b5172ee7c3295829397bcf7ff50f7e4bad5d7.png
---

## Addressing Secure Boot Grayout: Windows BIOS Fix Guide

 You need a secure boot-compatible computer to install Windows 11\. But there are other reasons to enable secure boot when available. It is a safety standard that prevents malicious codes from running on your PC during boot.

 But what if secure boot option is grayed out in BIOS? This can happen due to incorrect changes to your BIOS settings. You can load the default boot configuration to restore secure boot on Windows. Here is how to troubleshoot and fix the secure boot grayed-out problem in the BIOS.

## 1\. Set Admin Password in BIOS

 You can set an administrator password in BIOS security to prevent unauthorized access to the setup utility. On some computers, you may need to enable an administrator password to enable secure boot.

 To set an administrator password, you need to access the BIOS Security tab. The following steps are for an HP Pavilion laptop. Refer to your manufacturer's manual for other OEM devices.

To set an administrator password in BIOS:

1. Shut down your PC.
2. Press the**Power** to restart and then start pressing the**F10** key to enter BIOS Setup Utility. Other manufacturers like Dell, Asus, and Lenovo use F2 to access the BIOS utility.
3. In the BIOS Setup Utility, use the right and left arrow keys to open the**Security** tab.  
![bios set administrator password 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/bios-set-administrator-password-1.jpg)
4. Next, select**Administrator Password** and press**Enter** . On other computers, you may see the**Set Supervisor Password** option instead.
5. Here, type your new administrator password and then repeat the password in the**Confirm New Password** field.
6. Press**Enter** to save the password.  
![bios set administrator password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/bios-set-administrator-password.jpg)
7. Next, press**F10** to save the changes and exit**BIOS** .
8. Boot into**BIOS** again, and**Secure Boot** should be available for use.

 You can remove the administrator password after enabling Secure Boot. To do this, open the**Security** tab in BIOS and select**Administrator Password** . Next, enter your administrator password, but leave the**Enter New Password** and**Confirm New Password** fields blank. Press**Enter** again to save the changes.

## 2\. Disable Fast Boot in BIOS

 Fast Boot is a UEFI/BIOS feature. When enabled, it skips the check for a USB device, such as a bootable drive to speed up the boot process. However, the same can also prevent you from enabling secure boot in BIOS.

 To fix the issue, boot into the BIOS Setup Utility and disable Fast Boot. This feature may not be available on all computers. If not available, skip to the next solution.

 Note that the fast boot feature is different from Fast Startup. Fast Boot is a BIOS feature, whereas [Fast Startup is a Windows feature to speed up the boot process](https://www.makeuseof.com/what-is-windows-fast-startup-why-disable-it/) .

To disable fast boot in BIOS:

1. Boot into**BIOS**
2. Use the right and left arrow keys to open the**Advanced** tab.
3. Next, select**Boot Options** and press**Enter** .
4. Select**Fast Boot** and set it to**Disabled** .
5. Press**Enter** to save the changes.
6. Press**F10** to save the changes and exit.
7. After the computer restarts, boot into BIOS to see if you can access Secure Boot.

## 3\. Restore the BIOS Security Settings to Factory Defaults

 You can restore BIOS security settings to factory defaults to enable secure boot. If you have made major changes to the BIOS security settings, a reset will remove the custom configuration and restore the factory default security settings. Most BIOS utilities allow you to perform a restore in the BIOS Security tab.

To restore BIOS Security settings to factory defaults:

1. Boot into BIOS.
2. Open the**Security** tab using the arrow keys.
3. Use the down arrow keys and select**Restore Security settings to factory defaults** .  
![restore bios factory settings default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-bios-factory-settings-default.jpg)
4. Read the description in the**Security Feature Reset Request** dialog. Here you'll need to enter a pass code to complete the reset request.
5. So, enter the shown**pass code** and press**Enter** .  
![restore bios factory settings default pass code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-bios-factory-settings-default-pass-code.jpg)
6. Press**F10** to save the changes and exit**BIOS** .
7. Boot into BIOS again and check if the greyed-out secure boot problem is resolved.

## 4\. Update BIOS

![system information bios version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/system-information-bios.jpg)

 If the issue persists, your problem may be due to outdated BIOS firmware. While you don't need to update your system BIOS as frequently, the newer version tends to bring bug fixes, performance improvements, and newer hardware support.

 A BIOS update is recommended if your motherboard or laptop manufacturer recommends it. Any updates will be available via the laptop or motherboard manufacturer's websites.

### Prepare Your Computer for a BIOS Update

 Before you update your BIOS, you'll need to [suspend BitLocker protection](https://www.makeuseof.com/windows-10-disable-or-suspend-bitlocker/) . You may also need to [temporarily turn off Windows Security protection](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and third-party antivirus.

 Next, check your current BIOS version. You don't want to install an older version of BIOS on your computer. So, press the**Win** key, type**system information** , and open the System Information app from the search results. In the System Information dialog, locate and check the**BIOS Version/Date** entry. Note down the BIOS version, for example,**AMI F.27, 3/17/2022** .

 Unlike other driver and software feature updates, updating your BIOS can be tricky. You can update BIOS from within BIOS, where the BIOS Setup Utility can check your laptop manufacturer's website for BIOS updates. This option, however, is not available for all computers.

![HP download bios firmware update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hp-download-bios-firmware-update.jpg)

 Alternatively, you can also manually install BIOS from within Windows. For example, on an HP computer, go to the [HP Drivers page](https://support.hp.com/drivers) . Select your device manually or let the website detect the device for you.

 Next, check for the pending drivers and BIOS updates. If detected, download the HP Notebook System BIOS Update (Intel / AMD Processors). Make sure to compare the version with the version installed on your PC. If same or older, you don't need to update your BIOS.

 To update BIOS, run the firmware file and follow the on-screen instructions. Your computer will restart into the BIOS Update utility. Select**Apply Update Now** and wait for the update to finish installing. Once done, boot into BIOS and check if the Secure Boot option is available. Make sure to enable your antivirus and BitLocker protection again.

## 5\. Load the BIOS Defaults Settings

![load BIOS default settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/load-bios-default-settings.jpg)

 You can restore your BIOS to its factory default settings to fix issues occurring due to corrupt BIOS configuration. While loading the default settings will not affect your data, we recommend you back up any and all the important data on your computer before proceeding with a BIOS reset.

To load BIOS defaults settings:

1. Boot into**BIOS** and open the**Exit** tab.
2. Next, select the**Load Setup Defaults** option and press**Enter** .
3. Select**Yes** and press**Enter** . This will load setup default values for all SETUP items.
4. Select**Save Changes** and**Exit** .
5. Boot into**BIOS** again and check if the secure boot option is restored.

## Fixing the Grayed Out Secure Boot Option in BIOS

 Secure Boot in BIOS is greyed out if the administrator password is not set. In other instances, incorrect BIOS security settings and outdated BIOS can cause the issue. As a last resort, try to restore BIOS settings to factory defaults to restore Secure Boot in BIOS.


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
<li><a href="https://youtube-clips.techidaily.com/updated-channeling-creativity-get-green-screen-tips-from-youtube/"><u>[Updated] Channeling Creativity  Get Green Screen Tips From YouTube</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-seamless-storytelling-top-10-premiere-pro-transition-effects/"><u>2024 Approved Seamless Storytelling Top 10 Premiere Pro Transition Effects</u></a></li>
<li><a href="https://win11.techidaily.com/cease-auditory-gain-on-windows-operating-system/"><u>Cease Auditory Gain on Windows Operating System</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-accurate-mac-location-techniques-in-windows-11/"><u>Expert Insights: Accurate MAC Location Techniques in Windows 11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-mastering-fcp-editing-audio-like-a-pro/"><u>Updated In 2024, Mastering FCP Editing Audio Like a Pro</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-role-and-usage-of-windows-component-services/"><u>Deciphering the Role & Usage of Windows Component Services</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-instant-expertise-changing-photos-to-captivating-youtube-thumbnails/"><u>[New] 2024 Approved  Instant Expertise  Changing Photos to Captivating YouTube Thumbnails</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-parsing-hiccup-code-0xc00ce556/"><u>Correcting Windows Parsing Hiccup Code 0xC00CE556</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Tecno Pop 7 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-out-of-place-window-elements/"><u>Correcting Out-of-Place Window Elements</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-no-server-errors-a-windows-guide-to-apex-success-(156-chars/"><u>Eliminating No-Server Errors: A Windows Guide to Apex Success (<156 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-skip-recurring-enter-credentials-messages/"><u>Techniques to Skip Recurring 'Enter Credentials' Messages</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-why-windows-fails-to-execute-exe-files/"><u>Decoding Why Windows Fails to Execute .exe Files</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-unleash-your-creativity-with-fast-video-editing-tools/"><u>Updated In 2024, Unleash Your Creativity with Fast Video Editing Tools</u></a></li>
<li><a href="https://win11.techidaily.com/visual-clarity-in-note-taking-with-obsidian-design/"><u>Visual Clarity in Note-Taking with Obsidian Design</u></a></li>
<li><a href="https://win11.techidaily.com/discover-your-device-the-ultimate-guide-for-model-names/"><u>Discover Your Device: The Ultimate Guide for Model Names</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-tiktok-to-mp4-mastery-free-watermark-free-extractors-for-2024/"><u>[New] TikTok to MP4 Mastery  Free, Watermark-Free Extractors for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-operation-failed-error-code-0x0000011b/"><u>Tackling Operation Failed Error: Code 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/from-ios-to-desktop-seamless-sync-with-windows-os/"><u>From iOS to Desktop: Seamless Sync with Windows OS</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-nokia-c300-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Nokia C300</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-java-vm-error-on-windows/"><u>Unraveling the Mystery of Java VM Error on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-beast-boosting-fps-in-cs-go/"><u>Unleash the Beast - Boosting FPS in CS Go</u></a></li>
<li><a href="https://win11.techidaily.com/5-simple-ways-to-unlock-startup-repairs-in-windows/"><u>5 Simple Ways to Unlock Startup Repairs in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-pathways-to-windows-performance-details/"><u>Efficient Pathways to Windows Performance Details</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-zero-empty-directories-issue-in-windows-11-and-11/"><u>Tackling the Zero-Empty Directories Issue in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-usage-options-on-windows-11-devices-and-systems/"><u>Streamlining Usage Options on Windows 11 Devices and Systems</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-designs-unleashed-comprehensive-guide-to-animation-suites/"><u>2024 Approved  Innovative Designs Unleashed  Comprehensive Guide to Animation Suites</u></a></li>
<li><a href="https://win11.techidaily.com/clipit-woes-uncover-top-fixes-for-swift-recovery/"><u>ClipIt Woes? Uncover Top Fixes for Swift Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/from-digital-tunes-to-physical-form-transforming-your-mp3s-on-pc-using-imgburn-windows/"><u>From Digital Tunes to Physical Form: Transforming Your MP3s on PC Using ImgBurn (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/windows-filing-mastery-key-principles-max-156/"><u>Windows Filing Mastery: Key Principles (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-app-install-failures-on-microsoft-store/"><u>Correcting App Install Failures on Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-a-strategy-to-resolve-locked-windows-update/"><u>Unveiling a Strategy to Resolve Locked Windows Update</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/shield-against-random-youtube-video-plays-for-2024/"><u>Shield Against Random YouTube Video Plays for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-pinnacle-performance-comparison-hero5-black-and-hero4-silver/"><u>2024 Approved  Pinnacle Performance Comparison  Hero5 Black and Hero4 Silver</u></a></li>
<li><a href="https://win11.techidaily.com/the-unmatched-features-in-windows-10-why-its-superior-to-win11/"><u>The Unmatched Features in Windows 10: Why It's Superior to Win11</u></a></li>
<li><a href="https://win11.techidaily.com/uncluttered-windows-desktop-at-a-glance/"><u>Uncluttered Windows Desktop at a Glance</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-fix-windows-key-problems/"><u>Essential Steps to Fix Windows Key Problems</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-redesigned-windows-11-widget-pickers/"><u>Enabling Redesigned Windows 11 Widget Pickers</u></a></li>
<li><a href="https://win11.techidaily.com/ten-simple-steps-for-fixing-def5-onedrive-woes-on-win11/"><u>Ten Simple Steps for Fixing DEF5: OneDrive Woes on Win11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-elevate-your-igtv-status-strategies-for-viewership-surge/"><u>2024 Approved  Elevate Your IGTV Status  Strategies for Viewership Surge</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-hidden-login-screens-in-windows-11/"><u>Eradicating Hidden Login Screens in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-audio-access-failures-in-audacity/"><u>Troubleshooting Audio Access Failures in Audacity</u></a></li>
</ul></div>
