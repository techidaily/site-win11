---
title: BitLocker's Encryption Is Broken, But It's Still Not Time to Switch
date: 2024-07-13T11:01:52.867Z
updated: 2024-07-14T11:01:52.867Z
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

### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

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
<li><a href="https://some-guidance.techidaily.com/in-2024-subtle-shift-top-8-choices-for-transforming-sub-into-easy-to-use-srt/"><u>In 2024, Subtle Shift  Top 8 Choices for Transforming SUB Into Easy-to-Use SRT</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-top-8-linux-compatible-cutting-apps/"><u>2024 Approved  Top 8 Linux-Compatible Cutting Apps</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-directx-protocols-for-your-gaming-system/"><u>Effortless DirectX Protocols for Your Gaming System</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-photo-fusion-mastery-windows-users-guide/"><u>In 2024, Photo Fusion Mastery  Windows Users Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-interpreting-the-significance-of-a-blue-image-on-fb-chat/"><u>2024 Approved  Interpreting the Significance of a Blue Image on FB Chat</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-the-conflict-between-apps-and-computers-default-audio/"><u>Remedying the Conflict Between Apps and Computer's Default Audio</u></a></li>
<li><a href="https://win11.techidaily.com/win-over-webp-saving-chrome-image-format-change-guide/"><u>Win Over WebP Saving: Chrome Image Format Change Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlock-epic-video-with-gopro-time-lapse-strategies/"><u>[New] Unlock Epic Video with GoPro Time Lapse Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-common-obstacles-when-installing-java/"><u>Addressing Common Obstacles When Installing Java</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-experience-clearing-and-rebuilding-icons/"><u>Streamlining Your Experience: Clearing and Rebuilding Icons</u></a></li>
<li><a href="https://win11.techidaily.com/protocols-to-enter-windows-administrative-hub/"><u>Protocols to Enter Windows' Administrative Hub</u></a></li>
<li><a href="https://screen-capture.techidaily.com/integrated-technique-for-cross-platform-movie-logging-for-2024/"><u>Integrated Technique for Cross-Platform Movie Logging for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-pcs-safety-with-these-7-password-generators/"><u>Boost Your PC's Safety with These 7 Password Generators</u></a></li>
<li><a href="https://win11.techidaily.com/win-11-guide-reactivate-disabled-slack-notifications/"><u>Win 11 Guide: Reactivate Disabled Slack Notifications</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/bypassing-tiktoks-watermarking-for-iphones-how-to-guide-for-2024/"><u>Bypassing TikTok's Watermarking for iPhones – How-To Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/batch-terminate-programs-in-windows-effortlessly/"><u>Batch Terminate Programs in Windows Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-fixes-conquering-the-fatal-javascript-glitch-in-discord-win-11/"><u>Step-by-Step Fixes: Conquering the Fatal Javascript Glitch in Discord Win 11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-the-ring-of-creatives-evaluating-own-and-adversary-arts-for-2024/"><u>In the Ring of Creatives  Evaluating Own and Adversary Arts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-solve-package-problems-in-windows-oses/"><u>Strategies to Solve Package Problems in Windows OSes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-science-of-naming-your-podcast-for-success/"><u>The Science of Naming Your Podcast for Success</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-to-rectify-hiberflattening-windows/"><u>Easy Steps to Rectify HiberFlattening Windows</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-missing-thermal-policy-in-windows-environment/"><u>Restoring Missing Thermal Policy in Windows Environment</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-comparative-analysis-the-leading-edge-with-active/"><u>In 2024, Comparative Analysis  The Leading Edge with Active</u></a></li>
<li><a href="https://win11.techidaily.com/swift-methods-how-to-determine-hard-drivessd-status-in-windows-system/"><u>Swift Methods: How to Determine Hard Drive/SSD Status in Windows System</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-securing-your-games-with-diverse-screen-capture-options/"><u>[New] 2024 Approved  Securing Your Games with Diverse Screen Capture Options</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-driver-not-running-error-in-windows-11/"><u>Solutions for Driver Not Running Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-prolong-shutdown-in-windows-10-amidst-active-processes/"><u>Techniques to Prolong Shutdown in Windows 10 Amidst Active Processes</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-transform-your-images-with-freepaid-lut-bundles-for-canon/"><u>In 2024, Transform Your Images with Free/Paid LUT Bundles for Canon</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-5ghz-wireless-hurdles/"><u>Overcoming Windows 11 5GHz Wireless Hurdles</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-the-art-of-easing-audio-levels-keyframe-control-in-filmora-for-mac-users/"><u>New In 2024, The Art of Easing Audio Levels Keyframe Control in Filmora for Mac Users</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/valhallas-vanguard-fiery-rebirth/"><u>Valhalla's Vanguard  Fiery Rebirth</u></a></li>
<li><a href="https://win11.techidaily.com/1719222893625-eradicate-failed-capture-on-windows-devices-today/"><u>Eradicate Failed Capture on Windows Devices Today!</u></a></li>
<li><a href="https://win11.techidaily.com/quashing-the-spontaneous-search-on-win11-pc/"><u>Quashing the Spontaneous Search on Win11 PC</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-infinixwithwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Infinixwith/without a PC</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-samsung-galaxy-a05s-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your Samsung Galaxy A05s Device</u></a></li>
<li><a href="https://win11.techidaily.com/determining-optimal-nvidia-driver-gamingstudio-edition/"><u>Determining Optimal Nvidia Driver: Gaming/Studio Edition</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-master-video-presentation-implement-lc-and-bb-techniques-on-facebook/"><u>[Updated] In 2024, Master Video Presentation  Implement LC and BB Techniques on Facebook</u></a></li>
<li><a href="https://win11.techidaily.com/determine-your-pcs-wattage-usage-on-windows-system/"><u>Determine Your PC's Wattage Usage on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-to-optimize-cpu-load-from-tiworkerexe/"><u>Approaches to Optimize CPU Load From TiWorker.exe</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-unleashing-brand-potential-with-free-youtube-marketing-templates/"><u>[Updated] In 2024, Unleashing Brand Potential with FREE YouTube Marketing Templates</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-xbox-storage-solutions-the-essential-5-for-2024/"><u>[Updated] Xbox Storage Solutions  The Essential 5 for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-unleash-creative-fb-ad-videos-access-free-video-tools-now/"><u>[Updated] Unleash Creative FB Ad Videos - Access FREE Video Tools Now</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-all-about-iphone-14-unlock-chip-you-need-to-know-by-drfone-ios/"><u>In 2024, All About iPhone 14 Unlock Chip You Need to Know</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-the-comprehensive-guide-to-capturing-perfect-instagram-covers/"><u>In 2024, The Comprehensive Guide to Capturing Perfect Instagram Covers</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-your-pc-with-apples-imessage/"><u>Setting Up Your PC with Apple's iMessage</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-closed-nvidia-cp-window-in-w11-os/"><u>Overcoming Closed Nvidia CP Window in W11 OS</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/2024-approved-dive-into-fb-360-videos-recording-and-sharing-secrets/"><u>2024 Approved  Dive Into FB 360 Videos  Recording and Sharing Secrets</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-audiovisual-experts-choices-the-ultimate-video-editing-gear/"><u>In 2024, Audiovisual Experts' Choices  The Ultimate Video Editing Gear</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-windows-error-e8024002e-for-updates/"><u>Bypassing Windows Error E:8024002E for Updates</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-visionary-4k-cameras-leading-brands-a-to-z-top-18/"><u>2024 Approved  Visionary 4K Cameras  Leading Brands A-to-Z (Top 18)</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-not-writable-file-problems-in-windows-11/"><u>Solutions for Not Writable File Problems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-services-command-line-tool-with-these-7-steps/"><u>Restoring Window's Services Command Line Tool with These 7 Steps</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/movie-magic-for-kids-a-step-by-step-guide/"><u>Movie Magic for Kids A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/debugging-made-easy-essential-windows-fixers-guide/"><u>Debugging Made Easy: Essential Windows Fixers Guide</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-dismantling-windows-11s-misaligned-html-emails/"><u>Deciphering and Dismantling Windows 11'S Misaligned HTML Emails</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-choices-activating-filters-on-windows-11-files/"><u>Streamline Choices: Activating Filters on Windows 11 Files</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-use-estimating-windows-app-size/"><u>Efficient Use: Estimating Windows App Size</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-photo-mastery-top-8-web-based-creation-suite/"><u>[New] Photo Mastery  Top 8 Web-Based Creation Suite</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-screen-size-screen-sense-how-aspect-ratio-impacts-youtube-video-engagement/"><u>2024 Approved Screen Size, Screen Sense How Aspect Ratio Impacts YouTube Video Engagement</u></a></li>
<li><a href="https://win11.techidaily.com/why-gamers-should-trust-windows-vision-and-performance/"><u>Why Gamers Should Trust Windows' Vision and Performance</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Realme 12+ 5G? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-oppo-find-x6-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Oppo Find X6 Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Lava Blaze 2 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-11-mail-issues-with-html-enhanced-emails/"><u>Troubleshooting Windows 11 Mail Issues with HTML-Enhanced Emails</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-progressive-procedure-masterful-method-with-applewatch/"><u>In 2024, Progressive Procedure  Masterful Method with AppleWatch</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-keypads-your-guide-to-buying-youtube-ringtone-vids/"><u>In 2024, Keypads  Your Guide to Buying YouTube Ringtone Vids</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-best-of-the-best-top-intro-making-websites/"><u>New In 2024, Best of the Best Top Intro Making Websites</u></a></li>
<li><a href="https://extra-information.techidaily.com/revolutionizing-presentation-content-with-automated-transcription/"><u>Revolutionizing Presentation Content with Automated Transcription</u></a></li>
<li><a href="https://win11.techidaily.com/pro-tips-for-using-lesser-known-windows-11-assets-efficiently/"><u>Pro-Tips for Using Lesser Known Windows 11 Assets Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/the-10-best-apps-to-replace-windows-11s-default-apps/"><u>The 10 Best Apps to Replace Windows 11'S Default Apps</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/ultimate-roguelike-rankings-the-best-10-games/"><u>Ultimate Roguelike Rankings  The Best 10 Games</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-exception-breaking-point-achieved-in-windows/"><u>Troubleshooting Error: Exception Breaking Point Achieved in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-fix-to-unknown-not-initialized-in-windows/"><u>Step-by-Step Fix to 'Unknown Not Initialized' In Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-prime-selection-of-top-20-humorous-lockdown-memes-lifting-spirits-on-facebook/"><u>In 2024, Prime Selection of Top 20 Humorous Lockdown Memes, Lifting Spirits on Facebook</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-liberate-content-consumption-with-these-leading-free-and-on-demand-tools/"><u>[Updated] Liberate Content Consumption with These Leading Free & On-Demand Tools</u></a></li>
<li><a href="https://win11.techidaily.com/to-keep-or-not-to-delete-the-case-of-pagefilesys/"><u>To Keep or Not to Delete: The Case of Pagefile.sys</u></a></li>
<li><a href="https://win11.techidaily.com/auto-shutdown-hacks-for-idle-pcs-running-w10w11/"><u>Auto Shutdown Hacks for Idle PCs Running W10/W11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-easy-video-joining-solutions-top-alternatives-to-popular-software-for-2024/"><u>New Easy Video Joining Solutions Top Alternatives to Popular Software for 2024</u></a></li>
</ul></div>
