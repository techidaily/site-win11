---
title: "Disassembled Data Dike: Consider Continuity Over Change"
date: 2024-11-23T21:47:35.604Z
updated: 2024-11-28T03:52:35.095Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Disassembled Data Dike: Consider Continuity Over Change"
excerpt: "This Article Describes Disassembled Data Dike: Consider Continuity Over Change"
keywords: Data Dike Breakdown,Dike Disassembly,Continuous Data,Change Vs. Continuity,Data Integrity Analysis,Persistent Systems Review,Consistency in Data Management
thumbnail: https://thmb.techidaily.com/ac0768cd06937c4c888756e7c488f5bb27ac1d6ad36698509cc3575ae5a17b1c.jpg
---

## Disassembled Data Dike: Consider Continuity Over Change

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://desktop-recording.techidaily.com/new-recording-techniques-for-stellar-voice-over-audio-for-2024/"><u>[New] Recording Techniques for Stellar Voice-Over Audio for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-persistent-display-transcription-for-2024/"><u>[Updated] Persistent Display Transcription for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-the-essentials-navigating-whatsapp-call-functionality/"><u>[Updated] The Essentials Navigating WhatsApp Call Functionality</u></a></li>
<li><a href="https://extra-information.techidaily.com/affordable-cloud-keep-optimal-pricing-for-huge-archives-for-2024/"><u>Affordable Cloud Keep Optimal Pricing for Huge Archives for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-lack-of-access-for-windows-app-removal/"><u>Correcting Lack of Access for Windows App Removal</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-resource-consumption-handling-unrealcefsubprocess-in-windows/"><u>Decreasing Resource Consumption: Handling UnrealCEFSubprocess in Windows</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-vivo-y78-5g-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Vivo Y78 5G Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-the-taskbar-for-tablets-on-windows-11/"><u>How to Get the Taskbar for Tablets on Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-xiaomi-redmi-13c-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Xiaomi Redmi 13C</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/insider-guide-decoding-youtube-live-image-codes/"><u>Insider Guide Decoding YouTube Live Image Codes</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-wi-fi-prompt-shortcomings-completing-missing-steps-in-windows/"><u>Overcoming Wi-Fi Prompt Shortcomings: Completing Missing Steps in Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-gaming-odyssey-of-yesteryear-using-dosbox-x/"><u>The Gaming Odyssey of Yesteryear: Using DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-hidden-features-of-system-restore-in-win11/"><u>Unlocking the Hidden Features of System Restore in Win11</u></a></li>
</ul></div>

