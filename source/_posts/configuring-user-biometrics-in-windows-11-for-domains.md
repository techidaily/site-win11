---
title: Configuring User Biometrics in Windows 11 for Domains
date: 2024-12-22T02:21:52.739Z
updated: 2024-12-27T23:03:32.886Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Configuring User Biometrics in Windows 11 for Domains
excerpt: This Article Describes Configuring User Biometrics in Windows 11 for Domains
keywords: Win11 Biometric Setup,Domain-Level Biometry,Windows Biometrics Config,Secure Windows Biometrics,User Access Control Windows,Windows Authentication Domains,Biometric Enablement in Win11
thumbnail: https://thmb.techidaily.com/73087a990223851f6a7c5417d3512a4d93ddbbb6cac79840abc644367d7f8449.jpg
---

## Configuring User Biometrics in Windows 11 for Domains

 Biometric authentication allows you to quickly log in to the system using fingerprint, facial, or iris recognition. However, what if you want to prevent a domain user from logging in using biometrics?

 This article will show some quick ways to allow or block a domain user from logging on using biometrics in Windows 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-techniques.techidaily.com/updated-hues-harmony-an-editors-guide-to-perfect-grading/"><u>[Updated] Hues Harmony An Editor's Guide to Perfect Grading</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-prime-editing-choosing-the-best-for-youtube/"><u>[Updated] Prime Editing Choosing the Best For YouTube</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-revolutionizing-storytelling-free-onlineoffline-animations/"><u>2024 Approved Revolutionizing Storytelling Free Online/Offline Animations</u></a></li>
<li><a href="https://win11.techidaily.com/elevated-note-management-smarter-strategies-for-windows-users/"><u>Elevated Note Management: Smarter Strategies for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/fresh-start-from-past-protection-4-key-windows-cleanup-tips/"><u>Fresh Start From Past Protection: 4 Key Windows Cleanup Tips</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-xs-to-androidios-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone XS To Android/iOS? | Dr.fone</u></a></li>
<li><a href="https://win-studio.techidaily.com/march-highlights-mastering-karaoke-with-software-stars-russ-doc-and-wristen-on-cloud-streaming-success/"><u>March Highlights: Mastering Karaoke with Software Stars Russ DOC and Wristen on Cloud Streaming Success!</u></a></li>
<li><a href="https://solve-manuals.techidaily.com/master-scan-troubleshooting-on-windows-with-tips-from-yl-computings-yl-software/"><u>Master Scan Troubleshooting on Windows with Tips From YL Computing's YL Software</u></a></li>
<li><a href="https://win11.techidaily.com/master-windows-task-handling-with-advanced-execution-tools/"><u>Master Windows Task Handling with Advanced Execution Tools</u></a></li>
<li><a href="https://data-wizards.techidaily.com/mendcorrupted-high-definition-data-doctor/"><u>MendCorrupted: High Definition Data Doctor</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-art-of-note-saving-windows/"><u>Navigating the Art of Note-Saving Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-correct-unsuranlized-device-error-on-windows/"><u>Steps to Correct Unsuranlized Device Error on Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-complete-guide-to-google-pixel-7a-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Google Pixel 7a FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-device-usage-mastering-samsungs-dex-application/"><u>Transform Your Device Usage: Mastering Samsung's DeX Application</u></a></li>
<li><a href="https://common-error.techidaily.com/what-should-i-do-when-windows-10-hangs/"><u>What Should I Do when Windows 10 Hangs?</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-comparison-discovering-the-ideal-edition-fit-homepro/"><u>Windows 11 Comparison: Discovering the Ideal Edition Fit (Home/Pro)</u></a></li>
</ul></div>

