---
title: Intruder Alert! Hiding Windows Wi-Fi SSID
date: 2024-10-24T17:15:49.577Z
updated: 2024-10-26T22:27:36.264Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Intruder Alert! Hiding Windows Wi-Fi SSID
excerpt: This Article Describes Intruder Alert! Hiding Windows Wi-Fi SSID
keywords: Wi-Fi Intrusion Alert,SSID Security Notice,Stealthy Wi-Fi Networks,Hidden Wi-Fi Detection,Wi-Fi SSID Obscurity,Unseen Wi-Fi Signals,Alert
thumbnail: https://thmb.techidaily.com/56db2abce12454619eb56aa29719b3ba982081a7573c4ec93a0c358d91bb966c.jpg
---

## Intruder Alert! Hiding Windows Wi-Fi SSID

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
<a href="https://aligracehair.sjv.io/c/5597632/1918703/19272" target="_top" id="1918703">
  <img src="//a.impactradius-go.com/display-ad/19272-1918703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918703/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Block Suspicious Wi-Fi Networks on Windows

 When a network is named inappropriately or looks suspicious owing to the lack of a password or protection, blocking it becomes imperative. Hopefully, now you know how to block and unblock a Wi-Fi network in the Command Prompt by running simple commands.

 While blocking other networks is essential, securing your network from prying eyes is equally important in maintaining your security and privacy.

 If you spot such a network and want to stop it from appearing among available Wi-Fi networks to prevent your children or yourself from viewing or accidentally connecting to it, here's how you can do that.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-camera-duel-sj6-against-xiaomis-yi-visionary/"><u>[New] The Ultimate Camera Duel SJ6 Against Xiaomi's Yi Visionary</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-how-to-stream-smoothly-with-nook-miles-tactics/"><u>[Updated] In 2024, How to Stream Smoothly with Nook Miles Tactics</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-emotion-to-entertainment-the-artisans-approach-to-making-memes-gifs/"><u>2024 Approved From Emotion to Entertainment The Artisan’s Approach to Making Memes (GIFs)</u></a></li>
<li><a href="https://win11.techidaily.com/create-a-window-showcase-customizing-with-spotlight-picture-inspired-backgrounds/"><u>Create a Window Showcase: Customizing with Spotlight Picture-Inspired Backgrounds</u></a></li>
<li><a href="https://win11.techidaily.com/discerning-safe-from-risky-windows-11-features/"><u>Discerning Safe From Risky Windows 11 Features</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-sticky-notes-in-win11win10-apps/"><u>Expert Guide to Sticky Notes in Win11/Win10 Apps</u></a></li>
<li><a href="https://win11.techidaily.com/implementing-windows-1011-update-reminder-feature/"><u>Implementing Windows 10/11 Update Reminder Feature</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-10-budget-friendly-image-editing-apps-for-smartphones-for-2024/"><u>Top 10 Budget-Friendly Image Editing Apps for Smartphones for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-successfully-fixing-steam-network-reachability-glitches/"><u>Troubleshooting Successfully: Fixing Steam Network Reachability Glitches</u></a></li>
</ul></div>

