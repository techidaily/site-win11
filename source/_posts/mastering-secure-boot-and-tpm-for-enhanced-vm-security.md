---
title: Mastering Secure Boot and TPM for Enhanced VM Security
date: 2024-11-30T20:41:48.421Z
updated: 2024-12-07T05:14:26.313Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Secure Boot and TPM for Enhanced VM Security
excerpt: This Article Describes Mastering Secure Boot and TPM for Enhanced VM Security
keywords: Secure Boot Basics,TPM Fundamentals,Virtualization Hardening,Boot Chain Protection,Encryption Standards,Access Control Measures,VM Security Techniques
thumbnail: https://thmb.techidaily.com/b6c1c170b3fb34192b1990649e9c8685733790cb7484ba703ce124bf47249cb0.jpg
---

## Mastering Secure Boot and TPM for Enhanced VM Security

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-unmissable-gameplay-in-virtual-realms/"><u>[New] 2024 Approved Unmissable Gameplay in Virtual Realms</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-screen-saving-snapchat-memories-on-phone/"><u>[New] Screen Saving Snapchat Memories on Phone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-the-genuine-appraisal-of-recordcast-features/"><u>[New] The Genuine Appraisal of RecordCast Features</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-how-to-cut-video-for-instagram-on-mac/"><u>[Updated] 2024 Approved How To Cut Video For Instagram On Mac</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-youtube-angle-adjustment-a-step-by-step-editing-guide-for-2024/"><u>[Updated] Youtube Angle Adjustment A Step-by-Step Editing Guide for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-4k-monitor-buying-guide-how-to-choose-the-right-monitor/"><u>2024 Approved 4K Monitor Buying Guide How to Choose the Right Monitor</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-oneplus-nord-n30-se-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock OnePlus Nord N30 SE Pattern Lock Screen</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstarting-your-pc-with-offline-win11-setup/"><u>Jumpstarting Your PC with Offline Win11 Setup</u></a></li>
<li><a href="https://win-solutions.techidaily.com/master-the-tips-ensuring-smooth-performance-of-bloodhunt-on-your-pc-setup/"><u>Master the Tips: Ensuring Smooth Performance of Bloodhunt on Your PC Setup</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ed-themed-windows-11/"><u>Mastering Ed-Themed Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/securing-systems-five-key-approaches-to-reinstate-defender-safeguard/"><u>Securing Systems: Five Key Approaches to Reinstate Defender Safeguard</u></a></li>
<li><a href="https://win11.techidaily.com/synopsis-shortcut-strategies-for-win11-narrator/"><u>Synopsis: Shortcut Strategies for Win11 Narrator</u></a></li>
</ul></div>

