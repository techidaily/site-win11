---
title: "Mastery: Setting Up/Deactivating Metric Tracker in Win11"
date: 2024-07-13T10:39:37.201Z
updated: 2024-07-14T10:39:37.201Z
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
<li><a href="https://win11.techidaily.com/8-microsoft-apps-you-must-install-on-android-if-you-have-a-windows-pc/"><u>8 Microsoft Apps You Must Install on Android if You Have a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-way-for-printer-use-by-one-pc-only/"><u>Clearing the Way for Printer Use by One PC Only</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-cut-edit-and-share-the-best-free-open-source-video-editors/"><u>2024 Approved Cut, Edit, and Share The Best Free Open-Source Video Editors</u></a></li>
<li><a href="https://win11.techidaily.com/skyrim-booster-issues-windows-repair-guide/"><u>Skyrim Booster Issues: Windows Repair Guide</u></a></li>
<li><a href="https://win11.techidaily.com/proactive-strategies-to-unlock-computer-management-interface/"><u>Proactive Strategies to Unlock Computer Management Interface</u></a></li>
<li><a href="https://driver-install.techidaily.com/gtx-970-gpu-upgrade-guide-for-windows-11-users/"><u>GTX 970 GPU Upgrade Guide for Windows 11 Users</u></a></li>
<li><a href="https://screen-recording.techidaily.com/exclusive-choices-to-replace-traditional-fbx-recorder-games/"><u>Exclusive Choices to Replace Traditional FBX Recorder Games</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-display-management-in-windows-11/"><u>Understanding Display Management in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-gpu-usage-in-windows-desktop-window/"><u>Decreasing Excessive GPU Usage in Windows Desktop Window</u></a></li>
<li><a href="https://win11.techidaily.com/craft-a-personalized-windows-console-experience/"><u>Craft a Personalized Windows Console Experience</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-the-blueprint-for-traffic-boost-masterful-techniques-for-effective-fb-videos-for-2024/"><u>[New] The Blueprint for Traffic Boost  Masterful Techniques for Effective FB Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-5-best-auto-clickers-with-hotkeys-for-windows/"><u>The 5 Best Auto Clickers With Hotkeys for Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-2023s-leading-browser-extensions-for-video-streaming/"><u>[Updated] 2024 Approved  2023'S Leading Browser Extensions for Video Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/1719374785731-unlock-additional-space-on-your-windows-system-for-free/"><u>Unlock Additional Space on Your Windows System, For Free!</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instagram-video-editor-how-to-edit-instagram-video-for-2024/"><u>Instagram Video Editor  How to Edit Instagram Video for 2024</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/championing-the-best-3-sites-master-a-new-language-today/"><u>Championing the Best 3 Sites: Master a New Language Today</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-crafting-crisp-audio-a-detailed-guide-to-de-emphasizing-vocals-in-adobe-audition-tracks/"><u>Updated Crafting Crisp Audio A Detailed Guide to De-Emphasizing Vocals in Adobe Audition Tracks</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-find-hidden-watch-tile-artwork-for-2024/"><u>[New] Find Hidden Watch Tile Artwork for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-omegle-explored-understanding-the-platform-its-community-dynamics-and-safety-protocols-for-2024/"><u>New Omegle Explored Understanding the Platform, Its Community Dynamics & Safety Protocols for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-2024-approved-top-6-best-free-divx-video-cutters/"><u>New 2024 Approved Top 6 Best Free Divx Video Cutters</u></a></li>
<li><a href="https://win11.techidaily.com/secure-app-locations-in-windows-task-management/"><u>Secure App Locations in Windows Task Management</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/iphone-shutterbug-secrets-perfecting-reflections-in-water-for-2024/"><u>IPhone Shutterbug Secrets  Perfecting Reflections in Water for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-precise-documentation-how-to-record-full-fbm-calls-for-2024/"><u>[New] Precise Documentation  How to Record Full FBM Calls for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-tackle-zeroxc000003e-application-errors-in-win1011/"><u>Strategies to Tackle ZeroXc000003e Application Errors in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-removing-null-space-in-your-system-drive/"><u>Step-by-Step Guide: Removing Null Space in Your System Drive</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-streamlined-social-integration-linktree-and-tiktok-profiles-united/"><u>[Updated] Streamlined Social Integration  Linktree and TikTok Profiles United</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-mastering-the-art-of-viewing-youtube-video-reactions-and-votes/"><u>[New] Mastering the Art of Viewing YouTube Video Reactions and Votes</u></a></li>
<li><a href="https://win11.techidaily.com/system-fixes-for-error-0x800700e1-in-windows-11/"><u>System Fixes for Error 0X800700E1 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-void-recovering-startups-on-windows/"><u>Bridging the Void: Recovering Startups on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/trick-to-invoke-admin-level-powershell-on-your-win11-pc/"><u>Trick to Invoke Admin-Level PowerShell on Your Win11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-the-invalid-token-reference-in-modern-oses/"><u>Dealing with the Invalid Token Reference in Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-settings-error-in-nvidias-geforce-app-windows-11/"><u>Steps to Overcome 'Settings Error' In NVIDIA's GeForce App (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/10-solutions-for-stuck-pin-locks-on-windows/"><u>10 Solutions for Stuck PIN Locks on Windows</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-enchanting-escapades-childhood-playtime-picks/"><u>[New] Enchanting Escapades  Childhood Playtime Picks</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-menu-unlocking-ancestral-functions/"><u>Windows 11'S Menu: Unlocking Ancestral Functions</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-geforce-0x0001-in-windows-1011-environment/"><u>Addressing GeForce 0X0001 in Windows 10/11 Environment</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-hdr-rating-does-aurora-deliver-quality/"><u>[New] HDR Rating  Does Aurora Deliver Quality?</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-the-pathway-to-popularity-strategies-for-soaring-viewership/"><u>[Updated] The Pathway to Popularity  Strategies for Soaring Viewership</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-ceasing-wired-pc-keyboard-on-windows/"><u>Tutorial: Ceasing Wired PC Keyboard on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/switching-notepad-to-dark-mode-on-windows-11plus/"><u>Switching Notepad to Dark Mode on Windows 11+</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-instagram-sound-essentials-for-personalization/"><u>2024 Approved  Instagram Sound Essentials for Personalization</u></a></li>
<li><a href="https://win11.techidaily.com/the-financial-backbone-of-microsofts-windows-11/"><u>The Financial Backbone of Microsoft's Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-ties-with-windows-11-store/"><u>Cutting Ties with Windows 11 Store</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-setup-for-windows-11-install-craft-usb-in-just-three-ways/"><u>Rapid Setup for Windows 11 Install: Craft USB in Just Three Ways</u></a></li>
<li><a href="https://extra-information.techidaily.com/a-step-by-step-to-achieving-realism-in-photoshop-artwork/"><u>A Step-by-Step to Achieving Realism in Photoshop Artwork</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-11-arm-installation-via-iso-download/"><u>Seamless Windows 11 ARM Installation via ISO Download</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-unlock-windows-defense-against-admins-choice/"><u>Techniques to Unlock Windows Defense Against Admins' Choice</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-premiere-pro-speed-blackouts/"><u>2024 Approved  Premiere Pro Speed Blackouts</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-secrets-of-devhome-in-windows-11/"><u>Deciphering the Secrets of DevHome in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-immersive-surround-sound-incorporating-atmos-into-win-1011/"><u>Achieve Immersive Surround Sound: Incorporating Atmos Into Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/restart-windows-paper-processor/"><u>Restart Windows' Paper Processor</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-steam-e84-glitches-on-windows-systems/"><u>Overcoming Steam E84 Glitches on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-interruptions-during-steam-video-streaming/"><u>Preventing Interruptions During Steam Video Streaming</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-quickly-speed-up-or-decelerate-videos-for-peak-engagement/"><u>In 2024, Quickly Speed Up or Decelerate Videos for Peak Engagement</u></a></li>
</ul></div>
