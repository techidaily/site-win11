---
title: Strategizing Domain Users' Biometric Use on W11
date: 2024-06-25T11:43:26.206Z
updated: 2024-06-26T11:43:26.206Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategizing Domain Users' Biometric Use on W11
excerpt: This Article Describes Strategizing Domain Users' Biometric Use on W11
keywords: Biometrics for Domains,User Authentication,Secure Login Systems,Identity Verification Tech,Advanced Access Controls,Innovative Domain Security,W11 Biometric Integration
thumbnail: https://thmb.techidaily.com/8f13b229b4309cc607ca12c22275ed95f06f33bc5a9a2ad4f10fdb3f8f16d4fd.jpeg
---

## Strategizing Domain Users' Biometric Use on W11

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
<li><a href="https://win11.techidaily.com/step-by-step-guide-activating-newly-redesigned-widget-tool/"><u>Step-by-Step Guide: Activating Newly Redesigned Widget Tool</u></a></li>
<li><a href="https://win11.techidaily.com/7-noteworthy-changes-in-the-windows-11-file-explorer/"><u>7 Noteworthy Changes in the Windows 11 File Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-icons-bunching-up-on-the-windows-11-taskbar/"><u>How to Fix Icons Bunching Up on the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-to-refresh-windows-group-policy-settings/"><u>Key Techniques to Refresh Windows Group Policy Settings</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-personalized-windows-speech-to-text-app-using-whisper-and-ahk/"><u>Creating a Personalized Windows Speech-to-Text App Using Whisper & AHK</u></a></li>
<li><a href="https://win11.techidaily.com/winx-fix-guide-for-geforce-xs-cant-retrieve-settings/"><u>WinX Fix Guide for GeForce X's Can’t Retrieve Settings</u></a></li>
<li><a href="https://win11.techidaily.com/10-ways-to-open-the-windows-recovery-drive-tool/"><u>10 Ways to Open the Windows Recovery Drive Tool</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-remove-flashlight-from-apple-iphone-12-pro-lock-screen-by-drfone-ios/"><u>How To Remove Flashlight From Apple iPhone 12 Pro Lock Screen</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-do-we-experience-realities-in-a-virtual-sense/"><u>2024 Approved  How Do We Experience Realities in a Virtual Sense?</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-ideas-that-will-help-you-out-in-making-transparent-image/"><u>Updated 2024 Approved Ideas That Will Help You Out in Making Transparent Image</u></a></li>
<li><a href="https://video-capture.techidaily.com/efficient-methods-for-recording-minecraft-sessions-for-2024/"><u>Efficient Methods for Recording Minecraft Sessions for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-sail-through-the-sea-of-tiktok-video-downloads-for-2024/"><u>[New] Sail Through the Sea of TikTok Video Downloads for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/smooth-transition-from-skype-to-zoom-for-better-collaboration-for-2024/"><u>Smooth Transition From Skype to Zoom for Better Collaboration for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-art-of-crafting-winning-giveaway-posts-on-facebook/"><u>[New] The Art of Crafting Winning Giveaway Posts on Facebook</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-mastering-insta-video-sharing-from-youtube/"><u>In 2024, Mastering Insta-Video Sharing From YouTube</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/mastery-of-screen-recording-top-6-on-mac-systems-for-2024/"><u>Mastery of Screen Recording  Top 6 on Mac Systems for 2024</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>