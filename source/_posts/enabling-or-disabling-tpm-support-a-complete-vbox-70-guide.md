---
title: Enabling or Disabling TPM Support - A Complete VBox 7.0 Guide
date: 2024-12-06T03:05:20.879Z
updated: 2024-12-07T01:30:42.579Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-captivating-stories-in-motion-best-video-theme-choices/"><u>[New] 2024 Approved Captivating Stories in Motion Best Video Theme Choices</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-from-still-photos-to-dynamic-video-how-to-use-your-cellular-device-for-2024/"><u>[New] From Still Photos to Dynamic Video How To Use Your Cellular Device for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-reviewing-multiple-cameras-are-there-upgrades/"><u>[Updated] Reviewing Multiple Cameras Are There Upgrades?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-pro-tips-for-video-conference-recordings-desktop-edition/"><u>2024 Approved Pro Tips for Video Conference Recordings Desktop Edition</u></a></li>
<li><a href="https://unlock-android.techidaily.com/6-solutions-to-unlock-google-phones-if-you-forgot-password-pin-pattern-by-drfone-android/"><u>6 Solutions to Unlock Google Phones If You Forgot Password, PIN, Pattern</u></a></li>
<li><a href="https://win11.techidaily.com/designing-your-own-fingerprint-on-win11/"><u>Designing Your Own Fingerprint on Win11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-realme-11x-5g-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Realme 11X 5G Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-swiftly-reset-and-enhance-pc-graphics-in-windows-10-and-11/"><u>How to Swiftly Reset and Enhance PC Graphics in Windows 10 & 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-show-wi-fi-password-on-xiaomi-civi-3-disney-100th-anniversary-edition-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Xiaomi Civi 3 Disney 100th Anniversary Edition</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-remedy-for-error-code-windows-audio-0xd36b4/"><u>Mastering Remedy for Error Code: Windows Audio 0Xd36b4</u></a></li>
<li><a href="https://win11.techidaily.com/steering-clear-of-installer-rights-problems-on-pcs/"><u>Steering Clear of Installer Rights Problems on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-revive-a-stuck-warcraft-62-update/"><u>Tips to Revive a Stuck Warcraft 6.2 Update</u></a></li>
<li><a href="https://win11-tips.techidaily.com/top-innovations-a-closer-look-at-windows-latest-february-update/"><u>Top Innovations: A Closer Look at Windows' Latest February Update</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-meanings-and-solutions-for-winerror-0x80071a90/"><u>Unpacking the Meanings and Solutions for WinError 0X80071a90</u></a></li>
</ul></div>

