---
title: Simultaneous Wi-Fi & Ethernet Use Guide for Windows PCs
date: 2024-09-28T00:26:09.561Z
updated: 2024-10-03T21:21:00.434Z
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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657396/16446" target="_top" id="1657396">
  <img src="//a.impactradius-go.com/display-ad/16446-1657396" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657396/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. In the**Networking** tab, click the**Configure** button.
2. Next, open the**Advanced** tab.
3. Select**Priority and VLAN** under the**Property** section.
4. Click the drop-down under**Value** .  
![priority vlan disabled](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/priority-vlan-disabled.jpg)
5. Select**Priority and VLAN Disabled.**

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1576474/17382" target="_top" id="1576474">
  <img src="//a.impactradius-go.com/display-ad/17382-1576474" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1576474/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484939/16446" target="_top" id="1484939">
  <img src="//a.impactradius-go.com/display-ad/16446-1484939" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484939/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.
6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001453/11832" target="_top" id="1001453">
  <img src="//a.impactradius-go.com/display-ad/11832-1001453" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001453/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-posts.techidaily.com/new-cutting-edge-creativity-high-quality-ae-samples-without-fee-for-2024/"><u>[New] Cutting-Edge Creativity High-Quality AE Samples Without Fee for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-20-best-non-copyrighted-pubg-montage-thumbnail/"><u>2024 Approved 20 Best Non Copyrighted PUBG Montage Thumbnail</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-harnessing-background-video-to-enrich-primary-scenes/"><u>2024 Approved Harnessing Background Video to Enrich Primary Scenes</u></a></li>
<li><a href="https://techtrends.techidaily.com/2022pc/"><u>錄像片2022保存至PC：探究三大傳統技術</u></a></li>
<li><a href="https://games-able.techidaily.com/breaking-the-code-ps5s-internet-enigma/"><u>Breaking the Code: PS5's Internet Enigma</u></a></li>
<li><a href="https://win11.techidaily.com/comeback-king-windows-guide-essential-13-restoration-steps/"><u>Comeback King Windows Guide: Essential 13 Restoration Steps</u></a></li>
<li><a href="https://win11.techidaily.com/escape-key-troubles-discover-immediate-remedies-for-your-pc/"><u>Escape Key Troubles? Discover Immediate Remedies for Your PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/essential-factors-to-evaluate-when-purchasing-your-first-video-recording-gadget/"><u>Essential Factors to Evaluate When Purchasing Your First Video Recording Gadget</u></a></li>
<li><a href="https://techtrends.techidaily.com/explore-the-world-of-superman-a-comprehensive-ordered-list-for-a-perfect-movie-marathon-experience/"><u>Explore the World of 'Superman': A Comprehensive Ordered List for a Perfect Movie Marathon Experience</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-error-code-0xc0000005-a-techs-approach/"><u>How to Overcome Error Code 0XC0000005: A Tech's Approach</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-fcpx-title-effects-unlocking-creative-possibilities/"><u>In 2024, FCPX Title Effects Unlocking Creative Possibilities</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/latest-guide-how-to-bypass-realme-c67-4g-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Realme C67 4G FRP Without Computer</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ms-store-themes-setup-and-utilization-guide/"><u>Mastering MS Store Themes: Setup & Utilization Guide</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reinstate-the-mia-dxgidll-in-windows-11/"><u>Steps to Reinstate the MIA Dxgi.dll in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-store-apps-in-windows-11/"><u>Troubleshooting Non-Functional Store Apps in Windows 11</u></a></li>
</ul></div>

