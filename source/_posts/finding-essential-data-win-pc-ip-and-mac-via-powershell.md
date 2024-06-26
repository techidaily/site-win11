---
title: "Finding Essential Data: Win PC IP & MAC via PowerShell"
date: 2024-06-25T10:08:04.629Z
updated: 2024-06-26T10:08:04.629Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Finding Essential Data: Win PC IP & MAC via PowerShell"
excerpt: "This Article Describes Finding Essential Data: Win PC IP & MAC via PowerShell"
keywords: Win PC IP Address,Mac IP Command,PowerShell IP Find,PC Network Info,IP Details Windows,OS X Net Data,PowerShell Network Query
thumbnail: https://thmb.techidaily.com/a0ea0929e49147a7aa2982696f1085c4ea3dc3044596db757054a8f03e6ab91e.jpg
---

## Finding Essential Data: Win PC IP & MAC via PowerShell

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
<li><a href="https://win11.techidaily.com/unveiling-windows-11s-user-sid-identification-methods/"><u>Unveiling Windows 11'S User SID Identification Methods</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-launch-windows-11-on-mac-through-parallels/"><u>Essential Steps to Launch Windows 11 on Mac Through Parallels</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-familiarity-migrating-custom-powertoys-on-a-new-device/"><u>Bringing Familiarity: Migrating Custom PowerToys on a New Device</u></a></li>
<li><a href="https://win11.techidaily.com/swift-keystrokes-in-win-os-a-guide-to-eliminate-delay/"><u>Swift Keystrokes in WIN OS: A Guide to Eliminate Delay</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-username-experience-on-windows-11-platform/"><u>Transforming UserName Experience on Windows 11 Platform</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-custom-audio-commands-in-the-latest-windows-os/"><u>Crafting Custom Audio Commands in the Latest Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-education-elements-into-windows-ui/"><u>Infuse Education Elements Into Windows UI</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-snap-happy-with-hero5-black-tips-for-stunning-visuals/"><u>In 2024, Snap-Happy with Hero5 Black  Tips for Stunning Visuals</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-the-compreenasional-path-to-post-perfection-instagram-video-upload-from-pcmac/"><u>[Updated] The Compreenasional Path to Post-Perfection  Instagram Video Upload From PC/Mac</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-oneplus-12-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on OnePlus 12</u></a></li>
<li><a href="https://screen-recording.techidaily.com/1716068867693-updated-2024-approved-2023-browser-snapshot-winners-announced/"><u>[Updated] 2024 Approved  2023 Browser Snapshot Winners Announced!</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-snap-and-save-games-the-nvidia-way/"><u>[Updated] 2024 Approved  Snap & Save Games - The NVIDIA Way</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-adapting-spotify-playlists-into-a-youtube-music-format/"><u>[Updated] Adapting Spotify Playlists Into a YouTube Music Format</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-crafting-captivating-igtv-cover-images-thumbnails/"><u>2024 Approved  Crafting Captivating IGTV Cover Images (Thumbnails)</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-retrace-mechanic-setup/"><u>In 2024, Retrace Mechanic Setup</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-innovations-in-mobile-sound-design-top-7-non-audacity-apps-for-android-enthusiasts/"><u>2024 Approved Innovations in Mobile Sound Design Top 7 Non-Audacity Apps for Android Enthusiasts</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>