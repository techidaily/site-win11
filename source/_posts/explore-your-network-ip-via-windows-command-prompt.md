---
title: Explore Your Network IP via Windows Command Prompt
date: 2024-12-21T17:44:29.993Z
updated: 2024-12-22T16:07:49.061Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Explore Your Network IP via Windows Command Prompt
excerpt: This Article Describes Explore Your Network IP via Windows Command Prompt
keywords: Find IP Address Windows Command,Navigate Network IP Windows,Command Prompt IP Lookup,Locate Computer IP Terminal,Discover Hostname Command,Inspect System IP Cmd,View PC IP Directly Window
thumbnail: https://thmb.techidaily.com/d2538de48c05d03d5115f0d6f4197d40a4705facf7c78bd0835d847acacb8649.jpg
---

## Explore Your Network IP via Windows Command Prompt

 A computer or any device connected to the Internet has two types of IP addresses necessary to communicate. Each Internet-enabled device comes with a private IP address, whereas a public IP address, also known as the external IP address, is provided by your Internet Service Provider (ISP).

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Check Your Private IP Address on Windows

![command prompt ipconfig private ip address](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-ipconfig-private-ip-address.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OdlXe5RELW0?si=Iz1H1QnLQVw-Eu3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Get Your Public IP Address on Windows

![Command Prompt running Curl command showing Public IP Address on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/command-prompt-public-ip-address-curl.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you prefer a more intuitive experience, you can use online web services that can provide information on your network configuration. These services can also detect the ISP location and other information, including the user agent.

 Online services to view public IP addresses:

* **[WhatIsMyIP](https://www.whatismyip.com/)**: A simple and intuitive web service to view your public IPv4 and IPv6 addresses. In addition, it also shows your ISP’s location and name.
* [**My External IP**](https://myexternalip.com/): A barebone web app that can detect your public IPv4 address and Port.
* **Use a search engine**: If you don’t want to remember another website to do basic stuff, try your search engine. Type “What’s my IP” in Google or Bing search to get your public IPv4/IPv6 address quickly.

## Many Ways to Check Your Public IP Address on Windows

 Whether you want to perform remote access or set up a gaming server, you may need to share your public IP address to allow others to connect to your network. Fortunately, plenty of web services allow you to check your network details using Command Prompt and online tools.

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-interactive-instagram-flipbook-feature/"><u>[New] 2024 Approved Interactive Instagram Flipbook Feature</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-youtubes-best-10-cutting-edge-reaction-ideas/"><u>[New] 2024 Approved YouTube's Best 10 Cutting-Edge Reaction Ideas</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-selecting-superior-webcams-on-windows-10/"><u>[New] Selecting Superior Webcams on Windows 10</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-sound-identity-shift-for-free-fire-characters-no-money-required/"><u>[Updated] Sound Identity Shift for Free Fire Characters - No Money Required</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-eye-catching-narrative-starter-gadget/"><u>2024 Approved Eye-Catching Narrative Starter Gadget</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-streamline-your-media-files-8-pro-convertors-sub-to-srt-style/"><u>2024 Approved Streamline Your Media Files 8 Pro Convertors, Sub to Srt Style</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/chatgpts-my-bot-a-new-era-of-board-game-strategy-and-image-making/"><u>ChatGPT's My Bot: A New Era of Board Game Strategy and Image Making</u></a></li>
<li><a href="https://win11.techidaily.com/diagnose-and-rectify-absent-devices-in-dm/"><u>Diagnose & Rectify Absent Devices In DM</u></a></li>
<li><a href="https://win11.techidaily.com/driving-income-from-windows-11-at-microsoft/"><u>Driving Income From Windows 11 at Microsoft</u></a></li>
<li><a href="https://win11.techidaily.com/embark-on-gesture-driven-navigation-within-microsoft-edge-windows-11/"><u>Embark on Gesture-Driven Navigation Within Microsoft Edge, Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-personalize-your-windowed-terminal-environment/"><u>How To Personalize Your Windowed Terminal Environment</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-circulation-of-playlists-on-youtube/"><u>Swift Circulation of Playlists on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-wintoys-leveraging-windows-capabilities/"><u>The Essential Guide to 'WinToys': Leveraging Windows Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-harnessing-the-strength-of-windows-11s-auto-hdr/"><u>Understanding and Harnessing the Strength of Windows 11'S Auto HDR</u></a></li>
<li><a href="https://win11.techidaily.com/win-the-battle-of-content-top-8-videography-tools-unveiled/"><u>Win the Battle of Content - Top 8 Videography Tools Unveiled</u></a></li>
</ul></div>

