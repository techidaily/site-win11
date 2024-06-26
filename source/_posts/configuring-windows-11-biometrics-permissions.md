---
title: Configuring Windows 11 Biometrics Permissions
date: 2024-06-25T11:23:47.612Z
updated: 2024-06-26T11:23:47.612Z
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
<li><a href="https://win11.techidaily.com/modify-homescreen-without-altering-windows-11-start-menu/"><u>Modify Homescreen without Altering Windows 11 Start Menu</u></a></li>
<li><a href="https://win11.techidaily.com/openai-whisper-for-windows-voice-to-text-techniques-unveiled/"><u>OpenAI Whisper for Windows: Voice-to-Text Techniques Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/the-quintessential-4-password-sentinels-of-windows-11-era/"><u>The Quintessential 4 Password Sentinels of Windows 11 Era</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-fixes-for-non-operational-voice-command-in-win11/"><u>Unveiling Fixes for Non-Operational Voice Command in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-steam-read-only-barrier-errors-in-windows-11/"><u>Eliminating Steam Read-Only Barrier Errors in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-windows-11-securely-without-screensaver/"><u>Unlock Windows 11 Securely Without Screensaver</u></a></li>
<li><a href="https://win11.techidaily.com/privacy-hacked-no-more-winning-encryption-tools-ranked-149-chars/"><u>Privacy Hacked No More: Winning Encryption Tools Ranked (149 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/uninstalling-wsl-a-complete-guide-for-win-1011-users/"><u>Uninstalling WSL: A Complete Guide for Win 10/11 Users</u></a></li>
<li><a href="https://techidaily.com/sign-dot-file-documents-online-for-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>Sign .dot file Documents Online for Free</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-chorus-and-bass-macs-sound-control/"><u>[New] In 2024, Chorus & Bass  Mac's Sound Control</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-essential-guide-to-the-top-5-windows-snipper-tools/"><u>[Updated] 2024 Approved  Essential Guide to The Top 5 Windows Snipper Tools</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-huawei-nova-y71-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Huawei Nova Y71 | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-easily-edit-avi-files-a-step-by-step-guide-to-trimming-and-splitting/"><u>New 2024 Approved Easily Edit AVI Files A Step-by-Step Guide to Trimming and Splitting</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/harnessing-online-platforms-beyond-youtube-to-30plus-communities/"><u>Harnessing Online Platforms  Beyond YouTube to 30+ Communities</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-real-time-harmony-streams-on-tiktok-for-2024/"><u>[New] Real-Time Harmony Streams on TikTok for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-mac-and-pc-harmony-the-most-reliable-android-emulator-list/"><u>[New] Mac & PC Harmony  The Most Reliable Android Emulator List</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-quickly-edit-video-speed-in-camtasia/"><u>Updated 2024 Approved Quickly Edit Video Speed in Camtasia</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>