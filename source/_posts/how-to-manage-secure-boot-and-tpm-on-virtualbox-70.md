---
title: How to Manage Secure Boot & TPM on VirtualBox 7.0
date: 2024-11-11T06:54:23.784Z
updated: 2024-11-18T06:29:46.316Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Manage Secure Boot & TPM on VirtualBox 7.0
excerpt: This Article Describes How to Manage Secure Boot & TPM on VirtualBox 7.0
keywords: Secure Boot Control in VirtualBox,TPM Management VirtualBox,VirtualBox Secure Boot Setup,Managing TPM in VirtualBox 7,VirtualBox Security Boot Options,Optimizing VirtualBox TPM Configurations,VirtualBox Secure Boot & TPM Guide
thumbnail: https://thmb.techidaily.com/b734a2c6690e4996dacb7188f3387d968781f292fbd537e9c3d8dd96d06bbb96.jpg
---

## How to Manage Secure Boot & TPM on VirtualBox 7.0

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997717/19272" target="_top" id="1997717">
  <img src="//a.impactradius-go.com/display-ad/19272-1997717" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997717/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151883/7443" target="_top" id="2151883">
  <img src="//a.impactradius-go.com/display-ad/7443-2151883" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151883/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1013424/11832" target="_top" id="1013424">
  <img src="//a.impactradius-go.com/display-ad/11832-1013424" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1013424/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-videos.techidaily.com/new-peeling-back-the-layers-of-visual-past-a-guide-to-fb-image-searching-reversed-for-2024/"><u>[New] Peeling Back the Layers of Visual Past A Guide to FB Image Searching (Reversed) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-virtualization-running-windows-11-on-vmware-player-17/"><u>Effortless Virtualization: Running Windows 11 on VMware Player 17</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-erroneous-pc-label-in-windows-os/"><u>Fixing Erroneous PC Label in Windows OS</u></a></li>
<li><a href="https://blog-min.techidaily.com/from-mp3-to-wav-master-the-conversion-process-in-audacity-for-crystal-clear-audio-quality/"><u>From MP3 to WAV: Master the Conversion Process in Audacity for Crystal Clear Audio Quality</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-infinix-pictures-an-easy-method-explained-by-fonelab-android-recover-pictures/"><u>How to Restore Deleted Infinix Pictures An Easy Method Explained.</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-bypass-the-required-apple-store-verification-for-iphone-se-by-drfone-ios/"><u>In 2024, How To Bypass the Required Apple Store Verification For iPhone SE</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-nokia-c22-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Nokia C22 Device</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-windowsmac-execute-srt-files-with-ease/"><u>In 2024, Windows/Mac Execute SRT Files with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/mending-data-flow-issues-with-windows-usb-devices/"><u>Mending Data Flow Issues with Windows' USB Devices</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-safe-access-getting-back-to-normal-outlook/"><u>Overcoming Safe Access: Getting Back to Normal Outlook</u></a></li>
<li><a href="https://win-able.techidaily.com/overcoming-the-0xc19t01e1-hurdle-fixing-common-windows-10-boot-issues/"><u>Overcoming the 0Xc19t01e1 Hurdle: Fixing Common Windows 10 Boot Issues</u></a></li>
<li><a href="https://win11.techidaily.com/secure-effective-setting-up-powershell-script-policies-right/"><u>Secure, Effective: Setting Up PowerShell Script Policies Right</u></a></li>
<li><a href="https://win11.techidaily.com/solving-missing-device-drivers-alert-during-windows-setup-process/"><u>Solving Missing Device Drivers Alert During Windows Setup Process</u></a></li>
<li><a href="https://win11.techidaily.com/steering-clear-of-errors-in-windows-health-indicator/"><u>Steering Clear of Errors in Windows Health Indicator</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-brain-challenge-top-trivia-networks-for-24-for-2024/"><u>Ultimate Brain Challenge - Top Trivia Networks for '24 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unmasking-the-covert-context-options-in-windows-11/"><u>Unmasking the Covert Context Options in Windows 11</u></a></li>
<li><a href="https://fox-info.techidaily.com/unrivaled-streaming-experience-ranking-the-leaders-for-2024/"><u>Unrivaled Streaming Experience Ranking the Leaders for 2024</u></a></li>
</ul></div>

