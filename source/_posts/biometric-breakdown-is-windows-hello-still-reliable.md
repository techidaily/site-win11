---
title: "Biometric Breakdown: Is Windows Hello Still Reliable?"
date: 2025-02-25T17:48:23.155Z
updated: 2025-03-04T22:16:00.972Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Biometric Breakdown: Is Windows Hello Still Reliable?"
excerpt: "This Article Describes Biometric Breakdown: Is Windows Hello Still Reliable?"
keywords: Biometric Security,Windows Login,Facial Recognition,Tech Reliability,Identity Verification,Microsoft Hello,Authentication Flaws
thumbnail: https://thmb.techidaily.com/e3e57dc288a15eebc6a087ce47534d889b154128f1cec9b763b947b83648c7c9.jpg
---

## Biometric Breakdown: Is Windows Hello Still Reliable?

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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/new-blur-out-not-into-discovering-photo-clarity-web-tools/"><u>[New] Blur Out, Not Into! Discovering Photo Clarity Web Tools</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-navigating-through-fbs-in-stream-ad-landscape-configuration-and-evaluation-techniques/"><u>[New] In 2024, Navigating Through FB's In-Stream Ad Landscape Configuration and Evaluation Techniques</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-no-pay-no-problem-get-your-free-passport-photo-creator-now-online-and-on-desktop/"><u>[New] In 2024, No Pay, No Problem Get Your Free Passport Photo Creator Now Online & On Desktop</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-facetime-made-simple-for-android-users/"><u>[Updated] FaceTime Made Simple for Android Users</u></a></li>
<li><a href="https://win11.techidaily.com/ease-up-on-the-graphics-winwm-usage-optimization-tips/"><u>Ease Up on the Graphics: WinWM Usage Optimization Tips</u></a></li>
<li><a href="https://win11.techidaily.com/ejecting-onedrive-from-windows-integrated-ms-identity/"><u>Ejecting OneDrive From Windows-Integrated MS Identity</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-pcs-auditory-experience-with-atmos-technology/"><u>Elevate Your PC's Auditory Experience with Atmos Technology</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-smooth-operations-fixing-breakdowns-in-windows-registry/"><u>Ensuring Smooth Operations: Fixing Breakdowns in Windows Registry</u></a></li>
<li><a href="https://some-techniques.techidaily.com/grasping-virtual-realitys-revolutionary-gear-for-2024/"><u>Grasping Virtual Reality's Revolutionary Gear for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/guide-on-handling-windows-error-code-30005-create-failure/"><u>Guide on Handling Windows Error Code: 30005 Create Failure</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-resolving-no-device-driver-detected-errors/"><u>Guidelines for Resolving No Device Driver Detected Errors</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-achieve-stunning-visual-impact-top-color-grading-tutorials/"><u>In 2024, Achieve Stunning Visual Impact - Top Color Grading Tutorials</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-leading-downloader-software-facebooks-top-choices-5/"><u>In 2024, Leading Downloader Software Facebook's Top Choices #5</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/top-picks-exploring-the-best-screen-recorder-apps/"><u>Top Picks Exploring the Best Screen Recorder Apps</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-login-gone-blank/"><u>Troubleshooting Windows Login Gone Blank</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-peer-to-peer-power-top-windows-apps/"><u>Unleashing Peer-to-Peer Power: Top Windows Apps</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-apple-iphone-11-with-forgotten-passcode-different-methods-you-can-try-by-drfone-ios/"><u>Unlock Apple iPhone 11 With Forgotten Passcode Different Methods You Can Try</u></a></li>
</ul></div>

