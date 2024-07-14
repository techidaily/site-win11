---
title: Reinstating Legacy Boot Configurations
date: 2024-07-13T09:47:31.908Z
updated: 2024-07-14T09:47:31.908Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstating Legacy Boot Configurations
excerpt: This Article Describes Reinstating Legacy Boot Configurations
keywords: Legacy BIOS Setup,Boot Configuration Restore,System Boot Legacy,Re-Enable Old Boots,Revive Legacy Boot,Backup Boot Configs,Legacy Boot Management
thumbnail: https://thmb.techidaily.com/67c52f8f8d1e1c526acfd18d30076a8ec8c694652a5ccde76155c26629dae8fb.png
---

## Reinstating Legacy Boot Configurations

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

## 1\. Disable Secure Boot to Enable Boot

 Secure Boot is a UEFI feature that protects your computer against malware by allowing only trusted system software to run on your computer. When enabled, it will perform a cryptographic check during the boot process to verify the integrity of the system image.

 However, if you have Secure Boot enabled, it will likely disable Legacy Boot as well. You'll need to [disable Secure Boot in your BIOS utility](https://www.makeuseof.com/tag/disable-secure-uefi-dual-boot/) to fix the issue.

 The below steps to disable Secure Boot are for an HP Pavilion computer. For other systems, refer to your system manual.

To disable secure boot:

1. Click on**Start** and then click on**Power** .
2. Press and hold the**Shift key** and click on**Restart** . Confirm the action if necessary.
3. Release the**Shift** key as the PC shuts down and boot into the**Recovery Menu.**
4. Go to**Troubleshoot** and click on**Advanced options** .
5. Next, click on**UEFI Firmware Settings.**  
![Advanced OptionspUEFI Firmware Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/advanced-optionspuefi-firmware-settings.jpg)

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

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

 To fix the issue, try to [disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

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
<li><a href="https://digital-screen-recording.techidaily.com/expertly-selected-8-recording-software/"><u>Expertly Selected 8 Recording Software</u></a></li>
<li><a href="https://win11.techidaily.com/modifying-account-lockout-tally-post-unsuccessful-login-attempts-in-windows-1011/"><u>Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-task-management-in-windows-11-via-enhanced-run-functionality/"><u>Optimizing Task Management in Windows 11 via Enhanced Run Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-to-rejuvenate-a-non-operative-resource-monitor-in-windows-11/"><u>Quick Fixes to Rejuvenate a Non-Operative Resource Monitor in Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-professional-video-resizer-suite/"><u>[New] Professional Video Resizer Suite</u></a></li>
<li><a href="https://screen-recording.techidaily.com/game-recording-mastery-utilizing-gameye-and-more/"><u>Game Recording Mastery  Utilizing GamEye and More</u></a></li>
<li><a href="https://win11.techidaily.com/finding-essential-data-win-pc-ip-and-mac-via-powershell/"><u>Finding Essential Data: Win PC IP & MAC via PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-change-windows-11-search-icon-from-a-text-bar/"><u>How to Change Windows 11 Search Icon From a Text Bar</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-wakeable-entities-on-dormant-windows/"><u>Controlling Wakeable Entities on Dormant Windows</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-beat-blast-updated-technology/"><u>[New] 2024 Approved  Beat Blast  Updated Technology</u></a></li>
<li><a href="https://win11.techidaily.com/boost-budget-efficiency-windows-11-pro-discounts/"><u>Boost Budget Efficiency: Windows 11 Pro Discounts</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-flight-expertise-unleashed-an-examination-of-dji-phantom-3-for-2024/"><u>[Updated] Flight Expertise Unleashed  An Examination of DJI Phantom 3 for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-the-beginners-guide-to-joining-facebook/"><u>[Updated] The Beginner's Guide to Joining Facebook</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-explore-the-most-effective-zoom-screen-recorders/"><u>In 2024, Explore the Most Effective Zoom Screen Recorders</u></a></li>
<li><a href="https://win11.techidaily.com/directly-to-dialer-windows-11-tutorial/"><u>Directly to Dialer: Windows 11 Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/windows-without-drive-letters-reasons-and-redeeming-solutions-explored/"><u>Windows Without Drive Letters: Reasons and Redeeming Solutions Explored</u></a></li>
<li><a href="https://win11.techidaily.com/from-easy-access-to-higher-security-transitioning-your-logon-method-on-windows-11/"><u>From Easy Access to Higher Security: Transitioning Your Logon Method on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-rectify-erroneous-device-listings-in-windows/"><u>Guidelines to Rectify Erroneous Device Listings in Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-oppo-a78-5g-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Oppo A78 5G Phone? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-a-step-by-written-by-a-lawyer/"><u>2024 Approved  A Step-By Written by a Lawyer?</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-how-to-change-your-voice-on-audacity/"><u>New How to Change Your Voice on Audacity?</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-microsoft-hololens-review-a-glimpse-of-holographic-future/"><u>2024 Approved  Microsoft HoloLens Review- a Glimpse of Holographic Future</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-screen-capture-tool-in-windows-11-swiftly/"><u>Navigate to Screen Capture Tool in Windows 11 Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/essential-insights-into-os-upgrade-schedules-and-methods/"><u>Essential Insights Into OS Upgrade Schedules & Methods</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-start-the-quick-assist-tool-in-windows-11/"><u>How to Start the Quick Assist Tool in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-mitigate-local-security-offline-issue/"><u>Essential Steps to Mitigate Local Security Offline Issue</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectify-screen-flickering-phenomena/"><u>Rectify Screen Flickering Phenomena</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-the-soft-bricked-realme-11-proplus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Realme 11 Pro+? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/critics-common-grumbles-windows-11-unveiled/"><u>Critics' Common Grumbles: Windows 11 Unveiled</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-mastering-aspect-ratios-for-engaging-social-media-content/"><u>New Mastering Aspect Ratios for Engaging Social Media Content</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-windows-1110s-required-privilege-error-code-0x80070522/"><u>Eradicating Windows 11/10'S “Required Privilege” Error: Code 0X80070522</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-crashes-sonic-frontiers-full-screen-fixes/"><u>Conquering Crashes: Sonic Frontiers Full-Screen Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-github-desktop-adoption-in-windows-11/"><u>Best Practices for GitHub Desktop Adoption in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-graphics-from-windows-search-interface/"><u>Clearing Graphics From Windows Search Interface</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-windows-temp-file-deletion-guide/"><u>Effortless Windows Temp File Deletion Guide</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/decoding-your-own-tiktok-trend-identifier-key/"><u>Decoding Your Own TikTok Trend Identifier Key</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/preferable-strategies-for-digital-tv-recording-via-pc-monitors-for-2024/"><u>Preferable Strategies for Digital TV Recording via PC Monitors for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-peak-productivity-configure-multiple-monitors-in-win11/"><u>Achieve Peak Productivity: Configure Multiple Monitors in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-why-you-cant-see-drive-letters-on-your-windows-system/"><u>Unveiling Why You Can't See Drive Letters on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-rectifying-epic-games-logins/"><u>Quick Guide to Rectifying Epic Games Logins</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-making-the-most-of-both-worlds-obs-and-zoom-guide/"><u>[New] Making the Most of Both Worlds  OBS & Zoom Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-win-os-files-editable-again/"><u>How to Make Win OS Files Editable Again</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-functional-state-in-dead-usb-ports-win-edition/"><u>Enabling Functional State in Dead USB Ports, Win Edition</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-action-cam-showdown-which-holds-the-crown-gopro-or-yi/"><u>2024 Approved  Action Cam Showdown  Which Holds the Crown - GoPro or Yi?</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-frozen-grammarly-app-a-windows-users-guide/"><u>Fixing Frozen Grammarly App: A Windows User's Guide</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-disable-microsoft-edge-tab-preloading-in-windows-11/"><u>4 Ways to Disable Microsoft Edge Tab Preloading in Windows 11</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-the-bottom-line-best-practices-for-ogg-conversion-for-2024/"><u>New The Bottom Line Best Practices for OGG Conversion for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-elevate-your-profile-with-vimeo-on-instagram/"><u>[Updated] In 2024, Elevate Your Profile with Vimeo on Instagram</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-caption-crafting-select-writing-apps-for-your-photos/"><u>2024 Approved  Caption Crafting  Select Writing Apps for Your Photos</u></a></li>
<li><a href="https://win11.techidaily.com/quick-and-efficient-downloads-tips-from-microsofts-store/"><u>Quick and Efficient Downloads: Tips From Microsoft’s Store</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-finest-zero-cost-windows-media-devices/"><u>Discover the Finest Zero-Cost Windows Media Devices</u></a></li>
<li><a href="https://win11.techidaily.com/win-volume-adjustment-reviving-dull-edges/"><u>Win Volume Adjustment: Reviving Dull Edges</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-exe-file-opener-failures-in-windows/"><u>Overcoming .exe File Opener Failures in Windows</u></a></li>
</ul></div>
