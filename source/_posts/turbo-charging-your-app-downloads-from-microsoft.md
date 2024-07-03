---
title: Turbo-Charging Your App Downloads From Microsoft
date: 2024-06-25T11:26:26.742Z
updated: 2024-06-26T11:26:26.742Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turbo-Charging Your App Downloads From Microsoft
excerpt: This Article Describes Turbo-Charging Your App Downloads From Microsoft
keywords: Boost Windows Store Traffic,Increase App Sales, MS,Enhance Microsoft App Downloads,Drive MS App Purchases Up,Amplify MS App Popularity,Escalate iOS/Android Installations,Accelerate Application Uptake
thumbnail: https://thmb.techidaily.com/861e642d844db4b2f3d772a017498464c5809d87279c75b02518b1d6b111bfc3.jpg
---

## Turbo-Charging Your App Downloads From Microsoft

 Do games and apps take forever to download on the Microsoft Store? If so, you don't need to suffer; there are plenty of ways to speed up your downloads.

 In this article, we'll share a few different things you can try to increase your download speeds on the Microsoft Store.

## 1\. Check Your Internet Connection

 Before making any major changes in the Windows settings, ensure your internet connection isn't responsible for slow downloading on the Microsoft Store. You can confirm this by testing your internet speed using one of the[best speed test websites](https://www.makeuseof.com/best-free-websites-test-internet-speed/) .

 If you are getting a slower download speed across all your internet-based apps, check out our guide on[how to boost your internet speed](https://www.makeuseof.com/tag/10-ways-to-improve-the-speed-of-your-current-router/) . If this guide resolves the slow downloading issue, you're good to go. But if you're still facing the problem, contact your internet service provider (ISP).

## 2\. Close Network-Consuming Applications

 To get the best downloading speed on the Microsoft Store, you must close all the network-consuming applications running in the background. You can do that by following the below instructions:

1. Open the**Task Manager** by pressing the**Ctrl + Shift + Esc** hotkeys.
2. In the**Processes** tab, look in the**Network** column, and close all non-essential applications that are consuming a lot of data.

 Additionally, make sure the Microsoft Store is not running in[Efficiency mode](https://www.makeuseof.com/windows-11-task-manager-efficiency-mode/) , which makes it a less-priority process. To remove the Microsoft Store from efficiency mode, follow the below steps:

1. In the Task Manager, right-click on the Microsoft Store.
2. Click on the**Efficiency mode** option from the context menu.  
![Disabling the Efficiency Mode of the Microsoft Store](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disabling-the-efficiency-mode.jpg)

 Next, restart your computer and check if there's any improvement in the downloading speed.

## 3\. Turn Off Windows' Metered Connection

 Windows metered connection feature lets users save data. This feature becomes really useful when you are under a data cap, but on the negative side, it can limit how apps use the available bandwidth.

 You must disable the metered connection feature if you are on an unlimited data plan or don't want to restrict apps from using a certain amount of bandwidth. Here's how to do it:

1. Open the**Settings menu** by pressing the**Win + I** hotkeys.
2. Click the**Network** **& internet** option in the left panel.
3. Choose**Wi-Fi** and then select your Wi-Fi connection.
4. Disable the toggle next to the**Metered connection** option.  
![Disable Metered Connection in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/metered-connection.jpg)

## 4\. Change the Background Download Bandwidth

 The next thing you can try to get better speeds on the Microsoft Store is to increase the background download bandwidth. Here's how:

1. Open the Settings menu, and choose**Windows Update** from the left panel.
2. Choose**Advanced options.**
3. Under**Additional options,** choose**Delivery Optimization.**
4. Choose**Advanced options.**
5. Under**Download settings,** select the **Percentage of measured bandwidth (measured against the updates source)** option.  
![Percentage of measured bandwidth (measured against the updates source) option in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/percentage-of-measured-bandwidth-measured-against-the-updates-source.jpg)
6. Check the **Limit how much bandwidth is used for downloading updates in the background** option, and drag the slider to**100%.**
7. Then, check the **Limit how much bandwidth is used for downloading updates in the foreground** option and drag the slider to**100%.**  
![Limit how much bandwidth is used for downloading updates in the foreground option in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/limit-how-much-bandwidth-is-used-for-downloading-updates-in-the-foreground.jpg)

 That's it. Check if there is an improvement in the downloading speed.

## 5\. Clear the Microsoft Store Cache Data

 Microsoft Store stores cache data to offer a better user experience. But if the cache data gets corrupted, it might adversely affect the downloading speed.

 The solution, in this case, is to clear the Microsoft Store cache data. To do this, follow the below steps:

1. Launch the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and choose**Run as administrator** from the right pane.
3. In the elevated Command Prompt window, type**wsreset** and press**Enter** .  
![wsreset command in the Command Prompt window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/wsreset-command.jpg)

## 6\. Switch to the Google Public DNS

 By default, the[DNS server](https://www.makeuseof.com/tag/what-is-dns-server/) is set to automatic, which can be the reason behind the slow downloading speed on the Microsoft Store. You will have to switch to an open-source DNS server like Google Public DNS to get a better downloading speed. Here's how to do it:

1. Launch the Start Menu, type**Control Panel** and press Enter.
2. In the Control Panel, change the**View by** to**Category.**
3. Choose the**Network and Internet** option.
4. Click on**Network and Sharing Center,** and then click on**Change adapter settings** in the left panel.  
![Change Adapter settings option in Windows 11 Network and Sharing center](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/05/Change-Adapter-settings.jpg)
5. Right-click on the connected network and choose**Properties.**
6. Double-click on the**Internet Protocol Version 4 (TCP/IPv4)** and select the**Use the following DNS server addresses** bulletin.
7. Type**8.8.8.8** in the**Preferred DNS** **server** box and**8.8.4.4** in the**Alternate DNS** **server** box.  
![Configuring the Google Public DNS in the Control Panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/google-public-dns.jpg)
8. Click**OK** to save the settings.

## 7\. Re-register the Microsoft Store

 Sometimes, a temporary glitch can be the reason behind slow downloads on the Microsoft Store. To get rid of such a glitch, you'll have to re-register the Microsoft Store.

 You can't uninstall the Microsoft Store using the Control Panel or any other method used for uninstalling the standard apps. Instead, you will have to execute a command in the PowerShell window to re-register the Microsoft Store.

1. Launch the Start Menu, type**PowerShell,** and choose**Run as administrator** from the right pane.
2. In the PowerShell window, type the following command:  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. Press**Enter** to re-register the Microsoft Store.

 After that, restart your computer and check if the download speed has increased. If not, then you might have to reset the network settings of your computer.

## 8\. Reset the Network Settings

 Is there still no improvement in the Microsoft Store download speed? Probably there's something wrong with your current network settings.

 To fix this, you'll have to reset the network settings, which will remove and then reinstall network adapters and set other network components back to their default values. Here's how:

1. Open the Settings menu, and choose Network & Internet from the left panel.
2. Select**Advanced network settings** and then choose**Network reset.**
3. Click the**Reset now** button.  
![Reset now button to reset the network settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-now-button.jpg)
4. Click**Yes** to the confirmation box that appears.

## Improve Your Microsoft Store Download Speed

 Microsoft Store is the go-to place to download games and apps on a Windows computer. But sometimes, misconfigured Windows settings, a temporary glitch, or network-hogging applications running in the background can slow down the download speed on the Microsoft Store. Fortunately, you can quickly fix this issue by applying the above fixes.


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
<li><a href="https://win11.techidaily.com/is-voice-access-not-working-on-windows-11-heres-how-to-fix-it/"><u>Is Voice Access Not Working on Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/prime-windows-experience-select-top-optimizers-ranked/"><u>Prime Windows Experience: Select Top Optimizers Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/file-locations-decoded-win11s-best-practices-for-retrieving-file-and-folder-paths-6-methods/"><u>File Locations Decoded: Win11's Best Practices for Retrieving File & Folder Paths (6 Methods)</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-to-screen-capture-tool-in-windows-11-swiftly/"><u>Navigate to Screen Capture Tool in Windows 11 Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-app-migration-tips-to-fix-windows-task-manager-positions/"><u>Avoid App Migration: Tips to Fix Windows Task Manager Positions</u></a></li>
<li><a href="https://win11.techidaily.com/7-obstacles-hindering-windows-11-upgrade-traction/"><u>7 Obstacles Hindering Windows 11 Upgrade Traction</u></a></li>
<li><a href="https://win11.techidaily.com/pro-tips-for-maximizing-speed-and-efficiency-in-3d-painting/"><u>Pro Tips for Maximizing Speed and Efficiency in 3D Painting</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-track-windows-10-and-11-note-hacks/"><u>Keeping Track: Windows 10 & 11 Note Hacks</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-how-to-create-marketing-videos/"><u>New How to Create Marketing Videos?</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-guide-to-high-quality-voice-capture-with-your-samsung-galaxy-s10s9/"><u>New 2024 Approved Guide to High-Quality Voice Capture with Your Samsung Galaxy S10/S9</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-customize-your-video-to-fit-seamlessly-in-instagram/"><u>[Updated] In 2024, Customize Your Video to Fit Seamlessly in Instagram</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/streamlined-approach-save-youtube-videos-for-2024/"><u>Streamlined Approach  Save YouTube Videos for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-tailored-transmission-terminal-podcasters-hub/"><u>In 2024, Tailored Transmission Terminal  Podcaster's Hub</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-top-10-timeless-family-adventures-on-screen-this-season/"><u>In 2024, Top 10 Timeless Family Adventures on Screen This Season</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-complete-guide-webinar-software-10-best-webinar-software/"><u>[New] 2024 Approved  Complete Guide Webinar Software  10 Best Webinar Software</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/how-to-manual-for-crafting-youtube-playlists/"><u>How-To Manual for Crafting YouTube Playlists</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-no-cost-creative-corner-finding-the-finest-tiktok-backgrounds/"><u>In 2024, No-Cost Creative Corner  Finding the Finest TikTok Backgrounds</u></a></li>
</ul></div>
