---
title: Tips to Retrieve Faded BIOS Messages
date: 2024-06-25T11:22:01.201Z
updated: 2024-06-26T11:22:01.201Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips to Retrieve Faded BIOS Messages
excerpt: This Article Describes Tips to Retrieve Faded BIOS Messages
keywords: Revive BIOS Errors,Clearing Faded BIOS,Fix Fading BIOS Message,Restore Hidden BIOS,Recover Lost BIOS Msg,Reset BIOS Display,Reveal BIOS Screen Issues
thumbnail: https://thmb.techidaily.com/1e40e68e85695875cbdf7c309b6e95c0f93def47629f17026d118c0eda7b469c.png
---

## Tips to Retrieve Faded BIOS Messages

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
<li><a href="https://win11.techidaily.com/switching-notepad-to-dark-mode-on-windows-11plus/"><u>Switching Notepad to Dark Mode on Windows 11+</u></a></li>
<li><a href="https://win11.techidaily.com/explaining-and-correcting-the-msvcr110dll-deficit/"><u>Explaining & Correcting the msvcr110.dll Deficit</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11s-program-compatibility-troubleshooter/"><u>Mastering Windows 11'S Program Compatibility Troubleshooter</u></a></li>
<li><a href="https://win11.techidaily.com/from-windows-to-kali-an-installation-journey/"><u>From Windows to Kali: An Installation Journey</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-microsoft-store-crash-0x80073d26/"><u>Strategies to Overcome Microsoft Store Crash: 0X80073D26</u></a></li>
<li><a href="https://win11.techidaily.com/solve-yellow-tint-issue-in-windows-monitorage/"><u>Solve Yellow Tint Issue in Windows Monitorage</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-errors-wows-glitches-in-windows-11/"><u>Navigating Through Errors: WoW's Glitches in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-unseen-initiating-windows-secret-self-profile-editor/"><u>Deciphering the Unseen: Initiating Windows' Secret Self-Profile Editor</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-enhance-your-webcam-recordings-with-mac-tricks/"><u>[New] Enhance Your Webcam Recordings with Mac Tricks</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-v29e-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Vivo V29e Bootloader Easily</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-the-professionals-selection-top-5-drones-ranked-for-2024/"><u>[Updated] The Professionals' Selection  Top 5 Drones Ranked for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-honor-magic-v2-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Honor Magic V2 | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/advanced-protocols-for-adding-melodies-to-instagram-live-streams-for-2024/"><u>Advanced Protocols for Adding Melodies to Instagram Live Streams for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-essential-guide-to-pre-eminent-video-conferencing-tools/"><u>[New] Essential Guide to Pre-Eminent Video Conferencing Tools</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-tailor-your-text-to-voice-top-5-cloud-services-for-chrome-os-sound-transformation/"><u>In 2024, Tailor Your Text to Voice  Top 5 Cloud Services for Chrome OS Sound Transformation</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-from-beginner-to-appreciator-grasping-the-fundamentals-of-jazz/"><u>Updated 2024 Approved From Beginner to Appreciator Grasping the Fundamentals of Jazz</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-beauty-bard-in-depth-gear-and-tutorial-roundups/"><u>The Beauty Bard  In-Depth Gear & Tutorial Roundups</u></a></li>
</ul></div>
