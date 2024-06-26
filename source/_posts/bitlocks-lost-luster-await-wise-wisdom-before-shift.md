---
title: "BitLocks Lost Luster: Await Wise Wisdom Before Shift"
date: 2024-06-25T11:24:32.604Z
updated: 2024-06-26T11:24:32.604Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes BitLocks Lost Luster: Await Wise Wisdom Before Shift"
excerpt: "This Article Describes BitLocks Lost Luster: Await Wise Wisdom Before Shift"
keywords: BitLock Secure Fading,Losing Lock Security,Wise Safeguarding Tips,Smart Security Transition,Guardianship Insights,Wisdom in Protection Shift,Prudent Encryption Guide
thumbnail: https://thmb.techidaily.com/0ca201532589a8340625e0277d57d7a6d8a4fe5f03caf08035754438a176d190.jpg
---

## BitLocks Lost Luster: Await Wise Wisdom Before Shift

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/cooler-computing-strategies-for-gamers-systems/"><u>Cooler Computing Strategies for Gamers' Systems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-0x87e00017-when-downloading-ms-games/"><u>Addressing Error 0X87e00017 When Downloading MS Games</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-directx-setup-failures/"><u>Steps to Resolve DirectX Setup Failures</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-error-403-in-roblox-space/"><u>Navigating Through Windows Error 403 in Roblox Space</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-an-improved-taskbar-on-windows-11/"><u>Tips for an Improved Taskbar on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-error-correction-for-rpc-failures/"><u>Mastering Windows Error Correction for RPC Failures</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-users-from-adjusting-windows-time-and-date/"><u>Stopping Users From Adjusting Windows Time and Date</u></a></li>
<li><a href="https://win11.techidaily.com/5-clear-signals-its-time-for-windows-reset/"><u>5 Clear Signals It's Time for Windows Reset</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-innovating-visual-storytelling-utilizing-dslr-for-facebook-live-through-personal-devices-for-2024/"><u>[New] Innovating Visual Storytelling  Utilizing DSLR for Facebook LIVE Through Personal Devices for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/elevate-your-social-media-impact-secrets-unveiled-in-the-best-facebook-bios/"><u>Elevate Your Social Media Impact  Secrets Unveiled in the Best Facebook Bios</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mastering-youtube-thumbnails-with-neon-edges-for-2024/"><u>Mastering YouTube Thumbnails with Neon Edges for 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-practices-for-detaching-soundtracks-in-film-clips/"><u>Updated In 2024, Practices for Detaching Soundtracks in Film Clips</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-guide-to-writing-enthralling-videography-content/"><u>In 2024, Guide to Writing Enthralling Videography Content</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-a-comprehensive-guide-to-pc-speaker-monitoring-and-editing-via-audacity/"><u>Updated A Comprehensive Guide to PC Speaker Monitoring and Editing via Audacity</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-showdown-twitchs-challenge-to-youtubes-market/"><u>[Updated] The Ultimate Showdown  Twitch's Challenge to YouTube's Market</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-tweettracker-monitor-and-grab-visuals-from-social-feeds/"><u>[Updated] TweetTracker  Monitor & Grab Visuals From Social Feeds</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/essential-tools-top-8-mirrorless-cams-for-professional-filmmakers/"><u>Essential Tools  Top 8 Mirrorless Cams For Professional Filmmakers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>