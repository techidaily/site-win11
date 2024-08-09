---
title: How to Manage Virtual Machine's TPM and Secure Boot on VBox 7.0
date: 2024-08-08T13:17:14.447Z
updated: 2024-08-09T13:17:14.447Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Manage Virtual Machine's TPM and Secure Boot on VBox 7.0
excerpt: This Article Describes How to Manage Virtual Machine's TPM and Secure Boot on VBox 7.0
keywords: VM TPM Control,Secure Boot VBOX,VBox 7.0 Security,TPM Management in VBox,Enable Secure Boot (VBOX),VBox TPM Guide,Virtual Secure Boot Setup
thumbnail: https://thmb.techidaily.com/30c580f4aaa4373c8a4d05322fd912eb007bcd184d7b7f33639176575d3c4909.jpg
---

## How to Manage Virtual Machine's TPM and Secure Boot on VBox 7.0

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![Enable Secure Boot and TPM Support in VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-secure-boot-and-tpm-support-in-virtualbox-7-0.jpg)
8. Now, click on the**OK** button. The settings window will close automatically.
9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
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
<li><a href="https://extra-tips.techidaily.com/new-best-available-avi-player-cross-platform-compatibility/"><u>[New] Best Available AVi Player - Cross-Platform Compatibility</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-high-quality-vector-graphics-top-10-sources/"><u>[New] High-Quality Vector Graphics  Top 10 Sources</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-smartcapture-hd-v2/"><u>[New] In 2024, SmartCapture HD V2</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-how-to-record-video-with-logitech-webcam/"><u>[Updated] 2024 Approved  How to Record Video with Logitech Webcam</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-maximize-monetization-the-step-by-step-for-youtube-profiles/"><u>[Updated] Maximize Monetization  The Step-by-Step for YouTube Profiles</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-transformative-versat-cookies-creative-edition/"><u>2024 Approved  Transformative Versat Cookies  Creative Edition</u></a></li>
<li><a href="https://win11.techidaily.com/4-fixes-to-try-if-the-windows-snip-and-sketch-tool-wont-screenshot-the-entire-screen/"><u>4 Fixes to Try if the Windows Snip & Sketch Tool Won’t Screenshot the Entire Screen</u></a></li>
<li><a href="https://win11.techidaily.com/8-strategies-to-solve-vmware-booting-woes-on-win11/"><u>8 Strategies to Solve VMware Booting Woes on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-walkthrough-windows-11-calendar/"><u>A Comprehensive Walkthrough: Windows 11 Calendar</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreran-guide-to-install-and-configure-microsoft-pc-manager/"><u>A Compreran Guide to Install and Configure Microsoft PC Manager</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-permanently-vanish-language-sign-on-win11-ui/"><u>A Guide to Permanently Vanish Language Sign on Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-recover-your-windows-apps/"><u>A Step-by-Step Approach to Recover Your Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-performance-swapping-outdated-windows-drivers/"><u>Accelerating Performance: Swapping Outdated Windows Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-steam-transfers-avoiding-sudden-speed-slumps/"><u>Accelerating Steam Transfers: Avoiding Sudden Speed Slumps</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-faulty-timed-lock-screen-issue-windows/"><u>Addressing Faulty Timed Lock Screen Issue Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-functioning-windows-conditional-filters/"><u>Addressing Non-Functioning Windows Conditional Filters</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-help-function-breakdown-on-windows-11/"><u>Addressing the Help Function Breakdown on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-0x8007000f-on-task-sequences/"><u>Addressing Windows Error 0X8007000f on Task Sequences</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ai-driven-strategies-to-outshine-your-resume-competitors/"><u>AI-Driven Strategies to Outshine Your Resume Competitors</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-to-compatibility-issues-for-windows-packages/"><u>Approaches to Compatibility Issues for Windows Packages</u></a></li>
<li><a href="https://fox-links.techidaily.com/aps-hdr-essentials-for-professionals-and-enthusiasts-for-2024/"><u>APS HDR Essentials for Professionals & Enthusiasts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/arrow-anomalies-heres-how-to-tackle-them/"><u>Arrow Anomalies? Here’s How to Tackle Them</u></a></li>
<li><a href="https://win11.techidaily.com/auto-displaying-images-craft-your-windows-11-slide-show-7-ways/"><u>Auto-Displaying Images: Craft Your Windows 11 Slide Show (7 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-critical-windows-11-service-shutdowns/"><u>Avoiding Critical Windows 11 Service Shutdowns</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-html-overload-fixing-windows-11-mail-format-glitches/"><u>Avoiding HTML Overload: Fixing Windows 11 Mail Format Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-video-codecs-choices-and-justifications/"><u>Best Windows Video Codecs: Choices & Justifications</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-grayed-out-delete-pin-option-in-windows-11/"><u>Breaking Grayed-Out Delete PIN Option in Windows 11</u></a></li>
<li><a href="https://video-capture.techidaily.com/clear-screening-for-focused-online-participation/"><u>Clear Screening for Focused Online Participation</u></a></li>
<li><a href="https://data-wizards.techidaily.com/data-restoration-solutions-for-mac-best-of-free-and-paid-software/"><u>Data Restoration Solutions for Mac - Best of Free & Paid Software</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-airplane-mode-turn-off-gps-location-on-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>Does Airplane Mode Turn off GPS Location On Oppo Find X7? | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/fixing-windows-11-startup-errors-expert-revouninstaller-techniques-explained/"><u>Fixing Windows 11 Startup Errors: Expert RevoUninstaller Techniques Explained</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-asus-rog-phone-7-ultimate-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Asus ROG Phone 7 Ultimate Phone and Remove Locked Screen</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Fixing Foneazy MockGo Not Working On Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-realme-c53-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Realme C53? | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-best-video-to-live-photos-apps/"><u>New 2024 Approved Best Video to Live Photos Apps</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Oppo A1 5G | Dr.fone</u></a></li>
</ul></div>
