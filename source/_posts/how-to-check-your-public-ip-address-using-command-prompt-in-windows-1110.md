---
title: How to Check Your Public IP Address Using Command Prompt in Windows 11/10
date: 2024-06-25T11:38:59.349Z
updated: 2024-06-26T11:38:59.349Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Check Your Public IP Address Using Command Prompt in Windows 11/10
excerpt: This Article Describes How to Check Your Public IP Address Using Command Prompt in Windows 11/10
keywords: Find Public IP,IP Address Lookup,Command Line IP Viewing,Check Windows IP Address,Discover System Public IP,Windows IP Command Guide,Locate Default Windows IP
thumbnail: https://thmb.techidaily.com/f65801f01aff4d3373b4cf2db5d1bc7ed704b50a070459838ec79267fdebcd19.jpg
---

## How to Check Your Public IP Address Using Command Prompt in Windows 11/10

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
<li><a href="https://win11.techidaily.com/strategies-to-resolve-windows-high-dpi-screen-scaling/"><u>Strategies to Resolve Windows High DPI Screen Scaling</u></a></li>
<li><a href="https://win11.techidaily.com/secret-start-screen-tactics-vanish-power-buttons-from-windows-11/"><u>Secret Start Screen Tactics: Vanish Power Buttons From Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/minimizing-edges-process-count-in-windows/"><u>Minimizing Edge's Process Count in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/declutter-your-computer-finding-and-purging-windows-empties/"><u>Declutter Your Computer: Finding & Purging Windows' Empties</u></a></li>
<li><a href="https://win11.techidaily.com/effective-techniques-to-combat-dxgi-errors/"><u>Effective Techniques to Combat DXGI Errors</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolving-common-windows-os-issues/"><u>Quick Guide to Resolving Common Windows OS Issues</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-win11-startup-options-a-comprehensive-guide/"><u>Navigating Win11 Startup Options: A Comprehensive Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/subtitle-mastery-made-easy-10-free-online-tools-for-2024/"><u>Subtitle Mastery Made Easy - 10 Free Online Tools for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-best-vlc-trimming-software-for-mac-no-quality-loss-guaranteed-for-2024/"><u>Updated Best VLC Trimming Software for Mac No Quality Loss Guaranteed for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/laugh-ledger-noteworthy-personalities-in-tiktok-for-2024/"><u>Laugh Ledger  Noteworthy Personalities in TikTok for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-mastering-slow-motion-on-kapwing-tips-and-tricks-for-amazing-videos/"><u>Updated Mastering Slow Motion on Kapwing Tips and Tricks for Amazing Videos</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-t2x-5g-without-password-by-drfone-android-unlock-android-unlock/"><u>How to Unlock T2x 5G Without Password?</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-meizu-21-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-navigating-instagram-the-essential-guide-to-mastering-reels/"><u>2024 Approved  Navigating Instagram  The Essential Guide to Mastering Reels</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-androidios-tiktok-editing-winners/"><u>[Updated] 2024 Approved  Android/iOS TikTok Editing Winners</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>