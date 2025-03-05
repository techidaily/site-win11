---
title: Adjusting Network Settings with Precision (Win11)
date: 2025-03-02T22:58:59.645Z
updated: 2025-03-05T00:19:28.228Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Adjusting Network Settings with Precision (Win11)
excerpt: This Article Describes Adjusting Network Settings with Precision (Win11)
keywords: Win11 Network Tweak,Precision Setup Win11,Windows Network Adjustment,Win11 NetConfigurator,Accurate Win11 Settings,Exact Win11 Connect,Optimal Win11 Links
thumbnail: https://thmb.techidaily.com/92d935200679b107d6e949886541d1fff9656f8b1ef1aeadb85afda988825dc9.jpg
---

## Adjusting Network Settings with Precision (Win11)

 Devices in a subnetwork have IP addresses that begin with the same prefix. The length of this prefix is different for different devices—it depends on the network size, whose length is identified using the subnet mask.

 While troubleshooting network issues, you must ensure that the subnet mask is correct. So, we'll share how to find and change the subnet in Windows 11.

## How to Find the Subnet Mask in Windows 11

 The easiest way to find the subnet mask in Windows 11 is through the [Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) or Windows PowerShell. To find it using the Command Prompt, follow the steps below:

1. Press the**Win** key to launch the Start Menu.
2. In the search bar, type**Command Prompt** and choose the**Run as administrator** option from the right pane.
3. In the elevated Command Prompt window, type**ipconfig /all** and press Enter. This command will display all the important details about the network your computer is connected to, including the subnet mask.
4. Scroll and look for**Subnet Mask.** It'll be under the**Wireless LAN adapter Wi-Fi** section.  
![Finding the Subnet mask in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/finding-the-subnet-mask.jpg)

 The steps to do it using Windows PowerShell are similar to the Command Prompt. To do it,[open Windows PowerShell with admin rights](https://www.makeuseof.com/windows-11-powershell-administrator/) , type the ipconfig /all command, and press Enter.

 In the result that appears, you can see the subnet mask under the Wireless LAN adapter Wi-Fi section.

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

### 3\. Change the Subnet Mask Using Windows PowerShell

 Windows PowerShell is also one of the places from where you can change the subnet mask in Windows 11\. Here's how to do it:

1. Open Windows PowerShell with admin rights, type the following command, and press Enter. This command will display all the network adapters installed on your device.  
`Get-NetAdapter -physical`
2. To change the subnet mask, type the following command and press Enter. Make sure to replace the "**ifIndex Number** " with the number associated with the network adapter whose subnet mask you want to change. And replace "**subnet prefix length** " with the new subnet prefix length you want.  
`Set-NetIPAddress -InterfaceIndex (ifIndex Number) -PrefixLength (subnet prefix length)`

 For instance, if the ifIndex Number is 3 and the new subnet prefix length you want is 24, then the command will be:

`Set-NetIPAddress -InterfaceIndex 3 -PrefixLength 24`

![Command to change the subnet mask in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-change-the-subnet-mask.jpg)

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
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-pro-editors-pathway-perfecting-video-for-instagram-on-final-cut-x/"><u>[Updated] 2024 Approved Pro Editor's Pathway Perfecting Video for Instagram on Final Cut X</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-cloud-economy-unveiling-best-deals-for-2024/"><u>[Updated] Cloud Economy Unveiling Best Deals for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-exploring-the-world-of-youtube-channel-naming-innovative-ideas-for-vloggers-and-filmmakers-no-more-than-156-characters/"><u>[Updated] Exploring the World of YouTube Channel Naming Innovative Ideas For Vloggers & Filmmakers (No More than 156 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-your-pcs-blue-screen-madness-in-windows-11/"><u>Eliminate Your PC's Blue Screen Madness in Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-se-2022-to-an-older-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone SE (2022) to an Older iOS Version? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ideal-mobile-platforms-android-plus-windows-pc-compatibility/"><u>Ideal Mobile Platforms: Android + Windows PC Compatibility</u></a></li>
<li><a href="https://win11.techidaily.com/improve-battery-awareness-enable-full-charge-warnings-on-windows-11/"><u>Improve Battery Awareness: Enable Full Charge Warnings on Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-file-not-writable-error-in-windows-os/"><u>Resolving 'File Not Writable' Error in Windows OS</u></a></li>
<li><a href="https://facebook.techidaily.com/top-social-network-cast-your-vote/"><u>Top Social Network: Cast Your Vote</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-how-to-pick-a-superior-photo-monopod-for-self-portraits/"><u>Ultimate Guide: How to Pick a Superior Photo Monopod for Self-Portraits</u></a></li>
</ul></div>

