---
title: Reset & Reboot Your Way Back Into the MS Store (Windows 11)
date: 2024-06-25T11:31:15.114Z
updated: 2024-06-26T11:31:15.114Z
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
<li><a href="https://win11.techidaily.com/opening-your-canvas-microsoft-paint-on-windows-11/"><u>Opening Your Canvas: Microsoft Paint on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-rectify-virtualboxs-efail-windows-issue-0x80004005/"><u>Tips to Rectify Virtualbox's E_FAIL (Windows) Issue: 0X80004005</u></a></li>
<li><a href="https://win11.techidaily.com/traversing-through-system-failsafe-files-after-blue-screen/"><u>Traversing Through System Failsafe Files After Blue Screen</u></a></li>
<li><a href="https://win11.techidaily.com/5-simple-ways-to-unlock-startup-repairs-in-windows/"><u>5 Simple Ways to Unlock Startup Repairs in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-hover-over-sensitivity-and-trail-in-windows-11/"><u>Perfect Your Hover Over Sensitivity and Trail in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unwavering-erasure-made-simple-configuring-windows-trash-for-permanent-deletion/"><u>Unwavering Erasure Made Simple: Configuring Windows Trash for Permanent Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-solving-error-0x80073d26-in-xbox-app/"><u>Mastering the Art of Solving Error 0X80073D26 in Xbox App</u></a></li>
<li><a href="https://win11.techidaily.com/breath-of-fresh-air-reviving-outdated-microsoft-store-apps/"><u>Breath of Fresh Air: Reviving Outdated Microsoft Store Apps</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/mastering-vimeo-recorder-capturing-screens-and-cameras-on-streams-for-2024/"><u>Mastering Vimeo Recorder  Capturing Screens & Cameras on Streams for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-explore-innovative-ways-for-sound-capture-in-modern-windows-11-pcs/"><u>[New] Explore Innovative Ways for Sound Capture in Modern Windows 11 PCs</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unlocking-youtube-success-with-the-right-networking-choice/"><u>[New] Unlocking YouTube Success with the Right Networking Choice</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-no-more-shakes-top-free-video-stabilizer-apps-for-android-phones/"><u>New 2024 Approved No More Shakes Top Free Video Stabilizer Apps for Android Phones</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-full-breakdown-razers-hd-webcam-experience/"><u>[Updated] Full Breakdown  Razer's HD Webcam Experience</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/complete-guide-2024-a-review-on-3d-lut-creator/"><u>Complete Guide 2024 A Review On 3D LUT Creator</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-alternate-avenues-10-great-games-like-gta-v/"><u>[Updated] 2024 Approved  Alternate Avenues  10 Great Games Like GTA V</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/unify-your-visuals-a-step-by-step-color-matching-tutorial-for-powerdirector-for-2024/"><u>Unify Your Visuals A Step-by-Step Color Matching Tutorial for PowerDirector for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-unleash-potential-in-online-engagement-through-zoom-screenshares-for-2024/"><u>[Updated] Unleash Potential in Online Engagement Through Zoom Screenshares for 2024</u></a></li>
</ul></div>
