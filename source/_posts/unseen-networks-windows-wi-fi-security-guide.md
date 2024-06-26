---
title: "Unseen Networks: Windows Wi-Fi Security Guide"
date: 2024-06-25T11:35:13.434Z
updated: 2024-06-26T11:35:13.434Z
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
<li><a href="https://win11.techidaily.com/regaining-original-directory-display-preferences/"><u>Regaining Original Directory Display Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/nix-the-need-for-speedy-pointers-on-windows-11/"><u>Nix the Need for Speedy Pointers on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-mixed-user-microsoft-login-issues/"><u>Dealing with Mixed-User Microsoft Login Issues</u></a></li>
<li><a href="https://win11.techidaily.com/prose-perfection-on-a-windows-desktop-the-top-5-picks/"><u>Prose Perfection on a Windows Desktop - The Top 5 Picks</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-fixing-broken-internet-connections-6-strategies-for-windows-users/"><u>The Art of Fixing Broken Internet Connections - 6 Strategies for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/best-lighter-browsing-options-tested-for-memory-conservation/"><u>Best Lighter Browsing Options Tested For Memory Conservation</u></a></li>
<li><a href="https://win11.techidaily.com/avoidance-of-dxgierror-post-device-disconnect/"><u>Avoidance of DXGI_Error Post Device Disconnect</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-prime-steps-to-modify-playback-rate-of-songs-in-spotify/"><u>[New] Prime Steps to Modify Playback Rate of Songs in Spotify</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-smooth-watchers-guide-to-pacing-down-videos-on-youtube-60-chars-minor-exception-due-to-title-length-but-provides-rich-context/"><u>[Updated] The Smooth Watcher's Guide to Pacing Down Videos on YouTube (60 Chars, Minor Exception Due to Title Length but Provides Rich Context)</u></a></li>
<li><a href="https://extra-skills.techidaily.com/orchestrate-audio-amidst-slides-for-2024/"><u>Orchestrate Audio Amidst Slides for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-engaging-tiktok-personal-frames-ideas-that-pop/"><u>[New] 2024 Approved  Engaging TikTok Personal Frames  Ideas That Pop</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-in-2024-create-talking-cartoon-images-using-top-tools/"><u>Updated In 2024, Create Talking Cartoon Images Using Top Tools</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-a-lost-zte-axon-40-lite-for-free-drfone-by-drfone-virtual-android/"><u>How to Track a Lost ZTE Axon 40 Lite for Free? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-proven-instagram-analysis-apps-enhance-engagement-growth-and-conversion-rates/"><u>[Updated] Proven Instagram Analysis Apps  Enhance Engagement, Growth & Conversion Rates</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-advanced-3d-viewing-on-your-android-device/"><u>[New] Advanced 3D Viewing on Your Android Device</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-unlocking-vimeos-potential-screen-and-webcam-capture-mastery/"><u>In 2024, Unlocking Vimeo's Potential  Screen and Webcam Capture Mastery</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>