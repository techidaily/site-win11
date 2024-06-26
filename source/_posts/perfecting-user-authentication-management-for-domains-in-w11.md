---
title: Perfecting User Authentication Management for Domains in W11
date: 2024-06-25T10:28:14.254Z
updated: 2024-06-26T10:28:14.254Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Perfecting User Authentication Management for Domains in W11
excerpt: This Article Describes Perfecting User Authentication Management for Domains in W11
keywords: AuthDomainSetup,W11AuthManagement,DomainUserVerification,SecureW11Login,IdentityControlSystem,UserAccessInsight,AuthenticationDomainProf
thumbnail: https://thmb.techidaily.com/d5d5810dfb5162fe3838fd5a512ce840bf5c9c8c52397ab8a1f2ef651a47611e.jpg
---

## Perfecting User Authentication Management for Domains in W11

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
<li><a href="https://win11.techidaily.com/triggering-dormant-pane-windows-6-tips-for-win11-users/"><u>Triggering Dormant Pane Windows: 6 Tips for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/should-you-embrace-windows-11s-secure-environment/"><u>Should You Embrace Windows 11'S Secure Environment?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-disable-permission-restrictions-and-open-hidden-folders/"><u>How to Disable Permission Restrictions and Open Hidden Folders</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-system-reliability-automatic-updates-plus-graphics-card-swap/"><u>Enhance System Reliability: Automatic Updates + Graphics Card Swap</u></a></li>
<li><a href="https://win11.techidaily.com/harness-the-power-of-shortcut-creation-on-windows-11/"><u>Harness the Power of Shortcut Creation on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-windows-11-zoom-failure-1132/"><u>Unblocking Windows 11 Zoom Failure #1132</u></a></li>
<li><a href="https://win11.techidaily.com/enriching-old-directx-software-via-dxvk-conversion/"><u>Enriching Old DirectX Software via DXVK Conversion</u></a></li>
<li><a href="https://win11.techidaily.com/resetting-volume-mixer-to-default-after-errors-occurred/"><u>Resetting Volume Mixer to Default After Errors Occurred</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-clone-without-third-party-reliance-in-windows/"><u>Crafting Clone Without Third-Party Reliance in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/speak-clearly-write-exactly-using-whisper-in-windows/"><u>Speak Clearly, Write Exactly: Using Whisper in Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/quick-start-mastering-ez-grabbers-downloading-and-usage-for-2024/"><u>Quick Start  Mastering EZ Grabber's Downloading & Usage for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-everything-to-know-about-apple-id-password-requirements-for-iphone-6-plus-by-drfone-ios/"><u>In 2024, Everything To Know About Apple ID Password Requirements For iPhone 6 Plus</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-the-best-free-video-splitting-solutions-reviewed/"><u>New 2024 Approved The Best Free Video Splitting Solutions Reviewed</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-how-to-add-a-streamline-of-youtube-playlists-on-your-website/"><u>[Updated] How to Add a Streamline of YouTube Playlists on Your Website</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-how-to-record-your-memorable-honeymoon-video/"><u>Updated How to Record Your Memorable Honeymoon Video</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-the-blueprint-for-building-a-youtube-empire-in-quick-time/"><u>2024 Approved  The Blueprint for Building a YouTube Empire in Quick Time</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-simplified-steps-for-backdrop-elimination-in-photoshop-like-affinity-photo/"><u>[New] Simplified Steps for Backdrop Elimination in Photoshop-Like Affinity Photo</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-secrets-to-updating-your-facebook-banner-for-2024/"><u>[Updated] Secrets to Updating Your Facebook Banner for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-elite-selection-macs-finest-screen-recorder/"><u>[New] 2024 Approved  Elite Selection  Mac's Finest Screen Recorder</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-writings-on-the-best-practices-for-youtube-commentary/"><u>Incor Writings on the Best Practices for YouTube Commentary</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>