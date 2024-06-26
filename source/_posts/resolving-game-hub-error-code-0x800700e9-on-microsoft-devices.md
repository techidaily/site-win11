---
title: Resolving Game Hub Error Code 0X800700E9 on Microsoft Devices
date: 2024-06-25T10:20:02.704Z
updated: 2024-06-26T10:20:02.704Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Resolving Game Hub Error Code 0X800700E9 on Microsoft Devices
excerpt: This Article Describes Resolving Game Hub Error Code 0X800700E9 on Microsoft Devices
keywords: Game Hub Crash Fix,Xbox Error Resolution,Hub Error 0X800700E9 Troubleshoot,Microsoft Hub Issue Help,Devices Error Code ZeroX,Xbox Hub Problem Solve,Hub 0XError Fix Guide
thumbnail: https://thmb.techidaily.com/77bfb2c7f1c1fe0360a8a12d5582bbafa6a377d533d7c690d2e56cf6d1507405.jpg
---

## Resolving Game Hub Error Code 0X800700E9 on Microsoft Devices

 The Xbox Game Pass is a popular Microsoft subscription service for games. However, some users encounter a 0x800700e9 error when they try to download and install Xbox Game Pass titles via the Xbox app or Microsoft Store. The 0x800700e9 error code message says “Something unexpected happened,” which provides no clue as to how to resolve that issue.

 Users can’t download and install Xbox Game Pass content because of error 0x800700e9\. However, you can fix error 0x800700e9 with these potential resolutions.

## 1\. Run the Microsoft Store App Troubleshooter

 The Windows Store App troubleshooter might help fix the error 0x800700e9\. This is how you can access the Windows Store App troubleshooter in Windows 11:

1. Use one of the many[ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
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

1. First, bring up Registry Editor, which you can open with one of the methods in our guide on[how to open Regedit](https://www.makeuseof.com/windows-11-open-registry-editor/) .
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

 Check out our guide on[resetting apps in Windows 11 and 10](https://www.makeuseof.com/windows-reset-app/) to clear the Xbox app’s data. The**Repair** option for the Xbox app in Settings is available just above its**Reset** button.

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

 Have a look at our[how to reset your network settings on Windows](https://www.makeuseof.com/reset-network-settings-windows-11/) guide for details about how to apply this troubleshooting method.

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
<li><a href="https://win11.techidaily.com/how-to-make-win-os-files-editable-again/"><u>How to Make Win OS Files Editable Again</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-implications-of-removing-windows-11s-taskbar-chatting-capability-on-you/"><u>Unpacking the Implications of Removing Windows 11'S Taskbar Chatting Capability on You</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-slow-windows-edge-w10-w11/"><u>Quick Fixes for Slow Windows Edge (W10, W11)</u></a></li>
<li><a href="https://win11.techidaily.com/1719222893625-eradicate-failed-capture-on-windows-devices-today/"><u>Eradicate Failed Capture on Windows Devices Today!</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-transfer-in-google-chrome-now-easier-on-windows/"><u>Mastering File Transfer in Google Chrome, Now Easier on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/correction-procedure-for-windows-error-0xca00a009/"><u>Correction Procedure for Windows Error 0xCA00A009</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-clone-without-third-party-reliance-in-windows/"><u>Crafting Clone Without Third-Party Reliance in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/infuse-the-context-menu-with-divine-commands/"><u>Infuse the Context Menu with Divine Commands</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-14-pro-to-other-iphone-12-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 14 Pro to other iPhone 12 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/basic-video-editing-software-a-beginners-guide-for-2024/"><u>Basic Video Editing Software A Beginners Guide for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-nokia-g22-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Nokia G22 Phone When You Forget the Password</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unveiling-the-secrets-of-powerful-titles/"><u>In 2024, Unveiling the Secrets of Powerful Titles</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/prime-position-predictor-highest-charting-videos/"><u>Prime Position Predictor  Highest Charting Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-enhancing-audience-experience-four-ways-to-livestream-on-tv/"><u>[New] 2024 Approved  Enhancing Audience Experience  Four Ways to Livestream on TV</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-internets-influencers-top-10-global-youtube-sensations/"><u>In 2024, Internet's Influencers  Top 10 Global YouTube Sensations</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-can-i-unlock-my-apple-iphone-se-2020-after-forgetting-my-pin-code-drfone-by-drfone-ios/"><u>How Can I Unlock My Apple iPhone SE (2020) After Forgetting my PIN Code? | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-unleash-the-past-sharing-snaps-from-your-camera-roll/"><u>[New] In 2024, Unleash the Past - Sharing Snaps From Your Camera Roll</u></a></li>
</ul></div>
