---
title: "Mastery: Controlling Data Metering for Your Wi-Fi Connection"
date: 2024-11-27T04:19:55.330Z
updated: 2024-11-27T20:24:58.688Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastery: Controlling Data Metering for Your Wi-Fi Connection"
excerpt: "This Article Describes Mastery: Controlling Data Metering for Your Wi-Fi Connection"
keywords: Wi-Fi Meter Control,Data Metering Mastery,Wi-Fi Connections Monitor,Manage Wi-Fi Metrics,Optimize Wi-Fi Data Usage,Streamline Wi-Fi Networks,Enhance Wi-Fi Performance
thumbnail: https://thmb.techidaily.com/0004bab4ed76fb3b0e7b5e78faee5c8cd34739a5594338591ba06831ec971383.jpg
---

## Mastery: Controlling Data Metering for Your Wi-Fi Connection

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-knowledge.techidaily.com/2024-approved-unlocking-visual-potential-a-step-by-step-guide-to-video-enhancer-22/"><u>2024 Approved Unlocking Visual Potential A Step-by-Step Guide to Video Enhancer 2.2</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/amds-ryzen-ai-9-hx-aster-apples-m3-max-in-speed-a-deep-dive-into-single-core-benchmark-results/"><u>AMD's Ryzen AI 9 HX Aster Apple's M3 Max in Speed - A Deep Dive Into Single-Core Benchmark Results</u></a></li>
<li><a href="https://win11.techidaily.com/bring-back-vibrancy-to-windows-extended-volume-controls/"><u>Bring Back Vibrancy to Windows’ Extended Volume Controls</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-alive-silent-office-outlook-mail-feeds/"><u>Bringing Alive Silent Office Outlook Mail Feeds</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-windowed-world-exiting-wired-networks-at-100mbps/"><u>Bypassing the Windowed World: Exiting Wired Networks at 100Mbps</u></a></li>
<li><a href="https://win11.techidaily.com/changing-functionality-of-fn-keys-in-windows-11-pcs/"><u>Changing Functionality of FN Keys in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/chrome-notification-banishment-for-windows-users/"><u>Chrome Notification Banishment for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/circumventing-verification-failures-when-downloading-apps/"><u>Circumventing Verification Failures when Downloading Apps</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-cluttered-drives-the-defrag-walkthrough/"><u>Clearing Cluttered Drives: The Defrag Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-up-black-screen-problem-in-windows-marketplace/"><u>Clearing Up Black Screen Problem in Windows Marketplace</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-steps-for-successfully-installing-updated-cpu-drivers-on-windows-computers/"><u>Easy Steps for Successfully Installing Updated CPU Drivers on Windows Computers</u></a></li>
<li><a href="https://fox-http.techidaily.com/garagebands-easy-way-to-dull-down-noise-levels/"><u>Garageband's Easy Way to Dull Down Noise Levels</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-from-free-to-fiscal-determining-view-counts-for-youtube-earnings/"><u>In 2024, From Free to Fiscal Determining View Counts for YouTube Earnings</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-infinix-note-30i-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Infinix Note 30i Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-lock-your-vivo-y56-5g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Vivo Y56 5G Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210703544-9781959561163-laying-of-hands/"><u>Laying of Hands | Free Book</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-realme-gt-5-240w-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Realme GT 5 (240W)? | Dr.fone</u></a></li>
</ul></div>

