---
title: Enabling/Disabling User Biometric Use by Domains
date: 2024-08-16T00:38:25.892Z
updated: 2024-08-17T00:38:25.892Z
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
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
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-farm-tastic-fun-and-games-top-friendly-farming-titles/"><u>[New] 2024 Approved  Farm-Tastic Fun & Games  Top Friendly Farming Titles</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-brand-your-content-download-complimentary-templates-for-youtube-makers/"><u>[New] Brand Your Content  Download Complimentary Templates for YouTube Makers</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-ideal-tools-for-creating-animation-with-models/"><u>[New] Ideal Tools for Creating Animation with Models</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-pcs-choice-for-classic-gaming-essential-top-5-ps1-emulators-for-2024/"><u>[New] PC's Choice for Classic Gaming  Essential Top 5 PS1 Emulators for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-snap-it-all-complimentary-android-recordings/"><u>[New] Snap It All  Complimentary Android Recordings</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-essential-strategies-for-capturing-your-best-moments-in-snapchat/"><u>2024 Approved  Essential Strategies for Capturing Your Best Moments in Snapchat</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-real-world-usability-of-photoshops-motion-reduction/"><u>2024 Approved  The Real-World Usability of Photoshop’s Motion Reduction</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-msresourceappname-text-glitch-in-w11/"><u>Addressing 'MsResource/AppName Text' Glitch in W11</u></a></li>
<li><a href="https://win11.techidaily.com/assessing-the-impact-do-widgets-streamline-win-11s-usage/"><u>Assessing the Impact: Do Widgets Streamline Win 11'S Usage?</u></a></li>
<li><a href="https://win11.techidaily.com/cleaning-slates-in-windows-the-3-reset-routes/"><u>Cleaning Slates in Windows: The 3 Reset Routes</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-variability-between-offline-and-online-windows-installation-processes/"><u>Delving Into Variability Between Offline and Online Windows Installation Processes</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-copy-paste-with-predefined-text-in-w10w11/"><u>Efficient Copy-Paste with Predefined Text in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/fingerprint-fiasco-can-you-still-count-on-windows-hello/"><u>Fingerprint Fiasco: Can You Still Count on Windows Hello?</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-microsoft-teams-stalling-in-w11w10-systems/"><u>Fixing Microsoft Teams Stalling in W11/W10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/from-boring-to-stunning-switching-themes-in-windows-11-made-simple/"><u>From Boring to Stunning: Switching Themes in Windows 11 Made Simple</u></a></li>
<li><a href="https://vp-tips.techidaily.com/fundamental-concepts-of-cyber-narratives/"><u>Fundamental Concepts of Cyber Narratives</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-samsung-galaxy-s23plus-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Samsung Galaxy S23+ Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-ispoofer-update-on-poco-f5-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Will iSpoofer update On Poco F5 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fixes-for-error-code-0x8000fffd-on-pcs/"><u>Mastering Fixes for Error Code 0X8000FFFD on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-volume-adjustment-issues-in-windows-os/"><u>Mastering Volume Adjustment Issues in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-group-policy-changes-on-a-windows-system/"><u>Navigating Group Policy Changes on a Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-galaxy-performance-through-seamless-integration-in-windows-11/"><u>Optimizing Galaxy Performance Through Seamless Integration in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-more-space-files-issue/"><u>Overcoming 'No More Space' Files Issue</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unable-to-display-errors-in-microsoft-store/"><u>Overcoming 'Unable to Display' Errors in Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-thumbnails-dimensions-on-desktop/"><u>Personalize Thumbnails: Dimensions on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/power-tools-for-pc-mastery-command-prompt-edition-of-win-registry-edits/"><u>Power Tools for PC Mastery: Command Prompt Edition of Win Registry Edits</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-pc-data-access-everythingapp-utilization/"><u>Rapid PC Data Access: EverythingApp Utilization</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-keyboard-errors-fixing-function-keys-on-windows-11/"><u>Resolve: Keyboard Errors - Fixing Function Keys on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/resurrect-dead-audio-a-step-by-step-guide-to-tech-sound/"><u>Resurrect Dead Audio: A Step-by-Step Guide to Tech Sound</u></a></li>
<li><a href="https://win11.techidaily.com/solving-installed-but-inaccessible-microsoft-apps/"><u>Solving Installed but Inaccessible Microsoft Apps</u></a></li>
<li><a href="https://win11.techidaily.com/solving-mbs-service-connection-failures-on-windows-11/"><u>Solving MB's Service Connection Failures on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/stop-blue-screen-bsos-quick-fix-strategies-for-win11/"><u>Stop Blue Screen BSOS: Quick Fix Strategies for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/the-clear-sight-crusade-nine-methods-to-sharpen-your-monitor/"><u>The Clear Sight Crusade: Nine Methods to Sharpen Your Monitor</u></a></li>
<li><a href="https://win11.techidaily.com/the-top-7-no-cost-player-titles-for-pcs-and-viewing/"><u>The Top 7 No-Cost Player Titles for PCs & Viewing</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-6-gopro-helmet-harnesses-tips-and-techniques-unveiled-for-2024/"><u>Top 6 GoPro Helmet Harnesses  Tips and Techniques Unveiled for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transforming-your-search-with-microsofts-ai-enhanced-bing-the-future-is-here/"><u>Transforming Your Search with Microsoft's AI-Enhanced Bing: The Future Is Here</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-for-quickly-resolving-operation-requirement-errors/"><u>Troubleshooting Steps for Quickly Resolving Operation Requirement Errors</u></a></li>
<li><a href="https://win11.techidaily.com/1719276552494-unlock-windows-free-up-space-no-more-temp-files/"><u>Unlock Windows Free Up Space, No More Temp Files</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-distinctions-of-windows-terminal-vs-powershell/"><u>Unraveling The Distinctions of Windows Terminal Vs. PowerShell</u></a></li>
</ul></div>
