---
title: Reactivating Lost MS Store Access on Windows 11 & 11
date: 2024-06-25T11:34:41.193Z
updated: 2024-06-26T11:34:41.193Z
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
<li><a href="https://win11.techidaily.com/solve-yellow-tint-issue-in-windows-monitorage/"><u>Solve Yellow Tint Issue in Windows Monitorage</u></a></li>
<li><a href="https://win11.techidaily.com/modifying-account-lockout-tally-post-unsuccessful-login-attempts-in-windows-1011/"><u>Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/from-windows-to-kali-an-installation-journey/"><u>From Windows to Kali: An Installation Journey</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-error-code-0xc00d36b4-in-windows-11/"><u>Troubleshooting Error Code 0xC00D36B4 in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-0x00000001-restoring-xbox-playability/"><u>Remedy for 0X00000001: Restoring Xbox Playability</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-supercharge-video-memory-on-windows-devices/"><u>Tips to Supercharge Video Memory on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-defender-written-by-michael-cramer/"><u>Navigating Windows Defender' Written by Michael Cramer</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-code-0x80246007-from-windows-update-on-w10w11/"><u>Eliminating Error Code 0X80246007 From Windows Update on W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/prime-weather-software-for-w10w11-pcs/"><u>Prime Weather Software for W10/W11 PCs</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/best-kept-secrets-a-list-of-iconic-radio-effects-for-2024/"><u>Best-Kept Secrets A List of Iconic Radio Effects for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-magic-behind-the-lens-iphone-xs-groundbreayer-camera-tech/"><u>2024 Approved  The Magic Behind the Lens  IPhone X's Groundbreayer Camera Tech</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-get-noticed-on-linkedin-the-ideal-video-aspect-ratio-guide/"><u>Updated 2024 Approved Get Noticed on LinkedIn The Ideal Video Aspect Ratio Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-xml-and-ttml-conversion-to-srt/"><u>2024 Approved  Mastering XML & TTML Conversion to SRT</u></a></li>
<li><a href="https://techidaily.com/video-fixer-software-for-all-corrupt-videos-of-galaxy-s24-ultra-by-stellar-video-repair-mobile-video-repair/"><u>Video Fixer Software for all Corrupt Videos of Galaxy S24 Ultra</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-poco-x6-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Poco X6 Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-instagrams-edge-infusing-artistry-with-slow-motion/"><u>[New] Instagram's Edge  Infusing Artistry with Slow Motion</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/exploring-tools-to-integrate-special-mask-effects-into-your-content-read-the-following-article-to-master-some-tools-experts-in-mask-tracking/"><u>Exploring Tools to Integrate Special Mask Effects Into Your Content. Read the Following Article to Master some Tools Experts in Mask Tracking</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-samsung-galaxy-m14-4g-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Samsung Galaxy M14 4G Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/youtube-affiliate-marketing-how-to-make-money-with-it-for-2024/"><u>YouTube Affiliate Marketing  How to Make Money with It for 2024</u></a></li>
</ul></div>
