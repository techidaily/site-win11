---
title: Easy-to-Understand Guide for Extracting IP/MAC Addresses
date: 2024-10-13T18:58:52.204Z
updated: 2024-10-15T16:40:04.999Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Easy-to-Understand Guide for Extracting IP/MAC Addresses
excerpt: This Article Describes Easy-to-Understand Guide for Extracting IP/MAC Addresses
keywords: IP Address Basics,MAC Address Retrieval,Network Device Identification,IP/MAC Address Extraction,Locate Devices by Address,Accessing IP Info,Finding MAC Numbers
thumbnail: https://thmb.techidaily.com/20e687e989a89b1dd45743ceb6d6d3c635644bf241cd4154d769e7b945709de7.jpg
---

## Easy-to-Understand Guide for Extracting IP/MAC Addresses

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947750/11832" target="_top" id="947750">
  <img src="//a.impactradius-go.com/display-ad/11832-947750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947750/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://bluettifr.pxf.io/c/5597632/2145079/17095" target="_top" id="2145079">
  <img src="//a.impactradius-go.com/display-ad/17095-2145079" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettifr.pxf.io/i/5597632/2145079/17095" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043662/7443" target="_top" id="2043662">
  <img src="//a.impactradius-go.com/display-ad/7443-2043662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043662/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/rom-scribbles-to-spectacle-personalized-effect-crafting/"><u>[New] From Scribbles to Spectacle Personalized Effect Crafting</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-discovering-the-finest-mac-screen-capture-software/"><u>[Updated] In 2024, Discovering the Finest Mac Screen Capture Software</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-spotifys-marketplace-for-ultimate-ad-success/"><u>[Updated] Mastering Spotify's Marketplace for Ultimate Ad Success</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/apex-4k-screen-recorder-options-analysis-for-2024/"><u>Apex 4K Screen Recorder Options Analysis for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/conquer-clutter-a-fast-track-to-a-pristine-win11/"><u>Conquer Clutter: A Fast-Track to a Pristine Win11</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-controlled-access-a-step-by-step-for-windows-10-and-11/"><u>Enabling Controlled Access: A Step-by-Step for Windows 10 & 11</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/everything-you-need-to-know-about-the-popular-netflix-entertainment-hub/"><u>Everything You Need to Know About the Popular Netflix Entertainment Hub</u></a></li>
<li><a href="https://driver-error.techidaily.com/fixing-the-gtx-warton-950-code-43-problem-in-windows-11-comprehensive-guide/"><u>Fixing the GTX Warton 950 'Code 43' Problem in Windows 11 - Comprehensive Guide</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/maximizing-visibility-a-comprehensive-guide-to-yt-gaming-hashes/"><u>Maximizing Visibility A Comprehensive Guide to YT Gaming Hashes</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-windows-11-calculator-unlock/"><u>Quick Tips: Windows 11 Calculator Unlock</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-admin-controlled-features-in-windows-11-systems/"><u>Resetting Admin-Controlled Features in Windows 11 Systems</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/resolve-your-iphone-12-pro-max-keeps-asking-for-outlook-password-by-drfone-ios/"><u>Resolve Your iPhone 12 Pro Max Keeps Asking for Outlook Password</u></a></li>
<li><a href="https://app-tips.techidaily.com/revolutionizing-system-administration-how-red-hat-integrates-ai-for-enhanced-efficiency/"><u>Revolutionizing System Administration: How Red Hat Integrates AI for Enhanced Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/the-pros-guide-to-mastering-20-windows-cmd-commands/"><u>The Pro's Guide to Mastering 20 Windows CMD Commands</u></a></li>
</ul></div>

