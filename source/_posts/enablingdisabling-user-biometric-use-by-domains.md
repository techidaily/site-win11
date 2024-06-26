---
title: Enabling/Disabling User Biometric Use by Domains
date: 2024-06-25T11:25:21.891Z
updated: 2024-06-26T11:25:21.891Z
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
<li><a href="https://win11.techidaily.com/revamping-text-conversations-emoji-15-installation-guide-for-windows-11/"><u>Revamping Text Conversations: Emoji 15 Installation Guide for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-external-monitor-not-responding-in-windows-os/"><u>Resolving External Monitor Not Responding in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-classic-gaming-journey-add-trophy-features-through-retroarch/"><u>Transform Your Classic Gaming Journey - Add Trophy Features Through Retroarch</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-straighten-out-window-corners/"><u>How to Straighten Out Window Corners</u></a></li>
<li><a href="https://win11.techidaily.com/zero-entry-login-remote-desktop-innovations-on-win-11/"><u>Zero-Entry Login: Remote Desktop Innovations on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-6-oddities-in-windows-11-design/"><u>Decoding the 6 Oddities in Windows 11 Design</u></a></li>
<li><a href="https://win11.techidaily.com/connect-your-games-across-screens-win-11-and-android-via-google-linkup/"><u>Connect Your Games Across Screens: Win 11 & Android via Google Linkup</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-value-in-vcplusplus-release-packages/"><u>Unlocking the Value in VC++ Release Packages</u></a></li>
<li><a href="https://apple-account.techidaily.com/a-step-by-step-guide-to-finding-your-apple-id-from-your-apple-iphone-12-by-drfone-ios/"><u>A Step-by-Step Guide to Finding Your Apple ID From Your Apple iPhone 12</u></a></li>
<li><a href="https://location-social.techidaily.com/change-location-on-yik-yak-for-your-vivo-v27-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>Change Location on Yik Yak For your Vivo V27 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-fix-facebook-messenger-not-sending-videos-on-iphone-and-android/"><u>[Updated] 2024 Approved  Fix “Facebook Messenger Not Sending Videos” On iPhone and Android</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-2024-approved-synchronize-your-spectacle-an-exclusive-look-at-the-leading-5-multimedia-mergers/"><u>Updated 2024 Approved Synchronize Your Spectacle An Exclusive Look at the Leading 5 Multimedia Mergers</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-transforming-spoken-words-into-written-text-using-in-built-tools-of-office-suite-ms-word/"><u>[Updated] Transforming Spoken Words Into Written Text Using In-Built Tools of Office Suite - MS Word</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-windows-11-excellent-video-capture-tools-compared/"><u>[New] Windows 11  Excellent Video Capture Tools Compared</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-unleash-creativity-top-10-online-intro-maker-resources/"><u>New In 2024, Unleash Creativity Top 10 Online Intro Maker Resources</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-wondering-how-to-create-a-stunning-intro-video-with-kinemaster-here-are-the-simple-steps-to-use-kinemaster-to-design-your-intro-video-in-simple-step/"><u>In 2024, Wondering How to Create a Stunning Intro Video with KineMaster? Here Are the Simple Steps to Use KineMaster to Design Your Intro Video in Simple Steps</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-20-banger-tracks-from-tiktok-influencers-you-need/"><u>In 2024, 20 Banger Tracks From TikTok Influencers You Need</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>