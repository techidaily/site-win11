---
title: "Revive Your Windows 11: Re-Activate MS Store Applications"
date: 2024-06-25T10:22:32.025Z
updated: 2024-06-26T10:22:32.025Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revive Your Windows 11: Re-Activate MS Store Applications"
excerpt: "This Article Describes Revive Your Windows 11: Re-Activate MS Store Applications"
keywords: Reactivate W11 MSStore,Reset Windows 11 Apps,Revive Windows Store,Update MSStore,Fix Windows App Error,Re-Activate W11 Store,Restart W11 MSApps
thumbnail: https://thmb.techidaily.com/371f85ea9dfa1babb000dca91773b4eb09149fff5b762b5c34efcbd5187b5306.jpg
---

## Revive Your Windows 11: Re-Activate MS Store Applications

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
<li><a href="https://win11.techidaily.com/accessing-windows-11s-security-six-pathways-for-safe-mode/"><u>Accessing Windows 11'S Security: Six Pathways for Safe Mode</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-pc-graphics-with-optimal-vram-settings/"><u>Transform Your PC Graphics with Optimal VRAM Settings</u></a></li>
<li><a href="https://win11.techidaily.com/enable-microphone-and-camera-via-app-guard-in-windows-11/"><u>Enable Microphone & Camera via App Guard in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/learn-how-to-turn-off-games-for-w11-suggestions/"><u>Learn How To Turn Off Games for W11 Suggestions</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-halting-windows-boot-straight-into-cmos-setup/"><u>Techniques for Halting Windows Boot Straight Into CMOS Setup</u></a></li>
<li><a href="https://win11.techidaily.com/the-essentials-of-windows-cab-files-purpose-and-installation-tactics/"><u>The Essentials of Windows CAB Files: Purpose & Installation Tactics</u></a></li>
<li><a href="https://win11.techidaily.com/ignite-your-pc-bypassing-windows-11-lag-and-latency/"><u>Ignite Your PC: Bypassing Windows 11 Lag & Latency</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-crowded-taskbar-image-space-in-windows-11/"><u>Resetting Crowded Taskbar Image Space in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/auto-shutdown-hacks-for-idle-pcs-running-w10w11/"><u>Auto Shutdown Hacks for Idle PCs Running W10/W11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-the-best-practices-for-recording-apex-heroes/"><u>[Updated] In 2024, The Best Practices for Recording Apex Heroes</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-laptop-friendly-tips-to-start-live-chats-with-whatsapp-desktop/"><u>2024 Approved  Laptop-Friendly Tips to Start Live Chats with WhatsApp Desktop</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Realme 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/investigating-alternatives-to-popular-video-broadcaster/"><u>Investigating Alternatives to Popular Video Broadcaster</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-examining-performance-of-dji-raptor-eyewear/"><u>[New] Examining Performance of DJI Raptor Eyewear</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-navigating-through-video-editing-delight-filmoras-core-traits/"><u>[New] Navigating Through Video Editing Delight  Filmora's Core Traits</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-gear-showdown-2022-hero5-vs-garmin-streaming-cameras/"><u>[New] Gear Showdown 2022  Hero5 Vs. Garmin Streaming Cameras</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-maximizing-zoom-collaboration-essential-setup-tips/"><u>2024 Approved  Maximizing Zoom Collaboration  Essential Setup Tips</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/exciting-auto-play-hits-for-children/"><u>Exciting Auto-Play Hits for Children</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-infinix-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from Infinix</u></a></li>
</ul></div>
