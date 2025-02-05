---
title: "Speed Sensors: Windows-Based Methods for Examining Network Rate"
date: 2025-01-31T22:45:16.144Z
updated: 2025-02-03T16:00:18.193Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Speed Sensors: Windows-Based Methods for Examining Network Rate"
excerpt: "This Article Describes Speed Sensors: Windows-Based Methods for Examining Network Rate"
keywords: Network Rate Analysis,Speed Sensor Windows,Network Speed Test,Wireless Monitoring,Data Throughput Check,Windows Network Diagnostics,Real-Time Traffic Evaluation
thumbnail: https://thmb.techidaily.com/95788679327077f3bf6744c4870d74096e3663b00fb525d667e1a6c4f5883874.jpg
---

## Speed Sensors: Windows-Based Methods for Examining Network Rate

 The network adapter is a critical piece of hardware that connects your Windows computer to the internet via a wired or wireless connection. In order to achieve the maximum speeds offered by your Internet Service Provider, it is important to know what network speed your card is capable of.

 Whether you want to upgrade your internet plan or diagnose your network for performance issues, there are several ways to determine the network adapter speed on Windows. Let’s go over all of them one by one.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Check the Network Adapter Connection Speed Using the Settings App

 The quickest way to check the connection speed for a Wi-Fi or Ethernet adapter is through the Windows Settings app. Aside from network speed, the Settings app also provides important information like network band, local IP address, MAC address, and more.

To check the network adapter speed via the Settings app:

1. Press**Win + I** to open the Settings app.
2. Select**Network & internet** from the left sidebar.
3. Click on**Properties** at the top.
4. Scroll down to the**Link speed (Receive/Transmit)** field to check the connection speed.  
![Check Network Adapter Speed Using the Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-the-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Check the Network Adapter Connection Speed Using Control Panel

 Although Microsoft is gradually moving a large number of features to the Settings app, many people still prefer to use the Control Panel to modify settings and troubleshoot issues. If you are one of them, here's how you can check the network adapter connection speed via Control Panel.

1. Press**Win + R** to open the Run dialog (see[how to open Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways).
2. Type**control** in the box and press**Enter** .
3. In the Control Panel window that opens, use the drop-down menu in the top right corner to change the view type to**Small icons** or**Large icons** .
4. Go to**Network and Sharing Center** .
5. Click the**Change adapter settings** link from the left pane.
6. Double-click on your Ethernet or Wi-Fi adapter to open its properties.
7. Check the connection speed of your network adapter in the**Speed** field.  
![Check Network Adapter Speed Using Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-control-panel.jpg)

 Seeing too many network adapter entries on your Windows computer? Learn[how to get rid of old or inactive network adapters from Windows](https://www.makeuseof.com/how-to-remove-network-adapter-windows/) in a few easy steps.

## 3\. How to Check Network Adapter Connection Speed via Command Prompt

 Not a fan of GUI? No problem. You can also use a command-line utility like Command Prompt to check the network adapter connection speed on Windows. Here are the steps for the same.

1. Right-click on the Start icon or use the**Win + X** shortcut to open the[Power User menu](https://www.makeuseof.com/windows-power-menu-guide/) .
2. Select**Terminal** from the list.
3. In the console, paste the following command and press**Enter** .  
`netsh wlan show interfaces`
4. Check the values next to**Receive rate** and**Transmit rate** to determine the speed of your network adapter.  
![Check Network Adapter Speed Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Like using Command Prompt? Check our guide on[how to master Command Prompt on Windows](https://www.makeuseof.com/tag/windows-10-command-prompt-tips/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. How to Check Network Adapter Connection Speed via PowerShell

 PowerShell is yet another command-line tool you can use to interact with Windows. Although PowerShell is primarily used to automate tasks and troubleshoot errors, you can also use it to find system information such as the network adapter speed.

To check network adapter connection speed via PowerShell:

1. Press**Win + S** to open the search menu.
2. Type**Windows PowerShell** in the search box and press**Enter** .
3. Paste the following command in the console and press**Enter** .  
`Get-NetAdapter | select interfaceDescription, name, status, linkSpeed`  
![Check Network Adapter Speed Using PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/check-network-adapter-speed-using-powershell.jpg)

 Once you run the above command, PowerShell will display a list of all the Ethernet and Wi-Fi adapters on your Windows computer, along with their link speeds.

## Checking Network Adapter Connection Speed on Windows

 As we just learned, determining the network adapter connection speed on Windows is relatively simple. Do you know what else is easy? Speeding up the internet connection speed on your Windows computer.

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
<li><a href="https://youtube-docs.techidaily.com/n-2024-ace-your-shots-top-cameras-and-lenses-for-youtubers/"><u>[New] In 2024, Ace Your Shots Top Cameras & Lenses for YouTubers</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-maximizing-your-fb-page-visibility-a-step-by-step-guide/"><u>[Updated] In 2024, Maximizing Your FB Page Visibility A Step-by-Step Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-master-the-art-of-cutting-a-video-editors-handbook-for-instagram/"><u>[Updated] Master the Art of Cutting A Video Editor's Handbook for Instagram</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-pioneer-productions-leading-free-editors-on-android-for-2024/"><u>[Updated] Pioneer Productions Leading Free Editors on Android for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-optimal-sizing-for-youtube-thumbnail-impact/"><u>2024 Approved Optimal Sizing for YouTube Thumbnail Impact</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-hotkeys-for-pre-text-snip-pasting-in-w10w11/"><u>Efficient Hotkeys for Pre-Text Snip Pasting in W10/W11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-metaverse-makeover-easy-avatar-construction/"><u>In 2024, The Metaverse Makeover Easy Avatar Construction</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-red-screen-glitch-with-easy-fixes-and-expert-advice/"><u>Overcoming the 'Red Screen' Glitch with Easy Fixes and Expert Advice</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-wi-fi-network-configuration-bridging-prompt-gaps/"><u>Perfecting Wi-Fi Network Configuration: Bridging Prompt Gaps</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-wmi-service-overuse-on-pcs/"><u>Tackling WMI Service Overuse on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-hypervisor-error-blue-screen-on-win-1011/"><u>Troubleshooting Hypervisor Error Blue Screen on Win 10/11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-the-ultimate-time-lapse-crash-course-final-cut-pro-edition/"><u>Updated The Ultimate Time Lapse Crash Course Final Cut Pro Edition</u></a></li>
</ul></div>

