---
title: "Resurrecting Grayed Cursors: BIOS Update Guide"
date: 2024-09-11T09:38:25.108Z
updated: 2024-09-12T09:38:25.108Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Resurrecting Grayed Cursors: BIOS Update Guide"
excerpt: "This Article Describes Resurrecting Grayed Cursors: BIOS Update Guide"
keywords: Revive Cursor,Cursor Relaunch,Agey Cursor Fix,Cursor Rejuvenation,Grayed Cursor Aid,BIOS Update Tips,Cursor Recovery Guide
thumbnail: https://thmb.techidaily.com/da30e1ebb9eb5ab25a7effb66e03594a33963d6af1f63bbe87601ee182a33306.jpg
---

## Resurrecting Grayed Cursors: BIOS Update Guide

 Newer computers come with Unified Extensible Firmware Interface (UEFI) as the new standard. However, Legacy BIOS is still largely part of most active systems due to legacy software and hardware support. Switching from UEFI to Legacy BIOS is easy using the firmware utility. But what if the legacy boot option is grayed out in BIOS?

 This can happen for a few reasons. A common reason for the grayed-out BIOS is if you have Secure Boot or Platform Trusted Technology (TPM) enabled. Issues with Modern Standby supported system is another reason that prevents you from switching from UEFI to Legacy BIOS.

 Here is how to fix the Legacy Boot grayed-out in BIOS issue on your Windows system.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Causes the Legacy Boot Grayed Out Problem?

 You may find the Legacy Boot option grayed out if the UEFI settings, such as Secure Boot and TPM are enabled in the BIOS utility. In some instances, the BIOS utility can tell you why you can't switch to the Legacy boot option.

 Boot into your BIOS utility and open**Advanced Boot** **Options** . Next, check the**Enable Legacy Option ROMs** option. You may see an error prompt explaining why the Legacy option cannot be enabled. It usually hints that PPT/TPM or Secure Boot is enabled.

 If you don't have any such option, try the troubleshooting steps below to restore the Legacy boot option in BIOS.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2115933/19272" target="_top" id="2115933">
  <img src="//a.impactradius-go.com/display-ad/19272-2115933" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115933/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Click**Restart** to boot into the**Startup Menu.**  
![startup menu HP](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/startup-menu-hp-1.jpg)
2. In the Startup Menu, press**F10** to access the**BIOS Settings** . You may see other options depending on your computer manufacturer.
3. Use the right and left arrow keys to open the**Boot Options** tab in the BIOS Utility.
4. Next, use the up and down arrow key to highlight the**Secure Boot** option and press**Enter** to view more options.  
![disable secure boot bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-secure-boot-bios.jpg)
5. Select**Disabled** and make sure the changes are shown in the Boot Options tab.
6. Press**F10** to save the changes and disable Secure Boot.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Disable Trusted Platform Technology (TPM)

![disable TPM state BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-tpm-state-bios-1.jpg)

<!-- affiliate ads begin -->
<span id="1328683">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328683.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328683">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328683.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328683%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328683/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In addition to Secure Boot, you may also have enabled Trusted Platform Module (TPM), disabling Legacy BIOS. To fix the issue, check if TPM is enabled on your PC, which is likely a case on a Windows 11 running system, and disable the option if necessary.

 You can disable TPM from the BIOS setup utility. Here's how to do it.

1. Boot into your BIOS utility using the**Windows Recovery Menu.**
2. Next, open the**Security** tab using the right and left arrow keys.
3. Highlight the**TPM State** option and press**Enter** . If no TPM option is available, look for the**PTT** option.
4. Select**Disabled** to disable TPM on your device.
5. Press**F10** to save the change and exit.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Disable Modern Standby

 Modern Standby (S0) is a newer power mode available on select modern computers. It is enabled by default on compatible systems but can cause issues with Legacy Boot.

 To fix the issue, try to[disable Modern Standby on your Windows computer](https://www.makeuseof.com/windows-disable-modern-standby/) . Once disabled, restart your PC to see if you can switch to Legacy Boot now.

<!-- affiliate ads begin -->
<span id="2127886">
					<video width="576" height="1024" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2127886.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2127886">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2127886.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2127886%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2127886/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-hints.techidaily.com/new-20-leading-no-cost-digital-editing-platforms/"><u>[New] 20 Leading No-Cost Digital Editing Platforms</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-acclaimed-20-open-source-pubg-thumbnail-bundles/"><u>[New] Acclaimed 20 Open Source PUBG Thumbnail Bundles</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-advanced-strategies-for-endless-online-spaces/"><u>[New] Advanced Strategies for Endless Online Spaces</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-boost-your-meeting-impact-with-efficient-screen-sharing/"><u>[Updated] 2024 Approved Boost Your Meeting Impact with Efficient Screen Sharing</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-explore-the-highest-rated-virtual-reality-games/"><u>[Updated] 2024 Approved Explore the Highest-Rated Virtual Reality Games</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-perfect-your-video-calls-essential-10-free-recording-solutions-for-slack/"><u>[Updated] 2024 Approved Perfect Your Video Calls Essential 10 Free Recording Solutions for Slack</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-harnessing-home-content-a-commercialized-vlog-journey/"><u>[Updated] Harnessing Home Content A Commercialized Vlog Journey</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-online-gaming-earnings-in-the-future/"><u>[Updated] Online Gaming Earnings in the Future</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-seamless-integration-share-confidential-youtube-videos-on-gmail-for-2024/"><u>[Updated] Seamless Integration Share Confidential YouTube Videos on Gmail for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-efficiently-change-your-facebook-videos-into-mp3-songs/"><u>2024 Approved Efficiently Change Your Facebook Videos Into MP3 Songs</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/anticipating-apples-latest-innovation-the-sx-series-watch-price-estimates-and-launch-predictions-amidst-swirling-rumors/"><u>Anticipating Apple's Latest Innovation: The SX Series Watch, Price Estimates & Launch Predictions Amidst Swirling Rumors</u></a></li>
<li><a href="https://techtrends.techidaily.com/are-you-really-receiving-authentic-dolby-atmos-acoustics/"><u>Are You Really Receiving Authentic Dolby Atmos Acoustics?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/convergence-video-haute-definition-pour-apple-macintosh-convertisseurs-gratuits-and-premium-par-des-experts-envisagez-le-changement/"><u>Convergence Vidéo Haute Définition Pour Apple Macintosh: Convertisseurs Gratuits & Premium Par Des Experts Envisagez Le Changement!</u></a></li>
<li><a href="https://win11.techidaily.com/cracking-the-code-windows-versioning-insight/"><u>Cracking the Code: Windows Versioning Insight</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-samsung-galaxy-z-fold-5-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Samsung Galaxy Z Fold 5 Location Settings | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/electrical-use-analysis-for-windows-computers-unveiled/"><u>Electrical Use Analysis for Windows Computers Unveiled</u></a></li>
<li><a href="https://extra-information.techidaily.com/elevate-drones-to-new-peaks-with-these-crucial-supplementary-gear/"><u>Elevate Drones to New Peaks with These Crucial Supplementary Gear</u></a></li>
<li><a href="https://win11.techidaily.com/elusive-search-icon-techniques-for-windows-11/"><u>Elusive Search Icon Techniques for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-windows-1111-ui-for-auto-check-updates/"><u>Enabling Windows 11/11 UI for Auto-Check Updates</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-context-menu-with-submenus/"><u>Enhancing Windows 11 Context Menu with Submenus</u></a></li>
<li><a href="https://sound-issues.techidaily.com/expert-advice-overcoming-common-voice-chat-glitches-in-the-game-of-valorant/"><u>Expert Advice: Overcoming Common Voice Chat Glitches in the Game of VALORANT</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/exploring-the-new-apple-tv-4k-high-definition-streaming-and-intuitive-voice-controls-evaluated/"><u>Exploring the New Apple TV 4K : High-Definition Streaming and Intuitive Voice Controls Evaluated</u></a></li>
<li><a href="https://win11.techidaily.com/harness-powertoys-for-rapid-file-naming-tasks/"><u>Harness PowerToys for Rapid File Naming Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-the-best-linux-features-with-windows-apps/"><u>How to Get the Best Linux Features With Windows Apps</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-honor-90-lite-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Honor 90 Lite Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-drive-engagement-tips-for-going-viral-on-instagram/"><u>In 2024, Drive Engagement Tips for Going Viral on Instagram</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-fun-flair-for-text-memes-with-easy-genrator/"><u>In 2024, Fun Flair for Text Memes with Easy Gen'rator</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-asus-rog-phone-8-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Asus ROG Phone 8 to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-pinpoint-and-eliminate-android-video-glitches/"><u>In 2024, Pinpoint & Eliminate Android Video Glitches</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-vivo-x100-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Vivo X100? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-vivo-y55s-5g-2023-for-parents-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Telegram Spy Tools On Vivo Y55s 5G (2023) for Parents | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-itel-s23-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Itel S23? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/instantaneous-implementation-microsoft-works-for-windows-10plus/"><u>Instantaneous Implementation: Microsoft Works for Windows 10+</u></a></li>
<li><a href="https://win11.techidaily.com/intro-to-windows-accessibility-must-know-tips/"><u>Intro to Windows Accessibility: Must-Know Tips</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-xbox-mic-troubleshooting-in-windows-11-platforms/"><u>Mastering Xbox Mic Troubleshooting in Windows 11 Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-functional-adjustments-windows-1011-edition/"><u>Navigating Functional Adjustments: Windows 10/11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-network-navigation-for-the-elusive-mac-on-windows-11/"><u>Navigating Network Navigation for the Elusive MAC on WIndows 11</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-unrealcefsubprocess-for-lower-cpu-and-memory-usage/"><u>Optimizing UnrealCEFSubprocess for Lower CPU and Memory Usage</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-ui-fidelity-on-newest-windows-release/"><u>Perfecting UI Fidelity on Newest Windows Release</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-your-user-directory-naming/"><u>Personalizing Your User Directory Naming</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/professional-screen-capture-tools-reviewed-bandicam-and-camtasia-for-2024/"><u>Professional Screen Capture Tools Reviewed Bandicam & Camtasia for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/purple-pandemonium-a-guide-to-regaining-your-pcs-true-colors/"><u>Purple Pandemonium? A Guide to Regaining Your PC's True Colors</u></a></li>
<li><a href="https://win11.techidaily.com/quickly-link-tofrom-bing-chat-in-windows-11-search-field/"><u>Quickly Link To/From Bing Chat in Windows 11 Search Field</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reinforced-graphics-elevating-edges-protected-mode/"><u>Reinforced Graphics: Elevating Edge's Protected Mode</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-incomplete-network-prompt-guidance-on-windows/"><u>Resolving Incomplete Network Prompt Guidance on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-visual-placement-on-windows-devices/"><u>Reversing Visual Placement on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/reverting-custom-sort-and-group-order-of-files/"><u>Reverting Custom Sort and Group Order of Files</u></a></li>
<li><a href="https://techidaily.com/sign-docm-file-online-for-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>Sign .docm file Online for Free</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-sony-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from Sony</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-game-with-expert-multitasking-techniques-for-windows-11/"><u>Step Up Your Game with Expert Multitasking Techniques for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/stop-spotify-on-windows-startup-by-default/"><u>Stop Spotify on Windows Startup by Default</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ten-clear-indicators-of-pc-needs-a-factory-start/"><u>Ten Clear Indicators of PC Needs a Factory Start</u></a></li>
<li><a href="https://win11.techidaily.com/the-comprehensive-guide-to-disbanding-disk-divisions-in-win-os/"><u>The Comprehensive Guide to Disbanding Disk Divisions in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-purging-windows-drives-partition-units/"><u>The Ultimate Guide to Purging Windows Drives' Partition Units</u></a></li>
<li><a href="https://win11.techidaily.com/time-tracker-tweaks-top-apps-to-modify-file-timestamps-on-pc/"><u>Time Tracker Tweaks: Top Apps to Modify File Timestamps on PC</u></a></li>
<li><a href="https://win11.techidaily.com/top-six-strategies-to-scale-your-photos-on-windows-11-effectively/"><u>Top Six Strategies to Scale Your Photos on Windows 11 Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-into-a-personalized-oasis-8-winbubble-upgrades/"><u>Transform Windows Into a Personalized Oasis: 8 WinBubble Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-your-digital-music-library-a-comprehensive-guide-on-mp3-to-cd-conversion-with-imgburn-windows/"><u>Transforming Your Digital Music Library: A Comprehensive Guide on Mp3 to CD Conversion with ImgBurn (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/turning-phones-into-windows-audio-input/"><u>Turning Phones Into Windows Audio Input</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-premiere-pro-template-guide-no-cost-for-2024/"><u>Ultimate Premiere Pro Template Guide - No Cost for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-audacitys-windows-compatibility-issue-9999/"><u>Unlocking Audacity's Windows Compatibility Issue #9999</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secrets-disable-windows-11-tpm-effortlessly/"><u>Unlocking Secrets: Disable Windows 11 TPM Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secrets-fixing-windows-remote-desktop-errors/"><u>Unlocking Secrets: Fixing Windows Remote Desktop Errors</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-speech-technology-navigating-shortcuts-on-win-11/"><u>Unlocking Speech Technology: Navigating Shortcuts on Win 11</u></a></li>
</ul></div>

