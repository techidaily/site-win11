---
title: "Banishing Glitches: A Guide to Fixing Error Code 0X800700E9 in Xbox Game Pass & Windows 11"
date: 2024-07-13T11:24:23.222Z
updated: 2024-07-14T11:24:23.222Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Banishing Glitches: A Guide to Fixing Error Code 0X800700E9 in Xbox Game Pass & Windows 11"
excerpt: "This Article Describes Banishing Glitches: A Guide to Fixing Error Code 0X800700E9 in Xbox Game Pass & Windows 11"
keywords: Error 0X800700E9 Fix Guide,Xbox Game Pass Glitches Banish,Windows 11 Error Code Resolution,Fixing Xbox Errors in Windows 11,Overcoming Xbox Game Pass Bugs,Troubleshoot Code 0X700E9 on Xbox,Win 11 Error Fix for Game Pass Issues
thumbnail: https://thmb.techidaily.com/c64aba238bf38e8dde6a455b091ef6dd75fa774a21d0b3000a42b8339ddfda6c.jpg
---

## Banishing Glitches: A Guide to Fixing Error Code 0X800700E9 in Xbox Game Pass & Windows 11

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
<li><a href="https://win11.techidaily.com/boosting-your-excel-pace-on-a-windows-system/"><u>Boosting Your Excel Pace on a Windows System</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/unbiased-reviews-of-youtube-mp3-converters-for-beginners/"><u>Unbiased Reviews of YouTube MP3 Converters for Beginners</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-boost-your-discord-experience-mastering-emoji-enriched-statuses/"><u>[Updated] In 2024, Boost Your Discord Experience  Mastering Emoji-Enriched Statuses</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-step-by-step-guide-to-creating-fb-slideshows/"><u>[Updated] Step-by-Step Guide to Creating FB Slideshows</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-displaying-notifications-of-phone-link-app-on-pc/"><u>Addressing Non-Displaying Notifications of Phone Link App on PC</u></a></li>
<li><a href="https://win11.techidaily.com/blueprint-for-dominance-in-windows-appbrowser-arena/"><u>Blueprint for Dominance in Windows' App/Browser Arena</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-the-file-explorer-performance/"><u>Boosting the File Explorer Performance</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-overuse-steps-for-efficient-wlanextexe/"><u>Avoiding Overuse: Steps for Efficient Wlanext.exe</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-steam-transfer-speed-averting-sudden-stops/"><u>Boosting Windows Steam Transfer Speed: Averting Sudden Stops</u></a></li>
<li><a href="https://win11.techidaily.com/blueprint-for-winapp-and-web-browser-mastery/"><u>Blueprint for WinApp and Web Browser Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-pitfalls-of-error-xffffff-in-print-tasks/"><u>Avoiding the Pitfalls of Error XFFFFFF in Print Tasks</u></a></li>
<li><a href="https://win11.techidaily.com/boost-user-experience-add-portable-menus-on-win11plus/"><u>Boost User Experience: Add Portable Menus on Win11+</u></a></li>
<li><a href="https://driver-install.techidaily.com/windowsrtkupdate-rh5770drivers/"><u>WindowsRTKUpdate: RH5770Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/big-data-in-bare-minipcs-little-prowess/"><u>Big Data in Bare MiniPCs, Little Prowess</u></a></li>
<li><a href="https://win11.techidaily.com/banish-temp-files-quick-windows-fixes/"><u>Banish Temp Files: Quick Windows Fixes</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-data-from-apple-iphone-14-pro-max-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Data from Apple iPhone 14 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-windows-11-tablet-bar-accessibility/"><u>Maximizing Windows 11 Tablet Bar Accessibility</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-harmonizing-your-footage-a-color-grading-roadmap/"><u>[Updated] Harmonizing Your Footage  A Color Grading Roadmap</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-barriers-accessing-windowsstore-folder/"><u>Breaking Down Barriers: Accessing WindowsStore Folder</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-seamless-streaming-smarter-storing-top-51-exclusive-android-mobile-video-trimming-software/"><u>[New] Seamless Streaming, Smarter Storing  Top 51 Exclusive Android Mobile Video Trimming Software</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reverse-failed-zip-file-extractions-on-windows-11/"><u>How To Reverse Failed Zip File Extractions on Windows 11</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-most-viewed-vids-worldwide-roundup/"><u>2024 Approved  Most Viewed Vids Worldwide Roundup</u></a></li>
<li><a href="https://win11.techidaily.com/begin-your-digital-discourse-with-windows-11/"><u>Begin Your Digital Discourse with Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-3-ways-for-android-pokemon-go-spoofing-on-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways for Android Pokemon Go Spoofing On Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-novice-to-expert-a-comprehensive-guide-to-macs-preview-software/"><u>In 2024, From Novice to Expert  A Comprehensive Guide to Mac's Preview Software</u></a></li>
<li><a href="https://win11.techidaily.com/bootable-backup-a-self-reliant-approach/"><u>Bootable Backup: A Self-Reliant Approach</u></a></li>
<li><a href="https://win11.techidaily.com/awakening-obscured-windows-11-query-engine/"><u>Awakening Obscured Windows 11 Query Engine</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/aprendizaje-de-tiempo-en-espanol-fundamentos/"><u>Aprendizaje De Tiempo en Español: Fundamentos</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-connection-dropouts-with-steam-remote/"><u>Addressing Connection Dropouts with Steam Remote</u></a></li>
<li><a href="https://win11.techidaily.com/blocking-unsolicited-activation-of-windows-marketplace/"><u>Blocking Unsolicited Activation of Windows Marketplace</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-email-apps-0x800713f-issue-on-win11/"><u>Navigating Through Email App's 0X800713F Issue on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/banish-stubborn-epic-launcher-guide-for-win-11-users/"><u>Banish Stubborn Epic Launcher: Guide for Win 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-complications-with-an-efficient-in-place-windows-11-update/"><u>Avoiding Complications with an Efficient, In-Place Windows 11 Update</u></a></li>
<li><a href="https://win11.techidaily.com/boltgun-performance-tips-to-resolve-on-pc-interruptions/"><u>Boltgun Performance Tips to Resolve On-PC Interruptions</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-going-viral-guide-keyword-strategies-for-cut-to-the-chase-videos-for-2024/"><u>[Updated] Going Viral Guide  Keyword Strategies for Cut-to-the-Chase Videos for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-best-techniques-for-saving-your-discord-sessions-for-2024/"><u>[Updated] Best Techniques for Saving Your Discord Sessions for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-high-end-hardware-a-showcase-of-excellence/"><u>2024 Approved  High-End Hardware  A Showcase of Excellence</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ring-transitional-terminations-for-2024/"><u>Tailoring Transitional Terminations for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-locked-out-of-iphone-se-2022-5-ways-to-get-into-a-locked-iphone-se-2022-drfone-by-drfone-ios/"><u>In 2024, Locked Out of iPhone SE (2022)? 5 Ways to get into a Locked iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-windows-11-security-upgrading-pin-length/"><u>Boosting Windows 11 Security: Upgrading PIN Length</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-youth-voices-channeling-lifes-milestinasubscriber-channel-for-impactful-personal-storytelling/"><u>[Updated] Youth Voices  Channeling Life's Milestinasubscriber Channel for Impactful Personal Storytelling</u></a></li>
<li><a href="https://win11.techidaily.com/banishing-error-xc0f1103f-in-windows-11-nvidias-geforce-now/"><u>Banishing Error Xc0f1103f in Windows 11, NVIDIA's GeForce Now</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-se-2020-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone SE (2020) without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-iphone-lens-magic-perfecting-close-up-and-macro-shots/"><u>2024 Approved  IPhone Lens Magic  Perfecting Close-Up and Macro Shots</u></a></li>
<li><a href="https://win11.techidaily.com/activating-hidden-taskbar-query-function-in-windows-11/"><u>Activating Hidden Taskbar Query Function in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/boost-productivity-with-these-8-window-study-secrets/"><u>Boost Productivity with These 8 Window Study Secrets</u></a></li>
<li><a href="https://win11.techidaily.com/beating-blue-screens-a-guide-to-system-recovery/"><u>Beating Blue Screens: A Guide to System Recovery</u></a></li>
<li><a href="https://win11.techidaily.com/break-through-windows-barriers-be-an-admin-now/"><u>Break Through Windows Barriers - Be an Admin Now</u></a></li>
<li><a href="https://facebook.techidaily.com/beyond-boundaries-4-ways-online-connectivity-shaped-today/"><u>Beyond Boundaries: 4 Ways Online Connectivity Shaped Today</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-5-must-try-ways-to-add-and-send-gif-in-text-message-on-android/"><u>New 5 Must Try Ways to Add and Send GIF in Text Message on Android</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-real-time-performance-on-windows-11-task-monitor/"><u>Boosting Real-Time Performance on Windows 11 Task Monitor</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/2024-approved-harnessing-the-power-of-speech-on-tiktok-platform/"><u>2024 Approved  Harnessing the Power of Speech on TikTok Platform</u></a></li>
<li><a href="https://win11.techidaily.com/asuss-innovation-unleashed-exploring-s15-oled-and-bape-edition/"><u>Asus's Innovation Unleashed: Exploring S15 OLED and BAPE Edition</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-roadblocks-reinstating-access-on-windows-11-system/"><u>Avoiding Roadblocks: Reinstating Access on Windows 11 System</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-oppo-a1x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Oppo A1x 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-audio-5-ways-for-above-100-output-on-pcs/"><u>Boosting Audio: 5 Ways for Above-100%% Output on PCs</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unraveling-monetization-strategies-in-the-realm-of-video-shorts/"><u>In 2024, Unraveling Monetization Strategies in the Realm of Video Shorts</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-ai-assistant-via-vivetool/"><u>Activating Windows AI Assistant via ViveTool</u></a></li>
</ul></div>
