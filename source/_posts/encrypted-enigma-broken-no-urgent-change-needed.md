---
title: Encrypted Enigma Broken? No Urgent Change Needed
date: 2025-01-03T18:29:40.005Z
updated: 2025-01-06T18:40:19.360Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-next-level-livestream-selecting-the-best-360-cameras/"><u>[New] 2024 Approved Next-Level Livestream Selecting the Best 360° Cameras</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-snapscreen-scrutiny-a-deep-dive-into-recorders/"><u>[New] 2024 Approved SnapScreen Scrutiny A Deep Dive Into Recorders</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-superlative-action-video-snapshot-review/"><u>[New] In 2024, Superlative Action Video Snapshot Review</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-master-class-extracting-and-saving-vimeo-videos-for-2024/"><u>[New] Master Class Extracting and Saving Vimeo Videos for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-trending-beats-navigating-the-world-of-viral-tiktok-raps/"><u>[New] Trending Beats Navigating the World of Viral TikTok Raps</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-the-art-of-gathering-free-photo-display-videos/"><u>[Updated] 2024 Approved The Art of Gathering Free Photo Display Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-magix-vpx-the-ultimate-software-showdown/"><u>[Updated] Magix VPX The Ultimate Software Showdown</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-newest-compatible-cameras-to-match-samsung-gear-360/"><u>2024 Approved Newest Compatible Cameras to Match Samsung Gear 360</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-rectifying-error-0x8007251d-on-pcs/"><u>Deciphering and Rectifying Error 0X8007251d on PCs</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/essential-recording-gear-for-environmentalists/"><u>Essential Recording Gear for Environmentalists</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-pinning-software-on-win11-desktop/"><u>Essential Steps for Pinning Software on Win11 Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-steam-loss-of-color-issue/"><u>Overcoming Windows Steam Loss of Color Issue</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-workspace-hiccups-office-issue-fixes/"><u>Overcoming Windows Workspace Hiccups: Office Issue Fixes</u></a></li>
</ul></div>

