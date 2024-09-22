---
title: Renewal Guide for Reinstating Apps From the Microsoft Store
date: 2024-09-18T23:57:10.114Z
updated: 2024-09-21T22:49:11.245Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Renewal Guide for Reinstating Apps From the Microsoft Store
excerpt: This Article Describes Renewal Guide for Reinstating Apps From the Microsoft Store
keywords: Reinstall Windows Apps,MS Store App Restore,Redownload Apps,Revive Microsoft Store,Restore Apps in Store,Recycle Bin for Apps,Microsoft App Reinstatement Guide
thumbnail: https://thmb.techidaily.com/d222a947a358a9a5da5a72c775e634907e671d005e0a2808f2ac3a2ab7305bec.jpg
---

## Renewal Guide for Reinstating Apps From the Microsoft Store

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
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-igtvs-power-boosters-crafting-viral-hash-tags/"><u>[New] In 2024, IGTV's Power Boosters Crafting Viral Hash Tags</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-the-ultimate-list-of-6-instagram-reel-enhancers/"><u>[New] In 2024, The Ultimate List of 6 Instagram Reel Enhancers</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-making-your-videoclips-stand-out-with-easy-text-addition/"><u>[Updated] Making Your Videoclips Stand Out with Easy Text Addition</u></a></li>
<li><a href="https://some-guidance.techidaily.com/customized-advertising-solutions-optimized-with-the-latest-from-cookiebot/"><u>Customized Advertising Solutions: Optimized with the Latest From Cookiebot</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-itel-p40-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Itel P40? | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/ice-racers-unite-celebrating-snowboard-cross-victories-winter-olympics-edition/"><u>Ice Racers Unite Celebrating Snowboard Cross Victories, Winter Olympics Edition</u></a></li>
<li><a href="https://network-issues.techidaily.com/reverse-win11-blank-screen-hack/"><u>Reverse WIN11 Blank Screen Hack</u></a></li>
<li><a href="https://win11.techidaily.com/simple-guide-converting-your-dvd-files-into-avi-with-no-hassle/"><u>Simple Guide: Converting Your DVD Files Into AVI with No Hassle!</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-converting-vpj-files-into-mp4-format-using-videopad/"><u>Step-by-Step Guide: Converting VPJ Files Into MP4 Format Using VideoPad</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-instructions-effortless-installation-of-showbox-app-on-windowsmac-pc/"><u>Step-by-Step Instructions: Effortless Installation of ShowBox App on Windows/Mac PC</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-flawless-mkv-playback-with-chromecast-streaming/"><u>The Ultimate Guide to Flawless MKV Playback with Chromecast Streaming</u></a></li>
<li><a href="https://win11.techidaily.com/top-ranking-windows-11-media-converter-effortlessly-transform-dvds-into-mp4-mkv-and-more/"><u>Top-Ranking Windows 11 Media Converter: Effortlessly Transform DVDs Into MP4, MKV, and More</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087253/19272" target="_top" id="2087253">
  <img src="//a.impactradius-go.com/display-ad/19272-2087253" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087253/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

