---
title: How to Check Your Public IP Address Using Command Prompt in Windows 11/10
date: 2024-07-13T10:44:26.641Z
updated: 2024-07-14T10:44:26.641Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/addressing-dysfunctional-automation-settings-in-office-365outlook/"><u>Addressing Dysfunctional Automation Settings in Office 365/Outlook</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-natural-inside-glow-techniques-for-homes/"><u>[Updated] Natural Inside Glow Techniques for Homes</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-problem-of-non-opened-nvidia-control-panel-w11/"><u>Addressing the Problem of Non-Opened NVidia Control Panel, W11</u></a></li>
<li><a href="https://win11.techidaily.com/access-denied-tips-and-fixes-for-onedrive-on-windows-pcs/"><u>Access Denied? Tips and Fixes for OneDrive on Windows PCs</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-masterclass-selection-top-7-precision-games/"><u>2024 Approved  Masterclass Selection  Top 7 Precision Games</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-detect-and-stop-mspy-from-spying-on-your-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Stop mSpy from Spying on Your Realme 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/amplifying-steam-data-flow-combatting-sudden-drops/"><u>Amplifying Steam Data Flow: Combatting Sudden Drops</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-desktop-date-and-time-a-win-1011-guide/"><u>Adjusting Desktop Date & Time: A Win 10/11 Guide</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>3 Ways to Change Location on Facebook Marketplace for Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-solo-mastery-how-to-turn-off-apex-legends-cross-play-feature/"><u>2024 Approved  Solo Mastery  How to Turn Off Apex Legends' Cross-Play Feature</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-no-network-reachability-windows/"><u>Addressing No Network Reachability (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/alleviating-excessive-cpu-usage-by-tiworkerexe-software/"><u>Alleviating Excessive CPU Usage by TiWorker.exe Software</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-system-settings-for-outdated-app-packages/"><u>Adjusting System Settings for Outdated App Packages</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-cut-the-cost-not-your-content-quality-try-these-top-8-free-tools/"><u>[New] In 2024, Cut The Cost, Not Your Content Quality - Try These Top 8 Free Tools</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-convert-and-edit-wonders-10-best-youtube-tools-feat-audio/"><u>[Updated] Convert & Edit Wonders  10 Best YouTube Tools Feat. Audio</u></a></li>
<li><a href="https://win11.techidaily.com/ad-free-experience-just-for-you-with-win-11/"><u>Ad-Free Experience, Just for You with Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-your-cursors-cadence-turn-off-acceleration-win-11/"><u>Adjusting Your Cursor's Cadence: Turn Off Acceleration Win 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-students-gateway-to-history-the-top-10-youtube-archives/"><u>In 2024, Students' Gateway to History  The Top 10 Youtube Archives</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/2024-approved-top-10-free-spanish-text-to-speech-converter-software-windows-mac/"><u>2024 Approved Top 10 Free Spanish Text To Speech Converter Software Windows, Mac</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-creativity-best-writing-software-for-windows/"><u>Amplify Creativity: Best Writing Software For Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-taskbar-latency-issues/"><u>Addressing Windows 11 Taskbar Latency Issues</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-forgot-locked-iphone-14-pro-password-learn-the-best-methods-to-unlock-drfone-by-drfone-ios/"><u>In 2024, Forgot Locked iPhone 14 Pro Password? Learn the Best Methods To Unlock | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/audio-enhancement-for-windows-step-by-step-driver-instructions/"><u>Audio Enhancement for Windows: Step-by-Step Driver Instructions</u></a></li>
<li><a href="https://fox-access.techidaily.com/18-ways-to-record-internet-radio-comprehensive-tutorial/"><u>18 Ways To Record Internet Radio- Comprehensive Tutorial</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-single-stream-live-a-guide-for-solo-broadcasts/"><u>2024 Approved  Mastering Single-Stream LIVE  A Guide for Solo Broadcasts</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-gameplay-recording-harnessing-intel-graphics-hub/"><u>Advanced Gameplay Recording: Harnessing Intel Graphics Hub</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-premium-surround-sound-with-dolby-atmos-in-windows-11/"><u>Achieving Premium Surround Sound with Dolby Atmos in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-memory-usage-by-microsoft-edge-webview2/"><u>Addressing High-Memory Usage by Microsoft Edge WebView2</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-the-ultimate-imovie-strategy-to-eliminate-unwanted-sounds-in-your-projects/"><u>New In 2024, The Ultimate iMovie Strategy to Eliminate Unwanted Sounds in Your Projects</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-infinix-hot-30i-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Infinix Hot 30i Device SIM</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-accelerated-conversion-of-yt-content-for-mac-screens/"><u>[Updated] 2024 Approved  Accelerated Conversion of YT Content for MAC Screens</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-disasters-committing-to-weekly-windows-backup/"><u>Avoiding Disasters: Committing to Weekly Windows Backup</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-honor-magic-6-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-windows-based-excel-tasks-a-guide/"><u>Accelerating Windows-Based Excel Tasks: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-audio-output-not-found-in-windows/"><u>Addressing Audio Output Not Found in Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-on-your-iphone-7-plus-by-drfone-ios/"><u>In 2024, New Multiple Ways How To Remove iCloud Activation Lock On your iPhone 7 Plus</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-how-to-start-a-channel-a-beginners-guide-to-reviewing-books-and-ebooks-for-2024/"><u>[New] How To Start a Channel  A Beginner's Guide to Reviewing Books & Ebooks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/arrow-anomalies-heres-how-to-tackle-them/"><u>Arrow Anomalies? Here’s How to Tackle Them</u></a></li>
<li><a href="https://win11.techidaily.com/altering-the-native-pdf-reader-setup-in-windows/"><u>Altering the Native PDF Reader Setup in Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-from-clicks-to-cash-the-journey-of-youtubes-ajay-nagar/"><u>2024 Approved  From Clicks to Cash  The Journey of YouTube's Ajay Nagar</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-enhancing-youtube-videos-for-superior-quality/"><u>[New] Enhancing YouTube Videos for Superior Quality</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-insufficient-graphics-memory-in-hogwarts-educational-game/"><u>Addressing Insufficient Graphics Memory in Hogwarts Educational Game</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-inkpad-functionality-woes/"><u>Addressing Windows Inkpad Functionality Woes</u></a></li>
<li><a href="https://win11.techidaily.com/access-denied-top-7-fixes-for-browser-blockades-on-win-os/"><u>Access Denied? Top 7 Fixes for Browser Blockades on Win OS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/cross-platform-success-televisions-and-facebook-collaboration/"><u>Cross-Platform Success  Televisions & Facebook Collaboration</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-essential-steps-for-organizing-youtube-content/"><u>[New] In 2024, Essential Steps for Organizing YouTube Content</u></a></li>
</ul></div>
