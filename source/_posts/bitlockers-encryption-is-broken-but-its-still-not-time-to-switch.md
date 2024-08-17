---
title: BitLocker's Encryption Is Broken, But It's Still Not Time to Switch
date: 2024-08-15T23:33:00.783Z
updated: 2024-08-16T23:33:00.783Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes BitLocker's Encryption Is Broken, But It's Still Not Time to Switch
excerpt: This Article Describes BitLocker's Encryption Is Broken, But It's Still Not Time to Switch
keywords: BitLock Encryption Flaws,BitLocker Security Issues,Data Protection Concerns,Encrypted Storage Risks,Secure Lockdown Failures,Passkey Vulnerability,Safe Data Not Guaranteed
thumbnail: https://thmb.techidaily.com/6300778dc08ca1fabf45e37fea6b55cfeffea9a7ede93b82142ae1fd2f19eff3.jpg
---

## BitLocker's Encryption Is Broken, But It's Still Not Time to Switch

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Is It Time to Ditch BitLocker?

 Interestingly, [Microsoft was already aware](https://learn.microsoft.com/en-us/windows/security/operating-system-security/data-protection/bitlocker/countermeasures#attacker-countermeasures) of the potential for this attack. However, this is the first time a practical attack has surfaced at large, illustrating just how fast BitLocker encryption keys can be stolen.

 It raises the vital question of whether you should consider switching to a BitLocker alternative, like the [free and open-source VeraCrypt](https://www.makeuseof.com/encrypt-windows-system-drive-veracrypt/). The good news is that you don't need to jump ship for a few reasons.

 First, the exploit only works with external TPMs that request data from the module using the LPC bus. Most modern hardware integrates the TPM. While a motherboard-based TPM could theoretically be exploited, it would require more time, effort, and an extensive period with the target device. Extracting BitLocker Volume Master Key data from a TPM becomes even more difficult if the module is integrated into the CPU.

 AMD CPUs have integrated TPM 2.0 since 2016 (with the launch of AM4, known as fTPM), while Intel CPUs integrated TPM 2.0 with the launch of its 8th Generation Coffee Lake CPUs in 2017 (known as PTT). Suffice to say, if you're using a machine with an AMD or Intel CPU manufacturer after those dates, you're most likely safe.

 It's also worth noting that despite this exploit, BitLocker remains secure, and the actual encryption underpinning it, AES-128 or AES-256, is still secure.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-steps-for-capturing-hd-content-on-fb/"><u>[New] 2024 Approved  Steps for Capturing HD Content on FB</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-the-ultimate-vision-quest-samsung-galaxy-s8s-4k-prowess/"><u>[New] 2024 Approved  The Ultimate Vision Quest  Samsung Galaxy S8's 4K Prowess</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-from-concept-to-platform-crafting-engaging-fb-content/"><u>[New] From Concept to Platform  Crafting Engaging FB Content</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-cutting-edge-techniques-for-video-production-in-windows-photos/"><u>[New] In 2024, Cutting-Edge Techniques for Video Production in Windows Photos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-tips-for-crafting-effective-igtv-titles-and-summaries/"><u>[New] Tips for Crafting Effective IGTV Titles & Summaries</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-user-friendly-mac-gadget-visuals-and-voices-recorded/"><u>[New] User-Friendly Mac Gadget  Visuals & Voices Recorded</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-gaining-clarity-on-your-youtube-audiences-behavior/"><u>[Updated] 2024 Approved  Gaining Clarity on Your YouTube Audience's Behavior</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2024-approved-unveiling-the-hidden-meanings-behind-facebooks-messenger-icon/"><u>[Updated] 2024 Approved  Unveiling the Hidden Meanings Behind Facebook's Messenger Icon</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-create-video-ads-for-free-in-youtube-video-builder-for-2024/"><u>[Updated] How to Create Video Ads for Free in YouTube Video Builder for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-internal-recording-feature-screen-capture-for-huaweis-mate-and-p-series-phones/"><u>[Updated] In 2024, Internal Recording Feature  Screen Capture for Huawei's Mate & P Series Phones</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-webinar-recording-tactics-zero-price-strategy-for-2024/"><u>[Updated] Webinar Recording Tactics  Zero Price Strategy for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-the-essentials-of-real-time-tweets-on-twitter/"><u>2024 Approved  The Essentials of Real-Time Tweets on Twitter</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-heart-of-video-magic-10-key-edits-in-filmora/"><u>2024 Approved  The Heart of Video Magic  10 Key Edits in Filmora</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-application-failures-due-to-net-not-installed/"><u>Addressing Application Failures Due to .NET Not Installed</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-email-notifications-glitches-on-windows-devices/"><u>Addressing Email Notifications Glitches on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-memory-caching-in-windows-os/"><u>Breaking Down Memory Caching in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-tech-epochs-windows-7-key-to-boot-windows-11/"><u>Bridging the Tech Epochs: Windows 7 Key to Boot Windows 11</u></a></li>
<li><a href="https://extra-information.techidaily.com/catalyze-viewers-interest-tutorial-for-traffic-triumphs/"><u>Catalyze Viewers' Interest  Tutorial for Traffic Triumphs</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-honor-x50i-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Honor X50i | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/creative-steps-to-obliviate-win-11s-taskbar-button/"><u>Creative Steps to Obliviate Win 11'S Taskbar Button</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-resource-drains-in-windows-managing-multimedia-consumption/"><u>Cutting Down Resource Drains in Windows: Managing Multimedia Consumption</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-6-oddities-in-windows-11-design/"><u>Decoding the 6 Oddities in Windows 11 Design</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-excessive-windows-contrast-effects/"><u>Disabling Excessive Windows Contrast Effects</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/empower-your-site-insights-using-cookiebot-the-ultimate-web-tracker-solution/"><u>Empower Your Site Insights Using Cookiebot – The Ultimate Web Tracker Solution</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-11-drag-and-drop-failures-now/"><u>Fix Windows 11 Drag-and-Drop Failures Now</u></a></li>
<li><a href="https://win11.techidaily.com/fresh-beginnings-executing-a-clean-windows-11-reinstall/"><u>Fresh Beginnings: Executing a Clean Windows 11 Reinstall</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-resolve-microphone-problems-on-pc-and-xbox/"><u>Guidelines to Resolve Microphone Problems on PC & Xbox</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-photos-app-background-blur-feature-on-windows-11/"><u>How to Use the Photos App Background Blur Feature on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-high-space-consumers-on-your-windows-machine/"><u>Identifying High-Space Consumers on Your Windows Machine</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-actions-for-reviving-freeze-ups-on-resource-monitor-win11/"><u>Immediate Actions for Reviving Freeze-Ups on Resource Monitor, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/immersive-education-experience-windows-11-tutorials/"><u>Immersive Education Experience: Windows 11 Tutorials</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-how-to-guide-on-bypassing-the-apple-iphone-14-icloud-lock-by-drfone-ios/"><u>In 2024, A How-To Guide on Bypassing the Apple iPhone 14 iCloud Lock</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Catch 100 IV Pokémon Using a Map On Honor Magic 6 Lite | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/mastering-authenticity-on-instagrams-platform/"><u>Mastering Authenticity on Instagram's Platform</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-office-setup-on-windows-10-and-11-systems/"><u>Mastering Office Setup on WIndows 10 & 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/methods-for-bypassing-non-active-window-firewall/"><u>Methods for Bypassing Non-Active Window Firewall</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-9-methods-for-accessing-windows-11s-audio-control-panel/"><u>Navigate 9 Methods for Accessing Windows 11'S Audio Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-maze-of-mass-unzipping-on-your-pc/"><u>Navigating the Maze of Mass Unzipping on Your PC</u></a></li>
<li><a href="https://extra-resources.techidaily.com/nextgen-flawless-frame-processor-windowsmac/"><u>NextGen Flawless Frame Processor (Windows/Mac)</u></a></li>
<li><a href="https://some-skills.techidaily.com/perfect-pan-and-tilt-for-clearer-captures-for-2024/"><u>Perfect Pan & Tilt for Clearer Captures for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-your-windows-environment-adding-to-the-desktop-menu/"><u>Personalizing Your Windows Environment: Adding to the Desktop Menu</u></a></li>
<li><a href="https://extra-hints.techidaily.com/quirky-expressions-in-text-master-meme-creation/"><u>Quirky Expressions in Text  Master Meme Creation</u></a></li>
<li><a href="https://win11.techidaily.com/realign-google-chrome-clock-with-windows-time/"><u>Realign Google Chrome Clock with Windows Time</u></a></li>
<li><a href="https://win11.techidaily.com/reimagine-your-pc-with-the-top-10-must-try-powertoy-applications/"><u>Reimagine Your PC with the Top 10 Must-Try PowerToy Applications</u></a></li>
<li><a href="https://win11.techidaily.com/removing-no-associated-error-on-windows-devices/"><u>Removing 'No Associated' Error on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-discords-critical-js-error-on-windows-1011-systems/"><u>Resolving Discord's Critical JS Error on Windows 10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/securely-storing-windows-uac-prompt-pictures/"><u>Securely Storing Windows UAC Prompt Pictures</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/sky-dominance-top-5-fpv-glasses-for-pilots-for-2024/"><u>Sky Dominance  Top 5 FPV Glasses for Pilots for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-windows-1011-camera-app-error-a00f429f/"><u>Steps to Eliminate Windows 10/11 Camera App Error A00F429F</u></a></li>
<li><a href="https://win11.techidaily.com/stop-the-stutter-start-the-flow-top-9-tactics-to-enhance-video-on-pcs/"><u>Stop the Stutter, Start the Flow: Top 9 Tactics to Enhance Video on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/swift-resolution-to-hypervisor-errors-for-winxose-users/"><u>Swift Resolution to Hypervisor Errors for WINXOSE Users</u></a></li>
<li><a href="https://win11.techidaily.com/time-travel-in-gameplay-implementing-retroarchs-shader-effects/"><u>Time Travel in Gameplay: Implementing RetroArch's Shader Effects</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-your-way-through-windows-application-hiccups-7-tips/"><u>Troubleshoot Your Way Through Windows Application Hiccups (7 Tips)</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-grammarlys-non-operational-status/"><u>Troubleshooting Grammarly's Non-Operational Status</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-overwatch-2-renderer-issues-on-windows/"><u>Troubleshooting Overwatch 2 Renderer Issues on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-persistent-windows-boot-issue-to-bios-mode/"><u>Troubleshooting Persistent Windows Boot Issue to BIOS Mode</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-from-lava-blaze-2-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Lava Blaze 2 FRP Bypass</u></a></li>
<li><a href="https://fox-that.techidaily.com/unlock-effective-voice-typing-on-your-iphone-with-these-5-essential-troubleshooting-steps/"><u>Unlock Effective Voice Typing on Your iPhone with These 5 Essential Troubleshooting Steps</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secrets-to-windows-11-success/"><u>Unlocking the Secrets to Windows 11 Success</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveil-top-gadgets-and-tools-a-deep-dive-into-tech-by-toms-hardware/"><u>Unveil Top Gadgets & Tools - A Deep Dive Into Tech by Tom's Hardware</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-power-of-wpm-in-windows-11-environments/"><u>Unveiling the Power of WPM in Windows 11 Environments</u></a></li>
</ul></div>
