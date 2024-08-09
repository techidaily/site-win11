---
title: "Breached ByteBandit: Ponder the Path for a Possible Pivot"
date: 2024-08-08T13:12:52.045Z
updated: 2024-08-09T13:12:52.045Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Breached ByteBandit: Ponder the Path for a Possible Pivot"
excerpt: "This Article Describes Breached ByteBandit: Ponder the Path for a Possible Pivot"
keywords: Breach ByteBandit,Cybersecurity Shift,Data Protection Change,Risk Management Redirection,Security Update Strategy,IT Transformation Tactic,Digital Defense Revision
thumbnail: https://thmb.techidaily.com/6ef16648595e97873cff52eb597372e60de93b0601596509e90390a2a00c63c2.jpg
---

## Breached ByteBandit: Ponder the Path for a Possible Pivot

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-audio-improvement-for-effective-online-communication/"><u>[New] 2024 Approved  Audio Improvement for Effective Online Communication</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-avoiding-poverty-earning-in-beauty-media/"><u>[New] 2024 Approved  Avoiding Poverty  Earning in Beauty Media</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-a-dive-into-ar-sticker-technology-and-alternatives/"><u>[New] A Dive Into AR Sticker Technology and Alternatives</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-enhancing-filmmaking-top-choices-in-camera-lenses/"><u>[New] In 2024, Enhancing Filmmaking  Top Choices in Camera Lenses</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-15-youtube-starter-templates-a-guide-to-popularity/"><u>[Updated] 2024 Approved  15 YouTube Starter Templates  A Guide to Popularity</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-examining-key-features-in-vr-headsets/"><u>2024 Approved  Examining Key Features in VR Headsets</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-revolutionary-date-insertion-methods-for-digital-artifacts/"><u>2024 Approved  Revolutionary Date Insertion Methods for Digital Artifacts</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-rectifying-mmc-snap-in-failures/"><u>A Guide to Rectifying MMC Snap-In Failures</u></a></li>
<li><a href="https://extra-tips.techidaily.com/chucklechain-master-the-art-of-memes-at-home/"><u>ChuckleChain  Master the Art of Memes at Home</u></a></li>
<li><a href="https://win11.techidaily.com/concealed-commands-disguise-power-settings-in-start-screen/"><u>Concealed Commands: Disguise Power Settings in Start Screen</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-windows-access-denial-mysteries/"><u>Deciphering Windows Access Denial Mysteries</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/diy-troubleshooting-techniques-for-fixing-lameencdll-malfunctions-in-audacity-mp3-encoding/"><u>DIY Troubleshooting Techniques for Fixing lame_enc.dll Malfunctions in Audacity MP3 Encoding</u></a></li>
<li><a href="https://tech-revival.techidaily.com/elevate-your-content-game-with-8-essential-ai-tools-for-writers/"><u>Elevate Your Content Game with 8 Essential AI Tools for Writers</u></a></li>
<li><a href="https://win11.techidaily.com/error-2e-unravelled-enabling-windows-update/"><u>Error 2E Unravelled: Enabling Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-grammarly-disabled-status-on-windows-pcs/"><u>Fixing Grammarly Disabled Status on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correct-xbox-games-access-error-in-windows-pcs/"><u>Guide to Correct Xbox Games Access Error in Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-intel-unison-power-for-effective-pc-phone-calls/"><u>Harnessing Intel Unison Power for Effective PC Phone Calls</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-restore-your-gta-5-online-gameplay-experience-effectively/"><u>How to Restore Your GTA 5 Online Gameplay Experience Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-stop-the-aw-snap-error-in-chrome/"><u>How to Stop the Aw, Snap! Error in Chrome</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-vivo-y78t-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Vivo Y78t? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-leave-a-life360-group-on-realme-narzo-60-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How To Leave a Life360 Group On Realme Narzo 60 5G Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-vivo-x100-pro-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Vivo X100 Pro to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-superfast-windows-images-scaner/"><u>In 2024, Superfast Windows Images Scaner</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-faster-windows-11-boots-a-triad-of-tips/"><u>Mastering Faster Windows 11 Boots: A Triad of Tips</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-github-desktop-on-windows-11-a-complete-guide/"><u>Mastering GitHub Desktop on Windows 11: A Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-highlight-and-search-features-in-windows-11-os/"><u>Mastering Highlight & Search Features in Windows 11 OS</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-iphone-flipping-and-tilting-photos-perfectly-for-2024/"><u>Mastering iPhone  Flipping & Tilting Photos Perfectly for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-password-storage-windows-text-file-security-tips/"><u>Mastering Password Storage: Windows Text File Security Tips</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-removing-false-device-notifications/"><u>Mastering the Art of Removing False Device Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-computers-visual-experience-with-enhanced-vram/"><u>Optimize Your Computer's Visual Experience with Enhanced VRAM</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-media-makers-code-0x8007043c-issue/"><u>Overcoming Windows Media Maker's Code 0X8007043C Issue</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/quick-fixes-screen-recording-snapchat-hacks-for-2024/"><u>Quick Fixes  Screen Recording Snapchat Hacks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-forcing-printer-deletion-in-win-1011/"><u>Quick Guide: Forcing Printer Deletion in Win 10/11</u></a></li>
<li><a href="https://games-able.techidaily.com/raspberry-pi-gaming-face-off-batocera-or-retropie/"><u>Raspberry Pi Gaming Face-Off: Batocera or RetroPie?</u></a></li>
<li><a href="https://win11.techidaily.com/smoothing-windows-11-update-combat-error-0x30017/"><u>Smoothing Windows 11 Update: Combat Error 0X30017</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-rectifying-file-history-missteps-in-windows-os/"><u>Steps for Rectifying File History Missteps in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-eliminating-restricted-admin-windows-alert/"><u>Strategies for Eliminating Restricted Admin Windows Alert</u></a></li>
<li><a href="https://win11.techidaily.com/subnet-adjustment-for-win11-users/"><u>Subnet Adjustment for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-windows-based-counter-strike-play/"><u>Supercharge Windows-Based Counter-Strike Play</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-snap-open-apps-in-windows-11/"><u>Swiftly Snap Open Apps in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-pc-performance-deficiencies-amidst-intel-errors/"><u>Tackling PC Performance Deficiencies Amidst Intel Errors</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-update-problem-code-0x800f0922/"><u>Tackling Windows Update Problem - Code 0X800f0922</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tango-dancing-devices-androidwindows-synchro/"><u>Tech Tango: Dancing Devices - Android/Windows Synchro</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-of-control-for-winapps-and-browsers/"><u>The Blueprint of Control for WinApps & Browsers</u></a></li>
<li><a href="https://win11.techidaily.com/three-methods-to-remove-microsoft-store-from-pcs/"><u>Three Methods to Remove Microsoft Store From PCs</u></a></li>
<li><a href="https://techidaily.com/useful-ways-that-can-help-to-effectively-recover-deleted-files-from-xiaomi-redmi-13c-by-fonelab-android-recover-data/"><u>Useful ways that can help to effectively recover deleted files from Xiaomi Redmi 13C</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/visualize-better-incorporating-borders-in-insta-videos/"><u>Visualize Better  Incorporating Borders in Insta-Videos</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-oppo-reno-10-pro-5g-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
</ul></div>
