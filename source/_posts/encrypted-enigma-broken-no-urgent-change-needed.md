---
title: Encrypted Enigma Broken? No Urgent Change Needed
date: 2024-12-24T22:58:57.562Z
updated: 2024-12-28T03:35:42.650Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kTHQrw8e1gk?si=gTPIa7KjhSZ0Vz97" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-breakdown-of-how-youtube-ad-revenue-works-cpm/"><u>[New] 2024 Approved Breakdown of How YouTube Ad Revenue Works (CPM)</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/op-6-free-audio-apps-convert-youtube-hits-to-your-android-device/"><u>[New] Top 6 Free Audio Apps - Convert YouTube Hits to Your Android Device</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-the-fast-track-building-elegant-google-photo-collage-art-for-2024/"><u>[Updated] The Fast Track Building Elegant Google Photo Collage Art for 2024</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210146418-9783200071933-50-shades-of-love/"><u>50 Shades of Love | Free Book</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-realme-gt-5-pro-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Realme GT 5 Pro Fingerprint Lock</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-ways-to-enjoy-microsoft-word-at-no-cost/"><u>Discover the Ways to Enjoy Microsoft Word at No Cost</u></a></li>
<li><a href="https://win11.techidaily.com/excel-tips-and-tricks-effectively-displaying-data-with-icon-sets-for-clarity-and-impact/"><u>Excel Tips & Tricks: Effectively Displaying Data with Icon Sets for Clarity and Impact</u></a></li>
<li><a href="https://win11.techidaily.com/excel-tricks-writing-your-own-function-to-count-business-days/"><u>Excel Tricks: Writing Your Own Function to Count Business Days</u></a></li>
<li><a href="https://win11.techidaily.com/excel-the-perfect-alternative-for-non-wearable-tech-enthusiasts-to-monitor-their-wellness/"><u>Excel: The Perfect Alternative for Non-Wearable Tech Enthusiasts to Monitor Their Wellness</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-cleaning-up-smart-tags-in-your-excel-spreadsheets/"><u>Expert Tips for Cleaning Up Smart Tags in Your Excel Spreadsheets</u></a></li>
<li><a href="https://win-blog.techidaily.com/expert-tips-for-getting-your-among-us-voice-chat-running-smoothly-again-windows-users/"><u>Expert Tips for Getting Your Among Us Voice Chat Running Smoothly Again (Windows Users)</u></a></li>
<li><a href="https://win11.techidaily.com/genuine-deal-alert-claim-your-50-savings-on-microsoft/"><u>Genuine Deal Alert: Claim Your 50% Savings on Microsoft</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-highlighting-incorrect-values-using-circular-boundaries-in-excel-spreadsheets/"><u>Guide to Highlighting Incorrect Values Using Circular Boundaries in Excel Spreadsheets</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ess-audio-transfer-youtube-videos-)-mp3-macos-2023-for-2024/"><u>Seamless Audio Transfer YouTube Videos > MP3, MacOS 2023 for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-and-fixing-your-logitech-g230-microphone-issues/"><u>Troubleshooting and Fixing Your Logitech G230 Microphone Issues</u></a></li>
</ul></div>

