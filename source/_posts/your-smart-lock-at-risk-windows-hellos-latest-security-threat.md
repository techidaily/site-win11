---
title: Your Smart Lock at Risk? Windows Hello's Latest Security Threat
date: 2024-12-22T04:32:58.135Z
updated: 2024-12-27T20:47:32.879Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Your Smart Lock at Risk? Windows Hello's Latest Security Threat
excerpt: This Article Describes Your Smart Lock at Risk? Windows Hello's Latest Security Threat
keywords: Lock Risks,Windows Hello Vulnerability,Home Security Alerts,Smart Lock Safety,Secure Windows Login,IoT Threat Awareness,Cybersecurity Breach
thumbnail: https://thmb.techidaily.com/bf32c159170edbc355c721b22ee8ee6c67dda36feed408fdb0ec7f3ca8b4ddc2.jpg
---

## Your Smart Lock at Risk? Windows Hello's Latest Security Threat

 Logging into a Windows laptop with a fingerprint scanner is easy; just place your finger on a scanner, and the operating system lets you in. However, researchers have shown that, while this method is convenient, it's not hackproof.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Can People Hack Windows Hello Fingerprint Scanners?

![Lock Having Fingerprint in the Middle on Blue Background](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/passwords-are-a-thing-of-the-past-passwordless-logins-benefits.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If a hacker wants to bypass a fingerprint scanner on a Windows machine, they're aiming to get past a service called Windows Hello. This service handles how you log into Windows, such as PINs, facial scans, and fingerprint scans.

 As part of research into Windows Hello's strength, two [white-hat hackers](https://www.makeuseof.com/white-hat-hacker/), Jesse D'Aguanno and Timo Teräs, posted a report on their website, [Blackwing HQ](https://blackwinghq.com/blog/posts/a-touch-of-pwn-part-i/). The report details how they breached three popular devices: the Dell Inspiron 15, Lenovo ThinkPad T14, and the Microsoft Surface Pro Type Cover.

### How the Hackers Breached Windows Hello on the Dell Inspiron 15

 For the Dell Inspiron 15, the hackers noticed they could boot into Linux on the laptop. Once logged into Linux, they can register their fingerprints in the system and give it the same ID as the Windows user they want to log into.

 Then, they perform a man-in-the-middle attack on the connection between the PC and the sensor. They set it up so that when Windows goes to double-check that a scanned fingerprint is legitimate, it ends up checking the Linux database of fingerprints instead of its own.

 To dodge Windows Hello, the hackers uploaded their fingerprints to the Linux database, assigned it the same ID as the user on Windows, and then tried to log into Windows with their fingerprints. During the authentication process, they redirected the packet to the Linux database, which told Windows that the user at the specified ID was ready to log in.

### How the Hackers Breached Windows Hello on the Lenovo ThinkPad T14

 For the Lenovo ThinkPad, the hackers discovered that the laptop used a custom encryption method to verify fingerprints. With some work, the hackers managed to decrypt it, giving them a way into the fingerprint verification process.

 Once done, the hackers could force the fingerprint database to accept their fingerprint as the user's. Then, all they had to do was scan their fingerprint to access the Lenovo ThinkPad.

### How the Hackers Breached Windows Hello on the Microsoft Surface Pro Type Cover

 The hackers believed the Surface Pro would be the hardest device to crack, but they were surprised to find the Surface Pro lacked a lot of security measures for checking valid fingerprints. In fact, they discovered that they only had to dodge past one defense, then tell the Surface Pro that the fingerprint scan was successful, and the device let them in.

## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 These hacks may sound pretty scary if you use fingerprints to log into your laptop. However, it's essential to remember some crucial things before you forgo fingerprint scans entirely.

### 1\. The Attacks Were Performed by Skilled Hackers

 The reason threats like [ransomware as a service](https://www.makeuseof.com/what-is-ransomware-as-a-service/) are so deadly is that anyone with minimal cybersecurity can use them. However, the above hacks require a high level of expertise, with a deep understanding of how devices authenticate fingerprints and how to avoid them.

### 2\. The Attacks Require the Attacker to Physically Interact With the Device

 The hackers must have physical contact with the device to perform the above hacks. In the report, the hackers stated they might be able to create USB devices that can perform the attack once plugged in, but that means a potential attacker needs to plug something into your PC to hack it.

### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

## How to Stay Safe From Fingerprint Hacking

![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Use a Different Login Method

 Windows Hello supports many different login methods, some more secure than others. If you've fallen out of love with fingerprint scans, check out if [face, iris, fingerprint, PIN, or password logins are more secure](https://www.makeuseof.com/face-iris-fingerprint-password-pin-most-secure/), and choose one that suits you best.

 If you're worried about these hacks, it's important to remember that there's a very low chance they'll target you specifically. As such, you should be safe using fingerprint scans; just don't allow people to steal your devices.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-breathing-life-into-bios-a-zodiac-perspective/"><u>[New] Breathing Life Into Bios A Zodiac Perspective</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-efficiently-delete-unwanted-video-feedback-for-2024/"><u>[New] How to Efficiently Delete Unwanted Video Feedback for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-top-recommended-asmrists-for-nighttime-calmness/"><u>[Updated] Top Recommended ASMRists for Nighttime Calmness</u></a></li>
<li><a href="https://win-wonderful.techidaily.com/1728480782966-3/"><u>共有ドライブの削除ファイルを取り戻す究極の方法3つ</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-and-correcting-directdraw-mistakes-in-win1011-systems/"><u>Confronting and Correcting DirectDraw Mistakes in Win10/11 Systems</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/full-tutorial-to-bypass-your-poco-c55-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Poco C55 Face Lock?</u></a></li>
<li><a href="https://win11.techidaily.com/get-a-new-look-for-windows-three-clearing-ways/"><u>Get a New Look for Windows: Three Clearing Ways</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3-ways-to-change-location-on-facebook-marketplace-for-nokia-c02-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Change Location on Facebook Marketplace for Nokia C02 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-linux-into-hyper-v-on-windows-systems/"><u>Integrating Linux Into Hyper-V on Windows Systems</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-watermark-free-video-editing-software-the-top-14-free-options/"><u>New In 2024, Watermark-Free Video Editing Software The Top 14 Free Options</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-error-0xc0000001-solutions/"><u>Overcoming Windows 11 Error 0xC0000001: Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/powershell-vs-windows-terminal-delving-into-their-distinctive-features/"><u>PowerShell Vs. Windows Terminal: Delving Into Their Distinctive Features</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-search-bar-inactivity-on-windows-11/"><u>Resolving Search Bar Inactivity on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-windows-interface-8-winbubble-ideas-unveiled/"><u>Transforming Windows Interface: 8 WinBubble Ideas Unveiled</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-infinix-hot-30-5g-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://discover-fantastic.techidaily.com/understanding-file-recovery-does-windows-backup-include-previously-removed-documents/"><u>Understanding File Recovery: Does Windows Backup Include Previously Removed Documents?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/universal-unlock-pattern-for-oppo-k11-5g-by-drfone-android/"><u>Universal Unlock Pattern for Oppo K11 5G</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-dual-programming-conflict-in-win-10/"><u>Unraveling the 'Dual Programming Conflict' In Win 10</u></a></li>
<li><a href="https://win11.techidaily.com/windows-feature-switch-on-wsl-integration-mode/"><u>Windows Feature Switch: On WSL Integration Mode</u></a></li>
</ul></div>

