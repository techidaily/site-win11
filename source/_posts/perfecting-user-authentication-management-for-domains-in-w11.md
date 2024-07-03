---
title: Perfecting User Authentication Management for Domains in W11
date: 2024-06-25T11:36:53.653Z
updated: 2024-06-26T11:36:53.653Z
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
<li><a href="https://win11.techidaily.com/top-7-steps-before-factory-clearing-a-pc/"><u>Top 7 Steps Before Factory Clearing a PC</u></a></li>
<li><a href="https://win11.techidaily.com/minimize-pc-load-tips-for-managing-multimedia-tasks-on-windows/"><u>Minimize PC Load: Tips for Managing Multimedia Tasks on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-batch-scripts-creating-windows-exes/"><u>Elevating Your Batch Scripts: Creating Windows EXEs</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-space-windows-11s-disk-defragmentation-guide/"><u>Maximizing Space: Windows 11'S Disk Defragmentation Guide</u></a></li>
<li><a href="https://win11.techidaily.com/linuxs-rise-is-wsl-a-factor/"><u>Linux's Rise: Is WSL a Factor?</u></a></li>
<li><a href="https://win11.techidaily.com/what-everyone-must-know-before-purchasing-their-first-win-notebook/"><u>What Everyone Must Know Before Purchasing Their First Win Notebook</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-generations-old-games-with-dosbox-x/"><u>Bridging Generations: Old Games with DOSBox-X</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/transform-your-clips-time-lapse-video-editing-essentials-in-final-cut-pro-for-2024/"><u>Transform Your Clips Time Lapse Video Editing Essentials in Final Cut Pro for 2024</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/echoes-of-creativity-where-to-access-premium-audio-for-episodic-storytelling/"><u>Echoes of Creativity Where to Access Premium Audio for Episodic Storytelling</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-the-leaderboard-top-15-free-and-secure-apps-to-grow-your-insta-circle/"><u>[Updated] 2024 Approved  The Leaderboard  Top 15 Free & Secure Apps to Grow Your Insta Circle</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-vivo-v27-pro-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Vivo V27 Pro without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-premier-sound-pivot-for-podcast-masters/"><u>2024 Approved  Premier Sound Pivot for Podcast Masters</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-archivists-collection-essential-retro-visual-hacks-for-video-editors-for-2024/"><u>The Archivist's Collection  Essential Retro Visual Hacks for Video Editors for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-if-you-wish-to-edit-flv-videos-without-any-problems-you-should-utilize-a-multipurpose-video-editor-that-supports-the-flv-file-format/"><u>2024 Approved If You Wish to Edit FLV Videos without Any Problems, You Should Utilize a Multipurpose Video Editor that Supports the FLV File Format</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-2024-approved-tips-for-removing-discord-servers-on-pcs-and-phones/"><u>[Updated] 2024 Approved  Tips for Removing Discord Servers on PCs & Phones</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-excellence-unleashed-the-pinnacle-fps-selections/"><u>2024 Approved  Excellence Unleashed  The Pinnacle FPS Selections</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>