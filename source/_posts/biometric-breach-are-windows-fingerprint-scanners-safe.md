---
title: "Biometric Breach: Are Windows Fingerprint Scanners Safe?"
date: 2024-07-13T11:27:06.846Z
updated: 2024-07-14T11:27:06.846Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Biometric Breach: Are Windows Fingerprint Scanners Safe?"
excerpt: "This Article Describes Biometric Breach: Are Windows Fingerprint Scanners Safe?"
keywords: Windows Fingerprint Security,Biometric Data Safety,Fingerprint Scanner Risks,Breach in Biometrics,Secure Fingerprint Tech,Windows TouchID Threats,Safe Biometric Devices
thumbnail: https://thmb.techidaily.com/9687aa834ae00807e9d2f77ee77a3ac9fdfd8db29a944a670186797d57bfaab8.jpg
---

## Biometric Breach: Are Windows Fingerprint Scanners Safe?

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
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-perfect-harmony-unveiling-the-best-5-mixers-for-mac-enthusiasts/"><u>2024 Approved Perfect Harmony Unveiling the Best 5 Mixers for Mac Enthusiasts</u></a></li>
<li><a href="https://extra-skills.techidaily.com/optimal-webcams-to-improve-your-zoom-video-interactions-for-2024/"><u>Optimal Webcams to Improve Your Zoom Video Interactions for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-delve-into-the-realm-of-mirthful-noises-for-2024/"><u>Updated Delve Into the Realm of Mirthful Noises for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-metaverse-vs-multimetverse-what-are-the-differences-ultimate-guide/"><u>2024 Approved  Metaverse Vs. MultiMetverse  What Are the Differences [Ultimate Guide]</u></a></li>
<li><a href="https://win11.techidaily.com/blackview-minipc-storage-space-speeds-still-sparse/"><u>Blackview MiniPC: Storage Space - Speeds Still Sparse</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-write-prohibited-steam-directories-in-win-11/"><u>Addressing Write-Prohibited Steam Directories in Win 11</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-recording-sims-4-games-professionally/"><u>2024 Approved  Recording Sims 4 Games Professionally</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/leading-mp3-to-text-conversion-tools-unveiled-for-2024/"><u>Leading MP3-to-Text Conversion Tools Unveiled for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-perfecting-drone-captured-imagery-a-gimbal-journey/"><u>2024 Approved  Perfecting Drone-Captured Imagery  A Gimbal Journey</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-out-of-space-issue-in-windows-oses/"><u>Addressing Out-of-Space Issue in Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/adopting-new-visual-elements-the-microsoft-store-experience/"><u>Adopting New Visual Elements: The Microsoft Store Experience</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-package-malfunctions-in-windows-updates/"><u>Addressing Package Malfunctions in Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overloaded-capacity-alerts-on-pcsupremum/"><u>Avoiding Overloaded Capacity Alerts on PC'supremum</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-infinix-hot-30i-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Infinix Hot 30i Phone Without Password?</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tactics-to-boost-file-organization-with-multi-folder-setup-in-windows-1011/"><u>Advanced Tactics to Boost File Organization with Multi-Folder Setup in Windows 10/11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-access-your-apple-iphone-7-when-you-forget-the-passcode-by-drfone-ios/"><u>How to Access Your Apple iPhone 7 When You Forget the Passcode?</u></a></li>
<li><a href="https://win11.techidaily.com/block-unwanted-startup-stop-snipping-tool-from-prtscan-on-win-11/"><u>Block Unwanted Startup: Stop Snipping Tool From PrtScan on Win 11</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-2024-approved-invest-in-quality-best-4k-mirrorless-under-1000/"><u>[New] 2024 Approved  Invest in Quality  Best 4K Mirrorless Under $1,000</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/add-amazing-filters-and-effects-for-fun-to-watch-gifs-using-adobe-after-effects-read-on-to-discover-an-easy-to-learn-after-effects-alternative/"><u>Add Amazing Filters and Effects for Fun to Watch GIFs Using Adobe After Effects. Read on to Discover an Easy-to-Learn After Effects Alternative</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-complete-guide-to-lava-yuva-2-pro-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Lava Yuva 2 Pro FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-essential-win11-and-cmd-commands/"><u>Boosting Productivity: Essential Win11 and Cmd Commands</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-administration-local-groups-and-users/"><u>Boosting Windows Administration: Local Groups and Users</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-best-windows-video-calls-the-top-8-list/"><u>[New] In 2024, Best Windows Video Calls  The Top 8 List</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-remote-procedure-call-mishaps-in-windows/"><u>Avoiding Remote Procedure Call Mishaps in Windows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-retro-editing-magic-cutting-classical-cinematography/"><u>2024 Approved  Retro Editing Magic  Cutting Classical Cinematography</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/spoof-ballads-and-jests-the-funniest-sounds/"><u>Spoof Ballads & Jests  The Funniest Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-a-valid-temp-folder-in-windows-11/"><u>Best Practices for a Valid Temp Folder in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-sluggish-pace-of-win-based-outlook/"><u>Beat the Sluggish Pace of Win-Based Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/boost-work-efficiency-select-6-best-pc-monitoring-apps/"><u>Boost Work Efficiency: Select 6 Best PC Monitoring Apps</u></a></li>
<li><a href="https://win11.techidaily.com/boot-overhaul-guide-windows-revival-in-eight-steps/"><u>Boot Overhaul Guide: Windows Revival in Eight Steps</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-organize-your-fb-content-access-to-free-downloaders-online/"><u>2024 Approved  Organize Your FB Content  Access to Free Downloaders Online</u></a></li>
<li><a href="https://win11.techidaily.com/baffling-taskers-display-with-edge-and-others/"><u>Baffling Tasker's Display with Edge & Others</u></a></li>
<li><a href="https://win11.techidaily.com/arrow-troubles-15-windows-fixes-to-consider/"><u>Arrow Troubles? 15 Windows Fixes to Consider</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disconnection-hurdles-in-nvidia-for-windows-users/"><u>Addressing Disconnection Hurdles in Nvidia for Windows Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-interface-interlink-bridging-ig-and-tiktok-worlds-for-2024/"><u>The Interface Interlink  Bridging IG & TikTok Worlds for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-smooth-mouse-movement-on-modern-windows-oses/"><u>Achieving Smooth Mouse Movement on Modern Windows OSes</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-smooth-moves-5-best-free-video-stabilizers-for-android-devices/"><u>2024 Approved Smooth Moves 5 Best Free Video Stabilizers for Android Devices</u></a></li>
<li><a href="https://techidaily.com/hard-reset-itel-s23-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Itel S23 in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-the-workload-of-ntoskrnlexe/"><u>Balancing the Workload of Ntoskrnl.exe</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-the-deadly-javascript-error-from-discord-on-win-11/"><u>Banishing the Deadly JavaScript Error From Discord on Win 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-overcoming-virtual-reality-discomfort/"><u>[New] Overcoming Virtual Reality Discomfort</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-top-keys-fan-secrets-for-free-windows-11-at-612lifetime/"><u>Black Friday: Top Keys Fan Secrets for Free Windows 11 at $6.12/Lifetime</u></a></li>
<li><a href="https://youtube-web.techidaily.com/outubes-shorts-thumbnail-dilemnas-and-quick-fixes-for-2024/"><u>[New] YouTube's Shorts Thumbnail Dilemnas & Quick Fixes for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-top-rated-free-video-editing-software-for-newbies/"><u>Updated Top-Rated Free Video Editing Software for Newbies</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-microsoft-edge-performance-in-win10win11/"><u>Boosting Microsoft Edge Performance in Win10/Win11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-how-to-add-captions-to-instagram-videos-for-2024/"><u>[Updated] How to Add Captions to Instagram Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-sonic-full-screen-pitfalls-on-windows-11-os/"><u>Avoiding Sonic Full-Screen Pitfalls on Windows 11 OS</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-the-ultimate-recording-playbook-your-roblox-adventures-transformed-for-2024/"><u>[New] The Ultimate Recording Playbook  Your Roblox Adventures, Transformed for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>