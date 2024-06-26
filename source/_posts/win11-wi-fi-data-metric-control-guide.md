---
title: Win11 Wi-Fi Data Metric Control Guide
date: 2024-06-25T09:44:20.771Z
updated: 2024-06-26T09:44:20.771Z
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
<li><a href="https://win11.techidaily.com/outsmart-windows-delete-temp-files-without-fuss/"><u>Outsmart Windows: Delete Temp Files Without Fuss</u></a></li>
<li><a href="https://win11.techidaily.com/enhanced-workflows-via-custom-task-integration-into-explorer-menus/"><u>Enhanced Workflows via Custom Task Integration Into Explorer Menus</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-alt-code-not-responding-on-windows-pc/"><u>Overcoming ALT Code Not Responding on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-incorporating-copy-and-move-commands-in-win-11/"><u>Step-by-Step Guide: Incorporating Copy & Move Commands in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/terminal-insight-discover-public-ip-in-windows-1110/"><u>Terminal Insight: Discover Public IP in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-code-of-windowsstore-folder-protection/"><u>Breaking the Code of WindowsStore Folder Protection</u></a></li>
<li><a href="https://win11.techidaily.com/get-across-taskbar-and-tile-adjustments-fast/"><u>Get Across Taskbar & Tile Adjustments Fast</u></a></li>
<li><a href="https://win11.techidaily.com/unwrapping-and-solving-isdonedll-failures-in-w10w11-oses/"><u>Unwrapping and Solving ISDone.dll Failures in W10/W11 OSes</u></a></li>
<li><a href="https://win11.techidaily.com/the-hackers-guide-to-swiftly-executing-windows-actions/"><u>The Hacker's Guide to Swiftly Executing Windows Actions</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-fix-wrongly-entered-characters-in-windows/"><u>Tips to Fix Wrongly Entered Characters in Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-unlocking-fcpx-advanced-freeze-frame-and-slow-motion-techniques/"><u>Updated Unlocking FCPX Advanced Freeze Frame and Slow Motion Techniques</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-videotoaudiotweeter-direct-output-for-2024/"><u>[Updated] VideoToAudioTweeter  Direct Output for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-samsung-galaxy-z-flip-5-by-fonelab-android-recover-photos/"><u>How To  Restore Missing Photos Files from Samsung Galaxy Z Flip 5.</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-navigating-through-channels-aesthetics-with-these-tools/"><u>In 2024, Navigating Through Channels' Aesthetics with These Tools</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-premier-selection-of-11-costless-yt-moniker-makers/"><u>[New] The Premier Selection of 11 Costless YT Moniker Makers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-craft-your-contents-voyage-from-camera-to-instagram-tv/"><u>[Updated] 2024 Approved  Craft Your Content's Voyage From Camera to Instagram TV</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Samsung Galaxy A54 5G | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/photo-mastery-top-8-web-based-creation-suite-for-2024/"><u>Photo Mastery  Top 8 Web-Based Creation Suite for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/pioneering-film-making-skills-through-youtube-videos-for-2024/"><u>Pioneering Film Making Skills Through YouTube Videos for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/playing-halted-a6400-video-viewing-woes/"><u>Playing Halted  A6400 Video Viewing Woes</u></a></li>
</ul></div>
