---
title: TCP/IP Windows Checklist for Unblocked Ports
date: 2024-09-16T20:25:16.226Z
updated: 2024-09-21T21:46:18.619Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes TCP/IP Windows Checklist for Unblocked Ports
excerpt: This Article Describes TCP/IP Windows Checklist for Unblocked Ports
keywords: Blocked Port Fixation,TCP/IP Unblock Guide,IP Unblocking Steps,Windows Network Security,Port Unblock Strategy,Network Protocols Safety,Firewall Configuration Help
thumbnail: https://thmb.techidaily.com/f780668281f43de469309d641324f16afda3a68eb738e8c283227d7e47f57830.jpg
---

## TCP/IP Windows Checklist for Unblocked Ports

 Sometimes it's worth finding out which TCP/IP ports are open on your device. For example, let’s say your device is communicating with another PC, but the connection suddenly gets interrupted. In this case, you can check all the open TCP/IP ports. From there, you could try to resolve the issue at hand by troubleshooting any faulty port.

 This article covers the various ways to check active TCP/IP ports on Windows. But first, let’s find out how these ports work.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2111995/7443" target="_top" id="2111995">
  <img src="//a.impactradius-go.com/display-ad/7443-2111995" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111995/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 CurrPorts almost looks similar to TCPView, but it has a couple of additional tabs that display critical information. For example, this tool also shows you the Process Path (file path), the Product Name, the File Description, and the File Version (for apps).

 The tool displays all the open TCP/IP and UDP ports on your PC.

 If you want to close some ports, highlight them and then click the “close” icon. To filter your results, click the “filter” icon, select your filter, and then click **OK**.

 If you want to search for specific ports, click the “find” icon, type the name of the port, and then click **Find Next**.

 To edit your ports, navigate to the **Edit** tab and then select the relevant option.

 If you want to customize the CurrPorts tool, click the **View** tab and select the relevant option. And if you want to discover more customization features, head to the **Options** tab.

**Download**: CurrPorts for [Windows](https://www.nirsoft.net/utils/cports.html) (Free)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-footage.techidaily.com/new-invigorating-channel-content-best-video-concepts-to-inspire-viewers/"><u>[New] Invigorating Channel Content Best Video Concepts to Inspire Viewers</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-from-captured-moments-to-digital-fame-broadcasting-with-gopro-and-social-platforms/"><u>[Updated] In 2024, From Captured Moments to Digital Fame Broadcasting with GoPro & Social Platforms</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-pushing-boundaries-in-video-photography-nikon-1j5/"><u>[Updated] Pushing Boundaries in Video Photography - Nikon 1J5</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-xiaomi-redmi-note-13-proplus-5g-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Xiaomi Redmi Note 13 Pro+ 5G Phone</u></a></li>
<li><a href="https://fox-that.techidaily.com/frustrated-with-your-iphones-messaging-problems-fix-them-in-these-10-easy-ways/"><u>Frustrated with Your iPhone’s Messaging Problems? Fix Them in These 10 Easy Ways!</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-reset-the-security-questions-of-your-apple-id-on-your-apple-iphone-7-by-drfone-ios/"><u>How To Reset the Security Questions of Your Apple ID On Your Apple iPhone 7</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-peeking-at-high-resolution-display-innovation-the-dell-p2715q-review/"><u>In 2024, Peeking at High-Resolution Display Innovation - The Dell P2715Q Review</u></a></li>
<li><a href="https://win11.techidaily.com/mp3dailymotion/"><u>MP3への変換：Dailymotionビデオからスマートな転送ガイド</u></a></li>
<li><a href="https://win11.techidaily.com/mp4pcgif5/"><u>MP4ビデオをPC上でGIFへの変換方法:5選ベストガイド</u></a></li>
<li><a href="https://win11.techidaily.com/offline-entertainment-unlimited-quick-download-movies-shows-songs-and-special-features-for-on-the-go-viewing/"><u>Offline Entertainment Unlimited: Quick-Download Movies, Shows, Songs, and Special Features for On-The-Go Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/playing-japanese-region-bddvd-on-american-systems-without-a-specialized-disc-player/"><u>Playing Japanese Region BD/DVD on American Systems Without a Specialized Disc Player</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-conversion-top-3-techniques-for-turning-your-google-slides-into-videos/"><u>Seamless Conversion: Top 3 Techniques for Turning Your Google Slides Into Videos</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ering-synthetic-statistics-on-youtube/"><u>Shattering Synthetic Statistics on YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/simplify-audio-conversion-discover-the-three-best-avi-to-mp3-transformation-techniques/"><u>Simplify Audio Conversion: Discover the Three Best AVI to MP3 Transformation Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-ac3-audio-format-conversion-the-ultimate-tool-for-fast-and-effortless-mp3-creation/"><u>Speedy AC3 Audio Format Conversion: The Ultimate Tool for Fast and Effortless MP3 Creation</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unleashing-video-potential-mastering-script-craft-with-chatgpt/"><u>Unleashing Video Potential: Mastering Script Craft with ChatGPT</u></a></li>
</ul></div>

