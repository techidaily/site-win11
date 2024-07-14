---
title: "Breath of Fresh Air: Reviving Outdated Microsoft Store Apps"
date: 2024-07-13T10:02:22.479Z
updated: 2024-07-14T10:02:22.479Z
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

 If the [Microsoft Store app issue](https://www.makeuseof.com/tag/5-tips-fix-windows-store-app-issues-windows-10/) exists with a specific user account, you don’t need to re-register the app for all the user accounts on your computer. Instead, you can re-register the app only for the current user account.

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
<li><a href="https://win11.techidaily.com/declutter-your-computer-finding-and-purging-windows-empties/"><u>Declutter Your Computer: Finding & Purging Windows' Empties</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-simplify-tech-transitions-smartphone-vr-integration-guide/"><u>[Updated] In 2024, Simplify Tech Transitions  Smartphone-VR Integration Guide</u></a></li>
<li><a href="https://win11.techidaily.com/procedure-opening-driver-verifier-for-fault-analysis/"><u>Procedure: Opening Driver Verifier for Fault Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-prohibited-application-red-flag-in-windows/"><u>Fixing the Prohibited Application Red Flag in Windows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-peer-reviewed-best-action-replay-tech/"><u>2024 Approved  Peer-Reviewed Best Action Replay Tech</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-backwards-play-mastering-youtube-video-reversals/"><u>[Updated] Backwards Play  Mastering YouTube Video Reversals</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-device-engagement-in-power-save-mode/"><u>Maximizing Device Engagement in Power Save Mode</u></a></li>
<li><a href="https://win11.techidaily.com/advancing-windows-experience-the-significance-of-16gb-ram/"><u>Advancing Windows Experience: The Significance of 16GB RAM</u></a></li>
<li><a href="https://win11.techidaily.com/old-wallpapers-no-more-discover-three-solutions/"><u>Old Wallpapers No More! Discover Three Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/your-quick-reference-to-fixing-windows-photo-application/"><u>Your Quick Reference to Fixing Window's Photo Application</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-resolution-of-windows-activation-flaw-0x803f700f/"><u>Mastering the Resolution of Windows Activation Flaw 0X803F700f</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unresponsive-touch-screen-on-tecno-camon-30-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Touch Screen on Tecno Camon 30 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-list-of-windows-most-reliable-usage-monitors/"><u>Exclusive List of Windows' Most Reliable Usage Monitors</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-checklist-12-must-have-cameras-for-vlogging-professionals/"><u>2024 Approved  The Ultimate Checklist  12 Must-Have Cameras for Vlogging Professionals</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-and-resolve-windows-error-code-0xc00000f-quickly/"><u>Avoid and Resolve Windows Error Code: 0Xc00000f Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-to-do-management-in-the-microsoft-ecosystem/"><u>Mastering To-Do Management in the Microsoft Ecosystem</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-inability-to-install-windows-store-apps/"><u>Resolving Inability to Install Windows Store Apps</u></a></li>
<li><a href="https://techidaily.com/reset-pattern-lock-tutorial-for-oppo-find-x7-by-drfone-android-unlock-android-unlock/"><u>Reset pattern lock Tutorial for Oppo Find X7</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-unveiling-the-secrets-to-link-sharing-on-instagram/"><u>In 2024, Unveiling the Secrets to Link Sharing on Instagram</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-quick-start-downloading-and-using-tiktok-on-macbook-for-2024/"><u>[Updated] Quick Start  Downloading and Using TikTok on MacBook for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/ready-for-success-testing-your-meeting-tech-on-windows/"><u>Ready for Success: Testing Your Meeting Tech on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-regain-windows-11-help-application-use/"><u>Steps to Regain Windows 11 Help Application Use</u></a></li>
<li><a href="https://win11.techidaily.com/windows-update-halted-by-error-2e-solutions-here/"><u>Windows Update Halted by Error 2E? Solutions Here</u></a></li>
<li><a href="https://win11.techidaily.com/biometric-management-for-windows-11-domain-based/"><u>Biometric Management for Windows 11, Domain-Based</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Realme 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-error-xc0000142-in-microsoft-oses/"><u>Remedying Error XC0000142 in Microsoft OSes</u></a></li>
<li><a href="https://audio-editing.techidaily.com/elevating-calmness-low-impact-noise-reduction-techniques-in-premiere-pro-for-2024/"><u>Elevating Calmness Low-Impact Noise Reduction Techniques in Premiere Pro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-no-powershell-on-windows-system/"><u>Troubleshooting: No PowerShell on Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/the-essence-of-devhome-transforming-your-w11-experience/"><u>The Essence of DevHome: Transforming Your W11 Experience</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-realme-12plus-5g-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Realme 12+ 5G? | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-elevating-engagement-with-innovative-techniques-in-fb-lives-for-2024/"><u>[Updated] Elevating Engagement with Innovative Techniques in FB Lives for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-exploring-earning-potential-an-uncomplicated-triad-technique-for-youtube-profit-analysis/"><u>[New] In 2024, Exploring Earning Potential  An Uncomplicated Triad Technique for YouTube Profit Analysis</u></a></li>
<li><a href="https://win11.techidaily.com/quicken-real-time-update-of-task-manager-in-win-11/"><u>Quicken Real-Time Update of Task Manager in Win 11</u></a></li>
</ul></div>
