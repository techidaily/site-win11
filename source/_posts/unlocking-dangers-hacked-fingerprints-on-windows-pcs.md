---
title: "Unlocking Dangers: Hacked Fingerprints on Windows PCs"
date: 2024-07-13T10:30:32.904Z
updated: 2024-07-14T10:30:32.904Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Dangers: Hacked Fingerprints on Windows PCs"
excerpt: "This Article Describes Unlocking Dangers: Hacked Fingerprints on Windows PCs"
keywords: Windows Cyber Threat,Fingerprint Hacking,Unsafe PC Access,Hacked Biometrics,Fingerprint Security,Digital Privacy Risk,PC Identity Theft
thumbnail: https://thmb.techidaily.com/7f46fac9a85eca734c1f07440ac82d4e70260de3231ef2557f357bda5f1ea303.jpg
---

## Unlocking Dangers: Hacked Fingerprints on Windows PCs

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
<li><a href="https://win11.techidaily.com/a-deeper-dive-into-your-computer-writes-mouse-secrets-of-windows-11/"><u>A Deeper Dive Into Your Computer' Writes: Mouse Secrets of Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-create-an-apple-developer-account-from-iphone-14-pro-by-drfone-ios/"><u>How To Create an Apple Developer Account From iPhone 14 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/a-concise-guide-to-windows-11-user-grievances-and-gripes/"><u>A Concise Guide to Windows 11 User Grievances and Gripes</u></a></li>
<li><a href="https://win11.techidaily.com/4-fixes-to-try-if-you-cant-enable-the-windows-firewall/"><u>4 Fixes to Try if You Can’t Enable the Windows Firewall</u></a></li>
<li><a href="https://unlock-android.techidaily.com/a-complete-guide-to-oem-unlocking-on-zte-axon-40-lite-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on ZTE Axon 40 Lite</u></a></li>
<li><a href="https://techidaily.com/hard-reset-motorola-moto-g73-5g-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Motorola Moto G73 5G in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreran-guide-resolving-source-disk-errors-in-microsoft-oses/"><u>A Compreran Guide: Resolving Source Disk Errors in Microsoft OSes</u></a></li>
<li><a href="https://win11.techidaily.com/1719367006018-need-windows-help-find-support-tips-and-solutions/"><u>Need Windows Help? Find Support Tips & Solutions!</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-changing-esd-into-an-iso-for-windows-pcs/"><u>A Beginner's Guide to Changing ESD Into an ISO for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-keyboard-input-lag-on-windows-10-and-11/"><u>7 Ways to Fix Keyboard Input Lag on Windows 10 and 11</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-the-easy-path-to-crafting-your-audio-book-a-detailed-tutorial/"><u>In 2024, The Easy-Path to Crafting Your Audio Book A Detailed Tutorial</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-reviewing-tech-trends-the-vlle-method/"><u>In 2024, Reviewing Tech Trends  The VLLE Method</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-for-optimizing-task-management-in-administrative-mode-on-windows-11/"><u>A Step-by-Step Guide for Optimizing Task Management in Administrative Mode on Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-a-comprehensive-dive-into-creating-inspiring-slow-mo-videos-on-ig/"><u>[New] In 2024, A Comprehensive Dive Into Creating Inspiring Slow Mo Videos on IG</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-screencapture-101-with-springs-latest-release/"><u>[Updated] 2024 Approved  ScreenCapture 101 with Spring's Latest Release</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-fix-for-0x800704b3-error-in-windows-11/"><u>A Quick Fix for 0X800704B3 Error in Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/master-australian-lingo-100plus-slang-terms-and-sayings-to-speak-like-an-aussieback-buttonfilter-button/"><u>Master Australian Lingo: 100+ Slang Terms & Sayings To Speak Like An AussieBack ButtonFilter Button</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-shielding-game-data/"><u>A Step-by-Step Guide to Shielding Game Data</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-crafting-engaging-channels-using-tubebuddys-framework/"><u>[New] Crafting Engaging Channels Using TubeBuddy's Framework</u></a></li>
<li><a href="https://win11.techidaily.com/1719371064101-windows-11-ready-embrace-google-chrome-now/"><u>Windows 11 Ready? Embrace Google Chrome Now</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensive-overview-using-nearby-share-effectively/"><u>A Comprehensive Overview: Using Nearby Share Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/1719370462941-understanding-power-settings-save-charges/"><u>Understanding Power Settings - Save Charges</u></a></li>
<li><a href="https://win11.techidaily.com/1719376423944-addressing-windows-faults-with-proven-remedies/"><u>Addressing Windows Faults with Proven Remedies</u></a></li>
<li><a href="https://win11.techidaily.com/8-simple-steps-for-unlocking-your-windows-hello-device/"><u>8 Simple Steps for Unlocking Your Windows Hello Device</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-unleash-your-creativity-adobe-premiere-pro-for-mac-professionals/"><u>In 2024, Unleash Your Creativity Adobe Premiere Pro for Mac Professionals</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-core-elements-in-asmr-visual-media/"><u>In 2024, The Core Elements in ASMR Visual Media</u></a></li>
<li><a href="https://win11.techidaily.com/5-essential-time-saving-pc-apps-for-dynamic-desktop-screensavers/"><u>5 Essential Time-Saving PC Apps for Dynamic Desktop Screensavers</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-unmatched-windows-10-recorders/"><u>[Updated] 2024 Approved  Unmatched Windows 10 Recorders</u></a></li>
<li><a href="https://win11.techidaily.com/6-polarizing-windows-features-that-are-gone-for-good/"><u>6 Polarizing Windows Features That Are Gone for Good</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-fix-the-local-device-name-is-already-in-use-error-on-windows/"><u>5 Ways to Fix the Local Device Name Is Already in Use Error on Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-prime-windows-11-recording-software-ranked-15/"><u>[New] In 2024, Prime Windows 11 Recording Software  Ranked #15</u></a></li>
<li><a href="https://games-able.techidaily.com/a-comparative-study-of-cannabinoid-delivery-systems-and-their-impact-on-treatment-outcomes/"><u>A Comparative Study of Cannabinoid Delivery Systems and Their Impact on Treatment Outcomes</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-cutting-down-the-queue-tips-for-rapid-tiktok-browsing/"><u>[New] Cutting Down the Queue  Tips for Rapid TikTok Browsing</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-sharpen-aesthetic-focus-learning-border-techniques-for-insta-videos/"><u>[New] Sharpen Aesthetic Focus  Learning Border Techniques for Insta-Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-playful-pedal-powered-pastimes/"><u>[Updated] 2024 Approved  Playful Pedal-Powered Pastimes</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-entering-your-folder-of-apps-in-windows-11/"><u>A Step-by-Step Guide to Entering Your Folder of Apps in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-windows-tasks-with-top-5-car-drivers/"><u>Accelerate Windows Tasks with Top 5 Car Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/5-superior-bittorrent-tools-for-windows-users/"><u>5 Superior BitTorrent Tools for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-win-utorrent-downloads-tips-and-tricks/"><u>Accelerate Win uTorrent Downloads: Tips and Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-fixing-windows-lsass-components-issue/"><u>A Guide to Fixing Windows Lsass Components Issue</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-searching-for-the-best-video-editor-to-make-your-video-more-attractive-this-article-introduce-you-everything-about-choosing-a-video-editing-software/"><u>In 2024, Searching for the Best Video Editor to Make Your Video More Attractive? This Article Introduce You Everything About Choosing a Video Editing Software</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-triumph-in-football-fantasyland-at-no-cost/"><u>A Guide to Triumph in Football Fantasyland at No Cost</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-in-2024-the-essentials-of-navigating-googles-podcast-experience/"><u>Updated In 2024, The Essentials of Navigating Googles Podcast Experience</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-remedy-onedrives-blob-tag-inaccuracy-error/"><u>A Guide to Remedy OneDrive's Blob Tag Inaccuracy Error</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-expert-tips-for-effective-io-image-capture-use/"><u>[Updated] In 2024, Expert Tips for Effective IO Image Capture Use</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-seamless-podcast-journey-from-creation-to-google-submission/"><u>2024 Approved  Seamless Podcast Journey  From Creation to Google Submission</u></a></li>
<li><a href="https://win11.techidaily.com/1719359386759-overcoming-dim-windows-11-screens-tips-inside/"><u>Overcoming Dim Windows 11 Screens - Tips Inside</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-top-selections-top-6-fb-lite-extractors-for-2024/"><u>[New] Top Selections  #Top 6 FB Lite Extractors for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-3d-paint-process-with-these-tips/"><u>Accelerate Your 3D Paint Process with These Tips</u></a></li>
<li><a href="https://win11.techidaily.com/a-compreayers-guide-to-top-windows-compatible-file-sharing-software/"><u>A Compreayer's Guide to Top Windows-Compatible File Sharing Software</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-mastering-google-voice-calls-the-ultimate-guide/"><u>[Updated] 2024 Approved  Mastering Google Voice Calls  The Ultimate Guide</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-change-themes-on-windows-11/"><u>9 Ways to Change Themes On Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/9-essential-fixes-for-troublesome-email-notifications-in-windows/"><u>9 Essential Fixes for Troublesome Email Notifications in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-telnet-in-windows-11-and-11/"><u>3 Ways to Enable Telnet in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719329356847-chrome-freezing-woes-on-win11-try-these-swift-solutions/"><u>Chrome Freezing Woes on Win11? Try These Swift Solutions</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-depth-analysis-simplified-dynamic-range-photography/"><u>[New] In-Depth Analysis  Simplified Dynamic Range Photography</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-on-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Fake Snapchat Location on Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-incentivizing-engagement-for-a-robust-subscription-base/"><u>2024 Approved  Incentivizing Engagement for a Robust Subscription Base</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-groundbreaking-photo-editor-photonshift-tech/"><u>[Updated] 2024 Approved  Groundbreaking Photo Editor  PhotonShift Tech</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-make-a-killer-gaming-intro-best-software-for-pc-and-mac/"><u>2024 Approved Make a Killer Gaming Intro Best Software for PC and Mac</u></a></li>
<li><a href="https://win11.techidaily.com/a-visionary-approach-to-taskbar-design-essential-improvements-for-microsofts-new-release/"><u>A Visionary Approach to Taskbar Design: Essential Improvements for Microsoft's New Release</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-can-we-unlock-our-vivo-y27s-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Vivo Y27s Phone Screen?</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-find-the-mac-address-on-windows-11/"><u>4 Ways to Find the MAC Address on Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/efficient-methods-to-delete-past-games-data-on-ps5-console/"><u>Efficient Methods to Delete Past Games' Data on PS5 Console</u></a></li>
<li><a href="https://win11.techidaily.com/1719362972502-enhance-printer-functionality-in-windows-11-today/"><u>Enhance Printer Functionality in Windows 11 Today!</u></a></li>
</ul></div>
