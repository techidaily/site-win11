---
title: Reactivating Your MS Store Applications in Windows OSes
date: 2024-11-02T17:48:37.216Z
updated: 2024-11-07T23:35:11.266Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Your MS Store Applications in Windows OSes
excerpt: This Article Describes Reactivating Your MS Store Applications in Windows OSes
keywords: Reactivate MS Store,Reopen MS Apps,Resume MSOS Games,Restart Microsoft Services,Fix MS Store Errors,Boot MS Windows Apps,Recover OS-MS Programs
thumbnail: https://thmb.techidaily.com/c856d755f3f7d2c0f103fd6d2cd384857bef4cae5585cde42e136d87338a8911.jpg
---

## Reactivating Your MS Store Applications in Windows OSes

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
<a href="https://appsumo.8odi.net/c/5597632/2105863/7443" target="_top" id="2105863">
  <img src="//a.impactradius-go.com/display-ad/7443-2105863" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105863/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136615/26400" target="_top" id="2136615">
  <img src="//a.impactradius-go.com/display-ad/26400-2136615" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136615/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037318/7443" target="_top" id="2037318">
  <img src="//a.impactradius-go.com/display-ad/7443-2037318" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037318/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-tips.techidaily.com/new-in-2024-premier-video-cutting-software-recommendations-for-windows-users/"><u>[New] In 2024, Premier Video Cutting Software Recommendations for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/1-quick-and-simple-guide-downloading-and-setting-up-showbox-on-your-computer/"><u>1. Quick & Simple Guide: Downloading & Setting Up ShowBox on Your Computer</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-sparkle-in-your-ads-20-most-effective-marketing-terms/"><u>2024 Approved Sparkle in Your Ads 20 Most Effective Marketing Terms</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-the-ultimate-list-of-8-free-video-editing-programs-for-creatives/"><u>2024 Approved The Ultimate List of 8 FREE Video Editing Programs for Creatives</u></a></li>
<li><a href="https://win11.techidaily.com/handling-runtime-failure-tips-for-correcting-malwarebytes-execution-errors-on-win10win11/"><u>Handling Runtime Failure: Tips for Correcting Malwarebytes' Execution Errors on Win10/Win11</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-share-location-in-messenger-on-realme-11-5g-drfone-by-drfone-virtual-android/"><u>How to Share Location in Messenger On Realme 11 5G? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208249116-how-to-troubleshoot-pc-game-crashes-in-nier-automata-solved/"><u>How to Troubleshoot PC Game Crashes in Nier: Automata - Solved</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-realme-c33-2023mirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Realme C33 2023Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-unveiling-top-7-adblocker-apps-for-android-users/"><u>In 2024, Unveiling Top 7 AdBlocker Apps for Android Users</u></a></li>
<li><a href="https://win11.techidaily.com/intel-unison-not-working-try-this-fix-guide-on-windows-11/"><u>Intel Unison Not Working? Try This Fix Guide on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-notes-at-the-forefront-on-win-oses/"><u>Keep Your Notes at the Forefront on Win OSes</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/meet-the-new-wave-of-audio-introducing-flexus-200/"><u>Meet the New Wave of Audio: Introducing Flexus 200</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-search-troubleshooting-steps/"><u>Navigating Through Windows Search Troubleshooting Steps</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-win11-vagrant-start-issues-with-7-effective-approaches/"><u>Resolve Win11 Vagrant Start Issues with 7 Effective Approaches</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-transition-getting-started-with-outlook-preview-on-windows-11/"><u>Seamless Transition: Getting Started with Outlook Preview on Windows 11</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/swiftly-assemble-a-stunning-google-image-mosaic-with-ease/"><u>Swiftly Assemble a Stunning Google Image Mosaic with Ease</u></a></li>
</ul></div>

