---
title: "Command Prompt Wizardry: Unmasking Your IP"
date: 2024-06-25T10:30:25.798Z
updated: 2024-06-26T10:30:25.798Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Command Prompt Wizardry: Unmasking Your IP"
excerpt: "This Article Describes Command Prompt Wizardry: Unmasking Your IP"
keywords: IP Unveil Secrets,Command IP Hack,Dissect IP Address,Uncover IP Details,Master IP Exposure,Decode IP Info,Reveal IP Mystery
thumbnail: https://thmb.techidaily.com/fe142fc722967440c0a67173b1e546447bf0e801339eadf58291eb4451fb4b01.jpg
---

## Command Prompt Wizardry: Unmasking Your IP

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
<li><a href="https://win11.techidaily.com/how-to-fix-a-yellow-tint-on-a-windows-laptop-screen/"><u>How to Fix a Yellow Tint on a Windows Laptop Screen</u></a></li>
<li><a href="https://win11.techidaily.com/craft-command-capabilities-for-the-windowed-world/"><u>Craft Command Capabilities for the Windowed World</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-wasteful-usage-by-core-system-processes/"><u>Reducing Wasteful Usage by Core System Processes</u></a></li>
<li><a href="https://win11.techidaily.com/explaining-and-correcting-the-msvcr110dll-deficit/"><u>Explaining & Correcting the msvcr110.dll Deficit</u></a></li>
<li><a href="https://win11.techidaily.com/from-iphone-to-desktop-syncing-ios-calendar-with-windows-1011/"><u>From iPhone to Desktop: Syncing iOS Calendar with Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/a-simple-guide-to-mouse-customization-for-better-trail-control/"><u>A Simple Guide to Mouse Customization for Better Trail Control</u></a></li>
<li><a href="https://win11.techidaily.com/new-horizons-for-windows-11-widgets-a-comprehensive-list-of-enhancements/"><u>New Horizons for Windows 11 Widgets: A Comprehensive List of Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-straighten-out-window-corners/"><u>How to Straighten Out Window Corners</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-user-administration-in-windows-11/"><u>Streamlining User Administration in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-broken-usb-connections-on-windows-systems/"><u>Tackling Broken USB Connections on Windows Systems</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-clip-narration-devisee-for-2024/"><u>[New] Clip Narration Devisee for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-samsung-galaxy-a05-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Samsung Galaxy A05 for Streaming | Dr.fone</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-revealing-the-best-of-both-worlds-1-tiktoks-on-twitter/"><u>[Updated] Revealing the Best of Both Worlds  #1 TikToks on Twitter</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/fiendish-funny-factory-for-2024/"><u>Fiendish Funny Factory for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-mastering-pinterest-videos-to-mp3s-essential-strategies/"><u>[Updated] Mastering Pinterest Videos to MP3s  Essential Strategies</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-preferred-practices-for-streaming-video-recording-on-youtube/"><u>[New] In 2024, Preferred Practices for Streaming Video Recording on YouTube</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713965867335-updated-what-is-lumetri-color-and-how-do-you-use-it-in-adobe-after-effects-find-out-the-numerous-functions-of-lumetri-panel-and-ways-to-apply-them-to-your-v/"><u>Updated What Is Lumetri Color and How Do You Use It in Adobe After Effects? Find Out the Numerous Functions of Lumetri Panel and Ways to Apply Them to Your Video for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/social-media-connectivity-embedding-live-streams-from-twitch-to-fb/"><u>Social Media Connectivity  Embedding Live Streams From Twitch to FB</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-vivo-y17s-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-transform-your-webcam-footage-edit-and-export-tips/"><u>[New] 2024 Approved  Transform Your WebCam Footage  Edit & Export Tips</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>