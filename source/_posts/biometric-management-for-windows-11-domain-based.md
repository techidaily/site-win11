---
title: Biometric Management for Windows 11, Domain-Based
date: 2024-07-13T10:48:09.364Z
updated: 2024-07-14T10:48:09.364Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Biometric Management for Windows 11, Domain-Based
excerpt: This Article Describes Biometric Management for Windows 11, Domain-Based
keywords: Win11 Biometrics Secure,Domain-Based Biometric,Windows Security Key,PC Biometric Access,Windows 11 Identity,Domain Authentication,Windows ID Management
thumbnail: https://thmb.techidaily.com/0f08e68155172a78a589fb6b8f18fbb5a0a1a4069ed8867faff7b1ab4f999000.jpg
---

## Biometric Management for Windows 11, Domain-Based

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
<li><a href="https://unlock-android.techidaily.com/top-12-prominent-vivo-y200e-5g-fingerprint-not-working-solutions-by-drfone-android/"><u>Top 12 Prominent Vivo Y200e 5G Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-realme-gt-5-drfone-by-drfone-virtual-android/"><u>Best Pokemons for PVP Matches in Pokemon Go For Realme GT 5 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/break-free-from-google-chrome-glitch-on-windows-11-now/"><u>Break Free From Google Chrome Glitch on Windows 11 Now!</u></a></li>
<li><a href="https://win11.techidaily.com/ceasing-erratic-mouse-movement-in-windows/"><u>Ceasing Erratic Mouse Movement in Windows</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-instagram-filters-in-a-nutshell-get-them-right-this-year/"><u>2024 Approved  Instagram Filters in a Nutshell  Get Them Right This Year</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-down-on-space-spotlight-on-large-files-in-windows/"><u>Cutting Down on Space: Spotlight on Large Files in Windows</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-horizon-captured-which-camera-takes-the-lead/"><u>[New] Horizon Captured  Which Camera Takes the Lead?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-differentiate-with-style-on-snapchat-top-120plus-narratives-for-your-private-stories/"><u>[New] 2024 Approved  Differentiate with Style on Snapchat  Top 120+ Narratives for Your Private Stories</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-depth-guide-to-extracting-vimeo-media/"><u>[Updated] In-Depth Guide to Extracting Vimeo Media</u></a></li>
<li><a href="https://win11.techidaily.com/cutting-edge-control-set-active-hours-to-avoid-surprises-on-windows-11/"><u>Cutting Edge Control: Set Active Hours to Avoid Surprises on Windows 11</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-easiest-video-making-apps-for-mac-unleash-your-creativity/"><u>New Easiest Video Making Apps for Mac Unleash Your Creativity</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-wacatacbml-understanding-and-neutralizing-threats-on-windows/"><u>Breaking Down Wacatac.B!ml: Understanding and Neutralizing Threats on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/flush-your-steam-dns-data-a-windows-user-guide/"><u>Flush Your Steam DNS Data - A Windows User Guide</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-syncing-your-phone-with-windows-11-via-unison/"><u>Expert Tips: Syncing Your Phone with Windows 11 via Unison</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-adobe-premiere-pro-cs6-mac-version-get-it-free/"><u>New In 2024, Adobe Premiere Pro CS6 Mac Version Get It Free</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-root-user-access-in-the-windows-terminal/"><u>Ensuring Root User Access in the Windows Terminal</u></a></li>
<li><a href="https://win11.techidaily.com/converting-from-pin-to-password-a-windows-11-users-guide-for-enhanced-security/"><u>Converting From PIN to Password: A Windows 11 User's Guide for Enhanced Security</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-add-firewall-options-for-blocking-software-to-windows-11s-context-menu/"><u>How to Add Firewall Options for Blocking Software to Windows 11’S Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/expertly-restoring-erased-data-in-a-microsoft-world/"><u>Expertly Restoring Erased Data in a Microsoft World</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-user-sign-in-after-windows-authentication-issues/"><u>Enabling User Sign-In After Windows Authentication Issues</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-1011s-audacity-audio-connection-failures/"><u>Fixing Windows 10/11’S Audacity Audio Connection Failures</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-explore-free-vimeo-video-editing-tips-and-tricks/"><u>[New] In 2024, Explore Free Vimeo Video Editing Tips and Tricks</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-globe-spin-technology-in-lenses-versus-depth-perception-tech/"><u>[New] Globe-Spin Technology in Lenses versus Depth Perception Tech</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-photoshopping-in-windows-11-without-hurdles/"><u>Enabling Photoshopping in Windows 11 Without Hurdles</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-leading-tools-to-download-your-favorite-pinterest-videos-for-nothing/"><u>[Updated] Leading Tools to Download Your Favorite Pinterest Videos for Nothing</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-keep-windows-open-avoid-lockout-feature/"><u>How To Keep Windows Open: Avoid Lockout Feature</u></a></li>
<li><a href="https://win11.techidaily.com/1719193162154-unlocking-the-secrets-to-fixing-non-working-win-plus-printer/"><u>Unlocking The Secrets to Fixing Non-Working Win + Printer.</u></a></li>
<li><a href="https://win11.techidaily.com/aesthetic-enhancement-in-wt-with-personalized-schemes/"><u>Aesthetic Enhancement in WT with Personalized Schemes</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-fixing-blue-windows-fails/"><u>Mastering the Art of Fixing Blue Windows Fails</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-error-code-0xa00f425d-in-windows-1e11-camera/"><u>Correcting Error Code: 0XA00F425D in Windows 1E11 Camera</u></a></li>
<li><a href="https://win11.techidaily.com/wrapping-windows-games-in-christmas-carols/"><u>Wrapping Windows Games in Christmas Carols</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-oppo-reno-11-pro-5g-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Oppo Reno 11 Pro 5G Phones</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-management-using-mspcm-toolbar-in-w11-os/"><u>Efficient Management Using MSPCM Toolbar in W11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-in-nullifying-windows-11s-eyes-on-you/"><u>Mastery in Nullifying Windows 11'S Eyes on You</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/enhance-your-game-with-this-superb-cost-free-sound-altering-app/"><u>Enhance Your Game with This Superb, Cost-Free Sound Altering App</u></a></li>
<li><a href="https://win11.techidaily.com/deactivating-mouse-speed-sensitivity-in-windows-1011/"><u>Deactivating Mouse Speed Sensitivity in Windows 10/11</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-rectify-invalid-label-error-on-windows-11/"><u>Guide to Rectify 'Invalid Label' Error on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-critical-winerror-upgrade-fault-0xc004f050/"><u>Fixing Critical WinError: Upgrade Fault #0XC004F050</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-advanced-techniques-in-final-cut-pro-embedding-waveform-diagrams-with-live-audio-animation/"><u>New Advanced Techniques in Final Cut Pro Embedding Waveform Diagrams with Live Audio Animation</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-factory-reset-ipad-or-apple-iphone-14-pro-without-icloud-password-or-apple-id-by-drfone-ios/"><u>How to Factory Reset iPad or Apple iPhone 14 Pro without iCloud Password or Apple ID?</u></a></li>
<li><a href="https://win11.techidaily.com/1719376947968-regain-your-account-in-microsoft-store-now/"><u>Regain Your Account in Microsoft Store, Now!</u></a></li>
<li><a href="https://android-frp.techidaily.com/latest-guide-how-to-bypass-oppo-reno-10-pro-5g-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Oppo Reno 10 Pro 5G FRP Without Computer</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-breakthrough-in-youtube-saving-technology/"><u>2024 Approved  Breakthrough in YouTube Saving Technology</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-how-to-manipulate-iphone-pics-flip-tilt-and-more/"><u>2024 Approved  How to Manipulate iPhone Pics  Flip, Tilt & More</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-exploring-the-purpose-of-instagram-story-sections-for-2024/"><u>[New] Exploring the Purpose of Instagram Story Sections for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-integrating-social-networks-sharing-fb-videos-on-whatsapp/"><u>[New] 2024 Approved  Integrating Social Networks  Sharing FB Videos on WhatsApp</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-esteemed-creators-best-of-breed-insta-hlv-makers/"><u>[Updated] 2024 Approved  Esteemed Creators  Best-of-Breed Insta HLV Makers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Huawei Nova Y91? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/speedy-windows-file-review-strategies-for-2024/"><u>Speedy Windows File Review Strategies for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-text-actions-in-the-snipping-tool-on-windows-11/"><u>How to Use Text Actions in the Snipping Tool on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/easy-paths-back-to-success-in-steam-gaming/"><u>Easy Paths Back to Success in Steam Gaming</u></a></li>
<li><a href="https://discord-videos.techidaily.com/disconnect-your-discord-account-for-2024/"><u>Disconnect Your Discord Account for 2024</u></a></li>
</ul></div>
