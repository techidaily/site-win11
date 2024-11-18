---
title: Tearing Protection? Keep Holding Onto BitLocker
date: 2024-11-13T17:01:42.565Z
updated: 2024-11-18T04:12:33.659Z
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
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098705/14409" target="_top" id="2098705">
  <img src="//a.impactradius-go.com/display-ad/14409-2098705" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098705/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137975/21526" target="_top" id="2137975">
  <img src="//a.impactradius-go.com/display-ad/21526-2137975" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137975/21526" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-boxes.techidaily.com/new-techniques-to-amplify-youtube-video-clarity-for-2024/"><u>[New] Techniques to Amplify YouTube Video Clarity for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-free-film-and-image-repository-highlights-for-2024/"><u>[Updated] Free Film and Image Repository Highlights for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-pioneering-sustainability-transforming-metropolitan-environments-for-2024/"><u>[Updated] Pioneering Sustainability Transforming Metropolitan Environments for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-recognizing-invisible-social-presence-for-2024/"><u>[Updated] Recognizing Invisible Social Presence for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-remedy-dxgierrordevicehunk-in-win1011/"><u>Guide to Remedy DXGI_ERROR_DEVICE_HUNK in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-windows-users-through-gif-resizing-woes-in-discord/"><u>Guiding Windows Users Through GIF Resizing Woes in Discord</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-superior-5-options-to-connect-on-the-net/"><u>In 2024, Superior 5 Options to Connect on the Net</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-google-pixel-7a-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Google Pixel 7a | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-classics-polishing-your-archive-with-windows-madvr/"><u>Reviving Classics: Polishing Your Archive With Windows MadVR</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-capture-mastering-windows-11s-microphone-shortcuts/"><u>Speedy Capture: Mastering Windows 11'S Microphone Shortcuts</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/top-10-best-4k-mirrorless-cameras-for-2024/"><u>Top 10 Best 4K Mirrorless Cameras for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-require-promotion-windows-error-how-to-guide/"><u>Unraveling 'Require Promotion' Windows Error: How-To Guide</u></a></li>
</ul></div>

