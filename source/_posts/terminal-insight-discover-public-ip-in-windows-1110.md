---
title: "Terminal Insight: Discover Public IP in Windows 11/10"
date: 2024-07-13T10:16:51.727Z
updated: 2024-07-14T10:16:51.727Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/addressing-the-surge-in-cpu-usage-by-wlanext/"><u>Addressing the Surge in CPU Usage by WLANEXT</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/amplify-views-effortlessly-discovering-the-best-20-youtube-techniques-for-2024/"><u>Amplify Views Effortlessly  Discovering the Best 20 YouTube Techniques for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/what-does-the-signature-blue-glyph-on-messenger-stand-for/"><u>What Does the Signature Blue Glyph on Messenger Stand For?</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-windows-steam-transfers-averting-sudden-halt/"><u>Amplify Windows Steam Transfers: Averting Sudden Halt</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-seamless-process-of-instagram-video-content-for-2024/"><u>[Updated] Seamless Process of Instagram Video Content for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-seamless-sessions-tailoring-your-zoom-environment/"><u>[Updated] Seamless Sessions  Tailoring Your Zoom Environment</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-no-supported-issue-during-os-setup-and-update/"><u>Addressing 'No Supported' Issue During OS Setup and Update</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disrupted-copy-and-paste-on-windows-11/"><u>Addressing Disrupted Copy & Paste on Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-audio-exploration-the-comprehensible-review-of-pazera/"><u>In 2024, Audio Exploration  The Comprehensible Review of Pazera</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-faults-with-proven-remedies/"><u>Addressing Windows Faults with Proven Remedies!</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-sims-4-documentation-cutting-edge-methods-to-preserve-gaming-experiences/"><u>[New] 2024 Approved  Sims 4 Documentation  Cutting-Edge Methods to Preserve Gaming Experiences</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unveiling-cropped-lengths-imovies-automatic-trimming-logic/"><u>2024 Approved  Unveiling Cropped Lengths  IMovie's Automatic Trimming Logic</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-imaging-separating-subjects-from-surroundings/"><u>Advanced Imaging: Separating Subjects From Surroundings</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-spotify-location-after-moving-to-another-country-on-motorola-edge-40-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Spotify Location After Moving to Another Country On Motorola Edge 40 Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-install-net-application-complaint/"><u>Addressing the Install .NET Application Complaint</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-how-can-you-deny-these-top-10-free-speech-to-text-software/"><u>New How Can You Deny These Top 10 Free Speech to Text Software</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-watch-deleted-youtube-videos-online-in-2-ways-for-2024/"><u>How to Watch Deleted YouTube Videos Online in 2 Ways for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-driver-verifier-manager-w11-edition/"><u>Accessing Driver Verifier Manager W11 Edition</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/the-art-of-recording-facebook-lives-discover-4-key-strategies-for-2024/"><u>The Art of Recording Facebook Lives  Discover 4 Key Strategies for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-concept-to-reality-the-vr-story-for-2024/"><u>From Concept to Reality  The VR Story for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-recovery-tactics-for-unavailable-defender-security-features/"><u>Accelerated Recovery Tactics for Unavailable Defender Security Features</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-failed-logon-wait-duration-settings/"><u>Adjusting Failed Logon Wait Duration Settings</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-configuration-for-optimal-android-resource-use/"><u>Advanced Configuration for Optimal Android Resource Use</u></a></li>
<li><a href="https://win11.techidaily.com/alleviating-high-cpu-demands-in-setups/"><u>Alleviating High CPU Demands in Setups</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-incompatible-format-in-windows-vlc-error/"><u>Addressing Incompatible Format in Windows VLC Error</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-pinnacle-portals-select-laptops-for-uhd-content-creation/"><u>[New] Pinnacle Portals  Select Laptops for UHD Content Creation</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-top-slide-show-collections-10-places-to-download-high-quality-designs/"><u>[New] Top Slide Show Collections  10 Places to Download High-Quality Designs</u></a></li>
<li><a href="https://win11.techidaily.com/adding-a-functional-system-update-alert-in-win11-pro/"><u>Adding a Functional System Update Alert in Win11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-for-correcting-err-87-invalid-parameters-on-winos/"><u>Approaches for Correcting Err 87: Invalid Parameters on WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/asuss-steam-deck-challenger-the-rog-ally/"><u>ASUS's Steam Deck Challenger: The ROG Ally?</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-must-read-top-10-ai-realistic-avatar-generators-for-2024/"><u>Updated Must-Read Top 10 AI Realistic Avatar Generators for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-edit-mp4-files-like-a-pro-mac-and-windows-tutorial-for-beginners-for-2024/"><u>New Edit MP4 Files Like a Pro Mac and Windows Tutorial for Beginners for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/altering-visual-angle-in-windows-configuration/"><u>Altering Visual Angle in Windows Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-functional-gadget-alert-in-windows-11/"><u>Addressing Non-Functional Gadget Alert in Windows 11</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-the-virtual-quest-a-jaunt-vr-exploration/"><u>In 2024, The Virtual Quest  A Jaunt VR Exploration</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-update-problem-code-0x8024800c/"><u>Addressing Windows Update Problem: Code 0X8024800C</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/altering-account-access-in-windows-11-easily/"><u>Altering Account Access in Windows 11 Easily</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-network-not-reachable-issues-on-windows-11-computers/"><u>Addressing 'Network Not Reachable' Issues on Windows 11 Computers</u></a></li>
<li><a href="https://win11.techidaily.com/ahead-of-change-enabling-tpm-secure-boot-for-windows-11/"><u>Ahead of Change: Enabling TPM, Secure Boot for Windows 11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-vivo-s17-pro-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Vivo S17 Pro Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-profile-not-valid-issue-for-users-in-windows/"><u>Addressing Profile Not Valid Issue for Users in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/altering-system-index-for-optimization/"><u>Altering System Index for Optimization</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-store-glitch-code-0x80073cf3/"><u>Addressing Windows Store Glitch: Code 0X80073CF3</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-frustration-fixing-the-missing-print-feature-on-windows/"><u>Avoid Frustration: Fixing the Missing Print Feature on Windows.</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-top-10-professional-grade-microphones-for-podcasters/"><u>2024 Approved  Top 10 Professional-Grade Microphones for Podcasters</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-fresh-pioneers-8-youtubes-fastest-climbers-for-2024/"><u>[New] Fresh Pioneers 8  YouTube's Fastest Climbers for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-windows-troubleshooting-locating-and-fixing-system-error-messages-using-commands/"><u>Advanced Windows Troubleshooting: Locating & Fixing System Error Messages Using Commands</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-geforce-notaxc0f1103f-windows-errors/"><u>Addressing GeForce NotaXC0F1103F Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-limited-usb-interface-on-pcs/"><u>Addressing Limited USB Interface on PCs</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-dodge-digital-watchers-accelerating-view-count-growth/"><u>[Updated] 2024 Approved  Dodge Digital Watchers  Accelerating View Count Growth</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-identifying-leading-drone-motors-for-superior-stability-for-2024/"><u>[Updated] Identifying Leading Drone Motors for Superior Stability for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/advice-for-fixing-untraceable-windows-drives/"><u>Advice for Fixing Untraceable Windows Drives</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Xiaomi Redmi Note 12T Pro | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-motorola-g24-power-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Motorola G24 Power to iPod | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-vanished-pc-displays-at-launch/"><u>Addressing Vanished PC Displays at Launch</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-joining-google-meet-from-computerphone/"><u>In 2024, Joining Google Meet From Computer/Phone</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-techniques-removing-restrictions-in-windows/"><u>Advanced Techniques: Removing Restrictions in Windows</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-digital-music-layering-and-editing-suite-for-2024/"><u>Updated Digital Music Layering & Editing Suite for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-az-video-logger-full-application-scrutiny/"><u>In 2024, AZ Video Logger - Full Application Scrutiny</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-step-by-step-process-for-adding-unique-emojis-to-your-discord-avatar-pcmobile/"><u>2024 Approved  Step-By-Step Process for Adding Unique Emojis to Your Discord Avatar (PC/Mobile)</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/essential-screen-capture-techniques-for-powerpoint-presentations/"><u>Essential Screen Capture Techniques for PowerPoint Presentations</u></a></li>
<li><a href="https://win11.techidaily.com/automatic-program-management-in-windows-os/"><u>Automatic Program Management in Windows OS</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-prime-online-spots-for-availing-text-enhancement-files/"><u>[New] Prime Online Spots for Availing Text Enhancement Files</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-windows-11-volume-mixer-shortcut/"><u>Accessing Windows 11 Volume Mixer Shortcut</u></a></li>
<li><a href="https://win11.techidaily.com/automating-productivity-with-to-do-and-ifttt/"><u>Automating Productivity with To-Do and IFTTT</u></a></li>
<li><a href="https://win11.techidaily.com/automated-uninstall-process-for-printers-in-windows-11/"><u>Automated Uninstall Process for Printers in Windows 11</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/essential-tips-for-capturing-high-quality-audio-in-filmmaking/"><u>Essential Tips for Capturing High-Quality Audio in Filmmaking</u></a></li>
</ul></div>
