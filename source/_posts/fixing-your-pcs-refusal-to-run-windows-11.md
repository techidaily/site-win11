---
title: Fixing Your PC's Refusal to Run Windows 11
date: 2024-08-16T00:54:37.078Z
updated: 2024-08-17T00:54:37.078Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fixing Your PC's Refusal to Run Windows 11
excerpt: This Article Describes Fixing Your PC's Refusal to Run Windows 11
keywords: Windows 11 Installation Issues,Upgrading PCs to Windows 11,Resolving Windows 11 Errors,Troubleshooting Windows 11 Launch,Fix Windows 11 Refusal,Overcoming Windows 11 Boot Failure,Enabling Windows 11 OS
thumbnail: https://thmb.techidaily.com/06e8346e5608d987194209ad6987c897b2a9a9792c4b565af91b063377adb915.jpg
---

## Fixing Your PC's Refusal to Run Windows 11

 Microsoft Windows 11 is here, and you can use the company's PC Health Check app to check if your PC meets the minimum system requirements to install Windows 11\. Unfortunately, for many users, running the PC Health Check app returns the This PC can't Run Windows 11 error.

 You will most likely encounter this error if the app detects your system hardware incompatible with Windows 11\. Fortunately, there are workarounds to get around this annoying error that may prevent you from upgrading to Windows 11 successfully.

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
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->

 You may also encounter said error when installing Windows 11 through a bootable drive or setup file from the mounted ISO.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
### What Is UEFI Boot Mode?

 UEFI (Unified Extensible Firmware Interface) is a booting method designed to replace BIOS (Basic Input Output System). In the legacy boot, the system uses BIOS firmware for booting.

 In general, installing Windows using the newer UEFI mode is recommended as it comes with more security features such as Secure Boot than the legacy BIOS mode. You can[learn more about BIOS](https://www.makeuseof.com/tag/the-bios-explained-boot-order-video-memory-saving-resets-and-optimum-defaults-si/) here.

## What Causes the "PC Can't Run Windows 11 Error?"

 This error occurs when you run the PC Health Check app to check if your PC supports Windows 11\. It may also occur when you try to install Windows 11 from the bootable flash drive or using the setup file from the mounted ISO.

 For Windows 11 to be compatible with your computer, it must support UEFI with Secure Boot, and TPM 1.2 or 2.0 must be enabled. Since Windows 11 requires a UEFI Secure Boot compatible system, the setup will fail to detect required features if you have installed Windows 10 via the legacy boot mode.

 This will trigger the This PC can't install Windows 11 error as the system requirements are unmet. Even if your PC support both Secure Boot and TMP 2.0, you may still have to enable them to resolve the error manually.

 If you use legacy boot mode, you need to set the Boot Mode to UEFI in your BIOS setup to enable the Secure Boot feature (and potentially switch TMP 1.2/2.0 on, too).

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Fix the "This PC Can't Run Windows 11 Error?"

 To fix this error, you should set the Boot Mode to UEFI and enable Secure Boot, and then make sure TPM 1.2/2.0 is enabled on your computer. Please note that the tab names may vary between manufacturers, but the instructions should translate roughly across hardware.

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Enable Secure Boot in Windows 10

![Enable Secure Boot UEFI Windows 10](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/Secure-Boot-enabled.png)
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
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

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## 2\. Enable TMP 1.2/2.0 to fix the "This PC Can't Install Windows 11 Error"

![Enable Trusted Platform Module](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/06/Enable-TPM-2-0-BIOS.png)

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
8. Close the Registry Editor and try to install Windows 11 using the media creation tool or ISO. The upgrade should complete without the error.

 If the issue persists, read our guide to[bypass Windows 11 minimum installation requirements](https://www.makeuseof.com/bypass-windows-11-minimum-installation-requirements/) to learn more ways to bypass the restrictions and upgrade your PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-all-about-youtubes-elite-access-a-complete-breakdown/"><u>[New] 2024 Approved  All About YouTube's Elite Access - A Complete Breakdown</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-attracting-eyes-with-these-6-video-genres/"><u>[New] Attracting Eyes with These 6 Video Genres</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-ace-the-art-of-game-recordings-in-windows-11-for-2024/"><u>[Updated] Ace the Art of Game Recordings in Windows 11 for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/15-best-action-cameras/"><u>15 Best Action Cameras</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-iphone-photo-management-guide-for-albums-and-cloud-storage/"><u>2024 Approved  IPhone Photo Management Guide for Albums & Cloud Storage</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-laugh-loom-robotic-deadlines/"><u>2024 Approved  Laugh Loom  Robotic Deadlines</u></a></li>
<li><a href="https://win11.techidaily.com/6-tips-to-improve-your-wsl-2-docker-experience-on-windows/"><u>6 Tips to Improve Your WSL 2 Docker Experience on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/ai-copilot-in-windows-11-enhancing-user-efficiency/"><u>AI Copilot in Windows 11: Enhancing User Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/alter-viewer-angle-in-windows-setup/"><u>Alter Viewer Angle in Windows Setup</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-music-live-streaming-services/"><u>Best Music Live Streaming Services</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-an-inactive-firewall-a-step-by-step-guide/"><u>Bypassing an Inactive Firewall: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-ai-capabilities-at-ms-store/"><u>Delving Into AI Capabilities at MS Store</u></a></li>
<li><a href="https://win11.techidaily.com/dxvk-uncovered-enhancing-win-based-gameplay-dynamics/"><u>DXVK Uncovered: Enhancing Win-Based Gameplay Dynamics</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-learning-7-strategies-for-windows-users/"><u>Enhancing Learning: 7 Strategies for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/expanding-pin-code-length-in-windows-11-and-11/"><u>Expanding Pin Code Length in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-and-fixing-absence-of-hypervisor-on-windows-sandbox/"><u>Identifying and Fixing Absence of Hypervisor on Windows Sandbox</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-product-id-from-windows-with-ms-online-service/"><u>Integrating Product ID From Windows with MS Online Service</u></a></li>
<li><a href="https://extra-skills.techidaily.com/leading-android-and-ios-timer-tools-reviewed-your-big-day-planners-must-haves-for-2024/"><u>Leading Android & iOS Timer Tools Reviewed  Your Big Day Planner's Must-Haves for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/leveraging-zoom-features-for-immersive-fb-live-views/"><u>Leveraging Zoom Features for Immersive FB Live Views</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-window-image-display-windows-11-style/"><u>Maximizing Window Image Display: Windows 11 Style</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-error-403-in-roblox-space/"><u>Navigating Through Windows Error 403 in Roblox Space</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-avs-video-editor-2023-review-pros-cons-and-verdict-for-2024/"><u>New AVS Video Editor 2023 Review Pros, Cons, and Verdict for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-top-rated-video-editing-tools-for-4k-content-for-2024/"><u>New Top-Rated Video Editing Tools for 4K Content for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/prioritizing-and-optimizing-windows-11-service-usage-wisely/"><u>Prioritizing and Optimizing Windows 11 Service Usage Wisely</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/proven-elements-for-optimal-bot-assisted-support-systems/"><u>Proven Elements for Optimal Bot-Assisted Support Systems</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-crashes-during-xbox-app-update-process/"><u>Resolving Crashes During Xbox App Update Process</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-your-pcs-wi-fi-woes-six-effective-steps-from-fixing-adapter-failure/"><u>Reviving Your PC's Wi-Fi Woes - Six Effective Steps From Fixing Adapter Failure</u></a></li>
<li><a href="https://win11.techidaily.com/stabilizing-win-os-cease-df-glitching-issues/"><u>Stabilizing Win OS: Cease DF Glitching Issues</u></a></li>
<li><a href="https://win11.techidaily.com/successful-virtualbox-setup-in-winscape/"><u>Successful VirtualBox Setup in Winscape</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-yuzu-experience-on-windows/"><u>Supercharge Your Yuzu Experience on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-rectify-virtualboxs-efail-windows-issue-0x80004005/"><u>Tips to Rectify Virtualbox's E_FAIL (Windows) Issue: 0X80004005</u></a></li>
<li><a href="https://win11.techidaily.com/turning-onoff-phishing-filter-in-microsoftinas-windows-oses/"><u>Turning On/Off Phishing Filter in Microsoft’inas Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-top-windows-11-fps-monitors-and-counter-tools/"><u>Unveiling Top Windows 11 FPS Monitors & Counter Tools</u></a></li>
<li><a href="https://driver-install.techidaily.com/win7-guide-to-elevate-your-graphics-experience-with-hp/"><u>Win7 Guide to Elevate Your Graphics Experience with HP</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-guide-to-security-focused-dialogue-shortcuts/"><u>Windows 11: Guide to Security-Focused Dialogue Shortcuts</u></a></li>
</ul></div>
