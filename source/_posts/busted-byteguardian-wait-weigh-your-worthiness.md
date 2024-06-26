---
title: Busted ByteGuardian? Wait, Weigh Your Worthiness
date: 2024-06-25T10:05:33.830Z
updated: 2024-06-26T10:05:33.830Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Busted ByteGuardian? Wait, Weigh Your Worthiness
excerpt: This Article Describes Busted ByteGuardian? Wait, Weigh Your Worthiness
keywords: ByteGuardian Busted,Worthiness Measurement,Security Breach Alert,Assess Internet Safety,Guard Your Digital Value,Evaluate Cyber Trust,Online Security Worth
thumbnail: https://thmb.techidaily.com/62017b9a75f2be738008dfd82e88e32736119212be885f48835d0be5b0d3459a.jpg
---

## Busted ByteGuardian? Wait, Weigh Your Worthiness

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
<li><a href="https://win11.techidaily.com/how-to-fix-the-volume-control-slider-not-working-in-windows-11-and-11/"><u>How to Fix the Volume Control Slider Not Working in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/top-12-redundant-windows-extras-for-removal/"><u>Top 12 Redundant Windows Extras for Removal</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-window-11s-secure-browsing-graphically/"><u>Enhancing Window 11'S Secure Browsing Graphically</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-interruption-nightmares-keeping-your-ps4-remote-connected/"><u>Overcoming Interruption Nightmares: Keeping Your PS4 Remote Connected</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-silent-speaker-issue-in-win11-environments/"><u>Resolving Silent Speaker Issue in Win11 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-converting-cr2-photos-to-jpeg-format/"><u>Windows Guide: Converting CR2 Photos to JPEG Format</u></a></li>
<li><a href="https://win11.techidaily.com/searching-for-a-slender-browser-footprint-on-your-desktop/"><u>Searching For a Slender Browser Footprint on Your Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-cannot-end-task-on-your-computer/"><u>Tackling 'Cannot End Task' On Your Computer</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-fix-windows-key-problems/"><u>Essential Steps to Fix Windows Key Problems</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-recordings-best-free-windows-programs/"><u>Perfect Your Recordings: Best FREE Windows Programs</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-ultimate-guide-to-bypassing-icloud-activation-lock-from-apple-iphone-12-pro-max-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Bypassing iCloud Activation Lock from Apple iPhone 12 Pro Max</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-facebooks-visual-storytelling-what-angle-matters-most/"><u>[Updated] In 2024, Facebook's Visual Storytelling  What Angle Matters Most?</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/the-ultimate-decision-final-cut-pro-or-lumafusion-for-your-video-needs-for-2024/"><u>The Ultimate Decision Final Cut Pro or LumaFusion for Your Video Needs for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-top-10-viral-tiktok-kitchen-secrets/"><u>[Updated] Top 10 Viral TikTok Kitchen Secrets</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-15-tips-for-accessing-nba-games-online-for-2024/"><u>Top 15 Tips for Accessing NBA Games Online for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-unraveling-the-secrets-to-smooth-vimeo-video-downloads/"><u>[New] 2024 Approved  Unraveling the Secrets to Smooth Vimeo Video Downloads</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-building-a-brand-with-captivating-haul-videos-and-edits/"><u>In 2024, Building a Brand with Captivating Haul Videos and Edits</u></a></li>
<li><a href="https://youtube-help.techidaily.com/launching-educator-channels-10-key-tips-for-youtube-success-for-2024/"><u>Launching Educator Channels  10 Key Tips for YouTube Success for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/broadcast-perfection-recommended-tech-and-apps-for-youtubers/"><u>Broadcast Perfection  Recommended Tech and Apps for YouTubers</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-leading-the-color-grading-revolution-with-lightrooms-best-10-luts/"><u>In 2024, Leading the Color Grading Revolution with LightRoom’s Best 10 LUTs</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>