---
title: Adjusting Network Settings with Precision (Win11)
date: 2024-08-08T13:14:48.243Z
updated: 2024-08-09T13:14:48.243Z
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
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Finding the Subnet mask in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/finding-the-subnet-mask.jpg)

 The steps to do it using Windows PowerShell are similar to the Command Prompt. To do it,[open Windows PowerShell with admin rights](https://www.makeuseof.com/windows-11-powershell-administrator/) , type the ipconfig /all command, and press Enter.

 In the result that appears, you can see the subnet mask under the Wireless LAN adapter Wi-Fi section.

## How to Change the Subnet Mask in Windows 11

 Now that you know how to find the subnet mask on your computer, let's check out how to change it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
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
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
### 2\. Change the Subnet Mask Using the Control Panel

 The Control Panel is the go-to place to configure window settings and make changes to your device. To use it to change the subnet mask, follow the below instructions:

1. Press the Win key, type**Control Panel** in the search bar, and press Enter.
2. Click the drop-down icon next to**View by** and choose**Large icons.**
3. Choose**Network and Internet** , and then select**Network and Sharing Center** in the following window.
4. Click on your network next to**Connections.**  
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Network name in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-name.jpg)
5. Choose**Properties** from the window that appears.
6. Select the IP version you're using. For instance, if you're using IPv4, select**Internet Protocol Version 4 (TCP/IPv4)** and click the**Properties** button.  
![IPv4 properties option in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/ipv4-properties.jpg)
7. Select the**Use the following address** option and enter the details.  
![Changing the Subnet Mask in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/changing-the-subnet-mask.jpg)
8. Click**OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
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
<li><a href="https://article-helps.techidaily.com/new-frame-your-life-with-iphones-top-10-photo-rules-for-2024/"><u>[New] Frame Your Life with iPhone's Top 10 Photo Rules for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-android-and-iphones-powerful-picklist-boosting-facebook-likeability/"><u>[New] In 2024, Android & iPhone's Powerful Picklist  Boosting Facebook Likeability</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-top-15-facebook-strategies-for-maximizing-online-selling-power-for-2024/"><u>[New] Top 15 Facebook Strategies for Maximizing Online Selling Power for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-unveiling-secrets-to-broadcast-recordings-on-facebook-live-for-2024/"><u>[New] Unveiling Secrets to Broadcast Recordings on Facebook Live for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-behind-the-scenes-how-much-creators-earn-from-youtube-shorts-for-2024/"><u>[Updated] Behind the Scenes  How Much Creators Earn From YouTube Shorts for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-digital-distinction-design-molding-an-animated-profile-for-2024/"><u>[Updated] Digital Distinction Design  Molding an Animated Profile for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-exclusive-7-secure-download-services/"><u>[Updated] Exclusive 7 Secure Download Services</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-how-to-use-creative-commons-copyright-licenses-complete-guide-for-2024/"><u>[Updated] How to Use Creative Commons Copyright Licenses [Complete Guide] for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-tips-for-faster-vimeo-video-viewing-for-2024/"><u>[Updated] Tips for Faster Vimeo Video Viewing for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-troubleshooting-stop-sequential-frame-skips-in-live-streaming/"><u>[Updated] Troubleshooting  Stop Sequential Frame Skips in Live Streaming</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-lightning-speed-seamless-transformation-from-srt-to-text-format/"><u>2024 Approved  Lightning Speed  Seamless Transformation From SRT to Text Format</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-securing-memories-a-comprehensive-guide-for-scanning-and-storing-vintage-photos/"><u>2024 Approved  Securing Memories  A Comprehensive Guide for Scanning and Storing Vintage Photos</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-synchronizing-tiktok-viewership-and-facebook-shares/"><u>2024 Approved  Synchronizing TikTok Viewership and Facebook Shares</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-access-10-fast-methods-to-control-center/"><u>Accelerate Access: 10 Fast Methods to Control Center</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-the-read-only-shackles-of-windows-11/"><u>Breaking Free From the Read-Only Shackles of Windows 11</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-view-mov-movies-content-on-13t-pro-by-aiseesoft-video-converter-play-mov-on-android/"><u>Can’t view MOV movies content on 13T Pro</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-workspace-incorporating-sketches-into-windows-11/"><u>Customize Your Workspace: Incorporating Sketches Into Windows 11</u></a></li>
<li><a href="https://program-issues.techidaily.com/destiny-2-the-ultimate-guide-to-the-broccoli-crash-patch-of-2024/"><u>Destiny 2: The Ultimate Guide to the Broccoli Crash Patch of 2024</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-block-of-microsoft-store-in-windows-11/"><u>Disabling Block of Microsoft Store in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/disguising-or-displaying-time-win-1011-tutorial/"><u>Disguising or Displaying Time: Win 10/11 Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/effective-strategies-to-dial-down-memorycpu-in-windows/"><u>Effective Strategies to Dial Down Memory/CPU in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-techniques-for-inspecting-and-cleansing-windows-trail/"><u>Efficient Techniques for Inspecting & Cleansing Windows Trail</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-rgb-customization-on-your-win11-device/"><u>Enabling RGB Customization on Your Win11 Device</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-system-reliability-automatic-updates-plus-graphics-card-swap/"><u>Enhance System Reliability: Automatic Updates + Graphics Card Swap</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/essential-tips-for-mastering-instagram-reels/"><u>Essential Tips for Mastering Instagram Reels</u></a></li>
<li><a href="https://win11.techidaily.com/freedomgpt-for-pc-running-ai-conversation-tools/"><u>FreedomGPT for PC: Running AI Conversation Tools</u></a></li>
<li><a href="https://win11.techidaily.com/google-nearby-share-vs-windows-nearby-sharing-which-should-you-use/"><u>Google Nearby Share Vs. Windows Nearby Sharing: Which Should You Use?</u></a></li>
<li><a href="https://win11.techidaily.com/hasten-enablingdisabling-microsofts-bing-assistant-in-taskbar/"><u>Hasten Enabling/Disabling: Microsoft's Bing Assistant in Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-achieve-a-seamless-experience-less-latency-more-fps/"><u>How to Achieve a Seamless Experience: Less Latency, More FPS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-cut-off-others-access-in-the-windows-network/"><u>How to Cut Off Others' Access in the WIndows Network</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-lava-yuva-2-pro-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Lava Yuva 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-6s-plus-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 6s Plus With an Apple Watch & What to Do if It Doesnt Work</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-precision-in-upload-a-deep-dive-into-youtube-video-size-settings/"><u>In 2024, Precision in Upload  A Deep-Dive Into YouTube Video Size Settings</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-unlocking-potential-mastering-facebooks-best-practices-for-video-advertising/"><u>In 2024, Unlocking Potential  Mastering Facebook's Best Practices for Video Advertising</u></a></li>
<li><a href="https://win11.techidaily.com/mapping-out-gpo-landscape-a-gpresult-perspective/"><u>Mapping Out GPO Landscape: A GPResult Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-art-of-effortless-data-purging-in-windows-1011/"><u>Master the Art of Effortless Data Purging in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-password-protectionists-for-the-modern-windows-user/"><u>Masterful Password Protectionists for the Modern Windows User</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-access-to-windows-odbc-settings/"><u>Mastering Access to Windows' ODBC Settings</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-cutting-down-cpu-load-on-windows-hosts/"><u>Mastery of Cutting Down CPU Load on Windows Hosts</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-onedrive-servers-errors-easily/"><u>Navigating Through OneDrive Servers Errors Easily</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-the-ultimate-deal-final-cut-pro-at-a-fraction-of-the-cost-for-students/"><u>New The Ultimate Deal Final Cut Pro at a Fraction of the Cost for Students</u></a></li>
<li><a href="https://vp-tips.techidaily.com/perfecting-your-images-the-art-of-curving/"><u>Perfecting Your Images  The Art of Curving</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/pokemon-go-cooldown-chart-on-google-pixel-7a-drfone-by-drfone-virtual-android/"><u>Pokémon Go Cooldown Chart On Google Pixel 7a | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-closed-caption-mishaps-in-windows-10/"><u>Resolving Closed Caption Mishaps in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/rewind-to-reality-efficiently-launching-windows-11-from-scratch/"><u>Rewind to Reality: Efficiently Launching Windows 11 From Scratch</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-files-navigate-smaller-with-windows-explorer/"><u>Simplifying Files: Navigate Smaller with Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-the-task-of-updating-administrator-name-on-windows-11/"><u>Simplifying the Task of Updating Administrator Name on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/skimming-through-complex-windows-update-issues-with-error-0x800736cc/"><u>Skimming Through Complex Windows Update Issues with Error 0X800736CC</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-disable-your-it-admin-limited-access-warning/"><u>Solutions to Disable 'Your IT Admin Limited Access' Warning</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-enhance-text-via-snip-tool-features/"><u>Step-by-Step: Enhance Text via Snip Tool Features</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-compatibility-with-photoshop/"><u>Steps to Overcome Windows Compatibility with Photoshop</u></a></li>
<li><a href="https://win11.techidaily.com/system-rescue-in-13-easy-to-follow-tips/"><u>System Rescue in 13 Easy-to-Follow Tips</u></a></li>
<li><a href="https://win11.techidaily.com/tailored-guide-to-using-github-desktop-for-windows-11-dev-teams/"><u>Tailored Guide to Using GitHub Desktop for Windows 11 Dev Teams</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-art-of-effortless-video-size-transformation-on-macos-for-2024/"><u>The Art of Effortless Video Size Transformation on MacOS for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/top-16-strategies-for-archiving-online-tunes-and-talks-for-2024/"><u>Top 16 Strategies for Archiving Online Tunes and Talks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-with-snipit-try-these-top-tips-for-repairing/"><u>Trouble with SnipIt? Try These Top Tips for Repairing</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-windows-mobility-settings-quick-guide-win-11/"><u>Turn Off Windows Mobility Settings Quick Guide (Win 11)</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-precision-ditch-delays-top-fixes-for-bf2-players/"><u>Unleash Precision, Ditch Delays: Top Fixes for BF2 Players</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-success-removing-0x800700e9-from-your-xbox-game-pass-windows-11-setup/"><u>Unlocking Success: Removing 0X800700E9 From Your Xbox Game Pass, Windows 11 Setup</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ling-the-secrets-to-thriving-with-youtube-adsense/"><u>Unveiling the Secrets to Thriving With YouTube AdSense</u></a></li>
<li><a href="https://win11.techidaily.com/want-to-use-windows-11-without-bloatware-and-stern-hardware-requirements-try-tiny11/"><u>Want to Use Windows 11 Without Bloatware and Stern Hardware Requirements? Try Tiny11</u></a></li>
</ul></div>
