---
title: Mastering the Biometric Settings of W11 for Domains
date: 2024-06-25T11:26:30.570Z
updated: 2024-06-26T11:26:30.570Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Biometric Settings of W11 for Domains
excerpt: This Article Describes Mastering the Biometric Settings of W11 for Domains
keywords: BioSecure W11 Domain Config,W11 Biometrics Mastery,Enhanced Domain Security,W11 Identity Authentication,Optimize W11 Settings,Advanced Biometric Domains,Tailored W11 Safeguards
thumbnail: https://thmb.techidaily.com/73087a990223851f6a7c5417d3512a4d93ddbbb6cac79840abc644367d7f8449.jpg
---

## Mastering the Biometric Settings of W11 for Domains

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
<li><a href="https://win11.techidaily.com/solutions-for-driver-not-running-error-in-windows-11/"><u>Solutions for Driver Not Running Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/proactive-strategies-to-unlock-computer-management-interface/"><u>Proactive Strategies to Unlock Computer Management Interface</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-failed-syncs-a-guide-to-onedrive-operations-on-windows/"><u>Fixing Failed Syncs: A Guide to OneDrive Operations on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/configure-your-windows-11-to-suit-your-auditory-preferences/"><u>Configure Your Windows 11 to Suit Your Auditory Preferences</u></a></li>
<li><a href="https://win11.techidaily.com/turn-on-wsl-a-guide-to-windows-linux-integration/"><u>Turn on WSL: A Guide to Windows' Linux Integration</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-windows-11-file-transfers-that-halt/"><u>How to Resolve Windows 11 File Transfers That Halt</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-desktop-no-overlaps/"><u>Streamline Your Desktop: No Overlaps</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-ditch-premiere-rush-top-alternative-video-editing-software/"><u>Updated In 2024, Ditch Premiere Rush Top Alternative Video Editing Software</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/easy-passes-to-friends-tiktok-live-events-for-2024/"><u>Easy Passes to Friends' TikTok Live Events for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-simple-and-free-the-best-online-tone-generators-reviewed/"><u>2024 Approved Simple and Free The Best Online Tone Generators Reviewed</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-xiaomi-13t-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Xiaomi 13T to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-blend-soundscapes-into-igtv-broadcasts-for-2024/"><u>Updated Blend Soundscapes Into IGTV Broadcasts for 2024</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-professional-edge-adding-letterbox-frame-to-your-fb-videos/"><u>[Updated] In 2024, Professional Edge  Adding Letterbox Frame to Your FB Videos</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-10-best-free-image-hosting-sites/"><u>2024 Approved  10 Best Free Image Hosting Sites</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Honor Magic 6 Lite? | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-unmatched-recording-alternatives-for-modern-gaming-enthusiasts/"><u>[Updated] In 2024, Unmatched Recording Alternatives for Modern Gaming Enthusiasts</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>