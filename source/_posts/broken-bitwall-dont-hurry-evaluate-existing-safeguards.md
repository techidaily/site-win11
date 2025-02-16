---
title: "Broken BitWall: Don't Hurry, Evaluate Existing Safeguards"
date: 2025-02-14T19:12:59.764Z
updated: 2025-02-15T19:56:14.104Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Broken BitWall: Don't Hurry, Evaluate Existing Safeguards"
excerpt: "This Article Describes Broken BitWall: Don't Hurry, Evaluate Existing Safeguards"
keywords: Broken Wall Security,Assess Safe Measures,BitWall Breach Analysis,Slow Down, Check Safety,Evaluate Safeguard Systems,Preventing Cyber Faults,Strengthen Digital Defenses
thumbnail: https://thmb.techidaily.com/daf5ba2a8491ccb029544c33871dfddf8c00a96e763bab0af0faf409f9f29c9c.jpg
---

## Broken BitWall: Don't Hurry, Evaluate Existing Safeguards

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-access-10-free-thumbnail-downloader-apps/"><u>[New] 2024 Approved Access 10 Free Thumbnail Downloader Apps</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-unveiling-the-unexpected-10-truths-about-instagram-reels-for-2024/"><u>[New] Unveiling the Unexpected 10 Truths About Instagram Reels for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-frame-it-right-essential-2023-tools-and-sites-for-image-edits/"><u>[Updated] 2024 Approved Frame It Right Essential 2023 Tools & Sites for Image Edits</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-comparing-googles-flat-cube-and-samsungs-headset/"><u>[Updated] Comparing Google's Flat Cube and Samsung's Headset</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-rectifying-silent-windows-headset-microphone/"><u>Decoding and Rectifying Silent Windows Headset Microphone</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-windows-network-knowledge-with-ping-mastery/"><u>Elevating Your Windows Network Knowledge with Ping Mastery</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-nokia-g22-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Nokia G22 to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-breaking-down-the-elements-of-a-youtube-shorts-template/"><u>In 2024, Breaking Down the Elements of a YouTube Shorts Template</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-chuckle-creation-making-memes-on-kapwing/"><u>In 2024, Chuckle Creation Making Memes on Kapwing</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-could-not-create-snaps-in-windows-admin-tools/"><u>Overcoming 'Could Not Create' Snaps in Windows Admin Tools</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-yellow-tint-restore-true-color-on-windows/"><u>Overcoming Yellow Tint: Restore True Color on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-secure-windows-against-unauthorized-removable-storage/"><u>Steps to Secure Windows Against Unauthorized Removable Storage</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/toms-tech-insights-in-depth-guides-on-the-latest-gadgets/"><u>Tom's Tech Insights: In-Depth Guides on the Latest Gadgets</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-powershell-potential-through-script-policy-settings/"><u>Unleashing PowerShell Potential Through Script Policy Settings</u></a></li>
</ul></div>

