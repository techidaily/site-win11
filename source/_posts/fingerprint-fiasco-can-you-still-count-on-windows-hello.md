---
title: "Fingerprint Fiasco: Can You Still Count on Windows Hello?"
date: 2024-06-25T11:26:17.827Z
updated: 2024-06-26T11:26:17.827Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Fingerprint Fiasco: Can You Still Count on Windows Hello?"
excerpt: "This Article Describes Fingerprint Fiasco: Can You Still Count on Windows Hello?"
keywords: Windows Hello Security,Facial Recognition Failure,Fingerprint False ID,Biometric Lockdown,Identity Verification Issues,TouchID Troubleshoot,Faseroom Login Concerns
thumbnail: https://thmb.techidaily.com/a68c5c5018f608284d7af133f2911830741f898253edd18111f294ce2b839027.jpg
---

## Fingerprint Fiasco: Can You Still Count on Windows Hello?

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
<li><a href="https://win11.techidaily.com/restoring-access-post-error-code-22-fixing-a-locked-down-pc-in-windows-11/"><u>Restoring Access Post-Error Code 22: Fixing a Locked Down PC in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/key-to-the-past-windows-11s-historical-files-retrieval/"><u>Key to the Past: Windows 11’S Historical Files Retrieval</u></a></li>
<li><a href="https://win11.techidaily.com/minimalist-pc-large-space-slight-lag/"><u>Minimalist PC - Large Space, Slight Lag</u></a></li>
<li><a href="https://win11.techidaily.com/essential-insights-into-os-upgrade-schedules-and-methods/"><u>Essential Insights Into OS Upgrade Schedules & Methods</u></a></li>
<li><a href="https://win11.techidaily.com/rearranging-display-panel-configurations/"><u>Rearranging Display Panel Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-overheating-prevention-on-windows-pcs/"><u>Adjusting Overheating Prevention on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/disguising-or-displaying-time-win-1011-tutorial/"><u>Disguising or Displaying Time: Win 10/11 Tutorial</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-say-goodbye-to-vertical-and-horizontal-bars-in-youtube-movies/"><u>In 2024, Say Goodbye to Vertical and Horizontal Bars in YouTube Movies</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-pro-free-ending-makers-ranked-1-6/"><u>2024 Approved  Pro-FREE Ending Makers - Ranked 1-6</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-2024-approved-best-5-audio-ducking-software-you-should-know/"><u>New 2024 Approved Best 5 Audio Ducking Software You Should Know</u></a></li>
<li><a href="https://extra-information.techidaily.com/fusionphotosync-designers-slide-show-tool/"><u>FusionPhotosync  Designers' Slide Show Tool</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-exploring-options-a-treasure-hunt-for-your-tiktok-symbol/"><u>[New] In 2024, Exploring Options  A Treasure Hunt for Your TikTok Symbol</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/the-voiceover-revolution-in-tiktok-content-creation/"><u>The Voiceover Revolution in TikTok Content Creation</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-5-expert-approaches-to-preserve-virtual-reality-adventures/"><u>[New] 2024 Approved  5 Expert Approaches to Preserve Virtual Reality Adventures</u></a></li>
<li><a href="https://techidaily.com/what-should-i-do-if-i-dont-find-the-deleted-iphone-15-pro-files-after-scanning-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>What should I do if I dont find the deleted iPhone 15 Pro files after scanning? | Stellar</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>