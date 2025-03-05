---
title: "Boost Security: Enable or Disable TPM & Secure Boot in VirtualBox"
date: 2025-03-01T02:55:43.826Z
updated: 2025-03-05T02:38:03.849Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boost Security: Enable or Disable TPM & Secure Boot in VirtualBox"
excerpt: "This Article Describes Boost Security: Enable or Disable TPM & Secure Boot in VirtualBox"
keywords: VirtualBox TPM Security,Boost VirtualSecureBoot,TPM Control in VirtualBox,Secure Boot Virtualization,Enable Disable TPM (Virtual),Virtual Box TPM Activation,TPM & Secure Boot Settings
thumbnail: https://thmb.techidaily.com/16e517e86ce5511ef20be02a34a06ee211f62f0d8653c2cec4d55484854e4b69.jpg
---

## Boost Security: Enable or Disable TPM & Secure Boot in VirtualBox

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on [what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

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

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see [how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

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
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-crafting-impactful-reactions-the-ultimate-guidebook/"><u>[New] In 2024, Crafting Impactful Reactions The Ultimate Guidebook</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-aw-snap-faults-in-google-chrome-windows/"><u>Eradicating Aw, Snap! Faults in Google Chrome Windows</u></a></li>
<li><a href="https://youtube-web.techidaily.com/nizing-tracks-in-youtube-music-for-2024/"><u>Harmonizing Tracks in YouTube Music for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-remove-passcode-from-apple-iphone-xs-complete-guide-drfone-by-drfone-ios/"><u>How To Remove Passcode From Apple iPhone XS? Complete Guide | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expert-editions-selecting-high-quality-blu-ray-players-freepaid/"><u>In 2024, Expert Editions Selecting High-Quality Blu-Ray Players (Free/Paid)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-streamlining-video-transfer-from-imovie-to-youtube-platform/"><u>In 2024, Streamlining Video Transfer From iMovie to YouTube Platform</u></a></li>
<li><a href="https://win11.techidaily.com/interpreting-policy-settings-on-windows-a-three-pronged-look/"><u>Interpreting Policy Settings on Windows: A Three-Pronged Look</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-windows-11-deployment-offline/"><u>Mastery of Windows 11 Deployment Offline</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-xbox-service-disruption-in-windows-devices/"><u>Overcoming Xbox Service Disruption in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-rectifying-internal-error-on-windows-devices/"><u>Quick Guide: Rectifying Internal Error on Windows Devices</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/sharp-as-a-razor-toptools-to-unblur-and-enhance-images-online-for-2024/"><u>Sharp as a Razor #TopTools to Unblur & Enhance Images Online for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/smart-owners-integrating-these-pioneering-five-ai-solutions/"><u>Smart Owners: Integrating These Pioneering Five AI Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-1011-menu-navigation-process/"><u>Streamlining Windows 10/11 Menu Navigation Process</u></a></li>
<li><a href="https://apple-account.techidaily.com/the-easy-way-to-remove-an-apple-id-from-your-macbook-for-your-apple-iphone-13-pro-by-drfone-ios/"><u>The Easy Way to Remove an Apple ID from Your MacBook For your Apple iPhone 13 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-trick-to-deciphering-your-devices-identity-via-windows/"><u>The Ultimate Trick to Deciphering Your Devices' Identity via Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubled-by-error-0x80pressure0426-in-windows-11-heres-how-you-can-correct-it/"><u>Troubled by Error 0X80pressure0426 in Windows 11? Here’s How You Can Correct It</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-power-of-windows-11s-wi-fi-broadcasting-feature/"><u>Unlocking the Power of Windows 11'S Wi-Fi Broadcasting Feature</u></a></li>
</ul></div>

