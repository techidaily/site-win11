---
title: Techniques for Halting Windows Boot Straight Into CMOS Setup
date: 2024-07-13T09:46:38.908Z
updated: 2024-07-14T09:46:38.908Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques for Halting Windows Boot Straight Into CMOS Setup
excerpt: This Article Describes Techniques for Halting Windows Boot Straight Into CMOS Setup
keywords: Stop Windows Boot,CMOS Control Halt,BIOS Prevention,CMOS Lockout,Windows Boot Delay,Secure BIOS,Booting Restriction
thumbnail: https://thmb.techidaily.com/5c5beff306decd9e31c3216a57ffb320c5012e1719fd0426ca459ec8dc06e9a5.jpg
---

## Techniques for Halting Windows Boot Straight Into CMOS Setup

 Does your Windows device keep booting to BIOS every time you restart it? Numerous factors could be responsible for this, such as having the boot key pressed on the keyboard, running outdated BIOS, improperly plugged-in operating system drive, misconfigured boot sequence, or a CMOS battery issue.

 If you have trouble booting the operating system repeatedly and want your device to boot to Windows rather than BIOS, here are a few checks and fixes you can apply.

## 1\. Disconnect Peripherals and Discharge Static Charge

 Disconnecting the peripherals and discharging the static charge has fixed the issue under discussion for some users. Therefore, before you proceed with any other fixes, unplug all peripherals from your device, and press the power button for half a minute to discharge static electricity. After that, reboot your device. If it boots back into BIOS, begin applying the remaining fixes.

## 2\. Perform a Quick Restart From the BIOS

 Although it sounds pretty simple, restarting the computer after saving BIOS settings usually boots a device into Windows, which may help bypass the issue. Therefore, once your device boots into BIOS, do not make any changes; save the changes and exit BIOS. Afterward, your device may restart once and boot directly into Windows this time.

 Even if this workaround works, it isn't a permanent fix, as you will need to restart Windows through BIOS every time you turn it on, which can be annoying. Continue applying the remaining fixes for a permanent solution.

## 3\. Ensure That the Boot Key Isn't Pressed Down

 Booting into BIOS requires users to press a specific key on the keyboard, which is different for nearly every Windows laptop manufacturer. If you're unfamiliar with it, our guide on [how to enter the BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) covers the correct key to enter BIOS on laptops from different manufacturers.

![HyperX Alloy Origins Core Function Keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/02/Alloy-Origins-Core-HyperX-Function-Keys.jpg)

 When this button is pressed, Windows will boot into BIOS instead of the operating system following a turn-on. So, if your device is automatically booting into BIOS, it is possible that this key got stuck while pressed down on the keyboard, telling your PC to boot into BIOS.

 Therefore, make sure the boot key on your keyboard isn't pressed. If there are any dust particles on it, wipe them off and press the key several times to ensure nothing is stuck.

## 4\. Ensure the Drive Containing the Operating System Is Plugged In

 Your device can also boot into BIOS if it does not find a bootable drive containing your operating system. Typically, it happens when your PC's hard drive disconnects or is no longer detected by your device due to a hardware issue.

 Thus, you must ensure that your drive is connected and detectable by your system and that it isn't causing your device to boot into BIOS. Since the BIOS interfaces of most laptops differ between manufacturers, the process to check that varies.

 Users facing this issue on a Dell device should navigate to the **System Information** tab in BIOS and look under **Device Information**.

![Checking the Device Information in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/checking-the-device-information-in-bios-1.jpg)

 If you don't see the drive with your OS installed, ensure it's connected properly. If your drive is connected but not detectable by your device, you should have it inspected to see if there is a hardware problem. However, if the drive containing your operating system is listed there, move on to the next step.

## 5\. Check Your Boot Sequence

 Boot sequence refers to the order in which your device searches for bootable data. It's recommended to keep the device containing your OS at the top of the sequence, especially if you have multiple storage devices connected. With this, your device can quickly find the bootable data and boot your operating system.

 If the drive containing your OS appears connected in the previous step, ensure it comes first in the boot sequence. To check that on a Dell device, select **Boot Sequence** from the left sidebar. After that, choose **Legacy** under **Boot List Option** and make sure your desired drive appears first in the **Boot Sequence**.

![Changing the Boot Mode in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/changing-the-boot-mode-in-bios.jpg)

 If it isn't selected, click on the **arrow button** and move the drive containing your operating system to the top.

![Putting the Drive Containing the OS at Top in Boot Sequence in BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/putting-the-drive-containing-the-os-at-top-in-boot-sequence-in-bios.jpg)

## 6\. Disable Fast Startup

 The Fast Startup feature in Windows hibernates the system and loads the files quicker. In a nutshell, it helps Windows boot faster. Even though it saves users a lot of time and helps them get back to work quickly, it is known to cause annoying issues during bootup. Often, disabling this feature fixes most of these problems.

 If you can boot into Windows from BIOS, our guide on [turning Fast Startup on and off](https://www.makeuseof.com/windows-11-turn-on-or-off-fast-startup/) can help you disable this feature. However, if you are stuck at the BIOS screen and cannot boot into Windows, you can also disable Fast Startup from there. For that, go to your laptop manufacturer's website for instructions on turning off Fast Startup from BIOS.

## 7\. Update the BIOS

 An outdated BIOS can also prevent Windows from booting correctly. It's the most neglected cause of most booting problems. Therefore, to ensure that the issue under discussion is not caused due to an outdated BIOS, you should upgrade it to the latest version.

 So, if you are able to boot to Windows from BIOS but again encounter the issue when restarting, refer to our guide on [how to update your UEFI BIOS in Windows](https://www.makeuseof.com/tag/update-uefi-bios-windows/). If you cannot boot to Windows, you will have to resort to other methods of updating BIOS.

## 8\. Replace or Reinsert the CMOS Battery

![Person tampering with a motherboard.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/09/cmos-battery-explained-featured.jpg)

 The CMOS battery powers the BIOS firmware on the laptop. If you are unable to boot to Windows, a dead CMOS battery could also be to blame. Often, just removing and reinserting the battery fixes the issue; however, it resets a few settings, including the date and time. In case of a dead battery, you may need to replace it.

 If you want to know more about the CMOS battery and how to remove it, refer to our guide on [what a CMOS battery is](https://www.makeuseof.com/what-is-a-cmos-battery-and-how-do-you-remove-one/).

## Don’t Let Your Windows PC Boot to BIOS

 Seeing your device boot directly into BIOS rather than Windows can be extremely frustrating. We hope the above fixes will help you successfully resolve the issue and boot to Windows. If the above fixes don't work, repair or reinstall Windows. If that doesn't work either, the laptop could have a hardware problem, so take it to a technician for inspection.

 If you have trouble booting the operating system repeatedly and want your device to boot to Windows rather than BIOS, here are a few checks and fixes you can apply.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/ed-evaluating-the-financial-returns-for-makers-on-youtube-shorts-for-2024/"><u>[Updated] Evaluating the Financial Returns for Maker's on YouTube Shorts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-prime-audiosubtitle-malfunctions-on-windows-11-systems/"><u>Resolve Prime Audio/Subtitle Malfunctions on Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-missing-window-panes-with-win11-6-tips/"><u>Reclaiming Missing Window Panes with Win11 (6 Tips)</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-the-ultimate-blueprint-for-earning-money-on-tiktok-8-strategies/"><u>[New] In 2024, The Ultimate Blueprint for Earning Money on TikTok (8 Strategies)</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-fixing-unsupported-devices-warning/"><u>Quick Guide: Fixing Unsupported Devices Warning</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/apple-iphone-11-pro-max-asking-for-passcode-after-ios-1714-update-what-to-do-drfone-by-drfone-ios/"><u>Apple iPhone 11 Pro Max Asking for Passcode after iOS 17/14 Update, What to Do? | Dr.fone</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/hannel-makeovers-made-easy-top-10-online-tools-for-artists-for-2024/"><u>[New] Channel Makeovers Made Easy - Top 10 Online Tools for Artists for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-google-nearby-to-link-devices-easily/"><u>Leveraging Google Nearby to Link Devices Easily</u></a></li>
<li><a href="https://win11.techidaily.com/14-unveiling-windows-11-post-update-feature-list/"><u>14 Unveiling Windows 11: Post-Update Feature List</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-n-a-comparative-study-for-it-pros/"><u>Unveiling Windows N: A Comparative Study for IT Pros</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-uncover-the-secrets-to-converting-youtube-videos-to-mp3-with-ease/"><u>New Uncover the Secrets to Converting YouTube Videos to MP3 with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/speeding-up-win11-startup-easy-strategies-to-reduce-delays/"><u>Speeding Up Win11 Startup: Easy Strategies to Reduce Delays</u></a></li>
<li><a href="https://win11.techidaily.com/roblox-error-403-resolving-access-denied-in-win/"><u>Roblox Error 403: Resolving Access Denied in Win</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-windows-1110s-d3d11-gpu-woes-to-fixable-errors/"><u>Simplifying Windows 11/10'S D3D11 GPU Woes to Fixable Errors</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-to-connect-to-a-network/"><u>Navigating Windows to Connect to a Network</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-on-mac-via-parallels/"><u>Mastering Windows 11 on Mac via Parallels</u></a></li>
<li><a href="https://win11.techidaily.com/reverse-windows-update-failure-code-xc004f050/"><u>Reverse Windows Update Failure Code XC004F050</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-decoding-the-best-software-to-perform-audio-time-reversal-a-curated-selection-for-desktop-phone-and-tablet-users-for-2024/"><u>New Decoding the Best Software to Perform Audio Time-Reversal A Curated Selection for Desktop, Phone, and Tablet Users for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reimagining-display-technology-an-in-depth-exploration-of-windows-11s-hdr/"><u>Reimagining Display Technology: An In-Depth Exploration of Windows 11'S HDR</u></a></li>
<li><a href="https://win11.techidaily.com/onedrive-path-alteration-guide-for-windows-11-users/"><u>OneDrive Path Alteration Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-sound-in-obs-studio-resolving-no-audio-on-win-11/"><u>Amplify Sound in OBS Studio - Resolving No Audio on Win 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-march-madness-deal-wondershare-filmora-coupon-code-dont-miss-out/"><u>In 2024, March Madness Deal Wondershare Filmora Coupon Code - Dont Miss Out</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-greyed-out-pin-deletion-in-windows-11-interface/"><u>Resetting Greyed-Out Pin Deletion in Windows 11 Interface</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-alter-mouse-trail-and-size-on-win11/"><u>Step-by-Step: Alter Mouse Trail & Size on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/methodology-for-disabling-onedrive-indicator-in-windows-11/"><u>Methodology for Disabling OneDrive Indicator in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-rejuvenating-stuck-windows-based-itunes/"><u>Strategies for Rejuvenating Stuck Windows-Based iTunes</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-frenetic-frolic-the-ultimate-list-of-wildest-tiktok-games/"><u>[New] In 2024, Frenetic Frolic  The Ultimate List of Wildest TikTok Games</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-no-connection-found-error-in-win/"><u>Steps to Solve No Connection Found Error in WIN</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-pc-mysteries-a-step-by-step-guide-to-error-code-management-in-command-prompt/"><u>Unraveling PC Mysteries: A Step-by-Step Guide to Error Code Management in Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-legacy-boot-configurations/"><u>Reinstating Legacy Boot Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-windows-audioscape-via-driver-update-steps/"><u>Revamping Windows Audioscape via Driver Update Steps</u></a></li>
<li><a href="https://win11.techidaily.com/resurrecting-devices-in-sleep-mode-of-win11-pc/"><u>Resurrecting Devices in Sleep Mode of Win11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-windows-zoom-obstacles-stop-code-1132-issues/"><u>Avoid Windows Zoom Obstacles: Stop Code 1132 Issues</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-innovative-design-and-graphics-free-and-affordable-sources/"><u>[New] Innovative Design and Graphics  Free & Affordable Sources</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-vds-failures-head-on/"><u>Tackling Windows VDS Failures Head-On</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-a-dormant-services-console-a-list-of-7-restoration-techniques/"><u>Reviving a Dormant Services Console: A List of 7 Restoration Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/1719354508470-fix-compatibility-nightmares-in-windows-without-troubleshooting-tools/"><u>Fix Compatibility Nightmares in Windows without Troubleshooting Tools.</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-compatibility-of-brightness-controls-via-fn-key-win-11/"><u>Restoring Compatibility of Brightness Controls via Fn Key Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/investigating-windows-n-editions-for-business-purposes/"><u>Investigating Windows N Editions: For Business Purposes</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-apple-iphone-8-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Apple iPhone 8 Plus? | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-discover-these-27-purely-free-youtube-audio-ripper-tools-for-2024/"><u>[New] Discover These 27 Purely Free YouTube Audio Ripper Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-reviving-copy-paste-feature-across-browsers/"><u>Quick Guide: Reviving Copy-Paste Feature Across Browsers</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-approaches-to-restoring-windows-11-logins/"><u>Masterful Approaches to Restoring Windows 11 Logins</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-vivo-y77t-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-sync-video-elements-to-captivate-instagram-audiences/"><u>[Updated] In 2024, Sync Video Elements to Captivate Instagram Audiences</u></a></li>
<li><a href="https://win11.techidaily.com/three-simplified-steps-for-customizing-win11-ui/"><u>Three Simplified Steps for Customizing Win11 UI</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-navigating-screen-recordings-with-gotomeeting/"><u>2024 Approved  Navigating Screen Recordings with GoToMeeting</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-cheap-traps-the-realities-of-inferior-windows-activation-codes/"><u>Avoid Cheap Traps: The Realities of Inferior Windows Activation Codes</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-android-windows-webcam-transition-techniques/"><u>Seamless Android-Windows Webcam Transition Techniques</u></a></li>
</ul></div>
