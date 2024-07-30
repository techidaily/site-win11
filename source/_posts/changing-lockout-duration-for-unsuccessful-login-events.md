---
title: Changing Lockout Duration for Unsuccessful Login Events
date: 2024-07-29T15:53:47.522Z
updated: 2024-07-30T15:53:47.522Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Changing Lockout Duration for Unsuccessful Login Events
excerpt: This Article Describes Changing Lockout Duration for Unsuccessful Login Events
keywords: Shorten Lockout Times,Reduce Lockouts,Login Failure Policy,Extend Access Delay,Modify Lockout Periods,Adjust Login Cooldown,Change Unsuccessful Logins
thumbnail: https://thmb.techidaily.com/b97d0ebad54511b61b45570cc2aa70ceb4b57e4382ef455cbbee6f6a39f5f377.jpg
---

## Changing Lockout Duration for Unsuccessful Login Events

 Windows has a policy setting that can lock someone out from signing in if they enter the wrong local account password too many times. The user is not allowed to sign in for a set number of minutes after being locked out, but you can change this lockout duration.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change the Duration a User Is Locked Out of Their Account via Local Security Policy

 This method will work as long as the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press **Windows key + R** to open the **Run** dialogue.
2. Type “secpol.msc” into the text field and hit **Enter**.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, click on the **Account Lockout Policy** folder under **Account Policies**.  
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on **Account lockout duration**.  
<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
![Increase or decrease local account lockout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-change-local-account-lockout-duration.jpg)
5. Type in a number between zero and 99,999, and hit **OK**. This will set how long (in minutes) the system will need before it accepts another login attempt.  
<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
![Choose how long a local account is locked out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-set-local-account-lockout-duration.jpg)

## How to Change the Account Lockout Duration in Windows via the Command Prompt

 If the system isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll need to use the command prompt to change how long a user must wait before signing in again after failed login attempts.

1. [Open Command Prompt as Administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/). You can also perform this task with Windows PowerShell if you prefer.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Opening Windows account lockout policies via command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts.jpg)
3. This will pull up information, among other things, about how long this account lockout duration is currently set.
4. To change account lockout duration on Windows 10 and 11, type the following command into the console and hit **Enter.** Replace the number “60” in the command with any other number from zero to 99,999 to set how many minutes a user will have to wait before being allowed to try and log in again.  
`net accounts /lockoutduration:60`  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Use the command prompt to change account lockout duration](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-duration-command-prompt.jpg)

 Setting this value to zero means the locked-out user will not be able to sign in unless an administrator intervenes and unlocks it. Also, the account lock-out duration must be greater than or equal to the time for the system to [automatically reset the number of failed login attempts](https://www.makeuseof.com/reset-account-lockout-counter-windows/).

 If you don’t ever want users to be locked out of their local accounts, you must [change the number of failed login attempts](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) a user is allowed.

## Find the Balance Between Security and Convenience

 Setting account lockout duration too high will cause inconvenience, but if you set it to zero, an administrator will have to be contacted each time a user locks themselves out. Find a balance between security and convenience when it comes to changing how long a user is locked out after a set number of failed login attempts.

 Here’s how to change how long someone using a specific Windows machine is locked out if they enter the wrong login credentials a certain number of times. You must be signed in as an administrator to change this policy.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/024-approved-symphony-of-streams-efficiently-uploading-melodies/"><u>[New] 2024 Approved  Symphony of Streams  Efficiently Uploading Melodies</u></a></li>
<li><a href="https://article-files.techidaily.com/new-merge-skype-and-zoom-easy-techniques-for-effective-communication-for-2024/"><u>[New] Merge Skype and Zoom  Easy Techniques for Effective Communication for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-live-play-and-log-mobile-gaming-with-samsung/"><u>[Updated] 2024 Approved  Live, Play & Log  Mobile Gaming with Samsung</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-dish-on-titles-crafting-captivating-cookery-channel-names-for-2024/"><u>[Updated] Dish on Titles  Crafting Captivating Cookery Channel Names for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-optimizing-story-video-playback-rate-on-instagram-app/"><u>[Updated] In 2024, Optimizing Story Video Playback Rate on Instagram App</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-top-25-instagram-hashtags-to-get-likes-and-followers-for-2024/"><u>[Updated] Top 25 Instagram Hashtags to Get Likes and Followers for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-electorate-enthrallment-best-politic-based-game-reviews/"><u>2024 Approved  Electorate Enthrallment  Best Politic-Based Game Reviews</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-enhancing-your-media-with-professional-voiceovers/"><u>2024 Approved  Enhancing Your Media With Professional Voiceovers</u></a></li>
<li><a href="https://win11.techidaily.com/7-ways-to-fix-a-mouse-wheel-that-keeps-zooming-instead-of-scrolling-on-windows/"><u>7 Ways to Fix a Mouse Wheel That Keeps Zooming Instead of Scrolling on Windows</u></a></li>
<li><a href="https://fox-info.techidaily.com/advanced-techniques-in-aerial-cinematography/"><u>Advanced Techniques in Aerial Cinematography</u></a></li>
<li><a href="https://extra-tips.techidaily.com/boosting-zoom-hd-quality-step-by-step-guide-for-2024/"><u>Boosting Zoom HD Quality  Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-blackout-getting-out-of-dark-mode/"><u>Bypassing The Blackout: Getting Out Of Dark Mode</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/easy-steps-to-capturing-films-on-various-operating-systems/"><u>Easy Steps to Capturing Films on Various Operating Systems</u></a></li>
<li><a href="https://win11.techidaily.com/effortlessly-incorporate-google-maps-into-windows/"><u>Effortlessly Incorporate Google Maps Into Windows</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-the-hurdles-of-error-0x80040610-a-comprehensive-approach/"><u>Eliminating the Hurdles of Error 0X80040610: A Comprehensive Approach</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/evolving-scripts-in-cinema-today-for-2024/"><u>Evolving Scripts in Cinema Today for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/excel-in-windows-top-5-productivity-enhancers-you-cant-miss/"><u>Excel in Windows: Top 5 Productivity Enhancers You Can't Miss</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-handling-winservicesexe-errors/"><u>Expert Tips for Handling Winservices.exe Errors</u></a></li>
<li><a href="https://win11.techidaily.com/from-minuscule-to-monumental-boosting-windows-11-icon-sizes/"><u>From Minuscule to Monumental - Boosting Windows 11 Icon Sizes</u></a></li>
<li><a href="https://win11.techidaily.com/fundamentals-of-windows-executable-files-pe/"><u>Fundamentals of Windows Executable Files (PE)</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-resetting-and-changing-login-credentials-in-win-11/"><u>Guide to Resetting and Changing Login Credentials in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/harnessing-visual-upgrades-with-themes-from-microsoft-store/"><u>Harnessing Visual Upgrades with Themes From Microsoft Store</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-can-we-bypass-lava-yuva-3-pro-frp-by-drfone-android/"><u>How Can We Bypass Lava Yuva 3 Pro FRP?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-icons-bunching-up-on-the-windows-11-taskbar/"><u>How to Fix Icons Bunching Up on the Windows 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-re-establish-bluetooth-linkage-on-windows-1011/"><u>How To Re-Establish Bluetooth Linkage on Windows 10/11</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-successfully-solve-the-iphone-mtp-connection-problem/"><u>How To Successfully Solve The iPhone MTP Connection Problem</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-6s-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone 6s? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/immediate-solution-fixing-windows-auto-detect-proxy-errors/"><u>Immediate Solution: Fixing Windows' Auto Detect Proxy Errors</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-pc-screen-to-motorola-moto-e13-phones-drfone-by-drfone-android/"><u>In 2024, How to Mirror PC Screen to Motorola Moto E13 Phones? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-nokia-150-2023-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Nokia 150 (2023) to iPod | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Samsung Galaxy A05? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-pro-video-zoom-editing-cutting-edge-tools-listed/"><u>In 2024, Pro Video Zoom Editing  Cutting Edge Tools Listed</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-ultimate-compilation-of-best-cams-for-mountain-sports/"><u>In 2024, Ultimate Compilation of Best Cams for Mountain Sports</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-imessage-for-windows-expert-techniques-revealed/"><u>Leveraging iMessage for Windows: Expert Techniques Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/masterclass-on-mending-windows-1011-corrupted-recycle-bin/"><u>Masterclass on Mending Windows 10/11 Corrupted Recycle Bin</u></a></li>
<li><a href="https://win11.techidaily.com/method-to-resolve-audacitys-device-open-error-on-pc/"><u>Method to Resolve Audacity's Device Open Error on PC</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-mastering-adobe-premiere-top-6-tricks-for-professional-video-editing/"><u>New 2024 Approved Mastering Adobe Premiere Top 6 Tricks for Professional Video Editing</u></a></li>
<li><a href="https://win11.techidaily.com/next-steps-for-mobile-connectivity-in-windows-11/"><u>Next Steps for Mobile Connectivity in Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/peerless-bots-crafted-for-chats/"><u>Peerless Bots Crafted for Chats</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-your-pc-saving-spotlight-pictures-as-wallpapers/"><u>Personalizing Your PC: Saving Spotlight Pictures as Wallpapers</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-stuck-on-downloading-of-vivo-t2-5g-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Vivo T2 5G? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/power-buttons-ahead-crafting-shortcuts-on-windows-11/"><u>Power Buttons Ahead: Crafting Shortcuts on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/powertoys-integration-into-win11-systems/"><u>PowerToys Integration Into Win11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-systemsettingsexe-failure-on-windows-11/"><u>Preventing SystemSettings.exe Failure on Windows 11</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/process-of-screen-sharing-google-pixel-8-to-pc-detailed-steps-drfone-by-drfone-android/"><u>Process of Screen Sharing Google Pixel 8 to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/quick-disconnect-solution-non-operative-printer-removal-in-win-1011/"><u>Quick Disconnect Solution: Non-Operative Printer Removal in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-full-enter-key-capabilities-in-win-os/"><u>Regaining Full Enter Key Capabilities in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/reinstate-your-favorite-microsoft-store-for-windows-devices/"><u>Reinstate Your Favorite Microsoft Store for Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-direct-voice-communication-for-xbox-on-windows-11/"><u>Reinstating Direct Voice Communication for Xbox on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-unable-to-open-on-ges-sharing-feature/"><u>Remedy for Unable to Open on GE's Sharing Feature</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-setup-for-icloud-users-with-windows-pcs/"><u>Seamless Setup for iCloud Users with Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-common-vscode-crash-causes-on-winw11/"><u>Sidestep Common VSCode Crash Causes on WinW11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-reactivating-razer-device-detection-by-synapse-software/"><u>Solutions for Reactivating Razer Device Detection by Synapse Software</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-telnet-enablement-in-win11/"><u>Step-by-Step: Telnet Enablement in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-improve-usb-interaction-points/"><u>Steps to Improve USB Interaction Points</u></a></li>
<li><a href="https://win11.techidaily.com/sticky-note-savvy-in-the-world-of-windows-11/"><u>Sticky Note Savvy in the World of Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-disrupted-photo-packaging-in-windows-10-and-11/"><u>Tackling Disrupted Photo Packaging in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-reverse-color-issue-with-windows-marketplace/"><u>Techniques to Reverse Color Issue with Windows Marketplace</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-samsung-galaxy-f04-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Samsung Galaxy F04 Device</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-tale-of-two-platforms-youtube-and-dailymention-for-2024/"><u>The Tale of Two Platforms  YouTube and DailyMention for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-dolby-atmos-integration-in-windows-1011/"><u>The Ultimate Guide to Dolby Atmos Integration in Windows 10/11</u></a></li>
<li><a href="https://facebook.techidaily.com/the-visual-voyage-for-more-engagement-on-social-platforms/"><u>The Visual Voyage for More Engagement on Social Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-secret-of-your-computers-ram-type/"><u>Unlocking the Secret of Your Computer's RAM Type</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-windows-error-0x80300024-problems/"><u>Unraveling Windows' Error 0X80300024 Problems</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-best-songs-logging-top-tools-for-quickly-preserving-your-cherished-tunes-for-2024/"><u>Updated Best Songs Logging Top Tools for Quickly Preserving Your Cherished Tunes for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-honor-100-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Honor 100? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-basics-easy-access-aids-for-novices/"><u>Windows Basics: Easy-Access Aids for Novices</u></a></li>
<li><a href="https://win11.techidaily.com/winning-smoothly-eradicate-lags-from-star-wars-bf2-on-pc/"><u>Winning Smoothly: Eradicate Lags From Star Wars BF2 on PC</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>