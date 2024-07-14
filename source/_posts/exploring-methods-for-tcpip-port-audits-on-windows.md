---
title: Exploring Methods for TCP/IP Port Audits on Windows
date: 2024-07-13T10:42:25.425Z
updated: 2024-07-14T10:42:25.425Z
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
<li><a href="https://win11.techidaily.com/1719337024529-get-chrome-back-in-windows-11-quick-recovery-methods/"><u>Get Chrome Back in Windows 11 – Quick Recovery Methods.</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-tailoring-content-to-trends-organic-growth-strategies-for-youtubers/"><u>In 2024, Tailoring Content to Trends  Organic Growth Strategies for YouTubers</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-for-win10-blue-screen-resolution/"><u>Key Techniques for Win10 Blue Screen Resolution</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-speed-setback-by-apps-with-innocuous-exteriors/"><u>Windows 11’S Speed Setback by Apps with Innocuous Exteriors</u></a></li>
<li><a href="https://win11.techidaily.com/the-sound-surge-5-apps-to-take-windows-volume-well-above-100/"><u>The Sound Surge: 5 Apps to Take Windows' Volume Well Above 100%%</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-simplify-slide-sharing-at-work-webcam-assisted-tips/"><u>2024 Approved  Simplify Slide Sharing at Work  Webcam-Assisted Tips</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-windows-features-for-macos-advantages/"><u>Integrating Windows Features for MacOS Advantages</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-search-service-not-available-on-windows/"><u>Tackling Search Service Not Available on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-accessibility-features/"><u>Navigating Through Windows' Accessibility Features</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-git-operations-with-github-desktop-and-windows-1011/"><u>Streamlining Git Operations with GitHub Desktop & Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-start-guide-for-efficient-note-placement-in-win11win10/"><u>Quick-Start Guide for Efficient Note Placement in Win11/Win10</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-android-fun-for-windows-users-through-google-play/"><u>Streamlining Android Fun for Windows Users Through Google Play</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-realme-12-5g-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Realme 12 5G?</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-modify-indexer-in-windows/"><u>Step-by-Step: Modify Indexer in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-when-windows-cant-locate-powershell-console/"><u>What to Do When Windows Can't Locate PowerShell Console</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-server-stumbled-errors-in-microsoft-store/"><u>Steps to Eliminate Server Stumbled Errors in Microsoft Store</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-realme-11-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, How PGSharp Save You from Ban While Spoofing Pokemon Go On Realme 11 Pro+? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-artisans-approach-to-perfect-slide-printouts-from-powerpoint-in-windows/"><u>The Artisan's Approach to Perfect Slide Printouts From PowerPoint in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-window-pc-always-unlocked/"><u>Keep Your Window PC Always Unlocked</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-removing-epic-games-hub-from-windows-11-a-quick-guide/"><u>Trouble Removing Epic Games Hub From Windows 11: A Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-office-outlook-alerts-in-windows/"><u>Troubleshooting Non-Functional Office Outlook Alerts in Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-access-your-iphone-6-plus-when-you-forget-the-passcode-by-drfone-ios/"><u>In 2024, How to Access Your iPhone 6 Plus When You Forget the Passcode?</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-navigating-the-obscured-realm-of-youtube-a-methodical-approach/"><u>2024 Approved  Navigating the Obscured Realm of YouTube  A Methodical Approach</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-googles-advanced-upload-techniques-for-podcasters/"><u>[Updated] Google's Advanced Upload Techniques for Podcasters</u></a></li>
<li><a href="https://win11.techidaily.com/swift-keystrokes-in-win-os-a-guide-to-eliminate-delay/"><u>Swift Keystrokes in WIN OS: A Guide to Eliminate Delay</u></a></li>
<li><a href="https://win11.techidaily.com/windows-users-save-your-keys-from-failure/"><u>Windows Users: Save Your Keys From Failure</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-infinix-hot-30-5g-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Infinix Hot 30 5G to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/notetaking-renaissance-discovering-obsidians-visuality/"><u>Notetaking Renaissance: Discovering Obsidian's Visuality</u></a></li>
<li><a href="https://extra-support.techidaily.com/podcastpathfinder-moving-past-dacast-for-2024/"><u>PodcastPathfinder  Moving Past DaCast for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-enhancing-tiktok-metrics-with-innovative-and-memorable-usernames-for-2024/"><u>[New] Enhancing TikTok Metrics with Innovative and Memorable Usernames for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-top-10-youtubers-with-the-most-subscribers/"><u>2024 Approved  Top 10 YouTubers with the Most Subscribers</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-oneplus-11r-frp-by-drfone-android/"><u>In 2024, How Can We Bypass OnePlus 11R FRP?</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-pixels-designing-unique-displays-on-each-monitor-of-windows/"><u>Personalized Pixels: Designing Unique Displays on Each Monitor of Windows</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-mac-movie-magic-a-beginners-guide-to-choosing-the-perfect-video-editor-for-2024/"><u>New Mac Movie Magic A Beginners Guide to Choosing the Perfect Video Editor for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-free-film-production-integrating-soundtracks-into-your-workflow/"><u>New In 2024, Free Film Production Integrating Soundtracks Into Your Workflow</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-seamlessly-upload-twitter-videos-on-instagram/"><u>[Updated] 2024 Approved  Seamlessly Upload Twitter Videos on Instagram</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-installer-errors-in-windows-10-and-11/"><u>Overcoming Windows Installer Errors in Windows 10 & 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-strategies-for-dampening-aerial-drone-vibration-artifacts/"><u>2024 Approved  Strategies for Dampening Aerial Drone Vibration Artifacts</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-dominance-digest-the-ultimate-battle-royale-list/"><u>[New] Dominance Digest  The Ultimate Battle Royale List</u></a></li>
<li><a href="https://win11.techidaily.com/4-key-approaches-to-activate-a-dormant-windows-guard/"><u>4 Key Approaches to Activate a Dormant Windows Guard</u></a></li>
<li><a href="https://win11.techidaily.com/microsofts-ai-hub-enhancing-shopping-experience/"><u>Microsoft’s AI Hub – Enhancing Shopping Experience</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-disable-protected-app-ban-on-windows/"><u>Steps to Disable Protected App Ban on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-disruptions-preventing-unexpected-crashes-in-dwarf-fortress/"><u>Unraveling Disruptions: Preventing Unexpected Crashes in Dwarf Fortress</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-join-the-visual-speech-the-simple-guide-to-posting-and-uploading-gifs-on-instagram-for-2024/"><u>[New] Join the Visual Speech  The Simple Guide to Posting and Uploading GIFs on Instagram for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/windows-installation-manual-for-chatgpt/"><u>Windows Installation Manual for ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-web-sites-becoming-win-desktops/"><u>The Art of Web Sites Becoming Win Desktops</u></a></li>
</ul></div>
