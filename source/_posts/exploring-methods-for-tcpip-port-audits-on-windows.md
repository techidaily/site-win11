---
title: Exploring Methods for TCP/IP Port Audits on Windows
date: 2024-08-15T23:52:21.041Z
updated: 2024-08-16T23:52:21.041Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Exploring Methods for TCP/IP Port Audits on Windows
excerpt: This Article Describes Exploring Methods for TCP/IP Port Audits on Windows
keywords: WinTCPPortAudit,IPCheckWindows,NetworkSecurityScan,AuditTCPPortsWin,WindowsNetAudit,PortScannerOS,TCPAnalysisWindows
thumbnail: https://thmb.techidaily.com/8383b1955265d208bd65863f99fa93e0506dbf01fc1cf31d37490fb679a3c33d.png
---

## Exploring Methods for TCP/IP Port Audits on Windows

 Sometimes it's worth finding out which TCP/IP ports are open on your device. For example, let’s say your device is communicating with another PC, but the connection suddenly gets interrupted. In this case, you can check all the open TCP/IP ports. From there, you could try to resolve the issue at hand by troubleshooting any faulty port.

 This article covers the various ways to check active TCP/IP ports on Windows. But first, let’s find out how these ports work.

## What Are TCP/IP Ports, and How Do They Work?

![An illustration of questions and answers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/An-illustration-of-questions-and-answers.jpg)

 Let’s break down the “TCP/IP” term and explain what it means.

 TCP (Transmission Control Protocol) refers to a connection-oriented protocol. And in simple terms, protocols are the rules that determine how data is transferred between devices.

 Meanwhile, the "IP" (Internet Protocol) part refers to the internet protocol address. This is a unique value assigned to a network device, and it’s used to identify that particular device.

 Now, TCP/IP ports are simply the ports that ensure that all the data you send reaches its recipient. These ports ensure that internet-connected devices can communicate with each other. Some examples of TCP/IP ports include the IMAP port (143) for emails and the File Transfer Protocol ports (20 and 21).

 Let's now explore the various ways to check active TCP/IP ports.

## 1\. Check the Open TCP/IP Ports and Their Process Names Using the Command Prompt

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 When checking the TCP/IP ports that are open, you might also want to discover some additional information.

 For example, let’s say you want to check out active TCP/IP ports along with their process names. In such an instance, you can apply these methods:

1. Press **Win + R** to open the Run command dialog box.
2. Type **CMD** and press **Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Type the following command and press **Enter**.

netstat -ab

 The results will display four columns: **Proto, Local Address, Foreign Address,** and **State**.

![Checking the TCP-IP ports that are open](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-the-tcp-ip-ports-that-are-open.jpg)

 The process names are the values displayed in square brackets below the port names.

 For example, you might see the “\[svchost.exe\]” process name under one of the TCP ports.

## 2\. Check the Open TCP/IP Ports and the Process Identifiers Using the Command Prompt

![Person using a Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/10/Person-using-a-Windows-PC.jpg)
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In some instances, you might want to check out the TCP/IP ports along with their Process Identifiers (the unique numbers that identify processes). This method could be useful if you can’t find the process names using the previous method.

 When you’re done [searching for the Process Identifier (PID) on Windows](https://www.makeuseof.com/ways-to-find-application-process-id-in-windows-10/), you can check out the task name linked to the PID in the Task Manager.

 Let’s start by checking out how to check the open TCP/IP ports and their PIDs:

1. Press **Win + R** to open the Run command dialog box.
2. Type **CMD** and press **Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Type the following command and press **Enter**.

netstat -aon

 Your screen should display five columns: **Proto, Local Address, Foreign Address, State,** and **PID**.

![Checking TCP-IP ports and process identifiers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-tcp-ip-ports-and-process-identifiers.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->

 Once you've found the PID of a certain port, here’s how you can use the Task Manager to find the task linked to that PID:

1. Type **Task Manager** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Details** tab.
3. Look for your PID value in the **PID section** and locate the task name from the results on the left.

![Checking the PID value and task name on the Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-the-pid-value-and-task-name-on-the-task-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->

## 3\. Check Which TCP/IP Ports Are Open Using Third-Party Apps

 If you’re a fan of third-party apps, here are some tools that can help you check active TCP/IP ports on your device.

### TCPView

![The TCPView Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-tcpview-tool.jpg)

 The TCPView app shows a detailed list of all the [TCP and UDP (User Datagram Protocol) ports](https://www.makeuseof.com/what-are-tcp-and-udp-ports/). It also shows you the Process Name, Process IDs (PIDs), the Local Address, the Remote Address, the Local Port, the Remote Port, and more.

 You can customize the TCPView screen by clicking the **View** tab and selecting the relevant option.

 If you’d like to change the window to dark mode, head to the **Options** tab, select **Theme**, and then pick the **Dark** option. You can also tweak other settings (such as changing the font size) on the Options tab.

 And if you’d like to close one of the processes on the screen, select the process in question, click the **Process** tab, and then select the **Kill…** option.

 If you want to edit a process, click on the process in question, click the **Edit** tab, and then select the relevant option. And if you need some assistance, head to the **Help** tab.

**Download**: TCPView for [Windows](https://learn.microsoft.com/en-us/sysinternals/downloads/tcpview) (Free)

### CurrPorts

![The CurrPorts Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-currports-tool.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->

 CurrPorts almost looks similar to TCPView, but it has a couple of additional tabs that display critical information. For example, this tool also shows you the Process Path (file path), the Product Name, the File Description, and the File Version (for apps).

 The tool displays all the open TCP/IP and UDP ports on your PC.

 If you want to close some ports, highlight them and then click the “close” icon. To filter your results, click the “filter” icon, select your filter, and then click **OK**.

 If you want to search for specific ports, click the “find” icon, type the name of the port, and then click **Find Next**.

 To edit your ports, navigate to the **Edit** tab and then select the relevant option.

 If you want to customize the CurrPorts tool, click the **View** tab and select the relevant option. And if you want to discover more customization features, head to the **Options** tab.

**Download**: CurrPorts for [Windows](https://www.nirsoft.net/utils/cports.html) (Free)

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
### TCP Monitor Plus

![The TCP Monitor Plus Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-tcp-monitor-plus-tool.jpg)

 TCP Monitor Plus comprises 11 tabs that you can use for various purposes. But in this case, we’ll focus on the Session Monitor tab because that’s where the TCP/IP information is located.

 Once you’re on the Session Monitor tab, you should see various sections containing information about the TCP/IP ports. The "Status" tab tells you whether the ports are open or connecting. The other tabs display information such as the IP address, hostname, process name, and more.

 If you want to make changes to a specific port, right-click on it and select a relevant option.

**Download**: TCP Monitor Plus for [Windows](https://www.softpedia.com/get/Network-Tools/Network-Monitoring/TCP-Monitor-Plus.shtml) (Free)

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Finding All Your Active TCP/IP Ports Shouldn't Be Difficult

 Are you communicating with a remote computer but suddenly run into connection issues? Maybe the problem comes from TCP/IP ports. In this case, you can simply check which TCP/IP ports are open using the tips we’ve covered. From there, you can apply the relevant troubleshooting steps to fix the faulty port.

 And if you run into other problems while connecting to a remote device, check out some common remote desktop connection issues and their fixes.


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
<li><a href="https://fox-direct.techidaily.com/new-from-raw-footage-to-stunning-visuals-using-luts-in-obs-studio-for-2024/"><u>[New] From Raw Footage to Stunning Visuals  Using LUTs in OBS Studio for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-best-fun-car-games-also-for-kids/"><u>[New] In 2024, Best Fun Car Games [Also for Kids ]</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-mastering-the-art-of-customizing-your-youtube-channel-url/"><u>[New] In 2024, Mastering the Art of Customizing Your YouTube Channel URL</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-game-away-your-worries-the-coolest-titles/"><u>[Updated] 2024 Approved  Game Away Your Worries  The Coolest Titles</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-tiktok-titans-who-inspire-you-today/"><u>[Updated] 2024 Approved  TikTok Titans Who Inspire You Today</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-future-filmmaking-favorites-2024s-best-cameras/"><u>[Updated] Future Filmmaking Favorites  2024'S Best Cameras</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-pro-tips-to-enhance-your-use-of-instagrams-query-symbol/"><u>2024 Approved  Pro Tips to Enhance Your Use of Instagram's Query Symbol</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-enable-or-disable-the-delete-confirmation-dialog-on-windows/"><u>3 Ways to Enable or Disable the Delete Confirmation Dialog on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/3-ways-to-make-windows-11-start-up-faster/"><u>3 Ways to Make Windows 11 Start Up Faster</u></a></li>
<li><a href="https://win11.techidaily.com/4-keys-to-reviving-a-device-stuck-in-night-setting/"><u>4 Keys to Reviving a Device Stuck in Night Setting</u></a></li>
<li><a href="https://win11.techidaily.com/4-ways-to-clear-the-tpm-on-windows-11/"><u>4 Ways to Clear the TPM on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/5-must-have-desktop-writing-assistants-windows/"><u>5 Must-Have Desktop Writing Assistants (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/a-beginners-guide-to-upgrading-virtualbox-v70-in-win11/"><u>A Beginner's Guide to Upgrading VirtualBox v7.0 in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-unveiling-affordable-windows-10-mastery/"><u>A Complete Unveiling: Affordable Windows 10 Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/a-comprehensible-guide-to-reviving-stuck-windows-itunes/"><u>A Comprehensible Guide to Reviving Stuck Windows iTunes</u></a></li>
<li><a href="https://win11.techidaily.com/a-twelve-days-of-windows-11-christmas-guide/"><u>A Twelve Days of Windows 11 Christmas Guide</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-sluggish-windows-based-excel-processes/"><u>Accelerate Sluggish Windows-Based Excel Processes</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-tasks-high-speed-windows-autoclickers/"><u>Accelerate Tasks: High-Speed Windows Autoclickers</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-your-gaming-setup-with-fast-valorant-loading/"><u>Accelerate Your Gaming Setup with Fast Valorant Loading</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-workflow-creating-windows-shortcuts-for-uwp/"><u>Accelerating Workflow: Creating Windows Shortcuts for UWP</u></a></li>
<li><a href="https://win11.techidaily.com/accurate-printouts-from-powerpoint-in-windows-9-top-fixes-unveiled/"><u>Accurate Printouts From PowerPoint in Windows: 9 Top Fixes Unveiled</u></a></li>
<li><a href="https://extra-tips.techidaily.com/achieving-fluidity-in-audio-blending-using-audacity-tools/"><u>Achieving Fluidity in Audio Blending Using Audacity Tools</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-windows-baseline-energy-profile/"><u>Achieving Windows' Baseline Energy Profile</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-the-essential-items-not-met-error-in-windows-11/"><u>Addressing the 'Essential Items Not Met' Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-photo-preview-sizes-on-windows-11/"><u>Adjusting Photo Preview Sizes on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-users-activate-elevated-cmd-status/"><u>Advanced Users: Activate Elevated CMD Status</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-window-settings-unseen-toolbar-configurations/"><u>Advanced Window Settings: Unseen Toolbar Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/alternative-approaches-for-integrating-additional-av-software/"><u>Alternative Approaches for Integrating Additional AV Software</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-clutter-pro-tips-to-adhere-sticky-notes-on-w11w10/"><u>Avoid Clutter: Pro Tips to Adhere Sticky Notes on W11/W10</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-common-setbacks-when-launching-csgo-on-w11/"><u>Avoiding Common Setbacks When Launching CS:GO on W11</u></a></li>
<li><a href="https://win11.techidaily.com/beginners-blueprint-to-windows-11-installation/"><u>Beginner's Blueprint to Windows 11 Installation</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-archive-game-creating-win11-sefx-packages-now/"><u>Boost Your Archive Game: Creating Win11 SEFx Packages Now</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-oppo-a2-device-sim-by-drfone-android/"><u>Easily Unlock Your Oppo A2 Device SIM</u></a></li>
<li><a href="https://win11.techidaily.com/1719382051492-exclusive-deal-for-tech-lovers-612-windows-11-lifetime-thanks-to-keys-fans/"><u>Exclusive Deal for Tech Lovers: $6.12 Windows 11 Lifetime, Thanks to Keys Fans</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719218317457-gpt4all-windows-guide-to-free-on-premise-chatbots/"><u>GPT4All Windows Guide to Free, On-Premise ChatBots.</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-xiaomi-14-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Xiaomi 14? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-music-from-honor-play-7t-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Music from Honor Play 7T to iPod | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-poco-x6-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Poco X6 | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-realme-12-5g-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Realme 12 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-non-gta-narratives-urban-games-of-similar-flair/"><u>In 2024, Non-GTA Narratives  Urban Games of Similar Flair</u></a></li>
<li><a href="https://extra-support.techidaily.com/picshots-innovation-hassle-free-collages-made-simple-for-2024/"><u>Picshot's Innovation  Hassle-Free Collages Made Simple for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/1719271169588-reclaim-your-browser-quick-fixes-to-unlock-chrome-on-win11/"><u>Reclaim Your Browser: Quick Fixes to Unlock Chrome on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/1719375739489-relaunch-google-chrome-on-win11-fixes-and-tips-here/"><u>Relaunch Google Chrome on Win11 – Fixes and Tips Here.</u></a></li>
<li><a href="https://win11.techidaily.com/1719364636660-self-hosted-windows-gptclone-via-gpt4all/"><u>Self-Hosted Windows GPTClone via GPT4All</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/streamlining-console-experience-with-computer-playback-tech-for-2024/"><u>Streamlining Console Experience with Computer Playback Tech for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/the-comprehensive-guide-to-zoom-screen-casts-for-2024/"><u>The Comprehensive Guide to Zoom Screen Casts for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-ultimate-guide-to-configuring-network-visibility-settings-onoff-for-windows-10-users/"><u>The Ultimate Guide to Configuring Network Visibility Settings (On/Off) for Windows 10 Users</u></a></li>
<li><a href="https://win11.techidaily.com/1719328494393-uninstalling-epic-launcher-on-w11-solutions-present/"><u>Uninstalling Epic Launcher on W11 - Solutions Present!</u></a></li>
<li><a href="https://data-wizards.techidaily.com/video-restoration-techniques-for-amateurs/"><u>Video Restoration Techniques for Amateurs</u></a></li>
</ul></div>
