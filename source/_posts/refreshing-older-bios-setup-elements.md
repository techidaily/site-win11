---
title: Refreshing Older BIOS Setup Elements
date: 2024-06-25T10:02:41.384Z
updated: 2024-06-26T10:02:41.384Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Refreshing Older BIOS Setup Elements
excerpt: This Article Describes Refreshing Older BIOS Setup Elements
keywords: Refresh BIOS Basics,Update BIOS Interface,Modernize BIOS Layout,Revitalize BIOS Settings,Improve BIOS User Experience,Enhance BIOS Navigation,Streamline BIOS Functions
thumbnail: https://thmb.techidaily.com/07ec08194f82a5c0eb7f1dbd160d4285a74e061c99e34448dc11e18d2afb1ddd.png
---

## Refreshing Older BIOS Setup Elements

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
<li><a href="https://win11.techidaily.com/understanding-the-special-traits-of-ai-machines/"><u>Understanding the Special Traits of AI Machines</u></a></li>
<li><a href="https://win11.techidaily.com/the-most-impressive-windows-10-sketch-software-lineup/"><u>The Most Impressive Windows 10 Sketch Software Lineup</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-unrecognized-disk-issue-a-comprehensive-guide-for-windows-11-users/"><u>Understanding 'Unrecognized Disk' Issue: A Comprehensive Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-to-manage-files-and-tabs-windows-11/"><u>Expert Strategies to Manage Files and Tabs (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-freespace-a-comprehensive-windows-approach/"><u>Enhancing FreeSpace: A Comprehensive Windows Approach</u></a></li>
<li><a href="https://win11.techidaily.com/win32keygen-understanding-identifying-and-neutralizing-its-threat-to-windows/"><u>Win32/Keygen: Understanding, Identifying & Neutralizing Its Threat to Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-security-basics-in-windows-11-setup/"><u>Restoring Security Basics in Windows 11 Setup</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-vivo-y36-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Vivo Y36 to Protect Your Individual Information</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-the-top-rated-educational-animation-software-for-schools/"><u>New The Top-Rated Educational Animation Software for Schools</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/use-auto-sync-of-final-cut-pro-to-deal-with-out-of-sync-problem-in-you-video-this-article-shows-you-how-and-more-for-2024/"><u>Use Auto-Sync of Final Cut Pro to Deal with Out of Sync Problem in You Video. This Article Shows You How and More for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-definitive-guide-to-flawless-morphvox-technique/"><u>2024 Approved  The Definitive Guide to Flawless MorphVOX Technique</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/freecam-x-an-in-depth-webcam-capture-analysis-for-2024/"><u>FreeCam X  An In-Depth Webcam Capture Analysis for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-refined-music-mixes-to-amplify-web-videos/"><u>Updated In 2024, Refined Music Mixes to Amplify Web Videos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-pioneers-panoramas-open-for-all/"><u>[Updated] Pioneer's Panoramas  Open for All</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-beginners-guide-to-interpreting-facebook-metrics/"><u>In 2024, Beginner's Guide to Interpreting Facebook Metrics</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-the-metaverse-and-multiplemetaverse-explained-key-contrasts-highlighted-for-2024/"><u>[New] The Metaverse & MultipleMetaverse Explained  Key Contrasts Highlighted for 2024</u></a></li>
</ul></div>
