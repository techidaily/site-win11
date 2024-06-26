---
title: "Mastery: Setting Up/Deactivating Metric Tracker in Win11"
date: 2024-06-25T10:30:44.943Z
updated: 2024-06-26T10:30:44.943Z
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
<li><a href="https://win11.techidaily.com/secure-edge-with-microsofts-advanced-protection-technology-aguard-on-windows-11/"><u>Secure Edge with Microsoft's Advanced Protection Technology (Aguard) on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-and-configuring-windows-sandbox-in-win-11/"><u>Enabling and Configuring Windows Sandbox in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/setting-updeactivating-wi-fi-data-tracking-on-windows-11/"><u>Setting Up/Deactivating Wi-Fi Data Tracking on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/proven-windows-11-ways-to-boost-workflow-and-productivity-45/"><u>Proven Windows 11 Ways to Boost Workflow and Productivity (45)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-temporarily-turn-off-your-pcs-firewall/"><u>How to Temporarily Turn Off Your PC's Firewall</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-interruption-nightmares-keeping-your-ps4-remote-connected/"><u>Overcoming Interruption Nightmares: Keeping Your PS4 Remote Connected</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-keep-windows-open-avoid-lockout-feature/"><u>How To Keep Windows Open: Avoid Lockout Feature</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-a-dormant-services-console-a-list-of-7-restoration-techniques/"><u>Reviving a Dormant Services Console: A List of 7 Restoration Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-gaming-with-dxvk-the-windows-perspective/"><u>Revolutionizing Gaming with DXVK - The Windows Perspective</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-discover-the-best-vsdc-video-editor-alternatives-for-mac-computers/"><u>In 2024, Discover the Best VSDC Video Editor Alternatives for Mac Computers</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-samsung-galaxy-f34-5g-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Samsung Galaxy F34 5G | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-innovative-windows-podcast-solutions-top-8-cutting-edge-apps/"><u>[Updated] Innovative Windows Podcast Solutions  Top 8 Cutting-Edge Apps</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-gain-more-traction-on-tiktok-a-compendium-of-unique-username-concepts-for-2024/"><u>[Updated] Gain More Traction on TikTok  A Compendium of Unique Username Concepts for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-shot-matchmaking-optimal-gimbals-for-dslr-quality-vids/"><u>Best Shot Matchmaking  Optimal Gimbals for DSLR-Quality Vids</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-realme-c51-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Realme C51 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-premier-editing-software-for-mobile-app-creation/"><u>In 2024, Premier Editing Software for Mobile App Creation</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-lava-blaze-pro-5g-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Lava Blaze Pro 5G Device SIM</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-hit-tracks-at-your-disposal-10-prime-tools-for-capturing-and-storing-favorite-songs-with-ease/"><u>New Hit Tracks at Your Disposal 10 Prime Tools for Capturing and Storing Favorite Songs with Ease</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-mastering-the-art-of-iphone-speech-capture/"><u>[Updated] Mastering the Art of iPhone Speech Capture</u></a></li>
</ul></div>
