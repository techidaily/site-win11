---
title: Troubleshooting Non-Functional Store Apps in Windows 11
date: 2025-01-30T07:09:36.485Z
updated: 2025-02-04T02:43:40.710Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Troubleshooting Non-Functional Store Apps in Windows 11
excerpt: This Article Describes Troubleshooting Non-Functional Store Apps in Windows 11
keywords: Win11 App Issues,Functional Store Apps,Fixing App Problems,Windows App Troubleshoot,Non-Functioning Store App,Windows Store Repair,Optimize Windows 11 Shop
thumbnail: https://thmb.techidaily.com/2684d5fa5a1c919bbd381e1623060c80ce06ce75787ca76ee6f109f43567431f.jpg
---

## Troubleshooting Non-Functional Store Apps in Windows 11

 You may want to re-register built-in Windows apps if the Microsoft Store apps are not working. In other instances, issues with other Windows elements like Taskbar can be resolved by re-registering the built-in Windows apps.

 You can use a PowerShell cmdlet to perform this action. Here we show how you can re-register apps for individual or all accounts on Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for Current Users

![re register windows microsoft store apps current user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-windows-microsoft-store-apps-current-user.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0nGlyEL5K6Y?si=3KZhTTBvKcPmyS68" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Re-Register Microsoft Store Apps for All Users

![re register microsoft store apps all users](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/re-register-microsoft-store-apps-all-users.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you need to re-register the built-in Windows apps for all users, you’ll need to tweak the above PowerShell cmdlet a little to include the -AllUsers parameter. This would allow the cmdlet to search through all user accounts on the system and install and re-register the Microsoft Store apps.

1. [Open PowerShell as administrator](https://www.makeuseof.com/windows-11-powershell-administrator/) .
2. In the PowerShell window, type the following command and press**Enter** :  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`
3. This process may take some time to complete depending on the number of apps that require re-registering and reinstalling.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-the-quick-recovery-of-twitch-broadcasts/"><u>[New] 2024 Approved The Quick Recovery of Twitch Broadcasts</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-crafting-memes-with-ease-on-9gag-platform-for-2024/"><u>[New] Crafting Memes with Ease on 9GAG Platform for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/new-in-2024-master-iphone-video-editing-for-quick-clear-trims/"><u>[New] In 2024, Master iPhone Video Editing for Quick, Clear Trims</u></a></li>
<li><a href="https://hardware-help.techidaily.com/asus-maximus-x-hero-driver-maintenance-made-simple-and-swift-update-procedures-inside/"><u>ASUS Maximus X Hero Driver Maintenance Made Simple and Swift – Update Procedures Inside</u></a></li>
<li><a href="https://win11.techidaily.com/effective-booting-technique-startup-windows-unveil-notebooks/"><u>Effective Booting Technique: Startup Windows, Unveil Notebooks</u></a></li>
<li><a href="https://fox-helps.techidaily.com/elevate-your-images-mastering-text-on-pc-and-mac-photos/"><u>Elevate Your Images Mastering Text on PC & Mac Photos</u></a></li>
<li><a href="https://win11.techidaily.com/fasten-the-toggling-of-microsofts-taskbar-integrated-chat/"><u>Fasten the Toggling of Microsoft’s Taskbar-Integrated Chat</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-fixes-to-solve-apple-iphone-11-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/"><u>In 2024, Complete Fixes To Solve Apple iPhone 11 Randomly Asking for Apple ID Password | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-windows-11-notes-for-universal-accessibility/"><u>Optimize Windows 11 Notes for Universal Accessibility</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-addressing-launch-failed-lunar-client-issues/"><u>Techniques for Addressing “Launch Failed Lunar Client” Issues</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/top-online-tools-to-create-fake-faces-for-free-for-2024/"><u>Top Online Tools to Create Fake Faces for Free for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/triggers-for-launching-system-restore-in-windows-11-environment/"><u>Triggers for Launching System Restore in Windows 11 Environment</u></a></li>
</ul></div>

