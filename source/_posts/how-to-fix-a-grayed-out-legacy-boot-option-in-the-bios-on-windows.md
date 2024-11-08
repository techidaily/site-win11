---
title: How to Fix a Grayed-Out Legacy Boot Option in the BIOS on Windows
date: 2024-11-05T23:27:04.906Z
updated: 2024-11-07T21:09:01.705Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix a Grayed-Out Legacy Boot Option in the BIOS on Windows
excerpt: This Article Describes How to Fix a Grayed-Out Legacy Boot Option in the BIOS on Windows
keywords: Legacy BIOS Fix,Boot Menu Repair,Restore Legacy Options,Clearing Boot Issues,Resetting Boot Settings,Update BIOS Firmware,Windows BIOS Troubleshooting
thumbnail: https://thmb.techidaily.com/08c04182a5370a9894bbb7d5aedb620a94eb3a5d17a6c123fae986b1d0cc282e.jpg
---

## How to Fix a Grayed-Out Legacy Boot Option in the BIOS on Windows

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037319/7443" target="_top" id="2037319">
  <img src="//a.impactradius-go.com/display-ad/7443-2037319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Press**F10** to save the changes and disable Secure Boot.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037350/7443" target="_top" id="2037350">
  <img src="//a.impactradius-go.com/display-ad/7443-2037350" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037350/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148771/18498" target="_top" id="2148771">
  <img src="//a.impactradius-go.com/display-ad/18498-2148771" border="0" alt="https://techidaily.com" width="350" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148771/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151866/7443" target="_top" id="2151866">
  <img src="//a.impactradius-go.com/display-ad/7443-2151866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151866/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://digital-screen-recording.techidaily.com/new-complete-evaluation-the-ultimate-test-of-gecata-logging/"><u>[New] Complete Evaluation The Ultimate Test of Gecata Logging</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-visionedit-ace/"><u>[New] VisionEdit Ace</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-film-the-face-of-your-fb-space/"><u>[Updated] Film the Face of Your FB Space</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-unlocking-color-richness-the-role-of-look-up-tables-in-adobe-photos-for-2024/"><u>[Updated] Unlocking Color Richness The Role of Look-Up Tables in Adobe Photos for 2024</u></a></li>
<li><a href="https://iphone-location.techidaily.com/7-fixes-to-no-gps-showing-approximate-location-on-apple-iphone-11-pro-max-waze-drfone-by-drfone-virtual-ios/"><u>7 Fixes to No GPS - Showing Approximate Location on Apple iPhone 11 Pro Max Waze | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/customize-winterral-backdrop/"><u>Customize WinTerral Backdrop</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-another-users-windows-microsoft-error/"><u>Decoding Another User's Windows Microsoft Error</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/1726030662968-dvd-dvd/"><u>DVDヘルスケア : 家庭用DVD修復ガイド - 手軽なレシピ</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-evolution-of-security-shifting-from-pin-to-password-on-windows-11/"><u>Exploring the Evolution of Security: Shifting From PIN to Password on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-tackle-windows-activation-failure-code-0x803f700f/"><u>Guide to Tackle Windows Activation Failure: Code 0X803F700f</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-record-calls-on-windows/"><u>How to Record Calls on Windows</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-network-troubleshooting-a-guide-to-using-tracert-on-windows/"><u>Mastering Network Troubleshooting: A Guide to Using Tracert on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-address-unsuccessful-message-load/"><u>Quick Fixes to Address Unsuccessful Message Load</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-no-typing-from-keyboard-issue/"><u>Resolved: No Typing From Keyboard Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-your-input-not-recognized-by-vlc/"><u>Resolving Windows: Your Input Not Recognized by VLC</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-active-directory-printer-issues-on-modern-oses/"><u>Troubleshooting Active Directory Printer Issues on Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-full-potential-with-elevated-cmd/"><u>Unlock Full Potential with Elevated CMD</u></a></li>
</ul></div>

