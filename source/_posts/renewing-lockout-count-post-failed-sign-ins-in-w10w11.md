---
title: Renewing Lockout Count Post-Failed Sign-Ins in W10/W11
date: 2024-08-16T00:09:12.220Z
updated: 2024-08-17T00:09:12.220Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Renewing Lockout Count Post-Failed Sign-Ins in W10/W11
excerpt: This Article Describes Renewing Lockout Count Post-Failed Sign-Ins in W10/W11
keywords: Failed Login Recovery,Password Reset Process,Lockout Event Management,W10/W11 Access Troubleshooting,Sign-In Failure Resolution,Post-Login Lockout Strategy,Windows 10/11 Security Keying
thumbnail: https://thmb.techidaily.com/5ba7b3f6e60e87bd15e4d0d59cd473305f169947afe8b79e803b03fc556698ce.jpg
---

## Renewing Lockout Count Post-Failed Sign-Ins in W10/W11

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
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
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
<li><a href="https://discord-videos.techidaily.com/new-disconnect-and-delete-discord-accounts-devices/"><u>[New] Disconnect and Delete Discord Accounts (Devices)</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-fresh-talent-8-rapidly-rising-online-stars-for-2024/"><u>[New] Fresh Talent 8  Rapidly Rising Online Stars for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-inside-the-tech-evaluating-webcam-videotaping-devices/"><u>[New] In 2024, Inside the Tech  Evaluating WebCam Videotaping Devices</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-entryway-investments-cost-effective-channels-for-newbies/"><u>[Updated] 2024 Approved  Entryway Investments  Cost-Effective Channels for Newbies</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-becoming-a-bull-or-bear-best-stock-vids-on-youtube/"><u>[Updated] In 2024, Becoming a Bull or Bear  Best Stock Vids on YouTube</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-core-elements-in-virtual-narrative-design/"><u>2024 Approved  Core Elements in Virtual Narrative Design</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-navigating-youtube-video-production-tools/"><u>2024 Approved  Navigating YouTube Video Production Tools</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-effective-power-indicators-in-windows/"><u>Crafting Effective Power Indicators in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-correcting-error-0x80004004-on-defender/"><u>Deciphering and Correcting Error 0X80004004 on Defender</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-windows-11s-spotify-connectivity-fails/"><u>Eliminating Windows 11'S Spotify Connectivity Fails</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-vivo-t2-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-realme-c51-frp-by-drfone-android/"><u>Full Guide to Bypass Realme C51 FRP</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-skirt-sie-and-load-unsigned-drivers-in-windows-oses/"><u>How to Skirt SIE & Load Unsigned Drivers in Windows OSes</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-fbx-the-ultimate-gaming-video-guide/"><u>In 2024, FBX  The Ultimate Gaming Video Guide</u></a></li>
<li><a href="https://win11.techidaily.com/initiating-playback-how-to-start-windows-media-player/"><u>Initiating Playback - How to Start Windows Media Player</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ipados-paint-the-creme-de-la-creation-apps/"><u>IPadOS Paint  The Crème De La Création Apps</u></a></li>
<li><a href="https://win11.techidaily.com/keeping-tabs-on-pc-login-separating-goals-from-errors/"><u>Keeping Tabs on PC Login: Separating Goals From Errors</u></a></li>
<li><a href="https://win11.techidaily.com/keyboardmouse-wake-issues-fix-for-win11-users/"><u>Keyboard/Mouse Wake Issues: Fix for Win11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-activation-failures-in-office-suite/"><u>Navigating Activation Failures in Office Suite</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/order-of-excellence-the-definitive-watchlist-for-the-james-bond-series/"><u>Order of Excellence: The Definitive Watchlist for the James Bond Series</u></a></li>
<li><a href="https://win11.techidaily.com/personalizing-windows-inactive-session-limit/"><u>Personalizing Windows Inactive Session Limit</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-original-look-for-discoloured-extend-volume/"><u>Reclaim Original Look for Discoloured Extend Volume</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-cannot-preview-error-with-microsoft-office-outlook/"><u>Resolving 'Cannot Preview' Error with Microsoft Office Outlook</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-ui-proposing-innovations-in-windows-11-widget-design/"><u>Revolutionizing UI: Proposing Innovations in Windows 11 Widget Design</u></a></li>
<li><a href="https://win11.techidaily.com/squashing-faulty-empty-directory-alert-with-0x80070091-on-windows-11/"><u>Squashing Faulty Empty Directory Alert with #0X80070091 on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/swift-systems-top-strategies-for-fixed-windows-11-wwe-games/"><u>Swift Systems: Top Strategies for Fixed Windows 11 WWE Games</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-11-no-response-to-click-events/"><u>Tackling Windows 11: No Response to Click Events</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-guide-to-integrating-chatgpt-with-whatsapp-transforming-your-customer-service-experience/"><u>The Ultimate Guide to Integrating ChatGPT with WhatsApp – Transforming Your Customer Service Experience</u></a></li>
<li><a href="https://win11.techidaily.com/tips-to-retrieve-faded-bios-messages/"><u>Tips to Retrieve Faded BIOS Messages</u></a></li>
<li><a href="https://win11.techidaily.com/top-windows-fixes-to-unblock-firefox-page-load-blockage/"><u>Top Windows Fixes to Unblock Firefox Page Load Blockage</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-purpose-of-pagefilesys-and-should-it-be-deleted/"><u>What Is the Purpose of Pagefile.sys and Should It Be Deleted?</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-vivo-y100-5g-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Vivo Y100 5G Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/winning-back-access-to-steam-remote-play/"><u>Winning Back Access to Steam Remote Play</u></a></li>
</ul></div>
