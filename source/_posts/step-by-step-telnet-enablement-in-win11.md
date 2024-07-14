---
title: "Step-by-Step: Telnet Enablement in Win11"
date: 2024-07-13T10:32:31.301Z
updated: 2024-07-14T10:32:31.301Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Telnet Enablement in Win11"
excerpt: "This Article Describes Step-by-Step: Telnet Enablement in Win11"
keywords: Win11 Telnet Setup Guide,Enabling Telnet Windows 11,Stepwise Telnet Activation WS11,Win11 Telnet Configuration Tutorial,Telnet in Windows 11 Easy Steps,Enable Telnet Service WS11,Win11 Guide
thumbnail: https://thmb.techidaily.com/e77b802386df347968174243d9eec6b1ff5aaa13a757fb94ecaebe8d1775e8b5.jpg
---

## Step-by-Step: Telnet Enablement in Win11

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it [add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  
![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

## 2\. Enable Telnet Client Using Windows PowerShell

![enable telnet client powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-powershell.jpg)

 You can use the Enable-WindowsOptionalFeature cmdlet to enable Telnet Client using Windows PowerShell. Useful if you are unable to turn on the feature using the Windows Features dialog and it is also faster than the GUI method.

To enable Telnet using Windows PowerShell:

1. Press**Win + X** to open the**WinX** menu.
2. Click on**Windows Terminal(Admin)** and click**Yes** to open the terminal app as administrator. If you are using Windows 10, type**PowerShell** in**Windows Search** and open**Windows PowerShell** administrator.
3. In the PowerShell window, type the following command and press**Enter** to enable Telnet:  
`Enable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
4. This process may take several minutes, so wait for it to complete and return a status report. If successful, you’ll see the result as**Online:True.**
5. If you want to disable Telnet Client, use the following command instead:  
`Disable-WindowsOptionalFeature -Online -FeatureName TelnetClient`
6. Close PowerShell and restart your PC.

## 3\. Install Telnet Client Using Command Prompt

![enable telnet command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-command-prompt.jpg)

 If you prefer Command Prompt over PowerShell, you can use the DISM /Online command to enable the optional features on your Windows 11 computer.

Follow these steps to install Telnet using Command Prompt:

1. Press the**Win** key and type**cmd** .
2. Right-click on**Command Prompt** and select**Run as administrator.**
3. In the Command Prompt window, type the following command and press**Enter** :  
`dism /online /Enable-Feature /FeatureName:TelnetClient`
4. Command Prompt will start enabling the feature and display the operation completed successfully message.
5. If you need to disable Telnet, type the following command and press**Enter** :  
`dism /Online /Disable-Feature /FeatureName:TelnetClient`
6. Wait for the success message.
7. Type**exit** and press**Enter** to close Command Prompt.

## How to Check the Telnet Client Status on Your PC

![telnet status enabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/telnet-status-enabled.jpg)

 You can check if the Telnet client is enabled on your PC using a Command Prompt command. When enabled, the Telnet command will open a new CMD to connect to remote servers and perform other tasks.

1. Launch Command Prompt as administrator (see [how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

## All the Ways to Enable Telnet On Your Windows 11 Computer

 Telnet is a built-in remote access utility that you can use to troubleshoot firewall and network issues. While it is still part of Windows, system administrators now prefer the more secure SSH protocol to access computers over an unsecured network.

 The major disadvantage of Telnet is that it is not secure and prone to a man-in-the-middle attack. If not for particular situations, switch to a more secure network protocol such as SSH and Mosh with better password and public key authentication.


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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-premium-top-11-list-audio-recording-essentials/"><u>[New] 2024 Approved  Premium Top 11 List - Audio Recording Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-metered-connection-for-wifi-networks-on-win11/"><u>Configuring Metered Connection for Wifi Networks on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-synapse-glitches-on-w11-and-w10/"><u>How to Mend Synapse Glitches on W11 and W10</u></a></li>
<li><a href="https://network-issues.techidaily.com/winrts-errors-eradicated-with-new-tools/"><u>WinRTS Errors Eradicated with New Tools</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-11-writable-driver-verifier/"><u>Activating Windows 11' Writable Driver Verifier</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-non-persistent-nvidia-panel-changes/"><u>Correcting Non-Persistent Nvidia Panel Changes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/audible-allure-choosing-background-beats-for-videos/"><u>Audible Allure  Choosing Background Beats for Videos</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-new-folders-into-explorers-interface/"><u>Incorporating New Folders Into Explorer's Interface</u></a></li>
<li><a href="https://win11.techidaily.com/circumvent-unauthorized-windows-login-errors-easy-guide/"><u>Circumvent Unauthorized Windows Login Errors (Easy Guide)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-unterminated-process-failures-in-windows/"><u>How to Resolve Unterminated Process Failures in Windows</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-enhance-your-photo-game-with-top-editors/"><u>[New] 2024 Approved  Enhance Your Photo Game with Top Editors</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-update-checks-with-these-9-fixes-on-windows-setup/"><u>Accelerate Update Checks with These 9 Fixes on Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-system-safe-spotting-hidden-threats-in-windows/"><u>Keep Your System Safe: Spotting Hidden Threats in Windows</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-chilly-competition-unveiling-highlights-of-2022s-snowboard-cross-showdown/"><u>In 2024, Chilly Competition  Unveiling Highlights of 2022'S Snowboard Cross Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-processor-limits-in-power-options-menu/"><u>Demystifying Processor Limits in Power Options Menu</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-invalid-profile-on-windows-11-systems/"><u>How to Tackle 'Invalid Profile' On Windows 11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-insufficient-ram-warning-for-hogwarts-simulator/"><u>Fixing Insufficient RAM Warning for Hogwarts Simulator</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-best-places-for-downloading-free-lofi-imagery-and-tunes/"><u>2024 Approved Best Places for Downloading Free Lofi Imagery and Tunes</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-prior-to-starting-the-window-operating-system-renewal/"><u>Key Steps Prior to Starting the Window Operating System Renewal</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-mending-the-internal-error-in-rdp-on-windows-11-and-11-pro/"><u>Guide to Mending the Internal Error in RDP on Windows 11 & 11 Pro</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-agni-2-5g-by-fonelab-android-recover-video/"><u>How to recover old videos from your Agni 2 5G</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-iphone-photography-excellence-follow-the-top-10-rules/"><u>[New] IPhone Photography Excellence  Follow the Top 10 Rules</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-failure-codes-0x80072f8f/"><u>Addressing Windows Failure Codes: 0X80072f8f</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-free-mac-friendly-tiktok-video-crafting-tools-top-10/"><u>[Updated] Free, Mac-Friendly TikTok Video Crafting Tools (Top 10)</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-subscribers-guide-to-effective-dialogue-on-youtube/"><u>In 2024, The Subscriber's Guide to Effective Dialogue on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/1719352195023-quick-fixes-for-your-windows-hurdles-and-complications/"><u>Quick Fixes for Your Windows Hurdles & Complications</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-overlooked-windows-extras-a-step-by-step-manual/"><u>Enabling Overlooked Windows Extras: A Step-by-Step Manual</u></a></li>
<li><a href="https://win11.techidaily.com/guide-accessing-and-opening-verifier-manager-w11/"><u>Guide: Accessing and Opening Verifier Manager W11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/need-a-change-from-sony-vegas-check-out-these-top-windows-alternatives-for-2024/"><u>Need a Change From Sony Vegas? Check Out These Top Windows Alternatives for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-screen-seizing-specialists-the-best-browser-recorder-tools-ranked/"><u>[New] In 2024, Screen Seizing Specialists  The Best Browser Recorder Tools Ranked</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-s-top-picks-movie-trailer-editors-for-mac-and-windows-for-2024/"><u>New S Top Picks Movie Trailer Editors for Mac and Windows for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-reactivating-razer-device-detection-by-synapse-software/"><u>Solutions for Reactivating Razer Device Detection by Synapse Software</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-11-and-11-desktop-context-menu-not-working/"><u>How to Fix the Windows 11 & 11 Desktop Context Menu Not Working</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-vpn-network-disconnection-on-a-remote-work-pc/"><u>Fixing VPN Network Disconnection on a Remote Work PC</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-remove-iphone-13-mini-device-from-icloud-by-drfone-ios/"><u>In 2024, How to Remove iPhone 13 mini Device from iCloud</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-initiating-your-journey-with-wave-editors-tips-and-tricks-for-aspiring-audio-editors/"><u>Updated In 2024, Initiating Your Journey with Wave Editors Tips and Tricks for Aspiring Audio Editors</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-easily-uninstall-applications-in-win-11/"><u>Breaking Barriers: Easily Uninstall Applications in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-workflow-with-top-windows-to-do-apps/"><u>Enhance Your Workflow with Top Windows To-Do Apps</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-and-set-up-windows-sandbox-in-windows-11/"><u>How to Enable and Set Up Windows Sandbox in Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-pictures-from-motorola-razr-40-ultra-by-fonelab-android-recover-pictures/"><u>Best Android Data Recovery - Retrieve Lost Pictures from Motorola Razr 40 Ultra.</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-harmonizing-visuals-and-audio-the-impact-of-piano-compositions-in-film-production-for-2024/"><u>Updated Harmonizing Visuals and Audio The Impact of Piano Compositions in Film Production for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-navigating-board-usage-a-universal-guide-for-ios-android-and-windows-platforms/"><u>[New] 2024 Approved  Navigating Board Usage  A Universal Guide for iOS, Android & Windows Platforms</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-encompassing-angle-video-systems/"><u>2024 Approved  Encompassing Angle Video Systems</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-step-by-step-to-stunning-photomontages/"><u>[Updated] Step-by-Step to Stunning Photomontages</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-cutting-edge-techniques-for-incorporating-soundtracks-in-youtube-creations/"><u>[Updated] 2024 Approved  Cutting-Edge Techniques for Incorporating Soundtracks in YouTube Creations</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-google-pixel-8-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Google Pixel 8 Devices | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-dive-into-the-world-of-youtube-on-facebook-video-content/"><u>[New] In 2024, Dive Into the World of YouTube on Facebook Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/from-iphone-to-desktop-syncing-ios-calendar-with-windows-1011/"><u>From iPhone to Desktop: Syncing iOS Calendar with Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-restoring-windows-11-search-efficiency/"><u>Essential Tips: Restoring Windows 11 Search Efficiency</u></a></li>
</ul></div>
