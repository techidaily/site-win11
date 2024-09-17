---
title: "Shattered Crypto Key: Don't Rush for New Guardians"
date: 2024-09-14T06:00:07.069Z
updated: 2024-09-17T06:11:02.748Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Shattered Crypto Key: Don't Rush for New Guardians"
excerpt: "This Article Describes Shattered Crypto Key: Don't Rush for New Guardians"
keywords: Shattered Crypto Security,Crypto Keys Breach Alert,No Haste, Find Guards,Secure Cryptography Update,Immediate Key Protection,Guard Against Crypto Risk,New Safekeepers for Coins
thumbnail: https://thmb.techidaily.com/fb5f458ad35f6a8088f1d0bc0256a6dfcf5f90caa0def063b41c33922ff4a5cb.jpg
---

## Shattered Crypto Key: Don't Rush for New Guardians

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134218/18498" target="_top" id="2134218">
  <img src="//a.impactradius-go.com/display-ad/18498-2134218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134218/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is It Time to Ditch BitLocker?

 Interestingly, [Microsoft was already aware](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/countermeasures#attacker-countermeasures) of the potential for this attack. However, this is the first time a practical attack has surfaced at large, illustrating just how fast BitLocker encryption keys can be stolen.

 It raises the vital question of whether you should consider switching to a BitLocker alternative, like the [free and open-source VeraCrypt](https://www.makeuseof.com/encrypt-windows-system-drive-veracrypt/). The good news is that you don't need to jump ship for a few reasons.

 First, the exploit only works with external TPMs that request data from the module using the LPC bus. Most modern hardware integrates the TPM. While a motherboard-based TPM could theoretically be exploited, it would require more time, effort, and an extensive period with the target device. Extracting BitLocker Volume Master Key data from a TPM becomes even more difficult if the module is integrated into the CPU.

 AMD CPUs have integrated TPM 2.0 since 2016 (with the launch of AM4, known as fTPM), while Intel CPUs integrated TPM 2.0 with the launch of its 8th Generation Coffee Lake CPUs in 2017 (known as PTT). Suffice to say, if you're using a machine with an AMD or Intel CPU manufacturer after those dates, you're most likely safe.

 It's also worth noting that despite this exploit, BitLocker remains secure, and the actual encryption underpinning it, AES-128 or AES-256, is still secure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/updated-superior-sound-capture-insiders-list-of-the-best-9-microphones-online-for-2024/"><u>[Updated] Superior Sound Capture Insider's List of the Best 9 Microphones Online for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1-quick-and-simple-guide-downloading-and-setting-up-showbox-on-your-computer/"><u>1. Quick & Simple Guide: Downloading & Setting Up ShowBox on Your Computer</u></a></li>
<li><a href="https://win11.techidaily.com/1726028090190-20248/"><u>2024年度人気動画編集ツールベスト8！無料でダウンロード可能</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-guide-to-installing-titanium-kodi-skin-across-various-kodi-editions/"><u>A Comprehensive Guide to Installing Titanium Kodi Skin Across Various Kodi Editions</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-oppo-a56s-5g-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/all-you-need-to-know-about-mega-greninja-for-tecno-spark-10-5g-drfone-by-drfone-virtual-android/"><u>All You Need To Know About Mega Greninja For Tecno Spark 10 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-youtubes-limits-tips-to-fix-stalled-video-encoding-at-critical-percentages/"><u>Bypass YouTube's Limits: Tips to Fix Stalled Video Encoding at Critical Percentages</u></a></li>
<li><a href="https://win11.techidaily.com/canva-tutorial-mastering-video-sound-adjustments-eliminating-or-incorporating-audio-seamlessly/"><u>Canva Tutorial: Mastering Video Sound Adjustments - Eliminating or Incorporating Audio Seamlessly</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-nokia-xr21-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-itel-p55-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Itel P55 | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/inside-the-tech-what-is-virtual-reality-gear/"><u>Inside the Tech What Is Virtual Reality Gear?</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-youtube-video-extraction-dumpertnls-top-4-strategies-unveiled/"><u>Mastering the Art of YouTube Video Extraction: Dumpert.nl's Top 4 Strategies Unveiled!</u></a></li>
<li><a href="https://win11.techidaily.com/1726027263067-step-by-step-guide-video-editing-in-windows-10-updated/"><u>Step-by-Step Guide: Video Editing in Windows 10 (Updated)</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/streamline-video-analytics-a-guide-to-youtube-statistics-with-social-blade/"><u>Streamline Video Analytics A Guide to YouTube Statistics with Social Blade</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ltimate-list-of-8-free-video-editing-programs-for-creatives/"><u>The Ultimate List of 8 FREE Video Editing Programs for Creatives</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>Top 15 Augmented Reality Games Like Pokémon GO To Play On Motorola Edge 40 Neo | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    