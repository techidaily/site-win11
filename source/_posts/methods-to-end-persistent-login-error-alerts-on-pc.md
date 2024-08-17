---
title: Methods to End Persistent Login Error Alerts on PC
date: 2024-08-16T00:40:45.622Z
updated: 2024-08-17T00:40:45.622Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Methods to End Persistent Login Error Alerts on PC
excerpt: This Article Describes Methods to End Persistent Login Error Alerts on PC
keywords: Fixing Login Fails,Stop Login Alerts,Resolve Login Errors,Eliminate Login Issues,End Erroneous Logins,Quiet PC Login Errors,Prevent Login Troubles
thumbnail: https://thmb.techidaily.com/672b93a029ff6e4433ec19a377fab4ffa2a67286a950d0a63433c57fd863da90.jpg
---

## Methods to End Persistent Login Error Alerts on PC

 The network credentials on your PC are important because they prevent others from using your computer across the network. While this feature is essential to protect your important files and improve the overall security of your system, it can sometimes cause issues as well.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.

## 1\. Modify the Advanced Sharing Settings

 An incorrectly set Advanced Sharing setting is one of the most common causes of this error. Ideally, your PC should be allowed to manage homegroup connections. You can also use the Advanced Sharing settings page to disable password-protected sharing, which will allow you to share files without needing to log in.

 Here is how you can configure the Advanced Sharing settings correctly:

1. Locate the network icon on your taskbar and right-click on it.
2. Choose **Network and Internet settings** from the context menu.  
![Network and Internet settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/network-and-internet-settings.jpg)
3. In the following window, select **Network and Sharing Center**.
4. Choose **Change advanced sharing settings** option in the left pane.
5. Now, enable the **Allow Windows to manage homegroup connections (recommended)** option under Homegroup connections.
6. Click **Save changes** (you will need administrative access for this).
7. Now, expand the **All Networks** section and enable the **Turn off password protected sharing** option.  
![Turn off password sharing option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/turn-off-pasword-sharing.jpg)
8. Hit the **Save changes** button to complete the process.

 After you've transferred the files, re-enable password-protected sharing so that others don't get easy access to your PC.

## 2\. Use Your Microsoft Account Credentials or the Computer's Name

 You can also try logging onto the target PC using the Microsoft account credentials instead of the local username and password.

 Alternatively, you can also try using the name of the computer you are using alongside your username in the text field associated with the Username. Do not enter a space, bar, or any other symbol between the names.

 If the problem is associated with the credentials, one of these two methods is likely to help you get rid of it for good.

## 3\. Manually Add the Credentials of the Target Computer to the Credential Manager

 Another way to fix the issue is by manually adding the credentials of the targeted computer in the Credential Manager and seeing if that makes a difference.

 Here is how you can do that:

1. Type "Credential Manager" into Windows Search and click **Open**.
2. Select **Windows Credential** and click on **Add a Windows Credential**.  
![Windows credentials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/windows-credentials-1.jpg)
3. Now, add the username, computer name, and password of the computer you are trying to access. Check if you can now share files with the other device successfully.

## 4\. Create a New User Account on Both Devices

 There are times when user accounts become corrupt and stop you from performing certain actions. If this has happened, either on your PC or the target computer, it can interrupt the file-sharing process.

 To fix this problem, first, try [switching to a different user account](https://www.makeuseof.com/windows-11-switch-user-accounts/) on your own computer and see if that works. If this strategy fails, then we recommend [creating a new user account](https://www.makeuseof.com/windows-11-create-local-user-account/) on both devices with the same username and password. Make sure that both accounts have administrative privileges. While you are at it, we also suggest temporarily disabling any third-party antivirus program that you might be using, as it can sometimes block network access.

 If the root of your issue was a corrupt user account, this should be enough to fix the issue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
## 5\. Restart the Credential Manager Service

 The issue might also be with the Credential Manager service itself instead of the targeted computer or the network settings of your device. In this method, we will first enable the Credential Manager service if the service is disabled.

 If it is working already, then we will proceed with restarting the service and see if that does the trick.

 Here is what you need to do:

1. Press **Win** \+ **R** to open Run.
2. Type services.msc in the Run and click **Enter**.
3. In the following window, look for the Credential Manager service and right-click on it.
4. Choose **Properties** from the context menu.
5. If the service is disabled, click on the **Start button** to enable it.
6. In case it is working already, click on the **Stop button**, wait for a few seconds, and then hit the **Start button**.
7. ![Credential Manager properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-properties.jpg)  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
 Make sure that the Startup type is set to **Automatic**.  
![Credential Manager service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-service.jpg)
8. Click **Apply** \> **OK** to save the changes.

 Now try connecting to the targeted computer and see if you can do so without any problems.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## 6\. Make Changes to the Local Security Policy

 Several users also managed to fix the problem by modifying the settings of the "Accounts: Limit local account use of blank passwords to console logon only" policy. Here is how you can give it a try too:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "secpol.msc" in Run and click **Enter**.
3. In the following window, navigate to the following location:  
Local Policies > Security Options > Accounts: Limit local account use of blank passwords to console logon only
4. Choose **Disabled** and click **Apply** \> **OK** to save the changes.  
![Make changes to the Local Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-security-policy.jpg)
5. Restart your computer and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 7\. Try Using Safe Mode With Networking

 If the credentials you are entering and all the network configurations on the system are correct, something might have gone wrong on a system level.

 In this case, you can boot into Safe Mode to determine the cause of the issue. Safe Mode starts Windows with only the basic set of drivers and apps — the ones that are essential for the operating system to function.

 There are several types of Safe Mode including Minimal, Alternate Shells, Active Directory Repair, and Network. In this method, we will be booting Windows into Safe Mode with Networking. This mode launches Windows with the drivers and programs required to connect the system to the internet or other devices over the network.

 If the error at hand does not appear in Safe Mode, then there is a chance that malware or other software issues are causing the problem.

 Here is what you need to do:

1. Head over to the Start menu and click on the **Power button**.
2. Choose **Restart** while holding the **Shift key**.
3. Wait for the Windows to boot into the recovery mode and then choose **Troubleshoot** \> **Advanced Options**.
4. Navigate to **Startup Settings** \> **Restart**.
5. In the following window, press the **F5 key** on your keyboard to boot into Safe Mode with Networking.  
![Pick safe mode with Networking option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/Tweak-Startup-Settings-1.jpg)
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Once you are logged into Safe Mode, try connecting to the device you were previously trying to connect to. If the error does not appear in Safe Mode, then you might want to report this issue to Microsoft’s official support team and wait for a fix from their side.

 In case you cannot access this Windows state using the steps outlined above, you can try [other ways of booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/).

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
## Share Data Over Network Without Issues

 Windows has made it simpler to share your files and other data across networks, but there are times when you run into unexpected errors. Hopefully, one of the methods mentioned above did the trick for you in fixing the issue under consideration.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-from-novice-to-pro-creating-impressive-fb-covers/"><u>[New] In 2024, From Novice to Pro  Creating Impressive FB Covers</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-mastering-the-art-of-digital-recording-for-gotomeet-sessions/"><u>[New] In 2024, Mastering the Art of Digital Recording for GoToMeet Sessions</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-inside-apoyser-detailed-comparison-with-leading-screen-recorder-apps-for-2024/"><u>[New] Inside Apoyser  Detailed Comparison with Leading Screen Recorder Apps for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-viewer-growth-strategy-dynamic-description-templates-for-youtube-success/"><u>[New] Viewer Growth Strategy  Dynamic Description Templates for YouTube Success</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-the-instagram-growth-strategy-handbook/"><u>[Updated] 2024 Approved  The Instagram Growth Strategy Handbook</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-making-the-most-out-of-video-calls-combining-skype-and-zoom/"><u>[Updated] Making the Most Out of Video Calls  Combining Skype & Zoom</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-streamline-your-thumbnail-design-journey-today/"><u>[Updated] Streamline Your Thumbnail Design Journey Today</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-companion-for-creating-unique-metaverse-avatars/"><u>[Updated] The Ultimate Companion for Creating Unique Metaverse Avatars</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-optimal-vision-selections-of-best-4k-dslrs-in-action/"><u>2024 Approved  Optimal Vision  Selections of Best 4K DSLRs in Action</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-photoshops-stabilization-capabilities-real-advantage/"><u>2024 Approved  Photoshop's Stabilization Capabilities  Real Advantage?</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-delete-a-drive-partition-on-windows/"><u>4 Ways to Delete a Drive Partition on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/5-proven-methods-to-clean-your-win11s-dns-cache/"><u>5 Proven Methods to Clean Your Win11's DNS Cache</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-the-windows-11-mixer-interface/"><u>A Beginner’s Guide to the Windows 11 Mixer Interface</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprerante-tale-to-transform-your-windows-11-desk/"><u>A Comprerante Tale to Transform Your Windows 11 Desk</u></a></li>
<li><a href="https://win11.techidaily.com/a-quick-fix-for-0x800704b3-error-in-windows-11/"><u>A Quick Fix for 0X800704B3 Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-to-windows-11-shortcuts/"><u>A Step-by-Step Approach to Windows 11 Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-restoring-content-servers-connectivity/"><u>A Step-by-Step Guide to Restoring Content Servers' Connectivity</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-print-settings-made-easy-a-win11-guide-max-52-chars/"><u>Accessing Print Settings Made Easy: A Win11 Guide (Max 52 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-a-pristine-windows-11-workspace/"><u>Achieve a Pristine Windows 11 Workspace</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-3d-audio-with-dolby-atmos-on-windows/"><u>Achieving 3D Audio with Dolby Atmos on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/actions-for-correcting-microsoft-outlook-glitches-on-windows/"><u>Actions for Correcting Microsoft Outlook Glitches on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/adding-external-disk-to-explorers-sidebar/"><u>Adding External Disk to Explorer's Sidebar</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-conflict-between-apps-and-computer-audio/"><u>Addressing Conflict Between Apps and Computer Audio</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-malfunctions-in-windows-batch-file-systems/"><u>Addressing Malfunctions in Windows Batch File Systems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-problem-of-non-opened-nvidia-control-panel-w11/"><u>Addressing the Problem of Non-Opened NVidia Control Panel, W11</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tactics-make-windows-11-search-invisible/"><u>Advanced Tactics: Make Windows 11 Search Invisible</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-tips-for-organizing-files-in-win-os-max-156/"><u>Advanced Tips for Organizing Files in Win OS (Max 156)</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-infinix-hot-30-5g-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Infinix Hot 30 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/alternatives-for-enabling-elusive-firewall-on-windows/"><u>Alternatives for Enabling Elusive Firewall on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/approaches-to-fixing-windows-file-download-failures/"><u>Approaches to Fixing Windows File Download Failures</u></a></li>
<li><a href="https://win11.techidaily.com/atlasos-resurgence-guide-for-older-tech/"><u>AtlasOS Resurgence Guide for Older Tech</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-common-windows-11-login-blunders/"><u>Avoiding Common Windows 11 Login Blunders</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-microsoft-store-crashes-solving-0x80072f30-error/"><u>Avoiding Microsoft Store Crashes: Solving 0X80072F30 Error</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-the-workload-of-ntoskrnlexe/"><u>Balancing the Workload of Ntoskrnl.exe</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-lags-7-solutions-to-boost-windows-keyboard-speed/"><u>Banishing Lags: 7 Solutions to Boost Window's Keyboard Speed</u></a></li>
<li><a href="https://tech-hub.techidaily.com/behind-closed-portals-a-comprehensive-guide-to-internet-phantoms/"><u>Behind Closed Portals: A Comprehensive Guide to Internet Phantoms</u></a></li>
<li><a href="https://win11.techidaily.com/boost-chat-speed-enable-bing-ai-in-windows-11-menu-bar/"><u>Boost Chat Speed: Enable Bing AI in Windows 11 Menu Bar</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-using-github-desktop-on-windows-1011/"><u>Boost Productivity: Using GitHub Desktop on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-file-explorer-performance-on-win-11/"><u>Boosting File Explorer Performance on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-productivity-essential-win11-and-cmd-commands/"><u>Boosting Productivity: Essential Win11 and Cmd Commands</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-steam-transfer-speed-averting-sudden-stops/"><u>Boosting Windows Steam Transfer Speed: Averting Sudden Stops</u></a></li>
<li><a href="https://win11.techidaily.com/boot-barriers-busted-5-proven-steps-for-secure-boot-fixes/"><u>Boot Barriers Busted: 5 Proven Steps for Secure Boot Fixes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-pictures-from-honor-70-lite-5g-by-fonelab-android-recover-pictures/"><u>Easy steps to recover deleted pictures from Honor 70 Lite 5G.</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-go-joystick-on-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Tecno Spark 10 4G? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Xiaomi Redmi Note 12R | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-cut-the-clutter-advanced-techniques-for-cam-recordings/"><u>In 2024, Cut the Clutter  Advanced Techniques for Cam Recordings</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-gopro-hero-5-vs-nikon-km-170-for-adventurers/"><u>In 2024, GoPro HERO 5 vs Nikon KM-170 for Adventurers</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-oppo-a58-4g-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Oppo A58 4G to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-apple-iphone-13-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, List of Pokémon Go Joysticks On Apple iPhone 13 mini | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-smartphone-guide-crafting-engaging-video-content/"><u>In 2024, Smartphone Guide  Crafting Engaging Video Content</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-nubia-red-magic-8s-proplus-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Nubia Red Magic 8S Pro+ FRP</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-photographers-guide-to-online-image-editing-and-cropping/"><u>In 2024, The Photographer's Guide to Online Image Editing and Cropping</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/list-of-pokemon-go-joysticks-on-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/lock-your-nokia-c12-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>Lock Your Nokia C12 Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-mobile-listening-androids-best-podcast-apps-top-6/"><u>Mastering Mobile Listening  Android's Best Podcast Apps (Top 6)</u></a></li>
<li><a href="https://win11.techidaily.com/1719292127499-overcome-windows-shift-glitch/"><u>Overcome Windows Shift Glitch.</u></a></li>
<li><a href="https://data-wizards.techidaily.com/prime-image-rehabilitation-app/"><u>Prime Image Rehabilitation App</u></a></li>
<li><a href="https://extra-hints.techidaily.com/quick-and-easy-how-to-transform-your-mobile-device-into-a-vr-headset/"><u>Quick and Easy  How to Transform Your Mobile Device Into a VR Headset</u></a></li>
<li><a href="https://extra-tips.techidaily.com/understanding-the-capacity-for-storing-videos-on-large-scale-drives-64128gb/"><u>Understanding the Capacity for Storing Videos on Large-Scale Drives (64/128GB)</u></a></li>
</ul></div>
