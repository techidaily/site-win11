---
title: "Hacked Hard Drive Locks: Wait It Out Wisely"
date: 2024-11-16T19:45:38.867Z
updated: 2024-11-18T08:31:31.513Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Hacked Hard Drive Locks: Wait It Out Wisely"
excerpt: "This Article Describes Hacked Hard Drive Locks: Wait It Out Wisely"
keywords: Hacked HD Recovery,Lockout Solutions,Safe Data Retrieval,Lockouts & Hard Drives,Secure Drive Unlocking,Data Breach Aid,System Restore Post-Hack
thumbnail: https://thmb.techidaily.com/3e4359dd584ef6e6b8909874d88727d66b87bd9dc8bc7dbf15b341990bd1a4b9.jpg
---

## Hacked Hard Drive Locks: Wait It Out Wisely

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144308/7443" target="_top" id="2144308">
  <img src="//a.impactradius-go.com/display-ad/7443-2144308" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144308/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137975/21526" target="_top" id="2137975">
  <img src="//a.impactradius-go.com/display-ad/21526-2137975" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137975/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005196/22899" target="_top" id="2005196">
  <img src="//a.impactradius-go.com/display-ad/22899-2005196" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005196/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-clips.techidaily.com/new-crafting-musical-content-on-instagram-for-2024/"><u>[New] Crafting Musical Content on Instagram for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discover-insights-with-the-august-16-new-york-times-connections-puzzle-solution-431-available-now/"><u>Discover Insights with the August 16 New York Times Connections Puzzle - Solution #431 Available Now!</u></a></li>
<li><a href="https://fox-making.techidaily.com/guide-facile-pour-relocaliser-votre-partition-de-sauvegarde-sur-un-disque-dur-different/"><u>Guide Facile Pour Relocaliser Votre Partition De Sauvegarde Sur Un Disque Dur Différent</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-quickly-resolve-sound-problems-in-windows-10-computers/"><u>How to Quickly Resolve Sound Problems in Windows 10 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-and-repair-a-black-display-in-google-chrome-browser/"><u>How to Troubleshoot and Repair a Black Display in Google Chrome Browser</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-tecno-pop-7-promirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Tecno Pop 7 ProMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-list-winning-ds-emulators-for-nintendo-switch-fans/"><u>Master List: Winning DS Emulators for Nintendo Switch Fans</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-fbm-hiccups-on-windows-seamlessly/"><u>Navigate Through FBM Hiccups on Windows Seamlessly</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-output-9-proven-methods-to-improve-windows-video-quality/"><u>Optimal Output: 9 Proven Methods to Improve Window's Video Quality</u></a></li>
<li><a href="https://techidaily.com/sign-word-2023-documents-online-for-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>Sign Word 2023 Documents Online for Free</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocket-your-typing-speed-on-windows-uncover-the-quickest-fixes/"><u>Skyrocket Your Typing Speed on Windows: Uncover the Quickest Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-rectify-local-security-not-active-error/"><u>Steps to Rectify 'Local Security Not Active' Error</u></a></li>
<li><a href="https://youtube-web.techidaily.com/est-3d-software-for-youtube-intro-creators/"><u>The Best 3D Software for YouTube Intro Creators</u></a></li>
<li><a href="https://discover-great.techidaily.com/transforma-tu-biblioteca-musical-con-soluciones-seguras-para-descargas-sin-drm-desde-itunes/"><u>Transforma Tu Biblioteca Musical Con Soluciones Seguras Para Descargas Sin DRM Desde iTunes</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-java-installation-obstacles-on-windows-os/"><u>Unblocking Java Installation Obstacles on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-why-your-digital-pen-is-failing-on-windows/"><u>Unraveling Why Your Digital Pen Is Failing on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/workarounds-to-administrative-restrictions-on-software-installs/"><u>Workarounds to Administrative Restrictions on Software Installs</u></a></li>
</ul></div>

