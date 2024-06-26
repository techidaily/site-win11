---
title: "BitLocks Lost Luster: Await Wise Wisdom Before Shift"
date: 2024-06-25T09:48:41.056Z
updated: 2024-06-26T09:48:41.056Z
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
<li><a href="https://win11.techidaily.com/taskbar-chat-disappearance-in-windows-11-what-it-entails-for-users/"><u>Taskbar Chat Disappearance in Windows 11: What It Entails for Users</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-screen-capture-tool-in-windows-11-swiftly/"><u>Navigate to Screen Capture Tool in Windows 11 Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-0x80d03801-issue-in-windows-shop/"><u>Remedying 0X80D03801 Issue in Windows Shop</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-alternative-methods-in-windows-exploration-no-ls/"><u>Deciphering Alternative Methods in Windows Exploration (No LS)</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-unseen-initiating-windows-secret-self-profile-editor/"><u>Deciphering the Unseen: Initiating Windows' Secret Self-Profile Editor</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-your-windows-11-efficiency-with-these-5-reliability-checks/"><u>Maximize Your Windows 11 Efficiency with These 5 Reliability Checks</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-experience-powertoys-on-win11/"><u>Enhancing User Experience: PowerToys on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/6-high-performance-windows-video-editors-unveiled/"><u>6 High-Performance Windows Video Editors Unveiled</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/celestial-sound-shift-exploring-the-features-user-manuals-and-alternatives-for-star-voice-transformation-for-2024/"><u>Celestial Sound Shift Exploring the Features, User Manuals & Alternatives for Star Voice Transformation for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Samsung Galaxy A54 5G | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-elevate-your-storytelling-on-snapchat-top-15-ideas/"><u>[New] 2024 Approved  Elevate Your Storytelling on Snapchat (Top 15 Ideas)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-navigating-the-complexities-of-health-marketing-on-fb/"><u>2024 Approved  Navigating the Complexities of Health Marketing on FB</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-seo-explosion-leading-tech-for-your-videos/"><u>2024 Approved  SEO Explosion  Leading Tech for Your Videos</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/show-your-love-how-to-create-a-beautiful-valentines-day-video-montage-for-2024/"><u>Show Your Love How to Create a Beautiful Valentines Day Video Montage for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/2024-approved-time-lapse-video-editing-top-picks-for-free-and-paid-tools/"><u>2024 Approved Time-Lapse Video Editing Top Picks for Free and Paid Tools</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-direct-tiktok-to-mp4-format-downloader-for-2024/"><u>[New] Direct TikTok to MP4 Format Downloader for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-social-media-syncing-made-simple-tweets-and-tiktoks-for-2024/"><u>[Updated] Social Media Syncing Made Simple  Tweets and TikToks for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>