---
title: Overcoming Outdated BOOT Options Gray
date: 2024-08-15T23:33:32.962Z
updated: 2024-08-16T23:33:32.962Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Outdated BOOT Options Gray
excerpt: This Article Describes Overcoming Outdated BOOT Options Gray
keywords: Old BOOT Fixed,Revise Boot Settings,Update Boot Configs,Modernize System BOOT,Resolve Boot Glitches,Enhance BOOT Options,Correct BOOT Errors
thumbnail: https://thmb.techidaily.com/92459487433dd8191ecb6f79f9b025b7d93038fc1418a5a54e50bbd98af412de.jpg
---

## Overcoming Outdated BOOT Options Gray

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537547&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/vcfpro.png" border="0">Video Converter Factory Pro</a>
<!-- affiliate ads end -->
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to [disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-maximizing-tv-viewership-for-facebook-live-events/"><u>[New] 2024 Approved  Maximizing TV Viewership for Facebook Live Events</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-the-essence-of-polarr-revolutionizing-digital-photography/"><u>[New] 2024 Approved  The Essence of Polarr  Revolutionizing Digital Photography</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-banish-your-flickering-facebook-feeds-for-2024/"><u>[New] Banish Your Flickering Facebook Feeds for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-from-youtube-to-instagram-sharing-video-content-with-ease-for-2024/"><u>[New] From YouTube to Instagram  Sharing Video Content with Ease for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-deleting-facebook-stories-laptop-and-mobile-guide/"><u>[New] In 2024, Deleting Facebook Stories  Laptop & Mobile Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-onestepcams-evaluation-are-we-overlooking-gems-for-2024/"><u>[New] OneStepCams Evaluation  Are We Overlooking Gems for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-7-best-vocal-modification-software-on-the-market/"><u>[Updated] 2024 Approved  7 Best Vocal Modification Software on the Market</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-audience-retention-through-reel-magic-boomers-on-ig/"><u>[Updated] 2024 Approved  Audience Retention Through Reel Magic  Boomers on IG</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exclusive-content-review-the-best-15-youtube-unboxers-of-2024/"><u>[Updated] Exclusive Content Review  The Best 15 YouTube Unboxers of 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-gain-momentum-with-these-strategies-for-trending-youtubers-for-2024/"><u>[Updated] Gain Momentum with These Strategies for Trending YouTubers for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-skyrocketing-fb-engagement-masterful-seo-techniques-explored-for-2024/"><u>[Updated] Skyrocketing FB Engagement  Masterful SEO Techniques Explored for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-the-ultimate-guide-to-choosing-between-gopro-and-yi-for-2024/"><u>[Updated] The Ultimate Guide to Choosing Between GoPro and Yi for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-urban-elegance-best-6-modern-mc-mansions-for-2024/"><u>[Updated] Urban Elegance  Best 6 Modern MC Mansions for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-your-own-soundtrack-awaits-step-by-step-youtube-playlist-creation-guide-webmobile/"><u>[Updated] Your Own Soundtrack Awaits  Step-by-Step YouTube Playlist Creation Guide (Web/Mobile)</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-boosting-tiktok-quality-with-smart-zoom-use/"><u>2024 Approved  Boosting TikTok Quality with Smart Zoom Use</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-expertly-manipulating-colors-in-video-edits/"><u>2024 Approved  Expertly Manipulating Colors in Video Edits</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-prime-gpus-for-sharp-4k-image-display/"><u>2024 Approved  Prime GPUs for Sharp 4K Image Display</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/2024-approved-step-by-step-guide-to-compliant-twitter-media-posts/"><u>2024 Approved  Step-by-Step Guide to Compliant Twitter Media Posts</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-the-best-of-both-worlds-screenflow-for-mac-creatives-reviewed/"><u>2024 Approved  The Best of Both Worlds  ScreenFlow for Mac Creatives Reviewed</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-10-naming-algorithms-for-podcast-mastery/"><u>2024 Approved  Top 10 Naming Algorithms for Podcast Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/a-novices-guide-to-windows-11-sound-capture/"><u>A Novice's Guide to Windows 11 Sound Capture</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-blink-quick-fixes-for-input-lag-on-latest-microsoft-os/"><u>Beat the Blink: Quick Fixes for Input Lag on Latest Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-generations-old-games-with-dosbox-x/"><u>Bridging Generations: Old Games with DOSBox-X</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-vivo-v29-pro-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Vivo V29 Pro is off? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/determining-the-ideal-nearby-networking-method-google-vs-windows/"><u>Determining the Ideal Nearby Networking Method: Google Vs. Windows</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-fixing-the-frozen-resource-monitor-app-in-win11/"><u>Diagnosing and Fixing the Frozen Resource Monitor App in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-source-of-windows-parse-error-0xc00ce556/"><u>Dissecting the Source of Windows' Parse Error 0xC00CE556</u></a></li>
<li><a href="https://win11.techidaily.com/enable-microphone-and-camera-via-app-guard-in-windows-11/"><u>Enable Microphone & Camera via App Guard in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enrich-your-galaxy-experience-utilizing-the-dex-app-in-windows/"><u>Enrich Your Galaxy Experience: Utilizing the DeX App in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/esd-file-transformation-mastery-your-pathway-to-windows-iso-success/"><u>ESD File Transformation Mastery: Your Pathway to Windows ISO Success</u></a></li>
<li><a href="https://win11.techidaily.com/expanding-windows-hard-drive-sustainably/"><u>Expanding Windows Hard Drive Sustainably</u></a></li>
<li><a href="https://win11.techidaily.com/fix-slow-download-issues-in-steam-on-windows-platform/"><u>Fix Slow Download Issues in Steam on Windows Platform</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-absent-windows-notification-icons/"><u>Fixes for Absent Windows Notification Icons</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-an-application-not-installed-via-microsofts-store/"><u>Fixing an Application Not Installed via Microsoft's Store</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-installer-access-rights-shortcomings/"><u>Fixing Windows Installer Access Rights Shortcomings</u></a></li>
<li><a href="https://win11.techidaily.com/from-emulator-to-operating-system-windows-for-steam-deck/"><u>From Emulator to Operating System: Windows for Steam Deck</u></a></li>
<li><a href="https://techidaily.com/how-do-i-reset-my-infinix-smart-8-pro-phone-without-technical-knowledge-drfone-by-drfone-reset-android-reset-android/"><u>How do I reset my Infinix Smart 8 Pro Phone without technical knowledge? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-infinix-note-30-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Infinix Note 30 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3-ways-to-fake-gps-without-root-on-xiaomi-redmi-13c-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Fake GPS Without Root On Xiaomi Redmi 13C | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-about-sony-xperia-10-v-frp-bypass-by-drfone-android/"><u>In 2024, About Sony Xperia 10 V FRP Bypass</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-leading-edge-approaches-in-spotifys-advertising-realm/"><u>In 2024, Leading Edge Approaches in Spotify's Advertising Realm</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-proven-strategies-for-precise-web-based-photo-cropping/"><u>In 2024, Proven Strategies for Precise Web-Based Photo Cropping</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-proficiency-the-path-to-mastering-project/"><u>Keyboard Proficiency: The Path to Mastering Project</u></a></li>
<li><a href="https://extra-information.techidaily.com/layer-audio-onto-video-clips-in-premiere-pro/"><u>Layer Audio Onto Video Clips in Premiere Pro</u></a></li>
<li><a href="https://win11.techidaily.com/1719286453674-library-installation/"><u>Library Installation:</u></a></li>
<li><a href="https://win11.techidaily.com/lightening-windows-11-startup-latency-tips-for-a-speedy-launch/"><u>Lightening Windows 11 Startup Latency – Tips for a Speedy Launch</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-adding-folders-without-delays-in-windows-onedrive/"><u>Mastering the Art of Adding Folders without Delays in Windows OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-app-changes-in-the-latest-windows-11-update/"><u>Navigating App Changes in the Latest Windows 11 Update</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-final-cut-pro-x-crash-fix-solutions/"><u>New 2024 Approved Final Cut Pro X Crash Fix Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unable-to-detect-camera-in-win11/"><u>Overcoming Unable to Detect Camera in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/preventive-measures-for-windows-safescreensaver-alteration/"><u>Preventive Measures for Windows SafeScreensaver Alteration</u></a></li>
<li><a href="https://extra-tips.techidaily.com/professionals-choice-best-drone-gimbals/"><u>Professional's Choice  Best Drone Gimbals</u></a></li>
<li><a href="https://win11.techidaily.com/reset-and-reboot-your-way-back-into-the-ms-store-windows-11/"><u>Reset & Reboot Your Way Back Into the MS Store (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/six-easy-steps-to-knowing-the-model-behind-your-pc-windows-edition/"><u>Six Easy Steps To Knowing The Model Behind Your PC Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/solving-win-error-no-access-to-network-paths/"><u>Solving WIN Error: No Access to Network Paths</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-10-file-organization-hacks-max-156/"><u>Streamlining Windows: 10 File Organization Hacks (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/tech-guide-uninstalling-the-microsoft-store/"><u>Tech Guide: Uninstalling the Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/terminal-insight-discover-public-ip-in-windows-1110/"><u>Terminal Insight: Discover Public IP in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-in-speed-mastering-double-click-on-windows-pc/"><u>Triumph in Speed: Mastering Double-Click on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-with-file-explorer-on-win11-effective-repair-methods/"><u>Trouble with File Explorer on Win11? Effective Repair Methods</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-interruptexception-solution-for-win11/"><u>Unveiling INTERRUPT_EXCEPTION Solution for Win11</u></a></li>
</ul></div>
