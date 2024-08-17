---
title: "Brightening Dull Cursors: Simple Steps"
date: 2024-08-15T23:35:59.594Z
updated: 2024-08-16T23:35:59.594Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Brightening Dull Cursors: Simple Steps"
excerpt: "This Article Describes Brightening Dull Cursors: Simple Steps"
keywords: Brighten Cursor,Dull Curser Tips,Enhance Mouse Glow,Fade Cursor Dark,Light Up Mouse,Improve Mouse Visibility,Brilliant Mouse Design
thumbnail: https://thmb.techidaily.com/843a2530bd30cf31b24741cc2e56b474bee5d065dd6fb56cbf786d1e09002e10.jpg
---

## Brightening Dull Cursors: Simple Steps

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
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->

 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to [disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-free-video-conferencing-excellence-plus-screen-sharing-guide/"><u>[New] 2024 Approved  Free Video Conferencing Excellence + Screen Sharing Guide</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-explore-and-compare-apps-via-az-recorder/"><u>[New] Explore & Compare Apps via AZ Recorder</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-movavi-screen-recorder-11-review/"><u>[New] Movavi Screen Recorder 11 Review</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-securing-photo-libraries-without-copyright-notices-for-2024/"><u>[New] Securing Photo Libraries Without Copyright Notices for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-transform-textual-treasures-ae-font-exploration/"><u>[New] Transform Textual Treasures  AE Font Exploration</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-sifting-through-legacy-works-a-cultural-journey/"><u>[Updated] 2024 Approved  Sifting Through Legacy Works  A Cultural Journey</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-charting-new-heights-with-popular-youtube-content/"><u>[Updated] Charting New Heights with Popular YouTube Content</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-financial-flourishing-with-glamour-vlogs/"><u>[Updated] Financial Flourishing with Glamour Vlogs</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-gaming-streams-best-recording-programs-for-2024/"><u>[Updated] Gaming Streams  Best Recording Programs for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-prime-10-channel-list-best-history-yt-groups/"><u>[Updated] Prime 10 Channel List  Best History YT Groups</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-health-advocacy-through-strategic-social-media-plays/"><u>2024 Approved  Health Advocacy Through Strategic Social Media Plays</u></a></li>
<li><a href="https://win11.techidaily.com/5-fun-tricks-you-can-do-in-command-prompt/"><u>5 Fun Tricks You Can Do in Command Prompt</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-complete-guide-to-oem-unlocking-on-motorola-moto-g23-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Motorola Moto G23</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreenas-for-navigating-windows-11s-troubleshooter/"><u>A Compreenas for Navigating Windows 11'S Troubleshooter</u></a></li>
<li><a href="https://win11.techidaily.com/a-journey-into-celestial-mastery-windows-11s-divine-control/"><u>A Journey Into Celestial Mastery: Windows 11'S Divine Control</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-rectify-a-wrongly-setup-temp-folder-in-win11/"><u>A Step-by-Step Guide to Rectify a Wrongly Setup Temp Folder in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/a-tri-method-approach-to-understanding-and-applying-windows-policies/"><u>A Tri-Method Approach to Understanding and Applying Windows Policies</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-success-reinstalling-microsofts-pc-manager-in-winxp/"><u>Achieve Success: Reinstalling Microsoft's PC Manager in WinXP</u></a></li>
<li><a href="https://win11.techidaily.com/ad-free-experience-just-for-you-with-win-11/"><u>Ad-Free Experience, Just for You with Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failed-downloads-in-windows-environments/"><u>Addressing Failed Downloads in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-memory-usage-by-microsoft-edge-webview2/"><u>Addressing High-Memory Usage by Microsoft Edge WebView2</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inoperative-fault-finders-in-windows/"><u>Addressing Inoperative Fault Finders in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-installation-access-violation-on-win1011/"><u>Addressing Installation Access Violation on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-taskbar-latency-issues/"><u>Addressing Windows 11 Taskbar Latency Issues</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-disk-read-failures-on-your-pc/"><u>Avoiding Disk Read Failures on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/backup-basics-protecting-your-digital-adventures-in-epic-games/"><u>Backup Basics: Protecting Your Digital Adventures in Epic Games</u></a></li>
<li><a href="https://win11.techidaily.com/begin-your-windows-journey-with-a-voice-guide/"><u>Begin Your Windows Journey with a Voice Guide</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/best-10-free-video-translators-to-mitigate-translation-risks-for-2024/"><u>Best 10 Free Video Translators to Mitigate Translation Risks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-breach-are-windows-fingerprint-scanners-safe/"><u>Biometric Breach: Are Windows Fingerprint Scanners Safe?</u></a></li>
<li><a href="https://win11.techidaily.com/boost-keyboard-efficiency-top-strategies-for-speed-on-windows-devices/"><u>Boost Keyboard Efficiency: Top Strategies for Speed on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/boost-playnites-capabilities-with-windows-compatible-emulators/"><u>Boost Playnite's Capabilities with Windows-Compatible Emulators</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-barriers-fixing-steam-problems-on-windows-11-os/"><u>Breaking Down Barriers: Fixing Steam Problems on Windows 11 OS</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-vivo-y36-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Vivo Y36</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-itel-a60s-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Itel A60s Phone Screen?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-photo-perfection-at-your-fingertips-top-10-stickers-on-iphones-and-androids/"><u>In 2024, Photo Perfection at Your Fingertips  Top 10 Stickers on iPhones & Androids</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-quick-fix-hide-identities-in-photos-with-picart/"><u>In 2024, Quick Fix  Hide Identities in Photos with PicArt</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-ultimate-checklist-for-your-youtubes-most-impactful-visuals/"><u>In 2024, The Ultimate Checklist for Your YouTube's Most Impactful Visuals</u></a></li>
<li><a href="https://win-blog.techidaily.com/mastering-stability-solving-team-fortress-2-game-crashes/"><u>Mastering Stability: Solving Team Fortress 2 Game Crashes</u></a></li>
<li><a href="https://win11.techidaily.com/1719319611800-overcoming-challenges-in-full-screen-snip-and-sketch-capturing/"><u>Overcoming Challenges in Full-Screen Snip & Sketch Capturing.</u></a></li>
<li><a href="https://win11.techidaily.com/1719328295929-reduce-or-increase-software-size-on-windows-11-the-easy-way/"><u>Reduce or Increase Software Size on Windows 11 – The Easy Way!</u></a></li>
<li><a href="https://win11.techidaily.com/1719333062146-resolve-windows-scheduler-glitches-now/"><u>Resolve Windows Scheduler Glitches Now</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-dichotomy-of-cyberpunk-amoknforevew-a-game-with-glitches-and-greatness/"><u>The Dichotomy of Cyberpunk amoKN_FoRevEw, A Game with Glitches and Greatness</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-ultimate-hair-and-makeup-guide-on-youtubes-top-influencers-for-2024/"><u>The Ultimate Hair & Makeup Guide on YouTube's Top Influencers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719347016533-unlock-your-computers-print-command-solutions-for-faulty-wwinplusp-operations/"><u>Unlock Your Computer's Print Command: Solutions for Faulty WWin+P Operations.</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-samsung-galaxy-a15-4g-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Samsung Galaxy A15 4G Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
</ul></div>
