---
title: "Crippled CoreCrypt: Still Stand, Not Suddenly Shift"
date: 2024-10-08T22:20:22.980Z
updated: 2024-10-15T19:38:43.046Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Crippled CoreCrypt: Still Stand, Not Suddenly Shift"
excerpt: "This Article Describes Crippled CoreCrypt: Still Stand, Not Suddenly Shift"
keywords: CrippledCoreCrypto,CoreStandStrong,ResilientEncryption,NoSuddenShift,SecurityNoChange,StandThroughUpheaval,UnchangedCryptography
thumbnail: https://thmb.techidaily.com/d64a92b374563fd7f8dd564ef2b564a68a3b72b9d9892ee74121db7b4e7f60bc.jpg
---

## Crippled CoreCrypt: Still Stand, Not Suddenly Shift

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105866/7443" target="_top" id="2105866">
  <img src="//a.impactradius-go.com/display-ad/7443-2105866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105866/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938721/19272" target="_top" id="1938721">
  <img src="//a.impactradius-go.com/display-ad/19272-1938721" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938721/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-screen-grab.techidaily.com/new-pixelpilot-studio-direct-access-screen-recorder/"><u>[New] PixelPilot Studio Direct-Access Screen Recorder</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-essential-vids-summary-uncovered/"><u>[Updated] Essential Vids Summary Uncovered</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-exploring-stardews-peak-mods-list-of-the-best/"><u>[Updated] Exploring Stardew's Peak Mods - List of the Best</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-the-riders-eye-view-unveiling-23s-finest-action-camera-hats-for-bike-enthusiasts/"><u>[Updated] In 2024, The Rider's Eye View – Unveiling '23’S Finest Action Camera Hats for Bike Enthusiasts</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-navigating-instagrams-video-limit-regulations/"><u>2024 Approved Navigating Instagram's Video Limit Regulations</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/87/"><u>87</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-guide-to-modifying-windows-file-attributes/"><u>A Step-by-Step Guide to Modifying Windows File Attributes</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-explorer-to-show-disk-space/"><u>Enhancing Windows Explorer to Show Disk Space</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/get-ready-for-ios-18-unpack-the-release-moment-zero-expense-feature-rich-experience-and-newest-developments/"><u>Get Ready for iOS 18: Unpack the Release Moment, Zero Expense, Feature-Rich Experience & Newest Developments</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigating-artifical-intelligence-in-apple-devices-comprehensive-insight-on-upcoming-ai-features-for-iphones-macs-and-ipads-zdnet-exclusive/"><u>Navigating Artifical Intelligence in Apple Devices: Comprehensive Insight on Upcoming AI Features for iPhones, Macs & iPads | ZDNET Exclusive</u></a></li>
<li><a href="https://win11.techidaily.com/relaunching-file-explorer-a-step-bystep-guide/"><u>Relaunching File Explorer: A Step-Bystep Guide</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-solution-matching-internet-on-mobile-and-desktop/"><u>Speedy Solution: Matching Internet on Mobile & Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/subtle-system-tweaks-windows-toolbars-unseen/"><u>Subtle System Tweaks: Windows Toolbars Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/the-quest-to-resolve-skies-sse-woes/"><u>The Quest to Resolve Skies' SSE Woes</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-win-error-31-in-network-connections/"><u>Troubleshooting WIN Error 31 in Network Connections</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-your-pc-strategies-to-exit-s-mode/"><u>Unlocking Your PC: Strategies to Exit S Mode</u></a></li>
</ul></div>

