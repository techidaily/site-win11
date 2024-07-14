---
title: Subnet Adjustment for Win11 Users
date: 2024-07-13T10:58:35.110Z
updated: 2024-07-14T10:58:35.110Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Subnet Adjustment for Win11 Users
excerpt: This Article Describes Subnet Adjustment for Win11 Users
keywords: Win11 Subnet Change,Net Settings Win11,Win11 IP Configuration,Network Setup Win11,Win11 Adjust Networking,Win11 VLAN Modification,Win11 IP Assignment
thumbnail: https://thmb.techidaily.com/a9e60c359d76678f8aad5193db4d1713b6255faff22e113abbe3abedfe2cc94d.jpeg
---

## Subnet Adjustment for Win11 Users

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
<li><a href="https://win11.techidaily.com/resolving-code-0xc0000142-in-winos/"><u>Resolving Code 0XC0000142 in WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-11-overcoming-5ghz-wi-fi-barriers/"><u>Breaking Down Windows 11: Overcoming 5GHz Wi-Fi Barriers</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-an-unadulterated-system-restart-in-windows-11/"><u>Achieving an Unadulterated System Restart in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/smart-pc-enhancement-add-gmail-bar-to-taskbar-border/"><u>Smart PC Enhancement: Add Gmail Bar to Taskbar Border</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-line-up-of-artistic-software-for-windows-10/"><u>The Ultimate Line-Up of Artistic Software for Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/ancestry-unveiled-7-enduring-features-of-windows-11/"><u>Ancestry Unveiled: 7 Enduring Features of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-system-use-with-6-advanced-trackers-for-win-users/"><u>Streamline System Use with 6 Advanced Trackers for Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-msstore-from-error-0x0-issue-in-windows-os/"><u>Unblocking MsStore From Error 0X0 Issue in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-hidden-taskbar-while-running-full-screen-edges/"><u>Unveiling Hidden Taskbar While Running Full Screen Edges</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-professional-video-editor-for-mac-os-unleash-your-creativity/"><u>Updated 2024 Approved Professional Video Editor for Mac OS Unleash Your Creativity</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-recurring-audiotrack-flaw-the-fix-for-code-9999/"><u>Tackling Windows' Recurring Audiotrack Flaw: The Fix for Code 9999</u></a></li>
<li><a href="https://win11.techidaily.com/evaluating-the-disparity-between-remote-windows-upgrades-and-purchases/"><u>Evaluating the Disparity Between Remote Windows Upgrades & Purchases</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-errors-with-proper-use-of-winservicesexe/"><u>Avoiding Errors with Proper Use of Winservices.exe</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-huawei-nova-y71-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Huawei Nova Y71 | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/how-to-compose-your-own-videos-with-melodies-without-spending-a-penny/"><u>How to Compose Your Own Videos with Melodies, Without Spending a Penny</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-from-novice-to-noteworthy-a-step-by-step-guide-for-verified-partnership-for-2024/"><u>[Updated] From Novice to Noteworthy  A Step-by-Step Guide for Verified Partnership for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/sketch-mastery-for-desktop-users-in-windows-11/"><u>Sketch Mastery for Desktop Users in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-vivo-v27-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Vivo V27 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win11-fixing-persistent-read-only-folders/"><u>Win11: Fixing Persistent Read-Only Folders</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-sluggish-windows-printer/"><u>Troubleshoot Sluggish WIndows Printer</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-grouped-taskbar-symbols-on-windows-11/"><u>Clearing Grouped Taskbar Symbols on Windows 11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713942698073-camtasia-vs-final-cut-pro-for-2024/"><u>Camtasia vs Final Cut Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-science-behind-windows-11s-streamlined-file-safety-measures/"><u>The Science Behind Windows 11’S Streamlined File Safety Measures</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-windows-11s-potential-with-latest-patch-details/"><u>Unlocking Windows 11'S Potential with Latest Patch Details</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-and-configuring-windows-data-sources-by-odbc/"><u>Accessing and Configuring Windows Data Sources by ODBC</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-file-damaged-message-error-0x80070570-in-windows-oses/"><u>Eliminating 'File Damaged' Message (Error 0X80070570) in Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/commanding-control-navigating-the-windows-print-hub/"><u>Commanding Control: Navigating the Windows Print Hub</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-digital-disappointment-unexpected-deletion/"><u>[Updated] Digital Disappointment  Unexpected Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategy-against-c0000022-system-collapse/"><u>Winning Strategy Against C0000022 System Collapse</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-honor-v-purse-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Honor V Purse to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/win11-quick-fixes-for-photoshop-not-launching/"><u>Win11: Quick Fixes for Photoshop Not Launching</u></a></li>
<li><a href="https://win11.techidaily.com/the-leaders-small-computers-running-windows/"><u>The Leaders: Small Computers Running Windows</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-sound-error-on-audacity-in-win1011/"><u>Resolving Sound Error on Audacity in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-for-bulk-folder-formation-in-windows-1011/"><u>Efficient Methods for Bulk Folder Formation in Windows 10/11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-demystifying-facebooks-blue-image-symbol/"><u>[Updated] 2024 Approved  Demystifying Facebook's Blue Image Symbol</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-short-form-video-rivals-can-likes-overtake-tiktoks-global-fanbase/"><u>[Updated] In 2024, Short-Form Video Rivals  Can Likes Overtake TikTok’s Global Fanbase?</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-d3d11-gpu-error-on-windows-11-and-10/"><u>Troubleshooting D3D11 GPU Error on Windows 11 & 10</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-screens-boost-your-pcs-performance-with-hotkeys/"><u>Streamlined Screens: Boost Your PC's Performance with Hotkeys</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-the-easiest-way-to-edit-gopro-videos-a-beginners-guide/"><u>New The Easiest Way to Edit GoPro Videos A Beginners Guide</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-bsod-traces-within-windows-108/"><u>Understanding BSOD Traces Within Windows 10/8</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-studio-2-the-artists-dream-device-unveiled/"><u>Surface Laptop Studio 2: The Artist's Dream Device Unveiled</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Samsung Galaxy S24 | Dr.fone</u></a></li>
</ul></div>
