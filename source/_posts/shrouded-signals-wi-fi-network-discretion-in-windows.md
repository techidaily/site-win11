---
title: "Shrouded Signals: Wi-Fi Network Discretion in Windows"
date: 2024-11-17T07:44:38.633Z
updated: 2024-11-17T21:51:43.558Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Shrouded Signals: Wi-Fi Network Discretion in Windows"
excerpt: "This Article Describes Shrouded Signals: Wi-Fi Network Discretion in Windows"
keywords: Wi-Fi Privacy,Secure Wi-Fi,Stealth Wi-Fi,Discreet Networks,Hidden Wi-Fi Signals,Windows Network Security,Sensitive Wireless
thumbnail: https://thmb.techidaily.com/2aeb02acf862b6ad4b67e9ce99d75289c32cf73cca9a229e16ca142428daa51f.jpg
---

## Shrouded Signals: Wi-Fi Network Discretion in Windows

 By default, Windows displays all available Wi-Fi networks close to your device. Even if the networks are insecure, don't have parental controls enabled, or are just named inappropriately, Windows does not make an exception to block or hide them automatically.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052063/7443" target="_top" id="2052063">
  <img src="//a.impactradius-go.com/display-ad/7443-2052063" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052063/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Block Suspicious Wi-Fi Networks on Windows

 When a network is named inappropriately or looks suspicious owing to the lack of a password or protection, blocking it becomes imperative. Hopefully, now you know how to block and unblock a Wi-Fi network in the Command Prompt by running simple commands.

 While blocking other networks is essential, securing your network from prying eyes is equally important in maintaining your security and privacy.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-navigating-the-world-of-online-streaming-wirecast-and-facebook/"><u>[New] 2024 Approved Navigating the World of Online Streaming Wirecast & Facebook</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-record-and-relive-your-guide-to-capturing-phonescreens-with-snapchat/"><u>[New] 2024 Approved Record and Relive Your Guide to Capturing Phonescreens with Snapchat</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-amplifying-audio-and-visual-quality-in-your-youtube-videos-for-2024/"><u>[New] Amplifying Audio and Visual Quality in Your YouTube Videos for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/est-practices-in-selecting-youtube-video-extractor-apps-for-android/"><u>[New] Best Practices in Selecting YouTube Video Extractor Apps for Android</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-windows-update-problems-quickly/"><u>Break Free From Windows Update Problems Quickly</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/distinguishing-between-ev-types-bev-vs-phev-vs-fcev-vs-hybrid/"><u>Distinguishing Between EV Types: BEV vs PHEV vs FCEV vs Hybrid</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-temporary-directory-error-win-error-1152/"><u>Fixing 'Temporary Directory Error' - Win Error 1152</u></a></li>
<li><a href="https://apple-account.techidaily.com/guide-on-how-to-remove-apple-id-from-apple-iphone-se-by-drfone-ios/"><u>Guide on How To Remove Apple ID From Apple iPhone SE</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-understanding-whatsapps-sound-conversations/"><u>In 2024, Understanding WhatsApp's Sound Conversations</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-maze-of-windows-11s-error-codes/"><u>Navigating Through the Maze of Windows 11'S Error Codes</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-predominant-rainmeter-malfunctions-in-windows/"><u>Remedying Predominant Rainmeter Malfunctions in Windows</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    