---
title: Your Smart Lock at Risk? Windows Hello's Latest Security Threat
date: 2024-08-28T00:52:31.686Z
updated: 2024-08-29T00:52:31.686Z
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

## Can People Hack Windows Hello Fingerprint Scanners?

![Lock Having Fingerprint in the Middle on Blue Background](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/passwords-are-a-thing-of-the-past-passwordless-logins-benefits.jpg)

 If a hacker wants to bypass a fingerprint scanner on a Windows machine, they're aiming to get past a service called Windows Hello. This service handles how you log into Windows, such as PINs, facial scans, and fingerprint scans.

 As part of research into Windows Hello's strength, two [white-hat hackers](https://www.makeuseof.com/white-hat-hacker/), Jesse D'Aguanno and Timo Teräs, posted a report on their website, [Blackwing HQ](https://blackwinghq.com/blog/posts/a-touch-of-pwn-part-i/). The report details how they breached three popular devices: the Dell Inspiron 15, Lenovo ThinkPad T14, and the Microsoft Surface Pro Type Cover.

### How the Hackers Breached Windows Hello on the Dell Inspiron 15

 For the Dell Inspiron 15, the hackers noticed they could boot into Linux on the laptop. Once logged into Linux, they can register their fingerprints in the system and give it the same ID as the Windows user they want to log into.

 Then, they perform a man-in-the-middle attack on the connection between the PC and the sensor. They set it up so that when Windows goes to double-check that a scanned fingerprint is legitimate, it ends up checking the Linux database of fingerprints instead of its own.

 To dodge Windows Hello, the hackers uploaded their fingerprints to the Linux database, assigned it the same ID as the user on Windows, and then tried to log into Windows with their fingerprints. During the authentication process, they redirected the packet to the Linux database, which told Windows that the user at the specified ID was ready to log in.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How the Hackers Breached Windows Hello on the Lenovo ThinkPad T14

 For the Lenovo ThinkPad, the hackers discovered that the laptop used a custom encryption method to verify fingerprints. With some work, the hackers managed to decrypt it, giving them a way into the fingerprint verification process.

 Once done, the hackers could force the fingerprint database to accept their fingerprint as the user's. Then, all they had to do was scan their fingerprint to access the Lenovo ThinkPad.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
### How the Hackers Breached Windows Hello on the Microsoft Surface Pro Type Cover

 The hackers believed the Surface Pro would be the hardest device to crack, but they were surprised to find the Surface Pro lacked a lot of security measures for checking valid fingerprints. In fact, they discovered that they only had to dodge past one defense, then tell the Surface Pro that the fingerprint scan was successful, and the device let them in.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
## What Do These Hacks Mean for You?

![Professional Thinking With Laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/11/professional-thinking-with-laptop.jpg)

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
 These hacks may sound pretty scary if you use fingerprints to log into your laptop. However, it's essential to remember some crucial things before you forgo fingerprint scans entirely.

### 1\. The Attacks Were Performed by Skilled Hackers

 The reason threats like [ransomware as a service](https://www.makeuseof.com/what-is-ransomware-as-a-service/) are so deadly is that anyone with minimal cybersecurity can use them. However, the above hacks require a high level of expertise, with a deep understanding of how devices authenticate fingerprints and how to avoid them.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. The Attacks Require the Attacker to Physically Interact With the Device

 The hackers must have physical contact with the device to perform the above hacks. In the report, the hackers stated they might be able to create USB devices that can perform the attack once plugged in, but that means a potential attacker needs to plug something into your PC to hack it.

### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
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
<li><a href="https://desktop-recording.techidaily.com/new-how-android-enables-seamless-screen-capturing-for-2024/"><u>[New] How Android Enables Seamless Screen Capturing for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-best-sixers-comprehensive-4k-camera-guide/"><u>2024 Approved  Best Sixer's Comprehensive 4K Camera Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-tips-for-gradual-decrease-of-audio-loudness-in-fl-studio/"><u>2024 Approved  Tips for Gradual Decrease of Audio Loudness in FL Studio</u></a></li>
<li><a href="https://win11.techidaily.com/connectivity-compass-navigating-through-4-ways-of-net-speed-check/"><u>Connectivity Compass: Navigating Through 4 Ways of Net Speed Check</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-code-e84-in-steam-games/"><u>Eliminating Error Code E84 in Steam Games</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-no-device-drivers-detected-in-windows-setup/"><u>Eliminating Error: No Device Drivers Detected in Windows Setup</u></a></li>
<li><a href="https://program-issues.techidaily.com/enhance-ark-gameplay-master-the-art-of-fps-boosting-on-pc/"><u>Enhance ARK Gameplay: Master the Art of FPS Boosting on PC</u></a></li>
<li><a href="https://win11.techidaily.com/enriching-text-input-experience-integrating-wordpad-triggers-in-windows-11/"><u>Enriching Text Input Experience: Integrating WordPad Triggers in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-lowering-wlanext-cpu-usage/"><u>Essential Tips for Lowering WLANEXT CPU Usage</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/exclusive-review-of-the-best-philips-somneo-alarm-clock-on-the-market/"><u>Exclusive Review of the Best Philips Somneo Alarm Clock on the Market</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-on-skyrocketing-your-cs-gameplay/"><u>Expert Advice on Skyrocketing Your CS Gameplay</u></a></li>
<li><a href="https://win11.techidaily.com/from-apple-to-microsoft-transition-guide-for-windows-11-via-parallels/"><u>From Apple to Microsoft: Transition Guide for Windows 11 via Parallels</u></a></li>
<li><a href="https://win11.techidaily.com/from-old-extensions-to-new-ones-the-windows-way/"><u>From Old Extensions to New Ones: The Windows Way</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reducing-sound-boost-in-windows/"><u>Guide to Reducing Sound Boost in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-windows-11-secures-your-files-understanding-the-backup-feature/"><u>How Windows 11 Secures Your Files: Understanding the Backup Feature</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/how-to-manual-for-creating-an-inclusive-and-productive-skype-chat-room-accessible-by-both-windows-and-mac-users-for-2024/"><u>How-To Manual for Creating an Inclusive and Productive Skype Chat Room Accessible by Both Windows & Mac Users for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-poco-c65-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Poco C65</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/integrating-igtv-videos-with-your-facebook-network-for-2024/"><u>Integrating IGTV Videos with Your Facebook Network for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/mastering-the-art-of-accessing-your-facebook-watchlist-for-2024/"><u>Mastering the Art of Accessing Your Facebook Watchlist for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-video-playback-rate-adjustments-in-snapchat-for-2024/"><u>Mastering Video Playback Rate Adjustments in Snapchat for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-locked-credential-management/"><u>Navigating Locked Credential Management</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-file-selection-activating-filters-with-box-on-win11/"><u>Optimal File Selection: Activating Filters with Box on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-chromes-screen-darkness-problem/"><u>Overcoming Chrome's Screen Darkness Problem</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-obstacles-windows-11-manager-access-restoration-techniques/"><u>Overcoming Obstacles: Windows 11 Manager Access Restoration Techniques</u></a></li>
<li><a href="https://technical-tips.techidaily.com/quick-guide-top-5-methods-for-rapid-removal-of-audiobooks-from-your-library/"><u>Quick Guide: Top 5 Methods for Rapid Removal of Audiobooks From Your Library</u></a></li>
<li><a href="https://win11.techidaily.com/reactivating-a-non-functional-windows-11-search-box-in-the-ui/"><u>Reactivating a Non-Functional Windows 11 Search Box in the UI</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-uninstalled-hdd-in-windows-11-a-step-by-step-guide/"><u>Resolving Uninstalled HDD in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-missing-banner-icons/"><u>Solutions for Missing Banner Icons</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-recognize-absconded-drive-issues/"><u>Solutions to Recognize Absconded Drive Issues</u></a></li>
<li><a href="https://hardware-help.techidaily.com/speedy-and-hassle-free-wacom-driver-installation/"><u>Speedy and Hassle-Free Wacom Driver Installation</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-entry-tricks-beat-delayed-inputs-in-windows-11-environment/"><u>Speedy Entry Tricks: Beat Delayed Inputs in Windows 11 Environment</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-turning-on-mouse-gestures-in-windows-11s-edge/"><u>Step-by-Step: Turning on Mouse Gestures in Windows 11'S Edge</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-alleviate-full-capacity-error-windows/"><u>Steps to Alleviate Full-Capacity Error Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-and-revitalize-windows-timer-functions/"><u>Streamline and Revitalize Windows Timer Functions</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/techniques-for-streaming-seminars-on-a-fee-free-basis/"><u>Techniques for Streaming Seminars on a Fee-Free Basis</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-compilation-of-html5s-best-video-tools/"><u>The Ultimate Compilation of HTML5's Best Video Tools</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-sticking-notebooks-front-and-center/"><u>Tips for Sticking Notebooks Front and Center</u></a></li>
<li><a href="https://win11.techidaily.com/triumph-over-obstacles-disable-windows-11-tpm-swiftly/"><u>Triumph Over Obstacles: Disable Windows 11 TPM Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-enterprise-controlled-chromeedge-browsers-on-pcs/"><u>Troubleshooting Enterprise-Controlled Chrome/Edge Browsers on PCs</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/unmissable-discounts-on-ipads-shop-the-latest-savings-now/"><u>Unmissable Discounts on iPads – Shop the Latest Savings Now!</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-error-262-robloxs-solution-path/"><u>Unraveling Error 262: Roblox's Solution Path</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-top-7-strong-reasons-why-you-shouldnt-upgrade-to-win11/"><u>Unveiling Top 7 Strong Reasons Why You Shouldn't Upgrade to Win11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-reserve-a-detailed-look-at-memory-management/"><u>Windows Reserve: A Detailed Look at Memory Management</u></a></li>
<li><a href="https://win11.techidaily.com/windows-strategies-to-identify-your-intel-processor-gen/"><u>Windows Strategies to Identify Your Intel Processor Gen</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-online-how-to-mend-fall-guys-connection-glitches-on-pc/"><u>Winning Back Online: How to Mend Fall Guys Connection Glitches on PC</u></a></li>
<li><a href="https://win-blog.techidaily.com/winning-the-battle-against-chrome-freezing-tips-for-windows-11-users/"><u>Winning the Battle Against Chrome Freezing - Tips for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/winning-war-against-sse-windows-woes/"><u>Winning War Against SSE Windows Woes</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>