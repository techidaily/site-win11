---
title: Unveiling PC's Global IP Address with Terminal Commands
date: 2024-06-25T11:26:01.904Z
updated: 2024-06-26T11:26:01.904Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling PC's Global IP Address with Terminal Commands
excerpt: This Article Describes Unveiling PC's Global IP Address with Terminal Commands
keywords: Global IP Uncovering,Terminal Command Guide,IP Address Exposure,Access PC Internally,Terminal Network Diagnostics,Find PC's IP Quickly,Locate IP Via Terminal
thumbnail: https://thmb.techidaily.com/e4680a85088d1a2f44c589b1c74f41a831760d9eaf6ae422f8b959a2a9262d12.jpg
---

## Unveiling PC's Global IP Address with Terminal Commands

 A computer or any device connected to the Internet has two types of IP addresses necessary to communicate. Each Internet-enabled device comes with a private IP address, whereas a public IP address, also known as the external IP address, is provided by your Internet Service Provider (ISP).

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

## How to Check Your Private IP Address on Windows

![command prompt ipconfig private ip address](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-ipconfig-private-ip-address.jpg)

 Windows offers multiple ways to view your network information, including the IP address. For instance, you can easily [check your IP address from the Settings app](https://www.makeuseof.com/tag/find-ip-address-windows-10/). You can also use the Network and Sharing Center in Control Panel or dig a little bit in the Task Manager’s Performance tab to access your system’s network details.

 But if you would rather skip multiple clicks and are comfortable with Command Prompt, the ipconfig (Internet Protocol configuration) command is all you need. It is easy to remember and shows more information quickly than the Settings app.

 Follow these steps to get your Private IP address using Command Prompt:

1. Press the **Win** key, and type **cmd**. From the search result, click on **Command Prompt**.
2. Next, type the following command in the Command Prompt window and press Enter:  
`ipconfig`
3. The output will display a host of network information. Look for the IPv4 address for your Ethernet or Wireless LAN adapter to identify your private IP address.
4. If you need complete information, including NetBIOS over TCPIP, DHCP status, and Physical IP address, use the following command instead:  
`Ipconfig /all`
5. You’ll likely see multiple network adapter entries with unique IP addresses. This is usually due to your computer having multiple network adapters, including Ethernet, Wireless LAN, and vEthernet switches.

 If you need to share the output for troubleshooting purposes, you can export the output to a text file. In Command Prompt, run **ipconfig > NetworkInfo.txt** to save the output to a **NetworkInfo.text** file. By default, it is saved to the **C:\\Users\\Username** directory.

## How to Get Your Public IP Address on Windows

![Command Prompt running Curl command showing Public IP Address on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-public-ip-address-curl.jpg)

 Unlike the private IP address, the **ipconfig** command cannot retrieve the public IP address of your ISP. Instead, you’ll need to [use the curl command-line utility to make HTTP requests](https://www.makeuseof.com/curl-how-make-http-requests/) using a third-party service, like ifconfig.me, to obtain IP address mapping information.

 The newer versions of the OS, Windows 10 and 11, come with the curl utility built-in. If you are using an older version, you may need to install curl for Windows to run the utility.

 Follow these steps to get the public IP address using Command Prompt:

1. Press **Win + R**, type **cmd** and click **OK** to [open Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/)
2. Type the following command in the Command Prompt window and press Enter:  
`curl ifconfig.me`
3. The above command sends an HTTP request to the **ifconfig.me** server, which returns your public IP address information. Similarly, you can visit the **ifconfig.me** URL using your web browser to view your public IP address.
4. That said, if the **ifconfig.me** command doesn’t return a public IPv6 address, use the following command instead:  
`nslookup myip.opendns.com resolver1.opendns.com`
5. The above command uses the **nslookup** command-line utility to retrieve your public IP address using the OpenDNS service. Your public IPv6 address will look something like this 2401:\*\*00:1c08:55f0:594b:cdbe:\*\*\*\*.\*\*\*\*.

 If you check your public IPv6 address again after a few hours or days—depending on the router's configuration—you may notice a different IPv6 address. Due to privacy concerns, your router dynamically assigns and changes the IPv6 address for all connected devices.

## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)

 If you prefer a more intuitive experience, you can use online web services that can provide information on your network configuration. These services can also detect the ISP location and other information, including the user agent.

 Online services to view public IP addresses:

* **[WhatIsMyIP](https://www.whatismyip.com/)**: A simple and intuitive web service to view your public IPv4 and IPv6 addresses. In addition, it also shows your ISP’s location and name.
* [**My External IP**](https://myexternalip.com/): A barebone web app that can detect your public IPv4 address and Port.
* **Use a search engine**: If you don’t want to remember another website to do basic stuff, try your search engine. Type “What’s my IP” in Google or Bing search to get your public IPv4/IPv6 address quickly.

## Many Ways to Check Your Public IP Address on Windows

 Whether you want to perform remote access or set up a gaming server, you may need to share your public IP address to allow others to connect to your network. Fortunately, plenty of web services allow you to check your network details using Command Prompt and online tools.

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/top-notch-windows-11-skins-no-one-knows/"><u>Top-Notch Windows 11 Skins No One Knows</u></a></li>
<li><a href="https://win11.techidaily.com/1719338109987-windows-desk-icons-clashing-find-harmony/"><u>Windows Desk Icons Clashing - Find Harmony</u></a></li>
<li><a href="https://win11.techidaily.com/sleight-of-keyboard-how-to-make-keys-unseen/"><u>Sleight of Keyboard: How to Make Keys Unseen</u></a></li>
<li><a href="https://win11.techidaily.com/solving-win-error-no-access-to-network-paths/"><u>Solving WIN Error: No Access to Network Paths</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-directory-is-not-empty-error-0x80070091-in-windows-11-and-11/"><u>How to Fix the “Directory Is Not Empty” Error 0X80070091 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-tackle-zeroxc000003e-application-errors-in-win1011/"><u>Strategies to Tackle ZeroXc000003e Application Errors in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdles-of-reverting-folders-to-read-only/"><u>Overcoming the Hurdles of Reverting Folders to Read-Only</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-avoid-bots-manual-linking-between-spotify-and-discord-works/"><u>In 2024, Avoid Bots? Manual Linking Between Spotify & Discord Works</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-elevate-your-footage-expert-advice-for-stunning-home-videos-for-2024/"><u>Updated Elevate Your Footage Expert Advice for Stunning Home Videos for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-ideal-equipment-for-animation-photography/"><u>[Updated] In 2024, Ideal Equipment for Animation Photography</u></a></li>
<li><a href="https://audio-editing.techidaily.com/beatmaking-breakdown-top-8-digital-audio-workstations-daws-for-mac-and-pc-enthusiasts-for-2024/"><u>Beatmaking Breakdown Top 8 Digital Audio Workstations (DAWs) For Mac & PC Enthusiasts for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/pictorial-chuckles-kapwings-memetic-composer-for-2024/"><u>Pictorial Chuckles  Kapwing’s Memetic Composer for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-xiaomi-14-pro-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Xiaomi 14 Pro Phone that is Locked?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-enhance-imagery-with-elegant-borders-ig-edition/"><u>In 2024, Enhance Imagery with Elegant Borders – IG Edition</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-unlock-tiktok-secrets-with-top-7-emojis-list/"><u>[Updated] In 2024, Unlock TikTok Secrets with Top 7 Emojis List</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>