---
title: Fixing Grayed BOOT Prompt Issues
date: 2024-11-30T16:04:46.143Z
updated: 2024-12-06T19:08:09.509Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Grayed BOOT Prompt Issues
excerpt: This Article Describes Fixing Grayed BOOT Prompt Issues
keywords: Boot Gray Fix Guide,Restore BOOT Color,Clear Gray Prompt Errors,Remedy BOOT Issue,Ungray BOOT Display,Fixing Grayed BOOT Screen,Revert Boots PROMPT
thumbnail: https://thmb.techidaily.com/f308ec8a50cc9a493046d8e6543aebbcad8cb9f6d5b3eda7f842ca1c1e275bb8.png
---

## Fixing Grayed BOOT Prompt Issues

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Press**F10** to save the changes and disable Secure Boot.

## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ITtcSWvS8bo?si=4M4BfMgaabrW6148" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://some-techniques.techidaily.com/excellent-global-music-livestreams-for-2024/"><u>Excellent Global Music Livestreams for 2024</u></a></li>
<li><a href="https://win-able.techidaily.com/forza-horizon-4-error-de-arranque-soluciones-comprobadas-y-estrategias-preventivas-en-2024/"><u>Forza Horizon 4 Error De Arranque: Soluciones Comprobadas Y Estrategias Preventivas en 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-0x8007045d-error-on-windows-11-or-11/"><u>How to Fix the 0X8007045d Error on Windows 11 or 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-device-not-existing-issues-on-pcs/"><u>How to Rectify Device Not Existing Issues on PCs</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-oneplus-11r-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix OnePlus 11R Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-samsung-galaxy-m34-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Samsung Galaxy M34 to Outlook | Dr.fone</u></a></li>
<li><a href="https://fox-direct.techidaily.com/inspiring-movies-to-ignite-your-inner-strength/"><u>Inspiring Movies to Ignite Your Inner Strength</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/laptop-and-web-navigating-live-video-communication-in-whatsapp-for-2024/"><u>Laptop & Web Navigating Live Video Communication in WhatsApp for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-without-11-strategies-for-sustaining-old-pcs-on-windows-10/"><u>Navigating without 11: Strategies for Sustaining Old PCs on Windows 10</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/one-ear-beats-troubleshoot-guide-for-2024/"><u>One-Ear Beats Troubleshoot Guide for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/premiere-pros-finest-10-text-plans-for-2024/"><u>Premiere Pro's Finest 10 Text Plans for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-online-connection-steam-and-windows-fixed/"><u>Re-Establishing Online Connection: Steam & Windows Fixed</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-xc10100bf-file-playback-error/"><u>Strategies to Address XC10100BF File Playback Error</u></a></li>
<li><a href="https://win11.techidaily.com/windows-through-time-finding-ancient-elements-in-modern-11/"><u>Windows Through Time: Finding Ancient Elements in Modern 11</u></a></li>
</ul></div>

