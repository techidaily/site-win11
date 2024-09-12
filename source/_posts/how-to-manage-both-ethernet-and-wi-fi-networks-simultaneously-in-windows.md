---
title: How to Manage Both Ethernet & Wi-Fi Networks Simultaneously in Windows
date: 2024-09-11T09:40:00.422Z
updated: 2024-09-12T09:40:00.422Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Manage Both Ethernet & Wi-Fi Networks Simultaneously in Windows
excerpt: This Article Describes How to Manage Both Ethernet & Wi-Fi Networks Simultaneously in Windows
keywords: Windows Wi-Fi Management,Ethernet+Wi-Fi Control,Combine Wi-Fi, Ethernet,Manage Both Networks Windows,Simultaneous Ethernet/Wi-Fi,Integrated Ethernet/Wi-Fi Hub,Windows Network Handling
thumbnail: https://thmb.techidaily.com/4892cc1fafe3d31e97b196d4517b9323f9c488cf1481955b4a1bd1f77d8839e7.jpg
---

## How to Manage Both Ethernet & Wi-Fi Networks Simultaneously in Windows

 You can have your Windows computer connected to Wi-Fi and Ethernet simultaneously, but the system won't use both connections at the same. Windows automatically configures the network adapter order priority to provide the best Internet connection via Ethernet or Wi-Fi.

 However, if you have multiple ISP connections or have a local media server, you can configure your Windows laptop to use Wi-Fi and Ethernet simultaneously. To do this, you must disable packet priority for both Wi-Fi and Ethernet network adapter.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129739/7443" target="_top" id="2129739">
  <img src="//a.impactradius-go.com/display-ad/7443-2129739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139119/17108" target="_top" id="2139119">
  <img src="//a.impactradius-go.com/display-ad/17108-2139119" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139119/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Right-click on your**Ethernet network adapter** and select**Properties** . Alternatively, double-click on the**Ethernet adapter** and then click on**Properties** .  
![ethernet properties configure networking control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/ethernet-properties-configure-networking-control-panel.jpg)

<!-- affiliate ads begin -->
<span id="1982596">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982596.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982596">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982596.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982596%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982596/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Next, uncheck**Automatic metric** and type**5** in the**Interface metric** field.
7. Click**OK** on all the open windows to save the changes.
8. Note that if you use Internet Protocol Version 6 (IPv6) protocol, you’ll need to assign an interface metric for it as well.

 With the changes saved, Windows will prioritize your preference when multiple network adapters are connected to your computer. To undo the changes, open**Advanced TCP/IP Settings** and check the**Automatic** **metric** option. Then, click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136623/26400" target="_top" id="2136623">
  <img src="//a.impactradius-go.com/display-ad/26400-2136623" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136623/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/new-budget-friendly-twit-to-gif-guide/"><u>[New] Budget-Friendly Twit-to-GIF Guide</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-recommendation-best-iphone-ringtone-makers/"><u>[New] In 2024, Recommendation Best iPhone Ringtone Makers</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-quality-monitors-showdown-best-4k-edition-ranked-1-10/"><u>[New] Quality Monitors Showdown Best 4K Edition, Ranked #1-10</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-windows-11-strategies-to-secure-lasting-gaming-memories-for-2024/"><u>[New] Windows 11 Strategies to Secure Lasting Gaming Memories for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-editorelite-analysis-complete-insight/"><u>[Updated] 2024 Approved EditorElite Analysis – Complete Insight</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-finest-list-of-cost-effective-video-conferencing-apps/"><u>[Updated] Finest List of Cost-Effective Video Conferencing Apps</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-fostering-connection-strategies-for-striking-fb-slideshows/"><u>2024 Approved Fostering Connection Strategies for Striking FB Slideshows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-video-expertise-elevated-streamline-your-edits-with-these-vimeo-shortening-techniques/"><u>2024 Approved Video Expertise Elevated Streamline Your Edits with These Vimeo Shortening Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-copilot-key-in-windows-11-enhance-your-experience/"><u>Decoding Copilot Key in Windows 11 - Enhance Your Experience</u></a></li>
<li><a href="https://win11.techidaily.com/enable-missing-sd-card-view-on-file-explorer-platform/"><u>Enable Missing SD Card View on File Explorer Platform</u></a></li>
<li><a href="https://win11.techidaily.com/ftdibussys-in-depth-investigating-windows-memory-integrity-breach/"><u>Ftdibus.sys in Depth: Investigating Windows Memory Integrity Breach</u></a></li>
<li><a href="https://games-able.techidaily.com/get-hooked-on-these-6-non-monetary-gaming-treasures/"><u>Get Hooked on These 6 Non-Monetary Gaming Treasures</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-music-from-infinix-smart-7-hd-by-fonelab-android-recover-music/"><u>How to retrieve erased music from Infinix Smart 7 HD</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-realme-c55-to-iphone-xs11-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Realme C55 to iPhone XS/11 | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-gradual-sound-escalation-auditions-guide-to-fades/"><u>In 2024, The Gradual Sound Escalation Audition’s Guide to Fades</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-motorola-moto-g73-5g-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Motorola Moto G73 5G</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-vivo-v30-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Vivo V30 Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win11.techidaily.com/kickstart-windows-11-help-and-support-mechanism/"><u>Kickstart Windows 11 Help & Support Mechanism</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-windows-server-with-iis-manager/"><u>Master Your Windows Server with IIS Manager</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-explorer-top-errors-and-how-to-evade-them/"><u>Mastering File Explorer: Top Errors & How to Evade Them</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-game-potential-with-these-pro-gamers-top-tips-for-win-11/"><u>Maximize Game Potential with These Pro-Gamers' Top Tips for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-11-common-steam-freeze-during-gaming/"><u>Overcoming Windows 11: Common Steam Freeze During Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-exe-opener-dilemmrances/"><u>Overcoming Windows Exe Opener Dilemmrances</u></a></li>
<li><a href="https://win11.techidaily.com/overriding-windows-update-requests/"><u>Overriding Windows Update Requests</u></a></li>
<li><a href="https://win11.techidaily.com/precision-tactics-for-perfect-window-updates/"><u>Precision Tactics for Perfect Window Updates</u></a></li>
<li><a href="https://win11.techidaily.com/purple-pandemonium-a-guide-to-regaining-your-pcs-true-colors/"><u>Purple Pandemonium? A Guide to Regaining Your PC's True Colors</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-virtualbox-error-code-0x80004005-in-windows/"><u>Remedying Virtualbox Error Code: 0X80004005 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-up-your-game-with-expert-multitasking-techniques-for-windows-11/"><u>Step Up Your Game with Expert Multitasking Techniques for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-fix-geforce-nows-error-code-0xc0f1103f-in-windows/"><u>Steps to Fix GeForce Now's Error Code 0Xc0f1103f in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-error-e8024002e/"><u>Steps to Overcome Windows Error E:8024002E</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-no-write-windows-saving-hurdles/"><u>Strategies for Overcoming No Write Windows Saving Hurdles</u></a></li>
<li><a href="https://win11.techidaily.com/swift-and-smooth-keyboard-shortcuts-for-3d-artists/"><u>Swift and Smooth: Keyboard Shortcuts for 3D Artists</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-technique-to-design-personalized-lock-patterns-on-windows-11/"><u>The Complete Technique to Design Personalized Lock Patterns on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-top-7-picks-of-drawing-apps-for-windows-11-enthusiasts/"><u>The Top 7 Picks of Drawing Apps for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-hub-ultimate-guide-to-the-latest-in-computer-hardware/"><u>Tom's Tech Hub: Ultimate Guide to the Latest in Computer Hardware</u></a></li>
<li><a href="https://win11.techidaily.com/tracing-your-digital-steps-in-windows-11/"><u>Tracing Your Digital Steps in Windows 11</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/unclogging-saturation-issue-gpt-in-windows/"><u>Unclogging Saturation Issue: GPT in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-blue-screen-mysteries-where-are-the-logs/"><u>Unlocking Blue Screen Mysteries: Where Are the Logs?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/why-is-ipogo-not-working-on-nubia-red-magic-9-proplus-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Nubia Red Magic 9 Pro+? Fixed | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win-pc-download-speedups-navigate-the-net-faster/"><u>Win-PC Download Speedups: Navigate the Net Faster</u></a></li>
<li><a href="https://win11.techidaily.com/winning-torrent-clients-the-best-of-windows-list/"><u>Winning Torrent Clients: The Best of Windows List</u></a></li>
</ul></div>

