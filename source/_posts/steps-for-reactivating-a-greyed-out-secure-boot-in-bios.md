---
title: Steps for Reactivating a Greyed Out Secure Boot in BIOS
date: 2024-07-29T15:45:43.624Z
updated: 2024-07-30T15:45:43.624Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps for Reactivating a Greyed Out Secure Boot in BIOS
excerpt: This Article Describes Steps for Reactivating a Greyed Out Secure Boot in BIOS
keywords: Reactive Secure Boot BIOS,Reviving Secure Boot Setup,Resetting Secure Boot Status,Fixing Booted Security Issue,Secure Boot Restoration Steps,Reinstating Secure Boot Function,Enable Secure Boot in BIOS
thumbnail: https://thmb.techidaily.com/1a06e5fd0d5cec8ff438d2d94c98e453ecdfe96f957771d6cb6ed139269884f8.jpg
---

## Steps for Reactivating a Greyed Out Secure Boot in BIOS

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Restore the BIOS Security Settings to Factory Defaults

 You can restore BIOS security settings to factory defaults to enable secure boot. If you have made major changes to the BIOS security settings, a reset will remove the custom configuration and restore the factory default security settings. Most BIOS utilities allow you to perform a restore in the BIOS Security tab.

To restore BIOS Security settings to factory defaults:

1. Boot into BIOS.
2. Open the**Security** tab using the arrow keys.
3. Use the down arrow keys and select**Restore Security settings to factory defaults** .  
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![restore bios factory settings default](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-bios-factory-settings-default.jpg)
4. Read the description in the**Security Feature Reset Request** dialog. Here you'll need to enter a pass code to complete the reset request.
5. So, enter the shown**pass code** and press**Enter** .  
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
![restore bios factory settings default pass code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/restore-bios-factory-settings-default-pass-code.jpg)
6. Press**F10** to save the changes and exit**BIOS** .
7. Boot into BIOS again and check if the greyed-out secure boot problem is resolved.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
## 4\. Update BIOS

![system information bios version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/system-information-bios.jpg)

 If the issue persists, your problem may be due to outdated BIOS firmware. While you don't need to update your system BIOS as frequently, the newer version tends to bring bug fixes, performance improvements, and newer hardware support.

 A BIOS update is recommended if your motherboard or laptop manufacturer recommends it. Any updates will be available via the laptop or motherboard manufacturer's websites.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
### Prepare Your Computer for a BIOS Update

 Before you update your BIOS, you'll need to [suspend BitLocker protection](https://www.makeuseof.com/windows-10-disable-or-suspend-bitlocker/) . You may also need to [temporarily turn off Windows Security protection](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and third-party antivirus.

 Next, check your current BIOS version. You don't want to install an older version of BIOS on your computer. So, press the**Win** key, type**system information** , and open the System Information app from the search results. In the System Information dialog, locate and check the**BIOS Version/Date** entry. Note down the BIOS version, for example,**AMI F.27, 3/17/2022** .

 Unlike other driver and software feature updates, updating your BIOS can be tricky. You can update BIOS from within BIOS, where the BIOS Setup Utility can check your laptop manufacturer's website for BIOS updates. This option, however, is not available for all computers.

![HP download bios firmware update](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hp-download-bios-firmware-update.jpg)

 Alternatively, you can also manually install BIOS from within Windows. For example, on an HP computer, go to the [HP Drivers page](https://support.hp.com/drivers) . Select your device manually or let the website detect the device for you.

 Next, check for the pending drivers and BIOS updates. If detected, download the HP Notebook System BIOS Update (Intel / AMD Processors). Make sure to compare the version with the version installed on your PC. If same or older, you don't need to update your BIOS.

 To update BIOS, run the firmware file and follow the on-screen instructions. Your computer will restart into the BIOS Update utility. Select**Apply Update Now** and wait for the update to finish installing. Once done, boot into BIOS and check if the Secure Boot option is available. Make sure to enable your antivirus and BitLocker protection again.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-adept-vlc-playback-and-capture-techniques-for-2024/"><u>[New] Adept VLC Playback & Capture Techniques for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-audience-acclaim-index-worlds-most-engaged-youtubers-for-2024/"><u>[New] Audience Acclaim Index  World's Most Engaged YouTubers for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-what-lies-beneath-the-core-of-asmr-videos/"><u>[New] In 2024, What Lies Beneath  The Core of ASMR Videos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-metaviews-analyzing-6-in-depth-metaverse-scenarios/"><u>[New] Metaviews  Analyzing 6 In-Depth Metaverse Scenarios</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-super-camcorders-ranking-15-best-on-the-market/"><u>[New] Super Camcorders Ranking  #15 Best on the Market</u></a></li>
<li><a href="https://youtube-data.techidaily.com/op-10-network-for-entrepreneurs-how-they-conquered-channels/"><u>[New] Top 10 Network for Entrepreneurs  How They Conquered Channels</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-eliminate-youtube-short-headaches-with-these-tips/"><u>[Updated] 2024 Approved  Eliminate YouTube Short Headaches with These Tips</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-top-10-instagram-tags-for-maximum-engagement-right-now/"><u>[Updated] 2024 Approved  Top 10 Instagram Tags for Maximum Engagement Right Now</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-balancing-act-a-comprehensive-guide-to-drone-gimbals/"><u>[Updated] Balancing Act  A Comprehensive Guide to Drone Gimbals</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-facesave-quickly-grab-facebook-media-for-2024/"><u>[Updated] FaceSave  Quickly Grab Facebook Media for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-unveiling-the-potential-of-magix-music-maker-2024/"><u>[Updated] Unveiling the Potential of Magix Music Maker 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-fine-tuning-your-linkedin-headline/"><u>2024 Approved  Fine-Tuning Your LinkedIn Headline</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-gratis-android-capture-free-your-devices-potential/"><u>2024 Approved  Gratis Android Capture  Free Your Device's Potential</u></a></li>
<li><a href="https://win11.techidaily.com/5-effective-strategies-to-fix-rpc-issues-in-win/"><u>5 Effective Strategies to Fix RPC Issues in Win</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/android-and-ios-leading-titles-mimicking-playstation-games-for-2024/"><u>Android & iOS  Leading Titles Mimicking PlayStation Games for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/antimalware-resource-hog-turn-it-off-for-better-performance/"><u>Antimalware Resource Hog: Turn It Off for Better Performance</u></a></li>
<li><a href="https://win11.techidaily.com/breathing-life-into-your-windows-11-screen/"><u>Breathing Life Into Your Windows 11 Screen</u></a></li>
<li><a href="https://extra-hints.techidaily.com/comprehensive-strategies-for-windows-media-players-audio-operations-for-2024/"><u>Comprehensive Strategies for Windows Media Player's Audio Operations for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-rectifying-webcam-error-code-a00f4289-on-windows-11/"><u>Deciphering and Rectifying Webcam Error Code A00F4289 on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-windows-program-format-pe/"><u>Demystifying Windows Program Format (PE)</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-accessing-cloud-drives-from-windows-drive-letters/"><u>Effortlessly Accessing Cloud Drives: From Windows Drive Letters</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-windows-11s-voice-recorder-usability-via-shortcut-guide/"><u>Elevating Windows 11'S Voice Recorder Usability via Shortcut Guide</u></a></li>
<li><a href="https://win11.techidaily.com/1719286727564-gpt4all-for-pcs-local-free-chatgpt-version/"><u>GPT4All for PCs: Local, Free ChatGPT Version</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-hidden-icons-in-windows-11/"><u>Guiding Through Hidden Icons in Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-realme-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Realme Phone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-autonomous-command-line-openings/"><u>How to Disable Autonomous Command Line Openings</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-get-the-apple-id-verification-code-from-apple-iphone-13-in-the-best-ways-by-drfone-ios/"><u>How To Get the Apple ID Verification Code From Apple iPhone 13 in the Best Ways</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-the-absence-of-dxgidll-in-windows-11/"><u>How to Rectify the Absence of Dxgi.dll in Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-xiaomi-redmi-note-12-4g-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Xiaomi Redmi Note 12 4G</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-bring-your-ideas-to-life-top-free-3d-animation-apps-for-android-and-iphone/"><u>In 2024, Bring Your Ideas to Life Top Free 3D Animation Apps for Android and iPhone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Oppo F23 5G? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unleashing-potential-with-the-q500-drone/"><u>In 2024, Unleashing Potential with the Q500 Drone</u></a></li>
<li><a href="https://win11.techidaily.com/inside-the-windows-world-crafting-and-examining-system-data/"><u>Inside the Windows World: Crafting and Examining System Data</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ipogo-will-be-the-new-ispoofer-on-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Honor Magic 5 Pro? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/is-voice-access-not-working-on-windows-11-heres-how-to-fix-it/"><u>Is Voice Access Not Working on Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-eradicating-predominant-anomalies-with-anydesk-on-windows/"><u>Key Techniques: Eradicating Predominant Anomalies with AnyDesk on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/linux-perfection-bypassing-wsl/"><u>Linux Perfection: Bypassing WSL</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-wsl-registration-failure-with-error-x80370102/"><u>Mastering The Fix: WSL Registration Failure with Error X80370102</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-your-windows-11-top-20-optimizations-guide/"><u>Mastering Your Windows 11: Top 20 Optimizations Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-to-silent-tab-disabling-in-windows-11/"><u>Navigating to Silent Tab Disabling in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-keyboard-method-to-resize-programs/"><u>Navigating Windows 11'S Keyboard Method to Resize Programs</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-step-by-step-tutorial-integrating-songs-into-your-imovie-masterpiece/"><u>New In 2024, Step-by-Step Tutorial Integrating Songs Into Your iMovie Masterpiece</u></a></li>
<li><a href="https://win11.techidaily.com/regain-lost-dxgidll-with-effective-win11-tactics/"><u>Regain Lost Dxgi.dll with Effective Win11 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/review-of-surface-laptop-go-3s-new-cpu-unchanged-shortcomings/"><u>Review of Surface Laptop Go 3'S New CPU - Unchanged Shortcomings</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/see-all-around-the-ultimate-guide-to-11-bridging-cams/"><u>See All Around  The Ultimate Guide to #11 Bridging Cams</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-mouse-click-rate-with-just-a-few-tweaks/"><u>Skyrocket Mouse Click Rate with Just a Few Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/smoothing-out-irregularities-a-guide-to-correction-of-windows-charmap-issues/"><u>Smoothing Out Irregularities: A Guide to Correction of Windows CharMap Issues</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-xbox-game-pass-x8007e9-error-in-windows/"><u>Solutions for Xbox Game Pass X8007E9 Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-users-from-adjusting-windows-time-and-date/"><u>Stopping Users From Adjusting Windows Time and Date</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-new-row-insertion-issues-in-excel-windows/"><u>Strategies for Fixing New Row Insertion Issues in Excel Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-disconnected-remote-resources-in-windows/"><u>Strategies to Address Disconnected Remote Resources in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streaming-windows-network-shares-from-smartphones/"><u>Streaming Windows Network Shares From Smartphones</u></a></li>
<li><a href="https://win11.techidaily.com/the-guide-to-creating-a-unique-terminal-theme/"><u>The Guide to Creating a Unique Terminal Theme</u></a></li>
<li><a href="https://win11.techidaily.com/top-notch-windows-11-skins-no-one-knows/"><u>Top-Notch Windows 11 Skins No One Knows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-freezing-and-black-steam-in-winos/"><u>Troubleshooting Freezing & Black Steam in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-quick-fixes-for-five-common-defender-disruptions/"><u>Troubleshooting Guide: Quick Fixes For Five Common Defender Disruptions</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-approach-to-sound-channel-division/"><u>Understanding Windows’ Approach to Sound Channel Division</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-potential-a-complete-walkthrough-of-wpm-on-windows-os/"><u>Unlock Full Potential: A Complete Walkthrough of WPM on Windows OS</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-nokia-c32-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-np-settings-a-simple-fix-guide/"><u>Windows NP Settings: A Simple Fix Guide</u></a></li>
</ul></div>
