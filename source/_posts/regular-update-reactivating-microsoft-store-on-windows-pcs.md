---
title: "Regular Update: Reactivating Microsoft Store on Windows PCs"
date: 2025-01-16T21:21:00.867Z
updated: 2025-01-19T00:23:40.555Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Regular Update: Reactivating Microsoft Store on Windows PCs"
excerpt: "This Article Describes Regular Update: Reactivating Microsoft Store on Windows PCs"
keywords: Reactivate MS Store,Re-Enable MS Store,MS Store Revival,Microsoft Store Update,Restore MS Store,Accessing MS Store,Windows Store Activation
thumbnail: https://thmb.techidaily.com/9c252b23b1e3ad8357c15bea477480a8c23a36edb5cd9b4be147d76d8870fe38.jpg
---

## Regular Update: Reactivating Microsoft Store on Windows PCs

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-docs.techidaily.com/ed-start-streaming-sports-creating-your-own-mac-based-channel/"><u>[Updated] Start Streaming Sports Creating Your Own Mac-Based Channel</u></a></li>
<li><a href="https://fox-tls.techidaily.com/1728462664217-pc/"><u>問題なし：PC内ではシステムイメージを発見不可</u></a></li>
<li><a href="https://facebook.techidaily.com/facebook-flips-the-script-with-weekend-live-selling/"><u>Facebook Flips the Script with Weekend Live-Selling</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On OnePlus Nord CE 3 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-wsl-removal-in-win-1011/"><u>Mastering WSL Removal in Win 10/11</u></a></li>
<li><a href="https://win-reviews.techidaily.com/mp4-video-downloads-from-artistworks-save-your-favorite-lessons/"><u>MP4 Video Downloads From ArtistWorks - Save Your Favorite Lessons</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-systemic-resource-clashes-in-technology/"><u>Resolving Systemic Resource Clashes in Technology</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/screen-recorder-showdown-apoyser-vs-emerging-alternatives-review-for-2024/"><u>Screen Recorder Showdown Apoyser Vs Emerging Alternatives Review for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-upgrade-for-sluggish-microsoft-edge-on-win10plus11/"><u>Speedy Upgrade for Sluggish Microsoft Edge on Win10+11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-disabling-winos-gfx-tasking/"><u>Step-by-Step: Disabling WinOS GFX Tasking</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-library-loading-problem-87-in-windows/"><u>Steps to Resolve Library Loading Problem 87 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/stutter-free-screenplay-essential-steps-for-a-seamless-windows-media/"><u>Stutter-Free Screenplay: Essential Steps for a Seamless Windows Media</u></a></li>
<li><a href="https://win11.techidaily.com/win11-unwaking-from-sleep-with-input-devices/"><u>Win11: Unwaking From Sleep with Input Devices</u></a></li>
</ul></div>

