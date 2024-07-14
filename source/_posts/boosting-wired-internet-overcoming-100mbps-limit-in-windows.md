---
title: "Boosting Wired Internet: Overcoming 100Mbps Limit in Windows"
date: 2024-07-13T11:27:26.938Z
updated: 2024-07-14T11:27:26.938Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boosting Wired Internet: Overcoming 100Mbps Limit in Windows"
excerpt: "This Article Describes Boosting Wired Internet: Overcoming 100Mbps Limit in Windows"
keywords: Boost WiFi Speed,Max Out Windows,Eliminate Bandwidth Cap,Enhance PC Connectivity,Overcome Data Threshold,Increase Internet Limit,Break 100Mbps Barrier
thumbnail: https://thmb.techidaily.com/675815b145dcafd84fe359ee4ac52511e6c57ba8907f6c40cdafb2c11a8f5a83.jpg
---

## Boosting Wired Internet: Overcoming 100Mbps Limit in Windows

 Is the speed of your Ethernet connection stuck at 100Mbps? If so, several factors could be limiting it. You may only have a 100Mbps connection, and the speed technically cannot go higher; router settings could be limiting the bandwidth, or there could be an issue with the router, Ethernet cable, or cable connectors.

 Likewise, misconfigured Ethernet adapter speed settings, incompatible or corrupted drivers, and technical difficulties with the ISP can also limit speed. If you want your Ethernet connection to surpass 100Mbps, here are a few checks and fixes you should try.

## 1\. Check Your Internet Plan

![wifi speed test](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/wifi-speed-test.jpg)

 Make sure you have a high-speed connection capable of delivering speeds greater than 100Mbps before you blame other factors for limiting your internet speed. Check with your internet provider that you're subscribed to a plan that offers 100Mbps+ or more. Also, ensure the ISP has a good reputation and track record of consistently delivering high speeds.

 If your internet service provider is reliable and you are subscribed to a good plan, then it's likely that something on your side is keeping the speed from reaching its maximum.

## 2\. Perform Some Basic Checks

 Start troubleshooting the problem by performing these basic fixes, as they may resolve the issue right away:

* [Reboot your router](https://www.makeuseof.com/reboot-router-correct-way/) once to rule out temporary issues.
* Ensure the Ethernet cable isn't loosely connected to your device. Disconnect both ends of the cable and reconnect them.
* Run the built-in network troubleshooter to identify and resolve any network problems. If you're not familiar with the process, check out our guide on [how to run a troubleshooter](https://www.makeuseof.com/run-troubleshooter-windows-10-11/).
* An outdated network driver can also slow down a connection. Check out our guide on [how to find and replace outdated network drivers](https://www.makeuseof.com/tag/find-replace-outdated-windows-drivers/) to update your network drivers fully.

 If none of the above checks uncaps the internet speed, it's time to move on to the remaining fixes

## 3\. Ensure Your Network Card Supports Gigabit Speed

 The Ethernet Card, also known as the Network Interface Card, connects your computer to the internet via an Ethernet cable. If you have an old computer, the adapter installed may not be capable of delivering over 100Mbps. Therefore, ensuring that your card supports the gigabit connection is imperative.

 To check this, look at the name of the adapter. If it contains keywords such as gigabit, gbe, 10/100/1000M gigabit, you probably have a gigabit connection. In contrast, if you see Fast Ethernet, 10/100FE, your connection is 100Mbps. Alternatively, you can check if your network adapter supports gigabit speeds in Device Manager. Here's how:

1. Right-click the **Start** button and select **Device Manager**.
2. Expand the **Network adapters** category.
3. Right-click the network connection adapter and select **Properties**.
4. Then, go to the **Advanced** tab.
5. Select **Speed and Duplex** from the **Property** column, then expand the **Value** dropdown.  
![Speed and Duplex Settings in the Network Adapter Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/speed-and-duplex-settings-in-the-network-adapter-settings.jpg)

 If **1.0 Gbps Full Duplex** is listed, your card supports gigabit connectivity. Your card does not support gigabit connections if **100 Mbps Full Duplex** is the highest value listed. In any case, select **Auto Negotiation** from the **Value** dropdown in the network adapter settings if any other value is selected.

## 4\. Ensure Your Router Supports Gigabit Connection

![a close up shot of router ports](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/modern-wifi-router-ports.jpg)

 Like your network card, your router should also be capable of delivering 100Mbps+ speeds. You can check that by looking at the router's documentation or description on the manufacturer's website. If the router manufacturer claims this specific model is a gigabit router, it can likely deliver gigabit speeds.

 If you have a gigabit router, make sure the port where your Ethernet cable is connected is also a gigabit LAN port that can handle up to 1Gbps data rates. Switch to a gigabit port if it's connected to a "Fast Ethernet" port, which can only deliver 100Mbps. Hopefully, this will increase your internet connection's speed.

 If your router doesn't support a gigabit connection, you will have no choice but to switch to one that does.

## 5\. Get a High-Category Ethernet Cable

![CAT5, CAT5e, CAT6, CAT6A Ethernet cables](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/02-picture-showing-cat5-cat5e-cat6-cat6a-ethernet-cables.jpg)

 The Ethernet cable itself should be capable of delivering 100Mbps+ speed, just like your router. Ethernet cables with low bandwidth, such as Cat5, can only deliver speeds up to 100Mbps. If you want higher speeds, you need at least Cat5e cable, which can provide speeds of up to 1000Mbps.

 Cat5e and Cat5 cables have identical physical appearances, but don't let that fool you. Instead, look at the cable's label to determine its category. If it's low bandwidth, replace it with Cat5e or higher.

## 6\. Remove Restrictions in the Router Settings

 Most routers allow users to limit the connection speed. Therefore, log into the router's admin interface to ensure speed isn't constrained there. Here's how you can do it:

1. Open the **Command Prompt** and type **"ipconfig."** Then, hit **Enter**.
2. Copy the **IP address** next to **Default Gateway**—that's your router's IP address.  
![Check the Default Gateway IP Address in Windows Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/check-the-default-gateway-ip-address-in-windows-command-prompt.jpg)
3. Paste this address into any internet browser to access your router's admin interface. Then, log in with your username and password.
4. Go to the **Ethernet** settings and check if there are any restrictions on your internet speed. Remove any constraints you find here.

 Some routers allow users to switch between gigabit and 100Mbps speeds. If your router offers this option, opt for the 1Gbps connection.

## 7\. Rule Out Any Hardware Issues

 If none of the above fixes resolve the issue, it's time to check for and rule out hardware problems thoroughly.

![image of ethernet cables connected to router](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/ethernet-router-connection.jpg)

 Start the hardware inspection by checking both ends of the Ethernet cable where cable connectors are installed. Ensure both connectors are in good condition and all internal wires/conductors are pushed to the end and aren't falling off.

 Once you have confirmed that, inspect the Ethernet cable from one end and go through the entire length. If the cable shows any physical damage, especially areas that remain bent all the time, you may need to replace it.

 If the cable is intact, examine the Ethernet ports on your router and laptop. If any of the ports appears damaged, you should switch to another one (if available).

## Get the Most Out of Your Ethernet Connection on Windows

 Getting 100Mbps when subscribed to a higher-speed plan can be pretty frustrating. By now, you should better understand why the connection speed could be capped at 100Mbps. If you carefully follow all the steps listed above, you will likely be able to identify the leading cause and remove any restrictions.

 If your internet speed remains capped at 100Mbps despite applying all the fixes above, you should contact your internet service provider.

 Likewise, misconfigured Ethernet adapter speed settings, incompatible or corrupted drivers, and technical difficulties with the ISP can also limit speed. If you want your Ethernet connection to surpass 100Mbps, here are a few checks and fixes you should try.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-clips.techidaily.com/why-watch-hd-switch-to-av1-codec-on-youtube/"><u>Why Watch HD? - Switch to AV1 Codec on YouTube</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/recording-skype-meetings-on-modern-operating-systems/"><u>Recording Skype Meetings on Modern Operating Systems</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-unveiling-the-art-of-converting-still-images-into-engaging-videos-with-pixiz/"><u>[Updated] In 2024, Unveiling the Art of Converting Still Images Into Engaging Videos with Pixiz</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unplugging-confirmation-failures-in-win/"><u>Addressing Unplugging Confirmation Failures in WIN</u></a></li>
<li><a href="https://win11.techidaily.com/boost-brainpower-proven-techniques-to-master-studying-on-windows/"><u>Boost Brainpower: Proven Techniques to Master Studying on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-app-aesthetics-with-win11s-automatic-tuning/"><u>Boosting App Aesthetics with Win11's Automatic Tuning</u></a></li>
<li><a href="https://win11.techidaily.com/best-windows-video-codecs-choices-and-justifications/"><u>Best Windows Video Codecs: Choices & Justifications</u></a></li>
<li><a href="https://win11.techidaily.com/arrow-troubles-15-windows-fixes-to-consider/"><u>Arrow Troubles? 15 Windows Fixes to Consider</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-in-win-11-with-top-7-essential-widgets/"><u>Boost Productivity in Win 11 with Top 7 Essential Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/balancing-the-thermal-load-of-windows-11-devices/"><u>Balancing the Thermal Load of Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overheat-proper-maintenance-during-gaming-sessions/"><u>Avoiding Overheat: Proper Maintenance During Gaming Sessions</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-code-breakdowns-quick-windows-fixes/"><u>Breaking Free From Code Breakdowns: Quick Windows Fixes</u></a></li>
<li><a href="https://facebook.techidaily.com/digital-democracy-decisions-valid-banning-of-trump-short-term-strategy/"><u>Digital Democracy Decisions: Valid Banning of Trump, Short-Term Strategy</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-refined-connections-zoom-insight-for-professional-google-meets/"><u>In 2024, Refined Connections  Zoom Insight for Professional Google Meets</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-energy-drain-auto-shutdown-at-idle-in-win11/"><u>Avoiding Energy Drain: Auto-Shutdown at Idle in Win11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-video-sectioning-mastery-in-vimeo-videos/"><u>[Updated] 2024 Approved  Video Sectioning Mastery in Vimeo Videos</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-disruptions-to-wsl-after-installing-windows-11/"><u>Avoiding Disruptions to WSL After Installing Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-infographics-spotlight-on-future-social-trends/"><u>In 2024, Infographics Spotlight on Future Social Trends</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/twitter-to-whatsapp-sharing-videos-simplified/"><u>Twitter to WhatsApp  Sharing Videos Simplified</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-behind-the-scenes-how-apples-m1-max-attachments-work/"><u>[Updated] Behind-the-Scenes  How Apple’s M1 Max Attachments Work</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-microsoft-store-crashes-solving-0x80072f30-error/"><u>Avoiding Microsoft Store Crashes: Solving 0X80072F30 Error</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/win10s-favorite-video-grabber-tools/"><u>Win10's Favorite Video Grabber Tools</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-navigating-the-social-sea-identifying-unfollowers-on-instagram/"><u>[Updated] Navigating the Social Sea  Identifying Unfollowers on Instagram</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-premium-fonts-with-dynamic-movement/"><u>2024 Approved  Premium Fonts with Dynamic Movement</u></a></li>
<li><a href="https://win11.techidaily.com/bolster-window-app-interactions-via-efficient-internet-accessing-methods/"><u>Bolster Window App Interactions via Efficient Internet Accessing Methods</u></a></li>
<li><a href="https://win11.techidaily.com/ameliorating-non-working-cut-and-paste-in-win-11/"><u>Ameliorating Non-Working Cut and Paste in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/baffling-taskers-display-with-edge-and-others/"><u>Baffling Tasker's Display with Edge & Others</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-unauthorized-user-error-on-windows-11-and-11/"><u>Avoiding Unauthorized User Error on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-the-deadly-javascript-error-from-discord-on-win-11/"><u>Banishing the Deadly JavaScript Error From Discord on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-breach-are-windows-fingerprint-scanners-safe/"><u>Biometric Breach: Are Windows Fingerprint Scanners Safe?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-more-video-glitches-on-upgraded-windows-10/"><u>No More Video Glitches on Upgraded Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-visual-quality-enable-win11s-color-adjustment/"><u>Boosting Visual Quality: Enable Win11's Color Adjustment</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-windows-unlicensed-adobe-errors/"><u>Avoid Windows 'Unlicensed' Adobe Errors</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-rhythm-reduction-techniques-efficiently-extracting-percussion-from-songs-digitally/"><u>New 2024 Approved Rhythm Reduction Techniques Efficiently Extracting Percussion From Songs Digitally</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-top-5-online-film-editors/"><u>[New] 2024 Approved  Top 5 Online Film Editors</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-budget-conscious-obs-tweaks-and-tricks/"><u>In 2024, Budget-Conscious OBS Tweaks and Tricks</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-transforming-your-spotify-list-into-a-youtube-music-collection/"><u>[Updated] Transforming Your Spotify List Into a YouTube Music Collection</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-mastering-the-search-function-of-windows-11/"><u>Boost Productivity: Mastering the Search Function of Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-samsung-galaxy-m54-5g-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Samsung Galaxy M54 5G to Samsung Phone | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>