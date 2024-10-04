---
title: Reactivation Guide for Apps From the Microsoft Store
date: 2024-10-02T23:31:24.521Z
updated: 2024-10-04T04:18:10.200Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivation Guide for Apps From the Microsoft Store
excerpt: This Article Describes Reactivation Guide for Apps From the Microsoft Store
keywords: Reactivate MS Store Apps,Reviving Microsoft Store Games,Restarting MS Store Programs,Resurrecting Microsoft Store Purchases,Reacting MS App Installations,Reinstating Store App Accessibility,Restoring MS App Functionality
thumbnail: https://thmb.techidaily.com/de2b8c65401e9876b1b1a5fbf84a14916f9f22a18062d51200fd6852f871f665.jpg
---

## Reactivation Guide for Apps From the Microsoft Store

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148638/16836" target="_top" id="2148638">
  <img src="//a.impactradius-go.com/display-ad/16836-2148638" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148638/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151894/7443" target="_top" id="2151894">
  <img src="//a.impactradius-go.com/display-ad/7443-2151894" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151894/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-streamlined-techniques-blur-background-on-chrome-os-and-ios/"><u>[New] 2024 Approved Streamlined Techniques Blur Background on Chrome OS & iOS</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-step-by-step-on-youtube-annotations/"><u>[New] A Step-by-Step on YouTube Annotations</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-digital-media-mapper/"><u>[New] In 2024, Digital Media Mapper</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-10-best-youtube-video-to-mp3-converter/"><u>[Updated] 10 Best YouTube Video to Mp3 Converter</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-correcting-faulty-windows-programs/"><u>Deciphering and Correcting Faulty Windows Programs</u></a></li>
<li><a href="https://driver-install.techidaily.com/expert-guide-to-overhauling-windows-audio-with-drivers/"><u>Expert Guide to Overhauling Windows Audio with Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-failed-logins-for-windows-sign-in-options/"><u>Fixing Failed Logins for Windows Sign-In Options</u></a></li>
<li><a href="https://win11.techidaily.com/handling-please-exit-problems-with-roblox-on-windows/"><u>Handling Please Exit Problems with Roblox on Windows</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-android-achieves-a-smart-adaptive-user-experience/"><u>How Android Achieves a Smart, Adaptive User Experience</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-honor-90-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-infinix-smart-7-hd-to-mac-drfone-by-drfone-android/"><u>In 2024, How to Mirror Infinix Smart 7 HD to Mac? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-updates-7-key-techniques/"><u>Mastering Windows Updates: 7 Key Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-tackling-broken-asana-features/"><u>Mastering Windows: Tackling Broken Asana Features</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-windows-netflix-usage/"><u>Streamline Your Windows Netflix Usage</u></a></li>
<li><a href="https://youtube-web.techidaily.com/reme-de-la-creativite-youtube-subscriber-list/"><u>The Crème De La Créativité YouTube Subscriber List</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-utorrent-unresponsive-on-win-devices/"><u>Troubleshooting: UTorrent Unresponsive on Win Devices</u></a></li>
<li><a href="https://win11.techidaily.com/why-16gb-ram-is-essential-for-modern-windows-systems/"><u>Why 16GB RAM Is Essential for Modern Windows Systems</u></a></li>
</ul></div>

