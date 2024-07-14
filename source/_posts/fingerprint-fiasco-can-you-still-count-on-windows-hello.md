---
title: "Fingerprint Fiasco: Can You Still Count on Windows Hello?"
date: 2024-07-13T09:58:23.351Z
updated: 2024-07-14T09:58:23.351Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/overcoming-excessive-use-of-windows-module-installer/"><u>Overcoming Excessive Use of Windows Module Installer</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-next-level-game-monitoring-software-beyond-the-fbx-standard/"><u>In 2024, Next Level Game Monitoring Software Beyond the FBX Standard</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-device-integration-using-googles-nearby/"><u>Seamless Device Integration Using Google's Nearby</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-11-and-11-desktop-context-menu-not-working/"><u>How to Fix the Windows 11 & 11 Desktop Context Menu Not Working</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-comprehensive-guide-record-webcam-in-hd-via-vlc/"><u>[Updated] In 2024, Comprehensive Guide  Record Webcam in HD via VLC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-unterminated-process-failures-in-windows/"><u>How to Resolve Unterminated Process Failures in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-mending-the-internal-error-in-rdp-on-windows-11-and-11-pro/"><u>Guide to Mending the Internal Error in RDP on Windows 11 & 11 Pro</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-drone-experience-yuneec-q500-for-2024/"><u>The Ultimate Drone Experience  Yuneec Q500 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-powertoys-reset-on-new-machine/"><u>Navigating PowerToys: Reset on New Machine</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-prior-to-starting-the-window-operating-system-renewal/"><u>Key Steps Prior to Starting the Window Operating System Renewal</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-vpn-network-disconnection-on-a-remote-work-pc/"><u>Fixing VPN Network Disconnection on a Remote Work PC</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-comedic-choreography-producing-funny-mock-films/"><u>[Updated] 2024 Approved  Comedic Choreography  Producing Funny Mock Films</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-new-folders-into-explorers-interface/"><u>Incorporating New Folders Into Explorer's Interface</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-failed-driver-loading-issues-in-the-latest-os/"><u>Overcoming Failed Driver Loading Issues in the Latest OS</u></a></li>
<li><a href="https://win11.techidaily.com/guide-accessing-and-opening-verifier-manager-w11/"><u>Guide: Accessing and Opening Verifier Manager W11</u></a></li>
<li><a href="https://win11.techidaily.com/recovering-hidden-notifications-on-desktops/"><u>Recovering Hidden Notifications on Desktops</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-the-ultimate-guide-to-free-online-glitch-effect-makers-2023-edition/"><u>New In 2024, The Ultimate Guide to Free Online Glitch Effect Makers (2023 Edition)</u></a></li>
<li><a href="https://win11.techidaily.com/from-iphone-to-desktop-syncing-ios-calendar-with-windows-1011/"><u>From iPhone to Desktop: Syncing iOS Calendar with Windows 10/11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-speedyshot-echoloop-media/"><u>2024 Approved  SpeedyShot EchoLoop Media</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-fix-apple-iphone-14-unavailable-issue-with-ease-drfone-by-drfone-ios/"><u>How To Fix Apple iPhone 14 Unavailable Issue With Ease | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlock-your-realme-gt-neo-5-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Realme GT Neo 5 Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-realme-c55-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Realme C55 without App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/opening-editing-and-personalizing-your-win11-fax-cover-page/"><u>Opening, Editing & Personalizing Your Win11 Fax Cover Page</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-jest-jar-imgur-meme-tool/"><u>[Updated] Jest Jar  Imgur Meme Tool</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-cutting-edge-video-recording-techniques-on-modern-win-11-devices-for-2024/"><u>[Updated] Cutting-Edge Video Recording Techniques on Modern Win 11 Devices for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-the-spirit-of-victory-a-steam-achievements-reset/"><u>Reviving the Spirit of Victory: A Steam Achievements Reset</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-beyond-imagination-the-real-world-significance-of-snapchat-emojis/"><u>In 2024, Beyond Imagination  The Real-World Significance of Snapchat Emojis</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unresponsive-windows-11-cortana-commands/"><u>Overcoming Unresponsive Windows 11 Cortana Commands</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-synapse-glitches-on-w11-and-w10/"><u>How to Mend Synapse Glitches on W11 and W10</u></a></li>
<li><a href="https://win11.techidaily.com/setting-specific-windows-lockdown-period/"><u>Setting Specific Windows Lockdown Period</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-overcoming-connectivity-issues-in-remote-recording/"><u>[Updated] Overcoming Connectivity Issues in Remote Recording</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-giggles-galore-celebrating-the-funniest-web-content-creators/"><u>[Updated] In 2024, Giggles Galore  Celebrating the Funniest Web Content Creators</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-google-pixel-8-pro-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Google Pixel 8 Pro to Apple TV | Dr.fone</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-the-ultimate-checklist-10-high-quality-websites-streaming-free-hd-wallpaper-videos/"><u>Updated In 2024, The Ultimate Checklist 10 High-Quality Websites Streaming Free HD Wallpaper Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-preservation-in-audio-how-ffmpeg-handles-originality/"><u>In 2024, Preservation in Audio  How FFmpeg Handles Originality</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-video-splitting-wins-ranking-recorder-titans-for-2024/"><u>[Updated] Video Splitting Wins  Ranking Recorder Titans for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/separate-onedrive-and-microsoft-accounts-on-desktop-windows/"><u>Separate OneDrive & Microsoft Accounts on Desktop Windows</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-zte-nubia-flip-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on ZTE Nubia Flip 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-avoiding-motion-illusions-tips-for-vr-users/"><u>[Updated] Avoiding Motion Illusions  Tips for VR Users</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-best-8-ar-apps-for-android-and-ios-help-you-see-the-world-of-ar/"><u>New 2024 Approved Best 8 AR Apps for Android and iOS | Help You See the World of AR</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-gain-money-on-youtube-understanding-required-number-of-views-for-2024/"><u>[New] Gain Money on YouTube  Understanding Required Number of Views for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-invalid-profile-on-windows-11-systems/"><u>How to Tackle 'Invalid Profile' On Windows 11 Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-realme-12plus-5g-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Realme 12+ 5G? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-missing-file-updates-error-on-windows-error-code-0x80070003/"><u>Navigating Through Missing File Updates Error on Windows (Error Code: 0X80070003)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-and-set-up-windows-sandbox-in-windows-11/"><u>How to Enable and Set Up Windows Sandbox in Windows 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-the-ultimate-list-10-best-intro-makers-on-the-web/"><u>In 2024, The Ultimate List 10 Best Intro Makers on the Web</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-system-safe-spotting-hidden-threats-in-windows/"><u>Keep Your System Safe: Spotting Hidden Threats in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/pinpointing-internal-sound-malfunctions-in-winaudacity-interface/"><u>Pinpointing Internal Sound Malfunctions in WinAudacity Interface</u></a></li>
<li><a href="https://win11.techidaily.com/mending-microsoft-outlook-glitches-on-windows-devices/"><u>Mending Microsoft Outlook Glitches on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-disruptive-discord-js-error-in-windows-environments/"><u>Overcoming Disruptive Discord JS Error in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-undetermined-status-messages-on-windows/"><u>Remedying 'Undetermined' Status Messages on Windows</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/initially-released-voice-controlled-ar-experience/"><u>Initially Released Voice-Controlled AR Experience</u></a></li>
</ul></div>
