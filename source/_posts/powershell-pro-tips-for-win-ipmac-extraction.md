---
title: PowerShell Pro Tips for Win IP/MAC Extraction
date: 2024-07-13T11:05:27.865Z
updated: 2024-07-14T11:05:27.865Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes PowerShell Pro Tips for Win IP/MAC Extraction
excerpt: This Article Describes PowerShell Pro Tips for Win IP/MAC Extraction
keywords: PowerShell Extract MACs,WinIP Mac Extraction,PowerShell IP Addressing,Advanced Windows IP Tools,PowerShell Network Forensics,OSINT via PowerShell,Security Scripts for IP/MAC
thumbnail: https://thmb.techidaily.com/e90a41374ab8bcea029035e600ef5fff009cee16ec9e8eead9f3969598aefde0.jpg
---

## PowerShell Pro Tips for Win IP/MAC Extraction

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://unlock-android.techidaily.com/in-2024-7-ways-to-unlock-a-locked-infinix-note-30-vip-racing-edition-phone-by-drfone-android/"><u>In 2024, 7 Ways to Unlock a Locked Infinix Note 30 VIP Racing Edition Phone</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-security-avoid-chatbots-for-win-11-keys/"><u>Bypassing Security: Avoid Chatbots for Win 11 Keys</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-update-failure-0x8024800c/"><u>Correcting Windows Update Failure: 0X8024800C</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-print-on-edge-security-mode-windows-11/"><u>Enabling Print on Edge Security Mode Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-cutting-through-the-noise-strategies-for-standout-instagram-success/"><u>[Updated] 2024 Approved  Cutting Through the Noise  Strategies for Standout Instagram Success</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-cpu-usage-from-dropbox-on-windows-pcs/"><u>Addressing High CPU Usage From Dropbox on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/chronology-clash-wintime-harmony-guide/"><u>Chronology Clash? WinTime Harmony Guide</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-update-fault-x8019/"><u>Eliminating Windows Update Fault X8019</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-harnessing-technology-the-art-of-capturing-ios-devices-in-media/"><u>[New] 2024 Approved  Harnessing Technology  The Art of Capturing iOS Devices in Media</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-from-apple-iphone-6-plus-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data from Apple iPhone 6 Plus? | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/ideal-selections-the-best-9-mobile-video-meeting-solutions-reviewed-for-2024/"><u>Ideal Selections  The Best 9 Mobile Video Meeting Solutions Reviewed for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719358014112-chrome-woes-on-windows-11-a-fixers-guide-to-reopening-it/"><u>Chrome Woes on Windows 11: A Fixer’s Guide to Reopening It.</u></a></li>
<li><a href="https://win11.techidaily.com/windows-struggles-lack-of-drive-letters-explained-and-cured/"><u>Windows Struggles: Lack of Drive Letters Explained & Cured</u></a></li>
<li><a href="https://win11.techidaily.com/blowing-up-gpu-usage-7-remedies-for-wm-in-win11/"><u>Blowing Up GPU Usage: 7 Remedies for WM in Win11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-guide-to-professional-gopro-filming/"><u>2024 Approved  The Ultimate Guide to Professional GoPro Filming</u></a></li>
<li><a href="https://win11.techidaily.com/windows-10plus-users-unlocking-the-secrets-of-your-ram-type/"><u>Windows 10+ Users: Unlocking the Secrets of Your RAM Type</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-elevate-conference-quality-the-list-of-top-10-free-audio-capture/"><u>2024 Approved  Elevate Conference Quality  The List of Top 10 Free Audio Capture</u></a></li>
<li><a href="https://win11.techidaily.com/why-excel-fails-to-open-in-windows-notepad/"><u>Why Excel Fails to Open in Windows Notepad?</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-apple-iphone-15-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Apple iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-fb-video-grabber-hq-download-guide/"><u>[New] 2024 Approved  FB Video Grabber  HQ Download Guide</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Nokia G42 5G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-galaxy-s23-tactical-edition-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve deleted photos on Galaxy S23 Tactical Edition</u></a></li>
<li><a href="https://win11.techidaily.com/1719326965126-unravel-windows-troubles-step-by-step-support-guide/"><u>Unravel Windows Troubles: Step-by-Step Support Guide</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-the-lock-screen-timeout-stops-working-on-windows/"><u>What to Do if the Lock Screen Timeout Stops Working on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-sound-revolution-embrace-dolby-atmos/"><u>Win 10/11 Sound Revolution: Embrace Dolby Atmos</u></a></li>
<li><a href="https://win11.techidaily.com/flashback-fun-enjoying-oldschool-games-with-dosbox-x/"><u>Flashback Fun: Enjoying Oldschool Games with DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-microsoft-store-error-x00000000-in-win-11/"><u>Addressing the Microsoft Store Error X00000000 in Win 11</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-enhancing-engagement-with-solutions-to-common-shorts-challenges/"><u>[New] Enhancing Engagement with Solutions to Common Shorts Challenges</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-functionality-of-component-services-utility-in-windows/"><u>Exploring the Functionality of Component Services Utility in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-to-re-enable-your-windows-11-device-after-error-22/"><u>Expert Tips to Re-Enable Your Windows 11 Device After Error 22</u></a></li>
<li><a href="https://win11.techidaily.com/ace-file-moves-with-advanced-auto-transfer-techniques-on-win-11/"><u>Ace File Moves with Advanced Auto-Transfer Techniques on Win 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-screen-capture-showdown-is-obs-better-than-fraps/"><u>[New] Screen Capture Showdown  Is OBS Better Than Fraps?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-xiaomi-13t-pro-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Xiaomi 13T Pro Phone? Unlock It Now</u></a></li>
</ul></div>
