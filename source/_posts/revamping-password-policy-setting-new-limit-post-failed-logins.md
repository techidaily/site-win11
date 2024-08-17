---
title: "Revamping Password Policy: Setting New Limit Post Failed Logins"
date: 2024-08-15T23:43:10.296Z
updated: 2024-08-16T23:43:10.296Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Revamping Password Policy: Setting New Limit Post Failed Logins"
excerpt: "This Article Describes Revamping Password Policy: Setting New Limit Post Failed Logins"
keywords: Strong Passwords Now,Updated Login Policies,Safe Access Guidelines,Prevent Unauthorized Entry,Password Expiry Rules,Enhanced Security Measures,Limit Failed Logins Impact
thumbnail: https://thmb.techidaily.com/dadc574a72620fb10d26a05d18b7bc541d4008da38e3f5b8b4a33a2f717ba587.jpg
---

## Revamping Password Policy: Setting New Limit Post Failed Logins

 Enter the wrong local account password too many times and Windows could lock you out. The system also counts how many failed attempts you make when attempting to sign on to the machine.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.

## Reset the Windows Account Lockout Counter in Windows via Local Security Policy

 This method should be your preferred choice if the system is running the Pro, Enterprise, or Education edition of Windows 10 or 11\.

1. Press the Windows key + R to open the **Run** dialogue.
2. In the text field, type “secpol.msc” and hit Enter.  
![Opening security policy via Run option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/01-windows-run-security-policy.jpg)
3. On the left pane, navigate to **Account Lockout Policy** under the **Account Policies** folder.  
![Change Windows account lockout in Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/02-windows-account-policies.jpg)
4. On the right pane, double-click on the **Reset account lockout counter after** option.  
![Windows account logon counter setting](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/03-reset-windows-account-logon-counter.jpg)
5. Choose a number between one and 99,999, and hit **OK** to change how long the system will require to automatically reset any failed logon attempts.  
![Set Windows account logon reset timer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/04-choose-windows-account-logon-reset-timer.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Control How Long Before the Incorrect Logon Counter Is Reset

 With this setting, you control how long before the counter that keeps track of incorrect logon attempts is reset. Use it in conjunction with the lockout duration option account policy to make things more convenient for local users.

 Exceed this threshold and you will need this counter to be reset, which you can do by waiting a set amount of time. Here’s how to change the time you must wait in order for the counter to be automatically reset.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-record-twitch-stream-5-solutions/"><u>[New] 2024 Approved  Record Twitch Stream [5 Solutions]</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-livestreaming-elite-showdown/"><u>[New] LiveStreaming Elite Showdown</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-21-pioneering-metaverse-ventures-for-insightful-discussion/"><u>[Updated] In 2024, 21 Pioneering Metaverse Ventures for Insightful Discussion</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-the-best-oculus-rift-video-players-review/"><u>[Updated] The Best Oculus Rift Video Players Review</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-conquering-the-complexities-of-360-video-post-production-in-premiere/"><u>2024 Approved  Conquering the Complexities of 360° Video Post-Production in Premiere</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-djis-minis-and-air-2-free-fun-luts-for-ultimate-mixes/"><u>2024 Approved  DJI's Minis & Air 2  Free, Fun LUTS for Ultimate Mixes</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-investing-successfully-with-a-makeup-channel/"><u>2024 Approved  Investing Successfully with a Makeup Channel</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-the-complete-guide-to-saving-live-periscope-broadcasts/"><u>2024 Approved  The Complete Guide to Saving Live Periscope Broadcasts</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-transforming-gifs-to-stickers-comprehensive-instruction-for-messaging-apps/"><u>2024 Approved  Transforming GIFs to Stickers  Comprehensive Instruction for Messaging Apps</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-vivo-y28-5g-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Vivo Y28 5G to Roku | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-deep-dive-into-metaverse-gear-top-8-recommendations/"><u>A Deep Dive Into Metaverse Gear  Top 8 Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/actions-to-take-against-lunar-client-start-up-failure-notice/"><u>Actions to Take Against Lunar Client Start-Up Failure Notice</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/affordable-apeman-c450-comprehensive-budget-dashcam-evaluation/"><u>Affordable Apeman C450: Comprehensive Budget Dashcam Evaluation</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-slow-icon-loading-with-cache-refresh/"><u>Avoiding Slow Icon Loading with Cache Refresh</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-dxgi-error-by-reattaching-devices-in-windows/"><u>Bypassing DXGI ERROR by Reattaching Devices in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-glitch-0x80072746-a-fix-guide-for-windows-mail/"><u>Bypassing Glitch 0X80072746: A Fix Guide for Windows Mail</u></a></li>
<li><a href="https://win11.techidaily.com/epic-sign-in-solutions-for-non-responsive-launcher/"><u>Epic Sign-In Solutions for Non-Responsive Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/essential-role-of-windows-batch-files-in-os-functioning/"><u>Essential Role of Windows Batch Files in OS Functioning</u></a></li>
<li><a href="https://extra-hints.techidaily.com/fitness-frontiers-unveiling-premier-virtual-reality-walkers/"><u>Fitness Frontiers  Unveiling Premier Virtual Reality Walkers</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-video-buffer-issues-streamlined-vlc-on-pc/"><u>Fixing Video Buffer Issues: Streamlined VLC on PC</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-this-computer-doesnt-meet-minimum-requirements-intel-hd-graphics-error/"><u>How to Fix the This Computer Doesn’t Meet Minimum Requirements Intel HD Graphics Error</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reestablish-network-connection-after-failure-in-windows-11/"><u>How to Reestablish Network Connection After Failure in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-realme-12-5g-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Realme 12 5G to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-chuckles-and-challenges-best-fun-for-young-minds/"><u>In 2024, Chuckles & Challenges - Best Fun for Young Minds</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-12-pro-max-to-mac-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone 12 Pro Max to Mac? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-maneuvers-for-concealing-windows-11s-control-icon/"><u>Masterful Maneuvers for Concealing Windows 11'S Control Icon</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-directdraw-fixes-in-windows-10-and-11/"><u>Mastering DirectDraw Fixes in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-customization-for-a-macos-feel-in-windows/"><u>Mastering Window Customization for a macOS Feel in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-customization-adding-contextual-options-in-win-11/"><u>Mastering Window Customization: Adding Contextual Options in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-administrator-settings-in-windows-security/"><u>Navigating Administrator Settings in Windows Security</u></a></li>
<li><a href="https://win11.techidaily.com/prime-windows-experience-select-top-optimizers-ranked/"><u>Prime Windows Experience: Select Top Optimizers Ranked</u></a></li>
<li><a href="https://win11.techidaily.com/prioritizing-improvement-in-windows-11/"><u>Prioritizing Improvement in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/pushing-boundaries-exploring-win-and-ps1-synergy-via-duckstation/"><u>Pushing Boundaries: Exploring WIN and PS1 Synergy via Duckstation</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-restoring-previous-windows-configurations/"><u>Quick Guide to Restoring Previous Windows Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/regain-control-over-silent-slack-alerts-in-win-11/"><u>Regain Control Over Silent Slack Alerts in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-browsing-copy-pasting-shortfalls-across-oses/"><u>Remedying Browsing Copy-Pasting Shortfalls Across OSes</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-no-connection-found-on-win-810/"><u>Remedying No Connection Found on Win 8/10</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-microsofts-speech-recognition-in-windows-11/"><u>Restoring Microsoft's Speech Recognition in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-snaps-windows-strategies-for-sticky-notes/"><u>Secure Your Snaps: Windows Strategies for Sticky Notes</u></a></li>
<li><a href="https://win11.techidaily.com/setting-alternative-pdf-printer-in-windows/"><u>Setting Alternative PDF Printer in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-restore-functionality-of-missing-steamuidll/"><u>Steps to Restore Functionality of Missing Steamui.dll</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/streamlining-your-youtube-editing-with-imovie-tools/"><u>Streamlining Your YouTube Editing with iMovie Tools</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-faulty-microsoft-store-eradicate-0x80072efd/"><u>Tackling Faulty Microsoft Store: Eradicate 0X80072EFD</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-androidpc-junctioning/"><u>The Ultimate Guide to Android/PC Junctioning</u></a></li>
<li><a href="https://win11.techidaily.com/why-you-shouldnt-use-ai-chatbots-to-generate-windows-11-keys/"><u>Why You Shouldn’t Use AI Chatbots to Generate Windows 11 Keys</u></a></li>
</ul></div>
