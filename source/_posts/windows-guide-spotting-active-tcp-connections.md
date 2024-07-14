---
title: "Windows Guide: Spotting Active TCP Connections"
date: 2024-07-13T10:01:13.583Z
updated: 2024-07-14T10:01:13.583Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows Guide: Spotting Active TCP Connections"
excerpt: "This Article Describes Windows Guide: Spotting Active TCP Connections"
keywords: WinTCPConnSpotter,WindowsTCPActivity,NetworkingGuideWin,TCPConnectActiveWin,SpottingWindowsTCP,ActiveTCPTrackWin,ConnectionsGuideWin
thumbnail: https://thmb.techidaily.com/b9236612d2096893f2d14ce12421ffb6e267518dd04f148a1a29c144e2d43e5b.jpg
---

## Windows Guide: Spotting Active TCP Connections

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

 In some instances, you might want to check out the TCP/IP ports along with their Process Identifiers (the unique numbers that identify processes). This method could be useful if you can’t find the process names using the previous method.

 When you’re done [searching for the Process Identifier (PID) on Windows](https://www.makeuseof.com/ways-to-find-application-process-id-in-windows-10/), you can check out the task name linked to the PID in the Task Manager.

 Let’s start by checking out how to check the open TCP/IP ports and their PIDs:

1. Press **Win + R** to open the Run command dialog box.
2. Type **CMD** and press **Ctrl + Shift + Enter** to open an elevated Command Prompt.
3. Type the following command and press **Enter**.

netstat -aon

 Your screen should display five columns: **Proto, Local Address, Foreign Address, State,** and **PID**.

![Checking TCP-IP ports and process identifiers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-tcp-ip-ports-and-process-identifiers.jpg)

 Once you've found the PID of a certain port, here’s how you can use the Task Manager to find the task linked to that PID:

1. Type **Task Manager** in the Start menu search bar and select the **Best match**.
2. Navigate to the **Details** tab.
3. Look for your PID value in the **PID section** and locate the task name from the results on the left.

![Checking the PID value and task name on the Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-the-pid-value-and-task-name-on-the-task-manager.jpg)

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

 CurrPorts almost looks similar to TCPView, but it has a couple of additional tabs that display critical information. For example, this tool also shows you the Process Path (file path), the Product Name, the File Description, and the File Version (for apps).

 The tool displays all the open TCP/IP and UDP ports on your PC.

 If you want to close some ports, highlight them and then click the “close” icon. To filter your results, click the “filter” icon, select your filter, and then click **OK**.

 If you want to search for specific ports, click the “find” icon, type the name of the port, and then click **Find Next**.

 To edit your ports, navigate to the **Edit** tab and then select the relevant option.

 If you want to customize the CurrPorts tool, click the **View** tab and select the relevant option. And if you want to discover more customization features, head to the **Options** tab.

**Download**: CurrPorts for [Windows](https://www.nirsoft.net/utils/cports.html) (Free)

### TCP Monitor Plus

![The TCP Monitor Plus Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-tcp-monitor-plus-tool.jpg)

 TCP Monitor Plus comprises 11 tabs that you can use for various purposes. But in this case, we’ll focus on the Session Monitor tab because that’s where the TCP/IP information is located.

 Once you’re on the Session Monitor tab, you should see various sections containing information about the TCP/IP ports. The "Status" tab tells you whether the ports are open or connecting. The other tabs display information such as the IP address, hostname, process name, and more.

 If you want to make changes to a specific port, right-click on it and select a relevant option.

**Download**: TCP Monitor Plus for [Windows](https://www.softpedia.com/get/Network-Tools/Network-Monitoring/TCP-Monitor-Plus.shtml) (Free)

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
<li><a href="https://win11.techidaily.com/windows-users-the-gains-from-dxvk-adoption/"><u>Windows Users - The Gains From DXVK Adoption</u></a></li>
<li><a href="https://win11.techidaily.com/why-the-shift-from-windows-10-to-version-11-fails/"><u>Why the Shift From Windows 10 to Version 11 Fails</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/combating-an-unresponsive-obs-camera-input-stream/"><u>Combating an Unresponsive OBS Camera Input Stream</u></a></li>
<li><a href="https://win11.techidaily.com/diagnosing-and-fixing-the-frozen-resource-monitor-app-in-win11/"><u>Diagnosing and Fixing the Frozen Resource Monitor App in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-the-mystery-of-the-blank-steam-window/"><u>Dealing With the Mystery of the Blank Steam Window</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-apple-iphone-6-drfone-by-drfone-virtual-ios/"><u>Full Guide to Fix iToolab AnyGO Not Working On Apple iPhone 6 | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-crack-up-compilation-the-most-funny-tiktok-joke-threads/"><u>[New] 2024 Approved  Crack-Up Compilation  The Most Funny TikTok Joke Threads</u></a></li>
<li><a href="https://win11.techidaily.com/ux3405-vs-macbooks-asuss-oled-showdown/"><u>UX3405 vs MacBooks: Asus's OLED Showdown</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-in-the-views-youtube-thumbnail-size-and-ratios/"><u>Reign in the Views  Youtube Thumbnail Size & Ratios</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-i-add-my-signature-to-excel-2021-files-by-ldigisigner-sign-a-excel-sign-a-excel/"><u>How do i add my signature to Excel 2021 files</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-real-time-reality-rally-does-digital-dethrone-device-dominance/"><u>[New] Real-Time Reality Rally  Does Digital Dethrone Device Dominance?</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-latency-and-silence-in-valorants-voice-communication-windows/"><u>Fixing Latency and Silence in Valorant's Voice Communication (Windows)</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-xiaomi-redmi-13c-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Xiaomi Redmi 13C | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-instagram-video-speed-boosting-for-smooth-playbacks-mobiledesktop/"><u>2024 Approved  Instagram Video Speed Boosting for Smooth Playbacks (Mobile/Desktop)</u></a></li>
<li><a href="https://win11.techidaily.com/esd-file-transformation-mastery-your-pathway-to-windows-iso-success/"><u>ESD File Transformation Mastery: Your Pathway to Windows ISO Success</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-x100-bootloader-easily-by-drfone-android/"><u>How to Unlock Vivo X100 Bootloader Easily</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-secrets-to-effective-targeted-tweets/"><u>[New] Secrets to Effective Targeted Tweets</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-installer-access-rights-shortcomings/"><u>Fixing Windows Installer Access Rights Shortcomings</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-education-themes-on-windows-11/"><u>How to Enable Education Themes on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-apps-to-monitor-win-os-temperatures/"><u>Ideal Apps to Monitor Win OS Temperatures</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-generations-old-games-with-dosbox-x/"><u>Bridging Generations: Old Games with DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-blink-quick-fixes-for-input-lag-on-latest-microsoft-os/"><u>Beat the Blink: Quick Fixes for Input Lag on Latest Microsoft OS</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-top-digital-scrapbooking-tools-for-photos-and-videos-for-2024/"><u>Updated Top Digital Scrapbooking Tools for Photos and Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/enable-microphone-and-camera-via-app-guard-in-windows-11/"><u>Enable Microphone & Camera via App Guard in Windows 11</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-unleash-your-creativity-best-mac-video-maker-apps/"><u>In 2024, Unleash Your Creativity Best Mac Video Maker Apps</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-digitally-delving-into-deleted-youtubes-easy-watch-options/"><u>[New] In 2024, Digitally Delving Into Deleted YouTubes  Easy Watch Options</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-an-application-not-installed-via-microsofts-store/"><u>Fixing an Application Not Installed via Microsoft's Store</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-identifying-the-worlds-top-8-youtube-surges/"><u>[New] Identifying the World's Top 8 YouTube Surges</u></a></li>
<li><a href="https://win11.techidaily.com/yearly-best-offer-buy-now-at-612-for-eternal-win10-life/"><u>Yearly Best Offer: Buy Now at $6.12 for Eternal Win10 Life</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-correcting-windows-defender-error-0x80004004/"><u>Deciphering & Correcting Windows Defender Error 0X80004004</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-data-discovery-on-pc-via-everythingapp/"><u>Effortless Data Discovery on PC via EverythingApp</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-and-powershell-a-comparative-analysis-on-their-uniqueness/"><u>Windows Terminal & PowerShell: A Comparative Analysis on Their Uniqueness</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-mastering-youtubes-visual-flow-five-budget-friendly-methods/"><u>[New] Mastering YouTube's Visual Flow - Five Budget-Friendly Methods</u></a></li>
<li><a href="https://win11.techidaily.com/banish-keystroke-chaos-an-effective-guide-to-repair-common-windows-shortcut-issues/"><u>Banish Keystroke Chaos! An Effective Guide to Repair Common Windows Shortcut Issues</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-startup-launching-windows-and-notebooks-effortlessly/"><u>Accelerated Startup: Launching Windows and Notebooks Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/a-dual-screen-dream-realized-android-plus-windows-11-collaboration/"><u>A Dual-Screen Dream Realized: Android + Windows 11 Collaboration</u></a></li>
<li><a href="https://win11.techidaily.com/enrich-your-galaxy-experience-utilizing-the-dex-app-in-windows/"><u>Enrich Your Galaxy Experience: Utilizing the DeX App in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-security-of-windows-11s-s-mode/"><u>Unpacking the Security of Windows 11'S 'S Mode'</u></a></li>
<li><a href="https://win11.techidaily.com/expanding-windows-hard-drive-sustainably/"><u>Expanding Windows Hard Drive Sustainably</u></a></li>
<li><a href="https://win11.techidaily.com/determining-the-ideal-nearby-networking-method-google-vs-windows/"><u>Determining the Ideal Nearby Networking Method: Google Vs. Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-novices-guide-to-windows-11-sound-capture/"><u>A Novice's Guide to Windows 11 Sound Capture</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-honor-play-40c-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Honor Play 40C Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-activation-lock-on-apple-iphone-12-mini-4-easy-ways-by-drfone-ios/"><u>In 2024, Bypass Activation Lock On Apple iPhone 12 mini - 4 Easy Ways</u></a></li>
<li><a href="https://win11.techidaily.com/countering-dxgideviceremoved-failsafe-techniques/"><u>Countering DXGI_DEVICE_REMOVED Failsafe Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-absent-windows-notification-icons/"><u>Fixes for Absent Windows Notification Icons</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unresponsive-task-issues-in-windows-os/"><u>Addressing 'Unresponsive Task' Issues in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/winning-with-linux-the-windows-integration-edge/"><u>Winning with Linux: The Windows Integration Edge</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-how-to-loop-a-video-on-iphone/"><u>[Updated] 2024 Approved  How to Loop A Video on iPhone?</u></a></li>
</ul></div>
