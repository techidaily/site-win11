---
title: PowerShell Pro Tips for Win IP/MAC Extraction
date: 2024-06-25T11:45:04.280Z
updated: 2024-06-26T11:45:04.280Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/reconnecting-windows-remotes-resolving-unacceptable-links/"><u>Reconnecting Windows Remotes: Resolving Unacceptable Links</u></a></li>
<li><a href="https://win11.techidaily.com/six-easy-steps-to-knowing-the-model-behind-your-pc-windows-edition/"><u>Six Easy Steps To Knowing The Model Behind Your PC Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-clipchamp-solve-windows-11-install-problems/"><u>Unlocking ClipChamp: Solve Windows 11 Install Problems</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-services-command-line-tool-with-these-7-steps/"><u>Restoring Window's Services Command Line Tool with These 7 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/prodigy-preparation-must-haves-from-microsoft-store/"><u>Prodigy Preparation: Must-Haves From Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-savings-with-windows-11-pro-secure-top-deals/"><u>Maximize Savings with Windows 11 Pro: Secure Top Deals</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-addressing-system-call-failed-on-pcs/"><u>Best Practices for Addressing System Call Failed on PCs</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-explore-the-globe-top-10-travelers-youtube-guide/"><u>[New] 2024 Approved  Explore the Globe  Top 10 Traveler's YouTube Guide</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-effective-approaches-for-transferring-audacity-productions-into-mp3-format/"><u>Updated Effective Approaches for Transferring Audacity Productions Into MP3 Format</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-the-ultimate-list-of-free-video-cutter-and-joiner-software-for-beginners/"><u>2024 Approved The Ultimate List of Free Video Cutter and Joiner Software for Beginners</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-honor-magic-v2-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Honor Magic V2 for Free? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/icloud-separation-how-to-disconnect-apple-iphone-11-pro-and-ipad-by-drfone-ios/"><u>iCloud Separation How To Disconnect Apple iPhone 11 Pro and iPad</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-a-step-by-step-guide-to-mastering-quick-scrubbing/"><u>[Updated] A Step-by-Step Guide to Mastering Quick Scrubbing</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>Thinking About Changing Your Netflix Region Without a VPN On Apple iPhone 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-comparing-the-giants-an-in-depth-guide-to-tiktok-vs-snapchats-functionality-for-2024/"><u>[New] Comparing the Giants  An In-Depth Guide to TikTok vs Snapchat's Functionality for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>