---
title: How to Enable or Disable Metered Connection for a Wi-Fi Network in Windows 11
date: 2024-12-18T17:24:40.834Z
updated: 2024-12-22T17:32:37.326Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Enable or Disable Metered Connection for a Wi-Fi Network in Windows 11
excerpt: This Article Describes How to Enable or Disable Metered Connection for a Wi-Fi Network in Windows 11
keywords: Metro Connection Settings Windows 11,Wi-Fi Metering Control Windows,Enable/Disable Wi-Fi Metering Windows,Windows 11 Metered Mode Adjustment,Manage Metered Wi-Fi in Windows 11,Windows 11 Set Metered Connection,Wi-Fi Data Usage Management Win11
thumbnail: https://thmb.techidaily.com/e68430bcb106e10e6ed671e16682f01d022f0799c626556c343ddc595fa9cde5.jpg
---

## How to Enable or Disable Metered Connection for a Wi-Fi Network in Windows 11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-choosing-the-best-portable-microphones-for-macos-users/"><u>[New] Choosing the Best Portable Microphones for MacOS Users</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-snap-and-share-the-brief-vlog-age/"><u>[New] In 2024, Snap & Share The Brief Vlog Age</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-the-ultimate-iphone-x-handbook-for-users-for-2024/"><u>[New] The Ultimate iPhone X Handbook for Users for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-screen-recording-through-built-in-features-of-huaweis-mate-and-p-devices-p20-p10/"><u>2024 Approved Screen Recording Through Built-In Features of Huawei's Mate and P Devices (P20, P10)</u></a></li>
<li><a href="https://win11.techidaily.com/credential-manager-breaking-the-open-barrier/"><u>Credential Manager: Breaking the Open Barrier</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/cross-platform-harmony-transferring-your-curated-playlists-between-apple-music-and-youtube-music-unveiled/"><u>Cross-Platform Harmony: Transferring Your Curated Playlists Between Apple Music and YouTube Music Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-0x8004def5-nine-fixes-for-onedrive-issues-win11/"><u>Deciphering 0X8004DEF5 - Nine Fixes for Onedrive Issues, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/discover-the-leading-6-task-assistants-that-work-with-windows-11/"><u>Discover the Leading 6 Task Assistants That Work with Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fps-counters-in-windows-11-landscape/"><u>Essential FPS Counters in Windows 11 Landscape</u></a></li>
<li><a href="https://win11.techidaily.com/get-back-whats-gone-enhance-your-windows-functionality/"><u>Get Back What's Gone: Enhance Your Window's Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-perfectly-configure-the-win11s-dns-service/"><u>How to Perfectly Configure the Win11's DNS Service</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-fix-iphone-xr-unavailable-issue-with-ease-drfone-by-drfone-ios/"><u>In 2024, How To Fix iPhone XR Unavailable Issue With Ease | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-poco-x6frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Poco X6FRP Lock</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-personalized-instagram-notification-melodies/"><u>In 2024, Personalized Instagram Notification Melodies</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-secrets-of-the-trade-in-sourcing-professional-filmmakers/"><u>In 2024, Secrets of the Trade in Sourcing Professional Filmmakers</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-full-charge-indicators-for-modern-wins/"><u>Optimize Full Charge Indicators for Modern WINs</u></a></li>
<li><a href="https://win11.techidaily.com/the-invisible-hand-hidden-descriptors-for-folders-in-windows/"><u>The Invisible Hand: Hidden Descriptors for Folders in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-quintet-of-top-tier-write-enhancers-windows-edition/"><u>The Quintet of Top-Tier Write Enhancers (Windows Edition)</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unleash-efficient-communication-5-no-cost-ai-utilities-to-compose-elite-emails-using-chatgpt-and-summarize-messages/"><u>Unleash Efficient Communication: 5 No-Cost AI Utilities to Compose Elite Emails Using ChatGPT & Summarize Messages</u></a></li>
</ul></div>

