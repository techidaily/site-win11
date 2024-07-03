---
title: Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0
date: 2024-06-25T11:23:46.652Z
updated: 2024-06-26T11:23:46.652Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0
excerpt: This Article Describes Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0
keywords: Secure Boot Mastery,TPM Control Guide,VMBoost 7 Security,TPM Enablement Tips,VBox Secure Startup,Advanced TPM Activation,VBox 7.0 TPM Management
thumbnail: https://thmb.techidaily.com/abb5b783422357ac326d246e72e8c7f9c8f3c9e301b0d6289c4da0aac55fb642.jpg
---

## Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0

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
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-fixed-gif-sizes-in-discord-for-windows-11-users/"><u>Unraveling the Mystery of Fixed GIF Sizes in Discord (for Windows 11 Users)</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unauthorized-access-errors-in-windows-environment/"><u>Overcoming Unauthorized Access Errors in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-closed-nvidia-cp-window-in-w11-os/"><u>Overcoming Closed Nvidia CP Window in W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-screen-unresponsive-message-in-windows-1111/"><u>Fixing Screen Unresponsive Message in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-installation-of-ai-tools-in-windows/"><u>Efficient Installation of AI Tools in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-skip-recurring-enter-credentials-messages/"><u>Techniques to Skip Recurring 'Enter Credentials' Messages</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-android-studio-on-windows-for-faster-compilation/"><u>Optimizing Android Studio on Windows for Faster Compilation</u></a></li>
<li><a href="https://win11.techidaily.com/cortanas-farewell-windows-future-awaits/"><u>Cortana's Farewell, Windows' Future Awaits</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-radeon-driver-updates-in-windows-11-step-by-step-guide/"><u>Mastering Radeon Driver Updates in Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11-remote-desktop-troubleshoot-internal-errors/"><u>Resolving Windows 11 Remote Desktop: Troubleshoot Internal Errors</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transform-images-into-movies-xp-software-guide/"><u>In 2024, Transform Images Into Movies  XP Software Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-a-step-by-step-guide-to-curved-image-design/"><u>[New] A Step-by-Step Guide to Curved Image Design</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-assessing-igtv-content-performance-levels/"><u>2024 Approved  Assessing IGTV Content Performance Levels</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-understanding-more-about-capcut-lenta-template-and-slow-motion-videos/"><u>New 2024 Approved Understanding More About CapCut Lenta Template and Slow-Motion Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-facebook-360-video-how-to-make-and-upload-360-video-to-facebook/"><u>2024 Approved  Facebook 360 Video  How to Make and Upload 360 Video to Facebook</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-samsung-galaxy-s23-ultra-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Samsung Galaxy S23 Ultra Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-make-animated-magic-happen-top-5-online-stop-motion-makers/"><u>2024 Approved Make Animated Magic Happen Top 5 Online Stop Motion Makers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-building-brands-and-bonds-on-instagram-steps-to-reach-a-thousand-followers/"><u>[New] In 2024, Building Brands and Bonds on Instagram  Steps to Reach a Thousand Followers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-enhancing-photographic-expression-through-snapchat-edits-for-2024/"><u>[New] Enhancing Photographic Expression Through Snapchat Edits for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/mobile-apps-for-top-notch-introduction-videos-on-iosandroid/"><u>Mobile Apps for Top-Notch Introduction Videos on iOS/Android</u></a></li>
</ul></div>
