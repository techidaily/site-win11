---
title: Enabling or Disabling TPM Support - A Complete VBox 7.0 Guide
date: 2024-12-10T10:52:09.900Z
updated: 2024-12-12T17:09:32.254Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling or Disabling TPM Support - A Complete VBox 7.0 Guide
excerpt: This Article Describes Enabling or Disabling TPM Support - A Complete VBox 7.0 Guide
keywords: VirtualBox TPM Guide,Enable/Disable TPM,VMWare TPM Setup,TPM in VirtualBox 7.0,VBox TPM Support Guide,Secure Boot TPM Virtualization,Manage TPM VirtualBox
thumbnail: https://thmb.techidaily.com/eb6c43743edfe7719c43f746c3a62c94afe56182a98c24ab59e2903c5366daaa.jpg
---

## Enabling or Disabling TPM Support - A Complete VBox 7.0 Guide

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Enable or Disable Secure Boot and TPM Support in VirtualBox 7.0

 Repeat the following steps to enable TPM 2.0 and Secure Boot in VirtualBox.

1. Press the**Win** key and search VirtualBox. Click on the first relevant search result to launch the app.
2. Click on a Windows virtual machine and then click on the**Settings** icon.
3. Navigate to the**System** settings option.
4. Find the**TPM** option. If it is set to none, click on the**arrow** icon to open the drop-down menu.
5. Select the TPM**v2.0** option from the list. Windows 11 won't work with anything lower but if you are using Windows 10 then you can pick**v1.2** from the list.
6. Scroll down and locate the**Extended Features** section. Click on the**Enable EFI (special OSes only)** option check box.
7. Then click on the**Enable Secure Boot** option check box.  
![Enable Secure Boot and TPM Support in VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-secure-boot-and-tpm-support-in-virtualbox-7-0.jpg)
8. Now, click on the**OK** button. The settings window will close automatically.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Manage TPM and Secure Boot Features in VirtualBox With Ease

 You can choose to keep both features active or not. After installing Windows 11 as a virtual machine, you can turn TPM and Secure Boot off and not face any issues with the operating system. However, remember that these are important from a security perspective.

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
<li><a href="https://extra-support.techidaily.com/new-revolutionizing-operations-with-virtual-engineering/"><u>[New] Revolutionizing Operations with Virtual Engineering</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-secrets-of-snapping-finding-missing-private-images/"><u>[Updated] 2024 Approved Secrets of Snapping Finding Missing Private Images</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-mastering-pip-feature-in-microsoft-edge/"><u>[Updated] In 2024, Mastering PIP Feature in Microsoft Edge</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-realme-gt-neo-5-se-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/disable-clustered-taskbar-on-windows-11/"><u>Disable Clustered Taskbar on Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-the-brother-ql-7800nw-printer-driver-for-free-today/"><u>Download the Brother QL-7800NW Printer Driver for Free Today!</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-gestures-and-swipes-for-flawless-pc-use-in-windows/"><u>Enhancing Gestures and Swipes for Flawless PC Use in Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/from-canvas-to-cryptos-select-7-nft-creating-powerhouses-for-2024/"><u>From Canvas to Cryptos Select 7 NFT-Creating Powerhouses for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed Guide on Faking Your Location in Mozilla Firefox On Honor Magic 6 Lite | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-your-calendar-the-windows-outlook-way/"><u>Revamping Your Calendar - The Window's Outlook Way</u></a></li>
<li><a href="https://win11.techidaily.com/smart-strategies-convert-heic-images-to-jpeg-on-windows-11-seamlessly/"><u>Smart Strategies: Convert HEIC Images to JPEG on Windows 11 Seamlessly</u></a></li>
<li><a href="https://win11.techidaily.com/smooth-gameplay-resumes-with-fixing-epic-launcher-sign-ins/"><u>Smooth Gameplay Resumes with Fixing Epic Launcher Sign-Ins</u></a></li>
<li><a href="https://win-great.techidaily.com/the-ultimate-guide-simplifying-audio-editing-with-an-ogg-file-splitter/"><u>The Ultimate Guide: Simplifying Audio Editing with an OGG File Splitter</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unlocking-seamless-linktree-addition-in-your-tiktok-profile-for-2024/"><u>Unlocking Seamless Linktree Addition in Your TikTok Profile for 2024</u></a></li>
</ul></div>

