---
title: "Discover Your IP: Command Prompt Guide for PCs"
date: 2024-06-25T10:03:58.752Z
updated: 2024-06-26T10:03:58.752Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Discover Your IP: Command Prompt Guide for PCs"
excerpt: "This Article Describes Discover Your IP: Command Prompt Guide for PCs"
keywords: PC Command Line Tutorial,Windows PowerShell Basics,Networking with IP Tools,PC Command Prompt Utility,Enhance System Control,Troubleshoot via Terminal,Master Computer Commands
thumbnail: https://thmb.techidaily.com/d66a628fa0cf48140c10b181f20d8c3673ed432efe3b9eaa0c987c81fd05af8c.jpg
---

## Discover Your IP: Command Prompt Guide for PCs

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
<li><a href="https://win11.techidaily.com/essentials-for-enabling-win11-on-5ghz-networks-effortlessly/"><u>Essentials for Enabling Win11 on 5GHz Networks Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-office-hours-the-top-5-task-boosting-tools-for-win-11/"><u>Elevate Your Office Hours: The Top 5 Task-Boosting Tools for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-windows-update-error-0x8024800c/"><u>Solutions for Windows Update Error 0X8024800C</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-compatibility-with-photoshop/"><u>Steps to Overcome Windows Compatibility with Photoshop</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-windows-photography-errors/"><u>Mastering the Art of Fixing Windows Photography Errors</u></a></li>
<li><a href="https://win11.techidaily.com/7-strategies-to-rectify-chromes-profile-problems-on-desktop/"><u>7 Strategies to Rectify Chrome's Profile Problems on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-media-player-disruptions/"><u>Overcoming Windows Media Player Disruptions</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-exploring-the-frontier-combining-images-with-soundscapes-2utopia-tech-review-2023/"><u>Updated 2024 Approved Exploring the Frontier Combining Images with Soundscapes 2Utopia Tech Review, 2023</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-lost-video-steps-to-fix-sony-a6400-problem/"><u>In 2024, Lost Video  Steps to Fix Sony A6400 Problem</u></a></li>
<li><a href="https://location-social.techidaily.com/does-apple-iphone-6s-plus-have-find-my-friends-drfone-by-drfone-virtual-ios/"><u>Does Apple iPhone 6s Plus Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-captivate-audiences-from-day-one/"><u>2024 Approved  Captivate Audiences From Day One</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/seek-out-all-shared-media-on-messenger-platform/"><u>Seek Out All Shared Media on Messenger Platform</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-comparative-study-vidma-vs-other-screen-recorders-for-2024/"><u>[New] Comparative Study  Vidma vs Other Screen Recorders for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-ai-features-of-wondershare-filmora-silence-detection-in-videos-for-2024/"><u>New AI Features of Wondershare Filmora - Silence Detection in Videos for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-note-30-vip-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Infinix Note 30 VIP Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-guidance-instagram-ringtone-download-and-make-instagram-ringtone-on-your-own/"><u>2024 Approved  Guidance  Instagram Ringtone Download and Make Instagram Ringtone on Your Own</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>