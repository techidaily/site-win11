---
title: Win11 Wi-Fi Data Metric Control Guide
date: 2024-07-13T09:46:48.613Z
updated: 2024-07-14T09:46:48.613Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Win11 Wi-Fi Data Metric Control Guide
excerpt: This Article Describes Win11 Wi-Fi Data Metric Control Guide
keywords: Win11 Wi-Fi Guide,Data Monitoring Win11,Wi-Fi Management Tool,Win11 Network Diagnostics,Data Usage Control Win11,Win11 Wi-Fi Optimization,Metric Analysis Win11
thumbnail: https://thmb.techidaily.com/75030bd59360efbfc2946329061573b90f37300b7251c4b711e0f5f10f28322c.jpg
---

## Win11 Wi-Fi Data Metric Control Guide

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to [launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the [Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

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

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on [the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

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
<li><a href="https://win11.techidaily.com/overcoming-camera-app-error-0xa00f425d-in-windows-11/"><u>Overcoming Camera App Error 0xA00F425D in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/revealing-how-ai-pcs-outperform-standard-computers/"><u>Revealing How AI PCs Outperform Standard Computers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-non-recognized-ports-and-devices-on-windows-11/"><u>How to Fix Non-Recognized Ports and Devices on Windows 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/the-pros-and-cons-of-final-cut-pro-vs-final-cut-express/"><u>The Pros and Cons of Final Cut Pro vs Final Cut Express</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-using-windows-11-snap-features/"><u>Essential Tips for Using Windows 11 Snap Features</u></a></li>
<li><a href="https://win11.techidaily.com/eye-catching-laptops-exhibited-at-ifa-2023/"><u>Eye-Catching Laptops Exhibited at IFA 2023</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-growing-engagement-ethically-youtube-success-stories/"><u>[Updated] 2024 Approved  Growing Engagement Ethically  YouTube Success Stories</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-better-performance-on-roblox-windows-edition/"><u>Elevate Your Gaming: Better Performance on Roblox Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-false-negatives-restoring-accurate-game-status-in-discord-windows/"><u>Eliminating False Negatives: Restoring Accurate Game Status in Discord (Windows)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-expert-tips-for-blending-multiple-hdr-photographs-in-lightroom/"><u>In 2024, Expert Tips for Blending Multiple HDR Photographs in Lightroom</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-package-registration-problems-on-windows-devices/"><u>Eliminating Package Registration Problems on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-booting-procedures-complete-guide/"><u>Navigating Windows' Booting Procedures Complete Guide</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unbidden-command-window-activations/"><u>Preventing Unbidden Command Window Activations</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-1110-app-installation-obstacles-in-oculus/"><u>Overcoming Windows 11/10 App Installation Obstacles in Oculus</u></a></li>
<li><a href="https://win11.techidaily.com/from-concept-to-reality-paving-new-ways-in-windows-11-widgets/"><u>From Concept to Reality: Paving New Ways in Windows 11 Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/quantify-windows-computer-power-usage-for-optimization/"><u>Quantify Windows Computer Power Usage for Optimization</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-winget-a-guide-for-windows-11-users/"><u>Reviving Winget: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-vivo-y100i-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Vivo Y100i FRP Without Computer</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-linux-capabilities-through-windows-software/"><u>Elevating Linux Capabilities Through Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/no-window-no-problem-master-the-art-of-reviving-hidden-apps-on-win-1011-with-6-tactics/"><u>No Window, No Problem! Master the Art of Reviving Hidden Apps on Win 10/11 with 6 Tactics</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-dialing-up-the-drama-captivating-tiktok-intros-via-mac/"><u>[New] 2024 Approved  Dialing Up the Drama  Captivating TikTok Intros via Mac</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-silent-speaker-issue-in-win11-environments/"><u>Resolving Silent Speaker Issue in Win11 Environments</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-poco-f5-5g-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Poco F5 5G in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-live-to-share-top-tech-for-high-quality-youtube-livestreams/"><u>In 2024, Live to Share  Top Tech For High-Quality YouTube Livestreams</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-unresponsive-mail-alerts-on-windows-11/"><u>How to Overcome Unresponsive Mail Alerts on Windows 11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/how-to-optimize-rl-recording-hardware-and-software-for-2024/"><u>How to Optimize RL Recording Hardware & Software for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/opera-on-windows-thwarting-the-downloading-dilemma/"><u>Opera on Windows: Thwarting the Downloading Dilemma</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-mastering-facebook-visuals-adding-text-boxes-and-dark-bar-overlays/"><u>In 2024, Mastering Facebook Visuals  Adding Text Boxes & Dark Bar Overlays</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11s-seamless-program-deployment/"><u>Navigating Windows 11'S Seamless Program Deployment</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-memory-and-cpu-for-streamers-on-w11/"><u>Optimizing Memory & CPU for Streamers on W11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-error-nvidia-geforce-x0001/"><u>Overcoming Windows 11 Error: Nvidia GeForce X0001</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-local-devices-avoid-in-use-names-errors/"><u>Overcoming Windows' Local Devices: Avoid In-Use Names Errors</u></a></li>
<li><a href="https://games-able.techidaily.com/3-quick-fixes-for-recognizing-unplugged-headsets-on-xbox/"><u>3 Quick Fixes for Recognizing Unplugged Headsets on Xbox</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-get-assistance-problems/"><u>Overcoming Windows 11 'Get Assistance' Problems</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-windows-speaker-recognition-errors/"><u>Rectifying Windows Speaker Recognition Errors</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-diy-guide-to-turning-youtube-screen-time-into-a-free-screencast/"><u>2024 Approved  DIY Guide to Turning YouTube Screen Time Into a FREE Screencast</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-vivo-v27e-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Vivo V27e | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/hiding-archives-within-pictures-techniques-for-windows-users/"><u>Hiding Archives Within Pictures: Techniques for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-self-triggered-command-prompt-issues/"><u>Fixing Self-Triggered Command Prompt Issues</u></a></li>
</ul></div>
