---
title: Renewing Lockout Count Post-Failed Sign-Ins in W10/W11
date: 2024-07-13T10:26:05.585Z
updated: 2024-07-14T10:26:05.585Z
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

## How to Change Account Lockout Counter Reset Time via Command Prompt

 If the system you’re working with isn’t running the Pro, Enterprise, or Education edition of Windows 10 or 11, you’ll have to change how long before the account lockout counter is reset via the command prompt.

1. Open command prompt as administrator, also called the [elevated command prompt](https://www.makeuseof.com/windows-run-command-prompt-admin/), or Windows PowerShell.
2. Type the following command into the console and hit **Enter**:  
`net accounts`  
![Using the command prompt to list Windows account policies](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/05-command-prompt-net-accounts-02.jpg)
3. This will pull up information on how long a user has to wait before their account lockout counter is reset. It will be under the heading **Lockout observation window**.
4. To change the account lockout counter reset duration on Windows 10 and 11, type the following command into the console and hit **Enter**:  
`net accounts /lockoutwindow:60`  
![Use the command prompt to change account lockout counter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/06-change-account-lockout-counter-command-prompt.jpg)
5. Replace the number “60” in the command with any other number from one to 99,999 to set how many minutes a user will have to wait before their failed logon attempts are reset.

 A related setting, the [account lock-out duration](https://www.makeuseof.com/change-lockout-duration-windows/), must equal or exceed the time for the system to automatically reset the number of failed login attempts. If you want, you can [change the account lock-out duration on Windows](http://www.makeuseof.com/change-lockout-duration-windows/) to something that suits you best.

 You can also [limit the number of failed logon attempts on Windows](https://www.makeuseof.com/how-limit-number-failed-login-attempts-windows-10/) with a similar setting change.

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
<li><a href="https://win11.techidaily.com/ace-at-tech-how-to-revitalize-your-pcs-apps/"><u>Ace at Tech: How to Revitalize Your PC's Apps</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-poco-c55-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Poco C55 Device</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-rdc-launches-windows-11-guide/"><u>Effortless RDC Launches - Windows 11 Guide</u></a></li>
<li><a href="https://article-helps.techidaily.com/swift-techniques-for-shifting-iphone-media-to-pc/"><u>Swift Techniques for Shifting iPhone Media to PC</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-resolve-windows-high-dpi-screen-scaling/"><u>Strategies to Resolve Windows High DPI Screen Scaling</u></a></li>
<li><a href="https://win11.techidaily.com/the-compreenas-guide-track-down-your-windows-serial-number/"><u>The Compreenas Guide: Track Down Your Windows Serial Number</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-check-your-public-ip-address-using-command-prompt-in-windows-1110/"><u>How to Check Your Public IP Address Using Command Prompt in Windows 11/10</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-on-photo-corrections-stripping-backdrops/"><u>Expert Advice on Photo Corrections: Stripping Backdrops</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-expert-insights-selecting-superior-4k-camera-stands/"><u>[New] Expert Insights  Selecting Superior 4K Camera Stands</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-free-video-trimming-made-easy-no-watermarks-no-hassle/"><u>Updated In 2024, Free Video Trimming Made Easy No Watermarks, No Hassle</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-spotlight-on-todays-viral-tiktok-experiments/"><u>[Updated] In 2024, Spotlight on Today’s Viral TikTok Experiments</u></a></li>
<li><a href="https://win11.techidaily.com/charting-a-course-for-change-windows-11-explore-evolution/"><u>Charting a Course for Change: Windows 11 Explore Evolution</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-how-to-reestablish-disconnected-copilot/"><u>Windows 11: How To Reestablish Disconnected Copilot</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-thoughts-on-youtubing-best-makers-tips-and-templates/"><u>Final Thoughts on YouTubing - Best Makers, Tips, and Templates</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-tecno-pova-6-pro-5gfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Tecno Pova 6 Pro 5GFRP Lock</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-closed-captions-a-windows-10-experts-method/"><u>Troubleshoot Closed Captions: A Windows 10 Expert's Method</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-breakdown-of-triggering-system-restore-in-windows-11/"><u>The Complete Breakdown of Triggering System Restore in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-resolving-installation-hurdles-in-windows-1011/"><u>Understanding & Resolving Installation Hurdles in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-finding-fixes-for-systemsettingsexe-in-win11/"><u>Tips for Finding Fixes for SystemSettings.exe in Win11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-unlimited-access-90-day-free-trial-of-final-cut-pro-inside/"><u>Updated Unlimited Access 90-Day Free Trial of Final Cut Pro Inside</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-1011-installer-errors/"><u>Navigating Through Windows 10/11 Installer Errors</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-correcting-missed-audio-segments-in-obs-recordings/"><u>2024 Approved  Correcting Missed Audio Segments in OBS Recordings</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-search-tracing-programs-settlement-in-windows/"><u>Streamlining Your Search: Tracing Programs' Settlement in Windows</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/tiktok-shadowban-how-to-get-unshadowbanned-on-tiktok2-for-2024/"><u>TikTok Shadowban  How to Get Unshadowbanned on Tiktok2 for 2024</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-best-of-the-best-10-webcam-recording-programs-for-windows-10/"><u>New In 2024, Best of the Best 10 Webcam Recording Programs for Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/7-affordable-solutions-to-skyrocket-your-pcs-hard-drive-size/"><u>7 Affordable Solutions to Skyrocket Your PC's Hard Drive Size</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-how-to-create-captions-in-final-cut-pro-x-a-comprehensive-guide/"><u>Updated How to Create Captions in Final Cut Pro X A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-chrome-download-errors-on-windows-systems/"><u>Fixing Chrome Download Errors on Windows Systems</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-complete-playbook-to-conquer-spotify-advertising-for-2024/"><u>The Complete Playbook to Conquer Spotify Advertising for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/what-makes-a-good-video-coder-for-use-on-windows-systems/"><u>What Makes A Good Video Coder for Use on Windows Systems?</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-error-code-0x80246007-from-windows-update-on-w10w11/"><u>Eliminating Error Code 0X80246007 From Windows Update on W10/W11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-avoid-oversaturated-greenscreen-effective-strategies-for-mac-editors/"><u>In 2024, Avoid Oversaturated Greenscreen  Effective Strategies for Mac Editors</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-resolving-obs-fullscreen-not-functional/"><u>[Updated] 2024 Approved  Resolving OBS Fullscreen Not Functional</u></a></li>
<li><a href="https://extra-skills.techidaily.com/pro-level-strategies-for-mass-downloading-tiktok-content-for-2024/"><u>Pro-Level Strategies for Mass Downloading TikTok Content for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-resolving-operational-breakdowns-of-your-windows-stylus/"><u>Understanding and Resolving Operational Breakdowns of Your Windows Stylus</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-try-connecting-error-on-windows-11-devices/"><u>Conquering Try Connecting Error on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-microsofts-zero-error-in-windows-11-shop/"><u>Rectifying Microsoft's Zero-Error in Windows 11 Shop</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/is-avs-video-editor-worth-it-a-detailed-review-for-2024/"><u>Is AVS Video Editor Worth It? A Detailed Review for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-samsung-galaxy-a34-5g-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Samsung Galaxy A34 5G Phone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/things-you-should-know-when-unlocking-total-wireless-of-apple-iphone-13-pro-by-drfone-ios/"><u>Things You Should Know When Unlocking Total Wireless Of Apple iPhone 13 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reactivate-deactivated-menu-items-on-windows/"><u>Steps to Reactivate Deactivated Menu Items on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/familiarize-yourself-with-microsoft-family-safety/"><u>Familiarize Yourself With Microsoft Family Safety</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-learning-visuals-in-win-11/"><u>Setting Up Learning Visuals in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-pairings-winning-webp-viewers-and-windows-devices/"><u>Top 4 Pairings: Winning WebP Viewers & Windows Devices</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-vivo-s17-pro-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Vivo S17 Pro Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/proven-strategy-batch-convert-heic-to-jpeg-in-windows-11/"><u>Proven Strategy: Batch Convert HEIC to JPEG in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-poco-x6-pro-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Poco X6 Pro to iPhone | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-win1110-guide-altering-nat-type-correctly/"><u>The Ultimate Win11/10 Guide: Altering NAT Type Correctly</u></a></li>
</ul></div>
