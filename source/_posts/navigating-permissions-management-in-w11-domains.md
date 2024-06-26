---
title: Navigating Permissions Management in W11, Domains
date: 2024-06-25T10:08:57.754Z
updated: 2024-06-26T10:08:57.754Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Permissions Management in W11, Domains
excerpt: This Article Describes Navigating Permissions Management in W11, Domains
keywords: W11 Permissions Guide,Domain Access Control,W11 Security Setup,Managing W11 Rights,Permissions Management,Domain Policy Handling,W11 Authorization Strategy
thumbnail: https://thmb.techidaily.com/b3641ebe2988ec7265ef07a79816e61c990d023d2c0afe9a3bce0644ce087752.jpg
---

## Navigating Permissions Management in W11, Domains

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
<li><a href="https://win11.techidaily.com/leading-password-guardians-revolutionizing-windows-11-life/"><u>Leading Password Guardians Revolutionizing Windows 11 Life</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-halting-windows-boot-straight-into-cmos-setup/"><u>Techniques for Halting Windows Boot Straight Into CMOS Setup</u></a></li>
<li><a href="https://win11.techidaily.com/overhaul-your-inbox-and-calendar-use-custom-images/"><u>Overhaul Your Inbox and Calendar: Use Custom Images</u></a></li>
<li><a href="https://win11.techidaily.com/surface-laptop-studio-review-the-quest-for-perfection-continues/"><u>Surface Laptop Studio Review: The Quest for Perfection Continues</u></a></li>
<li><a href="https://win11.techidaily.com/bridging-generations-old-games-with-dosbox-x/"><u>Bridging Generations: Old Games with DOSBox-X</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-windows-traditional-explore-view/"><u>Unleashing Windows' Traditional Explore View</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-rescuing-flaky-windows-programs/"><u>Mastering the Art of Rescuing Flaky Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-and-configuring-windows-data-sources-by-odbc/"><u>Accessing and Configuring Windows Data Sources by ODBC</u></a></li>
<li><a href="https://win11.techidaily.com/guide-repairing-windows-based-pen-tablets/"><u>Guide: Repairing Windows-Based Pen Tablets</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-30-leading-free-platforms-for-exceptional-youtube-intros/"><u>[New] In 2024, 30 Leading Free Platforms for Exceptional YouTube Intros</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-leading-8-multimedia-apps-for-creative-phones-android-ios/"><u>[New] The Leading 8 Multimedia Apps for Creative Phones (Android, iOS)</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-ultimate-guide-to-calculate-your-youtube-views-and-money/"><u>[New] Ultimate Guide to Calculate Your YouTube Views and Money</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-vivo-y78plus-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your Vivo Y78+ Phone Pattern Lock</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-your-journey-to-stylish-vlogging-a-beginners-guide-mac-edition/"><u>2024 Approved  Your Journey to Stylish Vlogging  A Beginner's Guide, Mac Edition</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-elite-streaming-sensations-worlds-most-popular-video-content-makers/"><u>[Updated] In 2024, Elite Streaming Sensations  World's Most Popular Video Content Makers</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-xiaomi-redmi-note-12-pro-4g-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Xiaomi Redmi Note 12 Pro 4G for Streaming | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-oneplus-nord-3-5g-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For OnePlus Nord 3 5G Phones</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-tailoring-teammate-backgrounds-on-teams-chat/"><u>2024 Approved  Tailoring Teammate Backgrounds on Teams Chat</u></a></li>
<li><a href="https://extra-information.techidaily.com/evaluating-available-vs-desired-vr-content-today/"><u>Evaluating Available Vs. Desired VR Content Today</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>