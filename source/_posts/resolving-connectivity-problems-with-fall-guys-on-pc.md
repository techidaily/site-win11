---
title: Resolving Connectivity Problems with Fall Guys on PC
date: 2024-07-13T10:26:06.759Z
updated: 2024-07-14T10:26:06.759Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Connectivity Problems with Fall Guys on PC
excerpt: This Article Describes Resolving Connectivity Problems with Fall Guys on PC
keywords: Fix Game Connections,PC Gaming Network Issues,Fall Guys Internet Troubleshoot,Tackle Connectivity in FGPC,Optimize Online Multiplayer,Enhance PC Game Links,Stabilize Fall Guys Connection
thumbnail: https://thmb.techidaily.com/8467c9e20d909c3a99e5604c440b3f79e42d4e9a9f150048899a6b75835712f0.jpg
---

## Resolving Connectivity Problems with Fall Guys on PC

 Connection errors are a real curse for online games like Fall Guys. Not only do they spoil the gaming mood, but they also stop you from continuing your ranked hot streak. Luckily, it's very easy to fix connection errors in Fall Guys.

 In this article, we'll see all the possible culprits behind a connection error in Fall Guys, along with ways to eliminate them. So, let's get started.

## What Causes a Connection Error in Fall Guys for Windows?

 It's very easy to log in to Fall Guys and play it on your computer. But if you're unable to log in and see a connection error, the following can be the reasons behind it:

1. Your internet connection is weak or unstable.
2. You're using a VPN or proxy server.
3. Windows Firewall is blocking Fall Guys from accessing the internet.

 Now that we know all the possible culprits behind the issue, let's jump into the fixes.

## 1\. Check Your Connection

 Before making any changes to your network settings, ensure that a weak internet connection is not causing the issue. You can check this by visiting an [internet-speed testing website](https://www.makeuseof.com/best-free-websites-test-internet-speed/) .

 If the results show that your connection is unstable and weak, then you'll have to troubleshoot your connection. Check out our guide on [network diagnostic tricks you can try](https://www.makeuseof.com/tag/7-simple-steps-diagnose-network-problem/) for ways to get your connection fixed again.

 f manual troubleshooting makes no difference, consider contacting your ISP.

## 2\. Close Network Hogging Applications from Background

 Connection errors in most online games often result from network-hogging applications running in the background. These applications consume most of the available bandwidth, leaving the main application (Fall Guys, in this case) with limited options.

 In this case, the best thing to do is to locate and close all such applications from the background. You can do this with the help of the Task Manager.

 To begin with,[launch the Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/) and look for applications consuming the maximum bandwidth. You can detect them by looking at the Network section. Note that the higher the network value, the more bandwidth the application consumes.

![End high network apps in Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/end-high-network-apps.jpg)

 Then, right-click on all such applications, and choose**End task.** After that, restart Fall Guys and check if the problem persists.

## 3\. Temporarily Disable the Windows Firewall

 Windows Firewall can interfere with the working of Fall Guys and cause connection errors. The solution, in this case, is to temporarily disable the Windows Firewall.

Here's how you can do that:

1. Open the**Windows Search** by pressing the**Win + S** hotkey, type**Windows Defender Firewall,** and press Enter.
2. Choose**Windows Defender Firewall on or off** in the left sidebar.  
![Turn Windows Defender on or off option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/turn-windows-defender-on-or-off.jpg)
3. Choose**Turn off Windows Defender Firewall (not recommended)** option for both**private** and**public** network settings.  
![Turn off firewall option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/turn-off-firewall.jpg)

 Now, check if the problem continues. If not, enable the Windows Defender Firewall and then add Fall Guys to the Windows Firewall exception list. Here's how:

1. In the Windows Search, type**Allow an app through Windows Firewall** and press**Enter** .
2. Click the**Change settings** button and then choose the**Allow another app** option.
3. Click**Browse** from the window that crops up.  
![Browse option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/browse-option.jpg)
4. Go to the Fall Guys installation folder. It'd be**C:\\Program Files\\Epic Games\\FallGuys** if you kept the same target location during installation.
5. Select**FallGuys\_client.exe** and click**Add.**  
![FallGuys file in browse option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/fallguys-file.jpg)

 That's it! Fall Guys has now been added to the Windows Firewall exception list.

## 4\. Disable Any Active Proxy Servers

 If you're connected to a [proxy server](https://www.makeuseof.com/tag/what-is-a-proxy-server/) , there's a chance it can cause connection issues. So, disable any proxies you are using and check if it resolves the problem. Here's how you can do it:

1. Open the Windows Search, type**Command Prompt,** and choose**Run as administrator** from the right pane.
2. In the console, type**netsh winhttp reset proxy** and press**Enter** .  
![Disabling proxy command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disabling-proxy.jpg)

## 5\. Connect to a Different DNS Server

 Sometimes, the DNS you're using might not be the fastest. The best thing to do in this situation is to switch to a public DNS like Google DNS. Switching to a public DNS will ensure that you get better connectivity and performance from your internet connection.

Follow the below steps to change to Google DNS:

1. Use one of the many [ways to open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) .
2. Navigate to**Network and Internet** \>**Network and Sharing Center** .
3. Click on your connection name and choose**Properties** from the window that crops up.
4. Select**Internet Protocol Version 4 (TCP/ IPv4)** or**Internet Protocol Version 6 (TCP/ IPv6)** and then click**Properties.**  
![IPv6 option in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv6-option.jpg)
5. Select the**Use the following DNS server addresses** option.
6. If you're on IPv4, type**8.8.8.8** in the**Preferred DNS server** and**8.8.4.4** in the**Alternate DNS server.**
7. If you're on IPv6, type**2001:4860:4860::8888** in the**Preferred DNS server** and**2001:4860:4860::8844** in the**Alternate DNS** server.  
![Editing IPv6 properties in Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/editing-ipv6-properties.jpg)
8. Click**OK.**

## 6\. Edit the Fall Guys Engine.ini File

 The next thing you can try to fix the connection error in Fall Guys is to edit the Engine.ini file. Here's how to do it:

1. Open the Run dialog box by pressing the**Win + R** hotkeys, type**%localappdata%,** and click**OK.**
2. Navigate to**EpicGamesLauncher** \>**Saved** \>**Config** \>**Windows.**
3. Right-click on the**Engine.ini** file, hover the cursor to**Open** with, and choose**Notepad** from the context menu.
4. In the Notepad window that appears, type the following lines and then press**Ctrl + S** to save it.  
`[HTTP]  
HttpTimeout=10  
HttpConnectionTimeout=10  
HttpReceiveTimeout=10  
HttpSendTimeout=10  

[Portal.BuildPatch]  
ChunkDownloads=3  
ChunkRetries=20  
RetryTime=0.5`

![Editing the Engine.ini file in Notepad](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/editing-the-engine-ini-file.jpg)

Launch Fall Guys and check if the problem persists.

## 7\. Reset Winsock Settings

 Winsock is a program that allows programs to connect to the internet through Transmission Control Protocol/ Internet Protocol (TCP/IP). If there's something wrong with this program, apps like Fall Guys will struggle to connect to the internet.

 To fix this, you will have to reset the Winsock data. You can do this by following the below steps:

1. Open Command Prompt with admin rights, as we covered in method four above.
2. Type**netsh winsock reset** and press**Enter** .  
![Reset Winsock command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-winsock-command.jpg)

Now, restart your computer and check if the problem is fixed.

## Your Fall Guys Connection Errors, Fixed

 Fall Guys, like most multiplayer games, requires an internet connection to function. But when it fails to connect to the internet, it is of little use. Fortunately, it is a very common issue and can easily be fixed using the above fixes.


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
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-capturing-life-on-a-macbook-air-the-comprehensive-guide-to-screen-recording/"><u>2024 Approved  Capturing Life on a MacBook Air  The Comprehensive Guide to Screen Recording</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-windows-disk-space-save-personal-files/"><u>Amplify Windows Disk Space, Save Personal Files</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-or-increase-software-size-on-windows-11-the-easy-way/"><u>Reduce or Increase Software Size on Windows 11 – The Easy Way</u></a></li>
<li><a href="https://win11.techidaily.com/take-command-of-your-mouse-globally-with-powertoys-expertise/"><u>Take Command of Your Mouse Globally with PowerToys Expertise</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-exploring-acoustic-illusions-in-motion-techniques-to-illustrate-sound-tracks-via-animated-waveforms-within-premiere-pro-workflow-for-2024/"><u>New Exploring Acoustic Illusions in Motion Techniques to Illustrate Sound Tracks via Animated Waveforms Within Premiere Pro Workflow for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-masterclass-in-visual-updates-igtv-cover-photos/"><u>In 2024, Masterclass in Visual Updates  IGTV Cover Photos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-vkontakte-profile-picture-info-pixel-count-codec-time/"><u>[New] 2024 Approved  VKontakte Profile Picture Info  Pixel Count, Codec, Time</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/key-browser-aides-optimized-vimeo-content-downloads-for-2024/"><u>Key Browser Aides  Optimized Vimeo Content Downloads for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-insiders-look-mastering-windows-for-qr-codes/"><u>The Insider's Look: Mastering Windows for QR Codes</u></a></li>
<li><a href="https://network-issues.techidaily.com/winning-wifi-woes-on-win-10-and-11/"><u>Winning WiFi Woes on WIN 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-swiftly-finding-and-fixing-windows-update-problems/"><u>Strategies for Swiftly Finding and Fixing Windows Update Problems</u></a></li>
<li><a href="https://win11.techidaily.com/stepwise-guide-to-amplifying-virtual-memory-on-microsofts-latest-os/"><u>Stepwise Guide to Amplifying Virtual Memory on Microsoft's Latest OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-process-to-remove-wsl-from-windows/"><u>Mastering the Process to Remove WSL From Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-windows-11-webcam-problem-a00f4289-expedition/"><u>Eradicating Windows 11 Webcam Problem: A00F4289 Expedition</u></a></li>
<li><a href="https://network-issues.techidaily.com/rectified-gdx-creation-failure-in-oswin/"><u>Rectified GDX Creation Failure in OS/Win</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-windows-11-video-editor-roundup-top-picks/"><u>2024 Approved Windows 11 Video Editor Roundup Top Picks</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-failed-outlook-notification-popups/"><u>Addressing Failed Outlook Notification Popups</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-steam-connectivity-issues-with-quick-solutions/"><u>Enhancing Steam Connectivity Issues with Quick Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/orchestrated-workflows-joining-ifttt-and-to-do/"><u>Orchestrated Workflows: Joining IFTTT and To-Do</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-grammarly-an-inactive-service/"><u>How to Reactivate Grammarly, an Inactive Service</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-correcting-virtualboxs-0x80004005-error/"><u>Mastering the Art of Correcting VirtualBox's 0X80004005 Error</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-pristine-20-uncopyrighted-pubg-visual-sequences/"><u>[Updated] Pristine 20 Uncopyrighted PUBG Visual Sequences</u></a></li>
<li><a href="https://win11.techidaily.com/4-cool-things-you-can-do-with-windows-11-god-mode/"><u>4 Cool Things You Can Do With Windows 11 God Mode</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-repairing-windows-enter-key-issues/"><u>Diagnosing and Repairing Windows Enter Key Issues</u></a></li>
<li><a href="https://win11.techidaily.com/journey-to-greatness-your-ultimate-new-pc-apps/"><u>Journey to Greatness: Your Ultimate New PC Apps</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reactivate-login-after-windows-errors/"><u>How to Reactivate Login After Windows Errors</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/exploring-the-world-of-youtube-channel-naming-innovative-ideas-for-vloggers-and-filmmakers-no-more-than-156-characters-for-2024/"><u>Exploring the World of YouTube Channel Naming  Innovative Ideas For Vloggers & Filmmakers (No More than 156 Characters) for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/narrative-basics-explanation/"><u>Narrative Basics Explanation</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-common-windows-1110-gpu-challenges/"><u>Navigating Through Common Windows 11/10 GPU Challenges</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-building-a-strong-visual-narrative-in-youtube-videos-for-2024/"><u>[Updated] Building a Strong Visual Narrative in YouTube Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/supercharging-valorant-downloads-on-slow-systems/"><u>Supercharging Valorant Downloads on Slow Systems</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-integration-web-pages-as-windows-tools/"><u>Seamless Integration: Web Pages as Windows Tools</u></a></li>
<li><a href="https://win11.techidaily.com/the-window-whisperers-guide-to-unveiling-off-screen-apps-in-win-1011-6-proven-steps/"><u>The Window Whisperer's Guide to Unveiling Off-Screen Apps in Win 10/11 (6 Proven Steps)</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-business-best-windows-time-management-and-productivity-software/"><u>Boost Your Business: Best Windows Time Management and Productivity Software</u></a></li>
<li><a href="https://win11.techidaily.com/breeze-through-blurred-taskbars-in-windows-11/"><u>Breeze Through Blurred Taskbars in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/securing-save-configurations-in-your-windows-pubg-game/"><u>Securing Save Configurations in Your Windows PUBG Game</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-eye-catching-thumbnails-made-easy-youtube-image-dimensions-templates-and-pro-tips/"><u>Updated 2024 Approved Eye-Catching Thumbnails Made Easy YouTube Image Dimensions, Templates, and Pro Tips</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-silence-the-expiring-windows-license-message/"><u>How To Silence the Expiring Window's License Message</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/unintended-tiktok-reset-how-to-get-back-old-videos-in-2024/"><u>Unintended TikTok Reset – How to Get Back Old Videos, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-directx-setup-failures/"><u>Steps to Resolve DirectX Setup Failures</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-downloading-the-latest-tracks-a-guide-to-free-extractors-for-pc-users/"><u>2024 Approved  Downloading the Latest Tracks  A Guide to Free Extractors for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-troubled-waters-eliminating-error-code-80080300-in-win11-tech/"><u>Navigate Through Troubled Waters: Eliminating Error Code 80080300 in Win11 Tech</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-simple-steps-for-correction-of-character-map-errors/"><u>Unveiling Simple Steps for Correction of Character Map Errors</u></a></li>
</ul></div>
