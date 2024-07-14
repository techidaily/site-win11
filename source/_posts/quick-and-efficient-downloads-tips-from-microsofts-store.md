---
title: "Quick and Efficient Downloads: Tips From Microsoft’s Store"
date: 2024-07-13T10:14:23.733Z
updated: 2024-07-14T10:14:23.733Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Quick and Efficient Downloads: Tips From Microsoft’s Store"
excerpt: "This Article Describes Quick and Efficient Downloads: Tips From Microsoft’s Store"
keywords: Download Speed Tips,Quick File Access,Efficient Microsoft Updates,Fast Windows Apps,Optimal Downloads,Streamline Storage,Save Time with Store Tips
thumbnail: https://thmb.techidaily.com/0f08e68155172a78a589fb6b8f18fbb5a0a1a4069ed8867faff7b1ab4f999000.jpg
---

## Quick and Efficient Downloads: Tips From Microsoft’s Store

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
<li><a href="https://extra-resources.techidaily.com/in-2024-action-videography-showdown-hero-5-black-or-km-170/"><u>In 2024, Action Videography Showdown  Hero 5 Black or KM-170?</u></a></li>
<li><a href="https://win11.techidaily.com/secrets-to-everlasting-deactivation-of-microsoft-defender/"><u>Secrets to Everlasting Deactivation of Microsoft Defender</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unrecognizable-hardware-in-windows-1011/"><u>Overcoming Unrecognizable Hardware in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-recycle-bin-disruptions-in-win-11-os/"><u>Remedying Recycle Bin Disruptions in Win 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/guide-enable-data-transfer-operations-in-edges-protective-mode-win-11/"><u>Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-starting-windows-search-service-problems/"><u>Solutions for Starting Windows Search Service Problems</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-correcting-error-740-on-winos/"><u>Mastering the Art of Correcting Error 740 on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-update-error-0x80246007-in-windows-11-and-11/"><u>How to Fix the Windows Update Error 0X80246007 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-taskbar-visibility-when-browser-is-maximized/"><u>Restoring Taskbar Visibility When Browser Is Maximized</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-microsoft-office-365-fault-code-30015-26/"><u>Rectify Microsoft Office 365 Fault: Code 30015-26</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-steam-network-failure-on-modern-pc-win11/"><u>Tackling Steam Network Failure on Modern PC, Win11</u></a></li>
<li><a href="https://win11.techidaily.com/speak-clearly-write-exactly-using-whisper-in-windows/"><u>Speak Clearly, Write Exactly: Using Whisper in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-window-11-custom-taskbar-sizing/"><u>Guide to Window 11 Custom Taskbar Sizing</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-final-cuts-ultimate-10-plug-in-essentials-list/"><u>2024 Approved  Final Cut's Ultimate 10 Plug-In Essentials List</u></a></li>
<li><a href="https://win11.techidaily.com/equalize-internet-pace-syncing-laptop-and-mobile-phones/"><u>Equalize Internet Pace: Syncing Laptop & Mobile Phones</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sluggishness-fixing-edge-speed-woes-in-windows-10plus11/"><u>Overcoming Sluggishness: Fixing Edge Speed Woes in Windows 10+11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-store-issues-address-x80072f17/"><u>Streamlining Windows Store Issues: Address X80072F17</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-apple-iphone-15-pro-max-drfone-by-drfone-virtual-ios/"><u>How to Fix Pokemon Go Route Not Working On Apple iPhone 15 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-toolbar-in-microsoft-pc-manager-on-windows-11/"><u>How to Use the Toolbar in Microsoft PC Manager on Windows 11</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/top-7-free-pc-screen-capture-programs-for-2024/"><u>Top 7 Free PC Screen Capture Programs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/revamp-windows-clippy-with-compatibility-fixes/"><u>Revamp Windows Clippy with Compatibility Fixes</u></a></li>
<li><a href="https://video-capture.techidaily.com/step-by-step-installation-of-professional-vrecorder/"><u>Step-by-Step Installation of Professional VRecorder</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-mastering-3d-painting-shortcuts/"><u>Expert Tips for Mastering 3D Painting Shortcuts</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-lava-blaze-curve-5g-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Lava Blaze Curve 5G Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-practices-in-podcast-image-editing-tech/"><u>Best Practices in Podcast Image Editing Tech</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-tasks-with-the-magic-of-flow-launcher/"><u>Supercharge Your Tasks with the Magic of Flow Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-volume-mixer-to-default-after-errors-occurred/"><u>Resetting Volume Mixer to Default After Errors Occurred</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-honor-70-lite-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Honor 70 Lite 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-practical-approach-switching-video-orientation-in-vlc-for-2024/"><u>[New] Practical Approach  Switching Video Orientation in VLC for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-typing-managing-filter-keys-on-pcs/"><u>Elevate Your Typing: Managing Filter Keys on PCs</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-whats-your-no-1-maker-to-animate-your-logo-online-free/"><u>Updated In 2024, Whats Your No. 1 Maker to Animate Your Logo Online Free</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-screen-brilliance-adjustments-in-windows-11/"><u>Mastering Screen Brilliance Adjustments in Windows 11</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-how-to-translate-video-from-japanese-to-english-online-in-2024/"><u>New How To Translate Video From Japanese to English Online, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mend-freezing-clicks-your-action-plan-for-windows/"><u>Mend Freezing Clicks: Your Action Plan for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-typing-experience-speed-up-windows-keyboard-delay/"><u>Enhance Your Typing Experience: Speed Up Windows Keyboard Delay</u></a></li>
<li><a href="https://win11.techidaily.com/master-autominimize-windows-woes-no-more/"><u>Master AutoMinimize: Windows Woes No More</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-woes-a-script-error-cure-all-guide/"><u>Tackling Windows Woes: A Script Error Cure-All Guide</u></a></li>
<li><a href="https://win11.techidaily.com/running-task-manager-administrative-command-for-windows-11/"><u>Running Task Manager: Administrative Command for Windows 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-the-ultimate-guide-to-managing-fast-forward-functions/"><u>2024 Approved  The Ultimate Guide to Managing Fast Forward Functions</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-xbox-stranded-glitch-on-win11/"><u>Overcoming the Xbox Stranded Glitch on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/steering-device-interactions-from-power-save-mode/"><u>Steering Device Interactions From Power Save Mode</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-hyper-v-in-windows-11-steps-to-follow/"><u>Enabling Hyper-V in Windows 11: Steps to Follow</u></a></li>
<li><a href="https://win11.techidaily.com/severing-cloud-storage-bond-onedrive-from-your-microsoft-account-in-windows/"><u>Severing Cloud Storage Bond: OneDrive From Your Microsoft Account in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-power-indicator-designs-for-win-users/"><u>Masterful Power Indicator Designs for Win Users</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-your-pc-to-recognize-razer-devices-again/"><u>How to Get Your PC to Recognize Razer Devices Again</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-regaining-original-windows-configs/"><u>Expert Advice: Regaining Original Windows Configs</u></a></li>
</ul></div>
