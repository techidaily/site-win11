---
title: "Crippled CoreCrypt: Still Stand, Not Suddenly Shift"
date: 2024-10-05T13:35:48.844Z
updated: 2024-10-08T16:29:32.602Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Crippled CoreCrypt: Still Stand, Not Suddenly Shift"
excerpt: "This Article Describes Crippled CoreCrypt: Still Stand, Not Suddenly Shift"
keywords: CrippledCoreCrypto,CoreStandStrong,ResilientEncryption,NoSuddenShift,SecurityNoChange,StandThroughUpheaval,UnchangedCryptography
thumbnail: https://thmb.techidaily.com/d64a92b374563fd7f8dd564ef2b564a68a3b72b9d9892ee74121db7b4e7f60bc.jpg
---

## Crippled CoreCrypt: Still Stand, Not Suddenly Shift

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136626/26400" target="_top" id="2136626">
  <img src="//a.impactradius-go.com/display-ad/26400-2136626" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136626/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111994/7443" target="_top" id="2111994">
  <img src="//a.impactradius-go.com/display-ad/7443-2111994" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111994/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is It Time to Ditch BitLocker?

 Interestingly, [Microsoft was already aware](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/countermeasures#attacker-countermeasures) of the potential for this attack. However, this is the first time a practical attack has surfaced at large, illustrating just how fast BitLocker encryption keys can be stolen.

 It raises the vital question of whether you should consider switching to a BitLocker alternative, like the [free and open-source VeraCrypt](https://www.makeuseof.com/encrypt-windows-system-drive-veracrypt/). The good news is that you don't need to jump ship for a few reasons.

 First, the exploit only works with external TPMs that request data from the module using the LPC bus. Most modern hardware integrates the TPM. While a motherboard-based TPM could theoretically be exploited, it would require more time, effort, and an extensive period with the target device. Extracting BitLocker Volume Master Key data from a TPM becomes even more difficult if the module is integrated into the CPU.

 AMD CPUs have integrated TPM 2.0 since 2016 (with the launch of AM4, known as fTPM), while Intel CPUs integrated TPM 2.0 with the launch of its 8th Generation Coffee Lake CPUs in 2017 (known as PTT). Suffice to say, if you're using a machine with an AMD or Intel CPU manufacturer after those dates, you're most likely safe.

 It's also worth noting that despite this exploit, BitLocker remains secure, and the actual encryption underpinning it, AES-128 or AES-256, is still secure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-unlocking-live-streams-rokus-path-to-fb-live/"><u>[New] Unlocking Live Streams Roku's Path to FB LIVE</u></a></li>
<li><a href="https://win11.techidaily.com/10-early-symptoms-of-windows-needing-a-fresh-start/"><u>10 Early Symptoms of Windows Needing a Fresh Start</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-transforming-recording-into-stunning-podcast-edits/"><u>2024 Approved Transforming Recording Into Stunning Podcast Edits</u></a></li>
<li><a href="https://win11.techidaily.com/art-software-showdown-windows-programs-vs-procreate/"><u>Art Software Showdown: Windows Programs Vs. Procreate</u></a></li>
<li><a href="https://win11.techidaily.com/atlasos-reboot-transform-your-old-game-machine/"><u>AtlasOS Reboot: Transform Your Old Game Machine</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-glitches-enabling-latest-emojis-on-windows-11/"><u>Avoiding Glitches: Enabling Latest Emojis on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/beating-back-corrupt-files-error-code-0x80070570-solutions-for-windows-11/"><u>Beating Back Corrupt Files Error Code 0X80070570: Solutions for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-limits-why-16gb-ram-is-key-for-modern-pcs/"><u>Beyond Limits: Why 16GB RAM Is Key for Modern PCs</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-media-stream-efficiency-taming-vlc-lags/"><u>Boosting Media Stream Efficiency: Taming VLC Lags</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-11-security-upgrading-pin-length/"><u>Boosting Windows 11 Security: Upgrading PIN Length</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-forgotten-island-xbox-hiccup/"><u>Breaking Free From the Forgotten Island Xbox Hiccup</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/futures-palette-the-best-sci-fi-films-crafting-virtual-worlds-for-2024/"><u>Future's Palette The Best Sci-Fi Films Crafting Virtual Worlds for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-honor-magic-5-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Honor Magic 5</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-asus-rog-phone-8-pro-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Asus ROG Phone 8 Pro to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-tecno-pova-5-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Tecno Pova 5 Location by Number | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/inside-the-high-definition-world-of-nikon-j5-for-2024/"><u>Inside the High-Definition World of Nikon J5 for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-itel-p55-5g-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your Itel P55 5G Phone</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-pacificadrive-issues-steps-to-restore-functionality/"><u>Troubleshooting PacificaDrive Issues: Steps to Restore Functionality</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/videocutter-expertise-full-evaluation/"><u>VideoCutter Expertise – Full Evaluation</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    