---
title: Reset & Reboot Your Way Back Into the MS Store (Windows 11)
date: 2024-06-25T10:09:59.282Z
updated: 2024-06-26T10:09:59.282Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reset & Reboot Your Way Back Into the MS Store (Windows 11)
excerpt: This Article Describes Reset & Reboot Your Way Back Into the MS Store (Windows 11)
keywords: Reset MS Store,Reboot Windows 11,MS Store Access,Boot PC for MS,Restore Windows,Reinstall MS Store,Startup Repair MS
thumbnail: https://thmb.techidaily.com/07f3d5f057a0a1f3c1d2492add732e27fc47138ba4a1808a078297c558520a47.png
---

## Reset & Reboot Your Way Back Into the MS Store (Windows 11)

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
<li><a href="https://win11.techidaily.com/how-to-change-what-the-fn-keys-do-in-windows-11-and-11/"><u>How to Change What the Fn Keys Do in Windows 11 and 11</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-apples-calendar-in-a-win1011-setup/"><u>Leveraging Apple's Calendar in a Win10/11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/modifying-account-lockout-tally-post-unsuccessful-login-attempts-in-windows-1011/"><u>Modifying Account Lockout Tally Post Unsuccessful Login Attempts in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/learn-win-11s-network-proxy-configuration/"><u>Learn Win 11'S Network Proxy Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-restrictions-disabling-signatures-adding-unsigned-drivers/"><u>Navigating Windows' Restrictions: Disabling Signatures, Adding Unsigned Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/solving-disabled-network-visibility-in-windows/"><u>Solving Disabled Network Visibility in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719302097899-opera-on-windows-end-the-stalling-spectacle-now/"><u>Opera on Windows: End the Stalling Spectacle Now!</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-the-art-of-recording-tiktok-videos-expert-insights-and-filmmaking-magic/"><u>[New] The Art of Recording TikTok Videos  Expert Insights and Filmmaking Magic</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unleash-creative-potential-using-storyremix-for-windows-11s-photo-videos/"><u>In 2024, Unleash Creative Potential  Using StoryRemix for Windows 11'S Photo Videos</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-the-ultimate-list-10-online-gaming-intro-designers/"><u>Updated 2024 Approved The Ultimate List 10 Online Gaming Intro Designers</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-5-quick-methods-to-bypass-infinix-note-30-pro-frp-by-drfone-android/"><u>In 2024, 5 Quick Methods to Bypass Infinix Note 30 Pro FRP</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-free-windows-software-perfect-tv-recording-techniques-for-2024/"><u>[Updated] Free Windows Software  Perfect TV Recording Techniques for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oneplus-nord-ce-3-lite-5g-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from OnePlus Nord CE 3 Lite 5G To Phone | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unleash-creativity-a-comprehensive-guide-to-movie-maker-on-windows-11/"><u>[New] Unleash Creativity  A Comprehensive Guide to Movie Maker on Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-accelerated-windows-review-strategies/"><u>2024 Approved  Accelerated Windows Review Strategies</u></a></li>
</ul></div>
