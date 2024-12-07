---
title: Securely Regulating Biometrics for Domain Users in Windows 11
date: 2024-12-01T22:07:07.000Z
updated: 2024-12-06T18:37:26.233Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Securely Regulating Biometrics for Domain Users in Windows 11
excerpt: This Article Describes Securely Regulating Biometrics for Domain Users in Windows 11
keywords: BioMetric Security,Windows 11 Privacy,Domain User Policy,Secure Biometrics Regulation,Win11 Biometric Safety,Identity Management in Win11,Domain Biometric Controls
thumbnail: https://thmb.techidaily.com/8614a77f9e633f7b68cb429db560c3992306d2b5be6c80ea6d2432a854e4bb42.jpg
---

## Securely Regulating Biometrics for Domain Users in Windows 11

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Allow or Block a Biometrics Log-On via the Local Group Policy Editor

 The quickest way to configure your computer to allow or block a biometrics scan for domain users is through the Local Group Policy Editor. Here are the steps you need to follow:

1. Press the **Win + R** key to open the **Run tool.**
2. Type **gpedit.msc** in the search bar and click OK.
3. In the Local Group Policy Editor, head towards the following location:  
`Computer Configuration > Administrative Templates > Windows Components > Biometrics`
4. Double-click on the **Allow domain users to log on using biometrics** policy in the right pane.  
![Allow domain users to log on using biometrics policy in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/allow-domain-users-to-log-on-using-biometrics-policy.jpg)
5. Choose the **Enabled** option to allow biometrics log on for the domain users. And choose the **Disabled** option to block biometrics log on for the domain users.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/M5pwd2mwaQQ?si=qyZHgdTlbQbc32Mp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-optimal-method-for-incorporating-linktree-in-tiktok-profiles/"><u>[New] 2024 Approved Optimal Method for Incorporating Linktree in TikTok Profiles</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-rhythmic-resonance-top-10-yogis-on-the-web/"><u>[New] 2024 Approved Rhythmic Resonance Top 10 Yogis on the Web</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-viral-video-legends-youtubed-for-millions/"><u>[Updated] 2024 Approved Viral Video Legends YouTubed for Millions</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-instagram-stardom-a-beginners-blueprint/"><u>[Updated] Instagram Stardom A Beginner's Blueprint</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Honor Magic5 Ultimate? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-videos-on-p40plus-by-fonelab-android-recover-video/"><u>How to restore wiped videos on P40+</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-poco-c51-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Poco C51 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-zip-or-unzip-files-using-the-command-prompt-and-windows-powershell/"><u>How to Zip or Unzip Files Using the Command Prompt and Windows PowerShell</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-locked-for-security-reasons-on-iphone-8-find-the-best-solution-here-by-drfone-ios/"><u>In 2024, Apple ID Locked for Security Reasons On iPhone 8? Find the Best Solution Here</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-realme-10t-5g-for-parents-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Telegram Spy Tools On Realme 10T 5G for Parents | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-10-restore-eliminating-error-code-0x80042306/"><u>Mastering Windows 10 Restore: Eliminating Error Code 0X80042306</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-avoiding-disk-read-errors/"><u>Mastering Windows: Avoiding Disk Read Errors</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-mmc-snaps-not-displayed-on-windows/"><u>Navigating Through MMC Snaps Not Displayed on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-access-to-tools-setting-up-command-line-tricks/"><u>Speedy Access to Tools: Setting up Command-Line Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-correct-dll-failure-in-steam-interface/"><u>Steps to Correct DLL Failure in Steam Interface</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    