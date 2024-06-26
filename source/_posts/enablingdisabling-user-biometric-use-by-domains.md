---
title: Enabling/Disabling User Biometric Use by Domains
date: 2024-06-25T09:51:15.138Z
updated: 2024-06-26T09:51:15.138Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enabling/Disabling User Biometric Use by Domains
excerpt: This Article Describes Enabling/Disabling User Biometric Use by Domains
keywords: Biometric Access Control,Domain Biometrics Switch,User Authentication Methods,Disable Biometric Login,Enable Facial Recognition,Biometric Use Management,Security Policy
thumbnail: https://thmb.techidaily.com/f7aa9f91ee25ba92e513ec309ccac0797742d37b71585737d9811b8df3523624.jpg
---

## Enabling/Disabling User Biometric Use by Domains

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
<li><a href="https://win11.techidaily.com/addressing-windows-error-0x80780119-on-system-image/"><u>Addressing Windows Error 0X80780119 on System Image</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-recycle-bin-disruptions-in-win-11-os/"><u>Remedying Recycle Bin Disruptions in Win 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/restore-optional-features-on-windows-os-with-ease/"><u>Restore Optional Features on Windows OS with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/activating-windows-11-writable-driver-verifier/"><u>Activating Windows 11' Writable Driver Verifier</u></a></li>
<li><a href="https://win11.techidaily.com/windows-basics-easy-access-aids-for-novices/"><u>Windows Basics: Easy-Access Aids for Novices</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-to-resolve-microphone-problems-on-pc-and-xbox/"><u>Guidelines to Resolve Microphone Problems on PC & Xbox</u></a></li>
<li><a href="https://win11.techidaily.com/set-personalized-idle-lock-on-windows/"><u>Set Personalized Idle Lock on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/commanding-control-navigating-the-windows-print-hub/"><u>Commanding Control: Navigating the Windows Print Hub</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-the-maze-quickly-entering-windows-support-space/"><u>Avoiding the Maze: Quickly Entering Windows' Support Space</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-dismantling-windows-11s-misaligned-html-emails/"><u>Deciphering and Dismantling Windows 11'S Misaligned HTML Emails</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/the-social-searchers-guide-fb-profiles-made-easy/"><u>The Social Searcher's Guide  FB Profiles Made Easy</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-on-oppo-f25-pro-5g-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Oppo F25 Pro 5G FRP Bypass</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/unleash-potential-with-instagram-vids-formulating-an-effective-marketing-plan-for-2024/"><u>Unleash Potential with Instagram Vids  Formulating an Effective Marketing Plan for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/exploring-the-impactful-fusion-of-audio-elements-in-visual-storytelling/"><u>Exploring the Impactful Fusion of Audio Elements in Visual Storytelling</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-essential-techniques-for-efficient-utilization-of-zooms-whiteboard-feature/"><u>[New] Essential Techniques for Efficient Utilization of Zoom's Whiteboard Feature</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-in-depth-guide-to-full-transcription-and-archiving-of-fb-messages/"><u>2024 Approved  In-Depth Guide to Full Transcription & Archiving of FB Messages</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-a-comprehensive-look-at-stardew-and-ginger-isle/"><u>[New] In 2024, A Comprehensive Look at Stardew and Ginger Isle</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/mens-guide-to-leading-female-voices-with-technology/"><u>Mens Guide to Leading Female Voices with Technology</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-comprehensive-vlc-use-manual-for-mac-users/"><u>[Updated] Comprehensive VLC Use Manual for Mac Users</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/incorporating-on-screen-words-a-tiktok-video-transformation-for-2024/"><u>Incorporating On-Screen Words  A TikTok Video Transformation for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>