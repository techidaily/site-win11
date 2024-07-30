---
title: "Bridging the Gap with Telnet: 3 Easy Steps for Wins Users"
date: 2024-07-29T15:51:50.834Z
updated: 2024-07-30T15:51:50.834Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Bridging the Gap with Telnet: 3 Easy Steps for Wins Users"
excerpt: "This Article Describes Bridging the Gap with Telnet: 3 Easy Steps for Wins Users"
keywords: Win User Connectivity,Telnet Access Guide,Easy Telnet Setup,Simple Network Bridge,Secure Telnet Protocol,Network Bridging Steps,Optimize Telnet Usage
thumbnail: https://thmb.techidaily.com/9fa9e4346708270d82530e01172580b66a8c63e17b3edbe0866986af1acde6f2.jpg
---

## Bridging the Gap with Telnet: 3 Easy Steps for Wins Users

 Despite the vulnerability issues, Telnet is still used as a client-server protocol by Windows users. It is primarily used for initial network hardware configuration, remote access, port testing and forwarding, and other tasks that don't involve sensitive information transfer.

 You can enable Telnet on Windows 10 and 11 computers via Command Prompt or the Graphics User Interface (GUI) tool. Here we show you the many ways to enable Telnet on your Windows computer.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Enable Telnet on Windows Using Control Panel

 You can enable Telnet Client using the Classic Control Panel. Since it is an optional feature, you can enable it using the Windows Optional Feature dialog. You can use it[add or remove other users' optional features on Windows](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) .

To enable Telnet Client using Control Panel:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel.**
3. In Control Panel, Click on**Uninstall a Program** under**Programs and Features.**  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
![turn windows features on or off control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/turn-windows-features-on-or-off-control-panel.jpg)
4. In the left pane, click on the**Turn Windows feature on or off.**  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![enable telnet client windows features dialog](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enable-telnet-client-windows-features-dialog.jpg)
5. In the Windows Features dialog, scroll down and select**Telnet Client.**
6. Click**OK** and wait for the feature to install. Once installed, restart your PC to apply the changes and enable the feature.

If you need to disable Telnet:

1. Open the**Windows Features** dialog and unselect**Telnet Client.**
2. Click**OK** and wait for the feature to uninstall.
3. Click on**Restart** now to reboot your PC and apply the changes.

## 2\. Enable Telnet Client Using Windows PowerShell

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

1. Launch Command Prompt as administrator (see[how to run the Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) for in-depth steps).
2. In the Command Prompt window, type**Telnet** and press**Enter** .
3. A new CMD with Microsoft Telnet will open.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-easy-photo-progression-on-instagram/"><u>[New] 2024 Approved  Easy Photo Progression on Instagram</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-easy-to-navigate-top-10-youtube-downloader-tools/"><u>[New] 2024 Approved  Easy-to-Navigate Top 10 YouTube Downloader Tools</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-elite-video-influencers/"><u>[New] 2024 Approved  Elite Video Influencers</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-tailor-your-devices-alerts-with-custom-android-sounds/"><u>[New] 2024 Approved  Tailor Your Device's Alerts with Custom Android Sounds</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-election-enthusiasts-essentials-quintessential-voting-games-for-2024/"><u>[New] Election Enthusiasts' Essentials  Quintessential Voting Games for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-enhancing-video-discoverability-with-smart-thumbnails-for-2024/"><u>[New] Enhancing Video Discoverability with Smart Thumbnails for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-decoding-youtubes-operations-following-uploads/"><u>[Updated] 2024 Approved  Decoding YouTube’s Operations Following Uploads</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-gamble-for-peace-10-chill-out-choices/"><u>[Updated] Gamble for Peace  10 Chill-Out Choices</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-the-social-image-saver-stealing-and-storing-gif-images-from-twitter/"><u>[Updated] In 2024, The Social Image Saver  Stealing and Storing GIF Images From Twitter</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-unlock-the-power-scriptwriting-for-popular-vlogs/"><u>[Updated] In 2024, Unlock the Power  Scriptwriting for Popular Vlogs</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-the-ultimate-guide-to-reverse-playback-in-snapchat/"><u>[Updated] The Ultimate Guide to Reverse Playback in Snapchat</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-top-25-instagram-hashtags-to-get-more-likes-and-followers-for-2024/"><u>[Updated] Top 25 Instagram Hashtags to Get More Likes and Followers for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-urban-pursuit-without-the-need-for-gta/"><u>[Updated] Urban Pursuit Without the Need for GTA</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-websites-for-rhythmic-alerts-unique-sounds/"><u>2024 Approved  Top Websites for Rhythmic Alerts  Unique Sounds</u></a></li>
<li><a href="https://win11.techidaily.com/6-ways-to-view-the-registry-file-contents-on-windows-11/"><u>6 Ways to View the Registry File Contents on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/7-techniques-to-lower-desktop-wm-energy-usage/"><u>7 Techniques to Lower Desktop WM Energy Usage</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-motorola-moto-g23-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Motorola Moto G23 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-roadmap-to-resolve-file-creation-issues-windows-error-30005/"><u>A Roadmap to Resolve File Creation Issues - Windows Error 30005</u></a></li>
<li><a href="https://win11.techidaily.com/a-simple-guide-to-finding-out-what-model-you-run-on-windows/"><u>A Simple Guide to Finding Out What Model You Run on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-universal-companion-windows-now-app-for-iosmac-and-windows-devices/"><u>A Universal Companion: Windows Now App for iOS/Mac and Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/accessible-configuration-of-win11-connectivity-options/"><u>Accessible Configuration of Win11 Connectivity Options</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-the-character-visualization-tool/"><u>Accessing the Character Visualization Tool</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-perfect-sizing-of-your-pics-with-these-six-windows-11-tactics/"><u>Achieve Perfect Sizing of Your Pics with These Six Windows 11 Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-address-invalid-label-warning-in-windows-11/"><u>Actions to Address 'Invalid Label' Warning in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/activating-the-action-center-volume-mixing-in-windows-11/"><u>Activating the Action Center Volume Mixing in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/activatingdeactivating-filter-keys-on-microsoft-os/"><u>Activating/Deactivating Filter Keys on Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/adding-command-tab-to-taskmanager-in-windows-11-pro/"><u>Adding Command Tab to TaskManager in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-no-qt-platform-support-error-for-app-starts/"><u>Addressing 'No Qt Platform Support' Error for App Starts</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disrupted-copy-and-paste-on-windows-11/"><u>Addressing Disrupted Copy & Paste on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-jvm-not-created-a-windows-solution/"><u>Addressing JVM Not Created: A Windows Solution</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-runtime-exceptions-your-ultimate-guide-for-windows-users/"><u>Addressing Runtime Exceptions: Your Ultimate Guide for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-alert-it-admin-limited-power/"><u>Addressing Windows Alert: IT Admin Limited Power</u></a></li>
<li><a href="https://win11.techidaily.com/alter-icon-and-thumbnail-dimensions-w11/"><u>Alter Icon and Thumbnail Dimensions W11</u></a></li>
<li><a href="https://win11.techidaily.com/amplify-windows-steam-transfers-averting-sudden-halt/"><u>Amplify Windows Steam Transfers: Averting Sudden Halt</u></a></li>
<li><a href="https://win11.techidaily.com/android-transition-post-subsystem-discontinuation-whats-next/"><u>Android Transition Post-Subsystem Discontinuation: What's Next?</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-disasters-committing-to-weekly-windows-backup/"><u>Avoiding Disasters: Committing to Weekly Windows Backup</u></a></li>
<li><a href="https://win11.techidaily.com/awaken-clandestine-windows-11-search-sentinel/"><u>Awaken Clandestine Windows 11 Search Sentinel</u></a></li>
<li><a href="https://win11.techidaily.com/black-friday-brilliance-essential-keys-collectors-year-round-windows-11-savings/"><u>Black Friday Brilliance: Essential Keys Collectors, Year-Round Windows 11 Savings</u></a></li>
<li><a href="https://win11.techidaily.com/boost-speed-identifying-your-gpu-on-windows-11-os/"><u>Boost Speed: Identifying Your GPU on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-net-essential-windows-fixes-max-156/"><u>Boosting .NET: Essential Windows Fixes (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-functionality-of-taskbar-in-modern-win11/"><u>Boosting Functionality of Taskbar in Modern Win11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-image-quality-windows-11s-secret-weapon/"><u>Boosting Image Quality: Windows 11'S Secret Weapon</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-internet-performance-with-intels-ethernet-driver-on-debian/"><u>Boosting Internet Performance with Intel's Ethernet Driver on Debian</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-screen-legibility-win11-scaling-guide/"><u>Boosting Screen Legibility: Win11 Scaling Guide</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-the-file-explorer-performance/"><u>Boosting the File Explorer Performance</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-run-handbrake-in-windows/"><u>Breaking Barriers: Run HandBrake in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-boundaries-chatgpt-alternatives-win-style/"><u>Breaking Boundaries: ChatGPT Alternatives, WIN-Style</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-graphics-glitch-d3d11-error-fixes-for-win11win10/"><u>Conquering Graphics Glitch: D3D11 Error Fixes for Win11/Win10</u></a></li>
<li><a href="https://win11.techidaily.com/1719337262601-cure-frozen-shift-key-woes-quickly/"><u>Cure Frozen Shift Key Woes Quickly.</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/gamers-paradise-leading-5-hdmi-21-monitors-for-ps5-for-2024/"><u>Gamers' Paradise  Leading 5 HDMI 2.1 Monitors for PS5 for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On Samsung Galaxy XCover 7? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-vivo-x100-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Vivo X100 Location by Number | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-11-pro-max-to-other-iphone-12-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 11 Pro Max to other iPhone 12 devices? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-motorola-moto-g24-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Motorola Moto G24 to iPhone | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-honor-x50-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Honor X50 FRP Android 10/11/12/13</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-apple-iphone-15-pro-data-to-iphone-12-a-complete-guide-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Apple iPhone 15 Pro Data to iPhone 12 A Complete Guide | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-realme-v30-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Realme V30</u></a></li>
<li><a href="https://win11.techidaily.com/1719350786682-operas-plight-unleash-it-from-windows-freeze/"><u>Opera's Plight? Unleash It From Windows Freeze</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/overcome-dimness-with-easy-iphone-editing/"><u>Overcome Dimness with Easy iPhone Editing</u></a></li>
<li><a href="https://video-capture.techidaily.com/step-by-step-guide-for-filming-sims-adventures-for-2024/"><u>Step-by-Step Guide for Filming Sims Adventures for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-ultimate-list-of-ios-solutions-to-play-your-favorite-psp-games-for-2024/"><u>The Ultimate List of iOS Solutions to Play Your Favorite PSP Games for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-oneplus-open-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for OnePlus Open | Dr.fone</u></a></li>
</ul></div>
