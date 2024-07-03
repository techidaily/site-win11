---
title: "Finding Essential Data: Win PC IP & MAC via PowerShell"
date: 2024-06-25T11:30:34.341Z
updated: 2024-06-26T11:30:34.341Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Finding Essential Data: Win PC IP & MAC via PowerShell"
excerpt: "This Article Describes Finding Essential Data: Win PC IP & MAC via PowerShell"
keywords: Win PC IP Address,Mac IP Command,PowerShell IP Find,PC Network Info,IP Details Windows,OS X Net Data,PowerShell Network Query
thumbnail: https://thmb.techidaily.com/a0ea0929e49147a7aa2982696f1085c4ea3dc3044596db757054a8f03e6ab91e.jpg
---

## Finding Essential Data: Win PC IP & MAC via PowerShell

 Have you been facing some network or troubleshooting issues on your PC? Or maybe you simply need to fix your access control or networking problems caused by your device or hardware. In cases like this, knowing your MAC or IP address will come in handy.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

## How to Find Your IP or MAC Address on a Windows Using the PowerShell

 Figuring out your IP address using [PowerShell](https://www.makeuseof.com/what-is-windows-powershell/) is easy. Here's how you can get started:

1. Head to the **Start menu** search bar, type in 'powershell,' and select the best match.
2. Once the PowerShell is up, type in the following command and hit **Enter**:  
`Get-NetIPAddress <code class="language-powershell" lang="powershell">-AddressFamily IPV4`

 That's it; as soon as you type in this command, the PowerShell will give you the IPv4 addresses of all network adapters of your Windows system. As you can see below, you will get your PC's IP address, subnet mask, default gateway, etc.

![windows powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-3.jpg)

## Find the MAC Address on Your Windows

 Like your IP address, [finding out about your MAC address](https://www.makeuseof.com/how-to-find-mac-address-windows-11/) works somewhat similarly. Again, once you're inside the PowerShell, type in the following command on the shell and hit **Enter**:

`Get-NetAdapter`

 That's it; this command will give you the details about all the network adapters from your system, along with their MAC addresses. Look over at the "MacAddress" column, and you will get the address.

### An Alternate Way to Find the MAC Address on Windows

 While the "Get-NetAdapter" will work in most cases, we'd understand that if you'd want to try a different approach for any reason. In cases like that, the "ipconfig" command is your second-best bet.

 In fact, the "ipconfig" will give you all the information, which can make your screen unnecessarily complicated. So it's important that you filter out the fluff, and only get the information that you need. For that, add the "findstr "Description Physical"" section at the end of your command.

 Here's how you can do that:

`ipconfig /all | findstr "Description Physical"  
<img alt="windows powershell" height="665" src="https://static0.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-powershell-4.jpg" width="1200" />`

 Your adapter will be listed along with its MAC address, referenced by "Description" and "Physical Address".

## Finding Your IP or MAC Address on Windows PC

 So that's all about your IP or MAC address on your Windows PC. Type in the above commands, and you will get your MAC or IP addresses instantly. Of course, PowerShell is just one way of doing that. For instance, you can even find out your IP address on Windows with both settings menu and Command prompt. Knowing all the different methods, then, will come in handy in places like this.

 While other more straightforward methods exist, you can find your IP or MAC address on Windows using PowerShell. Let's find out how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/dxvk-uncovered-enhancing-win-based-gameplay-dynamics/"><u>DXVK Uncovered: Enhancing Win-Based Gameplay Dynamics</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-shared-connectivity-options-google-versus-windows/"><u>Exploring Shared Connectivity Options: Google Versus Windows</u></a></li>
<li><a href="https://win11.techidaily.com/rekindle-your-computers-potential-with-windows-11-via-to-go-and-rufus-path/"><u>Rekindle Your Computer's Potential with Windows 11, Via To Go & Rufus Path</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-art-of-app-migration-from-older-windows-versions/"><u>Unveiling the Art of App Migration From Older Windows Versions</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-seamless-link-for-windows-steam-streaming/"><u>Restoring Seamless Link for Windows Steam Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-product-id-from-windows-with-ms-online-service/"><u>Integrating Product ID From Windows with MS Online Service</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-repairing-code-0x0000004e-on-pcs/"><u>Step-by-Step: Repairing Code 0X0000004E on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-to-change-file-formats-on-pc/"><u>Expert Strategies to Change File Formats on PC</u></a></li>
<li><a href="https://win11.techidaily.com/three-simplified-steps-for-customizing-win11-ui/"><u>Three Simplified Steps for Customizing Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-correct-invalid-identifier-error-in-win11/"><u>Guide to Correct 'Invalid Identifier' Error in Win11</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-rapid-route-learning-the-ins-and-outs-of-insta-talks-for-2024/"><u>[Updated] Rapid Route  Learning the Ins and Outs of Insta Talks for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-ar-is-a-trend-these-days-here-you-can-browse-the-list-of-top-10-picks-for-ar-video-editing-apps/"><u>New 2024 Approved AR Is a Trend These Days. Here, You Can Browse the List of Top 10 Picks for AR Video Editing Apps</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-identify-high-end-filters-and-processors-that-eradicate-unwanted-sounds-from-audio-content/"><u>Updated Identify High-End Filters and Processors That Eradicate Unwanted Sounds From Audio Content</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-want-to-edit-video-with-sony-vegas-on-mac-but-it-only-available-on-windows-platform-below-are-the-best-alternatives-to-sony-vegas-pro-mac/"><u>New Want to Edit Video with Sony Vegas on Mac? But It only Available on Windows Platform, Below Are the Best Alternatives to Sony Vegas Pro Mac</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unite-auditory-elements-with-visuals-in-ppt/"><u>In 2024, Unite Auditory Elements with Visuals in PPT</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-twitters-best-binge-friends-amazon-primes-most-liked-shows-23/"><u>In 2024, Twitter's Best Binge-Friends  Amazon Prime's Most Liked Shows, '23</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-decoding-hashtags-role-in-elevating-your-youtube-gaming-experience-for-2024/"><u>[Updated] Decoding Hashtags' Role in Elevating Your YouTube Gaming Experience for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-maximizing-engagement-choosing-your-fb-video-direction/"><u>[New] Maximizing Engagement - Choosing Your FB Video Direction</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-12-hacks-to-find-and-download-the-best-free-stock-photography/"><u>2024 Approved  12 Hacks to Find and Download the Best Free Stock Photography</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-achieving-the-pinnacle-of-color-accuracy-in-11-crucial-edits/"><u>[Updated] Achieving the Pinnacle of Color Accuracy in 11 Crucial Edits</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>