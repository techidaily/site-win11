---
title: Deciphered Doorkeeper? No Swift Shift to New Solution
date: 2024-06-25T09:58:07.412Z
updated: 2024-06-26T09:58:07.412Z
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
<li><a href="https://win11.techidaily.com/enhance-windows-application-speed-through-improved-networking/"><u>Enhance Windows Application Speed Through Improved Networking</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-dealing-with-not-handled-exception-error-on-pcs/"><u>Tips for Dealing with Not Handled Exception Error on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-your-network-preferences-with-windows-11-proxies/"><u>Navigating Your Network Preferences with Windows 11 Proxies</u></a></li>
<li><a href="https://win11.techidaily.com/is-steam-unable-to-connect-to-the-internet-on-windows-heres-how-to-fix-it/"><u>Is Steam Unable to Connect to the Internet on Windows? Here's How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/secret-start-screen-tactics-vanish-power-buttons-from-windows-11/"><u>Secret Start Screen Tactics: Vanish Power Buttons From Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/explore-5-innovative-windows-folder-strategies/"><u>Explore 5 Innovative Windows Folder Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-path-not-found-in-windows-os/"><u>Troubleshooting PATH Not Found in Windows OS</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-the-quintessential-list-of-top-tier-gaming-cams-for-live-viewers-for-2024/"><u>[New] The Quintessential List of Top-Tier Gaming Cams for Live Viewers for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/advanced-tips-and-tricks-for-speech-transcription-with-gdoc/"><u>Advanced Tips and Tricks for Speech Transcription with GDoc</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-top-mac-frame-freezes-collection-limit-156-chars/"><u>[New] Top Mac Frame Freezes Collection (Limit  156 Chars)</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-12-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 12 without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-top-class-ai-mates-for-online-squares/"><u>[Updated] Top-Class AI Mates for Online Squares</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-virtual-ventures-10-near-misses-to-gta-v/"><u>In 2024, Virtual Ventures  10 Near-Misses to GTA V</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-premium-online-sound-snatchers/"><u>In 2024, Premium Online Sound Snatchers</u></a></li>
<li><a href="https://extra-resources.techidaily.com/3-best-smartphones-for-recording-video-for-2024/"><u>3 Best Smartphones for Recording Video for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-aplus-craftsmen-outstanding-instagram-highlight-pages-for-2024/"><u>[New] A+ Craftsmen  Outstanding Instagram Highlight Pages for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>