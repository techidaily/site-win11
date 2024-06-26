---
title: Steps to Eliminate Server Stumbled Errors in Microsoft Store
date: 2024-06-25T10:15:07.229Z
updated: 2024-06-26T10:15:07.229Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Eliminate Server Stumbled Errors in Microsoft Store
excerpt: This Article Describes Steps to Eliminate Server Stumbled Errors in Microsoft Store
keywords: Fixing Microsoft Store Errors,Eliminating Store Glitches,Resolving Store Crashes,Troubleshooting MS Stumble,Clearing Store Errors Quickly,Stop MS Store Failures,Removing Store Hiccups
thumbnail: https://thmb.techidaily.com/37be59bd79492103146c553d037e355365677b2067dd8fea4392e3520b311142.jpg
---

## Steps to Eliminate Server Stumbled Errors in Microsoft Store

 Some Microsoft Store users have reported a “server stumbled” error on support forums. Those users have seen this error message within the Microsoft Store app: “The server stumbled… We all have bad days.” That error message usually has 0x80072F05, 0x80131500, or 0x80072ee7 codes.

 This is yet another error that makes the Microsoft Store app unusable when users launch it. Does the same “server stumble” error message crash your Microsoft Store app? If that’s the case, this is how you can resolve that “server stumble” error in Windows 11 and 10.

## 1\. Run the Troubleshooter for Microsoft Store Apps

 The Windows Store App troubleshooter can resolve issues that stop the Microsoft Store app from working. Running that troubleshooter isn’t a surefire fix for every Microsoft Store error, but it’s worth a try.

 These are the steps for running the Windows Store App troubleshooter in Windows:

1. Press**Win + I** keyboard shortcut to open Settings.
2. Then select the**Troubleshoot** navigation bar within Settings’ default**System** tab.
3. Click**Other troubleshooters** to reach the troubleshooting tools.
4. Select the**Run** option for launching Windows Store Apps.  
![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/the-run-button.jpg)
5. Click to apply any potential fix suggested within the troubleshooter.  
![Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-store-apps-troubleshooter.jpg)

 The steps for opening the same troubleshooter in Windows 10 aren’t exactly the because of the Settings app’s different layout. You’ll need to click**Update & Security** \>**Troubleshoot** \>**Additional Troubleshooters** in Windows 10’s Settings app. Click Windows Store Apps to press a**Run the troubleshooter** button that opens that troubleshooting tool.

## 2\. Check the Date & Time Settings on Your PC

 Date & time discrepancies on your PC can cause Microsoft Store connectivity issues like the “server stumbled” error to arise. Check the time zone you’ve got set matches up with your PC’s regional configuration. You can verify your PC’s time by selecting to sync its clock. This is how you can check the time configuration within Settings:

1. Open Settings and select the**Time & language** tab.
2. Then click**Date & time** to view those settings.
3. Make sure the correct time zone for your region is selected on the**Time zone** drop-down menu.  
![The Sync now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/time-zone-drop-down-menu.jpg)
4. Press the**Sync now** button to synchronize with the Windows time server.

## 3\. Start or Restart the Windows Update Service

 MS Store users have confirmed they’ve fixed the “server stumbled” error by starting or restarting the Windows Update service. The Windows Update service is linked with Microsoft Store. So, make sure that the update service is enabled and running as follows:

1. Press**Win + S** to access the Windows Search tool.
2. Type "services," then select**Services** to access the app.
3. Double-click**Windows Update** to view the various settings for that service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-service.jpg)
4. Select**Automatic** if any other option is set on the**Startup** type drop-down menu.
5. Then click the service’s**Start** option if Windows Update is stopped.
6. Press**Apply** to set the service settings.  
![The Windows Update Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/windows-update-properties-window.jpg)
7. Click**OK** or the**X** button to exit Windows Update’s properties window.

 Restart Windows Update if you find that the service is already running with an**Automatic** startup set. You can do that by clicking Windows Update with your mouse’s right button and selecting**Restart** . Or select**Stop** and then**Start** within its properties window.

![The Restart option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/restart-option.jpg)

## 4\. Reset the Microsoft Store Cache

 The Microsoft Store has a cache containing temporary, thumbnail, and log file data. A clogged-up cache with corrupted data can cause many MS Store issues. So, some users might need to reset (clear) that cache to fix the “server stumbled” error.

 You can clear that cache by entering the**WSreset.exe** command as outlined in method two within our guide on[how to reset the Microsoft Store](https://www.makeuseof.com/windows-10-11-reset-microsoft-store/) .

![The wsreset command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/wsreset-command.jpg)

## 5\. Turn Off Any Active Proxy Server Settings

 Some users use a proxy server to mask their IP address, but doing sooften causes Microsoft Store connection errors. If you’ve got an intermediary proxy server enabled on your PC, disable it via Settings or the Control Panel.

 Our guide on[how to disable the proxy server settings on Windows](https://www.makeuseof.com/windows-11-disable-proxy/) provides step-by-step instructions for both methods.

![The Use a proxy server for your LAN checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/use-a-proxy-server-option.jpg)

## 6\. Set Up a Connection to Google's DNS Servers

 The “server stumbled” error message highlights that the error could be linked to your PC’s DNS (Domain Name System) server. So, changing to a more reliable public server like Google DNS is a potential resolution that could feasibly work for some users.

 It is indeed the case some users have confirmed setting a Google DNS fixed this error on their PCs. To do that, check out our article about[how to change a DNS server](https://www.makeuseof.com/windows-11-alternate-ways-change-dns-server-settings/) , which also includes Google’s IPv4 addresses.

![DNS settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/dns-settings.jpg)

## 7\. Disable Any Active Third-Party Security Software

 Third-party security software packages that incorporate antivirus shields and firewalls can interfere with MS Store’s network connection. The firewall components of security apps will more likely do so since they monitor inbound and outbound network traffic. So, try temporarily disabling a firewall within any third-party security installed on your PC before opening MS Store.

 However, don’t rule out the possibility that an antivirus component of an installed third-party security app could also be causing the “server stumbled” error. You can usually disable an antivirus shield by right-clicking the security software’s system tray icon and selecting a turnoff option.

 Should this troubleshooting method work, you don’t necessarily need to leave your security software disabled or uninstall it. Instead, add MS Store to the firewall’s allowed app list within your antivirus software. In addition, add that app to the antivirus component’s whitelist.

## 8\. Enable TLS

 If you’re seeing a “server stumbled” error with 80072EFD or 80072EFF codes, you might need to enable some TLS (Transport Layer Security) protocol settings to resolve the issue. Enable TLS with the following steps:

1. Activate Run by pressing**Win + R** .
2. Type**inetcpl.cpl** (for Internet Options) inside Run and select OK.
3. Click**Advanced** to view that tab’s options.
4. Select the Use**TLS 1.0** ,**1.1** ,**1.2** , and**1.3** checkboxes there.  
![The TLS checkboxes](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/tls-settings.jpg)
5. Press**Apply** in the Internet Properties window.
6. Click**OK** to exit Internet Properties.

## 9\. Reregister the Microsoft Store

 Reregistering Microsoft Store will reset that app to its factory defaults. That’s a troubleshooting method worth trying if nothing else resolves the “server stumbled” error. You can apply this potential fix by executing a PowerShell command that generally reregisters pre-installed Windows apps.

 Our article about[reregistering Microsoft Store apps on Windows](https://www.makeuseof.com/reregister-microsoft-store-apps-windows/) includes step-by-step instructions for executing that command.

![The reregister command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/reregister-command.jpg)

## Download and Install Apps From the Microsoft Store Again

 Many users have stopped the “server stumbled” error crashing MS Store by applying the potential fixes outlined above. So, there’s a strong likelihood that one of those resolutions will get that issue sorted on your Windows 11/10 PC. Then you can get back to downloading and installing apps from Microsoft Store.

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
<li><a href="https://win11.techidaily.com/resurrecting-the-core-of-windows-11s-problem-solving-tools/"><u>Resurrecting the Core of Windows 11'S Problem-Solving Tools</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-wasteful-usage-by-core-system-processes/"><u>Reducing Wasteful Usage by Core System Processes</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-your-way-through-windows-application-hiccups-7-tips/"><u>Troubleshoot Your Way Through Windows Application Hiccups (7 Tips)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-and-set-up-windows-sandbox-in-windows-11/"><u>How to Enable and Set Up Windows Sandbox in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-playback-issues-with-windows-errors/"><u>Overcoming Playback Issues with Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-winuac-new-techniques-for-administrators/"><u>Enhancing WinUAC: New Techniques for Administrators</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-mandatory-components-not-available-in-win10win11/"><u>Sidestep Mandatory Components Not Available in WIN10/WIN11</u></a></li>
<li><a href="https://win11.techidaily.com/deactivating-mouse-speed-sensitivity-in-windows-1011/"><u>Deactivating Mouse Speed Sensitivity in Windows 10/11</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-premier-selections-versatile-and-affordable-macpc-bd-decoders/"><u>[New] Premier Selections  Versatile and Affordable Mac/PC BD Decoders</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-gamers-edition-obs-studio-streaming/"><u>[New] 2024 Approved  Gamers' Edition  OBS Studio Streaming</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-a-beginners-guide-to-selecting-premium-mac-mp3-label-editors/"><u>Updated A Beginners Guide to Selecting Premium Mac MP3 Label Editors</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-a-compreayers-primer-to-navigating-the-online-copyright-labyrinth/"><u>[Updated] A Compreayer's Primer to Navigating the Online Copyright Labyrinth</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-in-2024-facebook-live-shopping-a-comprehensive-guide/"><u>Updated In 2024, Facebook Live Shopping A Comprehensive Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-behind-the-scenes-10-underrated-aspects-of-reels-on-instagram/"><u>[Updated] Behind the Scenes  10 Underrated Aspects of Reels on Instagram</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-how-to-bypass-htc-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass HTC FRP Android 10/11/12/13</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-crafting-the-impeccable-circle-and-sphere-forms-in-mc-world/"><u>[New] 2024 Approved  Crafting the Impeccable Circle & Sphere Forms in MC World</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mobile-mastery-establishing-your-brands-youtube-outlet-for-2024/"><u>Mobile Mastery  Establishing Your Brand's YouTube Outlet for 2024</u></a></li>
</ul></div>
