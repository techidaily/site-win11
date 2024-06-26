---
title: Altering Network Addresses on Win11
date: 2024-06-25T09:43:39.991Z
updated: 2024-06-26T09:43:39.991Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Altering Network Addresses on Win11
excerpt: This Article Describes Altering Network Addresses on Win11
keywords: Win11 IP Change,Win11 Router Update,Network Adjustment Win11,Win11 MAC Alteration,Windows IP Address Editing,Win11 Gateway Reconfiguration,Win11 DHCP Modification
thumbnail: https://thmb.techidaily.com/cd939fa7a6d55f7872fb793de3dd6a0a1cf42f10f319881184a8db53e138fd0a.jpg
---

## Altering Network Addresses on Win11

 Devices in a subnetwork have IP addresses that begin with the same prefix. The length of this prefix is different for different devices—it depends on the network size, whose length is identified using the subnet mask.

 While troubleshooting network issues, you must ensure that the subnet mask is correct. So, we'll share how to find and change the subnet in Windows 11.

## How to Find the Subnet Mask in Windows 11

 The easiest way to find the subnet mask in Windows 11 is through the[Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) or Windows PowerShell. To find it using the Command Prompt, follow the steps below:

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
<li><a href="https://win11.techidaily.com/unlock-full-control-of-windows-panel-settings/"><u>Unlock Full Control of Windows Panel Settings</u></a></li>
<li><a href="https://win11.techidaily.com/eradicate-stranded-status-from-xbox-console-experience-on-pc/"><u>Eradicate ‘Stranded’ Status From Xbox Console Experience on PC</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-stopping-bsod-from-vmware-on-windows-11/"><u>Strategies for Stopping BSOD From VMware on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-cortana-integration-vivetool-approach/"><u>Optimizing Cortana Integration: ViveTool Approach</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-faulty-m365-functionality-code-30015-26/"><u>Disabling Faulty M365 Functionality: Code 30015-26</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-strategies-for-windows-11-cc-issues/"><u>Quick-Fix Strategies for Windows 11 CC Issues</u></a></li>
<li><a href="https://win11.techidaily.com/boost-windows-11-search-11-tricks-for-a-functional-bar/"><u>Boost Windows 11 Search: 11 Tricks for a Functional Bar</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-crafting-your-gaming-channel-on-youtube/"><u>2024 Approved  Crafting Your Gaming Channel on YouTube</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-from-noise-to-masterpiece-10-glitch-art-video-editing-apps-for-mobile-devices-for-2024/"><u>New From Noise to Masterpiece 10 Glitch Art Video Editing Apps for Mobile Devices for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-crafting-allure-in-online-visuals-for-beauty/"><u>[Updated] 2024 Approved  Crafting Allure in Online Visuals for Beauty</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-asus-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Asus?</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-unlocking-your-gaming-potential-the-complete-guide-to-getting-disconitro/"><u>[Updated] Unlocking Your Gaming Potential  The Complete Guide to Getting DiscoNitro</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-art-of-collaborative-marketing-on-youtube/"><u>[Updated] The Art of Collaborative Marketing on YouTube</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-transparency-in-tracking-youtube-viewers/"><u>[New] Transparency in Tracking YouTube Viewers</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/med-dialogue-scribe-for-2024/"><u>Streamed Dialogue Scribe for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-finding-free-music-a-producers-handbook/"><u>2024 Approved  Finding Free Music  A Producer's Handbook</u></a></li>
</ul></div>
