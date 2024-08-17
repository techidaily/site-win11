---
title: Perfecting User Authentication Management for Domains in W11
date: 2024-08-15T23:58:48.756Z
updated: 2024-08-16T23:58:48.756Z
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

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
## How to Allow or Block a Biometrics Log-On Using the Registry Editor

 Another way to configure biometrics log-on for the domain users is through the Registry Editor. Here's how:

 Editing the registry is risky, as one wrong edit can make your system unstable. Therefore, make sure to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding with the steps.

1. Open the Run tool, type **regedit** in the search bar, and press Enter.
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Biometrics\Credential Provider`
3. Right-click the **Credential Provider** key in the left sidebar, hover the cursor to **New,** and choose **DWORD (32-bit) Value**.  
![DWORD (32-bit) Value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/dword-32-bit-value.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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
<li><a href="https://fox-access.techidaily.com/new-high-definition-wonders-our-favorites-list/"><u>[New] High Definition Wonders  Our Favorites List</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-talking-head-techniques-diy-filming-made-simple/"><u>[New] Talking Head Techniques  DIY Filming Made Simple</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-top-5-eco-conscious-filmmaking-advances-for-2024/"><u>[New] Top 5 Eco-Conscious Filmmaking Advances for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-video-splitting-expertise-best-recorder-verdict/"><u>[Updated] Video Splitting Expertise  Best Recorder Verdict</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-digital-frontier-exploration-selecting-best-tools-for-turning-images-into-nfts/"><u>2024 Approved  Digital Frontier Exploration  Selecting Best Tools for Turning Images Into NFTs</u></a></li>
<li><a href="https://win11.techidaily.com/5-quick-wins-to-tackle-your-window-writes-woes/"><u>5 Quick Wins to Tackle Your Window' Writes Woes</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-success-must-haves-from-microsoft-store/"><u>Accelerated Success: Must-Haves From Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/compreehing-windows-11-printer-offline-error-causes/"><u>Compreehing Windows 11 Printer Offline Error Causes</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-custom-audio-commands-in-the-latest-windows-os/"><u>Crafting Custom Audio Commands in the Latest Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-tips-to-unite-folders-and-files-in-windows-11/"><u>Cutting-Edge Tips to Unite Folders & Files in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/easy-steps-setup-google-play-store-on-win11/"><u>Easy Steps: Setup Google Play Store on Win11</u></a></li>
<li><a href="https://howto.techidaily.com/fix-lava-blaze-pro-5g-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Lava Blaze Pro 5G Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guarding-against-hidden-threats-in-these-7-windows-processes/"><u>Guarding Against Hidden Threats in These 7 Windows Processes</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-tecno-pova-6-pro-5g-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Tecno Pova 6 Pro 5G Without Password | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-itel-p55-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Itel P55 by Phone Number | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-11-best-pokemon-go-spoofers-for-gps-spoofing-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>In 2024, 11 Best Pokemon Go Spoofers for GPS Spoofing on Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/kobo-libra-vs-amazon-kindle-showdown-an-in-depth-book-reader-comparison/"><u>Kobo Libra Vs. Amazon Kindle Showdown: An In-Depth Book Reader Comparison</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-realtek-audio-driver-downloads-compatible-with-windows-11107/"><u>Latest Realtek Audio Driver Downloads Compatible with Windows 11/10/7</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-ms-store-repairs-overcoming-server-slip-ups-on-windows-os/"><u>Mastering MS Store Repairs: Overcoming Server Slip-Ups on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-of-microsoft-store-error-solving-in-windows/"><u>Mastery of Microsoft Store Error Solving in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mend-your-guard-easy-steps-to-making-family-safe-work-again/"><u>Mend Your Guard: Easy Steps to Making Family Safe Work Again</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-gaming-glitches-keeping-df-playtime-uninterrupted/"><u>Navigating Gaming Glitches: Keeping DF Playtime Uninterrupted</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-lan-gaming-challenges-on-pc-winsminecraft/"><u>Overcoming LAN Gaming Challenges on PC, WinsMinecraft</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-missing-display-after-power-on/"><u>Overcoming Missing Display After Power On</u></a></li>
<li><a href="https://win11.techidaily.com/pro-wls-2-strategies-optimizing-linux-experience-in-windows/"><u>Pro WLS 2 Strategies: Optimizing Linux Experience in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-enabling-your-pen-on-windows-os/"><u>Quick Fix: Enabling Your Pen on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/reveal-windows-secrets-to-handbrake-use/"><u>Reveal Windows' Secrets to HandBrake Use</u></a></li>
<li><a href="https://win11.techidaily.com/secure-and-cost-free-windows-password-gen-options-listed/"><u>Secure & Cost-Free Windows Password Gen Options Listed</u></a></li>
<li><a href="https://win11.techidaily.com/setting-custom-keys-for-windows-applications/"><u>Setting Custom Keys for Windows Applications</u></a></li>
<li><a href="https://win11.techidaily.com/solving-windows-11-menu-glitches-a-step-by-step-guide/"><u>Solving Windows 11 Menu Glitches: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-prevent-and-fix-winscombsvrdll-crashes-on-pcs/"><u>Steps to Prevent and Fix WinscombSvr.dll Crashes on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-solve-the-non-operational-escape-button-on-your-desktop/"><u>Swiftly Solve the Non-Operational Escape Button on Your Desktop</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/switch-cards-between-apple-iphone-12-and-other-iphones-will-move-all-phone-services-drfone-by-drfone-transfer-from-ios/"><u>Switch Cards Between Apple iPhone 12 and other iPhones Will Move All Phone Services? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-vivo-x90s-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Vivo X90S Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-subsystem-for-android-is-going-away-what-should-you-do-now/"><u>Windows Subsystem for Android Is Going Away: What Should You Do Now?</u></a></li>
</ul></div>
