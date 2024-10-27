---
title: "Digital Dilemnas: Windows Fingerprint Hacking Concerns Rising"
date: 2024-10-26T06:13:25.282Z
updated: 2024-10-26T21:05:47.207Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Digital Dilemnas: Windows Fingerprint Hacking Concerns Rising"
excerpt: "This Article Describes Digital Dilemnas: Windows Fingerprint Hacking Concerns Rising"
keywords: Window Fingerprint Hack,Digital Security Woes,Fingerprint Risks,Privacy Dilemmas,Windows Biometric,Tech Safety Concerns,Identity Theft Alert
thumbnail: https://thmb.techidaily.com/62d72eb39093270995757df1adc43019ed0e362b73decee245e264928d768a5a.jpg
---

## Digital Dilemnas: Windows Fingerprint Hacking Concerns Rising

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

### How the Hackers Breached Windows Hello on the Microsoft Surface Pro Type Cover

 The hackers believed the Surface Pro would be the hardest device to crack, but they were surprised to find the Surface Pro lacked a lot of security measures for checking valid fingerprints. In fact, they discovered that they only had to dodge past one defense, then tell the Surface Pro that the fingerprint scan was successful, and the device let them in.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075462/7443" target="_top" id="2075462">
  <img src="//a.impactradius-go.com/display-ad/7443-2075462" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075462/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)

 These hacks may sound pretty scary if you use fingerprints to log into your laptop. However, it's essential to remember some crucial things before you forgo fingerprint scans entirely.

### 1\. The Attacks Were Performed by Skilled Hackers

 The reason threats like [ransomware as a service](https://www.makeuseof.com/what-is-ransomware-as-a-service/) are so deadly is that anyone with minimal cybersecurity can use them. However, the above hacks require a high level of expertise, with a deep understanding of how devices authenticate fingerprints and how to avoid them.

### 2\. The Attacks Require the Attacker to Physically Interact With the Device

 The hackers must have physical contact with the device to perform the above hacks. In the report, the hackers stated they might be able to create USB devices that can perform the attack once plugged in, but that means a potential attacker needs to plug something into your PC to hack it.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005183/22899" target="_top" id="2005183">
  <img src="//a.impactradius-go.com/display-ad/22899-2005183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005183/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

## How to Stay Safe From Fingerprint Hacking

![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135370/19272" target="_top" id="2135370">
  <img src="//a.impactradius-go.com/display-ad/19272-2135370" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135370/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896527/19272" target="_top" id="1896527">
  <img src="//a.impactradius-go.com/display-ad/19272-1896527" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896527/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Use a Different Login Method

 Windows Hello supports many different login methods, some more secure than others. If you've fallen out of love with fingerprint scans, check out if [face, iris, fingerprint, PIN, or password logins are more secure](https://www.makeuseof.com/face-iris-fingerprint-password-pin-most-secure/), and choose one that suits you best.

 If you're worried about these hacks, it's important to remember that there's a very low chance they'll target you specifically. As such, you should be safe using fingerprint scans; just don't allow people to steal your devices.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-access.techidaily.com/new-newbies-manual-to-vector-art-grasping-different-kinds-and-software/"><u>[New] Newbie’s Manual to Vector Art Grasping Different Kinds & Software</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-a-song-of-ice-and-fire-top-sites-to-snatch-game-of-thrones-ringtones-for-2024/"><u>[Updated] A Song of Ice and Fire Top Sites to Snatch Game of Thrones Ringtones for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-establishing-value-driven-partnerships-with-brand-sponsors-in-youtubesphere/"><u>[Updated] Establishing Value-Driven Partnerships with Brand Sponsors in Youtubesphere</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-evaluating-toolwiz-in-a-world-of-mobile-photography-apps-for-2024/"><u>[Updated] Evaluating Toolwiz in a World of Mobile Photography Apps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-n-series-usefulness-and-viability/"><u>Decoding Windows N Series: Usefulness and Viability</u></a></li>
<li><a href="https://win11.techidaily.com/driving-earnings-with-windows-11-a-microsoft-perspective/"><u>Driving Earnings with Windows 11: A Microsoft Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/eradicate-chrome-glitches-a-windows-solution/"><u>Eradicate Chrome Glitches: A Windows Solution</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-loophole-ideas-for-7-hilarious-youtube-showcases-for-2024/"><u>Laugh Loophole Ideas for 7 Hilarious YouTube Showcases for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-ping-for-peak-performance-on-your-windows-devices/"><u>Leveraging Ping for Peak Performance on Your Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/pathways-to-a-new-beginning-windows-in-three-stages/"><u>Pathways to a New Beginning: Windows in Three Stages</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Xiaomi 14 Ultra? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-display-of-windows-amdnvidia-boost/"><u>Prevent Display of Windows' AMD/Nvidia Boost</u></a></li>
<li><a href="https://win11.techidaily.com/push-the-envelope-with-these-8-customizations-by-winbubble/"><u>Push The Envelope with These 8 Customizations by WinBubble</u></a></li>
<li><a href="https://fox-making.techidaily.com/step-by-step-tutorial-converting-android-pdfs-into-microsoft-word-format-for-efficient-editing-updated-for-2020/"><u>Step-by-Step Tutorial: Converting Android PDFs Into Microsoft Word Format for Efficient Editing (Updated for 2020)</u></a></li>
<li><a href="https://win11.techidaily.com/the-non-advanced-path-to-disk-replication/"><u>The Non-Advanced Path to Disk Replication</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-untouched-understandings-in-ml-mastery/"><u>Unveiling Untouched Understandings in ML Mastery</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-now-get-the-newest-samsung-nvme-850-evo-controller-drivers-for-optimal-performance/"><u>Update Now: Get the Newest Samsung Nvme 850 EVO Controller Drivers for Optimal Performance</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-oppo-f25-pro-5g-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Oppo F25 Pro 5G Phone Network-Ready</u></a></li>
<li><a href="https://win11.techidaily.com/your-lost-wingman-copilot-in-windows-11-what-now/"><u>Your Lost Wingman (Copilot) in Windows 11, What Now?</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    