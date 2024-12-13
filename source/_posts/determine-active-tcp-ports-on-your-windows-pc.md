---
title: Determine Active TCP Ports on Your Windows PC
date: 2024-12-09T14:06:01.897Z
updated: 2024-12-13T00:28:08.548Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Determine Active TCP Ports on Your Windows PC
excerpt: This Article Describes Determine Active TCP Ports on Your Windows PC
keywords: Active TCP Windows,Find TCP Ports Windows,Identify Windows TCP,Windows TCP Status,Check TCP Open Windows,Discover TCP Windows,Pinpoint Active TCP
thumbnail: https://thmb.techidaily.com/ab11097b735383eb1301c6c7953b6d3e90027241dcabace0ad8db43fe24b30d7.jpg
---

## Determine Active TCP Ports on Your Windows PC

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UUPt2zKtJ5k?si=LLHdsFDLzVByJsKj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The process names are the values displayed in square brackets below the port names.

 For example, you might see the “\[svchost.exe\]” process name under one of the TCP ports.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Check Which TCP/IP Ports Are Open Using Third-Party Apps

 If you’re a fan of third-party apps, here are some tools that can help you check active TCP/IP ports on your device.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 CurrPorts almost looks similar to TCPView, but it has a couple of additional tabs that display critical information. For example, this tool also shows you the Process Path (file path), the Product Name, the File Description, and the File Version (for apps).

 The tool displays all the open TCP/IP and UDP ports on your PC.

 If you want to close some ports, highlight them and then click the “close” icon. To filter your results, click the “filter” icon, select your filter, and then click **OK**.

 If you want to search for specific ports, click the “find” icon, type the name of the port, and then click **Find Next**.

 To edit your ports, navigate to the **Edit** tab and then select the relevant option.

 If you want to customize the CurrPorts tool, click the **View** tab and select the relevant option. And if you want to discover more customization features, head to the **Options** tab.

**Download**: CurrPorts for [Windows](https://www.nirsoft.net/utils/cports.html) (Free)

### TCP Monitor Plus

![The TCP Monitor Plus Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/the-tcp-monitor-plus-tool.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-live-gaming-shows-set-up-with-obs/"><u>[New] 2024 Approved Live Gaming Shows Set Up with OBS</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-cataloging-tiktok-scenes-as-backgrounds/"><u>[New] Cataloging TikTok Scenes as Backgrounds</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-eluding-prying-eyes-privacy-preserving-video-editing/"><u>[Updated] 2024 Approved Eluding Prying Eyes Privacy-Preserving Video Editing</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-converting-your-favourite-tracks-bridging-spotify-with-youtube-music/"><u>[Updated] In 2024, Converting Your Favourite Tracks Bridging Spotify with YouTube Music</u></a></li>
<li><a href="https://win11.techidaily.com/easy-sticknotes-setup-for-optimal-note-taking-in-win11win10/"><u>Easy StickNotes Setup for Optimal Note-Taking in Win11/Win10</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-frp-on-oppo-a1x-5g-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass FRP on Oppo A1x 5G</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-realme-10t-5g-get-deleted-pictures-back-with-ease-and-safety-by-fonelab-android-recover-pictures/"><u>How to Realme 10T 5G Get Deleted Pictures Back with Ease and Safety?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rebuild-the-icon-cache-in-windows/"><u>How to Rebuild the Icon Cache in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-cure-for-windows-11-drag-glitches/"><u>Immediate Cure for Windows 11 Drag Glitches</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-purchasing-options-choosing-premium-vs-standard-fixtures-and-whether-they-are-integrated-or-retrofit-options-can-alter-costs/"><u>In 2024, __Purchasing Options__ Choosing Premium Vs. Standard Fixtures and Whether They Are Integrated or Retrofit Options Can Alter Costs.</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/is-xbox-network-down-or-is-it-just-you/"><u>Is Xbox Network Down ... Or Is It Just You?</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-win-rpc-failures-five-essential-steps/"><u>Preventing Win RPC Failures: Five Essential Steps</u></a></li>
<li><a href="https://win11.techidaily.com/quick-steps-to-mend-a-stuck-windows-11-search-bar-on-settings-page/"><u>Quick Steps to Mend a Stuck Windows 11 Search Bar on Settings Page</u></a></li>
<li><a href="https://techtrends.techidaily.com/smart-shopping-tips-for-acquiring-a-quality-television-for-your-residence/"><u>Smart Shopping Tips for Acquiring a Quality Television for Your Residence</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-sluggishness-in-microsoft-edge-win10w11/"><u>Solutions for Sluggishness in Microsoft Edge, Win10/W11</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/spotify-and-socializing-how-to-create-shared-listening-experiences/"><u>Spotify & Socializing: How To Create Shared Listening Experiences</u></a></li>
<li><a href="https://win11.techidaily.com/the-new-frontier-of-programming-with-microsoft-copilot/"><u>The New Frontier of Programming with Microsoft Copilot</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-power-5-must-try-apps-to-supercharge-windows-productivity/"><u>Unleashing Power: 5 Must-Try Apps to Supercharge Windows Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/winrar-integrity-restoration-6-summation-error-solutions/"><u>WinRAR Integrity Restoration: 6 Summation Error Solutions</u></a></li>
</ul></div>

