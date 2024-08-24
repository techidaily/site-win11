---
title: Mastering IP/MAC Discovery on Windows, PS Style
date: 2024-08-23T06:07:40.445Z
updated: 2024-08-24T06:07:40.445Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering IP/MAC Discovery on Windows, PS Style
excerpt: This Article Describes Mastering IP/MAC Discovery on Windows, PS Style
keywords: IP/MAC WinDiscovery,MAC Address Finder,Windows Discover IP,PS Network Identify,OS IPMAC Locate,NET_SNMP Enable,NetBIOS SNMP Info
thumbnail: https://thmb.techidaily.com/bdb8177ec45e10fcd4ec5499f6e255ec00146feb57465bd8edaf95619ca00bc2.jpg
---

## Mastering IP/MAC Discovery on Windows, PS Style

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-beyond-basic-usage-mastering-instagrams-interrogation-icon/"><u>[New] Beyond Basic Usage  Mastering Instagram's Interrogation Icon</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-digital-learning-session-replays-for-2024/"><u>[New] Digital Learning Session Replays for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-earning-as-a-video-game-geek-for-2024/"><u>[New] Earning as a Video Game Geek for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-cutting-edge-platforms-for-digital-transformation-into-nft-tokens/"><u>[New] In 2024, Cutting-Edge Platforms for Digital Transformation Into NFT Tokens</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-top-5-ps3-emulation-software-pc-edition-2023/"><u>[New] In 2024, Top 5 Ps3 Emulation Software - PC Edition, 2023</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-joy-of-journeys-end-innovative-box-revelations/"><u>[Updated] The Joy of Journey's End  Innovative Box Revelations</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-transform-stories-in-a-flash-free-extensions-and-mobile-magic-for-2024/"><u>[Updated] Transform Stories in a Flash – Free Extensions & Mobile Magic for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-optical-character-recognition-ocr-understanding-image-based-text-capture-with-copernic-software/"><u>A Deep Dive Into Optical Character Recognition (OCR): Understanding Image-Based Text Capture with Copernic Software</u></a></li>
<li><a href="https://tech-hub.techidaily.com/artificeintelligent-advancements-transforming-academic-research-methods/"><u>ArtificeIntelligent Advancements: Transforming Academic Research Methods</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-unwanted-edge-shortcut-popups/"><u>Conquering Unwanted Edge Shortcut Popups</u></a></li>
<li><a href="https://win-blog.techidaily.com/defeating-the-devil-how-to-overcome-code-red-error-5573-in-call-of-duty-warzone-on-multiple-platforms/"><u>Defeating the Devil: How to Overcome Code Red (Error 5573) in Call of Duty: Warzone on Multiple Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/discover-how-to-leverage-copernic-for-efficient-cloud-storage-searches/"><u>Discover How to Leverage Copernic for Efficient Cloud Storage Searches</u></a></li>
<li><a href="https://win11.techidaily.com/easily-activate-snipping-tool-in-modern-windows-os/"><u>Easily Activate Snipping Tool in Modern Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-connection-integrate-your-pc-and-phone-through-flow/"><u>Effortless Connection - Integrate Your PC & Phone Through Flow</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-image-quality-mastering-windows-11s-background-blur-function-in-photos/"><u>Elevate Your Image Quality: Mastering Windows 11'S Background Blur Function in Photos</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-lsassexe-identification-failure-on-pcs/"><u>Eliminating lsass.exe Identification Failure on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-comprehensibility-with-obsidians-artistic-note-taking/"><u>Enhancing Comprehensibility with Obsidian's Artistic Note-Taking</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-pc-performance-for-faster-steam-content-loading/"><u>Enhancing PC Performance for Faster Steam Content Loading</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-fixing-two-users-ms-login-conflicts/"><u>Expert Tips: Fixing Two Users' MS Login Conflicts</u></a></li>
<li><a href="https://win11.techidaily.com/find-your-inbox-efficiency-discover-faster-email-recovery-with-outlook-and-copernics-lightning-quick-search/"><u>Find Your Inbox Efficiency: Discover Faster Email Recovery with Outlook and Copernic's Lightning-Quick Search</u></a></li>
<li><a href="https://win11.techidaily.com/1723809008305-find-your-inbox-efficiency-discover-faster-email-recovery-with-outlook-and-copernics-lightning-quick-search/"><u>Find Your Inbox Efficiency: Discover Faster Email Recovery with Outlook and Copernic's Lightning-Quick Search!</u></a></li>
<li><a href="https://win11.techidaily.com/fix-windows-11s-zerox-error-code-0x80049dd3-and-enhance-typing/"><u>Fix Windows 11'S Zerox Error (Code: 0X80049DD3) and Enhance Typing</u></a></li>
<li><a href="https://win11.techidaily.com/go-direct-to-linux-with-no-wsl/"><u>Go Direct to Linux with No WSL</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-ipad-or-apple-iphone-14-pro-stuck-on-activation-lock-by-drfone-ios/"><u>How to Fix iPad or Apple iPhone 14 Pro Stuck On Activation Lock?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-you-are-not-connected-to-any-networks-on-windows/"><u>How to Fix You Are Not Connected to Any Networks on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-the-wsl-error-4294967295-on-windows/"><u>How to Resolve the WSL Error 4294967295 on Windows</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-solve-missing-audio-in-it-takes-two-steps-for-a-quiet-pc/"><u>How To Solve Missing Audio in 'It Takes Two': Steps For A Quiet PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-troubleshoot-a-printer-connection-in-windows/"><u>How to Troubleshoot a Printer Connection in Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-from-oneplus-ace-2-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock from OnePlus Ace 2 Devices</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-display-apple-iphone-14-screen-on-pc-easily-drfone-by-drfone-ios/"><u>In 2024, How to Display Apple iPhone 14 Screen on PC Easily? | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-dell-network-adapter-drivers-compatible-with-windows-7/"><u>Latest Dell Network Adapter Drivers Compatible with Windows 7</u></a></li>
<li><a href="https://win11.techidaily.com/learn-your-computers-identity-a-quick-guide-with-6-methods/"><u>Learn Your Computer’s Identity: A Quick Guide with 6 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-email-management-9-key-upgrades-in-windows-outlook/"><u>Mastering Email Management: 9 Key Upgrades in Windows' Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/1723809006534-mastering-social-media-growth-with-seamless-menu-expand-functions-on-fb-li-yt-top-level-navigation-essentials/"><u>Mastering Social Media Growth with Seamless Menu Expand Functions on FB, LI, YT - Top-Level Navigation Essentials!</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/mastering-the-conversion-of-vids-to-mp3-on-insta/"><u>Mastering the Conversion of Vids to MP3 on Insta</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-network-configurations-in-win11/"><u>Navigating Network Configurations in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-1011-gpu-drivers-with-precision/"><u>Navigating Windows 10/11 GPU Drivers with Precision</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-system-streamlined-windows-autoupdate-and-driver-change/"><u>Optimize System: Streamlined Windows Autoupdate & Driver Change</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-your-workspace-learning-to-use-windows-11s-taskbar-search/"><u>Optimizing Your Workspace: Learning to Use Windows 11'S Taskbar Search</u></a></li>
<li><a href="https://win11.techidaily.com/reboot-your-world-effortless-windows-factory-techniques/"><u>Reboot Your World: Effortless Windows Factory Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/removing-persistent-edge-toolbar-items/"><u>Removing Persistent Edge Toolbar Items</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-non-functional-cut-and-paste-in-windows-11/"><u>Repairing Non-Functional Cut & Paste in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/savings-saved-the-hidden-dangers-in-cheap-windows-activation-codes/"><u>Savings, Saved? The Hidden Dangers in Cheap Windows Activation Codes</u></a></li>
<li><a href="https://win11.techidaily.com/seven-big-mistakes-new-users-could-make-in-windows-11-to-avoid/"><u>Seven Big Mistakes New Users Could Make in Windows 11 - To Avoid</u></a></li>
<li><a href="https://techidaily.com/sign-a-pdf-v12-document-with-digital-signature-software-by-ldigisigner-sign-a-pdf-sign-a-pdf/"><u>Sign a PDF v1.2 document with digital signature software</u></a></li>
<li><a href="https://win11.techidaily.com/speed-up-workflow-windows-custom-key-combinations/"><u>Speed Up Workflow: Windows Custom Key Combinations</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-document-discovery-using-copernics-expert-text-search-features-for-professionals/"><u>Streamline Document Discovery Using Copernic's Expert Text Search Features for Professionals</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-workflow-with-outlook-preview-on-windows-11/"><u>Streamlining Workflow with Outlook Preview on Windows 11</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/tablet-tug-of-war-making-the-right-choice-between-an-amazon-fire-or-a-samsung-device/"><u>Tablet Tug-of-War: Making the Right Choice Between an Amazon Fire or a Samsung Device</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-ultimate-tutorial-on-permanently-removing-your-instagram-profile-for-2024/"><u>The Ultimate Tutorial on Permanently Removing Your Instagram Profile for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/top-rated-portable-gaming-devices-in-2/"><u>Top Rated Portable Gaming Devices in 2</u></a></li>
<li><a href="https://win11.techidaily.com/transitioning-to-virtualbox-70-on-windows-11-your-ultimate-walkthrough/"><u>Transitioning to VirtualBox 7.0 on Windows 11 – Your Ultimate Walkthrough</u></a></li>
<li><a href="https://win11.techidaily.com/turn-back-to-standard-contrast-on-windows/"><u>Turn Back to Standard Contrast on Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-battery-drivers-in-windows-easily/"><u>Update Battery Drivers in Windows. EASILY!</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-meet-the-brilliant-minds-behind-the-best-lego-stop-motion-videos/"><u>Updated In 2024, Meet the Brilliant Minds Behind the Best Lego Stop Motion Videos</u></a></li>
<li><a href="https://win11.techidaily.com/win-fixes-overcoming-firefox-page-load-issues-in-windows/"><u>Win Fixes: Overcoming Firefox Page Load Issues in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-print-admin-a-user-friendly-approach/"><u>Windows Print Admin: A User-Friendly Approach</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>