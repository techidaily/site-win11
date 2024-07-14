---
title: "Biometric Breakdown: Is Windows Hello Still Reliable?"
date: 2024-07-13T11:28:38.523Z
updated: 2024-07-14T11:28:38.523Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/avoiding-clutter-smart-note-management-for-windows/"><u>Avoiding Clutter: Smart Note Management for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-task-power-top-5-apps-to-enhance-window-11-workflow/"><u>Boosting Task Power: Top 5 Apps to Enhance Window 11 Workflow</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-cost-effective-4k-photography-gear/"><u>2024 Approved  Cost-Effective 4K Photography Gear</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-through-strategic-task-management-in-windows-11/"><u>Boosting Productivity Through Strategic Task Management in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-powershell-from-windows-command-prompt/"><u>Addressing Missing PowerShell From Windows Command Prompt</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tailoring-audio-alerts-setting-custom-ringtones-and-sounds-on-android-devices-for-2024/"><u>Tailoring Audio Alerts  Setting Custom Ringtones & Sounds on Android Devices for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/the-ultimate-software-for-mp4-recording/"><u>The Ultimate Software for MP4 Recording</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-itel-p55plus-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Itel P55+ If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/a-comprehensive-guide-to-apple-iphone-8-plus-blacklist-removal-tips-and-tools-drfone-by-drfone-ios/"><u>A Comprehensive Guide to Apple iPhone 8 Plus Blacklist Removal Tips and Tools | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-graphics-techniques-in-edge-app-guard/"><u>Advanced Graphics Techniques in Edge App Guard</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/the-ultimate-handbook-for-watching-facebook-livestreams-for-2024/"><u>The Ultimate Handbook for Watching Facebook Livestreams for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-pioneering-mobile-broadcasting-mastering-obs-studio-and-android/"><u>[New] In 2024, Pioneering Mobile Broadcasting  Mastering OBS Studio and Android</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-mobile-sound-for-windows-pc-use-case/"><u>Boosting Mobile Sound for Windows PC Use Case</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-poco-c55-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Poco C55 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unlocking-income-from-youtube-as-a-newbie/"><u>[New] Unlocking Income From YouTube as a Newbie</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-win1011-graphics-power-the-ultimate-guide-to-vram/"><u>Boosting Win10/11 Graphics Power: The Ultimate Guide to VRAM</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-secrets-of-success-converting-ipv-video-files-with-flair/"><u>[New] 2024 Approved  Secrets of Success  Converting IPV Video Files with Flair</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-system-stability-fixing-high-memory-usage-of-services/"><u>Boosting System Stability: Fixing High Memory Usage of Services</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-oneplus-ace-2v-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On OnePlus Ace 2V | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-grayed-out-delete-pin-option-in-windows-11/"><u>Breaking Grayed-Out Delete PIN Option in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/banish-the-bluescreen-error-in-win11-with-these-simple-fixes/"><u>Banish the Bluescreen Error in Win11 with These Simple Fixes</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/deciphering-complete-fbm-call-transcripts-guide-for-2024/"><u>Deciphering Complete FBM Call Transcripts Guide for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/from-idea-to-impact-top-8-online-courses-for-new-creators/"><u>From Idea to Impact  Top 8 Online Courses for New Creators</u></a></li>
<li><a href="https://win11.techidaily.com/breached-bytebandit-ponder-the-path-for-a-possible-pivot/"><u>Breached ByteBandit: Ponder the Path for a Possible Pivot</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-html-overload-fixing-windows-11-mail-format-glitches/"><u>Avoiding HTML Overload: Fixing Windows 11 Mail Format Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-common-windows-11-login-blunders/"><u>Avoiding Common Windows 11 Login Blunders</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-wi-fi-setup-barriers-filling-action-voids-on-pc/"><u>Breaking Down Wi-Fi Setup Barriers: Filling Action Voids on PC</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-a-comprehensive-list-of-mac-methods-to-record-minecraft-play/"><u>2024 Approved  A Comprehensive List of Mac Methods to Record Minecraft Play</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/top-10-decibel-upgraders-for-every-os-for-2024/"><u>Top 10 Decibel Upgraders for Every OS for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/quintessential-quests-and-thrills-top-10-games-for-2024/"><u>Quintessential Quests & Thrills – Top 10 Games for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-manual-inputs-embracing-ai-in-windows-operations/"><u>Beyond Manual Inputs: Embracing AI in Windows Operations</u></a></li>
<li><a href="https://win11.techidaily.com/boost-notability-of-your-scribbles-with-strategic-sticky-note-placement-in-win-os/"><u>Boost Notability of Your Scribbles with Strategic Sticky Note Placement in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/bargain-bonanza-black-friday-612-for-lifelong-win10-life/"><u>Bargain Bonanza: Black Friday - $6.12 for Lifelong Win10 Life</u></a></li>
<li><a href="https://win11.techidaily.com/bitlocker-less-protection-4-effective-methods-for-win-users/"><u>BitLocker-Less Protection: 4 Effective Methods for Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-cycles-of-compliance-my-defiance-against-app-guard-norms/"><u>Breaking Cycles of Compliance: My Defiance Against App Guard Norms</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-boost-your-videos-popularity-on-youtube/"><u>[New] Boost Your Video's Popularity on YouTube</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/a-peek-at-the-cutting-edge-features-for-windows-users/"><u>A Peek at the Cutting-Edge Features for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-disruption-bypass-game-glitches-immediately/"><u>Avoid Disruption - Bypass Game Glitches Immediately</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-the-barriers-to-customizing-windows-11-apps/"><u>Breaking Down the Barriers to Customizing Windows 11 Apps</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-the-looks-like-youre-stranded-error-from-xbox/"><u>Banishing the ‘Looks Like You’re Stranded’ Error From Xbox</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-enhancing-visuals-the-guide-to-blending-photos-with-music/"><u>New 2024 Approved Enhancing Visuals The Guide to Blending Photos with Music</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-utilities-convert-any-media-file/"><u>Best Windows Utilities Convert Any Media File</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-best-solutions-for-nokia-network-unlock-by-drfone-android/"><u>In 2024, Best Solutions for Nokia Network Unlock</u></a></li>
<li><a href="https://win11.techidaily.com/bare-bones-pc-boasts-bulky-but-lackluster-loops/"><u>Bare-Bones PC Boasts Bulky, but Lackluster Loops</u></a></li>
<li><a href="https://win11.techidaily.com/best-way-to-wrap-windows-store-games-for-yule/"><u>Best Way to Wrap Windows Store Games for Yule</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-itel-a60s-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Itel A60s | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-black-backdrops-on-windows/"><u>Breaking Free From Black Backdrops on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-frozen-mouse-menu-stasis-on-pc/"><u>Break Free From Frozen Mouse Menu Stasis on PC</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-xiaomi-redmi-note-13-5g-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Xiaomi Redmi Note 13 5G ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-the-ultimate-guide-to-top-audio-extraction-tools-in-videos-for-2024/"><u>Updated The Ultimate Guide to Top Audio Extraction Tools in Videos for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-visual-flow-control-simple-fade-strategies/"><u>2024 Approved  Visual Flow Control  Simple Fade Strategies</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-structured-approach-to-managing-youtube-videos-a-complete-watch-later-system/"><u>In 2024, Structured Approach to Managing YouTube Videos  A Complete Watch Later System</u></a></li>
<li><a href="https://win11.techidaily.com/boost-display-output-clarity-with-high-dpi-adjustments/"><u>Boost Display Output Clarity with High-DPI Adjustments</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>