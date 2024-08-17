---
title: Busted ByteGuardian? Wait, Weigh Your Worthiness
date: 2024-08-16T00:21:58.576Z
updated: 2024-08-17T00:21:58.576Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Busted ByteGuardian? Wait, Weigh Your Worthiness
excerpt: This Article Describes Busted ByteGuardian? Wait, Weigh Your Worthiness
keywords: ByteGuardian Busted,Worthiness Measurement,Security Breach Alert,Assess Internet Safety,Guard Your Digital Value,Evaluate Cyber Trust,Online Security Worth
thumbnail: https://thmb.techidaily.com/62017b9a75f2be738008dfd82e88e32736119212be885f48835d0be5b0d3459a.jpg
---

## Busted ByteGuardian? Wait, Weigh Your Worthiness

### Quick Links

* [How Was BitLocker's Encryption Broken?](#how-was-bitlocker-39-s-encryption-broken)
* [Is It Time to Ditch BitLocker?](#is-it-time-to-ditch-bitlocker)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Key Takeaways

* BitLocker's encryption keys can be stolen with a Raspberry Pi Pico, but the exploit only works with external TPMs using the LPC bus.
* Most modern hardware integrates the TPM, making it more difficult to extract BitLocker keys. AMD and Intel CPUs are likely safe.
* Despite the exploit, BitLocker's AES-128 or AES-256 encryption is still secure, so there's no need to abandon it.

 Microsoft's BitLocker is one of the most popular full-disk encryption tools, and is built into Windows 10 and 11 Pro providing an easy encryption option for millions of Windows users worldwide. But BitLocker's reputation as a leading encryption tool could be under threat after a YouTuber successfully stole encryption keys and decrypted private data in just 43 seconds—using a Raspberry Pi Pico costing $6\.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How Was BitLocker's Encryption Broken?

 BitLocker's encryption was broken by YouTuber Stacksmashing, who posted a video detailing how he intercepted BitLocker data, extracted decryption keys, and successfully exploited the BitLocker encryption process.

 Stacksmashing's exploit involves the external Trusted Platform Module (TPM)—the same TPM chip that stops Windows 11 upgrades—found on some laptops and computers. While many motherboards integrate the TPM chip and modern CPUs integrate the TPM into their design, other machines still use an external TPM.

 Now, here's the issue and the exploit discovered by Stacksmashing. External TPMs communicate with the CPU using what's known as an LPC bus (Low Pin Count), which is a way for low-bandwidth devices to maintain communication with other hardware without creating a performance overhead.

 However, Stacksmashing found that while the data on the TPM is secure, during the boot-up process, the communication channels (the LPC bus) between the TPM and CPU are completely unencrypted. With the right tools, an attacker can intercept data sent between the TPM and CPU containing insecure encryption keys.

 Tools like the [Raspberry Pi Pico, the minute $6 single-board computer](https://www.makeuseof.com/raspberry-pi-pico-projects/) that has a bunch of uses. In this case, Stacksmashing connected a Raspberry Pi Pico to unused connectors on a test laptop and managed to read the binary data as the machine booted. The resulting data contained the Volume Master Key stored on the TPM, which he could then use to decrypt other data.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-essential-5-video-editing-software-excluding-youtube/"><u>[New] 2024 Approved  Essential 5 Video Editing Software Excluding Youtube</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-free-frame-conversion-tweeting-vids-into-animated-gifs/"><u>[New] 2024 Approved  Free Frame Conversion  Tweeting Vids Into Animated GIFs</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-affiliate-allies-for-small-channels-an-easy-approach-for-2024/"><u>[New] Affiliate Allies for Small Channels  An Easy Approach for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-calculating-costs-in-youtube-advertising-campaigns/"><u>[New] Calculating Costs in YouTube Advertising Campaigns</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-crafting-compelling-content-strategies-for-snapbiz-for-2024/"><u>[New] Crafting Compelling Content  Strategies for SnapBiz for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-engage-with-googles-online-gatherings-for-2024/"><u>[New] Engage with Google's Online Gatherings for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-crafting-compelling-slug-lines-a-step-by-step-approach/"><u>[New] In 2024, Crafting Compelling Slug Lines  A Step-by-Step Approach</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-the-art-of-aural-storytelling-on-instagram-reels/"><u>[Updated] 2024 Approved  The Art of Aural Storytelling on Instagram Reels</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-expert-tips-for-converting-facebook-hd-video-quality-to-mp4-online/"><u>[Updated] Expert Tips for Converting Facebook HD Video Quality to MP4 Online</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-secrets-of-facebooks-2023-full-screen-video-settings/"><u>[Updated] Secrets of Facebook's 2023 Full Screen Video Settings</u></a></li>
<li><a href="https://win11.techidaily.com/5-ways-to-stop-infinite-data-depletion-in-windows/"><u>5 Ways to Stop Infinite Data Depletion in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-home-screen-norm-setting-default-position-of-win-11-keyboards/"><u>Achieving Home Screen Norm: Setting Default Position of Win 11 Keyboards</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-alternative-methods-in-windows-exploration-no-ls/"><u>Deciphering Alternative Methods in Windows Exploration (No LS)</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-clipboard-problems-in-windows-11/"><u>Diagnosing Clipboard Problems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/dive-into-efficiency-utilizing-windows-11s-taskbar-search/"><u>Dive Into Efficiency: Utilizing Windows 11'S Taskbar Search</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-pc-information-gathering-using-everythingapp/"><u>Efficient PC Information Gathering Using EverythingApp</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/effortless-online-path-to-czech-fluency/"><u>Effortless Online Path to Czech Fluency</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-microcomputers-reviewed/"><u>Essential Windows Microcomputers Reviewed</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-new-strategies-behind-extended-updates-in-windows-11-h2/"><u>Exploring the New Strategies Behind Extended Updates in Windows 11 H2</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-free-epson-stylus-nx42n-driver-compatible-with-windows-7810-here/"><u>Get Your Free Epson Stylus NX42n Driver Compatible with Windows 7/8/10 Here!</u></a></li>
<li><a href="https://win11.techidaily.com/how-runtime-broker-enhances-system-efficiency-and-security/"><u>How Runtime Broker Enhances System Efficiency & Security</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-realme-gt-5-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On Realme GT 5 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correct-display-not-available-error-in-windows-11/"><u>How to Correct 'Display Not Available' Error in Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-display-apple-iphone-6s-plus-screen-on-pc-easily-drfone-by-drfone-ios/"><u>How to Display Apple iPhone 6s Plus Screen on PC Easily? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-samsung-galaxy-a05-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Samsung Galaxy A05 Quickly? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-folders-reverting-to-read-only-mode-in-windows-10-and-11/"><u>How to Fix Folders Reverting to Read-Only Mode in Windows 10 and 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-sony-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Sony</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-individual-gpo-settings-for-windows-users-1111-edition/"><u>Implementing Individual GPO Settings for Windows Users 11/11 Edition</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-print-functions-in-microsofts-security-shield/"><u>Implementing Print Functions in Microsoft's Security Shield</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-overcoming-technical-hurdles-in-iphone-xs-facial-detection/"><u>In 2024, Overcoming Technical Hurdles in iPhone X's Facial Detection</u></a></li>
<li><a href="https://win11.techidaily.com/key-apps-to-bring-your-windows-pc-and-android-together/"><u>Key Apps to Bring Your Windows PC and Android Together</u></a></li>
<li><a href="https://win11.techidaily.com/locate-vanished-settings-a-guide-to-finding-them-on-win11/"><u>Locate Vanished Settings: A Guide to Finding Them on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/quelling-the-0x800736cc-dilemran-in-windows-update/"><u>Quelling the 0X800736CC Dilemran in Windows Update</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-instantaneous-folder-upload-failures-in-the-windows-onedrive-environment/"><u>Quick Fixes for Instantaneous Folder Upload Failures in the Windows OneDrive Environment</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolve-0x80072efd-on-windows-devices/"><u>Quick Guide to Resolve 0X80072EFD on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-normal-operations-of-netflix-window/"><u>Re-Establishing Normal Operations of Netflix Window</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-0x80d03801-issue-in-windows-shop/"><u>Remedying 0X80D03801 Issue in Windows Shop</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/resolved-complications-pci-encrypt-decrypt-engine-module-troubleshooting/"><u>Resolved Complications: PCI Encrypt-Decrypt Engine Module Troubleshooting</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-copy-and-paste-on-chrome-edge-and-firefox-windows/"><u>Restoring Copy & Paste on Chrome, Edge, and Firefox (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-pc-three-methods-for-a-clean-windows-boot/"><u>Revitalize PC: Three Methods for a Clean Windows Boot</u></a></li>
<li><a href="https://win11.techidaily.com/selecting-the-best-downloader-choco-vs-windows-package-tool/"><u>Selecting the Best Downloader: Choco Vs. Windows Package Tool</u></a></li>
<li><a href="https://unlock-android.techidaily.com/still-using-pattern-locks-with-vivo-g2-tips-tricks-and-helpful-advice-by-drfone-android/"><u>Still Using Pattern Locks with Vivo G2? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-user-initiated-windows-screen-shift/"><u>Stopping User-Initiated Windows Screen Shift</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-averting-crashes-of-epic-games-launcher/"><u>Strategies for Averting Crashes of Epic Games Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/sweeping-away-windows-access-errors-effectively/"><u>Sweeping Away Windows' Access Errors Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-unresponsive-windows-11-printer-ports-and-devices/"><u>Tackling Unresponsive Windows 11 Printer Ports & Devices</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-your-pc-experience-on-windows-11-devices/"><u>Tailoring Your PC Experience on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tip-converting-esd-to-iso-without-compromising-data-integrity-on-windows/"><u>Tech Tip: Converting ESD to ISO without Compromising Data Integrity on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-stop-discord-initial-launch-and-searching-at-boot/"><u>Techniques: Stop Discord Initial Launch & Searching at Boot</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-foremost-chatgpt-techniques-for-enhanced-health-outcomes/"><u>The Foremost ChatGPT Techniques for Enhanced Health Outcomes</u></a></li>
<li><a href="https://win11.techidaily.com/the-path-to-peace-sleep-mode-strategies/"><u>The Path to Peace: Sleep Mode Strategies</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-oneplus-12-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your OnePlus 12 Phone Pattern Lock</u></a></li>
<li><a href="https://some-guidance.techidaily.com/titlegenius-revolutionizing-video-title-generation-for-2024/"><u>TitleGenius  Revolutionizing Video Title Generation for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-xiaomi-redmi-note-12-5g-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Xiaomi Redmi Note 12 5G Phones</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/transcribing-speech-to-mp3-audio-format-for-diverse-platforms/"><u>Transcribing Speech to MP3 Audio Format for Diverse Platforms</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unleashing-imagination-in-writing-through-chatgpt-learn-these-6-strategies/"><u>Unleashing Imagination in Writing Through ChatGPT: Learn These 6 Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/windows-adjusting-user-permissions-for-regular-accounts/"><u>Windows: Adjusting User Permissions for Regular Accounts</u></a></li>
</ul></div>
