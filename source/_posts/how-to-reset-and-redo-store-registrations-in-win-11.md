---
title: How to Reset and Redo Store Registrations in Win 11
date: 2024-06-25T10:16:25.036Z
updated: 2024-06-26T10:16:25.036Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Reset and Redo Store Registrations in Win 11
excerpt: This Article Describes How to Reset and Redo Store Registrations in Win 11
keywords: Windows 11 Registration Recovery,Win11 Update Store Settings,Resetting Microsoft Store,Redoing App Registrations,Win11 Store Fixes,Reinstalling Apps in Win11,Restore Win11 App Marketplace
thumbnail: https://thmb.techidaily.com/9f88f4d439bd19afe08962ae532d3a6f41b689b2a4dc10b0fa384c3313d41768.jpg
---

## How to Reset and Redo Store Registrations in Win 11

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
<li><a href="https://win11.techidaily.com/solving-the-puzzle-of-inaccessible-secure-boot-in-windows-bios/"><u>Solving the Puzzle of Inaccessible Secure Boot in Windows BIOS</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-unable-to-open-on-ges-sharing-feature/"><u>Remedy for Unable to Open on GE's Sharing Feature</u></a></li>
<li><a href="https://win11.techidaily.com/fingerprint-fiasco-can-you-still-count-on-windows-hello/"><u>Fingerprint Fiasco: Can You Still Count on Windows Hello?</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-large-archiving-tasks-with-windows-powershell-tips/"><u>Simplifying Large Archiving Tasks with Windows PowerShell Tips</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-ubiquitous-blue-screen-enigma/"><u>Overcoming the Ubiquitous Blue Screen Enigma</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-the-empty-directory-faux-pas-in-windows-a-guide-to-error-x80070091/"><u>Demystifying the 'Empty Directory' Faux Pas in Windows - A Guide to Error X80070091</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-credentials-a-fix-guide/"><u>Decoding Windows Credentials: A Fix Guide</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-storage-strategies-with-a-focus-on-windows-diskusage/"><u>Streamlining Storage Strategies with a Focus on Windows' DiskUsage</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-motorola-edge-40-neo-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From Motorola Edge 40 Neo to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-explore-the-limitless-potential-of-fb-vr-upload-tips-for-2024/"><u>[New] Explore the Limitless Potential of FB VR Upload Tips for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-blueprint-for-captivating-consumer-vlogs/"><u>2024 Approved  The Blueprint for Captivating Consumer Vlogs</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-2023s-guide-effortless-fb-post-planning-with-free-tools/"><u>[Updated] 2023'S Guide  Effortless FB Post Planning with Free Tools</u></a></li>
<li><a href="https://extra-hints.techidaily.com/photo-fusion-mastery-windows-users-guide/"><u>Photo Fusion Mastery  Windows Users Guide</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>In 2024, How does the stardust trade cost In pokemon go On Apple iPhone 11? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/enhance-and-unblur-photo-editing-tools-ranked-1-10/"><u>Enhance and Unblur  Photo Editing Tools Ranked #1-10</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-essential-tips-for-free-youtube-video-transcriptions/"><u>[Updated] Essential Tips for FREE YouTube Video Transcriptions</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-lava-storm-5g-pin-by-drfone-android-unlock-android-unlock/"><u>How to remove Lava Storm 5G PIN</u></a></li>
</ul></div>
