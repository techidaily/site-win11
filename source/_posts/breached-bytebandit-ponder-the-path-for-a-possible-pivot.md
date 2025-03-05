---
title: "Breached ByteBandit: Ponder the Path for a Possible Pivot"
date: 2025-02-26T03:39:40.930Z
updated: 2025-03-05T03:20:56.977Z
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
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-aspiring-youtubers-guide-to-affiliate-allies/"><u>[New] In 2024, Aspiring YouTubers' Guide to Affiliate Allies</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-discover-the-top-30-free-unlimited-and-ultimate-1tbplus-cloud-service-options/"><u>[Updated] In 2024, Discover the Top 30 Free, Unlimited, & Ultimate (1TB+) Cloud Service Options</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-folder-corruption-clearing-write-limitations/"><u>Deciphering Folder Corruption: Clearing Write Limitations</u></a></li>
<li><a href="https://win11.techidaily.com/enrich-your-playnite-experience-with-emulators/"><u>Enrich Your Playnite Experience with Emulators</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-for-activation-of-frozen-wsreset-in-windows/"><u>Essential Guide for Activation of Frozen WSReset in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-videos-on-infinix-note-30-vip-racing-edition-by-fonelab-android-recover-video/"><u>How to restore wiped videos on Infinix Note 30 VIP Racing Edition</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-samsung-galaxy-a23-5g-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Samsung Galaxy A23 5G Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-vivo-g2-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Vivo G2 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-broadcasting-conferences-with-no-expense-account/"><u>In 2024, Broadcasting Conferences with No Expense Account</u></a></li>
<li><a href="https://win11.techidaily.com/remedies-for-user-not-found-error-on-windows-devices/"><u>Remedies for User Not Found Error on Windows Devices</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tutorial-actualizado-como-capturar-la-pantalla-con-vlc-media-player/"><u>Tutorial Actualizado: Cómo Capturar La Pantalla Con VLC Media Player</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-power-of-windows-call-recording/"><u>Unlocking the Power of Windows Call Recording</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-discover-expressive-humming-track/"><u>Updated In 2024, Discover Expressive Humming Track</u></a></li>
</ul></div>

