---
title: "Command Prompt Wizardry: Unmasking Your IP"
date: 2024-06-25T11:37:49.874Z
updated: 2024-06-26T11:37:49.874Z
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
<li><a href="https://win11.techidaily.com/avoiding-slow-icon-loading-with-cache-refresh/"><u>Avoiding Slow Icon Loading with Cache Refresh</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-win-troubleshooting-toolkit/"><u>The Ultimate Win Troubleshooting Toolkit</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-resolving-windows-update-defeat-error-0x800736cc/"><u>Swiftly Resolving Windows Update: Defeat Error 0X800736CC</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-rectify-ge-share-function-failures/"><u>Guide to Rectify GE Share Function Failures</u></a></li>
<li><a href="https://win11.techidaily.com/win11-error-fixer-correcting-code-0x0000011b/"><u>Win11 Error Fixer: Correcting Code 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/winning-cars-mouse-keys-and-acceleration-mastery/"><u>Winning Cars: Mouse, Keys, and Acceleration Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/top-benefits-of-windows-11-overtaking-macos/"><u>Top Benefits of Windows 11 Overtaking macOS</u></a></li>
<li><a href="https://win11.techidaily.com/smoothly-switching-programs-for-your-first-win-11-experience/"><u>Smoothly Switching Programs for Your First Win 11 Experience</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-from-basic-to-breathtaking-crafting-top-tier-tiktok-videos-using-templates/"><u>In 2024, From Basic to Breathtaking  Crafting Top-Tier TikTok Videos Using Templates</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-poco-x6-pro-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Poco X6 Pro Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-in-2024-your-first-guide-to-iphone-audio-transformation-voice-changer-plus-explained/"><u>New In 2024, Your First Guide to iPhone Audio Transformation Voice Changer Plus Explained</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/flexibility-in-viewing-with-youtube-tv-options/"><u>Flexibility in Viewing with YouTube TV Options</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-ways-to-get-the-most-up-to-date-cartoon-character-design-tips/"><u>New Ways to Get the Most up to Date Cartoon Character Design Tips</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-comprehensively-ranking-free-screen-capture-tools-2023-for-2024/"><u>[New] Comprehensively Ranking Free Screen Capture Tools 2023 for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-amazon-prime-and-tweet-fandom-most-appreciated-videos-2023/"><u>[Updated] 2024 Approved  Amazon Prime and Tweet Fandom - Most Appreciated Videos, 2023</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-9-free-online-tools-to-make-your-own-movies-for-2024/"><u>Updated 9 Free Online Tools to Make Your Own Movies for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-peering-into-popularity-instagram-analytics-for-you-for-2024/"><u>[Updated] Peering Into Popularity  Instagram Analytics for You for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>