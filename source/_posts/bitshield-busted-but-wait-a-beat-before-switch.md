---
title: BitShield Busted, But Wait a Beat Before Switch
date: 2024-07-13T11:24:43.903Z
updated: 2024-07-14T11:24:43.903Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes BitShield Busted, But Wait a Beat Before Switch
excerpt: This Article Describes BitShield Busted, But Wait a Beat Before Switch
keywords: BitGuard Failure,Postpone Security Shift,Risky Encryption Breach,Delay Secure Transition,Busted CyberShield,Hold Off Switch,Waiting on BitSecurity
thumbnail: https://thmb.techidaily.com/15566fd0d6cad9f26c793e08c16498fac2c5b48034aed23a907d05190328dc6a.png
---

## BitShield Busted, But Wait a Beat Before Switch

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
<li><a href="https://win11.techidaily.com/beat-the-wait-winning-strategies-to-fasten-upstart-in-win11/"><u>Beat The Wait: Winning Strategies to Fasten Upstart in Win11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-maximizing-tiktok-engagement-in-unboxing-videos/"><u>2024 Approved  Maximizing TikTok Engagement in Unboxing Videos</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-mishaps-validate-your-webcammic-on-windows-pc/"><u>Avoiding Mishaps: Validate Your Webcam/Mic on Windows PC</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-lightrooms-10-lut-sensations-transforming-photos/"><u>[New] LightRoom's 10 LUT Sensations  Transforming Photos</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-functions-of-winservicesexe/"><u>Breaking Down the Functions of Winservices.exe</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/do-you-want-to-know-how-to-make-a-collage-in-lightroom-it-doesnt-matter-whether-you-are-a-novice-or-a-professional-this-guide-will-teach-you-to-do-it-well.m/"><u>Do You Want to Know How to Make a Collage in Lightroom? It Doesnt Matter Whether You Are a Novice or a Professional; This Guide Will Teach You to Do It Well</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-camera-enthusiasts-top-list-ultimate-6-4k-dslr-cameras/"><u>2024 Approved  Camera Enthusiasts' Top List  Ultimate 6 4K DSLR Cameras</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/elevating-your-video-projects-with-audio-synchronization-in-magix-pro-for-2024/"><u>Elevating Your Video Projects with Audio Synchronization in Magix Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-glitches-a-guide-to-fixing-error-code-0x800700e9-in-xbox-game-pass-and-windows-11/"><u>Banishing Glitches: A Guide to Fixing Error Code 0X800700E9 in Xbox Game Pass & Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-pc-life-after-declining-windows-11-upgrade/"><u>Boost Your PC Life After Declining Windows 11 Upgrade</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/mac-alternatives-to-vegas-pro-top-10-video-editing-software/"><u>Mac Alternatives to Vegas Pro Top 10 Video Editing Software</u></a></li>
<li><a href="https://win11.techidaily.com/beneath-the-surface-tools-for-win-1011s-dropdowns/"><u>Beneath-the-Surface Tools for Win 10/11'S Dropdowns</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-cursor-signal-strength-in-win-11-os/"><u>Boosting Cursor Signal Strength in Win 11 OS</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/speedy-alteration-of-yt-vids-for-mac-screens-for-2024/"><u>Speedy Alteration of YT Vids for Mac Screens for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-how-to-reverse-a-video-on-snapchat-for-2024/"><u>[New] How to Reverse a Video on Snapchat for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-pubg-setup-failures-a-windows-guide/"><u>Addressing PUBG Setup Failures: A Windows Guide</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-failure-starting-services-on-windows-efficiently/"><u>Avoiding Failure: Starting Services on Windows Efficiently</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-ignite-motivation-the-hottest-playlists-for-workouts/"><u>[Updated] Ignite Motivation  The Hottest Playlists for Workouts</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-real-time-performance-on-windows-11-task-monitor/"><u>Boosting Real-Time Performance on Windows 11 Task Monitor</u></a></li>
<li><a href="https://apple-account.techidaily.com/troubleshooting-error-connecting-to-the-apple-id-server-from-apple-iphone-11-by-drfone-ios/"><u>Troubleshooting Error Connecting to the Apple ID Server From Apple iPhone 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-security-with-improved-graphics-on-windows-11/"><u>Boosting Security with Improved Graphics on Windows 11</u></a></li>
<li><a href="https://techidaily.com/sign-wps-file-documents-online-for-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>Sign .wps file Documents Online for Free</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-motorola-moto-e13-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Motorola Moto E13 Activity | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/rapid-viewer-for-10-windows-photos-for-2024/"><u>Rapid Viewer for 10 Windows Photos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-image-quality-windows-11s-secret-weapon/"><u>Boosting Image Quality: Windows 11'S Secret Weapon</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-saturated-chatgpt-windows-error/"><u>Addressing Saturated ChatGPT Windows Error</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-digital-dominion-rise-as-a-youtube-guru/"><u>[Updated] In 2024, Digital Dominion  Rise as a YouTube Guru</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/tweeting-videos-directly-from-your-phone-no-rt/"><u>Tweeting Videos Directly From Your Phone (No RT)</u></a></li>
<li><a href="https://win11.techidaily.com/beating-back-blue-screens-in-your-daily-computing-life/"><u>Beating Back Blue Screens in Your Daily Computing Life</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-audience-friendly-approach-to-pc-audio-recording-using-audacity-gratis/"><u>Updated 2024 Approved Audience-Friendly Approach to PC Audio Recording Using Audacity Gratis</u></a></li>
<li><a href="https://win11.techidaily.com/big-data-in-bare-minipcs-little-prowess/"><u>Big Data in Bare MiniPCs, Little Prowess</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-motorola-moto-g-5g-2023-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Motorola Moto G 5G (2023) Location | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-functioning-windows-conditional-filters/"><u>Addressing Non-Functioning Windows Conditional Filters</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-apple-iphone-14-by-drfone-ios/"><u>Top 11 Free Apps to Check IMEI on Apple iPhone 14</u></a></li>
<li><a href="https://win11.techidaily.com/blocking-user-interference-with-windows-clocks/"><u>Blocking User Interference with Windows Clocks</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-complications-with-an-efficient-in-place-windows-11-update/"><u>Avoiding Complications with an Efficient, In-Place Windows 11 Update</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-mismatch-of-speaker-assignment-due-to-another-app/"><u>Avoiding Mismatch of Speaker Assignment Due to Another App</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-microsoft-store-hiccup-error-0x00000000-solution/"><u>Avoiding Microsoft Store Hiccup: Error 0X00000000 Solution</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-m4r-conversion-basics-setting-yourself-up-for-success/"><u>New M4R Conversion Basics Setting Yourself Up for Success</u></a></li>
<li><a href="https://win11.techidaily.com/boost-efficiency-navigating-windows-11s-disk-management-quickly/"><u>Boost Efficiency: Navigating Windows 11'S Disk Management Quickly</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-boosting-your-businesss-productivity-with-top-fb-planners/"><u>[Updated] In 2024, Boosting Your Business's Productivity with Top FB Planners</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>