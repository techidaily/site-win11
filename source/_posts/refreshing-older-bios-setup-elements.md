---
title: Refreshing Older BIOS Setup Elements
date: 2024-08-16T00:27:39.933Z
updated: 2024-08-17T00:27:39.933Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Refreshing Older BIOS Setup Elements
excerpt: This Article Describes Refreshing Older BIOS Setup Elements
keywords: Refresh BIOS Basics,Update BIOS Interface,Modernize BIOS Layout,Revitalize BIOS Settings,Improve BIOS User Experience,Enhance BIOS Navigation,Streamline BIOS Functions
thumbnail: https://thmb.techidaily.com/07ec08194f82a5c0eb7f1dbd160d4285a74e061c99e34448dc11e18d2afb1ddd.png
---

## Refreshing Older BIOS Setup Elements

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to [disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-covert-snapsnapper-stealth-techniques-for-picture-capture/"><u>[New] 2024 Approved  Covert SnapSnapper  Stealth Techniques for Picture Capture</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-make-a-thumbnail-for-your-youtube-free-easily/"><u>[New] 2024 Approved  How to Make a Thumbnail for Your YouTube Free Easily</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-full-disclosure-ricoh-theta-s-inside-and-out/"><u>[New] Full Disclosure  Ricoh Theta S Inside & Out</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/n-2024-harness-the-power-of-engagement-boosting-youtube-traffic/"><u>[New] In 2024, Harness the Power of Engagement  Boosting YouTube Traffic</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-comparing-top-free-players-vlc-or-mpc/"><u>[Updated] In 2024, Comparing Top Free Players  VLC or MPC?</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-prime-8-tripod-picks-for-exceptional-4k-footage/"><u>[Updated] Prime 8 Tripod Picks for Exceptional 4K Footage</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-seize-control-of-your-viewing-experience-these-top-6-free-youtube-short-downloaders/"><u>[Updated] Seize Control of Your Viewing Experience  These Top 6 Free YouTube Short Downloaders</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-comprehensive-acid-pro-evaluation-and-alternative-software/"><u>2024 Approved  Comprehensive ACID Pro Evaluation & Alternative Software</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-haul-videography-101-preparation-and-editing-for-maximum-impact/"><u>2024 Approved  Haul Videography 101  Preparation & Editing for Maximum Impact</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-hidden-gems-for-private-insta-story-viewing/"><u>2024 Approved  Hidden Gems for Private Insta Story Viewing</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-5-audio-to-video-makers-online/"><u>2024 Approved  Top 5 Audio to Video Makers Online</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-motorola-moto-g84-5g-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Motorola Moto G84 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnected-from-vpn-client-errors/"><u>Addressing Disconnected From VPN Client Errors</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-software-for-live-broadcasting/"><u>Best Software for Live Broadcasting</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-your-vms-with-virtualbox-70-now-for-windows-11-users/"><u>Boosting Your VMs with VirtualBox 7.0, Now for Windows 11 Users</u></a></li>
<li><a href="https://games-able.techidaily.com/capture-the-dreamcatcher-spirit-playing-game-on-android/"><u>Capture the Dreamcatcher Spirit: Playing Game on Android</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-backup-error-in-windows-file-history-configuration/"><u>Correcting “Backup Error” In Windows File History Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-how-choosing-a-pc-over-a-mac-can-benefit-you-more-9/"><u>Decoding How Choosing a PC Over A Mac Can Benefit You More (#9)</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-text-glyphs-in-windows-11/"><u>Discovering Text Glyphs in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/effective-strategies-for-identifying-high-space-usage-windows/"><u>Effective Strategies for Identifying High-Space Usage Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliciting-hidden-taskbar-recon-in-windows-11/"><u>Eliciting Hidden Taskbar Recon in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-your-taskbar-clarity-with-w11-tricks/"><u>Enhancing Your Taskbar Clarity with W11 Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/expert-methods-purging-directdraw-problems-from-win1011-systems/"><u>Expert Methods: Purging DirectDraw Problems From WIN10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-methods-for-tcpip-port-audits-on-windows/"><u>Exploring Methods for TCP/IP Port Audits on Windows</u></a></li>
<li><a href="https://win-forum.techidaily.com/exploring-todays-leading-social-networks-the-impact-of-facebook-twitter-instagram-and-youtube/"><u>Exploring Today's Leading Social Networks: The Impact of Facebook, Twitter, Instagram, and YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/from-browsers-to-desktops-website-conversion-guide/"><u>From Browsers to Desktops: Website Conversion Guide</u></a></li>
<li><a href="https://win11.techidaily.com/growth-plans-for-windows-hard-drive-without-data-loss/"><u>Growth Plans for Windows Hard Drive without Data Loss</u></a></li>
<li><a href="https://win11.techidaily.com/guide-dealing-with-invalid-app-installs-on-windows/"><u>Guide: Dealing with Invalid App Installs on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-requested-operation-requires-elevation-error-740-on-windows-10-and-11/"><u>How to Fix the “Requested Operation Requires Elevation” Error 740 on Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-windows-this-device-is-being-used-by-another-application-audio-error/"><u>How to Fix Windows' This Device Is Being Used by Another Application Audio Error</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-14-pro-ios-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone 14 Pro iOS? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-poco-c55-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Poco C55? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-honor-magic-v2-phone-forgot-password-by-drfone-android-unlock-android-unlock/"><u>How to Unlock Honor Magic V2 Phone Forgot Password</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-instagrams-inconsistent-video-timings/"><u>In 2024, Navigating Instagram's Inconsistent Video Timings</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-smileshop-memelore-hub/"><u>In 2024, SmileShop  Memelore Hub</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-top-10-hilarious-tiktok-skits-unveiled/"><u>In 2024, Top 10 Hilarious TikTok Skits Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-elevated-commands-always-access-terminal-as-admin/"><u>Mastering Elevated Commands: Always Access Terminal as Admin</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-iphones-podcast-downloads-made-easy-for-2024/"><u>Mastering iPhones  Podcast Downloads Made Easy for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-microsoft-store-eradicating-code-0x80072f30/"><u>Mastering the Microsoft Store: Eradicating Code 0X80072F30</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-browser-blues-overcome-site-blockades-with-these-tips/"><u>Microsoft Browser Blues? Overcome Site Blockades with These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/multitasking-made-simple-windows-1110-window-cascade-guide/"><u>Multitasking Made Simple: Windows 11/10 Window Cascade Guide</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-deletion-warning-settings-on-pcs/"><u>Navigating Deletion Warning Settings on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/no-illusions-allowed-true-tales-of-unmasking-windows-ploys/"><u>No Illusions Allowed: True Tales of Unmasking Windows Ploys</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-nonexistent-hardware-warning-in-windows/"><u>Overcoming Nonexistent Hardware Warning in WIndows</u></a></li>
<li><a href="https://win11.techidaily.com/premium-laptops-highlighted-at-ifa-2023/"><u>Premium Laptops Highlighted at IFA 2023</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/pro-tips-for-capturing-360-degree-fisheye-photos-for-2024/"><u>Pro Tips for Capturing 360-Degree Fisheye Photos for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-vivo-y200-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Vivo Y200 to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/proven-windows-11-ways-to-boost-workflow-and-productivity-45/"><u>Proven Windows 11 Ways to Boost Workflow and Productivity (45)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/rapid-bavarder-configuration-guide-for-linux/"><u>Rapid Bavarder Configuration Guide for Linux</u></a></li>
<li><a href="https://win11.techidaily.com/reintroduce-missing-cameras-to-device-manager-display/"><u>Reintroduce Missing Cameras to Device Manager Display</u></a></li>
<li><a href="https://win11.techidaily.com/reinvent-the-way-you-handle-aging-pcs-less-windows/"><u>Reinvent the Way You Handle Aging PCs: Less Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-code-a00f425d-on-windows-11-camera-app/"><u>Resolving Error Code A00F425D on Windows 11 Camera App</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unlinked-files-and-absence-of-assigned-apps-win/"><u>Resolving Unlinked Files and Absence of Assigned Apps (Win)</u></a></li>
<li><a href="https://win11.techidaily.com/saving-yourself-from-install-error-in-discord-set-up/"><u>Saving Yourself From Install Error in Discord Set-Up</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-mastery-in-artificially-inspired-visuals-using-paint-cocreator-on-win11/"><u>Step-by-Step Mastery in Artificially Inspired Visuals Using Paint Cocreator on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-improve-performance-of-a-non-responsive-windows-folder/"><u>Strategies to Improve Performance of a Non-Responsive Windows Folder</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-tasks-using-supercharged-run-tool-in-windows-1011/"><u>Streamline Tasks Using Supercharged Run Tool in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-user-administration-in-windows-11/"><u>Streamlining User Administration in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-broken-usb-connections-on-windows-systems/"><u>Tackling Broken USB Connections on Windows Systems</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-honor-play-8t-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your Honor Play 8T Phone Hassle-Free</u></a></li>
<li><a href="https://win11.techidaily.com/the-unopened-notepad-predicament-solutions-to-make-it-open-once-more/"><u>The Unopened Notepad Predicament: Solutions to Make It Open Once More</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-an-improved-taskbar-on-windows-11/"><u>Tips for an Improved Taskbar on Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/top-apps-and-online-tools-to-track-vivo-y27-4g-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Vivo Y27 4G Phone With/Without IMEI Number</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-ringtone-bazaar-navigating-online-sound-archives-for-2024/"><u>Ultimate Ringtone Bazaar  Navigating Online Sound Archives for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-file-explorers-gallery-view-capability/"><u>Unlocking File Explorer's Gallery View Capability</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-realme-11-pro-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Realme 11 Pro Device</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unlocking-the-magic-advanced-techniques-for-tiktok-videos-for-2024/"><u>Unlocking the Magic  Advanced Techniques for TikTok Videos for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-tecno-spark-20c-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Tecno Spark 20C? Here Is the Answer | Dr.fone</u></a></li>
</ul></div>
