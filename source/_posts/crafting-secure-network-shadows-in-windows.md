---
title: Crafting Secure Network Shadows in Windows
date: 2024-06-25T11:44:19.209Z
updated: 2024-06-26T11:44:19.209Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Crafting Secure Network Shadows in Windows
excerpt: This Article Describes Crafting Secure Network Shadows in Windows
keywords: Secure Networks,Windows Security,Cybersecurity,Network Protection,Privacy Safeguards,Safe Shadows,Encrypted Connections
thumbnail: https://thmb.techidaily.com/eea9086dc7bf337d2bb499bc698c2b462f09146348f5ebcda0ff8ce585d15359.jpg
---

## Crafting Secure Network Shadows in Windows

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
<li><a href="https://win11.techidaily.com/seamless-add-on-of-portable-software-to-windows-oses/"><u>Seamless Add-On of Portable Software to Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-11s-camera-app-glitch-afc-error/"><u>Resolving Windows 11'S Camera App Glitch: AFC Error</u></a></li>
<li><a href="https://win11.techidaily.com/win11-error-fixer-correcting-code-0x0000011b/"><u>Win11 Error Fixer: Correcting Code 0X0000011B</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-connection-between-win-code-and-microsoft-services/"><u>Streamlining Connection Between WIN Code and Microsoft Services</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-steam-sound-fidelity/"><u>Enhancing Windows Steam Sound Fidelity</u></a></li>
<li><a href="https://win11.techidaily.com/removing-updater-code-0x8019-issue-on-xp/"><u>Removing Updater Code 0X8019 Issue on XP</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-value-in-vcplusplus-release-packages/"><u>Unlocking the Value in VC++ Release Packages</u></a></li>
<li><a href="https://win11.techidaily.com/1719218317457-gpt4all-windows-guide-to-free-on-premise-chatbots/"><u>GPT4All Windows Guide to Free, On-Premise ChatBots.</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-transforming-your-ad-strategy-with-animation-for-max-roi/"><u>In 2024, Transforming Your Ad Strategy with Animation for Max ROI</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-vloggers-paradise-14-best-video-editing-software-for-hot-platforms/"><u>2024 Approved Vloggers Paradise 14 Best Video Editing Software for Hot Platforms</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-discord-text-formatting-how-to-change-text-style-in-discord/"><u>[New] Discord Text Formatting  How to Change Text Style in Discord?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-screen-free-entertainment-top-10-best-offline-ipad-games/"><u>[New] 2024 Approved  Screen-Free Entertainment  Top 10 Best Offline iPad Games</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-mastering-audio-files-with-lame-in-audacity-a-detailed-walkthrough-for-2024/"><u>Updated Mastering Audio Files with Lame in Audacity – A Detailed Walkthrough for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/crafting-engagement-with-weblink-content-in-instagram-for-2024/"><u>Crafting Engagement with Weblink Content in Instagram for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-honor-x50-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Honor X50 Without Password | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-cartoon-video-creation-made-easy-10-best-mobile-apps/"><u>Updated Cartoon Video Creation Made Easy 10 Best Mobile Apps</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-content-kings-and-queens-highest-subscribers-crowned/"><u>[New] Content Kings & Queens  Highest Subscribers Crowned</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>