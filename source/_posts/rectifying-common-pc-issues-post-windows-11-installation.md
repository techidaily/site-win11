---
title: Rectifying Common PC Issues Post-Windows 11 Installation
date: 2024-09-18T21:11:53.014Z
updated: 2024-09-22T10:31:32.050Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Rectifying Common PC Issues Post-Windows 11 Installation
excerpt: This Article Describes Rectifying Common PC Issues Post-Windows 11 Installation
keywords: Windows 11 Troubleshooting,PC Repair Tips,Fixing Win11 Errors,Bootloader Problems,Update Issues Resolved,System Restore Post-Win11,Win11 Installation Hacks
thumbnail: https://thmb.techidaily.com/3b1acf72418bcbc32cbafc2ecf801ef760b09fcf6908ac7624af651ae9d18172.jpg
---

## Rectifying Common PC Issues Post-Windows 11 Installation

 Microsoft Windows 11 is here, and you can use the company's PC Health Check app to check if your PC meets the minimum system requirements to install Windows 11\. Unfortunately, for many users, running the PC Health Check app returns the This PC can't Run Windows 11 error.

 You will most likely encounter this error if the app detects your system hardware incompatible with Windows 11\. Fortunately, there are workarounds to get around this annoying error that may prevent you from upgrading to Windows 11 successfully.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the Windows 11 Upgrade Error Message?

The full error message reads:

 "This PC can't run Windows 11—While this PC doesn't meet the system requirements to run Windows 11, you'll keep getting Windows 10 updates"

Additionally, you may also see the following error:

* This PC must support TMP 1.2/2.0.
* This PC must support Secure Boot.

 If you are experiencing similar errors, it is possible that your PC doesn't have the minimum system requirements to run Windows 11\. That said, the error can be a false flag as well as it will not detect a Secure Boot and TMP 2.0-supported systems if the features are disabled in BIOS.

## What Are the System Requirements to Install Windows 11?

 Interestingly, the official[Windows 11 system requirements](https://www.makeuseof.com/can-your-pc-run-windows-11/) aren't the most intensive, and most modern systems should support it out of the box. However, there are some upgrades from Windows 10.

 The following are the system requirements to install and run Windows 11:

* 1GHz 64-bit processor
* 4GB of RAM
* 64 GB of storage space
* System firmware that supports UEFI, Secure Boot capable
* Trusted Platform Module (TPM) 1.2/2.0.

 Now, if you meet the hardware specifications and still encounter this PC can't run Windows 11 error when using the[PC Health Checkup](https://www.microsoft.com/en-us/windows/windows-11) app, you can fix it by tweaking a few settings in your BIOS/UEFI setup.

![pc health check upgrade windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/pc-health-check-upgrade-windows-11.png)

 You may also encounter said error when installing Windows 11 through a bootable drive or setup file from the mounted ISO.

### What Is UEFI Boot Mode?

 UEFI (Unified Extensible Firmware Interface) is a booting method designed to replace BIOS (Basic Input Output System). In the legacy boot, the system uses BIOS firmware for booting.

 In general, installing Windows using the newer UEFI mode is recommended as it comes with more security features such as Secure Boot than the legacy BIOS mode. You can[learn more about BIOS](https://www.makeuseof.com/tag/the-bios-explained-boot-order-video-memory-saving-resets-and-optimum-defaults-si/) here.

## What Causes the "PC Can't Run Windows 11 Error?"

 This error occurs when you run the PC Health Check app to check if your PC supports Windows 11\. It may also occur when you try to install Windows 11 from the bootable flash drive or using the setup file from the mounted ISO.

 For Windows 11 to be compatible with your computer, it must support UEFI with Secure Boot, and TPM 1.2 or 2.0 must be enabled. Since Windows 11 requires a UEFI Secure Boot compatible system, the setup will fail to detect required features if you have installed Windows 10 via the legacy boot mode.

 This will trigger the This PC can't install Windows 11 error as the system requirements are unmet. Even if your PC support both Secure Boot and TMP 2.0, you may still have to enable them to resolve the error manually.

 If you use legacy boot mode, you need to set the Boot Mode to UEFI in your BIOS setup to enable the Secure Boot feature (and potentially switch TMP 1.2/2.0 on, too).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094415/7443" target="_top" id="2094415">
  <img src="//a.impactradius-go.com/display-ad/7443-2094415" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094415/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Fix the "This PC Can't Run Windows 11 Error?"

 To fix this error, you should set the Boot Mode to UEFI and enable Secure Boot, and then make sure TPM 1.2/2.0 is enabled on your computer. Please note that the tab names may vary between manufacturers, but the instructions should translate roughly across hardware.

## 1\. Enable Secure Boot in Windows 10

![Enable Secure Boot UEFI Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/Secure-Boot-enabled.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948937/19272" target="_top" id="1948937">
  <img src="//a.impactradius-go.com/display-ad/19272-1948937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Follow these steps to enable Secure Boot compatibility in Windows 10.

1. Close all the open Windows and save your work. Then shut down your PC.
2. Restart your system and start pressing**F2** to enter BIOS setup. Different laptop and PC manufacturers may use other function keys such as F12, F10, F8, or Esc key to enter BIOS. If you need help, refer to our guide on[how to enter BIOS](https://www.makeuseof.com/tag/enter-bios-computer/) for more tips.
3. In the BIOS setup utility, use the arrow keys to open the**Boot** tab. Highlight**Boot Mode** and check if it is set to**Legacy** .
4. To change the Boot Mode, press Enter while the**Boot Mode** is highlighted.
5. Choose**UEFI** from the options. Use the Up and Down arrow keys to select UEFI, and hit Enter to select the option.
6. Next, open the**Security** tab.
7. Highlight the**Secure Boot** option using the arrow keys and hit Enter.
8. Choose**Enabled** to enable Secure Boot on your PC.

 Once you have enabled Secure Boot and UEFI in Boot Mode, make sure TPM 1.2/2.0 is also enabled for your PC. So, don't close the BIOS setup menu yet.

## 2\. Enable TMP 1.2/2.0 to fix the "This PC Can't Install Windows 11 Error"

![Enable Trusted Platform Module](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/Enable-TPM-2-0-BIOS.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948905/19272" target="_top" id="1948905">
  <img src="//a.impactradius-go.com/display-ad/19272-1948905" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948905/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 TMP 1.2/2.0 feature is accessible from the BIOS setup as well. Here's how to do it.

1. In BIOS/UEFI, open the**Security** tab.
2. Scroll down and highlight the**Trusted Platform Technology** option, and hit Enter. On Intel laptops, you may see the**Intel Platform Trust Technology** option instead.
3. Choose**Enabled** and press Enter to apply your selection.
4. Save the changes and exit.

 That's it. You have successfully enabled Secure Boot compatibility and TMP 2.0 on Windows 10\. Restart your PC, run the PC Health Checkup tool, or install Windows 11 to see if the error is resolved.

## 3\. Bypass TPM 2.0 and Secure Boot Requirement Using Registry Editor

 If your PC doesn't support Secure Boot and TPM 2.0, you can bypass the restriction using a workaround. To do this, we will modify the registry entry, allowing you to upgrade without Secure Boot and TPM 2.0 requirements.

 Note that your system must support at least TPM 1.2 for this workaround to work.

 Note that editing your Windows Registry involves risk. Make sure to[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and then proceed with the step below.

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor.**
3. In Registry Editor, navigate to the following location. You can copy and paste the registry path for quick navigation:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\Setup\MoSetup`
4. Right-click on the**MoSetup** key and selec**t New > DWORD** (32-bit) value.  
![registry editor mosetup new value bypass windows 11 restriction](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-mosetup-new-value-bypass-windows-11-restriction.jpg)
5. Rename the value as**AllowUpgradeWithUnsupportedTPMorCPU.**
6. Right-click on the newly created value and select**Modify** .  
![registry editor mosetup new value 1 bypass windows 11 restriction](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/registry-editor-mosetup-new-value-1-bypass-windows-11-restriction.jpg)
7. In the Value data field, type**1** and click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Close the Registry Editor and try to install Windows 11 using the media creation tool or ISO. The upgrade should complete without the error.

 If the issue persists, read our guide to[bypass Windows 11 minimum installation requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) to learn more ways to bypass the restrictions and upgrade your PC.

## No Boot Device Found Error After Changing Boot Mode from Legacy to UEFI

 You may encounter the**No Boot Device Found** error if you change the Boot Mode for an existing Windows 10 installation from Legacy to UEFI. However, there's nothing to worry about.

 You can easily boot into your existing Windows 10 installation by changing the Boot Mode to Legacy from UEFI again in the BIOS setup. Next, use the MBR2GTP tool to convert your installation drive/disk from Master Boot Record (MBR) to the GUID Partition Table (GPT) without modifying or deleting data on the disk. You can learn more about using MBR2GRP here .

 Once you have converted the drive, you can change the Boot Mode from Legacy to UEFI without the No Boot Device Found error. Alternatively, if you are going to clean install Windows 11, make sure to install Windows 11 (or Windows 10) in the UEFI mode to prevent any issues in the future.

 If the bootable drive does not show up in the Boot Manager after enabling Secure Boot, ensure it is formatted with the UEFI system in Rufus. If not, create a bootable drive again with the target system set to UEFI (CMS).

## Fixing the This PC Can't Run Windows 11 Error

 Windows computers with the BIOS legacy firmware enabled won't be able to install Windows 11\. Fortunately, you can easily fix the error by tweaking your BIOS setup utility to enable UEFI firmware mode to enable Secure Boot and TPM 2.0.

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
<li><a href="https://win11-tips.techidaily.com/addressing-non-shown-pc-monitor-at-startup/"><u>Addressing Non-Shown PC Monitor at Startup</u></a></li>
<li><a href="https://win-able.techidaily.com/boost-your-fallout-76-performance-top-techniques-to-eliminate-lag/"><u>Boost Your Fallout 76 Performance: Top Techniques to Eliminate Lag</u></a></li>
<li><a href="https://network-issues.techidaily.com/fallout-4s-crash-defeated-on-pc/"><u>Fallout 4'S Crash, Defeated on PC</u></a></li>
<li><a href="https://win11.techidaily.com/free-ways-to-eliminate-your-tiktok-videos-branding/"><u>Free Ways to Eliminate Your TikTok Video's Branding</u></a></li>
<li><a href="https://win11.techidaily.com/from-concept-to-screen-essential-techniques-for-creating-amazing-music-videos-beginner-level/"><u>From Concept to Screen: Essential Techniques for Creating Amazing Music Videos (Beginner Level)</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-upgrading-your-dvd-files-a-step-by-step-tutorial-for-hd-wmv-playback-on-windows-pcs/"><u>Guide to Upgrading Your DVD Files: A Step-by-Step Tutorial for HD WMV Playback on Windows PCs</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-best-solutions-for-htc-network-unlock-by-drfone-android/"><u>In 2024, Best Solutions for HTC Network Unlock</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>In 2024, Does Life360 Notify When You Log Out On Apple iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/insignia-usb-20-to-ethernet-adapter-driver-download-windows-11-10/"><u>Insignia USB 2.0 to Ethernet Adapter Driver Download | Windows 11, 10</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-dvd-screen-fitting-for-widescreen-televisions/"><u>Mastering the Art of DVD Screen Fitting for Widescreen Televisions</u></a></li>
<li><a href="https://technical-tips.techidaily.com/navigating-the-smart-tv-market-7-crucial-points-to-keep-in-mind-pre-purchase/"><u>Navigating the Smart TV Market: 7 Crucial Points to Keep in Mind Pre-Purchase</u></a></li>
<li><a href="https://app-tips.techidaily.com/nvidia-leads-with-blackwell-jensen-huang-reveals-revolutionary-chip-series-during-gtc-keynote-insights-for-tech-enthusiasts-zdnet/"><u>Nvidia Leads with Blackwell: Jensen Huang Reveals Revolutionary Chip Series During GTC Keynote - Insights for Tech Enthusiasts | ZDNet</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-tips-for-fixing-missing-shelldll-files/"><u>Troubleshooting Tips for Fixing Missing Shell.dll Files</u></a></li>
</ul></div>

