---
title: Biometric Management for Windows 11, Domain-Based
date: 2024-06-25T11:40:16.231Z
updated: 2024-06-26T11:40:16.231Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Biometric Management for Windows 11, Domain-Based
excerpt: This Article Describes Biometric Management for Windows 11, Domain-Based
keywords: Win11 Biometrics Secure,Domain-Based Biometric,Windows Security Key,PC Biometric Access,Windows 11 Identity,Domain Authentication,Windows ID Management
thumbnail: https://thmb.techidaily.com/0f08e68155172a78a589fb6b8f18fbb5a0a1a4069ed8867faff7b1ab4f999000.jpg
---

## Biometric Management for Windows 11, Domain-Based

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
<li><a href="https://win11.techidaily.com/controlling-devices-in-the-dormant-system-state/"><u>Controlling Devices in the Dormant System State</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-changing-picture-preview-size/"><u>Windows 11: Changing Picture Preview Size</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-approaches-to-restoring-windows-11-logins/"><u>Masterful Approaches to Restoring Windows 11 Logins</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-explore-tab-glitches-in-modern-os/"><u>Disabling Explore Tab Glitches in Modern OS</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-hello-login-fingerprint-failure/"><u>Eliminating Windows Hello Login Fingerprint Failure</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-image-quality-with-auto-hdr-in-w11/"><u>Maximizing Image Quality with Auto HDR in W11</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-charging-your-app-downloads-from-microsoft/"><u>Turbo-Charging Your App Downloads From Microsoft</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/unveiling-booktiks-must-read-masterpieces-a-reading-delight-for-2024/"><u>Unveiling #Booktik's Must-Read Masterpieces  A Reading Delight for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/apples-silicon-spectrum-comparing-m1-pro-and-the-powerhouse-m1-max-for-2024/"><u>Apple's Silicon Spectrum  Comparing M1 Pro and the Powerhouse M1 Max for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-proper-mac-photo-tips-identifying-and-comparing-the-top-5-techniques/"><u>[Updated] Proper Mac Photo Tips  Identifying and Comparing The Top 5 Techniques</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-workings-of-drones-an-introduction-for-beginners/"><u>The Workings of Drones  An Introduction for Beginners</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/doubled-surface-capture-method-for-2024/"><u>Doubled Surface Capture Method for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-dominate-the-digital-landscape-commerce-via-tiktok/"><u>[New] Dominate the Digital Landscape  Commerce via TikTok</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-resize-like-a-pro-tips-for-converting-horizontal-videos-to-vertical-for-2024/"><u>Updated Resize Like a Pro Tips for Converting Horizontal Videos to Vertical for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/injecting-spark-into-your-unique-podcast-format-for-2024/"><u>Injecting Spark Into Your Unique Podcast Format for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastering-microscopic-views-on-ms-teams-chat/"><u>Mastering Microscopic Views on MS Teams Chat</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>