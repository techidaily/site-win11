---
title: "Hacked Hard Drive Locks: Wait It Out Wisely"
date: 2024-11-01T23:23:29.148Z
updated: 2024-11-07T18:07:17.119Z
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
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918714/19272" target="_top" id="1918714">
  <img src="//a.impactradius-go.com/display-ad/19272-1918714" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918714/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-50plus-amazing-online-sources-to-boost-your-fb-cover-image/"><u>[New] 2024 Approved 50+ Amazing Online Sources to Boost Your FB Cover Image</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-unveiling-the-high-res-sky-scenes-with-mi-drone/"><u>[New] Unveiling the High-Res Sky Scenes with Mi Drone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-top-eco-friendly-film-tech-for-2024/"><u>[Updated] Top Eco-Friendly Film Tech for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/6-ways-to-record-mov-files-on-windows-11-for-2024/"><u>6 Ways to Record .mov Files on Windows 11 for 2024</u></a></li>
<li><a href="https://win-remarkable.techidaily.com/clona-tu-disco-duro-mas-rapidamente-con-estos-metodos-faciles-para-windows-1187/"><u>Clona Tu Disco Duro Más Rápidamente Con Estos Métodos Fáciles Para Windows 11/8/7</u></a></li>
<li><a href="https://win11.techidaily.com/effective-ways-to-eliminate-apple-device-images-not-uploading-in-windows/"><u>Effective Ways to Eliminate Apple Device Images Not Uploading in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-msresourceappnametext-error-in-windows-11/"><u>Eliminating 'MsResource:AppName/Text Error' In Windows 11</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-move-custom-ringtones-from-apple-iphone-12-pro-max-to-android-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Move Custom Ringtones from Apple iPhone 12 Pro Max to Android? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-palette-perfection-the-colorists-manual/"><u>In 2024, Palette Perfection The Colorist's Manual</u></a></li>
<li><a href="https://win11.techidaily.com/learn-and-master-window-11s-taskbar-search-box-quickly/"><u>Learn and Master Window 11’S Taskbar Search Box Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-resolve-secure-boot-non-activation-on-windows-systems/"><u>Methods to Resolve Secure Boot Non-Activation on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/restore-your-controller-to-steams-attention-in-win/"><u>Restore Your Controller to Steam's Attention in Win</u></a></li>
<li><a href="https://win11.techidaily.com/standby-stumbles-in-windows-an-investigative-report/"><u>Standby Stumbles in Windows: An Investigative Report</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-guide-why-visual-look-up-fails-on-iphones/"><u>Troubleshooting Guide: Why Visual Look Up Fails on iPhones</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-how-to-create-your-own-lol-montage-video/"><u>Updated In 2024, How to Create Your Own LOL Montage Video</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    