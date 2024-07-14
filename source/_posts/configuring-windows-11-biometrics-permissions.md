---
title: Configuring Windows 11 Biometrics Permissions
date: 2024-07-13T09:49:00.763Z
updated: 2024-07-14T09:49:00.763Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring Windows 11 Biometrics Permissions
excerpt: This Article Describes Configuring Windows 11 Biometrics Permissions
keywords: Win11 Biometric Perms Config,Windows 11 Facial Permission,Biometric Access Windows 11,Set Windows 11 Biometrics,Enable Windows 11 Fingerprint,Windows 11 Voice Recognition,Activate Windows 11 Touch ID
thumbnail: https://thmb.techidaily.com/6a18129a35160648e7ff206817c86c3e7a35764f1e5155e4ea51973b0ba8c3ca.jpg
---

## Configuring Windows 11 Biometrics Permissions

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
<li><a href="https://win11.techidaily.com/understanding-and-removing-windows-defender-error-0x80004004/"><u>Understanding & Removing Windows Defender Error 0X80004004</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-crafting-the-perfect-online-persona-with-discord-pics-for-2024/"><u>[Updated] Crafting the Perfect Online Persona with Discord Pics for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-guide-to-enable-startup-diagnostics/"><u>A Step-by-Step Guide to Enable Startup Diagnostics</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/master-your-first-steps-in-using-tiktok-macpc-edition-for-2024/"><u>Master Your First Steps in Using TikTok  Mac/PC Edition for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/deletion-risks-for-windows-bt-folder-expert-advice/"><u>Deletion Risks for Windows ~BT Folder: Expert Advice</u></a></li>
<li><a href="https://win11.techidaily.com/top-windows-compatible-nds-emulators/"><u>Top Windows Compatible NDS Emulators</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-classic-gaming-journey-add-trophy-features-through-retroarch/"><u>Transform Your Classic Gaming Journey - Add Trophy Features Through Retroarch</u></a></li>
<li><a href="https://win11.techidaily.com/managing-your-digital-life-restarting-apps-in-windows-11/"><u>Managing Your Digital Life: Restarting Apps in Windows 11</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-tecno-spark-10c-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Tecno Spark 10C Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-playlist-extraction-made-simple-download-steps-revealed/"><u>2024 Approved  Playlist Extraction Made Simple  Download Steps Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/employing-rufus-to-navigate-windows-11s-security-barriers/"><u>Employing Rufus to Navigate Windows 11'S Security Barriers</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-ccleaner-in-win11/"><u>Troubleshooting Non-Functional CCleaner in Win11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-windows-phone-video-players-essential-app-selections/"><u>[Updated] Top Windows Phone Video Players  Essential App Selections</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-fundamentals-of-animation-and-graphic-expression/"><u>2024 Approved  Fundamentals of Animation and Graphic Expression</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-sluggishness-in-windows-discord-app/"><u>Overcoming Sluggishness in Windows Discord App</u></a></li>
<li><a href="https://win11.techidaily.com/zero-entry-login-remote-desktop-innovations-on-win-11/"><u>Zero-Entry Login: Remote Desktop Innovations on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/winmc-lan-connectivity-woes-solutions-explored/"><u>WinMC LAN Connectivity Woes: Solutions Explored</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-steam-read-only-barrier-errors-in-windows-11/"><u>Eliminating Steam Read-Only Barrier Errors in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-infinix-smart-7-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-windows-experience-filter-key-settings/"><u>Customize Your Windows Experience: Filter Key Settings</u></a></li>
<li><a href="https://win11.techidaily.com/quickening-boot-process-windows-11-timeout-reduction-guide/"><u>Quickening Boot Process: Windows 11 Timeout Reduction Guide</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-overcoming-windows-1011s-isdonedll-errors/"><u>Deciphering and Overcoming Windows 10/11'S ISDone.dll Errors</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-color-management-glitches/"><u>Navigating Through Windows' Color Management Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-window-preview-failures-in-win-810/"><u>Addressing Window Preview Failures in Win 8/10</u></a></li>
<li><a href="https://win11.techidaily.com/8-ways-to-restore-missing-desktop-icons-on-windows-11/"><u>8 Ways to Restore Missing Desktop Icons on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/the-13-step-blueprint-to-reactivating-your-windows/"><u>The 13-Step Blueprint to Reactivating Your Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fast-setupuninstall-bings-ai-on-win-11-taskbar/"><u>Fast Setup/Uninstall: Bing's AI on Win 11 Taskbar</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-tecno-spark-10-pro-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>How to Cast Tecno Spark 10 Pro to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-your-computers-msvcr110dll-void/"><u>Remedying Your Computer’s Msvcr110.dll Void</u></a></li>
<li><a href="https://win11.techidaily.com/the-invisible-handshake-direct-pc-links-in-windows-11-rdp/"><u>The Invisible Handshake: Direct PC Links in Windows 11 RDP</u></a></li>
<li><a href="https://windows11.techidaily.com/decorating-windows-11-with-a-christmas-twist/"><u>Decorating Windows 11 with a Christmas Twist</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/echoes-of-tomorrow-7-pioneering-sound-alterations-redefining-music-production-for-2024/"><u>Echoes of Tomorrow 7 Pioneering Sound Alterations Redefining Music Production for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-the-username-switch-on-windows-11/"><u>Streamlining the UserName Switch on Windows 11</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-breaking-into-the-market-a-guide-to-facebook-video-content/"><u>In 2024, Breaking Into the Market  A Guide to Facebook Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-steam-network-access-on-pc-windows/"><u>Unlocking Steam Network Access on PC Windows</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-error-windows-security-cut-by-admin-policies/"><u>Deciphering Error: Windows Security Cut by Admin Policies</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-oppo-reno-8t-5g-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Oppo Reno 8T 5G</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-access-barriers-top-solutions/"><u>Navigating Through Windows Access Barriers: Top Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-failed-file-creation-by-camera-app/"><u>Solutions for Fixing Failed File Creation by Camera App</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-turn-off-overlay-effects-in-nvidia-graphics/"><u>How to Turn Off Overlay Effects in NVIDIA Graphics</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/creating-comedy-gold-top-8-techniques-that-shape-meme-artistry-for-2024/"><u>Creating Comedy Gold  Top 8 Techniques That Shape Meme Artistry for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-blueprints-for-impressive-fb-ad-campaigns/"><u>[Updated] Blueprints for Impressive FB Ad Campaigns</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-to-optimal-windows-11-search-performance/"><u>Navigating to Optimal Window's 11 Search Performance</u></a></li>
<li><a href="https://win11.techidaily.com/dissecting-the-role-of-windows-cab-files-in-system-setup/"><u>Dissecting the Role of Windows CAB Files in System Setup</u></a></li>
<li><a href="https://win11.techidaily.com/smoothly-switching-programs-for-your-first-win-11-experience/"><u>Smoothly Switching Programs for Your First Win 11 Experience</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-vivo-t2-5g-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Vivo T2 5G</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-exploring-the-dynamics-of-canon-timelapse-imagery/"><u>2024 Approved  Exploring the Dynamics of Canon Timelapse Imagery</u></a></li>
<li><a href="https://win11.techidaily.com/augmenting-dedicated-ram-win-11-edition-guide/"><u>Augmenting Dedicated RAM: Win 11 Edition Guide</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-se-2022-apples-new-iphone-drfone-by-drfone-ios/"><u>In 2024, How to Unlock iPhone SE (2022), Apples New iPhone | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/mov-in-the-cloud-top-six-techniques-for-windows-11-users-for-2024/"><u>.MOV in the Cloud - Top Six Techniques for Windows 11 Users for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-motorola-moto-g84-5g-drfone-by-drfone-virtual-android/"><u>In 2024, iPogo will be the new iSpoofer On Motorola Moto G84 5G? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>Does find my friends work on OnePlus 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-resolve-printer-network-errors-in-windows/"><u>Steps to Resolve Printer Network Errors in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-everlasting-file-elimination-on-your-desktop-bin-with-windows-11/"><u>Simplifying Everlasting File Elimination on Your Desktop Bin with Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-elevate-your-creativity-top-50plus-viral-tiktok-quotes/"><u>[Updated] 2024 Approved  Elevate Your Creativity  Top 50+ Viral TikTok Quotes</u></a></li>
<li><a href="https://win11.techidaily.com/increase-visible-pins-on-windows-11-desktop-ui/"><u>Increase Visible Pins on Windows 11 Desktop UI</u></a></li>
</ul></div>
