---
title: Adjusting Network Settings with Precision (Win11)
date: 2024-07-13T11:25:54.068Z
updated: 2024-07-14T11:25:54.068Z
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
<li><a href="https://youtube-videos.techidaily.com/avoid-mainstream-underrated-movies-of-the-year-for-2024/"><u>Avoid Mainstream  Underrated Movies of the Year for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-vm-performance-with-these-six-simple-steps/"><u>Boost Your VM Performance with These Six Simple Steps</u></a></li>
<li><a href="https://win11.techidaily.com/bluescreenview-explained-with-ease-and-clarity/"><u>BlueScreenView Explained with Ease and Clarity</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-master-downloader-facebook-and-firefox-integration/"><u>In 2024, Master Downloader  Facebook & FireFox Integration</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-xffffeee-error-from-your-inkjet-printer/"><u>Banishing XFFFFEEE Error From Your Inkjet Printer</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-steam-application-icon-absence/"><u>Avoiding Steam Application Icon Absence</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-orchestrate-audio-amidst-slides/"><u>In 2024, Orchestrate Audio Amidst Slides</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-ultimate-resource-for-mac-users-unlocking-preview-capabilities/"><u>In 2024, The Ultimate Resource for Mac Users  Unlocking Preview Capabilities</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-building-brand-presence-through-strategic-smm/"><u>[New] Building Brand Presence Through Strategic SMM</u></a></li>
<li><a href="https://win11.techidaily.com/beat-the-slowness-essential-tricks-for-windows-11s-pace/"><u>Beat the Slowness: Essential Tricks for Windows 11'S Pace</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-stagnant-windows-update-status/"><u>Break Free From Stagnant Windows Update Status</u></a></li>
<li><a href="https://win11.techidaily.com/bootable-windows-11-usb-setup-a-quick-easy-guide-to-3-methods/"><u>Bootable Windows 11 USB Setup: A Quick, Easy Guide to 3 Methods</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-device-naming-disputes-on-your-computer-network/"><u>Avoiding Device Naming Disputes on Your Computer Network</u></a></li>
<li><a href="https://win11.techidaily.com/blending-gmail-with-outlook-on-windows-comprehensive-guide/"><u>Blending Gmail with Outlook on Windows: Comprehensive Guide</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-picpartition-testimonials/"><u>[Updated] In 2024, PicPartition Testimonials</u></a></li>
<li><a href="https://win11.techidaily.com/batch-transformation-heic-to-jpeg-in-windows/"><u>Batch Transformation: HEIC to JPEG in Windows</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-composing-captivating-cinema-trailers/"><u>2024 Approved  Composing Captivating Cinema Trailers</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-firewall-restrictions-allow-chrome-network-entry-in-windows/"><u>Breaking Firewall Restrictions: Allow Chrome Network Entry in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-zoom-crashes-windows-error-1132-fix/"><u>Banishing Zoom Crashes: Windows Error 1132 Fix</u></a></li>
<li><a href="https://win11.techidaily.com/awaken-your-windows-11-to-create-stunning-ai-images-with-paint-tool-sai/"><u>Awaken Your Windows 11 to Create Stunning AI Images with Paint Tool SAI</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-guide-on-how-to-change-your-apple-id-email-address-on-iphone-11-pro-by-drfone-ios/"><u>In 2024, Guide on How To Change Your Apple ID Email Address On iPhone 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/bitlock-less-windows-defense-tactics-4-suggestions/"><u>BitLock-Less Windows Defense Tactics: 4 Suggestions</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-unending-enter-password-interruptions-in-windows/"><u>Avoiding Unending Enter Password Interruptions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/adjust-screen-direction-on-windows-pc/"><u>Adjust Screen Direction on Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-screen-legibility-win11-scaling-guide/"><u>Boosting Screen Legibility: Win11 Scaling Guide</u></a></li>
<li><a href="https://win11.techidaily.com/black-out-bliss-with-microsofts-basic-brush/"><u>Black-Out Bliss with Microsoft's Basic Brush</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-endless-eradication-guide-bypassing-youtubes-snappy-content/"><u>[New] In 2024, Endless Eradication Guide  Bypassing YouTube's Snappy Content</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-how-to-disable-the-pesky-epic-games-hub/"><u>Break Free: How to Disable the Pesky Epic Games Hub</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-simplified-social-syncing-from-instagram-to-facebook/"><u>[Updated] In 2024, Simplified Social Syncing  From Instagram To Facebook</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-icloud-activation-lock-with-imei-code-on-your-apple-iphone-x-by-drfone-ios/"><u>In 2024, Bypass iCloud Activation Lock with IMEI Code On your Apple iPhone X</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-best-free-online-transcribers-convert-your-audio-files-with-ease/"><u>Updated Best Free Online Transcribers Convert Your Audio Files with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/beware-the-traps-in-budget-friendly-windows-license-purchases/"><u>Beware the Traps in Budget-Friendly Windows License Purchases</u></a></li>
<li><a href="https://screen-recording.techidaily.com/the-3-essential-voice-logging-tactics-for-ipad/"><u>The 3 Essential Voice Logging Tactics for iPad</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-the-ultimate-youtube-conclusion-handbook-creators-choice/"><u>[New] The Ultimate YouTube Conclusion Handbook [Creators' Choice]</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-windows-11-shutdown-time-for-ongoing-tasks/"><u>Adjusting Windows 11 Shutdown Time for Ongoing Tasks</u></a></li>
</ul></div>
