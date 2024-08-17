---
title: Subnet Adjustment for Win11 Users
date: 2024-08-15T23:37:28.163Z
updated: 2024-08-16T23:37:28.163Z
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

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
### 1\. Change the Subnet Mask Using the Windows Settings

 The settings menu is the central hub of a Windows operating system. It's a place to configure different settings of your computer and manage the network. You can also use it to change the subnet mask.

Here's how to do it:

1. [Open the Windows Systems Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and choose**Network & internet** from the left panel.
2. Select**Wi-Fi,** and then choose your network in the following window.
3. Click the**Edit** button next to the**IP assignment** option.  
![Edit button in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/edit-button.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
4. In the prompt that crops up, click on the drop-down icon and choose**Manual.**
5. Enable the toggle next to the IP version you're using.
6. Enter the details, including the subnet mask, and click**Save.**  
![Entering the new Subnet Mask in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/entering-the-new-subnet-mask.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
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
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
7. Select the**Use the following address** option and enter the details.  
![Changing the Subnet Mask in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/changing-the-subnet-mask.jpg)
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-audio-ambiance-weaving-music-into-instagram-moments/"><u>[New] 2024 Approved  Audio Ambiance  Weaving Music Into Instagram Moments</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-clipmaster-software/"><u>[New] 2024 Approved  ClipMaster Software</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-iphone-7-proven-strategies-for-screen-capture/"><u>[New] 2024 Approved  IPhone 7  Proven Strategies for Screen Capture</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-mastering-transitions-in-audition-fade-in-basics-for-2024/"><u>[New] Mastering Transitions in Audition  Fade-In Basics for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-perfecting-your-tone-techniques-for-zoom-podcast-sessions/"><u>[Updated] In 2024, Perfecting Your Tone  Techniques for ZOOM Podcast Sessions</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-tailored-transitions-5-innovative-techniques-for-video-length-optimization-on-vimeo/"><u>[Updated] Tailored Transitions  5 Innovative Techniques for Video Length Optimization on Vimeo</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-pathway-errors-with-windows-devices/"><u>Addressing Pathway Errors with Windows Devices</u></a></li>
<li><a href="https://win-dash.techidaily.com/boost-your-mixing-table-performance-free-download-of-m-audio-fast-track-ultra-driver/"><u>Boost Your Mixing Table Performance – Free Download of M-Audio Fast Track Ultra Driver</u></a></li>
<li><a href="https://driver-install.techidaily.com/bypass-usb-issues-in-win-solutions-available/"><u>Bypass USB Issues in WIN - Solutions Available</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-reclaiming-faulty-usb-connectivity-windows/"><u>Comprehensive Guide to Reclaiming Faulty USB Connectivity, Windows</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-excessive-cpu-consumption-by-dropbox-on-windows-pcs/"><u>Decreasing Excessive CPU Consumption by Dropbox on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-differences-of-windows-terminal-vs-powershell/"><u>Dissecting the Differences of Windows Terminal Vs. PowerShell</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-remedies-to-address-instantaneous-failure-when-adding-a-folder-in-the-windows-onedrive-environment/"><u>Efficient Remedies to Address Instantaneous Failure when Adding a Folder in the Windows OneDrive Environment</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-steam-sound-fidelity/"><u>Enhancing Windows Steam Sound Fidelity</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-ai-synergy-with-windows-11-features/"><u>Exploring AI Synergy with Windows 11 Features</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-d3d11-hardware-error-in-w11w10-environments/"><u>Fixing D3D11 Hardware Error in W11/W10 Environments</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-err0r-code-e1-in-w10w11/"><u>Fixing Err0r: Code E1 in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/getting-started-with-msoffice-on-win11-os/"><u>Getting Started with MSOffice on Win11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-link-your-windows-product-key-to-a-microsoft-account/"><u>How to Link Your Windows Product Key to a Microsoft Account</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-map-a-network-drive-in-windows-11/"><u>How to Map a Network Drive in Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-expert-tips-to-zoom-in-on-your-favorite-roblox-locales/"><u>In 2024, Expert Tips to Zoom In on Your Favorite Roblox Locales</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlock-your-disabled-apple-iphone-15-pro-without-itunes-in-5-ways-drfone-by-drfone-ios/"><u>In 2024, Unlock Your Disabled Apple iPhone 15 Pro Without iTunes in 5 Ways | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-dont-make-these-top-8-mistakes/"><u>Mastering Windows 11: Don't Make These Top 8 Mistakes</u></a></li>
<li><a href="https://win11.techidaily.com/merging-windows-credentials-with-microsoft-identity-hub/"><u>Merging Windows Credentials with Microsoft Identity Hub</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-nuances-of-color-management-in-windows/"><u>Navigating the Nuances of Color Management in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-erroneous-non-existing-device-alert-on-win-11/"><u>Overcoming Erroneous Non-Existing Device Alert on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-failed-admin-mode-execution-in-windows-console/"><u>Overcoming Failed Admin Mode Execution in Windows Console</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-and-enhance-desktop-usage-by-adding-win-11-widgets/"><u>Personalize and Enhance Desktop Usage by Adding Win 11 Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/prevent-windows-from-logging-app-starts/"><u>Prevent Windows From Logging App Starts</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/prime-business-sky-storage-choice-for-2024/"><u>Prime Business Sky-Storage Choice for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-synapse-seamlessly-on-windows-1110-systems/"><u>Reinstating Synapse Seamlessly on Windows 11/10 Systems</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/restoring-correct-self-image-amidst-message-distortion/"><u>Restoring Correct Self-Image Amidst Message Distortion</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-full-functionality-to-windows-tablet-gestures/"><u>Restoring Full Functionality to Windows Tablet Gestures</u></a></li>
<li><a href="https://win11.techidaily.com/solving-non-responsive-media-on-pc-guide/"><u>Solving Non-Responsive Media on PC: Guide</u></a></li>
<li><a href="https://win11.techidaily.com/surging-downloads-overcome-the-01kbs-stall-on-windows/"><u>Surging Downloads: Overcome the 0.1KB/S Stall on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-overlooked-duo-of-windows-monitoring-metrics/"><u>The Overlooked Duo of Windows Monitoring Metrics</u></a></li>
<li><a href="https://win11.techidaily.com/the-quintessential-4-password-sentinels-of-windows-11-era/"><u>The Quintessential 4 Password Sentinels of Windows 11 Era</u></a></li>
<li><a href="https://win11.techidaily.com/the-silent-key-syndrome-cure-for-muted-mouse-clicks/"><u>The Silent Key Syndrome: Cure for Muted Mouse Clicks</u></a></li>
<li><a href="https://win11.techidaily.com/turbocharge-your-printer-fast-windows-fixes/"><u>Turbocharge Your Printer: Fast Windows Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-key-differences-between-windows-terminal-and-powershell/"><u>Understanding Key Differences Between Windows Terminal and PowerShell</u></a></li>
<li><a href="https://driver-download.techidaily.com/xbox-360-controllers-get-the-newest-drivers-for-seamless-gaming-experience/"><u>Xbox 360 Controllers: Get the Newest Drivers for Seamless Gaming Experience</u></a></li>
</ul></div>
