---
title: Easy-to-Understand Guide for Extracting IP/MAC Addresses
date: 2024-09-10T02:11:25.973Z
updated: 2024-09-16T17:13:00.718Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easy-to-Understand Guide for Extracting IP/MAC Addresses
excerpt: This Article Describes Easy-to-Understand Guide for Extracting IP/MAC Addresses
keywords: IP Address Basics,MAC Address Retrieval,Network Device Identification,IP/MAC Address Extraction,Locate Devices by Address,Accessing IP Info,Finding MAC Numbers
thumbnail: https://thmb.techidaily.com/20e687e989a89b1dd45743ceb6d6d3c635644bf241cd4154d769e7b945709de7.jpg
---

## Easy-to-Understand Guide for Extracting IP/MAC Addresses

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-help.techidaily.com/new-step-by-step-launching-google-meet-on-youtube/"><u>[New] Step-by-Step Launching Google Meet on YouTube</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-erase-background-noises-with-ease-using-audacity-tools/"><u>[Updated] 2024 Approved Erase Background Noises with Ease Using Audacity Tools</u></a></li>
<li><a href="https://some-approaches.techidaily.com/44cm5yid5bplusd6icf5zcr44gr44gn576o44gx44ge6ieq5a6255so44kk44or44of44on44o844k344on44oz5l2c44kk5oml5byv44gn44cn/"><u>「初心者向けで美しい自家用イルミネーション作り手引き」</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-lava-yuva-2-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost Lava Yuva 2 for Free? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/network-fixation-six-easy-ways-to-get-windows-network-hardware-working-again/"><u>Network Fixation: Six Easy Ways to Get Windows Network Hardware Working Again</u></a></li>
<li><a href="https://win11.techidaily.com/sleuthing-out-stealthy-cyber-menaces-on-pcs/"><u>Sleuthing Out Stealthy Cyber Menaces on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-wi-fi-connectivity-issues-in-winmc-minecraft/"><u>Tackling Wi-Fi Connectivity Issues in WinMC Minecraft</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-mechanism-of-winos-gpu-ordering-suspension/"><u>Understanding the Mechanism of WinOS GPU Ordering Suspension</u></a></li>
<li><a href="https://win-blog.techidaily.com/warzone-20-performance-tuning-how-to-achieve-lower-latency-and-improve-your-gaming-experience/"><u>Warzone 2.0 Performance Tuning: How to Achieve Lower Latency and Improve Your Gaming Experience</u></a></li>
<li><a href="https://blog-min.techidaily.com/why-i-spend-half-of-my-time-playing-games-on-my-iphone-a-look-into-mobile-gaming-habits/"><u>Why I Spend Half of My Time Playing Games on My iPhone: A Look Into Mobile Gaming Habits</u></a></li>
<li><a href="https://win11.techidaily.com/windows-best-weather-app-picks-compiled/"><u>Window's Best Weather App Picks, Compiled</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    