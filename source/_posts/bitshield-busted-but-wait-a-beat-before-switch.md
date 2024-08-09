---
title: BitShield Busted, But Wait a Beat Before Switch
date: 2024-08-08T13:15:47.913Z
updated: 2024-08-09T13:15:47.913Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes BitShield Busted, But Wait a Beat Before Switch
excerpt: This Article Describes BitShield Busted, But Wait a Beat Before Switch
keywords: BitGuard Failure,Postpone Security Shift,Risky Encryption Breach,Delay Secure Transition,Busted CyberShield,Hold Off Switch,Waiting on BitSecurity
thumbnail: https://thmb.techidaily.com/15566fd0d6cad9f26c793e08c16498fac2c5b48034aed23a907d05190328dc6a.png
---

## BitShield Busted, But Wait a Beat Before Switch

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## Is It Time to Ditch BitLocker?

 Interestingly, [Microsoft was already aware](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/countermeasures#attacker-countermeasures) of the potential for this attack. However, this is the first time a practical attack has surfaced at large, illustrating just how fast BitLocker encryption keys can be stolen.

 It raises the vital question of whether you should consider switching to a BitLocker alternative, like the [free and open-source VeraCrypt](https://www.makeuseof.com/encrypt-windows-system-drive-veracrypt/). The good news is that you don't need to jump ship for a few reasons.

 First, the exploit only works with external TPMs that request data from the module using the LPC bus. Most modern hardware integrates the TPM. While a motherboard-based TPM could theoretically be exploited, it would require more time, effort, and an extensive period with the target device. Extracting BitLocker Volume Master Key data from a TPM becomes even more difficult if the module is integrated into the CPU.

 AMD CPUs have integrated TPM 2.0 since 2016 (with the launch of AM4, known as fTPM), while Intel CPUs integrated TPM 2.0 with the launch of its 8th Generation Coffee Lake CPUs in 2017 (known as PTT). Suffice to say, if you're using a machine with an AMD or Intel CPU manufacturer after those dates, you're most likely safe.

 It's also worth noting that despite this exploit, BitLocker remains secure, and the actual encryption underpinning it, AES-128 or AES-256, is still secure.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/024-approved-unlocking-the-secrets-of-valorant-video-thumbnail-designs/"><u>[New] 2024 Approved  Unlocking the Secrets of Valorant Video Thumbnail Designs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-enhance-visuals-basic-ps-color-techniques/"><u>[New] In 2024, Enhance Visuals  Basic PS Color Techniques</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-the-smart-planners-guide-to-virtual-meeting-success/"><u>[Updated] 2024 Approved  The Smart Planner's Guide to Virtual Meeting Success</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-automating-subtitles-for-social-media-visuals-on-instagram/"><u>[Updated] Automating Subtitles for Social Media Visuals on Instagram</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-unlocking-the-potential-of-discord/"><u>[Updated] In 2024, Unlocking the Potential of Discord</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-strategies-for-itunes-podcast-enrollment-success/"><u>[Updated] Strategies for iTunes Podcast Enrollment Success</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-methods-for-iphone-image-arrangement/"><u>2024 Approved  Innovative Methods for iPhone Image Arrangement</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-youtube-glamour-a-guide-to-video-color-balance/"><u>2024 Approved  YouTube Glamour  A Guide to Video Color Balance</u></a></li>
<li><a href="https://win11.techidaily.com/boost-windows-11-search-11-tricks-for-a-functional-bar/"><u>Boost Windows 11 Search: 11 Tricks for a Functional Bar</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-messages-files-on-nord-3-5g-by-fonelab-android-recover-messages/"><u>Complete guide for recovering messages files on Nord 3 5G</u></a></li>
<li><a href="https://win11.techidaily.com/convenient-routines-installing-app-shortcuts-in-desktop-menu/"><u>Convenient Routines: Installing App Shortcuts in Desktop Menu</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/crafting-the-perfect-sound-for-stories-and-reels-on-instagram/"><u>Crafting the Perfect Sound for Stories & Reels on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-secrets-of-devhome-in-windows-11/"><u>Deciphering the Secrets of DevHome in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-guide-windows-obs-not-starting-issue-resolution/"><u>Detailed Guide: Windows OBS Not Starting Issue Resolution</u></a></li>
<li><a href="https://win11.techidaily.com/distinguishing-variations-between-exe-and-traditional-msis/"><u>Distinguishing Variations Between EXE and Traditional MSIs</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-package-unopenable-error-on-win11-10-oses/"><u>Eliminating the 'Package Unopenable' Error on Win11, 10 OSes</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-and-configuring-windows-sandbox-in-win-11/"><u>Enabling and Configuring Windows Sandbox in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-and-customizing-proxies-in-windows-11/"><u>Enabling and Customizing Proxies in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-11s-behind-the-scenes-sid-processes/"><u>Exploring Windows 11'S Behind-the-Scenes SID Processes</u></a></li>
<li><a href="https://win11.techidaily.com/grow-windows-capacity-without-file-loss/"><u>Grow Windows Capacity Without File Loss</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-overcoming-wmp-playback-issues/"><u>Guide to Overcoming WMP Playback Issues</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-wows-unexpected-crash-in-windows-1111/"><u>How to Tackle WoW’s Unexpected Crash in Windows 11/11</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-pro-level-insights-into-win11-enhancements/"><u>In 2024, Pro-Level Insights Into Win11 Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/is-the-outlook-app-not-syncing-on-windows-heres-how-to-fix-it/"><u>Is the Outlook App Not Syncing on Windows? Here’s How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-common-display-issues-in-modern-windows-versions/"><u>Overcoming Common Display Issues in Modern Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-disconnecting-printers-in-windows/"><u>Quick Fixes for Disconnecting Printers in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-addressing-windows-onedrive-errors-and-restoring-folder-integration/"><u>Quick Guide: Addressing Windows OneDrive Errors and Restoring Folder Integration</u></a></li>
<li><a href="https://win11.techidaily.com/re-activate-your-pc-addressing-error-code-22-in-windows-11/"><u>Re-Activate Your PC: Addressing Error Code 22 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-convenient-path-to-iis-manager-entry-point/"><u>The Convenient Path to IIS Manager Entry Point</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-code-0xc00d36b4-in-windows-11/"><u>Troubleshooting Error Code 0xC00D36B4 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-lost-connection-between-powershell-and-windows/"><u>Troubleshooting: Lost Connection Between PowerShell and Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-cpu-woes-strategies-from-windows-rm-window/"><u>Unraveling CPU Woes: Strategies From Windows' RM Window</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unraveling-instagrams-video-sideways-quandary/"><u>Unraveling Instagram's Video Sideways Quandary</u></a></li>
</ul></div>
