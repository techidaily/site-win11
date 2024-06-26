---
title: Step-by-Step Guide to Manage Secure Boot & TPM Settings on VirtualBox 7.0
date: 2024-06-25T11:45:27.462Z
updated: 2024-06-26T11:45:27.462Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Step-by-Step Guide to Manage Secure Boot & TPM Settings on VirtualBox 7.0
excerpt: This Article Describes Step-by-Step Guide to Manage Secure Boot & TPM Settings on VirtualBox 7.0
keywords: Secure Boot Control,VirtualBox TPM Management,TPM Virtualization Guide,VirtualBox Security Settings,Manage Secure Boot in VMs,VirtualBox TPM Configuration,Step-by-Step Secure Boot VM
thumbnail: https://thmb.techidaily.com/502b1cdc938497dc65859bd4dea7388cbc83b5388aae8627911832c708fd7626.jpg
---

## Step-by-Step Guide to Manage Secure Boot & TPM Settings on VirtualBox 7.0

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

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

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
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
<li><a href="https://win11.techidaily.com/troubleshooting-windows-1110-onedrive-errors/"><u>Troubleshooting Windows 11/10 OneDrive Errors</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-code-0x80246007-from-windows-update-on-w10w11/"><u>Eliminating Error Code 0X80246007 From Windows Update on W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-error-x0001-in-windows-devices/"><u>Strategies for Overcoming Error X0001 in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-non-recognized-ports-and-devices-on-windows-11/"><u>How to Fix Non-Recognized Ports and Devices on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-startup-program-management-for-a-flawless-windows-11-start/"><u>Mastering Startup Program Management for a Flawless Windows 11 Start</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-overcoming-windows-11s-rename-limitations/"><u>Essential Fixes: Overcoming Windows 11'S Rename Limitations</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-clear-unidentified-devices-issue-in-win-11/"><u>How to Clear Unidentified Devices Issue in Win 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-premium-high-resolution-pics-viewer-quickly/"><u>[New] Premium High-Resolution Pics Viewer, Quickly</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/does-the-customary-speed-of-your-tiktok-slideshow-appear-to-be-slow-enough-of-late-if-yes-drop-your-worries-here-with-the-know-how-of-increasing-the-tiktok-/"><u>Does the Customary Speed of Your TikTok Slideshow Appear to Be Slow Enough of Late? If Yes, Drop Your Worries Here with the Know-How of Increasing the TikTok Slideshow Speed</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-resolve-motorola-razr-40-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve Motorola Razr 40 Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-unlock-the-potential-of-your-facebook-lives-for-2024/"><u>[Updated] Unlock the Potential of Your Facebook Lives for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-a-step-by-step-approach-for-adding-soundtracks-to-youtube-clips/"><u>[Updated] 2024 Approved  A Step-by-Step Approach for Adding Soundtracks to YouTube Clips</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-roadmap-to-exceptional-spotify-ad-performance/"><u>In 2024, The Roadmap to Exceptional Spotify Ad Performance</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-secure-again-combating-2023s-facebook-vulnerability/"><u>[Updated] In 2024, Secure Again  Combating 2023'S Facebook Vulnerability</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-feast-on-these-15-viral-tiktok-dishes-your-next-kitchen-experiment-awaits/"><u>[Updated] 2024 Approved  Feast on These 15 Viral TikTok Dishes – Your Next Kitchen Experiment Awaits</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-inside-look-key-aspects-of-srt-mastery/"><u>In 2024, Inside Look  Key Aspects of SRT Mastery</u></a></li>
</ul></div>
