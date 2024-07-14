---
title: How to Fix Fall Guys Connection Errors on Windows
date: 2024-07-13T10:53:26.342Z
updated: 2024-07-14T10:53:26.342Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix Fall Guys Connection Errors on Windows
excerpt: This Article Describes How to Fix Fall Guys Connection Errors on Windows
keywords: Fix Fall Guys Win,Resolve Win Error,Bandwidth Boost,Clear Network Glitches,Optimize Gameplay,Troubleshoot Disconnects,Enhance PC Performance
thumbnail: https://thmb.techidaily.com/bfe527075b76486c457bb40593f28ebdf4420fa39a7d079da9e7faa5dde71ba1.jpg
---

## How to Fix Fall Guys Connection Errors on Windows

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
<li><a href="https://bypass-frp.techidaily.com/a-quick-guide-to-realme-gt-neo-5-se-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Realme GT Neo 5 SE FRP Bypass Instantly</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-boosting-playback-speed-guidelines-for-secure-sound-enhancement/"><u>2024 Approved  Boosting Playback Speed  Guidelines for Secure Sound Enhancement</u></a></li>
<li><a href="https://win11.techidaily.com/1719299925084-understanding-and-correcting-windows-error-0xc00000f/"><u>Understanding & Correcting Windows Error: 0Xc00000f</u></a></li>
<li><a href="https://win11.techidaily.com/10-effective-command-line-steps-for-info-exploration/"><u>10 Effective Command-Line Steps for Info Exploration</u></a></li>
<li><a href="https://win11.techidaily.com/1719261545557-eliminate-roblox-error-262-in-minutes/"><u>Eliminate Roblox Error 262 in Minutes</u></a></li>
<li><a href="https://win11.techidaily.com/1719265267578-fixing-winsplit-display-issues-now/"><u>Fixing WinSplit Display Issues Now</u></a></li>
<li><a href="https://win11.techidaily.com/1719254323833-overcome-shift-key-stickiness-in-windows-os/"><u>Overcome Shift Key Stickiness in Windows OS.</u></a></li>
<li><a href="https://win11.techidaily.com/1719275577489-winshift-troubles-how-to-resolve-them/"><u>WinShift Troubles: How to Resolve Them</u></a></li>
<li><a href="https://printer-issues.techidaily.com/quick-start-guide-to-connect-and-configure-your-hp-deskjet-3470v2/"><u>Quick Start Guide to Connect and Configure Your HP DeskJet 3470V2</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-a-comprehensive-guide-to-infusing-fun-with-emojis-in-discords-status-field/"><u>[Updated] 2024 Approved  A Comprehensive Guide to Infusing Fun with Emojis in Discord's Status Field</u></a></li>
<li><a href="https://win11.techidaily.com/1719286727564-gpt4all-for-pcs-local-free-chatgpt-version/"><u>GPT4All for PCs: Local, Free ChatGPT Version</u></a></li>
<li><a href="https://win11.techidaily.com/1719292127499-overcome-windows-shift-glitch/"><u>Overcome Windows Shift Glitch.</u></a></li>
<li><a href="https://win11.techidaily.com/12-unnecessary-windows-programs-and-apps-you-should-uninstall/"><u>12 Unnecessary Windows Programs and Apps You Should Uninstall</u></a></li>
<li><a href="https://win11.techidaily.com/10-early-symptoms-of-windows-needing-a-fresh-start/"><u>10 Early Symptoms of Windows Needing a Fresh Start</u></a></li>
<li><a href="https://win11.techidaily.com/1719231593414-unveiling-the-impact-of-eradicating-windows-11s-taskbar-chatting-functionality/"><u>Unveiling the Impact of Eradicating Windows 11'S Taskbar Chatting Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/1719258150800-win-rpc-problems-here-are-5-fixes-you-need/"><u>Win RPC Problems? Here Are 5 Fixes You Need</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-melody-migration-made-easy-a-guide-to-the-best-free-youtube-downloading-apps/"><u>[Updated] 2024 Approved  Melody Migration Made Easy  A Guide to the Best Free YouTube Downloading Apps</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-tecno-phantom-v-flip-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Tecno Phantom V Flip</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Sony Xperia 10 V | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-daily-motivation-delivered-by-tiktoks-best-ten/"><u>[New] Daily Motivation Delivered by TikTok's Best Ten</u></a></li>
<li><a href="https://win11.techidaily.com/10-quick-tips-recognizing-your-xbox-controller-in-windows/"><u>10 Quick Tips: Recognizing Your Xbox Controller in Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-easy-implementation-of-snap-camera-on-ms-teams/"><u>2024 Approved  Easy Implementation of Snap Camera on MS Teams</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-mastering-the-art-of-youtube-viewership-6-proven-methods/"><u>[Updated] Mastering the Art of YouTube Viewership  6 Proven Methods</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pro-shooters-guide-the-best-4k-camcorders-ranked/"><u>2024 Approved  Pro Shooters' Guide  The Best 4K Camcorders Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/1719290483430-quick-fixes-for-stubborn-shift-on-pc/"><u>Quick Fixes for Stubborn Shift on PC</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-mastering-audio-book-publishing-with-ease-a-modern-guide/"><u>New 2024 Approved Mastering Audio Book Publishing with Ease A Modern Guide</u></a></li>
<li><a href="https://win11.techidaily.com/1719304374554-quick-fixes-to-tackle-everyday-windows-glitches/"><u>Quick Fixes to Tackle Everyday Windows Glitches!</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-free-filmora-no-crack-no-risk-just-genuine-methods/"><u>New In 2024, Free Filmora No Crack, No Risk, Just Genuine Methods</u></a></li>
<li><a href="https://win11.techidaily.com/10-fixes-for-windows-restoring-controllers-with-steam/"><u>10 Fixes for Windows: Restoring Controllers with Steam</u></a></li>
<li><a href="https://win11.techidaily.com/1719265441814-change-power-saving-settings-adjust-the-screen-brightness-on-battery-saver-by-tweaking-the-power-plans-in-system-settings/"><u>Change Power Saving Settings: Adjust the Screen Brightness on Battery Saver by Tweaking the Power Plans in 'System Settings'</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-non-athlete-front-rows-the-ultimate-alternative-list/"><u>2024 Approved  Non-Athlete Front Rows  The Ultimate Alternative List</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-podcast-title-craft-the-essential-handbook/"><u>2024 Approved  Mastering Podcast Title Craft  The Essential Handbook</u></a></li>
<li><a href="https://win11.techidaily.com/1719319756779-revive-your-frozen-shift-key-on-pc/"><u>Revive Your Frozen Shift Key on PC.</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamline-computers-upgrade-chip-drivers/"><u>Streamline Computers: Upgrade Chip-Drivers</u></a></li>
<li><a href="https://facebook.techidaily.com/unmasking-the-role-of-app-analytics-in-ad-personalization/"><u>Unmasking the Role of App Analytics in Ad Personalization</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-webcam-master-ultimate-live-recording-guide/"><u>2024 Approved  WebCam Master  Ultimate Live Recording Guide</u></a></li>
<li><a href="https://win11.techidaily.com/1719251209823-overcome-wwinplusprint-hurdles-for-seamless-operations-in-windows/"><u>Overcome WWin+Print Hurdles for Seamless Operations in Windows.</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-gps-location-on-vivo-y100a-easily-and-safely-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change GPS Location on Vivo Y100A Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/capturing-imagery-with-a-track-discover-the-top-5-photo-experts-with-musical-accompaniment/"><u>Capturing Imagery with a Track  Discover the Top 5 Photo Experts with Musical Accompaniment</u></a></li>
<li><a href="https://win11.techidaily.com/1719239311887-unlock-the-future-at-an-irresistible-price-best-windows-11-deal-612lifetime-key-lovers-delight/"><u>Unlock the Future at an Irresistible Price – Best Windows 11 Deal, $6.12/Lifetime, Key Lovers' Delight</u></a></li>
<li><a href="https://win11.techidaily.com/1719231160491-streamline-your-desktop-no-overlaps/"><u>Streamline Your Desktop: No Overlaps!</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/in-2024-dj-haven-platforms-for-exclusive-audio-mixes/"><u>In 2024, DJ Haven Platforms for Exclusive Audio Mixes</u></a></li>
<li><a href="https://win11.techidaily.com/1719281206376-win11-printer-woes-solutions-here/"><u>Win11 Printer Woes? Solutions Here!</u></a></li>
<li><a href="https://win11.techidaily.com/1719228805701-quick-jot-down-techniques-in-windows-11-no-apps/"><u>Quick Jot-Down Techniques in Windows 11, No Apps!</u></a></li>
<li><a href="https://win11.techidaily.com/1719285802254-say-goodbye-to-troubleshooting-woes-on-vistawindows-7/"><u>Say Goodbye to Troubleshooting Woes on Vista/Windows 7.</u></a></li>
<li><a href="https://win11.techidaily.com/12-common-windows-11-aesthetic-oddities/"><u>12 Common Windows 11 Aesthetic Oddities</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-photos-from-apple-iphone-14-pro-max-to-other-iphone-without-icloud-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer Photos from Apple iPhone 14 Pro Max to other iPhone without iCloud | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719289257399-black-friday-top-keys-fan-secrets-for-free-windows-11-at-612lifetime/"><u>Black Friday: Top Keys Fan Secrets for Free Windows 11 at $6.12/Lifetime!</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-boosting-online-presence-top-30-freefire-hashtags-and-tag-strategies/"><u>[Updated] In 2024, Boosting Online Presence  Top 30 FreeFire Hashtags and Tag Strategies</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/from-flashy-feeds-to-fm-sounds-the-instagram-to-mp3-methodology/"><u>From Flashy Feeds to FM Sounds  The Instagram-to-Mp3 Methodology</u></a></li>
<li><a href="https://win11.techidaily.com/1719268980675-optimize-disk-space-clear-temporary-windows-files-now/"><u>Optimize Disk Space: Clear Temporary Windows Files Now!</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-uncover-the-top-12-best-flip-screen-vlogging-tools/"><u>[New] Uncover the Top 12 Best Flip-Screen Vlogging Tools</u></a></li>
<li><a href="https://win11.techidaily.com/1719271169588-reclaim-your-browser-quick-fixes-to-unlock-chrome-on-win11/"><u>Reclaim Your Browser: Quick Fixes to Unlock Chrome on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/1719218745181-panels-in-peril-bring-them-back-with-these-hacks/"><u>Panels in Peril? Bring Them Back with These Hacks!</u></a></li>
<li><a href="https://win11.techidaily.com/1719298121554-troubleshoot-windows-update-hurdles-quick-solutions/"><u>Troubleshoot: Windows Update Hurdles - Quick Solutions</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-hues-harmony-an-editors-guide-to-perfect-grading/"><u>In 2024, Hues Harmony  An Editor's Guide to Perfect Grading</u></a></li>
<li><a href="https://win11.techidaily.com/1719224494525-revive-w11s-chrome-immediate-troubleshooting-advice/"><u>Revive W11's Chrome - Immediate Troubleshooting Advice</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exceptional-environments-the-best-screen-snapshots/"><u>[Updated] Exceptional Environments  The Best Screen Snapshots</u></a></li>
<li><a href="https://win11.techidaily.com/15-key-improvements-added-to-windows-11s-next-version/"><u>15 Key Improvements Added to Windows 11'S Next Version</u></a></li>
<li><a href="https://win11.techidaily.com/1719245846865-windows-issues-learn-how-to-seek-expert-guidance/"><u>Windows Issues? Learn How to Seek Expert Guidance</u></a></li>
<li><a href="https://win11.techidaily.com/1719301836134-clear-and-confident-windows-viewing-top-6-fixes-now/"><u>Clear and Confident Windows Viewing: Top 6 Fixes Now!</u></a></li>
</ul></div>
