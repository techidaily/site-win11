---
title: Configuring User Biometrics in Windows 11 for Domains
date: 2024-08-28T00:55:28.021Z
updated: 2024-08-29T00:55:28.021Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring User Biometrics in Windows 11 for Domains
excerpt: This Article Describes Configuring User Biometrics in Windows 11 for Domains
keywords: Win11 Biometric Setup,Domain-Level Biometry,Windows Biometrics Config,Secure Windows Biometrics,User Access Control Windows,Windows Authentication Domains,Biometric Enablement in Win11
thumbnail: https://thmb.techidaily.com/73087a990223851f6a7c5417d3512a4d93ddbbb6cac79840abc644367d7f8449.jpg
---

## Configuring User Biometrics in Windows 11 for Domains

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-demystifying-the-world-of-youtube-shorts/"><u>[New] 2024 Approved  Demystifying the World of YouTube Shorts</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-achieving-financial-freedom-joshis-youtube-tactics-for-2024/"><u>[New] Achieving Financial Freedom  Joshi’s YouTube Tactics for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-augmenting-our-perception-an-introduction/"><u>[New] Augmenting Our Perception  An Introduction</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-the-undercover-guide-to-enhancing-your-window-11-experience-for-2024/"><u>[New] The Undercover Guide to Enhancing Your WINDOW 11 Experience for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unite-auditory-elements-with-visuals-in-ppt/"><u>[New] Unite Auditory Elements with Visuals in PPT</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-master-class-extracting-and-saving-vimeo-videos/"><u>[Updated] 2024 Approved  Master Class  Extracting and Saving Vimeo Videos</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-fixing-absence-of-color-on-game-feedback/"><u>[Updated] Fixing Absence of Color on Game Feedback</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-elevating-your-minecraft-game-perfectly-shaped-circles-and-spheres/"><u>[Updated] In 2024, Elevating Your Minecraft Game  Perfectly Shaped Circles and Spheres</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-achieve-superior-mp4-output-from-instagram-videos-2-ways/"><u>2024 Approved  Achieve Superior MP4 Output From Instagram Videos 2 Ways</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-download-and-translate-youtube-videos-for-free/"><u>2024 Approved  Download and Translate YouTube Videos for Free</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-simplified-guide-to-advanced-xbox-video-recording-methods/"><u>2024 Approved  Simplified Guide to Advanced Xbox Video Recording Methods</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-speedy-tactics-for-disorganized-youtube-song-listings/"><u>2024 Approved  Speedy Tactics for Disorganized YouTube Song Listings</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-incompatibility-issues-in-windows-vlc-player/"><u>Correcting Incompatibility Issues in Windows, VLC Player</u></a></li>
<li><a href="https://win11.techidaily.com/cure-windows-notepad-freeze-phenomena/"><u>Cure Windows Notepad Freeze Phenomena</u></a></li>
<li><a href="https://win11.techidaily.com/cure-your-consoles-crashing-wow-problems-quickly/"><u>Cure Your Console's Crashing WoW Problems Quickly</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-search-experience-in-windows-11/"><u>Elevate Your Search Experience in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-workspace-with-these-easy-themes-changes-on-win11/"><u>Enhance Your Workspace with These Easy Themes Changes on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/error-2e-and-its-impact-on-windows-updating/"><u>Error 2E and Its Impact on Windows Updating</u></a></li>
<li><a href="https://win11.techidaily.com/expanding-windows-11s-folder-menu-options-with-new-commands/"><u>Expanding Windows 11'S Folder Menu Options with New Commands</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expert-analysis-of-samsung-photo-editor-prospects-and-constraints-for-2024/"><u>Expert Analysis of Samsung Photo Editor Prospects & Constraints for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/from-vintage-to-virtual-realm-activate-windows-11-using-a-windows-7-key/"><u>From Vintage to Virtual Realm: Activate Windows 11 Using a Windows 7 Key</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-aim-for-picture-perfect-facebooks-hd-streaming/"><u>In 2024, Aim for Picture-Perfect  Facebook's HD Streaming</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Samsung Galaxy XCover 6 Pro Tactical Edition? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-windows-data-safe-a-must-do-habit/"><u>Keeping Windows Data Safe: A Must-Do Habit</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-chromes-inaccurate-virus-alert-and-resolving-it/"><u>Navigating Chrome's Inaccurate Virus Alert and Resolving It</u></a></li>
<li><a href="https://driver-install.techidaily.com/navigating-win11-printers-and-their-drivers/"><u>Navigating Win11: Printers and Their Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-blue-screen-error-0xc0000142/"><u>Overcoming Blue Screen Error 0XC0000142</u></a></li>
<li><a href="https://win11.techidaily.com/power-play-four-strategies-for-removing-user-entries-from-win11/"><u>Power Play: Four Strategies for Removing User Entries From Win11</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-tap-your-way-through-win11s-print-settings-max-48-chars/"><u>Quick Guide: Tap Your Way Through Win11's Print Settings (Max 48 Chars)</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-infinix-note-30-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Infinix Note 30 Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-non-selectable-text-within-windows-pdf-files/"><u>Rectify Non-Selectable Text Within Windows PDF Files</u></a></li>
<li><a href="https://win11.techidaily.com/reinitializing-windows-graphics-a-step-by-step-guide/"><u>Reinitializing Windows Graphics: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-non-operational-display-driver-on-windows-11-os/"><u>Remedy for Non-Operational Display Driver on Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/simplified-techniques-for-batch-installing-windows-11-apps-via-winstall/"><u>Simplified Techniques for Batch Installing Windows 11 Apps via Winstall</u></a></li>
<li><a href="https://windows11.techidaily.com/speed-up-task-managers-dynamic-display-in-windows-11/"><u>Speed up Task Manager's Dynamic Display in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-address-unsupported-device-error/"><u>Strategies to Address 'Unsupported Device' Error</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-improve-fps-and-reduce-lag-in-roblox-windows-edition/"><u>Strategies to Improve FPS & Reduce Lag in Roblox Windows Edition</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-call-journals-on-windows-pcs/"><u>Streamlining Call Journals on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-spotify-links-on-windows-11-pcs/"><u>Streamlining Spotify Links on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/switching-on-windows-11s-updated-widget-chooser/"><u>Switching On Windows 11'S Updated Widget Chooser</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-nonresponsive-diagnostics-in-win10win11/"><u>Tackling Nonresponsive Diagnostics in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-plan-for-your-epic-games-files/"><u>The Ultimate Plan for Your Epic Games Files</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On OnePlus 11 5G? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-gripes-windows-11-user-experience/"><u>Top 5 Gripes: Windows 11 User Experience</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-secrets-of-windows-screen-hangouts/"><u>Unlocking Secrets of Windows Screen Hangouts</u></a></li>
<li><a href="https://win11.techidaily.com/win11-wizardry-invisible-archiving-techniques-in-photos/"><u>Win11 Wizardry: Invisible Archiving Techniques in Photos</u></a></li>
<li><a href="https://win11.techidaily.com/windows-screen-grabs-snip-tool-versus-print-screen-efficacy/"><u>Windows Screen Grabs: Snip Tool Versus Print Screen Efficacy</u></a></li>
<li><a href="https://win11.techidaily.com/windows-steps-to-purge-unnecessary-steam-dns-data/"><u>Windows Steps to Purge Unnecessary Steam DNS Data</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>