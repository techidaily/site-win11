---
title: "Mastering Subnet Settings: Windows 11 Guide"
date: 2024-11-25T16:24:46.209Z
updated: 2024-11-27T22:29:10.548Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Subnet Settings: Windows 11 Guide"
excerpt: "This Article Describes Mastering Subnet Settings: Windows 11 Guide"
keywords: Win11 Subnet Mastery,Windows NetConfig,Network Subsetting,Subnet Adjustment W11,SetNet Windows 11,Windows Subnet Guide,Optimize Subnet Settings
thumbnail: https://thmb.techidaily.com/cd3d45b359655445d3a3fddc84f4f42edd47a1ec876e69fbcc20cbbbf17a86ba.png
---

## Mastering Subnet Settings: Windows 11 Guide

 Devices in a subnetwork have IP addresses that begin with the same prefix. The length of this prefix is different for different devices—it depends on the network size, whose length is identified using the subnet mask.

 While troubleshooting network issues, you must ensure that the subnet mask is correct. So, we'll share how to find and change the subnet in Windows 11.

## How to Find the Subnet Mask in Windows 11

 The easiest way to find the subnet mask in Windows 11 is through the[Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) or Windows PowerShell. To find it using the Command Prompt, follow the steps below:

1. Press the**Win** key to launch the Start Menu.
2. In the search bar, type**Command Prompt** and choose the**Run as administrator** option from the right pane.
3. In the elevated Command Prompt window, type**ipconfig /all** and press Enter. This command will display all the important details about the network your computer is connected to, including the subnet mask.
4. Scroll and look for**Subnet Mask.** It'll be under the**Wireless LAN adapter Wi-Fi** section.  
![Finding the Subnet mask in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/finding-the-subnet-mask.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The steps to do it using Windows PowerShell are similar to the Command Prompt. To do it,[open Windows PowerShell with admin rights](https://www.makeuseof.com/windows-11-powershell-administrator/) , type the ipconfig /all command, and press Enter.

 In the result that appears, you can see the subnet mask under the Wireless LAN adapter Wi-Fi section.

## How to Change the Subnet Mask in Windows 11

 Now that you know how to find the subnet mask on your computer, let's check out how to change it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1dR4tF3VgyU?si=AJipgqZsNNxsRsBW&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Change the Subnet Mask Using the Windows Settings

 The settings menu is the central hub of a Windows operating system. It's a place to configure different settings of your computer and manage the network. You can also use it to change the subnet mask.

Here's how to do it:

1. [Open the Windows Systems Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and choose**Network & internet** from the left panel.
2. Select**Wi-Fi,** and then choose your network in the following window.
3. Click the**Edit** button next to the**IP assignment** option.  
![Edit button in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/edit-button.jpg)
4. In the prompt that crops up, click on the drop-down icon and choose**Manual.**
5. Enable the toggle next to the IP version you're using.
6. Enter the details, including the subnet mask, and click**Save.**  
![Entering the new Subnet Mask in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/entering-the-new-subnet-mask.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Change the Subnet Mask Using the Control Panel

 The Control Panel is the go-to place to configure window settings and make changes to your device. To use it to change the subnet mask, follow the below instructions:

1. Press the Win key, type**Control Panel** in the search bar, and press Enter.
2. Click the drop-down icon next to**View by** and choose**Large icons.**
3. Choose**Network and Internet** , and then select**Network and Sharing Center** in the following window.
4. Click on your network next to**Connections.**  
![Network name in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-name.jpg)
5. Choose**Properties** from the window that appears.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Select the IP version you're using. For instance, if you're using IPv4, select**Internet Protocol Version 4 (TCP/IPv4)** and click the**Properties** button.  
![IPv4 properties option in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv4-properties.jpg)
7. Select the**Use the following address** option and enter the details.  
![Changing the Subnet Mask in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/changing-the-subnet-mask.jpg)
8. Click**OK** to save the changes.

### 3\. Change the Subnet Mask Using Windows PowerShell

 Windows PowerShell is also one of the places from where you can change the subnet mask in Windows 11\. Here's how to do it:

1. Open Windows PowerShell with admin rights, type the following command, and press Enter. This command will display all the network adapters installed on your device.  
`Get-NetAdapter -physical`
2. To change the subnet mask, type the following command and press Enter. Make sure to replace the "**ifIndex Number** " with the number associated with the network adapter whose subnet mask you want to change. And replace "**subnet prefix length** " with the new subnet prefix length you want.  
`Set-NetIPAddress -InterfaceIndex (ifIndex Number) -PrefixLength (subnet prefix length)`

 For instance, if the ifIndex Number is 3 and the new subnet prefix length you want is 24, then the command will be:

`Set-NetIPAddress -InterfaceIndex 3 -PrefixLength 24`

![Command to change the subnet mask in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-change-the-subnet-mask.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Changing the Subnet Mask in Windows 11

 The subnet mask helps to identify the network and the host bit of the IP address. If you want to find and change the subnet mask on your computer, you can do it using either of the above methods.

 Meanwhile, you might be interested to know more about subnets and how to calculate them.

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
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-instantaneously-showcasing-archived-video-sessions-via-facebook-live/"><u>[New] In 2024, Instantaneously Showcasing Archived Video Sessions via Facebook Live</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-in-2024-prioritize-these-5-facts-when-tiktoking-on-macos/"><u>[New] In 2024, Prioritize These 5 Facts When TikToking on macOS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-initial-steps-to-professional-motion-graphics/"><u>[New] Initial Steps to Professional Motion Graphics</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-understanding-cultural-influences-on-consumer-behavior-in-global-markets/"><u>[New] Understanding Cultural Influences on Consumer Behavior in Global Markets</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-vivo-y78t-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Vivo Y78t | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/employing-microsofts-techniques-for-error-exploration-on-w11/"><u>Employing Microsoft's Techniques for Error Exploration on W11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-disconnected-printer-issues-on-windows-11/"><u>Fixing Disconnected Printer Issues on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/future-tech-on-your-desk-ifa-2023-winners/"><u>Future Tech on Your Desk - IFA 2023 Winners</u></a></li>
<li><a href="https://win11.techidaily.com/how-artificial-intelligence-is-revolutionizing-windows-software/"><u>How Artificial Intelligence Is Revolutionizing Windows Software</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-error-0x80242016-in-updates/"><u>How to Resolve Error 0X80242016 in Updates</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/ideal-tools-leading-mac-video-recording-programs-for-2024/"><u>Ideal Tools Leading Mac Video Recording Programs for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-maximizing-your-youtube-videos-viewer-count/"><u>In 2024, Maximizing Your YouTube Video's Viewer Count</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-efficiency-essential-strategies-for-windows-11-users-36/"><u>Mastering Efficiency: Essential Strategies for Windows 11 Users (36)</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/sculpt-satirical-scenes-with-giphy-for-2024/"><u>Sculpt Satirical Scenes with Giphy for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-file-sharing-between-windows-pcs-using-aoemi/"><u>Seamless File Sharing Between Windows PCs Using AOEMi</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-keyboard-triggers-embedding-commands-for-wordpad-into-context-menus/"><u>Streamlining Keyboard Triggers: Embedding Commands for Wordpad Into Context Menus</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-update-failure-error-code-0xc004f050/"><u>Tackling Windows Update Failure: Error Code 0XC004F050</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Vivo Y55s 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/your-ultimate-guide-to-get-and-set-up-epson-xp-410-printing-drivers-for-windows-pcs/"><u>Your Ultimate Guide to Get and Set Up Epson XP-410 Printing Drivers for Windows PCs</u></a></li>
</ul></div>

