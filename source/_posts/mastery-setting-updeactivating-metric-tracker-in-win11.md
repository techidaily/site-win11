---
title: "Mastery: Setting Up/Deactivating Metric Tracker in Win11"
date: 2024-07-02T13:01:35.859Z
updated: 2024-07-03T13:01:35.859Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastery: Setting Up/Deactivating Metric Tracker in Win11"
excerpt: "This Article Describes Mastery: Setting Up/Deactivating Metric Tracker in Win11"
keywords: Win11 Tracker Setup Guide,Deactive Metric Tracking,Win11 Performance Monitoring,Setting Up Win11 Tracker,Disable Win11 Metrics,Win11 Tracker Configuration,Optimize Win11 Metric System
thumbnail: https://thmb.techidaily.com/bd1f3164b21938808543fb77a181f9a976b01572cf9b49cfe1852edc61f82d53.jpg
---

## Mastery: Setting Up/Deactivating Metric Tracker in Win11

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
<li><a href="https://win11.techidaily.com/essential-4-password-guardians-elevating-windows-11-security/"><u>Essential 4 Password Guardians Elevating Windows 11 Security</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-vm-picks-to-enhance-your-windows-11-experience/"><u>Ideal VM Picks to Enhance Your Windows 11 Experience</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-screen-snapshotting-4-key-strategies-for-windows-users/"><u>Mastering the Art of Screen Snapshotting: 4 Key Strategies for Windows Users.</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-attaching-notes-to-windows-apps/"><u>The Art of Attaching Notes to Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-requires-elevation-puzzle-win-11s-error-740-solution/"><u>Unraveling the Requires Elevation Puzzle: Win 11'S Error #740 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/set-windows-clock-without-automatic-regional-switching/"><u>Set Windows Clock Without Automatic Regional Switching</u></a></li>
<li><a href="https://win11.techidaily.com/1719319611800-overcoming-challenges-in-full-screen-snip-and-sketch-capturing/"><u>Overcoming Challenges in Full-Screen Snip & Sketch Capturing.</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-systray-information-showcasing-cpu-and-ram-in-ui/"><u>Elevate SysTray Information: Showcasing CPU & RAM in UI</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/unlocking-engagement-the-value-of-paying-for-youtube-watch-time/"><u>Unlocking Engagement  The Value of Paying for YouTube Watch Time?</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-the-art-of-effortless-video-size-transformation-on-macos/"><u>In 2024, The Art of Effortless Video Size Transformation on MacOS</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-final-cut-pro-x-troubleshooting-handbook-fixing-common-issues/"><u>New In 2024, Final Cut Pro X Troubleshooting Handbook Fixing Common Issues</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-11-essential-drone-gear-for-your-phantom-4/"><u>[Updated] 11 Essential Drone Gear for Your Phantom 4</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-the-future-of-soundscape-engineering-navigating-through-film-and-video-to-uncover-audio-for-2024/"><u>New The Future of Soundscape Engineering Navigating Through Film and Video to Uncover Audio for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-samsung-galaxy-xcover-7-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Samsung Galaxy XCover 7 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-tecno-spark-10-pro-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Tecno Spark 10 Pro Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-quick-shot-guide-for-chromebook-users/"><u>2024 Approved  Quick Shot Guide for Chromebook Users</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-what-is-the-best-video-format-for-youtube-for-2024/"><u>[Updated] What Is the Best Video Format for YouTube for 2024</u></a></li>
</ul></div>
