---
title: How to Find Your IP or MAC Address on Windows Using PowerShell
date: 2024-10-26T23:12:16.082Z
updated: 2024-11-02T04:49:40.312Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Find Your IP or MAC Address on Windows Using PowerShell
excerpt: This Article Describes How to Find Your IP or MAC Address on Windows Using PowerShell
keywords: Windows IP Finder,PowerShell IP Location,MAC Address Powershell,Find Windows MAC,Locate IP in Win,Windows Address Detect,PowerShell Network ID
thumbnail: https://thmb.techidaily.com/e9711d2ba9e06d496671fabcb5c03dc2cfd9b4b1eb26d7f5f5a9a68662ceb542.jpg
---

## How to Find Your IP or MAC Address on Windows Using PowerShell

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
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148634/16836" target="_top" id="2148634">
  <img src="//a.impactradius-go.com/display-ad/16836-2148634" border="0" alt="https://techidaily.com" width="80" height="31"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148634/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137378/7443" target="_top" id="2137378">
  <img src="//a.impactradius-go.com/display-ad/7443-2137378" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://twitter-clips.techidaily.com/new-in-2024-tweeting-visual-content-from-video-to-gif-transformation/"><u>[New] In 2024, Tweeting Visual Content From Video to GIF Transformation</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-ranked-best-voice-change-software-echo-magic-edition-for-2024/"><u>[New] Ranked Best Voice Change Software Echo Magic Edition for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-synchronizing-success-brand-partnerships-on-youtube-channel/"><u>[Updated] 2024 Approved Synchronizing Success Brand Partnerships on YouTube Channel</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-maximizing-videography-with-youtubes-creative-commons/"><u>[Updated] Maximizing Videography with YouTube's Creative Commons</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-instagrams-essential-edits-the-definitive-list-of-apps/"><u>2024 Approved Instagram's Essential Edits The Definitive List of Apps</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-for-restoring-windows-hello-fingerprint-functionality/"><u>7 Key Steps for Restoring Windows Hello Fingerprint Functionality</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/p-dive-into-the-world-of-youtubes-minis-for-2024/"><u>A Deep Dive Into the World of Youtube's Minis for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-dawn-of-taskbars-in-windows-11-proposing-six-crucial-changes-for-enhanced-ux/"><u>A New Dawn of Taskbars in Windows 11: Proposing Six Crucial Changes for Enhanced UX</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-powershell-with-admin-privileges-on-windows-11/"><u>Accessing PowerShell with Admin Privileges on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-smooth-mouse-movement-on-modern-windows-oses/"><u>Achieving Smooth Mouse Movement on Modern Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/behind-the-veil-of-user-interface-accessing-windows-hidden-personality-editor/"><u>Behind the Veil of User Interface: Accessing Windows’ Hidden Personality Editor</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-wake-up-alerts-win-1011-full-charge-ding/"><u>Boosting Wake-Up Alerts: Win 10/11 FULL CHARGE DING</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-from-poco-c50-by-drfone-android/"><u>How to Bypass FRP from Poco C50?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/network-locked-sim-card-inserted-on-your-samsung-galaxy-a34-5g-phone-unlock-it-now-by-drfone-android/"><u>Network Locked SIM Card Inserted On Your Samsung Galaxy A34 5G Phone? Unlock It Now</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/understanding-googles-ai-gemini-vision-workings-and-development/"><u>Understanding Google's AI Gemini: Vision, Workings & Development</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    