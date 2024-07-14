---
title: Enabling/Disabling User Biometric Use by Domains
date: 2024-07-13T09:55:12.713Z
updated: 2024-07-14T09:55:12.713Z
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



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-tunetrimmer-pro-the-essential-tool-for-distraction-free-listening/"><u>2024 Approved TuneTrimmer Pro The Essential Tool for Distraction-Free Listening</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/silence-your-tiktok-sounds-quick-techniques-for-a-noiseless-experience-for-2024/"><u>Silence Your TikTok Sounds Quick Techniques for a Noiseless Experience for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-no-fuss-filming-dell-laptop-screen-recordings/"><u>[New] In 2024, No-Fuss Filming  Dell Laptop Screen Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-the-invalid-token-reference-in-modern-oses/"><u>Dealing with the Invalid Token Reference in Modern OSes</u></a></li>
<li><a href="https://win11.techidaily.com/tutorial-ceasing-wired-pc-keyboard-on-windows/"><u>Tutorial: Ceasing Wired PC Keyboard on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-display-management-in-windows-11/"><u>Understanding Display Management in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-ties-with-windows-11-store/"><u>Cutting Ties with Windows 11 Store</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-fostering-duets-tiktok-vocal-pairings/"><u>[Updated] In 2024, Fostering Duets  TikTok Vocal Pairings</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-how-to-make-money-on-tiktok-in-8-ways-cannot-miss/"><u>[Updated] How to Make Money on TikTok in 8 Ways [Cannot Miss]</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-exploring-the-essence-of-youtube-live-imagery-language-for-2024/"><u>[Updated] Exploring the Essence of YouTube Live Imagery Language for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/bypass-software-for-youtube-downloads-for-2024/"><u>Bypass Software for YouTube Downloads for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-vivo-y200e-5g-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Vivo Y200e 5G</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-the-virtual-age-present-and-future-challenges-for-2024/"><u>Unveiling the Virtual Age  Present and Future Challenges for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/craft-a-personalized-windows-console-experience/"><u>Craft a Personalized Windows Console Experience</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-advanced-techniques-for-360-video-editing-in-premiere/"><u>2024 Approved  Advanced Techniques for 360° Video Editing in Premiere</u></a></li>
<li><a href="https://win11.techidaily.com/the-5-best-auto-clickers-with-hotkeys-for-windows/"><u>The 5 Best Auto Clickers With Hotkeys for Windows</u></a></li>
<li><a href="https://win11.techidaily.com/skyrim-booster-issues-windows-repair-guide/"><u>Skyrim Booster Issues: Windows Repair Guide</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-the-way-for-printer-use-by-one-pc-only/"><u>Clearing the Way for Printer Use by One PC Only</u></a></li>
<li><a href="https://win11.techidaily.com/trick-to-invoke-admin-level-powershell-on-your-win11-pc/"><u>Trick to Invoke Admin-Level PowerShell on Your Win11 PC</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-a-fair-assessment-unveiling-recordcasts-capabilities/"><u>[New] A Fair Assessment  Unveiling RecordCast's Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-the-void-recovering-startups-on-windows/"><u>Bridging the Void: Recovering Startups on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-removing-null-space-in-your-system-drive/"><u>Step-by-Step Guide: Removing Null Space in Your System Drive</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-menu-unlocking-ancestral-functions/"><u>Windows 11'S Menu: Unlocking Ancestral Functions</u></a></li>
<li><a href="https://win11.techidaily.com/the-financial-backbone-of-microsofts-windows-11/"><u>The Financial Backbone of Microsoft's Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-oppo-find-n3-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Oppo Find N3 System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719374785731-unlock-additional-space-on-your-windows-system-for-free/"><u>Unlock Additional Space on Your Windows System, For Free!</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-unlock-windows-defense-against-admins-choice/"><u>Techniques to Unlock Windows Defense Against Admins' Choice</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-settings-error-in-nvidias-geforce-app-windows-11/"><u>Steps to Overcome 'Settings Error' In NVIDIA's GeForce App (Windows 11)</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-getting-started-with-macos-11-big-sur-upgrade/"><u>[New] 2024 Approved  Getting Started with macOS 11 Big Sur Upgrade</u></a></li>
<li><a href="https://win11.techidaily.com/8-microsoft-apps-you-must-install-on-android-if-you-have-a-windows-pc/"><u>8 Microsoft Apps You Must Install on Android if You Have a Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/10-solutions-for-stuck-pin-locks-on-windows/"><u>10 Solutions for Stuck PIN Locks on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/system-fixes-for-error-0x800700e1-in-windows-11/"><u>System Fixes for Error 0X800700E1 in Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-clearing-the-path-to-account-deactivation-on-linkedin/"><u>[New] Clearing the Path to Account Deactivation on LinkedIn</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-geforce-0x0001-in-windows-1011-environment/"><u>Addressing GeForce 0X0001 in Windows 10/11 Environment</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Samsung Galaxy S23 FE? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/say-goodbye-to-stumbles-in-your-instagram-stream/"><u>Say Goodbye to Stumbles in Your Instagram Stream</u></a></li>
<li><a href="https://tools.techidaily.com/wondershare/drfone/android-screen-mirror/"><u>Android Screen Mirror</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-11-arm-installation-via-iso-download/"><u>Seamless Windows 11 ARM Installation via ISO Download</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-infinix-smart-8-pro-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Infinix Smart 8 Pro Is Unlocked</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-best-value-tech-for-costless-screen-mirroring-for-2024/"><u>[Updated] Best Value Tech for Costless Screen Mirroring for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/upgrading-windows-11s-atheros-connectivity-easy-driver-installation-guide/"><u>Upgrading Windows 11'S Atheros Connectivity: Easy Driver Installation Guide</u></a></li>
<li><a href="https://win11.techidaily.com/switching-notepad-to-dark-mode-on-windows-11plus/"><u>Switching Notepad to Dark Mode on Windows 11+</u></a></li>
<li><a href="https://win11.techidaily.com/achieve-immersive-surround-sound-incorporating-atmos-into-win-1011/"><u>Achieve Immersive Surround Sound: Incorporating Atmos Into Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-tackle-zeroxc000003e-application-errors-in-win1011/"><u>Strategies to Tackle ZeroXc000003e Application Errors in Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/secure-app-locations-in-windows-task-management/"><u>Secure App Locations in Windows Task Management</u></a></li>
</ul></div>
