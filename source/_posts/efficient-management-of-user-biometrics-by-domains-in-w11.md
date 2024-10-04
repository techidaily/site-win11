---
title: Efficient Management of User Biometrics by Domains in W11
date: 2024-10-02T22:22:31.514Z
updated: 2024-10-03T19:40:12.316Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Efficient Management of User Biometrics by Domains in W11
excerpt: This Article Describes Efficient Management of User Biometrics by Domains in W11
keywords: User Bio-Metric Mgmt Efficiency,Domain-Based User Bioscans,Bio-Metrics Within Domains,Manage Biometrics by W11,Biodata Management Strategies,User Authentication via Domains,Efficient Bio-Data Control
thumbnail: https://thmb.techidaily.com/d11ab69328de06b2bbe702807d8f8d332f02dd668667f50f1987a428d6465f16.jpg
---

## Efficient Management of User Biometrics by Domains in W11

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
![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135415/19272" target="_top" id="2135415">
  <img src="//a.impactradius-go.com/display-ad/19272-2135415" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135415/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080312/19272" target="_top" id="2080312">
  <img src="//a.impactradius-go.com/display-ad/19272-2080312" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080312/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151870/7443" target="_top" id="2151870">
  <img src="//a.impactradius-go.com/display-ad/7443-2151870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Control Biometrics Logins on Your Computer

 Securing sensitive information has now become more important than ever. If you want to allow or block a domain user from logging on using biometrics, you can do that using the above methods.

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-how-to-delete-a-tiktok-account-permanently-in-2024/"><u>[New] How to Delete a TikTok Account Permanently, In 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-swiftvideo-pro-accelerate-your-android-content/"><u>[Updated] In 2024, SwiftVideo Pro Accelerate Your Android Content</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-monetization-mastery-guide-choosing-the-right-platform/"><u>[Updated] Monetization Mastery Guide Choosing the Right Platform</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-delete-visual-fluff-from-win-search-ui/"><u>How to Delete Visual Fluff From Win Search UI</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-xiaomi-civi-3-disney-100th-anniversary-edition-screen-sharing-drfone-by-drfone-android/"><u>How To Do Xiaomi Civi 3 Disney 100th Anniversary Edition Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-tecno-spark-20-pro-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Tecno Spark 20 Pro to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-nikons-1j5-videographer-a-spectacle-in-4k/"><u>In 2024, Nikon's 1J5 Videographer A Spectacle in 4K</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-youtubes-filmmaking-essentials-plus-invaluable-substitutes/"><u>In 2024, YouTube's Filmmaking Essentials + Invaluable Substitutes</u></a></li>
<li><a href="https://win11.techidaily.com/key-steps-for-a-detailed-look-at-your-windows-10-history/"><u>Key Steps for a Detailed Look at Your Windows 10 History</u></a></li>
<li><a href="https://win11.techidaily.com/notepadnightvisionswitchtutorialwin1011/"><u>NotepadNightVisionSwitchTutorialWin10/11</u></a></li>
<li><a href="https://win11.techidaily.com/swift-steps-for-resuming-google-drives-auto-sync-on-window-pc/"><u>Swift Steps for Resuming Google Drive's Auto-Sync on Window PC</u></a></li>
<li><a href="https://win11.techidaily.com/sync-your-swat-team-tips-to-stop-mouse-delay-in-bf2/"><u>Sync Your Swat Team: Tips to Stop Mouse Delay in BF2</u></a></li>
<li><a href="https://win11.techidaily.com/tech-tips-resolving-win-access-denials-swiftly/"><u>Tech Tips: Resolving Win Access Denials Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-batches-into-executables-on-windows-os/"><u>Transforming Batches Into Executables on Windows OS</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    