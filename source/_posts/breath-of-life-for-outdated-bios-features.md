---
title: Breath of Life for Outdated BIOS Features
date: 2025-02-13T20:51:38.116Z
updated: 2025-02-15T17:19:23.855Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Breath of Life for Outdated BIOS Features
excerpt: This Article Describes Breath of Life for Outdated BIOS Features
keywords: Outdated BIOS Advantages,Breathe New Life BIOS,Upgrading BIOS Systems,Reviving Old BIOS,Modernize Old BIOS,Enhance BIOS Features,BIOS Lifeline Tech
thumbnail: https://thmb.techidaily.com/8bc720ee0adbf09ae88a648a38e027832e102c5d3884a2078035ea55eb60772c.jpg
---

## Breath of Life for Outdated BIOS Features

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-exclusive-access-to-premium-playlists-on-mobile-devices/"><u>[New] 2024 Approved Exclusive Access to Premium Playlists on Mobile Devices</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-top-picks-for-professional-4k-reflective-tech/"><u>[New] Top Picks for Professional 4K Reflective Tech</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-fixing-face-id-on-iphone-x-a-compreenasome-guide/"><u>2024 Approved Fixing Face ID on iPhone X A Compreenasome Guide</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-the-complete-guide-to-proficient-kinemaster-use-and-top-digital-services/"><u>2024 Approved The Complete Guide to Proficient KineMaster Use and Top Digital Services</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-typical-rainmeter-setbacks-a-step-by-step-approach/"><u>Conquering Typical Rainmeter Setbacks: A Step-by-Step Approach</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/elevate-your-content-strategy-with-social-blade-and-youtube-stats-for-2024/"><u>Elevate Your Content Strategy with Social Blade and YouTube Stats for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-win-11s-dxgi-deletion-hurdles/"><u>Overcoming Win 11'S DXGI Deletion Hurdles</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/practical-methods-for-instagram-story-capture/"><u>Practical Methods for Instagram Story Capture</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solve-iphone-to-apple-watch-cellular-connectivity-problems-easily/"><u>Solve iPhone to Apple Watch Cellular Connectivity Problems Easily</u></a></li>
<li><a href="https://facebook.techidaily.com/step-into-the-future-of-socializing-with-ar-in-messenger/"><u>Step Into the Future of Socializing with AR in Messenger</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-windows-1011s-unable-to-open-share-error/"><u>Steps to Solve Windows 10/11'S Unable to Open Share Error</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-tackle-usb30-device-malfunctions-in-windows/"><u>Steps to Tackle USB3.0 Device Malfunctions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/taking-back-control-with-fresh-windows-11-installation/"><u>Taking Back Control with Fresh Windows 11 Installation</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-shutdown-4-steps-for-windows-firewall/"><u>Unlocking the Shutdown: 4 Steps for Windows' Firewall</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-best-of-the-best-top-10-video-players-for-slow-motion-video/"><u>Updated Best of the Best Top 10 Video Players for Slow Motion Video</u></a></li>
<li><a href="https://win11.techidaily.com/utilizing-rapid-response-feature-windows-11s-qa-tool/"><u>Utilizing Rapid Response Feature: Windows 11'S QA Tool</u></a></li>
</ul></div>

