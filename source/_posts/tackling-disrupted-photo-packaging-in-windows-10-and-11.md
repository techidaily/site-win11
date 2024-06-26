---
title: Tackling Disrupted Photo Packaging in Windows 10 & 11
date: 2024-06-25T11:35:36.209Z
updated: 2024-06-26T11:35:36.209Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tackling Disrupted Photo Packaging in Windows 10 & 11
excerpt: This Article Describes Tackling Disrupted Photo Packaging in Windows 10 & 11
keywords: PhotoPackagingW10,W10DisruptionSolutions,W11PackagingChallenges,WinPackagingIssues,PackagingTechWindows10,Windows10Photopack,PhotoPackWin11
thumbnail: https://thmb.techidaily.com/c2347da6ec78a1b069be335abb7dc18b2b1262d176e6b4d47161337afbbb6cd1.jpeg
---

## Tackling Disrupted Photo Packaging in Windows 10 & 11

 Microsoft Photos is the default image viewer in Windows with which many users open picture files. However, some users can’t open images in Photos because of a “Package could not be registered” error. That issue arises for some Photos users when they try to open JPG or PNG images in that app.

 This is how you can fix the “Package could not be registered” error in Windows 11 and 10.

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
<li><a href="https://win11.techidaily.com/a-blueprint-for-an-enhanced-taskbar-in-microsofts-next-windows-release/"><u>A Blueprint for an Enhanced Taskbar in Microsoft's Next Windows Release</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-android-studio-on-windows-for-faster-compilation/"><u>Optimizing Android Studio on Windows for Faster Compilation</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-switch-apps-using-snap-feature-in-windows-11/"><u>Swiftly Switch Apps Using Snap Feature in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tactics-avoiding-counterfeit-creations-on-microsofts-platform/"><u>Tech Tactics: Avoiding Counterfeit Creations on Microsoft's Platform</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-bluetooth-attempt-error-in-windows/"><u>Mastering the Fix: Bluetooth Attempt Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tech-renaissance-atlasos-for-obsolete-systems/"><u>Tech Renaissance: AtlasOS for Obsolete Systems</u></a></li>
<li><a href="https://win11.techidaily.com/curating-a-personal-touch-for-windows-mouse-pointer/"><u>Curating a Personal Touch for Windows Mouse Pointer</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-resolving-bandwidth-issues-in-high-quality-obs-for-2024/"><u>[New] Resolving Bandwidth Issues in High Quality OBS for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-the-no-cost-guide-to-capturing-your-favorite-shows/"><u>[New] 2024 Approved  The No-Cost Guide to Capturing Your Favorite Shows</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-mouthwatering-moments-the-hottest-tiktok-food-videos-for-the-modern-kitchen-aficionado/"><u>[New] 2024 Approved  Mouthwatering Moments  The Hottest TikTok Food Videos for the Modern Kitchen Aficionado</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-premierly-free-female-speech-alteration-platform-for-2024/"><u>Updated Premierly Free Female Speech Alteration Platform for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-turning-viewers-into-cash-a-youtube-advertising-primer/"><u>[New] Turning Viewers Into Cash  A YouTube Advertising Primer</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/how-to-reverse-a-youtube-playlist-for-2024/"><u>How to Reverse a YouTube Playlist for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-poco-c65-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Poco C65</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-pgsharp-legal-when-you-are-playing-pokemon-on-oppo-k11x-drfone-by-drfone-virtual-android/"><u>In 2024, Is pgsharp legal when you are playing pokemon On Oppo K11x? | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-passive-viewers-to-earnings-youtubes-monetization-mastery/"><u>[New] 2024 Approved  From Passive Viewers to Earnings  YouTube's Monetization Mastery</u></a></li>
</ul></div>
