---
title: Navigating Permissions Management in W11, Domains
date: 2024-08-16T00:19:11.577Z
updated: 2024-08-17T00:19:11.577Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
4. Name the value **Domain Accounts.**  
![Naming the Value Domain Accounts](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/domain-accounts.jpg)
<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Double-click on the Domain Accounts value, type **1** in the **Value data** section to enable biometrics log on and **0** to disable biometrics log on for domain users.  
![Editing the Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/value-data.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click **OK** to save the changes.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-mastering-media-locate-your-latest-favorites-on-facebook/"><u>[New] 2024 Approved  Mastering Media  Locate Your Latest Favorites on Facebook</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-converting-ephemeral-content-fb-messenger-video-secrets-revealed-for-2024/"><u>[New] Converting Ephemeral Content  FB Messenger Video Secrets Revealed for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-effortless-hulu-recordings-for-windows-mac-and-mobile-users-for-2024/"><u>[New] Effortless Hulu Recordings for Windows, Mac & Mobile Users for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-open-world-wonders-beyond-gtas-empire/"><u>[New] In 2024, Open World Wonders Beyond GTA's Empire</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-academic-anchors-identifying-top-10-lecture-preservation-tools/"><u>[Updated] 2024 Approved  Academic Anchors  Identifying Top 10 Lecture Preservation Tools</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-channel-acquisition-101-maximizing-youtubers-earnings/"><u>[Updated] 2024 Approved  Channel Acquisition 101  Maximizing Youtubers' Earnings</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-full-exploration-decoding-googles-podcast-app/"><u>[Updated] Full Exploration  Decoding Google's Podcast App</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-chaos-to-order-youtube-playlists-unveiled/"><u>[Updated] In 2024, From Chaos to Order  YouTube Playlists Unveiled</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-the-clearest-waves-premier-mic-selection/"><u>2024 Approved  The Clearest Waves  Premier Mic Selection</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-samsung-galaxy-xcover-6-pro-tactical-edition-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Samsung Galaxy XCover 6 Pro Tactical Edition | Dr.fone</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723013467976-a-lack-of-depth-and-complexity-compared-to-its-predecessors-meant-that-hardcore-fans-of-the-series-felt-unchallenged-by-the-gameplay-experience/"><u>A Lack of Depth and Complexity Compared to Its Predecessors Meant that Hardcore Fans of the Series Felt Unchallenged by the Gameplay Experience.</u></a></li>
<li><a href="https://win11.techidaily.com/boost-your-git-proficiency-with-github-desktop-on-windows-11/"><u>Boost Your Git Proficiency with Github Desktop on Windows 11</u></a></li>
<li><a href="https://printer-issues.techidaily.com/correcting-scan-failures-with-xerox/"><u>Correcting Scan Failures with Xerox</u></a></li>
<li><a href="https://win11.techidaily.com/discover-your-device-the-ultimate-guide-for-model-names/"><u>Discover Your Device: The Ultimate Guide for Model Names</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-redesigned-windows-11-widget-pickers/"><u>Enabling Redesigned Windows 11 Widget Pickers</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-edge-browsing-experience-on-win10w11/"><u>Enhance Your Edge Browsing Experience on Win10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-fix-windows-key-problems/"><u>Essential Steps to Fix Windows Key Problems</u></a></li>
<li><a href="https://win-dash.techidaily.com/expert-guide-choosing-and-downloading-high-quality-sound-drivers-for-win7/"><u>Expert Guide: Choosing & Downloading High-Quality Sound Drivers for Win7</u></a></li>
<li><a href="https://win11.techidaily.com/expert-insights-accurate-mac-location-techniques-in-windows-11/"><u>Expert Insights: Accurate MAC Location Techniques in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-windows-11s-foundation-a-deep-dive-into-its-registry/"><u>Exploring Windows 11'S Foundation: A Deep Dive Into Its Registry</u></a></li>
<li><a href="https://win11.techidaily.com/from-digital-tunes-to-physical-form-transforming-your-mp3s-on-pc-using-imgburn-windows/"><u>From Digital Tunes to Physical Form: Transforming Your MP3s on PC Using ImgBurn (Windows)</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-zero-to-hero-in-instagram-world-top-9-pathways-unveiled-for-2024/"><u>From Zero to Hero in Instagram World  Top 9 Pathways Unveiled for 2024</u></a></li>
<li><a href="https://techidaily.com/how-to-hard-reset-vivo-y100-without-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Hard Reset Vivo Y100 Without Password | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-nvidia-cp-access-denied-in-win1110/"><u>How to Overcome NVidia CP Access Denied in Win11/10</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-infinix-hot-40i-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Infinix Hot 40i FRP Locks</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-locating-and-unveiling-your-personalized-melodic-repository-on-youtube/"><u>In 2024, Locating and Unveiling Your Personalized Melodic Repository on Youtube</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/laugh-line-by-line-building-a-meme-friendly-video-portfolio-for-2024/"><u>Laugh Line by Line  Building a Meme-Friendly Video Portfolio for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-maneuvers-to-navigate-stalled-windows-install-steps/"><u>Masterful Maneuvers to Navigate Stalled Windows Install Steps</u></a></li>
<li><a href="https://win11.techidaily.com/max-out-your-games-on-windows-the-amd-optimization-guide/"><u>Max Out Your Games on Windows: The AMD Optimization Guide</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/midgard-alliance-defenders-of-ragnarok/"><u>Midgard Alliance  Defenders of Ragnarok</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-spotify-connection-failures-on-win11/"><u>Navigating Through Spotify Connection Failures on Win11</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-what-is-ai-voice-text-to-speech-in-2024/"><u>New What Is AI Voice Text to Speech, In 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-detection-issues-with-razer-on-windows-11/"><u>Overcoming Device Detection Issues with Razer on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-hurdles-of-reverting-folders-to-read-only/"><u>Overcoming the Hurdles of Reverting Folders to Read-Only</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-error-codes-0xc0000001-guide/"><u>Overcoming Windows Error Codes - 0xC0000001 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/perfect-your-footage-the-ultimate-selection-of-video-cutters-on-win11/"><u>Perfect Your Footage: The Ultimate Selection of Video Cutters on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/purging-power-users-the-guide-to-default-settings/"><u>Purging Power Users: The Guide to Default Settings</u></a></li>
<li><a href="https://extra-tips.techidaily.com/skys-the-limit-with-dji-spark-an-in-depth-miniature-drone-study/"><u>Sky's the Limit with DJI Spark  An In-Depth Miniature Drone Study</u></a></li>
<li><a href="https://extra-skills.techidaily.com/stealthy-strategies-for-anonymous-instagram-broadcasts-for-2024/"><u>Stealthy Strategies for Anonymous Instagram Broadcasts for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-solve-the-email-fault-caused-by-0x800713f-on-win11/"><u>Steps to Solve the Email Fault Caused by 0X800713F on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-connection-between-win-code-and-microsoft-services/"><u>Streamlining Connection Between WIN Code and Microsoft Services</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-geforce-failures-head-on-today/"><u>Tackle Windows GeForce Failures Head-On Today</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-amd-195-error-in-windows-installations/"><u>Tackling AMD 195 Error in Windows Installations</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-need-privilege-escalation-issue-fixing-error-740/"><u>Tackling Need Privilege Escalation Issue: Fixing Error 740</u></a></li>
<li><a href="https://win11.techidaily.com/teams-growth-without-the-heavy-load/"><u>Teams Growth Without the Heavy Load</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-fix-wrongly-entered-characters-in-windows/"><u>Tips to Fix Wrongly Entered Characters in Windows</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-realme-gt-neo-5-se-drfone-by-drfone-virtual-android/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Realme GT Neo 5 SE | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/top-8-methods-for-eliminating-windows-errors/"><u>Top 8 Methods for Eliminating Windows Errors</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-techniques-windows-sandbox-lacks-hyprocvisor/"><u>Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-correcting-windows-install-errors-win11/"><u>Understanding and Correcting Windows Install Errors (Win11)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Motorola Defy 2? | Dr.fone</u></a></li>
</ul></div>
