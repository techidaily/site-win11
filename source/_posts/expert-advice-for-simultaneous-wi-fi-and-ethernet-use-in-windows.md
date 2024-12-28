---
title: Expert Advice for Simultaneous Wi-Fi & Ethernet Use in Windows
date: 2024-12-25T21:39:32.228Z
updated: 2024-12-27T16:00:53.716Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Q8Feep0Rc0?si=YkPhRxXGvrRRMJtb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click**OK** to save the changes.
7. Next, you need to repeat the steps for your Wi-Fi adapter. So, open Properties for your Wi-Fi adapter and set its**Priority and VLAN** value to**Priority & VLAN Disabled** .
8. Click**OK** to save the changes.

 With the network adapter priority option disabled, Windows will now use both network connections simultaneously.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Set the Network Priority for Wi-Fi or Ethernet Using Interface Metric

 By default, Windows uses an automatic metric to detect and use the best network connectivity option available. However, if you need, you can manually set network priority to force Windows to use Ethernet or Wi-Fi as the preferred connectivity option.

To change network priority on Windows:

1. Press**Win + R** to open**Run** .
2. Type**ncpa.cpl** and click**OK** .  
![ncpa cpl open control panel network and sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ncpa-cpl.jpg)
3. Right-click on your Ethernet adapter and select**Properties** . If you want to prioritize your Wi-Fi adapter, choose that instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Next, select**Internet Protocol Version 4 (TCP/IPv4)** and click on**Properties** .  
![tcp ip v4 properties control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tcp-ip-v4-properties-control-panel.jpg)
5. Click the**Advanced** button in the**Properties** dialog.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

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
<li><a href="https://facebook-video-footage.techidaily.com/new-basics-of-online-videos-the-easiest-10-ideas-for-beginners-on-youtube-for-2024/"><u>[New] Basics of Online Videos The Easiest 10 Ideas for Beginners on YouTube for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-essential-steps-picking-your-ideal-4k-lens/"><u>[New] Essential Steps Picking Your Ideal 4K Lens</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-smart-video-alteration-for-mac-users-seeking-insta-perfect-posts/"><u>[Updated] 2024 Approved Smart Video Alteration for Mac Users Seeking Insta-Perfect Posts</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-parrots-at-play-unpacking-bebops-next-gen-flight/"><u>2024 Approved Parrots at Play Unpacking Bebop’s Next-Gen Flight</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-zoom-mastery-for-selfie-success-in-instagram-stories/"><u>2024 Approved Zoom Mastery for Selfie Success in Instagram Stories</u></a></li>
<li><a href="https://win11.techidaily.com/command-line-a-step-by-step-guide-to-win-registry-alteration/"><u>Command Line: A Step-by-Step Guide to Win Registry Alteration</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-drives-type-recognition-for-your-pc/"><u>Decoding Drives: Type Recognition for Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/designing-your-own-terminal-schemes-in-wt/"><u>Designing Your Own Terminal Schemes in WT</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/epson-gt-s50-printer-software-for-windows-users-version-compatible-with-windows-7-8-and-10/"><u>Epson GT-S50 Printer Software for Windows Users: Version Compatible with Windows 7, 8 & 10</u></a></li>
<li><a href="https://win11.techidaily.com/five-effective-strategies-for-firewall-management/"><u>Five Effective Strategies for Firewall Management</u></a></li>
<li><a href="https://win-studio.techidaily.com/guide-complet-comment-transferer-simplement-des-fichiers-et-un-systeme-dexploitation-entre-deux-ssd/"><u>Guide Complet: Comment Transférer Simplement Des Fichiers Et Un Système D’Exploitation Entre Deux SSD</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-through-error-code-31-restoring-your-internet-connection/"><u>Navigate Through Error Code 31: Restoring Your Internet Connection</u></a></li>
<li><a href="https://win11.techidaily.com/re-establishing-windows-11-taskbar-connectivity/"><u>Re-Establishing Windows 11 Taskbar Connectivity</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/skys-best-the-ultimate-hd-collection-websites-for-2024/"><u>Sky's Best - The Ultimate HD Collection Websites for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-securing-your-settings-against-unintentional-loss-by-cp/"><u>Strategies for Securing Your Settings Against Unintentional Loss by CP</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-workflows-incorporating-additional-folders-in-windows/"><u>Streamlining Workflows: Incorporating Additional Folders in Windows</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/top-prime-day-electronics-bargains-exclusive-october-2024-shopping-guide-on-zdnet/"><u>Top Prime Day Electronics Bargains: Exclusive October 2024 Shopping Guide on ZDNet</u></a></li>
<li><a href="https://article-posts.techidaily.com/transforming-traditional-markets-with-virtual-engineering-for-2024/"><u>Transforming Traditional Markets with Virtual Engineering for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-personalized-clock-settings-bypass-automatic-windows-change/"><u>Unlock Personalized Clock Settings, Bypass Automatic Windows Change</u></a></li>
</ul></div>

