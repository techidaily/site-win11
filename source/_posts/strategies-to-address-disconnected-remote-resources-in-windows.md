---
title: Strategies to Address Disconnected Remote Resources in Windows
date: 2024-06-25T11:41:52.658Z
updated: 2024-06-26T11:41:52.658Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Address Disconnected Remote Resources in Windows
excerpt: This Article Describes Strategies to Address Disconnected Remote Resources in Windows
keywords: Win Remote Connectivity Strategies,Remote Resource Linking Tips,Secure Window Remote Access,Bypass Disconnected Windows,Optimize Remote Workflows,Enhance Remote Network Usage,Fixing Remote Resource Isolation
thumbnail: https://thmb.techidaily.com/e2b3e6d5f3444ca9eb9fe2e05133bcedc239a2116beb3419cf2a3656ee84dbb0.jpg
---

## Strategies to Address Disconnected Remote Resources in Windows

 So, you've connected your Windows computer to a network and are ready to surf the internet, but you're getting the "No internet access" error. You fire up the Windows Network Diagnostics tool, only to be told that "The remote device or resource won’t accept the connection."

 Well, don't panic, as we're going to show you how to get rid of that error.

## 1\. Disable Your Antivirus and Firewall

 You might be getting the "The remote device or resource won’t accept the connection" error due to your antivirus interfering with the connection. To rule out that possibility, try disabling it to see if the error goes away. If you're using Windows' built-in antivirus, then you can learn [how to disable Microsoft Defender](http://www.makeuseof.com/how-to-turn-off-windows-defender/).

 If turning off your antivirus didn't work, then perhaps the Firewall could be behind the issue. While this program does a good job of keeping your network safe from harmful traffic, it can sometimes block connections it shouldn't. Try [turning off the Windows Firewall](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) and see if that will resolve the error.

## 2\. Reset Your Web Browser

 Corrupt or misconfigured browser settings can also cause the error to pop up, and resetting it can help. We're going to show you how to reset three of the most popular browsers on Windows: Chrome, Edge, and Firefox.

 To reset Chrome, follow the steps below:

1. Open Chrome and click the three-dot icon in the top-right corner.  
![the three dot icon in google chrome](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-three-dot-icon-in-google-chrome.jpg)
2. In the menu, click on **Settings**.  
![the google chrome menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-google-chrome-menu.jpg)
3. On the left side menu, select **Reset settings**, and then click on **Reset settings to their original defaults** on the right.  
![the reset settings page of google chrome](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-reset-settings-page-of-google-chrome.jpg)
4. In the pop-up, confirm you want to reset Chrome by clicking on **Reset settings**.  
![the pop up to reset settings in google chrome](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-pop-up-to-reset-settings-in-google-chrome.jpg)

 To reset Edge, follow the steps below:

1. Open Edge and click on the three-dot icon in the top-right corner.  
![the three dot icon in microsoft edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-three-dot-icon-in-microsoft-edge.jpg)
2. In the menu, click on **Settings**.  
![the microsoft edge menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-microsoft-edge-menu.jpg)
3. On the left side menu, select **Reset settings**, and then click on **Restore settings to their default values** on the right.  
![the reset settings page of microsoft edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-reset-settings-page-of-microsoft-edge.jpg)
4. In the pop-up, confirm you want to reset Edge by clicking on **Reset**.  
![the pop up to reset settings in microsoft edge](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-pop-up-to-reset-settings-in-microsoft-edge.jpg)

 To reset Firefox, follow the steps below:

1. Open Firefox and click on the hamburger menu icon in the top-right corner.  
![the hamburger menu icon in firefox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-hamburger-menu-icon-in-firefox.jpg)
2. In the menu, click on **Help**.  
![the firefox menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-firefox-menu.jpg)
3. Click on **More troubleshooting information**.  
![the firefox help menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-firefox-help-menu.jpg)
4. In the small panel on the right side, click on **Refresh Firefox**.  
![the troubleshooting information page of firefox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-troubleshooting-information-page-of-firefox.jpg)
5. In the pop-up, confirm you want to reset Firefox by clicking on **Refresh Firefox**.  
![the pop up to reset settings in firefox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-pop-up-to-reset-settings-in-firefox.jpg)

 After resetting the browser, try and see if the error has disappeared in the Windows Network Diagnostics tool.

## 3\. Reset Your IP Address

 If there's a problem with your computer's IP address, you can run into the "The remote device or resource won’t accept the connection" error.

 Follow the steps below to reset your IP address:

1. Press **Win + S** to bring up Windows Search. Type **cmd** in the search results, and when Command Prompt shows up in the search results, right-click it and select **Run as administrator**.  
![Opening CMD as Administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/opening-CMD-as-administrator.jpg)
2. Type the following command in Command Prompt and then press **Enter**:  
ipconfig/release
3. Next, type the following command and press **Enter**:  
ipconfig/renew  
![resetting and renewing an ip address in command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/reseting-and-renewing-an-ip-address-in-command-prompt.jpg)

 Once you finish running the commands, check to see if the error is gone.

## 4\. Turn Off the Proxy Server

 If you're using a proxy server that is no longer working properly, you can also run into the "The remote device or resource won’t accept the connection" error.

 Follow the steps below to disable the proxy server:

1. Press **Win + R** to launch Windows Run.
2. In the Run text box, type **inetcpl.cpl**, and then hit the **Enter** key on your keyboard to open Internet Properties.  
![run inetcpl](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/run-inetcpl.png)
3. Select the **Connections** tab and then click on the **LAN settings** button towards the bottom.  
![the connections tab in internet properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-connections-tab-in-internet-properties.jpg)
4. In the **Proxy server** section, uncheck the **Use a proxy server for your LAN** checkbox.  
![the lan settings page on windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/08/the-lan-settings-page-on-windows.jpg)
5. Click **OK** to close LAN Settings.
6. Click **OK** in Internet Properties to apply the changes and close it.

 Check to see if the internet on your computer is working properly again.

## 5\. Force Update Your Group Policies

 If you have made changes to your proxy server settings, it could be that some group policies have not had time to register and consolidate those changes.

 While they will eventually refresh on their own and start working as expected, you can speed the process along by [manually refreshing the Local Group Policy Editor](https://www.makeuseof.com/window-refresh-group-policy-settings/). Then, try and see if the error is gone afterward.

## Get to the Bottom of What's Interfering With the Connection

 With the steps outlined above, you should be able to get to the bottom of the "The remote device or resource won’t accept the connection" error.

 As you can see, the root cause of this error boils down to a misconfiguration of your network settings. And if everything outlined above doesn't work, you should consider the nuclear option: resetting Windows.

 Well, don't panic, as we're going to show you how to get rid of that error.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/elevate-valorant-gameplay-fps-fixes-and-tips/"><u>Elevate Valorant Gameplay: FPS Fixes and Tips</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-scripts-in-windows-quick-fixes-for-loading-powershell-failures/"><u>Enabling Scripts in Windows: Quick Fixes for Loading PowerShell Failures</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-gaming-power-drain-from-wm/"><u>Cutting Down Gaming Power Drain From WM</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-errors-with-windows-event-logger/"><u>Overcoming Errors with Windows Event Logger</u></a></li>
<li><a href="https://win11.techidaily.com/win-friendly-tools-the-8-best-video-editing-picks/"><u>Win-Friendly Tools: The 8 Best Video Editing Picks</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-uncertainty-check-cpu-generation-on-windows-8-ways/"><u>Avoid Uncertainty – Check CPU Generation on Windows (8 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-steam-audio-issues/"><u>Fixing Common Steam Audio Issues</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-settings-error-in-nvidias-geforce-app-windows-11/"><u>Steps to Overcome 'Settings Error' In NVIDIA's GeForce App (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/handling-dxgierrordeviceremoved-in-win-10-and-11/"><u>Handling DXGI_ERROR_DEVICE_REMOVED in Win 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/betrayed-by-touch-the-latest-vulnerabilities-in-windows-fingerprint-tech/"><u>Betrayed by Touch: The Latest Vulnerabilities in Windows Fingerprint Tech</u></a></li>
<li><a href="https://some-guidance.techidaily.com/streamlining-your-video-calls-how-to-utilize-zoom-on-win10-pcs-for-2024/"><u>Streamlining Your Video Calls  How to Utilize Zoom on Win10 PCs for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-a-comprehensive-guide-to-apple-iphone-11-pro-blacklist-removal-tips-and-tools-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to Apple iPhone 11 Pro Blacklist Removal Tips and Tools</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-camera-elevation-best-tripods-for-smartphone-shots/"><u>[New] Camera Elevation  Best Tripods for Smartphone Shots</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-realme-c51-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Realme C51 Phone | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-the-ephemeral-era-of-fb-video/"><u>2024 Approved  The Ephemeral Era of FB Video</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/top-10-guide-to-simple-business-channel-launches-on-youtube/"><u>Top 10 Guide to Simple Business Channel Launches on YouTube</u></a></li>
<li><a href="https://extra-information.techidaily.com/building-a-vivid-world-with-animated-clips-in-movie-maker/"><u>Building a Vivid World with Animated Clips in Movie Maker</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-strategies-for-effortlessly-sharing-youtube-videos-on-fb/"><u>[Updated] Strategies for Effortlessly Sharing YouTube Videos on FB</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-unleashing-video-potential-the-imovie-blueprint-for-youtube-editors/"><u>[New] Unleashing Video Potential  The iMovie Blueprint for YouTube Editors</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-photo-enhancing-apps-for-smartphones-with-overlays-top-10/"><u>Best Photo-Enhancing Apps for Smartphones with Overlays (Top 10)</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>