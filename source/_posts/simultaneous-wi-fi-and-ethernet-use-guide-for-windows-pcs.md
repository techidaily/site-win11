---
title: Simultaneous Wi-Fi & Ethernet Use Guide for Windows PCs
date: 2024-09-17T22:36:13.863Z
updated: 2024-09-22T00:23:54.444Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Simultaneous Wi-Fi & Ethernet Use Guide for Windows PCs
excerpt: This Article Describes Simultaneous Wi-Fi & Ethernet Use Guide for Windows PCs
keywords: Wi-Fi/Ethernet Windows Guide,Simultaneous Networking in Windows,Windows PCs Network Management,Integrated Wi-Fi Ethernet Usage,Cross-Platform Connectivity Guide,Multi-Network Windows Setup,Seamless Wireless/Ethernet Connection
thumbnail: https://thmb.techidaily.com/42d888d9431637ab1388aeb276d6888b24b9d1d85a816656ff3b301d8b067e97.jpg
---

## Simultaneous Wi-Fi & Ethernet Use Guide for Windows PCs

 You can have your Windows computer connected to Wi-Fi and Ethernet simultaneously, but the system won't use both connections at the same. Windows automatically configures the network adapter order priority to provide the best Internet connection via Ethernet or Wi-Fi.

 However, if you have multiple ISP connections or have a local media server, you can configure your Windows laptop to use Wi-Fi and Ethernet simultaneously. To do this, you must disable packet priority for both Wi-Fi and Ethernet network adapter.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.
4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.
6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106655/12108" target="_top" id="2106655">
  <img src="//a.impactradius-go.com/display-ad/12108-2106655" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106655/12108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-the-rotation-rush-guide-mastering-instagrams-art-of-turned-around-content/"><u>[New] 2024 Approved The Rotation Rush Guide Mastering Instagram's Art of Turned-Around Content</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-in-2024-photographys-new-frontier-illustration-and-motion-blurring-techniques/"><u>[New] In 2024, Photography's New Frontier Illustration and Motion Blurring Techniques</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-pathway-to-seamless-integration-of-voice-inputs-in-powerpoint-presentations/"><u>[New] The Pathway to Seamless Integration of Voice Inputs in PowerPoint Presentations</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-most-effective-ways-to-log-youtube-live-events-for-2024/"><u>[Updated] Most Effective Ways to Log YouTube Live Events for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/expert-guide-to-dismantling-breakpoint-exception-in-windows/"><u>Expert Guide to Dismantling Breakpoint Exception in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-issues-with-googles-nearby-sharing-on-windows/"><u>Fixing Issues with Google's Nearby Sharing on Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-realme-c53-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Realme C53 to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-stop-google-chrome-from-tracking-your-location-on-samsung-galaxy-a24-drfone-by-drfone-virtual-android/"><u>In 2024, How to Stop Google Chrome from Tracking Your Location On Samsung Galaxy A24? | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-live-streaming-showdown-streamlabs-vs-obs-face-off/"><u>In 2024, Live Streaming Showdown Streamlabs Vs. OBS Face-Off</u></a></li>
<li><a href="https://win11.techidaily.com/perpetual-disposal-setting-up-unchangeable-deletion-bin-on-pc/"><u>Perpetual Disposal: Setting up Unchangeable Deletion Bin on PC</u></a></li>
<li><a href="https://win11.techidaily.com/retouching-lost-plans-win-11-power-settings-guide/"><u>Retouching Lost Plans: Win 11 Power Settings Guide</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-prevent-file-explorer-crashes-on-windows-11/"><u>Tips to Prevent File Explorer Crashes on Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ultimate-fix-how-to-overcome-power-issues-with-your-ps5-controller/"><u>Ultimate Fix: How to Overcome Power Issues with Your PS5 Controller</u></a></li>
<li><a href="https://win11.techidaily.com/unresponsive-click-problems-guide-for-win11-users/"><u>Unresponsive Click Problems: Guide for Win11 Users</u></a></li>
</ul></div>

