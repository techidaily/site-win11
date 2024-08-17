---
title: PowerShell Pro Tips for Win IP/MAC Extraction
date: 2024-08-15T23:30:26.442Z
updated: 2024-08-16T23:30:26.442Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes PowerShell Pro Tips for Win IP/MAC Extraction
excerpt: This Article Describes PowerShell Pro Tips for Win IP/MAC Extraction
keywords: PowerShell Extract MACs,WinIP Mac Extraction,PowerShell IP Addressing,Advanced Windows IP Tools,PowerShell Network Forensics,OSINT via PowerShell,Security Scripts for IP/MAC
thumbnail: https://thmb.techidaily.com/e90a41374ab8bcea029035e600ef5fff009cee16ec9e8eead9f3969598aefde0.jpg
---

## PowerShell Pro Tips for Win IP/MAC Extraction

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-navigate-through-dynamic-gifs-find-these-best-recorders-in-winos/"><u>[New] In 2024, Navigate Through Dynamic GIFs  Find These Best Recorders in WinOS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-learn-to-redefine-your-instagram-sound-with-ease/"><u>[New] Learn to Redefine Your Instagram Sound with Ease</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-professional-video-tweaks-via-youtube-studio-editor/"><u>[Updated] 2024 Approved  Professional Video Tweaks via YouTube Studio Editor</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-ace-your-earnings-game-in-youtube-shorts-for-2024/"><u>[Updated] Ace Your Earnings Game in YouTube Shorts for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-the-art-of-editing-with-final-cut-pro/"><u>[Updated] Mastering the Art of Editing with Final Cut Pro</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-quick-youtube-snippets-explained-simply/"><u>[Updated] Quick YouTube Snippets Explained Simply</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-digital-discussion-documentary-vault/"><u>2024 Approved  Digital Discussion Documentary Vault</u></a></li>
<li><a href="https://win11.techidaily.com/consistent-connections-avoiding-disruptions-in-windows/"><u>Consistent Connections: Avoiding Disruptions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-win-11-boot-drive-essential-tips-for-3-techniques/"><u>Creating a Win 11 Boot Drive – Essential Tips for 3 Techniques</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/elevate-your-pc-screenshots-with-apowersofts-tool/"><u>Elevate Your PC Screenshots with Apowersoft’s Tool</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-pc-display-with-best-time-clock-screen-savers/"><u>Enhance PC Display with Best Time Clock Screen Savers</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-shared-connectivity-options-google-versus-windows/"><u>Exploring Shared Connectivity Options: Google Versus Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-automatic-detect-of-proxy-issues/"><u>Fixing Windows' Automatic Detect of Proxy Issues</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/from-letters-to-love-how-to-effortlessly-create-a-heart-symbol-online/"><u>From Letters to Love: How to Effortlessly Create a Heart Symbol Online</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-tecno-camon-30-pro-5g-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Tecno Camon 30 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-organize-a-virtual-gathering-using-zoom-on-android-for-2024/"><u>How to Organize a Virtual Gathering Using Zoom on Android for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-uninstall-programs-without-admin-privileges-on-windows/"><u>How to Uninstall Programs Without Admin Privileges on WINDOWS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/how-to-upload-videos-to-igtv/"><u>How to Upload Videos to IGTV?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-complete-fixes-to-solve-iphone-11-randomly-asking-for-apple-id-password-by-drfone-ios/"><u>In 2024, Complete Fixes To Solve iPhone 11 Randomly Asking for Apple ID Password</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-essential-youtube-video-editing-techniques/"><u>In 2024, Essential YouTube Video Editing Techniques</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-flourishing-on-a-beauty-youtube-channel/"><u>In 2024, Flourishing on a Beauty YouTube Channel</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-masterful-tag-utilization-boosting-video-performance/"><u>In 2024, Masterful Tag Utilization Boosting Video Performance</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixed-overcoming-application-crash-error/"><u>Mastering the Art of Fixed: Overcoming 'Application Crash' Error</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-error-correction-for-rpc-failures/"><u>Mastering Windows Error Correction for RPC Failures</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-chrome-file-uploading-woes-a-guide-for-windows-devices/"><u>Navigate Chrome File Uploading Woes: A Guide for Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-windows-streams-stopping-abrupt-download-drops/"><u>Optimize Windows Streams: Stopping Abrupt Download Drops</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-xbox-audio-hurdles-with-windows-11-system-upgrades/"><u>Overcoming Xbox Audio Hurdles with Windows 11 System Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-unwanted-keystrokes-during-typing/"><u>Preventing Unwanted Keystrokes During Typing</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-tecno-spark-20-proplus-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Tecno Spark 20 Pro+ Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-restore-screen-share-in-teams/"><u>Steps to Restore Screen Share in Teams</u></a></li>
<li><a href="https://win11.techidaily.com/stop-spacing-out-sounds-fixes-to-unmute-keyboard-volume/"><u>Stop Spacing Out Sounds: Fixes to Unmute Keyboard Volume</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-setting-up-bings-chat-for-windows-11-users/"><u>Streamline Setting Up Bing's Chat for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-sync-windows-plus-android-via-flow-app/"><u>Streamlining Sync: Windows + Android via Flow App</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remediation-for-elusive-obs-studio-issue-on-win-11-pcs/"><u>Swift Remediation for Elusive OBS Studio Issue on Win 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/taking-out-trash-onedrive-from-your-pcs-file-explorer/"><u>Taking Out Trash: OneDrive From Your PC's File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/the-forgotten-windows-11-theme-archive/"><u>The Forgotten Windows 11 Theme Archive</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-roadmap-to-making-money-with-personal-videos-for-2024/"><u>The Roadmap to Making Money with Personal Videos for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/the-seamless-guide-to-saving-gifs-on-iphonesandroids/"><u>The Seamless Guide to Saving GIFs on iPhones/Androids</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-utilizing-qr-scanners-in-windows/"><u>The Ultimate Guide to Utilizing QR Scanners in Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-ultimate-warrior-challenge-t5-vs-sjcam-s6/"><u>The Ultimate Warrior Challenge  T5 vs SJCAM S6</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-overcoming-a-non-functional-search-in-windows-11s-environment/"><u>Tips for Overcoming a Non-Functional Search in Windows 11’S Environment</u></a></li>
<li><a href="https://win11.techidaily.com/turn-on-school-inspired-themes-for-win-11/"><u>Turn On School-Inspired Themes for Win 11</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-g54-5g-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from G54 5G.</u></a></li>
<li><a href="https://win11.techidaily.com/unravel-windows-mysteries-get-the-support-you-need/"><u>Unravel Windows Mysteries: Get the Support You Need!</u></a></li>
<li><a href="https://win11.techidaily.com/unyielding-security-seven-ways-to-shield-your-system/"><u>Unyielding Security: Seven Ways to Shield Your System</u></a></li>
<li><a href="https://win11.techidaily.com/windows-program-commands-keybinding-setup/"><u>Windows Program Commands: Keybinding Setup</u></a></li>
<li><a href="https://win11.techidaily.com/windows-define-custom-idle-timeframe/"><u>Windows: Define Custom Idle Timeframe</u></a></li>
</ul></div>
