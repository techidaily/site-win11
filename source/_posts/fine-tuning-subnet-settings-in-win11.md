---
title: Fine-Tuning Subnet Settings in Win11
date: 2025-01-30T09:47:14.683Z
updated: 2025-02-04T08:31:20.360Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Fine-Tuning Subnet Settings in Win11
excerpt: This Article Describes Fine-Tuning Subnet Settings in Win11
keywords: Win11 NetConfig Tuning,ProSubnet Optimization,Network Interface Fine-Tune,Win11 IP Address Filtering,Subnet Settings Optimization,Network Gateway Adjustment,Win11 NIC Configurations
thumbnail: https://thmb.techidaily.com/e03e7f36869e1845d154715bfdea777a291cb2eaca41f020a72559cf27e30f77.jpg
---

## Fine-Tuning Subnet Settings in Win11

 Devices in a subnetwork have IP addresses that begin with the same prefix. The length of this prefix is different for different devices—it depends on the network size, whose length is identified using the subnet mask.

 While troubleshooting network issues, you must ensure that the subnet mask is correct. So, we'll share how to find and change the subnet in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Find the Subnet Mask in Windows 11

 The easiest way to find the subnet mask in Windows 11 is through the[Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) or Windows PowerShell. To find it using the Command Prompt, follow the steps below:

1. Press the**Win** key to launch the Start Menu.
2. In the search bar, type**Command Prompt** and choose the**Run as administrator** option from the right pane.
3. In the elevated Command Prompt window, type**ipconfig /all** and press Enter. This command will display all the important details about the network your computer is connected to, including the subnet mask.
4. Scroll and look for**Subnet Mask.** It'll be under the**Wireless LAN adapter Wi-Fi** section.  
![Finding the Subnet mask in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/finding-the-subnet-mask.jpg)

 The steps to do it using Windows PowerShell are similar to the Command Prompt. To do it,[open Windows PowerShell with admin rights](https://www.makeuseof.com/windows-11-powershell-administrator/) , type the ipconfig /all command, and press Enter.

 In the result that appears, you can see the subnet mask under the Wireless LAN adapter Wi-Fi section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Subnet Mask in Windows 11

 Now that you know how to find the subnet mask on your computer, let's check out how to change it.

### 1\. Change the Subnet Mask Using the Windows Settings

 The settings menu is the central hub of a Windows operating system. It's a place to configure different settings of your computer and manage the network. You can also use it to change the subnet mask.

Here's how to do it:

1. [Open the Windows Systems Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and choose**Network & internet** from the left panel.
2. Select**Wi-Fi,** and then choose your network in the following window.
3. Click the**Edit** button next to the**IP assignment** option.  
![Edit button in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/edit-button.jpg)
4. In the prompt that crops up, click on the drop-down icon and choose**Manual.**

5. Enable the toggle next to the IP version you're using.
6. Enter the details, including the subnet mask, and click**Save.**  
![Entering the new Subnet Mask in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/entering-the-new-subnet-mask.jpg)

### 2\. Change the Subnet Mask Using the Control Panel

 The Control Panel is the go-to place to configure window settings and make changes to your device. To use it to change the subnet mask, follow the below instructions:

1. Press the Win key, type**Control Panel** in the search bar, and press Enter.
2. Click the drop-down icon next to**View by** and choose**Large icons.**
3. Choose**Network and Internet** , and then select**Network and Sharing Center** in the following window.
4. Click on your network next to**Connections.**  
![Network name in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-name.jpg)
5. Choose**Properties** from the window that appears.

6. Select the IP version you're using. For instance, if you're using IPv4, select**Internet Protocol Version 4 (TCP/IPv4)** and click the**Properties** button.  
![IPv4 properties option in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv4-properties.jpg)
7. Select the**Use the following address** option and enter the details.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Changing the Subnet Mask in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/changing-the-subnet-mask.jpg)
8. Click**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Change the Subnet Mask Using Windows PowerShell

 Windows PowerShell is also one of the places from where you can change the subnet mask in Windows 11\. Here's how to do it:

1. Open Windows PowerShell with admin rights, type the following command, and press Enter. This command will display all the network adapters installed on your device.  
`Get-NetAdapter -physical`
2. To change the subnet mask, type the following command and press Enter. Make sure to replace the "**ifIndex Number** " with the number associated with the network adapter whose subnet mask you want to change. And replace "**subnet prefix length** " with the new subnet prefix length you want.  
`Set-NetIPAddress -InterfaceIndex (ifIndex Number) -PrefixLength (subnet prefix length)`

 For instance, if the ifIndex Number is 3 and the new subnet prefix length you want is 24, then the command will be:

`Set-NetIPAddress -InterfaceIndex 3 -PrefixLength 24`

![Command to change the subnet mask in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-change-the-subnet-mask.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aG3NRuHrIJg?si=HwzwD0RXmrzIXX1V" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Changing the Subnet Mask in Windows 11

 The subnet mask helps to identify the network and the host bit of the IP address. If you want to find and change the subnet mask on your computer, you can do it using either of the above methods.

 Meanwhile, you might be interested to know more about subnets and how to calculate them.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-clips.techidaily.com/updated-film-like-a-pro-scenic-filter-ideas-for-tiktok-stars/"><u>[Updated] Film Like a Pro Scenic Filter Ideas for TikTok Stars</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-viberushers-top-10-themes-betterdiscord-style-for-2024/"><u>[Updated] VibeRusher’s Top 10 Themes - BetterDiscord Style for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-transform-your-snapchat-storytelling-learn-to-zoom-like-pros/"><u>2024 Approved Transform Your Snapchat Storytelling Learn to Zoom Like Pros</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-unseen-strategies-how-to-tap-into-your-facebook-message-library/"><u>2024 Approved Unseen Strategies How to Tap Into Your Facebook Message Library</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-instructions-for-adding-intel-lan-drivers-to-pcs/"><u>Comprehensive Instructions for Adding Intel LAN Drivers to PCs</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/dominance-index-top-ten-royale-survival-games-for-2024/"><u>Dominance Index Top Ten Royale Survival Games for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-security-add-trusted-sites-to-windows-11/"><u>Enhancing Security: Add Trusted Sites to Windows 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-xiaomi-redmi-12-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Xiaomi Redmi 12 FRP Locks</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/is-fake-gps-location-spoofer-a-good-choice-on-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>Is Fake GPS Location Spoofer a Good Choice On Apple iPhone XS? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-microsoft-store-apps-await-you-2023/"><u>Masterful Microsoft Store Apps Await You, 2023</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-0x800700e1-in-surface-pro-win10/"><u>Overcoming 0X800700E1 in Surface Pro (Win10)</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-bluetooth-device-music-without-mutevolume-control/"><u>Overcoming Windows Bluetooth Device - Music Without Mute/Volume Control</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/snag-the-perfect-pair-premium-earbud-and-over-ear-deals-for-march-2-insider-tips/"><u>Snag the Perfect Pair: Premium Earbud and Over-Ear Deals for March 2^ | Insider Tips</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-guide-how-to-fix-no-signal-issue-when-linking-your-dvd-player-to-an-hdtv/"><u>Troubleshooting Guide: How To Fix No-Signal Issue When Linking Your DVD Player to an HDTV</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-leap-forward-unpacking-patch-release-wxx-features/"><u>Windows 11'S Leap Forward: Unpacking Patch Release W.x.x Features</u></a></li>
</ul></div>

