---
title: Tackling Error Code 0X800700E9 on Xbox Game Pass & Windows 11
date: 2024-07-13T09:54:52.163Z
updated: 2024-07-14T09:54:52.163Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Error Code 0X800700E9 on Xbox Game Pass & Windows 11
excerpt: This Article Describes Tackling Error Code 0X800700E9 on Xbox Game Pass & Windows 11
keywords: Xbox Error Code Fix,XPSSO Failure Resolution,Windows 11 Xbox Play,Error 0X800700E9 Guide,Game Pass Connect Issue,Xbox Sign-In Troubleshoot,E9 Error on Gaming Platforms
thumbnail: https://thmb.techidaily.com/3de06be99a3225bd572539cfd46d39535123115f6244e3ee7a3676c38fda1900.jpg
---

## Tackling Error Code 0X800700E9 on Xbox Game Pass & Windows 11

 The Xbox Game Pass is a popular Microsoft subscription service for games. However, some users encounter a 0x800700e9 error when they try to download and install Xbox Game Pass titles via the Xbox app or Microsoft Store. The 0x800700e9 error code message says “Something unexpected happened,” which provides no clue as to how to resolve that issue.

 Users can’t download and install Xbox Game Pass content because of error 0x800700e9\. However, you can fix error 0x800700e9 with these potential resolutions.

## 1\. Run the Microsoft Store App Troubleshooter

 The Windows Store App troubleshooter might help fix the error 0x800700e9\. This is how you can access the Windows Store App troubleshooter in Windows 11:

1. Use one of the many [ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Click the**Troubleshoot** box that has a spanner icon.
3. Next, click**Other-troubleshooters** to access the Settings app’s list of troubleshooting tools.
4. Select**Run** for activating the Windows Store Apps.  
![The Run button for the Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/run-button-for-windows-store-apps-troubleshooter.jpg)
5. Apply any suggestions the troubleshooter provides.

 The Windows 10 troubleshooters are available within the**Update & Security** category of Settings. Click the**Troubleshoot** tab in that category and select**Additional troubleshooters** . Then you can select Windows Store Apps from there and click**Run** to access the tool.

## 2\. Turn Delivery Optimization On in Settings

 Delivery Optimization is a service that enables Windows Update downloads from other PCs. Error 0x800700e9 often arises when Delivery Optimization is disabled in Windows. You can turn on Delivery Optimization via Settings like this:

1. Open the**Windows Update** tab in Settings.
2. Click**Advanced options** to view more settings.
3. Select the**Delivery Optimization** navigation option.  
![The Delivery Optimization navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-navigation-option.jpg)
4. Turn on the**Allow downloads from other PCs** option to enable Delivery Optimization.  
![The Allow downloads from other PCs option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/allow-downloads-from-other-pcs-option.jpg)
5. Click the**Devices on my local network** radio button.

 You can enable Delivery Optimization in Windows 10’s Settings app much the same. However, you’ll need to select the**Windows Update** category. Then click the**Deliver Optimization** tab in the**Windows Update** category to access and turn on the same**Allow downloads from other PCs** setting.

## 3\. Enable the Delivery Optimization and BITS Services

 Some Xbox Game Pass users have resolved error 0x800700e9 by enabling and running the Delivery Optimization and BITS services. You can enable and start those services via that app as follows:

1. To access Run, press**Win + R** .
2. Type**services.msc** inside Run’s**Open** command box.
3. Select**OK** to open Services.
4. Double-click the Delivery Optimization service.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/services-window2.jpg)
5. Select**Start** if it’s not running.
6. Click**Automatic** on Delivery Optimization’s**Startup type** menu.  
![The Delivery Optimization Properties window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delivery-optimization-properties-window.jpg)
7. Select**Apply** \>**OK** to save the service’s new settings.
8. Repeat steps four to seven for the Background Intelligent Transfer service.

 If the services are already running, try restarting them. Right-click the services and select their**Stop** options. Then you can start those services again by right-clicking them and selecting**Restart** .

## 4\. Enable Delivery Optimization via the Windows Registry

 If the above methods didn't work for you, try enabling Delivery Optimization service by editing the registry. You can back up the registry or set up a restore point before editing the registry if you want to be extra careful. To apply this potential solution, edit the**DoSvc** key like this:

1. First, bring up Registry Editor, which you can open with one of the methods in our guide on [how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) .
2. Click inside the address bar at the top of Registry Editor and erase the current key location.
3. Input this**DoSvc** key location in the address bar and hit**Return** :  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\DoSvc`  
![The DoSvc key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/dovsc-key.jpg)
4. Select the**DoSvc** key, and right-click the**Start** DWORD to select**Modify** .  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/modify-option.jpg)
5. Input**3** in the**Value** box and click**OK** .  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/start-dword-key.jpg)
6. Exit Regedit, and restart the PC.

## 5\. Reset or Repair the Xbox App

 Many users go through the Xbox app to get at their Xbox Game Pass titles on Windows. As such, you might be able to fix error 0x800700e9 by selecting**Reset and Repair** options for the Xbox app inside Settings.

 Check out our guide on [resetting apps in Windows 11 and 10](https://www.makeuseof.com/windows-reset-app/) to clear the Xbox app’s data. The**Repair** option for the Xbox app in Settings is available just above its**Reset** button.

![The Reset option for the Xbox app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reset-option.jpg)

## 6\. Reset the Microsoft Store Cache

 A corrupted Microsoft Store cache data can cause download and installation issues to arise for apps available on Microsoft’s online store. So, resetting the Store’s cache could be another potential solution for the 0x800700e9 error. Try resetting Microsoft Store’s cache in the following steps:

1. Bring up the Windows Search by clicking the magnifying glass or**Search** box on your taskbar.
2. Type**WSReset.exe** within the search box to find that Run command file.
3. Click**WSReset.exe** to run the command.  
![The wsreset.exe Run command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/wsreset-exe-command.jpg)
4. Wait for MS Store to open automatically, and then try downloading Xbox Game Pass titles again.

## 7\. Reinstall the Microsoft Store

 Reinstalling the Microsoft Store can fix deeper issues with that app that could be causing error 0x800700e9\. Although you can’t select to uninstall Microsoft Store, you can still reinstall that app with a PowerShell command. Here are the steps for reinstalling the Microsoft Store via PowerShell:

1. Bring up Run with the**Win + R** keyboard shortcut, and input**PowerShell** within the text box.
2. Right-click PowerShell to bring up a context menu, and select the**Run as administrator** option.
3. Execute this PowerShell command for reinstalling Microsoft Store:  
`Get-AppxPackage -allusers Microsoft.WindowsStore | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Microsoft Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/reinstall-microsoft-store-command.jpg)
4. Wait for the command to finish, and then exit the command app.

## 8\. Reset Your Network

![The Network reset option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-reset-option.jpg)

 Error 0x800700e9 can also sometimes occur because of network issues. Performing a network reset is a good way to troubleshoot issues in this area; however, do note that this will restore your network components to their factory defaults and erase your Wi-Fi and Ethernet connections.

 Have a look at our [how to reset your network settings on Windows](https://www.makeuseof.com/reset-network-settings-windows-11/) guide for details about how to apply this troubleshooting method.

## Enjoy Your Xbox Game Pass Games Again

 Fortunately, you don’t have to cancel your Xbox Game Pass subscription because of error 0x800700e9\. A lot of users have fixed this installation issue for Xbox Game Pass titles with the resolutions in this guide.

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
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-infinix-zero-5g-2023-turbo-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Infinix Zero 5G 2023 Turbo | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-unchanged-environment-powertoys-settings-replication/"><u>Ensuring Unchanged Environment: PowerToys Settings Replication</u></a></li>
<li><a href="https://win11.techidaily.com/betrayed-by-touch-the-latest-vulnerabilities-in-windows-fingerprint-tech/"><u>Betrayed by Touch: The Latest Vulnerabilities in Windows Fingerprint Tech</u></a></li>
<li><a href="https://win11.techidaily.com/basics-on-windows-exepe-files-an-overview/"><u>Basics on Windows EXE/PE Files: An Overview</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-systray-information-showcasing-cpu-and-ram-in-ui/"><u>Elevate SysTray Information: Showcasing CPU & RAM in UI</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-converting-cr2-photos-to-jpeg-format/"><u>Windows Guide: Converting CR2 Photos to JPEG Format</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/constructing-captivating-valorant-youtube-thumbnails-for-2024/"><u>Constructing Captivating Valorant YouTube Thumbnails for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/3-keyways-to-refresh-file-explorer-in-win1011/"><u>3 Keyways to Refresh File Explorer in WIN10/11</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/echoes-of-the-digital-age-leading-tts-platforms-unveiled-for-2024/"><u>Echoes of the Digital Age Leading TTS Platforms Unveiled for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-primer-on-locating-and-navigating-components-management-console/"><u>A Primer on Locating & Navigating Components Management Console</u></a></li>
<li><a href="https://win11.techidaily.com/configure-your-windows-11-to-suit-your-auditory-preferences/"><u>Configure Your Windows 11 to Suit Your Auditory Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-workspace-drawing-on-windows-desktop/"><u>Elevate Your Workspace: Drawing on Windows Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/comparing-local-data-exchange-protocols-google-and-windows-showdown/"><u>Comparing Local Data Exchange Protocols: Google & Windows Showdown</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-crafting-a-holiday-ambiance/"><u>Windows 11: Crafting a Holiday Ambiance</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-risks-associated-with-economical-licenses/"><u>Unveiling the Risks Associated with Economical Licenses</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-efficiency-the-ultimate-guide-to-taskbar-controls/"><u>Unlocking Efficiency: The Ultimate Guide to Taskbar Controls</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-a-smooth-operational-flow-for-wsl-after-win-11s-installation/"><u>Ensuring a Smooth Operational Flow for WSL After Win 11'S Installation</u></a></li>
<li><a href="https://win11.techidaily.com/curated-list-best-weather-trackers-for-w10w11/"><u>Curated List: Best Weather Trackers for W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/embracing-apples-messaging-on-your-windows-machine/"><u>Embracing Apple's Messaging on Your Windows Machine</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-perfect-for-every-task-our-choice-in-8-5k-displays/"><u>In 2024, Perfect for Every Task  Our Choice in 8 5K Displays</u></a></li>
<li><a href="https://win11.techidaily.com/wintime-discrepents-resolved/"><u>WinTime Discrepents Resolved</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-honor-x9b-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Honor X9b | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-end-non-registered-user-sessions-on-windows-11/"><u>A Step-by-Step Guide to End Non-Registered User Sessions on WIndows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/no-expense-required-grab-your-custom-outro-scene/"><u>No Expense Required - Grab Your Custom Outro Scene</u></a></li>
<li><a href="https://win11.techidaily.com/7-ultimate-remedies-for-a-disconnected-usb-wi-fi-adapter-in-windows/"><u>7 Ultimate Remedies for a Disconnected USB Wi-Fi Adapter in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/accelerating-workflow-microsofts-innovative-ai-integration-for-windows-11-taskbar/"><u>Accelerating Workflow: Microsoft's Innovative AI Integration for Windows 11 Taskbar</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-5-leading-video-processors-transforming-podcasts/"><u>[Updated] 5 Leading Video Processors Transforming Podcasts</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-best-practices-for-documenting-youtube-live-videos-for-2024/"><u>[New] Best Practices for Documenting Youtube LIVE Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unwavering-erasure-made-simple-configuring-windows-trash-for-permanent-deletion/"><u>Unwavering Erasure Made Simple: Configuring Windows Trash for Permanent Deletion</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/rewinding-to-reactions-tiktoks-classic-videos-for-2024/"><u>Rewinding to Reactions  TikTok's Classic Videos for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-embrace-classic-gaming-leading-ps3-tools-for-pcs/"><u>[Updated] Embrace Classic Gaming  Leading PS3 Tools for PCs</u></a></li>
<li><a href="https://win11.techidaily.com/easing-windows-safety-blocks-set-by-high-ranking-admins/"><u>Easing Windows Safety Blocks Set By High-Ranking Admins</u></a></li>
<li><a href="https://article-tips.techidaily.com/top-picks-essential-voice-transformers-for-vtuber-success/"><u>Top Picks  Essential Voice Transformers for VTuber Success</u></a></li>
<li><a href="https://win11.techidaily.com/concealing-the-windows-11-taskbars-search-icon/"><u>Concealing the Windows 11 Taskbar's Search Icon</u></a></li>
<li><a href="https://win11.techidaily.com/delving-deep-into-windows-booting-mechanics-and-settings/"><u>Delving Deep Into Windows' Booting Mechanics and Settings</u></a></li>
</ul></div>
