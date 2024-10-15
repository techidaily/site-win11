---
title: "Shattered Crypto Key: Don't Rush for New Guardians"
date: 2024-10-09T22:04:10.643Z
updated: 2024-10-15T21:29:24.986Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915810/19272" target="_top" id="1915810">
  <img src="//a.impactradius-go.com/display-ad/19272-1915810" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915810/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997722/19272" target="_top" id="1997722">
  <img src="//a.impactradius-go.com/display-ad/19272-1997722" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997722/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://bluettifr.pxf.io/c/5597632/2145082/17095" target="_top" id="2145082">
  <img src="//a.impactradius-go.com/display-ad/17095-2145082" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettifr.pxf.io/i/5597632/2145082/17095" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-building-personalized-instagram-feed-outlines/"><u>[New] In 2024, Building Personalized Instagram Feed Outlines</u></a></li>
<li><a href="https://win11.techidaily.com/enlightening-windows-users-on-camera-memory-issues/"><u>Enlightening Windows Users on Camera Memory Issues</u></a></li>
<li><a href="https://fox-access.techidaily.com/expert-insights-into-efficient-lunapic-usage/"><u>Expert Insights Into Efficient LunaPic Usage</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-best-video-chatting-tools-for-remote-team-interactions/"><u>In 2024, Best Video Chatting Tools for Remote Team Interactions</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/insta-tiktik-mastery-uniting-two-social-giants-for-2024/"><u>Insta-TikTik Mastery Uniting Two Social Giants for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/lenovo-ideapad-3-15-inch-i7-gtx-1660-ti-in-depth-analysis-of-an-affordable-powerhouse-for-gamers/"><u>Lenovo IdeaPad 3 15-Inch (I7, GTX 1660 Ti) - In-Depth Analysis of an Affordable Powerhouse for Gamers</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fast-download-rates-for-epic-launcher/"><u>Mastering Fast Download Rates for Epic Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-failed-discord-setup-in-windows-11/"><u>Navigating Through Failed Discord Setup in Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/professional-video-editing-does-m1-macbook-air-hold-up-in-2024/"><u>Professional Video Editing Does M1 MacBook Air Hold Up, In 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/struggling-with-erratic-key-presses-in-windows-11-discover-effective-remedies-now/"><u>Struggling with Erratic Key Presses in Windows 11? Discover Effective Remedies Now!</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-functionalities-of-fn-keys-on-windows-11-devices/"><u>Tailoring Functionalities of FN Keys on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/the-finest-alternatives-to-microsofts-core-applications/"><u>The Finest Alternatives to Microsoft's Core Applications</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-full-potential-with-network-traffic-insight-via-win11s-netstat/"><u>Unlock Your Full Potential with Network Traffic Insight via Win11's Netstat</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unveiling-bing-an-alternative-powerhouse-in-web-search-technology-by-microsoft/"><u>Unveiling Bing - An Alternative Powerhouse in Web Search Technology by Microsoft</u></a></li>
<li><a href="https://win11.techidaily.com/vivetool-breakdown-how-to-pre-emptive-access-updates/"><u>ViVeTool Breakdown: How to Pre-Emptive Access Updates</u></a></li>
</ul></div>

