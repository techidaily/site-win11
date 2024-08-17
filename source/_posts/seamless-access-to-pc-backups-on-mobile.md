---
title: Seamless Access to PC Backups on Mobile
date: 2024-08-16T00:45:00.825Z
updated: 2024-08-17T00:45:00.825Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Seamless Access to PC Backups on Mobile
excerpt: This Article Describes Seamless Access to PC Backups on Mobile
keywords: Mobile Backup Access,Seamless PC Restore,Mobile Data Protection,Secure Backup Transfer,Fast PC Recovery Mobile,Easy PC Backup Sync,Remote Mobile Backup
thumbnail: https://thmb.techidaily.com/56330953ffdc4465c49b828b7088926c62fd587a191eaa2e733d9cf68d627d09.jpg
---

## Seamless Access to PC Backups on Mobile

 If you searched for ways to access your Windows files from your Android/iOS devices, chances are you landed on guides suggesting you to download all sorts of external applications, free or paid. Did you know that you absolutely don't need any external application for file transfers across your devices? Well, now you do. Windows Network Share is a really easy way of sharing files, folders, or entire drives across devices on the same network. Let's learn how to set up Windows Network Share to access your PC files from Android/iOS.

## What Is Network File Sharing?

 When you want to share a file or folder with someone, sometimes it is faster to share it over your local network, rather than uploading to the cloud or looking for a USB flash drive. This process is called network file sharing. File Transfer Protocol (FTP) is also a valid option for file sharing remotely or on the local network but, it's much more of a hassle to set up than Windows Network Share.

 Windows Network Share utilizes the SMB protocol internally to make files, directories, or, entire drives available for read/write access for devices on the local network. While it's super easy and swift to set up, it's also a common target for adversaries. So, it's wise that you learn [how the SMB protocol works and some common SMB vulnerabilities](https://www.makeuseof.com/what-is-smb-protocol-and-what-are-its-risks/) to ensure that your network perimeter isn't breached.

## How to Share a Windows Drive on Your Local Network

 To access your computer's files, you need to share them on the local network. For the demonstration, I'll be sharing a drive on the local network. If you wish to share a folder or a single file instead, you can follow the same steps but with only the folder(s) and file(s) selected.

 Before you dive into the steps, it's recommended you [create a separate, local Windows user account](https://www.makeuseof.com/windows-11-create-local-user-account/) to be used solely for network drive access.

 Here are the steps to share files on the local network in Windows 10/11:

1. **Right-click** on the drive you want to share.
2. From the drop-down menu, click on **Properties**.
3. In the **Properties** menu, go to the **Sharing** tab.  
![sharing tab open in properties menu of a drive-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sharing-tab-open-in-properties-menu-of-a-drive-1.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
4. Click on **Advanced Settings** in the new pop-up menu, check the **Share this folder** box, and wait, it's not over yet. Now to prevent unsolicited access to your locally shared drives, click on **Permissions**.
5. In the new menu that pops up, click on **Add**. Yet another box should pop up. Here, type in the username of your user account. Use a dedicated user account only for network access or use your primary account's username and press **Enter**. You should find your name is present on the list of users with permission to the shared drive.  
![Adding a new user in the access group of the shared drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-a-new-user-in-the-access-group-of-the-shared-drive.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Finally, click on your account name, and in the **Permissions for <account name>** section, check the **Full Control** box and hit **Apply**.  
![Adding permissions to the user account and confimring changes by pressing on Apply](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-permissions-to-the-user-account-and-confimring-changes-by-pressing-on-apply.jpg)
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's all the steps to share your drive on the local network. However, if you run into any trouble, it's recommended you check out the [dedicated guide on enabling Windows Network Share](https://www.makeuseof.com/how-network-file-share-windows-10/).

## How to Access Your Windows Files From an Android Device

 Now that you have shared the drive on the local network you'll be able to access your newly shared drives and files from your Android device in just a few taps. Make sure your Android device and Windows PC are connected to the same Wi-Fi network. With these checks out of the way, let's look at the steps to access Windows network shared files from Android:

1. Fire up the **Files** application on your Android device.
2. On the **Files** application, scroll to **Network Storage** and tap on it.
3. Inside **Network Storage**, tap on **Add network storage**. You might be asked to select an option from a list of protocols. Tap on **Network Drive** or any option with **SMB** in the name.
4. Your device will start to scan for locally shared drives. Wait for it to locate your Windows drive. If your device is unable to locate it follow the next steps. First, you need to [find the IP address of your Windows PC](https://www.makeuseof.com/find-ip-mac-address-windows-powershell/).
5. After noting the IP address, go back to your Android device and tap on **Add Manually**.
6. In the new window, type in the IPv4 address you copied earlier into the Address field. Then, type **445** into the **Port** field. Finally, fill in the **Username** and **Password** fields with your account credentials and hit on **Add** or **Connect**.

![Selecting Network Share on Files app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/selecting-network-share-on-files-app.jpg)

![Selecting SMB Protocol](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/selecting-smb-protocol.jpg)

![Manually adding the device and account details](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/manually-adding-the-device-and-account-details.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->

![Access established to the drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/access-established-to-the-drive.jpg)

Close

 Now, you should be able to access files on your Windows PC from your Android device. You can modify the files or download them to your Android device. All done without ever needing any external application!

 On some devices, such as Samsung phones, when you click on **Network Storage**, you might be asked to update the Files app to add the network access functionality. Proceed to do so, and then return to the guide.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## How to Access Your Windows Files From an iOS Device

 The steps to access Windows files from iOS are pretty much identical to the steps required for Android devices. Here's how you can access your Windows PC's files from iOS:

1. Before opening your iOS device. You need to grab the IP address of your Windows PC. There are multiple ways to do it. The easiest one being typing in **cmd** in the search box and then using the **ipconfig** command to fetch network-related details. Note down the value of the IPv4 field.
2. Fire up the **Files** application on your iOS device.
3. Click on the three horizontal dots (ellipsis) in the top right corner. From there, select **Connect to Server**.
4. A new window should open up asking you to input the IP address of the shared drive. Type in the IP address that you previously noted down and tap on **Next**.
5. Then, you will be prompted to enter the user account credentials to access the shared drive. Type them in and tap on **Next**.

![Connecting to the shared drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/connecting-to-the-shared-drive.jpeg)

![Typing in the IP of the Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/typing-in-the-ip-of-the-windows-pc.jpeg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->

![Typing in user account credentials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/typing-in-user-account-credentials.jpeg)

![Access established to the drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/access-established-to-the-drive.jpeg)

![The shared drive being listed on the Browse Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-shared-drive-being-listed-on-the-browse-menu.jpeg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->

Close

 Now you should be able to view the files on the shared drive. You can now download, upload or modify the local files on your Windows PC with ease and without having to download any third-party application.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Access Your PC Files on iOS/Android Without Third-Party Apps

 Now that you know how to access your PC files using Windows Network Share, uploading, downloading, and modifying files should be super easy to do. You won't have to rely on downloading and testing third-party applications for minor tasks like copying over a PDF file from your Windows PC to your Android/iOS devices.

 If you wish to share files between computers on the same network, that is possible as well. But, for heavy file sharing between two computers, a few alternatives to network sharing may be worth checking out if you'll be sharing large chunks of data.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/024-approved-commanding-the-screen-top-10-women-gamers-yt/"><u>[New] 2024 Approved  Commanding the Screen  Top 10 Women Gamers YT</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-fundamental-definitions-of-interactive-storytelling/"><u>[New] Fundamental Definitions of Interactive Storytelling</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-is-splitcam-the-premier-choice-for-video-capture-for-2024/"><u>[New] Is SplitCam the Premier Choice for Video Capture for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-elevating-video-view-count-top-hashtag-trends-guide-for-2024/"><u>[Updated] Elevating Video View Count  Top Hashtag Trends Guide for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-secrets-of-snapsharing-creating-invisible-chronicles/"><u>[Updated] Secrets of Snapsharing  Creating Invisible Chronicles</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-a-compreenas-guide-to-leveraging-ps-background-erasure-for-professional-results/"><u>2024 Approved  A Compreenas Guide to Leveraging PS Background Erasure for Professional Results</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-exploring-lgs-ultra-clear-4k-screen-capabilities/"><u>2024 Approved  Exploring LG's Ultra-Clear 4K Screen Capabilities</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-top-10-terraria-game-boosters/"><u>2024 Approved  Top 10 Terraria Game Boosters</u></a></li>
<li><a href="https://win11.techidaily.com/5-proven-methods-to-clean-your-win11s-dns-cache/"><u>5 Proven Methods to Clean Your Win11's DNS Cache</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-the-windows-11-mixer-interface/"><u>A Beginner’s Guide to the Windows 11 Mixer Interface</u></a></li>
<li><a href="https://win11.techidaily.com/a-guide-to-essential-windows-saver-techniques/"><u>A Guide to Essential Windows Saver Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-fix-for-0x800704b3-error-in-windows-11/"><u>A Quick Fix for 0X800704B3 Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-restoring-content-servers-connectivity/"><u>A Step-by-Step Guide to Restoring Content Servers' Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-correcting-microsoft-outlook-glitches-on-windows/"><u>Actions for Correcting Microsoft Outlook Glitches on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-and-correcting-window-based-roblox-error-403/"><u>Addressing and Correcting Window-Based Roblox Error 403</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-conflict-between-apps-and-computer-audio/"><u>Addressing Conflict Between Apps and Computer Audio</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-problem-of-non-opened-nvidia-control-panel-w11/"><u>Addressing the Problem of Non-Opened NVidia Control Panel, W11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-zeroxc000003e-problem-in-pc-application-startup/"><u>Addressing ZeroXc000003e Problem in PC Application Startup</u></a></li>
<li><a href="https://win11.techidaily.com/alternatives-for-enabling-elusive-firewall-on-windows/"><u>Alternatives for Enabling Elusive Firewall on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-to-fixing-windows-file-download-failures/"><u>Approaches to Fixing Windows File Download Failures</u></a></li>
<li><a href="https://win11.techidaily.com/atlasos-resurgence-guide-for-older-tech/"><u>AtlasOS Resurgence Guide for Older Tech</u></a></li>
<li><a href="https://win11.techidaily.com/automatic-program-management-in-windows-os/"><u>Automatic Program Management in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/averting-unwanted-windows-store-automatization/"><u>Averting Unwanted Windows Store Automatization</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-common-windows-11-login-blunders/"><u>Avoiding Common Windows 11 Login Blunders</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-data-breaches-proper-password-addition-in-windows/"><u>Avoiding Data Breaches: Proper Password Addition in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-disruptions-to-wsl-after-installing-windows-11/"><u>Avoiding Disruptions to WSL After Installing Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-lags-7-solutions-to-boost-windows-keyboard-speed/"><u>Banishing Lags: 7 Solutions to Boost Window's Keyboard Speed</u></a></li>
<li><a href="https://win11.techidaily.com/beyond-cortana-four-visionary-windows-updates/"><u>Beyond Cortana: Four Visionary Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-with-these-top-5-file-management-hacks/"><u>Boost Productivity with These Top 5 File Management Hacks</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-accessibility-of-grandparents-pre-ultimate-pcs/"><u>Boosting Accessibility of Grandparents' Pre-Ultimate PCs</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-file-explorer-performance-on-win-11/"><u>Boosting File Explorer Performance on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-essential-win11-and-cmd-commands/"><u>Boosting Productivity: Essential Win11 and Cmd Commands</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-steam-transfer-speed-averting-sudden-stops/"><u>Boosting Windows Steam Transfer Speed: Averting Sudden Stops</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-wired-internet-overcoming-100mbps-limit-in-windows/"><u>Boosting Wired Internet: Overcoming 100Mbps Limit in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-your-pc-how-to-turn-on-hyper-v-in-win11/"><u>Boosting Your PC: How To Turn On Hyper-V in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-how-to-disable-the-pesky-epic-games-hub/"><u>Break Free: How to Disable the Pesky Epic Games Hub</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-firewall-restrictions-allow-chrome-network-entry-in-windows/"><u>Breaking Firewall Restrictions: Allow Chrome Network Entry in Windows</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/comparing-smart-speakers-google-nest-audio-vs-nest-mini-showdown/"><u>Comparing Smart Speakers: Google Nest Audio Vs. Nest Mini Showdown</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/consumer-beware-only-50-of-advertised-top-tier-watercoolers-actually-incorporate-promoted-copper-components-study-finds/"><u>Consumer Beware: Only 50%% of Advertised Top-Tier Watercoolers Actually Incorporate Promoted Copper Components, Study Finds</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-zte-nubia-z60-ultra-phone-without-password-by-drfone-android/"><u>How To Unlock ZTE Nubia Z60 Ultra Phone Without Password?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-lifetime-love-affair-with-top-15-classic-stop-motion-movies/"><u>In 2024, A Lifetime Love Affair with Top 15 Classic Stop-Motion Movies</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-realme-narzo-n53-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Realme Narzo N53 Location | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719271419179-navigate-through-windows-woes-with-simple-fixes/"><u>Navigate Through Windows Woes with Simple Fixes!</u></a></li>
<li><a href="https://win11.techidaily.com/1719312305473-premium-savings-with-w11-pro-key-dont-miss-out/"><u>Premium Savings with W11 Pro Key - Don't Miss Out!</u></a></li>
<li><a href="https://extra-support.techidaily.com/prime-choice-of-low-cost-hd-action-recorders-for-2024/"><u>Prime Choice of Low-Cost HD Action Recorders for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/securely-acquire-the-most-recent-broadcom-bluetooth-software-support-for-windows-systems-versions-10-8-and-7/"><u>Securely Acquire the Most Recent Broadcom Bluetooth Software Support for Windows Systems (Versions 10, 8 & 7)</u></a></li>
<li><a href="https://sound-issues.techidaily.com/silence-the-pop-effective-solutions-to-fix-crackling-sound-problems-with-your-pcs-audio-windows-107-edition/"><u>Silence the Pop: Effective Solutions to Fix Crackling Sound Problems with Your PC's Audio - Windows 10/7 Edition</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/sim-unlock-samsung-galaxy-m34-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>Sim Unlock Samsung Galaxy M34 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-beginner-friendly-video-editing-software-top-free-options/"><u>Updated Beginner-Friendly Video Editing Software Top Free Options</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>