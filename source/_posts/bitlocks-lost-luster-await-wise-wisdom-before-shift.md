---
title: "BitLocks Lost Luster: Await Wise Wisdom Before Shift"
date: 2024-07-13T09:52:00.815Z
updated: 2024-07-14T09:52:00.815Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes BitLocks Lost Luster: Await Wise Wisdom Before Shift"
excerpt: "This Article Describes BitLocks Lost Luster: Await Wise Wisdom Before Shift"
keywords: BitLock Secure Fading,Losing Lock Security,Wise Safeguarding Tips,Smart Security Transition,Guardianship Insights,Wisdom in Protection Shift,Prudent Encryption Guide
thumbnail: https://thmb.techidaily.com/0ca201532589a8340625e0277d57d7a6d8a4fe5f03caf08035754438a176d190.jpg
---

## BitLocks Lost Luster: Await Wise Wisdom Before Shift

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
<li><a href="https://meme-emoji.techidaily.com/updated-2024-approved-how-to-make-a-video-for-your-babys-first-year/"><u>Updated 2024 Approved How to Make a Video for Your Babys First Year</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/gain-cost-free-visuals-from-selective-4-youtube-feeds-for-2024/"><u>Gain Cost-Free Visuals From Selective 4 YouTube Feeds for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-overcoming-a-non-functional-search-in-windows-11s-environment/"><u>Tips for Overcoming a Non-Functional Search in Windows 11’S Environment</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-captivating-audience-leading-5-tiktok-font-generators-of-2023/"><u>In 2024, Captivating Audience  Leading 5 TikTok Font Generators of 2023</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-teams-screen-share-issues-quick-fixes/"><u>Microsoft Teams Screen Share Issues: Quick Fixes</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-mastering-video-speed-a-step-by-step-camtasia-tutorial/"><u>New In 2024, Mastering Video Speed A Step-by-Step Camtasia Tutorial</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-your-pathway-to-instagram-stardom-top-video-strategies-for-2024/"><u>[Updated] Your Pathway to Instagram Stardom  Top Video Strategies for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/high-res-quests-ultimate-guide-to-playing-adventures-in-hd-using-scummvm/"><u>High-Res Quests: Ultimate Guide to Playing Adventures in HD Using ScummVM</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-low-end-pc-visual-logging-software/"><u>[Updated] In 2024, Low-End PC Visual Logging Software</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-integrating-video-content-from-youtube-into-websites-a-comprehensive-guide/"><u>In 2024, Integrating Video Content From YouTube Into Websites - A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-new-browsing-potential-with-gesture-controls-in-microsoft-written-by-ai/"><u>Unlocking New Browsing Potential with Gesture Controls in Microsoft' Written by AI</u></a></li>
<li><a href="https://win11.techidaily.com/learn-mouse-gesture-tricks-in-microsofts-modern-edge-browser/"><u>Learn Mouse Gesture Tricks in Microsoft's Modern Edge Browser</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-unique-snap-configurations-in-win-os/"><u>Crafting Unique Snap Configurations in Win OS</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-integrating-twitter-feed-into-your-whatsapp-conversations/"><u>In 2024, Integrating Twitter Feed Into Your WhatsApp Conversations</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-powertoys-top-10-must-have-features/"><u>Boosting Productivity: PowerToys' Top 10 Must-Have Features</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-assessing-gopro-hero5-session-quality/"><u>[New] Assessing GoPro Hero5 Session Quality</u></a></li>
<li><a href="https://win11.techidaily.com/stop-spacing-out-sounds-fixes-to-unmute-keyboard-volume/"><u>Stop Spacing Out Sounds: Fixes to Unmute Keyboard Volume</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-pinnacle-recording-solutions-best-15-free-options-for-pcosx/"><u>[New] Pinnacle Recording Solutions  Best 15 Free Options for PC/OSX</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-insufficient-vram-for-enchanted-learning-environment/"><u>Tackling Insufficient VRAM for Enchanted Learning Environment</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-essential-list-15-books-shining-on-tiktoks-literary-scene/"><u>[Updated] In 2024, Essential List  15 Books Shining on TikTok's Literary Scene</u></a></li>
<li><a href="https://win11.techidaily.com/unravel-windows-mysteries-get-the-support-you-need/"><u>Unravel Windows Mysteries: Get the Support You Need!</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-external-monitor-not-responding-in-windows-os/"><u>Resolving External Monitor Not Responding in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/explore-win-11s-top-ranked-to-do-list-software-selections/"><u>Explore Win 11'S Top-Ranked To-Do List Software Selections</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-win-11-boot-drive-essential-tips-for-3-techniques/"><u>Creating a Win 11 Boot Drive – Essential Tips for 3 Techniques</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-enhancing-your-youtube-reach-with-famebit-ad-sponsorships/"><u>[New] In 2024, Enhancing Your YouTube Reach with FameBit Ad Sponsorships</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-usefulness-of-pagefilesys-backup-storage/"><u>Decoding Windows’ Usefulness of Pagefile.sys Backup Storage</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-win-1011-ad-ds-printer-errors-effectively-and-efficiently/"><u>Addressing Win 10/11 AD DS Printer Errors Effectively and Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-cpu-temp-controls-on-windows-1011/"><u>Customizing CPU Temp Controls on Windows 10/11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-nokia-c02-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Nokia C02 to Roku | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-calendar-game-with-personalization-tips-on-a-windows-pc/"><u>Step Up Your Calendar Game with Personalization Tips on a Windows PC</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-transformative-editing-experience-windows-photos-meets-story-remix/"><u>[New] 2024 Approved  Transformative Editing Experience  Windows Photos Meets Story Remix</u></a></li>
<li><a href="https://win11.techidaily.com/finding-and-fixing-non-functional-delete-keys-on-windows/"><u>Finding and Fixing Non-Functional Delete Keys on Windows</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-optimizing-hashtags-for-youtube-traffic-triplets/"><u>[Updated] Optimizing Hashtags for YouTube Traffic Triplets</u></a></li>
<li><a href="https://win11.techidaily.com/re-enabling-razer-device-discovery-on-win1011/"><u>Re-Enabling Razer Device Discovery on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/combat-the-frozen-discord-overlay-on-your-windows-system/"><u>Combat the Frozen Discord Overlay on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-shared-connectivity-options-google-versus-windows/"><u>Exploring Shared Connectivity Options: Google Versus Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-streaming-wars-recap-fb-live-yt-live-and-twitter-spaces/"><u>[Updated] Streaming Wars Recap  FB LIVE, YT Live & Twitter Spaces</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-debut-video-capture-review-and-alternative/"><u>2024 Approved  Debut Video Capture Review and Alternative</u></a></li>
<li><a href="https://win11.techidaily.com/transition-to-open-source-enable-linux-subsystem-for-windows/"><u>Transition to Open Source: Enable Linux Subsystem for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-vanishing-battery-time-indicator-in-windows-11/"><u>How to Fix the Vanishing Battery Time Indicator in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steam-and-internet-connectivity-woes-on-pc-heres-a-fix/"><u>Steam & Internet Connectivity Woes on PC? Here's a Fix</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-tracking-down-sites-that-sparkle-with-collective-cheers/"><u>Updated 2024 Approved Tracking Down Sites That Sparkle with Collective Cheers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-the-anonymous-advantage-in-instagram-viewing/"><u>[Updated] 2024 Approved  The Anonymous Advantage in Instagram Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-configuration-with-microsofts-pc-manager-on-w11/"><u>Conquer Configuration with Microsoft's PC Manager on W11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-quick-fix-techniques-for-social-media-collaborative-art/"><u>In 2024, Quick-Fix Techniques for Social Media Collaborative Art</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-battery-status-notifications-on-windows-os/"><u>Enhancing Battery Status Notifications on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-efficiency-essential-strategies-for-windows-11-users/"><u>Mastering Efficiency: Essential Strategies for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unwanted-keystrokes-during-typing/"><u>Preventing Unwanted Keystrokes During Typing</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-package-open-failures-in-win11win10-systems/"><u>Navigating Package Open Failures in Win11/Win10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixed-overcoming-application-crash-error/"><u>Mastering the Art of Fixed: Overcoming 'Application Crash' Error</u></a></li>
<li><a href="https://win11.techidaily.com/consistent-connections-avoiding-disruptions-in-windows/"><u>Consistent Connections: Avoiding Disruptions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/methods-to-utilize-copy-features-with-edge-protector-win11/"><u>Methods to Utilize Copy Features with Edge Protector, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/regain-control-fixing-wi-fi-mouse-malfunctions-in-windows/"><u>Regain Control: Fixing Wi-Fi Mouse Malfunctions in Windows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-elevate-video-popularity-12-key-strategies-unveiled-for-2024/"><u>[Updated] Elevate Video Popularity  12 Key Strategies Unveiled for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-network-link-disruptions-in-winmc-minecraft/"><u>Tackling Network Link Disruptions in WinMC Minecraft</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-convincing-audiences-to-join-a-positive-approach/"><u>In 2024, Convincing Audiences to Join  A Positive Approach</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-enhancing-tiktok-visibility-boosting-followers-and-like-ratios/"><u>[New] In 2024, Enhancing TikTok Visibility  Boosting Followers & Like Ratios</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-add-emotional-depth-learn-to-create-a-ken-burns-effect-in-minutes-for-2024/"><u>Updated Add Emotional Depth Learn to Create a Ken Burns Effect in Minutes for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/end-hibernation-hurdles-with-easy-fixes-for-win/"><u>End Hibernation Hurdles with Easy Fixes for Win</u></a></li>
<li><a href="https://win11.techidaily.com/typingpros-guide-to-swift-typing-using-typingaid/"><u>TypingPros Guide to Swift Typing Using TypingAid</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/professional-video-techniques-top-10-edits-for-2024/"><u>Professional Video Techniques  Top 10 Edits for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-navigating-facebook-live-your-2023-playbook/"><u>[Updated] Navigating Facebook Live  Your 2023 Playbook</u></a></li>
<li><a href="https://win11.techidaily.com/command-line-trick-turn-off-nvidias-visual-effects/"><u>Command Line Trick: Turn Off NVIDIA's Visual Effects</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-samsung-galaxy-s23-tactical-edition-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Samsung Galaxy S23 Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-instant-inspiration-free-video-intro-kits/"><u>2024 Approved  Instant Inspiration - Free Video Intro Kits</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-a-step-by-step-guide-to-forming-effective-youtube-partner-relationships-for-2024/"><u>[Updated] A Step-by-Step Guide to Forming Effective YouTube Partner Relationships for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Vivo X Fold 2? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-guide-how-to-check-icloud-activation-lock-status-from-your-iphone-se-2020-by-drfone-ios/"><u>New Guide How To Check iCloud Activation Lock Status From Your iPhone SE (2020)</u></a></li>
</ul></div>
