---
title: Switch On/Off TPM Support in VirtualBox Version 7.0
date: 2024-12-01T16:23:52.377Z
updated: 2024-12-06T21:37:35.071Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Switch On/Off TPM Support in VirtualBox Version 7.0
excerpt: This Article Describes Switch On/Off TPM Support in VirtualBox Version 7.0
keywords: VirtualBox TPM Control,Enable/Disable TPM VirtualBox,TPM Management VirtualBox,TPM Switching VirtualBox,TPM Support VirtualBox 7.0,Activate/Deactivate TPM in VBox,TPM Functionality VirtualBox Version 7
thumbnail: https://thmb.techidaily.com/db39cf974b891a971b269fa1b5c545ac5598c4412d012bd826ff7f5dff9de440.png
---

## Switch On/Off TPM Support in VirtualBox Version 7.0

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-docs.techidaily.com/ed-seek-out-stimulating-youtube-snippets/"><u>[Updated] Seek Out Stimulating YouTube Snippets</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-collection-best-zero-price-photo-editing-software/"><u>[Updated] The Ultimate Collection Best Zero-Price Photo Editing Software</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-why-are-facebook-recommended-videos-vanishing/"><u>[Updated] Why Are Facebook Recommended Videos Vanishing?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-revolutionary-rider-helmet-cams-top-picks-for-23/"><u>2024 Approved Revolutionary Rider Helmet Cams - Top Picks for '23</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-essential-tips-for-perfect-gopro-time-lapse/"><u>2024 Approved The Essential Tips for Perfect GoPro Time Lapse</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-update-group-policy-on-pcs/"><u>Essential Steps to Update Group Policy on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-network-resource-unavailable-error-on-windows/"><u>How to Fix the Network Resource Unavailable Error on Windows</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-the-essential-guide-to-smartphone-based-youtube-thumbnails/"><u>In 2024, The Essential Guide to Smartphone-Based YouTube Thumbnails</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-tips-of-transferring-messages-from-vivo-v29-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Tips of Transferring Messages from Vivo V29 to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-files-on-two-windows-pcs-with-aoemi/"><u>Integrating Files on Two Windows PCs with AOEMi</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-0x800700e1-windows-errors/"><u>Overcoming 0X800700E1 Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-ease-windows-11-license-soon-to-end-stress/"><u>Solutions to Ease Windows 11 License 'Soon-to-End' Stress</u></a></li>
<li><a href="https://win11.techidaily.com/solving-ms-resouce-error-win11-text-showcase-fix/"><u>Solving Ms-Resouce Error, Win11 Text Showcase Fix</u></a></li>
</ul></div>

