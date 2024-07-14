---
title: Configuring Metered Connection for Wifi Networks on Win11
date: 2024-07-13T10:32:56.500Z
updated: 2024-07-14T10:32:56.500Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring Metered Connection for Wifi Networks on Win11
excerpt: This Article Describes Configuring Metered Connection for Wifi Networks on Win11
keywords: Wi-Fi Metering Setup (Wifi+Metering),Windows 11 WLAN Metering,Configure Wi-Fi Metering (Win11),Win11 Wireless Meter Configurations,Metered Wi-Fi on Windows 11,Optimizing Metric in Win11 Wifi,Win11 Setup for Wifi Metering
thumbnail: https://thmb.techidaily.com/681aed17cbdddeac0350ff3fe9a9a1770d531416a3cf82559b42c4110e5fe7f0.jpg
---

## Configuring Metered Connection for Wifi Networks on Win11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to [launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the [Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on [the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.


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
<li><a href="https://win11.techidaily.com/efficient-methods-to-unlock-your-windows-pin/"><u>Efficient Methods to Unlock Your Windows PIN</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-old-masters-legacy-images-without-limits/"><u>[Updated] In 2024, Old Masters' Legacy  Images Without Limits</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-digital-asset-preservation-with-adobe-and-exploring-best-non-adobe-options-for-2024/"><u>Mastering Digital Asset Preservation with Adobe & Exploring Best Non-Adobe Options for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-finding-fixes-for-systemsettingsexe-in-win11/"><u>Tips for Finding Fixes for SystemSettings.exe in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-and-solving-roblox-errors-tied-to-account-restrictions/"><u>Unveiling and Solving Roblox Errors Tied to Account Restrictions</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-breakthrough-turned-breach-windows-hellos-future/"><u>Biometric Breakthrough Turned Breach: Windows Hello's Future?</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-code-0x80246007-from-windows-update-on-w10w11/"><u>Eliminating Error Code 0X80246007 From Windows Update on W10/W11</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-videographers-guide-to-capturing-sports-competitions/"><u>[Updated] 2024 Approved  Videographer's Guide to Capturing Sports Competitions</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-plugged-inspection-error-for-audio-hardware-on-winos/"><u>Fixing Plugged Inspection Error for Audio Hardware on WinOS</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-say-goodbye-to-frustration-easy-filmora-coupon-code-access/"><u>In 2024, Say Goodbye to Frustration Easy Filmora Coupon Code Access</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-esd-and-its-transformation-into-iso-format-for-pcs/"><u>Understanding ESD and Its Transformation Into ISO Format for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/charting-a-course-for-change-windows-11-explore-evolution/"><u>Charting a Course for Change: Windows 11 Explore Evolution</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/seamless-system-updates-implementing-macos-sierra-for-2024/"><u>Seamless System Updates  Implementing macOS Sierra for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Samsung Galaxy S23+? | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/breaking-language-barriers-with-these-top-20-video-translators/"><u>Breaking Language Barriers with These Top 20 Video Translators</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-internal-audio-faults-in-audacity-wos-edition/"><u>Dissecting Internal Audio Faults in Audacity, WOS Edition</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-try-connecting-error-on-windows-11-devices/"><u>Conquering Try Connecting Error on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-resolving-installation-hurdles-in-windows-1011/"><u>Understanding & Resolving Installation Hurdles in Windows 10/11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-lava-blaze-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-performance-and-functionality-with-alomwares-tools/"><u>Optimize Performance & Functionality with AlomWare's Tools</u></a></li>
<li><a href="https://win11.techidaily.com/minimalist-pc-large-space-slight-lag/"><u>Minimalist PC - Large Space, Slight Lag</u></a></li>
<li><a href="https://win11.techidaily.com/regain-missing-windows-storage-access/"><u>Regain Missing Windows Storage Access</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-essential-elements-missing-windows-error/"><u>Overcoming 'Essential Elements Missing' Windows Error</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-xpatch-fixes-for-error-0x80073712/"><u>Mastering Windows XPatch Fixes for Error 0X80073712</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-iphone-8-online-here-are-6-easy-ways-by-drfone-ios/"><u>How to Unlock iPhone 8 Online? Here are 6 Easy Ways</u></a></li>
<li><a href="https://win11.techidaily.com/booting-into-safety-6-ways-to-enter-windows-11s-safe-mode/"><u>Booting Into Safety: 6 Ways to Enter Windows 11'S Safe Mode</u></a></li>
<li><a href="https://win11.techidaily.com/removing-intrusive-edge-toolbar-items/"><u>Removing Intrusive Edge Toolbar Items</u></a></li>
<li><a href="https://win11.techidaily.com/a-new-era-of-taskbars-proposing-key-improvements-to-microsofts-design/"><u>A New Era of Taskbars: Proposing Key Improvements to Microsoft's Design</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-boost-your-linkedin-video-views-with-eye-catching-custom-thumbnails-for-2024/"><u>New Boost Your LinkedIn Video Views with Eye-Catching Custom Thumbnails for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/traversing-through-system-failsafe-files-after-blue-screen/"><u>Traversing Through System Failsafe Files After Blue Screen</u></a></li>
<li><a href="https://win11.techidaily.com/ace-at-tech-how-to-revitalize-your-pcs-apps/"><u>Ace at Tech: How to Revitalize Your PC's Apps</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-top-tiktok-watermark-erasers-remove-logos-easily-for-2024/"><u>New Top TikTok Watermark Erasers Remove Logos Easily for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/tactical-steps-to-evade-windows-account-prompts/"><u>Tactical Steps to Evade Windows Account Prompts</u></a></li>
</ul></div>
