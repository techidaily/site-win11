---
title: Encrypted Enigma Broken? No Urgent Change Needed
date: 2024-12-17T16:19:07.292Z
updated: 2024-12-22T17:11:14.284Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Encrypted Enigma Broken? No Urgent Change Needed
excerpt: This Article Describes Encrypted Enigma Broken? No Urgent Change Needed
keywords: Encryption Secrets Unveiled,Breaking Enigma Cipher,Urgency in Crypto Changes,Decrypting Digital Mysteries,No Immediate Security Update Required,Coding Challenge Solved,Navigating Cryptography Shifts
thumbnail: https://thmb.techidaily.com/45fa216ed9179ff239c54a97ced9b6daebc95dcdcc42950e7937059431f2b557.jpg
---

## Encrypted Enigma Broken? No Urgent Change Needed

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/djPqRkskaBo?si=O6FEI-KVW0HwN417" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Is It Time to Ditch BitLocker?

 Interestingly, [Microsoft was already aware](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/countermeasures#attacker-countermeasures) of the potential for this attack. However, this is the first time a practical attack has surfaced at large, illustrating just how fast BitLocker encryption keys can be stolen.

 It raises the vital question of whether you should consider switching to a BitLocker alternative, like the [free and open-source VeraCrypt](https://www.makeuseof.com/encrypt-windows-system-drive-veracrypt/). The good news is that you don't need to jump ship for a few reasons.

 First, the exploit only works with external TPMs that request data from the module using the LPC bus. Most modern hardware integrates the TPM. While a motherboard-based TPM could theoretically be exploited, it would require more time, effort, and an extensive period with the target device. Extracting BitLocker Volume Master Key data from a TPM becomes even more difficult if the module is integrated into the CPU.

 AMD CPUs have integrated TPM 2.0 since 2016 (with the launch of AM4, known as fTPM), while Intel CPUs integrated TPM 2.0 with the launch of its 8th Generation Coffee Lake CPUs in 2017 (known as PTT). Suffice to say, if you're using a machine with an AMD or Intel CPU manufacturer after those dates, you're most likely safe.

 It's also worth noting that despite this exploit, BitLocker remains secure, and the actual encryption underpinning it, AES-128 or AES-256, is still secure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-support.techidaily.com/new-mastering-video-on-twitter-top-converter-picks/"><u>[New] Mastering Video on Twitter Top Converter Picks</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-editors-alchemy-transforming-raw-to-radiant-pictures/"><u>[New] The Editor's Alchemy Transforming Raw to Radiant Pictures</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-magix-vpx-review-transforming-media-with-ease/"><u>2024 Approved Magix VPX Review Transforming Media with Ease</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unlocking-efficient-google-podcast-postings/"><u>2024 Approved Unlocking Efficient Google Podcast Postings</u></a></li>
<li><a href="https://win11.techidaily.com/3-effective-methods-to-enhance-windows-ram-usage/"><u>3 Effective Methods to Enhance Windows' RAM Usage</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-run-the-program-compatibility-troubleshooter-on-windows/"><u>4 Ways to Run the Program Compatibility Troubleshooter on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-adobe-acquisition-through-microsofts-marketplace/"><u>Achieving Adobe Acquisition Through Microsoft's Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-system-restore-problem-code-0x80780119/"><u>Addressing System Restore Problem: Code 0X80780119</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-lock-screen-delay-anomaly/"><u>Addressing Windows Lock Screen Delay Anomaly</u></a></li>
<li><a href="https://win11.techidaily.com/android-ios-direct-pc-file-access/"><u>Android-iOS: Direct PC File Access</u></a></li>
<li><a href="https://win11.techidaily.com/averting-error-22-disable-situation-in-windows-11-settings/"><u>Averting Error 22 Disable Situation in Windows 11 Settings</u></a></li>
<li><a href="https://win11.techidaily.com/away-from-clouds-data-at-your-fingertips-onedrive-tutorial/"><u>Away From Clouds, Data at Your Fingertips - OneDrive Tutorial</u></a></li>
<li><a href="https://fox-links.techidaily.com/cloud-keepers-value-deal-economical-mass-storage/"><u>Cloud Keepers' Value Deal Economical Mass Storage</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/crafting-compelling-online-livestreams-from-a-single-source/"><u>Crafting Compelling Online Livestreams From a Single Source</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-avi-files-of-11-5g-with-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and AVI files of 11 5G with Video Repair Utility on Windows?</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-best-10-facelift-tech-for-iphones-and-android-phones/"><u>In 2024, Best 10 Facelift Tech for iPhones and Android Phones</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-video-grabber-tool-decompiler/"><u>In 2024, Video Grabber Tool Decompiler</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    