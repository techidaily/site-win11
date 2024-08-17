---
title: Restoring Legacy BOOT Menu Colors
date: 2024-08-16T00:45:37.961Z
updated: 2024-08-17T00:45:37.961Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Restoring Legacy BOOT Menu Colors
excerpt: This Article Describes Restoring Legacy BOOT Menu Colors
keywords: Legacy BOOT Colors Restore,BOOT Legacy Color Restoration,Restore Legacy Menu Colors,Color BOOT Legacy Revival,Legacy Menu Color Reinstatement,Booting Legacy Color Fixation,Menu Color Restoration Legacy
thumbnail: https://thmb.techidaily.com/4c1b7ae799c3eb4ebbe55615e8284400f0c118d4f2fc06cbee13880f73f171b3.jpg
---

## Restoring Legacy BOOT Menu Colors

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
## 1\. Disable Secure Boot to Enable Boot

 Secure Boot is a UEFI feature that protects your computer against malware by allowing only trusted system software to run on your computer. When enabled, it will perform a cryptographic check during the boot process to verify the integrity of the system image.

 However, if you have Secure Boot enabled, it will likely disable Legacy Boot as well. You'll need to[disable Secure Boot in your BIOS utility](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) to fix the issue.

 The below steps to disable Secure Boot are for an HP Pavilion computer. For other systems, refer to your system manual.

To disable secure boot:

1. Click on**Start** and then click on**Power** .
2. Press and hold the**Shift key** and click on**Restart** . Confirm the action if necessary.
3. Release the**Shift** key as the PC shuts down and boot into the**Recovery Menu.**
4. Go to**Troubleshoot** and click on**Advanced options** .
5. Next, click on**UEFI Firmware Settings.**  
![Advanced OptionspUEFI Firmware Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/advanced-optionspuefi-firmware-settings.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to[disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Restore a Grayed Out Legacy Boot Option in Your BIOS

 You can fix the grayed-out Legacy boot option in BIOS by disabling Secure Boot and Trusted Platform Technology. In addition, disable Standard Standby (S0) to fix the problem.

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-tapping-into-youtubes-creative-commons-for-video-creators/"><u>[New] 2024 Approved  Tapping Into YouTube's Creative Commons for Video Creators</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-best-10-tiktok-layer-filters-amplifying-impact/"><u>[New] In 2024, Best 10 TikTok Layer Filters Amplifying Impact</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ptimize-your-watch-activate-av1-on-youtube-platform-for-2024/"><u>[New] Optimize Your Watch  Activate AV1 on YouTube Platform for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-top-10-choices-the-ultimate-gb-emulator-list-android/"><u>[Updated] In 2024, Top 10 Choices  The Ultimate GB Emulator List, Android</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-integrating-social-networks-sharing-fb-videos-on-whatsapp/"><u>[Updated] Integrating Social Networks  Sharing FB Videos on WhatsApp</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-step-by-step-method-to-share-subtitle-text-online/"><u>[Updated] Step-by-Step Method to Share Subtitle Text Online</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-the-windows-recovery-drive-tool/"><u>10 Ways to Open the Windows Recovery Drive Tool</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-easy-guide-to-rectify-ios-and-android-videos-not-sent-by-messenger/"><u>2024 Approved  Easy Guide to Rectify iOS and Android Videos Not Sent by Messenger</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-key-metrics-to-track-igtv-video-analytics/"><u>2024 Approved  Key Metrics to Track  IGTV Video Analytics</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-panoramic-lenses-and-fixed-angle-gear/"><u>2024 Approved  Panoramic Lenses & Fixed-Angle Gear</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-quintessential-accessories-list-for-sj4000-lovers/"><u>2024 Approved  The Quintessential Accessories List for SJ4000 Lovers</u></a></li>
<li><a href="https://win11.techidaily.com/4-fixes-to-try-if-the-windows-snip-and-sketch-tool-wont-screenshot-the-entire-screen/"><u>4 Fixes to Try if the Windows Snip & Sketch Tool Won’t Screenshot the Entire Screen</u></a></li>
<li><a href="https://win11.techidaily.com/5-exceptional-windows-compatible-file-sharing-software/"><u>5 Exceptional Windows-Compatible File Sharing Software</u></a></li>
<li><a href="https://win11.techidaily.com/5-superior-bittorrent-tools-for-windows-users/"><u>5 Superior BitTorrent Tools for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-reset-the-windows-firewall-settings/"><u>5 Ways to Reset the Windows Firewall Settings</u></a></li>
<li><a href="https://win11.techidaily.com/6-android-apps-perfect-for-a-windows-11-enthusiast/"><u>6 Android Apps Perfect for a Windows 11 Enthusiast</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-accessing-windows-odbc-tools/"><u>A Beginner's Guide to Accessing Windows' ODBC Tools</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-walkthrough-windows-11-calendar/"><u>A Comprehensive Walkthrough: Windows 11 Calendar</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreran-guide-to-install-and-configure-microsoft-pc-manager/"><u>A Compreran Guide to Install and Configure Microsoft PC Manager</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-permanently-vanish-language-sign-on-win11-ui/"><u>A Guide to Permanently Vanish Language Sign on Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-recover-your-windows-apps/"><u>A Step-by-Step Approach to Recover Your Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-stopping-blued-in-windows-10/"><u>A Step-by-Step Guide to Stopping Blued in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/a-stepwise-approach-to-win11s-hyper-v-activation/"><u>A Stepwise Approach to Win11's Hyper-V Activation</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-performance-swapping-outdated-windows-drivers/"><u>Accelerating Performance: Swapping Outdated Windows Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/ace-your-battery-life-win-1011-tips/"><u>Ace Your Battery Life: Win 10/11 Tips</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-clarity-windows-11-taskbar-tutorial/"><u>Achieving Clarity: Windows 11 Taskbar Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-fixing-missing-keyboard-erase-feature-in-windows/"><u>Actions for Fixing Missing Keyboard Erase Feature in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/adding-removable-storage-via-explore-navigation-menu/"><u>Adding Removable Storage via Explore Navigation Menu</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dysfunctional-automation-settings-in-office-365outlook/"><u>Addressing Dysfunctional Automation Settings in Office 365/Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-0x8007000f-on-task-sequences/"><u>Addressing Windows Error 0X8007000f on Task Sequences</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-brightness-control-software-for-windows-multiscreen-enthusiasts/"><u>Advanced Brightness Control Software for Windows Multiscreen Enthusiasts</u></a></li>
<li><a href="https://fox-info.techidaily.com/affordable-4k-cameras-guide-(1k-top-picks/"><u>Affordable 4K Cameras Guide (<$1K) - Top Picks</u></a></li>
<li><a href="https://win11.techidaily.com/amplifying-volume-control-on-windows-bluetooth/"><u>Amplifying Volume Control on Windows-Bluetooth</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-to-compatibility-issues-for-windows-packages/"><u>Approaches to Compatibility Issues for Windows Packages</u></a></li>
<li><a href="https://win11.techidaily.com/are-excel-files-opening-in-windows-notepad-try-these-solutions/"><u>Are Excel Files Opening in Windows Notepad? Try These Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/arrow-anomalies-heres-how-to-tackle-them/"><u>Arrow Anomalies? Here’s How to Tackle Them</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-worth-of-windows-11-widgets-in-detail/"><u>Assessing the Worth of Windows 11 Widgets in Detail</u></a></li>
<li><a href="https://win11.techidaily.com/auto-displaying-images-craft-your-windows-11-slide-show-7-ways/"><u>Auto-Displaying Images: Craft Your Windows 11 Slide Show (7 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-html-overload-fixing-windows-11-mail-format-glitches/"><u>Avoiding HTML Overload: Fixing Windows 11 Mail Format Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-mishaps-validate-your-webcammic-on-windows-pc/"><u>Avoiding Mishaps: Validate Your Webcam/Mic on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-sonic-full-screen-pitfalls-on-windows-11-os/"><u>Avoiding Sonic Full-Screen Pitfalls on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-blues-effective-methods-for-hybrid-os-errors-in-winxose/"><u>Beat the Blues: Effective Methods for Hybrid OS Errors in WINXOSE</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-a-valid-temp-folder-in-windows-11/"><u>Best Practices for a Valid Temp Folder in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-video-codecs-choices-and-justifications/"><u>Best Windows Video Codecs: Choices & Justifications</u></a></li>
<li><a href="https://win11.techidaily.com/blending-gmail-with-outlook-on-windows-comprehensive-guide/"><u>Blending Gmail with Outlook on Windows: Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-system-with-these-5-ease-access-tricks/"><u>Boost Your System with These 5 Ease Access Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-task-power-top-5-apps-to-enhance-window-11-workflow/"><u>Boosting Task Power: Top 5 Apps to Enhance Window 11 Workflow</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-overturning-monochrome-windows-display/"><u>Breaking Free: Overturning Monochrome Windows Display</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-grayed-out-delete-pin-option-in-windows-11/"><u>Breaking Grayed-Out Delete PIN Option in Windows 11</u></a></li>
<li><a href="https://fox-access.techidaily.com/exploring-advanced-options-with-gopro-burst-features-for-2024/"><u>Exploring Advanced Options with GoPro Burst Features for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/flip-shift-and-merge-videos-for-professional-android-results/"><u>Flip, Shift & Merge Videos for Professional Android Results</u></a></li>
<li><a href="https://android-unlock.techidaily.com/forgotten-the-voicemail-password-of-samsung-galaxy-s24-ultra-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Samsung Galaxy S24 Ultra? Try These Fixes</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-vivo-s17-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Vivo S17? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-asus-rog-phone-8-pro-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Asus ROG Phone 8 Pro to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-nubia-red-magic-9-proplus-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Nubia Red Magic 9 Pro+</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-elevate-your-meetings-with-teamsnap-expertise/"><u>In 2024, Elevate Your Meetings with TeamSnap Expertise</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Honor Magic 6 Lite | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-lock-your-oppo-f25-pro-5g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Oppo F25 Pro 5G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-nikon-j5-and-its-breakthrough-in-4k-video-technology/"><u>In 2024, Nikon J5 and Its Breakthrough in 4K Video Technology</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-the-clear-cut-guide-to-high-definition-twitter-videos/"><u>In 2024, The Clear-Cut Guide to High Definition Twitter Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-tricks-for-enhanced-video-quality-via-nvidia/"><u>In 2024, Tricks for Enhanced Video Quality via NVIDIA</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-lenovo-webcam-driver-update-for-windows-7/"><u>Latest Lenovo Webcam Driver Update for Windows 7</u></a></li>
<li><a href="https://fox-that.techidaily.com/no-need-for-itunes-heres-how-you-can-bring-your-iphone-back-from-the-dead/"><u>No Need for iTunes? Here's How You Can Bring Your iPhone Back From the Dead!</u></a></li>
<li><a href="https://network-issues.techidaily.com/reviving-pc-gaming-fixing-win-minecraft-graphics-drivers/"><u>Reviving PC Gaming: Fixing Win-Minecraft Graphics Drivers</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-discords-problem-with-recording-gaming-sounds-effectively/"><u>Solving Discord's Problem with Recording Gaming Sounds Effectively</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-pinnacle-of-slow-motion-tech-slomos-full-review-2024/"><u>The Pinnacle of Slow-Motion Tech  SloMo's Full Review, 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/the-quick-start-method-for-combining-obs-and-zoom-for-2024/"><u>The Quick-Start Method for Combining OBS & Zoom for 2024</u></a></li>
<li><a href="https://buynow-help.techidaily.com/top-features-and-performance-of-the-newly-released-apple-tv-4k-3rd-gen-analyzed/"><u>Top Features and Performance of the Newly Released Apple TV 4K, 3Rd Gen Analyzed</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-add-emojis-to-videos-on-youtubefacebooksnapchat-2023-guide/"><u>Updated Add Emojis to Videos on YouTube/Facebook/Snapchat 2023 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/1719325788950-windows-users-create-a-self-hosted-free-chatgpt-copy-with-gpt4all/"><u>Windows Users, Create a Self-Hosted Free ChatGPT Copy with GPT4All.</u></a></li>
</ul></div>
