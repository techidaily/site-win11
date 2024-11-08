---
title: Tearing Protection? Keep Holding Onto BitLocker
date: 2024-11-06T16:59:14.453Z
updated: 2024-11-07T16:27:49.545Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tearing Protection? Keep Holding Onto BitLocker
excerpt: This Article Describes Tearing Protection? Keep Holding Onto BitLocker
keywords: BitLocker Security,Data Encryption,Tear-Proofing PCs,Secure Storage,Crypto Protection,Key Lockdown,Advanced Security
thumbnail: https://thmb.techidaily.com/4f556f53b702be059c5baaa605e55372122aad0cd1b5268a8b5026540ff9ee16.jpg
---

## Tearing Protection? Keep Holding Onto BitLocker

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144278/7443" target="_top" id="2144278">
  <img src="//a.impactradius-go.com/display-ad/7443-2144278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144278/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151859/7443" target="_top" id="2151859">
  <img src="//a.impactradius-go.com/display-ad/7443-2151859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is It Time to Ditch BitLocker?

 Interestingly, [Microsoft was already aware](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/countermeasures#attacker-countermeasures) of the potential for this attack. However, this is the first time a practical attack has surfaced at large, illustrating just how fast BitLocker encryption keys can be stolen.

 It raises the vital question of whether you should consider switching to a BitLocker alternative, like the [free and open-source VeraCrypt](https://www.makeuseof.com/encrypt-windows-system-drive-veracrypt/). The good news is that you don't need to jump ship for a few reasons.

 First, the exploit only works with external TPMs that request data from the module using the LPC bus. Most modern hardware integrates the TPM. While a motherboard-based TPM could theoretically be exploited, it would require more time, effort, and an extensive period with the target device. Extracting BitLocker Volume Master Key data from a TPM becomes even more difficult if the module is integrated into the CPU.

 AMD CPUs have integrated TPM 2.0 since 2016 (with the launch of AM4, known as fTPM), while Intel CPUs integrated TPM 2.0 with the launch of its 8th Generation Coffee Lake CPUs in 2017 (known as PTT). Suffice to say, if you're using a machine with an AMD or Intel CPU manufacturer after those dates, you're most likely safe.

 It's also worth noting that despite this exploit, BitLocker remains secure, and the actual encryption underpinning it, AES-128 or AES-256, is still secure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-best-in-class-iphone-and-android-video-enhancers/"><u>[New] Best-In-Class iPhone and Android Video Enhancers</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-efficient-obs-settings-for-thrifty-users/"><u>[New] In 2024, Efficient OBS Settings for Thrifty Users</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-explore-largest-collection-of-free-vector-graphics-portals/"><u>[Updated] Explore Largest Collection of Free Vector Graphics Portals</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-essential-tips-on-calculating-your-youtube-traffic-and-earnings/"><u>[Updated] In 2024, Essential Tips on Calculating Your YouTube Traffic & Earnings</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-perfect-photos-at-a-click-top-captioning-software/"><u>[Updated] Perfect Photos at a Click Top Captioning Software</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/basics-of-evolving-media-and-graphics-for-2024/"><u>Basics of Evolving Media and Graphics for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-maximize-disk-capacity-in-windows-systems/"><u>Efficiently Maximize Disk Capacity in Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-and-read-comics-in-windows-11/"><u>How to Open and Read Comics in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-process-control-on-windows-108/"><u>Mastering Process Control on Windows 10/8</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/meet-the-minimums-premiere-pro-system-requirements-explained/"><u>Meet the Minimums Premiere Pro System Requirements Explained</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-roblox-error-262-resolution/"><u>Navigating Through Roblox Error 262 Resolution</u></a></li>
<li><a href="https://win11.techidaily.com/patched-past-microsofts-cutoff-of-windows-7-and-81-security-updates/"><u>Patched Past: Microsoft's Cutoff of Windows 7 and 8.1 Security Updates</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-uncooperative-controllers-on-pc/"><u>Quick Fixes for Uncooperative Controllers on PC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-error-code-0x80240034-in-windows-10-updates/"><u>Resolving 'Error Code: 0X80240034' In Windows 10 Updates</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-voice-recordings-unveiled-mastering-keyboard-shortcuts-on-win-11/"><u>Speedy Voice Recordings Unveiled: Mastering Keyboard Shortcuts on Win 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/steps-to-install-applications-on-your-samsung-smart-television/"><u>Steps to Install Applications on Your Samsung Smart Television</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11-wireless-potential-a-complete-guide-to-setting-up-a-hotspot/"><u>Unlocking Window's 11 Wireless Potential: A Complete Guide to Setting Up a Hotspot</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    