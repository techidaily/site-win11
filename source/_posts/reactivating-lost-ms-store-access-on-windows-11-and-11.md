---
title: Reactivating Lost MS Store Access on Windows 11 & 11
date: 2024-07-13T10:29:10.577Z
updated: 2024-07-14T10:29:10.577Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reactivating Lost MS Store Access on Windows 11 & 11
excerpt: This Article Describes Reactivating Lost MS Store Access on Windows 11 & 11
keywords: Reactivate MS Store,Windows 11 Store,Restore MS Store Access,Reinstalling Store,MS Store Fix,Microsoft Store Recovery,Resetting Store Access
thumbnail: https://thmb.techidaily.com/f0922cdea4398af9eb93c3915c9d932ac3a495368c2166a8e69e3bccbb692700.jpg
---

## Reactivating Lost MS Store Access on Windows 11 & 11

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
<li><a href="https://win11.techidaily.com/configuring-metered-connection-for-wifi-networks-on-win11/"><u>Configuring Metered Connection for Wifi Networks on Win11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-vivo-s17-drfone-by-drfone-virtual-android/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Vivo S17 | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-sound-effects-for-podcasts-11-places-to-find-them/"><u>Updated Sound Effects for Podcasts 11 Places to Find Them</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/tailoring-your-devices-audio-alerts-a-cutting-edge-approach-for-2024/"><u>Tailoring Your Devices Audio Alerts A Cutting Edge Approach for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-11-and-11-desktop-context-menu-not-working/"><u>How to Fix the Windows 11 & 11 Desktop Context Menu Not Working</u></a></li>
<li><a href="https://win11.techidaily.com/from-iphone-to-desktop-syncing-ios-calendar-with-windows-1011/"><u>From iPhone to Desktop: Syncing iOS Calendar with Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-restoring-windows-11-search-efficiency/"><u>Essential Tips: Restoring Windows 11 Search Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/incorporating-new-folders-into-explorers-interface/"><u>Incorporating New Folders Into Explorer's Interface</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-failed-driver-loading-issues-in-the-latest-os/"><u>Overcoming Failed Driver Loading Issues in the Latest OS</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-processor-limits-in-power-options-menu/"><u>Demystifying Processor Limits in Power Options Menu</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-more-than-just-likes-and-watch-time-the-complexity-of-youtubes-view-tally/"><u>In 2024, More than Just Likes and Watch Time  The Complexity of YouTube's View Tally</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/how-to-blur-background-of-your-youtube-video/"><u>How to Blur Background of Your YouTube Video</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-excessive-use-of-windows-module-installer/"><u>Overcoming Excessive Use of Windows Module Installer</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-update-checks-with-these-9-fixes-on-windows-setup/"><u>Accelerate Update Checks with These 9 Fixes on Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-failure-codes-0x80072f8f/"><u>Addressing Windows Failure Codes: 0X80072f8f</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-kdenlive-is-a-free-open-source-video-editing-software-application-kdenlive-is-a-powerful-video-editor-that-can-be-used-to-create-professional-qualit/"><u>Updated Kdenlive Is a Free, Open-Source Video Editing Software Application. Kdenlive Is a Powerful Video Editor that Can Be Used to Create Professional-Quality Videos</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-system-safe-spotting-hidden-threats-in-windows/"><u>Keep Your System Safe: Spotting Hidden Threats in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/circumvent-unauthorized-windows-login-errors-easy-guide/"><u>Circumvent Unauthorized Windows Login Errors (Easy Guide)</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-insufficient-ram-warning-for-hogwarts-simulator/"><u>Fixing Insufficient RAM Warning for Hogwarts Simulator</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-non-persistent-nvidia-panel-changes/"><u>Correcting Non-Persistent Nvidia Panel Changes</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-synapse-glitches-on-w11-and-w10/"><u>How to Mend Synapse Glitches on W11 and W10</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-overlooked-windows-extras-a-step-by-step-manual/"><u>Enabling Overlooked Windows Extras: A Step-by-Step Manual</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-11-writable-driver-verifier/"><u>Activating Windows 11' Writable Driver Verifier</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-vpn-network-disconnection-on-a-remote-work-pc/"><u>Fixing VPN Network Disconnection on a Remote Work PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-disruptive-discord-js-error-in-windows-environments/"><u>Overcoming Disruptive Discord JS Error in Windows Environments</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-workflow-with-top-windows-to-do-apps/"><u>Enhance Your Workflow with Top Windows To-Do Apps</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-tackle-invalid-profile-on-windows-11-systems/"><u>How to Tackle 'Invalid Profile' On Windows 11 Systems</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-are-you-looking-to-make-a-thumbnail-for-your-fortnite-video-this-article-features-a-guide-explaining-creating-a-fortnite-motion-blur-thumbnail/"><u>2024 Approved Are You Looking to Make a Thumbnail for Your Fortnite Video? This Article Features a Guide Explaining Creating a Fortnite Motion Blur Thumbnail</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-steps-to-prevent-unplanned-recordings-in-qt/"><u>[New] Steps to Prevent Unplanned Recordings in QT</u></a></li>
<li><a href="https://win11-tips.techidaily.com/1719343275245-tackle-windows-geforce-failures-head-on-today/"><u>Tackle Windows GeForce Failures Head-On Today!</u></a></li>
<li><a href="https://win11.techidaily.com/guide-accessing-and-opening-verifier-manager-w11/"><u>Guide: Accessing and Opening Verifier Manager W11</u></a></li>
<li><a href="https://win11.techidaily.com/1719352195023-quick-fixes-for-your-windows-hurdles-and-complications/"><u>Quick Fixes for Your Windows Hurdles & Complications</u></a></li>
<li><a href="https://win11.techidaily.com/opening-editing-and-personalizing-your-win11-fax-cover-page/"><u>Opening, Editing & Personalizing Your Win11 Fax Cover Page</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-expert-endorsed-facebook-videos-now-easily-converted-to-mp4-hd/"><u>[New] In 2024, Expert-Endorsed  Facebook Videos Now Easily Converted to MP4 HD</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-and-set-up-windows-sandbox-in-windows-11/"><u>How to Enable and Set Up Windows Sandbox in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-easily-uninstall-applications-in-win-11/"><u>Breaking Barriers: Easily Uninstall Applications in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-mending-the-internal-error-in-rdp-on-windows-11-and-11-pro/"><u>Guide to Mending the Internal Error in RDP on Windows 11 & 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-unterminated-process-failures-in-windows/"><u>How to Resolve Unterminated Process Failures in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mending-microsoft-outlook-glitches-on-windows-devices/"><u>Mending Microsoft Outlook Glitches on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-missing-file-updates-error-on-windows-error-code-0x80070003/"><u>Navigating Through Missing File Updates Error on Windows (Error Code: 0X80070003)</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-oppo-find-x7-ultra-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Oppo Find X7 Ultra | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-prior-to-starting-the-window-operating-system-renewal/"><u>Key Steps Prior to Starting the Window Operating System Renewal</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-cultivating-a-positive-mindset-against-cyberbullying/"><u>In 2024, Cultivating a Positive Mindset Against Cyberbullying</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-powertoys-reset-on-new-machine/"><u>Navigating PowerToys: Reset on New Machine</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-origami-like-folded-havens-in-mc/"><u>[Updated] In 2024, Origami-Like Folded Havens in MC</u></a></li>
</ul></div>
