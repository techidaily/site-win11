---
title: "Guide: Setting Up or Removing Wi-Fi Cost Tracking in Win11"
date: 2024-06-25T09:47:16.520Z
updated: 2024-06-26T09:47:16.520Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Guide: Setting Up or Removing Wi-Fi Cost Tracking in Win11"
excerpt: "This Article Describes Guide: Setting Up or Removing Wi-Fi Cost Tracking in Win11"
keywords: Wi-Fi Cost Monitor,Win11 Cost Tracking,Wi-Fi Setup Guide,Remove Wi-Fi Meter,Windows Cost Control,Win11 Meter Removal,Wi-Fi Expense Tracker
thumbnail: https://thmb.techidaily.com/d2c52f6827b7d364ed0cc4d3f212393bb0ad8a3a90dc3d2a15bfc646351df71a.jpg
---

## Guide: Setting Up or Removing Wi-Fi Cost Tracking in Win11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

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

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

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
<li><a href="https://win11.techidaily.com/navigating-through-install-failed-messages-on-discord/"><u>Navigating Through Install Failed Messages on Discord</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-preventing-heat-in-w11-systems/"><u>Essential Steps for Preventing Heat in W11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-closed-caption-fixes-the-win11-way/"><u>Mastering Closed Caption Fixes: The Win11 Way</u></a></li>
<li><a href="https://win11.techidaily.com/uncluttered-windows-desktop-at-a-glance/"><u>Uncluttered Windows Desktop at a Glance</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-diskusage-in-windows-strategies-for-effective-drive-space-analysis/"><u>Decoding DiskUsage in Windows: Strategies for Effective Drive Space Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-experience-7-fixes-for-broken-apps/"><u>Seamless Windows Experience: 7 Fixes for Broken Apps</u></a></li>
<li><a href="https://win11.techidaily.com/prime-time-performance-top-5-wins-speed-up-solutions/"><u>Prime Time Performance: Top 5 Win's Speed-Up Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-note-placement-in-the-windows-desktop/"><u>Navigating Note Placement in the Windows Desktop</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/achieve-maximum-impact-in-fb-video-ads-use-free-tools-for-2024/"><u>Achieve Maximum Impact in FB Video Ads - Use Free Tools for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-12-passcode-screen-by-drfone-ios/"><u>How to Unlock iPhone 12 Passcode Screen?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/walls-and-windows-selecting-the-best-online-laps-background-sources/"><u>Walls & Windows  Selecting the Best Online Laps Background Sources</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-evaluating-the-leading-video-calling-platforms-for-tech-enthusiasts/"><u>[Updated] Evaluating the Leading Video Calling Platforms for Tech Enthusiasts</u></a></li>
<li><a href="https://fox-direct.techidaily.com/gaming-frontier-exploration-premium-oculus-players-guide/"><u>Gaming Frontier Exploration  Premium Oculus Players Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-cerebral-quests-the-ultimate-list-of-escape-rooms-for-2024/"><u>[New] Cerebral Quests  The Ultimate List of Escape Rooms for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-streamline-and-slim-vids-instagram-tips-using-macos/"><u>2024 Approved  Streamline and Slim Vids  Instagram Tips Using macOS</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-unveiling-youtubes-behind-the-scenes-editor-space/"><u>[New] Unveiling YouTube's Behind-the-Scenes Editor Space</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-conquer-the-world-of-video-downloads-software-or-freely-whats-best-for-you-for-2024/"><u>[Updated] Conquer the World of Video Downloads  Software or Freely, What's Best for You for 2024</u></a></li>
</ul></div>
