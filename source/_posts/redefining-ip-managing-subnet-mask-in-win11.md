---
title: "Redefining IP: Managing Subnet Mask in Win11"
date: 2024-10-25T21:57:24.163Z
updated: 2024-11-02T05:27:46.784Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Redefining IP: Managing Subnet Mask in Win11"
excerpt: "This Article Describes Redefining IP: Managing Subnet Mask in Win11"
keywords: Win11 IP Management,Subnet Config Win11,Redefine IP Addressing,Win11 Network Setup,Advanced Win11 Mask,Subnet Mask Win11 Guide,IP Configuration Win11
thumbnail: https://thmb.techidaily.com/3b3b313aac4422406d268b9ec86a52f71522ac5dfd6eae7e41b861cd70dad021.png
---

## Redefining IP: Managing Subnet Mask in Win11

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129738/7443" target="_top" id="2129738">
  <img src="//a.impactradius-go.com/display-ad/7443-2129738" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Enable the toggle next to the IP version you're using.
6. Enter the details, including the subnet mask, and click**Save.**  
![Entering the new Subnet Mask in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/entering-the-new-subnet-mask.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1328683">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328683.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328683">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328683.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328683%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328683/15852" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/he-art-of-turning-youtube-media-on-its-head/"><u>[New] The Art of Turning YouTube Media on Its Head</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-ide-speed-and-productivity-for-developers-on-windows/"><u>Enhancing IDE Speed & Productivity for Developers on Windows</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/explore-the-finest-movie-series-youtubes-10-pack-no-cost-in-2024/"><u>Explore the Finest Movie Series YouTube's 10-Pack, No Cost, In 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-fix-iphone-x-unavailable-issue-with-ease-drfone-by-drfone-ios/"><u>How To Fix iPhone X Unavailable Issue With Ease | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-my-poco-f5-pro-5g-location-is-wrong-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix My Poco F5 Pro 5G Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-the-full-scale-of-precision-a-review-of-asus-pa32us-capabilities/"><u>In 2024, The Full Scale of Precision A Review of Asus PA32U's Capabilities</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-top-ranked-screen-recorder-for-seamless-youtubing/"><u>In 2024, Top-Ranked Screen Recorder for Seamless YouTubing</u></a></li>
<li><a href="https://hardware-help.techidaily.com/inside-the-world-of-computing-detailed-breakdowns-from-toms-systems/"><u>Inside the World of Computing: Detailed Breakdowns From Tom's Systems</u></a></li>
<li><a href="https://win-answers.techidaily.com/league-of-legends-errors-fast-fixes-for-rapid-restart/"><u>League of Legends Errors: Fast Fixes for Rapid Restart</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-system-restore-on-windows-for-past-fixes/"><u>Navigating System Restore on Windows for Past Fixes</u></a></li>
<li><a href="https://fox-useful.techidaily.com/solucion-urgente-liderando-la-busqueda-para-reobtener-tus-archivos-eliminados-por-el-onedrive/"><u>Solución Urgente: Liderando La Búsqueda Para Reobtener Tus Archivos Eliminados Por (El) OneDrive</u></a></li>
<li><a href="https://win11.techidaily.com/tailoring-functionalities-of-fn-keys-on-windows-11-devices/"><u>Tailoring Functionalities of FN Keys on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-restoring-integrity-in-the-windows-registry/"><u>The Ultimate Guide to Restoring Integrity in the Windows Registry</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-your-full-potential-with-network-traffic-insight-via-win11s-netstat/"><u>Unlock Your Full Potential with Network Traffic Insight via Win11's Netstat</u></a></li>
<li><a href="https://win11.techidaily.com/vivetool-breakdown-how-to-pre-emptive-access-updates/"><u>ViVeTool Breakdown: How to Pre-Emptive Access Updates</u></a></li>
</ul></div>

