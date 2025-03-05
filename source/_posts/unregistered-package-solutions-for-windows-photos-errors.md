---
title: Unregistered Package Solutions for Windows Photos Errors
date: 2025-03-01T00:39:15.301Z
updated: 2025-03-04T20:02:50.228Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unregistered Package Solutions for Windows Photos Errors
excerpt: This Article Describes Unregistered Package Solutions for Windows Photos Errors
keywords: Photo Error Fix,Windows Photos Troubleshoot,Unregister Windows Photos,Photo Package Management,Windows Error Resolution,Unlisted Package Solutions,Photo System Glitches
thumbnail: https://thmb.techidaily.com/af14611bf221d9521ecefac4bb5738408a7016fb6a0da262331d951510430549.jpg
---

## Unregistered Package Solutions for Windows Photos Errors

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Run the Windows Store Apps Troubleshooter

 Start your error troubleshooting with a troubleshooter for UWP apps on Microsoft Store. Windows Store Apps is a troubleshooter that could identify and resolve an issue with the Photos app. These are the steps for running that troubleshooter in Windows 11:

1. Simultaneously press the**Win + I** keyboard keys to bring up Settings.
2. Click**Troubleshoot** within the**System** tab of Settings.
3. Next, select**Other trouble-shooters** to reach the Windows troubleshooters in Settings.
4. Press the Windows Store Apps troubleshooter’s**Run** button.  
![The troubleshooters in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/other-troubleshooters-in-settings.jpg)
5. Then select to apply fixes suggested by the Windows Store App troubleshooter.  

![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/windows-store-apps-troubleshooter.jpg)

 The same troubleshooter is also available within Windows 10’s Settings app. To access it, click the**Update & Security** category and**Troubleshoot** tab. Then you can select**Additional troubleshooters** to bring up the list of troubleshooting tools.

## 2\. Update Photos

 Updating Microsoft Store apps like Photos can fix issues with them. So, try updating Microsoft Photos like this:

1. Click**Start** and select Microsoft Store on that button’s menu.
2. Select Microsoft Store’s**Library** tab.
3. Click**Get updates** to see what apps need updating. MS Store will then automatically download and install an update for Photos if available.  
![The Get updates button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/get-updates-button.jpg)
4. Wait for the Photos app update to finish before closing Microsoft Store.

## 3\. Repair and Reset the Photos Apps

 Repairing or resetting Photos will likely fix the “Package could not be registered” if that app has corrupted files or data. You can select adjacent**Repair** and**Reset** troubleshooting options for Photos within Settings’ Apps & Features tool. To apply this solution, follow the instructions in our guide for[resetting Microsoft Store apps](https://www.makeuseof.com/windows-reset-app/) . Select the**Repair** option first and**Reset** second if necessary.

![The Repair and Reset buttons for Photos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-repair-reset-buttons.jpg)

## 4\. Run the Deployment Image and System File Checker Tools

 The “Package could not be registered” error can also be due to Windows system file corruption. That much has been confirmed by users who’ve said that running Deployment Image Servicing Management and System File Checker scans fixed this issue on their PCs. You can apply this potential solution by[opening the Command Prompt with admin rights](https://www.makeuseof.com/windows-11-open-command-prompt/) and running these separate DISM and SFC commands:

`DISM.exe /Online /Cleanup-image /Restorehealth`

`sfc /scannow`

 Run the Deployment Image Servicing Management scan command before the System File Checker tool. Leave the Command Prompt open until it shows a Windows Resource Protection message for the SFC scan. If it says Windows Resource Protection repaired files, this resolution might have resolved the “Package could not be registered” error.

## 5\. Reinstall Photos

 If the “Package could not be registered” error persists after applying the resolutions above, you might need to reinstall Photos to fix it. This solution is the most likely one to fix a corrupted Photos app. You can uninstall and reinstall Photos with PowerShell like this:

1. Start PowerShell with a method in our guide to[opening PowerShell as an administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. Then input this command for uninstalling PowerShell and hit**Enter** :  
`Get-AppxPackage Microsoft.Windows.Photos | Remove-AppxPackage`  
![The uninstall Photos command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-photos-command.jpg)
3. To reinstall Photos, input this PowerShell command and press**Enter** :  

`Get-AppxPackage -allusers Microsoft.Windows.Photos | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reinstall Photos app command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/reinstall-photos-app.jpg)
4. Restart your PC after reinstalling Photos.

## 6\. Reset Windows

 If you’ve tried all other resolutions suggested here, there could be a deeper Windows issue causing the “Package could not be registered” Photos error. Then a system reset could be needed to remedy that deeper issue. Resetting Windows will refresh the platform’s components and restore it to a default state.

![The Reset this PC tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-reset-this-pc-tool.jpg)

 This is suggested as a last resort because you’ll need to reinstall third-party software installed before resetting Windows. However, you can select to keep user files such as photos, documents, videos, etc. Our[guide to resetting Windows 10 and 11](https://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer/) tells you how to perform a factory reset.

## Open Your Images in Photos Again

 One of the above resolutions will likely resolve the “Package Could not be Registered” error on your Windows 11/10 PC. However, remember there are plenty of third-party app alternatives you can open your images with if that Photos error persists. IrfanView, XnView, and FastStone Image Viewer are among the best Photos alternatives that are freely available.

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
<li><a href="https://screen-video-capture.techidaily.com/new-a-comprehensive-guide-to-capturing-facebook-chats-for-2024/"><u>[New] A Comprehensive Guide to Capturing Facebook Chats for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-50plus-youtube-channel-names-for-vloggers-100-new-filmora-for-2024/"><u>[Updated] 50+ Youtube Channel Names for Vloggers [100% New] - Filmora for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/accelerated-scanning-process-for-windows/"><u>Accelerated Scanning Process for Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatting-with-future-tech-diving-into-mistral-ais-le-chat-and-its-comparison-to-chatgpt/"><u>Chatting with Future Tech: Diving Into Mistral AI's Le Chat and Its Comparison to ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-single-board-pcs-for-windows-users/"><u>Efficient Single-Board PCs for Windows Users</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-learn-how-to-lock-stolen-your-iphone-13-properly-drfone-by-drfone-ios/"><u>In 2024, Learn How To Lock Stolen Your iPhone 13 Properly | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/mastering-screen-recordings-powerpoint-edition-for-2024/"><u>Mastering Screen Recordings PowerPoint Edition for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/remove-the-lock-screen-fingerprint-of-your-vivo-y100-5g-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Vivo Y100 5G</u></a></li>
<li><a href="https://win11.techidaily.com/thrilling-new-functionality-awaits-with-w11-update-22h2/"><u>Thrilling New Functionality Awaits with W11 Update #22H2</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-tools-for-fixing-win11-filesystem-errors/"><u>Troubleshooting Tools for Fixing Win11 Filesystem Errors</u></a></li>
<li><a href="https://win11.techidaily.com/whispered-slumber-routines-for-computers/"><u>Whispered Slumber Routines for Computers</u></a></li>
</ul></div>

