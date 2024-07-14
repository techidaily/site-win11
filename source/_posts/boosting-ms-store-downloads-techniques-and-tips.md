---
title: "Boosting MS Store Downloads: Techniques and Tips"
date: 2024-07-13T10:30:45.771Z
updated: 2024-07-14T10:30:45.771Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boosting MS Store Downloads: Techniques and Tips"
excerpt: "This Article Describes Boosting MS Store Downloads: Techniques and Tips"
keywords: Boost MS Store Sales,Download Tricks MS,Enhance MS Apps,Increase MS Orders,Optimize MS Downloads,Streamline MS Purchases,Elevate MS Access
thumbnail: https://thmb.techidaily.com/566315d56d553ccbd049a4fe3b4211dbde8cabf2cb29973d2f7eb7ff1fc0e46d.jpg
---

## Boosting MS Store Downloads: Techniques and Tips

 Do games and apps take forever to download on the Microsoft Store? If so, you don't need to suffer; there are plenty of ways to speed up your downloads.

 In this article, we'll share a few different things you can try to increase your download speeds on the Microsoft Store.

## 1\. Check Your Internet Connection

 Before making any major changes in the Windows settings, ensure your internet connection isn't responsible for slow downloading on the Microsoft Store. You can confirm this by testing your internet speed using one of the [best speed test websites](https://www.makeuseof.com/best-free-websites-test-internet-speed/) .

 If you are getting a slower download speed across all your internet-based apps, check out our guide on [how to boost your internet speed](https://www.makeuseof.com/tag/10-ways-to-improve-the-speed-of-your-current-router/) . If this guide resolves the slow downloading issue, you're good to go. But if you're still facing the problem, contact your internet service provider (ISP).

## 2\. Close Network-Consuming Applications

 To get the best downloading speed on the Microsoft Store, you must close all the network-consuming applications running in the background. You can do that by following the below instructions:

1. Open the**Task Manager** by pressing the**Ctrl + Shift + Esc** hotkeys.
2. In the**Processes** tab, look in the**Network** column, and close all non-essential applications that are consuming a lot of data.

 Additionally, make sure the Microsoft Store is not running in [Efficiency mode](https://www.makeuseof.com/windows-11-task-manager-efficiency-mode/) , which makes it a less-priority process. To remove the Microsoft Store from efficiency mode, follow the below steps:

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

 By default, the [DNS server](https://www.makeuseof.com/tag/what-is-dns-server/) is set to automatic, which can be the reason behind the slow downloading speed on the Microsoft Store. You will have to switch to an open-source DNS server like Google Public DNS to get a better downloading speed. Here's how to do it:

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
<li><a href="https://win11.techidaily.com/accessing-accelerated-troubleshooting-in-w11-interface/"><u>Accessing Accelerated Troubleshooting in W11 Interface</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/sound-effects-for-podcasts-places-to-find-them-for-2024/"><u>Sound Effects for Podcasts Places to Find Them for 2024</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-samsung-galaxy-f04-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Samsung Galaxy F04</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/best-youtube-video-ideas-to-spark-inspiration/"><u>Best YouTube Video Ideas to Spark Inspiration</u></a></li>
<li><a href="https://win11.techidaily.com/alternatives-for-enabling-elusive-firewall-on-windows/"><u>Alternatives for Enabling Elusive Firewall on Windows</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-premium-webcams-for-professional-sound-recording/"><u>[New] Premium Webcams for Professional Sound Recording</u></a></li>
<li><a href="https://win11.techidaily.com/an-intuitive-roadmap-for-installing-java-development-kit-on-windows-11/"><u>An Intuitive Roadmap for Installing Java Development Kit on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-spontaneous-store-openings-on-pc/"><u>Addressing Spontaneous Store Openings on PC</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dysfunctional-automation-settings-in-office-365outlook/"><u>Addressing Dysfunctional Automation Settings in Office 365/Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-sluggish-downloads-on-windows-pcs-a-guide/"><u>Addressing Sluggish Downloads on Windows PCs: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/augment-windows-11-notebook-with-cognitive-companion/"><u>Augment Windows 11 Notebook with Cognitive Companion</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-roblox-inaccessibility-via-user-restrictions/"><u>Addressing Windows Error: Roblox Inaccessibility via User Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/access-denied-top-7-fixes-for-browser-blockades-on-win-os/"><u>Access Denied? Top 7 Fixes for Browser Blockades on Win OS</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/tutorial-how-to-add-motion-blur-in-blender-for-2024/"><u>Tutorial How To Add Motion Blur in Blender for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/automating-success-windows-audio-at-system-startup/"><u>Automating Success: Windows Audio at System Startup</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-desktop-date-and-time-a-win-1011-guide/"><u>Adjusting Desktop Date & Time: A Win 10/11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-premium-surround-sound-with-dolby-atmos-in-windows-11/"><u>Achieving Premium Surround Sound with Dolby Atmos in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-visual-fluff-remove-windows-search-images/"><u>Avoid Visual Fluff: Remove Windows Search Images</u></a></li>
<li><a href="https://win11.techidaily.com/audio-enhancement-for-windows-step-by-step-driver-instructions/"><u>Audio Enhancement for Windows: Step-by-Step Driver Instructions</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-magic-meets-technology-the-future-of-home-studio-production/"><u>2024 Approved  Magic Meets Technology  The Future of Home Studio Production</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-command-prompt-authorization-problems/"><u>Addressing Command Prompt Authorization Problems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-no-network-reachability-windows/"><u>Addressing No Network Reachability (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-a-pristine-windows-11-workspace/"><u>Achieve a Pristine Windows 11 Workspace</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-earnings-insights-for-video-content-surpassing-1-million-views/"><u>[New] In 2024, Earnings Insights for Video Content Surpassing 1 Million Views</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-from-scenes-to-screens-sims-4-video-capturing/"><u>[Updated] In 2024, From Scenes to Screens  Sims 4 Video Capturing</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-gameplay-recording-harnessing-intel-graphics-hub/"><u>Advanced Gameplay Recording: Harnessing Intel Graphics Hub</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-steam-download-rates-in-windows-environment/"><u>Accelerating Steam Download Rates in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/alleviating-excessive-cpu-usage-by-tiworkerexe-software/"><u>Alleviating Excessive CPU Usage by TiWorker.exe Software</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-game-bar-issues-due-to-subpar-pcs/"><u>Addressing Game Bar Issues Due to Subpar PCs</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-time-honored-directx-experiences-through-dxvk/"><u>Augmenting Time-Honored DirectX Experiences Through DXVK</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-your-cursors-cadence-turn-off-acceleration-win-11/"><u>Adjusting Your Cursor's Cadence: Turn Off Acceleration Win 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-engaging-and-eye-catching-tiktok-videos-made-simple/"><u>[New] 2024 Approved  Engaging and Eye-Catching TikTok Videos Made Simple</u></a></li>
<li><a href="https://apple-account.techidaily.com/tips-and-tricks-for-apple-id-locked-issue-on-apple-iphone-14-pro-by-drfone-ios/"><u>Tips and Tricks for Apple ID Locked Issue On Apple iPhone 14 Pro</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-unlock-the-secrets-of-effective-video-cropping-for-instagram-for-2024/"><u>[New] Unlock the Secrets of Effective Video Cropping for Instagram for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-high-memory-usage-by-microsoft-edge-webview2/"><u>Addressing High-Memory Usage by Microsoft Edge WebView2</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-unleash-creativity-best-animation-software-for-students-and-teachers/"><u>Updated 2024 Approved Unleash Creativity Best Animation Software for Students and Teachers</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-performance-swapping-outdated-windows-drivers/"><u>Accelerating Performance: Swapping Outdated Windows Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/activating-wordpad-efficiently-in-windows-computers/"><u>Activating WordPad Efficiently in Windows Computers</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-strategies-for-extending-shutdown-duration-in-windows-10/"><u>Advanced Strategies for Extending Shutdown Duration in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/amplifying-steam-data-flow-combatting-sudden-drops/"><u>Amplifying Steam Data Flow: Combatting Sudden Drops</u></a></li>
<li><a href="https://win11.techidaily.com/altering-the-native-pdf-reader-setup-in-windows/"><u>Altering the Native PDF Reader Setup in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/activate-invisible-mode-quick-turnoff-of-windows-pcs/"><u>Activate Invisible Mode: Quick Turnoff of Windows PCs</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-interpreting-the-significance-of-blue-emojis-on-messenger/"><u>[Updated] In 2024, Interpreting the Significance of Blue Emojis on Messenger</u></a></li>
<li><a href="https://change-location.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-vivo-y78t-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Vivo Y78t? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-11-taskbar-latency-issues/"><u>Addressing Windows 11 Taskbar Latency Issues</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-clarity-windows-11-taskbar-tutorial/"><u>Achieving Clarity: Windows 11 Taskbar Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/activate-enhanced-browser-protection-with-microsofts-defender-on-windows-11s-edge/"><u>Activate Enhanced Browser Protection with Microsoft's Defender on Windows 11'S Edge</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-honor-90-pro-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Honor 90 Pro is off? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/advancing-classic-games-in-hd-best-practices-with-scummvm-and-windows-os/"><u>Advancing Classic Games in HD: Best Practices with ScummVM and Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/ad-free-experience-just-for-you-with-win-11/"><u>Ad-Free Experience, Just for You with Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-silencing-of-windows-11-pings/"><u>Accelerated Silencing of Windows 11 Pings</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-apple-iphone-11-pro-max-without-passcode-easily-by-drfone-ios/"><u>Unlock Apple iPhone 11 Pro Max Without Passcode Easily</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-disasters-committing-to-weekly-windows-backup/"><u>Avoiding Disasters: Committing to Weekly Windows Backup</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-compatibility-woes-with-surface-firmware-upgrade-tips/"><u>Avoid Compatibility Woes with Surface Firmware Upgrade Tips</u></a></li>
</ul></div>
