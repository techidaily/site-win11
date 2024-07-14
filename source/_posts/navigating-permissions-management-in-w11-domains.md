---
title: Navigating Permissions Management in W11, Domains
date: 2024-07-13T10:15:21.553Z
updated: 2024-07-14T10:15:21.553Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Permissions Management in W11, Domains
excerpt: This Article Describes Navigating Permissions Management in W11, Domains
keywords: W11 Permissions Guide,Domain Access Control,W11 Security Setup,Managing W11 Rights,Permissions Management,Domain Policy Handling,W11 Authorization Strategy
thumbnail: https://thmb.techidaily.com/b3641ebe2988ec7265ef07a79816e61c990d023d2c0afe9a3bce0644ce087752.jpg
---

## Navigating Permissions Management in W11, Domains

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

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/bypassing-the-blackout-getting-out-of-dark-mode/"><u>Bypassing The Blackout: Getting Out Of Dark Mode</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-for-secure-external-drive-handling/"><u>Configuring Windows for Secure External Drive Handling</u></a></li>
<li><a href="https://win11.techidaily.com/windows-photos-shortcuts-for-the-savvy-editor/"><u>Windows Photos Shortcuts for the Savvy Editor</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-visual-upgrades-with-themes-from-microsoft-store/"><u>Harnessing Visual Upgrades with Themes From Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/terminal-and-powershell-delving-into-their-distinct-uses/"><u>Terminal and PowerShell: Delving Into Their Distinct Uses</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-messages-from-infinix-hot-40i-by-fonelab-android-recover-messages/"><u>Undelete lost messages from Infinix Hot 40i</u></a></li>
<li><a href="https://win11.techidaily.com/unshackle-chromiums-network-access-via-windows-settings-blockers/"><u>Unshackle Chromium's Network Access via Windows Settings Blockers</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unrequested-file-explorer-startups/"><u>Addressing Unrequested File Explorer Startups</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-windows-programming-file-layout-pe/"><u>Deciphering the Windows Programming File Layout (PE)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/asus-mg28uq-4k-revolution-experience-unparalleled-clarity-review/"><u>ASUS MG28UQ 4K Revolution - Experience Unparalleled Clarity Review</u></a></li>
<li><a href="https://win11.techidaily.com/step-wise-approach-to-adding-icons-to-windows-11-taskbar/"><u>Step-Wise Approach to Adding Icons to Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-internet-connections-a-guide-for-steam-on-windows/"><u>Fixing Internet Connections: A Guide for Steam on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-guide-implementing-animated-wallpapers-on-desktop/"><u>Windows 11 Guide: Implementing Animated Wallpapers on Desktop</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-restored-full-screen-happy-obs-users/"><u>[New] Restored Full Screen, Happy OBS Users</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-in-depth-analysis-of-excellent-zoom-screen-recorders/"><u>[New] In 2024, In-Depth Analysis of Excellent Zoom Screen Recorders</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-banishing-stickers-from-social-media-short-clips/"><u>In 2024, Banishing Stickers From Social Media Short Clips</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-full-tutorial-to-bypass-your-xiaomi-14-ultra-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Xiaomi 14 Ultra Face Lock?</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-potential-the-best-9-features-in-new-outlook/"><u>Unlocking Potential: The Best 9 Features in New Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/from-problem-to-perfection-tactics-to-install-missing-features-in-windows-11-and-11-pro/"><u>From Problem to Perfection: Tactics to Install Missing Features in Windows 11 & 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-desktop-no-overlaps/"><u>Streamline Your Desktop: No Overlaps</u></a></li>
<li><a href="https://win11.techidaily.com/cut-down-on-computing-power-spent-by-malware-scanners/"><u>Cut Down on Computing Power Spent by Malware Scanners</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>How To Activate and Use Life360 Ghost Mode On Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-photograph-whole-page-spectacle/"><u>In 2024, Photograph Whole Page Spectacle</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unlocking-color-richness-the-role-of-look-up-tables-in-adobe-photos/"><u>[Updated] Unlocking Color Richness  The Role of Look-Up Tables in Adobe Photos</u></a></li>
<li><a href="https://win11.techidaily.com/fundamentals-of-windows-executable-files-pe/"><u>Fundamentals of Windows Executable Files (PE)</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-ms-store-downloads-techniques-and-tips/"><u>Boosting MS Store Downloads: Techniques and Tips</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-classic-cinema-revisited-step-by-step-video-guide/"><u>[Updated] In 2024, Classic Cinema Revisited  Step-by-Step Video Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-10-sci-fi-vr-adventures-new-realms-unveiled/"><u>In 2024, Top 10 Sci-Fi VR Adventures  New Realms Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/unseen-networks-windows-wi-fi-security-guide/"><u>Unseen Networks: Windows Wi-Fi Security Guide</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-cant-connect-nvidia-error-on-win-11-devices/"><u>Bypassing the Can't Connect Nvidia Error on Win 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-stop-windows-from-misidentifying-audio-device/"><u>Techniques to Stop Windows From Misidentifying Audio Device</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-win32keygen-threat-symptoms-damage-and-removal-guide/"><u>Unraveling Win32/Keygen Threat: Symptoms, Damage, & Removal Guide</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-long-start-ups-in-windows-11-easily-and-swiftly/"><u>Conquering Long Start-Ups in Windows 11 Easily and Swiftly</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-realme-12plus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Realme 12+ 5G | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/unlock-efficiency-the-most-useful-adobe-premiere-shortcuts-revealed-for-2024/"><u>Unlock Efficiency The Most Useful Adobe Premiere Shortcuts Revealed for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/strategies-for-apps-that-wont-download-from-play-store-on-samsung-galaxy-z-flip-5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Strategies for Apps That Wont Download From Play Store On Samsung Galaxy Z Flip 5 | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-the-perfect-stream-a-comprehensive-guide-to-youtubes-full-rotation-videos-for-2024/"><u>Craft the Perfect Stream  A Comprehensive Guide to YouTube’s Full-Rotation Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-microsoft-can-improve-windows-11s-clipboard-history/"><u>9 Ways Microsoft Can Improve Windows 11'S Clipboard History</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-honor-x50i-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Honor X50i Back to Operation | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-error-0x80780119-on-system-image/"><u>Addressing Windows Error 0X80780119 on System Image</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/innovative-videography-for-sims-playtime-for-2024/"><u>Innovative Videography for Sims Playtime for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-activation-lock-on-iphone-x-4-easy-ways-by-drfone-ios/"><u>In 2024, Bypass Activation Lock On iPhone X - 4 Easy Ways</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-real-time-game-capture-aps4-strategies-in-obs/"><u>[Updated] 2024 Approved  Real-Time Game Capture  APS4 Strategies in OBS</u></a></li>
<li><a href="https://win11.techidaily.com/winning-over-full-screen-issues-in-sonic-adventure-on-windows-11/"><u>Winning Over Full-Screen Issues in Sonic Adventure on Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-a-guide-to-navigating-instagrams-new-updates-for-2024/"><u>[Updated] A Guide to Navigating Instagram's New Updates for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/curbing-the-catastrophe-recycle-bin-errors-in-win1011/"><u>Curbing the Catastrophe: Recycle Bin Errors in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-resetting-and-changing-login-credentials-in-win-11/"><u>Guide to Resetting and Changing Login Credentials in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/win11-addressing-inaudible-wireless-speaker-issues/"><u>Win11: Addressing Inaudible Wireless Speaker Issues</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-maximize-your-gameplay-in-depth-tips-and-tricks-for-freefirers/"><u>[Updated] Maximize Your Gameplay  In-Depth Tips & Tricks for FreeFirers</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-6-best-sim-unlock-services-that-actually-work-on-your-vivo-x-flip-device-by-drfone-android/"><u>In 2024, The 6 Best SIM Unlock Services That Actually Work On Your Vivo X Flip Device</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-crafting-effective-affordable-youtube-intros-with-templates/"><u>[Updated] In 2024, Crafting Effective, Affordable YouTube Intros with Templates</u></a></li>
<li><a href="https://win11.techidaily.com/expert-strategies-to-manage-files-and-tabs-windows-11/"><u>Expert Strategies to Manage Files and Tabs (Windows 11)</u></a></li>
<li><a href="https://win11.techidaily.com/which-window-suits-you-best-home-versus-pro-in-windows-11/"><u>Which Window Suits You Best? Home Versus Pro in Windows 11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-the-enigma-exchange-where-anonymity-meets-digital-riches-2023-edition-for-2024/"><u>[New] The Enigma Exchange  Where Anonymity Meets Digital Riches, 2023 Edition for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-create-extract-and-manage-files-via-cli/"><u>Step-by-Step Guide to Create, Extract and Manage Files via CLI</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-icons-bunching-up-on-the-windows-11-taskbar/"><u>How to Fix Icons Bunching Up on the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-optimal-msoffice-functionality-on-w11/"><u>Achieving Optimal MSOffice Functionality on W11</u></a></li>
<li><a href="https://win11.techidaily.com/discover-file-systems-better-with-diskspace-added-to-windows-menu/"><u>Discover File Systems Better with Diskspace Added to Windows Menu</u></a></li>
</ul></div>
