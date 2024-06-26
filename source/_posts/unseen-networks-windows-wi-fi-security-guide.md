---
title: "Unseen Networks: Windows Wi-Fi Security Guide"
date: 2024-06-25T10:22:40.419Z
updated: 2024-06-26T10:22:40.419Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unseen Networks: Windows Wi-Fi Security Guide"
excerpt: "This Article Describes Unseen Networks: Windows Wi-Fi Security Guide"
keywords: Wi-Fi Security Basics,Safe Windows Networking,Guard Your Wi-Fi,Wi-Fi Protection Tips,Secure Windows WLAN,Enhance Wireless Safety,Windows Net Defense Guide
thumbnail: https://thmb.techidaily.com/0e8b59a0a7e5a9b9173ae5feaad5ddb56b135eee3ed22a8b3f83cf8fa8dfaeb8.jpg
---

## Unseen Networks: Windows Wi-Fi Security Guide

 By default, Windows displays all available Wi-Fi networks close to your device. Even if the networks are insecure, don't have parental controls enabled, or are just named inappropriately, Windows does not make an exception to block or hide them automatically.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.

## How to Hide or Block a Wi-Fi Network on Windows

 Follow these steps to [use the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to stop a Wi-Fi network from showing up among the available networks:

1. Type"Command Prompt" into Windows Search, right-click on the **Command Prompt** app and then click **Run as administrator**.
2. Note the full name of the network you intend to block or hide.
3. Enter the name of the Wi-Fi network next to the SSID field in the following command:  
`netsh wlan add filter permission=block ssid="add the name of the Wi-Fi network you want to block here" networktype=infrastructure`
4. Copy and paste the command into the Command Prompt app and press **Enter**.  
![Block the Wi-Fi Network By Running a Command in Command Prompt on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/block-the-wi-fi-network-by-running-a-command-in-command-prompt-on-windows.jpg)

 If you see the message "The filter is added on the system successfully," the Wi-Fi network has been blocked, and it'll no longer appear in your Wi-Fi list. While the above steps will indeed block the Wi-Fi network, it will reappear among the available networks if the owner decides to [rename the Wi-Fi adapter](https://www.makeuseof.com/windows-11-rename-network-adapter/).

 If you change your mind and want to unblock the network you just blocked, enter the following command into the Command Prompt after entering the blocked network name:

`netsh wlan delete filter permission=block ssid="add the of the name of the Wi-Fi network you want to unblock here" networktype=infrastructure`

![Remove the Blocked Filter to Unblock the Wi-Fi Network Using the Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/remove-the-blocked-filter-to-unblock-the-wi-fi-network-using-the-windows-command-prompt.jpg)

## Block Suspicious Wi-Fi Networks on Windows

 When a network is named inappropriately or looks suspicious owing to the lack of a password or protection, blocking it becomes imperative. Hopefully, now you know how to block and unblock a Wi-Fi network in the Command Prompt by running simple commands.

 While blocking other networks is essential, securing your network from prying eyes is equally important in maintaining your security and privacy.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/displaying-networked-storage-options-on-screen/"><u>Displaying Networked Storage Options on Screen</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-secure-boot-and-tpm-activationdeactivation-in-vbox-70/"><u>Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0</u></a></li>
<li><a href="https://win11.techidaily.com/open-windows-ease-of-access-center-top-5-tactics/"><u>Open Windows Ease of Access Center: Top 5 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/securing-windows-with-a-side-of-kali-linux/"><u>Securing Windows with a Side of Kali Linux</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-wasteful-usage-by-core-system-processes/"><u>Reducing Wasteful Usage by Core System Processes</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-top-methods-for-an-effective-windows-11-launch/"><u>Discover the Top Methods for an Effective Windows 11 Launch</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-resolving-error-code-0x000-on-your-windows-11-devices-xbox-game-pass/"><u>Swiftly Resolving Error Code 0X000_ on Your Windows 11 Devices' Xbox Game Pass</u></a></li>
<li><a href="https://win11.techidaily.com/faster-booting-window-11s-boot-delay-adjustment-explained/"><u>Faster Booting: Window 11'S Boot Delay Adjustment Explained</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-top-9-free-online-movie-makers/"><u>New Top 9 Free Online Movie Makers</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-sony-xperia-10-v-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Sony Xperia 10 V to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-preserving-pixels-in-the-sky-selecting-best-photo-cloud-storages/"><u>In 2024, Preserving Pixels in the Sky  Selecting Best Photo Cloud Storages</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-enhance-your-music-library-top-6-free-ios-apps-for-audio-conversion/"><u>[New] Enhance Your Music Library  Top 6 Free iOS Apps for Audio Conversion</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-strategies-to-design-lively-and-uplifting-content-shows/"><u>[Updated] Strategies to Design Lively and Uplifting Content Shows</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-epic-prank-ideas-with-a-twist-of-anime-on-tiktok-for-2024/"><u>[New] Epic Prank Ideas with a Twist of Anime on TikTok for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/revamp-your-tiktok-profile-an-in-depth-editing-roadmap-for-2024/"><u>Revamp Your TikTok Profile  An In-Depth Editing Roadmap for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-lock-on-your-apple-iphone-11-pro-max-and-ipad-by-drfone-ios/"><u>In 2024, How to Unlock iCloud lock on your Apple iPhone 11 Pro Max and iPad?</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-streaming-tweets-on-whatsapp-a-2023-guide/"><u>2024 Approved  Streaming Tweets on WhatsApp  A 2023 Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>