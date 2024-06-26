---
title: Mastering the Biometric Settings of W11 for Domains
date: 2024-06-25T09:55:05.428Z
updated: 2024-06-26T09:55:05.428Z
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
<li><a href="https://win11.techidaily.com/set-personalized-idle-lock-on-windows/"><u>Set Personalized Idle Lock on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-microsoft-office-365-fault-code-30015-26/"><u>Rectify Microsoft Office 365 Fault: Code 30015-26</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-windows-10-file-organization-hacks-max-156/"><u>Streamlining Windows: 10 File Organization Hacks (Max 156)</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-workspace-integrating-spotlight-images-into-wallpaper/"><u>Elevate Your Workspace: Integrating Spotlight Images Into Wallpaper</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-file-explorers-gallery-view-capability/"><u>Unlocking File Explorer's Gallery View Capability</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-why-you-cant-see-drive-letters-on-your-windows-system/"><u>Unveiling Why You Can't See Drive Letters on Your Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-bluetooth-mouse-blackout-on-windows-systems/"><u>Overcoming Bluetooth Mouse Blackout on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-cut-off-others-access-in-the-windows-network/"><u>How to Cut Off Others' Access in the WIndows Network</u></a></li>
<li><a href="https://win11.techidaily.com/simple-steps-to-acquire-and-implement-microsoft-stores-application-bundles/"><u>Simple Steps to Acquire & Implement Microsoft Store's Application Bundles</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-edges-unending-task-on-windows-11-pcs/"><u>Exploring Edge's Unending Task on Windows 11 PCs</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-watch-hulu-outside-us-on-xiaomi-14-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/the-way-to-recover-deleted-contacts-on-vivo-without-backup-by-fonelab-android-recover-contacts/"><u>The way to recover deleted contacts on Vivo without backup.</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-vr-wave-crafting-engaging-360-video-narratives-for-youtube-audiences-for-2024/"><u>The VR Wave  Crafting Engaging 360 Video Narratives for YouTube Audiences for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-decoding-the-earning-dynamics-for-podcasters/"><u>[Updated] 2024 Approved  Decoding the Earning Dynamics for Podcasters</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-watch-what-you-liked-no-more-unveiling-yt-deletions-online/"><u>[Updated] Watch What You Liked No More  Unveiling YT Deletions Online</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-10-android-video-editing-apps-that-rival-imovie/"><u>New 2024 Approved 10 Android Video Editing Apps That Rival iMovie</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-skillful-use-of-skypes-screen-share-capabilities-in-telecommuting/"><u>[New] 2024 Approved  Skillful Use of Skype's Screen Share Capabilities in Telecommuting</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/the-best-methods-to-unlock-the-iphone-locked-to-owner-for-apple-iphone-14-plus-by-drfone-ios/"><u>The Best Methods to Unlock the iPhone Locked to Owner for Apple iPhone 14 Plus</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-infinix-zero-30-5gfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Infinix Zero 30 5GFRP Lock</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-lava-blaze-2-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Lava Blaze 2 5G | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>