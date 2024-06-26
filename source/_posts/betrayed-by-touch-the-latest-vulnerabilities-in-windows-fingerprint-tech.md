---
title: "Betrayed by Touch: The Latest Vulnerabilities in Windows Fingerprint Tech"
date: 2024-06-25T11:35:04.596Z
updated: 2024-06-26T11:35:04.596Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Betrayed by Touch: The Latest Vulnerabilities in Windows Fingerprint Tech"
excerpt: "This Article Describes Betrayed by Touch: The Latest Vulnerabilities in Windows Fingerprint Tech"
keywords: Fingerprint Tech Weaknesses,Windows Biometric Risks,Touch Security Breaches,Fingerprint Recognition Vulnerabilities,Windows Authentication Gaps,Privacy in Touch Technology,Secure Fingerprinting Devices
thumbnail: https://thmb.techidaily.com/1b6976e6cb0861a8e856af8d9b91eb1dc370f068cc6322414a1134e31c0876a0.jpg
---

## Betrayed by Touch: The Latest Vulnerabilities in Windows Fingerprint Tech

 Logging into a Windows laptop with a fingerprint scanner is easy; just place your finger on a scanner, and the operating system lets you in. However, researchers have shown that, while this method is convenient, it's not hackproof.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

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

 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

### 2\. Use a Different Login Method

 Windows Hello supports many different login methods, some more secure than others. If you've fallen out of love with fingerprint scans, check out if [face, iris, fingerprint, PIN, or password logins are more secure](https://www.makeuseof.com/face-iris-fingerprint-password-pin-most-secure/), and choose one that suits you best.

 If you're worried about these hacks, it's important to remember that there's a very low chance they'll target you specifically. As such, you should be safe using fingerprint scans; just don't allow people to steal your devices.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/reinstating-legacy-boot-configurations/"><u>Reinstating Legacy Boot Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-clearing-microsoft-protection-archives/"><u>Mastering the Art of Clearing Microsoft Protection Archives</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-common-roadblocks-in-windows-app-functionality/"><u>Overcoming Common Roadblocks in Windows App Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-a-non-operational-windows-netflix-service/"><u>Troubleshooting a Non-Operational Windows Netflix Service</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-restricted-administrator-error-in-winsec/"><u>Overcoming Restricted Administrator Error in WinSec</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-notification-interface-in-win-11/"><u>Tailoring Your Notification Interface in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-new-folders-into-windows-11s-menu/"><u>Integrating New Folders Into Windows 11'S Menu</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-syncing-your-phone-with-windows-11-via-unison/"><u>Expert Tips: Syncing Your Phone with Windows 11 via Unison</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-updates-error-0x80242016-fix/"><u>Mastering Windows Updates' Error 0X80242016 Fix</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-detailed-survey-gecatas-game-capture-utility/"><u>[New] 2024 Approved  Detailed Survey  Gecata's Game Capture Utility</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-10-best-tools-to-bypass-icloud-activation-lock-on-apple-iphone-7-plus-you-should-try-out-by-drfone-ios/"><u>In 2024, The 10 Best Tools to Bypass iCloud Activation Lock On Apple iPhone 7 Plus You Should Try Out</u></a></li>
<li><a href="https://youtube-data.techidaily.com/xploring-object-oriented-programming-for-complex-applications-for-2024/"><u>[New] Exploring Object-Oriented Programming for Complex Applications for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-leveraging-xbox-ones-zoom-features-effectively/"><u>[New] Leveraging Xbox One's Zoom Features Effectively</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-the-young-cinematographer-empowering-kids-to-tell-their-stories/"><u>New 2024 Approved The Young Cinematographer Empowering Kids to Tell Their Stories</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-install-device-drivers-manually-on-windows-11-and-10-by-drivereasy-guide/"><u>How to install device drivers manually on Windows 11 & 10</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-top-5-quick-filming-diy-hacks-to-try-at-home/"><u>In 2024, Top 5 Quick Filming DIY Hacks to Try at Home</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-6-best-free-mov-video-cutter-tools-for-beginners/"><u>Updated In 2024, 6 Best Free MOV Video Cutter Tools for Beginners</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-skype-voice-changer-5-useful-tools-to-change-voice-for-skype/"><u>Updated In 2024, Skype Voice Changer 5 Useful Tools to Change Voice for Skype</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-chord-connoisseurs-top-choice-mobile-apps-for-identifying-songs-on-android-devices/"><u>Updated In 2024, Chord Connoisseurs Top Choice Mobile Apps for Identifying Songs on Android Devices</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>