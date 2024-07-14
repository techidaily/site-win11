---
title: "Breached ByteBandit: Ponder the Path for a Possible Pivot"
date: 2024-07-13T11:28:08.216Z
updated: 2024-07-14T11:28:08.216Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Breached ByteBandit: Ponder the Path for a Possible Pivot"
excerpt: "This Article Describes Breached ByteBandit: Ponder the Path for a Possible Pivot"
keywords: Breach ByteBandit,Cybersecurity Shift,Data Protection Change,Risk Management Redirection,Security Update Strategy,IT Transformation Tactic,Digital Defense Revision
thumbnail: https://thmb.techidaily.com/6ef16648595e97873cff52eb597372e60de93b0601596509e90390a2a00c63c2.jpg
---

## Breached ByteBandit: Ponder the Path for a Possible Pivot

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/advanced-file-system-interactions-a-step-bystep-guide/"><u>Advanced File System Interactions: A Step-Bystep Guide</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-free-avi-video-editor-reviews-our-top-picks-for-2024/"><u>New Free AVI Video Editor Reviews Our Top Picks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/beating-full-screen-freezes-and-crashes-in-sonic-games-on-w11-os/"><u>Beating Full-Screen Freezes and Crashes in Sonic Games on W11 OS</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unlocking-iphone-shot-potential-adopt-these-10-principles/"><u>[New] Unlocking iPhone Shot Potential  Adopt These 10 Principles</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-into-windowsstore-app-folder-secrets/"><u>Breaking Into WindowsStore App Folder Secrets</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-vivo-y77t-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Vivo Y77t Activity | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/basking-in-low-light-the-art-of-dark-modes-in-paint/"><u>Basking in Low Light: The Art of Dark Modes in Paint</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/10-best-foreign-films-to-improve-your-language-skills/"><u>10 Best Foreign Films To Improve Your Language Skills</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-xiaomi-redmi-note-13-pro-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Xiaomi Redmi Note 13 Pro 5G without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-optimizing-your-video-capture-with-screencastify/"><u>[Updated] In 2024, Optimizing Your Video Capture with Screencastify</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-a-comprehensive-guide-to-crafting-stellar-tiktok-campaigns/"><u>[New] In 2024, A Comprehensive Guide to Crafting Stellar TikTok Campaigns</u></a></li>
<li><a href="https://extra-hints.techidaily.com/one-source-livestream-perfection-a-streamers-blueprint/"><u>One-Source Livestream Perfection  A Streamer's Blueprint</u></a></li>
<li><a href="https://win11.techidaily.com/boost-input-speed-learn-from-typingaid/"><u>Boost Input Speed: Learn From TypingAid</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-why-windows-dominates-in-gaming-landscape/"><u>Breaking Down Why Windows Dominates in Gaming Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-net-essential-windows-fixes-max-156/"><u>Boosting .NET: Essential Windows Fixes (Max 156)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-forge-funnies-giphys-playground/"><u>In 2024, Forge Funnies  Giphy's Playground</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-not-working-mishaps-on-your-devices-windows-apps/"><u>Avoiding 'Not Working' Mishaps on Your Device’s Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-10-safe-free-software-download-sites/"><u>Best Practices: 10 Safe Free Software Download Sites</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-boundaries-chatgpt-alternatives-win-style/"><u>Breaking Boundaries: ChatGPT Alternatives, WIN-Style</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-efficiency-using-keyboard-shortcuts-for-windows-taskbar-management/"><u>Boosting Efficiency: Using Keyboard Shortcuts for Windows Taskbar Management</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-a-guide-to-peak-performance-posting-times-for-insta-success/"><u>[New] A Guide to Peak Performance  Posting Times for Insta Success</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-game-loading-times-for-epic-universe/"><u>Boosting Game Loading Times for Epic Universe</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-into-windows-passwords-the-11-easiest-ways-to-open-credential-manager/"><u>Breaking Into Windows Passwords: The 11 Easiest Ways to Open Credential Manager</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-linux-infrastructure-with-windows-software/"><u>Augmenting Linux Infrastructure with Windows Software</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-reset-a-locked-vivo-y200-phone-by-drfone-android/"><u>How to Reset a Locked Vivo Y200 Phone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-verified-app-alerts-for-windows-users/"><u>Addressing Non-Verified App Alerts for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-android-performance-with-optimized-resources-on-wsl/"><u>Boosting Android Performance with Optimized Resources on WSL</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-converting-heic-images-to-jpeg-in-windows-11/"><u>Advanced Tips for Converting HEIC Images to JPEG in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/backup-basics-protecting-your-digital-adventures-in-epic-games/"><u>Backup Basics: Protecting Your Digital Adventures in Epic Games</u></a></li>
<li><a href="https://win11.techidaily.com/break-the-code-essential-steps-to-game-folder-opening/"><u>Break the Code: Essential Steps to Game Folder Opening</u></a></li>
<li><a href="https://extra-resources.techidaily.com/step-by-step-review-of-picsart-apps-new-features-2024-edition/"><u>Step-by-Step Review of PicsArt App's New Features, 2024 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/big-bulky-minipcs-with-brainy-bare-performance/"><u>Big, Bulky Minipcs with Brainy Bare Performance</u></a></li>
<li><a href="https://win11.techidaily.com/beating-down-error-code-31-in-the-windows-landscape/"><u>Beating Down Error Code 31 in the Windows Landscape</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-unlock-creative-potential-with-customizable-vocal-effects-on-tiktok/"><u>2024 Approved  Unlock Creative Potential with Customizable Vocal Effects on TikTok</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-the-utility-of-windows-11s-initial-interface/"><u>Boosting the Utility of Windows 11'S Initial Interface</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-supreme-song-synchronizer-app-android/"><u>In 2024, Supreme Song Synchronizer App (Android)</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-powershell-from-windows-command-prompt/"><u>Addressing Missing PowerShell From Windows Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-in-remote-steam-functionality/"><u>Breaking Barriers in Remote Steam Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-using-github-desktop-on-windows-1011/"><u>Boost Productivity: Using GitHub Desktop on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/best-browsing-on-three-oses-minimal-resource-browser-choices/"><u>Best Browsing on Three OSes: Minimal Resource Browser Choices</u></a></li>
<li><a href="https://win11.techidaily.com/banish-old-wallpaper-memories-triple-approach/"><u>Banish Old Wallpaper Memories: Triple Approach</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-reimagining-administrative-protocols-on-windows/"><u>Breaking Barriers: Reimagining Administrative Protocols on Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/elevate-your-tech-game-master-the-craft-of-screen-recordings-in-macos-for-2024/"><u>Elevate Your Tech Game  Master the Craft of Screen Recordings in macOS for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-nostalgia-bites-the-best-kiddie-games-ever-for-2024/"><u>[Updated] Nostalgia Bites  The Best Kiddie Games Ever for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/averting-the-def5-blunder-in-onedrive-w11-issues/"><u>Averting the Def5 Blunder in OneDrive W11 Issues</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-barriers-to-accessing-steam-files/"><u>Breaking Down Barriers to Accessing Steam Files</u></a></li>
<li><a href="https://techidaily.com/xiaomi-video-recovery-recover-deleted-videos-from-xiaomi-by-fonelab-android-recover-video/"><u>Xiaomi Video Recovery - Recover Deleted Videos from Xiaomi</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-wmv-video-splitting-made-easy-top-5-free-tools/"><u>Updated In 2024, WMV Video Splitting Made Easy Top 5 Free Tools</u></a></li>
<li><a href="https://win11.techidaily.com/boost-keyboard-efficiency-top-strategies-for-speed-on-windows-devices/"><u>Boost Keyboard Efficiency: Top Strategies for Speed on Windows Devices</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-sizzling-stories-whos-cooking-up-the-trends-in-2024/"><u>[Updated] Sizzling Stories  Who's Cooking Up the Trends, In 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>