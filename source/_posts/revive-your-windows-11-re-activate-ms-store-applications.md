---
title: "Revive Your Windows 11: Re-Activate MS Store Applications"
date: 2024-07-02T13:01:37.690Z
updated: 2024-07-03T13:01:37.690Z
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
<li><a href="https://win11.techidaily.com/experience-refined-creativity-with-microsofts-latest-paint-features/"><u>Experience Refined Creativity with Microsoft's Latest Paint Features</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-incorporating-folders-in-win11-ui/"><u>Techniques for Incorporating Folders in Win11 UI</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-pc-repair-access-with-windows-troubleshooting-hotkeys/"><u>Enhancing PC Repair Access with Windows Troubleshooting Hotkeys</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-remote-desktop-failures-in-current-windows/"><u>Addressing Remote Desktop Failures in Current Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-mitigating-roblox-error-403-for-pc-users/"><u>Understanding & Mitigating Roblox Error 403 for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-potential-with-microsofts-pc-manager-in-win11/"><u>Unlocking Potential with Microsoft's PC Manager in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-error-x0001-in-windows-devices/"><u>Strategies for Overcoming Error X0001 in Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/1719289257399-black-friday-top-keys-fan-secrets-for-free-windows-11-at-612lifetime/"><u>Black Friday: Top Keys Fan Secrets for Free Windows 11 at $6.12/Lifetime!</u></a></li>
<li><a href="https://win11.techidaily.com/swift-resolution-to-hypervisor-errors-for-winxose-users/"><u>Swift Resolution to Hypervisor Errors for WINXOSE Users</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-entertainment-software-deep-dive/"><u>[New] 2024 Approved  Entertainment Software Deep Dive</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-pooch-pulses-and-vocalizations-a-comprehensive-collection-for-creatives/"><u>2024 Approved Pooch Pulses & Vocalizations A Comprehensive Collection for Creatives</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-creating-engaging-youtube-trailers-in-filmora-for-2024/"><u>[Updated] Creating Engaging YouTube Trailers in Filmora for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-honor-magic-5-pro-is-unlocked-by-drfone-android/"><u>How To Check if Your Honor Magic 5 Pro Is Unlocked</u></a></li>
<li><a href="https://audio-editing.techidaily.com/audiophiles-guide-to-clear-audio-overcoming-background-sibilance-and-hum/"><u>Audiophiles Guide to Clear Audio Overcoming Background Sibilance and Hum</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unlock-the-power-of-spotifys-advertising-potential/"><u>Unlock the Power of Spotify’s Advertising Potential</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-virtual-visions-versus-tangible-tools-in-streaming/"><u>[Updated] In 2024, Virtual Visions Versus Tangible Tools in Streaming</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-devices-to-device-guide-for-google-meet-participation/"><u>[New] 2024 Approved  Devices to Device Guide for Google Meet Participation</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-gopro-vlogging-101-techniques-for-a-polished-look/"><u>[Updated] GoPro Vlogging 101  Techniques for a Polished Look</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-top-tweets-on-screen-expert-guide-for-capturing-vids/"><u>[Updated] In 2024, Top Tweets on Screen  Expert Guide for Capturing Vids</u></a></li>
</ul></div>
