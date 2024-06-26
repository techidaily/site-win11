---
title: "Breath of Fresh Air: Reviving Outdated Microsoft Store Apps"
date: 2024-06-25T09:58:03.679Z
updated: 2024-06-26T09:58:03.679Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Breath of Fresh Air: Reviving Outdated Microsoft Store Apps"
excerpt: "This Article Describes Breath of Fresh Air: Reviving Outdated Microsoft Store Apps"
keywords: Fresh Store Updates,Old MS App Renewal,Modernize MS Store,Refresh App Lifecycle,Update Microsoft Suite,Redesign MS Apps,Clean OS App Revamp
thumbnail: https://thmb.techidaily.com/300b8b150f8464b487683b06984fcbd6662b4fb116965638afb915b9861f6dbd.jpg
---

## Breath of Fresh Air: Reviving Outdated Microsoft Store Apps

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
<li><a href="https://win11.techidaily.com/exploring-the-distinctions-windows-10-vs-windows-11-features/"><u>Exploring the Distinctions: Windows 10 Vs. Windows 11 Features</u></a></li>
<li><a href="https://win11.techidaily.com/unable-to-install-the-microsoft-pc-manager-on-windows-try-these-7-fixes/"><u>Unable to Install the Microsoft PC Manager on Windows? Try These 7 Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-sudden-freeze-and-blackout-with-steam/"><u>Resolving Sudden Freeze & Blackout with Steam</u></a></li>
<li><a href="https://win11.techidaily.com/guiding-through-correction-processes-for-faulty-win11-registry-data/"><u>Guiding Through Correction Processes for Faulty Win11 Registry Data</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-the-windows-access-denied-error-code-0x80070522/"><u>Correcting the Windows Access Denied Error: Code 0X80070522</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-easily-uninstall-applications-in-win-11/"><u>Breaking Barriers: Easily Uninstall Applications in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/must-know-factors-a-consumers-checklist-for-buying-a-win-laptop/"><u>Must-Know Factors: A Consumer's Checklist for Buying a Win Laptop</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-obs-full-screen-no-more-problem/"><u>[Updated] Obs Full-Screen No More Problem</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-score-selection-service-enhancing-media-pieces/"><u>[New] Score Selection Service  Enhancing Media Pieces</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-oneplus-ace-3-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-dating-bliss-on-the-most-popular-discord-channels/"><u>2024 Approved  Dating Bliss on the Most Popular Discord Channels</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-optimal-video-recording-best-fullscreen-tools-for-pcmac/"><u>2024 Approved  Optimal Video Recording  Best Fullscreen Tools for PC/Mac</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-microtones-and-monikers-shorts-sound-roles/"><u>[New] Microtones and Monikers  Shorts' Sound Roles</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-best-android-options-10-gb-emulation-tools-for-2024/"><u>[New] Best Android Options  10 GB Emulation Tools for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-a-beginners-guide-to-understanding-youtube-responses/"><u>2024 Approved  A Beginner's Guide to Understanding YouTube Responses</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-dissonant-designs-mastering-on-a-mac/"><u>2024 Approved  Dissonant Designs  Mastering on a Mac</u></a></li>
</ul></div>
