---
title: Encrypted Enigma Broken? No Urgent Change Needed
date: 2025-02-26T05:02:26.510Z
updated: 2025-03-04T20:44:48.478Z
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

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-the-ultimate-mac-obs-guide-installation-and-operational-knowledge/"><u>[New] 2024 Approved The Ultimate Mac OBS Guide Installation & Operational Knowledge</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-a-quick-primer-accessing-ioss-vr-content-easily-for-2024/"><u>[New] A Quick Primer Accessing IOS’s VR Content Easily for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-decode-and-listen-srt-files-in-winosx/"><u>[New] In 2024, Decode and Listen SRT Files in Win/OSX</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-cutting-ties-with-instagram-navigating-a-permanent-exit-strategy/"><u>[Updated] 2024 Approved Cutting Ties with Instagram Navigating a Permanent Exit Strategy</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-a-comprehensive-guide-to-thumbnail-production-for-2024/"><u>[Updated] A Comprehensive Guide to Thumbnail Production for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-whatsapp-wizardry-unveiling-the-ultimate-chat-strategies-for-2024/"><u>[Updated] WhatsApp Wizardry Unveiling the Ultimate Chat Strategies for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-windows-11-registry-editor-accessibility/"><u>Controlling Windows 11 Registry Editor Accessibility</u></a></li>
<li><a href="https://tech-hub.techidaily.com/from-voice-to-vision-how-chatgpt-elevates-smartwatch-capabilities/"><u>From Voice to Vision: How ChatGPT Elevates Smartwatch Capabilities</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-master-your-captions-the-top-10-precision-subtitle-editors/"><u>In 2024, Master Your Captions The Top 10 Precision Subtitle Editors</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-refining-shots-with-gopros-advanced-color-tools/"><u>In 2024, Refining Shots with GoPro's Advanced Color Tools</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-pc-cool-tackling-high-cpu-consumption-with-rm/"><u>Keep Your PC Cool: Tackling High CPU Consumption with RM</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-missing-updater-files-problem-error-code-0x80070003/"><u>Overcoming Windows' Missing Updater Files Problem (Error Code: 0X80070003)</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-shadow-copy-suspension-error/"><u>Reversing Shadow Copy Suspension Error</u></a></li>
<li><a href="https://win11.techidaily.com/uncomplicated-start-menus-say-no-to-ads/"><u>Uncomplicated Start Menus - Say No to Ads</u></a></li>
<li><a href="https://win11.techidaily.com/win10-network-resolution-path-unreachable/"><u>Win10 Network Resolution: Path Unreachable</u></a></li>
</ul></div>

