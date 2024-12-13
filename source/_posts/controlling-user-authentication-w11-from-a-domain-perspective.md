---
title: "Controlling User Authentication: W11 From a Domain Perspective"
date: 2024-12-08T00:21:01.147Z
updated: 2024-12-12T17:55:43.815Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Controlling User Authentication: W11 From a Domain Perspective"
excerpt: "This Article Describes Controlling User Authentication: W11 From a Domain Perspective"
keywords: User Auth Control,Domain Access Management,Security Login Systems,Identity Verification,Authentication Protocols,Wireless Network Safety,Authentication From a Domain View
thumbnail: https://thmb.techidaily.com/4c3c65f6b07b6c1127c499f9b9889ab3244702ce710d3692e68eb1f54ab083aa.jpg
---

## Controlling User Authentication: W11 From a Domain Perspective

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-docs.techidaily.com/ed-achieving-virality-on-youtube-essential-steps-demystified/"><u>[Updated] Achieving Virality on YouTube Essential Steps Demystified</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-invaluable-list-of-prime-no-charge-sites-for-seamless-video-editing-experience/"><u>[Updated] Invaluable List of Prime No-Charge Sites for Seamless Video Editing Experience</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-youtube-followers-surge-top-tips-for-channel-expansion/"><u>2024 Approved YouTube Followers Surge Top Tips for Channel Expansion</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-auto-triggered-cmd-openings-on-windows/"><u>Disabling Auto-Triggered CMD Openings on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/effective-strategies-for-print-problem-resolution-in-windows/"><u>Effective Strategies for Print Problem Resolution in Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-asus-rog-phone-8-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-itel-p55-5g-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Itel P55 5G? | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/narrative-analysis-torment-where-science-meets-fantasy-in-a-world-building-masterpiece/"><u>Narrative Analysis: Torment - Where Science Meets Fantasy in a World Building Masterpiece</u></a></li>
<li><a href="https://some-approaches.techidaily.com/streaming-stardom-versus-punch-driven-legends-for-2024/"><u>Streaming Stardom Versus Punch-Driven Legends for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-huawei-nova-y71-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Huawei Nova Y71 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-manual-to-thriving-at-ps1-on-win-unveiled-by-duckstation/"><u>The Complete Manual to Thriving at PS1 on WIN - Unveiled by Duckstation</u></a></li>
<li><a href="https://win11.techidaily.com/the-expert-writerspace-for-windows-photo-keys/"><u>The Expert' Writerspace for Windows Photo Keys</u></a></li>
<li><a href="https://win11.techidaily.com/the-in-depth-guide-to-fixing-your-windows-camera-app/"><u>The In-Depth Guide to Fixing Your Windows Camera App</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-creativity-with-these-windows-11-customizations/"><u>Unleash Creativity with These Windows 11 Customizations</u></a></li>
<li><a href="https://blog-min.techidaily.com/1725285473740-winx-dvd-rippervideo-converter/"><u>WinX DVD Ripper與Video Converter的解決方法: 最常遇到的磁盘分解器線上客户服务问题</u></a></li>
</ul></div>

