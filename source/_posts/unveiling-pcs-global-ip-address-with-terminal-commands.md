---
title: Unveiling PC's Global IP Address with Terminal Commands
date: 2024-07-13T09:57:59.881Z
updated: 2024-07-14T09:57:59.881Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unveiling PC's Global IP Address with Terminal Commands
excerpt: This Article Describes Unveiling PC's Global IP Address with Terminal Commands
keywords: Global IP Uncovering,Terminal Command Guide,IP Address Exposure,Access PC Internally,Terminal Network Diagnostics,Find PC's IP Quickly,Locate IP Via Terminal
thumbnail: https://thmb.techidaily.com/e4680a85088d1a2f44c589b1c74f41a831760d9eaf6ae422f8b959a2a9262d12.jpg
---

## Unveiling PC's Global IP Address with Terminal Commands

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
<li><a href="https://win11.techidaily.com/improve-energy-monitoring-full-charge-alerts-for-a-more-efficient-win11/"><u>Improve Energy Monitoring: Full Charge Alerts for a More Efficient Win11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-an-easy-to-follow-guide-to-applying-cc-license-types/"><u>[New] In 2024, An Easy-to-Follow Guide to Applying CC License Types</u></a></li>
<li><a href="https://win11.techidaily.com/filter-irrelevant-notification-feedback-in-windows-11/"><u>Filter Irrelevant Notification Feedback in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-pre-use-disk-formatting-notice-on-windows/"><u>Eliminating Pre-Use Disk Formatting Notice on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/essential-guide-win-compatible-free-media-devices/"><u>Essential Guide: Win-Compatible Free Media Devices</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-premier-list-of-the-most-reliable-song-recorders-on-the-market-for-2024/"><u>New Premier List of the Most Reliable Song Recorders on the Market for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-window-pc-always-unlocked/"><u>Keep Your Window PC Always Unlocked</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-sound-control-software-showdown-best-vocal-reduction-options/"><u>In 2024, Sound Control Software Showdown Best Vocal Reduction Options</u></a></li>
<li><a href="https://win11.techidaily.com/copying-powertoys-preferences-to-another-pc/"><u>Copying PowerToys Preferences to Another PC</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-the-metaverse-and-multimetase-core-disparities-explored-for-2024/"><u>Unveiling the Metaverse & MultiMetase  Core Disparities Explored for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/bypass-reset-zte-nubia-z60-ultra-phone-screen-passcode-pattern-pin-by-drfone-android-unlock-android-unlock/"><u>Bypass/Reset ZTE Nubia Z60 Ultra Phone Screen Passcode/Pattern/Pin</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-forgot-locked-apple-iphone-15-pro-max-password-learn-the-best-methods-to-unlock-by-drfone-ios/"><u>In 2024, Forgot Locked Apple iPhone 15 Pro Max Password? Learn the Best Methods To Unlock</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-make-the-most-of-your-apple-iphone-se-2020-lock-screen-with-notifications-drfone-by-drfone-ios/"><u>In 2024, How to Make the Most of Your Apple iPhone SE (2020) Lock Screen with Notifications? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-shortcuts-next-to-the-power-button-on-windows-11/"><u>How to Add Shortcuts Next to the Power Button on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-clone-without-third-party-reliance-in-windows/"><u>Crafting Clone Without Third-Party Reliance in Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-direct-links-sending-fb-videos-via-whatsapp/"><u>[Updated] Direct Links  Sending FB Videos via WhatsApp</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-the-5-prime-apps-for-clandestine-story-viewers/"><u>2024 Approved  The 5 Prime Apps for Clandestine Story Viewers</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-password-strength-in-windows-11-with-longer-pins/"><u>Enhancing Password Strength in Windows 11 with Longer Pins</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/2024-approved-extract-sound-from-instagram-reels-and-videos/"><u>2024 Approved Extract Sound From Instagram Reels and Videos</u></a></li>
<li><a href="https://win11.techidaily.com/notetaking-renaissance-discovering-obsidians-visuality/"><u>Notetaking Renaissance: Discovering Obsidian's Visuality</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-x80072f30-quick-fix-for-windows-store-problems/"><u>Eliminate X80072F30: Quick Fix for Windows Store Problems</u></a></li>
<li><a href="https://win11.techidaily.com/ending-failed-operations-fix-code-0x0000011b/"><u>Ending Failed Operations: Fix Code 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-controlling-installer-service-in-windows/"><u>Guide to Controlling Installer Service in Windows</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-smartphone-youtube-experience-apple-vs-android-review/"><u>2024 Approved  Smartphone YouTube Experience  Apple vs Android Review</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-windows-control-with-administrator-rights/"><u>Conquering Windows Control with Administrator Rights</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-accessibility-features/"><u>Navigating Through Windows' Accessibility Features</u></a></li>
<li><a href="https://video-capture.techidaily.com/freenoweb-cam-app-assessment-and-comparison-guide/"><u>FreenoWeb Cam App Assessment & Comparison Guide</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-code-a-secure-window-for-hardware-unhook-in-win11/"><u>How to Code a Secure Window for Hardware Unhook in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/directives-for-disabling-errors-on-gaming-platform/"><u>Directives for Disabling Errors on Gaming Platform</u></a></li>
<li><a href="https://win11.techidaily.com/microsofts-ai-hub-enhancing-shopping-experience/"><u>Microsoft’s AI Hub – Enhancing Shopping Experience</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-crafting-timeless-videos-with-historical-flair/"><u>[Updated] In 2024, Crafting Timeless Videos with Historical Flair</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-apple-iphone-11-pro-max-data-to-iphone-12-a-complete-guide-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Apple iPhone 11 Pro Max Data to iPhone 12 A Complete Guide | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-windows-features-for-macos-advantages/"><u>Integrating Windows Features for MacOS Advantages</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-comprehensive-review-of-ios-free-video-editing-apps/"><u>[New] Comprehensive Review of iOS Free Video Editing Apps</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-social-stunt-planters-handbook-meme-mastery-at-9gag/"><u>[New] The Social Stunt Planters' Handbook  Meme Mastery at 9GAG</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-maximizing-online-exposure-on-youtube-by-keeping-up-creative-commons-usage/"><u>[Updated] Maximizing Online Exposure on YouTube by Keeping Up Creative Commons Usage</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-hdtv-revolution-comparing-the-leading-8k-tv-brands/"><u>[Updated] HDTV Revolution  Comparing the Leading 8K TV Brands</u></a></li>
<li><a href="https://extra-hints.techidaily.com/optimal-live-video-distributors-suite/"><u>Optimal Live Video Distributors' Suite</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-efficient-windows-11-shortcuts-for-uwp-apps/"><u>Crafting Efficient Windows 11 Shortcuts for UWP Apps</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-10-free-video-editing-software-for-windows-10-trim-cut-and-more/"><u>New In 2024, 10 Free Video Editing Software for Windows 10 Trim, Cut, and More</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-non-complying-windows-scripts/"><u>Essential Fixes for Non-Complying Windows Scripts</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/classic-computing-redeemed-by-atlasos/"><u>Classic Computing Redeemed by AtlasOS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-understanding-and-implementing-slug-line-rules/"><u>2024 Approved  Understanding and Implementing Slug Line Rules</u></a></li>
<li><a href="https://win11.techidaily.com/insight-into-windows-11s-new-automated-data-safeguarding/"><u>Insight Into Windows 11’S New Automated Data Safeguarding</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-engaging-consumers-effectively-through-snapbiz-insights/"><u>2024 Approved  Engaging Consumers Effectively Through SnapBiz Insights</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-windows-error-0x80070522-enhance-client-access-control/"><u>Eliminate Window's Error 0X80070522: Enhance Client Access Control</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-for-win10-blue-screen-resolution/"><u>Key Techniques for Win10 Blue Screen Resolution</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-in-2024-the-social-media-face-off-is-the-future-of-sharing-with-likes-not-tiktok/"><u>[Updated] In 2024, The Social Media Face-Off  Is the Future of Sharing with Likes, Not TikTok?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-a-perfect-replica-of-your-drive/"><u>How to Make a Perfect Replica of Your Drive</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-absence-of-rockalldll-in-windows-os/"><u>Fixes for Absence of Rockalldll in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/explore-1-6-gpu-power-tools-to-assess-on-your-pc/"><u>Explore #1-#6 GPU Power Tools to Assess on Your PC</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ways-to-get-free-views-on-youtube-alternative-methods/"><u>Easy Ways To Get Free Views on YouTube! Alternative Methods</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-windows-alt-key-errors-48-characters/"><u>Diagnosing Windows Alt Key Errors (48 Characters)</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-penning-podcasts-to-perfection-a-compreomed-writers-guide/"><u>[Updated] Penning Podcasts to Perfection  A Compreomed Writer’s Guide</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-diskusage-in-windows-strategies-for-effective-drive-space-analysis/"><u>Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/from-vanished-panes-to-visible-windows-essential-steps-for-recovering-hidden-screens-6-ways/"><u>From Vanished Panes to Visible Windows: Essential Steps for Recovering Hidden Screens (6 Ways)</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-xiaomi-redmi-note-12-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Xiaomi Redmi Note 12 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-shutdown-the-guide-to-auto-mode-with-windows-1011/"><u>Efficient Shutdown: The Guide to Auto Mode with Windows 10/11</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-oneplus-open-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your OnePlus Open Auto Does Not Work | Dr.fone</u></a></li>
</ul></div>
