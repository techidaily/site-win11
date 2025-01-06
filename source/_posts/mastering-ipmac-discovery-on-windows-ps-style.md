---
title: Mastering IP/MAC Discovery on Windows, PS Style
date: 2025-01-04T18:45:40.463Z
updated: 2025-01-06T18:37:38.940Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering IP/MAC Discovery on Windows, PS Style
excerpt: This Article Describes Mastering IP/MAC Discovery on Windows, PS Style
keywords: IP/MAC WinDiscovery,MAC Address Finder,Windows Discover IP,PS Network Identify,OS IPMAC Locate,NET_SNMP Enable,NetBIOS SNMP Info
thumbnail: https://thmb.techidaily.com/bdb8177ec45e10fcd4ec5499f6e255ec00146feb57465bd8edaf95619ca00bc2.jpg
---

## Mastering IP/MAC Discovery on Windows, PS Style

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-freeze-frame-fun-the-complete-guide-to-xbox-one-snapshots/"><u>[New] 2024 Approved Freeze Frame Fun The Complete Guide to Xbox One Snapshots</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-refining-audio-in-obs-high-quality-mode-for-2024/"><u>[Updated] Refining Audio in OBS High-Quality Mode for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-videos-from-vivo-y77t-by-fonelab-android-recover-video/"><u>Easy steps to recover deleted videos from Vivo Y77t</u></a></li>
<li><a href="https://win11.techidaily.com/expedited-troubleshoot-utility-access-via-windows-hotkey-setups/"><u>Expedited Troubleshoot Utility Access via WIndows Hotkey Setups</u></a></li>
<li><a href="https://win-blog.techidaily.com/1723009885237-forza-horizon-4-pc-fix-no-more-vehicle-collisions/"><u>Forza Horizon 4 PC Fix - No More Vehicle Collisions</u></a></li>
<li><a href="https://win11.techidaily.com/identifying-older-windows-systems-quickly/"><u>Identifying Older Windows Systems Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-quick-fix-in-windows-11/"><u>Implementing Quick Fix in Windows 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-building-harmonious-forms-crafting-circles-and-spheres/"><u>In 2024, Building Harmonious Forms Crafting Circles and Spheres</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Detect and Remove Spyware on Apple iPhone X? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlocking-iphone-8-passcode-without-a-computer-drfone-by-drfone-ios/"><u>In 2024, Unlocking iPhone 8 Passcode without a Computer | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/master-swift-keystrokes-through-powertoys-use/"><u>Master Swift Keystrokes Through PowerToys Use</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-remote-desktop-connections-in-windows-11/"><u>Mastering Remote Desktop Connections in Windows 11</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-in-2024-how-to-record-your-memorable-honeymoon-video/"><u>New In 2024, How to Record Your Memorable Honeymoon Video</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-surfing-adding-trusted-websites/"><u>Secure Your Surfing: Adding Trusted Websites</u></a></li>
<li><a href="https://win11.techidaily.com/skyrocketing-back-to-basics-three-windows-restarts/"><u>Skyrocketing Back to Basics: Three Windows Restarts</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-quick-repair-of-call-failed-on-windows-1011/"><u>Strategies for Quick Repair of 'Call Failed' On Windows 10/11</u></a></li>
</ul></div>

