---
title: BitLocker's Encryption Is Broken, But It's Still Not Time to Switch
date: 2024-06-25T11:44:02.629Z
updated: 2024-06-26T11:44:02.629Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes BitLocker's Encryption Is Broken, But It's Still Not Time to Switch
excerpt: This Article Describes BitLocker's Encryption Is Broken, But It's Still Not Time to Switch
keywords: BitLock Encryption Flaws,BitLocker Security Issues,Data Protection Concerns,Encrypted Storage Risks,Secure Lockdown Failures,Passkey Vulnerability,Safe Data Not Guaranteed
thumbnail: https://thmb.techidaily.com/6300778dc08ca1fabf45e37fea6b55cfeffea9a7ede93b82142ae1fd2f19eff3.jpg
---

## BitLocker's Encryption Is Broken, But It's Still Not Time to Switch

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
<li><a href="https://win11.techidaily.com/mastering-windows-11-taskbar-size-tweaks/"><u>Mastering Windows 11 Taskbar Size Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/the-key-to-seamless-slide-showouts-top-tips-for-powerpoint-printing-on-windows/"><u>The Key to Seamless Slide Showouts: Top Tips for PowerPoint Printing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-the-windows-firewall-with-precision/"><u>Resetting the Windows Firewall with Precision</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-interruption-nightmares-keeping-your-ps4-remote-connected/"><u>Overcoming Interruption Nightmares: Keeping Your PS4 Remote Connected</u></a></li>
<li><a href="https://win11.techidaily.com/explore-the-finest-6-windows-usage-analysis-programs/"><u>Explore the Finest 6 Windows Usage Analysis Programs</u></a></li>
<li><a href="https://win11.techidaily.com/standby-struggles-dissecting-modern-standby-issues/"><u>Standby Struggles: Dissecting Modern Standby Issues</u></a></li>
<li><a href="https://win11.techidaily.com/the-quintessential-4-password-sentinels-of-windows-11-era/"><u>The Quintessential 4 Password Sentinels of Windows 11 Era</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-becoming-a-confident-content-creator-youtubes-top-tips/"><u>[Updated] 2024 Approved  Becoming a Confident Content Creator  YouTube's Top Tips</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/navigating-through-virtual-realms-with-headgear/"><u>Navigating Through Virtual Realms with Headgear</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-zte-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On ZTE</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-rapid-techniques-mix-up-and-shuffle-youtube-listings/"><u>2024 Approved  Rapid Techniques  Mix Up and Shuffle YouTube Listings</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/1715860560815-new-employing-in-device-recording-for-screen-capture-across-huaweis-mate-and-p-series/"><u>[New] Employing In-Device Recording for Screen Capture Across Huawei’s Mate and P Series.</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-quickcapture-for-windows-ultimate/"><u>[New] QuickCapture for Windows Ultimate</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-pioneering-clear-sound-in-podcasts-with-top-mixers/"><u>[New] Pioneering Clear Sound in Podcasts with Top Mixers</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-a-beginners-guide-to-personal-brand-craftsmanship-for-2024/"><u>[Updated] A Beginner's Guide to Personal Brand Craftsmanship for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-itel-p40plus-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Itel P40+ | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>