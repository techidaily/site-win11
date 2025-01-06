---
title: "Windows Identity Compromised: Trust in Your Biometrics Questioned"
date: 2024-12-31T18:00:22.963Z
updated: 2025-01-06T18:13:51.706Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Identity Compromised: Trust in Your Biometrics Questioned"
excerpt: "This Article Describes Windows Identity Compromised: Trust in Your Biometrics Questioned"
keywords: Windows Security Breach,Bio-Compromise Risk,Identity Theft Alert,Biometric Vulnerability,Fingerprint Hacking,Facial Recognition Flaw,Safe Browsing Tips
thumbnail: https://thmb.techidaily.com/afda68c97ad8ab431f217d1a649d9d5c1081b7b5e12422de4ab2672dba23567f.jpg
---

## Windows Identity Compromised: Trust in Your Biometrics Questioned

 Logging into a Windows laptop with a fingerprint scanner is easy; just place your finger on a scanner, and the operating system lets you in. However, researchers have shown that, while this method is convenient, it's not hackproof.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/58KlTPHv8dU?si=7ICagyNgrao7OkVO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Can People Hack Windows Hello Fingerprint Scanners?

![Lock Having Fingerprint in the Middle on Blue Background](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/passwords-are-a-thing-of-the-past-passwordless-logins-benefits.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 These hacks may sound pretty scary if you use fingerprints to log into your laptop. However, it's essential to remember some crucial things before you forgo fingerprint scans entirely.

### 1\. The Attacks Were Performed by Skilled Hackers

 The reason threats like [ransomware as a service](https://www.makeuseof.com/what-is-ransomware-as-a-service/) are so deadly is that anyone with minimal cybersecurity can use them. However, the above hacks require a high level of expertise, with a deep understanding of how devices authenticate fingerprints and how to avoid them.

### 2\. The Attacks Require the Attacker to Physically Interact With the Device

 The hackers must have physical contact with the device to perform the above hacks. In the report, the hackers stated they might be able to create USB devices that can perform the attack once plugged in, but that means a potential attacker needs to plug something into your PC to hack it.

### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Stay Safe From Fingerprint Hacking

![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-light-up-your-feed-expert-tips-for-instagram-highlights-3-steps/"><u>[New] In 2024, Light Up Your Feed Expert Tips for Instagram Highlights (3 Steps)</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-a-comprehensive-walkthrough-for-embedding-youtube-plays-in-web-design-for-2024/"><u>[Updated] A Comprehensive Walkthrough for Embedding YouTube Plays in Web Design for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-yi-cameras-edge-in-cinematic-quality-4k-capture/"><u>[Updated] In 2024, Yi Camera's Edge in Cinematic Quality 4K Capture</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-unveiling-the-secrets-to-thriving-with-youtube-adsense/"><u>[Updated] Unveiling the Secrets to Thriving With YouTube AdSense</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-understanding-and-evaluating-blackberrys-playbook-tablet/"><u>Comprehensive Guide: Understanding and Evaluating BlackBerry's PlayBook Tablet</u></a></li>
<li><a href="https://win11.techidaily.com/dvd-mp4/"><u>DVDコピーワラジ脱出 MP4への変換手順</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-techniques-for-bulk-downloading-anime-a-step-by-step-guide/"><u>Efficient Techniques for Bulk Downloading Anime: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-guide-finding-and-downloading-your-favorite-disney-films/"><u>Effortless Guide: Finding & Downloading Your Favorite Disney Films</u></a></li>
<li><a href="https://win11.techidaily.com/free-mp4-to-mpg-conversion-techniques-top-8-solutions-unveiled/"><u>Free MP4-to-MPG Conversion Techniques: Top 8 Solutions Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/get-your-youtube-vids-as-mp4mp3-best-unpaid-video-and-audio-downloader-apps-available-now/"><u>Get Your YouTube Vids as MP4/MP3 - Best Unpaid Video & Audio Downloader Apps Available Now!</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-my-spouse-from-spying-on-my-infinix-smart-7-hd-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop My Spouse from Spying on My Infinix Smart 7 HD | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/reverse-the-repost-action-solutions-for-tiktok-content-errors/"><u>Reverse the Repost Action: Solutions for TikTok Content Errors</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723015310757-world-of-warcraft-fixes-now-playing-with-surround-sound/"><u>World of Warcraft Fixes – Now Playing with Surround Sound</u></a></li>
</ul></div>

