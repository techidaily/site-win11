---
title: Reactivating Lost MS Store Access on Windows 11 & 11
date: 2024-06-25T10:20:44.606Z
updated: 2024-06-26T10:20:44.606Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Lost MS Store Access on Windows 11 & 11
excerpt: This Article Describes Reactivating Lost MS Store Access on Windows 11 & 11
keywords: Reactivate MS Store,Windows 11 Store,Restore MS Store Access,Reinstalling Store,MS Store Fix,Microsoft Store Recovery,Resetting Store Access
thumbnail: https://thmb.techidaily.com/f0922cdea4398af9eb93c3915c9d932ac3a495368c2166a8e69e3bccbb692700.jpg
---

## Reactivating Lost MS Store Access on Windows 11 & 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

 If the[Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

To re-register Microsoft Store apps for the current user:

1. Press the**Win** key and type "powershell" into the Search bar.
2. Right-click on**Windows PowerShell** and select**Run as administrator** .
3. In the PowerShell console, type the following command and press**Enter** :  
`Get-AppXPackage *Microsoft.WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
4. Wait for the command to execute and complete. You may see a blue loading graphic.
5. Once done, type**exit** and press**Enter** to close PowerShell.

 During the process, you may see some errors highlighted in red. It is due to PowerShell trying to reinstall existing apps on Windows. So, ignore the error and wait for the process to complete.

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

## Install and Re-Register All Microsoft Store Apps on Windows 11

 Re-registering Windows apps is often necessary when Microsoft Store is not working. It can also help deal with other Windows settings and apps. If the issue persists, try the built-in Windows Store Apps troubleshooter to fix common Microsoft Store app issues.


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
<li><a href="https://win11.techidaily.com/customizing-firewall-defenses-in-5-easy-steps/"><u>Customizing Firewall Defenses in 5 Easy Steps</u></a></li>
<li><a href="https://win11.techidaily.com/win11-audit-steps-for-default-user-permission-reset/"><u>Win11 Audit: Steps for Default User Permission Reset</u></a></li>
<li><a href="https://win11.techidaily.com/winning-strategy-against-c0000022-system-collapse/"><u>Winning Strategy Against C0000022 System Collapse</u></a></li>
<li><a href="https://win11.techidaily.com/conjuring-powerful-tools-for-windows-users/"><u>Conjuring Powerful Tools for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-winrars-summation-oversights-a-6-step-approach/"><u>Correcting WinRAR's Summation Oversights: A 6-Step Approach</u></a></li>
<li><a href="https://win11.techidaily.com/enter-the-inner-workings-of-your-pc/"><u>Enter the Inner Workings of Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-overcoming-stuck-windows-update-fixer/"><u>Swiftly Overcoming Stuck Windows Update Fixer</u></a></li>
<li><a href="https://win11.techidaily.com/the-sound-surge-5-apps-to-take-windows-volume-well-above-100/"><u>The Sound Surge: 5 Apps to Take Windows' Volume Well Above 100%%</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Motorola G24 Power? | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-decoding-the-secrets-of-high-quality-screen-recordings-with-showmore/"><u>[Updated] Decoding the Secrets of High-Quality Screen Recordings with ShowMore</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-best-practices-in-selecting-youtube-video-extractor-apps-for-android-for-2024/"><u>[Updated] Best Practices in Selecting YouTube Video Extractor Apps for Android for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-honor-x9a-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Honor X9a in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-multimedia-text-producer/"><u>In 2024, Multimedia Text Producer</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-virtualdub-the-go-to-tool-for-shrinking-mpeg2-file-sizes/"><u>2024 Approved VirtualDub The Go-To Tool for Shrinking MPEG2 File Sizes</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/l-cuts-and-j-cuts-demystified-a-beginners-guide-to-fcpx-audio-editing/"><u>L-Cuts and J-Cuts Demystified A Beginners Guide to FCPX Audio Editing</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-navigating-the-backlink-jungle-a-video-content-guide/"><u>[Updated] Navigating the Backlink Jungle  A Video Content Guide</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-samsung-galaxy-s24-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Samsung Galaxy S24</u></a></li>
</ul></div>
