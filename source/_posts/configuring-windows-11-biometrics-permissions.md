---
title: Configuring Windows 11 Biometrics Permissions
date: 2024-06-25T09:46:12.513Z
updated: 2024-06-26T09:46:12.513Z
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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/troubleshooting-heat-in-windows-11-pcs/"><u>Troubleshooting Heat in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-mystery-of-windows-ram-caching/"><u>Unveiling the Mystery of Windows RAM Caching</u></a></li>
<li><a href="https://win11.techidaily.com/reflect-organize-and-proliferate-using-obsidian-canvas/"><u>Reflect, Organize, and Proliferate: Using Obsidian Canvas</u></a></li>
<li><a href="https://win11.techidaily.com/resuming-lost-link-fixes-for-disconnected-google-drive-on-pc/"><u>Resuming Lost Link: Fixes for Disconnected Google Drive on PC</u></a></li>
<li><a href="https://win11.techidaily.com/the-perfect-sync-blueprint-for-android-plus-microsoft-os/"><u>The Perfect Sync Blueprint for Android + Microsoft OS</u></a></li>
<li><a href="https://win11.techidaily.com/diagnose-and-mend-dormant-usb-ports-the-windows-manual/"><u>Diagnose & Mend Dormant USB Ports - The Windows Manual</u></a></li>
<li><a href="https://win11.techidaily.com/non-light-no-problem-master-five-cures-for-backlit-keyboard-failure/"><u>Non-Light, No Problem: Master Five Cures for Backlit Keyboard Failure</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-free-animated-logo-design-software-top-picks-and-expert-advice/"><u>In 2024, Free Animated Logo Design Software Top Picks and Expert Advice</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-ploughing-through-the-past-top-farming-games-follow/"><u>[New] 2024 Approved  Ploughing Through the Past  Top Farming Games Follow</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-how-to-balance-your-stream-sound-with-obs-audio-ducking-in-2024/"><u>New How to Balance Your Stream Sound with OBS Audio Ducking, In 2024</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-free-film-production-integrating-soundtracks-into-your-workflow/"><u>Updated Free Film Production Integrating Soundtracks Into Your Workflow</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-exploring-the-essence-of-digital-audio-studios-debunking-myths-about-daw-technology/"><u>In 2024, Exploring the Essence of Digital Audio Studios Debunking Myths About DAW Technology</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/screenprime-pro-for-advanced-users-for-2024/"><u>ScreenPrime Pro for Advanced Users for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-shine-bright-enhancing-video-quality-tools/"><u>[Updated] Shine Bright  Enhancing Video Quality Tools</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>