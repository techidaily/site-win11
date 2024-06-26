---
title: Overcoming Outdated BOOT Options Gray
date: 2024-06-25T11:44:07.064Z
updated: 2024-06-26T11:44:07.064Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Outdated BOOT Options Gray
excerpt: This Article Describes Overcoming Outdated BOOT Options Gray
keywords: Old BOOT Fixed,Revise Boot Settings,Update Boot Configs,Modernize System BOOT,Resolve Boot Glitches,Enhance BOOT Options,Correct BOOT Errors
thumbnail: https://thmb.techidaily.com/92459487433dd8191ecb6f79f9b025b7d93038fc1418a5a54e50bbd98af412de.jpg
---

## Overcoming Outdated BOOT Options Gray

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

## 1\. Disable Secure Boot to Enable Boot

 Secure Boot is a UEFI feature that protects your computer against malware by allowing only trusted system software to run on your computer. When enabled, it will perform a cryptographic check during the boot process to verify the integrity of the system image.

 However, if you have Secure Boot enabled, it will likely disable Legacy Boot as well. You'll need to[disable Secure Boot in your BIOS utility](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) to fix the issue.

 The below steps to disable Secure Boot are for an HP Pavilion computer. For other systems, refer to your system manual.

To disable secure boot:

1. Click on**Start** and then click on**Power** .
2. Press and hold the**Shift key** and click on**Restart** . Confirm the action if necessary.
3. Release the**Shift** key as the PC shuts down and boot into the**Recovery Menu.**
4. Go to**Troubleshoot** and click on**Advanced options** .
5. Next, click on**UEFI Firmware Settings.**  
![Advanced OptionspUEFI Firmware Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/advanced-optionspuefi-firmware-settings.jpg)

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to[disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

## Restore a Grayed Out Legacy Boot Option in Your BIOS

 You can fix the grayed-out Legacy boot option in BIOS by disabling Secure Boot and Trusted Platform Technology. In addition, disable Standard Standby (S0) to fix the problem.

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
<li><a href="https://win11.techidaily.com/unraveling-windows-error-0x80300024-problems/"><u>Unraveling Windows' Error 0X80300024 Problems</u></a></li>
<li><a href="https://win11.techidaily.com/swift-keystrokes-in-win-os-a-guide-to-eliminate-delay/"><u>Swift Keystrokes in WIN OS: A Guide to Eliminate Delay</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-password-strength-in-windows-11-with-longer-pins/"><u>Enhancing Password Strength in Windows 11 with Longer Pins</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-approach-backing-up-and-restoring-notebooks/"><u>A Practical Approach: Backing Up & Restoring Notebooks</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-gaming-setup-direct-to-windows-ps3-pad/"><u>Seamless Gaming Setup: Direct-to-Windows PS3 Pad</u></a></li>
<li><a href="https://win11.techidaily.com/instant-use-of-snipping-tool-on-modern-windows-os/"><u>Instant Use of Snipping Tool on Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/1719209276170-essential-windows-store-top-10-crucial-apps/"><u>Essential Windows Store: Top 10 Crucial Apps!</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-cpuram-drain-from-consuming-video-content/"><u>Reducing CPU/RAM Drain From Consuming Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/why-gamers-should-trust-windows-vision-and-performance/"><u>Why Gamers Should Trust Windows' Vision and Performance</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-still-using-pattern-locks-with-vivo-v30-pro-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Vivo V30 Pro? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Google Pixel 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/2024-approved-want-to-edit-videos-on-your-iphone-and-android-phones-but-not-know-where-to-start-dont-worry-in-this-article-i-will-show-you-some-of-the-best-/"><u>2024 Approved Want to Edit Videos on Your iPhone and Android Phones, but Not Know Where to Start? Dont Worry, in This Article, I Will Show You some of the Best Video Editing Apps for Mobile</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-top-5-samsung-galaxy-a54-5g-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Samsung Galaxy A54 5G Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-motion-tracking-software-top-picks-for-this-year/"><u>Updated 2024 Approved Motion Tracking Software Top Picks for This Year</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-streamlining-media-edits-storyremix-and-windows-11-photos-integration/"><u>2024 Approved  Streamlining Media Edits  StoryRemix & Windows 11 Photos Integration</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-honor-90-lite-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Honor 90 Lite? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/perfect-your-content-with-vimeo-on-instagram/"><u>Perfect Your Content with Vimeo on Instagram</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-the-ultimate-guide-for-high-quality-movies-on-windowsmac-and-tablets/"><u>[Updated] In 2024, The Ultimate Guide for High-Quality Movies on Windows/Mac & Tablets</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Apple iPhone XR | Dr.fone</u></a></li>
</ul></div>
