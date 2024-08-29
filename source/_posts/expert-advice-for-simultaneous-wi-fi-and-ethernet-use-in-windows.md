---
title: Expert Advice for Simultaneous Wi-Fi & Ethernet Use in Windows
date: 2024-08-28T00:53:57.712Z
updated: 2024-08-29T00:53:57.712Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Advice for Simultaneous Wi-Fi & Ethernet Use in Windows
excerpt: This Article Describes Expert Advice for Simultaneous Wi-Fi & Ethernet Use in Windows
keywords: Wi-Fi+Ethernet Use,Simultaneous Network,Win Use Dual Connections,Windows Dual Connectivity,Expert Network Setup,Efficient Dual-Link,Optimized WI-FI/Ethernet
thumbnail: https://thmb.techidaily.com/bbf8b4ac709b45ef5944f09a459d244c293de523e01954b86b12ee5efc9e9834.jpg
---

## Expert Advice for Simultaneous Wi-Fi & Ethernet Use in Windows

 You can have your Windows computer connected to Wi-Fi and Ethernet simultaneously, but the system won't use both connections at the same. Windows automatically configures the network adapter order priority to provide the best Internet connection via Ethernet or Wi-Fi.

 However, if you have multiple ISP connections or have a local media server, you can configure your Windows laptop to use Wi-Fi and Ethernet simultaneously. To do this, you must disable packet priority for both Wi-Fi and Ethernet network adapter.

## Why You May Need to Use Both the Wi-Fi and Ethernet Connections Simultaneously

 While you may not get an additional speed advantage when using the same ISP for your Wi-Fi and Ethernet, you can have both connections up and running as a backup for critical Internet-dependent services. Also, if you have access to multiple ISP connections, you can[merge multiple connections to increase your internet speed](https://www.makeuseof.com/how-to-merge-internet-connections/) .

 Additionally, it is also useful if you have a local server and want to be connected to both the Internet and the local server simultaneously. You can connect to the local media server via Ethernet and access the internet over Wi-Fi without dropping the connection.

 On the flip side, there are chances of packet loss due to duplicate packets being transmitted via both the Wi-Fi and Ethernet connection. Lower-end routers may also notice decreased speed due to increased load on your network device. This is part of the reasons[why you may want to replace your ISP's router](http://www.makeuseof.com/tag/reasons-replace-isp-router/) .

## How to Configure Windows to Use Wi-Fi and Ethernet Connections Simultaneously

 Since Windows automatically prioritizes the network adapter to use only one adapter at a time, you'll need to disable the packet priority option in the network adapter's network configuration. Doing so will allow Windows to use multiple connections simultaneously.

To disable packet priority and VLAN on Windows:

1. Press**Win + R** to open**Run** .
2. Type**control** and click**OK** to open**Control Panel** .
3. Next, go to**Network and Internet** and click on**Network and Sharing Center.**  
![control panel network change adapter settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/control-panel-network-change-adapter-settings.jpg)
4. In the left pane, click on**Change adapter settings.**
5. Right-click on your**Ethernet network adapter** and select**Properties** . Alternatively, double-click on the**Ethernet adapter** and then click on**Properties** .  
![ethernet properties configure networking control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ethernet-properties-configure-networking-control-panel.jpg)

1. In the**Networking** tab, click the**Configure** button.
2. Next, open the**Advanced** tab.
3. Select**Priority and VLAN** under the**Property** section.
4. Click the drop-down under**Value** .  
![priority vlan disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/priority-vlan-disabled.jpg)
5. Select**Priority and VLAN Disabled.**
6. Click**OK** to save the changes.
7. Next, you need to repeat the steps for your Wi-Fi adapter. So, open Properties for your Wi-Fi adapter and set its**Priority and VLAN** value to**Priority & VLAN Disabled** .
8. Click**OK** to save the changes.

 With the network adapter priority option disabled, Windows will now use both network connections simultaneously.

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Make Your Computer Use Your Wi-Fi and Ethernet at the Same Time

 You can configure the network adapter on your computer to use both Wi-Fi and Ethernet connection simultaneously. While it has many advantages, it won't increase your Internet speed. Instead, you’ll need multiple Internet connections powering your Wi-Fi and Ethernet networks to see increased speed.

 Alternatively, if you have multiple Wi-Fi connections at home or office, you can configure your Windows computer to automatically switch to the strongest Wi-Fi network available when you move around.


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
<li><a href="https://screen-capture.techidaily.com/new-budget-conscious-obs-tweaks-and-tricks/"><u>[New] Budget-Conscious OBS Tweaks and Tricks</u></a></li>
<li><a href="https://youtube-web.techidaily.com/nspecting-dialogues-in-youtube-vids/"><u>[New] Inspecting Dialogues in YouTube Vids</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-premium-mix-picture-taking-plus-sounds-recorder-titles/"><u>[New] Premium Mix  Picture Taking + Sounds Recorder Titles</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-boost-your-income-with-effective-vimeo-monetization-techniques/"><u>[Updated] In 2024, Boost Your Income with Effective Vimeo Monetization Techniques</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-ideation-at-its-peak-crafting-impressive-youtube-titles/"><u>[Updated] In 2024, Ideation at Its Peak  Crafting Impressive YouTube Titles</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-mastering-money-with-8-youtube-aspects/"><u>[Updated] Mastering Money with 8 YouTube Aspects</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-iphone-video-editing-shorten-crop-and-resize-basics/"><u>2024 Approved  IPhone Video Editing  Shorten, Crop & Resize Basics</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-no-complications-in-hdr-a-thorough-review/"><u>2024 Approved  No Complications in HDR  A Thorough Review</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-multiple-mail-systems-merge-gmail-and-outlook-windows/"><u>Conquering Multiple Mail Systems: Merge Gmail and Outlook, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-nvidia-experience-error-setting-retrieval-woes-in-windows-1011/"><u>Correcting NVIDIA Experience Error - Setting Retrieval Woes in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/customizing-windows-11s-system-monitor-homepage/"><u>Customizing Windows 11'S System Monitor Homepage</u></a></li>
<li><a href="https://activate-lock.techidaily.com/effective-ways-to-fix-checkra1n-error-31-on-apple-iphone-8-plus-by-drfone-ios/"><u>Effective Ways To Fix Checkra1n Error 31 On Apple iPhone 8 Plus</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-device-recognition-with-razers-software-on-windows-11/"><u>Enabling Device Recognition with Razer's Software on Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ensuring-device-compatibility-a-how-to-for-backing-up-drivers-in-windows-1110/"><u>Ensuring Device Compatibility: A How-To for Backing Up Drivers in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/erase-ms-defender-logs-a-guide-to-cleansing-on-windows-oses/"><u>Erase MS Defender Logs: A Guide to Cleansing on Windows OSes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/exploring-with-tomtom-actioncam-new-year-for-2024/"><u>Exploring with TomTom ActionCam New Year for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-non-working-keys-focus-on-windows-enter/"><u>Fixing Non-Working Keys: Focus on Windows Enter</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-app-blocks-system-function-problem-on-your-pc/"><u>Fixing the App Blocks System Function Problem on Your PC</u></a></li>
<li><a href="https://solve-helper.techidaily.com/harnessing-the-power-of-cookiebot-for-advanced-analytics-and-personalization/"><u>Harnessing the Power of Cookiebot for Advanced Analytics and Personalization</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-vivo-s17-pro-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Vivo S17 Pro? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-size-constraints-essential-tips-for-resizable-gifs-on-discowin11/"><u>How to Bypass Size Constraints: Essential Tips for Resizable GIFs on DiscoWin11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-google-chrome-from-tracking-your-location-on-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>How to Stop Google Chrome from Tracking Your Location On Vivo Y55s 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-switch-from-standard-home-page-in-windows-11/"><u>How to Switch From Standard Home Page in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-nokia-c12-pro-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Nokia C12 Pro to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-infinix-zero-30-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Infinix Zero 30 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-gameplay-streaming-tools-revealed-obs-or-fraps/"><u>In 2024, Gameplay Streaming Tools Revealed  OBS or Fraps?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-nokia-c32-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Nokia C32? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/innovative-window-11-lock-pattern-designing-techniques/"><u>Innovative Window 11 Lock Pattern Designing Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/key-fixes-for-smooth-play-on-apex-legends-after-a-crash/"><u>Key Fixes for Smooth Play on Apex Legends After a Crash</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-package-management-via-winget-in-windows-11/"><u>Mastering Package Management via Winget in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-store-fixes-handling-error-code-0x80072f17/"><u>Microsoft Store Fixes: Handling Error Code 0X80072F17</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-a-stuck-windows-update-hurdle-a-plan-b/"><u>Navigating a Stuck Windows Update Hurdle: A Plan B</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-process-of-turning-esd-files-into-windows-isos/"><u>Navigating the Process of Turning ESD Files Into Windows ISOs</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-audio-record-functionality/"><u>Navigating Windows' Audio Record Functionality</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-expert-approach-to-extracting-and-erasing-drum-tracks-from-songs-digitally-hosted-online/"><u>New Expert Approach to Extracting and Erasing Drum Tracks From Songs Digitally Hosted Online</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-integrated-graphics-a-step-by-step-guide/"><u>Overcoming Integrated Graphics: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-robloxs-access-denied-error-403-in-windows/"><u>Overcoming Roblox's Access Denied (Error 403) in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-stuck-in-resizing-error-a-step-by-step-guide-to-fixes-discord-win11/"><u>Overcoming Stuck-in-Resizing Error: A Step-by-Step Guide to Fixes (Discord, Win11)</u></a></li>
<li><a href="https://win11.techidaily.com/peering-into-win11s-data-harvest-routines/"><u>Peering Into Win11’s Data Harvest Routines</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-windows-lockscreen-enabledisable-image-display/"><u>Personalizing Windows Lockscreen: Enable/Disable Image Display</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/quick-guide-to-achieving-video-freeze-effects-on-snapchat-for-2024/"><u>Quick Guide to Achieving Video Freeze Effects on Snapchat for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-insufficient-vm-ram-issue/"><u>Resolving Windows: Insufficient VM RAM Issue</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functionality-of-disabled-print-spooler-in-winos/"><u>Restoring Functionality of Disabled Print Spooler in WinOS</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-using-onedrive-offline-in-windows/"><u>Step-by-Step Guide to Using OneDrive Offline in Windows</u></a></li>
<li><a href="https://program-issues.techidaily.com/stop-chrome-from-freezing-in-windows-10-with-simple-fixes/"><u>Stop Chrome From Freezing in Windows 10 with Simple Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/synchronize-chrono-errors-chrome-and-pc-tick-alignment/"><u>Synchronize Chrono-Errors: Chrome & PC Tick Alignment</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-separating-concentrated-pc-icons/"><u>Techniques for Separating Concentrated PC Icons</u></a></li>
<li><a href="https://buynow-info.techidaily.com/top-10-engrossing-board-and-video-games-perfect-for-your-next-free-time/"><u>Top 10 Engrossing Board and Video Games Perfect for Your Next Free Time</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-guide-for-broken-windows-google-nearby-share/"><u>Troubleshooting Guide for Broken Windows Google Nearby Share</u></a></li>
<li><a href="https://win11.techidaily.com/turning-onoff-win-10-and-11-phishing-alerts/"><u>Turning On/Off Win 10 & 11 Phishing Alerts</u></a></li>
<li><a href="https://win-blog.techidaily.com/update-or-fresh-install-logitech-g403-drivers-for-optimal-performance-on-windows-computers/"><u>Update or Fresh-Install Logitech G403 Drivers for Optimal Performance on Windows Computers</u></a></li>
<li><a href="https://win11.techidaily.com/windows-voice-conversion-made-easy-using-whisper/"><u>Windows Voice Conversion Made Easy Using Whisper</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-honor-magic-v2-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Honor Magic V2? Here Is the Answer | Dr.fone</u></a></li>
</ul></div>
