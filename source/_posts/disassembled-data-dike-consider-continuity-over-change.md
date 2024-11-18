---
title: "Disassembled Data Dike: Consider Continuity Over Change"
date: 2024-11-12T16:19:15.598Z
updated: 2024-11-17T21:29:30.607Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Disassembled Data Dike: Consider Continuity Over Change"
excerpt: "This Article Describes Disassembled Data Dike: Consider Continuity Over Change"
keywords: Data Dike Breakdown,Dike Disassembly,Continuous Data,Change Vs. Continuity,Data Integrity Analysis,Persistent Systems Review,Consistency in Data Management
thumbnail: https://thmb.techidaily.com/ac0768cd06937c4c888756e7c488f5bb27ac1d6ad36698509cc3575ae5a17b1c.jpg
---

## Disassembled Data Dike: Consider Continuity Over Change

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959759/19272" target="_top" id="1959759">
  <img src="//a.impactradius-go.com/display-ad/19272-1959759" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959759/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144283/7443" target="_top" id="2144283">
  <img src="//a.impactradius-go.com/display-ad/7443-2144283" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144283/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134234/18498" target="_top" id="2134234">
  <img src="//a.impactradius-go.com/display-ad/18498-2134234" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134234/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Is It Time to Ditch BitLocker?

 Interestingly, [Microsoft was already aware](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/countermeasures#attacker-countermeasures) of the potential for this attack. However, this is the first time a practical attack has surfaced at large, illustrating just how fast BitLocker encryption keys can be stolen.

 It raises the vital question of whether you should consider switching to a BitLocker alternative, like the [free and open-source VeraCrypt](https://www.makeuseof.com/encrypt-windows-system-drive-veracrypt/). The good news is that you don't need to jump ship for a few reasons.

 First, the exploit only works with external TPMs that request data from the module using the LPC bus. Most modern hardware integrates the TPM. While a motherboard-based TPM could theoretically be exploited, it would require more time, effort, and an extensive period with the target device. Extracting BitLocker Volume Master Key data from a TPM becomes even more difficult if the module is integrated into the CPU.

 AMD CPUs have integrated TPM 2.0 since 2016 (with the launch of AM4, known as fTPM), while Intel CPUs integrated TPM 2.0 with the launch of its 8th Generation Coffee Lake CPUs in 2017 (known as PTT). Suffice to say, if you're using a machine with an AMD or Intel CPU manufacturer after those dates, you're most likely safe.

 It's also worth noting that despite this exploit, BitLocker remains secure, and the actual encryption underpinning it, AES-128 or AES-256, is still secure.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://remote-screen-capture.techidaily.com/new-best-4k-screen-recorder-applications-for-2024/"><u>[New] Best 4K Screen Recorder Applications for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-the-essential-tutorial-for-creating-a-biz-focused-instagram/"><u>[New] In 2024, The Essential Tutorial for Creating a Biz-Focused Instagram</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-amplify-your-voice-on-twitter-top-video-uploading-solutions/"><u>2024 Approved Amplify Your Voice on Twitter Top Video Uploading Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/6-effective-techniques-to-resurrect-off-screen-windows-in-windows-11/"><u>6 Effective Techniques to Resurrect Off-Screen Windows in Windows 11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/effortless-ways-to-enjoy-mkv-files-on-your-xbox-one-a-step-by-step-guide/"><u>Effortless Ways to Enjoy MKV Files on Your Xbox One: A Step-by-Step Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/flash-video-flv-windows-113/"><u>Flash Video FLV再生解除: Windows 11で見られなかった動画、今こそ見せます！自由に鑑賞可能な手引き3つ</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-2024-how-to-teleport-your-gps-location-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, How To Teleport Your GPS Location On Honor Magic5 Ultimate? | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/iphone-microphone-failure-discover-effective-fixes-for-clear-audio-recording/"><u>IPhone Microphone Failure? Discover Effective Fixes for Clear Audio Recording</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-compatibility-checklist-tool/"><u>Navigating Windows 11'S Compatibility Checklist Tool</u></a></li>
<li><a href="https://win11.techidaily.com/swift-strategies-for-fixing-dism-error-0x800f082f-in-windows/"><u>Swift Strategies for Fixing DISM Error: 0X800F082F in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-merging-your-guide-to-windows-efficiency/"><u>The Art of Merging: Your Guide to Windows Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-devices-android-and-windows-with-nearby-share/"><u>Uniting Devices: Android & Windows With Nearby Share</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    