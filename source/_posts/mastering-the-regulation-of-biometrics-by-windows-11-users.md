---
title: Mastering the Regulation of Biometrics by Windows 11 Users
date: 2025-01-04T19:09:41.207Z
updated: 2025-01-06T19:51:13.665Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering the Regulation of Biometrics by Windows 11 Users
excerpt: This Article Describes Mastering the Regulation of Biometrics by Windows 11 Users
keywords: Windows 11 BioRegulation,Biometric Mastery Win11,11 Win Biometrics Control,Win11 Biometry Management,BioRegulate Win Users,User BioControl Win11,Win11 Biometrics Guide
thumbnail: https://thmb.techidaily.com/704c497d76ce3443a342fa34e8883ce74ed2e3eea338695faa58de9221c96a80.jpg
---

## Mastering the Regulation of Biometrics by Windows 11 Users

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Enable option in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/enable-option.png)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-helps.techidaily.com/new-2024-approved-score-big-with-these-8-no-cost-3d-videos-apps-for-windows-and-mac-os/"><u>[New] 2024 Approved Score Big with These 8 No-Cost 3D Videos Apps for Windows & Mac OS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-elevating-visual-content-a-guide-to-adding-descriptions-on-instagram/"><u>[New] In 2024, Elevating Visual Content A Guide to Adding Descriptions on Instagram</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-capturing-moments-with-the-best-5-photo-and-video-apps-for-iphonesandroid/"><u>[Updated] 2024 Approved Capturing Moments with the Best 5 Photo & Video Apps for iPhones/Android</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-xiaomi-redmi-12-5g-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Xiaomi Redmi 12 5G is off? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-n-versions-usage-insights/"><u>Exploring Windows N Versions: Usage Insights</u></a></li>
<li><a href="https://win11.techidaily.com/halt-discord-auto-launch-and-update-checks-on-windows-10/"><u>Halt Discord Auto-Launch & Update Checks on Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/how-does-windows-11-secure-your-digital-assets/"><u>How Does Windows 11 Secure Your Digital Assets?</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-address-and-rectify-the-btballoondll-file-missing-problem-on-pcs/"><u>How to Address and Rectify the Btballoon.dll File Missing Problem on PCs</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-gt-neo-5-se-by-drfone-android-unlock-android-unlock/"><u>How to unlock GT Neo 5 SE</u></a></li>
<li><a href="https://win11.techidaily.com/linux-pure-drop-wsl/"><u>Linux Pure - Drop WSL</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-pagefilesys-usage-and-importance-in-winos/"><u>Navigating Through Pagefile.sys Usage & Importance in WinOS</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/95935402-9781844098033-psychic-development-the-basics/"><u>Psychic Development the Basics | Free Book</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-syncs-restored-overcome-google-drive-pc-challenges/"><u>Seamless Syncs Restored: Overcome Google Drive PC Challenges</u></a></li>
<li><a href="https://extra-information.techidaily.com/step-by-step-to-becoming-a-9gag-meme-genius/"><u>Step-by-Step to Becoming a 9GAG Meme Genius</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-data-management-in-windows-with-date-mods/"><u>Streamlining Data Management in Windows with Date Mods</u></a></li>
<li><a href="https://win11.techidaily.com/the-mechanism-behind-windows-reserve-memory-system/"><u>The Mechanism Behind Windows' Reserve Memory System</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/vllo-on-mac-your-ultimate-guide-to-downloads-and-alternatives/"><u>VLLO on Mac Your Ultimate Guide to Downloads and Alternatives</u></a></li>
</ul></div>

