---
title: Deciphered Doorkeeper? No Swift Shift to New Solution
date: 2024-06-25T11:27:28.286Z
updated: 2024-06-26T11:27:28.286Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deciphered Doorkeeper? No Swift Shift to New Solution
excerpt: This Article Describes Deciphered Doorkeeper? No Swift Shift to New Solution
keywords: Decoded Keyholder,Quick Transition Halted,New Solution Delayed,Doorkeeper Insight,No Rapid Change,Solutions Postponed,Unveiling Locksmiths
thumbnail: https://thmb.techidaily.com/ce2efe940111a7e6cca801caf2d213cdd3c650dded56c51fea507b1e98fc61ee.jpg
---

## Deciphered Doorkeeper? No Swift Shift to New Solution

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
<li><a href="https://win11.techidaily.com/leveraging-luminosity-a-comprehensive-hdr-guide-for-windows-11-users/"><u>Leveraging Luminosity: A Comprehensive HDR Guide for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/quick-route-to-purchase-adobe-reader-in-microsoft-marketplace/"><u>Quick Route to Purchase Adobe Reader in Microsoft Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/windows-photo-perfection-troubleshooting-made-simple/"><u>Windows Photo Perfection: Troubleshooting Made Simple</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-precision-ditch-delays-top-fixes-for-bf2-players/"><u>Unleash Precision, Ditch Delays: Top Fixes for BF2 Players</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-steam-read-only-barrier-errors-in-windows-11/"><u>Eliminating Steam Read-Only Barrier Errors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-video-driver-crash-on-win1110/"><u>Addressing Video Driver Crash on Win11/10</u></a></li>
<li><a href="https://win11.techidaily.com/setting-failed-logon-retry-timeframe-in-win-1011/"><u>Setting Failed Logon Retry Timeframe in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-issues-with-windows-system-health-indicator/"><u>Remedying Issues with Windows System Health Indicator</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-link-ups-phones-and-windows-11-synergy/"><u>Innovative Link-Ups: Phones and Windows 11 Synergy</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-workflow-with-top-windows-to-do-apps/"><u>Enhance Your Workflow with Top Windows To-Do Apps</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-chromebooks-premium-free-video-capture-extensions/"><u>[Updated] 2024 Approved  Chromebook's Premium Free Video Capture Extensions</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-elevate-your-content-with-jujutsu-kaisen-on-tiktok/"><u>[Updated] In 2024, Elevate Your Content with Jujutsu Kaisen on TikTok</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-oppo-a38-easily-by-drfone-android/"><u>In 2024, How To Unlock a Oppo A38 Easily?</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-merging-markets-youtube-and-brand-collaboration-concepts/"><u>[Updated] Merging Markets  YouTube and Brand Collaboration Concepts</u></a></li>
<li><a href="https://extra-hints.techidaily.com/innovative-techniques-for-video-editing-on-windows-8-movie-maker/"><u>Innovative Techniques for Video Editing on Windows 8 Movie Maker</u></a></li>
<li><a href="https://extra-support.techidaily.com/pioneering-virtual-voyages-with-jaunt-vr-for-2024/"><u>Pioneering Virtual Voyages with Jaunt VR for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-unlocking-your-gaming-potential-the-complete-guide-to-getting-disconitro-for-2024/"><u>[New] Unlocking Your Gaming Potential  The Complete Guide to Getting DiscoNitro for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/strategies-to-streamline-your-google-meet-calendar-for-2024/"><u>Strategies to Streamline Your Google Meet Calendar for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-5-ways-to-track-asus-rog-phone-8-without-app-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Ways to Track Asus ROG Phone 8 without App | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-samsung-galaxy-f34-5gwithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Samsung Galaxy F34 5Gwith/without a PC</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>