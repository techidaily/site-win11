---
title: Navigating Permissions Management in W11, Domains
date: 2024-06-25T11:30:48.700Z
updated: 2024-06-26T11:30:48.700Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/revolutionize-file-management-with-windows-automatic-deletion/"><u>Revolutionize File Management with Windows' Automatic Deletion</u></a></li>
<li><a href="https://win11.techidaily.com/windows-without-bitlocker-here-are-4-steps-to-stay-secure/"><u>Windows Without Bitlocker? Here Are 4 Steps to Stay Secure</u></a></li>
<li><a href="https://win11.techidaily.com/swift-strategies-for-overcoming-steam-file-locks/"><u>Swift Strategies for Overcoming Steam File Locks</u></a></li>
<li><a href="https://win11.techidaily.com/7-game-changing-windows-11-additions-in-moment-22h2/"><u>7 Game-Changing Windows 11 Additions in Moment #22H2</u></a></li>
<li><a href="https://win11.techidaily.com/legacy-systems-to-win11-upgrade-essentials/"><u>Legacy Systems to Win11 Upgrade Essentials</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-failed-office-activation-setbacks/"><u>Navigating Through Failed Office Activation Setbacks</u></a></li>
<li><a href="https://win11.techidaily.com/safeguarding-data-update-windows-11-user-passwords/"><u>Safeguarding Data: Update Windows 11 User Passwords</u></a></li>
<li><a href="https://win11.techidaily.com/routine-task-for-eliminating-steam-dns-cache-on-pc/"><u>Routine Task for Eliminating Steam DNS Cache on PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-errors-with-windows-event-logger/"><u>Overcoming Errors with Windows Event Logger</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-resolving-inbox-notifications-on-pcs/"><u>Comprehensive Guide to Resolving Inbox Notifications on PCs</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-unbeatable-windows-chat-providers-3-1-ranked/"><u>[New] 2024 Approved  Unbeatable Windows Chat Providers, #3-#1 Ranked</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-reliving-retro-fun-with-top-5-emulated-game-boy-advance-games-on-desktop-systems/"><u>[New] In 2024, Reliving Retro Fun with Top 5 Emulated Game Boy Advance Games on Desktop Systems</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-should-i-apply-pitch-correction-to-elevate-speech-sounds/"><u>New Should I Apply Pitch Correction to Elevate Speech Sounds?</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-journey-into-the-heart-of-tiktoks-anime-a-convergence-of-dance-music-and-imagery-for-2024/"><u>[New] Journey Into the Heart of TikTok's Anime  A Convergence of Dance, Music & Imagery for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-obtaining-customized-animation-emojis-on-discord-without-a-premium-account-for-2024/"><u>[Updated] Obtaining Customized Animation Emojis on Discord Without a Premium Account for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/seamless-online-video-sharing-via-vimeo-for-2024/"><u>Seamless Online Video Sharing via Vimeo for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/photo-text-editing-made-simple-tools-and-techniques-for-2024/"><u>Photo Text Editing Made Simple  Tools & Techniques for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-light-up-your-media-select-5-excellent-apps/"><u>In 2024, Light Up Your Media  Select 5 Excellent Apps</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-hit-the-trend-hard-with-these-must-try-tiktok-items-on-amazon/"><u>[Updated] Hit the Trend Hard with These Must-Try TikTok Items on Amazon</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-perfect-guide-youtube-videos-on-instagram-feed/"><u>[Updated] Perfect Guide  YouTube Videos on Instagram Feed</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>