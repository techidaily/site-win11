---
title: Navigate to Public IP Using Windows Command Window
date: 2024-07-13T10:48:31.287Z
updated: 2024-07-14T10:48:31.287Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigate to Public IP Using Windows Command Window
excerpt: This Article Describes Navigate to Public IP Using Windows Command Window
keywords: Find Windows IP Address,Public Windows IP Locator,Command Window IP Checker,Windows IP Reverse Lookup,Accessing External IP (Windows),Display Public IP via CMD,Windows Network Explorer IP
thumbnail: https://thmb.techidaily.com/c6f194696eb0c1816baa0ea6eee51fe354f8a71c5648179d5bd043f05b446b5b.jpg
---

## Navigate to Public IP Using Windows Command Window

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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-motorola-edge-40-neo-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Motorola Edge 40 Neo Screen | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-signal-failures-windows-steam-fix-guide/"><u>Addressing Signal Failures: Windows Steam Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/trimming-down-excessive-ntoskrnlexe-utilization/"><u>Trimming Down Excessive Ntoskrnl.exe Utilization</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/splice-video-editor-a-must-have-for-mac-users-for-2024/"><u>Splice Video Editor A Must-Have for Mac Users for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-mastering-macos-producing-high-quality-ootd-tiktoks/"><u>[New] Mastering MacOS  Producing High-Quality OOTD TikToks</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-daily-deeds-for-digital-diaries-tips-on-virtual-journeys/"><u>[New] In 2024, Daily Deeds for Digital Diaries  Tips on Virtual Journeys</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/step-into-stardom-building-starry-eyed-tiktok-dances-on-macos/"><u>Step Into Stardom  Building Starry-Eyed TikTok Dances on MacOS</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-performance-trimming-high-memorycpu-usage-by-news-and-interests-apps-on-windows/"><u>Boosting Performance: Trimming High Memory/CPU Usage by News & Interests Apps on Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-is-av1-really-outdo-cooking-vp9/"><u>2024 Approved  Is AV1 Really Outdo Cooking VP9?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-10-best-3ds-emulator-you-can-find-on-pc-for-2024/"><u>[Updated] 10 Best 3Ds Emulator You Can Find on PC for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-obtain-high-quality-photos-without-watermarks/"><u>2024 Approved  Obtain High-Quality Photos Without Watermarks</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-dive-into-sound-design-an-overview-of-fundamental-wave-editor-features-for-2024/"><u>Updated Dive Into Sound Design An Overview of Fundamental Wave Editor Features for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-tunemaster-pro-how-to-download-and-assess/"><u>[New] TuneMaster Pro  How to Download & Assess</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-top-5-android-clippers-essential-image-editing-apps/"><u>[New] Top 5 Android Clippers  Essential Image Editing Apps</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-exemplary-audio-enhancing-programs-for-youtube-artists/"><u>[Updated] In 2024, Exemplary Audio-Enhancing Programs for YouTube Artists</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-h2-update-rolls-out-more-options/"><u>Windows 11 H2 Update Rolls Out More Options</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/revolutionize-your-console-proven-strategies-for-clear-gaming-recordings/"><u>Revolutionize Your Console  Proven Strategies for Clear Gaming Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-recovery-mode-on-microsoft-devices/"><u>Accessing Recovery Mode on Microsoft Devices</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-addressing-system-call-failed-on-pcs/"><u>Best Practices for Addressing System Call Failed on PCs</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-data-from-iphone-6s-using-stellar-data-recovery-for-iphone-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted Data from iPhone 6s using Stellar Data Recovery for iPhone? | Stellar</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-risks-of-keygen-malware-in-modern-windows-systems/"><u>Understanding the Risks of Keygen Malware in Modern Windows Systems</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-unlock-the-secret-to-insta-cash-with-our-guidebook/"><u>2024 Approved  Unlock the Secret to Insta Cash with Our Guidebook</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-storage-windows-1011-automatic-file-deletion/"><u>Streamlining Storage: Windows 10/11 Automatic File Deletion</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-effortless-4k-video-editing-top-proxy-editing-apps-for-creators-for-2024/"><u>New Effortless 4K Video Editing Top Proxy Editing Apps for Creators for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-value-in-vcplusplus-release-packages/"><u>Unlocking the Value in VC++ Release Packages</u></a></li>
<li><a href="https://apple-account.techidaily.com/the-easy-way-to-remove-an-apple-id-from-your-macbook-for-your-iphone-14-pro-max-by-drfone-ios/"><u>The Easy Way to Remove an Apple ID from Your MacBook For your iPhone 14 Pro Max</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-code-of-windowsstore-folder-protection/"><u>Breaking the Code of WindowsStore Folder Protection</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-safe-slumber-techniques/"><u>Understanding Window's Safe Slumber Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-video-reset-error-on-windows-systems/"><u>Dealing with Video Reset Error on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-workflow-coloring-without-conflict-on-windows/"><u>Streamlining Your Workflow: Coloring Without Conflict on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-into-your-dormant-device-speakers/"><u>Breathe Life Into Your Dormant Device Speakers</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-apex-legends-mastery-exploring-single-platform-potential-for-2024/"><u>[Updated] Apex Legends Mastery  Exploring Single Platform Potential for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/connect-your-games-across-screens-win-11-and-android-via-google-linkup/"><u>Connect Your Games Across Screens: Win 11 & Android via Google Linkup</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-cutting-edge-tips-for-elite-instagram-image-editing/"><u>[New] Cutting-Edge Tips for Elite Instagram Image Editing</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/best-escape-challenges-top-ten-must-play-rooms-for-2024/"><u>Best Escape Challenges  Top Ten Must-Play Rooms for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-cinematic-crafts-win8/"><u>In 2024, Cinematic Crafts Win8</u></a></li>
<li><a href="https://win11.techidaily.com/boot-time-essentials-configuring-windows-startups/"><u>Boot Time Essentials: Configuring Windows Startups</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-seamless-soundscapes-youtube-music-integration-tips/"><u>In 2024, Seamless Soundscapes  YouTube Music Integration Tips</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-tailoring-the-visual-experience/"><u>Windows Terminal: Tailoring the Visual Experience</u></a></li>
<li><a href="https://win11.techidaily.com/top-6-window-brighter-controls-the-ultimate-guide-for-multiscreen-enthusiasts/"><u>Top 6 Window Brighter Controls: The Ultimate Guide for Multiscreen Enthusiasts</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-to-overcome-windows-lunar-client-launch-problem/"><u>Tactics to Overcome Windows Lunar Client Launch Problem</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dxgi-failures-on-windows-1011/"><u>Addressing DXGI Failures on Windows 10/11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-explore-instagrams-per-video-limit-explained-for-2024/"><u>[New] Explore Instagram's Per-Video Limit Explained for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-risks-ignoring-windows-11-push-notifications/"><u>Understanding Risks: Ignoring Windows 11 Push Notifications</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-resolving-errors-in-windows-installer/"><u>Understanding and Resolving Errors in Windows Installer</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-spotting-active-tcp-connections/"><u>Windows Guide: Spotting Active TCP Connections</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-vivo-y100a-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Vivo Y100A FRP In 3 Different Ways</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-oppo-reno-11f-5g-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Oppo Reno 11F 5G Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-lock-essential-tpm-hacks-for-windows-11/"><u>Bypassing the Lock: Essential TPM Hacks for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-top-windows-11-challenges-with-ease/"><u>Tackling Top Windows 11 Challenges with Ease</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/effortless-snapchat-integration-mac-tips-and-tricks-for-2024/"><u>Effortless Snapchat Integration  Mac Tips & Tricks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-gateway-command-windows-11s-appsunlocked/"><u>Unlock the Gateway: Command Windows 11'S AppsUnlocked</u></a></li>
</ul></div>
