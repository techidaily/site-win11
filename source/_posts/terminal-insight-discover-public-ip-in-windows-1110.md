---
title: "Terminal Insight: Discover Public IP in Windows 11/10"
date: 2024-06-25T11:31:13.070Z
updated: 2024-06-26T11:31:13.070Z
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
<li><a href="https://win11.techidaily.com/solutions-for-slashing-dropbox-cpu-load-on-windows-devices/"><u>Solutions for Slashing Dropbox CPU Load on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-protection-enable-windows-11s-controlling-access/"><u>Setting Up Protection: Enable Windows 11’S Controlling Access</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-connectivity-issues-with-spotify-and-windows-11/"><u>Unraveling Connectivity Issues with Spotify & Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/usb-wi-fi-anomalies-on-windows-heres-the-solution-guide-you-need/"><u>USB Wi-Fi Anomalies on Windows? Here's the Solution Guide You Need</u></a></li>
<li><a href="https://win11.techidaily.com/organize-like-a-pro-5-must-try-windows-folder-tricks/"><u>Organize Like a Pro: 5 Must-Try Windows Folder Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/instituting-new-pdf-reader-as-standard/"><u>Instituting New PDF Reader as Standard</u></a></li>
<li><a href="https://win11.techidaily.com/1719302930005-bypass-incompatibility-woes-in-windows-xp-7-and-8-easily/"><u>Bypass Incompatibility Woes in Windows XP, 7 & 8 Easily.</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-touchpad-gestures-on-windows/"><u>Troubleshooting Non-Responsive Touchpad Gestures on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-app-changes-in-the-latest-windows-11-update/"><u>Navigating App Changes in the Latest Windows 11 Update</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-choosing-the-right-partners-for-a-safer-tiktok-expansion/"><u>[New] Choosing the Right Partners for a Safer TikTok Expansion</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-demystifying-creative-commons-and-its-legalities/"><u>[New] 2024 Approved  Demystifying Creative Commons and Its Legalities</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-animatedapp-full-guide-24-edition/"><u>[Updated] AnimatedApp Full Guide '24 Edition</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/expert-guide-to-shooting-awe-inspiring-igtv-content-on-mobile-and-dslrs/"><u>Expert Guide to Shooting Awe-Inspiring IGTV Content on Mobile & DSLRs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-resolve-instagram-video-glitches-today-for-2024/"><u>[Updated] Resolve Instagram Video Glitches Today for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-the-art-of-sound-exploring-tiktoks-voice-customization-features-for-2024/"><u>[New] The Art of Sound  Exploring TikTok's Voice Customization Features for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-essential-steps-to-upload-tiktok-content-on-chrome-os-for-2024/"><u>[New] Essential Steps to Upload TikTok Content on Chrome OS for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-easily-capturing-iphone-screens-on-the-go/"><u>In 2024, Easily Capturing iPhone Screens on the Go</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-data-from-motorola-moto-g73-5g-by-fonelab-android-recover-data/"><u>The way to get back lost data from Motorola Moto G73 5G</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-ways-on-how-to-unlockbypassswiperemove-itel-a60s-fingerprint-lock-by-drfone-android/"><u>In 2024, Best Ways on How to Unlock/Bypass/Swipe/Remove Itel A60s Fingerprint Lock</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>