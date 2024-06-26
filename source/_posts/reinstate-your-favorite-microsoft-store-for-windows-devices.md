---
title: Reinstate Your Favorite Microsoft Store for Windows Devices
date: 2024-06-25T10:24:06.613Z
updated: 2024-06-26T10:24:06.613Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reinstate Your Favorite Microsoft Store for Windows Devices
excerpt: This Article Describes Reinstate Your Favorite Microsoft Store for Windows Devices
keywords: WinStore Restore,MSFT Store Access,Reinstate MSOFT,Windows Device Hub,Devices Store Fix,Microsoft Window Support,Retrieve MStores
thumbnail: https://thmb.techidaily.com/3be6004f814f322eb7c81e59f5f3e6dc5377a1a28f18fb94887b3ff8d1dce543.jpg
---

## Reinstate Your Favorite Microsoft Store for Windows Devices

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
<li><a href="https://win11.techidaily.com/creating-a-personalized-windows-speech-to-text-app-using-whisper-and-ahk/"><u>Creating a Personalized Windows Speech-to-Text App Using Whisper & AHK</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-global-communication-hotkeys-for-windows-language-switch/"><u>Optimizing Global Communication: Hotkeys for Windows Language SwitcH</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-android-windows-webcam-transition-techniques/"><u>Seamless Android-Windows Webcam Transition Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-retry-interval-for-unsuccessful-login-attempts/"><u>Adjusting Retry Interval for Unsuccessful Login Attempts</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-linux-vm-setup-with-windows-and-hyper-v-integration/"><u>Streamlining Linux VM Setup with Windows and Hyper-V Integration</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-windows-11-installation-with-these-essential-tweaks/"><u>Streamline Your Windows 11 Installation with These Essential Tweaks</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-fixes-for-defenders-error-code-0x80004004/"><u>Unveiling Fixes for Defender’s Error Code: 0X80004004</u></a></li>
<li><a href="https://win11.techidaily.com/three-methods-for-exploring-windows-policy-settings/"><u>Three Methods for Exploring Windows Policy Settings</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-free-vs-paid-gaming-entrances-top-12-insights-for-youtube-gamers/"><u>[New] In 2024, Free vs Paid Gaming Entrances  Top 12 Insights for YouTube Gamers</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-xiaomi-redmi-12-5g-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/social-media-savvy-the-best-25-hashtags-for-likes-and-followers-for-2024/"><u>Social Media Savvy  The Best 25 Hashtags for Likes and Followers for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-xiaomi-redmi-note-12-5g-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Xiaomi Redmi Note 12 5G Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/android-unlock-code-sim-unlock-your-realme-narzo-60-pro-5g-phone-and-remove-locked-screen-by-drfone-android/"><u>Android Unlock Code Sim Unlock Your Realme Narzo 60 Pro 5G Phone and Remove Locked Screen</u></a></li>
<li><a href="https://extra-hints.techidaily.com/combat-blurry-iphone-hdri-4-pivotal-tips-for-premiere-pro-users/"><u>Combat Blurry iPhone HDRI  4 Pivotal Tips for Premiere Pro Users</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/complete-how-to-embedding-srt-tracks-into-mp4-media-2024/"><u>Complete How-To  Embedding SRT Tracks Into MP4 Media 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-on-oppo-find-x6-pro-by-drfone-android/"><u>How to Bypass FRP on Oppo Find X6 Pro?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instagram-soundtracks-law-and-ethics-for-2024/"><u>Instagram Soundtracks  Law & Ethics for 2024</u></a></li>
</ul></div>
