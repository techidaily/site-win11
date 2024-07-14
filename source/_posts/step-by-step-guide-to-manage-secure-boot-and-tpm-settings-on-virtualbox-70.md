---
title: Step-by-Step Guide to Manage Secure Boot & TPM Settings on VirtualBox 7.0
date: 2024-07-13T11:07:02.829Z
updated: 2024-07-14T11:07:02.829Z
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
<li><a href="https://win11.techidaily.com/how-to-bypass-sie-and-load-unverified-drivers-in-windows/"><u>How to Bypass SIE & Load Unverified Drivers in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-windows-11s-security-and-credentials-panel/"><u>Guide to Windows 11'S Security & Credentials Panel</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-breaking-through-youtubes-walls-using-advanced-creator-studio-skills/"><u>[Updated] Breaking Through YouTube's Walls Using Advanced Creator Studio Skills</u></a></li>
<li><a href="https://win11.techidaily.com/low-memory-high-performance-comparing-best-windows-browsers/"><u>Low-Memory, High Performance: Comparing Best Windows Browsers</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-the-invalid-token-reference-in-modern-oses/"><u>Dealing with the Invalid Token Reference in Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-vm-experience-seamless-upgrade-to-virtualbox-v70-on-w11-systems/"><u>Elevate Your VM Experience: Seamless Upgrade to VirtualBox v7.0 on W11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/easy-auto-shutdown-techniques-for-idle-windows-pcs/"><u>Easy Auto-Shutdown Techniques for Idle Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missed-display-after-windows-starts/"><u>Overcoming Missed Display After Windows Starts</u></a></li>
<li><a href="https://win11.techidaily.com/leading-password-guardians-revolutionizing-windows-11-life/"><u>Leading Password Guardians Revolutionizing Windows 11 Life</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-vivo-x100-pro-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Vivo X100 Pro Fingerprint Lock</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-powershell-experience-execution-policies-demystified/"><u>Optimize Your PowerShell Experience: Execution Policies Demystified</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-activate-black-background-on-wincalc/"><u>Guide to Activate Black Background on WinCalc</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-nokia-c22mirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Nokia C22Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-bring-your-camera-life-into-your-instagram-world/"><u>2024 Approved  Bring Your Camera Life Into Your Instagram World</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-file-properties-and-date-adjustments/"><u>Navigating Windows File Properties and Date Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/excellent-windows-pens-tablet-notes-companions/"><u>Excellent Windows Pens' Tablet Notes Companions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-expert-insights-bridging-obs-and-facebook-live-streaming/"><u>In 2024, Expert Insights  Bridging OBS and Facebook Live Streaming</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-annual-reveal-best-free-luts-with-direct-access-links/"><u>In 2024, Annual Reveal - Best FREE LUTs with Direct Access Links</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-num-caps-and-scroll-lock-key-indicators-to-windows-11s-system-tray/"><u>How to Add Num, Caps, and Scroll Lock Key Indicators to Windows 11’S System Tray</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-installed-disk-issue-on-windows-11-system/"><u>Fixing Non-Installed Disk Issue on Windows 11 System</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-mastery-for-streamlined-project-planning/"><u>Keyboard Mastery for Streamlined Project Planning</u></a></li>
<li><a href="https://win11.techidaily.com/journey-through-credential-management-fixes/"><u>Journey Through Credential Management Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-secrets-of-devhome-in-windows-11/"><u>Deciphering the Secrets of DevHome in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-read-failure-errors-in-windows-1011/"><u>Overcoming Read Failure Errors in Windows 10/11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-on-vivo-y78-5g-by-drfone-android/"><u>How to Bypass FRP on Vivo Y78 5G?</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-gpu-usage-in-windows-desktop-window/"><u>Decreasing Excessive GPU Usage in Windows Desktop Window</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-avid-viewers-check-out-these-top-15-alternatives-to-obs/"><u>[Updated] Avid Viewers, Check Out These Top 15 Alternatives to OBS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-combat-frozen-wireless-mice-on-windows-desktops/"><u>How to Combat Frozen Wireless Mice on Windows Desktops</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-over-system-restore-a-windows-11-perspective/"><u>Mastery Over System Restore: A Windows 11 Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-ties-with-windows-11-store/"><u>Cutting Ties with Windows 11 Store</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-budget-friendly-hd-desktop-recording-tools-roundup/"><u>[New] In 2024, Budget-Friendly HD Desktop Recording Tools Roundup</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-debunking-myths-5-little-known-truths-about-the-16x9-ratio-calculator/"><u>New Debunking Myths 5 Little-Known Truths About the 16X9 Ratio Calculator</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/a-comprehensive-introduction-to-streamlabs-obs-for-2024/"><u>A Comprehensive Introduction to Streamlabs OBS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enter-the-inner-workings-of-your-pc/"><u>Enter the Inner Workings of Your PC</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-maximize-account-performance-with-these-premier-tiktok-metrics/"><u>[Updated] In 2024, Maximize Account Performance with These Premier TikTok Metrics</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-a-compre-written-by-john-doe/"><u>[New] In 2024, A Compre Written By  John Doe</u></a></li>
<li><a href="https://win11.techidaily.com/guide-accessing-windows-11s-security-settings/"><u>Guide: Accessing Windows 11'S Security Settings</u></a></li>
<li><a href="https://win11.techidaily.com/invisible-windows-bar-make-it-transparent-on-win11/"><u>Invisible Windows Bar: Make It Transparent on Win11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-radiate-on-screen-quicker-ways-to-brighten-iphone-media/"><u>In 2024, Radiate on Screen  Quicker Ways to Brighten iPhone Media</u></a></li>
<li><a href="https://win11.techidaily.com/dont-overlook-the-side-effects-of-bargain-windows-keys/"><u>Don't Overlook: The Side Effects of Bargain Windows Keys</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-device-communication-efficiency-by-optimizing-windows-systems/"><u>Enhancing Device Communication Efficiency by Optimizing Windows Systems</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-youtubes-virality-secrets-effective-hashtag-strategies/"><u>In 2024, YouTube's Virality Secrets  Effective Hashtag Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-white-screens-and-blank-logins-on-windows-1011/"><u>Navigating Through White Screens and Blank Logins on Windows 10/11</u></a></li>
</ul></div>
