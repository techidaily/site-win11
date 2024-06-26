---
title: How to Adjust Metric Tracking Features for a Wi-Fi Network in Windows 11
date: 2024-06-25T11:42:00.586Z
updated: 2024-06-26T11:42:00.586Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Adjust Metric Tracking Features for a Wi-Fi Network in Windows 11
excerpt: This Article Describes How to Adjust Metric Tracking Features for a Wi-Fi Network in Windows 11
keywords: Wi-Fi Metrics Tuning,Win11 Wifi Tracker Settings,Wi-Fi Performance Optimization,Windows Network Adjustments,Gain Wi-Fi Data Insights,Wi-Fi Metrics Control,Wifi Settings Enhancement
thumbnail: https://thmb.techidaily.com/8605278b5d648a8e727674b42f156215fdccc4c56056b931eaef077a91501e84.jpg
---

## How to Adjust Metric Tracking Features for a Wi-Fi Network in Windows 11

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
<li><a href="https://win11.techidaily.com/enhancing-windows-steam-sound-fidelity/"><u>Enhancing Windows Steam Sound Fidelity</u></a></li>
<li><a href="https://win11.techidaily.com/deceleration-dilemnas-quick-fixes-for-discord-lag/"><u>Deceleration Dilemnas: Quick Fixes for Discord Lag</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-application-failures-due-to-net-not-installed/"><u>Addressing Application Failures Due to .NET Not Installed</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-address-app-support-issues-on-newer-windows/"><u>Techniques to Address App Support Issues on Newer Windows</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-password-protectionists-for-the-modern-windows-user/"><u>Masterful Password Protectionists for the Modern Windows User</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-system-use-a-guide-to-idle-shutdown-in-windows-11/"><u>Streamline System Use: A Guide to Idle Shutdown in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-boot-into-safe-mode-in-windows-11/"><u>6 Ways to Boot Into Safe Mode in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-w11-ui-aspects-that-seem-out-of-place/"><u>7 W11 UI Aspects That Seem Out of Place</u></a></li>
<li><a href="https://win11.techidaily.com/windows-wizardry-entering-control-panel-quickly/"><u>Windows Wizardry: Entering Control Panel Quickly</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/top-7-phone-number-locators-to-track-apple-iphone-14-pro-location-drfone-by-drfone-virtual-ios/"><u>Top 7 Phone Number Locators To Track Apple iPhone 14 Pro Location | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-get-more-video-views-on-youtube-for-2024/"><u>How To Get More Video Views on YouTube for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-do-i-sim-unlock-my-apple-iphone-6s-by-drfone-ios/"><u>In 2024, How Do I SIM Unlock My Apple iPhone 6s?</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-simplify-your-digital-life-5-essential-recording-strategies-web/"><u>[New] Simplify Your Digital Life  5 Essential Recording Strategies Web</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-discover-efficient-techniques-for-live-discord-recording-for-2024/"><u>[New] Discover Efficient Techniques for Live Discord Recording for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-join-the-social-gaming-movement-xbox-and-fb-livestreams/"><u>In 2024, Join the Social Gaming Movement  Xbox & FB Livestreams</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/tilizing-famebit-techniques-for-youtube-sponsorship-success/"><u>[New] Utilizing FameBit Techniques for YouTube Sponsorship Success</u></a></li>
<li><a href="https://techidaily.com/unlock-android-phone-if-you-don-t-have-motorola-edge-40-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Unlock android phone if you don't have Motorola Edge 40 fingerprint</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-profit-strategies-for-beauty-streams/"><u>2024 Approved  Profit Strategies for Beauty Streams</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-guide-on-how-to-enable-the-text-to-speech-function-on-iphone-for-2024/"><u>New Guide on How to Enable the Text to Speech Function on iPhone for 2024</u></a></li>
</ul></div>
