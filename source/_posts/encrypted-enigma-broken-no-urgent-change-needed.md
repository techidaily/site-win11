---
title: Encrypted Enigma Broken? No Urgent Change Needed
date: 2025-02-13T02:53:57.614Z
updated: 2025-02-16T04:14:45.845Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-building-brand-buzz-the-power-of-instagram-story-quizzes/"><u>[Updated] 2024 Approved Building Brand Buzz The Power of Instagram Story Quizzes</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-4-strategies-for-capturing-xbox-games-play-by-play/"><u>[Updated] 4 Strategies for Capturing Xbox Games Play-By-Play</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-20-great-free-options-for-web-based-photo-tinkering/"><u>2024 Approved 20 Great Free Options for Web-Based Photo Tinkering</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-understanding-the-underrated-downsides-of-vr/"><u>2024 Approved Understanding the Underrated Downsides of VR</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-vivo-v30-pro-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Vivo V30 Pro without App | Dr.fone</u></a></li>
<li><a href="https://win-trending.techidaily.com/convert-and-transfer-your-vidme-videos-into-high-quality-mp4-or-avi-format-for-windows-and-macos-systems/"><u>Convert and Transfer Your VidMe Videos Into High-Quality MP4 or AVI Format for Windows & macOS Systems</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-picking-efficiency-utilize-windows-11s-checkboxes/"><u>Enhance Picking Efficiency: Utilize Windows 11'S Checkboxes</u></a></li>
<li><a href="https://win-solutions.techidaily.com/enhance-your-pc-adventure-with-a-new-stable-version-of-pathfinder-wrath-of-the-righteous/"><u>Enhance Your PC Adventure with a New, Stable Version of Pathfinder: Wrath of the Righteous</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-google-pixel-8-pro-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On Google Pixel 8 Pro</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/mastering-instagram-utilizing-search-to-expand-your-filters-for-2024/"><u>Mastering Instagram Utilizing Search to Expand Your Filters for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-pin-modification-process/"><u>Navigating Windows PIN Modification Process</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-unsuited-scanner-for-windows-hello-authentication/"><u>Remedying 'Unsuited Scanner' For Windows Hello Authentication</u></a></li>
<li><a href="https://win11.techidaily.com/secrets-of-the-cli-finding-your-public-ip/"><u>Secrets of the CLI: Finding Your Public IP</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-safe-transition-enabling-tpm-and-secure-boot-before-w11/"><u>Steps for Safe Transition: Enabling TPM and Secure Boot Before W11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-conferences-troubleshoot-webcam-and-mic-windows/"><u>Streamlining Conferences: Troubleshoot Webcam and Mic (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-for-wi-fi-disassociation-in-win-11/"><u>Tactics for Wi-Fi Disassociation in Win 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-7-must-have-alarm-clock-applications-on-your-phone/"><u>Top 7 Must-Have Alarm Clock Applications on Your Phone</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11-from-sleep-with-input-devices/"><u>Unlocking Windows 11 From Sleep with Input Devices</u></a></li>
<li><a href="https://win11.techidaily.com/web-to-desktop-making-internet-content-win-compatible/"><u>Web to Desktop: Making Internet Content Win Compatible</u></a></li>
</ul></div>

