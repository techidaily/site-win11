---
title: How to Re-Register Microsoft Store Apps on Windows 10 & 11
date: 2024-11-01T04:11:36.536Z
updated: 2024-11-02T00:40:21.085Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Re-Register Microsoft Store Apps on Windows 10 & 11
excerpt: This Article Describes How to Re-Register Microsoft Store Apps on Windows 10 & 11
keywords: Regain MS Store Access,Restore Windows Store Apps,Resetting MS Store License,Reinstate Microsoft Store,Redoing MS App Registration,Fixing MS Store on W10/W11,Unlocking MS Store for PC
thumbnail: https://thmb.techidaily.com/1da8846cbd836d9712f7b59a73630f863ec9ad2fa528ea4ddf23335f3fc8b9a6.png
---

## How to Re-Register Microsoft Store Apps on Windows 10 & 11

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130533/26400" target="_top" id="2130533">
  <img src="//a.impactradius-go.com/display-ad/26400-2130533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130533/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407">
  <img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/977686/11832" target="_top" id="977686">
  <img src="//a.impactradius-go.com/display-ad/11832-977686" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/977686/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-achieve-cinematic-gaming-with-advanced-steam-recordings/"><u>[New] 2024 Approved Achieve Cinematic Gaming with Advanced Steam Recordings</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-monthly-income-for-content-creators-on-youtube/"><u>[Updated] In 2024, Monthly Income for Content Creators on YouTube?</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-effective-win-11-sandbox-setup/"><u>Essential Tips for Effective Win 11 Sandbox Setup</u></a></li>
<li><a href="https://app-tips.techidaily.com/exploring-the-future-with-linus-insights-on-artificebotics-rust-programming-and-why-linux-is-crucial-zdnet/"><u>Exploring the Future with Linus: Insights on Artificebotics, Rust Programming, and Why Linux Is Crucial | ZDNET</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-initiating-a-pure-boot-in-windows-11/"><u>Guide to Initiating a Pure Boot in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-configure-a-windows-hello-fingerprint-login-on-windows-11/"><u>How to Configure a Windows Hello Fingerprint Login on Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-top-6-ways-to-transfer-text-messages-from-huawei-p60-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Top 6 Ways to Transfer Text Messages from Huawei P60 to Other Android Devices | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-terminals-administrator-barrier/"><u>Navigating Windows Terminal's Administrator Barrier</u></a></li>
<li><a href="https://win11.techidaily.com/proper-techniques-for-auditory-and-visual-recordings-using-the-snipping-tool-in-windows-11-max-156/"><u>Proper Techniques for Auditory & Visual Recordings Using the Snipping Tool in Windows 11 (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/resurrect-corrupted-files-win-11s-zip-fix-guide/"><u>Resurrect Corrupted Files: Win 11'S ZIP Fix Guide</u></a></li>
<li><a href="https://android-unlock.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-motorola-moto-g-stylus-2023-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Motorola Moto G Stylus (2023)</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/swiftly-stow-facebook-broadcasts-for-smartphonedesktop-users/"><u>Swiftly Stow Facebook Broadcasts for Smartphone/Desktop Users</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/taking-flight-with-creativity-a-comprehensive-review-of-the/"><u>Taking Flight with Creativity: A Comprehensive Review of The</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ultimate-guide-to-generating-artificn-with-chatgpts-assistance/"><u>The Ultimate Guide to Generating Artificn with ChatGPT's Assistance</u></a></li>
</ul></div>

