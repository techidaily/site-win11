---
title: "Mastering IP Configuration: Windows 11 Focus"
date: 2024-11-30T10:40:34.197Z
updated: 2024-12-07T01:46:29.565Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering IP Configuration: Windows 11 Focus"
excerpt: "This Article Describes Mastering IP Configuration: Windows 11 Focus"
keywords: Win11_IPSetup,ConfigWindows11,IPConfigWin11,SetupNetConfig,NetIP11Mastery,WindowsNetSetup,IPConfigurationWin
thumbnail: https://thmb.techidaily.com/57dbc57b52c40c100c33b010fd03c7c914f04eea27a15b8c369fc3e51785f1d6.jpg
---

## Mastering IP Configuration: Windows 11 Focus

 Devices in a subnetwork have IP addresses that begin with the same prefix. The length of this prefix is different for different devices—it depends on the network size, whose length is identified using the subnet mask.

 While troubleshooting network issues, you must ensure that the subnet mask is correct. So, we'll share how to find and change the subnet in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Find the Subnet Mask in Windows 11

 The easiest way to find the subnet mask in Windows 11 is through the[Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) or Windows PowerShell. To find it using the Command Prompt, follow the steps below:

1. Press the**Win** key to launch the Start Menu.
2. In the search bar, type**Command Prompt** and choose the**Run as administrator** option from the right pane.
3. In the elevated Command Prompt window, type**ipconfig /all** and press Enter. This command will display all the important details about the network your computer is connected to, including the subnet mask.
4. Scroll and look for**Subnet Mask.** It'll be under the**Wireless LAN adapter Wi-Fi** section.  
![Finding the Subnet mask in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/finding-the-subnet-mask.jpg)

 The steps to do it using Windows PowerShell are similar to the Command Prompt. To do it,[open Windows PowerShell with admin rights](https://www.makeuseof.com/windows-11-powershell-administrator/) , type the ipconfig /all command, and press Enter.

 In the result that appears, you can see the subnet mask under the Wireless LAN adapter Wi-Fi section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Change the Subnet Mask in Windows 11

 Now that you know how to find the subnet mask on your computer, let's check out how to change it.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Change the Subnet Mask Using the Control Panel

 The Control Panel is the go-to place to configure window settings and make changes to your device. To use it to change the subnet mask, follow the below instructions:

1. Press the Win key, type**Control Panel** in the search bar, and press Enter.
2. Click the drop-down icon next to**View by** and choose**Large icons.**
3. Choose**Network and Internet** , and then select**Network and Sharing Center** in the following window.
4. Click on your network next to**Connections.**  
![Network name in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-name.jpg)
5. Choose**Properties** from the window that appears.
6. Select the IP version you're using. For instance, if you're using IPv4, select**Internet Protocol Version 4 (TCP/IPv4)** and click the**Properties** button.  
![IPv4 properties option in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv4-properties.jpg)
7. Select the**Use the following address** option and enter the details.  
![Changing the Subnet Mask in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/changing-the-subnet-mask.jpg)
8. Click**OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-files.techidaily.com/new-2024-approved-10plus-must-know-tactics-for-selecting-optimal-cricket-broadcasts/"><u>[New] 2024 Approved 10+ Must-Know Tactics for Selecting Optimal Cricket Broadcasts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-ultimate-guide-to-laughing-photo-editing-tools-iosandroid/"><u>[New] In 2024, Ultimate Guide to Laughing Photo Editing Tools (iOS/Android)</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-4k-clarity-comparison-projectors-vs-traditional-televisions/"><u>[Updated] 4K Clarity Comparison Projectors vs Traditional Televisions</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-navigating-the-new-era-top-tier-vr-exercise-machines-for-2024/"><u>[Updated] Navigating the New Era Top-Tier VR Exercise Machines for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-corrupted-file-on-windows-a-step-by-step-approach/"><u>How To Resolve 'Corrupted File' On Windows: A Step-by-Step Approach</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-analyzing-multi-angle-video-technology-trends-today/"><u>In 2024, Analyzing Multi-Angle Video Technology Trends Today</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-save-instastories-infinite-the-liberation-app/"><u>In 2024, Save InstaStories Infinite The Liberation App</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-asus-rog-phone-8-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost Asus ROG Phone 8 Device</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-oppo-find-n3-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Oppo Find N3 Device</u></a></li>
<li><a href="https://solve-news.techidaily.com/mov-to-h2-64-conversion-step-by-step-instructions-for-optimal-video-quality/"><u>MOV to H.2 64 Conversion: Step-by-Step Instructions for Optimal Video Quality</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-the-steps-for-kali-linux-on-your-windows-desktop/"><u>Navigate the Steps for Kali Linux on Your Windows Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-xps-problematic-error-x80300024/"><u>Overcoming Windows XP's Problematic Error X80300024</u></a></li>
<li><a href="https://win11.techidaily.com/overhauling-deactivated-coolant-regulation-mechanism/"><u>Overhauling Deactivated Coolant Regulation Mechanism</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-in-store-purchase-rates-on-microsoft-platform/"><u>Streamline Your In-Store Purchase Rates on Microsoft Platform</u></a></li>
<li><a href="https://win11.techidaily.com/taking-coding-to-new-heights-maximizing-use-of-dev-drive-in-win11/"><u>Taking Coding to New Heights: Maximizing Use of Dev Drive in Win11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-next-revolution-in-smartphones-samsungs-upcoming-galaxy-z-fold-7-price-guide-release-info-and-rumored-features/"><u>The Next Revolution in Smartphones: Samsung's Upcoming Galaxy Z Fold 7 Price Guide, Release Info & Rumored Features</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-stopping-windows-safe-screen-change/"><u>Tips for Stopping Windows Safe Screen Change</u></a></li>
<li><a href="https://win11.techidaily.com/top-10-solutions-for-non-responsive-wireless-mice-windows/"><u>Top 10 Solutions for Non-Responsive Wireless Mice (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-windows-count-for-each-app-opener/"><u>Turn Off Windows Count for Each App Opener</u></a></li>
</ul></div>

