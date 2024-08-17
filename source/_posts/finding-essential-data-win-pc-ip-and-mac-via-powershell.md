---
title: "Finding Essential Data: Win PC IP & MAC via PowerShell"
date: 2024-08-16T00:20:04.425Z
updated: 2024-08-17T00:20:04.425Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Finding Essential Data: Win PC IP & MAC via PowerShell"
excerpt: "This Article Describes Finding Essential Data: Win PC IP & MAC via PowerShell"
keywords: Win PC IP Address,Mac IP Command,PowerShell IP Find,PC Network Info,IP Details Windows,OS X Net Data,PowerShell Network Query
thumbnail: https://thmb.techidaily.com/a0ea0929e49147a7aa2982696f1085c4ea3dc3044596db757054a8f03e6ab91e.jpg
---

## Finding Essential Data: Win PC IP & MAC via PowerShell

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
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-beyond-sharex-in-depth-comparisons/"><u>[New] 2024 Approved  Beyond ShareX  In-Depth Comparisons</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-enhance-your-digital-footprint-upload-tiktoks-on-twitter/"><u>[New] 2024 Approved  Enhance Your Digital Footprint  Upload TikToks on Twitter</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-efficient-techniques-for-saving-online-meeting-transcripts-for-2024/"><u>[New] Efficient Techniques for Saving Online Meeting Transcripts for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-no-cost-screen-recording-tricks-for-pc-users-for-2024/"><u>[Updated] No-Cost Screen Recording Tricks for PC Users for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unveiling-top-templates-for-tiktok-videos/"><u>[Updated] Unveiling Top Templates for TikTok Videos</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-microsoft-family-safety/"><u>A Beginner's Guide to Microsoft Family Safety</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-steam-content-unavailable-glitches/"><u>Bypassing Steam Content Unavailable Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-secure-network-shadows-in-windows/"><u>Crafting Secure Network Shadows in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-working-state-for-ccleaner-in-windows-1011-systems/"><u>Enabling Working State for CCleaner in Windows 10/11 Systems</u></a></li>
<li><a href="https://vp-tips.techidaily.com/exploring-the-future-of-interactive-headsets/"><u>Exploring the Future of Interactive Headsets</u></a></li>
<li><a href="https://win11.techidaily.com/how-regular-windows-backup-prolongs-peace-of-mind/"><u>How Regular Windows Backup Prolongs Peace of Mind</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-an-enhanced-run-tool-to-windows-10-and-11/"><u>How to Add an Enhanced Run Tool to Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-diagnose-and-correct-disk-read-errors/"><u>How to Diagnose and Correct Disk Read Errors</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-league-of-legends-disconnecting-on-windows/"><u>How to Fix League of Legends Disconnecting on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-dolby-atmos-in-windows-11-pro/"><u>How to Install Dolby Atmos in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-your-smartphone-as-a-windows-microphone/"><u>How to Use Your Smartphone as a Windows Microphone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-activation-lock-on-iphone-12-pro-max-or-ipad-by-drfone-ios/"><u>In 2024, How to Bypass Activation Lock on iPhone 12 Pro Max or iPad?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-realme-gt-neo-5-drfone-by-drfone-virtual-android/"><u>In 2024, How to Spy on Text Messages from Computer & Realme GT Neo 5 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/launch-into-productivity-must-have-ms-store-picks/"><u>Launch Into Productivity: Must-Have MS Store Picks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-turn-off-corner-shaping/"><u>Mastering Windows 11: Turn Off Corner Shaping</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-landscape-of-winapp-and-browser-mastery/"><u>Navigating the Landscape of WinApp and Browser Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-hello-fingerprint-malfunctions-easily/"><u>Navigating Windows Hello Fingerprint Malfunctions Easily</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-how-to-make-your-memoji-talk-get-creative-with-your-messaging-for-2024/"><u>New How To Make Your Memoji Talk? Get Creative With Your Messaging for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-windows-11-taskbar-performance/"><u>Optimizing Windows 11 Taskbar Performance</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-system-calls-fails-on-windows-devices/"><u>Overcoming System Calls Fails on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-mobile-app-match-android-plus-windows-pc-edition/"><u>Perfect Mobile App Match: Android + Windows PC Edition</u></a></li>
<li><a href="https://win11.techidaily.com/premium-temperature-trackers-on-win-os/"><u>Premium Temperature Trackers on Win OS</u></a></li>
<li><a href="https://driver-error.techidaily.com/rediscovering-hidden-cds-and-dvds/"><u>Rediscovering Hidden CDs & DVDs</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-control-over-malfunctioning-windows-snippers/"><u>Regaining Control Over Malfunctioning Windows Snippers</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-legacy-windows-photo-viewer-features-in-win11/"><u>Restoring Legacy Windows Photo Viewer Features in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/revamping-text-conversations-emoji-15-installation-guide-for-windows-11/"><u>Revamping Text Conversations: Emoji 15 Installation Guide for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/sidestepping-error-0x80070522-on-windows-by-accessing-client-rights/"><u>Sidestepping Error 0X80070522 on Windows by Accessing Client Rights</u></a></li>
<li><a href="https://win11.techidaily.com/skirting-persistent-login-prompt-issues-in-windows/"><u>Skirting Persistent Login Prompt Issues in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-recover-lost-access-to-ubisofts-launcher/"><u>Steps to Recover Lost Access to Ubisoft's Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-fix-inaudible-microphone-during-screen-recordings/"><u>Techniques to Fix Inaudible Microphone During Screen Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/timeless-windows-syncing-the-digital-second-hand/"><u>Timeless Windows: Syncing the Digital Second Hand</u></a></li>
<li><a href="https://win11.techidaily.com/tips-and-tricks-for-addressing-winscombsvc-errors-in-windows-os/"><u>Tips & Tricks for Addressing WinScombSvc Errors in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/trimming-early-edges-methods-to-stop-tab-preload-on-windows-11/"><u>Trimming Early Edges: Methods to Stop Tab Preload on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-11s-6-unusual-visual-cues/"><u>Understanding Windows 11'S 6 Unusual Visual Cues</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-full-power-of-task-manager-with-admin-rights-in-win11/"><u>Unleash Full Power of Task Manager with Admin Rights in Win11</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-the-best-free-mpeg-video-merging-solutions/"><u>Updated In 2024, The Best Free MPEG Video Merging Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/why-ditch-bot-helmed-windows-key-creation/"><u>Why Ditch Bot-Helmed Windows Key Creation?</u></a></li>
<li><a href="https://win11.techidaily.com/win-1011-customize-your-functional-keys-configuration/"><u>Win 10/11: Customize Your Functional Keys Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/win1011-solving-directdraw-glitches-quickly/"><u>Win10/11: Solving DirectDraw Glitches Quickly</u></a></li>
</ul></div>
