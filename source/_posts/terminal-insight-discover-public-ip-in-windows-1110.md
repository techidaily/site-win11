---
title: "Terminal Insight: Discover Public IP in Windows 11/10"
date: 2024-06-25T10:10:08.602Z
updated: 2024-06-26T10:10:08.602Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Terminal Insight: Discover Public IP in Windows 11/10"
excerpt: "This Article Describes Terminal Insight: Discover Public IP in Windows 11/10"
keywords: Window Public IP,IP Windows OS,Windows 11 IP,Windows 10 IP,Insight Public IP,Terminal IP View,Discovering Windows IP
thumbnail: https://thmb.techidaily.com/fb708f6b02bb2770894398e8943ab9eb4326fec35c13c96d34e093f48763187e.jpg
---

## Terminal Insight: Discover Public IP in Windows 11/10

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
<li><a href="https://win11.techidaily.com/restoring-windows-services-command-line-tool-with-these-7-steps/"><u>Restoring Window's Services Command Line Tool with These 7 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-experience-with-these-ultimate-strategies-for-win-11/"><u>Elevate Your Gaming Experience with These Ultimate Strategies for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/surges-subdued-mastering-the-art-of-cpu-management-in-rm/"><u>Surges Subdued: Mastering the Art of CPU Management in RM</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-reverse-error-code-0x80780119-in-windows/"><u>Guide to Reverse Error Code 0X80780119 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-tasks-with-the-magic-of-flow-launcher/"><u>Supercharge Your Tasks with the Magic of Flow Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/windows-adjusting-user-permissions-for-regular-accounts/"><u>Windows: Adjusting User Permissions for Regular Accounts</u></a></li>
<li><a href="https://win11.techidaily.com/equalize-internet-pace-syncing-laptop-and-mobile-phones/"><u>Equalize Internet Pace: Syncing Laptop & Mobile Phones</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-failure-codes-0x80072f8f/"><u>Addressing Windows Failure Codes: 0X80072f8f</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-nokia-c32-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from Nokia C32 Devices</u></a></li>
<li><a href="https://extra-hints.techidaily.com/initial-steps-to-professional-motion-graphics/"><u>Initial Steps to Professional Motion Graphics</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-premier-windows-podcast-platforms-top-8-recommendations/"><u>[Updated] Premier Windows Podcast Platforms  Top 8 Recommendations</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-changeadd-location-filters-on-snapchat-for-your-gionee-f3-pro-drfone-by-drfone-virtual-android/"><u>How to Change/Add Location Filters on Snapchat For your Gionee F3 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-professional-approaches-for-logging-youtube-streams/"><u>2024 Approved  Professional Approaches for Logging YouTube Streams</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-from-apple-iphone-13-mini-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email From Apple iPhone 13 mini? Heres the Best Fixes</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-cutting-edge-audio-editing-with-sony-vegas-pro-complete-guide/"><u>New Cutting Edge Audio Editing with Sony Vegas Pro – Complete Guide</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-make-your-text-glow-10-best-neon-text-generators-online-updated-2023/"><u>In 2024, Make Your Text Glow 10 Best Neon Text Generators Online (Updated 2023)</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-xiaomi-redmi-note-12-5g-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Xiaomi Redmi Note 12 5G is off? | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>