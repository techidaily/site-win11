---
title: Windows 10/11 Command Guide for IP Location
date: 2024-11-01T19:23:44.177Z
updated: 2024-11-07T22:27:19.370Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Windows 10/11 Command Guide for IP Location
excerpt: This Article Describes Windows 10/11 Command Guide for IP Location
keywords: Windows OS Locale Guides,PC IP Addressing Guide,Windows Latitude Control,Command Line Network Tools,Device Geo-Location Tutorial,Navigate System Settings,Command Prompt Geo Info
thumbnail: https://thmb.techidaily.com/290fdfbe7988bc73a9658535e5e89697be7bda898900fabab3b9425630194609.jpg
---

## Windows 10/11 Command Guide for IP Location

 A computer or any device connected to the Internet has two types of IP addresses necessary to communicate. Each Internet-enabled device comes with a private IP address, whereas a public IP address, also known as the external IP address, is provided by your Internet Service Provider (ISP).

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528693/16446" target="_top" id="1528693">
  <img src="//a.impactradius-go.com/display-ad/16446-1528693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528693/16446" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896555/19272" target="_top" id="1896555">
  <img src="//a.impactradius-go.com/display-ad/19272-1896555" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896555/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Online Tools to Get Your Public IP Address

![whatismyip online public ip address tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/whatismyip-online-public-ip-address-tool.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you prefer a more intuitive experience, you can use online web services that can provide information on your network configuration. These services can also detect the ISP location and other information, including the user agent.

 Online services to view public IP addresses:

* **[WhatIsMyIP](https://www.whatismyip.com/)**: A simple and intuitive web service to view your public IPv4 and IPv6 addresses. In addition, it also shows your ISP’s location and name.
* [**My External IP**](https://myexternalip.com/): A barebone web app that can detect your public IPv4 address and Port.
* **Use a search engine**: If you don’t want to remember another website to do basic stuff, try your search engine. Type “What’s my IP” in Google or Bing search to get your public IPv4/IPv6 address quickly.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1061528/11832" target="_top" id="1061528">
  <img src="//a.impactradius-go.com/display-ad/11832-1061528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1061528/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Many Ways to Check Your Public IP Address on Windows

 Whether you want to perform remote access or set up a gaming server, you may need to share your public IP address to allow others to connect to your network. Fortunately, plenty of web services allow you to check your network details using Command Prompt and online tools.

 While checking your private IP address is easy, knowing your public IP address can be necessary for many tasks, including remote access, server hosting, network troubleshooting, and geolocation services. Here we show you a few ways to retrieve your public IPv4/IPv6 information on Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-diy-digital-storytelling-making-moving-pictures-on-your-smartphone/"><u>[Updated] 2024 Approved DIY Digital Storytelling Making Moving Pictures on Your Smartphone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-laughter-logic-lab/"><u>[Updated] 2024 Approved Laughter Logic Lab</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-optimal-list-of-10-excellent-spotify-audio-recorders/"><u>[Updated] 2024 Approved Optimal List of 10 Excellent Spotify Audio Recorders</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-top-video-resolution-converter-for-desktop-or-online-for-2024/"><u>[Updated] Top Video Resolution Converter for Desktop or Online for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-a-detailed-review-of-the-top-10-gopro-protectors/"><u>2024 Approved A Detailed Review of the Top 10 GoPro Protectors</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ing-up-opaque-video-views-on-youtube-for-2024/"><u>Clearing Up Opaque Video Views on YouTube for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-reconnection-strategies-for-your-disconnected-ps4-remote/"><u>Immediate Reconnection Strategies for Your Disconnected PS4 Remote</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-the-podcasters-guide-to-high-quality-home-recordings/"><u>In 2024, The Podcaster’s Guide to High-Quality Home Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/is-the-task-scheduler-not-working-on-windows-try-these-fixes/"><u>Is the Task Scheduler Not Working on Windows? Try These Fixes</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-unlock-vertical-video-potential-top-editing-apps-for-mobile/"><u>New 2024 Approved Unlock Vertical Video Potential Top Editing Apps for Mobile</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-corporate-browser-management-hurdles-in-chrome-and-edge/"><u>Overcoming Corporate Browser Management Hurdles in Chrome and Edge</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-premature-edges-a-11-way-guide/"><u>Preventing Premature Edges: A 11-Way Guide</u></a></li>
<li><a href="https://win11.techidaily.com/reinstate-the-missing-search-tool-for-task-management-in-windows-11/"><u>Reinstate the Missing Search Tool for Task Management in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/rescue-frozen-menu-items-on-pc-6-proven-methods/"><u>Rescue Frozen Menu Items on PC – 6 Proven Methods</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-unauthorized-installer-errors-in-win11win10/"><u>Resolving Unauthorized Installer Errors in Win11/Win10</u></a></li>
<li><a href="https://some-guidance.techidaily.com/streamline-your-images-in-canva-without-clutter-for-2024/"><u>Streamline Your Images in Canva Without Clutter for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-text-display-eliminating-html-from-your-windows-11s-mail-app/"><u>Streamlining Text Display: Eliminating HTML From Your Windows 11'S Mail App</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    