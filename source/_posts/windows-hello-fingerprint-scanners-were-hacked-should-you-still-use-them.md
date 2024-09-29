---
title: "Windows Hello Fingerprint Scanners Were Hacked: Should You Still Use Them?"
date: 2024-09-26T21:00:43.803Z
updated: 2024-09-28T17:59:36.382Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Hello Fingerprint Scanners Were Hacked: Should You Still Use Them?"
excerpt: "This Article Describes Windows Hello Fingerprint Scanners Were Hacked: Should You Still Use Them?"
keywords: Windows Hello Breach,Biometric Security Risk,Fingerprint Scanner Hack,Personal Data Safety,Smartphone Access Security,Facial Recognition Concerns,Secure Login Methods
thumbnail: https://thmb.techidaily.com/60a050976608e9140d90809a0ac2529ef41e9995b243e26e295a790742b88b8b.jpg
---

## Windows Hello Fingerprint Scanners Were Hacked: Should You Still Use Them?

 Logging into a Windows laptop with a fingerprint scanner is easy; just place your finger on a scanner, and the operating system lets you in. However, researchers have shown that, while this method is convenient, it's not hackproof.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Can People Hack Windows Hello Fingerprint Scanners?

![Lock Having Fingerprint in the Middle on Blue Background](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/passwords-are-a-thing-of-the-past-passwordless-logins-benefits.jpg)

 If a hacker wants to bypass a fingerprint scanner on a Windows machine, they're aiming to get past a service called Windows Hello. This service handles how you log into Windows, such as PINs, facial scans, and fingerprint scans.

 As part of research into Windows Hello's strength, two [white-hat hackers](https://www.makeuseof.com/white-hat-hacker/), Jesse D'Aguanno and Timo Teräs, posted a report on their website, [Blackwing HQ](https://blackwinghq.com/blog/posts/a-touch-of-pwn-part-i/). The report details how they breached three popular devices: the Dell Inspiron 15, Lenovo ThinkPad T14, and the Microsoft Surface Pro Type Cover.

### How the Hackers Breached Windows Hello on the Dell Inspiron 15

 For the Dell Inspiron 15, the hackers noticed they could boot into Linux on the laptop. Once logged into Linux, they can register their fingerprints in the system and give it the same ID as the Windows user they want to log into.

 Then, they perform a man-in-the-middle attack on the connection between the PC and the sensor. They set it up so that when Windows goes to double-check that a scanned fingerprint is legitimate, it ends up checking the Linux database of fingerprints instead of its own.

 To dodge Windows Hello, the hackers uploaded their fingerprints to the Linux database, assigned it the same ID as the user on Windows, and then tried to log into Windows with their fingerprints. During the authentication process, they redirected the packet to the Linux database, which told Windows that the user at the specified ID was ready to log in.

### How the Hackers Breached Windows Hello on the Lenovo ThinkPad T14

 For the Lenovo ThinkPad, the hackers discovered that the laptop used a custom encryption method to verify fingerprints. With some work, the hackers managed to decrypt it, giving them a way into the fingerprint verification process.

 Once done, the hackers could force the fingerprint database to accept their fingerprint as the user's. Then, all they had to do was scan their fingerprint to access the Lenovo ThinkPad.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100537/7443" target="_top" id="2100537">
  <img src="//a.impactradius-go.com/display-ad/7443-2100537" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100537/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How the Hackers Breached Windows Hello on the Microsoft Surface Pro Type Cover

 The hackers believed the Surface Pro would be the hardest device to crack, but they were surprised to find the Surface Pro lacked a lot of security measures for checking valid fingerprints. In fact, they discovered that they only had to dodge past one defense, then tell the Surface Pro that the fingerprint scan was successful, and the device let them in.

## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)

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
<a href="https://appsumo.8odi.net/c/5597632/2151884/7443" target="_top" id="2151884">
  <img src="//a.impactradius-go.com/display-ad/7443-2151884" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151884/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886019/19272" target="_top" id="1886019">
  <img src="//a.impactradius-go.com/display-ad/19272-1886019" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886019/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885947/19272" target="_top" id="1885947">
  <img src="//a.impactradius-go.com/display-ad/19272-1885947" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Use a Different Login Method

 Windows Hello supports many different login methods, some more secure than others. If you've fallen out of love with fingerprint scans, check out if [face, iris, fingerprint, PIN, or password logins are more secure](https://www.makeuseof.com/face-iris-fingerprint-password-pin-most-secure/), and choose one that suits you best.

 If you're worried about these hacks, it's important to remember that there's a very low chance they'll target you specifically. As such, you should be safe using fingerprint scans; just don't allow people to steal your devices.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-facebooks-top-visual-discoveries-a-guide/"><u>[New] 2024 Approved Facebook's Top Visual Discoveries A Guide</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ow-much-can-you-earn-on-youtube-via-ad-revenue-for-2024/"><u>[New] How Much Can You Earn on YouTube via Ad Revenue for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-navigating-youtubes-landscape-a-beginners-primer/"><u>[New] In 2024, Navigating YouTube's Landscape A Beginner's Primer</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-the-new-standard-how-does-av1-outperform-vp9/"><u>[Updated] 2024 Approved The New Standard How Does AV1 Outperform VP9?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-xiaomi-redmi-note-13-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Xiaomi Redmi Note 13 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-increase-dedicated-video-ram-vram-in-windows-11-and-11/"><u>How to Increase Dedicated Video RAM (VRAM) in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-locate-pcs-current-window-background-file/"><u>How to Locate PC's Current Window Background File</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>In 2024, Read This Guide to Find a Reliable Alternative to Fake GPS On Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-realme-gt-5-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Realme GT 5 Phone Network-Ready</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/master-your-privacy-with-stellar-file-eraser-v5-the-ultimate-standard-edition-for-windows-data-cleanse/"><u>Master Your Privacy with Stellar File Eraser v5: The Ultimate Standard Edition for Windows Data Cleanse</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-11-bypassing-hiccups-and-blockades/"><u>Streamlining Windows 11: Bypassing Hiccups & Blockades</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-your-digital-sketchpad-launching-ms-paint-on-win11/"><u>Unveiling Your Digital Sketchpad: Launching MS Paint on Win11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    