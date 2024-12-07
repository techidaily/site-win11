---
title: "Controlling User Authentication: W11 From a Domain Perspective"
date: 2024-12-06T04:56:53.353Z
updated: 2024-12-07T04:05:07.320Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/ed-2024s-guide-to-profit-youtube-monetization-with-joshi/"><u>[Updated] 2024'S Guide to Profit YouTube Monetization with Joshi</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-enter-the-world-of-online-promotion-exclusive-free-youtube-banner-access-for-2024/"><u>[Updated] Enter the World of Online Promotion Exclusive Free YouTube Banner Access for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-impressive-initiations-podcasting-prose-poems-for-2024/"><u>[Updated] Impressive Initiations Podcasting Prose Poems for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-motorola-moto-g24-frp-bypass-by-drfone-android/"><u>About Motorola Moto G24 FRP Bypass</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-mythical-device-spec-error-in-windows-11/"><u>Fixing Mythical Device Spec Error in Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-6s-plus-without-passcode-by-drfone-ios/"><u>How to Unlock iPhone 6s Plus Without Passcode?</u></a></li>
<li><a href="https://win11.techidaily.com/methodical-approach-to-quiet-background-programs-in-win11/"><u>Methodical Approach to Quiet Background Programs in Win11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/twitscam-takedown-with-the-advent-of-metasignature/"><u>TwitScam Takedown with the Advent of MetaSignature</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-autodelete-a-compreenas-guide-to-disk-management/"><u>Win11's Autodelete: A Compreenas Guide to Disk Management</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-drop-error-step-by-step-solutions/"><u>Win11's Drop Error: Step-by-Step Solutions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    