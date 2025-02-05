---
title: Encrypted Enigma Broken? No Urgent Change Needed
date: 2025-02-02T07:58:02.658Z
updated: 2025-02-03T17:35:59.889Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-7-key-tools-to-convert-youtube-videos-easily/"><u>[New] 2024 Approved 7 Key Tools to Convert YouTube Videos Easily</u></a></li>
<li><a href="https://screen-recording.techidaily.com/1716069842884-updated-2024-approved-leveraging-huaweis-inbuilt-screen-capture-tech-on-its-phones/"><u>[Updated] 2024 Approved Leveraging Huawei's Inbuilt Screen Capture Tech on Its Phones.</u></a></li>
<li><a href="https://win11.techidaily.com/enriched-user-experience-embedding-resource-consumption-data/"><u>Enriched User Experience: Embedding Resource Consumption Data</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-fine-tuning-online-discussions-with-advanced-zooming-skills/"><u>In 2024, Fine-Tuning Online Discussions with Advanced Zooming Skills</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-itel-p55-5g-by-drfone-android/"><u>In 2024, How to Bypass FRP from Itel P55 5G?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-samsung-galaxy-m34-5g-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Samsung Galaxy M34 5G to PC? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-lava-blaze-2-5g-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Lava Blaze 2 5G without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/navigating-the-pathway-of-earning-through-bug-hunting-at-openai/"><u>Navigating the Pathway of Earning Through Bug Hunting at OpenAI</u></a></li>
<li><a href="https://win11.techidaily.com/stop-windows-update-failures-with-error-x80246007-fixes/"><u>Stop WIndows Update Failures with Error X80246007 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-non-windows-screen-capturing-solutions/"><u>The Ultimate Guide to Non-Windows Screen Capturing Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-code-0x0000004e-in-win11/"><u>Troubleshooting Code 0X0000004E in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-fix-for-error-0x0000011b-on-win11-operations/"><u>Unraveling the Fix for Error 0X0000011B on Win11 Operations</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-in-2024-complete-guide-of-top-video-language-translators/"><u>Updated In 2024, Complete Guide of Top Video Language Translators</u></a></li>
</ul></div>

