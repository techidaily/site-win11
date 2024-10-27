---
title: "Security Concern: Hacked Biometrics in Windows Hello"
date: 2024-10-23T00:49:31.635Z
updated: 2024-10-27T05:31:41.460Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Security Concern: Hacked Biometrics in Windows Hello"
excerpt: "This Article Describes Security Concern: Hacked Biometrics in Windows Hello"
keywords: Windows Hello Breach,Biometric Security Flaw,Hacked Identity Protection,Safe Login Systems,Facial Recognition Risks,Password Replacement Dangers,Enhanced Biometric Safety
thumbnail: https://thmb.techidaily.com/3da56b4dd62c9d29faa422fa86eb533c5fdaa7995cd6fe5de9f6ecf749c3b6f7.jpg
---

## Security Concern: Hacked Biometrics in Windows Hello

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137202/26400" target="_top" id="2137202">
  <img src="//a.impactradius-go.com/display-ad/26400-2137202" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137202/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How the Hackers Breached Windows Hello on the Dell Inspiron 15

 For the Dell Inspiron 15, the hackers noticed they could boot into Linux on the laptop. Once logged into Linux, they can register their fingerprints in the system and give it the same ID as the Windows user they want to log into.

 Then, they perform a man-in-the-middle attack on the connection between the PC and the sensor. They set it up so that when Windows goes to double-check that a scanned fingerprint is legitimate, it ends up checking the Linux database of fingerprints instead of its own.

 To dodge Windows Hello, the hackers uploaded their fingerprints to the Linux database, assigned it the same ID as the user on Windows, and then tried to log into Windows with their fingerprints. During the authentication process, they redirected the packet to the Linux database, which told Windows that the user at the specified ID was ready to log in.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997680/19272" target="_top" id="1997680">
  <img src="//a.impactradius-go.com/display-ad/19272-1997680" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997680/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130529/26400" target="_top" id="2130529">
  <img src="//a.impactradius-go.com/display-ad/26400-2130529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130529/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. The Attacks Only Work on Specific Devices

 You'll notice that each attack had to take a different path to achieve the same goal. Every device is unique, and a hack that works on one device may not work on another. As such, you shouldn't believe that Windows Hello has now been blown wide open on every device; it's just these three that failed.

 While these hacks may sound scary, they'll be challenging to perform against actual targets. The hacker will likely have to steal the device to perform these hacks, which would undoubtedly alert the previous owner.

## How to Stay Safe From Fingerprint Hacking

![The face of a man wearing a hoodie](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hacher-hat.jpg)

 As stated above, the discovered hacks are complicated to perform and may require the hacker to remove the device to hack into it physically. As such, there's an extremely low chance that these attacks will personally target you.

 However, if you're still not satisfied, there are some ways to protect yourself from fingerprint scanner hacks:

### 1\. Do Not Leave Devices Unattended and Unprotected

 Because a hacker will need to interact with your device physically, you should ensure it doesn't fall into the wrong hands. For computers, you can [take steps to stop it from being stolen](https://www.makeuseof.com/tag/stop-entire-desktop-pc-home-office-stolen/). If you're using a laptop, never leave it alone in a public space, and use an [anti-theft laptop bag](https://www.makeuseof.com/tag/anti-theft-laptop-bags/) to stop people from tearing your bag open.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144282/7443" target="_top" id="2144282">
  <img src="//a.impactradius-go.com/display-ad/7443-2144282" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144282/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Use a Different Login Method

 Windows Hello supports many different login methods, some more secure than others. If you've fallen out of love with fingerprint scans, check out if [face, iris, fingerprint, PIN, or password logins are more secure](https://www.makeuseof.com/face-iris-fingerprint-password-pin-most-secure/), and choose one that suits you best.

 If you're worried about these hacks, it's important to remember that there's a very low chance they'll target you specifically. As such, you should be safe using fingerprint scans; just don't allow people to steal your devices.

 So, how can people hack past a Windows Hello fingerprint scan, and should you worry about it?

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-capture.techidaily.com/new-streaming-to-the-next-level-the-top-5-game-cameras-reviewed-for-2024/"><u>[New] Streaming to the Next Level The Top 5 Game Cameras Reviewed for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-tech-tutorial-record-on-hangouts-for-2024/"><u>[New] Tech Tutorial Record on Hangouts for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-become-a-design-pro-expertise-in-bypassing-backgrounds-with-canva/"><u>[Updated] Become a Design Pro Expertise in Bypassing Backgrounds with Canva</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-gopro-guide-achieving-excellent-underwater-cinematography/"><u>[Updated] GoPro Guide Achieving Excellent Underwater Cinematography</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-fixing-audio-gaps-in-social-network-videos/"><u>[Updated] In 2024, Fixing Audio Gaps in Social Network Videos</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/choosing-the-best-apple-wireless-speaker-a-comparison-between-homepod-and-homepod-mini-insights-from-zdnet/"><u>Choosing the Best Apple Wireless Speaker: A Comparison Between HomePod and HomePod Mini - Insights From ZDNet</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-differences-exe-vs-msi-installation/"><u>Decoding the Differences: Exe vs Msi Installation</u></a></li>
<li><a href="https://win11.techidaily.com/discover-best-free-desktop-password-makers-on-windows/"><u>Discover Best Free Desktop Password Makers on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/easing-updates-on-windows-1011-without-administrative-rights/"><u>Easing Updates on Windows 10/11 without Administrative Rights</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-correct-oculus-errors-in-windows-1110/"><u>Essential Tips to Correct Oculus Errors in Windows 11/10</u></a></li>
<li><a href="https://vp-tips.techidaily.com/how-to-efficiently-reduce-mp4-file-size-on-windows-10-and-macos/"><u>How to Efficiently Reduce MP4 File Size on Windows (10) and macOS</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-zte-blade-a73-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On ZTE Blade A73 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-improve-cloud-storage-access-fixing-onedrive-in-w11/"><u>How to Improve Cloud Storage Access: Fixing OneDrive in W11</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-tips-for-navigating-windows-11-widgets/"><u>Innovative Tips for Navigating Windows 11 Widgets</u></a></li>
<li><a href="https://fox-links.techidaily.com/navigating-virtual-realms-iphone-vr-video-playback/"><u>Navigating Virtual Realms IPhone VR Video Playback</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-challenge-winning-back-manager-tool-access-on-windows-11/"><u>Overcoming the Challenge: Winning Back Manager Tool Access on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-windows-11s-error-0x0000011b/"><u>Remedy for Windows 11'S Error 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-windows-keys-not-typing-properly/"><u>Solutions for Windows Keys Not Typing Properly</u></a></li>
<li><a href="https://some-tips.techidaily.com/ultimate-guide-to-macro-videography-techniques-for-2024/"><u>Ultimate Guide to Macro Videography Techniques for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    