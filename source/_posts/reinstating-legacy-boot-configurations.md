---
title: Reinstating Legacy Boot Configurations
date: 2024-06-25T09:44:57.442Z
updated: 2024-06-26T09:44:57.442Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Legacy Boot Configurations
excerpt: This Article Describes Reinstating Legacy Boot Configurations
keywords: Legacy BIOS Setup,Boot Configuration Restore,System Boot Legacy,Re-Enable Old Boots,Revive Legacy Boot,Backup Boot Configs,Legacy Boot Management
thumbnail: https://thmb.techidaily.com/67c52f8f8d1e1c526acfd18d30076a8ec8c694652a5ccde76155c26629dae8fb.png
---

## Reinstating Legacy Boot Configurations

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
<li><a href="https://win11.techidaily.com/defeating-inaccessible-program-uninstall-in-microsofts-latest-os/"><u>Defeating Inaccessible Program Uninstall in Microsoft's Latest OS</u></a></li>
<li><a href="https://win11.techidaily.com/low-memory-high-performance-comparing-best-windows-browsers/"><u>Low-Memory, High Performance: Comparing Best Windows Browsers</u></a></li>
<li><a href="https://win11.techidaily.com/discuss-the-limits-of-cultural-relativism-when-might-it-be-challenging-or-problematic-to-apply/"><u>Discuss the Limits of Cultural Relativism: When Might It Be Challenging or Problematic to Apply?</u></a></li>
<li><a href="https://win11.techidaily.com/color-confusion-correcting-windows-desktop-hues-quickly/"><u>Color Confusion? Correcting Windows Desktop Hues Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-a-strategy-to-resolve-locked-windows-update/"><u>Unveiling a Strategy to Resolve Locked Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secrets-of-ftdibussys-and-windows-memory-standards/"><u>Unlocking the Secrets of ftdibus.sys & Windows Memory Standards</u></a></li>
<li><a href="https://win11.techidaily.com/from-browsers-to-desktops-website-conversion-guide/"><u>From Browsers to Desktops: Website Conversion Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-recover-from-the-service-did-not-respond-windows-error-1053/"><u>How to Recover From The Service Did Not Respond Windows Error 1053</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-things-you-should-know-when-unlocking-total-wireless-of-iphone-6s-drfone-by-drfone-ios/"><u>In 2024, Things You Should Know When Unlocking Total Wireless Of iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-the-key-to-successful-large-scale-instagram-videos/"><u>2024 Approved  The Key to Successful Large-Scale Instagram Videos</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-triple-thrills-novel-bio-techniques-and-engaging-formats-to-boost-your-tiktok-filmora-following/"><u>[Updated] Triple Thrills  Novel Bio Techniques and Engaging Formats to Boost Your TikTok-Filmora Following</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-airplane-mode-turn-off-gps-location-on-tecno-camon-30-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does Airplane Mode Turn off GPS Location On Tecno Camon 30 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-narrowing-focus-mac-techniques-for-snapchat-videos-for-2024/"><u>[Updated] Narrowing Focus  Mac Techniques for Snapchat Videos for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-batteries-and-chargers-for-gopro-hero5-official-and-counterfeits/"><u>[New] Top Batteries and Chargers for GoPro Hero5 – Official & Counterfeits</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-samsung-galaxy-m14-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Samsung Galaxy M14 4G | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-iphone-time-lapse-capturing-moments-quickly/"><u>[Updated] IPhone Time-Lapse  Capturing Moments Quickly</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-the-cutting-edge-trendsetters-on-tiktok/"><u>In 2024, The Cutting-Edge Trendsetters on TikTok</u></a></li>
</ul></div>
