---
title: BitShield Busted, But Wait a Beat Before Switch
date: 2025-03-03T02:44:48.545Z
updated: 2025-03-04T19:57:42.008Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes BitShield Busted, But Wait a Beat Before Switch
excerpt: This Article Describes BitShield Busted, But Wait a Beat Before Switch
keywords: BitGuard Failure,Postpone Security Shift,Risky Encryption Breach,Delay Secure Transition,Busted CyberShield,Hold Off Switch,Waiting on BitSecurity
thumbnail: https://thmb.techidaily.com/15566fd0d6cad9f26c793e08c16498fac2c5b48034aed23a907d05190328dc6a.png
---

## BitShield Busted, But Wait a Beat Before Switch

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
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-the-ultimate-guide-to-facebook-live-recording/"><u>[New] 2024 Approved The Ultimate Guide to Facebook Live Recording</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-from-xml-to-srt-a-step-by-step-solution-approach/"><u>[New] In 2024, From XML to SRT A Step-by-Step Solution Approach</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-to-use-or-not-to-use-sns-hdr-pro-reviewed-for-2024/"><u>[New] To Use or Not to Use SNS HDR Pro Reviewed for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-launching-into-the-spotlight-instagram-lives/"><u>[Updated] 2024 Approved Launching Into the Spotlight Instagram Lives</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-free-video-chatting-software-for-windowsmac-users-uncovered/"><u>[Updated] Free Video Chatting Software for Windows/Mac Users Uncovered</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-13-creative-ways-to-save-and-store-online-audio-broadcasts/"><u>[Updated] In 2024, 13 Creative Ways to Save and Store Online Audio Broadcasts</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-ultimate-zoom-tricks-for-chromebook-users-for-2024/"><u>[Updated] Ultimate Zoom Tricks for Chromebook Users for 2024</u></a></li>
<li><a href="https://media-tips.techidaily.com/discovering-your-passion-for-the-latest-fallout-series-perfect-moment-to-begin-your-virtual-adventure/"><u>Discovering Your Passion for The Latest Fallout Series: Perfect Moment to Begin Your Virtual Adventure</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-anachronisms-the-guide-to-updated-window-drivers/"><u>Eliminating Anachronisms: The Guide to Updated Window Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-your-stickies-safe-a-step-by-step/"><u>Keeping Your Stickies Safe: A Step-by-Step</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-curtail-involuntary-terminal-showings/"><u>Methods to Curtail Involuntary Terminal Showings</u></a></li>
<li><a href="https://win11.techidaily.com/muting-unsolicited-system-suggestions-in-windows-11/"><u>Muting Unsolicited System Suggestions in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-microsoft-account-conflicts-in-shared-devices/"><u>Overcoming Microsoft Account Conflicts in Shared Devices</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-1011-print-sharing-woes/"><u>Tackling Windows 10/11 Print Sharing Woes</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/96028584-9780835621564-thoughts-for-aspirants/"><u>Thoughts for Aspirants | Free Book</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-dxgi-device-disappearance-issue/"><u>Troubleshooting Windows' DXGI Device Disappearance Issue</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-savings-on-upcoming-windows-11-keys/"><u>Unlocking Savings on Upcoming Windows 11 Keys</u></a></li>
</ul></div>

